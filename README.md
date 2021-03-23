# Teritorio Bicycle Style

Derived from [OSM Bright](https://github.com/openmaptiles/osm-bright-gl-style)

A GL JS basemap style showcasing Bicycle features from OpenStreetMap. It is using the vector tile schema of [OpenMapTiles](https://github.com/openmaptiles/openmaptiles).

## Teritorio Styles Family

- [OSM Bright](https://github.com/openmaptiles/osm-bright-gl-style)
    - [Teritorio Basic](https://github.com/teritorio/teritorio-basic-gl-style)
        - [Teritorio Tourism](https://github.com/teritorio/teritorio-tourism-gl-style) (Tourism thematic POIs, large icon)
            - [Teritorio Tourism Basic](https://github.com/teritorio/teritorio-tourism-basic-gl-style) (small icon)
        - [Teritorio City](https://github.com/teritorio/teritorio-city-gl-style) (City thematic POIs, large icon)
            - [Teritorio City Basic](https://github.com/teritorio/teritorio-tourism-basic-gl-style) (small icon)
        - [Teritorio Bicycle](https://github.com/teritorio/teritorio-bicycle-gl-style) (Network and Facilities)

## Preview

![](networks.png)

![](facilities.png)

## OpenMapTiles Data Layer

This style require the extra layers from [openmaptiles-contrib-bicycle_hiking_route](https://github.com/makina-maps/openmaptiles-contrib-bicycle_hiking_route).

## Edit the Style

Use the map editor in MapTiler Cloud to view and adjust this map. Open the editor and upload style from this repository or host from various styles available on the platform.

[Try style editor](https://cloud.maptiler.com/maps/editor)


Or use the [Maputnik CLI](http://openmaptiles.org/docs/style/maputnik/) to edit and develop the style.
After you've started Maputnik open the editor on `localhost:8000`.

```
maputnik --watch --file style.json
```

## Depencency

This style require at least the Mapbox GL JS version 1.10.1.
