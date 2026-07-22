# 🌐 AI Multilingual Enterprise Communication Platform

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.9+](https://img.shields.io/badge/python-3.9+-blue.svg)](https://www.python.org/downloads/)
[![React 18](https://img.shields.io/badge/react-18.2.0-blue.svg)](https://reactjs.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.104.1-009688.svg)](https://fastapi.tiangolo.com/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)
[![GitHub issues](https://img.shields.io/github/issues/vishakha2121/ai-multilingual-comm-platform)](https://github.com/vishakha2121/ai-multilingual-comm-platform/issues)

> **An AI-powered platform for real-time multilingual translation, meeting transcription, sentiment analysis, and automated summarization across 50+ languages.**

## 🚀 Overview

The **AI Multilingual Enterprise Communication Platform** is an innovative solution designed to break down language barriers in global business communications. This platform leverages state-of-the-art AI models to provide real-time multilingual translation, intelligent meeting transcription, sentiment analysis, and automated summarization.

Whether it's a boardroom discussion, a cross-border client meeting, or a multinational team sync, this platform ensures seamless communication with zero language friction.

## ✨ Key Features

### 🌍 Real-Time Multilingual Translation
- Instant translation between 50+ languages
- Support for major languages (English, Spanish, Mandarin, Hindi, Arabic, etc.)
- Bidirectional translation with context awareness
- Industry-specific terminology support
- Voice-to-text and text-to-text translation modes

### 📝 Advanced Meeting Transcription
- High-accuracy speech-to-text conversion using Whisper
- Speaker diarization (identifies who said what)
- Timestamp generation for easy reference
- Confidence scoring for transcription accuracy
- Support for multiple speakers and accents
- Live transcription during meetings

### 📊 Intelligent Sentiment Analysis
- Real-time emotion detection (happy, neutral, angry, sad)
- Overall meeting sentiment scoring
- Participant sentiment tracking
- Trend analysis across multiple meetings
- Visual sentiment dashboards
- Emotional intelligence insights

### 📋 AI-Powered Meeting Summaries
- Automated meeting minutes generation
- Key points extraction
- Action items identification
- Decision tracking
- Executive summary creation
- Shareable meeting reports

### 💻 Multi-Platform Support
- Web-based interface (responsive design)
- Mobile-friendly access
- Audio file upload support
- Real-time audio recording
- Integration-ready APIs

## 🏗️ Technology Stack

### Frontend
- **React.js** - UI Framework
- **Tailwind CSS** - Styling
- **Material-UI** - Component Library
- **WebSocket** - Real-time updates
- **Chart.js & Recharts** - Data visualization
- **Axios** - HTTP client
- **React Router** - Navigation

### Backend
- **FastAPI** - Web framework
- **Python 3.9+** - Programming language
- **SQLite** - Database (practice version)
- **JWT** - Authentication
- **WebSocket** - Real-time communication
- **Celery** - Background tasks
- **Redis** - Caching (optional)

### AI/ML Models
- **Whisper (OpenAI)** - Speech-to-Text
- **SeamlessM4T (Meta)** - Translation
- **Gemini API (Google)** - Summarization & Sentiment Analysis
- **Custom Models** - Language detection & processing

## 📁 Project Structure



## 🚀 Quick Start

### Prerequisites

- Python 3.9 or higher
- Node.js 16 or higher
- npm or yarn
- Git

### Installation

#### 1. Clone the Repository

```bash
git clone https://github.com/vishakha2121/ai-multilingual-comm-platform.git
cd ai-multilingual-comm-platform

# Navigate to backend
cd backend

# Create virtual environment
python -m venv venv

# Activate virtual environment
# On Windows:
venv\Scripts\activate
# On Mac/Linux:
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Create .env file
cp .env.example .env

# Update .env with your API keys
# GEMINI_API_KEY=your_api_key_here

# Navigate to frontend
cd frontend

# Install dependencies
npm install

# Create .env file
cp .env.example .env

# Update .env with your API URL
# VITE_API_URL=http://localhost:8000/api/v1