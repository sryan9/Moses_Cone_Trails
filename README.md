# Moses_Cone_Trails
Map of three trails originating at Bass Lake in Blowing Rock, North Carolina

### Moses Cone Manor Trails, Bass Lake


#### This map indicates three trails beginning at the Bass Lake Trail Trailhead on Moses Cone Manor in Blowing Rock, North Carolina. The trails range in length from 4-8 miles roundtrip.

#### I created this map in HTML, JavaScript and CSS, utilizing Leaflet and JQuery libraries in Atom. To create the map, leaflet functions were very helpful, including L.map to create my map, L.tileLayer to add my basemap and L.geoJSON to retrieve my geoJSON files. To indicate landmarks I used the bindTooltip function. If statements were used to indicate that point feature correspond to bindTooltip pop-ups, and to style line features.

#### I downloaded my basemap tile from [Leaflet Providers](https://leaflet-extras.github.io/leaflet-providers/preview/). The trail loops were determined using Google Maps. The cordinates of the markers from google maps were converted to GPX using a [GPX converter](https://mapstogpx.com/). This GPX file was then converted to a GeoJSON file using [geojson.io](https://geojson.io/#map=2/20.0/0.0). Text color in the description box was styled using css in the main.css file. All other styling was coded in the index.html file.

