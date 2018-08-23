{
  "info": {
    "name": "My News Desk Pressroom List Pressroom Info",
    "_postman_id": "fe2b9b9c-1299-4b12-9317-c94d5152696e",
    "description": "Pressroom Info",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "News",
      "item": [
        {
          "id": "8509251b-c9dd-40e1-bf45-9c87ad42041d",
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
              "id": "0ac0e132-92e6-4986-a255-ab0fb2a0acf7"
            }
          ]
        },
        {
          "id": "0d664c25-4f97-442f-a028-109c19b411c8",
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
              "id": "51666b61-f52f-4fd2-a3c2-538abeb21902"
            }
          ]
        }
      ]
    }
  ]
}