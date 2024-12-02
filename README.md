# My App

This is a simple Node.js app that uses Express.js to serve a "Hello, world!" message. The app is containerized using Docker and deployed to a Kubernetes cluster using a GitOps CI/CD pipeline.

## Overview

This repository contains the application code, a Dockerfile to build the application image, and a CI/CD pipeline using GitHub Actions to automatically deploy the app to a Kubernetes cluster via **Argo CD**.

## Features
- Simple REST API with Express.js.
- Built using Docker for easy containerization.
- CI/CD pipeline that automates deployments using GitHub Actions and Argo CD.

---

## Running Locally

To run this app locally, follow these steps:

### 1. Clone the repository:

```bash
git clone https://github.com/mahirahmed691/gitops.git
cd app-repo

