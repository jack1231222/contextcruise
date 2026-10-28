# Tested Scope and Known Limitations

- The current bilingual beta is `v1.0.0-beta.2`, build 10020, for Apple Silicon and macOS 13 or later.
- The final app and DMG have Developer ID signatures, Apple notarization, stapled tickets, and signed Sparkle update metadata.
- Build 10020 installation, both interface languages, saved language selection, local record reading, search, settings, and quit/reopen were checked on macOS 13.4.1. Test conversations include synthetic records and previously authorized redacted snapshots. The virtual machine has no Apple ID login and does not run a live Codex workload.
- Earlier real-Codex integration evidence came from macOS 27.0.1. The full macOS/Codex version matrix is not covered. Local protocol changes in Codex may require adapter updates.
- Disk-space preflight and incomplete-update notices were introduced in build 10015. Their isolated low-space, failure-preservation, retry, and read-only-location tests remain scoped baseline evidence. A minimum reserve is not a guarantee of future free space or every expanded update size.
- Prior external APFS upgrades, canceled downloads, unavailable-feed recovery, and unchanged runtime evidence remain historical results for those tested conditions. They do not cover every filesystem or installation location.
- Upgrades preserve the existing data formats. Conversation titles, source text, provider names, and custom theme names are user or source content and may use any language. Previously saved AI advice is shown in its original language. Changing the app language does not translate it or issue a paid request.
- Legacy import accepts only an empty first-use destination. It does not merge datasets or migrate API credentials. A validated one-click redacted diagnostic export is not available.
- Beta updates require explicit opt-in. The stable feed intentionally contains no release.
