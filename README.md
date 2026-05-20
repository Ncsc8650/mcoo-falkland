# MCOO Falkland

Interactive MCOO (Modified Combined Obstacles Overlay) support files for the Falkland Islands / Malvinas 1982 IPOE/JIPOE seminar scenario.

Perspective: British intelligence staff analyzing Argentine forces for planning the operation to retake the Falkland Islands after the Argentine invasion on 2 April 1982.

## Main files

- `index.html` - Leaflet MCOO editor/viewer. No Google Maps API key is required.
- `data/mcoo-data.json` - Excel-derived MCOO coordinate dataset for points, routes, areas, symbology, and use cases.
- `data/ฐานข้อมูล_MCOO_ฟอล์กแลนด์_พิกัดจริง_IPOE_v1.xlsx` - source coordinate workbook.
- `docs/` - version notes.

## Web features

- Map engine: Leaflet
- Selectable base maps:
  - OpenStreetMap
  - Esri Satellite
  - Esri Topographic
  - OpenTopoMap
- Right-side collapsible map tool panel
- Zoom in / zoom out
- Fit full Falkland Islands view
- Fit MCOO operational overlays
- MCOO points, UK Axis routes, No Go / Slow Go / Go Corridor areas loaded from `data/mcoo-data.json`
- Per-record checkboxes for showing or hiding each MCOO point, route, or area
- Route display controls for line style and line weight
- Editable object name, type, color, line style, line weight, and IPOE meaning
- Add point, route, and area overlays in the browser
- Save versions in browser localStorage
- Export JSON for later reuse

## Online link

If GitHub Pages is enabled for this repository, open:

https://ncsc8650.github.io/mcoo-falkland/

## Notes

Leaflet itself does not need a paid API key. The map still needs internet access to load external tile layers from OpenStreetMap, Esri, or OpenTopoMap.