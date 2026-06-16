# OhMyShot — Screenshot Beautifier for Windows, macOS & Linux

[![Latest Release](https://img.shields.io/github/v/release/redf0x1/ohmyshot-releases?label=Latest%20Release)](https://github.com/redf0x1/ohmyshot-releases/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/redf0x1/ohmyshot-releases/total?label=Downloads)](https://github.com/redf0x1/ohmyshot-releases/releases)
[![Platforms](https://img.shields.io/badge/platforms-Windows%20%7C%20macOS%20%7C%20Linux-blue)](https://ohmyshot.app)
[![Languages](https://img.shields.io/badge/languages-19-green)](https://ohmyshot.app)

Beautiful screenshot beautifier for macOS, Windows, and Linux.

<p align="center">
  <img src="https://ohmyshot.app/assets/images/screenshots/optimized/ohmyshot-banner.png" alt="OhMyShot - Screenshot Beautifier" width="100%">
</p>

### What's New in v1.25.2

- **Windows window capture fix** — Window Capture no longer stays stuck on "Loading windows..." with no way out.
- **Safe exit** — If Windows takes too long to return the open-window list, Cancel, Escape, and Close still work.
- **Faster recovery** — You can retry Window Capture or switch to another capture mode without killing the app.
- **Hotkeys restored** — Screenshot shortcuts work again after updating from v1.24.0 to v1.25.x.

### v1.25.1 Highlights

- **Combine screenshots** — Add multiple screenshots and make one combined image inside OhMyShot.
- **No more Paint workaround** — Arrange screenshots as Auto, Row, or Column directly from the Export panel.
- **Copy fix** — Copying a beautified screenshot with a background no longer stays loading forever.
- **Better reliability** — Combined images work more reliably with screenshots pasted from different apps.

### v1.25.0 Highlights

- **Annotation defaults** — Save your preferred text, shape, and arrow styles for the next annotation.
- **Line styles** — Use solid, dashed, and dotted lines for arrows, lines, rectangles, and ellipses.
- **Curved arrows** — Add adjustable curved arrows for clearer callouts.
- **Watermarks** — Add resizable text or image watermarks to screenshots.

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
- 🧩 Combine multiple screenshots into one image
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

### Latest Release: v1.25.2

| Platform | Download |
|----------|----------|
| macOS (Apple Silicon) | [GitHub](https://github.com/redf0x1/ohmyshot-releases/releases/download/v1.25.2/OhMyShot_1.25.2_aarch64.dmg) · [CDN](https://dl.ohmyshot.app/v1.25.2/OhMyShot_1.25.2_aarch64.dmg) |
| macOS (Intel) | [GitHub](https://github.com/redf0x1/ohmyshot-releases/releases/download/v1.25.2/OhMyShot_1.25.2_x64.dmg) · [CDN](https://dl.ohmyshot.app/v1.25.2/OhMyShot_1.25.2_x64.dmg) |
| Windows (Installer) | [GitHub](https://github.com/redf0x1/ohmyshot-releases/releases/download/v1.25.2/OhMyShot_1.25.2_x64-setup.exe) · [CDN](https://dl.ohmyshot.app/v1.25.2/OhMyShot_1.25.2_x64-setup.exe) |
| Windows (MSI) | [GitHub](https://github.com/redf0x1/ohmyshot-releases/releases/download/v1.25.2/OhMyShot_1.25.2_x64_en-US.msi) · [CDN](https://dl.ohmyshot.app/v1.25.2/OhMyShot_1.25.2_x64_en-US.msi) |
| Linux (AppImage) | [GitHub](https://github.com/redf0x1/ohmyshot-releases/releases/download/v1.25.2/OhMyShot_1.25.2_amd64.AppImage) · [CDN](https://dl.ohmyshot.app/v1.25.2/OhMyShot_1.25.2_amd64.AppImage) |
| Linux (Debian/Ubuntu) | [GitHub](https://github.com/redf0x1/ohmyshot-releases/releases/download/v1.25.2/OhMyShot_1.25.2_amd64.deb) · [CDN](https://dl.ohmyshot.app/v1.25.2/OhMyShot_1.25.2_amd64.deb) |
| Linux (Fedora/RHEL) | [GitHub](https://github.com/redf0x1/ohmyshot-releases/releases/download/v1.25.2/OhMyShot-1.25.2-1.x86_64.rpm) · [CDN](https://dl.ohmyshot.app/v1.25.2/OhMyShot-1.25.2-1.x86_64.rpm) |

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
sudo dpkg -i OhMyShot_1.25.2_amd64.deb

# Fedora/RHEL
sudo rpm -i OhMyShot-1.25.2-1.x86_64.rpm


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
