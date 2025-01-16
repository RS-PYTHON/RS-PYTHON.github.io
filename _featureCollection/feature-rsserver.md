---
title: "rs-server"
permalink: /feature/rs-server
excerpt: "The rs-server provides a STAC Catalog with a fine access control per Collection and per User."
header:
  image: /assets/images/architecture/rs-server_header.jpg
  teaser: assets/images/architecture/rs-server_teaser.jpg
sidebar:
  title: ""
  nav: sidebar-rsserver

---
## RS-Server Overview

The rs-server offers essential services for building Copernicus processing workflows, all secured by stringent access controls. Rs-server adheres to the **SpatioTemporal Asset Catalog (STAC)** format. By adopting a standardized format like STAC, rs-server aims to streamline the organization and querying of geospatial asset metadata.

### Key Features

- **Catalog Function**:  the **rs-server** offers robust **access control** per collection within a catalog. Each end-user, utilizing an API key, can access their collection and others they are authorized for. 

- **Search Function**: the **rs-server** provides STAC interfaces to search items on CSC stations:
  - **Copernicus Ground Stations**: Retrieve CADU chunks.
  - **Copernicus AUXIP Stations**: Retrieve auxiliary data.
  - **Copernicus Long Term Archives**: Retrieve any Level-0 products.
  - **Copernicus Production Services**: Retrieve Level-1 and Level-2 recent products.

- **Browsing Function**: the **rs-server** provides a **STAC Browser** tool for exploring data from stations. The browser features an intuitive and responsive design, making it accessible to users of all skill levels. It provides a seamless experience for both novice and experienced geospatial data users. 


- **Staging Function**: the **rs-server** allows end-users to integrate retrieved data into the STAC catalog. This feature stages a STAC itemCollection from external data sources to object storage and stores the STAC items in the catalog.



### About STAC

The **SpatioTemporal Asset Catalog (STAC)** specification provides a common structure for describing and cataloging spatiotemporal assets. A spatiotemporal asset is any file representing information about the Earth captured at a specific time and place. STAC allows geospatial data to be more easily searchable and queryable by establishing a standard, unified language.

