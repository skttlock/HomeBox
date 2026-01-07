# Software List

This is a list of the software to be used/provided in HomeBox. It is separated into three categories: User, Admin, and System. This list is not final and software choices may change.

- Software Selection Criteria
    - **Mature projects**: 3+ years active development
    - **Large user base**: 10,000+ active installations
    - **Docker support**: Official or well-maintained images
    - **Web interfaces**: No command-line user interaction
    - **Declarative configuration**: Works well with NixOS
    - **Strong backup/restore**: Critical for reliability

## Software List

### User
1. Main Apps
    - Dashboard - Dashy
    - Photo Gallery - Immich
    - Office Suite - ~~CryptDrive~~ NextCloud Office
    - File Manager - NextCloud Files
2. Optional Apps
    - Digital Library - Calibre
    - Genealogy - GrampsWeb OR GeneWeb
    - Medical Record Management - Mere Medical OR FastenHealth
    - Password Manager
    - Smart Home Automation
    - Media Server
    - Document Management
    - VPN?
    - Security Camera NVR?
    - Personal Git hosting?
    - Household/Recipe Management? - Grocy/Mealie?
    - Farm Management? - farmOS

### Admin

### System
- Base Operating System - NixOS
- Containers - Docker
- DNS/Ad-blocker - Pi-Hole
- Reverse Proxy - ~~Traefik~~ nginx (included with NextCloud)

## UNDECIDED ASPECTS:

### Base System
- **Management interface**: Portainer Community Edition
- **Remote access**: Tailscale mesh networking
- **Backup system**: Automated daily backups to external drive

### Possible Applications
- Jellyfin - Media streaming server
- Home Assistant - Smart home automation hub
- Vaultwarden - Password manager (Bitwarden compatible)
- Plex Media Server
- Paperless-ngx (document management)
- Wireguard VPN server
- ~~Gitea~~ Forgejo (personal Git hosting)
- Monitoring stack (Grafana/Prometheus)
- Frigate (security camera NVR)
- Custom applications per customer request
