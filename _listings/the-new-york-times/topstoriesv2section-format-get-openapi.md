---
swagger: "2.0"
x-collection-name: The New York Times
x-complete: 0
info:
  title: New York Times Top Stories
  description: The Top Stories API returns a list of articles and associated images
    currently on the specified section.  Support JSON and JSONP.
  termsOfService: https://developer.nytimes.com/tou
  version: 2.0.0
host: api.nytimes.com
basePath: /svc
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /topstories/v2/{section}.{format}:
    get:
      summary: Top Stories
      description: The Top Stories API returns a list of articles and associated images
        currently on the specified section.  Support JSON and JSONP.
      operationId: the-top-stories-api-returns-a-list-of-articles-and-associated-images-currently-on-the-specified-sect
      x-api-path-slug: topstoriesv2section-format-get
      parameters:
      - in: query
        name: callback
        description: The name of the function the API call results will be passed
          to
      - in: path
        name: format
        description: if this is JSONP or JSON
      - in: path
        name: section
        description: The section the story appears in
      responses:
        200:
          description: OK
      tags:
      - News
x-streamrank:
  polling_total_time_average: "0.13"
  polling_size_download_average: "102272.54"
  streaming_total_time_average: "0.08"
  streaming_size_download_average: "51159.62"
  change_yes: "115"
  change_no: "2012"
  time_percentage: "34"
  size_percentage: "50"
  change_percentage: "5"
  last_run: "2018-05-12"
  days_run: "7"
  minute_run: "0"
---