# PKI & TLS — Presentation

**"How Your Browser Trusts the Server"**  
Sertkaya Bilgehan · Wiegel Paulina · Kargl Tim · May 26, 2026

---

## Setup (30 seconds)

No Node, no npm, no build step required.

```bash
git clone <repo-url>
cd pki-tls-praesi
# Double-click index.html   — or:
open index.html
```

Works fully offline — everything (Reveal.js, fonts) is bundled locally in the repo.

---

## Controls

| Key | Action |
|-----|--------|
| `→` / `Space` | next slide |
| `←` | previous slide |
| `F` | fullscreen |
| `S` | Speaker View (notes + timer) |
| `O` | slide overview |
| `B` | blackout screen (pause) |

**Speaker View** opens a second window with speaker notes and a timer. Run the main window on the projector, keep the laptop showing the notes window.

> **Note:** Speaker View requires a local server. Start one with:
> ```bash
> python3 -m http.server 8765
> ```
> Then open `http://localhost:8765` in Chrome.

---

## PDF Export (Backup)

If the laptop fails at the venue:

1. Open `index.html` in **Chrome** or **Chromium**
2. Append `?print-pdf` to the URL:  
   `file:///…/pki-tls-praesi/index.html?print-pdf`
3. `Cmd+P` → **Save as PDF** → Margins: None, Background graphics: ✓
4. Done — all 15 slides as a printable PDF

---

## Project Structure

```
pki-tls-praesi/
├── index.html          ← presentation (all 15 slides + speaker notes)
├── css/
│   └── custom.css      ← design (Navy/Gold palette, typography)
├── fonts/              ← Fraunces, Inter, JetBrains Mono (offline, woff2)
├── vendor/
│   └── reveal.js/      ← Reveal.js 6 (local, no CDN)
└── README.md
```

---

## Talk Structure (~15 minutes)

| Part | Speaker | Slides | Time |
|------|---------|--------|------|
| The Problem | Sertkaya Bilgehan | 3–6 | ~4 min |
| The Solution: PKI | Wiegel Paulina | 7–10 | ~5 min |
| TLS in Action | Kargl Tim | 11–14 | ~5 min |
| Title / Agenda / Outro | all | 1, 2, 15 | ~1 min |
