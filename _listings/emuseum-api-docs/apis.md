---
name: eMuseum API docs
x-slug: emuseum-api-docs
description: Developed in partnership with museums, The Museum System makes capturing,
  managing and accessing collection information quick and easy. eMuseum is a web-based
  software program that integrates seamlessly with TMS and other collection management
  systems to dynamically publish information to your website, Intranet, and kiosks.
  This API delivers search information and images from TMS &amp; eMuseum to GSA.gov.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eMuseum5_Blog.jpg
x-kinRank: "8"
x-alexaRank: "0"
tags: eMuseum API docs
created: "2018-08-30"
modified: "2018-08-30"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/emuseum-api-docs/master/_listings/emuseum-api-docs/apis.md
specificationVersion: "0.14"
apis:
- name: eMuseum API - Artists
  x-api-slug: searchpeople-get
  description: Search for an artist
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eMuseum5_Blog.jpg
  humanURL: http://gsa.github.io/eMuseum-API/
  baseURL: https://gsafinearts.pbs.gsa.gov//emuseum/api
  tags: Federal Government   GSA, API Provider, Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/emuseum-api-docs/master/_listings/emuseum-api-docs/searchpeople-get-openapi.md
- name: eMuseum API - Artist
  x-api-slug: idpeopleid-get
  description: Request an artist
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eMuseum5_Blog.jpg
  humanURL: http://gsa.github.io/eMuseum-API/
  baseURL: https://gsafinearts.pbs.gsa.gov//emuseum/api
  tags: Federal Government   GSA, API Provider, Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/emuseum-api-docs/master/_listings/emuseum-api-docs/idpeopleid-get-openapi.md
- name: eMuseum API - Art
  x-api-slug: idobjectsid-get
  description: Get Art
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eMuseum5_Blog.jpg
  humanURL: http://gsa.github.io/eMuseum-API/
  baseURL: https://gsafinearts.pbs.gsa.gov//emuseum/api
  tags: Federal Government   GSA, API Provider, Profiles, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/emuseum-api-docs/master/_listings/emuseum-api-docs/idobjectsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/emuseum-api-docs/master/_listings/emuseum-api-docs/idobjectsid-get-openapi.md
- name: eMuseum API - Collections
  x-api-slug: collectionsall-get
  description: Get Collections
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eMuseum5_Blog.jpg
  humanURL: http://gsa.github.io/eMuseum-API/
  baseURL: https://gsafinearts.pbs.gsa.gov//emuseum/api
  tags: Federal Government   GSA, API Provider, Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/emuseum-api-docs/master/_listings/emuseum-api-docs/collectionsall-get-openapi.md
- name: eMuseum API - Collections
  x-api-slug: collectionsid-get
  description: Get Collection
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eMuseum5_Blog.jpg
  humanURL: http://gsa.github.io/eMuseum-API/
  baseURL: https://gsafinearts.pbs.gsa.gov//emuseum/api
  tags: Federal Government   GSA, API Provider, Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/emuseum-api-docs/master/_listings/emuseum-api-docs/collectionsid-get-openapi.md
- name: eMuseum API - Buildings
  x-api-slug: searchbuildings-get
  description: Search for art by building
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eMuseum5_Blog.jpg
  humanURL: http://gsa.github.io/eMuseum-API/
  baseURL: https://gsafinearts.pbs.gsa.gov//emuseum/api
  tags: Federal Government   GSA, API Provider, Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/emuseum-api-docs/master/_listings/emuseum-api-docs/searchbuildings-get-openapi.md
- name: eMuseum API - Building
  x-api-slug: idbuildingsid-get
  description: Get Art By Building
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eMuseum5_Blog.jpg
  humanURL: http://gsa.github.io/eMuseum-API/
  baseURL: https://gsafinearts.pbs.gsa.gov//emuseum/api
  tags: Federal Government   GSA, API Provider, Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/emuseum-api-docs/master/_listings/emuseum-api-docs/idbuildingsid-get-openapi.md
- name: eMuseum API - Art
  x-api-slug: searchobjects-get
  description: Seart for art by object
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eMuseum5_Blog.jpg
  humanURL: http://gsa.github.io/eMuseum-API/
  baseURL: https://gsafinearts.pbs.gsa.gov//emuseum/api
  tags: Federal Government   GSA, API Provider, Profiles, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/emuseum-api-docs/master/_listings/emuseum-api-docs/searchobjects-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/emuseum-api-docs/master/_listings/emuseum-api-docs/searchobjects-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://elastic.email.api.gallery.streamdata.io
- type: x-api-stack
  url: http://emuseum.api.docs.stack.network
- type: x-issues-page
  url: https://github.com/GSA/eMuseum-API/issues
- type: x-website
  url: http://gsa.github.io/eMuseum-API/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---