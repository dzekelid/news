---
swagger: "2.0"
x-collection-name: New York Times
x-complete: 0
info:
  title: New York Times Best Seller List
  description: The Books API has services for getting information about The New York
    Times Best Sellers Lists and Book Reviews.
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
  /search/v2/articlesearch.json:
    get:
      summary: Article Search
      description: Article SearchWith the Article Search API, you can search New York
        Times articles from Sept. 18, 1851 to today, retrieving headlines, abstracts,
        lead paragraphs, links to associated multimedia and other article.
      operationId: article-search-requests-use-the-following-uri-structure
      x-api-path-slug: searchv2articlesearch-json-get
      parameters:
      - in: query
        name: api-key
        description: The API key
        type: string
        format: string
      - in: query
        name: begin_date
        description: 'Format: YYYYMMDD Restricts responses to results with publication
          dates of the date specified or later'
      - in: query
        name: end_date
        description: 'Format: YYYYMMDD Restricts responses to results with publication
          dates of the date specified or earlier'
      - in: query
        name: facet_field
        description: Comma-delimited list of facetsSpecifies the sets of facet values
          to include in the facets array at the end of response, which collects the
          facet values from all the search results
      - in: query
        name: facet_filter
        description: When set to true, facet counts will respect any applied filters
          (fq, date range, etc
      - in: query
        name: fl
        description: Comma-delimited list of fields (no limit)  Limits the fields
          returned in your search results
      - in: query
        name: fq
        description: Filtered search query using standard Lucene syntax
      - in: query
        name: hl
        description: Enables highlighting in search results
      - in: query
        name: page
        description: The value of page corresponds to a set of 10 results (it does
          not indicate the starting number of the result set)
      - in: query
        name: q
        description: Search query term
      - in: query
        name: sort
        description: By default, search results are sorted by their relevance to the
          query term (q)
      responses:
        200:
          description: OK
      tags:
      - News
  /books/v2/lists.{format}:
    get:
      summary: Best Seller List
      description: The Books API has services for getting information about The New
        York Times Best Sellers Lists and Book Reviews.
      operationId: GET_lists-format
      x-api-path-slug: booksv2lists-format-get
      parameters:
      - in: query
        name: bestsellers-date
        description: YYYY-MM-DDThe week-ending date for the sales reflected on list-name
      - in: query
        name: date
        description: YYYY-MM-DD  The date the best-seller list was published on NYTimes
      - in: path
        name: format
        description: The format
        type: string
        format: string
      - in: query
        name: isbn
        description: International Standard Book Number, 10 or 13 digits
      - in: query
        name: list
        description: The name of the Times best-seller list
      - in: query
        name: offset
        description: Sets the starting point of the result set
      - in: query
        name: published-date
        description: YYYY-MM-DDThe date the best-seller list was published on NYTimes
      - in: query
        name: rank
        description: The rank of the best seller on list-name as of bestsellers-date
      - in: query
        name: rank-last-week
        description: The rank of the best seller on list-name one week prior to bestsellers-date
      - in: query
        name: sort-order
        description: Sets the sort order of the result set
      - in: query
        name: weeks-on-list
        description: The number of weeks that the best seller has been on list-name,
          as of bestsellers-date
      responses:
        200:
          description: OK
      tags:
      - News
      - Lists
x-streamrank:
  polling_total_time_average: "0.12"
  polling_size_download_average: "14702.92"
  streaming_total_time_average: "0.07"
  streaming_size_download_average: "7358.57"
  change_yes: "4"
  change_no: "2148"
  time_percentage: "40"
  size_percentage: "50"
  change_percentage: "0"
  last_run: "2018-05-12"
  days_run: "7"
  minute_run: "0"
---