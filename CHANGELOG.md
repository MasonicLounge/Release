# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added / Добавлено

- Docker Compose orchestration: `api`, `web` (nginx), `postgres`, `minio`, `minio-init`.
  Оркестрация Docker Compose: `api`, `web` (nginx), `postgres`, `minio`, `minio-init`.
- Environment template `.env.example` for the full stack.
  Шаблон окружения `.env.example` для всего стека.
- Container images: `backend/Dockerfile` (multi-stage Go) and `frontend/Dockerfile` (Vite build → nginx).
  Образы контейнеров: `backend/Dockerfile` (multi-stage Go) и `frontend/Dockerfile` (сборка Vite → nginx).