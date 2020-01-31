Backend Challenge
=======

Prerequisites
-------------

* [Git](http://git-scm.com/)
* [Postgres](https://www.postgresql.org/)

Option one
* [nodejs](https://nodejs.org/en/)
* nodejs framework of your choice

Option two
* [Ruby](https://www.ruby-lang.org)
* Ruby framework of your choice


* You can use any additional libraries you want.

Project description
-------------------

**Product Orders**

This application serves the purpose of exposing a JSON API to be consumed by a frontend client for ordering products.

The following entities should be created (including proper relations):

* *product* - has a name and price (e.g. Keyboard $15, Smartwatch $16, ...)
* *product details* - has product details
* *order* - has items
* *order item* - has a product and quantity

The following endpoints should return a JSON response:
* `/api/orders` (list of orders)
* `/api/orders/:id` (details of an individual order)
* `/api/products` (list of products; see './backend/example-products.json')
* `/api/product/:id/details` (list of products details; see './backend/example-products.json')