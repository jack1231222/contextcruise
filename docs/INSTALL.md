# Install and Use

ContextCruise requires an Apple Silicon Mac running macOS 13 or later. See the [tested scope and known limitations](KNOWN_ISSUES.md) before installing. The current bilingual beta is build 10020.

1. Download the Apple Silicon DMG from the official [Releases](https://github.com/jack1231222/contextcruise/releases). Check that release’s tested system versions.
2. Open the DMG and drag ContextCruise into Applications. Quit an older running version before launching the new one.
3. Choose your local Codex data folder, usually `~/.codex`. Hidden folders can be shown in the system picker. Readable sessions and a compatible local catalog, account identity, and status protocol are required.
4. Wait for the initial scan. Unknown or Syncing does not mean a conversation ended. The follow-up list is not every historical conversation.
5. Search, favorite, and inspect records. Pause Monitoring stops local refreshes. Closing a window can leave monitoring active; quit the app to stop its background processes.

## Optional AI

Local statistics do not make AI requests. AI is off by default. Configure a provider, credentials, model, prices, and budget before explicitly enabling automatic analysis. Your selected provider may charge API fees. Use only a service you trust with the necessary redacted conversation material. Disabling analysis keeps previous advice.

Choose English or Simplified Chinese in General & Monitoring settings or the application menu, then quit and reopen the app. New advice uses the selected language. Your conversation titles, source excerpts, and custom names are preserved in their original language. Previously saved advice stays in its original language. Changing the app language does not translate it or issue a paid request. Recheck Material can request new advice under your configured API and budget.

## Updates

Choose Check for Updates in the application menu. Automatic checks are optional and automatic installation is off. Receive Beta Updates is off by default; enable it to use the separate beta feed. There is no stable release yet. Switching channels does not force a downgrade.

Canceling an update keeps the installed version. Disk-space checks provide a minimum reserve based on the current app and known update size at the time of the check; they do not guarantee future free space or every expanded package size. If an update does not finish, check disk space and retry. Never bypass signature or Gatekeeper failures.

## Import Legacy Data

Before connecting Codex for the first time, choose Import Legacy Non-sensitive Data from the application menu. Select the old local data folder. Import copies only allowlisted settings and structurally verifiable timing statistics into an empty destination. It does not copy API credentials, configurations, or request ledgers. AI stays off, and legacy originals are not modified.

Quit and reopen after import, then connect Codex. A nonempty destination is refused. Merging two existing datasets is not supported.

## Uninstall or Revert

Quit the app and move it to Trash. Data in `~/Library/Application Support/ContextCruise` and dedicated Keychain credentials remain unless you explicitly remove them. Back up and confirm before deleting data or credentials.

Keep the installed version and a data backup before upgrading. Before reverting, separately preserve data created by the newer version. Never overwrite later records with an old backup. Cross-version rollback compatibility is not guaranteed without testing.
