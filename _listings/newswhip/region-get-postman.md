{
  "info": {
    "name": "News Whip API Region",
    "_postman_id": "f919ba7e-5ef8-4f1e-8136-a5666eec98b1",
    "description": "Retrieve list of regions",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "News",
      "item": [
        {
          "id": "05afd463-5451-47a8-87fa-2bfe620ca007",
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
              "id": "afb0c634-6c45-4623-9f95-e8fc6b66ee30"
            }
          ]
        },
        {
          "id": "4d90b034-d1c7-4fc4-888e-7f13449e1cdb",
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
              "id": "927868d7-6124-4ed6-a07c-17f167ff9a3f"
            }
          ]
        },
        {
          "id": "30b3826d-d835-4db4-b9ba-0155de427bba",
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
              "id": "ce432ea5-9010-4e14-9ca8-3c5d4278d29e"
            }
          ]
        },
        {
          "id": "7ee1e049-5d2d-4856-9eaa-e501cd8f3b64",
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
              "id": "9a5047cc-48a4-4f2c-bf9c-74b74af0069f"
            }
          ]
        },
        {
          "id": "a0598907-81f1-427f-b063-f2fd86e525f8",
          "name": "getRegion",
          "request": {
            "url": "http://api.newswhip.com/v1/region/?key=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieve list of regions"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a9e1bb79-1d8b-4cf2-8d8e-1a863e6f214a"
            }
          ]
        }
      ]
    }
  ]
}