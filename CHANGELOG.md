# Changelog

All notable changes to OhMyShot will be documented in this file.

## [1.1.0] - 2026-01-22

### Added
- **Blur/Pixelate Tool**: Hide sensitive information with blur or pixelate effects
- **Enhanced Arrow Tool**: Double-headed arrows with 3 head styles (triangle, rounded, diamond)
- **Copy & Close**: ⌘+C now closes window after copy (configurable in Settings)
- **Click-to-Record Shortcuts**: New intuitive keyboard shortcut capture UI in Settings
- **Dark Theme Menu Bar**: Native dark theme support for macOS title bar

### Fixed
- Toolbar overflow: Settings button no longer clips outside viewport
- Screen Recording Permission: Fixed Info.plist key typo (NSScreenCaptureUsageDescription)
- macOS Titlebar: Proper 32px safe area for traffic lights

### Changed
- Arrow tool now directly accessible in toolbar (moved from dropdown)
- Toolbar now scrollable when space is insufficient

---

## [1.0.0] - 2025-01-20

### Added
- Initial release
- Screenshot capture (full screen, window, region)
- Background customization (gradients, wallpapers, solid colors)
- Frame effects (shadows, borders, rounded corners)
- Multiple export formats (PNG, JPEG, WebP)
- Aspect ratio presets
- Keyboard shortcuts
- Auto-update functionality

### Platforms
- macOS (Apple Silicon & Intel)
- Windows (x64)
- Linux (Debian, RPM, AppImage)
