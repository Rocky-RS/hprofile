# 🚀 CI/CD Pipeline with GitHub Actions, Docker, AWS ECR & ECS

## 📌 Project Overview
This project demonstrates a complete CI/CD pipeline for deploying a Java web application using GitHub Actions, Docker, and AWS services.

The pipeline automates the process of building, testing, containerizing, and deploying the application to AWS ECS (Fargate).

---

## 🧰 Technologies Used

- GitHub Actions (CI/CD)
- Docker
- AWS ECR (Elastic Container Registry)
- AWS ECS (Fargate)
- AWS RDS (MySQL)
- Maven
- SonarQube (Code Quality)
- Checkstyle

---

## 🔄 CI/CD Workflow

### 1️⃣ Code Integration (CI)
- Code pushed to GitHub
- GitHub Actions pipeline triggered
- Maven build and tests executed
- Code quality checks using SonarQube & Checkstyle

---

### 2️⃣ Build & Containerization
- Docker image created using Dockerfile
- Application packaged as a container

---

### 3️⃣ Push to AWS ECR
- Docker image pushed to AWS ECR repository

---

### 4️⃣ Deployment (CD)
- ECS task definition updated with new image
- Application deployed to ECS Fargate
- Service automatically updated with latest version

---

### 5️⃣ Database Integration
- AWS RDS (MySQL) used as backend database
- Credentials securely managed using GitHub Secrets

---

## 🔐 Secrets Used

- AWS_ACCESS_KEY_ID  
- AWS_SECRET_ACCESS_KEY  
- REGISTRY  
- RDS_ENDPOINT  
- RDS_USER  
- RDS_PASS  
- SONAR_TOKEN  

---

## 📦 Project Architecture
