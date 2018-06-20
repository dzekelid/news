---
name: NewsWhip
x-slug: newswhip
description: Understand what social media content resonates with audiences. Centralize
  your social media monitoring and analytics to discover whats driving engagement.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11443-newswhip.jpg
x-kinRank: "8"
x-alexaRank: "97323"
tags: News
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/newswhip/apis.md
specificationVersion: "0.14"
apis:
- name: News Whip API Local
  x-api-slug: news-whip-api
  description: Pull list of localities.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11443-newswhip.jpg
  humanURL: https://www.newswhip.com/
  baseURL: https://api.newswhip.com/v1//local/
  tags: News,Local
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/newswhip/local-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/newswhip/local-get-openapi.md
- name: News Whip API Local
  x-api-slug: news-whip-api
  description: Search local news.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11443-newswhip.jpg
  humanURL: https://www.newswhip.com/
  baseURL: https://api.newswhip.com/v1//local/{city}/All/{time_period}
  tags: News,Local,City,Time,Period
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/newswhip/localcityalltime-period-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/newswhip/localcityalltime-period-get-openapi.md
- name: News Whip API Publisher
  x-api-slug: news-whip-api
  description: Pull publishers.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11443-newswhip.jpg
  humanURL: https://www.newswhip.com/
  baseURL: https://api.newswhip.com/v1//publisher/
  tags: News,Publisher
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/newswhip/publisher-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/newswhip/publisher-get-openapi.md
- name: News Whip API Publisher
  x-api-slug: news-whip-api
  description: Search news by publisiher.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11443-newswhip.jpg
  humanURL: https://www.newswhip.com/
  baseURL: https://api.newswhip.com/v1//publisher/{publisher}/{time_period}
  tags: News,Publisher,Publisher,Time,Period
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/newswhip/publisherpublishertime-period-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/newswhip/publisherpublishertime-period-get-openapi.md
- name: News Whip API Region
  x-api-slug: news-whip-api
  description: Retrieve list of regions
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11443-newswhip.jpg
  humanURL: https://www.newswhip.com/
  baseURL: https://api.newswhip.com/v1//region/
  tags: News,Region
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/newswhip/region-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/newswhip/region-get-openapi.md
- name: News Whip API Region
  x-api-slug: news-whip-api
  description: Search news by region
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11443-newswhip.jpg
  humanURL: https://www.newswhip.com/
  baseURL: https://api.newswhip.com/v1//region/{region}/{category}/{time_period}
  tags: News,Region,Region,Category,Time,Period
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/newswhip/regionregioncategorytime-period-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/newswhip/regionregioncategorytime-period-get-openapi.md
- name: News Whip API
  x-api-slug: news-whip-api
  description: Understand what social media content resonates with audiences. Centralize
    your social media monitoring and analytics to discover whats driving engagement.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11443-newswhip.jpg
  humanURL: https://www.newswhip.com/
  baseURL: https://api.newswhip.com/v1/
  tags: News
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/newswhip/openapi.md
x-common:
- type: x-authentication
  url: http://www.newswhip.com/api-widgets#authentication
- type: x-base
  url: https://api.newswhip.com
- type: x-blog
  url: http://blog.newswhip.com/
- type: x-blog-rss
  url: http://blog.newswhip.com/index.php/feed
- type: x-crunchbase
  url: https://crunchbase.com/organization/newswhip
- type: x-crunchbase
  url: http://www.crunchbase.com/organization/newswhip
- type: x-email
  url: contact@newswhip.com
- type: x-faq
  url: https://spike.newswhip.com/faq
- type: x-pricing
  url: https://spike.newswhip.com/pricing/team
- type: x-terms-of-service
  url: http://www.newswhip.com/PrivacyAndLegal
- type: x-twitter
  url: https://twitter.com/NewsWhip
- type: x-website
  url: https://www.newswhip.com/
- type: x-website
  url: http://newswhip.com
- type: x-widgets
  url: http://www.newswhip.com/widgetabout#widget
- type: x-wikipedia-
  url: http://en.wikipedia.org/wiki/NewsWhip
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---