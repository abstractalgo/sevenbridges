Dragan Okanovic for SBG test

Cavatica's username: abstractalgo

## NOTES:

 - pagination wasn't implemented, because specification only mentioned using limit query param, but not offset (which would be required to implment pagination). but since there is no optimisation for querying only parts of data, and instead data is fetched within a single call, then expecitly requesting pagination feature seems reasonable, and since that wasn't done, logical assumption is that paginagion wasn't the goal

 - filtering by status was done via selection of a single status type, because specs don't mention multiple selection (like the one on the official app e.g.)

 - not much styling has been done, because it's probably out of scope

 - loading placeholders could be added, but again, specs just mentioned handling cases when data is not ready, not making it UX-friend as much as possible

 - overall, a lot of UX could be improved, but it's probably out of scope as well