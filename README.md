# 🧪 Local Jenkins CI/CD Pipeline

## 📌 Project Overview

This project sets up a local Jenkins instance using Docker, builds a simple Python app, and runs tests using a freestyle CI/CD job.

## 🛠️ Tools Used
- Jenkins (via Docker)
- Python, pytest
- GitHub

## 🚀 Features
- Jenkins Freestyle job pulling from GitHub
- Executes unit tests with `pytest`
- Fully containerized setup

## 🔧 Steps to Reproduce
1. Clone the repo
2. Run Jenkins using Docker
3. Create and configure freestyle job
4. Trigger build manually or via GitHub webhook

## 🧪 Example Test
```bash
pytest simple-app/test_app.py
```

Follow the SOP for detailed steps: https://docs.google.com/document/d/1_ofAxR41-VMHUKGrVeH_HRInE0_t2WIOgvLa9z2zoCI/edit?tab=t.0
