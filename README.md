# OhMyShot — Screenshot Beautifier for Windows, macOS & Linux

[![Latest Release](https://img.shields.io/github/v/release/redf0x1/ohmyshot-releases?label=Latest%20Release)](https://github.com/redf0x1/ohmyshot-releases/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/redf0x1/ohmyshot-releases/total?label=Downloads)](https://github.com/redf0x1/ohmyshot-releases/releases)
[![Platforms](https://img.shields.io/badge/platforms-Windows%20%7C%20macOS%20%7C%20Linux-blue)](https://ohmyshot.app)
[![Languages](https://img.shields.io/badge/languages-19-green)](https://ohmyshot.app)

Beautiful screenshot beautifier for macOS, Windows, and Linux.

<p align="center">
  <img src="https://ohmyshot.app/assets/images/screenshots/optimized/ohmyshot-banner.png" alt="OhMyShot - Screenshot Beautifier" width="100%">
</p>

### 🆕 What's New in v1.24.0

- 🎯 **More Flexible Capture** — Choose how full-screen capture behaves and whether region capture happens instantly or lets you adjust first
- 🐧 **Better Linux Window Capture** — Picking a window and returning to the app now works more reliably on Linux desktops
- ✨ **Subtle Product Credit** — A small auto-bot.io credit now appears in the app

### 📸 v1.19.0 Highlights

- 📜 **Scrolling Screenshot** — Capture entire scrollable pages with automatic stitching
- 🌍 **Floating Translation** — Translated text appears in a convenient floating popup
- 🗣️ **Language Selector** — Choose your preferred UI language from 19 options
- 🌐 **Complete Localization** — All UI elements fully translated across supported languages

## Features

- 📸 Screenshot capture (full screen, region, window)
- 📜 Scrolling screenshot (auto-stitching)
- 🌐 Screen translation
- 🎥 GIF screen recording
- 🎨 Beautiful backgrounds, gradients, borders, shadows
- ✏️ 10+ annotation tools (arrow, text, rectangle, circle, line, freehand, blur, highlighter, numbering, callout)
- 🗂️ Annotation layers panel
- 📌 Pin screenshots (always-on-top)
- 📚 Template library
- 🖼️ Export to PNG, JPEG, modern compressed image format, GIF
- 📝 Custom filename templates
- 💧 Watermark (text + image/logo)
- 📋 Annotation copy/paste
- 🌍 19 languages supported
- 🔄 Auto-update

## Feature Showcase

<p align="center">
  <img src="https://ohmyshot.app/assets/images/showcase/gallery-01-gradients-full.%77ebp" alt="Gradient Backgrounds" width="600">
  <br>
  <em>Professional gradient backgrounds</em>
</p>

<p align="center">
  <img src="https://ohmyshot.app/assets/images/showcase/gallery-02-wallpapers-full.%77ebp" alt="Wallpaper Backgrounds" width="600">
  <br>
  <em>Custom wallpaper backgrounds</em>
</p>

## Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| ⌘⌥3 | Screenshot region capture |
| ⌘⌥4 | OCR Direct Capture (select & extract text) |
| ⌘⌥5 | Quick Capture Mode |
| E | Toggle Edit Panel |
| X | Toggle Export Panel |
| M | Toggle Minimal Mode |
| [ | Collapse/Expand Toolbar |
| ? | Show all shortcuts |

## Download

### Latest Release: v1.24.0

| Platform | Download |
|----------|----------|
| macOS (Apple Silicon) | [GitHub](https://github.com/redf0x1/ohmyshot-releases/releases/download/v1.24.0/OhMyShot_1.24.0_aarch64.dmg) · [CDN](https://dl.ohmyshot.app/v1.24.0/OhMyShot_1.24.0_aarch64.dmg) |
| macOS (Intel) | [GitHub](https://github.com/redf0x1/ohmyshot-releases/releases/download/v1.24.0/OhMyShot_1.24.0_x64.dmg) · [CDN](https://dl.ohmyshot.app/v1.24.0/OhMyShot_1.24.0_x64.dmg) |
| Windows (Installer) | [GitHub](https://github.com/redf0x1/ohmyshot-releases/releases/download/v1.24.0/OhMyShot_1.24.0_x64-setup.exe) · [CDN](https://dl.ohmyshot.app/v1.24.0/OhMyShot_1.24.0_x64-setup.exe) |
| Windows (MSI) | [GitHub](https://github.com/redf0x1/ohmyshot-releases/releases/download/v1.24.0/OhMyShot_1.24.0_x64_en-US.msi) · [CDN](https://dl.ohmyshot.app/v1.24.0/OhMyShot_1.24.0_x64_en-US.msi) |
| Linux (AppImage) | [GitHub](https://github.com/redf0x1/ohmyshot-releases/releases/download/v1.24.0/OhMyShot_1.24.0_amd64.AppImage) · [CDN](https://dl.ohmyshot.app/v1.24.0/OhMyShot_1.24.0_amd64.AppImage) |
| Linux (Debian/Ubuntu) | [GitHub](https://github.com/redf0x1/ohmyshot-releases/releases/download/v1.24.0/OhMyShot_1.24.0_amd64.deb) · [CDN](https://dl.ohmyshot.app/v1.24.0/OhMyShot_1.24.0_amd64.deb) |
| Linux (Fedora/RHEL) | [GitHub](https://github.com/redf0x1/ohmyshot-releases/releases/download/v1.24.0/OhMyShot-1.24.0-1.x86_64.rpm) · [CDN](https://dl.ohmyshot.app/v1.24.0/OhMyShot-1.24.0-1.x86_64.rpm) |

> ⚠️ **Windows Note**: You may see a SmartScreen warning. Click "More info" → "Run anyway" to proceed.

[View all releases →](https://github.com/redf0x1/ohmyshot-releases/releases)

### Installation

#### macOS
1. Download the `.dmg` file
2. Open and drag OhMyShot to Applications
3. If macOS shows "The application can't be opened":
  1. **Terminal (Recommended)**: Open Terminal and run:
    ```bash
    xattr -cr /Applications/OhMyShot.app
    ```
  2. **Right-click**: Right-click the app → Open → Open
  3. **System Settings**: Go to System Settings → Privacy & Security → click "Open Anyway"

#### Windows
1. Download the `.exe` installer
2. Run the installer
3. Follow the installation wizard

#### Linux
```bash
# Debian/Ubuntu
sudo dpkg -i OhMyShot_1.24.0_amd64.deb

# Fedora/RHEL
sudo rpm -i OhMyShot-1.24.0-1.x86_64.rpm


```

## Privacy

OhMyShot is privacy-first:
- No analytics or tracking
- No telemetry
- No account required
- Works offline by default (Cloud Upload is optional)

If you enable Cloud Upload, your screenshot is uploaded to ImgBB to generate a shareable link.

See our [Privacy Policy](https://ohmyshot.app/privacy.html) for details.

## Support

- 🐛 [Report a Bug](https://github.com/redf0x1/ohmyshot-releases/issues/new?template=bug_report.yml)
- 💡 [Request a Feature](https://github.com/redf0x1/ohmyshot-releases/issues/new?template=feature_request.yml)
- 💬 [Telegram](https://t.me/redf0x1)

## Changelog

See [CHANGELOG.md](./CHANGELOG.md) for version history.

## License

© 2026 RedFox Team. All rights reserved.

---

**Website**: [ohmyshot.app](https://ohmyshot.app)
