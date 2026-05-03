# Task-Manager
A web-based Task Management System built with Python and Flask featuring role-based access control (Admin, Manager, Employee), task assignment and tracking, a real-time chat module, and a secure SQL database backend. It helps teams coordinate and manage workflows efficiently.
# TaskManage: Role-Based Task Management System

TaskManage is a full-stack web application designed to streamline project workflows and team communication. Built with **Python** and the **Flask** framework, it provides tailored interfaces for Admins, Managers, and Employees.

## 2. Features

### 1. User Roles & Authentication
*   **Admin:** Full system control, including user management and system configuration.
*   **Manager:** Create, assign, and monitor tasks; view detailed employee performance.
*   **Employee:** View assigned tasks, update progress, and manage personal dashboards.
*   **Security:** Secure password hashing using `bcrypt`.

### 2. Task Management
*   Complete CRUD (Create, Read, Update, Delete) functionality for tasks.
*   Task assignment with status tracking (Pending, In Progress, Completed).

### 3. Real-time Communication
*   Integrated **Chat Module** for real-time discussion between team members.

### 4. Responsive UI
*   Clean, modular frontend built with **Jinja2** templates and custom **CSS/JavaScript**.

## 3. Tech Stack
*   **Backend:** Python 3.11, Flask
*   **Database:** SQLite/SQL (via `schema.sql`)
*   **Authentication:** Bcrypt
*   **Frontend:** HTML5, CSS3, JavaScript, Jinja2

## 4. Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/taskmanage.git](https://github.com/your-username/taskmanage.git)
   cd taskmanage
