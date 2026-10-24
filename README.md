# Nuka apps for Mac

macOS apps by Grigorii Iakovlev. Polly, Razzy and Viggo are free; Lexter is free to use with a daily AI limit, and Standard and Pro licenses are sold at https://nukatools.app/pricing. Every download is signed with Developer ID and notarized by Apple,
so it opens without warnings. Download the `.dmg` from [Releases](https://github.com/GrafDev/nuka-apps/releases),
open it and drag the app to Applications.

Requirements: macOS 15 Sequoia or later, Apple Silicon (Viggo also runs on Intel).

| App | What it does |
|---|---|
| **Lexter** | Translates and improves text in any app with an AI model that runs on your Mac; texts never leave it. Free daily limit, Standard (unlimited AI translation) and Pro (Improve Text) licenses. |
| **Polly** | Fixes words typed in the wrong keyboard layout as you type. Needs Accessibility and Input Monitoring. |
| **Razzy** | Opens and extracts RAR, ZIP, 7z, TAR, gz, bz2 and xz archives; double-click unpacks next to the archive. |
| **Viggo** | Lets QuickTime Player, Finder and Quick Look open the MKV and WebM files already on your Mac (no streaming, no online content) (enable once in System Settings → Login Items & Extensions → Media Extensions). |

Website: https://nukatools.app

## Notes

- Polly's word lists are derived from the Leipzig Corpora Collection (Universität Leipzig), CC BY 4.0, with sentences from Mozilla Common Voice (CC0). Details are in the app (Settings → Language data) and in `Polly.app/Contents/Resources/NOTICE.txt`.
- Razzy uses the UnRAR source by Alexander Roshal (RARLAB), macOS's libarchive and the LZMA SDK (public domain); their licences ship inside the app.

The source code is not published here; this repository only hosts the downloads.
