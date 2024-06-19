---
title: "Catalog"
permalink: /portfolio/catalog
excerpt: "The rs-server provides a STAC Catalog with a fine access control per Collection and per User."
header:
  image: /assets/images/architecture/stac_header.jpg
  teaser: assets/images/architecture/stac_teaser.jpg
sidebar:
  title: ""
  nav: sidebar-catalog

---
The rs-server offers a fine **access control** per Collection to the Catalog. Each end-user, thanks to an API-KEY can access to its collection an the ones for which he is authorized. The catalog provided by rs-server adheres to the SpatioTemporal Asset Catalog (STAC) format. By adopting a standardized format like STAC, rs-server aims to streamline the organization and querying of geospatial asset metadata.

The **SpatioTemporal Asset Catalog (STAC)** specification provides a common structure for describing and cataloging spatiotemporal assets. A spatiotemporal asset is any file that represents information about the Earth captured in a certain space and time. STAC allows geospatial data to be more easily searchable and queryable by establishing a standard, unified language. It consists of a network of JSON files that reference other JSON files, with each adhering to specific core specifications depending on the STAC component being described. These components include:

1. **STAC Item**: The foundational building block of STAC, represented as GeoJSON features supplemented with additional metadata. Each item can describe one or more spatiotemporal assets, making it easily readable by modern GIS or geospatial libraries.

2. **STAC Catalog**: Provides structural elements to group STAC Items and Collections. Collections are catalogs that add more required metadata and describe a group of related items.

3. **STAC Collection**: Extends Catalog directly, adding additional fields to enable description of spatial and temporal extents, licenses, keywords, providers, and more.

The flexibility and extensibility of the STAC specification allow different domains and tools to utilize it effectively, making it a powerful standard for Earth observation data.


The STAC spec itself provides a lowest common denominator JSON format to wrap around any relevant data about the earth. The core GeoJSON object and related structures are designed for extension, so it can adapt to different domains.

```json
{
    "stac_version": "1.0.0",
    "type": "Feature",
    "id": "20201211_223832_CS2",
    "bbox": [],
    "geometry": {},
    "properties": {},
    "collection": "simple-collection",
    "links": [],
    "assets": {}
}
```


