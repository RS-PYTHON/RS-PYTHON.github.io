---
title: "Deployment"
permalink: /feature/deployment
excerpt: "RS-Server can be deployed on a cluster or locally."
header:
  image: /assets/images/architecture/deployment_header.jpg
  teaser: /assets/images/architecture/deployment_teaser.jpg
sidebar:
  title: ""
  nav: sidebar-deployment

---
The rs-server offers two deployment targets:
- cluster
- local

For each kind of deployment, here are the overall associated features.

## Cluster mode
On the **cluster mode**, the rs-server is deployed as several Kubernetes PODs. A deployment with HELM chart is provided.
On the cluster environment, rs-server can be called from a Prefect chain or directly from a Jupyter notebook.
The rs-server running the cluster has a strong access control for each sensitive data access (CADIP, LTA, AUXIP, PRIP, and Catalog).

Here are **CSC RS Python in a Nutshell** features from the cluster.

<div id="conteneur">
  <img src="/assets/images/architecture/RSPY_cluster.jpg" width="1500" height="701">
</div>




## Local mode
On **local mode**, rs-server, the station mockups, Prefect, Dask and a Jupyter server are deployed on the local machine
with Docker Compose, without access control. It is used for development and tests: from the local machine, the end
user can read and write the local rs-server catalog, and run the Prefect flows locally.

See the [RS-Python documentation](https://home.rs-python.eu/rs-documentation/) for the details of both modes.

The differences between both modes:
<div id="conteneur">
  <img src="/assets/images/architecture/local-and-cluster-modes.svg" alt="Local mode and cluster mode">
</div>
