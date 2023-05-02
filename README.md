# OGC Two Dimensional Tile Matrix Set and Tileset Metadata

Latest published **version 2.0** of the OGC Two Dimensional Tile Matrix Set and Tileset Metadata standard: [HTML](https://docs.ogc.org/is/17-083r4/17-083r4.html) [PDF](https://docs.ogc.org/is/17-083r4/17-083r4.pdf)

Latest release notes: [HTML](https://docs.ogc.org/is/17-083r4/21-066r1.html) [PDF](https://docs.ogc.org/is/17-083r4/21-066r1.pdf)

This standard defines the models and encodings for the Tile Matrix Sets and Tileset metadata of [_OGC API - Tiles_](https://docs.ogc.org/is/20-057/20-057.html).

Before becoming an independent OGC standard, the original concepts were used in the [OGC Web Map Tile Service (WMTS)](https://portal.ogc.org/files/?artifact_id=35326) and [OGC GeoPackage](https://www.geopackage.org/spec131/index.html).

The main new capabilities of this independent standard are:

- the concept of common Tile Matrix Sets that can be registered e.g., in the [OGC Tile Matrix Set Register](http://www.opengis.net/def/tms), re-used and easily recognized by URI,
- support for [variable width tile matrices](https://docs.ogc.org/is/17-083r4/17-083r4.html#toc57) to better accommodate polar regions of Tile Matrix Sets defined in a geographic CRS,
- a new service-independent [tileset metadata model](https://docs.ogc.org/is/17-083r4/17-083r4.html#toc20) and [encodings](https://docs.ogc.org/is/17-083r4/17-083r4.html#toc23), including the ability to describe schemas for component data layers of tiles of vector features or coverage data,
- a [JSON encoding](https://docs.ogc.org/is/17-083r4/17-083r4.html#toc18) of Tile Matrix Set definitions.

This GitHub repository contains the draft content for a future revision or corrigendum of the standard.

The repo is organized as follows:

* [**registry/**](registry/) - The authoritative source of the [OGC Tile Matrix Set Register](http://www.opengis.net/def/tms), maintained by the _OGC API - Tiles_ Standard Working Group
* [**release_notes/**](release_notes/) - the differences and improvements between versions 2.0 (OGC 17-083r4) and 1.0 (OGC 17-083r2)
* [**schemas/**](schemas/) - XML and JSON Schemas and examples for TileMatrixSet definitions and Tileset Metadata
* [**standard/**](standard/) - the main standard document content
* [**standard/uml/**](standard/UML/) - The UML models used in the standard in EAP format.
