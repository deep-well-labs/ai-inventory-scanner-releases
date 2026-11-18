# AI Inventory Scanner 0.2.0 beta 1

The first public beta of a small, standalone Mac utility from Deep Well Labs and Angry Porter.

- On-demand discovery of recognizable AI application metadata, supported CLI package metadata/install layouts, and user/global MCP configuration entries.
- Evidence and limitations for each finding; inspection status is separate from catalog recognition.
- Detailed local JSON export with scan timing, versions, findings and coverage. Review paths and integration names before sharing a report.
- Native Mac interface with a restrained Angry Porter visual style. Bundled definitions: 2026-11-17.3.

Apple Silicon; macOS 26 or later. Version 0.2.0, build 5. Developer ID signed by Deep Well Labs, notarized by Apple, with stapled tickets. No account, background service, inventory upload or automatic updater.

Open the DMG and drag AI Inventory Scanner to Applications. Quit an older copy before replacing it. Scans are held in memory; export a report before quitting if you want to keep it.

## Coverage and beta limits

Metadata does not verify the identity or integrity of discovered software, working connections or actual use. Filename/layout-only candidates remain possible matches. Configured MCP entries can describe generic tools rather than AI services. No catalog match means unknown AI status.

Browser-only AI, embedded features, custom prefixes/manager homes, project dependencies, unsupported environments and other users can be missed. Some Homebrew receipt variants remain unrecognized. Scan budgets can leave incomplete coverage; inspect the coverage report.

Tested with synthetic fixtures on macOS 27.2.1. macOS 26 device coverage, Intel, a separate clean Mac, VoiceOver and the broader accessibility/compatibility matrix have not been verified. The five-second scan budget is cooperative rather than a hard wall-clock deadline. This beta does not claim a comprehensive inventory.
