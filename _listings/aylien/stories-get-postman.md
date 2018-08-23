{
  "info": {
    "name": "Aylien List Stories",
    "_postman_id": "58213882-c66b-40a8-b2b1-1754ead66de0",
    "description": "The stories endpoint is used to return stories based on parameters you set in your query. The News API crawler gathers articles in near real-time and stores information about them, or metadata. Below you can see all of the query parameters, which you can use to narrow down your query.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "News",
      "item": [
        {
          "id": "30bd9ecc-3b8e-4236-b3d7-11ff3da36d4b",
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
              "id": "0a541589-02f9-4579-8e85-78ff2b0dcd55"
            }
          ]
        }
      ]
    }
  ]
}