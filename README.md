# ☕ Bala's PDF Pro

> A powerful, free, browser-based PDF editor. No installs. No sign-ups. No Adobe needed.

[![Live Demo](https://img.shields.io/badge/🚀_Live_Demo-Visit_Now-4493f8?style=for-the-badge)](https://yourusername.github.io/balas-pdf-pro)
[![License](https://img.shields.io/badge/License-MIT-a371f7?style=for-the-badge)](LICENSE)
[![Made with](https://img.shields.io/badge/Made_with-❤️_&_Claude-f85149?style=for-the-badge)](https://claude.ai)

---

## ✨ What is this?

**Bala's PDF Pro** is a fully featured PDF editor that runs entirely in your browser — no downloads, no subscriptions, no data sent to any server. Open any PDF, edit it, sign it, and save it back — all for free.

Built by **Bala**, a QA tester at a media company, using AI-assisted development.

---

## 🛠️ Features

| Feature | Description |
|---|---|
| 📝 **Text Tool** | Click anywhere on the PDF to add text. Automatically matches the font size and colour of nearby text |
| ✏️ **Draw** | Freehand pen tool for annotations and sketches |
| 🖊️ **Highlight** | Mark important text with a translucent highlight |
| ✍️ **Signature** | Draw, type, or upload your signature and place it anywhere |
| ▭ **Shapes** | Add rectangles and arrows for diagrams and callouts |
| 🧹 **Eraser** | Remove any annotation with one click |
| ↖️ **Select & Move** | Click any annotation to select it, then drag it anywhere |
| 🔤 **Edit Text** | Double-click placed text to re-edit it; change font, size, and colour from the panel |
| ↩️ **Undo / Redo** | Full undo/redo history (up to 60 steps per page) |
| 🔍 **Zoom** | Zoom in/out or fit to window |
| 📄 **Multi-page** | Navigate pages with thumbnails; rotate or delete individual pages |
| 💾 **Save PDF** | Exports a real `.pdf` file with all edits permanently baked in |

---

## 🎨 Smart Text Matching

When you click the **Text tool** and click near existing text on the PDF, the editor automatically detects:

- ✅ **Font size** — matches the size of the nearest text line
- ✅ **Font colour** — reads the actual colour from the PDF
- ✅ **Font family** — detects serif, sans-serif, or monospace from the PDF font name

A toast notification confirms what was matched, e.g. `Matched 12px · serif · #1a1a1a`

---

## 🚀 How to Use

1. **Open** — Click **Open** or drag & drop any PDF file
2. **Select a tool** from the left sidebar (or use keyboard shortcuts)
3. **Edit** — click, draw, type, or sign directly on the document
4. **Save** — click **💾 Save PDF** to download your edited file

### Keyboard Shortcuts

| Key | Action |
|---|---|
| `S` | Select tool |
| `T` | Text tool |
| `D` | Draw tool |
| `H` | Highlight |
| `R` | Rectangle |
| `A` | Arrow |
| `E` | Erase |
| `[ ]` | Decrease / increase font size of selected text |
| `Del` | Delete selected annotation |
| `Ctrl+Z` | Undo |
| `Ctrl+Y` | Redo |
| `Ctrl+S` | Save PDF |
| `Arrow keys` | Nudge selected annotation (Shift = 20px) |
| `+` / `-` | Zoom in / out |
| `Esc` | Place text & switch to Select |

---

## 🖥️ Tech Stack

This is a **single HTML file** — zero dependencies to install, zero build steps.

| Library | Purpose |
|---|---|
| [PDF.js](https://mozilla.github.io/pdf.js/) | Render PDF pages to canvas |
| [pdf-lib](https://pdf-lib.js.org/) | Write annotations back into the PDF file |
| [Google Fonts](https://fonts.google.com/) | Inter, DM Mono, Dancing Script |

Everything else — the editor, annotation engine, font snapping, signature pad, undo/redo, drag-to-move — is written from scratch in vanilla JavaScript.

---

## 📁 Project Structure

```
balas-pdf-pro/
├── index.html      ← The entire application (HTML + CSS + JS)
└── README.md       ← This file
```

That's it. One file.

---

## 🌐 Hosting

This tool is hosted for free on **GitHub Pages**.

To run it locally, just open `index.html` in any modern browser — Chrome, Firefox, Edge, or Safari.

---

## 🤝 Contributing

Found a bug or want a new feature? Open an issue or submit a pull request.

1. Fork the repo
2. Make your changes in `index.html`
3. Open a pull request with a description of what you changed

---

## 📜 License

MIT License — free to use, modify, and distribute. See [LICENSE](LICENSE) for details.

---

## 👨‍💻 About the Author

**Bala** — QA Tester at a media company, PDF enthusiast, builder of things.

- Built this because Adobe Acrobat costs too much
- Developed with the help of [Claude AI](https://claude.ai)
- Feedback welcome — open an issue!

---

<div align="center">

**If this saved you money on Adobe, consider ⭐ starring the repo!**

Made with ☕ and a lot of Ctrl+Z

</div>
