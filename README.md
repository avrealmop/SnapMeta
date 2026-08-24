<div align="center">

# SnapMeta

**AI Metadata Studio for Microstock**

Generate titles, descriptions, and keywords for your stock files in seconds — written directly into JPG, PNG, SVG, and EPS.

![Version](https://img.shields.io/badge/version-1.0.1-blue)
![Platform](https://img.shields.io/badge/platform-Windows%2010%2F11%20(x64)-0078D6)
![License](https://img.shields.io/badge/license-AGPL--3.0-orange)

</div>

---

## About

SnapMeta is a desktop application for microstock creators (Shutterstock, Adobe Stock, Getty iStock, and similar agencies). It uses AI vision to detect the content of your files, then auto-generates a title, a description, and long-tail keywords — all respecting the character limits and naming rules of each platform. Results are written directly into file metadata: XMP/IPTC for JPG and PNG, native metadata for SVG, and metadata for EPS.

---

## Features

### Metadata Studio

- **AI-powered generation** — Drop one file or an entire folder. SnapMeta analyzes each asset and generates a title, description, and dozens of long-tail keywords matching each platform's rules.
- **Write directly into files** — Results are embedded into file metadata (XMP/IPTC for JPG/PNG, native `<title>`/`<desc>` + RDF for SVG, XMP headers for EPS). No manual copy-paste.
- **Review & refine before saving** — Preview every generated title, description, and keyword list. Edit what you need, add hidden keywords and categories.
- **Platform rules engine** — Presets for Shutterstock, Adobe Stock, and custom platforms. Configure max title length, max description length, and max tags.
- **Batch processing** — Process hundreds of files with progress bar, per-file logs (success/failed), and final summary.
- **Smart deduplication** — Detects duplicate metadata across files in the batch.
- **Auto-retry with fallback** — Failed generations automatically retry with alternate API keys.
- **Multiple API keys in parallel** — Add several keys per provider; SnapMeta distributes workload across them.

### Ideas / StockScope

- **Discover** — Scan trending niches for Footage, Raster, Vector, and PNG content. Get long-tail keyword lists, production notes, and AI-suggested sources.
- **Gap Analysis** — Find high-demand keywords with low supply. Filter by intent, trend volume, and potential, then push the best ones into your keyword list.

### World Calendar

- International, public, and bank holidays by country and month. Plan seasonal content before the buying window opens.

### Privacy & Security

- **Local-first** — Files are processed on your device. Only the selected file and your prompt are sent to the AI provider you configure.
- **Multi-provider support** — OpenAI, Google Gemini, Groq, OpenRouter, or any OpenAI-compatible endpoint (`/chat/completions`).
- **API keys stored locally** — Never transmitted anywhere except to your chosen provider.
- **Consent gate** — First-run privacy dialog explains data flow; you must agree before using AI features.
- **Ghostscript for EPS** — Bundled (AGPL-3.0), auto-installed on first EPS processing. Runs offline.

---

## Screenshots

| | | |
|:---:|:---:|:---:|
| ![1](assets/screenshots/snapmeta_WuNKX9igJY.png) | ![2](assets/screenshots/snapmeta_PCeshxXQSS.png) | ![3](assets/screenshots/snapmeta_Mk7myKF04z.png) |
| ![4](assets/screenshots/snapmeta_ZG929sPKlW.png) | ![5](assets/screenshots/snapmeta_ZwhA90LXtx.png) | ![6](assets/screenshots/snapmeta_0218tJbZ7G.png) |

---

## Requirements

- Windows 10 version 1809 (64-bit) or later
- AI provider API key (OpenAI, Google Gemini, Groq, OpenRouter, or compatible endpoint)

---

## Getting Started

1. Download the installer from [Releases](https://github.com/avrealmop/SnapMeta/releases/latest).
2. Run `SnapMeta-Setup-1.0.1.exe` and follow the wizard.
3. Open SnapMeta → **API Key** → add your AI provider API key.
4. Drop in a file or folder, click **Generate**, review, and save.

---

<!-- ============================================================
     CARA EDIT VIDEO TUTORIALS:
     1. Buka YouTube, klik video → Share → Copy video ID (bagian setelah watch?v=)
        Contoh: https://www.youtube.com/watch?v=ABCD1234XYZ  →  ID = ABCD1234XYZ
     2. Copy 1 blok baris di bawah ini (3 baris: <!--, ![], |), paste sebanyak jumlah video.
     3. Ganti VIDEO_ID dengan ID video kamu.
     4. Ganti caption thumbnail (misal "Getting Started", "Batch Processing", dll).
     5. Hapus atau komentari baris yang tidak dipakai.
     ============================================================ -->

## Video Tutorials

| | |
|:---:|:---:|
| [![Tutorial 1](https://img.youtube.com/vi/VIDEO_ID/maxresdefault.jpg)](https://www.youtube.com/watch?v=VIDEO_ID) | [![Tutorial 2](https://img.youtube.com/vi/VIDEO_ID/maxresdefault.jpg)](https://www.youtube.com/watch?v=VIDEO_ID) |

<!-- Tambah baris di atas sesuai jumlah video yang kamu punya. Hapus yang tidak dipakai. -->

---

## Download

| Package | Link |
|---|---|
| Windows (x64) Installer | [SnapMeta-Setup-1.0.1.exe](https://github.com/avrealmop/SnapMeta/releases/latest) |
| Windows Portable (x64) | [SnapMeta-Portable-1.0.1.zip](https://github.com/avrealmop/SnapMeta/releases/latest) |
| Microsoft Store | [SnapMeta on Store](https://apps.microsoft.com/detail/9PD3B95ZG4DJ) |

> Full changelog and previous releases: [Releases page](https://github.com/avrealmop/SnapMeta/releases)

---

## License

This project is licensed under the **GNU Affero General Public License v3.0**. See [LICENSE](LICENSE) for details.

Third-party notices: [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md)

---

## Contact & Support

- **GitHub Repository**: [https://github.com/avrealmop/SnapMeta](https://github.com/avrealmop/SnapMeta)
- **Bug Report / Feedback**: [Google Form](https://forms.gle/9BdPjvERsFKNTktX9)
- **Email**: [blackzedo@gmail.com](mailto:blackzedo@gmail.com)
