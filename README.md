# GLINT — Where Skills Shine
 
> An AI-Powered Social Media Platform for Freelancers and Independent Workers.

[![Live Demo](https://img.shields.io/badge/Live_Demo-glint--freelancer--platform.netlify.app-FF6B00?style=for-the-badge)](https://glint-freelancer-platform.netlify.app/) 

[![Built With](https://img.shields.io/badge/Built_With-MERN_Stack-3FA037?style=for-the-badge&logo=mongodb)](https://www.mongodb.com/mern-stack)
[![Database](https://img.shields.io/badge/Database-MongoDB-47A248?style=for-the-badge&logo=mongodb)](https://mongodb.com)
[![Backend](https://img.shields.io/badge/Backend-Node.js_+_Express-339933?style=for-the-badge&logo=node.js)](https://nodejs.org)
[![AI](https://img.shields.io/badge/AI-Google_Gemini-4285F4?style=for-the-badge&logo=google)](https://ai.google.dev)
[![ML](https://img.shields.io/badge/ML-TensorFlow -FF6F00?style=for-the-badge&logo=tensorflow)](https://tensorflow.org)

--- 

# About

**GLINT** is a professional social platform designed to bridge the gap between freelance creators and hirers. Unlike traditional freelancing platforms where talent competes through bidding wars, GLINT lets creators showcase their actual work — portfolio pieces, code demos, video edits, and case studies — allowing hirers to discover talent organically through quality, not price.

GLINT integrates Artificial Intelligence, Machine Learning, and Deep Learning technologies to create a smarter, safer, and more intelligent hiring ecosystem powered completely using the MERN Stack architecture.

---

# Problem Statement

Traditional freelancing platforms like Fiverr and Upwork suffer from:

- **Race-to-the-bottom pricing** caused by bidding systems
- **Limited creator visibility** beyond ratings and reviews
- **Weak portfolio showcasing**
- **No intelligent recommendation systems**
- **Fake portfolios and spam profiles**
- **Poor networking between creators and hirers**
- **Lack of AI-driven hiring assistance**

---

# Solution

GLINT provides:

- A **social-media-style creator platform**
- **Direct hiring without bidding wars**
- **AI-powered talent matching**
- **Deep Learning portfolio quality analysis**
- **AI spam and fraud detection**
- **Real-time messaging and collaboration**
- **Personalized recommendation feeds**
- **Transparent monetization system**
- **Intelligent creator discovery**

---

# AI & ML Integrations

## 1. AI Talent Recommendation Engine

GLINT uses Machine Learning and Deep Neural Networks (DNNs) to intelligently recommend:

- Best creators for hirers
- Personalized job opportunities
- Smart creator discovery
- Feed personalization based on user behavior
- Similar creators based on skills and engagement

### Features

- Smart creator-job matching
- Personalized recommendations
- AI-powered feed ranking
- Skill-based discovery
- Behavioral recommendation systems

### Technologies Used

- Python
- TensorFlow
- Scikit-learn
- Recommendation Algorithms
- NLP Embeddings
- Sentence Transformers

### AI Workflow

```text
User Activity → ML Models → Recommendation Engine → Personalized Results
```

---

## 2. Portfolio Quality Detection using Deep Learning

GLINT automatically analyzes uploaded portfolios using Deep Learning models.

The AI evaluates:

- Creativity
- Design quality
- Professionalism
- Content relevance
- Portfolio categories
- Media quality

### Features

- Automatic portfolio scoring
- AI image understanding
- Portfolio quality ranking
- Smart categorization
- AI-generated insights

### Technologies Used

- CNN (Convolutional Neural Networks)
- TensorFlow
- OpenCV
- ResNet Models
- Computer Vision APIs

### AI Workflow

```text
Portfolio Upload → Deep Learning Model → Quality Score & Insights
```

---

## 3. AI Fraud & Spam Detection

GLINT uses AI moderation systems to maintain a secure and trusted ecosystem.

The system detects:

- Fake creator profiles
- Spam job postings
- Duplicate portfolios
- Suspicious activities
- Scam behaviors
- Toxic content

### Features

- AI moderation
- Fraud monitoring
- Spam account detection
- Intelligent content filtering
- Real-time moderation alerts

### Technologies Used

- Random Forest Algorithms
- Scikit-learn
- NLP Text Classification
- Python ML Pipelines

### AI Workflow

```text
User Content → AI Detection Model → Spam/Safe Classification
```

---

# MERN Stack Tech Stack

| Layer | Technology | Purpose |
|-------|------------|---------|
| **Frontend** | React.js + Vite | UI development & routing |
| **Backend** | Node.js + Express.js | REST APIs & business logic |
| **Database** | MongoDB Atlas | NoSQL database management |
| **ODM** | Mongoose | MongoDB schema modeling |
| **Authentication** | JWT + bcrypt | Secure user authentication |
| **File Storage** | Cloudinary | Portfolio & media uploads |
| **AI Backend** | Python + FastAPI | AI & ML APIs |
| **AI/ML** | TensorFlow + Scikit-learn | Recommendation & detection systems |
| **Computer Vision** | OpenCV + CNN | Portfolio analysis |
| **NLP** | Sentence Transformers | Skill & text understanding |
| **AI Model** | Google Gemini 2.0 Flash | AI generation & smart matching |
| **Frontend Hosting** | Netlify / Vercel | Frontend deployment |
| **Backend Hosting** | Render / Railway / Vercel | Backend deployment |
| **Realtime Communication** | Socket.io | Live messaging & notifications |
| **Animations** | Framer Motion | Smooth UI interactions |
| **State Management** | Context API / Redux Toolkit | Application state |

---

# Features

## Authentication & Security

- JWT-based authentication system
- Encrypted password storage using bcrypt
- Email verification system
- Protected API routes
- Secure role-based authorization
- AI-powered spam protection
- Session management
- Secure backend validations
- Environment variable protection

---

## For Creators

- Portfolio posting system
- Upload images, videos, code snippets, and case studies
- AI-generated professional descriptions
- AI portfolio quality analysis
- Personalized AI job recommendations
- Direct messaging with hirers
- Profile analytics dashboard
- Rate card management
- Social following system

---

## For Hirers

- Creator discovery feed
- AI-powered talent matching
- Intelligent creator search
- Job posting system
- Direct hiring functionality
- Project tracking dashboard
- Collaboration management
- Creator review system

---

## Platform Features

- Dark premium UI design
- Glassmorphism effects
- Fully responsive design
- Real-time notifications
- Real-time chat system
- AI-powered feed personalization
- AI spam filtering
- AI portfolio ranking
- Social graph system
- Recommendation algorithms

---

# System Architecture

```text
┌─────────────────┐       ┌──────────────────┐       ┌─────────────────┐
│                 │       │                  │       │                 │
│    FRONTEND     │──────▶│     BACKEND      │──────▶│    AI/ML APIs   │
│   React + Vite  │       │  Node + Express  │       │ Python + FastAPI│
│                 │       │                  │       │                 │
│  Framer Motion  │       │  REST APIs       │       │ Recommendation  │
│  React Router   │       │  JWT Auth        │       │ Portfolio AI    │
│  Redux Toolkit  │       │  Socket.io       │       │ Spam Detection  │
│                 │       │                  │       │ Gemini AI       │
└────────┬────────┘       └────────┬─────────┘       └────────┬────────┘
         │                         │                          │
         │                         ▼                          │
         └────────────────────────▶ MongoDB Atlas ◀───────────┘
                                   Cloudinary
```

---

# Project Structure

```text
GLINT/
├── client/                         # Frontend React Application
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── context/
│   │   ├── redux/
│   │   ├── services/
│   │   ├── hooks/
│   │   ├── assets/
│   │   ├── App.jsx
│   │   └── main.jsx
│   ├── package.json
│   └── vite.config.js
│
├── server/                         # Backend Express Server
│   ├── controllers/
│   ├── routes/
│   ├── middleware/
│   ├── models/
│   ├── config/
│   ├── sockets/
│   ├── utils/
│   ├── uploads/
│   ├── server.js
│   └── package.json
│
├── ml-service/                     # AI & ML Services
│   ├── recommendation/
│   ├── portfolio-detection/
│   ├── fraud-detection/
│   ├── models/
│   └── app.py
│
├── .env
├── README.md
└── package.json
```

---

# Screenshots

## Landing Page

Premium dark-themed landing page with animated gradients, glassmorphism UI, and modern CTA sections.

## Dashboard

AI-personalized social feed with trending creators, job recommendations, and analytics.

## AI Talent Discovery

AI-powered creator discovery where hirers describe project requirements and GLINT recommends the best-fit talent.

## Profile Page

Professional creator profiles with portfolio showcases, AI analysis, reviews, skill tags, and hire functionality.

---

# Database Collections

| Collection | Description |
|------------|-------------|
| `users` | Creator & hirer profiles |
| `posts` | Portfolio posts |
| `jobs` | Job listings |
| `comments` | Post comments |
| `notifications` | Alerts & activities |
| `chats` | Chat conversations |
| `messages` | Real-time messages |
| `hires` | Hiring contracts |
| `followers` | Social connections |

---

# API Endpoints

| Feature | Endpoint | Description |
|---------|----------|-------------|
| **AI Assist** | `/api/ai/gemini-assist` | Generates professional portfolio descriptions |
| **AI Match** | `/api/ai/gemini-match` | Intelligent creator-hirer matching |
| **Recommendation Engine** | `/api/ai/recommendation` | ML-powered recommendations |
| **Portfolio Analysis** | `/api/ai/portfolio-analysis` | Deep Learning portfolio scoring |
| **Spam Detection** | `/api/ai/spam-detection` | AI moderation & fraud filtering |
| **AI Image** | `/api/ai/gemini-image` | AI-generated creative visuals |

---

# User Roles

## Creator

- Upload portfolio work
- Share case studies
- Set pricing and rate cards
- Receive AI recommendations
- Track analytics
- Chat with hirers
- Apply for opportunities

---

## Hirer

- Browse creators
- Post opportunities
- Discover talent using AI
- Hire creators directly
- Manage projects
- Review collaborations

---

# Future Enhancements

- AI video portfolio analysis
- Blockchain-based creator verification
- AI interview assistant
- Smart contract-based payments
- Voice-enabled AI hiring assistant
- AI-powered freelancer scoring system
- Global creator ranking algorithms
- Web3 creator identity integration

---

# Acknowledgements

- [React](https://react.dev) — Frontend framework
- [Node.js](https://nodejs.org) — Backend runtime
- [Express.js](https://expressjs.com) — Backend framework
- [MongoDB](https://mongodb.com) — NoSQL database
- [TensorFlow](https://tensorflow.org) — Deep Learning framework
- [Scikit-learn](https://scikit-learn.org) — Machine Learning tools
- [Google Gemini](https://ai.google.dev) — AI capabilities
- [Framer Motion](https://www.framer.com/motion/) — Animations
- [Cloudinary](https://cloudinary.com) — Media storage
- [Socket.io](https://socket.io) — Real-time communication

---

<div align="center">
  <b>Built for the next generation of intelligent freelance hiring</b>
  <br />
  <i>GLINT — Where Skills Shine</i>
</div>
