﻿# Django-Python-Machine-Test
# Project Name

A brief description of your project goes here. This could include the purpose of the project, its main features, and any relevant background information.

The task is to design APIS for the machine test using any REST framework

## Table of Contents

1. [Getting Started](#getting-started)
2. [Prerequisites](#prerequisites)
3. [Installation](#installation)
4. [Usage](#usage)
5. [API Endpoints](#api-endpoints)

## Getting Started

These instructions will help you set up and run the project on your local machine for development and testing purposes.

## Prerequisites

- **Python 3.x**: Make sure you have Python 3 installed.
- **PostgreSQL**: The project uses PostgreSQL as the database. You need to have PostgreSQL installed and running on your machine.

### Postgres SQL 
Passwaord : postgres@01

### Superuser :- details

username : admin

Email address: tejasvmehetre@gmail.com

Password : Test@1234


### Database Configuration

Before running the project, ensure you have the correct PostgreSQL configuration:

- **Database Name**: `postgres`
- **Username**: `postgres`
- **Password**: `root`

## Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/pradeep8577/machine_test_api.git
   cd machine_test_api
   ```

## Run database migrations:

   ```
   python manage.py migrate
   ```

## Start the development server:
   ```
   python manage.py runserver
   ```

## Usage
To use the application, open your web browser and navigate to:
   ```
   http://127.0.0.1:8000/
   ```

# You can also use tools like Postman to interact with the API.
API Endpoints
Here are some API endpoints you can use to interact with the application:
### http://127.0.0.1:8000/api/clients/
### http://127.0.0.1:8000/api/projects/


List all clients:
GET /api/clients/

Create a new client:
POST /api/clients/

Retrieve a client:
GET /api/clients/:id

Update a client:
PUT /api/clients/:id

Delete a client:
DELETE /api/clients/:id

Create a new project:
POST /api/clients/:id/projects/

List all projects for the logged-in user:
GET /api/projects/

#   M a c h i n e _ T e s t  
 