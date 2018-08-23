---
swagger: "2.0"
x-collection-name: Lykke
x-complete: 1
info:
  title: Wallet_Api
  version: 1.0.0
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/LykkeNews:
    get:
      summary: Get API Lykkenews
      description: Get api lykkenews.
      operationId: ApiLykkeNewsGet
      x-api-path-slug: apilykkenews-get
      parameters:
      - in: query
        name: skip
      - in: query
        name: take
      responses:
        200:
          description: OK
      tags:
      - Lykkenews
---