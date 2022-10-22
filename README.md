# Transmission with Caddy in Docker

Use Transmission with green https for the web interface on your local network.

Requirements
- Own domain
- Cloudflare DNS setup for your domain
- Cloudflare API Token with zone and dns access

Environment variables:

- WHITELIST
- ADMIN_USER
- ADMIN_PASS
- TRANSMISSION_DOMAIN
- APP_DIR
- FILE_DIR
- FILE_DIR2
- CLOUDFLARE_EMAIL
- CLOUDFLARE_API_TOKEN