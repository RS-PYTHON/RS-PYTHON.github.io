---
title: "Deployment and different modes"
permalink: /portfolio/deployment
excerpt: "Deployment"
header:
  image: /assets/images/architecture/deployment_header.jpg
  teaser: /assets/images/architecture/deployment_teaser.jpg
sidebar:
  title: ""
  nav: sidebar-deployment

---
RS-Server offers several targets for deployment:
- cluster
- local
- hybrid

For each kind of deployment, here are the overall associated features:

## Cluster mode
On the **cluster  mode**, the RS-Server is deployed as several Kubernetes PODs. A deployment with HELM chart is provided. 
On the cluster environement, RS-Server can be called from a Prefect chain or directy from a Jupyter notebook.
The RS-Server running the cluster has got a strong access control for each sensitive data access (CADIP, LTA, AUXIP, PRIP, and Catalog).

## Local mode
On **local mode**, RS-Server deploy a Catalog without access control.

## Hybrid mode
The **hybrid mode** is derived from the two other ones. RS-Server is deployed on both sides: local machine and cluster.
From the local machine, end user can:
- read / write to the local RS-Server catalog
- connect to the RS-Server running on the cluster and access any service which is authorised for.


<span style="color: black; background-color: #1A89DF;">**version 0.1**</span>
What is already in this release ? 
- cluster mode 
- local mode

For the hybrid mode, it is not possible to access the Prefect server running the cluster.


