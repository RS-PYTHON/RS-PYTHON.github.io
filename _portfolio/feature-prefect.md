---
title: "Orchestration"
permalink: /portfolio/prefect
excerpt: "RS uses Prefect as orchestration solution."
header:
  image: /assets/images/architecture/prefect_header.jpg
  teaser: assets/images/architecture/prefect_teaser.jpg
sidebar:
  title: ""
  nav: sidebar-prefect

---

Prefect Open Source version has been choosen as orchestrator for RS Python project. It offers several advantages for managing data pipelines and processing workflows. Here are some key benefits:

1. **Dynamic Pipeline Construction**: Prefect allows you to create complex workflows with ease. Its dynamic pipeline construction enables you to build workflows that adapt to changing requirements.

2. **Parameterized Tasks**: You can configure tasks at runtime using parameters. This flexibility allows for dynamic configuration of workflows, making it easier to handle different scenarios.

3. **Resilient Pipelines**: Prefect provides features like scheduling, retries, scaling, and concurrency control. These help ensure that your pipelines are robust and reliable, even in the face of failures.

4. **Lightweight**: Prefect is lightweight and easy to set up. You can start a local development server with a single command, making it convenient for testing and development².

RS Python provides some already made chain to process copernicus Sentinel chain.

