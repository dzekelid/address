---
swagger: "2.0"
x-collection-name: Etsy
x-complete: 0
info:
  title: Etsy Delete Users User Addresses User Address
  description: Deletes the UserAddress with the given id.
  version: 1.0.0
host: openapi.etsy.com
basePath: /v2/private/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /users/{user_id}/addresses/{user_address_id}:
    delete:
      summary: Delete Users User Addresses User Address
      description: Deletes the UserAddress with the given id.
      operationId: deleteUsersUserAddressesUserAddress
      x-api-path-slug: usersuser-idaddressesuser-address-id-delete
      parameters:
      - in: path
        name: user_address_id
      - in: path
        name: user_id
      responses:
        200:
          description: OK
      tags:
      - Users
      - Addresses
      - User
      - Address
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