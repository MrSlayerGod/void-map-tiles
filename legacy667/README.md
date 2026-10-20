# LegacyScape 667 cache export

Source: owner-provided D:/void-634/images/final-667 export, confirmed generated
from the owner's RSPS 667 desktop cache. Imported 20 October 2026.

Layout: {plane}/{zoom}/{x}/{y}.png, 256x256 PNGs, planes 0-3,
native zoom levels 4-8. Leaflet consumers must set maxNativeZoom: 8
and may allow display zooms through 11 using nearest-neighbour enlargement.
The existing Void map CRS and Y convention are retained.

locations.json contains labels from the same export. Missing tiles represent
unexported map areas; do not silently substitute a different cache dataset.
The cache binaries and keys are not included.