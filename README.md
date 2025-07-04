# 💼 Job Portal

A full-stack **Job and Internship Portal** connecting job seekers with employers. This platform allows employers to post jobs and internships, and applicants to register, search, and apply. It also features a dashboard for both users and admins to manage activity efficiently.

> 🚀 Live Demo: [View App](https://job-portal-wudv.onrender.com/)  
> 📦 Repository: [GitHub](https://github.com/Addii155/Job-Portal)

---

## 📚 Table of Contents

- [Features](#features)
- [Screenshots](#screenshots)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Folder Structure](#folder-structure)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## ✨ Features

✅ User authentication with JWT (Register/Login)  
✅ Role-based access (Employer / Job Seeker / Admin)  
✅ Job posting & management (CRUD)  
✅ Real-time job application tracking  
✅ Dynamic search & filter for jobs  
✅ Responsive UI (Mobile & Desktop)  
✅ Admin panel to manage jobs, users, and applications  
✅ RESTful API integration

---

## 🖼️ Screenshots

| Home Page | Job Listing | Application Form |
|-----------|-------------|------------------|
| ![home](./screenshots/home.png) | ![jobs](./screenshots/jobs.png) | ![apply](./screenshots/apply.png) |

> Add your screenshots in a `/screenshots` folder and update the paths above.

---

## 🛠️ Tech Stack

### 💻 Frontend:
- React.js
- Redux Toolkit
- Tailwind CSS
- Axios

### 🌐 Backend:
- Node.js
- Express.js
- MongoDB + Mongoose
- JWT for authentication
- bcrypt.js for password hashing

### 📦 Dev Tools:
- Postman
- Git & GitHub
- Render (Deployment)
- VS Code

---

## 🧪 Installation

```bash
# Clone the repo
git clone https://github.com/Addii155/Job-Portal.git
cd Job-Portal

# Install dependencies for both client & server
cd client
npm install
cd ../server
npm install

# Start backend server
npm run dev

# Start frontend
cd ../client
npm run dev
