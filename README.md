<div align="center">

# Jatin Nimje

### Backend Engineer · AI/ML Systems

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1200&color=6C8EF5&center=true&vCenter=true&width=560&lines=Building+RAG+and+ML-backed+APIs;FastAPI+%7C+PostgreSQL+%7C+pgvector;Final-year+Computer+Engineering+%40+TSEC+Mumbai" alt="typing animation" />

<br/>

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)

</div>

---

## About

I build backend systems where the interesting part is the architecture: async pipelines, retrieval, scheduling algorithms and ML models served behind clean APIs.

- Final-year Computer Engineering student at **Thadomal Shahani Engineering College (TSEC), Mumbai** (CGPA 9.725 / 10, graduating May 2027)
- Working across **FastAPI, Flask, PostgreSQL and MongoDB**, with a growing focus on **RAG, ML serving and cloud deployment**
- Looking for **backend SDE and AI/ML roles**

---

## Featured Projects

### Prepify: AI-Based Student Preparation Platform
*RAG-based, deployed*

Upload study material and an async pipeline extracts, chunks and embeds it without blocking the API. Semantic search over **pgvector** retrieves the most relevant parts of a student's notes, an LLM generates grounded practice questions from that context, and an **SM-2 spaced repetition engine** uses attempt history and topic mastery to decide what to revise next.

`Python` `FastAPI` `PostgreSQL` `pgvector` `Celery` `Redis` `RAG`

Deployed across Render, Vercel, Neon Postgres and Upstash Redis, with the ingestion queue decoupled from the API host so each can scale independently.

[Repository](https://github.com/Bhendi-J/Prepify)

---

### FlowDesk: Graph-Based Scheduling Sandbox
*CPM, resource constraints and Monte Carlo*

Models project workflows as DAGs and shows the gap between a dependency-only schedule and one that respects real resource limits.

- DFS-based cycle detection rejects dependency inserts that would create cycles
- Kahn's topological sort and the Critical Path Method calculate task timings, slack and the critical path
- A resource-constrained scheduling heuristic with interval-based capacity reservation models multi-resource contention
- Monte Carlo simulation samples triangular duration distributions to estimate completion-time uncertainty (p10/p50/p90) across up to 5,000 trials

`Python` `FastAPI` `SQLAlchemy` `SQLite` `React` `React Flow` `Dagre`

---

### DriveIQ: Smart Driving Analysis Platform
*Computer vision + explainable scoring*

Analyzes live and uploaded driving video to detect vehicles, extract behavior features and score a trip.

- **YOLOv8** and optical flow extract driving-behavior features from video
- An **XGBoost** model scores behavior, with EMA smoothing for stable real-time predictions
- **SHAP** identifies the behaviors that lowered the score and drives targeted coaching feedback
- Frame-level predictions are converted into segments so events like harsh braking are easy to locate and explain

`Python` `Flask` `YOLOv8` `OpenCV` `XGBoost` `SHAP`

---

## Tech Stack

| Area | Tools |
|---|---|
| **Languages** | Python, C++, SQL, HTML, CSS |
| **Backend** | FastAPI, Flask, REST APIs, JWT Authentication, Session Management |
| **Databases** | PostgreSQL, MongoDB, MySQL, SQLite |
| **Async and Queues** | Celery, Redis |
| **AI / ML** | XGBoost, NLP, SHAP, Sentence Transformers, FAISS, OpenCV, YOLOv8 |
| **Frontend** | React, React Flow |
| **Tools and Deployment** | Git, GitHub, Docker, Postman, Render, Vercel, Neon, Upstash |

---

## Currently Working On

- **DecisionIQ**: final-year project, an AI-powered business risk platform for SMEs. I own the API gateway and cloud deployment
- **Prepify**: hardening the study session, notes and summarization flow
- Going deeper on cloud deployment and DevOps

---

## Leadership

**Senior Committee Member (Content Head), IETE TSEC, 2025 to 2026**

- Created content and engagement campaigns to grow student participation in IETE TSEC initiatives
- Coordinated technical workshops, hackathon activities and student events
- Judged and mentored at Newbiethon, guiding first-year students through their projects

---

## Stats

<div align="center">

![GitHub stats](https://github-readme-stats.vercel.app/api?username=Bhendi-J&show_icons=true&theme=tokyonight&hide_border=true)
![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Bhendi-J&layout=compact&theme=tokyonight&hide_border=true)

</div>

---

## Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jatinnimje)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jatinnimje288@gmail.com)

</div>
