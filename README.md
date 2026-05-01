# వెలుగీత పుస్తకాలు · Velugeetha Books 📖

> **Accessible digital library for visually impaired students — supporting Telugu and Dravidian languages.**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![WCAG 2.1 AA](https://img.shields.io/badge/Accessibility-WCAG%202.1%20AA-green)](https://www.w3.org/WAI/WCAG21/quickref/)
[![Languages](https://img.shields.io/badge/Languages-Telugu%20%7C%20Tamil%20%7C%20Kannada%20%7C%20Malayalam-blue)]()

---

## 🌟 About This Project

**Velugeetha Books** is an open-source accessible library aimed at:

- 🧑‍🎓 **Visually impaired students** — screen-reader-ready, audio books, Braille-ready exports
- 👨‍👩‍👧 **Parents** — insight into their child's learning progress and resources
- 📚 **Dravidian language learners** — Telugu, Tamil, Kannada, Malayalam, and Sanskrit
- 🕉️ **Sanathana Dharma & classical text preservation** across sister Dravidian languages

---

## ✨ Features

| Feature | Description |
|---|---|
| 🔊 Text-to-Speech | Audio playback in Telugu, Tamil, Kannada, Malayalam |
| 🔠 Adjustable Text | Font size control (A− / A / A+) |
| ⬛ High Contrast | Toggle for low-vision users |
| ⌨️ Keyboard Navigation | Fully accessible without a mouse |
| 📱 Mobile Friendly | Works on any Android/iOS device |
| 📥 Offline Download | PDF and audio downloads |
| ♿ Screen Reader | NVDA, JAWS, TalkBack compatible |

---

## 🗣️ Dravidian Language Model 2.0

Mapping classical Sanathana Dharma texts and modern curriculum across Dravidian sister languages:

| Language | Script | Audio | Braille | Status |
|---|---|---|---|---|
| తెలుగు Telugu | Telugu | ✅ | ✅ | **Live** |
| தமிழ் Tamil | Tamil | ✅ | 🔄 | **Live** |
| ಕನ್ನಡ Kannada | Kannada | 🔄 | — | Coming Soon |
| മലയാളം Malayalam | Malayalam | 🔄 | — | Coming Soon |
| Sanskrit संस्कृत | Devanagari | — | — | Planned |

---

## 📁 Repository Structure

```
velugeetha-books/
├── index.html              ← Accessible main website
├── README.md               ← This file
├── styles/
│   └── accessible.css      ← Shared accessibility styles
├── books/
│   ├── telugu/             ← Telugu text books (PDF + EPUB)
│   ├── tamil/              ← Tamil books
│   ├── kannada/            ← Kannada books
│   └── sanskrit/           ← Sanskrit / Sanathana texts
├── audio/
│   ├── telugu/             ← MP3 audio versions
│   └── tamil/
├── data/
│   └── dravidian-model/    ← Language model datasets & mappings
└── docs/
    └── parents-guide.md    ← Guide for parents
```

---

## 👨‍👩‍👧 For Parents — తల్లిదండ్రులకు

This project is built with **parents in mind**:

- Know which lessons are available in audio format
- Share download links with your child's school
- All content is **free and open source**
- Works on low-cost Android phones

---

## 🚀 How to Contribute

1. **Fork** this repository
2. Add books in `books/<language>/` folder
3. Add audio files in `audio/<language>/` folder
4. Open a **Pull Request** with a description

### File Format Guidelines
- Books: **PDF (tagged/accessible)** or **EPUB**
- Audio: **MP3 or OGG** (recommended: 64kbps for small file size)
- Language data: **JSON or CSV**

---

## ♿ Accessibility Standards

This project aims to meet **WCAG 2.1 Level AA**:
- All images have alt text
- Color contrast ratio ≥ 4.5:1
- Keyboard navigable
- Screen reader compatible
- Skip navigation links included

---

## 📜 License

MIT License — Free to use, share, and modify.

---

*Built with ♥ for visually impaired students by [@srvelu61-ai](https://github.com/srvelu61-ai)*
