# ContextCruise

A free macOS companion for monitoring local Codex conversations: compaction counts, observed activity time, conversation state, search, favorites, and an archive view.

![ContextCruise 10014 on macOS 13.4.1](assets/contextcruise-macos13-build10014.png)

Actual UI in a clean macOS 13.4.1 virtual machine, using four synthetic test conversations with AI analysis disabled.


**Build 10015 is the current public beta. The app and DMG are signed and notarized, and isolated update-failure and recovery checks passed. Final installation, redacted real-record reading, search and quit/reopen checks passed on macOS 13.4.1. It has been publicly released.** Public HTTPS downloads and the beta feed passed public-access checks; no stable release is available yet.

- Apple Silicon only; macOS 13 or later. A clean macOS 13.4.1 virtual machine was used for embedded-runtime, installation, synthetic-record and UI checks. Existing real-Codex integration evidence comes from macOS 27.0.1. Other OS and Codex combinations are not fully covered.
- A single application with an embedded Python runtime. No separate connector, Python, or Homebrew installation is required.
- No Pro tier, subscriptions, in-app purchases, or two-conversation paywall.
- Optional AI analysis is off by default. Enabling it after configuration sends analysis material to your chosen provider, which may charge API fees.
- An independent project, not affiliated with or endorsed by OpenAI. Local Codex records are required; ChatGPT web conversations are not monitored.

See the [installation guide](docs/INSTALL.en.md), [privacy notice](PRIVACY.md), [known limitations](docs/KNOWN_ISSUES.md), and [license](FREE_USE_LICENSE.md).

Official installers are available through [Releases](https://github.com/jack1231222/contextcruise/releases). Never disable macOS security protections to install the app.

Report ordinary bugs through [Issues](https://github.com/jack1231222/contextcruise/issues). Do not attach conversation content, authentication files, databases, API credentials, or personal paths. See [SECURITY.md](SECURITY.md) for security reports.
