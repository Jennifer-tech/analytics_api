# An Analytics-API using FastAPI + Time-series Postgres

We start by building an analytics API service python, FastAPI, and Time-series Postgres with Timescale.

## DOCKER

- `docker build -t analytics-api -f Dockerfile.web .`
- `docker run analytics-api`

becomes

- `docker compose up --watch`
- `docker compose down` or `docker compose down -v` (to remove volumes)
- `docker compose run app /bin/bash` or `docker compose run app python`
