{
  "info": {
    "name": "New York Times Geographic API",
    "_postman_id": "3bda52b4-cfd7-49ec-9a76-c2989da4f5ef",
    "description": "The Geographic API extends the Semantic API, using a linked data approach to enhance location concepts used in The New York Times' controlled vocabulary and data resources which combine them with the GeoNames database, an authoritative and free to use database of global geographical places, names and features.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "news",
      "item": [
        {
          "id": "cb409c4d-ea21-4f05-9c5f-0ae50c2692bc",
          "name": "geographic-api",
          "request": {
            "url": "http://api.nytimes.com/svc/query.json?date_range=%7B%7D&elevation=%7B%7D&facets=%7B%7D&filter=%7B%7D&latitude=%7B%7D&limit=%7B%7D&longitude=%7B%7D&name=%7B%7D&offset=%7B%7D&query=%7B%7D&sort=%7B%7D&sw=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "The Geographic API extends the Semantic API, using a linked data approach to enhance location concepts used in The New York Times' controlled vocabulary and data resources which combine them with the GeoNames database, an authoritative and free to use database of global geographical places, names and features"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "155e77f2-4d12-4faa-ae3e-b1f19168b27b"
            }
          ]
        }
      ]
    }
  ]
}