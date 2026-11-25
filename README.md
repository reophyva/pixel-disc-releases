<div align="center">

# 💿 Pixel Disc

**Your music, beautifully played — offline, private and hi-res.**

[![Latest release](https://img.shields.io/github/v/release/reophyva/pixel-disc-releases?label=latest&color=4F8DFF)](https://github.com/reophyva/pixel-disc-releases/releases/latest)
[![Android](https://img.shields.io/badge/Android-10%2B-3DDC84?logo=android&logoColor=white)](#-requirements)
[![Downloads](https://img.shields.io/github/downloads/reophyva/pixel-disc-releases/total?color=8A6CFF)](https://github.com/reophyva/pixel-disc-releases/releases)
[![No ads · No tracking](https://img.shields.io/badge/ads%20%26%20tracking-none-success)](PRIVACY.md)

</div>

Pixel Disc is an offline music player for Android that plays the music **you own** — the files
on your phone. No account, no streaming, no ads and no tracking. It's built for hi-res and
lossless libraries, with smooth crossfades, synced lyrics from your own files, smart mixes and
listening stats, all in a clean, modern design.

---

## ✨ Highlights

### 🎧 Playback & sound
- **Crossfade** between songs (0–12 s, equal-power) and **Auto Mix**, which orders your queue so neighbouring songs flow together.
- **Volume leveling** with ReplayGain (track or album), pre-amp, a level for untagged songs, and clipping protection.
- **Equalizer** with your device's bands and presets, plus bass boost, surround and loudness boost.
- **Trim silence** at the start and end of songs — never inside a song; live albums and DJ mixes are left alone.
- **Sleep timer**, and a notification with buttons you choose (shuffle, repeat or favourite).
- Works with the rest of Android: lock screen and notification controls, Bluetooth and headphone buttons, **resume after a restart**, Android Auto and Wear OS browsing, and **“Open with”** for audio files. Can be set as your default music app.

### 💎 Hi-res & lossless
- Plays FLAC, ALAC, WAV, AIFF, MP3, AAC/M4A, OGG and Opus (as supported by your device).
- Shows the real quality of every song — format, sample rate and bit depth — with **Hi-Res** and **Lossless** badges.
- Fast, precise seeking even in large FLAC files.

### 📚 Library
- Songs, Albums, Artists and Genres with search and sorting.
- Smart tag handling: several genres or artists in one tag, grouping of similar genre names, your own genres, and pinned genres and artists.
- Choose which folders to use, and hide short clips such as voice notes.

### 🎶 Queue
- Drag to reorder, swipe to remove (with undo), play history, and one-tap **Reshuffle**.

### 📀 Playlists & mixes
- Create playlists with a name, description and cover (your own image or a generated one); pin favourites; grid or list view.
- **Import and export** M3U and CSV playlists.
- **Premade mixes** made on your device from your library and listening: Daily Mix, mixes for the time of day and day of the week, After Dark, On Repeat, Rediscover, Forgotten Favorites, Favorites, Recently Added, Workout, Focus, Chill, Hi-Res Showcase, Time Machine, Short & Sweet and Long Plays — keep any of them with one tap.

### 🎤 Lyrics from your own files
- Synced, karaoke-style lyrics that light up word by word; tap a line to jump to it.
- Read only from your files: lyrics embedded in MP3, FLAC and M4A tags, a `.lrc` file next to the song, or a `.lrc` file you pick. Nothing is looked up online.

### 📊 Stats & recaps
- Listening streaks, a calendar of the days you listened, minutes and plays.
- Top artists, genres and songs for the last week, month, 3 months, 6 months or year.
- **Recap stories**: a full-screen story of your listening, including your top picks and your “listening personality” — then play your top songs or save them as a playlist.

### 🎨 Appearance
- Light, dark, follow the system, or **switch automatically by the time of day**.
- Five accent colours, three backgrounds, frosted-glass or solid cards, pure-black (AMOLED) mode, corner styles and animation levels.
- A layout made for tablets, and smooth on high-refresh-rate screens.

### 🤖 AI playlist maker (optional)
- Describe a mix — “chill evening, 1 hour” — and Pixel Disc builds it from your library, **on your device**.
- Optionally use Claude with **your own** Anthropic API key for smarter mixes. Turn AI off completely if you prefer.

### 🌐 Artist photos & bios (optional)
- A photo and short biography from Wikipedia, credited to their authors. Off by default.

### 💾 Backups
- Automatic backups (daily, weekly or monthly) to a folder you choose, plus manual backup and restore of playlists, favourites, play counts, listening history and settings.

### 🔄 Auto-updates
- Pixel Disc checks this page for new versions (at most once a day, can be turned off) and installs updates **only with your OK**, after verifying they're genuine.

---

## 📸 Screenshots

<!-- Add images to the screenshots/ folder and replace each placeholder with:
     <img src="screenshots/home.png" width="240" alt="Home"> -->

<table>
  <tr>
    <td align="center" width="33%"><b>Home</b><br><sub>Screenshot coming soon</sub></td>
    <td align="center" width="33%"><b>Now playing</b><br><sub>Screenshot coming soon</sub></td>
    <td align="center" width="33%"><b>Synced lyrics</b><br><sub>Screenshot coming soon</sub></td>
  </tr>
  <tr>
    <td align="center"><b>Library</b><br><sub>Screenshot coming soon</sub></td>
    <td align="center"><b>Queue</b><br><sub>Screenshot coming soon</sub></td>
    <td align="center"><b>Playlists & mixes</b><br><sub>Screenshot coming soon</sub></td>
  </tr>
  <tr>
    <td align="center"><b>Stats</b><br><sub>Screenshot coming soon</sub></td>
    <td align="center"><b>Recap</b><br><sub>Screenshot coming soon</sub></td>
    <td align="center"><b>Settings</b><br><sub>Screenshot coming soon</sub></td>
  </tr>
</table>

---

## 📋 Requirements

- **Android 10 or newer** (API level 29+)
- Music files stored on your device or SD card

## 📥 Install

1. Open the **[latest release](https://github.com/reophyva/pixel-disc-releases/releases/latest)** on your phone and download `PixelDisc-vX.Y.Z.apk`.
2. Open the downloaded file. If Android asks, allow **“Install unknown apps”** for your browser or file manager, then go back.
3. Tap **Install**, open Pixel Disc and follow the short setup.

### Updates
Pixel Disc checks for new versions automatically (at most once a day) and shows what's new.
Tap **Update now**, and the first time, allow **“Install unknown apps”** for Pixel Disc. Every
update is checked before installing: its SHA-256 checksum must match, and it must be signed by the
same developer certificate as the app you already have. You can also check manually, or turn the
automatic check off, in **Settings → About**.

## 🔐 Verify your download

Each release lists the SHA-256 checksum of the APK (also inside `version.json`). To check it:

- **Windows (PowerShell):** `Get-FileHash .\PixelDisc-vX.Y.Z.apk -Algorithm SHA256`
- **macOS / Linux:** `shasum -a 256 PixelDisc-vX.Y.Z.apk`

The result must match the checksum on the release page exactly.

## 🛡️ Privacy

- **No ads, no analytics, no tracking, no account.** Your music, playlists and listening history stay on your device.
- Only optional features go online: Wikipedia for artist info (off by default), Anthropic only with your own API key, and the daily update check on GitHub (can be turned off).

Read the full **[Privacy Policy](PRIVACY.md)**.

## 💬 Support & feedback

Questions, bug reports or ideas: **[pixeldisc.support@gmail.com](mailto:pixeldisc.support@gmail.com)**

In the app, **Settings → General → Diagnostics** lets you copy or save a log to attach to your message.

## 🙏 Credits

- Created and developed by **ReOpHyVa**
- Built with the assistance of Claude Code by Anthropic
- Open-source components are listed in the app under **Settings → About → Open-source licenses**.

## 📄 License

Pixel Disc is **proprietary freeware**: free to download and use for personal use. Redistribution,
modification, reverse engineering or re-uploading require written permission. The source code is
not public. See **[LICENSE](LICENSE)**.

© 2026 ReOpHyVa. All rights reserved.
