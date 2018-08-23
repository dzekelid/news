{
  "info": {
    "name": "Aylien List time series",
    "_postman_id": "b711c880-eddb-4183-bd69-90b87e67997b",
    "description": "The time series endpoint allows you to track information contained in stories over time. This information can be anything from mentions of a topic or entities, sentiment about a topic, or the volume of stories published by a source, to name but a few. The full list of parameters is given below. Using the [Date Math Syntax](https://newsapi.aylien.com/docs/working-with-dates), you can easily set your query to return information from any time period, from the current point in time to when the News API started collecting stories. The returned information can be rounded to a time also specified by you, for example by setting the results into hourly, daily, or weekly data points.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "News",
      "item": [
        {
          "id": "a70a0f10-a8a3-4545-88b8-026775b07e02",
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
              "id": "c28bf2dc-c977-46e1-8233-2f45f0fbddc3"
            }
          ]
        },
        {
          "id": "4ff127ef-11d5-4e19-aa72-a97cc41e3467",
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
              "id": "c9ed0bb7-a462-4def-99d5-9cb48af9a394"
            }
          ]
        },
        {
          "id": "84c7f5cb-99cc-40b7-ba66-be9cf355af42",
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
              "id": "f3651466-e421-4116-8349-10df63824b98"
            }
          ]
        },
        {
          "id": "70dc22fe-1acc-4b93-a1db-d4055f7b6f0b",
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
              "id": "6748d59f-fba1-4b8e-95a9-0e941cb36050"
            }
          ]
        },
        {
          "id": "00b6aab3-d498-47f7-a151-a809d08baba9",
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
              "id": "93d799d4-1e27-4d83-b26f-63a4ad320b65"
            }
          ]
        },
        {
          "id": "8e2d72b7-c350-49aa-ae0b-378baea58941",
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
              "id": "a5151b88-a1ca-4af6-a0da-77409bd7ad7f"
            }
          ]
        },
        {
          "id": "8f408c64-b5eb-4e43-9c9d-7350b118e594",
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
              "id": "c28052e9-7e4b-49c9-9db9-f89b549b8ddf"
            }
          ]
        }
      ]
    }
  ]
}