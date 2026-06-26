# Course Management Dashboard API

A simple REST API built with **JSON Server** and deployed on **Railway** to serve the Course Management Dashboard frontend application.

## Features

* Get all courses
* Get a course by ID
* Create a new course
* Update an existing course
* Delete a course
* Persistent JSON-based database

## Tech Stack

* JSON Server
* Node.js
* Railway

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/omaremad20/Course-Management-Dashboard-Backend.git
```

### 2. Install dependencies

```bash
npm install
```

### 3. Start the server

```bash
npm run start
```

The API will be available at:

```text
http://localhost:3000
```

## Available Endpoints

| Method | Endpoint       | Description         |
| ------ | -------------- | ------------------- |
| GET    | `/courses`     | Get all courses     |
| GET    | `/courses/:id` | Get a course by ID  |
| POST   | `/courses`     | Create a new course |
| PUT    | `/courses/:id` | Update a course     |
| DELETE | `/courses/:id` | Delete a course     |

## Database

All data is stored inside:

```text
db.json
```

## Live API

https://course-management-dashboard-backend-production.up.railway.app

## License

This project is intended for assesment and portfolio purposes.

## Live Demo Using API

https://course-management-panel.vercel.app/list

## Github repo 

https://github.com/omaremad20/Course-Management-Dashboard.git