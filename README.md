# DevOpsify the Golang Web Application

The main goal of this project is to implement DevOps practices in the Go web application. The project is a simple website written in Golang. It uses the `net/http` package to serve HTTP requests.

## Project Overview

This project involves the following DevOps practices:
- **Creating Dockerfile (Multi-stage build)**
- **Containerization**
- **Continuous Integration (CI)**
- **Continuous Deployment (CD)**
- **GitOps with ArgoCD and AWS EKS**

## Prerequisites

- **Golang**
- **Docker**
- **AWS CLI**
- **EKS CTL**
- **Kubectl**
- **Helm**
- **ArgoCD**

## Steps to Implement DevOps Practices

### 1. Creating Dockerfile (Multi-stage build)

The Dockerfile is used to build a Docker image containing the Go web application and its dependencies. A Multi-stage build reduces the size of the final Docker image and enhances security by removing unnecessary files and packages.

### 2. Containerization

Containerization is the process of packaging an application and its dependencies into a container. Docker is used to containerize the Go web application.

#### Build, Run, and Push Docker Image

### 3. Continuous Integration (CI)

CI automates the integration of code changes into a shared repository. GitHub Actions is used to implement CI for the Go web application.

### 4. Continuous Deployment (CD)

CD automates the deployment of code changes to a production environment. ArgoCD is used to implement CD for the Go web application.

### 5. GitOps with ArgoCD and AWS EKS

The ArgoCD application deploys the Go web application to a Kubernetes cluster and keeps it in sync with the Git repository.

## Project Steps:

1. Run the project locally
2. Create a multi-stage Docker image
3. Create Kubernetes ingress, service, and deployment files
4. Create an AWS IAM user (optional but recommended)
5. Install and configure AWS CLI
6. Install Kubectl and AWS EKS
7. Install NGINX
8. Apply Kubernetes files
9. DNS map the load balancer
10. Move Kubernetes files to Helm template folder
11. Delete all the Kubernetes files applied
12. Install Helm charts
13. Uninstall the Helm project
14. Install the project on Helm charts for testing
15. Install ArgoCD
16. Obtain the password from the secret file
17. Create a new application by connecting the GitHub repository
18. Configure continuous integration and delivery

## Conclusion

This project showcases the complete end-to-end process of implementing DevOps practices, from containerization to continuous deployment using GitOps with AWS EKS and ArgoCD. It demonstrates the efficiency and reliability of modern DevOps tools and practices in managing and deploying applications.
