---
swagger: "2.0"
x-collection-name: Aylien
x-complete: 0
info:
  title: Aylien List Stories
  description: The stories endpoint is used to return stories based on parameters
    you set in your query. The News API crawler gathers articles in near real-time
    and stores information about them, or metadata. Below you can see all of the query
    parameters, which you can use to narrow down your query.
  termsOfService: https://newsapi.aylien.com/tos
  contact:
    name: API support
    url: https://newsapi.aylien.com/
    email: support@aylien.com
  version: 1.0.0
host: api.newsapi.aylien.com
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /stories:
    get:
      summary: List Stories
      description: The stories endpoint is used to return stories based on parameters
        you set in your query. The News API crawler gathers articles in near real-time
        and stores information about them, or metadata. Below you can see all of the
        query parameters, which you can use to narrow down your query.
      operationId: listStories
      x-api-path-slug: stories-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - News
      - List
      - Stories
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