---
swagger: "2.0"
x-collection-name: Gmail
x-complete: 0
info:
  title: Gmail Create Forward Addresse
  description: |-
    Creates a forwarding address. If ownership verification is required, a message will be sent to the recipient and the resource's verification status will be set to pending; otherwise, the resource will be created with verification status set to accepted.

    This method is only available to service account clients that have been delegated domain-wide authority.
  contact:
    name: Google
    url: https://google.com
  version: v1
host: www.googleapis.com
basePath: /gmail/v1/users
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{userId}/settings/forwardingAddresses:
    get:
      summary: Get Forward Addresses
      description: Lists the forwarding addresses for the specified account.
      operationId: gmail.users.settings.forwardingAddresses.list
      x-api-path-slug: useridsettingsforwardingaddresses-get
      parameters:
      - in: path
        name: userId
        description: Users email address
      responses:
        200:
          description: OK
      tags:
      - Forwarding Address
    post:
      summary: Create Forward Addresse
      description: |-
        Creates a forwarding address. If ownership verification is required, a message will be sent to the recipient and the resource's verification status will be set to pending; otherwise, the resource will be created with verification status set to accepted.

        This method is only available to service account clients that have been delegated domain-wide authority.
      operationId: gmail.users.settings.forwardingAddresses.create
      x-api-path-slug: useridsettingsforwardingaddresses-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: userId
        description: Users email address
      responses:
        200:
          description: OK
      tags:
      - Forwarding Address
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