<div align="center">
  <img align="center" width="128px" src="https://github.com/user-attachments/assets/a9ed9c53-84ab-4a65-a7d0-50b42a9552d5" />
  <h1 align="center">Öpfelmusig</h1>

An alternative Apple Music Client.

</div>
<br>

> \[!IMPORTANT]
>
> Source Code will stay private.

### Download
[Latest Version](https://github.com/opfelmusig/downloads/releases/latest)

## Setup

### Apple Music Token

1. Open https://music.apple.com
2. Open Dev Tools (press `F12` or right-click anywhere on the page and select Inspect).
3. Navigate to the Application tab (or Storage tab depending on your browser).
4. Look at the left sidebar menu, find Cookies, and click on `music.apple.com`.
5. Search or filter the list for the cookie named media-user-token or similar media user identification.
6. Click on that token and copy the full text string shown in the cookie value box at the bottom of the panel.

### Widevine license

> \[!CAUTION]
>
> Öpfelmusig cannot provide or help obtain Widevine credentials.
> Without them, you can finish setup and browse Apple Music, but protected songs will not play.

When the Widevine error appears during playback, click Open folder. Add either `device.wvd` or both `device_private_key.pem` and `device_client_id_blob` to that folder, then try playing the song again.

## Features

- Browse Apple Music Catalog
- Albums, artists, playlists, history, and recommendations
- Synchronized lyrics with translations and transliterations
- Immersive player and animated artwork
- Mini-player and lyrics widgets
- Equalizer
- Discord Rich Presence
- Native media controls and system-tray support

## Restrictions

- Max `256 kbps AAC-LC stereo` (Apple Music Web Quality)
- Can break at any time (uses private undocumented Apple Music APIs)
- First load and login can take its time especially on Linux

## Bug and Feature Reports

Just report them here in this repo as issues. Include the details in Settings -> Info.

## Showcase

Immersive Fullscreen
<img width="3136" height="2126" alt="immersive fullscreen" src="https://github.com/user-attachments/assets/f05d4714-4e62-4f62-8857-d6f31cc73560" />

Immersive Fullscreen Artwork
<img width="3136" height="2126" alt="immersive fullscreen artwork" src="https://github.com/user-attachments/assets/148004f1-3a6d-4949-b3cc-8eeef2232dbb" />

Artist Page
<img width="3136" height="2126" alt="artist page" src="https://github.com/user-attachments/assets/cc84783a-83f3-4411-b371-ecec0b775c61" />

