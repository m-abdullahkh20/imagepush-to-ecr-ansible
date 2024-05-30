# Automated Docker Image Deployment with Ansible

## Overview

This project aims to automate the deployment of Docker images to Amazon ECR (Elastic Container Registry) using Ansible. By leveraging automation, developers can streamline the process of building, tagging, and pushing Docker images, reducing manual effort and ensuring consistency in deployments.

## Features

- Automatically builds Docker images from a Dockerfile.
- Tags Docker images with the appropriate ECR repository URL.
- Pushes Docker images to Amazon ECR.
- Supports seamless integration with existing CI/CD pipelines.
- Easily configurable for different AWS regions and ECR repositories.

## Prerequisites

Before using this automation script, ensure you have the following prerequisites installed:

- Docker: [Installation Guide](https://docs.docker.com/get-docker/)
- Ansible: [Installation Guide](https://docs.ansible.com/ansible/latest/installation_guide/index.html)
- AWS CLI: [Installation Guide](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-install.html)

Additionally, make sure you have AWS credentials configured with appropriate permissions to
