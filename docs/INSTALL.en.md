# Install ContextCruise

1. On an Apple Silicon Mac running macOS 14 or later, [download the current DMG](https://github.com/jack1231222/contextcruise/releases/download/v11.21.45-beta.1/ContextCruise-11.21.45-beta.1-macOS-arm64.dmg) from the official release.
2. Open the DMG, quit an existing copy of ContextCruise, and drag ContextCruise into Applications. Launch it from Applications.
3. On first use, select your local Codex data folder (normally `~/.codex`). ContextCruise reads its session records. Existing installations reuse their saved folder if it is still readable.
4. Click the menu bar icon for the compact overview or open the full window. Additional sources, traffic collection, network queries, and remote reporting have separate settings.

The current statistics edition uses Simplified Chinese. Embedded Python and Zstandard are included. Keep a copy of your previous application and a backup of its data before a major-version update. Beta updates are opt-in.

## Uninstall or Revert

Quit the app and move it to Trash. Data in `~/Library/Application Support/ContextCruise` and dedicated Keychain credentials remain unless you explicitly remove them. Back up and confirm before deleting data or credentials.

Keep the installed version and a data backup before upgrading. Before reverting, separately preserve data created by the newer version. Never overwrite later records with an old backup. Cross-version rollback compatibility is not guaranteed without testing.
