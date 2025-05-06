# 🚀 NestJS Project Ideas by Skill Level

This list provides a curated roadmap of backend project ideas using **NestJS**, categorized by skill level from beginner to advanced. Each project is designed to help you learn real-world skills, including Prisma, TypeORM, authentication, file uploads, RBAC, microservices, and more.

---

## 🟢 Beginner Projects (Easy)
> Focus: CRUD operations, modules/controllers/providers, Prisma or TypeORM

### ✅ Task Manager API
- Full CRUD operations for tasks (create, update, delete)
- Task filtering by status
- User authentication using JWT
- **Tech Stack**: NestJS, Prisma, PostgreSQL

---

### ✅ Blog Platform (Backend Only)
- Manage posts, categories, and comments
- User registration and login
- Public and private routes
- Admin-only endpoints

---

### ✅ Library System
- Entities: Books, Authors, Borrowers
- Relationships: One-to-Many, Many-to-Many
- Implement basic search and pagination

---

## 🟡 Intermediate Projects (Real-world Use Cases)
> Focus: Authentication, RBAC, file uploads, guards, middlewares

### 📋 User Management System
- Roles: Admin, User
- Email verification + password reset
- Social login using Google OAuth
- Upload & update user profile pictures

---

### 🎓 Course Enrollment API
- Manage Courses, Sections, Lessons
- Student enrollment system
- Role-based access for Instructor vs Student
- Upload PDFs/videos using Multer

---

### 📝 Quiz & Assessment Platform
- Create and manage MCQ quizzes
- Auto-grading logic
- Timed exam sessions
- Track student score history

---

### 🏢 Multi-Tenant SaaS Boilerplate
- Each tenant has a unique subdomain
- Tenant-specific branding (name, theme, colors)
- Middleware for subdomain detection

---

## 🔴 Advanced Projects (Startup-Grade)
> Focus: Scalability, microservices, queues, websockets, payments

### 📅 Live Class Scheduler with Notifications
- Create and join Zoom/Google Meet sessions via API
- Schedule live classes
- Send email/SMS notifications (SMTP, Twilio)

---

### 🏆 Gamified Learning API
- Track points, badges, streaks, leaderboards
- Award logic for specific actions
- Real-time updates with WebSockets

---

### 🧑‍💻 Online Exam Proctoring System
- Webcam recording integration (with frontend)
- Screen/tab switch detection
- Timer, session logs, and cheating alerts (AI placeholder)

---

### 🛒 E-Learning Marketplace
- Instructor earnings dashboard
- Subscription model & payment history
- Role-based permissions: Admin / Instructor / Student
- Payment gateways: Vodafone Cash, Fawry (mock or Paymob APIs)

---

### 🧱 Modular Monorepo for Microservices
- Split services: Users, Courses, Exams, Payments
- Gateway API using REST or GraphQL
- Inter-service communication via RabbitMQ or Kafka

---

## ✅ Recommended Tools & Libraries
- ORM: [Prisma](https://www.prisma.io/) / [TypeORM](https://typeorm.io/)
- Auth: [Passport](https://docs.nestjs.com/security/authentication) + JWT
- Uploads: [Multer](https://github.com/expressjs/multer)
- Queue: [BullMQ](https://docs.bullmq.io/) / [RabbitMQ](https://www.rabbitmq.com/)
- Realtime: [Socket.IO](https://socket.io/)
- Payment: [Paymob API](https://docs.paymob.com/)

---

## 📌 Contributing

Feel free to fork and build any of the projects listed here. PRs are welcome if you’d like to contribute a boilerplate or example repository.

---

## 🧠 Stay Curious. Keep Building!
