# Mindaura

**Mindaura** is a full-stack mental wellness web application focused on structured mood tracking, behavioral consistency, and AI-assisted emotional reflection.

The platform combines habit formation (mood streaks), data visualization, and an AI chatbot to help users better understand emotional patterns and receive contextual suggestions based on their current mental state.

🔗 **Live Application:** https://mind-aura-ten.vercel.app

---

## Overview

Mental wellness tools often fail due to poor consistency and lack of personalization.  
Mindaura addresses this by:

- Encouraging **daily mood logging**
- Reinforcing behavior through **streak tracking**
- Providing **context-aware AI support**
- Maintaining a clean, distraction-free user experience

The system is designed with scalability, separation of concerns, and real-world product thinking in mind.

---

## Core Features

- **Authentication & Authorization**
  - Secure user registration and login
  - Session-based access control

- **Mood Logging System**
  - Daily mood entries with structured data
  - Persistent storage and retrieval

- **Mood Streak Tracking**
  - Tracks user consistency over time
  - Reinforces habit formation

- **AI-Powered Chatbot**
  - Integrated using OpenAI API
  - Generates responses and suggestions based on user mood context
  - Designed to assist, not replace, user self-reflection

- **Dashboard**
  - Centralized view of user activity
  - Mood history and streak insights

- **Dedicated Mood Log Interface**
  - Focused, low-friction UI for daily entries

---

## Tech Stack

### Frontend

- React.js
- JavaScript (ES6+)
- HTML5, CSS3

### Backend

- Node.js
- Express.js
- RESTful API design

### Database

- MongoDB (document-oriented schema)

### AI Integration

- OpenAI API (secured via environment variables)

### Architecture

- MERN Stack
- Clear frontend/backend separation
- Environment-based configuration

---

## Deployment

- **Frontend:** Vercel  
  Deployed as a production-ready React application with environment-based configuration.

- **Backend:** Render  
  Node.js + Express backend deployed on Render, handling authentication, mood data APIs, and AI chatbot requests.

- **Database:** MongoDB Atlas  
  Cloud-hosted database for persistent user and mood data.

The frontend communicates with the backend via REST APIs, with sensitive credentials managed using environment variables.

---

## Local Setup

### Prerequisites

- Node.js
- MongoDB
- OpenAI API key

### Clone Repository

```bash
git clone https://github.com/kalpanasharma-code/mindaura.git
cd mindaura

```
