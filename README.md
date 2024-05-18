#API PRACTISE LIST
1) # Contact API

This project is a simple RESTful API for managing contacts. It provides endpoints for CRUD (Create, Read, Update, Delete) operations on contacts.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Usage](#usage)

## Introduction

The Contact API is designed to simplify the management of contacts. It allows users to perform CRUD operations on contact entities, including creating, reading, updating, and deleting contacts. The API is built using ASP.NET Core and Entity Framework Core for data persistence.

## Features

- **Get All Contacts**: Retrieve a list of all contacts.
- **Get Contact by ID**: Retrieve a contact by its unique identifier.
- **Add Contact**: Create a new contact.
- **Update Contact**: Update an existing contact.
- **Delete Contact**: Remove a contact from the system.

## Technologies Used

- ASP.NET Core
- Entity Framework Core
- Swagger UI

## Getting Started

To get started with the Contact API, follow these steps:

1. Clone this repository to your local machine.
2. Ensure you have the necessary dependencies installed (e.g., .NET Core SDK).
3. Set up your database connection in the `appsettings.json` file.
4. Run the database migrations to create the necessary tables.
5. Build and run the application.

## Usage

Once the Contact API is up and running, you can interact with it using HTTP requests. Below are the available endpoints:

- `GET /api/contact`: Retrieve all contacts.
- `GET /api/contact/{id}`: Retrieve a contact by ID.
- `POST /api/contact`: Create a new contact.
- `PUT /api/contact/{id}`: Update an existing contact.
- `DELETE /api/contact/{id}`: Delete a contact.

You can also explore the API using Swagger UI, which provides an interactive documentation interface.
