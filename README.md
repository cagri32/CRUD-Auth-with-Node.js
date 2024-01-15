# Friend's List Express API

This is a simple Express server application that provides API endpoints for managing a Friend's list. The application supports operations like Create, Retrieve, Update, and Delete on friend details.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [API Endpoints](#api-endpoints)
- [Authentication](#authentication)


## Features

- Create a new friend with details like First name, Last name, Email, and Date of birth.
- Retrieve the list of friends.
- Update friend details.
- Delete a friend from the list.

## Getting Started

 ```git clone https://github.com/cagri32/CRUD-Auth-with-Node.js.git```

### Prerequisites

Before running the application, make sure you have the following installed:

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/) (Node Package Manager)

### Installation

Clone the repository:

   ``` git clone https://github.com/yourusername/friends-list-express-api.git ```

### Install and run:

```
cd friends-list-express-api
npm install
npm start
```


## API Endpoints

### Retrieve All Users

```GET /users/```
Retrieves details of all users.

### Retrieve User by Email
```GET /users/:email```
Retrieves details of a user based on their email ID.

### Create a New User
```POST /users/```
Creates a new user. Requires query parameters:

```
firstName: First name of the user.
lastName: Last name of the user.
email: Email address of the user.
DOB: Date of birth of the user.
```

### Update User Details by Email
```PUT /users/:email```
Updates details of a user based on their email ID. Requires query parameters:

```
firstName: Updated first name (optional).
lastName: Updated last name (optional).
DOB: Updated date of birth (optional).
```

### Delete User by Email
```DELETE /users/:email```
Deletes a user based on their email ID.

Note: Replace :email in the endpoints with the actual email ID.


## Authentication
JWT is used for session-level authentication.
