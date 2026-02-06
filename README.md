# Media Server
Dockerized media automation with VPN protection.

## Features
- **VPN:** Gluetun with Mullvad (Wireguard)
- **Downloader:** qBittorrent
- **Management:** Sonarr, Radarr, Prowlarr, Bazarr
- **Media Server:** Emby

## Setup
1. Copy `sample.env` to `.env`.
2. Fill in Mullvad keys and local paths.
3. Run `docker compose up -d`.