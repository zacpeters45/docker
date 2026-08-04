# 🏠 Homelab

> Personal self-hosted infrastructure built with Docker, Debian, and open-source services.


## 📸 Dashboard

*Homepage dashboard 

<img width="1474" height="506" alt="Screenshot 2026-08-01 005619" src="https://github.com/user-attachments/assets/47caac68-256b-4f76-835f-b975d8090753" />


## 📋 Overview

This homelab is designed for learning:

- Linux Administration
- Docker & Containers
- Reverse Proxies
- Networking
- Authentication & SSO
- Monitoring
- Media Automation

---

## 🏗️ Architecture

```text
Internet
    │
Cloudflare
    │
Nginx Proxy Manager
    │
Authentik
    │
─────────────────────────
│         │          │
│         │          └── AdGuard Home
│         └───────────── Arcane
└────────────────────── Jellyfin
                          │
                    Arr Stack
```

---

## 🚀 Running Services

### Infrastructure

| Service | Purpose |
|----------|----------|
| Homepage | Dashboard |
| Authentik | SSO & Authentication |
| AdGuard Home | DNS Filtering |
| Nginx Proxy Manager | Reverse Proxy |
| Portainer | Container Management |
| Vaultwarden | Password Manager |
| Uptime Kuma | Monitoring |

### Media

| Service | Purpose |
|----------|----------|
| Jellyfin | Media Streaming |
| Sonarr | TV Automation |
| Radarr | Movie Automation |
| Prowlarr | Indexer Management |
| Jellyseerr | Media Requests |
| qBittorrent | Download Client |

---

## 🖥️ Environment

```yaml
Operating System: Debian Linux
Container Platform: Docker
Container Management: Portainer
Reverse Proxy: Nginx Proxy Manager
Authentication: Authentik
Monitoring: Uptime Kuma
Dashboard: Homepage
DNS: AdGuard Home
```

---

## 🎯 Future Goals

- [ ] Immich
- [ ] WireGuard VPN
- [ ] Grafana
- [ ] Prometheus
- [ ] Automated Backups
- [ ] High Availability Testing

---

## 🔒 Security

The following are intentionally excluded from this repository:

- API Keys
- Authentication Tokens
- SSL Certificates
- Private Keys
- Environment Files
- Databases

Secrets are managed separately and are **not committed** to this repository.

---

## 📚 Repository Contents

```text
docker-compose.yml
README.md
.env.example
.gitignore
```

---

## 🛠️ Current Stack

- Debian Linux
- Docker
- Vaultwarden
- Authentik
- AdGuard Home
- Nginx Proxy Manager
- Homepage
- Arcane
- Uptime Kuma
- Jellyfin
- Sonarr
- Radarr
- Prowlarr
- Jellyseerr
- qBittorrent

---

Built for learning, experimentation, and self-hosting. 🚀
