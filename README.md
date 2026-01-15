# Employee Management System

## 📌 Overview

The **Employee Management System (EMS)** is a full-stack web application designed to manage employee records efficiently. It provides complete CRUD (Create, Read, Update, Delete) functionality using **Angular** for the frontend and **Spring Boot** for the backend.

This system is suitable for small to medium-sized organizations to maintain employee data in a centralized and user-friendly platform.

---

## 🚀 Features

* Add new employees
* View employee list
* Update employee details
* Delete employee records
* RESTful API integration
* Responsive and user-friendly UI

---

## 🛠️ Tech Stack

### Frontend

* Angular
* TypeScript
* HTML5 & CSS3
* Bootstrap

### Backend

* Java
* Spring Boot
* Spring Data JPA
* REST APIs

### Database

* MySQL / H2 (configurable)

---

## 📂 Project Structure

### Backend (Spring Boot)

```
backend/
 ├── controller
 ├── service
 ├── repository
 ├── model
 └── EmployeeManagementApplication.java
```

### Frontend (Angular)

```
frontend/
 ├── src/app
 │   ├── components
 │   ├── services
 │   └── models
 └── app.module.ts
```

---

## ⚙️ Installation & Setup

### Prerequisites

* Java 17+
* Node.js & npm
* Angular CLI
* MySQL (optional)

### Backend Setup

1. Navigate to the backend directory
2. Configure `application.properties`
3. Run the application

```bash
mvn spring-boot:run
```

### Frontend Setup

1. Navigate to the frontend directory
2. Install dependencies

```bash
npm install
```

3. Start Angular server

```bash
ng serve
```

4. Open `http://localhost:4200`

---

## 🔗 API Endpoints

| Method | Endpoint        | Description        |
| ------ | --------------- | ------------------ |
| GET    | /employees      | Get all employees  |
| GET    | /employees/{id} | Get employee by ID |
| POST   | /employees      | Create employee    |
| PUT    | /employees/{id} | Update employee    |
| DELETE | /employees/{id} | Delete employee    |

