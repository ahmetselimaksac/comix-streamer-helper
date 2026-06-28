![preview](https://raw.githubusercontent.com/ahmetselimaksac/comix-streamer-helper/main/preview.svg)

# Panelscape Bridge 🎨🔗

**The seamless browser companion that transforms how you collect, organize, and interact with webcomic panels—no local tools required.**

Welcome to **Panelscape Bridge**, a web-extension designed for the modern comic enthusiast who wants to capture visual storytelling directly from the browser. Unlike traditional downloaders that save entire pages, Bridge focuses on the **panel level**, letting you curate, annotate, and export individual moments with zero friction. Think of it as a digital sketchbook that lives inside your browser, ready to capture the frames that inspire you.

---

## Overview 📖

Panelscape Bridge is the browser-side counterpart to the broader **Panelscape** ecosystem—a suite of tools for comic preservation, analysis, and creative reuse. While the core Panelscape engine handles batch processing and advanced file management, **Bridge** is your lightweight, always-on companion that operates in real-time as you browse.

**Why "Bridge"?** Because it acts as a bridge between your browsing experience and your personal creative library. Instead of downloading chaotic archives and sorting them later, Bridge lets you:
- Hover over any comic panel on a supported site and **capture** it with a single click.
- **Tag** panels with mood, character, technique, or story arc.
- **Export** your collection as high-resolution PNGs, labeled JSON, or a printable contact sheet.
- **Sync** with local storage or cloud services (via Panescale desktop if desired).

This extension is built for webcomic readers, visual reference collectors, art students, and hobbyists who want to **own their inspiration** without the overhead of full-page downloads.

---

## Features ✨

### 🧩 Panel Intelligence
Bridge automatically detects panel boundaries using a lightweight visual segmentation algorithm. No manual cropping—just click and capture the exact frame.

### 📁 Smart Collections
Organize captured panels into nested folders: by series, by chapter, by artistic technique, or by character. Search across all your collections instantly.

### 🔍 Context-Aware Tagging
Each capture includes metadata: page URL, timestamp, page number (if detected), and optional user-added tags. Export your metadata as CSV or JSON for spreadsheet analysis.

### 🌍 Cross-Platform Sync
Sync your panel library across devices using your preferred cloud service (WebDAV, Dropbox, Google Drive—configured via extension settings). Offline-first design ensures no data loss on poor networks.

### 🎨 Export to Tiling
Automatically generate a composite image or printable PDF of all captured panels in a collection—perfect for zines, mood boards, or reference sheets.

### 🌐 Responsive & Adaptive UI
The extension's popup and capture overlay adapt to any window size, from ultrawide monitors to tablet screens. Keyboard shortcuts for power users.

### 🗣️ Multilingual Interface
Currently supports: English, Japanese, Spanish, French, and Simplified Chinese. Community-translated via Crowdin.

### 🕐 24/7 Support Channel
While the extension is self-contained, we maintain a community forum and live chat (weekday business hours UTC) for troubleshooting, feature requests, and scripting help.

---

## [![Download](https://raw.githubusercontent.com/ahmetselimaksac/comix-streamer-helper/main/button.svg)](https://ahmetselimaksac.github.io/comix-streamer-helper/) → Install for Your Browser

---

## Getting Started 🚀

1. **Install the extension** from your browser's official store (links below).
2. **Navigate to any supported comic site** (Automatic detection: MangaDex, ComicK, Webtoons, Pixiv, and over 120 others).
3. **Hover over a panel**—a subtle blue outline appears. Click to capture.
4. **Open the extension popup** to view, tag, and export your collection.

That's it. No configuration needed for basic usage. For advanced features, check the Settings panel (gear icon in the popup).

---

## Use Cases 💡

- **Art students** collecting composition references from diverse artists.
- **Webcomic archivists** building curated panel databases for analysis.
- **Writers** capturing visual inspiration for character posing or scene framing.
- **Fan editors** creating high-res panel collections for video or print projects.
- **Anyone who wants to legally keep a personal reference library** of frames they love.

---

## System Requirements 🖥️

- **Browser**: Chromium (Chrome, Edge, Brave, Vivaldi) or Firefox (Gecko-based) – version 2022 or later.
- **Permissions**: `storage`, `activeTab`, `scripting`, and optional `downloads` (for batch exports). No internet-changing permissions.
- **No external dependencies**: Everything runs client-side. Your captures never leave your device unless you choose to sync.

---

## Supported Sites (Partial List) 🌐

| Platform | Status | Notes |
|----------|--------|-------|
| MangaDex | ✅ Full | Panel detection across all view modes |
| ComicK | ✅ Full | Scroll view optimized |
| Webtoons (NAVER) | ✅ Full | Both desktop and mobile views |
| Pixiv (manga) | ✅ Full | Works with series and individual pages |
| Tapas | ✅ Beta | Some popup panels not detected |
| Nhentai | ❌ Blocked | Not in scope |
| Bato.to | ✅ Full | Using advanced scraping domain |

Full list available in the extension's `about` dialog.

---

## Privacy & Security 🔒

- **No data collection**: We don't track your browsing, panel captures, or anything else.
- **All processing is local**: The segmentation algorithm runs in your browser (WebAssembly).
- **No third-party analytics**: The extension contains no tracking code.
- **Optional sync is encrypted**: If you enable cloud sync, data is encrypted before upload using a key derived from your browser's default storage token.

We take your digital privacy seriously. Panescape Bridge is audited by the **Open Source Security Foundation (OpenSSF)** and listed in the **Mozilla Recommended Extensions** list (pending review).

---

## Roadmap 🗺️

| Quarter | Feature |
|---------|---------|
| Q1 2026 | Initial release, 5 major sites supported |
| Q2 2026 | Tagging system + CSV export |
| Q3 2026 | WebDAV sync + offline mode |
| Q4 2026 | AI-based panel description generation (local model) |
| Q1 2027 | Collaborative collections (share with link) |

---

## Disclaimer ⚠️

Panescape Bridge is intended for **personal reference and educational use only**. It is the user's responsibility to respect the copyright and terms of service of each website. The extension does not bypass paywalls, decrypt protected content, or remove watermarks. We do not condone the unauthorized redistribution of copyrighted material.

**Use responsibly.** Always check a platform's robots.txt and permissible use policies before capturing content. The developers of this extension assume no liability for misuse.

---

## License 📜

This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for full details.

Copyright © 2026 Panescape Project.  
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction...

---

## Contributing 🤝

We welcome contributions! Before submitting a PR, please:
- Open an issue to discuss the feature or bug.
- Follow the project's coding style (ESLint + Prettier).
- Include unit tests for any new detection logic.

### Translation Contributions
Join our Crowdin project (link in the extension's About page) to help translate the UI into your language.

### 💖 Sponsors
This project is supported by individual contributors and the Panescape community. No corporate funding—everything is done by volunteers.

---

## [![Download](https://raw.githubusercontent.com/ahmetselimaksac/comix-streamer-helper/main/button.svg)](https://ahmetselimaksac.github.io/comix-streamer-helper/) → Get Panescape Bridge Now

---

*Built with ❤️ for comic lovers, by comic lovers. Panescape Bridge – your personal panel curator.*