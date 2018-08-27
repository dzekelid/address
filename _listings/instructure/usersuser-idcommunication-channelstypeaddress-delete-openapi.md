---
swagger: "2.0"
x-collection-name: Instructure
x-complete: 0
info:
  title: Instructure Canvas Users API Delete a communication channel
  description: Delete a communication channel.
  termsOfService: https://www.canvaslms.com/policies/api-policy
  version: v1
host: canvas.instructure.com
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /users/{user_id}/communication_channels/type/{address}/notification_preferences/notification:
    get:
      summary: Get a preference
      description: Get a preference.
      operationId: get-a-preference
      x-api-path-slug: usersuser-idcommunication-channelstypeaddressnotification-preferencesnotification-get
      responses:
        200:
          description: OK
      tags:
      - Users
      - User
      - Id
      - Communication
      - Channels
      - Type
      - Address
      - Notification
      - Preferences
      - Notification
  /users/{user_id}/communication_channels/type/{address}/notification_preferences:
    get:
      summary: List preferences
      description: List preferences.
      operationId: list-preferences
      x-api-path-slug: usersuser-idcommunication-channelstypeaddressnotification-preferences-get
      responses:
        200:
          description: OK
      tags:
      - Users
      - User
      - Id
      - Communication
      - Channels
      - Type
      - Address
      - Notification
      - Preferences
  /users/{user_id}/communication_channels/type/{address}:
    delete:
      summary: Delete a communication channel
      description: Delete a communication channel.
      operationId: delete-a-communication-channel
      x-api-path-slug: usersuser-idcommunication-channelstypeaddress-delete
      responses:
        200:
          description: OK
      tags:
      - Users
      - User
      - Id
      - Communication
      - Channels
      - Type
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