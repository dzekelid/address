---
name: Gmail
x-slug: gmail
description: The Gmail API is a RESTful API that can be used to access Gmail mailboxes
  and send mail. For most web applications (including mobile apps), the Gmail API
  is the best choice for authorized access to a users Gmail data.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/gmail-icon.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Address
created: "2018-06-17"
modified: "2018-06-17"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/address/master/_listings/gmail/apis.md
specificationVersion: "0.14"
apis:
- name: Gmail Get Forward Addresses
  x-api-slug: gmail
  description: Lists the forwarding addresses for the specified account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/gmail-icon.png
  humanURL: https://www.google.com/gmail/
  baseURL: https://www.googleapis.com//gmail/v1/users//{userId}/settings/forwardingAddresses
  tags: Forwarding Address
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/address/master/_listings/gmail/useridsettingsforwardingaddresses-get-openapi.md
- name: Gmail Create Forward Addresse
  x-api-slug: gmail
  description: |-
    Creates a forwarding address. If ownership verification is required, a message will be sent to the recipient and the resource's verification status will be set to pending; otherwise, the resource will be created with verification status set to accepted.

    This method is only available to service account clients that have been delegated domain-wide authority.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/gmail-icon.png
  humanURL: https://www.google.com/gmail/
  baseURL: https://www.googleapis.com//gmail/v1/users//{userId}/settings/forwardingAddresses
  tags: Forwarding Address
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/address/master/_listings/gmail/useridsettingsforwardingaddresses-post-openapi.md
- name: Gmail Delete Forward Address
  x-api-slug: gmail
  description: |-
    Deletes the specified forwarding address and revokes any verification that may have been required.

    This method is only available to service account clients that have been delegated domain-wide authority.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/gmail-icon.png
  humanURL: https://www.google.com/gmail/
  baseURL: https://www.googleapis.com//gmail/v1/users//{userId}/settings/forwardingAddresses/{forwardingEmail}
  tags: Forwarding Address
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/address/master/_listings/gmail/useridsettingsforwardingaddressesforwardingemail-delete-openapi.md
- name: Gmail GGetet Forward Address
  x-api-slug: gmail
  description: Gets the specified forwarding address.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/gmail-icon.png
  humanURL: https://www.google.com/gmail/
  baseURL: https://www.googleapis.com//gmail/v1/users//{userId}/settings/forwardingAddresses/{forwardingEmail}
  tags: Forwarding Address
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/address/master/_listings/gmail/useridsettingsforwardingaddressesforwardingemail-get-openapi.md
- name: Gmail
  x-api-slug: gmail
  description: The Gmail API is a RESTful API that can be used to access Gmail mailboxes
    and send mail. For most web applications (including mobile apps), the Gmail API
    is the best choice for authorized access to a users Gmail data.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/gmail-icon.png
  humanURL: https://www.google.com/gmail/
  baseURL: https://www.googleapis.com//gmail/v1/users
  tags: Address
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/address/master/_listings/gmail/openapi.md
x-common:
- type: x-auth-scopes
  url: https://developers.google.com/gmail/api/auth/scopes
- type: x-authentication
  url: https://developers.google.com/gmail/api/auth/about-auth
- type: x-developer
  url: https://developers.google.com/gmail/api/
- type: x-documentation
  url: https://developers.google.com/gmail/api/v1/reference/
- type: x-twitter
  url: https://twitter.com/gmail
- type: x-website
  url: https://www.google.com/gmail/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---