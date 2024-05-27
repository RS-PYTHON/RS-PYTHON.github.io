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
  - excerpt: 'RS client libraries will provide Prefect chain to compute any Sentinel-1, Sentinel-2 and Sentinel-3 products. '

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
    


feature_catalog:
  - image_path: /assets/images/architecture/stac.jpg
    alt: "RS-Server Catalog"
    title: "RS-Server Catalog"
    excerpt: "RS-Server provides a Catalog compliant with the SpatioTemporal Asset Catalog (STAC) format. "
    url: "/portfolio/catalog"
    btn_label: "Read More"
    btn_class: "btn--primary"


feature_staging:
  - image_path: /assets/images/station/Svalbard_Ground_System_(33796875886).jpg
    alt: "RS-Server external data sources"
    title: "RS-Server staging"
    excerpt: 'RS-Server provides staging functionality to retrieves product from external data sources. RS-Server can provide access to auxillary data from ADGS station. It can also provide access to Telemetry raw data from CADIP stations, sentinel level-0 product from LTA or Level-1 and Level-2 from PRIP.'
    url: "#staging-article"
    btn_label: "Read More"
    btn_class: "btn--primary"

feature_prefect:
  - image_path: /assets/images/architecture/prefect1.png
    alt: "Workflow as a code"
    title: "Processing workflow as a code"
    excerpt: ''
    url: "#prefect"
    btn_label: "Read More"
    btn_class: "btn--primary"

    
feature_virtual:
  - image_path: /assets/images/architecture/jup.jpg
    alt: "Jupyter"
    title: "Virtual environment"
    excerpt: ''
    url: "#jupyter"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_catalog" type="left" %}
RS-Server implements the STAC API specification adding an access control per Collection and per User.
``` javascript 
 {
    "stac_version": "1.0.0",
    "type": "Collection",
    "license": "ISC",
    "id": "20201211_223832_CS2",
    "description": "A simple collection example",
    "links": [],
    "extent": {},
    "summaries": {}
}
```

{% include feature_row id="feature_staging" type="right" %}

{% include feature_row id="feature_prefect" type="left" %}

{% include feature_row id="feature_virtual" type="right" %}

