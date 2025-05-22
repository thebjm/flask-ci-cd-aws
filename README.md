# Flask CI/CD Project (AWS)

This project demonstrates a full DevOps pipeline using Flask, Docker, GitHub Actions, and AWS EC2.

## 🔧 Tech Stack
- Flask (Python)
- Docker
- GitHub Actions
- AWS EC2

## 🚀 CI/CD Pipeline
Push to `main` branch triggers:
- Code checkout
- SSH to EC2
- Docker build and run

## 📂 Structure
```
flask-ci-cd-aws/
├── app/
├── Dockerfile
├── .github/workflows/deploy.yml
```
