# Jazz Lien

**AI Product Engineer · Full-Stack Builder · GCP Authorized Trainer**

I build AI-powered products and ship them.

> [jazzlien.com](https://jazzlien.com/)

---

## About

Foreign languages graduate turned cloud solutions architect turned indie maker. Spent years helping enterprises adopt GCP, then equipped myself with AI tools and knowledge and build products stuck in my head for a lont time. Now I ship AI-powered tools — from video generation to podcast intelligence — end to end.

Open to product engineering, training roles and collaborations on AI tooling.

---

## Featured Projects

### [拾光 Glimmer](https://glimmer.video/) — AI Memorial Videos

Upload photos, pick a theme, get a cinematic video with music. Pay-per-use credits or project-based collaboration via ECPay.

Technical highlights:
- Client-driven polling for Cloudflare Edge, where background tasks die after 30s — enables reliable 2–3 min video generation on a serverless platform
- FFmpeg WASM for in-browser video export with chunked processing — no server upload needed, works on any device
- Unified abstraction across 3 AI video providers with different schemas — swap providers without touching application code

`Next.js 16` `Cloudflare Edge` `Google Gemini` `R2 Storage` `FFmpeg WASM`

### [Podsight](https://podsight.vercel.app/) — Podcast Intelligence

Processes 3 Taiwan finance podcasts daily — 100+ episodes transcribed, summarized, and auto-published to a Telegram channel with zero manual intervention.

Fully automated pipeline: GitHub Actions fires twice daily → Whisper transcription → AI summarization → social-ready drafts for 6 platforms → Telegram push.

`Python` `FastAPI` `Whisper` `Gemini` `GitHub Actions`

### [Articulate](https://github.com/jazzpujols34/articulate-mobile-app) — Vocabulary App

Spaced repetition vocabulary builder with 1,000+ words and root-based decoding. App Store launch Q2 2026.

`React Native` `Expo` `TypeScript`

### [post-to-visual](https://github.com/jazzpujols34/post-to-visual) — Article → Illustrated HTML

Turns any article or post into a single-file, illustrated, easy-read HTML page (圖文好讀版). A pipeline and toolkit, not a template. Open source.

Technical highlights:
- Dependency-free static verifier that catches the bugs hand-review misses — dead anchors, non-absolute Open Graph URLs, dark-mode contrast traps, JPEG bytes in a `.png`
- 8 themeable light/dark-safe SVG diagram recipes plus a palette generator that guarantees white-text contrast ≥4:1 in both themes
- Works with zero API keys (SVG-only mode is first-class); a standalone `p2v` CLI scaffolds, generates, and checks pages

`Python` `Vanilla JS` `SVG` `Claude Code skill`

**Other experiments:** [Jazz Gallery](https://jazz-gallery.onrender.com/) — AI artwork gallery with auth and admin panel &ensp;·&ensp; [Lucky Draw](https://lucky-draw-bice.vercel.app/) — event lottery for company events

> **[Project Presentations](https://jazzpujols34.github.io/jazz-presentations/)** — Slide decks with detailed explanations of each project's architecture and design decisions.

---

## Stack

- **Languages:** TypeScript, Python
- **Frontend:** React, Next.js, React Native, Tailwind CSS
- **Backend:** FastAPI, Node.js, SQLite, Firestore
- **AI:** Claude API, Google Gemini, Whisper, BytePlus Seedance
- **Deploy:** Cloudflare Pages, Vercel, Google Cloud Run, Expo

---

## Connect

[Website](https://jazzlien.com/) · [Presentations](https://jazzpujols34.github.io/jazz-presentations/) · [LinkedIn](https://www.linkedin.com/in/kuan-chieh-lien-0105451b5/)
