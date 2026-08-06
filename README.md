<h1 align="center">
  🚀 Project Manager App
</h1>

<p align="center">
  <strong>A full-stack project management application built with the modern MERN stack.</strong>
</p>

<div align="center">
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/Express.js-404D59?style=for-the-badge" alt="Express.js" />
  <img src="https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB" />
  <img src="https://img.shields.io/badge/Vite-B73BFE?style=for-the-badge&logo=vite&logoColor=FFD62E" alt="Vite" />
</div>

<br />

## 🌟 Features

- 🔐 **Secure Authentication**: User signup and login powered by JWT and bcrypt.
- ⚡ **Lightning Fast Frontend**: Built with React 19 and Vite for an optimal development and user experience.
- 🗄️ **Robust Database**: MongoDB integration via Mongoose for seamless data modeling and queries.
- 🌐 **RESTful API**: A well-structured Express.js backend handling all business logic and data processing.

## 🛠️ Tech Stack

### Frontend
- **React 19**
- **Vite**
- **Axios** (for API requests)

### Backend
- **Node.js & Express.js**
- **MongoDB & Mongoose**
- **JWT (JSON Web Tokens)** & **Bcrypt.js** (Auth & Security)
- **Dotenv** & **CORS**

---

## 🚀 Getting Started

Follow these instructions to get a copy of the project up and running on your local machine.

### Prerequisites

- [Node.js](https://nodejs.org/en/) (v16 or higher)
- [MongoDB](https://www.mongodb.com/) installed locally or a MongoDB Atlas URI.

### 1. Installation & Setup

Clone the repository and navigate into the project folder:

```bash
git clone https://github.com/SrushtiGV/project-manager-app.git
cd project-manager-app
```

### 2. Backend Setup

Open a terminal and navigate to the `backend` directory:

```bash
cd backend
npm install
```

Create a `.env` file in the `backend` directory and add the following:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

Start the backend server:

```bash
npm start
```
*The server should now be running on `http://localhost:5000`.*

### 3. Frontend Setup

Open a new terminal window and navigate to the `frontend` directory:

```bash
cd frontend
npm install
```

Start the development server:

```bash
npm run dev
```
*The frontend should now be running and accessible via the local URL provided by Vite.*

---

## 🤝 Contributing

Contributions, issues, and feature requests are always welcome! Feel free to check the issues page if you want to contribute.

## 📝 License

This project is open-source and licensed under the **ISC** License.
