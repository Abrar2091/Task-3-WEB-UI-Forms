# Task 1 – Java REST API
# Overview

This project implements a Java-based RESTful API that allows users to create, retrieve, search, and delete “server” objects.
The application is built using Spring Boot and uses MongoDB as the database to store server details.

# API Endpoints
# 1. GET /servers
Description:
Retrieves all server records if no parameters are provided.
If a server ID is passed, it returns the specific server.
Returns 404 if no server is found.

# 2. PUT /servers
Description:
Creates a new server entry using a JSON request body.
Example request:
{
  "name": "my centos",
  "id": "123",
  "language": "java",
  "framework": "django"
}

# 3. DELETE /servers/{id}
Description:
Deletes a server by its unique ID.
Returns 404 if the server does not exist.

# 4. GET /servers/find?name={string}
Description:
Searches for servers by name.
Returns one or more matching servers if their names contain the provided string.
Returns 404 if no matches are found.

# Database
All server objects are stored in a MongoDB database.
You can view and manage the data visually through MongoDB Compass UI.

# Demonstration
The API was tested and verified using Postman and cURL to demonstrate the following actions:
Adding a server
Viewing created servers
Deleting a server
Updating server details