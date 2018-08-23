---
swagger: "2.0"
x-collection-name: Spreaker
x-complete: 0
info:
  title: Spreaker API Newsfeed
  version: v1
  description: This API returns a list of newsfeed items. The request MUST be authenticated
    (an user can only fetch its own newsfeed).
host: api.spreaker.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /user/{user_id}/newsfeed:
    get:
      summary: Newsfeed
      description: This API returns a list of newsfeed items. The request MUST be
        authenticated (an user can only fetch its own newsfeed).
      operationId: getUserUserNewsfeed
      x-api-path-slug: useruser-idnewsfeed-get
      parameters:
      - in: query
        name: last_id
        description: The last newsfeed item received in the previous request, so that
          this request will contains immediately subsequent items
      - in: query
        name: max_per_page
        description: Max number of items in the response
      - in: path
        name: user_id
        description: The user id
      responses:
        200:
          description: OK
      tags:
      - Newsfeed
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