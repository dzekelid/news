swagger: "2.0"
x-collection-name: The Guardian
x-complete: 1
info:
  title: The Guardian
  version: 1.0.0
host: content.guardianapis.com
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /search:
    get:
      summary: Search
      description: Searches news content across the Guardian news platform.
      operationId: search
      x-api-path-slug: search-get
      responses:
        200:
          description: OK
      tags:
      - News
  /sections:
    get:
      summary: Sections
      description: Retrieves the sections used across the Guardian news platform.
      operationId: sections
      x-api-path-slug: sections-get
      responses:
        200:
          description: OK
      tags:
      - News
  /editions:
    get:
      summary: Editions
      description: Retrieves the editions of the Guardian news platform.
      operationId: editions
      x-api-path-slug: editions-get
      responses:
        200:
          description: OK
      tags:
      - News