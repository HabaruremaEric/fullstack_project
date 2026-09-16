# My Full-Stack Beginner Project

Welcome to my first full-stack web development project! 🚀

This project is part of my journey to learn **software engineering and full-stack web development**. I am building it step by step while learning how frontend, backend, databases, APIs, Git, and GitHub work together.

## 🛠️ Technologies Used

### Frontend

* React
* JavaScript
* HTML
* CSS
* Vite

### Backend

* Node.js
* Express.js
* REST API

### Database

* MySQL

### Development Tools

* Visual Studio Code
* Git
* GitHub
* npm

## 📁 Project Structure

```text
my-fullstack-app/
│
├── frontend/
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── ...
│
├── backend/
│   ├── server.js
│   ├── db.js
│   ├── package.json
│   └── .env
│
├── database/
│   └── schema.sql
│
├── .gitignore
└── README.md
```

## 🎯 Project Goals

The main goals of this project are to learn how to:

* Build a frontend with React
* Build a backend with Node.js and Express
* Create REST APIs
* Connect a backend to MySQL
* Work with databases and SQL
* Connect React to a backend API
* Use Git for version control
* Use GitHub to store and manage code
* Understand how frontend, backend, and database systems communicate

## 🔗 How the Application Works

The application follows this basic architecture:

```text
┌───────────────┐
│    React      │
│   Frontend    │
└───────┬───────┘
        │
        │ HTTP Requests
        ↓
┌───────────────┐
│ Node.js +     │
│ Express API   │
└───────┬───────┘
        │
        │ SQL Queries
        ↓
┌───────────────┐
│     MySQL     │
│   Database    │
└───────────────┘
```

React handles the user interface, Node.js and Express handle the API and application logic, and MySQL stores the application data.

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/HabaruremaEric/fullstack_project
```

### 2. Enter the project

```bash
cd my-fullstack-app
```

### 3. Install frontend dependencies

```bash
cd frontend
npm install
```

### 4. Install backend dependencies

Open another terminal:

```bash
cd backend
npm install
```

### 5. Configure environment variables

Create a `.env` file inside the `backend` folder:

```env
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=your_password
DB_NAME=fullstack_app
DB_PORT=3306
```

> Do not upload `.env` to GitHub. It is included in `.gitignore` because it can contain private credentials.

### 6. Set up MySQL

Create the database using the SQL file in:

```text
database/schema.sql
```

You can run the SQL commands using MySQL Workbench or the MySQL command line.

### 7. Start the backend

From the `backend` folder:

```bash
node server.js
```

The backend should run on:

```text
http://localhost:5000
```

### 8. Start the frontend

From the `frontend` folder:

```bash
npm run dev
```

Vite will provide a local address, usually:

```text
http://localhost:5173
```

Open that address in your browser.

## 🔐 Security

Sensitive information should never be committed to GitHub.

This project uses `.gitignore` to exclude:

```text
.env
node_modules/
dist/
```

Never publish:

* Database passwords
* API keys
* Authentication secrets
* Private credentials

## 📚 What I Am Learning

This project is helping me practice:

**Frontend**

```text
React → Components → State → API Requests
```

**Backend**

```text
Node.js → Express → Routes → REST API
```

**Database**

```text
MySQL → Tables → SQL → CRUD
```

**Development**

```text
VS Code → Git → GitHub
```

## 🔄 Git Workflow

My basic Git workflow is:

```bash
git status
git add .
git commit -m "Describe my changes"
git push
```

To get the latest changes from GitHub:

```bash
git pull
```

## 🗺️ Future Improvements

As I continue learning, I plan to add:

* User registration
* User login
* Authentication
* CRUD operations
* Better React components
* Form validation
* API error handling
* Database relationships
* Improved UI/UX
* Deployment
* More advanced REST API features

## 👨‍💻 About This Project

This is a learning project created while I am beginning my journey into **software engineering and full-stack web development**.

The project will continue to evolve as I learn new technologies and development practices.

---

⭐ **Thanks for checking out my project!**

More features and improvements are coming as I continue learning and building.
