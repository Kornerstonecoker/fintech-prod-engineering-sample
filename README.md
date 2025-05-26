# Fintech Production Engineering Sample

This repository showcases my production engineering work for a fintech platform I’m building. It focuses on Dockerization and CI/CD pipelines for both frontend and backend services. The goal of this sample is to demonstrate how I approach real-world DevOps workflows using GitHub Actions and Docker.

##  What’s Included

This is a stripped-down version of a larger platform. I've extracted only the parts that reflect my work in production engineering:

### GitHub Actions Pipelines
Located in `.github/workflows/`

- **backend.yml** – Builds, tests, and optionally deploys the backend service.
- **frontend.yml** – Handles build and deploy steps for the frontend (Next.js) app.


These workflows automate testing, building Docker images, and preparing for deployment in staging/production environments.

---

### Dockerfiles

- **Dockerfile.backend** – Defines a container image for the backend API (Node.js + TypeScript).
- **Dockerfile.frontend** – Dockerfile for the frontend (Next.js + TypeScript).
- **Dockerfile.backend.dev / Dockerfile.frontend.dev** – Development versions of the above for local use with hot-reloading.

These files are designed to support both local development and production-ready builds.

---

### Docker Compose

- **docker-compose.yml** – Spins up both the frontend and backend in development.
- **docker-compose.prod.yml** – Used for production builds and container orchestration.

These files define service dependencies, environment variables, and port mappings for a seamless multi-container setup.

---

## What I Learned

Working on this platform gave me hands-on experience with:
- Creating automated pipelines using GitHub Actions
- Writing optimized and clean Dockerfiles
- Using Docker Compose to manage multiple services
- Managing separate environments for development and production
- Ensuring code quality through automated linting and testing
- Structuring CI workflows that are scalable and maintainable

---

## 🔒 Note

This is a sample focused on production engineering. The actual business logic and application secrets have been removed to protect project integrity. If you’d like more details or walkthroughs, I’m happy to share privately during an interview.

