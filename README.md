# Jazz Lien

**AI Product Engineer · Full-Stack Builder · GCP Authorized Trainer**

I build AI-powered products and ship them.

> [jazzlien.com](https://jazzlien.com/)

---

## About

Foreign languages graduate turned cloud solutions architect turned indie maker. Spent years helping enterprises adopt GCP, then equipped myself with AI tools and knowledge and built products stuck in my head for a long time. Now I ship AI-powered tools — from video generation to podcast intelligence — end to end, and open-source the developer tooling I build for Claude Code along the way.

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

### [Podsight](https://podsight.tw/) — Podcast Intelligence

Processes 3 Taiwan finance podcasts daily — 100+ episodes transcribed, summarized, and auto-published to a Telegram channel with zero manual intervention.

Fully automated pipeline: GitHub Actions fires twice daily → Whisper transcription → AI summarization → social-ready drafts for 6 platforms → Telegram push.

`Python` `FastAPI` `Whisper` `Gemini` `GitHub Actions`

### [Articulate](https://github.com/jazzpujols34/articulate-mobile-app) — Vocabulary App

Spaced repetition vocabulary builder with 1,000+ words and root-based decoding. App Store launch Q2 2026.

`React Native` `Expo` `TypeScript`

**Other experiments:** [Jazz Gallery](https://jazz-gallery.onrender.com/) — AI artwork gallery with auth and admin panel &ensp;·&ensp; [Lucky Draw](https://lucky-draw-bice.vercel.app/) — event lottery for company events

> **[Project Presentations](https://jazzpujols34.github.io/jazz-presentations/)** — Slide decks with detailed explanations of each project's architecture and design decisions.

---

## Open Source — Claude Code Tooling

I don't just use Claude Code — I build and open-source the tooling around it. Three repos, from individual skills to the conventions that keep an AI pair-programmer reliable across sessions.

### [claude-skills](https://github.com/jazzpujols34/claude-skills) — Curated drop-in skills

Self-contained skills for Claude Code, each pulled from real production work and stripped of anything personal. Copy a folder, and the agent picks it up.

Technical highlights:
- A publish gate (`check-skill.sh`) scans every skill for hardcoded secrets and personalization before it ships — nothing reaches users pointing at private paths or keys
- Generated catalog (`catalog.json` + README) that can't drift from the skills; `AGENTS.md` + `llms.txt` make the repo machine-readable for AI tools
- 11 skills across the full build → ship → grow arc: SVG diagrams, test-first discipline, bounded goal-driven execution, debug-loop breaking, teaching mode, in-page annotation, browser-verify UI changes end-to-end, secret scanning, deploy checks, SEO, growth

`Bash` `Python` `Claude Code skills` `Open source`

### [post-to-visual](https://github.com/jazzpujols34/post-to-visual) — Article → illustrated HTML

Turns any article or post into a single-file, illustrated, easy-read HTML page (圖文好讀版). A pipeline and toolkit, not a template.

Technical highlights:
- Dependency-free static verifier that catches the bugs hand-review misses — dead anchors, non-absolute Open Graph URLs, dark-mode contrast traps, JPEG bytes in a `.png`
- 8 themeable light/dark-safe SVG diagram recipes plus a palette generator that guarantees white-text contrast ≥4:1 in both themes
- Works with zero API keys (SVG-only mode is first-class); a standalone `p2v` CLI scaffolds, generates, and checks pages

`Python` `Vanilla JS` `SVG` `Claude Code skill`

### [claude-code-workflow](https://github.com/jazzpujols34/claude-code-workflow) — The system layer

Conventions, templates, and decision frameworks (CLAUDE.md, session handover, file-based memory, hooks) so context compounds across sessions instead of resetting to zero. Refined across 12+ shipped projects.

`Claude Code` `Hooks` `Memory` `Open source`

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
