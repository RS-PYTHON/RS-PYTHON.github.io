---
title: "RS Software"
layout: splash
permalink: /
date: 2016-03-23T11:48:41-04:00
header:
  overlay_color: "#000"
  overlay_filter: "0.3"
  overlay_image: /assets/images/sentinel/South_Georgia_Island_as_seen_by_Sentinel-2.jpg
  actions:
    - label: "Download"
      url: "https://github.com/RS-PYTHON"
  caption: "South Georgia Island as seen by Sentinel-2"
excerpt: "Reference System Python implements and maintains a new version of the RS Software compatible with the new Python-based processors, taking advantage of existing Python libraries (in particular Prefect) and novel tools to maximise the flexibility and simplify the maintainability of the solution."


intro: 
  - excerpt: 'Welcome to the Reference-System Python ! Our platform is designed to efficiently orchestrate processing pipelines for Copernicus satellite imagery. We will  support at first processing chains for Sentinel-1, Sentinel-2, and Sentinel-3 data. Looking ahead, we’re excited to expand our capabilities to include Sentinel-5P and other upcoming Copernicus missions. Join us on this journey as we unlock valuable insights from Earth observation data!  '

feature_row:
  - image_path: assets/images/sentinel/Irkutsk_and_Lake_Baikal_ESA15342560.jpeg
    alt: "Irkutsk and Lake Baika Sentinel-1 image"
    title: "Sentinel-1"
#    excerpt: "This is some sample content that goes here with **Markdown** formatting."

  - image_path: /assets/images/sentinel/Lake_MacKay_Australia.jpg
#    image_caption: "Image courtesy of [Unsplash](https://unsplash.com/)"
    alt: "Lake MacKay Australia Sentinel-2 image"
    title: "Sentinel-2"
#    url: "#test-link"
#    btn_label: "Read More"
#    btn_class: "btn--primary"

  - image_path: /assets/images/sentinel/1024px-Cloud-free_Europe_ESA17486464.jpeg
    alt: "Europe Sentinel-3 image"
    title: "Sentinel-3"

  - image_path: /assets/images/sentinel/Sentinel-5P_CLOUD,_Effective_radiometric_cloud_fraction.jpg
    alt: "Cloud Sentinel-5 image"
    title: "Sentinel-5P"


    
    


feature_catalog:
  - image_path: /assets/images/architecture/stac_teaser.jpg
    alt: "RS-Server Catalog"
    title: "RS-Server Catalog"
    excerpt: "RS-Server offers a fine access control per Collection to the Catalog. 
The catalog provided by RS-Server adheres to the SpatioTemporal Asset Catalog (STAC) format. By adopting a standardized format like STAC, RS-Server aims to streamline the organization and querying of geospatial asset metadata. The term “spatiotemporal asset” encompasses any file that conveys information about Earth captured at a specific location and time."
    url: "/portfolio/catalog"
    btn_label: "Read More"
    btn_class: "btn--primary"


feature_staging:
  - image_path: /assets/images/station/staging_teaser.jpg
    alt: "RS-Server external data sources"
    title: "RS-Server staging"
    excerpt: "RS-Server offers staging functionality with access control for retrieving products from external data sources. RS-Server grants access to auxiliary data from the AUXIP station, as well as telemetry raw data from CADIP stations. It will also provide access to Sentinel level-0 products from LTA and Level-1 and Level-2 products from PRIP."
    url: "/portfolio/staging"
    btn_label: "Read More"
    btn_class: "btn--primary"

feature_prefect:
  - image_path: /assets/images/architecture/prefect_teaser.jpg
    alt: "Workflow as a code"
    title: "Processing workflow as a code"
    excerpt: "RS Python leverages the Prefect orchestrator for managing and automating workflows. Prefect simplifies workflow management, reduces operational costs, and provides a smoother experience for data orchestration compared to other tools. Its flexibility, quick adoption, and supportive community make it an excellent choice for RS’s workflow needs."
    url: "/portfolio/prefect"
    btn_label: "Read More"
    btn_class: "btn--primary"

    
feature_virtual:
  - image_path: /assets/images/architecture/jup_teaser.jpg
    alt: "Jupyter"
    title: "Virtual environment"
    excerpt: "RS Python provides access to JupyterLab to end-user. The end-user can build or start already made Prefect worflows from RS client libraries. JupyterLab proposes a flexible workspace organization to users making it easier to work with multiple tabs simultaneously. Additionally, JupyterLab provides a comprehensive Markdown editor, enhancing the writing and documentation experience within notebooks.
    JupyterLab offers a richer and more efficient data programming experience, making it a wise choice for RS."
    url: "/portfolio/jupyter"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_catalog" type="left" %}
Here is an example of STAC collection retrieved from RS catalog.
``` javascript 
 {
    "stac_version": "1.0.0",
    "type": "Collection",
    "license": "XXX",
    "id": "20201211_223832_XXX",
    "description": "A simple collection example",
    "links": [],
    "extent": {},
    "summaries": {}
}
```

{% include feature_row id="feature_staging" type="right" %}

{% include feature_row id="feature_prefect" type="left" %}

{% include feature_row id="feature_virtual" type="right" %}

