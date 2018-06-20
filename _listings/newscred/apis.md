---
name: NewsCred
x-slug: newscred
description: NewsCred is the leading enterprise content marketing company. NewsCred
  delivers content marketing solutions that drive business results for top brands
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/869-newscred.jpg
x-kinRank: "7"
x-alexaRank: "91598"
tags: News
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/newscred/apis.md
specificationVersion: "0.14"
apis:
- name: News Cred Topic Articles
  x-api-slug: news-cred
  description: Returns a list of articles related to the specified topic.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/869-newscred.jpg
  humanURL: http://newscred.com
  baseURL: https://api.newscred.com////topic/{guid]/articles/
  tags: News,Topic,Articles
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/newscred/topicguidarticles-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/newscred/topicguidarticles-get-openapi.md
- name: News Cred Articles
  x-api-slug: news-cred
  description: Returns a list of articles according to the specified set of parameters.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/869-newscred.jpg
  humanURL: http://newscred.com
  baseURL: https://api.newscred.com///articles/
  tags: News,Articles
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/newscred/articles-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/newscred/articles-get-openapi.md
- name: News Cred Author Articles
  x-api-slug: news-cred
  description: Returns articles written by the specified author and matching the given
    query string.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/869-newscred.jpg
  humanURL: http://newscred.com
  baseURL: https://api.newscred.com///author/{guid}/articles/
  tags: News,Author,Articles
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/newscred/authorguidarticles-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/newscred/authorguidarticles-get-openapi.md
- name: News Cred Author Topics
  x-api-slug: news-cred
  description: Gets a list of topics related to an author.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/869-newscred.jpg
  humanURL: http://newscred.com
  baseURL: https://api.newscred.com///author/{guid}/topics/
  tags: News,Author,Topics
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/newscred/authorguidtopics-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/newscred/authorguidtopics-get-openapi.md
- name: News Cred Categories
  x-api-slug: news-cred
  description: Search for categories
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/869-newscred.jpg
  humanURL: http://newscred.com
  baseURL: https://api.newscred.com///categories/
  tags: News,Categories
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/newscred/categories-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/newscred/categories-get-openapi.md
- name: News Cred Category Sources
  x-api-slug: news-cred
  description: Gets a list of sources that write most frequently about the category
    specified by the dashed name
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/869-newscred.jpg
  humanURL: http://newscred.com
  baseURL: https://api.newscred.com///category/dashed-name/sources/
  tags: News,Category,Dashed-name,Sources
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/newscred/categorydashednamesources-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/newscred/categorydashednamesources-get-openapi.md
- name: News Cred Category Topics
  x-api-slug: news-cred
  description: Gets a list of topics within the category specified by the dashed name.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/869-newscred.jpg
  humanURL: http://newscred.com
  baseURL: https://api.newscred.com///category/dashed-name/topics/
  tags: News,Category,Dashed-name,Topics
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/newscred/categorydashednametopics-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/newscred/categorydashednametopics-get-openapi.md
- name: News Cred Category Stories
  x-api-slug: news-cred
  description: Find the top news stories related to a given category. A story is a
    collection of similar articles.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/869-newscred.jpg
  humanURL: http://newscred.com
  baseURL: https://api.newscred.com///category/{category-name]/stories/
  tags: News,Category,Category-name],Stories
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/newscred/categorycategorynamestories-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/newscred/categorycategorynamestories-get-openapi.md
- name: News Cred Category Images
  x-api-slug: news-cred
  description: Gets images related to the specified category.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/869-newscred.jpg
  humanURL: http://newscred.com
  baseURL: https://api.newscred.com///category/{dashed-name}/images/
  tags: News,Category,Dashed-name,Images
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/newscred/categorydashednameimages-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/newscred/categorydashednameimages-get-openapi.md
- name: News Cred Source Articles
  x-api-slug: news-cred
  description: Returns a list of articles provided by the specified source
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/869-newscred.jpg
  humanURL: http://newscred.com
  baseURL: https://api.newscred.com///source/{GUID}/articles/
  tags: News,Source,GUID,Articles
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/newscred/sourceguidarticles-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/newscred/sourceguidarticles-get-openapi.md
- name: News Cred Source Topics
  x-api-slug: news-cred
  description: Returns a list of topics related to the source specified by the given
    GUID.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/869-newscred.jpg
  humanURL: http://newscred.com
  baseURL: https://api.newscred.com///source/{GUID}/topics/
  tags: News,Source,GUID,Topics
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/newscred/sourceguidtopics-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/newscred/sourceguidtopics-get-openapi.md
- name: News Cred Sources
  x-api-slug: news-cred
  description: Search sources by name. Returns a list of sources objects
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/869-newscred.jpg
  humanURL: http://newscred.com
  baseURL: https://api.newscred.com///sources/
  tags: News,Sources
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/newscred/sources-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/newscred/sources-get-openapi.md
- name: News Cred Stories
  x-api-slug: news-cred
  description: Returns the top stories related to the specified query. A story is
    a group of similar articles. By default, stories are sorted by a combination of
    recency and importance. If the from_date and/or to_date parameters are specified,
    stories are sorted by importance only.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/869-newscred.jpg
  humanURL: http://newscred.com
  baseURL: https://api.newscred.com///stories/
  tags: News,Stories
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/newscred/stories-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/newscred/stories-get-openapi.md
- name: News Cred Topic Images
  x-api-slug: news-cred
  description: Returns images related to the specified topic.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/869-newscred.jpg
  humanURL: http://newscred.com
  baseURL: https://api.newscred.com///topic/{guide{/images/
  tags: News,Topice,Images
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/newscred/topicguideimages-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/newscred/topicguideimages-get-openapi.md
- name: News Cred Topic
  x-api-slug: news-cred
  description: Return the topic specified by the given GUID.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/869-newscred.jpg
  humanURL: http://newscred.com
  baseURL: https://api.newscred.com///topic/{guid}/
  tags: News,Topic
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/newscred/topicguid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/newscred/topicguid-get-openapi.md
- name: News Cred Topic Sources
  x-api-slug: news-cred
  description: The guid for the topic.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/869-newscred.jpg
  humanURL: http://newscred.com
  baseURL: https://api.newscred.com///topic/{guid}/sources/
  tags: News,Topic,Sources
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/newscred/topicguidsources-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/newscred/topicguidsources-get-openapi.md
- name: News Cred Related Topics
  x-api-slug: news-cred
  description: Returns a list of topics related to the topic specified.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/869-newscred.jpg
  humanURL: http://newscred.com
  baseURL: https://api.newscred.com///topic/{guid}/topics/
  tags: News,Topic,Topics
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/newscred/topicguidtopics-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/newscred/topicguidtopics-get-openapi.md
- name: News Cred Related Tweets
  x-api-slug: news-cred
  description: Returns a list of real-time tweets related to the specified topic.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/869-newscred.jpg
  humanURL: http://newscred.com
  baseURL: https://api.newscred.com///topic/{guid}/tweets/
  tags: News,Topic,Tweets
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/newscred/topicguidtweets-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/newscred/topicguidtweets-get-openapi.md
- name: News Cred Topic Videos
  x-api-slug: news-cred
  description: Returns a list of videos related to the specified topic.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/869-newscred.jpg
  humanURL: http://newscred.com
  baseURL: https://api.newscred.com///topic/{guid}/videos/
  tags: News,Topic,Videos
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/newscred/topicguidvideos-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/newscred/topicguidvideos-get-openapi.md
- name: News Cred Topic Stories
  x-api-slug: news-cred
  description: Find the top stories that are happening for a given topic. A story
    is a collection of similar articles.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/869-newscred.jpg
  humanURL: http://newscred.com
  baseURL: https://api.newscred.com///topic/{topic_guid}/stories/
  tags: News,Topic,Topic,Stories
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/newscred/topictopic-guidstories-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/newscred/topictopic-guidstories-get-openapi.md
- name: News Cred Search Topics
  x-api-slug: news-cred
  description: Search for a specific topics.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/869-newscred.jpg
  humanURL: http://newscred.com
  baseURL: https://api.newscred.com///topics/
  tags: News,Topics
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/newscred/topics-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/newscred/topics-get-openapi.md
- name: News Cred Extract Related Topics
  x-api-slug: news-cred
  description: Returns a list of topics extracted from the input query.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/869-newscred.jpg
  humanURL: http://newscred.com
  baseURL: https://api.newscred.com///topics/extract/
  tags: News,Topics,Extract
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/newscred/topicsextract-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/newscred/topicsextract-get-openapi.md
- name: News Cred Related Topics
  x-api-slug: news-cred
  description: Given some search criteria, returns a list of topics related to those
    criteria.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/869-newscred.jpg
  humanURL: http://newscred.com
  baseURL: https://api.newscred.com///topics/related/
  tags: News,Topics,Related
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/newscred/topicsrelated-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/newscred/topicsrelated-get-openapi.md
- name: News Cred Videos
  x-api-slug: news-cred
  description: Returns videos matching the given query string
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/869-newscred.jpg
  humanURL: http://newscred.com
  baseURL: https://api.newscred.com///videos/
  tags: News,Videos
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/newscred/videos-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/newscred/videos-get-openapi.md
- name: News Cred
  x-api-slug: news-cred
  description: NewsCred is the leading enterprise content marketing company. NewsCred
    delivers content marketing solutions that drive business results for top brands
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/869-newscred.jpg
  humanURL: http://newscred.com
  baseURL: https://api.newscred.com//
  tags: News
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/news/master/_listings/newscred/openapi.md
x-common:
- type: x-base
  url: http://api.newscred.com
- type: x-blog
  url: http://blog.newscred.com/
- type: x-blog-rss
  url: http://blog.newscred.com/feed/rss/
- type: x-case-studies
  url: http://www.newscred.com/casestudies
- type: x-crunchbase
  url: https://crunchbase.com/organization/newscred
- type: x-crunchbase
  url: http://www.crunchbase.com/company/newscred
- type: x-developer
  url: http://www.newscred.com/developer/docs
- type: x-drupal-plugin
  url: http://www.newscred.com/developer/drupal_integration
- type: x-email
  url: legal@newscred.com
- type: x-email
  url: sales@newscred.com
- type: x-faq
  url: http://www.newscred.com/developer/faq
- type: x-github
  url: https://github.com/newscred
- type: x-pricing
  url: http://newscred.com/pricing
- type: x-privacy
  url: http://www.newscred.com/legal/privacy
- type: x-selfservice-registration
  url: http://www.newscred.com/developer/accesskey
- type: x-terms-of-service
  url: http://www.newscred.com/legal/tos
- type: x-twitter
  url: https://twitter.com/newscred
- type: x-website
  url: http://newscred.com
- type: x-website
  url: https://newscred.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---