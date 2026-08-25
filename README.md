# Docker-Compose

Generalized Docker Compose templates for homelab services / self-hosted stacks. Please adapt these per-deployment rather than run as-is.

## Scope

The types of services that will land here involve reverse proxies, monitoring, etc. There may be more Ansible/Terraform in the future, but that will likely be its own repository.

## Conventions

**Directory structure:** `service-name/docker-compose.yaml`, `service-name/.env`

**Secrets/env:** Placeholder `.env` files per service. No real values are committed.

**Networking:** Mostly service-local networks — my personal Traefik proxy network is handled through a separate `config.yaml` file.

**Volumes/paths:** Placeholder paths (e.g. `/path/to/data`) that need substitution before use.

**Image tagging:** `:latest` unless otherwise noted in the file.

## Credit

Credit where credit is due, a lot of what I have learned and a lot of these files come from [Jim's Garage](https://www.youtube.com/@Jims-Garage). I highly suggest visiting his channel as he is a wealth of knowledge and I wouldn't enjoy this nerdy hobby as much as I do without his videos.
