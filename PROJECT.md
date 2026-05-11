# Juwelier Achim Weidmann (Dark Gold Marble Build)

**Slug:** juwelier-weidmann-2 (lokal) / juwelier-weidmann-3 (Repo + Pages)
**Branche:** Juwelier (Goldschmiede, Trauringe, Verlobungsringe, Farbsteine, Perlen)
**Build-Datum:** 2026-05-11
**Live-URL:** https://adamanm780-dotcom.github.io/juwelier-weidmann-3/
**Repo:** https://github.com/adamanm780-dotcom/juwelier-weidmann-3
**Lokal:** C:/Users/Adria/claude-discord-projects/allgemein/juwelier-weidmann-2

## Hinweis zur Adresse / Slug-Differenz
- User-Input: `!build Juwelier Weidmann Burgstraße 77` → korrekte Adresse ist **Burgstr. 3**, nicht 77 (User-Tippfehler, in research.md dokumentiert).
- Es existiert bereits ein älterer FlowState-Build unter `juwelier-weidmann/` (heller Editorial-Look, jade Akzent, Build vom 2026-05-03). Dieser neue Build ist bewusst kontrastierend: dark, classical-luxury, warmer Bronze-Gold.
- Lokaler Ordner-Slug `juwelier-weidmann-2` ist via Workflow-Iteration entstanden (Phase 0). Repo-/Pages-Slug auf `juwelier-weidmann-3` iteriert, weil das Repo `-2` bereits anderweitig belegt war.

## Kontakt
- Adresse: Burgstraße 3, 65183 Wiesbaden (Wiesbaden Mitte, Fußgängerzone Mauritiusplatz)
- Telefon: +49 611 374 280
- E-Mail: n/a (Platzhalter `info@juwelier-weidmann.de` im HTML)
- Öffnungszeiten: Di–Fr 10:00–18:30 · Sa 10:00–16:00 · So+Mo geschlossen
- Website (Original): n/a
- Instagram: n/a

## Design
- Palette:
  - `--bg-deep:#040608` (Topbar, Footer, Contact)
  - `--bg:#0a0d13` (Body, dunkler Marmor-Body mit blau-kühlem Anteil)
  - `--bg-raised:#141a1f` (Categories, Atelier — Section-BG)
  - `--bg-elevated:#1d242a` (Karten/Featured)
  - `--accent:#c89548` (warm-bronze Gold, Hauptakzent vom Ring)
  - `--accent-light:#e8c98a` (Hover, Highlights)
  - `--accent-dark:#8b6324` (tiefes Bronze)
  - `--ivory:#f0eadd` (Display-Text, Headlines)
  - `--cream:#d9cfba` (Body-Copy)
  - `--muted:#6e6457` (Sub-Labels, desaturiert warm)
- Fonts: Italiana (Display) + Cormorant Garamond (Serif Headlines) + Inter (Sans Body)
- Style-Richtung: editorial-luxury, dark, classical European jeweler, warm bronze/gold auf Marmor-Schwarz, Heritage-Mood (Est. 1894), Wiesbadener Kurort-Eleganz

## Assets
- Hero: assets/hero.webp (Nano Banana 21:9 → Real-ESRGAN 4K → 6144×2688 → WebP 178K) + hero.jpg Fallback (1920×840, 62K)
- Maps-Fotos: 0 (n/a — kein reichhaltiges Google-Profil, in research.md dokumentiert)
- Insta-Posts: 0 (n/a — kein Instagram-Handle gefunden)
- Zusatz-Assets (alle Nano Banana, matching dark marble palette):
  - assets/about.webp (864×1184, Goldschmied-Hände am Werkbank, 3:4)
  - assets/detail-01.webp (1248×832, 3 Brillanten + Gold-Band auf Marmor, 3:2)
  - assets/detail-02.webp (1024×1024, Perlenkette auf Marmor-Sockel, 1:1)
  - assets/detail-03.webp (896×1152, Trauringe in Walnuss-Etui, 4:5)
  - assets/texture.webp (1344×768, dark marble texture, Section-Backgrounds, 16:9)
- Scroll-Frames: 50 × WebP (assets/scroll/frames-clean/, je ~24K, 960×960) — Ring 3/4-Profil → Frontalansicht. Source: Seedance 1-Pro (5s/24fps/1080p, fallback wegen Seedance 2.0 nicht öffentlich verfügbar). Start/End-Frames: Nano Banana Greenscreen (pastellgrün #96ba87, ffmpeg colorkey similarity=0.18 blend=0.08). Source-Video assets/scroll/source.mp4 + Greenscreen-Stills assets/scroll/frame-start/end.png im Repo

## Build-Stats
- Build-Zeit: ~10 min (von !build bis Pages-Push)
- Sections im HTML: 10 (Topbar, Header, Hero, Intro, Categories, Featured, Atelier, Detail-Grid, Contact, Footer)
- HTML: single-file mit inline CSS+JS, ~485 Zeilen

## Updates
- 2026-05-11: Initial Build (dark marble palette mit warm-bronze gold, Italiana display, Cormorant serif). Lokaler Slug `-2`, Repo/Pages `-3` (Iteration wegen belegtem Repo-Namen). Adresse korrigiert von User-Input „77" auf korrektes „3".
- 2026-05-11: !buildscroll dranhängt — Scroll-Frame-Animation (50 Frames Solitaire-Ring 3/4 → frontal) via Seedance 1-Pro (Fallback, Seedance 2.0 nicht verfügbar) + ChatGPT-Replacement via Nano Banana Greenscreen-Pair + ffmpeg colorkey-Workflow.
