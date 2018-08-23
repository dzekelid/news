{
  "info": {
    "name": "New York Times The Semantic API",
    "_postman_id": "33b2ea9c-1ab2-48ea-ad3b-c20520060964",
    "description": "The Semantic API complements the Articles API. With the Semantic API, you get access to the long list of people, places, organizations and other locations, entities and descriptors that make up the controlled vocabulary used as metadata by The New York Times (sometimes referred to as Times Tags and used for Times Topics pages.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "semantics",
      "item": [
        {
          "id": "ebbb54eb-c994-4221-99e1-dda5375cd283",
          "name": "getSemantics",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.nytimes.com",
              "path": [
                "svc",
                "name/:concept-type/:specific-concept.json"
              ],
              "query": [
                {
                  "key": "fields",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "query",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "concept-type",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "specific-concept",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "The Semantic API complements the Articles API"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d9919537-7004-43fa-9bd8-eae9c373fef1"
            }
          ]
        }
      ]
    }
  ]
}