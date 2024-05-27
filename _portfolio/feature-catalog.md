---
title: "RS Spatio Temporal Asset Catalog"
permalink: /portfolio/catalog
excerpt: "Baz Boom design system including logo mark, website design, and branding applications."
header:
  image: /
  teaser: /assets/images/architecture/stac.jpg
sidebar:
  - title: "Component"
    image: /assets/images/architecture/stac.jpg
    image_alt: "logo"
    text: "XXXX"
  - title: "Use Case"
    text: "YYYY"
gallery:
  - url: /assets/images/unsplash-gallery-image-1.jpg
    image_path: assets/images/unsplash-gallery-image-1-th.jpg
    alt: "placeholder image 1"
  - url: /assets/images/unsplash-gallery-image-2.jpg
    image_path: assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
  - url: /assets/images/unsplash-gallery-image-3.jpg
    image_path: assets/images/unsplash-gallery-image-3-th.jpg
    alt: "placeholder image 3"
---

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