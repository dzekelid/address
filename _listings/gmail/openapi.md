---
swagger: "2.0"
x-collection-name: Gmail
x-complete: 1
info:
  title: Gmail
  description: access-gmail-mailboxes-including-sending-user-email-
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
  /{userId}/settings/forwardingAddresses/{forwardingEmail}:
    delete:
      summary: Delete Forward Address
      description: |-
        Deletes the specified forwarding address and revokes any verification that may have been required.

        This method is only available to service account clients that have been delegated domain-wide authority.
      operationId: gmail.users.settings.forwardingAddresses.delete
      x-api-path-slug: useridsettingsforwardingaddressesforwardingemail-delete
      parameters:
      - in: path
        name: forwardingEmail
        description: The forwarding address to be deleted
      - in: path
        name: userId
        description: Users email address
      responses:
        200:
          description: OK
      tags:
      - Forwarding Address
    get:
      summary: GGetet Forward Address
      description: Gets the specified forwarding address.
      operationId: gmail.users.settings.forwardingAddresses.get
      x-api-path-slug: useridsettingsforwardingaddressesforwardingemail-get
      parameters:
      - in: path
        name: forwardingEmail
        description: The forwarding address to be retrieved
      - in: path
        name: userId
        description: Users email address
      responses:
        200:
          description: OK
      tags:
      - Forwarding Address
---