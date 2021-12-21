# golang-rest-api
Toy project for API built using Golang

## Endpoints
GET /coasters returns list of coasters as JSON

GET /coasters/{id} returns details of specific coaster as JSON

POST /coasters accepts a new coaster to be added

POST /coasters returns status 415 if content is not application/json

GET /admin requires basic auth

GET /coasters/random redirects (Status 302) to a random coaster
