# Decodelab-task2-Ujjwal
SkillForge: Built the Backend
# 🎓 SkillForge LMS Backend API Engine

Built for the SkillForge Learning Management System.

The backend infrastructure responsible for authentication,
course delivery, lesson progression, enrollment handling,
certificate management, and student analytics.

This system transforms SkillForge from a static educational
interface into a complete RESTful Learning Management Platform
powered by Node.js, Express.js, MongoDB, and JWT Authentication.

---

# 📂 Project Architecture Blueprint

```text
backend/
│
├── config/
├── controllers/
├── data/
├── docs/
├── middleware/
├── migrations/
├── models/
├── routes/
├── seed/
├── services/
├── utils/
├── validators/
│
├── server.js
├── package.json
├── .env
└── .env.example
```

# ⚙ Installation & Execution Setup

### 1. Install Dependencies

npm install

### 2. Configure Environment

Create .env

PORT=5000

MONGO_URI=mongodb://127.0.0.1:27017/skillforge_academy

JWT_SECRET=your_secret_key

### 3. Seed Course Data

npm run seed:lessons

### 4. Start Development Server

npm run dev

Expected Output:

MongoDB connected

SkillForge Academy API running on port 5000

---

### 🔐 Authentication System
- User Registration
- User Login
- JWT Authentication
- Protected Routes

### 📚 Course Management
- Course Catalogue APIs
- Course Details APIs
- Module & Lesson Retrieval

### 🎓 Enrollment System
- Student Enrollment
- Course Access Management

### 🎥 Learning System
- Lesson Retrieval
- Module-Based Learning Structure
- Lesson Navigation

### 📈 Progress Tracking
- Lesson Completion Tracking
- Progress Percentage Calculation
- Dashboard Statistics

### 🏆 Certificate System
- Certificate Unlock Logic
- Certificate Retrieval APIs

### 💳 Payment System
- Payment Initialization
- Payment Verification
- Enrollment Activation

### 📬 Communication APIs
- Contact Form API
- Newsletter Subscription API
- Testimonials API
- FAQs API
---

# 🗄 Database Layer

Database: MongoDB

ODM: Mongoose

Collections:

• Users

• Courses

• Modules

• Lessons

• Enrollments

• Progress

• Certificates

---

# 🛠 Technology Stack

Backend Runtime:

• Node.js

Framework:

• Express.js

Database:

• MongoDB

ODM:

• Mongoose

Authentication:

• JWT

• bcryptjs

Development Tools:

• Nodemon

• dotenv

---

# 🔌 REST API Endpoints

## 🔐 Authentication APIs

| Method | Endpoint | Description |
|---------|----------|-------------|
| POST | /api/auth/register | Register new user |
| POST | /api/auth/login | Login user |
| POST | /api/auth/logout | Logout user |

## 📚 Course APIs

| Method | Endpoint | Description |
|---------|----------|-------------|
| GET | /api/courses | Get all courses |
| GET | /api/courses/:id | Get course details |

## 🎓 Enrollment APIs

| Method | Endpoint | Description |
|---------|----------|-------------|
| POST | /api/enrollments | Enroll in course |
| GET | /api/enrollments/user | Get enrolled courses |

## 📖 Lesson APIs

| Method | Endpoint | Description |
|---------|----------|-------------|
| GET | /api/courses/:id/lessons | Get modules & lessons |

## 📈 Progress APIs

| Method | Endpoint | Description |
|---------|----------|-------------|
| GET | /api/progress/dashboard | Dashboard statistics |
| PATCH | /api/progress/lessons/:id/complete | Mark lesson complete |

## 🏆 Certificate APIs

| Method | Endpoint | Description |
|---------|----------|-------------|
| GET | /api/certificates | Get certificates |

## 🌐 Public APIs

| Method | Endpoint | Description |
|---------|----------|-------------|
| GET | /api/faqs | Get FAQs |
| GET | /api/testimonials | Get testimonials |
| GET | /api/stats | Platform stats |
| POST | /api/contact | Contact form |
| POST | /api/newsletter | Newsletter signup |

# 🎯 Learning Outcomes

• REST API Development

• MVC Architecture

• Authentication Systems

• MongoDB Integration

• Service Layer Design

• Learning Progress Management

• Certificate Automation

• Backend Engineering Best Practices

---

# 👨‍💻 Developer

developed for the Full Stack Summer Internship | Backend Development Milestone Completed
