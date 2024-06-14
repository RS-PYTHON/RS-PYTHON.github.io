---
title: "Deployment"
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



## Local mode
On **local mode**, RS-Server deploys a Catalog without access control.

From the local machine, end user can:
- read / write to the local RS-Server catalog
- connect to the RS-Server running on the cluster and access any service which is authorised for.




<span style="color: black; background-color: #1A89DF;">**version 0.1**</span>
What is already in this release ? 
- cluster mode 
- local mode

From the local laptop, it is not possible to run directly a Prefect chain running the cluster.



