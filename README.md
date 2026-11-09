# Sunlight Planner

Draw a building and its neighbors, pick a location and date, and scrub through the day to see where sunlight falls — on the site, on each face of your building, and inside your apartment (sun patches through the windows, minutes of direct sun on each piece of furniture and the balcony).

**Live:** https://speedofsound98.github.io/sunlight-planner/

Everything runs in the browser from a single `index.html` (Three.js r128 from cdnjs is the only dependency). No server, no build step — you can also just download `index.html` and double-click it.

## Features
- Plan view + 3D view with real-time shadows, solar position (NOAA/Spencer), date/time sliders, Play.
- Draw buildings on a 0.5 m grid, set heights, mark "my" building; per-wall direct-sun hours with neighbor occlusion.
- North angle / compass, map-image underlay with two-point scale calibration.
- Apartment view: floor selector, generator (m², rooms, baths, balcony, window directions), walls, windows, furniture catalog, sun patches, furniture & balcony sun report.
- Walk-through mode (WASD), best-orientation search, PNG export, JSON save/load.

The time slider is local solar time (no time zones or DST).
