# Release Notes

## 1.0.0-beta.2 · Build 10020

- Selectable English and Simplified Chinese throughout onboarding, menus, settings, monitoring, advice, accessibility labels, import, and update notices. The saved selection applies after reopening the app.
- English public documentation, issue forms, installer naming, and release notes.
- New AI advice is requested in the selected app language. Original conversation titles and source excerpts keep their original language.
- Saved settings, statistics, credentials, and original source records keep their existing storage formats. Previously saved advice remains visible in its original language; changing the app language does not translate it or issue a paid request.
- Fixes macOS 13 first-use timezone detection and safely handles background workers that exit during communication.
- The app and DMG use Developer ID signing, Apple notarization, and the existing Sparkle update channel.

## 1.0.0-beta.1 · Build 10015

- Free Codex conversation monitoring with an embedded ARM64 Python runtime and no paid conversation limit.
- Separate settings, statistics, and credentials; optional AI off by default.
- Explicit allowlisted legacy import that refuses to overwrite existing data.
- Stable and opt-in beta Sparkle channels. No stable release yet.
- Pre-update disk-space checks and a notice when an attempted update has not completed after relaunch.
- Installation, redacted real-record snapshots, search, quit/reopen, and the public 10014-to-10015 Sparkle update passed on a clean macOS 13.4.1 virtual machine.

Earlier build milestones included a macOS 13-compatible Zstandard binary and recovery from missing embedded-tool paths and older failed timing caches. These historical results do not replace validation of a newer final package.
