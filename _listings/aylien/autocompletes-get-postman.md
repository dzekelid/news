{
  "info": {
    "name": "Aylien List autocompletes",
    "_postman_id": "af96acf6-c20f-491d-bab9-82591727fbcc",
    "description": "The autocompletes endpoint a string of characters provided to it, and then returns suggested terms that are the most likely full words or strings. The terms returned by the News API are based on parameters the type parameters you can see below. For example, if you provide the autocompletes endpoint with the term `New York C` and select the type `dbpedia_resources`, the API will return links to the DBpedia resources `New_York_City`, `New_York_City_Subway`, `New_York_City_Police_Department`, and so on.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "News",
      "item": [
        {
          "id": "5c44e5b1-529f-48d8-b28f-c5899a8f6f9d",
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
              "id": "123b43ef-42a3-4daf-b16c-3604def9c891"
            }
          ]
        },
        {
          "id": "9bf0f0ff-4b49-4578-842f-0ec1ca4e1835",
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
              "id": "50b28179-4c7c-4934-ad9e-d16ed4467667"
            }
          ]
        },
        {
          "id": "eae11870-19a5-43d9-a126-fdec2fa563da",
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
              "id": "939fd06a-cd0f-49dc-928b-934a4075be3a"
            }
          ]
        },
        {
          "id": "493c25dc-f590-4630-91ae-a847f2ead82e",
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
              "id": "f3818e1f-36a5-41e6-8359-40c0ffea77b2"
            }
          ]
        },
        {
          "id": "82b43562-cc9c-40e6-baf6-bb0a76df85e9",
          "name": "listCoveragesAsPost",
          "request": {
            "url": "http://api.newsapi.aylien.com/api/v1/coverages?No Name=%7B%7D",
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
            "description": "The coverages endpoint allows you to understand the reach a document has had. For example, you can track the coverage of a press release or a Tweet based on how many times it has been mentioned in stories."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f5c7e244-5fc0-4c50-92fb-89ca32546725"
            }
          ]
        },
        {
          "id": "180f93a6-010c-48dd-a018-5e817a92ea64",
          "name": "listAutocompletes",
          "request": {
            "url": "http://api.newsapi.aylien.com/api/v1/autocompletes?No Name=%7B%7D",
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
            "description": "The autocompletes endpoint a string of characters provided to it, and then returns suggested terms that are the most likely full words or strings. The terms returned by the News API are based on parameters the type parameters you can see below. For example, if you provide the autocompletes endpoint with the term `New York C` and select the type `dbpedia_resources`, the API will return links to the DBpedia resources `New_York_City`, `New_York_City_Subway`, `New_York_City_Police_Department`, and so on."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a3b4fd99-bdcd-45d0-a5eb-f8a75b18629c"
            }
          ]
        }
      ]
    }
  ]
}