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
x-alexaRank: ""
tags: eMuseum API docs
created: "2018-05-21"
modified: "2018-05-21"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/emuseum-api-docs/master/_listings/emuseum-api-docs/apis.md
specificationVersion: "0.14"
apis:
- name: eMuseum API Artists
  x-api-slug: emuseum-api
  description: Search for an artist
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eMuseum5_Blog.jpg
  humanURL: http://gsa.github.io/eMuseum-API/
  baseURL: https://gsafinearts.pbs.gsa.gov//emuseum/api//search/people
  tags: Artists
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/emuseum-api-docs/master/_listings/emuseum-api-docs/searchpeople-get-openapi.md
- name: eMuseum API Artist
  x-api-slug: emuseum-api
  description: Request an artist
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eMuseum5_Blog.jpg
  humanURL: http://gsa.github.io/eMuseum-API/
  baseURL: https://gsafinearts.pbs.gsa.gov//emuseum/api//id/people/{id}
  tags: Artists
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/emuseum-api-docs/master/_listings/emuseum-api-docs/idpeopleid-get-openapi.md
- name: eMuseum API Art
  x-api-slug: emuseum-api
  description: Get Art
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eMuseum5_Blog.jpg
  humanURL: http://gsa.github.io/eMuseum-API/
  baseURL: https://gsafinearts.pbs.gsa.gov//emuseum/api//id/objects/{id}
  tags: Art
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/emuseum-api-docs/master/_listings/emuseum-api-docs/idobjectsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/emuseum-api-docs/master/_listings/emuseum-api-docs/idobjectsid-get-openapi.md
- name: eMuseum API Collections
  x-api-slug: emuseum-api
  description: Get Collections
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eMuseum5_Blog.jpg
  humanURL: http://gsa.github.io/eMuseum-API/
  baseURL: https://gsafinearts.pbs.gsa.gov//emuseum/api//collections/all
  tags: Collections
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/emuseum-api-docs/master/_listings/emuseum-api-docs/collectionsall-get-openapi.md
- name: eMuseum API Collections
  x-api-slug: emuseum-api
  description: Get Collection
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eMuseum5_Blog.jpg
  humanURL: http://gsa.github.io/eMuseum-API/
  baseURL: https://gsafinearts.pbs.gsa.gov//emuseum/api//collections/{id}
  tags: Collections
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/emuseum-api-docs/master/_listings/emuseum-api-docs/collectionsid-get-openapi.md
- name: eMuseum API Buildings
  x-api-slug: emuseum-api
  description: Search for art by building
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eMuseum5_Blog.jpg
  humanURL: http://gsa.github.io/eMuseum-API/
  baseURL: https://gsafinearts.pbs.gsa.gov//emuseum/api//search/buildings
  tags: Buildings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/emuseum-api-docs/master/_listings/emuseum-api-docs/searchbuildings-get-openapi.md
- name: eMuseum API Building
  x-api-slug: emuseum-api
  description: Get Art By Building
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eMuseum5_Blog.jpg
  humanURL: http://gsa.github.io/eMuseum-API/
  baseURL: https://gsafinearts.pbs.gsa.gov//emuseum/api//id/buildings/{id}
  tags: Buildings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/emuseum-api-docs/master/_listings/emuseum-api-docs/idbuildingsid-get-openapi.md
- name: eMuseum API Art
  x-api-slug: emuseum-api
  description: Seart for art by object
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eMuseum5_Blog.jpg
  humanURL: http://gsa.github.io/eMuseum-API/
  baseURL: https://gsafinearts.pbs.gsa.gov//emuseum/api//search/objects
  tags: Art
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/emuseum-api-docs/master/_listings/emuseum-api-docs/searchobjects-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/emuseum-api-docs/master/_listings/emuseum-api-docs/searchobjects-get-openapi.md
- name: eMuseum API
  x-api-slug: emuseum-api
  description: Developed in partnership with museums, The Museum System makes capturing,
    managing and accessing collection information quick and easy. eMuseum is a web-based
    software program that integrates seamlessly with TMS and other collection management
    systems to dynamically publish information to your website, Intranet, and kiosks.
    This API delivers search information and images from TMS &amp; eMuseum to GSA.gov.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eMuseum5_Blog.jpg
  humanURL: http://gsa.github.io/eMuseum-API/
  baseURL: https://gsafinearts.pbs.gsa.gov//emuseum/api
  tags: eMuseum API docs
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/emuseum-api-docs/master/_listings/emuseum-api-docs/openapi.md
x-common:
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