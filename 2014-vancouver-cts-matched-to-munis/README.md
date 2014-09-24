vancouver-cts-matched-to-munis
====

Table matching Vancouver Census Tracts (CTUIDs) to Metro Vancouver municipalities (Census Subdivisions). CTUIDText is the CT ID number but with decimal places (Even if .00) to ensure proper matching with StatsCan SHP files.

Helpful for interactive maps because you can put the city that a CT is part of in a tooltip or pop-up window.

Created in QGIS using a spatial join after turning the CT polygons into centroids first (got weird results when tried to join polygon to polygon).