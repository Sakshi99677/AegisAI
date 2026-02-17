# 🏦 AegisAI — Unified AI Observability & Governance Platform

## 🚨 Problem

Modern banks use multiple AI systems:

* Traditional ML models → credit scoring, fraud detection
* LLM systems → chatbots, document processing, assistants

But these systems are monitored separately.
There is **no single place to understand AI risk**.

This creates:

* Model drift going unnoticed
* Hallucinated responses
* Compliance violations
* Financial & reputational damage

---

## 💡 Our Solution

**AegisAI** provides a unified governance layer that continuously monitors ML + LLM systems and produces a real-time **AI Health Score**.

The platform detects risk before damage happens.

---

## 🧠 Key Features

### 1. ML Observability

* Detects model drift
* Tracks prediction accuracy
* Flags unreliable models

### 2. LLM Monitoring

* Measures latency
* Tracks token usage
* Detects unsafe responses

### 3. Governance Engine

* Combines ML + LLM risks
* Generates AI Health Score
* Classifies risk level

### 4. Unified Dashboard

* Single view of AI behavior
* Live risk alerts
* Explainable metrics

---

## 🏗️ Architecture Flow

AI Systems → Monitoring Layer → Risk Engine → Governance Score → Dashboard

---

## ⚙️ Tech Stack

**Backend**

* FastAPI
* Python
* NumPy / Scikit-learn

**Frontend**

* React

**Deployment**

* Render / Vercel

---

## ▶️ How To Run Locally

### Backend

```
cd backend
pip install -r requirements.txt
uvicorn main:app --reload
```

Open:

```
http://127.0.0.1:8000/docs
```

---

## 🎯 Demo Scenario

1. System starts in healthy state
2. Model drift is simulated
3. AI Health Score drops
4. Risk alert triggered

This demonstrates proactive AI governance.

---

## 👥 Team

Built for Hackathon Submission — AegisAI Team

---

Done ✅
Save → commit → push.

