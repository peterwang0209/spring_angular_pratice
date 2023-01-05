# spring_angular_practice

## Tech Stack

- Java 19
- Spring
- PostgreSQL 15
- Angular
  
## Package Management

- Maven

## Restful Test tool

- Postman

## Command

**make sure you have postgreSQL service running in the background**
you can download the postgreSQL [here](https://postgresapp.com/downloads.html)

- Backend
  - java -jar demo-0.0.1-SNAPSHOT.jar
- Frontend
  - ng serve

## Usage

![image](/image/ui.png)

- load all employee at the present
- add an employee
- delete an employee
- update an employee
- search for an employee


## port

- the backend listen on localhost:8080
- the frontend listen on localhost:4200

## API end point

```
GET http://localhost:8080/employee/all
```

```
POST http://localhost:8080/employee/add
Content-Type: application/json

{
    "email": "bond@getarrays.com",
    "imageUrl": "https://www.bootdey.com/img/Content/avatar/avatar2.png",
    "jobTitle": "JavaScript",
    "name": "James Bond",
    "phone": "007"
}

```
```
DELETE http://localhost:8080/employee/delete/{id_number}
```
```
PUT http://localhost:8080/employee/update
Content-Type: application/json

{
    "email": "bond@getarrays.com",
    "imageUrl": "https://www.bootdey.com/img/Content/avatar/avatar2.png",
    "jobTitle": "JavaScript",
    "name": "James Bond",
    "phone": "007"
}
```
