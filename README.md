# MERN_Job_Portal_Application With LLM + RAG Integration

## 💼 AI-Powered Full-Stack Job Portal with Authentication & Role-Based Access

A **production-ready Job Portal** built using the **MERN stack**, enhanced with **LLM + RAG architecture and Vector Database**, enabling intelligent job discovery, resume analysis, and personalized recommendations — all secured with **JWT authentication** and optimized **RESTful APIs**.

---
<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/e06a3b82-de01-4b00-9f86-39fc9a3e5f3c" />

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

- **Advanced Job Search (AI-Enhanced)**
  - Keyword-based + **Semantic Search using Vector DB**
  - Real-time filtering
  - Optimized MongoDB aggregation queries
  - Context-aware job discovery using embeddings

- **Responsive Job Feed**
  - Mobile-friendly layout
  - Fast loading job listings

---

### 🤖 AI-Powered Features (LLM + RAG)

- **Resume Analysis (LLM)**
  - Extract skills, experience, and keywords
  - Perform **skill-gap detection** against job descriptions
  - Generate AI-driven improvement suggestions

- **Semantic Search (Vector DB)**
  - Store job and user embeddings in **FAISS / Pinecone**
  - Enable context-based queries instead of keyword-only search

- **Personalized Recommendations (RAG)**
  - Combine **LLM + Vector DB** for relevant job matching
  - Context-aware ranking based on user profile

- **AI Resume & Cover Letter Generator**
  - Generate tailored resumes and cover letters
  - Improve application quality and success rate

- **Recruiter AI Assistant**
  - Auto-summarize candidate profiles
  - Rank applicants based on job fit
  - Reduce manual screening effort

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

### AI / LLM Stack
- **LLM APIs:** OpenAI / Gemini
- **RAG Architecture:** LangChain / Custom Pipeline
- **Vector Database:** FAISS / Pinecone
- **Embeddings:** OpenAI Embeddings / Sentence Transformers

### Database
- **Database:** MongoDB
- **ODM:** Mongoose
- **Queries:** Aggregation Pipelines + Vector Search

---
```md
> All API routes are protected using JWT-based authentication middleware.
