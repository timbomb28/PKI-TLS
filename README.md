# PKI & TLS — Präsentation

**„Wie dein Browser dem Server vertraut"**  
Sertkaya Bilgehan · Wiegel Paulina · Kargl Tim · 26. Mai 2026

---

## Setup (30 Sekunden)

Kein Node, kein npm, kein Build-Step nötig.

```bash
git clone <repo-url>
cd pki-tls-praesi
# Doppelklick auf index.html   — oder:
open index.html
```

Funktioniert offline — alles (Reveal.js, Fonts) liegt lokal im Repo.

---

## Präsentation steuern

| Taste | Aktion |
|-------|--------|
| `→` / `Space` | nächste Folie |
| `←` | zurück |
| `F` | Vollbild |
| `S` | Speaker View (Notizen + Timer) |
| `Esc` | Übersicht aller Folien |
| `B` | Bildschirm schwärzen (Pause) |

**Speaker View** öffnet ein zweites Fenster mit Sprecher-Notizen und einem Timer. Auf dem Beamer läuft das Hauptfenster, der Laptop zeigt die Notizen.

---

## PDF-Export (Backup)

Falls der Laptop beim Vortrag nicht funktioniert:

1. Öffne `index.html` in **Chrome** oder **Chromium**
2. Füge `?print-pdf` an die URL an:  
   `file:///…/pki-tls-praesi/index.html?print-pdf`
3. `Cmd+P` → **Als PDF speichern** → Ränder: Keine, Hintergrundgrafiken: ✓
4. Fertig — alle 15 Folien als druckbares PDF

---

## Struktur

```
pki-tls-praesi/
├── index.html          ← Präsentation (alle 15 Folien)
├── css/
│   └── custom.css      ← Design (Navy/Gold-Palette, Fonts)
├── fonts/              ← Fraunces, Inter, JetBrains Mono (offline)
├── vendor/
│   └── reveal.js/      ← Reveal.js 6 (lokal, kein CDN)
└── README.md
```

---

## Vortragsaufteilung (~15 Minuten)

| Teil | Sprecher | Folien | ~Zeit |
|------|----------|--------|-------|
| Das Problem | Sertkaya Bilgehan | 3–6 | 4 min |
| Die Lösung: PKI | Wiegel Paulina | 7–10 | 5 min |
| TLS in Aktion | Kargl Tim | 11–14 | 5 min |
| Titel / Agenda / Abschluss | alle | 1, 2, 15 | 1 min |
