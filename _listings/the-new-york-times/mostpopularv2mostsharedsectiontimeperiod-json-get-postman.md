{
  "info": {
    "name": "New York Times Most Shared by Section & Time Period",
    "_postman_id": "b120edf6-f916-4824-913a-886bce23f5d1",
    "description": "With the Most Popular API, you can get links and metadata for the blog posts and articles that are most frequently e-mailed, shared and viewed by NYTimes.co",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "news",
      "item": [
        {
          "id": "96d02e5f-5344-4cc2-b13f-2daa1d643e3f",
          "name": "GET_mostshared-section-time-period-json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.nytimes.com",
              "path": [
                "svc",
                "mostpopular/v2/mostshared/:section/:time-period.json"
              ],
              "variable": [
                {
                  "id": "section",
                  "value": "section",
                  "type": "string"
                },
                {
                  "id": "time-period",
                  "value": "time-period",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "With the Most Popular API, you can get links and metadata for the blog posts and articles that are most frequently e-mailed, shared and viewed by NYTimes"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a44a1f41-156f-4883-b93a-2fadbf2347c9"
            }
          ]
        }
      ]
    }
  ]
}