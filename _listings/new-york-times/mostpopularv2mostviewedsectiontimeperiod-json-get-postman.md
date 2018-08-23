{
  "info": {
    "name": "New York Times Most Viewed by Section & Time Period",
    "_postman_id": "7691f351-ecae-4231-9450-4d4053d409e5",
    "description": "With the Most Popular API, you can get links and metadata for the blog posts and articles that are most frequently e-mailed, shared and viewed by NYTimes.co",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "news",
      "item": [
        {
          "id": "44828615-0b77-4f16-b93b-087fdd5428f6",
          "name": "GET_mostviewed-section-time-period-json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.nytimes.com",
              "path": [
                "svc",
                "mostpopular/v2/mostviewed/:section/:time-period.json"
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
              "id": "9df63bd9-30bd-49b8-81f6-ff8db04e9a13"
            }
          ]
        }
      ]
    }
  ]
}