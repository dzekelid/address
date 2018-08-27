---
swagger: "2.0"
x-collection-name: Google Compute Engine
x-complete: 0
info:
  title: Google Compute Engine API Get Address
  description: Returns the specified address resource. Get a list of available addresses
    by making a list() request.
  contact:
    name: Google
    url: https://google.com
  version: v1
host: www.googleapis.com
basePath: /compute/v1/projects
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{project}/global/addresses/{address}:
    get:
      summary: Get Address
      description: Returns the specified address resource. Get a list of available
        addresses by making a list() request.
      operationId: compute.globalAddresses.get
      x-api-path-slug: projectglobaladdressesaddress-get
      parameters:
      - in: path
        name: address
        description: Name of the address resource to return
      - in: path
        name: project
        description: Project ID for this request
      responses:
        200:
          description: OK
      tags:
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