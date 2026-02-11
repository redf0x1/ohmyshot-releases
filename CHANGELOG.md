# Changelog

All notable changes to OhMyShot will be documented in this file.

## [1.8.0] - 2026-01-26

### 🎨 Major UI Redesign

This release brings a completely reimagined interface designed for maximum focus and efficiency.

### Added
- **Floating Editing Panels** ✨: Say goodbye to the fixed sidebar!
  - Edit panel appears on-demand (press `E`) for background and crop settings
  - Export panel pops up when you need it (press `X`)
  - Panels auto-hide after 5 seconds to keep your canvas clean
  - Smart hiding when you're drawing annotations

- **Minimal Mode** 🎯: Ultimate distraction-free editing
  - Press `M` to hide everything except your canvas
  - Perfect for presenting or focusing on your screenshot
  - ESC to return to normal view

- **Collapsible Toolbar** 📐: More canvas, less clutter
  - Double-click or press `[` to collapse the tools
  - Expands back with a single click
  - Your workspace, your way

- **Beautiful Empty State** 🖼️: A welcoming start
  - Clear guidance for drag-drop, paste, or capture
  - Quick action buttons for Screen, Window, Region capture
  - Smart keyboard shortcut hints

### Improved
- **Premium Animations**: Smooth, polished transitions throughout
- **Smarter Panels**: Automatically minimize when you start drawing
- **Canvas-First Design**: More screen space for what matters most
- **Visual Hierarchy**: Clear distinction between editing modes
- **Accessibility**: Supports reduced motion preferences

### Changed
- Sidebar replaced with modern floating panels
- Export and Edit controls are now separate, dedicated panels
- Left toolbar can now be collapsed for more workspace

### Known Issues
- **E Key Conflict**: The E key currently opens the Edit Panel instead of activating the Ellipse drawing tool. This conflicts with the original tool shortcut behavior from v1.2.0. A fix is planned for the next release to reassign the Edit Panel to a different shortcut and restore E key to Ellipse tool activation.

---

## [1.7.0] - 2026-01-24

### Added
- **OCR Direct Capture** ⚡: New `⌘⌥4` shortcut for instant text extraction
  - Select any region on screen → Text copied to clipboard immediately
  - Perfect for grabbing text from images, PDFs, or non-selectable content
  - No editor needed – just capture and paste!
- **Quick Capture Mode** 📸: Lightning-fast screenshot workflow with `⌘⌥5`
  - Instant region capture straight to clipboard
  - Skip the editor when you just need a quick screenshot
  - Inspired by power-user workflows for maximum speed
- **Native Notifications**: Beautiful macOS notifications for all capture events
  - Click any notification to open OhMyShot instantly
  - Know exactly when your capture is ready

### Improved
- **Enhanced System Tray Menu**: Redesigned with icons and keyboard shortcut hints
  - Quick access to all capture modes at a glance
  - Visual shortcuts help you learn the app faster

---

## [1.6.0] - 2026-01-24

### Added
- **Lightning-Fast Text Recognition**: Completely reimagined OCR experience with dramatically improved speed and accuracy
  - Text extraction now feels instant, even with complex documents
  - Better recognition of diverse fonts and text styles
  - Seamless copy-to-clipboard workflow
- **Professional Toolbar Redesign**: New streamlined interface for power users
  - Left vertical toolbar with logically grouped annotation tools
  - New Highlighter tool for marking important content (press `H`)
  - Context-sensitive settings bar that adapts to your current tool
  - Cleaner, distraction-free workspace

### Changed
- Simplified top toolbar for a more focused editing experience
- New custom-designed icons for improved visual clarity
- Enhanced tool shortcuts for faster workflow

### Fixed
- Crop tool now handles edge cases more reliably
- Window capture works consistently across different app types
- Various UI polish and refinements

---

## [1.3.0] - 2026-01-23

### Added
- **Enhanced Gradient System**: New tabbed interface with categories and search functionality
- **Enhanced Wallpaper System**: Favorites, recents, and search for quick wallpaper access

### Changed
- Updated domain and social links across the application

### Fixed
- OCR text extraction improvements based on customer feedback
- Various settings-related issues resolved

---

## [1.2.0] - 2026-01-22

### Added
- **OCR Text Extraction**: Extract text from screenshots with lightning-fast OCR
  - Press `Shift+T` to enter text selection mode
  - Word-level selection with blue highlight overlay
- **QR Code Detection**: Scan and decode QR codes from screenshots automatically
- **Keyboard Shortcuts Modal**: Press `?` to view all available shortcuts
- **Always on Top**: Keep window floating above others (Settings → General)
- **Background Corner Radius**: Adjust corner radius outside the screenshot (0-100)
- **Capture Sound Feedback**: Audio feedback when taking screenshots
- **Smooth Capture UX**: Coordinated transitions and visual feedback during screen capture

### Fixed
- Tool shortcuts (1-9, P, H, E, etc.) now properly switch between tools
- Fixed annotation color not applying correctly in some cases

### Changed
- Enhanced keyboard shortcuts with Space-to-Select (hold Space to temporarily switch to Select tool)
- Improved OCR performance

---

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
