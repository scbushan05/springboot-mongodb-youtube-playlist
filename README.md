# Build Complete REST API with Spring Data JPA and MongoDB - Todo Application
A simple Todo REST API built with Spring Data JPA that connects to the Mongodb database to perform the basic database operations such as Create, Read, Update and Delete

## Requirements

1. Java - 1.8.x

2. Maven - 3.x.x

3. Mongodb - 4.x.x

## Steps to Setup

**1. Clone the application**

```bash
git clone https://github.com/scbushan05/springboot-mongodb-youtube-playlist.git
```

**2. Create Mongodb database**
```bash
use todo-manager-api
```

**3. Change mysql username and password as per your installation**

+ open `src/main/resources/application.properties`

+ change `spring.datasource.username` and `spring.datasource.password` as per your mysql installation

**4. Build and run the app using maven (springbootmongodb)**

```bash
mvn package
java -jar target/springbootmongodb-v1.jar
```

Alternatively, you can run the app without packaging it using -

```bash
mvn spring-boot:run
```

The app will start running at <http://localhost:8080/>.

## Explore Rest APIs

The app defines following CRUD APIs.

    GET /todos
    
    POST /todos
    
    GET /todos/{id}
    
    PUT /todos/{id}
    
    DELETE /todos/{id}

You can test them using postman or any other rest client.

## Learn more

You can find the tutorial for this application on my blog -

<https://bushansirgur.in/spring-boot-and-mongodb-rest-api-crud-tutorial-updated-2021/>

