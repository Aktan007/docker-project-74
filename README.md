# docker-project-74

[![CI](https://github.com/Aktan007/docker-project-74/actions/workflows/push.yml/badge.svg)](https://github.com/Aktan007/docker-project-74/actions/workflows/push.yml)

## Docker Hub

[aktan007/docker-project-74](https://hub.docker.com/r/aktan007/docker-project-74)

## Requirements

- Docker >= 24
- Docker Compose >= 2

## Setup

Copy the environment file and fill in the values:

```bash
cp app/.env.example app/.env
```

## Commands

| Command | Description |
|---|---|
| `make dev` | Start the application in development mode |
| `make test` | Run tests inside Docker |
| `make setup` | Install dependencies |
| `make ci` | Run CI pipeline (tests inside Docker) |
