# Task 5 — Local Kubernetes Cluster with Minikube

Objective: Deploy and manage a simple application (NGINX) on a local Kubernetes cluster using Minikube.

## What’s included

- `deployment.yaml` — Kubernetes Deployment (3 replicas) using `nginx:stable`.
- `service.yaml` — Kubernetes Service (NodePort) exposing the deployment.
- `screenshot-instructions.txt` — directions for the required screenshots (pods / services / logs).

## How to run (local)

1. Start Minikube:
   ```bash
   minikube start --driver=docker
   ```
