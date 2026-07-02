# 🚀 AI Social Media Automation Platform

> A full-stack AI-powered social media management platform built with the MERN Stack that enables users to generate AI-driven content, connect multiple social media accounts, schedule posts, and automate publishing across platforms from a single dashboard.

![React](https://img.shields.io/badge/React-19-blue?logo=react)
![Node.js](https://img.shields.io/badge/Node.js-22-green?logo=node.js)
![Express](https://img.shields.io/badge/Express.js-black?logo=express)
![MongoDB](https://img.shields.io/badge/MongoDB-Database-green?logo=mongodb)
![JWT](https://img.shields.io/badge/Auth-JWT-orange)
![Gemini](https://img.shields.io/badge/AI-Google%20Gemini-blueviolet)
![Tailwind CSS](https://img.shields.io/badge/TailwindCSS-4.0-38BDF8?logo=tailwindcss)
![License](https://img.shields.io/badge/License-MIT-blue)

---

## 📖 Overview

AI Social Media Automation Platform is a modern SaaS application that simplifies social media management using Artificial Intelligence and automation.

Users can:

- 🤖 Generate engaging AI-powered social media posts
- 📅 Schedule content for future publishing
- 🔗 Connect multiple social media accounts
- 📊 Manage posts from a centralized dashboard
- ☁️ Upload and manage media using Cloudinary
- ⚡ Automate publishing through Zernio API

The application follows a scalable MERN architecture with secure authentication, REST APIs, scheduled background jobs, and responsive UI.

---

# ✨ Features

## 🤖 AI Content Generation

Generate high-quality social media posts using **Google Gemini AI**.

The AI automatically generates:

- Captions
- Social media content
- Hashtags
- Image prompts
- Multiple writing tones

Supported tones:

- Professional
- Casual
- Marketing
- Promotional
- Friendly
- Informative

---

## 📅 Social Media Scheduling

Create posts instantly or schedule them for future publishing.

Features include:

- Future scheduling
- Multiple platform selection
- Automatic publishing
- Post status tracking
- Scheduled jobs using Cron

---

## 🌐 Multi Platform Support

Connect and manage multiple social media platforms from one dashboard.

Supported platforms include:

- X (Twitter)
- LinkedIn
- Facebook
- Instagram

OAuth authentication is handled securely through the Zernio API.

---

## 👤 Authentication

Secure authentication system built with JWT.

Features:

- User Registration
- Login
- Protected Routes
- JWT Authentication
- Password Hashing
- Session Persistence

---

## 📂 Media Management

Upload media directly or generate AI content.

Features:

- Image Uploads
- Cloudinary Integration
- Image Hosting
- Secure Storage

---

## 📊 Dashboard

Modern responsive dashboard providing:

- Analytics Overview
- Scheduled Posts
- Generated Posts
- Connected Accounts
- Recent Activity

---

## 🔄 Automation

Background scheduler automatically:

- Checks scheduled posts
- Publishes content
- Updates database
- Creates activity logs

---

# 🏗️ System Architecture

```
                +--------------------+
                |   React Frontend   |
                +---------+----------+
                          |
                          |
                     REST API
                          |
                          |
              +-----------+------------+
              | Express + Node Backend |
              +-----------+------------+
                          |
          ---------------------------------------
          |             |            |          |
          |             |            |          |
      MongoDB       Gemini AI    Cloudinary   Zernio
          |             |            |          |
          |             |            |          |
      User Data     AI Content    Images   Social Platforms
```

---

# 🛠️ Tech Stack

## Frontend

- React 19
- TypeScript
- Vite
- Tailwind CSS
- React Router
- Axios
- Framer Motion

---

## Backend

- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT
- bcrypt
- Multer
- Node Cron

---

## AI

- Google Gemini API

Used for:

- AI Caption Generation
- Content Generation
- Image Prompt Generation

---

## Cloud Services

- MongoDB Atlas
- Cloudinary
- Zernio API

---

# 📁 Project Structure

```
AI-Social-Scheduler/
│
├── client/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── server/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── scheduler/
│   ├── services/
│   └── package.json
│
└── README.md
```

---

# 🔐 Environment Variables

Create a `.env` file inside the server folder.

```env
PORT=3000

MONGODB_URI=

JWT_SECRET=

GEMINI_API_KEY=

ZERNIO_API_KEY=

CLOUDINARY_CLOUD_NAME=

CLOUDINARY_API_KEY=

CLOUDINARY_API_SECRET=
```

> **Note:** `LEONARDO_API_KEY` is optional and only required if AI image generation via Leonardo AI is enabled.

---

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/yourusername/ai-social-media-automation.git
```

---

## Install Frontend

```bash
cd client

npm install
```

---

## Install Backend

```bash
cd server

npm install
```

---

## Run Backend

```bash
npm run dev
```

---

## Run Frontend

```bash
npm run dev
```

---

# 🚀 Workflow

```
User
   │
   ▼
Login
   │
   ▼
Dashboard
   │
   ├───────────────┐
   │               │
   ▼               ▼
Generate Post   Upload Media
   │               │
   ▼               │
Gemini AI          │
   │               │
   ▼               │
Generated Post     │
   │               │
   └──────┬────────┘
          ▼
Schedule Post
          ▼
Cron Scheduler
          ▼
Zernio API
          ▼
Social Media Platforms
```

---

# 📦 API Modules

Authentication

- Register
- Login
- JWT Verification

AI

- Generate AI Posts
- Generate Captions
- Generate Image Prompt

Posts

- Create
- Schedule
- Publish
- Update
- Delete

Accounts

- Connect Social Accounts
- Sync Accounts
- OAuth Authentication

Activity

- Activity Logs
- Publishing History

---

# 🔒 Security Features

- JWT Authentication
- Password Hashing
- Protected Routes
- Secure API Calls
- Environment Variables
- Cloud Media Storage

---

# 📸 Screenshots

Add screenshots here.

Example:

```
screenshots/

dashboard.png

login.png

generator.png

scheduler.png

accounts.png
```

---

# 📈 Future Improvements

- AI Image Generation
- Team Workspaces
- Content Calendar
- Analytics Dashboard
- AI Comment Generator
- AI Caption Variations
- Draft Management
- Email Notifications
- Multi-user Collaboration
- Bulk Scheduling
- Social Media Insights
- Dark Mode
- Mobile Application

---

# 🎯 Learning Outcomes

This project demonstrates:

- MERN Stack Development
- REST API Design
- JWT Authentication
- MongoDB Data Modeling
- AI Integration
- Cloud Storage
- OAuth Authentication
- Background Scheduling
- SaaS Architecture
- Responsive UI Development
- Production-ready Project Structure

---

# 👨‍💻 Author

**Sambhav Koshta**

B.Tech CSE | Full Stack Developer | MERN Stack | AI Applications

GitHub: https://github.com/Sambhav10-10

LinkedIn: https://linkedin.com/in/sambhavkoshta10

---

# ⭐ If you found this project helpful

Please consider giving it a **Star ⭐** on GitHub.