# From Scratch to Production: Deploying EKS Clusters and Applications with CI/CD using Jenkins and Terraform


# Project Overview
This project focuses on automating the deployment of an EKS (Elastic Kubernetes Service) cluster and containerized applications using Jenkins and Terraform. The primary goal is to streamline the infrastructure setup and application delivery through a CI/CD pipeline.

# Tools and Technologies Used
Infrastructure as Code: Terraform
Continuous Integration/Continuous Deployment (CI/CD): Jenkins
Container Orchestration: Amazon EKS (Elastic Kubernetes Service)
Containerization: Docker
Application Deployment: Kubernetes
Additional Tools: AWS CLI, Helm, Trivy, Sonar, Kubectl
Workflow

# Jenkins Server Setup:

Provision an EC2 instance using Terraform.
Install and configure Jenkins along with necessary tools like AWS CLI, Docker, Terraform CLI, and Kubernetes CLI.

# EKS Cluster Creation:

Use Terraform to write infrastructure configuration files for an EKS cluster.
Deploy the EKS cluster within a private subnet.

# Application Deployment:

Create Kubernetes manifest files to define the NGINX application.
Deploy the application to the EKS cluster.

# CI/CD Pipeline Automation:

Develop a Jenkins pipeline that automates the entire process of EKS cluster creation and application deployment.
Integrate Terraform and Kubernetes into the Jenkins pipeline for continuous integration and deployment.
