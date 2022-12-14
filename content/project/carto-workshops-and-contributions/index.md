---
title: CARTO - Workshops and Contributions
subtitle: Multiple projects conducted between May 2016 to August 2017 at CARTO
date: 2016-08-17T17:54:33.720Z
summary: ""
draft: false
featured: false
tags:
  - GIS
  - Spatial-Statistics
image:
  filename: featured.png
  focal_point: Smart
  preview_only: false
---
My first contribution to the CARTO environment was to develop materials for the [Carto Academy](https://carto.com/help/tutorials/using-builder/) depicting how to implement and interpret spatial tools on the web GIS platform. This has since been deprecated to accommodate for changes in the version of the current software.

### Carto Camp Meetup workshops

Workshop I

[![space-time](../../voting.gif)](http://bl.ocks.org/mehak-sachdeva/raw/503588cc042fd4b5500128034beae71a/)

As a part of exploring visualization tools I held several workshops at the Carto Camp Meetup. The map above is an implementation of primary election data using leaflet and charts.js. [Link to repository with workshop details](https://github.com/CartoCamp/workshops/tree/master/2016-10-07-Charts-and-interactive-maps)

Workshop II

The maps below were for a two-part collaborative workshop using Citi bike data, Google Maps API (for routing between origin-destination pairs) and d3.js for visualization of routing data. [Link to repository with workshop details](https://github.com/CartoCamp/workshops/tree/master/2017-04-28-carto-camp-routing)

[![space-time](../../citibike.gif)](https://team.carto.com/u/mehak-carto/builder/584986d2-2bb9-11e7-afcc-0e05a8b3e3d7/embed)

![space-time](../../d3-camp.gif)

Other projects

This project is an implementation of API.AI, a natural language interactions platform to make a bot that responds to simple sentences and makes maps. It is driven by a node.js app that extracts a “measure” from the sentence asked, geocodes the city of input, queries that measure for census tracts in the city from CARTO’s Data Observatory and maps it using the Maps API. As a first pass it was an internal slack integration to help train it more and scope further development.

![space-time](../../api-bot.gif)