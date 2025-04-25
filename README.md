# 🧑‍💼 Employee Management System

A full-stack Employee Management System built with **React** (frontend) and **Spring Boot** (backend). This application allows you to manage employees by performing operations like adding, updating, deleting, and viewing employees in a structured and efficient way.

## 🚀 Features

### ✅ Frontend (React)
- View a list of all employees
- Add a new employee
- Edit employee details
- Delete an employee
- Responsive and user-friendly interface using Bootstrap

### ⚙️ Backend (Spring Boot)
- RESTful API endpoints for CRUD operations
- Integration with MySQL/PostgreSQL
- Spring Data JPA for data persistence
- Exception handling and validation

## 🛠️ Tech Stack

| Layer         | Technology            |
| ------------- | --------------------- |
| Frontend      | React, Bootstrap      |
| Backend       | Spring Boot, Spring MVC, Spring Data JPA |
| Database      | MySQL or PostgreSQL   |
| Build Tools   | Maven, npm            |

## 🧹 Project Structure

```
employee-management/
├── backend/
│   ├── src/
│   └── pom.xml
├── frontend/
│   ├── src/
│   └── package.json
```

## 📦 Installation

### Prerequisites
- Node.js & npm
- Java 17+
- Maven
- MySQL/PostgreSQL

### 1. Clone the repository

```bash
git clone https://github.com/your-username/employee-management.git
cd employee-management
```

### 2. Backend Setup

```bash
cd backend
# Configure database credentials in application.properties
mvn spring-boot:run
```

### 3. Frontend Setup

```bash
cd frontend
npm install
npm start
```

Frontend will run at: `http://localhost:3000`  
Backend API runs at: `http://localhost:8080`

## 🥪 API Endpoints

| Method | Endpoint         | Description         |
|--------|------------------|---------------------|
| GET    | `/api/employees` | Get all employees   |
| GET    | `/api/employees/{id}` | Get employee by ID |
| POST   | `/api/employees` | Add new employee    |
| PUT    | `/api/employees/{id}` | Update employee    |
| DELETE | `/api/employees/{id}` | Delete employee    |

## 🙌 Contributing

Feel free to fork this repo and open a pull request with your changes.

## 📃 License

This project is licensed under the [MIT License](LICENSE).

---

> Made with 💻 by Christian

