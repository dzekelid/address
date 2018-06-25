---
name: MasterCard
x-slug: mastercard
description: Mastercard is a leading global payments & technology company that connects
  consumers, businesses, merchants, issuers & governments around the world.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/366-mastercard.jpg
x-kinRank: "9"
x-alexaRank: "48280"
tags: Address
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/address/master/_listings/mastercard/apis.md
specificationVersion: "0.14"
apis:
- name: Mastercard Get Node Address
  x-api-slug: mastercard
  description: |-
    Information about a specific node may be retrieved by its address.
    This is useful when navigating the network.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/366-mastercard.jpg
  humanURL: https://developer.mastercard.com/
  baseURL: https://eas5stl0.mastercard.int:13046//z0/core/v1//node/{address}
  tags: Blockchain,Node, Address
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/address/master/_listings/mastercard/nodeaddress-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/address/master/_listings/mastercard/nodeaddress-get-openapi.md
- name: Mastercard Get Address Address
  x-api-slug: mastercard
  description: |-
    Information about a particular address on the network. Note that this
    call may return information about a blockchain node or a signing entity.
    Also, the level of detail returned will vary depending on your permissions
    for the query target.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/366-mastercard.jpg
  humanURL: https://developer.mastercard.com/
  baseURL: https://eas5stl0.mastercard.int:13046//z0/core/v1//address/{address}
  tags: Blockchain,Address, Address
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/address/master/_listings/mastercard/addressaddress-get-openapi.md
- name: Mastercard
  x-api-slug: mastercard
  description: Mastercard is a leading global payments & technology company that connects
    consumers, businesses, merchants, issuers & governments around the world.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/366-mastercard.jpg
  humanURL: https://developer.mastercard.com/
  baseURL: https://eas5stl0.mastercard.int:13046//z0/core/v1
  tags: Address
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/address/master/_listings/mastercard/openapi.md
x-common:
- type: x-base
  url: https://api.simplify.com
- type: x-blog
  url: https://developer.mastercard.com/portal/display/blogs/Developer+Blogs
- type: x-crunchbase
  url: https://crunchbase.com/organization/mastercard
- type: x-crunchbase
  url: http://www.crunchbase.com/company/mastercard
- type: x-github
  url: https://github.com/MasterCard
- type: x-website
  url: https://developer.mastercard.com/
- type: x-twitter
  url: https://twitter.com/AskMastercard
- type: x-twitter
  url: https://twitter.com/MasterCardDev
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---