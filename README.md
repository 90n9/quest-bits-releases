# QuestBits — Releases

Public download page for **QuestBits**, a native macOS todo + Pomodoro app with a
bundled MCP server for Claude Code.

Source lives in the private repo `90n9/quest-bits`. Every tagged release there
(`vX.Y.Z`) is built by CI and published here as a downloadable DMG.

## Install

1. Download the latest `QuestBits_<version>.dmg` from the
   [Releases](https://github.com/90n9/quest-bits-releases/releases/latest) page.
2. Open the DMG and drag **QuestBits** into **Applications**.
3. First launch is blocked by Gatekeeper because the app is ad-hoc signed
   (not notarized by Apple). Clear the quarantine flag once:

   ```bash
   xattr -dr com.apple.quarantine /Applications/QuestBits.app
   ```

   Then open QuestBits normally.

## Notes

- macOS 14 (Sonoma) or later.
- Universal build — runs on Apple Silicon and Intel.
- This repo hosts binaries only; no source code.
