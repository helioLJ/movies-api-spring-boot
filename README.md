# Movie Review Backend API with Java Spring Boot

This repository contains the backend code for a movie review application developed using Java Spring Boot. The application is part of a full-stack development course and serves as the server-side component for managing movie data and reviews.

## Table of Contents

- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
    - [Project Initialization](#project-initialization)
    - [Project Structure](#project-structure)
    - [Running The Project](#running-the-project)
- [Endpoints](#endpoints)
- [Conclusion](#conclusion)

## Introduction

In this project, I have developed a backend API for a movie review application. The backend is responsible for managing movie data and reviews and exposes various endpoints to interact with the application's data.

## Stack Used

- [JDK (Java Development Kit)](https://www.oracle.com/java/technologies/javase-downloads.html)
- [IntelliJ IDEA](https://www.jetbrains.com/idea/download/)
- [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) (for database storage)

## Getting Started

### Project Initialization

To initialize the project, follow these steps:

1. Clone this repository to your local machine.
2. Open the project in IntelliJ IDEA.
3. Install any required dependencies.

### Project Structure

The project follows a structured organization to maintain code separation and modularity.

### Running The Project

To run the Spring Boot application, execute the following steps:

1. Configure your MongoDB Atlas connection in the application properties.
2. Start the application.
3. The API will be accessible at `http://localhost:8080`.

## Endpoints

### Movies

```js
http://localhost:8080/api/v1/movies // get all movies
```


```js
http://localhost:8080/api/v1/movies/{imdbId} // get one movie
```

### Reviews

```js
POST http://localhost:8080/api/v1/reviews/{imdbId} // post one review to a movie
```

## Conclusion

This concludes the README for the Movie Review Backend API with Java Spring Boot. You can explore the code and endpoints to understand the implementation in more detail.
