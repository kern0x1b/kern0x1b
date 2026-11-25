### kern0x1b

Reverse-engineering software that stopped working when someone else's API
changed — old iOS jailbreak tweaks, dev tooling built to outlive the next
version bump.

#### Old iOS, kept alive

- **[revenant](https://github.com/kern0x1b/revenant)** — current iOS software on iOS 6.1.3 (iPhone 4S, armv7): toolchain, emulator, arm64-to-armv7 recompiler, and SwiftUI, Combine and WebKit for iOS 6.
- **[classicgram](https://github.com/kern0x1b/classicgram)** — Telegram client for 32-bit armv7 iPhones and iPads on iOS 6, wearing the 2013 interface.
- **[kindle-sync-fix](https://github.com/kern0x1b/kindle-sync-fix)** — MobileSubstrate tweak fixing the Kindle Whispersync 417 error on jailbroken iOS 6.
- **[cydia](https://github.com/kern0x1b/cydia)** — the Cydia source that ships the packages above: Classicgram, the Kindle sync fix and a SoundCloud API fix.

#### JetBrains & editor tooling

- **[Penstock](https://getpenstock.com/)** — BPMN 2.0, DMN and form editor for Camunda 7 and 8 in JetBrains IDEs, VS Code and the browser, with a command line and an MCP server ([issues and releases](https://github.com/kern0x1b/penstock-release); CLI via [homebrew-penstock](https://github.com/kern0x1b/homebrew-penstock)).
- **[cef-openapi-generator](https://github.com/kern0x1b/cef-openapi-generator)** — OpenAPI code generator (Java and Kotlin) for Chromium Embedded Framework with JetBrains Platform integration. 99%+ instruction coverage, real integration tests, not a demo.
- **[vscode-intellij-code-formatter](https://github.com/kern0x1b/vscode-intellij-code-formatter)** — runs IntelliJ IDEA's actual formatting engine headlessly. No reimplementation, no drift from the real thing.
- **[vscode-intellij-theme](https://github.com/kern0x1b/vscode-intellij-theme)** — IntelliJ IDEA Islands colors, ported to VS Code.

#### Paseo plugins & agent tooling

- **[paseo-plugins](https://github.com/kern0x1b/paseo-plugins)** — plugins and tools for Paseo in one repository:
  - **paseo-gitlab** — a mini GitLab inside Paseo: issues, merge requests, review, pipelines, with the token in the OS keychain.
  - **paseo-slack** — Slack Web API access, real-time event router and MCP tools for agent sessions.
  - **paseo-channels** — pushes GitLab and Slack events into an agent session as Claude Code channel events; the protocol lets any other platform plug in.

No stats widget, no streak graph — the commits speak for themselves.
