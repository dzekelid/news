---
swagger: "2.0"
x-collection-name: NewsWhip
x-complete: 0
info:
  title: News Whip API Local
  description: Pull list of localities.
  termsOfService: http://www.newswhip.com/PrivacyAndLegal
  version: v1
host: api.newswhip.com
basePath: v1/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  local/:
    get:
      summary: Local
      description: Pull list of localities.
      operationId: getLocal
      x-api-path-slug: local-get
      parameters:
      - in: query
        name: key
        description: API Key
      responses:
        200:
          description: OK
      tags:
      - News
      - Local
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