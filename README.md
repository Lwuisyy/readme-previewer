<!-- ═══════════════════════════════════════════════════════════════════ -->
<!--                    README PREVIEWER — PROJECT README              -->
<!-- ═══════════════════════════════════════════════════════════════════ -->

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&height=80&text=README%20Previewer&fontSize=42&fontAlignY=50&fontColor=ffffff&color=0:0f172a,50:0e75b6,100:0f172a" />
</p>

<p align="center">
  <strong>Live markdown editor with GitHub-dark theme preview. Single file, zero install.</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML-Single_File-0e75b6?style=flat-square&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/No_Dependencies-0e75b6?style=flat-square" />
  <img src="https://img.shields.io/badge/License-MIT-0e75b6?style=flat-square" />
  <img src="https://img.shields.io/badge/Repo_Size-7_KB-0e75b6?style=flat-square" />
</p>

---

## ✦ What Is This?

**README Previewer** is a single HTML file that lets you write and preview GitHub-style markdown in real-time — no server, no npm, no extensions needed. Just open it in your browser.

Perfect for:
- Designing your **GitHub Profile README**
- Writing project documentation
- Testing markdown layouts before pushing

---

## ✦ Features

| Feature | Description |
|---|---|
| **Live Split Editor** | Type markdown on the left, see GitHub-dark preview on the right instantly |
| **GitHub Dark Theme** | Uses official `github-markdown-css` — looks exactly like GitHub |
| **Open File** | Load any `.md` file from your computer |
| **Save File** | Download your work as `README.md` |
| **Copy to Clipboard** | One-click copy of your markdown |
| **Drag & Drop** | Drop `.md` files directly into the browser |
| **Auto-save** | Content saved to `localStorage` — survives page refresh |
| **Syntax Highlighting** | Code blocks rendered with `highlight.js` |
| **Keyboard Shortcuts** | `Ctrl+S` to save, `Ctrl+O` to open |
| **Tab Support** | Tab key inserts 2 spaces |
| **Responsive** | Works on mobile — panels stack vertically |
| **Zero Install** | Single HTML file, no dependencies |

---

## ✦ How to Use

1. Download or clone this repo
2. Open `index.html` in your browser
3. Start typing or paste your markdown
4. Preview updates in real-time

```bash
git clone https://github.com/lwuisy/readme-previewer.git
cd readme-previewer
# Open index.html in your browser
```

Or just download the `index.html` file and open it directly.

---

## ✦ Tech Stack

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-0e75b6?style=for-the-badge&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-0e75b6?style=for-the-badge&logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-0e75b6?style=for-the-badge&logo=javascript&logoColor=white" />
</p>

Libraries (loaded via CDN):
- [marked.js](https://marked.js.org/) — Markdown parser
- [DOMPurify](https://github.com/cure53/DOMPurify) — XSS sanitization
- [highlight.js](https://highlightjs.org/) — Code syntax highlighting
- [github-markdown-css](https://github.com/sindresorhus/github-markdown-css) — GitHub styling

---

## ✦ Keyboard Shortcuts

| Shortcut | Action |
|---|---|
| `Ctrl + S` | Save as README.md |
| `Ctrl + O` | Open .md file |
| `Tab` | Insert 2 spaces |

---

## ✦ License

MIT — use it, fork it, modify it. No restrictions.

---

<p align="center">
  <i>Built for developers who want to preview READMEs without pushing to GitHub.</i>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&height=40&color=0:0f172a,50:0e75b6,100:0f172a" />
</p>
