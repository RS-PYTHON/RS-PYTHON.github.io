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
On the **cluster  mode**, the rs-server is deployed as several Kubernetes PODs. A deployment with HELM chart is provided. 
On the cluster environement, rs-server can be called from a Prefect chain or directy from a Jupyter notebook.
The rs-server running the cluster has got a strong access control for each sensitive data access (CADIP, LTA, AUXIP, PRIP, and Catalog).

Here are **CSC RS Python in a Nutshell** features from the cluster.

<div id="conteneur">
  <img src="/assets/images/architecture/RSPY_cluster.jpg" width="1500" height="701">
</div>




## Local mode
On **local mode**, rs-server deploys a Catalog without access control.

From the local machine, end user can:
- read / write to the local rs-server catalog
- connect to the rs-server running on the cluster and access any service which is authorised for.

And here are **CSC RS Python in a Nutshell** features from the laptop.
<div id="conteneur">
  <img src="/assets/images/architecture/RSPY_local.jpg" width="1500" height="701">
</div>





