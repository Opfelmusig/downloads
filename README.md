<div align="center">
  <img align="center" width="128px" src="https://github.com/user-attachments/assets/a9ed9c53-84ab-4a65-a7d0-50b42a9552d5" />
  <h1 align="center">Öpfelmusig</h1>

An alternative Apple Music client.  
Öpfelmusig is the literal Swiss German translation of "Apple Music"

</div>
<br>

> \[!IMPORTANT]
>
> The source code is currently private. This might change in the future.

### Download
[Latest Version](https://github.com/opfelmusig/downloads/releases/latest)

On macOS, the app is not signed or notarized and may appear damaged. After installing it, run `sudo xattr -rd com.apple.quarantine "/Applications/Öpfelmusig.app"`.

## Setup

A valid Apple Music subscription is required.

### Apple Music Token

1. Open https://music.apple.com
2. Open Dev Tools (press `F12` or right-click anywhere on the page and select Inspect).
3. Navigate to the Application tab (or Storage tab depending on your browser).
4. Look at the left sidebar menu, find Cookies, and click on `music.apple.com`.
5. Search or filter the list for the cookie named `media-user-token` or similar.
6. Click on that token and copy the full text shown in the cookie value box at the bottom of the panel.

### Widevine credentials

> \[!CAUTION]
>
> Öpfelmusig cannot provide or help obtain Widevine credentials.
> Without them, you can finish setup and browse Apple Music, but protected songs will not play.

When the Widevine error appears during playback, click Open folder. Add either `device.wvd` or both `device_private_key.pem` and `device_client_id_blob` to that folder, then try playing the song again.

## Features

- Apple Music Playback
- Browse Apple Music Catalog
- Albums, artists, playlists, history, and recommendations
- Synchronized lyrics with translations and transliterations
- Animated Artworks
- Library management
  - Add and remove songs and albums
  - Favorite, unfavorite, or mark items as Suggest Less
  - Pin and unpin songs, albums, artists, and playlists
  - Create, edit, move, and delete playlists
  - Add, remove, and reorder playlist tracks
  - Create playlist folders and organize playlists inside them
- Reports playback activity to Apple Music so Recently Played, recommendations, stats.fm, and Apple Music data exports continue to work
- Immersive player and animated artwork
- Mini-player and lyrics widgets
- Equalizer
- Discord Rich Presence
- Native media controls and system-tray support
- Updater

## Restrictions

- Music videos are not supported and are intentionally hidden.
- No Lossless, Dolby Atmos, or Spatial Audio. Playback is limited to 256 kbps AAC-LC stereo.
- Apple Music tokens can expire, requiring you to sign in again.
- Features may stop working when Apple changes its private APIs.
- First launch and initial synchronization may take a while, particularly on Linux.

## Feature Ideas

Features that may be added in the future based on interest or whenever I feel like it.

- Control playback from a phone on the same local network
- Apple Music Autoplay
- Themes (color or design)
- Crossfade
- Last.fm
- Statistics
- Library Backup (export/import)
- Better Keyboard navigation
- Apple Music login instead of token based authentication

## Bug and Feature Reports

Just report them here in this repo as issues. Include the details in Settings > Info.

## Showcase

Immersive Fullscreen  
<img width="3136" height="2126" alt="immersive fullscreen" src="https://github.com/user-attachments/assets/f05d4714-4e62-4f62-8857-d6f31cc73560" />

Immersive Fullscreen Artwork  
<img width="3136" height="2126" alt="immersive fullscreen artwork" src="https://github.com/user-attachments/assets/148004f1-3a6d-4949-b3cc-8eeef2232dbb" />

Album Page  
<img width="3136" height="2126" alt="album page" src="https://github.com/user-attachments/assets/e4a8ef82-a2c2-4920-b2cc-52cd8e28409e" />

Artist Page  
<img width="3136" height="2126" alt="artist page" src="https://github.com/user-attachments/assets/474c557d-099b-4da5-a610-1709228a9dc6" />

Search Page  
<img width="3136" height="2126" alt="search page" src="https://github.com/user-attachments/assets/ec5a9801-b24c-4392-83e9-03bebf8ea889" />

Home Page  
<img width="3136" height="2126" alt="home page" src="https://github.com/user-attachments/assets/78354aca-339d-47c3-bcdc-593b50c44e21" />

Mini Player  
<img width="572" height="302" alt="mini player" src="https://github.com/user-attachments/assets/d975edae-68a1-4ed8-a0ce-6bdcc9cafd53" />

Immersive Mini Player  
<img width="432" height="432" alt="immersive mini player" src="https://github.com/user-attachments/assets/ee1b2846-d332-4ad7-8be8-5a3e245ef505" />

Lyrics Widget (Also available with transparent background)  
<img width="819" height="613" alt="lyrics widget" src="https://github.com/user-attachments/assets/2e8a284b-d993-4254-896a-79b7654537ab" />

---

:apple::musical_note: is brought to you by [Noan](https://waradu.dev).
Check out my friends at [Epilogue](https://epilogue.team).

Looking for a local first music player? Try out [Vleer](https://vleer.app).
