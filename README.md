# Pipeline Node using Jenkins
This repository demonstrates the use of Jenkins for setting up a CI/CD pipeline for a Node.js application.

# Overview
Jenkins is used to automate the testing, building, and deployment of this Node.js application. The pipeline is defined using a `Jenkinsfile`, which allows for fine-grained control over the CI/CD process.

# CI/CD Pipeline

## Jenkins Pipeline
The Jenkins pipeline is defined in the `jenkinsfile` located in the root directory of the repository. This pipeline includes the following stages:

- **Checkout Code**: Clones the repository from the source control.
- **Build Docker Image**: Builds a Docker image for the application.
