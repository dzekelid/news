{
  "info": {
    "name": "News Whip API Local",
    "_postman_id": "31ed5f18-5d45-4125-9278-3b1ffe7b3cb0",
    "description": "Pull list of localities.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "News",
      "item": [
        {
          "id": "11fb1778-c432-4c50-9563-4a90d35046b3",
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
              "id": "283fbae0-e610-49ff-8d9d-50ae3c270453"
            }
          ]
        }
      ]
    }
  ]
}