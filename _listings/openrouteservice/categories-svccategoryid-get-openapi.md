---
swagger: "2.0"
x-collection-name: OpenRouteService
x-complete: 0
info:
  title: AP Breaking News API Category News
  description: Returns the latest content for a specific category. Depending on the
    specified parameters, returns  either the full story for each headline and/or
    the headlines linked to web pages with the full stories.
  version: v2
host: developerapi.ap.org
basePath: v2/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  categories.svc/{categoryID}/:
    get:
      summary: Category News
      description: Returns the latest content for a specific category. Depending on
        the specified parameters, returns  either the full story for each headline
        and/or the headlines linked to web pages with the full stories.
      operationId: getCategories.svcCategory
      x-api-path-slug: categories-svccategoryid-get
      parameters:
      - in: query
        name: apiKey
        description: API Key
      - in: query
        name: categoryID
        description: The ID of the AP Breaking News category
      - in: query
        name: contentOption
        description: Specifies whether to return full story content in the response
      - in: query
        name: count
        description: The number of content items to be returned
      - in: query
        name: mediaOption
        description: Includes related photos in the response
      responses:
        200:
          description: OK
      tags:
      - Category
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