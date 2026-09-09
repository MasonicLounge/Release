# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.1.0] - 2026-09-09

### Added / Добавлено

- CI workflow (GitHub Actions): validates `docker compose config` on every push/PR.
  CI workflow (GitHub Actions): валидация `docker compose config` на каждый push/PR.

- Docker Compose orchestration: `api`, `web` (nginx), `postgres`, `minio`, `minio-init`.
  Оркестрация Docker Compose: `api`, `web` (nginx), `postgres`, `minio`, `minio-init`.
- Environment template `.env.example` for the full stack.
  Шаблон окружения `.env.example` для всего стека.
- Container images: `backend/Dockerfile` (multi-stage Go) and `frontend/Dockerfile` (Vite build → nginx).
  Образы контейнеров: `backend/Dockerfile` (multi-stage Go) и `frontend/Dockerfile` (сборка Vite → nginx).

- Companion to **MasonicCore v0.1.0** and **MasonicSkin v0.1.0**. Source builds `api`/`web`;
  future releases will pull pinned images from `ghcr.io/masoniclounge`.
  Парный релиз к **MasonicCore v0.1.0** и **MasonicSkin v0.1.0**. `api`/`web` собираются из исходников;
  в следующих релизах — получение закреплённых образов из `ghcr.io/masoniclounge`.