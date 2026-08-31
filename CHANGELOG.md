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
