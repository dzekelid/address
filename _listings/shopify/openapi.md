swagger: "2.0"
x-collection-name: Shopify
x-complete: 1
info:
  title: Shopify API
  description: todo-add-description
  version: 1.0.0
host: DefaultParameterValue:DefaultParameterValue@DefaultParameterValue.myshopify.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /admin/customers/3989659651/addresses/5436816654.json:
    get:
      summary: Get a single customers address
      description: Get a single customers address.
      operationId: getAdminCustomers3989659651Addresses5436816654.json
      x-api-path-slug: admincustomers3989659651addresses5436816654-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Single
      - Customers
      - Address
  /admin/customers/3989659651/addresses/5436816654/default.json:
    put:
      summary: assigning a new default address to a customer
      description: Assigning a new default address to a customer.
      operationId: putAdminCustomers3989659651Addresses5436816654Default.json
      x-api-path-slug: admincustomers3989659651addresses5436816654default-json-put
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Assigning
      - New
      - Default
      - Address
      - To
      - Customer
  /admin/customers/search.json:
    get:
      summary: Get all customers with an address in the Brazil
      description: Get all customers with an address in the brazil.
      operationId: getAdminCustomersSearch.json
      x-api-path-slug: admincustomerssearch-json-get
      parameters:
      - in: header
        name: Content-Type
      - in: query
        name: query
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Customers
      - Address
      - In
      - Brazil
  /admin/customers/3989659651/addresses/5484465742.json:
    delete:
      summary: Removing a customers address
      description: Removing a customers address.
      operationId: deleteAdminCustomers3989659651Addresses5484465742.json
      x-api-path-slug: admincustomers3989659651addresses5484465742-json-delete
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Removing
      - Customers
      - Address