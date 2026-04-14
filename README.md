# GeoMapEditor – Polygon Drawing & GeoJSON Tool

A web-based interactive map tool built with Leaflet and Turf.js that allows users to draw, edit, analyze, and export geographic polygons.

---
## Features

###  Drawing & Editing
- Draw polygons directly on the map
- Edit and delete shapes using built-in tools
- Supports multiple shapes at once

### Selection System
- Click polygons to select them
- Selected polygons turn **red**
- Supports multi-selection

### Color Management
- Change polygon color using dropdown
- Colors persist after selection
- Each polygon remembers its own color

### GeoJSON Support
- Import GeoJSON from:
    - Text input
    - File upload (`.geojson`, `.json`)
- Export selected polygons as GeoJSON

### Spatial Operations (Turf.js)
- ➕ Union (merge polygons)
-  Intersection (common area)
- ➖ Subtraction (difference)

### Advanced Handling
- Supports **MultiPolygon**
- Converts circles → polygons for analysis
- Maintains layer state and IDs

---

## Technologies Used

- **Leaflet.js** → Interactive maps
- **Leaflet Draw** → Drawing tools
- **Turf.js** → Spatial analysis (GIS operations)
- **Vanilla JavaScript** → Logic and interactions
- **HTML / CSS** → UI


