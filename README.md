# Secure DevSecOps CI/CD Pipeline 🚀

A production-style CI/CD pipeline demonstrating DevSecOps practices using
GitHub Actions, Docker, and automated security scanning.

## Tech Stack
- GitHub Actions
- Docker & Docker Hub
- Python (Flask)
- Trivy (Security scanning)

## Pipeline Flow
1. Code pushed to GitHub
2. GitHub Actions triggers pipeline
3. Docker image is built
4. Image is pushed to Docker Hub
5. Trivy scans image for vulnerabilities

## Local Run
```bash
docker build -t secure-app .
docker run -p 5001:5000 secure-app

