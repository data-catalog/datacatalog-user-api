# Data Catalog User Service API OpenAPI Definition

The OpenAPI specification user handling service API within the Data Catalog application.


## API Description

Provides API endpoints to register, and log in to the application. 

It communicates with other services to tell informations about tokens, thus
authorizing a request made at another service.

Provides endpoints to delete, and list users for administrative purposes.

The api supports JWT token, and API key authentication.


## Working on the OpenAPI Definition

### Install

1. Install [Node JS](https://nodejs.org/).
2. Clone this repo and run `npm install` in the repo root.

### Usage

#### `npm start`
Starts the reference docs preview server.

#### `npm run build`
Bundles the definition to the dist folder.

#### `npm test`
Validates the definition.
