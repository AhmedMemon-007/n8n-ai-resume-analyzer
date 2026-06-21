# CareerIQ: AI Resume Analyzer & Job Matcher

## Overview

CareerIQ is an AI-powered Resume Analyzer and Job Matcher built using **n8n** and **Mistral AI**.

The system accepts a resume in PDF format and a target job role, extracts resume content, performs ATS-style analysis, identifies skill gaps, generates personalized career recommendations, and delivers a professional HTML report via email.

---

## Features

- Resume PDF Upload
- PDF Text Extraction
- ATS Resume Analysis
- Job Match Score Evaluation
- Technical Skills Identification
- Soft Skills Identification
- Strengths & Weakness Analysis
- Missing Skills Detection
- Learning Roadmap Generation
- Portfolio Project Recommendations
- Professional HTML Report Generation
- Automated Email Delivery

---

## Workflow

```text
Form Submission
      ↓
PDF Extraction
      ↓
Resume Analysis
      ↓
HTML Report Generation
      ↓
Email Delivery
```

---

## Tech Stack

- n8n
- Mistral AI
- Gmail API
- PDF Processing
- HTML Email Templates
- Workflow Automation

---

## How It Works

### 1. User Submission

The user provides:

- Full Name
- Email Address
- Target Job Role
- Years of Experience
- Resume PDF

### 2. Resume Processing

The workflow extracts text from the uploaded PDF resume.

### 3. AI Resume Analysis

Mistral AI analyzes the resume and generates:

- Candidate Overview
- Technical Skills
- Soft Skills
- Education Summary
- Experience Summary
- Strengths
- Areas for Improvement

### 4. Career Recommendations

The AI provides:

- ATS Score
- Job Match Score
- Missing Skills
- Learning Roadmap
- Recommended Portfolio Projects

### 5. Report Generation

The analysis is converted into a professional HTML report.

### 6. Email Delivery

The final report is automatically sent to the user's email address.

---

## Screenshots

### Workflow

CareerIQ.pdf

### Form Submission

CareerIQ.pdf

### Email Delivery

CareerIQ.pdf

---

## Future Improvements

- Resume Improvement Suggestions
- LinkedIn Profile Optimization
- Cover Letter Generation
- Interview Question Generation
- Multi-Role Job Matching
- Job Market Trend Analysis
- Resume Database Integration

---

## Project Structure

```text
careeriq-ai-resume-analyzer/
│
├── workflow/
│   └── ai-resume-analyzer-job-matcher.json
│
├── screenshots/
│   ├── CareerIQ.pdf
│
└── README.md
```

---

## Learning Outcomes

This project demonstrates:

- Workflow Automation
- Prompt Engineering
- LLM Integration
- PDF Processing
- Email Automation
- HTML Report Generation
- End-to-End AI Product Development

---

## Author

**Muhammad Ahmed Memon**

GitHub: https://github.com/immemon
