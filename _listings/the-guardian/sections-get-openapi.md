---
swagger: "2.0"
x-collection-name: The Guardian
x-complete: 0
info:
  title: The Guardian Sections
  description: Retrieves the sections used across the Guardian news platform.
  version: v1
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
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---