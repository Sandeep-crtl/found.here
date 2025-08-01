# 🧭 Found.Here – Lost & Found Web Application

**Found.Here** is a full-stack MERN web application that allows users to report, find, and track lost or found gadgets. Whether you've misplaced your phone or discovered someone else's device, this platform helps connect finders and seekers quickly and efficiently.

(client/public/found-here-banner.png)

## 🔗 Live Demo

🚀 [Live Site](https://found-here.onrender.com/)  
📂 [GitHub Repo](https://github.com/Sandeep-crtl/found.here)

---

## 🛠️ Tech Stack

**Frontend:**
- React.js
- Tailwind CSS
- JavaScript
- HTML/CSS

**Backend:**
- Node.js
- Express.js
- MongoDB (Mongoose)

**Tools & Libraries:**
- Multer (File Uploads)
- JWT (Authentication)
- MongoDB Atlas (Database)
- Vercel & Render (Deployment)
- Git & GitHub (Version Control)

---

## ✨ Features

- 📌 Report found gadgets with details, image, and location.
- 🔍 Search for lost items by type and location.
- 🔐 User authentication and secure routes.
- 🧠 Photo + location-based item matching logic.
- 📂 Admin dashboard to manage all reported items.
- 🌐 Fully responsive design (mobile & desktop).
- 📧 Email alert system for matched items (coming soon).

---

## 📁 Project Structure
found.here/
├── backend/ # Node.js + Express API
│ ├── controllers/
│ ├── models/
│ ├── routes/
│ ├── uploads/
│ ├── .env
│ └── server.js
├── client/ # React + Tailwind frontend
│ ├── public/
│ ├── src/
│ │ ├── components/
│ │ ├── pages/
│ │ ├── App.js
│ │ └── index.js
├── .gitignore
├── README.md
└── package.json

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Sandeep-crtl/found.here.git
cd found.here
cd backend

npm install
npm start

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret

cd ../client
npm install
npm run dev

🔐 Admin Access
Admins can view and manage all submitted items.
Route: /api/admin/items/:type
Secured using JWT authentication.


---

### ✅ Instructions:
- Update:
  - Screenshot paths (`client/public/…`)
  - Deployment link
  - MongoDB URI and JWT secret in `.env`
  - Your real email, LinkedIn, portfolio
- Add your actual screenshots in `client/public/` and rename the files if needed.

Let me know if you want me to create a light version, dark mode support badge, or project status section!
