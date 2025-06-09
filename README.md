# 🎓 Study Notion – Full Stack EdTech Platform

**Study Notion** is a full-featured online learning platform that empowers instructors to monetize educational content and enables learners to access high-quality course material. Built using the MERN stack, it offers seamless course creation, secure payments, content hosting, and a polished, responsive UI with real-time dashboards and analytics.



---

## ✨ Features

### 👨‍🏫 Instructor Features
- Create & manage courses, sections, and lectures
- Upload videos securely via Cloudinary
- View course analytics, enrollments & earnings
- Accept secure payments using Razorpay
- Role-based protected instructor dashboard

### 👨‍🎓 Student Features
- Register and browse free or paid courses
- Enroll in courses after secure checkout
- Track course progress with saved video status
- Submit ratings & reviews for enrolled courses
- View personal dashboard with enrolled course data

### 🔐 Authentication & Authorization
- User roles: `Admin`, `Instructor`, `Student`
- Email verification with OTP using Nodemailer
- Secure JWT-based authentication

### 💻 Tech Stack
| Category       | Tech Used                          |
|----------------|------------------------------------|
| Frontend       | React.js, Redux Toolkit, Tailwind CSS |
| Backend        | Node.js, Express.js                |
| Database       | MongoDB                            |
| Authentication | JWT, Nodemailer                    |
| File Storage   | Cloudinary                         |
| Payments       | Razorpay                           |
