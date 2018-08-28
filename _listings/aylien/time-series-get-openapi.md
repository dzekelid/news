---
swagger: "2.0"
x-collection-name: Aylien
x-complete: 0
info:
  title: Aylien List time series
  description: The time series endpoint allows you to track information contained
    in stories over time. This information can be anything from mentions of a topic
    or entities, sentiment about a topic, or the volume of stories published by a
    source, to name but a few. The full list of parameters is given below. Using the
    [Date Math Syntax](https://newsapi.aylien.com/docs/working-with-dates), you can
    easily set your query to return information from any time period, from the current
    point in time to when the News API started collecting stories. The returned information
    can be rounded to a time also specified by you, for example by setting the results
    into hourly, daily, or weekly data points.
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
  /related_stories:
    get:
      summary: List related stories
      description: This endpoint is used for finding semantically similar stories
        based on the parameters you provide as inputs. For example, if you want to
        find stories similar to a Tweet or any text extract you input, the related
        stories endpoint will analyze the entities present and the meaning of the
        text, and find stories with a similar meaning. The maximum number of related
        stories returned is 100.
      operationId: listRelatedStories
      x-api-path-slug: related-stories-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - News
      - List
      - Related
      - Stories
    post:
      summary: List related stories
      description: This endpoint is used for finding semantically similar stories
        based on the parameters you provide as inputs. For example, if you want to
        find stories similar to a Tweet or any text extract you input, the related
        stories endpoint will analyze the entities present and the meaning of the
        text, and find stories with a similar meaning. The maximum number of related
        stories returned is 100.
      operationId: listRelatedStoriesAsPost
      x-api-path-slug: related-stories-post
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - News
      - List
      - Related
      - Stories
  /coverages:
    get:
      summary: List coverages
      description: The coverages endpoint allows you to understand the reach a document
        has had. For example, you can track the coverage of a press release or a Tweet
        based on how many times it has been mentioned in stories.
      operationId: listCoverages
      x-api-path-slug: coverages-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - News
      - List
      - Coverages
    post:
      summary: List coverages
      description: The coverages endpoint allows you to understand the reach a document
        has had. For example, you can track the coverage of a press release or a Tweet
        based on how many times it has been mentioned in stories.
      operationId: listCoveragesAsPost
      x-api-path-slug: coverages-post
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - News
      - List
      - Coverages
  /autocompletes:
    get:
      summary: List autocompletes
      description: The autocompletes endpoint a string of characters provided to it,
        and then returns suggested terms that are the most likely full words or strings.
        The terms returned by the News API are based on parameters the type parameters
        you can see below. For example, if you provide the autocompletes endpoint
        with the term `New York C` and select the type `dbpedia_resources`, the API
        will return links to the DBpedia resources `New_York_City`, `New_York_City_Subway`,
        `New_York_City_Police_Department`, and so on.
      operationId: listAutocompletes
      x-api-path-slug: autocompletes-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - News
      - List
      - Autocompletes
  /time_series:
    get:
      summary: List time series
      description: The time series endpoint allows you to track information contained
        in stories over time. This information can be anything from mentions of a
        topic or entities, sentiment about a topic, or the volume of stories published
        by a source, to name but a few. The full list of parameters is given below.
        Using the [Date Math Syntax](https://newsapi.aylien.com/docs/working-with-dates),
        you can easily set your query to return information from any time period,
        from the current point in time to when the News API started collecting stories.
        The returned information can be rounded to a time also specified by you, for
        example by setting the results into hourly, daily, or weekly data points.
      operationId: listTimeSeries
      x-api-path-slug: time-series-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - News
      - List
      - Time
      - Series
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