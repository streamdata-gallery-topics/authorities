---
name: OpenRouteService
x-slug: openrouteservice
description: OpenStreetMap is the free wiki world map.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/882-openrouteservice.jpg
x-kinRank: "7"
x-alexaRank: "6266"
tags: Authorities
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/authorities/master/_listings/openrouteservice/apis.md
specificationVersion: "0.14"
apis:
- name: AP Metadata Services - Authority
  x-api-slug: dauthorityguid-format-get
  description: Returns a document for the specified authority and format with the
    AP vocabulary data for the  specified term GUID and the subset of the vocabulary
    located below the specified term.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/882-openrouteservice.jpg
  humanURL: http://wiki.openstreetmap.org/wiki/OpenRouteService#ORS_.22API.22
  baseURL: https://cv.ap.org//
  tags: Bicycle, Routes, Directions, Technology, SaaS, Routes, Routes, General Data,
    Relative Data, Service API, Locations, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/authorities/master/_listings/openrouteservice/dauthorityguid-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/authorities/master/_listings/openrouteservice/dauthorityguid-format-get-openapi.md
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