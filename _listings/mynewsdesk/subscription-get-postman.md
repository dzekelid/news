{
  "info": {
    "name": "My News Desk Pressroom List News Subscription",
    "_postman_id": "2be61bbf-ca33-4696-8585-eb3f1f865fa7",
    "description": "News Subscription",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "News",
      "item": [
        {
          "id": "cb1ca043-178f-4cb4-8eb3-91006f690a86",
          "name": "getList",
          "request": {
            "url": "http://www.mynewsdesk.com/services/pressroom/list/?archived=%7B%7D&callback=%7B%7D&format=%7B%7D&limit=%7B%7D&offset=%7B%7D&order=%7B%7D&pressroom=%7B%7D&type_of_media=%7B%7D&unique key=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists news"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3db7fccc-030b-49a9-87fd-2ddf14478409"
            }
          ]
        },
        {
          "id": "771f8c78-a87d-4512-bbf4-b1f162f0e7cc",
          "name": "getPressroomInfo",
          "request": {
            "url": "http://www.mynewsdesk.com/services/pressroom/pressroom_info/?pressroom=%7B%7D&unique key=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Pressroom Info"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e7bdd989-8c78-4a31-a0a6-c5df9c436f45"
            }
          ]
        },
        {
          "id": "054d19cc-e902-475a-b402-19a0e04a4af9",
          "name": "getSearch",
          "request": {
            "url": "http://www.mynewsdesk.com/services/pressroom/search/?callback=%7B%7D&date_end=%7B%7D&date_mode=%7B%7D&date_on=%7B%7D&date_start=%7B%7D&format=%7B%7D&limit=%7B%7D&page=%7B%7D&pressroom=%7B%7D&query=%7B%7D&type_of_media=%7B%7D&unique key=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "News Search"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a044dbad-c265-4f17-9f51-f47a342012a3"
            }
          ]
        },
        {
          "id": "b92e8921-f248-4912-8999-b501481fdb3b",
          "name": "getSubscription",
          "request": {
            "url": "http://www.mynewsdesk.com/services/pressroom/subscription/?newsdesk_pressroom=%7B%7D&newsdesk_subscriber_email=%7B%7D&newsdesk_subscribe_to_type=%7B%7D&unique key=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "News Subscription"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "038849b8-1771-4518-bb02-352cc89e0c6e"
            }
          ]
        }
      ]
    }
  ]
}