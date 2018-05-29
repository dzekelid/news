{
  "info": {
    "name": "New York Times Most Emailed by Section & Time Period",
    "_postman_id": "1ef9f997-b582-40ad-afec-a031a09e0949",
    "description": "With the Most Popular API, you can get links and metadata for the blog posts and articles that are most frequently e-mailed, shared and viewed by NYTimes.co",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "news",
      "item": [
        {
          "id": "3aff2c38-f8fc-4611-bc98-215d94dc0c0a",
          "name": "GET_mostemailed-section-time-period-json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.nytimes.com",
              "path": [
                "svc",
                "mostpopular/v2/mostemailed/:section/:time-period.json"
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
              "id": "9066a112-7565-4fbc-ba57-a72f296c63ba"
            }
          ]
        }
      ]
    }
  ]
}