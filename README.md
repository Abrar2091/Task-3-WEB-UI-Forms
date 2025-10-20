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

# Task 4: Web UI Forms
# Overview
This project implements a web-based user interface (UI) for interacting with the backend application developed in Task-1 or Task-2.
The frontend allows users to create, view, update, and delete records through an intuitive web interface built with React.js.
All operations are connected to a MongoDB database via RESTful API endpoints.

# Features
Create new records using a web form
View all stored records
Retrieve specific records by ID
Update record details
Delete records

# Real-time data updates synchronized with MongoDB
Contents
MongoDB Compass UI view
Adding a record (Actor)
Viewing created records
Deleting a record
Updating record details
API testing using Postman
MongoDB Database
Project Folder Structure
Postman API Testing
Add Data
Get All Data
Get Data by ID
Update Data
Delete Data by ID
Update Mobile Number
React.js User Interface Demonstration
View All Data
Register New Data
View Specific Data
Update Specific Data

<img width="1919" height="1007" alt="Screenshot 2025-10-20 181730" src="https://github.com/user-attachments/assets/4a25f182-3c24-4f94-bfaa-14c70e3c67d1" />
<img width="1919" height="979" alt="Screenshot 2025-10-20 181658" src="https://github.com/user-attachments/assets/cc05edcc-c0ec-4d0a-94df-c68c5a399af3" />
<img width="1919" height="955" alt="Screenshot 2025-10-20 182228" src="https://github.com/user-attachments/assets/6289cd28-2515-4926-a233-ecc8f69cbf1b" />
<img width="1919" height="852" alt="Screenshot 2025-10-20 182133" src="https://github.com/user-attachments/assets/c6a03e02-4abb-4cd6-8302-513569607045" />
<img width="1919" height="1010" alt="Screenshot 2025-10-20 182024" src="https://github.com/user-attachments/assets/05400b09-15c2-469d-93e6-38549b62ed17" />
<img width="1915" height="1001" alt="Screenshot 2025-10-20 182005" src="https://github.com/user-attachments/assets/7b0f7382-99db-464d-9efb-e81313e06a20" />
<img width="1919" height="1006" alt="Screenshot 2025-10-20 181947" src="https://github.com/user-attachments/assets/9c4911a9-5072-44f7-b025-e3989a82cf5c" />
<img width="1919" height="1008" alt="Screenshot 2025-10-20 181933" src="https://github.com/user-attachments/assets/d767cf6e-a3d0-4c8f-8292-5d2dad56912a" />
<img width="1919" height="1008" alt="Screenshot 2025-10-20 181920" src="https://github.com/user-attachments/assets/50828322-e2cd-4c94-a28d-18d4443b3071" />
<img width="1919" height="1002" alt="Screenshot 2025-10-20 181759" src="https://github.com/user-attachments/assets/a47b9ff7-fda0-42de-abd9-90e2ef804126" />



