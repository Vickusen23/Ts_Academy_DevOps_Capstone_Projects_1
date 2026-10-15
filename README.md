# TS-Academy DevOps Capstone Project 1

## Project Overview

This project demonstrates the deployment and operation of the Docker Voting App as part of the TS-Academy DevOps Capstone.

## Objectives

- Run the application locally using Docker Compose.
- Improve container security.
- Provision Kubernetes infrastructure using Terraform.
- Automate builds and deployments with GitHub Actions.
- Deploy and roll back releases using Helm.

## Application Services

- Vote: accepts votes.
- Redis: queues votes.
- Worker: processes votes and stores them in PostgreSQL.
- PostgreSQL: stores vote data.
- Result: displays voting results.

## Local Setup

Run the application using Docker Compose:

```bash
docker compose up -d --build
```

Check the running services:

```bash
docker compose ps
```

## Local URLs

- Voting app: http://localhost:8080
- Results app: http://localhost:8081

## Evidence

Screenshots will be saved in `docs/screenshots/`.

## Project Status

The application has been started locally, and a test vote has been recorded. Further container security, infrastructure, CI/CD and Kubernetes deployment work remains.
