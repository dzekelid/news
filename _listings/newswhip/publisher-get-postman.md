{
  "info": {
    "name": "News Whip API Publisher",
    "_postman_id": "af8239f1-2087-4466-9082-39a3b2708a2e",
    "description": "Pull publishers.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "News",
      "item": [
        {
          "id": "de6f9530-4d45-40b0-8458-253a31f9185b",
          "name": "getLocal",
          "request": {
            "url": "http://api.newswhip.com/v1/local/?key=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Pull list of localities."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9f25bbc2-a9d9-479b-9153-5ab0267c94c0"
            }
          ]
        },
        {
          "id": "58ace57a-d79f-4701-90b7-c5b2f3f3a107",
          "name": "getLocalCityAllTimePeriod",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.newswhip.com",
              "path": [
                "v1",
                "local/:city/All/:time_period"
              ],
              "query": [
                {
                  "key": "key",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "sort_by",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "video_only",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "city",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "time_period",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Search local news."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ca7b7485-3a05-4bf5-a59f-6845408ead3c"
            }
          ]
        },
        {
          "id": "53dd2852-2852-4275-b519-e29d1acd8edb",
          "name": "getPublisher",
          "request": {
            "url": "http://api.newswhip.com/v1/publisher/?key=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Pull publishers."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9e34acb0-cff6-4927-bab5-717570bbe455"
            }
          ]
        }
      ]
    }
  ]
}