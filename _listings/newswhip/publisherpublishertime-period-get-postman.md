{
  "info": {
    "name": "News Whip API Publisher",
    "_postman_id": "bfd2a278-0fcb-4d7c-ac3e-d958fbf33bcc",
    "description": "Search news by publisiher.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "News",
      "item": [
        {
          "id": "d494db09-e863-4a43-b960-8c9b713ad4ae",
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
              "id": "ecbc0683-14ba-406c-8fea-546ad0792d00"
            }
          ]
        },
        {
          "id": "ec6d53d7-6168-437b-b8fc-fb612ccd0abd",
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
              "id": "a1bff824-4106-4977-9f50-efe660d27f03"
            }
          ]
        },
        {
          "id": "e81dee9e-ec42-48dd-a785-0b9f79523907",
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
              "id": "2de6991d-14f4-4204-8879-572e69e52e1c"
            }
          ]
        },
        {
          "id": "1ec89e2e-3aec-4211-bb2b-ba9a3566e751",
          "name": "getPublisherPublisherTimePeriod",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.newswhip.com",
              "path": [
                "v1",
                "publisher/:publisher/:time_period"
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
                  "id": "publisher",
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
            "description": "Search news by publisiher."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "be9fa02d-93e3-41a2-bac6-558e40f4c679"
            }
          ]
        }
      ]
    }
  ]
}