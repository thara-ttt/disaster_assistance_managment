# Disaster Assistance Management System (DAMS)

Disaster Assistance Management System (DAMS) is a Python Flask and Node.js-based web application with PostgreSQL for managing disaster assistance. This system allows **Admins**, **Helpers (Donors)**, and **Helpees (Recipients)** to collaborate effectively during disaster events. 

- **Admins** manage disaster events and oversee the system.
- **Helpers** provide resources and assistance for disaster events.
- **Helpees** register for disaster events and request resources.

---

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Clone](#clone)


## Features

- **Disaster Event Management**:
  - Admins can create, update, and manage disaster events.
- **Resource Requests**:
  - Helpees can request resources related to disaster events.
- **Donor Assistance**:
  - Helpers can pledge and provide resources for disaster events.
- **Real-time Collaboration**:
  - Facilitates communication between Admins, Helpers, and Helpees.
- **Code Quality and Testing**:
  - Integrated with SonarQube for code quality analysis.
  - Automated testing with Jest (backend) and Pytest (frontend).

---

## Technologies Used

### **Frontend**
- **Python Flask**: For rendering templates and handling client-side logic.
- **HTML, CSS, JavaScript**: For building the user interface.
- **Bootstrap**: For responsive design.
- **AOS (Animate On Scroll)**: For animations.

### **Backend**
- **Node.js**: For handling server-side logic.
- **Express.js**: For building RESTful APIs.
- **Sequelize ORM**: For interacting with the PostgreSQL database.
- **JWT (JSON Web Tokens)**: For authentication and role-based access control.

### **Database**
- **PostgreSQL**: For storing disaster events, user data, and resource requests.

### **DevOps Tools**
- **Ansible**: For automating deployment and configuration.
- **Docker**: For containerizing the application.
- **GitHub Actions**: For CI/CD workflows.
- **SonarQube**: For code quality and security analysis.
- **AWS EC2**: For hosting the application.

---

## Clone

### Clone the Repository
```sh
git clone https://github.com/thara-ttt/disaster_management_system
```
