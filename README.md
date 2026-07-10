# HireMind AI

> An AI-powered recruitment platform that helps recruiters identify the right candidates and helps job seekers improve their resumes, prepare for interviews, and track their job applications.

---

## About the Project

Hiring today is still heavily dependent on keyword matching and manual resume screening. Many qualified candidates are overlooked simply because their resumes don't contain the exact keywords a recruiter is searching for.

HireMind AI is an attempt to make the recruitment process smarter.

Instead of relying only on keywords, the platform understands resumes and job descriptions semantically using Natural Language Processing (NLP), embeddings, and local Large Language Models (LLMs). Recruiters receive AI-assisted insights while candidates receive actionable feedback to improve their chances of getting hired.

The goal is **not to replace recruiters**, but to provide tools that help them make faster and more informed hiring decisions.

---

# Project Goals

- Build a complete AI-powered recruitment platform.
- Support both recruiters and job seekers.
- Perform intelligent resume screening.
- Calculate ATS compatibility scores.
- Match resumes with job descriptions using semantic similarity.
- Generate interview questions tailored to each candidate.
- Evaluate interview responses.
- Provide resume improvement suggestions.
- Keep the entire AI pipeline local without depending on paid APIs.

---

# Features

## Candidate

- User Registration & Login
- Profile Management
- Resume Upload
- Resume Parsing
- Resume Analysis
- ATS Score
- Resume Improvement Suggestions
- Job Search
- Job Filtering
- Apply to Jobs
- Saved Jobs
- Track Applications
- AI Interview Preparation
- Technical Questions
- HR Questions
- Coding Questions
- Interview Performance Report

---

## Recruiter

- Recruiter Registration
- Company Profile
- Post Jobs
- Edit Jobs
- Delete Jobs
- View Applicants
- Resume Screening
- Candidate Ranking
- Candidate Comparison
- Skill Gap Analysis
- AI Interview Question Generator
- Recruiter Analytics Dashboard

---

## Admin

- Manage Users
- Manage Recruiters
- Verify Companies
- Manage Jobs
- Platform Analytics
- Reports

---

# AI Features

## Resume Parser

Extracts information such as:

- Name
- Email
- Phone Number
- Skills
- Education
- Experience
- Projects
- Certifications
- GitHub
- LinkedIn
- Portfolio

---

## ATS Score

The ATS engine evaluates resumes based on multiple factors including:

- Skills
- Experience
- Education
- Project Relevance
- Resume Quality
- Keyword Coverage

---

## Semantic Matching

Instead of simple keyword matching, the platform compares the semantic meaning of resumes and job descriptions.

This allows recruiters to discover relevant candidates even when different terminology is used.

---

## Skill Gap Analysis

Shows:

- Required Skills
- Existing Skills
- Missing Skills
- Recommended Skills to Learn

---

## Candidate Ranking

Candidates are ranked using multiple signals rather than a single score.

Factors include:

- ATS Score
- Semantic Similarity
- Experience
- Education
- Projects
- Certifications

---

## Interview Assistant

The platform generates interview questions based on the candidate's profile.

Supported categories include:

- Technical Questions
- Coding Questions
- HR Questions
- Behavioral Questions

---

## Answer Evaluation

Candidates can practice interviews inside the platform.

The AI evaluates responses and provides:

- Strengths
- Missing Concepts
- Suggestions for Improvement
- Overall Performance

---

# User Roles

## Candidate

A candidate can:

- Create Profile
- Upload Resume
- Search Jobs
- Apply for Jobs
- Track Applications
- Prepare for Interviews

---

## Recruiter

A recruiter can:

- Create Company Profile
- Post Jobs
- View Applicants
- Screen Resumes
- Rank Candidates
- Compare Applicants
- Generate Interview Questions

---

## Admin

An administrator manages the overall platform.

Responsibilities include:

- User Management
- Company Verification
- Platform Monitoring
- Analytics

---

# Technology Stack

## Frontend

- React
- Vite
- Tailwind CSS
- React Router
- Axios

## Backend

- FastAPI
- Python

## Database

- MongoDB

## AI & Machine Learning

- spaCy
- NLTK
- Sentence Transformers
- FAISS
- Scikit-learn
- SHAP

## Local LLM

The project intentionally avoids paid APIs.

Planned local models include:

- Phi-3 Mini
- Qwen 2.5 Instruct
- Mistral (optional)

## Deployment

- Docker
- Docker Compose

---

# Project Structure

```text
HireMind-AI/

├── backend/
├── frontend/
├── datasets/
├── models/
├── docs/
├── docker/
├── tests/
└── README.md
```

---

# Future Enhancements

- Video Interview Analysis
- Voice-Based Interview Evaluation
- AI Resume Builder
- Salary Prediction
- Email Notifications
- Calendar Integration
- Mobile Application
- Multi-language Resume Support

---

# Why This Project?

Most recruitment platforms stop after allowing users to upload resumes and apply for jobs.

HireMind AI goes a step further by combining traditional software engineering with modern AI techniques.

The project demonstrates:

- Full Stack Development
- REST API Design
- Authentication & Authorization
- Database Design
- Natural Language Processing
- Semantic Search
- Machine Learning
- Explainable AI
- Local LLM Integration
- Docker-Based Deployment

The intention is to build something that resembles a real production system rather than a collection of isolated AI demos.

---

# Current Status

🚧 The project is currently under active development.

The focus is on building each module incrementally with clean architecture, thorough testing, and production-ready engineering practices.

---

## License

This project is being developed for learning, research, and portfolio purposes.

---

## Author

Developed by **Bobby** as a portfolio project to explore the intersection of Full Stack Development, Artificial Intelligence, and Machine Learning in modern recruitment systems.
