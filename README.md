# Task-tracker-be-v1
Task Tracker – Streamline task management by allowing administrators to create, assign, and track tasks across users.

A simple, secure, and efficient task management application built using the MERN Stack (MongoDB, Express.js, React.js, and Node.js).

## 🚀 Live Demo

**Demo Credentials**

* Email: `admin@yraviprakash.com`
* Password: `Test@123`

You can create users, assign tasks, track progress, and manage team activities from a centralized dashboard.

---

## 📋 Features

### ✅ User Authentication

* Secure user registration and login
* JWT-based authentication
* Role-based access control

### ✅ Task Management

* Create, update, and delete tasks
* Assign tasks to team members
* Set task priorities and statuses
* Track task progress

### ✅ User Management

* Create and manage users
* Assign tasks to specific users
* View user-specific task lists

### ✅ Dashboard

* Overview of assigned tasks
* Task statistics and summaries
* Easy task tracking interface

### ✅ Responsive Design

* Mobile-friendly UI
* Optimized for desktop and tablet devices

---

## 🌟 Why Choose Our Task Manager?

### Intuitive Interface

Easily create, organize, and track your tasks with a clean and user-friendly experience.

### Real-time Collaboration

Assign tasks and collaborate effectively with your team members.

### Secure & Reliable

User data and authentication are protected using industry-standard security practices.

---

## 🛠️ Tech Stack

### Frontend

* React.js
* React Router
* Axios
* Bootstrap / CSS

### Backend

* Node.js
* Express.js
* JWT Authentication
* Bcrypt.js

### Database

* MongoDB
* Mongoose

---

## 📂 Project Structure

```bash
task-manager/
│
├── client/
│   ├── src/
│   └── public/
│
├── server/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   └── config/
│
├── .env
├── package.json
└── README.md
```

## ⚙️ Installation

### Clone the Repository

```bash
git clone https://github.com/your-username/task-manager.git
cd task-manager
```

### Install Dependencies

Backend:

```bash
npm install
```

Frontend:

```bash
cd client
npm install
```

### Configure Environment Variables

Create a `.env` file inside the server directory:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

### Start Backend

```bash
npm run server
```

### Start Frontend

```bash
cd client
npm run dev
```

---

## 🔐 Authentication

The application uses JSON Web Tokens (JWT) for authentication and authorization.

Protected routes require a valid access token to access resources.

---

## 📸 Screenshots

Add screenshots of:

* Login Page
* Dashboard
* User Management
* Task Management

---

## 🚀 Future Enhancements

* Email notifications
* Task comments
* File attachments
* Activity logs
* Real-time updates using Socket.io
* Team workspaces

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome.

Feel free to fork the repository and submit a pull request.

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Yalavarthi Ravi Prakash**

Built with ❤️ using the MERN Stack.
