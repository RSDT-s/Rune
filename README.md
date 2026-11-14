# Rune — Android Music Player

<p align="center">
  <strong>A lightweight, ad-free, Amethyst OLED Android music player built with Kotlin & Jetpack Compose.</strong>
</p>

<p align="center">
  <img alt="Platform" src="https://img.shields.io/badge/Platform-Android%208.0%2B-8B5CF6?style=flat-square" />
  <img alt="UI" src="https://img.shields.io/badge/UI-Jetpack%20Compose%20%2B%20Material%203-C084FC?style=flat-square" />
  <img alt="Engine" src="https://img.shields.io/badge/Audio-Media3%20ExoPlayer-1A1A20?style=flat-square" />
  <a href="https://ko-fi.com/rs_dt">
    <img alt="Ko-fi" src="https://img.shields.io/badge/Support-Ko--fi-8B5CF6?style=flat-square" />
  </a>
</p>

---

## ✨ Features

- **Amethyst OLED Design:** Pure dark `#0E0E11` aesthetic crafted for OLED screens with smooth transitions and low battery impact.
- **Hybrid Library & Streaming:**
  - Scan local audio files (`.mp3`, `.flac`, `.wav`, `.m4a`, `.ogg`).
  - Stream tracks on demand via selectable servers with a **Data Saver** mode (~80 kbps vs High Fidelity).
  - Save online tracks for **Offline** playback directly inside the app.
- **Advanced Audio Engine:**
  - **5-Band Equalizer** + **Bass Boost** with 6 built-in presets (*Flat, Bass Boost, Rock, Pop, Electronic, Vocal*) and **Custom Saved Presets**.
  - **Speed, Pitch & Reverb Controls** with 1-tap *Slowed + Reverb* and *Nightcore* modes.
  - **Crossfade Transitions** (`Off`, `2s`, `4s`, `6s`), **Skip Silence**, and **Play Over Games** (ignore audio focus).
- **Smart Playback & Lyrics:**
  - Background playback with lock-screen & notification controls (`MediaSessionService`).
  - **Up Next Queue** viewer, **Shuffle**, and **Repeat** (`Off`, `All`, `One`).
  - Live auto-scrolling **Synced Lyrics** powered by [LRCLIB](https://lrclib.net/).
  - **Sleep Timer** with a smooth 10-second fade-out.
  - Intuitive gestures: swipe artwork or mini-player to skip, swipe down to minimize, double-tap artwork to favorite.
- **Hybrid Playlists & Backups:**
  - Combine local and online tracks in playlists, plus an automatic **Liked Songs** collection and **Most Played** / **Favorites** filters.
  - Share tracks with clean **Rune deep links**.
  - Export and restore everything (playlists, favorites, EQ presets, stats) in a portable `.json` file.
- **Built-in Updater:** Quietly checks GitHub Releases on launch and shows release changelogs when updated.

---

## 📲 Installation

1. Go to the [**Releases**](https://github.com/TU_USUARIO_GITHUB/Rune/releases/latest) page.
2. Download the latest `app-release.apk`.
3. Open the APK on your Android device (Android 8.0 Oreo or newer required) and allow installation from unknown sources if prompted.

> **Tip:** If Android stops music while gaming or with the screen off, go to **Support > Open App Battery & Permissions** inside Rune and set battery usage to **Unrestricted**.

---

## ☕ Support the Creator

I created Rune with love — **no ads, no subscriptions, free forever.**  
However, if you enjoy using it, I'd really appreciate your support!

[![Support on Ko-fi](https://img.shields.io/badge/Support%20RSDT%20on%20Ko--fi-8B5CF6?style=for-the-badge&logo=ko-fi&logoColor=white)](https://ko-fi.com/rs_dt)

---

## ⚖️ Disclaimer & Legal Notice

- **No Hosting or Distribution:** Rune does **not** host, store, index, or distribute any audio files or copyrighted media on any developer-owned server.
- **Client-Side Playback:** Online playback and optional local offline caching are initiated solely by the user through publicly accessible third-party endpoints.
- **Personal Use Only:** This software is provided as-is for personal, educational, and non-commercial use. Users are solely responsible for complying with applicable copyright laws and the Terms of Service of any third-party platforms they access.
- **No Affiliation:** Rune is an independent project by **RSDT** and is not affiliated with, endorsed by, or connected to any music streaming service or third-party media platform.
- **Removal / Inquiries:** If you are a rights holder and believe any metadata or functionality requires attention, please open an issue in this repository.
