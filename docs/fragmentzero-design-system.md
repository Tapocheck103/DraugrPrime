# FragmentZero Design System

This document outlines the core design principles, tools, and practices behind the FragmentZero cinematic web experience.

---

## 🎨 Visual Language

- **Cinematic UI**: Everything is styled with filmic depth — shadows, glows, and subtle motion.
- **Desaturated urban palette**: Greys, teals, and soft oranges dominate.
- **Iconography**: Based on clean glyphs or thin-line futurism (custom-designed where possible).
- **Layout Rhythm**: Vertical pacing between visuals, chapters, and paragraphs to support narrative clarity.

---

## 🧱 Code & Architecture

- Fully handcrafted HTML/CSS — no site builders or frameworks.
- Modular structure with folders for each chapter, image, and page.
- Semantic HTML for accessibility and long-term maintainability.
- CSS organized for reusability: shared utility classes, hover states, and transitions.

---

## 🧠 JavaScript Usage

- **No frameworks** (no React, Vue, jQuery, etc.)
- **Vanilla JavaScript only** — kept lightweight and purposeful.
- Used for:
  - Scroll-triggered reveals
  - Ambient effects like data rain
  - Minor interactivity (e.g. expand bios, glitch pulses)
- Kept at the end of pages or deferred for performance

---

## 🎞️ Animation Philosophy

- **CSS-first animations**: Fade-ins, transitions, soft scaling
- **Scroll-based animation triggers**: For chapters, panels, and character reveals
- **Atmosphere over flash**: Motion enhances immersion but never distracts

---

## 📂 Directory Snapshot

/FragmentZero/
├── DraugrPrime/                         # GitHub profile repo
│   ├── README.md
│   ├── draugrprime-banner-github.jpg
│   └── /docs/
│       ├── getting-started.md
│       └── fragmentzero-design-system.md
│
├── fragment-zero/                       # Main website project repo
│   ├── index.html
│   ├── digital-book.html
│   ├── Chapter0MemorySeed.html
│   ├── Prologue.html
│   ├── Fragment-Runner.html
│   ├── LICENSE
│   ├── favicon.ico
│   ├── og-image.jpg
│   ├── draugrprime-banner-github.jpg
│   ├── /Images/
│   └── README.md
│
└── FragmentZeroUpdate.zip              # Backup archive (manual export)

---

## 💡 Future Expansions

- Custom `<fragment-panel>` HTML tag (Web Component)
- Editable visual timeline for chapter animation
- Internal design token system (colors, spacing, z-indexes)

---

> This system is designed to be scalable, cinematic, and immersive — no matter how many chapters FragmentZero expands into.