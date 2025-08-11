cat << 'EOF' > README.md
# Kubernetes Minikube Deployment

This project demonstrates deploying Kubernetes using Minikube on an AWS EC2 instance.

## Prerequisites
- AWS EC2 instance (Ubuntu)
- At least 28 GB storage
- GitHub account
- Minikube & kubectl installed

## Setup Steps
1. Launch EC2 instance and connect via SSH.
2. Install required tools (`kubectl`, `minikube`, Docker).
3. Start Minikube:
   ```bash
   minikube start --driver=docker
4.Deploy your Kubernetes workloads.
