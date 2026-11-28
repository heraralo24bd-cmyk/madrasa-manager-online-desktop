# Alif Edu Manager — Desktop app (Windows)

Tauri v2 wrapper around https://app.alifedumanager.com/login — the same construction
as the offline Madrasa Manager desktop app (Tauri + NSIS installer).

- Opens the login page directly; login and licence stay on the server.
- NSIS installer (per-user): desktop shortcut + Start Menu entry.
- Built on GitHub Actions (`windows-latest`); each push to `main` rebuilds
  and updates the v1.1.0 release with the new installer.
