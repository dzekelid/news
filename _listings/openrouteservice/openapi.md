swagger: "2.0"
x-collection-name: OpenRouteService
x-complete: 1
info:
  title: AP Metadata Services
  description: add-value-to-your-news-content-with-apu2019s-industryleading-metadata--accurate-comprehensive-richly-detailed-data-designed-specifically-for-use-by-news-publishers--ap-metadata-services-is-a-new-set-of-apis-that-gives-you-direct-access-to-the-same-metadata-system-that-supports-apu2019s-awardwinning-global-news-operation-
  version: v1
host: cv.ap.org
basePath: /
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