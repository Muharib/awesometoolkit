<div align="center">

# Awesome Toolkit

**Your all-in-one file toolkit — 100% in your browser.**

Convert, compress, resize, watermark, remove backgrounds, extract text, and automate workflows.
No uploads. No servers. Your files never leave your device.

[![Tools](https://img.shields.io/badge/tools-40%2B-6366f1)](https://awesometoolkit.com)
[![Privacy](https://img.shields.io/badge/privacy-100%25_client--side-10b981)](https://awesometoolkit.com)
[![License](https://img.shields.io/badge/license-MIT-blue)](LICENSE)

[Try it free →](https://awesometoolkit.com)

</div>

---

![Awesome Toolkit Dashboard](https://awesometoolkit.com/og-image.png)

## What is Awesome Toolkit?
- [PDF Toolbox](https://pdftoolbox-three.vercel.app) - Privacy-first browser-based PDF tools. Files never leave your computer.

Awesome Toolkit is a free online platform with 40+ file processing tools that run entirely in your browser. No file uploads, no server queues, no privacy concerns. Powered by WebAssembly, Web Workers, and in-browser AI models.

Available in English and French.

## Tools

### Images
Convert (HEIC, PNG, WebP, SVG, ICO) · Compress · Resize · Crop · Rotate · Watermark · Remove Background (AI) · Upscale (AI) · Social Media Resize · Image to PDF · Image to SVG · Image to Text (OCR) · PNG to ICO

### Video
Compress · Trim · Change Speed · Extract Audio (MP3) · Convert to GIF

### PDF
Compress · Split · Rotate · Add Page Numbers · Add Text Stamps · PDF to Image · Image to PDF · Extract Text

### Audio
Compress · Convert

### Text & Developer Tools
JSON/CSV/YAML Converter · Markdown to HTML · Base64 Encode/Decode · Case Converter · Search & Replace · Sort · Filter · JSON Formatter

## Visual Workflow Builder

Chain any tools together into automated pipelines with a drag-and-drop node editor.

Build once, save, reuse. One input file in, multiple processed outputs out.

- Real-time format validation across the graph
- Save and reopen workflows as dashboard tabs
- Condition nodes for branching logic


## Why Client-Side?

| | Server-based tools | Awesome Toolkit |
|---|---|---|
| **Privacy** | Files uploaded to third-party servers | Files never leave your device |
| **Speed** | Limited by upload bandwidth | Limited only by your hardware |
| **Offline** | Requires internet | Works offline once loaded |
| **File size** | Capped by server costs | Limited by device RAM only |
| **Cost** | Servers, bandwidth, storage | Near-zero (static hosting) |

## Tech Stack

- **Framework:** Next.js 16 (App Router) + React 19
- **Processing:** WebAssembly (FFmpeg), Canvas API, Web Workers
- **AI:** ONNX Runtime (background removal, upscaling, OCR)
- **UI:** Tailwind CSS 4, Radix UI
- **Workflows:** ReactFlow
- **Auth:** NextAuth 5
- **Database:** Prisma + SQLite
- **i18n:** next-intl 4 (EN/FR)

## Getting Started

Visit **[awesometoolkit.com](https://awesometoolkit.com)** — no account required for basic use.

Create a free account for 80 usages/day and 1 saved workflow. Upgrade to Pro for unlimited usage and 25 saved workflows.

## License

[MIT](LICENSE)
