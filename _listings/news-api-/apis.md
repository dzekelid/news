---
name: "News API \U0001F5DE\uFE0F"
x-slug: news-api-
description: Get live article metadata from a range of sources including BBC News,
  TechCrunch, Huffington Post and more with our free News API.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/26590-news-api.jpg
x-kinRank: "9"
x-alexaRank: "120829"
tags: News
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/news-api-/apis.md
specificationVersion: "0.14"
apis:
- name: News API Top Headlines
  x-api-slug: news-api
  description: This endpoint provides live top and breaking headlines for a country,
    specific category in a country, single source, or multiple sources. You can also
    search with keywords. Articles are sorted by the earliest date published first.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/26590-news-api.jpg
  humanURL: https://newsapi.org
  baseURL: https://newsapi.org/v2//top-headlines/
  tags: News
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/news-api-/topheadlines-get-openapi.md
- name: News API Everything
  x-api-slug: news-api
  description: Search through millions of articles from over 5,000 large and small
    news sources and blogs. This includes breaking news as well as lesser articles.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/26590-news-api.jpg
  humanURL: https://newsapi.org
  baseURL: https://newsapi.org/v2//everything/
  tags: News
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/news-api-/everything-get-openapi.md
- name: News API Sources
  x-api-slug: news-api
  description: This endpoint returns the subset of news publishers that top headlines
    (/v2/top-headlines) are available from. It's mainly a convenience endpoint that
    you can use to keep track of the publishers available on the API, and you can
    pipe it straight through to your users.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/26590-news-api.jpg
  humanURL: https://newsapi.org
  baseURL: https://newsapi.org/v2//sources/
  tags: News
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/news-api-/sources-get-openapi.md
- name: News API
  x-api-slug: news-api
  description: Get live article metadata from a range of sources including BBC News,
    TechCrunch, Huffington Post and more with our free News API.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/26590-news-api.jpg
  humanURL: https://newsapi.org
  baseURL: https://newsapi.org/v2/
  tags: News
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/news-api-/openapi.md
x-common:
- type: x-email
  url: support@newsapi.org
- type: x-twitter
  url: https://twitter.com/NewsAPIorg
- type: x-website
  url: https://newsapi.org
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---