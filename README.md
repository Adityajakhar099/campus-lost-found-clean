# 🎒 Campus Lost & Found

A full-stack **Campus Lost & Found system** that helps students report, find, and recover lost items using **Google Authentication**, **real-time dashboards**, and **AI-generated claim verification questions**.

---

## 🚀 Live Demo

- **Frontend (Vercel)**  
  👉 https://campus-lost-found-clean.vercel.app/ 

- **Backend (Render)**  
  👉 https://campus-lost-found-se43.onrender.com  

---

## 🧩 Tech Stack

### Frontend
- React (Create React App)
- React Router
- CSS (custom modern UI)
- Deployed on **Vercel**

### Backend
- Node.js
- Express.js
- MongoDB (Atlas)
- Passport.js (Google OAuth 2.0)
- Sessions with cookies
- Deployed on **Render**

### AI Integration
- Google Gemini API  
  Used to generate **dynamic claim verification questions**

---

## 🔐 Authentication Flow

- Login via **Google OAuth**
- Secure session-based authentication
- Only authenticated users can access the dashboard
- Auto redirect after login/logout

---

## 📊 Key Features

- 📝 Report Lost Items  
- 📦 Report Found Items  
- 🔍 Browse all campus items  
- 🤝 Claim found items with AI-generated questions  
- 📈 Dashboard with user stats  
- 👤 User profile & activity tracking  
- 🔒 Secure Google login  

---

## 🗂️ Project Structure

campus-lost-found-clean/
│
├── app1/ # Frontend (React)
│ ├── public/
│ ├── src/
│ └── package.json
│
├── backend/ # Backend (Node + Express)
│ ├── models/
│ ├── routes/
│ ├── config/
│ ├── utils/
│ └── server.js
│
└── README.md

yaml
Copy code

---

## ⚙️ Environment Variables

### Frontend (`Vercel`)
REACT_APP_API_URL=https://campus-lost-found-se43.onrender.com

shell
Copy code

### Backend (`Render`)
FRONTEND_URL=https://campus-lost-found-five.vercel.app
GOOGLE_CLIENT_ID=your_client_id
GOOGLE_CLIENT_SECRET=your_client_secret
MONGO_URI=your_mongodb_uri
SESSION_SECRET=your_session_secret
GEMINI_API_KEY=your_gemini_key
NODE_ENV=production

yaml
Copy code

---

## 🛠️ Local Setup

### Clone the repo
```bash
git clone https://github.com/Adityajakhar099/campus-lost-found-clean.git
cd campus-lost-found-clean
Frontend
bash
Copy code
cd app1
npm install
npm start
Backend
bash
Copy code
cd backend
npm install
node server.js
🧠 Learning Outcomes
OAuth 2.0 integration with Google

Session-based authentication

Full-stack deployment (Vercel + Render)

Handling SPA routing (React Router)

Real-world debugging & deployment workflows

👨‍💻 Author
Aditya Jakhar
2nd Year CSE Student
Passionate about Full-Stack Development 🚀

⭐ If you like this project
Give it a ⭐ on GitHub — it really helps!

## 2️⃣ `app1/README.md` (optional but clean)

👉 path:
app1/README.md

shell
Copy code

Simple sa rakho:

```md
# Campus Lost & Found – Frontend

React frontend for the Campus Lost & Found system.

## Tech
- React
- React Router
- CSS
- Google OAuth redirect handling

## Deployed on
Vercel

git add README.md app1/README.md
git commit -m "docs: add complete project README"
git push
