swagger: "2.0"
x-collection-name: eMuseum API docs
x-complete: 1
info:
  title: eMuseum API
  description: developed-in-partnership-with-museums-the-museum-system-makes-capturing-managing-and-accessing-collection-information-quick-and-easy--emuseum-is-a-webbased-software-program-that-integrates-seamlessly-with-tms-and-other-collection-management-systems-to-dynamically-publish-information-to-your-website-intranet-and-kiosks--this-api-delivers-search-information-and-images-from-tms--emuseum-to-gsa-gov-
  version: 1.0.0
host: gsafinearts.pbs.gsa.gov
basePath: /emuseum/api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /search/people:
    get:
      summary: Artists
      description: Search for an artist
      operationId: searchArtists
      x-api-path-slug: searchpeople-get
      responses:
        200:
          description: OK
      tags:
      - Artists
  /id/people/{id}:
    get:
      summary: Artist
      description: Request an artist
      operationId: getArtist
      x-api-path-slug: idpeopleid-get
      responses:
        200:
          description: OK
      tags:
      - Artists
  /id/objects/{id}:
    get:
      summary: Art
      description: Get Art
      operationId: getArt
      x-api-path-slug: idobjectsid-get
      responses:
        200:
          description: OK
      tags:
      - Art
  /collections/all:
    get:
      summary: Collections
      description: Get Collections
      operationId: getCollections
      x-api-path-slug: collectionsall-get
      responses:
        200:
          description: OK
      tags:
      - Collections
  /collections/{id}:
    get:
      summary: Collections
      description: Get Collection
      operationId: getCollection
      x-api-path-slug: collectionsid-get
      responses:
        200:
          description: OK
      tags:
      - Collections
  /search/buildings:
    get:
      summary: Buildings
      description: Search for art by building
      operationId: searchBuildings
      x-api-path-slug: searchbuildings-get
      responses:
        200:
          description: OK
      tags:
      - Buildings
  /id/buildings/{id}:
    get:
      summary: Building
      description: Get Art By Building
      operationId: getBuilding
      x-api-path-slug: idbuildingsid-get
      responses:
        200:
          description: OK
      tags:
      - Buildings
  /search/objects:
    get:
      summary: Art
      description: Seart for art by object
      operationId: searchARt
      x-api-path-slug: searchobjects-get
      responses:
        200:
          description: OK
      tags:
      - Art