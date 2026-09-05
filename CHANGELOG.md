## v0.1.27

### Added

- Double click to set resize to default

### Fixed

- Sidebar always full width

## v0.1.26

### Added

- Command palette!
  - Navigate Pages, playlists and search catalog
  - Control playback
  - Manage current song like favorite, pin, open, copy link and more
  - Open and close immersive mode, mini player, lyrics widget and sidebar
  - Toggle quick settings
  - Manage the app like check for updates, clear caches, reload, quit and more
- Resizable sidebar and Player Sidebar
- Featured artists in playlists
- Copy öpfelmusig links to songs and albums
- Add to library confirmation
- Change search scope keybind

### Changed

- Seach keybind to `ctrl/cmd+f`

### Fixed

- Back links looping around
- Cleaned up messy and buggy mutation dialogs
- Debug dev tools arrow in compact sidebar
- Lyrics jump while resizing

## v0.1.25

### Added

- See more in home
- Repeat one
- Combined right sidebar button
- Many new keybinds! Check `Settings > Keybinds`
- Right click song in player for menu
- Show star in player, queue and history
- Forward button in titlebar

### Fixed

- Wait for image to load before flipping artwork
- Hide deleted media
- Player overflowing
- Made error page also show correctly on fatal error
- Lyrics mount fast scroll
- Messy/buggy context menu handling
- Player Song and Artist/Album separator
- Titlebar buttons hide and cause layout shift
- Queue wrapping issues
- Queue context hidden even when repeating

## v0.1.22

Cut binary size by ~50%.

- Linux: `16 MB -> 6.5 MB` ~60% smaller (excluding AppImage)
- Windows: `12 MB -> 5.5 MB` ~55% smaller
- macOS: `17 MB -> 9.5 MB` ~45% smaller

## v0.1.20

### Announcement

Öpfelmusig now uses selfhosted runners

### Added

- Check for update on startup and interval (can be disabled)
- Better update error and state handling
- Check for update in login and error pages
- Clear cache size
- New history grouping

### Removed

- Separate sidebar open toggle
- Intel Mac Support

### Fixed

- Looping falling back to false

## v0.1.17

### Added

- More url scheme actions like pause and open
- Activity reporting toggle
- Show App version in RPC

### Fixed

- Discord RPC now hides when paused

## v0.1.13

### Fixed

- Animated Artwork not working sometimes
- Show player even if there is no song playing

## v0.1.12

### Added

- Directional artwork flip animation

## v0.1.11

### Announcement

🎉 Öpfelmusig Lib release [on npm](https://www.npmjs.com/package/@opfelmusig/lib) 🎉

A Fully Typed Apple Music API Client and the foundation of the Öpfelmusig App. Currently no docs and also closed source.

### Fixed

- Seeking not working due to a bug in NuxtUI v4.11.0

## v0.1.10

### Added

- Equalizer
- Updater
- Release workflow

### Fixed

- Show the settings button even if the profile request has an error

## 27.08.2026

🎉 Öpfelmusig public release 🎉
