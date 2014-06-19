Outine
=====================

1. OpenStreetMap - data beyond good looking maps. - 10 mins.
2. Data - modelling your data the OSM way and why - 20 mins.
    1. Elements or Data Primitives
        * Nodes - points in space.
        * Ways - lines or area
        * Relations - how objects in space interact to each other.
    2. Breaking geographic data into Points, Lines and Polygons.
    3. Metadata taxonomy -
        * Map features - modeling and categorizing realworld objects. 
        * Tags - Keys and Values.
        * Presets - canned reusable features.
        * HSTORE FTW!
    4. The XML Data Format. - 10 mins.
        1. Structure.
        2. Parsers.
        3. More formats
            * PBF - compressed, optimised binary.
            * OSM JSON
    5. Changesets.
        1. Full history.
        2. Watch List.
3. Infrastructure - setting up everything to work together - 20 mins.
    1. Backend.
        1. PostgreSQL. Tuned. +PostGIS.
        2. Osmosis.
        3. Planet Dump.
        4. Overpass/API.
    2. Editing.
        1. iD.
        2. JOSM.
    3. Replication.
        1. Update other databases with changes from master OpenStreetMap database.
    4. Rendering.
        1. osm2pgsql
        2. Mapnik + Stylesheets
        3. Apache + mod_tile
        4. Map Tiles.
    5. Visualisation.
        1. Leaflet
        2. OpenLayers
