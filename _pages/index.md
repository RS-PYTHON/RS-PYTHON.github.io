---



title: "RS Python"
layout: splash
permalink: /
date: 2016-03-23T11:48:41-04:00
header:
  overlay_color: "#000"
  overlay_filter: "0.3"
  overlay_image: /assets/images/sentinel/South_Georgia_Island_as_seen_by_Sentinel-2.jpg
  actions:
    - label: "rs-server"
      url: "https://rspy.ops.rs-python.eu/docs"
    - label: "rs-catalog"
      url: "https://stac-browser-catalog.ops.rs-python.eu/"
    - label: "rs-cadip"
      url: "https://stac-browser-cadip.ops.rs-python.eu"
    - label: "rs-auxip"
      url: "https://stac-browser-auxip.ops.rs-python.eu/"
    - label: "processing"
      url: "https://processing.ops.rs-python.eu/dashboard"
    - label: "virtual environment" 
      url: "https://processing.ops.rs-python.eu/jupyter"
    - label: "monitoring"
      url: "https://monitoring.ops.rs-python.eu"

caption: "South Georgia Island as seen by Sentinel-2"
excerpt: 'The Copernicus Space Component Reference System is an open-source software solution allowing to implement, maintain, deploy, operate and monitor Sentinel data processing <b>workflows</b> based on the future re-engineered Level 0, 1, 2 Sentinel Data processors.<br/><br/>
<left>Operational platform available at working hours</left>'

intro: 
feature_row_sentinel:
  - image_path: assets/images/sentinel/Irkutsk_and_Lake_Baikal_ESA15342560.jpeg
    alt: "Irkutsk and Lake Baika Sentinel-1 image"
    title: "Sentinel-1"
#    excerpt: "This is some sample content that goes here with **Markdown** formatting."

  - image_path: /assets/images/sentinel/Lake_MacKay_Australia.jpg
    alt: "Lake MacKay Australia Sentinel-2 image"
    title: "Sentinel-2"
#    url: "#test-link"
#    btn_label: "Read More"
#    btn_class: "btn--primary"

  - image_path: /assets/images/sentinel/1024px-Cloud-free_Europe_ESA17486464.jpeg
    alt: "Europe Sentinel-3 image"
    title: "Sentinel-3"




feature_rsserver:
  - image_path: /assets/images/architecture/rs-server_teaser.jpg
    alt: "RS-Server"
    title: "RS-Server"
    excerpt: "The Reference System server offers essential services for building Copernicus processing workflows, all secured by stringent access controls. With RS-Server, STAC integration is seamless. RS-Server features a comprehensive catalog of Sentinel products, fully compatible with the STAC (SpatioTemporal Asset Catalog) standard. Additionally, it provides STAC interfaces to retrieve AUXIP and CADIP data. A versatile staging function rounds out this robust suite of services."
    url: "/feature/rs-server"
    btn_label: "Read More"
    btn_class: "btn--primary"


feature_staging:
  - image_path: /assets/images/station/staging_teaser.jpg
    alt: "RS-Server external data sources"
    title: "RS-Server staging"
    excerpt: "The rs-server offers staging functionality with access control for retrieving products from external data sources. The rs-server grants access to auxiliary data from the AUXIP station, as well as telemetry raw data from CADIP stations. It will also provide access to Sentinel level-0 products from LTA and Level-1 and Level-2 products from PRIP."
    url: "/feature/staging"
    btn_label: "Read More"
    btn_class: "btn--primary"

feature_prefect:
  - image_path: /assets/images/architecture/prefect_teaser.jpg
    alt: "Workflow as a code"
    title: "Processing workflow as a code"
    excerpt: "RS Python leverages the Prefect orchestrator for managing and automating workflows. Prefect simplifies workflow management, reduces operational costs, and provides a smoother experience for data orchestration compared to other tools. Its flexibility, quick adoption, and supportive community make it an excellent choice for RS’s workflow needs."
    url: "/feature/prefect"
    btn_label: "Read More"
    btn_class: "btn--primary"

    
feature_virtual:
  - image_path: /assets/images/architecture/jup_teaser.jpg
    alt: "Jupyter"
    title: "Virtual environment"
    excerpt: "RS Python provides access to JupyterLab to end-user. The end-user can build or start already made Prefect worflows from rs-client libraries. JupyterLab proposes a flexible workspace organization to users making it easier to work with multiple tabs simultaneously. Additionally, JupyterLab provides a comprehensive Markdown editor, enhancing the writing and documentation experience within notebooks.
    JupyterLab offers a richer and more efficient data programming experience, making it a wise choice for RS."
    url: "/feature/jupyter"
    btn_label: "Read More"
    btn_class: "btn--primary"
    
feature_deployment:
  - image_path: /assets/images/architecture/deployment_teaser.jpg
    alt: "Deployment"
    title: "RS deployment"
    excerpt: "The rs-server can be deployed on several environments. On a Kubernetes cluster or on a local machine. From the local machine it is also possible to access both local Catalog and remote rs-server services."
    url: "/feature/deployment"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}
  
<p align="justify">Reference System Python will  support at first processing chains for Sentinel-1, Sentinel-2, and Sentinel-3 data. </p>   
  
<table>
	<tr>
		<th><img src="/assets/images/sentinel/Irkutsk_and_Lake_Baikal_ESA15342560.jpeg" width="516" height="414"  alt="Irkutsk and Lake Baika Sentinel-1 image"></th>
		<th><img src="/assets/images/sentinel/Lake_MacKay_Australia.jpg" width="516" height="414" alt="Lake MacKay Australia Sentinel-2 image"></th>
		<th><img src="/assets/images/sentinel/1024px-Cloud-free_Europe_ESA17486464.jpeg" width="516" height="414" alt="Europe Sentinel-3 image"></th>
 		
 	</tr>
 	<tr>
  	<td><a href="https://sentinels.copernicus.eu/web/sentinel/copernicus/sentinel-1"><center><b>Sentinel-1</b></center></a><br/><br/></td>
  	<td><a href="https://sentinels.copernicus.eu/web/sentinel/copernicus/sentinel-2"><center><b>Sentinel-2</b></center></a><br/><br/></td>
  	<td><a href="https://sentinels.copernicus.eu/web/sentinel/copernicus/sentinel-3"><center><b>Sentinel-3</b></center></a><br/><br/></td>
  	

 	</tr>
	
</table>




{% include feature_row id="feature_rsserver" type="right" %}

{% include feature_row id="feature_prefect" type="left" %}

{% include feature_row id="feature_virtual" type="right" %}

{% include feature_row id="feature_deployment" type="left" %}

<style type="text/css">
  #conteneur {
    margin-top:0;
    margin-bottom:0;
    text-align: left;
    }
</style>

