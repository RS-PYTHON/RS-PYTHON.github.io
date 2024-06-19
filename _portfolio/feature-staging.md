---
title: "Staging"
permalink: /portfolio/staging
excerpt: "The rs-server offers staging functionality with access control for retrieving products from Copernicus external data sources (like AUXIP and CADIP stations)."
header:
  image: /assets/images/station/staging_header.jpg
  teaser: /assets/images/station/staging_teaser.jpg
sidebar:
  title: ""
  nav: sidebar-staging

---
The rs-server offers staging functionality with access control for retrieving products from external data sources. Authorised end user can connect to Copernicus interface to retrieve input data for processing.
These data came from :
- Copernicus ground stations : to retrieve CADU chunks 
- Copernicus AUXIP stations : to retrieve auxiliary data
- Copernicus Long Term Archives : to retrieve any Level-0 products 
- Copernicus Production Services : to retrieve Level-1 and Level-2 recent products 
 

The rs-server control user access to all of these sensitive interfaces. Access control is performed via an API-KEY.
In addition, rs-server will provide a STAC interface to access CADIP and AUXIP data.


<span style="color: black; background-color: #1A89DF;">**version 0.1**</span>
What is already in this release ? 
- Access control 
- Access to AUXIP and CADIP station is there !

Access to LTA and PRIP and providing staging as a STAC service will come on next release. 

