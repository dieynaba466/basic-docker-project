# Projet Serveur HTTP Minimaliste avec Docker

## Prérequis
- Docker installé
- Docker Compose installé (facultatif)

## Installation et exécution

### Exécution sans Docker Compose
```bash
docker build -t my-http-server .
docker run -p 8000:8000 my-http-server
