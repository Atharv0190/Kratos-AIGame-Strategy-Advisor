# ⚽ KRATOS – AI Game Strategy Advisor

An AI-powered multi-agent football strategy advisor built using IBM watsonx technologies. Kratos analyzes historical matches, player performance, tactical formations, and opponent strategies to generate evidence-based coaching recommendations.

---

## 📌 Problem Statement

**Problem Statement No. 29**

Build an AI-powered Game Strategy Advisor Agent that analyzes previous matches, opponent strategies, player performance, and tactical formations to help coaches make better strategic decisions before, during, and after a match.

---

## 🚀 Features

- Multi-Agent AI Architecture
- IBM watsonx Orchestrate Integration
- IBM Granite-4.0-8B-Instruct LLM
- Retrieval-Augmented Generation (RAG)
- FAISS Vector Database
- Opponent Analysis
- Match Performance Analysis
- Tactical Strategy Recommendations
- Explainable AI Insights
- REST API
- Coach Dashboard
- AI Chat Assistant

---

## 🏗 Architecture

```
Coach
   │
   ▼
IBM watsonx Orchestrate (Kratos)
   │
   ┼
   │ 
   ▼  
Match Analysis Agent
Opponent Strategy Agent
Strategy Recommendation Agent
Insight Explanation Agent
   │
   ▼
LangChain + RAG
   │
   ▼
FAISS Vector Database
   │
   ▼
Historical Football Knowledge
   │
   ▼
IBM Granite-4.0-8B-Instruct
```

---

## 🧠 AI Agents

### 1. Match Analysis Agent
- Possession Analysis
- xG Analysis
- Heatmaps
- Passing Statistics
- Player Ratings

### 2. Opponent Strategy Agent
- Formation Detection
- Strength & Weakness Analysis
- Pressing Style
- Dangerous Players
- Tactical Patterns

### 3. Strategy Recommendation Agent
- Best Formation
- Starting XI
- Pressing Strategy
- Set Pieces
- Risk Analysis

### 4. Insight Explanation Agent
- Explain AI Decisions
- Tactical Reasoning
- Confidence Scores
- Match Prediction

---

## 📂 Knowledge Base

The RAG pipeline uses:

- Historical Matches
- Player Statistics
- Match Reports
- Tactical Formations
- Coaching Notes
- Opponent Profiles
- Tournament History

---

## 🛠 Technology Stack

| Layer | Technology |
|---------|------------|
| Orchestrator | IBM watsonx Orchestrate |
| LLM | Granite-4.0-8B-Instruct |
| AI Framework | LangChain |
| Vector Database | FAISS |
| Backend | FastAPI |
| Frontend | ReactJS |
| Styling | Tailwind CSS |
| Deployment | Docker |
| Cloud | IBM Cloud |

---

## 📁 Project Structure

```
Kratos-AI-Game-Strategy-Advisor/

│── app.json
│── README.md
│── problemstatement.pdf
│── projectpresentation.pptx

---

## 📸 Demo

The system provides:

- Opponent Analysis
- Match Analysis
- Tactical Recommendations
- Match Prediction
- AI Chatbot
- Strategy Explanation

---

## 📦 Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Kratos-AI-Game-Strategy-Advisor.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run backend

```bash
uvicorn main:app --reload
```

Run frontend

```bash
npm install
npm run dev
```

---

## ☁ IBM Technologies Used

- IBM watsonx Orchestrate
- IBM watsonx.ai
- IBM Granite-4.0-8B-Instruct
- IBM Cloud

---

## 📄 Deliverables

- ✅ Source Code
- ✅ app.json
- ✅ Project Report
- ✅ Presentation
- ✅ Architecture Diagram
- ✅ README
- ✅ LangFlow Export
- ✅ API Documentation

---

## 👥 Team

**Project:** KRATOS – AI Game Strategy Advisor

Built for IBM SkillsBuild AI Workshop using IBM watsonx technologies.

---

## 📜 License

This project is developed for educational and demonstration purposes.
