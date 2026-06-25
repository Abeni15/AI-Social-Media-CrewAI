# AI-Powered Social Media Management System Using CrewAI

## Project Overview

This project is a multi-agent AI system developed using the CrewAI framework. The system automates the social media content creation workflow for small businesses by assigning specialized responsibilities to multiple AI agents.

Given a business description, platform, and target audience, the system generates:

* Audience Analysis
* Content Strategy
* Content Ideas
* Ready-to-Post Social Media Content
* Content Quality Review
* Posting Schedule

The project demonstrates how multiple AI agents can collaborate to solve a real-world business problem.

---

## Problem Statement

Small businesses often face challenges in:

* Understanding their target audience
* Creating engaging content consistently
* Generating new content ideas
* Maintaining a posting schedule
* Evaluating content quality

This system addresses these challenges through a team of AI agents working together.

---

## Framework Used

**CrewAI**

CrewAI enables multiple specialized AI agents to collaborate through sequential workflows and task delegation.

---

## Technology Stack

* Python
* CrewAI
* Ollama
* Llama 3.2 3B
* LiteLLM

---

## System Architecture

User Input
↓
Market Analyst
↓
Content Strategist
↓
Content Creator
↓
Quality Reviewer
↓
Scheduler
↓
Final Social Media Management Plan

---

## Agents

### Market Analyst

Analyzes the business niche, audience characteristics, content themes, and marketing opportunities.

### Content Strategist

Generates creative and engaging social media content ideas.

### Content Creator

Creates ready-to-post social media content including captions, hashtags, calls-to-action, and visual suggestions.

### Quality Reviewer

Evaluates content quality based on clarity, grammar, engagement, and relevance.

### Scheduler

Creates an optimized one-week social media posting calendar.

---

## Installation

### 1. Install Ollama

Download and install Ollama.

### 2. Download the Model

Run:

ollama pull llama3.2:3b

### 3. Install Dependencies

pip install -r requirements.txt

### 4. Run the Project

python main.py

---

## Example Input

Business Name: Physics Academy

Business Type: Online Physics Tutoring

Platform: Instagram

Target Audience: High School Students

---

## Output

The system generates:

* Audience Analysis Report
* Marketing Opportunities
* Content Ideas
* Social Media Posts
* Quality Evaluation
* Posting Calendar

---

## Future Improvements

* Web-based Streamlit interface
* Persistent memory for previous campaigns
* Trend analysis using external APIs
* Export reports to PDF
* Social media analytics integration

---

## Author

Abenezer

Developed as a CrewAI Multi-Agent System project.

