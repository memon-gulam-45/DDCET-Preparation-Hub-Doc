# 🚀 DDCET Preparation Hub

> A modern, full-stack web platform designed to help diploma students prepare effectively for the DDCET exam through structured learning, smart practice, and real exam simulation.

🌐 **Live Demo:** https://ddcet-prep-hub.vercel.app/

---

## 🎯 Problem Statement

Preparing for DDCET requires:
- Structured syllabus coverage  
- Consistent practice  
- Real exam simulation  
- Performance tracking  

Most students lack a **single platform** that provides all of this.

---

## 💡 Solution

**DDCET Preparation Hub** provides:
- 📚 Complete theory coverage (24 units)  
- 🧠 Smart practice system  
- 📝 Real exam-like mock tests  
- 📊 Data-driven performance insights  
- 🔥 Engagement features like streak tracking  

---

## ✨ Key Features

### 📚 Learning System
- Complete theory coverage of all subjects & units  
- Clean Markdown-based reading experience  
- Unit-wise structured learning  

---

### 🧠 Practice & Testing
- Unit-wise quizzes for targeted preparation  
- Full-length mock tests (DDCET pattern)  
- Resume capability for interrupted sessions  

---

### 📊 Performance Tracking
- Accuracy tracking  
- Attempt history  
- Visual analytics (charts & graphs)  

---

### 🔐 Authentication System
- Secure Login / Register  
- JWT-based authentication  
- Persistent sessions (up to 30 days)  

---

### 📧 Forgot Password (OTP System)
- Email-based OTP verification using Nodemailer  
- Secure hashed OTP storage  
- Auto-deletion after verification  

---

### 🔥 Engagement System
- Daily streak tracking  
- Motivation-driven UI  

---

### 🎨 UI/UX Highlights
- 3D animated backgrounds (Vanta.js)  
- Smooth animations (Framer Motion)  
- Glassmorphism UI  
- Fully responsive design  

---

### ⚙️ Technical Features
- Progressive Web App (PWA)  
- Offline-ready support  
- Optimized performance  
- Handles **15,000+ users (scalable architecture)**  

---

## 🧭 Product Walkthrough

### 👋 Welcome Experience
- Interactive 3D animated landing page  
- Smart CTA based on device:
  - Android → Download APK  
  - iOS → PWA install guide  
  - Desktop → Continue on Web  

---

### 🔐 Authentication Flow
- User registers / logs in  
- Forgot password via OTP email  
- Protected routes activated after login  

---

### 🏠 Dashboard (Home)
- Personalized greeting  
- Global progress tracking  
- Streak monitoring system  
- Performance overview cards  

---

### 📚 Study Module
- Subject-wise navigation  
- Unit-based learning  
- Markdown-based theory viewer  

#### Smart Learning Logic:
- ⏱️ 30-sec reading requirement before marking complete  
- 🔄 6-hour cooldown for revision  
- 📈 Tracks number of reads per unit  

---

### 🧠 Practice Module

#### 📌 Quizzes
- Unit-based questions  
- No timer (focus on learning)  
- Resume using Local Storage  

#### 📝 Mock Tests
- 100 MCQs | 150 minutes  
- Resume / restart options  
- Real exam simulation  

---

### 📊 Insights Dashboard

- 📈 Quiz Performance Trends (Line Chart)  
- 📊 Mock Test Analysis (Accuracy breakdown)  
- 📚 Theory Completion (Stacked Bar Chart)  
- 📜 Attempt history tracking  

---

## 🏗️ System Architecture

- **Frontend:** React.js + Tailwind CSS  
- **Backend:** Node.js + Express.js  
- **Database:** MongoDB  
- **Communication:** REST APIs  

---

## 🚀 Deployment

- **Frontend:** Vercel  
- **Backend:** Render  
- **Database:** MongoDB Atlas  

---

## 🛠️ Tech Stack

### Frontend
- React.js  
- Tailwind CSS  
- Axios  
- Framer Motion  
- Recharts  
- Swiper  
- KaTeX  
- Lottie  
- Vanta.js  

---

### Backend
- Node.js  
- Express.js  
- MongoDB + Mongoose  
- JWT Authentication  
- Nodemailer  

---

## 📦 Libraries Used

### 🔧 Backend
- bcrypt  
- cookie-parser  
- cors  
- dotenv  
- express  
- jsonwebtoken  
- mongodb  
- mongoose  
- nodemailer  

---

### 🎨 Frontend
- react  
- react-router-dom  
- axios  
- framer-motion  
- recharts  
- swiper  
- katex  
- react-markdown  
- remark-math  
- rehype-katex  
- lottie-react  
- lucide-react  
- sonner  
- vanta  
- tailwindcss  

---

## 📁 Folder Structure

<pre>
├── backend
│   ├── controllers
│   ├── inits (subjects, units, tests)
│   ├── middlewares
│   ├── models
│   ├── routes
│   ├── services
│   └── app.js
│
└── frontend
    ├── public (PWA assets)
    ├── src
    │   ├── components
    │   ├── pages
    │   ├── context
    │   └── assets
    └── App.jsx
</pre>

---

## 🔮 Future Enhancements

### 🎮 Gamification
- XP system  
- Level progression  
- Leaderboards  

---

### 🛠️ Admin Panel
- Manage users  
- Add/edit content  
- Analytics dashboard  

---

### 💰 Monetization
- Subscription system  
- Premium content  
- Advanced analytics  

---

### 🤖 Advanced Features
- AI-based performance analysis  
- Personalized recommendations  
- Doubt-solving system  

---

## 🧠 Learnings & Highlights

- Built a **scalable full-stack system**  
- Designed **real exam simulation logic**  
- Implemented **secure auth with OTP flow**  
- Created **data-driven analytics dashboards**  
- Focused on **UX + performance optimization**  

---

## ⚠️ Important Note

> Ensure **third-party cookies are enabled** in your browser.  
> Otherwise, authentication and core features may not function properly.

---

## 📘 About This Repository

> ⚠️ This is a **Documentation Repository**.

The actual source code is kept **private**.

If you are:
- 💼 HR / Recruiter  
- 🤝 Contributor  
- 👨‍💻 Developer interested in collaboration  

📩 Contact: **memongulam45@gmail.com**

---

## 👨‍💻 Author

**Gulam Mohyudin Memon**  
*Full Stack Web Developer*

> Passionate about building impactful educational platforms with modern technologies and clean user experiences.

---

## ⭐ Support

If you found this project useful:
- ⭐ Star the repo  
- 📢 Share with others  
- 🤝 Reach out for collaboration  

---
