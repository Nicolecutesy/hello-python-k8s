# 🚀 Hello Python on Kubernetes

This project demonstrates how to containerize and deploy a basic Python Flask app using Docker and Azure Kubernetes Service (AKS).

## 🧱 Technologies Used
- Python + Flask
- Docker
- Azure Container Registry (ACR)
- Azure Kubernetes Service (AKS)
- Kubernetes Deployment + Service

## 🐳 Run Locally

```bash
docker build -t hello-python-k8s .
docker run -p 5000:5000 hello-python-k8s
