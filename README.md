# AI-Powered Job Email Classifier

An automated email classification workflow built using n8n, Docker, Gmail API, Google OAuth2, and Groq LLM to help job seekers efficiently manage inbox overload.

## Features

- Fetches unread Gmail emails every hour
- Uses AI to classify emails into:
  - REPLY
  - NEW_JOB
  - IGNORE
- Automatically labels important emails
- Marks irrelevant emails as read
- Self-hosted using Docker
- Secure OAuth2 authentication
- Cloud deployment ready

## Tech Stack

- n8n
- Docker / Docker Compose
- Gmail API
- Google Cloud OAuth2
- Groq API (llama-3.3-70b-versatile)
- GitHub
- CI/CD Ready

## Workflow Overview

1. Schedule Trigger
2. Gmail Email Fetch
3. Loop Processing
4. AI Classification
5. Conditional Routing
6. Gmail Labeling / Read Status Update

## Setup Instructions

### Clone Repository
```bash
git clone <your-repo-url>
cd n8n-docker
