{
  "info": {
    "name": "Aylien List coverages",
    "_postman_id": "fa6634f0-7324-472e-ab67-e94263b49555",
    "description": "The coverages endpoint allows you to understand the reach a document has had. For example, you can track the coverage of a press release or a Tweet based on how many times it has been mentioned in stories.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "News",
      "item": [
        {
          "id": "4fc209ef-ffaa-41e8-8efa-5520e1973609",
          "name": "listStories",
          "request": {
            "url": "http://api.newsapi.aylien.com/api/v1/stories?No Name=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "The stories endpoint is used to return stories based on parameters you set in your query. The News API crawler gathers articles in near real-time and stores information about them, or metadata. Below you can see all of the query parameters, which you can use to narrow down your query."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9f006aa7-935b-476d-bc8a-ba6a78af13bc"
            }
          ]
        },
        {
          "id": "036098a1-3949-4736-a2d7-e845f472fb06",
          "name": "listRelatedStories",
          "request": {
            "url": "http://api.newsapi.aylien.com/api/v1/related_stories?No Name=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "This endpoint is used for finding semantically similar stories based on the parameters you provide as inputs. For example, if you want to find stories similar to a Tweet or any text extract you input, the related stories endpoint will analyze the entities present and the meaning of the text, and find stories with a similar meaning. The maximum number of related stories returned is 100."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bb8578f2-a145-4d75-a012-41c2ee1719da"
            }
          ]
        },
        {
          "id": "b27750d4-2c04-4eed-b9a6-979c34dc9329",
          "name": "listRelatedStoriesAsPost",
          "request": {
            "url": "http://api.newsapi.aylien.com/api/v1/related_stories?No Name=%7B%7D",
            "method": "POST",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "This endpoint is used for finding semantically similar stories based on the parameters you provide as inputs. For example, if you want to find stories similar to a Tweet or any text extract you input, the related stories endpoint will analyze the entities present and the meaning of the text, and find stories with a similar meaning. The maximum number of related stories returned is 100."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f63a98db-b225-47d9-9a05-b1252715bb53"
            }
          ]
        },
        {
          "id": "91e6cd2e-8325-47b4-a9dd-e7439552c2fe",
          "name": "listCoverages",
          "request": {
            "url": "http://api.newsapi.aylien.com/api/v1/coverages?No Name=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "The coverages endpoint allows you to understand the reach a document has had. For example, you can track the coverage of a press release or a Tweet based on how many times it has been mentioned in stories."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2d38e41c-c038-4575-8df9-326e029804ea"
            }
          ]
        }
      ]
    }
  ]
}