# Privacy Notice

## Local records

ContextCruise reads the local Codex logs, catalog, and status information you select. It stores settings, indexes, and derived statistics in its own application directory. The adapter reads account identity locally to match the current user; identity credentials are not sent to update services or public feedback channels. Monitoring does not modify Codex conversations, configuration, or read state, and does not resume a conversation.

ContextCruise has no separate user account, telemetry service, or marketing backend. Initial indexing reads the local records it needs. Do not submit these raw records publicly.

## Optional AI analysis

AI is off by default. If you configure and enable it, material needed for analysis is sent to the API provider you select. This may include conversation content. Check the endpoint, provider privacy terms, and budget before enabling analysis. Necessary material is redacted locally; material that cannot be reliably redacted is not sent.

API credentials are stored in a dedicated local macOS Keychain service. Legacy import does not copy credentials, API configurations, or request ledgers. The provider is responsible for its own retention, processing, and billing policies.

New analysis is requested in the selected app language, English or Simplified Chinese. Existing advice and source evidence are preserved during upgrades. Previously saved advice is shown in its original language. Changing the app language does not translate it or issue a paid request. Original conversation content remains in its original language.

## Updates

Enabled update checks contact GitHub Pages and GitHub Releases. These services receive ordinary request information, such as an IP address. ContextCruise does not add conversation text, account tokens, or statistics databases to update requests. Sparkle system-profile reporting is disabled.

Automatic checking is a user choice. Automatic installation is off. Beta updates require explicit opt-in and use a separate feed. The beta feed is public; no stable release is available yet.

## Feedback you submit

Feedback is submitted by you. Share only system and app/Codex versions, reproducible steps, and redacted screenshots. The app does not provide a validated one-click redacted diagnostic export. Do not assume an exported bundle is safe to share. Do not attach raw logs, databases, auth.json, cookies, API keys, or complete personal paths.
