# 🚀 Azure Container App with CI/CD Pipeline

![Azure](https://img.shields.io/badge/Azure-Cloud-blue?logo=microsoft-azure)
![Docker](https://img.shields.io/badge/Docker-Container-blue?logo=docker)
![GitHub Actions](https://img.shields.io/badge/GitHub-Actions-black?logo=github)
![CI/CD](https://img.shields.io/badge/CI/CD-Automated-green)

A complete beginner-friendly project demonstrating DevOps practices by deploying a containerized web application on Azure with full CI/CD automation.

## 📋 Project Architecture
GitHub Repository → GitHub Actions → Azure Container Registry → Azure Container Instances

## 🛠️ Technologies Used
- **Azure Container Registry (ACR)** - Private Docker registry
- **Azure Container Instances (ACI)** - Serverless containers
- **Docker** - Containerization platform
- **GitHub Actions** - CI/CD automation
- **Nginx** - Web server

## 🚀 Quick Start

### Prerequisites
- Azure Free Tier Account
- GitHub Account
- Git Bash

### Manual Deployment
```bash
# Clone repository
git clone https://github.com/YOUR_USERNAME/azure-container-app.git
cd azure-container-app

# Build and push container
docker build -t myappregistry2001.azurecr.io/my-web-app:v1 .
docker push myappregistry2001.azurecr.io/my-web-app:v1

📁 Project Structure
azure-container-app/
├── .github/
│   └── workflows/
│       └── deploy.yml          # CI/CD Pipeline
├── index.html                  # Web application
├── Dockerfile                  # Container definition
└── README.md                   # Project documentation

🔧 CI/CD Features
✅ Automated Builds - Triggered on git push
✅ Container Registry - Secure image storage
✅ Azure Deployment - Automatic to Container Instances
✅ Zero Downtime - Seamless updates
✅ Version Tracking - Git SHA based tagging

🌐 Live Application
URL: http://mywebapp-3bbdbac9.eastus.azurecontainer.io/

practices

📝 Step-by-Step Implementation
Setup: Azure resources & GitHub repository

Development: Web app & Docker container

Deployment: Manual container deployment

Automation: CI/CD with GitHub Actions

Documentation: Professional README


Project by Akshat Dwivedi
