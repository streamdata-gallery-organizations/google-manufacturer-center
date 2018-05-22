---
name: Google Manufacturer Center
x-slug: google-manufacturer-center
description: Public API for managing Manufacturer Center related data. Impact the
  way your products and product details appear within Google Shopping. You???ll attract
  more shoppers and elevate your brands online. With Manufacturer Center, you provide
  the images, descriptions, and product details to improve how your products appear
  to the world. That information helps create more effective listings on Google Shopping
  and other Google services. If anything changes, you can provide new product data
  at any time.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-manufacturer-center-800x546.png
x-kinRank: "9"
x-alexaRank: ""
tags: Google Manufacturer Center
created: "2018-05-21"
modified: "2018-05-21"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-manufacturer-center/master/_listings/google-manufacturer-center/apis.md
specificationVersion: "0.14"
apis:
- name: Google Manufacturer Center API Get Products
  x-api-slug: google-manufacturer-center-api
  description: Lists all the products in a Manufacturer Center account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-manufacturer-center-800x546.png
  humanURL: https://developers.google.com/manufacturers/quickstart
  baseURL: ://manufacturers.googleapis.com////v1/{parent}/products
  tags: Product
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-manufacturer-center/master/_listings/google-manufacturer-center/v1parentproducts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-manufacturer-center/master/_listings/google-manufacturer-center/v1parentproducts-get-openapi.md
- name: Google Manufacturer Center API Get Product
  x-api-slug: google-manufacturer-center-api
  description: |-
    Gets the product from a Manufacturer Center account, including product
    issues.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-manufacturer-center-800x546.png
  humanURL: https://developers.google.com/manufacturers/quickstart
  baseURL: ://manufacturers.googleapis.com////v1/{parent}/products/{name}
  tags: Product
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-manufacturer-center/master/_listings/google-manufacturer-center/v1parentproductsname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-manufacturer-center/master/_listings/google-manufacturer-center/v1parentproductsname-get-openapi.md
- name: Google Manufacturer Center API
  x-api-slug: google-manufacturer-center-api
  description: Public API for managing Manufacturer Center related data. Impact the
    way your products and product details appear within Google Shopping. You???ll
    attract more shoppers and elevate your brands online. With Manufacturer Center,
    you provide the images, descriptions, and product details to improve how your
    products appear to the world. That information helps create more effective listings
    on Google Shopping and other Google services. If anything changes, you can provide
    new product data at any time.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-manufacturer-center-800x546.png
  humanURL: https://developers.google.com/manufacturers/quickstart
  baseURL: ://manufacturers.googleapis.com//
  tags: Google Manufacturer Center
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-manufacturer-center/master/_listings/google-manufacturer-center/openapi.md
x-common:
- type: x-authentication
  url: https://developers.google.com/manufacturers/how-tos/authorizing
- type: x-code
  url: https://developers.google.com/manufacturers/libraries
- type: x-developers
  url: https://developers.google.com/manufacturers/quickstart
- type: x-website
  url: https://www.google.com/retail/manufacturer-center/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---