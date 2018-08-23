---
swagger: "2.0"
info:
  title: The Guardian Editions
  description: Retrieves the editions of the Guardian news platform.
  version: v1
host: content.guardianapis.com
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /editions:
    get:
      summary: Editions
      description: Retrieves the editions of the Guardian news platform
      operationId: editions
      responses:
        200:
          description: OK
      tags:
      - news
definitions: []
x-collection-name: The Guardian
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