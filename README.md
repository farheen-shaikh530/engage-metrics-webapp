#  MomentumOS — Focus Metrics Dashboard  
[![Gemini AI](https://img.shields.io/badge/AI-Gemini-blueviolet?logo=google)](https://deepmind.google/technologies/gemini/)
[![Google Cloud](https://img.shields.io/badge/Powered_by-Google_Cloud-red?logo=googlecloud)](https://cloud.google.com/)
[![FastAPI](https://img.shields.io/badge/API-FastAPI-teal?logo=fastapi)](https://fastapi.tiangolo.com/)
[![React](https://img.shields.io/badge/Frontend-React-blue?logo=react)](https://react.dev/)
[![License](https://img.shields.io/badge/license-MIT-yellow.svg)](LICENSE)

> **A full-stack productivity intelligence system powered by Google Gemini AI — designed to visualize focus, automate task imports, and analyze your weekly performance.**

---

## Why This Project

Modern professionals juggle multiple calendars, tools, and shifting priorities — losing sight of **focus metrics** that actually measure progress.  
**MomentumOS** unifies this by integrating **Gemini AI**, **FastAPI**, and **React** to provide real-time insights into productivity patterns, schedule imports, and goal tracking.


> *“Designed a full-stack productivity analytics platform integrating Google Gemini AI and external APIs (Google Calendar, WhenToWork) to visualize and automate weekly focus insights.”*

---

## Key Highlights

| Capability | Description |
|-------------|-------------|
|  **Gemini AI Coach** | Generates personalized productivity retrospectives and focus suggestions. |
|  **Dual Calendar Sync** | Imports shifts from **WhenToWork** and events from **Google Calendar** directly into tasks. |
|  **Focus Metrics Dashboard** | Tracks completion %, cycle times, and on-time performance with AI summaries. |
|  **Intuitive React UI** | Clean, responsive MUI layout with color-coded task stages. |
|  **FastAPI Backend** | High-performance Python 3.13 backend managing tasks, metrics, and AI endpoints. |

---

##  Architecture Overview

| Layer | Stack | Role |
|-------|--------|------|
| **Frontend** | React + Vite + TypeScript + MUI | Dashboard UI + data visualizations |
| **State Mgmt** | Zustand + IndexedDB | Local persistence + offline caching |
| **Backend** | FastAPI + Pydantic + Uvicorn | REST APIs for tasks, metrics, AI, and integrations |
| **AI Engine** | Google Gemini API | NLP-based insights and summarization |
| **Calendar Sync** | Google Calendar + WhenToWork ICS | Auto-imports work shifts and events |

---

## 🔗 Integrations

| Integration | Description | Env Variable |
|--------------|--------------|---------------|
| **Gemini AI** | Text generation and coaching | `GEMINI_API_KEY` |
| **WhenToWork** | ICS feed of scheduled shifts | `W2W_ICS_URL` |
| **Google Calendar** | ICS feed of events | `GCAL_ICS_URL` |
| **Frontend ↔ Backend** | API URL for FastAPI | `VITE_API_URL` |

---

##  Tech Stack Summary

**Frontend:**  
React (Vite + TypeScript), Material UI, Zustand, IndexedDB  

**Backend:**  
FastAPI, Python 3.13, Uvicorn, Pydantic  

**AI / Integrations:**  
Google Gemini API, Google Calendar ICS, WhenToWork ICS  

---

## 🧭 Setup Guide

### 1. Clone
```bash
git clone https://github.com/farheen-shaikh530/focus-metrics-dashboard.git
cd focus-metrics-dashboard
```

2. Frontend
```bash
npm install
npm run dev
```

3. Backend
```bash
cd server
pip install -r requirements.txt
uvicorn app:app --reload --app-dir server --port 8000
```

## Engage Metrics Dashboard (Live Demo Preview): Full demo coming soon...

<img width="1512" height="826" alt="Screenshot 2025-11-12 at 8 39 42 AM" src="https://github.com/user-attachments/assets/8eafa557-333f-4b1f-95f1-db100dc1962d" />



