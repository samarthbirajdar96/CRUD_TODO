## Technologies Used
* Framework: Spring Boot
* Language: Java
* Build Tool: Maven

## Data Flow

The Todo App application follows a structured data flow pattern to handle requests and manage data efficiently:

## Controller

Handles incoming HTTP requests.
Defines API endpoints for adding, retrieving, updating, and deleting todo items.
Delegates requests to the appropriate services.

## Services

Manages core business logic and data processing for todo items.
Interacts with an in-memory list to retrieve and store data.
Validates input data and performs necessary operations before returning results to the Controller.
Handles operations like adding todos, updating todo status, and removing todos.

## Repository

There's no explicit repository in this project, as it operates on an in-memory list of todo items.

## Database Design

This project does not use a traditional database; it uses an in-memory list to simulate data storage.

## Data Structure 

The primary data structure used in this project is a list (ArrayList) to store and manage todo items.
The Todo class defines the structure of a todo item, with fields for todoId, todoName, and todoStatus.

## Project Summary

The Todo App is a simple application built using Spring Boot and Java. It provides a RESTful API for managing todo items, including creating, retrieving, updating, and deleting todos. The project does not involve a traditional database; instead, it uses an in-memory list to store and manage todo items.
