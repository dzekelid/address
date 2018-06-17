---
swagger: "2.0"
x-collection-name: SendGrid
x-complete: 0
info:
  title: SendGrid Delete Ips Warmup Ip Address
  description: |-
    **This endpoint allows you to remove an IP address from warmup mode.**

    SendGrid can automatically warm up dedicated IP addresses by limiting the amount of mail that can be sent through them per hour, with the limit determined by how long the IP address has been in warmup. See the [warmup schedule](https://sendgrid.com/docs/API_Reference/Web_API_v3/IP_Management/ip_warmup_schedule.html) for more details on how SendGrid limits your email traffic for IPs in warmup.

    For more general information about warming up IPs, please see our [Classroom](https://sendgrid.com/docs/Classroom/Deliver/Delivery_Introduction/warming_up_ips.html).
  version: 1.0.0
host: api.sendgrid.com
basePath: /v3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /ips/warmup/{ip_address}:
    delete:
      summary: Delete Ips Warmup Ip Address
      description: |-
        **This endpoint allows you to remove an IP address from warmup mode.**

        SendGrid can automatically warm up dedicated IP addresses by limiting the amount of mail that can be sent through them per hour, with the limit determined by how long the IP address has been in warmup. See the [warmup schedule](https://sendgrid.com/docs/API_Reference/Web_API_v3/IP_Management/ip_warmup_schedule.html) for more details on how SendGrid limits your email traffic for IPs in warmup.

        For more general information about warming up IPs, please see our [Classroom](https://sendgrid.com/docs/Classroom/Deliver/Delivery_Introduction/warming_up_ips.html).
      operationId: ips.warmup.ip_address.delete
      x-api-path-slug: ipswarmupip-address-delete
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Email
      - Ips
      - Warmup
      - Ip
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