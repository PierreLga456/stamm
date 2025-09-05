# Logiciels (base)

- `software/docker-compose.yaml` : exemple minimal (MediaWiki, DLNA).
- Variables à adapter : ports, volumes, timezone.

```bash
# Exemples (à exécuter sur la machine cible)
docker compose -f software/docker-compose.yaml up -d
docker ps
