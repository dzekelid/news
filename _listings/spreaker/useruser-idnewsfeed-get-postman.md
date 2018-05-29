{
  "info": {
    "name": "Spreaker API Newsfeed",
    "_postman_id": "b9ed7dd8-0a60-49a3-90fa-5422591eae51",
    "description": "This API returns a list of newsfeed items. The request MUST be authenticated (an user can only fetch its own newsfeed).",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Newsfeed",
      "item": [
        {
          "id": "aef3f970-68da-47ed-b4b1-6db2ff06e5cf",
          "name": "getUserUserNewsfeed",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.spreaker.com",
              "path": [
                "user/:user_id/newsfeed"
              ],
              "query": [
                {
                  "key": "last_id",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "max_per_page",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "user_id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "This API returns a list of newsfeed items. The request MUST be authenticated (an user can only fetch its own newsfeed)."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c8189667-0617-4729-aa07-548a35198981"
            }
          ]
        }
      ]
    }
  ]
}