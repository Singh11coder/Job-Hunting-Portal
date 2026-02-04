# MERN_Job_Portal_Application

## 💼 Full-Stack Job Portal with Authentication & Role-Based Access

A **production-ready Job Portal** built using the **MERN stack**, enabling job seekers to discover and apply for jobs while allowing recruiters to manage companies, post jobs, and track applications — all secured with **JWT authentication** and optimized **RESTful APIs**.

---

## 🌟 Features

### 👤 User Authentication & Profiles

- **JWT-Based Authentication**
  - Secure login and registration
  - Protected routes using middleware
  - Password hashing with bcrypt

- **User Profile Management**
  - Profile creation and updates
  - Resume / profile photo uploads
  - Cloud-based storage integration

- **Role-Based Access Control (RBAC)**
  - Job Seekers and Recruiters
  - Separate permissions and dashboards

---

### 🏢 Company Management (Recruiter)

- **Company Registration**
  - Create and manage company profiles
  - Upload and update company logos

- **Company Dashboard**
  - View all registered companies
  - Update company details securely

- **Access Protection**
  - Auth-protected recruiter routes
  - Middleware-driven authorization

---

### 📌 Job Listings & Search

- **Job Posting**
  - Recruiters can create and manage job listings
  - Define job requirements and metadata

- **Advanced Job Search**
  - Keyword-based search
  - Real-time filtering
  - Optimized MongoDB aggregation queries

- **Responsive Job Feed**
  - Mobile-friendly layout
  - Fast loading job listings

---

### 📄 Job Applications & Tracking

- **Apply for Jobs**
  - One-click job application flow
  - Auth-protected job submissions

- **Application Tracking**
  - Job seekers can view applied jobs
  - Recruiters can view applicants per job

- **Application Status Management**
  - Pending / Accepted / Rejected
  - Recruiter-controlled status updates

---

### ☁️ File Uploads & Cloud Storage

- **Multer Middleware**
  - Secure file uploads
  - File validation before processing

- **Cloudinary Integration**
  - Optimized image storage
  - Reduced server storage usage
  - Fast CDN-based image delivery

---

## 🛠️ Technologies Used

### Frontend
- **Framework:** React.js
- **State Management:** Redux Toolkit
- **Routing:** React Router
- **Styling:** Tailwind CSS
- **Forms & Validation:** React Hook Form
- **Notifications:** Sonner Toasts

### Backend
- **Runtime:** Node.js
- **Framework:** Express.js
- **Authentication:** JWT
- **Security:** bcrypt password hashing
- **File Uploads:** Multer
- **Cloud Storage:** Cloudinary

### Database
- **Database:** MongoDB
- **ODM:** Mongoose
- **Queries:** Aggregation Pipelines

---
```md
> All API routes are protected using JWT-based authentication middleware.
```

## 📂 API Routes Overview

### 👤 User Routes
```http
POST   /api/v1/user/register
POST   /api/v1/user/login
GET    /api/v1/user/logout
POST   /api/v1/user/profile/update
GET    /api/v1/user/logout
POST   /api/v1/user/profile/update
```
### 🏢 Company Routes
```http
POST   /api/v1/company/register
GET    /api/v1/company/get
GET    /api/v1/company/get/:id
PUT    /api/v1/company/update/:id

```

### 📄 Application Routes
```http
GET    /api/v1/application/apply/:id
GET    /api/v1/application/get
GET    /api/v1/application/:id/applicants
POST   /api/v1/application/status/:id/update
```

### 📄 Application Routes
```http
GET    /api/v1/application/apply/:id
GET    /api/v1/application/get
GET    /api/v1/application/:id/applicants
POST   /api/v1/application/status/:id/update
```

### 📌 Job Routes
```http
POST   /api/v1/job/post
GET    /api/v1/job/get
GET    /api/v1/job/getadminjobs
GET    /api/v1/job/get/:id

```


