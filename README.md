<div align="center">

<img src="https://github.com/avrealmop/SnapMeta/blob/main/assets/logo.png" alt="SnapMeta Logo" width="128"/>

# SnapMeta

**AI Metadata Studio for Microstock**

Generate titles, descriptions, and keywords for your stock files in seconds — written directly into JPG, PNG, SVG, and EPS.

![Version](https://img.shields.io/badge/version-1.0.2-blue)
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

### Ideas

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

### Licensing

- **Paid app** — available on the Microsoft Store with a **7-day free trial**, then a one-time purchase.
- Trial and license are tied to your Microsoft account and verified against the Store on each launch; reinstalling does not reset the trial.
- When the trial ends, the app shows a purchase screen and unlocks automatically once the payment completes.

---

## Screenshots

| | | |
|:---:|:---:|:---:|
| ![1](https://github.com/avrealmop/SnapMeta/blob/main/assets/1.png) | ![2](https://github.com/avrealmop/SnapMeta/blob/main/assets/2.png) | ![3](https://github.com/avrealmop/SnapMeta/blob/main/assets/3.png) |
| ![4](https://github.com/avrealmop/SnapMeta/blob/main/assets/4.png) | ![5](https://github.com/avrealmop/SnapMeta/blob/main/assets/5.png) | 

---

## Requirements

- Windows 10 version 1809 (64-bit) or later
- AI provider API key (OpenAI, Google Gemini, Groq, OpenRouter, or compatible endpoint)

---

## Getting Started

1. [Download SnapMeta from the Microsoft Store](https://apps.microsoft.com/store/detail/9PD3B95ZG4DJ?cid=DevShareMCLPCS) (7-day free trial, then one-time purchase).
2. Install and launch SnapMeta.
3. Open SnapMeta → **API Key** → add your AI provider API key.
4. Drop in a file or folder, click **Generate**, review, and save.

---

## Download

| Package | Link |
|---|---|
| Microsoft Store (Windows x64) | [SnapMeta on Microsoft Store](https://apps.microsoft.com/store/detail/9PD3B95ZG4DJ?cid=DevShareMCLPCS) |

> Full changelog and previous releases: [Releases page](https://github.com/avrealmop/SnapMeta/releases)

---

## License

This project is licensed under the [GNU Affero General Public License v3.0](https://www.gnu.org/licenses/agpl-3.0.html).

Third-party notices: [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md)

---

## Donate

Love SnapMeta? Support the development:

- [Buy me a coffee on Ko-fi](https://ko-fi.com/avrealmop)
- [Donate via PayPal](https://www.paypal.com/paypalme/apriliyanto77)

