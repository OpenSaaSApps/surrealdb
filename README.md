# surrealdb

> Click To Deploy SurrealDB — Multi-model Database

[![Sync](https://github.com/opensaasapps/surrealdb/actions/workflows/sync.yml/badge.svg)](https://github.com/opensaasapps/surrealdb/actions/workflows/sync.yml) [![Docker](https://github.com/opensaasapps/surrealdb/actions/workflows/docker.yml/badge.svg)](https://github.com/opensaasapps/surrealdb/actions/workflows/docker.yml) [![Docker Pulls](https://img.shields.io/docker/pulls/thefractionalpm/surrealdb)](https://hub.docker.com/r/thefractionalpm/surrealdb)

Upstream: [surrealdb/surrealdb](https://github.com/surrealdb/surrealdb) · Auto-synced daily

---

## One-Command Deploy

```bash
cp .env.example .env && nano .env
docker compose up -d
```

## Coolify / Dokploy

1. New service → **Docker Compose**
2. Paste `docker-compose.yml`
3. Set env vars in UI
4. Deploy

## Environment Variables

| Variable | Required | Description |
|---|---|---|
| `SURREAL_USER` | ⚪ | |
| `SURREAL_PASS` | ✅ | |
| `SURREAL_PATH` | ⚪ | |

## Image

```
docker pull surrealdb/surrealdb:latest
docker pull thefractionalpm/surrealdb:latest
```

## Ports

| Port | Service |
|---|---|
| `8000` | Main app |

---

*Part of the [OpenSaaSApps](https://github.com/opensaasapps) Click-To-Deploy collection.*
