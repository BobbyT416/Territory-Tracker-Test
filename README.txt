Territory Tracker Version 4 test build

New in v4:
- Follow Road mode.
- Tap a starting road and an ending/intersection point.
- Points are snapped to the OpenStreetMap street network.
- A routed road segment is previewed before adding it to the boundary.
- Existing freehand editing remains available for fine adjustment.
- Houses ON/OFF and building status shading remain.

Important:
The public OSRM routing service is used for this prototype. Routing between two points follows the road network, but it is not yet a true named-road selector. For the production version, the road-selection tool should use road vector data so the user can explicitly choose "Stone Church Rd", "Bunker Hill Rd", etc. and then terminate at an intersection.
