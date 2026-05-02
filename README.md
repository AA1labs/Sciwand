# Sciwand

A SuperAI overlay for your research knowledge base. Connects to Zotero, EndNote, and Mendeley, with a built-in PDF viewer and integrated AI features.

> Source code lives in a private repository. This repository hosts public release binaries only.

## What it does

**Document analysis.** Chat with your library. Every AI answer is referenced, so you can trace each claim back to the source. View citing articles, references, and an in-app citation graph (like Connected Papers or Research Rabbit) with direct access to any paper.

**Academic database search.** Run AI-powered queries directly inside Google Scholar, PubMed, arXiv, Semantic Scholar, and more. Open PDFs in-app and ask the AI questions on the spot.

**Document writer.** A controlled writing copilot grounded in your library, not the open web. AI assists; you stay in charge of the data. No hallucinated references.

**Smart columns.** Add Yes/No or 1 to 10 score columns to screen large collections by AI prompt. Works on saved collections and live search results alike.

## Already in the box (rolling out)

- Microsoft Word extension with 10,000+ citation styles plus optional AI features
- Cloud sync (free and affordable paid tier, third-party hosted)
- Browser clipping extension
- iPad and mobile apps (shipping after Cloud sync)

This is a **public alpha**. Expect rough edges and error messages. Please be patient, be polite, and report issues. They will get attention.

## Download

Latest releases: https://github.com/AA1labs/Sciwand/releases/latest

| Platform | Architecture | File |
|---|---|---|
| macOS | Apple Silicon + Intel (universal) | `Sciwand_X.Y.Z_universal.dmg` |
| Windows | x86_64 | `Sciwand_X.Y.Z_x64-setup.exe` |
| Linux | x86_64 (AppImage) | `Sciwand_X.Y.Z_amd64.AppImage` |

## macOS

Mount the DMG and drag `Sciwand` to `/Applications`. Double-click to launch. Sciwand is signed with a Developer ID certificate and Apple-notarized, so no first-launch warning or workaround is needed.

## Windows

Run `Sciwand_X.Y.Z_x64-setup.exe`. SmartScreen may show "Windows protected your PC". Click **More info -> Run anyway**. Sciwand isn't EV-signed for Windows yet.

## Linux

```sh
chmod +x Sciwand_X.Y.Z_amd64.AppImage
./Sciwand_X.Y.Z_amd64.AppImage
```

## Auto-updates

Sciwand checks for updates from this repository on launch. Updates download in the background and apply on next restart. No manual intervention after the first install.

## Issues

Please open an issue on this repository for bugs, crashes, and feedback.

## License

Proprietary. (c) AA1 Labs. See in-app About -> Legal for details.
