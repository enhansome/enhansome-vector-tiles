# awesome-vector-tiles with stars

The [Mapbox Vector Tile spec](https://github.com/mapbox/vector-tile-spec) ⭐ 1,004 | 🐛 46 | 📅 2026-06-29 is an efficient encoding for map
data into vector tiles that can be rendered dynamically.

## Parsers & Generators

* [geojson-vt](https://github.com/mapbox/geojson-vt) ⭐ 2,041 | 🐛 15 | 🌐 JavaScript | 📅 2026-07-02 - Slice GeoJSON into vector tiles on the fly in the browser.
* [orb](https://github.com/paulmach/orb) ⭐ 1,126 | 🐛 19 | 🌐 Go | 📅 2026-03-30 - A Go geometry library with mvt <-> geojson support.
* [mapnik-vector-tile](https://github.com/mapbox/mapnik-vector-tile) ⚠️ Archived - C++ vector tile read/write implementation on top of Mapnik.
* [node-mapnik](https://github.com/mapnik/node-mapnik) ⭐ 545 | 🐛 104 | 🌐 C++ | 📅 2026-07-27 - Node.js API for vector tiles which depends on `mapnik-vector-tile`
* [vector-tile-js](https://github.com/mapbox/vector-tile-js) ⭐ 402 | 🐛 8 | 🌐 JavaScript | 📅 2026-06-24 - Parses vector tiles with JavaScript.
* [mapbox-vector-tile](https://github.com/mapzen/mapbox-vector-tile) ⭐ 274 | 🐛 18 | 🌐 Python | 📅 2025-07-08 is a Python package for vector tile encoding. Used in Mapzen's vector tile service [tileserver](https://github.com/tilezen/tileserver) ⭐ 80 | 🐛 6 | 🌐 Python | 📅 2024-05-30 and TileStache. [:warning:](https://github.com/tilezen/mapbox-vector-tile/issues/42) ⭐ 274 | 🐛 18 | 🌐 Python | 📅 2025-07-08 Only support V1 Tile spec and not V2, no longer maintained
* [java-vector-tile](https://github.com/ElectronicChartCentre/java-vector-tile) ⭐ 209 | 🐛 0 | 🌐 Java | 📅 2025-01-15 - A java encoder and decoder for vector tiles.
* [mapbox-vector-tile-java](https://github.com/wdtinc/mapbox-vector-tile-java) ⭐ 164 | 🐛 16 | 🌐 Java | 📅 2022-10-04 - Encode and decode v2.1 Mapbox Vector Tiles. Convert JTS Geometry to and from MVT features, including simple user data support. Utility functions for converting world coordinates to MVT coordinates and clipping to a tile envelope.
* [mapbox-vector-tile-cs](https://github.com/bertt/mapbox-vector-tile-cs) ⭐ 79 | 🐛 0 | 🌐 C# | 📅 2026-04-24 - Parses vector tiles with C# (uses protobuf-net).
* [tilelive-vector](https://github.com/mapbox/tilelive-vector) ⭐ 72 | 🐛 24 | 🌐 JavaScript | 📅 2026-06-29 - Implements [Tilelive API](https://github.com/mapbox/tilelive.js/blob/master/API.md) ⭐ 540 | 🐛 32 | 🌐 JavaScript | 📅 2026-06-29 for reading vector tiles and rendering to image tiles in Node.js.
* [tilegrinder](https://github.com/rastapasta/tilegrinder) ⭐ 67 | 🐛 3 | 🌐 CoffeeScript | 📅 2019-11-06 - A helper library for applying a data altering function on each vector tile in an MBTiles, using the native protobuf wrapper for de- and encoding, recompressing the results and storing them either in an MBTiles or as single files.
* [vector-tile-cs](https://github.com/mapbox/vector-tile-cs) ⭐ 65 | 🐛 15 | 🌐 C# | 📅 2026-06-29 - Parses vector tiles with C# (native C# implementation, no dependencies).
* [tilelive-bridge](https://github.com/mapbox/tilelive-bridge) ⭐ 63 | 🐛 11 | 🌐 JavaScript | 📅 2026-06-29 - Implements [Tilelive API](https://github.com/mapbox/tilelive.js/blob/master/API.md) ⭐ 540 | 🐛 32 | 🌐 JavaScript | 📅 2026-06-29 for creating vector tiles from traditional Mapnik datasources in Node.js.
* [geojson2vt](https://github.com/geometalab/geojson2vt) ⭐ 52 | 🐛 5 | 🌐 Python | 📅 2021-04-20 - Python port of [geojson-vt](https://github.com/mapbox/geojson-vt) ⭐ 2,041 | 🐛 15 | 🌐 JavaScript | 📅 2026-07-02 to convert GeoJSON into vector tiles.
* [mbtiles-cpp](https://github.com/TimSC/mbtiles-cpp) ⭐ 37 | 🐛 0 | 🌐 C++ | 📅 2026-05-04 - C++ library for decoding of mbtiles and vector data into function callbacks.
* [vector-tile-py](https://github.com/mapbox/vector-tile-py) ⚠️ Archived - Python tool to convert a Mapnik vector tile to GeoJSON
* [dart-vector-tile](https://github.com/saigontek/dart-vector-tile) ⭐ 17 | 🐛 3 | 🌐 Dart | 📅 2026-03-28 - A simple Dart package to encode & decode Mapbox Vector Tile.
* [vt2pbf](https://github.com/DenysMoskalenko/vt2pbf) ⭐ 15 | 🐛 1 | 🌐 Python | 📅 2026-03-02 - Python port of [vt-pbf](https://github.com/mapbox/vt-pbf) ⭐ 205 | 🐛 10 | 🌐 JavaScript | 📅 2026-06-17 encode vector tiles into pbf.
* [SwiftVectorTiles](https://github.com/manimaul/SwiftVectorTiles) ⭐ 15 | 🐛 1 | 🌐 Swift | 📅 2021-01-17 - A Swift encoder for vector tiles according to the Mapbox vector tile spec.
* [cached-vector-tile](https://github.com/developmentseed/cached-vector-tile) ⭐ 8 | 🐛 0 | 🌐 JavaScript | 📅 2016-08-19 - An alternative implementation of the vector-tile-js interface, backed by plain JS objects/arrays rather than parsed-on-demand protobuf data. Trades away memory efficiency for faster feature.loadGeometry() calls.
* [php-vector-tile-data-provider](https://github.com/heymoon-cc/php-vector-tile-data-provider) ⭐ 5 | 🐛 3 | 🌐 PHP | 📅 2026-05-01 - A Composer library for encoding arbitrary [OpenGIS](https://www.ogc.org/standards/sfa) data (as read from GeoJSON/WKT/WKB or populated manually) to MVT. Designed as a base dependency for custom tile server ready for frequent updates on high RPS. Best fit for real-time weather or traffic data visualization.
* [vtzero-dart](https://github.com/landyrev/vtzero-dart) ⭐ 1 | 🐛 1 | 🌐 Dart | 📅 2025-11-08 - Dart wrapper for vtzero with vector\_tile compatibility layer.

## Clients

* [Mapbox GL JS](https://github.com/mapbox/mapbox-gl-js) ⭐ 12,385 | 🐛 1,457 | 🌐 TypeScript | 📅 2026-08-20 - JavaScript/WebGL vector maps library.
* [MapLibre GL](https://github.com/maplibre/maplibre-gl-js) ⭐ 11,391 | 🐛 391 | 🌐 TypeScript | 📅 2026-08-20 - Is a community led fork derived from Mapbox GL JS prior to their switch to a non-OSS license.
* [Mapbox GL Native](https://github.com/mapbox/mapbox-gl-native) ⚠️ Archived - C++/OpenGL vector maps library with native SDKs for Android, iOS, Node.js, macOS, and Qt
* [Mapzen Tangram](https://github.com/tangrams/tangram) ⭐ 2,333 | 🐛 66 | 🌐 JavaScript | 📅 2026-02-08 - JavaScript library for rendering 2D & 3D maps live in a web browser with WebGL, supports MVT, GeoJSON, TopoJSON
* [Mapzen Tangram-es](https://github.com/tangrams/tangram-es) ⭐ 874 | 🐛 177 | 🌐 C++ | 📅 2024-01-08 - C++ library for rendering 2D and 3D maps using OpenGL ES 2 with custom styling and interactions
* [WhirlyGlobe/Maply](https://github.com/mousebird/WhirlyGlobe/tree/master/ios/library/WhirlyGlobe-MaplyComponent/src/vector_tiles/MaplyVectorTiles.mm) ⭐ 845 | 🐛 121 | 🌐 C++ | 📅 2026-07-31 - Objective C code that is able to read and render vector tiles(and style with mapnik xml) on iOS devices.
* [Leaflet.MapboxVectorTile](https://github.com/SpatialServer/Leaflet.MapboxVectorTile) ⭐ 302 | 🐛 43 | 🌐 JavaScript | 📅 2021-10-24 is able to read PBF MapboxVectorTiles from a REST endpoint and render them as a TileLayer on a Leaflet Map. Use this option if you want to utilize vector tiles on a standard Leaflet web map without needing WebGL.
* [CARTO Mobile SDK](https://github.com/CartoDB/mobile-sdk) ⚠️ Archived - C++ maps library focused on offline features, for iOS, Android, Windows Phone and Xamarin with bindings for Java, Objective-C and C#. Based on [Nutiteq Maps SDK](https://developer.nutiteq.com), but open source and uses CartoCSS.
* [OpenLayers](https://openlayers.org/en/latest/examples/mapbox-vector-layer.html) - JavaScript vector & raster library.

- [mapscii](https://github.com/rastapasta/mapscii) ⭐ 9,222 | 🐛 52 | 🌐 JavaScript | 📅 2024-11-03 - A Vector Tile to Braille and ASCII renderer for xterm-compatible terminals
- [react-native-mapbox-gl](https://github.com/mapbox/react-native-mapbox-gl) ⭐ 2,169 | 🐛 224 | 🌐 Java | 📅 2023-03-18 - Render Mapbox GL maps from React applications
- [iTowns](https://github.com/iTowns/itowns) ⭐ 1,263 | 🐛 289 | 🌐 JavaScript | 📅 2026-08-20 - Three.js based JavaScript library for visualizing 2D vector, raster and 3D geospatial data.
- [Leaflet.VectorGrid](https://github.com/IvanSanchez/Leaflet.VectorGrid) ⭐ 675 | 🐛 121 | 🌐 JavaScript | 📅 2025-01-09 - Display gridded vector data (sliced GeoJSON, TopoJSON or Mapbox Vector Tiles) in Leaflet 1.0.0
- [mapbox-gl-leaflet](https://github.com/mapbox/mapbox-gl-leaflet) ⭐ 546 | 🐛 19 | 🌐 JavaScript | 📅 2026-06-17 - Create Mapbox GL layers in Leaflet
- [AliFlux VectorTileRenderer](https://github.com/AliFlux/VectorTileRenderer) ⭐ 206 | 🐛 20 | 🌐 C# | 📅 2022-06-22 - A highly customizable vector tile renderer built using C# for .Net platform. Comes with bindings for Mapsui and Gmap.Net components.
- [Mapbox-vector-tiles-basic-js-renderer](https://github.com/landtechnologies/Mapbox-vector-tiles-basic-js-renderer) ⭐ 149 | 🐛 42 | 🌐 JavaScript | 📅 2023-06-19 - A fork of mapbox-gl-js giving you full control over rendering of specific tiles, also provides vector tile overlay for google maps.
- [hoverboard](https://github.com/devTristan/hoverboard) ⭐ 92 | 🐛 6 | 🌐 JavaScript | 📅 2025-12-18 - Render vector tiles on canvas with Leaflet 0.7.x (supports GeoJSON, TopoJSON, and protobuf) [:warning:](https://github.com/madd512/hoverboard/issues/13#issuecomment-171406102) no longer maintained
- [ImmersiveMap](https://github.com/artembobkin/ImmersiveMap) ⭐ 88 | 🐛 2 | 🌐 Swift | 📅 2026-08-20 - A Metal-rendered Mapbox Vector Tile map engine for SwiftUI with a 3D globe and flat map, for iOS and macOS.
- [QtPBFImagePlugin](https://github.com/tumic0/QtPBFImagePlugin) ⭐ 58 | 🐛 0 | 🌐 C++ | 📅 2025-10-27 - Qt image plugin for displaying Mapbox vector tiles.
- [Unofficial Mapbox GL Native bindings for Qt QML](https://github.com/rinigus/mapbox-gl-qml) ⭐ 48 | 🐛 0 | 🌐 C++ | 📅 2026-07-19 - Qt QML bindings for Qt 5.6 and higher.
- [Vector Tiles Google Maps](https://github.com/techjb/Vector-Tiles-Google-Maps) ⭐ 47 | 🐛 2 | 🌐 JavaScript | 📅 2026-02-03 - Render vector tile layers on Google Maps.
- [esri-gl](https://github.com/muimsd/esri-gl) ⭐ 13 | 🐛 1 | 🌐 TypeScript | 📅 2026-08-15 - A module for using Esri services in Mapbox GL JS or MapLibre GL JS, an alternative to esri-leaflet for WebGL.
- [ArcGIS API for JavaScript](https://developers.arcgis.com/javascript/) - Draw vector tile layers as part of your web map. Rendering done via `mapbox-gl-js` integration.
- [Azure Maps Web SDK](https://docs.microsoft.com/azure/azure-maps/) - Render vector tile layers on an interactive web map control using JavaScript or TypeScript.
- [deckGl](https://deck.gl/docs/api-reference/geo-layers/mvt-layer) - WebGL-powered framework for visual exploratory data analysis of large datasets

## Applications / Command line tools

* [Maputnik](https://github.com/maputnik/editor) ⭐ 2,610 | 🐛 97 | 🌐 TypeScript | 📅 2026-08-20 - A visual style editor for the Mapbox GL style specification.
* [Mapbox Studio Classic](https://github.com/mapbox/mapbox-studio) ⚠️ Archived - Desktop design studio for both creating vector tiles from raw geodata and for rendering them on-the-fly into image tiles. Internally uses `tilelive.js` modules to handle vector tiles (see `tilelive-bridge` and `tilelive-vector`) :warning: use [Mapbox Studio](https://www.mapbox.com/mapbox-studio/) instead.
* [kosmtik](https://github.com/kosmtik/kosmtik) ⭐ 750 | 🐛 112 | 🌐 JavaScript | 📅 2025-03-13 - Design maps with CartoCSS and Mapnik.
* [Fresco](https://github.com/go-spatial/fresco) ⚠️ Archived - is an open source Mapbox Vector Tile Style editor.
* [QGIS Vector Tiles Reader](https://github.com/geometalab/Vector-Tiles-Reader-QGIS-Plugin) ⭐ 153 | 🐛 44 | 🌐 Python | 📅 2024-06-20 - QGIS Python plugin which reads Mapbox Vector Tiles from local MBTiles file or remote
* [mapbox-gl-inspect](https://github.com/lukasmartinelli/mapbox-gl-inspect) ⭐ 143 | 🐛 10 | 🌐 JavaScript | 📅 2020-09-08 - Plugin for Mapbox GL JS to view the view and inspect VT features.
* [Vector Tile Lab](https://github.com/spider-hand/vector-tile-lab) ⭐ 41 | 🐛 0 | 🌐 Vue | 📅 2026-03-03 - An interactive sandbox to tune vector tiles.
* [Styl](https://github.com/navidnabavi/styl) ⭐ 38 | 🐛 6 | 🌐 Rust | 📅 2026-08-15 - A fast, opinionated linter, validator, and formatter for Mapbox GL and MapLibre GL style JSON files, written in Rust
* [Mapbox Studio](https://www.mapbox.com/mapbox-studio/) - Web design studio for creating and styling vector tiles.
* [ArcGIS Pro](http://www.esri.com/en/software/arcgis-pro) - Generate vector tiles from maps authored in ArcGIS Pro or imported from ArcMap.
* [MVT Styler](http://sputnik-maps.github.io/mvt-styler/) - map style editor for vector tiles.
* [QGIS](https://qgis.org/) - supports vector tiles as a new map layer type since 3.14 release. It reads and displays styled vector tiles, adds styling GUI and writing (available as a processing toolbox algorithm).
* [Mapbox MVT Chrome Extension](https://chrome.google.com/webstore/detail/mapbox-mvt/mfikcokdfehaofebfhoehbajfgbofdpk) - Google Chrome extension that parses loaded vector tiles on the fly, shows short statistics and shows each vector tile as GeoJSON
* [Baremaps](https://www.baremaps.com/) - An open source pipeline for producing Mapbox vector tiles from OpenStreetMap with Postgis and Java.
* [Felt](https://www.felt.com) - create, style, and share maps on the web

## CLI Utilities

* [Planetiler](https://github.com/onthegomap/planetiler) ⭐ 2,145 | 🐛 113 | 🌐 Java | 📅 2026-08-18 - Command-line Java program to build planet-scale vector tilesets from OpenStreetMap data in a few hours.
* [tilemaker](https://github.com/systemed/tilemaker) ⭐ 1,883 | 🐛 138 | 🌐 C++ | 📅 2026-07-04 - Command line tool to produce vector tiles directly from an .osm.pbf extract without an intermediate database.
* [tippecanoe](https://github.com/felt/tippecanoe) ⭐ 1,584 | 🐛 164 | 🌐 C++ | 📅 2026-08-14 - Build vector tilesets from large collections of GeoJSON features.
* [MBUtil](https://github.com/mapbox/mbutil) ⚠️ Archived - Import and export MBTiles to disk :warning: no longer maintained
* [mbview](https://github.com/mapbox/mbview) ⚠️ Archived - Watch MBTiles in your localhost. View tiles in a basic Mapbox GL JS webapp locally
* [Datamaps](https://github.com/ericfischer/datamaps) ⭐ 350 | 🐛 4 | 🌐 C | 📅 2014-08-19 C application that can be used to create vector tiles and store them in an mbtiles. See the `render-vector` command. :warning: no longer maintained, use tippecanoe instead
* [vt2geojson](https://github.com/mapbox/vt2geojson) ⭐ 156 | 🐛 3 | 🌐 JavaScript | 📅 2026-06-29 - Command line tool and npm package for converting vector tiles into GeoJSON.
* [tiler @GeoVation](https://github.com/Geovation/tiler) ⚠️ Archived - Command line tool for converting GeoJSON, Shapefiles or PostGIS layer to raw Vector Tiles (or MBTiles)
* [sequentially-generate-planet-mbtiles](https://github.com/lambdajack/sequentially-generate-planet-mbtiles) ⭐ 114 | 🐛 14 | 🌐 Go | 📅 2023-09-29 - Easily generate planet-scale vector tilesets on low memory / low cpu count devices.
* [geojson2mvt](https://github.com/NYCPlanning/geojson2mvt) ⚠️ Archived - npm package for building a static vector tile tree for given xyz bounds from a geojson file (uses [geojson-vt](https://github.com/mapbox/geojson-vt) ⭐ 2,041 | 🐛 15 | 🌐 JavaScript | 📅 2026-07-02)
* [vt-geojson](https://github.com/developmentseed/vt-geojson) ⭐ 61 | 🐛 3 | 🌐 JavaScript | 📅 2016-01-27 - decodes vector tiles to GeoJSON FeatureCollections
* [tiler @thomersch](https://github.com/thomersch/grandine/tree/master/cmd/tiler) ⭐ 52 | 🐛 1 | 🌐 Go | 📅 2022-04-04 - Command line tool to convert GeoJSON to Vector Tiles (written in Go language).
* [tl](https://github.com/mojodna/tl) ⭐ 37 | 🐛 14 | 🌐 JavaScript | 📅 2018-07-10 - An alternate command line interface to tilelive
* [tileshrink](https://github.com/rastapasta/tileshrink) ⭐ 33 | 🐛 4 | 🌐 CoffeeScript | 📅 2019-11-06 - Reduce the layer extent and simplify the resulting geometries of all vector tiles in an MBTiles
* [python-vt2geojson](https://github.com/Amyantis/python-vt2geojson) ⭐ 32 | 🐛 3 | 🌐 Python | 📅 2023-01-20 - Command line tool and Python package for converting vector tiles into GeoJSON.
* [mapbox-filter](https://github.com/ondrap/mapbox-filter) ⭐ 31 | 🐛 1 | 🌐 Haskell | 📅 2024-02-12 - Filter MBTiles according to Mapbox GL JS styles, shrink MBTiles directly, serve locally over http, publish to S3-compatibile storage
* [XYZ](https://github.com/dechristopher/xyz) ⭐ 31 | 🐛 3 | 🌐 Go | 📅 2023-04-23 - Simple tool to procedurally prime XYZ tile caches to a given zoom level.
* [tilefeed](https://github.com/muimsd/tilefeed) ⭐ 7 | 🐛 0 | 🌐 Rust | 📅 2026-08-14 - PostGIS vector tile pipeline that generates MBTiles via Tippecanoe with incremental updates via PostgreSQL LISTEN/NOTIFY.
* [vt2geojson](https://github.com/wangyoucao577/vt2geojson) ⭐ 5 | 🐛 1 | 🌐 Go | 📅 2023-02-20 Command line tool to convert Vector Tiles to GeoJSON (written in `Go` language based on the awesome [orb](https://github.com/paulmach/orb) ⭐ 1,126 | 🐛 19 | 🌐 Go | 📅 2026-03-30 package).
* [mbview-go](https://github.com/ATofighi/mbview-go) ⭐ 2 | 🐛 0 | 🌐 Go | 📅 2026-02-27 - Watch and debug MBTiles in your localhost. A go reimplentation of [mbview](https://github.com/mapbox/mbview) ⚠️ Archived designed for modern toolchains and distributed as standalone binaries.
* [vector-tiles-producer](https://github.com/vross/vector-tiles-producer) Command line tool in C++ to creates vector tiles for a given area at chosen zoom levels using a Mapnik XML. :warning: no longer maintained
* [OGR MVT](http://gdal.org/drv_mvt.html) and [MBTiles](http://gdal.org/frmt_mbtiles.html) - The GDAL/OGR MVT and MBTILES drivers can be used to read and write vector tiles, respectively as tileset on the filesystem or in a mbtiles container (GDAL >= 2.3.0)
* [tileinfo](https://www.npmjs.com/package/tileinfo) - Display TileJSON info about an mbtiles file.
* [Vtiles](https://pypi.org/project/vtiles/) - All in One Vector Tiles Utilities.

## Mapbox GL JS Plugins

* [gl-draw](https://github.com/mapbox/gl-draw) ⭐ 1,083 | 🐛 242 | 🌐 JavaScript | 📅 2026-08-17 - Adds support for drawing and editing features on Mapbox GL JS maps
* [map-gl-offline](https://github.com/muimsd/map-gl-offline) ⭐ 21 | 🐛 1 | 🌐 TypeScript | 📅 2026-07-15 - A TypeScript package for MapLibre GL JS and Mapbox GL JS to enable offline tiles.
* [map-gl-style-switcher](https://github.com/muimsd/map-gl-style-switcher) ⭐ 8 | 🐛 1 | 🌐 TypeScript | 📅 2026-07-28 - A customizable style switcher control for Mapbox GL JS and MapLibre GL JS.

## Servers

* [martin](https://github.com/maplibre/martin) ⭐ 3,837 | 🐛 74 | 🌐 Rust | 📅 2026-08-20 - Blazing fast and lightweight PostGIS, MBtiles and PMtiles tile server written in Rust. Support for tile copying, diffing and updating.
* [tileserver-gl](https://github.com/maptiler/tileserver-gl) ⭐ 2,882 | 🐛 274 | 🌐 JavaScript | 📅 2026-08-10 Vector and raster maps with GL styles. Server side rendering by Mapbox GL Native. Map tile server for Mapbox GL JS, Android, iOS, Leaflet, OpenLayers, GIS via WMTS, etc.
* [Tegola](https://github.com/go-spatial/tegola) ⭐ 1,499 | 🐛 182 | 🌐 Go | 📅 2026-08-10 - is a vector tile server delivering Mapbox Vector Tiles with support for PostGIS and GeoPackage data providers.
* [pg\_tileserv](https://github.com/CrunchyData/pg_tileserv) ⭐ 1,057 | 🐛 42 | 🌐 Go | 📅 2025-12-11 - A very thin PostGIS-only tile server in Go. Takes in HTTP tile requests, executes SQL, returns MVT tiles.
* [mbtileserver](https://github.com/consbio/mbtileserver) ⭐ 789 | 🐛 23 | 🌐 Go | 📅 2025-05-21 - A simple Go-based server for map tiles stored in mbtiles format.
* [TileStache](https://github.com/TileStache/TileStache) ⭐ 765 | 🐛 135 | 🌐 Python | 📅 2024-05-07 added support for Mapbox Vector tiles via .pbf extension requests.
* [t-rex](https://github.com/pka/t-rex/) ⭐ 577 | 🐛 54 | 🌐 Rust | 📅 2024-09-24 - MVT server in a single executable written in Rust. Serves tiles from PostGIS supporting custom tile grids.
* [SpatialServer (PGRestAPI)](https://github.com/spatialdev/PGRestAPI) ⭐ 434 | 🐛 88 | 🌐 JavaScript | 📅 2018-04-28 - A multi-purpose GeoSpatial NodeJS web server created at [SpatialDev](http://spatialdev.com) that not only serves MBTiles stuffed with vector tiles, it can also cut vector tiles on the fly from a PostGIS database. [:warning:](https://github.com/spatialdev/PGRestAPI/issues/142#issuecomment-231132808) ⭐ 434 | 🐛 88 | 🌐 JavaScript | 📅 2018-04-28 No longer maintained.
* [tilestrata](https://github.com/naturalatlas/tilestrata) ⭐ 426 | 🐛 8 | 🌐 JavaScript | 📅 2021-07-21 - with tilestrata-vt, it can generate Mapnik Vector Tiles; with [tilestrata-postgismvt](https://github.com/Stezii/tilestrata-postgismvt) ⭐ 18 | 🐛 4 | 🌐 JavaScript | 📅 2017-10-06, it can serve Mapbox Vector Tiles from a PostGIS db
* [tessera](https://github.com/mojodna/tessera) ⭐ 325 | 🐛 29 | 🌐 JavaScript | 📅 2026-08-02 - Supports serving and rendering vector tiles. Uses the same core libraries as Mapbox Studio.
* [Kartotherian](https://github.com/kartotherian/kartotherian) ⚠️ Archived Wikipedia tile server with [Tilerator](https://github.com/kartotherian/tilerator) ⚠️ Archived backend tile pre-generator
* [TiMVT](https://github.com/developmentseed/timvt) ⚠️ Archived - A lightweight PostGIS based dynamic vector tile server.
* [tilesplash](https://github.com/faradayio/tilesplash) ⭐ 178 | 🐛 17 | 🌐 JavaScript | 📅 2018-09-04 - A light and quick nodejs webserver for serving topojson or mapbox vector tiles from a postgis backend
* [BBOX](https://github.com/bbox-services/bbox) ⭐ 166 | 🐛 21 | 🌐 Rust | 📅 2025-10-11 - An open source server to provide geodata as OGC API features, maps, tiles and more
* [ClusterBuster](https://github.com/chargetrip/clusterbuster) ⭐ 98 | 🐛 29 | 🌐 TypeScript | 📅 2023-11-23 A Mapbox Vector Tile (MVT) map tiling server with built-in clustering and filtering.
* [tessella](https://github.com/urbica/tessella) ⭐ 85 | 🐛 12 | 🌐 JavaScript | 📅 2023-01-23 - lightweight Node.js Mapbox Vector Tiles server. Inspired by tessera.
* [tileserver](https://github.com/tilezen/tileserver) ⭐ 80 | 🐛 6 | 🌐 Python | 📅 2024-05-30 Mapzen Vector Tile Service.
* [Cloud-Tileserver](https://github.com/henrythasler/cloud-tileserver) ⭐ 67 | 🐛 7 | 🌐 TypeScript | 📅 2026-04-08 - Serve vector tiles with AWS. Includes a Lambda-Function written in Typescript to dynamically create vector tiles with postgis. Terraform configuration and step-by-step tutorial is also included.
* [FastVector](https://github.com/mkeller3/FastVector) ⭐ 65 | 🐛 1 | 🌐 Python | 📅 2022-07-08 - is a multi database PostGIS based vector tile server with cql filtering and caching written in [Python](https://www.python.org/) with [FastAPI](https://fastapi.tiangolo.com/). Inspired by TiMVT.
* [go-vtile-example](https://github.com/vicapow/go-vtile-example) ⭐ 57 | 🐛 2 | 🌐 Go | 📅 2016-07-30 - An example server written in Go
* [djangorestframework-mvt](https://github.com/corteva/djangorestframework-mvt) ⭐ 53 | 🐛 10 | 🌐 Python | 📅 2021-11-18 - A Django REST Framework extension for creating views that serve Postgres data as tiles.  Tiles can be paginated and filtered by their properties.
* [MVT Server](https://github.com/mvt-proj/mvt-rs) ⭐ 46 | 🐛 0 | 🌐 Rust | 📅 2026-08-19 - One platform for publishing cartographic resources from PostGIS (developed in Rust).
* [Utilery](https://github.com/etalab/utilery) ⭐ 44 | 🐛 6 | 🌐 Python | 📅 2017-11-01 Server to generate vector tiles from PostGIS queries. Python based [:warning:](https://github.com/tilery/utilery/issues/6) ⭐ 44 | 🐛 6 | 🌐 Python | 📅 2017-11-01 no longer maintained.
* [postserve](https://github.com/openmaptiles/postserve) ⚠️ Archived - A small Python based tileserver using ST\_AsMVT and ST\_AsMVTGeom to generate vector tiles on the fly. Designed for use with PostGIS 2.4 and the OpenMapTiles project
* [Maptoolkit.org](https://github.com/maptoolkit/maptoolkit.org) ⭐ 27 | 🐛 0 | 📅 2026-08-10 - free REST API serving MVT vector tiles
* [tilenol](https://github.com/StationA/tilenol) ⭐ 26 | 🐛 18 | 🌐 Go | 📅 2026-07-03 - A lightweight, scalable tile server that transforms geospatial data stored in multiple backends (e.g. Elasticsearch, PostgreSQL) into Mapbox Vector Tiles on demand
* [LOD](https://github.com/tile-fund/lod) ⭐ 24 | 🐛 12 | 🌐 Go | 📅 2026-08-20 - A thin map tile proxy with in-memory caching and a slim authentication backend.
* [Hastile](https://github.com/indicatrix/hastile) ⭐ 19 | 🐛 9 | 🌐 Haskell | 📅 2021-01-20 - Haskell web server using PostGIS to deliver vector tiles.
* [ngx\_http\_mbtiles\_module](https://github.com/durkie/ngx_http_mbtiles_module) ⭐ 17 | 🐛 1 | 🌐 C | 📅 2024-03-06 - Serve mbtiles files directly from nginx. Ideal for low-resource environments or situations where the mbtiles contents are changing frequently.
* [pgsql-omt-schema](https://github.com/feludwig/pgsql-omt-schema) ⭐ 5 | 🐛 0 | 🌐 PLpgSQL | 📅 2024-01-31 - A set of templated SQL functions to serve OpenMapTiles [schema](https://openmaptiles.org/schema/) vector tiles from a PostgreSQL database
* [ArcGIS Online](http://www.esri.com/software/arcgis/arcgisonline) - Supports serving vector tiles and rendering in the mapping application powered by the ArcGIS API for JavaScript
* [GeoServer](http://geoserver.org) - java web application for sharing and editing geospatial data. [Vector tile extension](https://docs.geoserver.org/latest/en/user/extensions/vectortiles/index.html) available since GeoServer 2.11.
* [MapAtlas](https://mapatlas.eu) - REST API serving MVT vector tiles along with geocoding, routing, isochrone, and map matching services, built on OpenStreetMap and proprietary data.
* [MapServer](https://mapserver.org/) - Open Source platform, written in C, for publishing spatial data and interactive mapping applications to the web. MVT output available since version 7.2
* [OpenMapTiles](https://github.com/openmaptiles) - Set of open-source tools for self-hosting of OpenStreetMap maps in more than 50 languages. It provides both raster as well as vector tiles, WMS and WMTS services for GIS programs, support for JavaScript viewers and mobile SDK.
* [OSM Scout Server](https://rinigus.github.io/osmscout-server/) - Maps server providing vector and raster tiles, geocoder, and router. Designed to be used on Linux (mobile and PC) to provide offline maps; written in C++
* [Portal for ArcGIS](http://www.esri.com/software/arcgis/arcgisserver/extensions/portal-for-arcgis) - Supports serving vector tiles and rendering in the mapping application powered by the ArcGIS API for JavaScript
* [Tyler](https://github.com/marauder-io/tyler) - An Open Source tiling server maintaining a Vector Tile storage providing a REST interface.
* [Vallaris Maps](https://vallarismaps.com) - Mapping Platforms to storage process and services GIS Data. Provide DataService API and Maps API (Vector Tiles, WMS, WMTS) Compilance in OGC API Standards.
* [Quarkus MVT Tile Server](https://gitlab.com/sigeosrl/quarkus-mvt-tile-server) - A Quarkus application that serves Mapbox Vector Tiles from PostGIS databases.

## Low-level utilities

* [vt-pbf](https://github.com/anandthakker/vt-pbf) ⭐ 205 | 🐛 10 | 🌐 JavaScript | 📅 2026-06-17 serialize JavaScript objects representing vector tiles into binary Protocol Buffer encodings of vector tiles
* [vtzero](https://github.com/mapbox/vtzero) ⭐ 106 | 🐛 1 | 🌐 C++ | 📅 2026-06-30 - minimalist vector tile decoder and encoder in C++
* [pymgl](https://github.com/brendan-ward/pymgl) ⭐ 48 | 🐛 8 | 🌐 C | 📅 2024-09-30 - Maplibre GL Native Static Renderer for Python
* [mvt-fixtures](https://github.com/mapbox/mvt-fixtures/) ⭐ 28 | 🐛 8 | 🌐 JavaScript | 📅 2026-06-29 - a suite of valid and invalid test fixtures according to the Mapbox Vector Tile spec versions. Includes simplified unit test fixtures and real-world fixtures to test your encoders and decoders.
* [mapbox-gl-function](https://github.com/mapbox/mapbox-gl-function) ⭐ 12 | 🐛 1 | 📅 2026-06-17 - Mapbox GL style function evaluator :warning: now maintained as party of mapbox-gl-js
* [mapbox-gl-filter-simplify](https://github.com/mapbox/mapbox-gl-filter-simplify) - Simplifies and complexifies filters in Mapbox GL Styles :warning: removed

## Articles

* [Vector tiles remixed](http://gdunlop.github.io/Vector-tiles-remixed/) - guide to using [tilemaker](https://github.com/systemed/tilemaker) ⭐ 1,883 | 🐛 138 | 🌐 C++ | 📅 2026-07-04 to generating vector tiles
* [Serverless Vector Tiles on AWS](https://github.com/addresscloud/serverless-tiles) ⚠️ Archived
* [Tegola OSM/OMT Import Procedure](https://github.com/dechristopher/tegola-omt) ⭐ 37 | 🐛 1 | 🌐 JavaScript | 📅 2021-10-17 - This document outlines everything necessary to build, from scratch, an operational OpenStreetMap vector tile server. The stack consists of the latest LTS Ubuntu Server distribution, Tegola as the tile server, PostgreSQL as the database, and the use of the open source OpenMapTiles standard schema.
* [Build Your Own Static Vector Tile Pipeline](https://geovation.github.io/build-your-own-static-vector-tile-pipeline) - guide transforming, encoding and hosting tiles in the cloud; using ogr2ogr + tippecanoe + Mapbox GL JS
* [Using the new MVT function in PostGIS](https://medium.com/nycplanninglabs/using-the-new-mvt-function-in-postgis-75f8addc1d68) - Building a vector tile service with PostGIS, express, and pg-promise.
* [Creating OpenStreetMap Tiles](https://p3dt.net/post/2020/12/28/creating-map-tiles.html) - create you own vector tileset (and it's raster representation) from openstreetmap pbf data using tilemaker and tileserver-gl.

## Performance analysis

* [vector-tiles-benchmark](https://github.com/FabianRechsteiner/vector-tiles-benchmark) ⭐ 74 | 🐛 3 | 🌐 JavaScript | 📅 2026-01-19 - Performance comparison of open source vector tiles server solutions for providing geodata from PostGIS databases ([BBOX], [ldproxy], [Martin], [pg\_tileserv][pg_tileserv], [Tegola], [TiPg])

<!-- GitHub Links-->

[BBOX]: https://github.com/bbox-services/bbox

[ldproxy]: https://github.com/interactive-instruments/ldproxy

[Martin]: https://github.com/maplibre/martin

[pg_tileserv]: https://github.com/CrunchyData/pg_tileserv

[Tegola]: https://github.com/go-spatial/tegola

[TiPg]: https://github.com/developmentseed/tipg

## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Tom MacWright](http://macwright.org) has waived all copyright and related or neighboring rights to this work.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-20._
