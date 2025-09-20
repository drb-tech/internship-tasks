
# DRB Internship – Backend Task

## Objective

Build a small REST API for a **Route Scheduling System** using Node.js. The task evaluates your ability to design APIs, apply business logic, and structure a clean backend application.

## Requirements

### Framework

* Use **Node.js** with either **Express** or **NestJS**.

### Endpoints to Implement

1. **POST /routes**

   * Add a new route.
   * Payload: `{ startLocation, endLocation, distance, estimatedTime }`

2. **POST /drivers**

   * Add a driver.
   * Payload: `{ id, name, licenseType, availability }`

3. **GET /schedule**

   * Return which driver is assigned to which route.

### Logic

* Each driver can handle only **one active route**.
* Prefer assigning drivers where `availability = true`.
* If no drivers are available, the route should be marked as **unassigned**.
* Use a database of your choice: **SQLite**, **Postgres**, or **MongoDB**.

### Bonus Features

* **GET /drivers/{id}/history**: Return all past routes assigned to a specific driver.
* **Pagination** for **GET /routes**.

## Submission Guidelines

1. Push your code to **GitHub**.
2. Share the repository link in your reply.
3. Include a short **README** inside your repository that explains:

   * Setup instructions
   * Assumptions made
   * Features implemented

## Deadline

* Submit your task by **25/09/2025**.
