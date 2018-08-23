{
  "info": {
    "name": "New York Times Best Seller List",
    "_postman_id": "49a82041-e584-4335-b44c-9c848693c401",
    "description": "The Books API has services for getting information about The New York Times Best Sellers Lists and Book Reviews.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "news",
      "item": [
        {
          "id": "8c0484f2-6c24-4079-bcd4-4c5f22b4a21e",
          "name": "GET_lists-format",
          "request": {
            "url": "http://api.nytimes.com/svc/books/v2/lists.json?bestsellers-date=%7B%7D&date=%7B%7D&format=format&isbn=%7B%7D&list=%7B%7D&offset=%7B%7D&published-date=%7B%7D&rank=%7B%7D&rank-last-week=%7B%7D&sort-order=%7B%7D&weeks-on-list=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "The Books API has services for getting information about The New York Times Best Sellers Lists and Book Reviews"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5c52ef8f-077e-4b2c-952c-62ae1ed8b7ab"
            }
          ]
        }
      ]
    }
  ]
}