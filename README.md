# Shop Stack

This repository runs the full **Shop application stack** using Docker Compose.

It pulls **pre-built Docker images** for the frontend and backend from **GitHub Container Registry (GHCR)**, so you only need this repo to run the system.

---

## Architecture

- **Frontend**: Angular (served via Nginx)
- **Backend**: Spring Boot (Java)
- **Database**: MySQL
- **Container registry**: GitHub Container Registry (GHCR)

Source repositories:

- Frontend: https://github.com/emillaudon/shop-frontend
- Backend: https://github.com/emillaudon/shop-backend

---

## Prerequisites

- Docker
- Docker Compose (v2)

---

## Run locally

### 1. Create env file

`.env` is not committed. Copy the example file:

**Windows**

```bash
copy .env.example .env

**Mac/Linux**
```
