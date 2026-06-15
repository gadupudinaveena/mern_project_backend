# MERN Backend CRUD API

A simple backend application built using **Node.js**, **Express.js**, **MongoDB**, and **Mongoose**. This project provides RESTful APIs for performing CRUD (Create, Read, Update, Delete) operations on user data.

##  Features

* Create a new user
* Get all users
* Update user details
* Delete a user
* MongoDB database integration
* RESTful API architecture
* Tested using Postman

## 🛠️ Technologies Used

* Node.js
* Express.js
* MongoDB
* Mongoose
* CORS
* Postman

##  Project Structure

```text
mern-backend/
│
├── index.js
├── db.js
├── User.js
├── package.json
└── node_modules/
```

##  API Endpoints

### Get All Users

```http
GET /users
```

### Create User

```http
POST /users
```

Request Body:

```json
{
  "name": "Naveena",
  "email": "naveena@gmail.com",
  "age": 21
}
```

### Update User

```http
PUT /users/:id
```

Request Body:

```json
{
  "name": "Naveena Updated",
  "email": "naveena@gmail.com",
  "age": 25
}
```

### Delete User

```http
DELETE /users/:id
```

## ⚙️ Installation

Clone the repository:

```bash
git clone <repository-url>
```

Navigate to the project folder:

```bash
cd mern-backend
```

Install dependencies:

```bash
npm install
```

Start the server:

```bash
node index.js
```

Server runs on:

```text
http://localhost:5000
```

##  Learning Outcomes

This project demonstrates:

* REST API development with Express.js
* MongoDB integration using Mongoose
* CRUD operations
* Backend application structure
* API testing with Postman

##  Author

Naveena
