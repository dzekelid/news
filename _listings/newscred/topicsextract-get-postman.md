{
  "info": {
    "name": "News Cred Extract Related Topics",
    "_postman_id": "53911dbc-1f95-4f73-964b-d74479b90c87",
    "description": "Returns a list of topics extracted from the input query.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "News",
      "item": [
        {
          "id": "235e74fa-b289-4230-abff-b62dd3ee21fd",
          "name": "getTopicGu]Articles",
          "request": {
            "url": "http://api.newscred.com/topic/{guid]/articles/?access_key=%7B%7D&article_filter_mode=%7B%7D&article_filter_name=%7B%7D&categories=%7B%7D&from_date=%7B%7D&get_topics=%7B%7D&guid=%7B%7D&has_images=%7B%7D&languages=%7B%7D&licensed=%7B%7D&media_types=%7B%7D&offset=%7B%7D&pagesize=%7B%7D&sort=%7B%7D&sources=%7B%7D&source_countries=%7B%7D&source_filter_mode=%7B%7D&source_filter_name=%7B%7D&to_date=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of articles related to the specified topic."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "43c6d79e-c1e2-4a51-9117-6493ad0d3ba0"
            }
          ]
        },
        {
          "id": "06c93475-66da-448a-80c0-d1b76b37617e",
          "name": "getArticles",
          "request": {
            "url": "http://api.newscred.com/articles/?access_key=%7B%7D&article_filter_mode=%7B%7D&article_filter_name=%7B%7D&boolean_operator=%7B%7D&categories=%7B%7D&exact=%7B%7D&from_date=%7B%7D&get_topics=%7B%7D&has_images=%7B%7D&languages=%7B%7D&licensed=%7B%7D&links=%7B%7D&max_length=%7B%7D&media_types=%7B%7D&min_length=%7B%7D&mm=%7B%7D&modified_since=%7B%7D&offset=%7B%7D&query=%7B%7D&query_fields=%7B%7D&safe_search=%7B%7D&sort=%7B%7D&sources=%7B%7D&source_countries=%7B%7D&source_filter_mode=%7B%7D&source_filter_name=%7B%7D&topics=%7B%7D&topic_filter_mode=%7B%7D&topic_filter_name=%7B%7D&to_date=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of articles according to the specified set of parameters."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "96aaf026-dadc-4905-9fd5-055591fb1034"
            }
          ]
        },
        {
          "id": "2e64e3fb-38b1-4fc2-ba92-d06f4a67a642",
          "name": "getAuthorGuArticles",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.newscred.com",
              "path": [
                "author/:guid/articles/"
              ],
              "query": [
                {
                  "key": "access_key",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "article_filter_mode",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "article_filter_name",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "categories",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "from_date",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "get_topics",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "has_images",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "languages",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "licensed",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "media_types",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "offset",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "pagesize",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "sort",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "sources",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "source_countries",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "source_filter_mode",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "source_filter_name",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "topics",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "topic_filter_mode",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "topic_filter_name",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "to_date",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "guid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns articles written by the specified author and matching the given query string."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b1d2ac1c-f1f2-43e8-ba91-4a3b2a77d545"
            }
          ]
        },
        {
          "id": "a9ab234e-19d2-423e-97a6-554667f0f2d1",
          "name": "getAuthorGuTopics",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.newscred.com",
              "path": [
                "author/:guid/topics/"
              ],
              "query": [
                {
                  "key": "access_key",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "from_date",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "offset",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "pagesize",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "topics",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "topic_classifications",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "topic_filter_mode",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "topic_filter_name",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "topic_subclassifications",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "to_date",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "guid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets a list of topics related to an author."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8c2287e4-a5fe-4917-b5e3-e5f548e65cf8"
            }
          ]
        },
        {
          "id": "016ee4dc-c320-460f-9c5f-6d513a6c5c40",
          "name": "getCategories",
          "request": {
            "url": "http://api.newscred.com/categories/?access_key=%7B%7D&autosuggest=%7B%7D&query=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Search for categories"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e63d3f33-c9b0-4725-840b-03cd838172ff"
            }
          ]
        },
        {
          "id": "c4ed4971-353d-4e25-80b1-f8aca4b4aa11",
          "name": "getCategoryDashedNameSources",
          "request": {
            "url": "http://api.newscred.com/category/dashed-name/sources/?access_key=%7B%7D&from_date=%7B%7D&media_types=%7B%7D&offset=%7B%7D&pagesize=%7B%7D&sources=%7B%7D&source_countries=%7B%7D&source_filter_mode=%7B%7D&source_filter_name=%7B%7D&to_date=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets a list of sources that write most frequently about the category specified by the dashed name"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ebc6ae12-bf52-44f8-a276-c2b731c554a5"
            }
          ]
        },
        {
          "id": "19b03cf5-85b2-4a07-bab3-012ed21d3b34",
          "name": "getCategoryDashedNameTopics",
          "request": {
            "url": "http://api.newscred.com/category/dashed-name/topics/?access_key=%7B%7D&from_date=%7B%7D&offset=%7B%7D&pagesize=%7B%7D&topic_classifications=%7B%7D&topic_filter_mode=%7B%7D&topic_filter_name=%7B%7D&topic_subclassifications=%7B%7D&to_date=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets a list of topics within the category specified by the dashed name."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5e43f389-d283-4c1f-a147-d6caf3862178"
            }
          ]
        },
        {
          "id": "4073154e-7be2-4f67-b27f-66f7accda209",
          "name": "getCategoryCategoryName]Stories",
          "request": {
            "url": "http://api.newscred.com/category/{category-name]/stories/?access_key=%7B%7D&article_filter_mode=%7B%7D&article_filter_name=%7B%7D&cluster_size=%7B%7D&from_date=%7B%7D&get_topics=%7B%7D&has_images=%7B%7D&languages=%7B%7D&licensed=%7B%7D&media_types=%7B%7D&offset=%7B%7D&pagesize=%7B%7D&sources=%7B%7D&source_countries=%7B%7D&source_filter_mode=%7B%7D&source_filter_name=%7B%7D&to_date=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Find the top news stories related to a given category. A story is a collection of similar articles."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "07f53df1-c6e8-4bb1-957f-4a31b0ca80d0"
            }
          ]
        },
        {
          "id": "fd0a80d8-7b21-4eac-8b98-3159f7ded40c",
          "name": "getCategoryDashedNameImages",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.newscred.com",
              "path": [
                "category/:dashed-name/images/"
              ],
              "query": [
                {
                  "key": "access_key",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "safe_search",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "dashed-name",
                  "value": "dashed-name",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets images related to the specified category."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1e6ec1a4-8115-4791-8d7f-9f8314931ad1"
            }
          ]
        },
        {
          "id": "6508d229-7731-4913-83f9-b228791be0ad",
          "name": "getSourceGuArticles",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.newscred.com",
              "path": [
                "source/:GUID/articles/"
              ],
              "query": [
                {
                  "key": "access_key",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "article_filter_mode",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "article_filter_name",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "categories",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "from_date",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "get_topics",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "has_images",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "languages",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "licensed",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "media_types",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "offset",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "pagesize",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "sort",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "topics",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "topic_filter_mode",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "topic_filter_name",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "to_date",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "GUID",
                  "value": "GUID",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of articles provided by the specified source"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0b73f639-a13f-4fd5-9cbb-1c68654fd049"
            }
          ]
        },
        {
          "id": "0eb3da4b-311a-4913-b886-f8ea41faaa61",
          "name": "getSourceGuTopics",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.newscred.com",
              "path": [
                "source/:GUID/topics/"
              ],
              "query": [
                {
                  "key": "access_key",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "from_date",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "offset",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "pagesize",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "topics",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "topic_classifications",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "topic_filter_mode",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "topic_filter_name",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "topic_subclassifications",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "to_date",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "GUID",
                  "value": "GUID",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of topics related to the source specified by the given GUID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "be103ff8-c9e5-4b55-8347-49ea1317d79d"
            }
          ]
        },
        {
          "id": "c1e02d15-47c4-4d1a-8a47-aa7581d2cc5b",
          "name": "getSources",
          "request": {
            "url": "http://api.newscred.com/sources/?access_key=%7B%7D&autosuggest=%7B%7D&licensed=%7B%7D&media_types=%7B%7D&query=%7B%7D&sources=%7B%7D&source_countries=%7B%7D&source_filter_mode=%7B%7D&source_filter_name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Search sources by name. Returns a list of sources objects"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "17bc817b-6a0b-4b00-aa71-381206cc137b"
            }
          ]
        },
        {
          "id": "25ebafc5-5424-43c8-8be7-3516f2d631eb",
          "name": "getStories",
          "request": {
            "url": "http://api.newscred.com/stories/?access_key=%7B%7D&article_filter_mode=%7B%7D&article_filter_name=%7B%7D&boolean_operator=%7B%7D&categories=%7B%7D&cluster_size=%7B%7D&exact=%7B%7D&from_date=%7B%7D&get_topics=%7B%7D&has_images=%7B%7D&languages=%7B%7D&licensed=%7B%7D&links=%7B%7D&max_length=%7B%7D&media_types=%7B%7D&min_length=%7B%7D&mm=%7B%7D&modified_since=%7B%7D&offset=%7B%7D&query=%7B%7D&query_fields=%7B%7D&safe_search=%7B%7D&sort=%7B%7D&sources=%7B%7D&source_countries=%7B%7D&source_filter_mode=%7B%7D&source_filter_name=%7B%7D&topics=%7B%7D&topic_filter_mode=%7B%7D&topic_filter_name=%7B%7D&to_date=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the top stories related to the specified query. A story is a group of similar articles. By default, stories are sorted by a combination of recency and importance. If the from_date and/or to_date parameters are specified, stories are sorted by importance only."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "423370cf-e384-4f4e-814e-8733550fcfb2"
            }
          ]
        },
        {
          "id": "f07e7d38-882c-4dc8-8797-ccea5b8b217b",
          "name": "getTopicGueImages",
          "request": {
            "url": "http://api.newscred.com/topic/{guide{/images/?access_key=%7B%7D&guid=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns images related to the specified topic."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6235d1f8-cc28-4a11-950c-006d8cb36db2"
            }
          ]
        },
        {
          "id": "261d45da-9508-43ff-866a-176299b583e8",
          "name": "getTopicGu",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.newscred.com",
              "path": [
                "topic/:guid/"
              ],
              "query": [
                {
                  "key": "access_key",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "guid",
                  "value": "guid",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Return the topic specified by the given GUID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7a483cb1-977a-46f9-83d6-9a4190f9ad31"
            }
          ]
        },
        {
          "id": "280a16c8-b3c3-4ffe-ade0-5c9938aec534",
          "name": "getTopicGuSources",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.newscred.com",
              "path": [
                "topic/:guid/sources/"
              ],
              "query": [
                {
                  "key": "access_key",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "from_date",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "offset",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "pagesize",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "sources",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "source_countries",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "source_filter_mode",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "source_filter_name",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "Topic Sources",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "to_date",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "guid",
                  "value": "guid",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "The guid for the topic."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "01e64178-63e5-4dde-b7cc-133bd0bb9f31"
            }
          ]
        },
        {
          "id": "d0218f4f-1282-4cba-8dff-7febf9fc7ca1",
          "name": "getTopicGuTopics",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.newscred.com",
              "path": [
                "topic/:guid/topics/"
              ],
              "query": [
                {
                  "key": "access_key",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "from_date",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "offset",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "pagesize",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "topics",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "topic_classifications",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "topic_filter_mode",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "topic_filter_name",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "topic_subclassifications",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "to_date",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "guid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of topics related to the topic specified."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "376e59e2-03d3-4642-94cd-7e488b0498d0"
            }
          ]
        },
        {
          "id": "7d5b082d-07b7-46e0-a54f-30afdde7297e",
          "name": "getTopicGuTweets",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.newscred.com",
              "path": [
                "topic/:guid/tweets/"
              ],
              "query": [
                {
                  "key": "access_key",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "offset",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "pagesize",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "guid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of real-time tweets related to the specified topic."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "08f72928-75d9-411e-89ce-b2f7a79baa29"
            }
          ]
        },
        {
          "id": "5ffa35d5-c306-4532-be22-99dd8056f184",
          "name": "getTopicGuVeos",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.newscred.com",
              "path": [
                "topic/:guid/videos/"
              ],
              "query": [
                {
                  "key": "access_key",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "categories",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "offset",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "pagesize",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "guid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of videos related to the specified topic."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4b5e90ed-e4cc-4f18-907b-56c4c953dbe8"
            }
          ]
        },
        {
          "id": "1c5c06a9-b53c-4f71-af28-0d9082ddbdcf",
          "name": "getTopicTopicGuStories",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.newscred.com",
              "path": [
                "topic/:topic_guid/stories/"
              ],
              "query": [
                {
                  "key": "access_key",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "article_filter_mode",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "article_filter_name",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "categories",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "cluster_size",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "from_date",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "get_topics",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "has_images",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "languages",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "licensed",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "media_types",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "offset",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "pagesize",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "sources",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "source_countries",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "source_filter_mode",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "source_filter_name",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "to_date",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "topic_guid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Find the top stories that are happening for a given topic. A story is a collection of similar articles."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "40d75479-8930-4622-a258-19e37f11da4e"
            }
          ]
        },
        {
          "id": "28b340c2-70fd-425b-a38d-ccc2ee7b2ad9",
          "name": "getTopics",
          "request": {
            "url": "http://api.newscred.com/topics/?access_key=%7B%7D&exact=%7B%7D&query=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Search for a specific topics."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "97ce6793-1252-4627-8511-d99ec0d5f647"
            }
          ]
        },
        {
          "id": "a24621a0-b387-4b31-a3f1-8ab224bc8b2f",
          "name": "getTopicsExtract",
          "request": {
            "url": "http://api.newscred.com/topics/extract/?access_key=%7B%7D&query=%7B%7D&topics=%7B%7D&topic_classifications=%7B%7D&topic_filter_mode=%7B%7D&topic_filter_name=%7B%7D&topic_subclassifications=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of topics extracted from the input query."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "61c44539-2583-4f9c-ae5a-91ca1c68d16d"
            }
          ]
        }
      ]
    }
  ]
}