# Raspberry Pi VPN Gateway Project

Modular setup using Docker for:

- NordVPN Gateway (WireGuard)
- Pi-hole with DNS-over-TLS
- FTP Server
- rsync Backup

## Quick Start

1. Rename `.env` and fill in credentials.
2. Run `docker-compose up -d`

## Notes

- Use external HDD mounted to `./data` for storage.
- FTP server listens on 21 + passive ports 21000–21010.