---
title: OpenAPI Center
subtitle: A tool for helping to manage APIs in Organizations
layout: page
callouts: home_callouts
show_sidebar: true
---

# OpenAPI Center

This is a set of tools composed of Self-hosted Web Application and plugins for communication with the server.  
It's aimed to software developers, testers, project managers and related areas.  

## Basic Idea

The server application is a centralized repository for all APIs from the organization.  
It's fed with support of its plugins, idealy during the build pipeline.  
The other features come on top of that, since we have the OpenAPI stored.  

{% include youtube.html video="PPcUU5CJE9E" %}

Learn more at [Features](features)

## Running

The simplest way to run it is through Docker + Kubernetes, and using helm charts.  

> Pre-requiment: Have docker or other container running, with Kubernetes available

1. Clone (or download as zip) the Ops repository on [Github](https://github.com/OpenAPI-Center/openapi-center)  
    * Alternativally, download the of only the required folder: https://minhaskamal.github.io/DownGit/#/home?url=https://github.com/OpenAPI-Center/openapi-center/tree/master/ops/helm-chart
2. Navigate to `ops/helm-chart`

```shell
helm install openapi-center .\helm-chart\
```

## Code

The source is available at:   
https://github.com/OpenAPI-Center

> Code is still being published 


## WIP

All the documentation (and the project itself) is still under development

