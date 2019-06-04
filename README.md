# simple-api
HTTP and REST: Build a working JSON Server

# Author: Chloie Parsons

# Links and Resources
* Submission PR: https://github.com/chloieparsons-401-advanced-javascript/simple-api/pull/2
* Travis: Not required as there was no testing on this assignment

# Documentation
* api docs (API servers): localhost/3000

# Requirements
## Build a working JSON Server
Implement an API server suitable for a storefront, using json-server

* Install json-server globally
* Create a new repository called "simple-api"
* Create a folder called data with a db.json file
* Start json-server from within the simple-api folder and "watch" your database file

## Data models should contain the following fields:
* categories
_id, name, display_name, description
* products
_id, category, name, display_name, description
* Your api will (should) respond to the following endpoints:
/categories GET, POST
/categories/:id/ PUT, DELETE
/products GET, POST
/products/:id/ PUT, DELETE

## Connect a web server

* Open this React Application and "Fork" it
* Open the .env file and enter the URL to your API Server
* This server is configured to use the routes noted in the first lab requirement
* If your lab is working, this app will show your API Data!

## Swagger Documentation

* In your API, Create a folder called docs.
* Write and publish swagger documentation with Swagger Inspector or Swagger Editor (I chose Editor.).
* Copy and paste swagger.json from the editor and add to your server project.
* For submission, this file needs to be in your repository
* Additionally, add the URL to the swagger hub page where you build the docs to your README.


# Setup
  Swagger.json was delivered as broken starter code and made functional by my own efforts via Swagger Editor.

# UML
* ./assets/HTTP REST UML.jpg