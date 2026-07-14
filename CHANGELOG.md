# Changelog

All notable changes to GameDrop are documented here.

## v0.1.0 (2026-07-14)

Initial Windows release.

### Added

- **Real-time deal notifications** — system tray alerts for free games and discounts
- **Multi-provider support** — syncs promotions from Steam, Epic Games Store, GOG, CheapShark, and GamerPower
- **Promotion pipeline** — automated discovery, verification, validation, and moderation workflow
- **Offline cache** — deals remain visible when the internet is down
- **Store filters** — filter by store, deal type, and recency
- **i18n** — English and Bahasa Indonesia
- **Auto-start** — launches with Windows automatically
- **Landing page** — marketing site at gamedrop.com
- **Admin dashboard** — web-based promotion moderation panel

### Technical

- Windows x64 installer (MSI + NSIS)
- Tauri 2 desktop application
- Go REST + SSE API backend
- PostgreSQL database
- Docker Compose deployment ready
- aaPanel Nginx configuration included
