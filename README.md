# Practical-10
# Terraform CI/CD with GitHub Actions

This repository demonstrates how to set up a CI/CD pipeline for Terraform using **GitHub Actions**. The pipeline is designed to automatically initialize, validate, plan, apply, and destroy Terraform configurations on AWS.

---

## 📌 Objectives

- Automate Terraform workflows using GitHub Actions.
- Configure GitHub Secrets for secure AWS credential management.
- Apply infrastructure changes on push to the `main` branch.
- Manually trigger infrastructure destroy actions.

---

## 🛠️ Prerequisites

- GitHub account
- AWS account with **programmatic access** credentials:
  - `AWS_ACCESS_KEY_ID`
  - `AWS_SECRET_ACCESS_KEY`
  - `AWS_SESSION_TOKEN`
- Basic understanding of:
  - Terraform
  - GitHub Actions
  - AWS IAM Roles/Policies

---
