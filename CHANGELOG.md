# 1.1.0
* expose `isPointOnSegment` function
* use `point-to-segment-2d` module
* remove stale warning about node `< 12.x` which has been unsupported for a while now


# 1.0.0
* accidentally changed default behavior to allow segments <= 1 distance to be considered intersecting
* refactor the API to provide a garbage collector friendly invocation and better performance (#2)
* switch to pure es module (#3)
* bump node dependency to v12+
* handle some additional failing intersection tests for colinear cases
* handle some an additional failing intersection test when a segment has one point on another segment (#1)
* add travis build badge
* simplify usage instructions in readme
* switch to es6 (use `let` and `const` everywhere)
* update URL in credits


# 0.2.2
* update URL in credits


# 0.2.1
* export to window object


# 0.2.0
* support multiple point input formats


# 0.1.1
* fix some collision bugs
* update readme


# 0.1.0
* initial implementation
