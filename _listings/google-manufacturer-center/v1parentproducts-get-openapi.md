---
swagger: "2.0"
x-collection-name: Google Manufacturer Center
x-complete: 0
info:
  title: Google Manufacturer Center API Get Products
  description: Lists all the products in a Manufacturer Center account.
  contact:
    name: Google
    url: https://google.com
  version: v1
host: manufacturers.googleapis.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/{parent}/products:
    get:
      summary: Get Products
      description: Lists all the products in a Manufacturer Center account.
      operationId: manufacturers.accounts.products.list
      x-api-path-slug: v1parentproducts-get
      parameters:
      - in: query
        name: pageSize
        description: Maximum number of product statuses to return in the response,
          used forpaging
      - in: query
        name: pageToken
        description: The token returned by the previous request
      - in: path
        name: parent
        description: Parent ID in the format `accounts/{account_id}`
      responses:
        200:
          description: OK
      tags:
      - Product
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---