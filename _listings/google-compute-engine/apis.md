---
name: Google Compute Engine
x-slug: google-compute-engine
description: Google Compute Engine delivers virtual machines running in Googles innovative
  data centers and worldwide fiber network. Compute Engines tooling and workflow support
  enable scaling from single instances to global, load-balanced cloud computing.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Address
created: "2018-06-17"
modified: "2018-06-17"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/address/master/_listings/google-compute-engine/apis.md
specificationVersion: "0.14"
apis:
- name: Google Compute Engine API Get Addresses
  x-api-slug: google-compute-engine-api
  description: Retrieves an aggregated list of addresses.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/aggregated/addresses
  tags: Address,Aggregation
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/address/master/_listings/google-compute-engine/projectaggregatedaddresses-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/address/master/_listings/google-compute-engine/projectaggregatedaddresses-get-openapi.md
- name: Google Compute Engine API Get Global Addreses
  x-api-slug: google-compute-engine-api
  description: Retrieves a list of global addresses.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/addresses
  tags: Address
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/address/master/_listings/google-compute-engine/projectglobaladdresses-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/address/master/_listings/google-compute-engine/projectglobaladdresses-get-openapi.md
- name: Google Compute Engine API Add Address
  x-api-slug: google-compute-engine-api
  description: Creates an address resource in the specified project using the data
    included in the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/addresses
  tags: Address
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/address/master/_listings/google-compute-engine/projectglobaladdresses-post-openapi.md
- name: Google Compute Engine API Delete Address
  x-api-slug: google-compute-engine-api
  description: Deletes the specified address resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/addresses/{address}
  tags: Address
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/address/master/_listings/google-compute-engine/projectglobaladdressesaddress-delete-openapi.md
- name: Google Compute Engine API Get Address
  x-api-slug: google-compute-engine-api
  description: Returns the specified address resource. Get a list of available addresses
    by making a list() request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/addresses/{address}
  tags: Address
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/address/master/_listings/google-compute-engine/projectglobaladdressesaddress-get-openapi.md
- name: Google Compute Engine API Get Region Addresses
  x-api-slug: google-compute-engine-api
  description: Retrieves a list of addresses contained within the specified region.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/addresses
  tags: Region Address
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/address/master/_listings/google-compute-engine/projectregionsregionaddresses-get-openapi.md
- name: Google Compute Engine API Create Region Address
  x-api-slug: google-compute-engine-api
  description: Creates an address resource in the specified project using the data
    included in the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/addresses
  tags: Region Address
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/address/master/_listings/google-compute-engine/projectregionsregionaddresses-post-openapi.md
- name: Google Compute Engine API Delete Region Address
  x-api-slug: google-compute-engine-api
  description: Deletes the specified address resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/addresses/{address}
  tags: Region Address
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/address/master/_listings/google-compute-engine/projectregionsregionaddressesaddress-delete-openapi.md
- name: Google Compute Engine API Get Region Address
  x-api-slug: google-compute-engine-api
  description: Returns the specified address resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/addresses/{address}
  tags: Region Address
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/address/master/_listings/google-compute-engine/projectregionsregionaddressesaddress-get-openapi.md
- name: Google Compute Engine API
  x-api-slug: google-compute-engine-api
  description: Google Compute Engine delivers virtual machines running in Googles
    innovative data centers and worldwide fiber network. Compute Engines tooling and
    workflow support enable scaling from single instances to global, load-balanced
    cloud computing.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects
  tags: Address
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/address/master/_listings/google-compute-engine/openapi.md
x-common:
- type: x-code
  url: https://cloud.google.com/compute/docs/api/libraries
- type: x-documentation
  url: https://cloud.google.com/compute/docs/reference/latest/
- type: x-guides
  url: https://cloud.google.com/compute/docs/api/how-tos/how-tos
- type: x-rate-limits
  url: https://cloud.google.com/compute/docs/api-rate-limits
- type: x-sla
  url: https://cloud.google.com/compute/sla
- type: x-website
  url: https://cloud.google.com/compute/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---