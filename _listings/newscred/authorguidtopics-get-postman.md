{
  "info": {
    "name": "News Cred Author Topics",
    "_postman_id": "f33be910-f38e-40ff-acc2-df9c9782cc12",
    "description": "Gets a list of topics related to an author.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "News",
      "item": [
        {
          "id": "c16184fe-01d2-43a7-820d-63397f1547a7",
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
              "id": "5505a376-b219-4667-b0d2-cfbf1b39dd9c"
            }
          ]
        },
        {
          "id": "c021001b-bf37-4901-afeb-0c43f2c53edc",
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
              "id": "4d552ef3-cbfd-4f59-93fe-8d5211d99fcc"
            }
          ]
        },
        {
          "id": "f8904401-30dc-474d-a1bb-5720c66a6c8c",
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
              "id": "fd4f12bb-7684-417d-ab13-e8fa4850eaf8"
            }
          ]
        },
        {
          "id": "ea8482d9-10b7-41e8-bb27-7f77c4276669",
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
              "id": "6492c34f-b830-4978-8624-1a2a8cc3660f"
            }
          ]
        }
      ]
    }
  ]
}