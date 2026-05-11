# Inspo — Juwelier Achim Weidmann (Branche: Juwelier / Goldschmiede)

**Sampling-Modus:** Limited inspo via grid-only sampling. Aus dem Such-Grid auf `https://dribbble.com/search/luxury-jewelry-website` wurden 6 Patterns abgelesen (statt einzelner Shot-Pages), um Recherche-Zeit zu sparen. Synthese ist tragfähig — das Grid liefert für klassische Juwelier-Genres reichlich Material.

## Übergeordnete Richtung

Editorial-luxury, dark, warm — Wiesbadener Kurort-/Casino-Eleganz trifft traditionelles Goldschmiedehandwerk. Im Kontrast zum Schwester-Build `juwelier-weidmann/` (heller Editorial-Look mit Jade) bewusst klassisch-dark mit warmem Bronze/Gold-Akzent. Hero-Bild lebt von der Komposition „kleines Subjekt links, weite dunkle Marmor-Fläche rechts" — Headline-Overlay-Spot ist eingebaut. Typografisch: hohe Serif für Display (Italiana / Cormorant) + ruhige Sans (Inter).

## Referenzen (aus Grid abgelesen)

### 1. „GOLDEN LEGACY"
- URL: dribbble.com/search/luxury-jewelry-website (Grid Reihe 2, Spalte 1)
- Stil: editorial warm-gold serif heritage
- Übernehmen:
  - Großes Wortmark-Display oben über Hero-Bild (Italiana-artige Display-Schrift)
  - Warmer Bronze-Akzent auf neutralem Dunkel statt grellem Gold
- Screenshot: inspo/grid.png

### 2. „Crafting Forever, One"
- URL: dribbble.com/search/luxury-jewelry-website (Grid Reihe 1, Spalte 3)
- Stil: cream-editorial split-layout serif
- Übernehmen:
  - Image-Text-Split-Section mit großer Headline + kurzer Body-Copy + kleinem Text-CTA
  - Atelier-/Werkstatt-Bild rechts, Story links → wird unsere Atelier-Section
- Screenshot: inspo/grid.png

### 3. „Jewellery E-commerce"
- URL: dribbble.com/search/luxury-jewelry-website (Grid Reihe 2, Spalte 3)
- Stil: clean catalog editorial dark
- Übernehmen:
  - Featured-Items als 4-Karten-Grid mit Roman-Numeral-Labels
  - Sehr enge Letter-Spacing-Caps für Produkt-Sub-Labels
- Screenshot: inspo/grid.png

### 4. „Pareto" (Reihe 3)
- URL: dribbble.com/search/luxury-jewelry-website (Grid Reihe 3)
- Stil: minimalist warm-cream type-heavy
- Übernehmen:
  - Lange dünne goldene Trennlinien zwischen Sections (`.gold-line`)
  - Sehr ruhige Section-Paddings, viel Weißraum (hier: Marmor-Raum)
- Screenshot: inspo/grid.png

### 5. „Sneway" / Collection-Explorer (Reihe 3)
- URL: dribbble.com/search/luxury-jewelry-website (Grid Reihe 3, Spalte 1)
- Stil: hovering-cards categorical
- Übernehmen:
  - Kategorien-Grid 3-4-Spalter mit Hover-Reveal + Pillen-Tags
  - Bild + Title + Mikro-Untertitel-Layout
- Screenshot: inspo/grid.png

### 6. „Pearl In Craft / Serene" (Reihe 3)
- URL: dribbble.com/search/luxury-jewelry-website (Grid Reihe 3, Spalte 4)
- Stil: warm-pastel magazine-spread
- Übernehmen (adaptiert auf Dark):
  - Magazin-Spread-Feeling für Featured-Section
  - Pull-Quotes mit Kursiv-Serif zwischen Bildern
- Screenshot: inspo/grid.png

## Konkrete Anpassungen für Phase 6

- **Font-Pair:** `Italiana` (Display, sehr hoch + spaced) + `Cormorant Garamond` (Serif Body-Headlines) + `Inter` (Sans Body + Overlines). Italiana steckt das klassisch-luxuriöse Heritage, Cormorant die Editorial-Eleganz, Inter die Lesbarkeit.
- **Hero-Treatment:** Vorbild „GOLDEN LEGACY" — full-width 21:9 Bild mit großem Display-Mark oben + Overlay-Bar unten mit Tags links + CTA rechts. Inset-Gold-Border (`::after`).
- **Section-Flourishes:**
  - Lange `.gold-line` Trennlinien zwischen Sections (Pareto)
  - Atelier-Split (Crafting Forever, One)
  - Featured-Items mit Roman Numerals (Jewellery E-commerce)
  - Pull-Quote im Atelier-Bereich (Pearl In Craft)
- **Mikro-Interaktionen-Highlights:**
  - Underline-Reveal auf Nav (Default)
  - Ken-Burns auf Hero
  - Hover-Scale auf Gallery (Default)
  - Fade-in-on-scroll via IntersectionObserver (Default)
  - Backdrop-Blur Sticky Header (Default)
- **Farb-Mood-Hinweis:** Warm-bronze Gold auf Marmor-Schwarz mit minimal blau-grauem Hauch. KEIN gelbliches Reines Gold (zu kitschig), sondern Kupfer-Bronze (`#c89548`). KEIN reines Schwarz im Body — der Marmor hat einen blau-kühlen Anteil (`#0a0d13`), damit der warme Gold-Akzent springt.
