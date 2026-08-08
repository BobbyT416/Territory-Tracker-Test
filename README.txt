Version 8 — editor visibility and Follow Road fix.

Fixes:
- Editor panel is above Leaflet map panes so Freehand / Follow Road and other controls remain clickable.
- Follow Road now previews a segment and refuses obviously excessive routes.
- Follow Road only accepts endpoints near the existing boundary.
- A road segment replaces a short section of the existing boundary instead of being appended to the polygon, preventing runaway/infinite-looking boundaries.
- Freehand/Add Point behavior remains available.
