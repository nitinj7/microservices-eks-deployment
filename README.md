# EKS Microservices Deployment

This project demonstrates deploying microservices on AWS Elastic Kubernetes Service (EKS) using Docker, Kubernetes, and CI/CD automation with GitHub Actions. It includes separate services for frontend, backend, and database, each containerized and orchestrated through Kubernetes.

## Table of Contents

- [Overview](#overview)
- [Architecture](#architecture)
- [Technologies Used](#technologies-used)
- [Setup](#setup)
- [Project Steps](#project-steps)
- [Usage](#usage)
- [Monitoring and Scaling](#monitoring-and-scaling)
- [Contributing](#contributing)
- [License](#license)

---

## Overview

This repository contains code and configurations to deploy a simple microservices application to AWS EKS. The project includes:
- Containerized microservices for frontend, backend, and database.
- Amazon Elastic Container Registry (ECR) to store Docker images.
- A CI/CD pipeline with GitHub Actions to automate image building, pushing, and deployment to EKS.

## Architecture

- **Frontend**: Static files served via NGINX.
- **Backend**: REST API service.
- **Database**: MySQL for data persistence.
- **CI/CD**: Automated using GitHub Actions, with GitHub Secrets for secure access to AWS.

## Technologies Used

- **AWS EKS**: Managed Kubernetes service for running containerized applications.
- **Docker**: Containerization of microservices.
- **Amazon ECR**: Repository to store and manage Docker images.
- **Kubernetes**: Orchestration for deployment, scaling, and management.
- **GitHub Actions**: CI/CD automation for continuous deployment.
- **CloudWatch & Prometheus**: Monitoring and logging tools.

---

## Setup

### Prerequisites

- **AWS Account**: [Sign up here](https://aws.amazon.com/) if you don’t have one.
- **AWS CLI**: Install and configure the AWS CLI.
- **kubectl**: Command-line tool to interact with Kubernetes.
- **eksctl**: CLI tool for EKS cluster setup.
