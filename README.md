# leaflet-topojson

Portions of https://github.com/mbostock/topojson required to convert TopoJSON to GeoJSON

## Usage

```javascript
var data     = {},  // via $.getJSON(), etc.
    geojson  = topojson.feature(data, data.objects.field),
    layer    = L.geoJson(geojson);
```
