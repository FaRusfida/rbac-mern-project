# RBAC MERN App - Capstone Project  
**23CSP-339 Full Stack-I**  
Chandigarh University | 2023-27 Batch

---

## Live Demo  
- **Frontend**: `https://rbac-mern-project.vercel.app` *(to be deployed)*  
- **Backend**: `https://rbac-mern-backend.onrender.com` *(to be deployed)*  

---

## Features  
- **JWT + httpOnly Cookie Authentication**  
- **3 Roles**: Viewer (Read), Editor (CRUD own), Admin (CRUD all)  
- **Ownership-based Edit/Delete**  
- **Full CRUD with Modal Forms**  
- **Responsive Bootstrap UI**  
- **Auto-login on refresh**  

---

## Tech Stack  
| Layer | Technology |
|------|------------|
| Frontend | React.js, Vite, React Router, Bootstrap CDN |
| Backend | Node.js, Express.js |
| Database | MongoDB (Local / Atlas) |
| Auth | JWT, js-cookie |
| Tools | VS Code, Postman, Git, Vercel, Render |

---

## Project Structure  
rbac-mern-project/
├── backend/
│   ├── server.js
|   ├── middleware/auth.js,permissions.js
│   ├── routes/auth.js, posts.js
│   ├── models/User.js, Post.js
│   └── seed.js
├── frontend/
│   ├── src/App.jsx, main.jsx
│   └── index.html
└── .gitignore, README.md


---

## Setup & Run Locally  
```bash
# Backend
cd backend
npm install
node seed.js
npm run dev

# Frontend (new terminal)
cd frontend
npm install
npm run dev