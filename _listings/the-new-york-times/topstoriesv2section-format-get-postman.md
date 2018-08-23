{
  "info": {
    "name": "New York Times Top Stories",
    "_postman_id": "b6b9dacb-9913-4700-8410-3d78869c6a17",
    "description": "The Top Stories API returns a list of articles and associated images currently on the specified section.  Support JSON and JSONP.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "news",
      "item": [
        {
          "id": "ee7d0150-f59c-4147-9f31-0e659432ca47",
          "name": "the-top-stories-api-returns-a-list-of-articles-and-associated-images-currently-on-the-specified-sect",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.nytimes.com",
              "path": [
                "svc",
                "topstories/v2/:section.json"
              ],
              "query": [
                {
                  "key": "callback",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "format",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "section",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "The Top Stories API returns a list of articles and associated images currently on the specified section"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4866b67f-f7d7-47a0-8a99-0f19b37ec1c9"
            }
          ]
        }
      ]
    }
  ]
}