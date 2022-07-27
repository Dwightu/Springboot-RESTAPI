# Springboot-RESTful API
This is an repository for displaying how to use spring boot to build a REST API. 

## Usage
This is a backend project, you should have <a href="https://www.postman.com/">Postman<a/> to test this API.<br>
- Step1: git clone
- Step2: cd folder
- Step3: `./mvnw clean spring-boot:run`


### POST request
POST `localhost:8080/contact` with body(JSON): `{
    "id":"1",
    "name":"Dehui",
    "phoneNumber":"19237281923"
}`

### GET request
GET `localhost:8080/contact/{id}`


### GET all request
GET `localhost:8080/contact/all`

### DELETE request
DELETE `localhost:8080/contact/{id}`

### PUT request
PUT `localhost:8080/contact/{id}`
with body(JSON): `{
    "id":"2",
    "name":"Dehui2",
    "phoneNumber":"192372819232"
}`
