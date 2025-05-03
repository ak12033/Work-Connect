# 🐝 Work Hive

**Work Hive** is a full-stack job portal application built with the **MERN stack**, providing a platform for job seekers to explore opportunities and for recruiters to manage job postings and applications. It integrates **Clerk** for seamless authentication and **Sentry** for real-time error and performance monitoring.

---

## 📌 Project Overview

- **Job Seekers** can search and apply for jobs, upload resumes, and track the status of their applications.
- **Recruiters** can publish new job openings, manage their postings, and review applications with resume attachments.

---

## ✨ Features

### 🏠 Public Homepage Features

- **Job Search Functionality**
  - Search jobs by title, keyword, or location.
  - Use filters to narrow down results based on categories like job type or sector.

- **Latest Job Posts Display**
  - View a curated list of the most recent job openings.

- **Paginated Job Listings**
  - Seamlessly navigate through multiple pages of job posts.

---

### 👩‍💻 Job Seeker Features

After securely logging in via **Clerk**, job seekers can:

- **Browse and Explore Jobs**
  - Access detailed job descriptions with company information and application criteria.

- **Apply to Jobs**
  - Apply for jobs directly through the portal with an option to upload a resume.

- **Application Tracking**
  - Monitor application statuses: `Pending`, `Accepted`, or `Rejected`.

- **Resume Management**
  - Upload or edit resumes associated with job applications.

---

### 🧑‍💼 Recruiter Features

Recruiters logging in through their dedicated portal can:

- **Post New Job Openings**
  - Create and publish job posts with relevant details such as title, description, location, and job type.

- **Manage Existing Job Posts**
  - View, update, or delete previously created job listings.

- **Review Job Applications**
  - Access a list of received applications for each job posting.
  - View applicant details and attached resumes.
  - Approve or reject applications and update their status for the applicant.

---

## 📊 Application Monitoring & Debugging

**Work Hive** uses **Sentry** for real-time monitoring of application health and error tracking:

- Detects and logs frontend and backend issues.
- Captures performance metrics and runtime errors.
- Sends alerts for production errors and anomalies.

🔗 [Learn more about Sentry](https://sentry.io/)

---

## 🛠️ Tech Stack

| Technology  | Usage |
|:-------------|:----------|
| React.js      | Frontend Development |
| Node.js + Express.js | Backend APIs |
| MongoDB       | Database |
| Clerk         | Authentication |
| Sentry        | Error Monitoring & Performance Tracking |
| Vercel        | Frontend Deployment |
| Vercel        | Backend Deployment |

---

## 🚀 Deployment — Vercel

## 🚀 Live Demo

🌐 Click this: [https://task-pilot-css1.vercel.app/login](https://work-hive-1ack.vercel.app/)

## Getting Started

To get started with the Task-Pilot project, follow these steps:

1. Clone the repository from GitHub:

2. **Set Environment Variables**: Navigate to the `frontend` and `backend` folders and add necessary environment variables. You may need to create a `.env` file and configure it with required variables:
   In the backend/.env file:

   ```
   MONGODB_URI = your-mongo-url
   PORT = 3000
   JWT_SECRET = your-jwt-secret
   CLOUDINARY_NAME = Your-cloundinary-name
   CLOUDINARY_API_KEY = your-cloudinary-api-key
   CLOUDINARY_SECRET_KEY = your-cloudinary-secret-key
   CLERK_WEBHOOK_SECRET = your-clerk-webhook-secret
   CLERK_PUBLISHABLE_KEY = your-clerk-publishable-key
   CLERK_SECRET_KEY = your-clerk-secret-key
   ```

   In the frontend/.env file:

   ```
   VITE_CLERK_PUBLISHABLE_KEY = your-publishable-key 
   VITE_BACKEND_URL = your-server-url
   ```

3. **Install Dependencies**: Install dependencies in the `frontend` and `backend` folders using npm or yarn:

   ```
   cd frontend
   npm install
   cd ../backend
   npm install
   ```

4. **Start the Backend Server**: In the `backend` folder, start the development server using npm:

   ```
   npm run server
   ```

5. **Start the Frontend**: In the `frontend` folder, start the frontend application:

   ```
   npm run dev
   ```
