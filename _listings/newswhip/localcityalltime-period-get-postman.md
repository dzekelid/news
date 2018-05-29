{
  "info": {
    "name": "News Whip API Local",
    "_postman_id": "7ebb94b4-ece2-4d5b-bd83-33c07c0a32d7",
    "description": "Search local news.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "News",
      "item": [
        {
          "id": "4729cf16-c32b-4390-b529-8c95e44c963f",
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
              "id": "e0b5f446-6af1-4da4-9a56-54d10fcf37e3"
            }
          ]
        },
        {
          "id": "0666c2f8-9186-499b-8ad9-8e548b9dcfd1",
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
              "id": "969561f9-8b62-41d3-9089-70eb0caab17e"
            }
          ]
        }
      ]
    }
  ]
}