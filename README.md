# 🐳 Dockerized Fullstack Pipeline — Demo

Full CI/CD pipeline from GitHub to production

> **DevOps Track — Demo Showcase** | **Real Problem, Synthetic Data**

## Overview
**Problem:** Manual deploys are slow and error-prone

**Solution:** Full CI/CD pipeline from GitHub to production This demo proves the engineering approach with synthetic data.

## Architecture
```
Code → GitHub → CI/CD → Docker → Linux → Nginx → SSL
```

## Tech Stack
- Docker, Linux, Nginx, GitHub Actions

## Features
- Dockerfile & Compose\n- Nginx reverse proxy\n- GitHub Actions CI

## Security
- Validation, JWT/RBAC, Rate limiting, No real secrets

## Screenshots
![Demo](./screenshots/demo.png)

## Demo
- **Demo Data:** `demo-data.json`
- **Live:** `https://kero.10001mb.com/demo/dockerized-fullstack-pipeline-demo` *(placeholder)*

## Installation
```bash
git clone https://github.com/KeroNaderDev/dockerized-fullstack-pipeline-demo.git
cd dockerized-fullstack-pipeline-demo
npm install
cp .env.example .env
npm run dev
```

## Usage
```bash
npm run dev
```

## What I Learned
- DevOps end-to-end design
- Demo vs real data separation
- Professional portfolio structure

---
*Track: DevOps • Portfolio: [KeroNaderDev](https://github.com/KeroNaderDev)*
