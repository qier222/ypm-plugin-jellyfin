# Jellyfin for YesPlayMusic

English · [简体中文](README.zh-CN.md)

Official Jellyfin music source plugin for [YesPlayMusic](https://github.com/qier222/YesPlayMusic) 3.0.

## Installation

- **Option 1 (Recommended)**: Open YesPlayMusic → **Settings → Plugins → Official Plugins**, then install **Jellyfin**.
- **Option 2**: Open **Settings → Plugins → Install Plugin** and paste `github.com/qier222/ypm-plugin-jellyfin`.

## Configuration

1. Open **Settings → Plugins → Jellyfin → ⋯ → Plugin Settings…** and fill in:
   - **Server address**: e.g. `http://127.0.0.1:8096`
   - **Username** and **Password** (or an **API key** to skip password sign-in)
   - **Music library ID (optional)**: limit browsing to a single library, or leave blank for all
2. Switch the active music source to **Jellyfin**.

## Features

- Home: Recently Added, Recently Played, Most Played, Playlists, and personalized recommendations
- Full library browsing (tracks, albums, artists, playlists) and search
- Album, artist, and playlist pages with playlist creation, renaming, deletion, and track management
- Liked tracks, saved albums, followed artists (synced with Jellyfin favorites), and play history
- Direct playback (High / Lossless) or 192 kbps MP3 transcoding (Standard), with playback reporting
- Native synced lyrics (Jellyfin 10.9+ `/Audio/{id}/Lyrics`) and similar tracks
- Multi-language support

## License

[MIT](LICENSE)
