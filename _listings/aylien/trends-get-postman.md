{
  "info": {
    "name": "Aylien List trends",
    "_postman_id": "9d40bb51-6a24-420d-bf2d-36d4584c596c",
    "description": "The trends endpoint allows you to identify the most-mentioned entities, concepts and keywords relevant to your query. For example, this endpoint allows you to set parameters like a time period, a subject category, or an entity, and your request will return the most mentioned entities or keywords that are mentioned in relation to your query.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "News",
      "item": [
        {
          "id": "8f22e9bc-75a3-41c5-a3e1-d991b1237956",
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
              "id": "d5ac9363-f64a-4089-9c99-f6fd95540511"
            }
          ]
        },
        {
          "id": "259ccef0-efbf-407f-b3a3-dd9600d9cb5a",
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
              "id": "bb548cf6-ec1d-4467-8e12-ab6a5e8cd7ca"
            }
          ]
        },
        {
          "id": "a03ee130-9132-44fe-9319-2db9bcff2003",
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
              "id": "3f5dd45f-33b4-4d2c-822d-f1533a14281d"
            }
          ]
        },
        {
          "id": "ebf6147b-bf46-4374-803e-2c22eb50f1a8",
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
              "id": "b74671b4-132c-4cc4-87d7-195588b41471"
            }
          ]
        },
        {
          "id": "6ffe68dc-f6df-488e-a054-2e3ac8eb7c16",
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
              "id": "be0804c0-8b35-4ec7-b9be-4908eb351151"
            }
          ]
        },
        {
          "id": "d8ee06e1-d3c8-4238-bbbf-5ab2c4c86925",
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
              "id": "a2c22314-7d78-46b3-bce8-76d1841fd38d"
            }
          ]
        },
        {
          "id": "8dfb5dd0-9a95-424c-8638-e3d8e8d40e97",
          "name": "listTimeSeries",
          "request": {
            "url": "http://api.newsapi.aylien.com/api/v1/time_series?No Name=%7B%7D",
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
            "description": "The time series endpoint allows you to track information contained in stories over time. This information can be anything from mentions of a topic or entities, sentiment about a topic, or the volume of stories published by a source, to name but a few. The full list of parameters is given below. Using the [Date Math Syntax](https://newsapi.aylien.com/docs/working-with-dates), you can easily set your query to return information from any time period, from the current point in time to when the News API started collecting stories. The returned information can be rounded to a time also specified by you, for example by setting the results into hourly, daily, or weekly data points."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dfa9c3a4-d6a0-4845-9c43-8e94670a1c56"
            }
          ]
        },
        {
          "id": "081e2fe6-dc6e-498d-9e12-522146412580",
          "name": "listTrends",
          "request": {
            "url": "http://api.newsapi.aylien.com/api/v1/trends?No Name=%7B%7D",
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
            "description": "The trends endpoint allows you to identify the most-mentioned entities, concepts and keywords relevant to your query. For example, this endpoint allows you to set parameters like a time period, a subject category, or an entity, and your request will return the most mentioned entities or keywords that are mentioned in relation to your query."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2537810d-7e49-4686-99ba-ae3b9c506e58"
            }
          ]
        }
      ]
    }
  ]
}