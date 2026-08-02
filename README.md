# Project FBD – Freelance Bidding Platform

## 📌 Overview

**Project FBD** is a full-stack web-based **Freelance Bidding Platform** designed to connect clients who need projects completed with users/freelancers who can provide the required services.

The platform provides a structured environment where clients can post and manage projects, users can explore projects and submit bids, and administrators can manage the overall platform. The application includes separate dashboards and functionalities for **Admin, Client, and User** roles.

The project is developed using modern web technologies with a frontend and backend architecture.

---

## 🚀 Features

### 👤 User / Freelancer

* User registration and login
* User profile management
* Browse available projects
* View project details
* Submit bids on projects
* Manage submitted bids
* View user dashboard
* Manage user projects
* Manage subscription/plans

### 🧑‍💼 Client

* Client registration and login
* Client profile management
* Client dashboard
* Post new projects
* Manage posted projects
* Review bids submitted by users
* Manage projects and project requirements

### 👨‍💻 Admin

* Admin dashboard
* Manage registered users
* Manage clients
* Manage projects
* Manage bids
* Manage subscription plans
* Admin profile management
* Centralized platform management

---

## 🛠️ Technology Stack

### Frontend

* React.js
* Vite
* JavaScript
* HTML5
* CSS3
* ESLint

### Backend

* Node.js
* Express.js
* JavaScript

### Database

* MongoDB

### Development Tools

* Git
* GitHub
* npm
* VS Code

---

## 📂 Project Structure

```text
Project_ST_26/
│
├── api/
│   ├── config/
│   │   └── db.js
│   │
│   ├── controller/
│   │   ├── admincontroller.js
│   │   ├── authcontroller.js
│   │   ├── clientcontroller.js
│   │   └── usercontroller.js
│   │
│   ├── model/
│   │   └── model.js
│   │
│   ├── router/
│   │   └── router.js
│   │
│   ├── index.js
│   ├── package.json
│   └── package-lock.json
│
├── ui/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   │   ├── admin/
│   │   │   ├── client/
│   │   │   └── user/
│   │   │
│   │   ├── Aboutus.jsx
│   │   ├── Contactus.jsx
│   │   ├── Home.jsx
│   │   ├── Login.jsx
│   │   ├── Navbar.jsx
│   │   └── Register.jsx
│   │
│   ├── App.jsx
│   ├── main.jsx
│   ├── package.json
│   └── vite.config.js
│
└── Zentora_Synopsis_Corrected.docx
```

---

## ⚙️ Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/abhishekksingh8756/Project-FBD-.git
```

Navigate into the project directory:

```bash
cd Project-FBD-
```

---

### 2. Setup Backend

Navigate to the API directory:

```bash
cd api
```

Install dependencies:

```bash
npm install
```

Start the backend server:

```bash
npm start
```

---

### 3. Setup Frontend

Open another terminal and navigate to the UI directory:

```bash
cd ui
```

Install dependencies:

```bash
npm install
```

Start the frontend development server:

```bash
npm run dev
```

The frontend will then be available through the local development URL provided by Vite.

---

## 🔐 User Roles

The platform is organized into three main user roles:

| Role                  | Main Responsibilities                             |
| --------------------- | ------------------------------------------------- |
| **Admin**             | Manage users, clients, projects, bids, and plans  |
| **Client**            | Post projects, manage projects, and review bids   |
| **User / Freelancer** | Browse projects, submit bids, and manage projects |

---

## 🔄 Application Workflow

```text
                ┌─────────────────┐
                │      User       │
                │    Registers    │
                └────────┬────────┘
                         │
                         ▼
                ┌─────────────────┐
                │     Login       │
                └────────┬────────┘
                         │
             ┌───────────┴───────────┐
             │                       │
             ▼                       ▼
     ┌───────────────┐       ┌───────────────┐
     │    Client     │       │ User/Freelancer│
     │    Dashboard  │       │    Dashboard   │
     └───────┬───────┘       └───────┬────────┘
             │                       │
             ▼                       ▼
     Post & Manage             Browse Projects
        Projects                     │
             │                       ▼
             │                 Submit Bids
             │                       │
             ▼                       │
       Review Bids ◄─────────────────┘
             │
             ▼
       Manage Projects

                 ┌─────────────────┐
                 │      Admin      │
                 │    Dashboard    │
                 └─────────────────┘
                         │
                         ▼
              Manage Platform Data
```

---

## 🎯 Project Objectives

The main objectives of this project are:

* To provide an online platform for freelance project collaboration.
* To allow clients to post and manage projects.
* To enable freelancers/users to find projects and submit bids.
* To provide a dedicated dashboard for different user roles.
* To simplify the process of connecting clients with skilled freelancers.
* To provide administrators with centralized control over platform activities.

---

## 💡 Benefits

* Easy project posting and management.
* Convenient bidding system for freelancers.
* Separate dashboards based on user roles.
* Centralized administration.
* Organized project and bid management.
* User-friendly web interface.
* Full-stack architecture for scalable application development.

---

## 🔮 Future Enhancements

The platform can be further improved by adding:

* Real-time chat between clients and freelancers.
* Online payment integration.
* Advanced project search and filtering.
* Email and notification systems.
* Freelancer ratings and reviews.
* AI-based freelancer recommendations.
* Advanced analytics and reporting.
* Secure authentication using JWT and role-based authorization.
* Project progress tracking.
* Deployment using cloud services.

---

## 👨‍💻 Author

**Abhishek Kumar Singh**

GitHub: [Abhishek Kumar Singh](https://github.com/abhishekksingh8756)

---

## 📄 License

This project is developed for educational and project purposes.
