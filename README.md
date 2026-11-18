# AI Inventory Scanner releases

Public binary releases and release metadata for **AI Inventory Scanner**, an Angry Porter tool by Deep Well Labs.

The macOS application source is private. GitHub's automatically generated “Source code” archives contain this metadata repository, not the application source. Download the versioned `.dmg` asset from [Releases](https://github.com/deep-well-labs/ai-inventory-scanner-releases/releases).

Initial platform target: Apple Silicon, macOS 26 or later. This is an on-demand, read-only scanner with bundled definitions and local JSON export. It does not monitor activity, upload inventory or update itself automatically.

Open the DMG and drag the app to Applications. To update, quit the app and replace the older copy. Check the release notes for supported coverage and known gaps. Metadata matches do not verify the publisher, integrity or use of discovered tools; a scan cannot establish that every AI tool has been found.

Each release includes the signed/notarized DMG, `SHA256SUMS` and `release.json`. Verify the downloaded file with:

```sh
shasum -a 256 -c SHA256SUMS
```

Details: [Deep Well Labs](https://www.deepwelllabs.com/tools/ai-inventory-scanner). Support: [support@angryporter.com](mailto:support@angryporter.com).
