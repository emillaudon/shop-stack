# Shop stack

This repository runs the full shop application using Docker Compose.

It uses pre-built Docker images, so you only need this repo to start everything.

---

## Includes

- Frontend: Angular (served via Nginx)
- Backend: Spring Boot (Java)
- Database: MySQL

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
```

**Mac / Linux**

```bash
cp .env.example .env
```

---

### 2. Start the stack

```bash
docker compose pull
docker compose up
```

---

## URLs

- Frontend: http://localhost:4200
- Backend: http://localhost:8080

---

## Notes

- Docker images are built automatically via GitHub Actions
- This repo only contains Docker Compose configuration
- `.env` is intentionally ignored
