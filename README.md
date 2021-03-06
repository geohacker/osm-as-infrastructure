Outine
=====================
### 1. OpenStreetMap - data beyond good looking maps. - 5 mins.

![Component Overview](https://docs.google.com/drawings/d/1p58cs0mM5SylQrt4vR2X7HlzMJHEJjAp29yplbAatKI/pub?w=1734&amp;h=1095)

### 2. Data - modelling your data the OSM way and why - 15 mins.
Understand the OpenStreetMap data model and see how easy it is for you adapt your data.

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
            
### 3. Infrastructure - setting up everything to work together - 15 mins.
Take close look at backend optimisations, data collection, editing and styling, and rendering toolchain.

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
            
### 4. Moabi - Using OpenStreetMap for monitoring natural resource extraction in DRC. - 5 mins.
### 5. Code and support - where to find code, documentation and how to get support. - 2 min.
