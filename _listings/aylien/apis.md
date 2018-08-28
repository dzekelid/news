---
name: Aylien
x-slug: aylien
description: Text Analysis API | Natural Language Processing
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20034-aylien.jpg
x-kinRank: "7"
x-alexaRank: "156410"
tags: News
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/aylien/apis.md
specificationVersion: "0.14"
apis:
- name: AYLIEN News API - List Stories
  x-api-slug: stories-get
  description: The stories endpoint is used to return stories based on parameters
    you set in your query. The News API crawler gathers articles in near real-time
    and stores information about them, or metadata. Below you can see all of the query
    parameters, which you can use to narrow down your query.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20034-aylien.jpg
  humanURL: http://aylien.com/
  baseURL: https://api.newsapi.aylien.com//api/v1
  tags: Scraping, Machine Learning, Content, Machine Learning Scraping, Service Level
    Agreement, SaaS, Technology, Enterprise, API Provider, Profiles
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/aylien/stories-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/aylien/stories-get-openapi.md
- name: AYLIEN News API - List related stories
  x-api-slug: related-stories-get
  description: This endpoint is used for finding semantically similar stories based
    on the parameters you provide as inputs. For example, if you want to find stories
    similar to a Tweet or any text extract you input, the related stories endpoint
    will analyze the entities present and the meaning of the text, and find stories
    with a similar meaning. The maximum number of related stories returned is 100.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20034-aylien.jpg
  humanURL: http://aylien.com/
  baseURL: https://api.newsapi.aylien.com//api/v1
  tags: Scraping, Machine Learning, Content, Machine Learning Scraping, Service Level
    Agreement, SaaS, Technology, Enterprise, API Provider, Profiles
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/aylien/related-stories-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/aylien/related-stories-get-openapi.md
- name: AYLIEN News API - List related stories
  x-api-slug: related-stories-post
  description: This endpoint is used for finding semantically similar stories based
    on the parameters you provide as inputs. For example, if you want to find stories
    similar to a Tweet or any text extract you input, the related stories endpoint
    will analyze the entities present and the meaning of the text, and find stories
    with a similar meaning. The maximum number of related stories returned is 100.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20034-aylien.jpg
  humanURL: http://aylien.com/
  baseURL: https://api.newsapi.aylien.com//api/v1
  tags: Scraping, Machine Learning, Content, Machine Learning Scraping, Service Level
    Agreement, SaaS, Technology, Enterprise, API Provider, Profiles
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/aylien/related-stories-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/aylien/related-stories-post-openapi.md
- name: AYLIEN News API - List coverages
  x-api-slug: coverages-get
  description: The coverages endpoint allows you to understand the reach a document
    has had. For example, you can track the coverage of a press release or a Tweet
    based on how many times it has been mentioned in stories.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20034-aylien.jpg
  humanURL: http://aylien.com/
  baseURL: https://api.newsapi.aylien.com//api/v1
  tags: Scraping, Machine Learning, Content, Machine Learning Scraping, Service Level
    Agreement, SaaS, Technology, Enterprise, API Provider, Profiles
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/aylien/coverages-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/aylien/coverages-get-openapi.md
- name: AYLIEN News API - List coverages
  x-api-slug: coverages-post
  description: The coverages endpoint allows you to understand the reach a document
    has had. For example, you can track the coverage of a press release or a Tweet
    based on how many times it has been mentioned in stories.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20034-aylien.jpg
  humanURL: http://aylien.com/
  baseURL: https://api.newsapi.aylien.com//api/v1
  tags: Scraping, Machine Learning, Content, Machine Learning Scraping, Service Level
    Agreement, SaaS, Technology, Enterprise, API Provider, Profiles
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/aylien/coverages-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/aylien/coverages-post-openapi.md
- name: AYLIEN News API - List autocompletes
  x-api-slug: autocompletes-get
  description: The autocompletes endpoint a string of characters provided to it, and
    then returns suggested terms that are the most likely full words or strings. The
    terms returned by the News API are based on parameters the type parameters you
    can see below. For example, if you provide the autocompletes endpoint with the
    term `New York C` and select the type `dbpedia_resources`, the API will return
    links to the DBpedia resources `New_York_City`, `New_York_City_Subway`, `New_York_City_Police_Department`,
    and so on.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20034-aylien.jpg
  humanURL: http://aylien.com/
  baseURL: https://api.newsapi.aylien.com//api/v1
  tags: Scraping, Machine Learning, Content, Machine Learning Scraping, Service Level
    Agreement, SaaS, Technology, Enterprise, API Provider, Profiles
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/aylien/autocompletes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/aylien/autocompletes-get-openapi.md
- name: AYLIEN News API - List time series
  x-api-slug: time-series-get
  description: The time series endpoint allows you to track information contained
    in stories over time. This information can be anything from mentions of a topic
    or entities, sentiment about a topic, or the volume of stories published by a
    source, to name but a few. The full list of parameters is given below. Using the
    [Date Math Syntax](https://newsapi.aylien.com/docs/working-with-dates), you can
    easily set your query to return information from any time period, from the current
    point in time to when the News API started collecting stories. The returned information
    can be rounded to a time also specified by you, for example by setting the results
    into hourly, daily, or weekly data points.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20034-aylien.jpg
  humanURL: http://aylien.com/
  baseURL: https://api.newsapi.aylien.com//api/v1
  tags: Scraping, Machine Learning, Content, Machine Learning Scraping, Service Level
    Agreement, SaaS, Technology, Enterprise, API Provider, Profiles
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/aylien/time-series-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/aylien/time-series-get-openapi.md
- name: AYLIEN News API - List trends
  x-api-slug: trends-get
  description: The trends endpoint allows you to identify the most-mentioned entities,
    concepts and keywords relevant to your query. For example, this endpoint allows
    you to set parameters like a time period, a subject category, or an entity, and
    your request will return the most mentioned entities or keywords that are mentioned
    in relation to your query.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20034-aylien.jpg
  humanURL: http://aylien.com/
  baseURL: https://api.newsapi.aylien.com//api/v1
  tags: Scraping, Machine Learning, Content, Machine Learning Scraping, Service Level
    Agreement, SaaS, Technology, Enterprise, API Provider, Profiles
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/aylien/trends-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/aylien/trends-get-openapi.md
- name: AYLIEN News API - List histograms
  x-api-slug: histograms-get
  description: For the numerical metadata that the News API gathers (such as word
    counts or social shares for example), you can use the histograms endpoint to access
    and display this information. As this endpoint does not return actual stories,
    the results you are given will not count towards your story allowance provided
    by your subscription, so you can effectively query this endpoint free of charge.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20034-aylien.jpg
  humanURL: http://aylien.com/
  baseURL: https://api.newsapi.aylien.com//api/v1
  tags: Scraping, Machine Learning, Content, Machine Learning Scraping, Service Level
    Agreement, SaaS, Technology, Enterprise, API Provider, Profiles
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/aylien/histograms-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/aylien/histograms-get-openapi.md
x-common:
- type: x-blog
  url: http://blog.aylien.com
- type: x-facebook
  url: https://www.facebook.com/aylieninc
- type: x-openapi
  url: https://newsapi.aylien.com/swagger/spec/news-api.json
- type: x-press
  url: http://aylien.com/press
- type: x-api-gallery
  url: http://axa.assistance.api.gallery.streamdata.io
- type: x-blog
  url: http://blog.aylien.com/
- type: x-blog-rss
  url: http://blog.aylien.com/rss
- type: x-crunchbase
  url: https://crunchbase.com/organization/aylien
- type: x-developer
  url: https://newsapi.aylien.com/
- type: x-email
  url: hello@aylien.com
- type: x-github
  url: https://github.com/AYLIEN
- type: x-pricing
  url: https://newsapi.aylien.com/pricing
- type: x-service-level-agreement
  url: http://aylien.com/text-api-sla
- type: x-twitter
  url: https://twitter.com/_aylien
- type: x-website
  url: http://aylien.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---