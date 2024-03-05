
# Project README

## Project Name: Employee Task Management System 

### Author: Abhijeet Goswami

---

### Overview:

This project is a backend application built using Node.js and Express. It serves as the server-side implementation for a web application, providing functionality for user authentication, employee management, task assignment, and more.

---

### Installation:

1. Clone the repository:

   ```bash
   git clone 
https://github.com/ABHI8769/Employee-Performance-Managment-System.git   cd [project_directory]
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Set up environment variables:

   Create a `.env` file in the project root and define the necessary environment variables.

---

### Project Structure:

- **sourceFiles:**
  - `connectDB.js`: Establishes a connection to the database.
  - `login.js`: Handles user login functionality.
  - `fakeFile.js`: Placeholder file for creating fake users (commented out).
  - `registerUser.js`: Manages user registration.
  - `allEmployees.js`: Retrieves a list of all employees.
  - `addTask.js`: Adds tasks for employees.
  - `getTasksForEmployees.js`: Retrieves tasks assigned to employees.
  - `updateEmployee.js`: Updates employee information.
  - `deleteEmployee.js`: Deletes employee records.

- **Main File:**
  - `app.js`: Entry point of the application.

---

### Usage:

1. Run the application:

   ```bash
   npm start
   ```

2. Access the endpoints:

   - Login: `http://localhost:8181/login`
   - Add Employee: `http://localhost:8181/addEmployee`
   - Get Employees: `http://localhost:8181/getEmployees`
   - Add Task: `http://localhost:8181/addTask`
   - Get Tasks For Employee: `http://localhost:8181/getTasksForEmployee`
   - Update Employee: `http://localhost:8181/updateEmployee`
   - Delete Employee: `http://localhost:8181/deleteEmployee`

---

### Production Deployment:

If in production mode, the application serves the frontend build located in the `frontend/build` directory. Ensure the frontend is properly built before deploying.

