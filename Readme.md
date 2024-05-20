Zoom levels
tippecanoe -o geography_regions.mbtiles -Z 2 -z 7 Documents/geography_regions.geojson

Continuous polygon features (states and provinces), visible at all zoom levels

tippecanoe -zg -o ne_10m_admin_1_states_provinces.mbtiles --coalesce-densest-as-needed --extend-zooms-if-still-dropping ne_10m_admin_1_states_provinces.geojson
