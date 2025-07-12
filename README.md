# Assignment-Week-6
# 🚀 RESTful API - Users CRUD

A simple REST API built with **Node.js**, **Express**, and **MongoDB** to manage users. Supports full CRUD operations.

---
## 📁 Folder Structure

├── models/
│ └── user.js
├── routes/
│ └── userRoutes.js
├── server.js
├── .env
├── .gitignore
├── package.json
└── README.md

---

## 📦 Technologies Used

- Node.js
- Express.js
- MongoDB
- Mongoose
- dotenv
- nodemon (dev)

---

## 🛠️ Setup Instructions

### 1. Clone the Repo

```bash
git clone https://github.com/yourusername/rest-api-users.git
cd rest-api-users

2. Install Dependencies

npm install

3. Configure Environment Variables
Create a .env file in the root:
PORT=5000
MONGO_URI=mongodb://localhost:27017/usersdb

3. Configure Environment Variables
Create a .env file in the root:

PORT=5000
MONGO_URI=mongodb://localhost:27017/usersdb

POST /api/users
Content-Type: application/json

{
  "name": "John Doe",
  "email": "john@example.com",
  "age": 30
}
📄 Get All Users

GET /api/users

✏️ Update User

PUT /api/users/USER_ID
Content-Type: application/json

{
  "age": 31
}
