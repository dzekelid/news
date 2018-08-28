---
name: OpenRouteService
x-slug: openrouteservice
description: OpenStreetMap is the free wiki world map.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/882-openrouteservice.jpg
x-kinRank: "7"
x-alexaRank: "6266"
tags: News
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/openrouteservice/apis.md
specificationVersion: "0.14"
apis:
- name: AP Breaking News API - Category News
  x-api-slug: categories-svccategoryid-get
  description: Returns the latest content for a specific category. Depending on the
    specified parameters, returns  either the full story for each headline and/or
    the headlines linked to web pages with the full stories.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/882-openrouteservice.jpg
  humanURL: http://wiki.openstreetmap.org/wiki/OpenRouteService#ORS_.22API.22
  baseURL: https://developerapi.ap.org/v2/
  tags: Bicycle, Routes, Directions, Technology, SaaS, Routes, Routes, General Data,
    Relative Data, Service API, Locations, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/openrouteservice/categories-svccategoryid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/openrouteservice/categories-svccategoryid-get-openapi.md
x-common:
- type: x-website
  url: http://wiki.openstreetmap.org/wiki/OpenRouteService#ORS_.22API.22
- type: x-api-gallery
  url: http://opendns.api.gallery.streamdata.io
- type: x-api-stack
  url: http://openrouteservice.stack.network
- type: x-crunchbase
  url: https://crunchbase.com/organization/openstreetmap-3
- type: x-developer
  url: https://developer.ap.org/
- type: x-website
  url: http://ap.org
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---