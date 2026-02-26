# Changelog / Nhật ký thay đổi

All notable changes to OhMyShot will be documented in this file.

## [1.14.0] - 2026-02-25

### Added
- **Capture Timer**: Set a delay before screenshots (3, 5, or 10 seconds) — gives you time to arrange windows or menus
- Animated countdown overlay shows remaining seconds before capture
- Press Esc or the same shortcut key to cancel the countdown at any time
- Press a different capture shortcut during countdown to switch capture mode
- Timer works with all capture types: Full Screen, Region, Window, Scrolling, Recording, and Text Recognition
- Timer can be triggered from both keyboard shortcuts and the tray menu

### Fixed
- Settings dropdowns now display correctly above other content
- Settings dropdown options are easier to read with improved contrast
- Countdown overlay now appears with a transparent background instead of a white box

### Changed
- All dropdowns in Settings (Language, PrintScreen Action, Capture Delay) have improved layering behavior

## [1.13.0] - 2026-02-25

### Fixed
- **Vietnamese Input**: Resolved keyboard conflict with Vietnamese input methods (EVKey, UniKey) that caused typing issues
- **Screenshot Quality**: Improved screenshot capture quality for sharper, pixel-perfect results
- **Text Editing**: Better support for Vietnamese, Chinese, Japanese, and Korean text input in annotations
- **Edit Panel**: Fixed panel position jumping when editing annotations

### Added
- **Text Background**: Add background color and opacity settings for text annotations
- **Reset Defaults**: New option in Settings to restore all tool settings to defaults

### Changed
- Callout annotation tool temporarily hidden (under development)

## [1.12.1] - 2026-02-23

### 🐛 Fixed
- Fixed small white gap at screen edges during region capture on Windows (#48)
- Fixed "Show in Folder" not working on Windows — Explorer now opens correctly (#44)
- Fixed Settings dropdowns unreadable in dark mode on Windows (#49)

### ✨ Improved
- Updated default border settings for better out-of-box experience — white border, width 11, opacity 21 (#50)

## [1.12.0] - 2026-02-23

### ✨ New: Focus Blur Tool
- New annotation tool that blurs the background to highlight important content
- Draw focus areas to direct attention — everything outside gets blurred
- Press `D` to activate

### Added
- **PrintScreen Key Capture** (Windows/Linux) — capture with a single key press, configurable in Settings
- **Transparent Background Toggle** — quickly switch between transparent and your previous background with one click

### Improved
- Image automatically re-centers when Edit/Export panels open or close
- More accurate region capture on multi-monitor setups with different display scales
- Smoother Focus Blur preview while drawing and dragging

### Fixed
- Fixed black screen when loading images — a loading indicator now appears
- Fixed Focus Blur effect not appearing during the first drawing
- Fixed region selection not responding to clicks on Windows multi-monitor setups
- Fixed multiple app instances being able to run at the same time — launching again now focuses the existing window

## [1.11.1] - 2026-02-20

### Fixed
- Fixed region capture not showing screenshot on Windows (double data URL prefix in cropBase64Image) (#38)
- Fixed number input spinners showing ugly native browser controls
- Fixed bottom bar content overflowing into "Select an annotation to edit" status text
- Fixed floating edit/export panels overlapping bottom settings bar

### Improved
- Added compact mode for SliderInput in bottom toolbar (horizontal single-row layout)
- Added CSS overflow protections across toolbar components

## [1.11.0] - 2026-02-17

### ☁️ New: Cloud Upload (ImgBB)
- Cloud upload via ImgBB — one-click share screenshots as URLs
- Upload history panel with copy/delete/open actions
- Sharing settings — enable/disable upload, auto-copy link, custom API key
- Upload progress toast — real-time upload status feedback
- Auto-upload after beautify — automatically upload after Capture & Beautify
- System tray "Upload Last Screenshot" — quick upload from tray menu
- Auto-upload toggle in Sharing settings

### ✨ UX Improvements
- Floating panel position clamping — panels stay within viewport
- Upload history sidebar panel with search and auto-cleanup
- SliderInput component with direct numeric input
- Watermark auto-size toggle for dynamic font sizing
- Fixed social media preset dimensions incorrect

### 🐛 Bug Fixes
- Text not selectable when editing annotations (select-none removed from annotation layer)
- Windows DWM rendering issue — added 100ms delay for Windows DWM flush
- App icon missing on Windows — fixed installer/app icon configuration
- Collapsible panels accessibility — added keyboard support and ARIA attributes
- Number annotation counter not resetting between sessions

## [1.10.0] - 2026-02-13

### 🌐 New: Multi-Language Support
- Full English and Vietnamese language support
- Easy language switching in Settings
- System tray menu translates automatically
- Auto-detects your system language on first launch

### 📸 New: Floating Capture Preview
- After a quick capture, a mini preview window appears in the corner
- One-click actions: Edit, OCR, Save, or Copy — right from the preview
- Auto-dismisses after 5 seconds; hover to keep it visible
- Non-intrusive — never steals focus from your work

### 🎨 New: Smart Tool Settings
- Each drawing tool now remembers its own settings
- Switch between tools without losing your preferred size, color, and style
- Settings persist across sessions — your workflow, your way

### 📋 New: Auto-Copy Per Capture Mode
- Independent auto-copy toggles for Screen, Region, and Window captures
- Choose which capture modes automatically copy to clipboard
- Configure each mode separately in Settings

### 🔄 New: Cross-Platform Auto-Updates
- Seamless automatic updates now available on all platforms
- Background update checks with zero interruption
- "Check for Updates" available in the system tray menu
- Always stay on the latest version

### ⚡ Improved: Capture & Beautify
- Now supports region selection — beautify any part of your screen, not just fullscreen
- Window auto-hides after copying the beautified screenshot
- Smoother cross-platform notifications

### ✏️ Improved: Text Tool
- Text now scales correctly at all zoom levels — no more garbled or tiny text
- Font and color changes apply instantly while editing
- Font size slider always shows the correct value
- Smoother text input — no jumping or flickering while typing
- Cursor is always visible, even on light backgrounds
- Better default text appearance (larger, with outline)
- Removed placeholder text for a cleaner editing experience

### 🖥️ Improved: Windows Experience
- Fixed multi-screen capture on high-DPI displays
- Region selection overlay scales correctly on HiDPI screens
- Light tray icon for better visibility on dark taskbars

### 📦 Improved: Smaller & Faster (macOS)
- macOS download size reduced by 80% — from 24MB to under 5MB
- App uses native text recognition on macOS for faster, smaller builds

### 🐛 Bug Fixes — Community Reports

We fixed **20+ bugs** reported by the community. Thank you for your feedback!

**Capture & Display:**
- Fixed overlay mask persisting on screen after capture (#7)
- Fixed crop tool only working in the top-left quarter (#8)
- Fixed region capture flash on Windows (#10)
- Fixed "Show in Folder" being hidden behind the app window (#13)
- Fixed app not hiding properly on macOS after capture (#14)
- Fixed captures from the system tray not showing the editor
- Fixed background presets sometimes resetting after restart

**Annotations:**
- Fixed crash when double-clicking text to edit (#17)
- Fixed text display issues at non-100% zoom (#18)
- Fixed toolbar showing wrong message for selected annotations (#19)
- Fixed color picker not matching the selected annotation's color (#20)
- Fixed number annotations appearing tiny at low zoom (#21)
- Fixed blur tool border showing in exported images (#23)
- Fixed number annotations not being resizable (#11)
- Fixed multiple spotlights progressively darkening the image (#15)

**Shortcuts & Settings:**
- Fixed Ctrl/Cmd mapping on macOS shortcuts (#9)
- Fixed E key conflict — E now correctly selects Ellipse tool (#3)
- Fixed annotation settings not saving between sessions (#24)
- Fixed "Always on Top" covering other apps by default (#12)

### 🔧 Under the Hood
- Error reporting now works in production builds for faster issue resolution
- Improved build pipeline for Windows and Linux releases

## [1.9.0] - 2026-02-10

### ⚡ New: Capture & Beautify

One-click screenshot magic! Press **⌘⌥6** (Mac) or **Ctrl+Alt+6** (Windows/Linux) to capture your screen, auto-apply your favorite background style, and copy the result to clipboard — all in one step.

### 🚀 New: Launch at Startup

OhMyShot can now start automatically when you log in. Enable it in **Settings → Behavior**.

### 🎯 Improved: Shortcut Hints

New keyboard shortcut hints appear when the editor is empty.

### 🐛 Fixed

- **OCR text extraction** now works reliably on Windows and Linux
- **Multi-screen capture** on macOS correctly captures the active monitor
- **Empty OCR results** show a friendly message instead of an error
- **Linux compatibility** improved — runs on a wider range of distributions

### 📦 Smaller & Faster

Significantly reduced app download size.

## [1.8.0] - 2026-01-26

### ✨ Major UI Redesign

This release brings a completely reimagined editing experience. We've rebuilt the interface from the ground up to give you more space, more focus, and a more delightful workflow.

### Added
- **Floating Panel System** 🎨: Say goodbye to the cramped sidebar!
  - Panels now float elegantly over your canvas
  - Your screenshot gets the full stage it deserves
  - Panels appear when you need them, vanish when you don't
- **Minimal Mode** (Press `M`) 🧘: Ultimate distraction-free editing
  - Hide everything – just you and your canvas
  - Perfect for detailed annotation work
  - Press `M` again to bring UI back instantly
- **Smart Edit Panel** (Press `E`) ⚙️: All background & crop controls in one place
  - Quick access to gradients, colors, and wallpapers
  - Padding, corner radius, and aspect ratio settings
  - Auto-hides after 5 seconds of inactivity
- **Quick Export Panel** (Press `X`) 📤: Streamlined export workflow
  - One-click access to all export options
  - Copy, save, or share in seconds
  - Stays out of your way until you need it
- **Collapsible Toolbar** 📐: Double-click or press `[` to minimize
  - Reclaim even more canvas space when needed
  - Compact mode keeps essential tools accessible
- **Beautiful Empty State** 🎯: Helpful guidance for new users
  - Clear instructions for getting started
  - Drag & drop, paste, or capture – your choice
  - Quick action buttons to jump right in

### Improved
- **Smarter Panel Behavior**: Panels auto-hide when you start drawing
  - No more accidentally clicking UI while annotating
  - Seamlessly returns when you're done
- **Silky Smooth Animations**: Premium transitions throughout
  - Every panel, every hover, every interaction feels polished
  - Respects "Reduce Motion" accessibility preference
- **Cleaner Visual Hierarchy**: Less clutter, more clarity
  - Tools disabled until you have an image (no confusion)
  - Visual feedback on every interaction

### Changed
- Sidebar replaced with floating panel architecture
- Export and edit controls moved to dedicated smart panels
- Toolbar now collapsible for maximum workspace flexibility

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

## [1.3.0] - 2026-01-23

### Added
- **Enhanced Gradient System**: Redesigned gradient picker with tabs, categories, and search functionality
- **Enhanced Wallpaper System**: New wallpaper picker with favorites, recents, and search capabilities

### Changed
- Updated domain and social links across the application
- Updated GitHub repository references

### Fixed
- Addressed customer feedback for OCR text extraction
- Fixed various settings-related issues based on user reports

## [1.2.0] - 2026-01-22

### Added
- **OCR Text Extraction**: Extract text from screenshots using Tesseract.js (Live Text style)
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
- Improved performance with lazy-loaded OCR worker

## [1.1.0] - 2026-01-21

### Added
- **Blur/Pixelate Tool**: Hide sensitive info with blur or pixelate effects
- **Enhanced Arrow Tool**: Double-headed arrows, 3 head styles (triangle, rounded, diamond)
- **Copy & Close**: CMD+C now closes window after copy (configurable in Settings)
- **Click-to-Record Shortcuts**: New keyboard shortcut capture UI in Settings
- **Dark Theme Menu Bar**: Native dark theme support for macOS title bar

### Fixed
- Toolbar overflow: Settings button no longer clips outside viewport
- Screen Recording Permission: Fixed Info.plist key typo (NSScreenCaptureUsageDescription)
- Shortcut Recording: New click-to-record interface replaces text input
- macOS Titlebar: Proper 32px safe area for traffic lights

### Changed
- Arrow tool now directly accessible in toolbar (not hidden in dropdown)
- Toolbar scrollable when space is insufficient

## [1.0.1] - 2026-01-21

### Fixed / Sửa lỗi
- Fixed Settings modal UI overflow on smaller screens
- Improved slider components layout in Settings panel

## [1.0.0] - 2026-01-19

### Added / Thêm mới
- Screenshot capture (fullscreen, region selection, window capture)
- Annotation tools (shapes, arrows, text, brush, spotlight)
- Beautification (gradients, wallpapers, solid colors, custom images)
- Image styling (blur, shadow, border radius, padding, border)
- Crop with 8 aspect ratio presets
- Export PNG/JPEG with 1x/2x/3x resolution
- Cross-platform support (Windows, macOS, Linux)
- System tray integration
- Global hotkeys
- Auto-update
