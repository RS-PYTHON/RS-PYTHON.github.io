---
title: "Deployment"
layout: splash
permalink: /portfolio/deployment
excerpt: "RS-Server can be deployed on a cluster or locally."
header:
  image: /assets/images/architecture/deployment_header.jpg
  teaser: /assets/images/architecture/deployment_teaser.jpg
sidebar:
  title: ""
  nav: sidebar-deployment

---
RS-Server offers two deployment targets:
- cluster
- local

For each kind of deployment, here are the overall associated features.

## Cluster mode
On the **cluster  mode**, the RS-Server is deployed as several Kubernetes PODs. A deployment with HELM chart is provided. 
On the cluster environement, RS-Server can be called from a Prefect chain or directy from a Jupyter notebook.
The RS-Server running the cluster has got a strong access control for each sensitive data access (CADIP, LTA, AUXIP, PRIP, and Catalog).

After deployment, here are **CSC RS-Python in a Nutshell** features from the cluster.
<style type="text/css">
  #conteneur {
    margin-top:0;
    margin-bottom:0;
    text-align: left;
    }
</style>


<div id="conteneur">
  <img src="/assets/images/architecture/RSPY_cluster.jpg" width="1500" height="701">
</div>


## Local mode
On **local mode**, RS-Server deploys a Catalog without access control.

From the local machine, end user can:
- read / write to the local RS-Server catalog
- connect to the RS-Server running on the cluster and access any service which is authorised for.

After deployment, here are **CSC RS-Python in a Nutshell** features from the laptop.
<div id="conteneur">
  <img src="/assets/images/architecture/RSPY_local.jpg" width="1500" height="701">
</div>




<span style="color: black; background-color: #1A89DF;">**version 0.1**</span>
What is already in this release ? 
- cluster mode 
- local mode

From the local laptop, it is not possible to run directly a Prefect chain running the cluster.



