# Co-Founder Search Platform (MVP)

A full-stack web application for discovering and filtering co-founder candidates.
Built with React, Express.js, and PostgreSQL.

![Tech Stack](https://img.shields.io/badge/React-19-blue)
![Node.js](https://img.shields.io/badge/Node.js-Express-green)
![PostgreSQL](https://img.shields.io/badge/Database-PostgreSQL-blue)
![License](https://img.shields.io/badge/license-MIT-green)

--- 

## Features

-  **User Authentication** — Signup/signin with bcrypt password hashing
-  **Advanced Filtering** — 40+ filters: age, gender, location, skills, interests & more
-  **Responsive Design** — Works seamlessly on desktop and mobile
-  **Dark/Light Theme** — Toggle between themes
-  **VPN Blocking** — Optional middleware to block VPN users
-  **Admin Panel** — Manage candidate levels with batch updates
-  **Pagination** — Efficiently handles large datasets

---

## Tech Stack

| Layer      | Technology                        |
|------------|-----------------------------------|
| Frontend   | React 19, Axios, React Router, CSS3 |
| Backend    | Node.js, Express.js               |
| Database   | PostgreSQL                        |
| Auth       | bcryptjs                          |
| API Style  | REST                              |

---

## Getting Started

### Prerequisites
- Node.js v14+
- PostgreSQL v12+
- npm or yarn

### 1. Clone the repo
```bash
git clone https://github.com/YOUR_USERNAME/cofounder-search-mvp.git
cd cofounder-search-mvp
```

### 2. Set up the backend
```bash
cd server
npm install
cp .env.example .env   # Fill in your values
```

### 3. Create the database
```bash
createdb candidate
npm run migrate
```

### 4. Set up the frontend
```bash
cd ../client
npm install
```

### 5. Run the app
```bash
# Terminal 1 — Backend
cd server && npm run dev

# Terminal 2 — Frontend
cd client && npm start
```

- Frontend: http://localhost:3000
- Backend API: http://localhost:4000

---

## Project Structure
