# Project 25 — Secure images with Trivy

This demo builds a Docker image and scans it with **Trivy** in GitHub Actions.

## How it works
- Build Docker image in CI
- Run Trivy to generate SARIF (uploaded to GitHub Security)
- Fail CI when HIGH/CRITICAL vulnerabilities are found

## Local quickstart
1. Build:

