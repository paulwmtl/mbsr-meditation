# Brand Guide – MBSR Meditation Andrea Weißmantel

Ein lebendiges Dokument zur visuellen und sprachlichen Identität der Marke. Grundlage: bestehende Website mbsr-meditation.de.

---

## 1. Markenpersönlichkeit

**Charakter in drei Worten:** geerdet · warm · klar.

Die Marke vermittelt Ruhe ohne Esoterik, Fachlichkeit ohne Distanz, Naturverbundenheit ohne Kitsch. Sie steht für eine erwachsene, wissenschaftlich fundierte Achtsamkeitspraxis – ohne Heilsversprechen, ohne Gurutum.

**Kernwerte**

| Wert | Bedeutung |
|---|---|
| **Authentizität** | Persönliche Stimme statt Marketingsprache. „Ich" statt „wir". |
| **Evidenz** | Wissenschaftlich belegt (Studien-Fußnoten, peer-reviewte Quellen). |
| **Ruhe** | Großzügiger Weißraum, gedeckte Farben, keine Reizüberflutung. |
| **Bodenständigkeit** | Konkrete Termine, klare Preise, lokale Verankerung in Groß-Gerau. |

---

## 2. Symbolik – die Hauswurz

Das **Markenbild** ist eine Hauswurz-Pflanze (*Sempervivum*). Sie erscheint als Favicon und als Open-Graph-Vorschaubild auf allen Seiten.

**Warum sie passt**

- Wächst geduldig in unwirtlichen Verhältnissen → Resilienz, Achtsamkeit unter Stress
- Strikte geometrische Rosette → klare Struktur, Ordnung, Konzentration
- Sattes, gedämpftes Grün → Bezug zur Farbpalette der Marke
- Bodenständig, regional, unprätentiös

---

## 3. Farben

Eine reduzierte, harmonische Palette in Salbei- und Olivtönen auf cremigem Hintergrund. Keine knalligen Akzente, keine kalten Blautöne.

### Primärfarben

| Name | Hex | Verwendung |
|---|---|---|
| **Olive** | `#6b7b3a` | Primärfarbe – Buttons, Links, Akzent-Icons |
| **Olive Dark** | `#4a5a28` | Hover-Zustand, Footer-Hintergrund, Headline-Akzent |
| **Sage** | `#becd9c` | Hero-Hintergrund (Verlauf), Logo-Icon, Course-Header |
| **Sage Dark** | `#8a9a5b` | Verlaufs-Endpunkt, Section-Labels |
| **Sage Light** | `#d4dfc0` | Sektion-Hintergründe, Info-Boxen, Icon-Container, Inputs |

### Neutrale Farben

| Name | Hex | Verwendung |
|---|---|---|
| **Cream** | `#faf9f6` | Body-Hintergrund (warmes, leicht beiges Weiß) |
| **White** | `#ffffff` | Karten, Heller Section-Hintergrund |
| **Text Dark** | `#2d2d2d` | H1–H4, wichtige Textelemente |
| **Text Body** | `#444444` | Fließtext |
| **Text Light** | `#666666` | Untergeordnete Texte, Bildunterschriften |

### Farb-Verläufe (Gradients)

- **Hero / Page-Header:** `linear-gradient(135deg, sage → sage-light → cream)`
- **Course-Header / Quote-Sektion:** `linear-gradient(135deg, sage → sage-dark)`

### Faustregel

> **80 % Cream + Weiß, 15 % Salbei-Töne, 5 % Olive-Akzente.**
> Olive-Dark nur sparsam (Footer, dunkle Headlines).

---

## 4. Typografie

Zwei Schriftfamilien, beide **lokal als Variable Fonts** eingebunden (DSGVO-konform, keine Google-Fonts-Verbindung). Variable Fonts liefern alle Gewichte in einer einzigen Datei.

### Schriftpaarung

| Rolle | Schrift | Charakter |
|---|---|---|
| **Headlines** | **Fraunces** (Variable Serif) | Warm, organisch, leicht humanistisch &ndash; geerdet ohne Förmlichkeit |
| **Fließtext / UI** | **Inter** (Variable Sans-Serif) | Klar, neutral-freundlich, optimiert für Bildschirme |

### Schriftgrößen & Gewichte

| Element | Schrift | Größe | Gewicht | Line-Height |
|---|---|---|---|---|
| H1 (Hero) | Fraunces | 3rem (48px) | 700 | 1.3 |
| H1 (Subpages) | Fraunces | 2.8rem (44.8px) | 700 | 1.3 |
| H2 | Fraunces | 2.2rem (35.2px) | 600 | 1.3 |
| H3 | Fraunces | 1.5rem (24px) | 600 | 1.3 |
| Body | Inter | 1rem (16px) | 400 | 1.7 |
| Hero-Subtitle | Inter | 1.2rem (19.2px) | 400 | 1.8 |
| Section-Label | Inter | 0.85rem (13.6px) | 700, UPPERCASE, +1.5px Letter-Spacing | – |
| Buttons | Inter | 1rem | 600 | – |

**Mobile Anpassung:** H1 auf 2rem (480px: 1.8rem), H2 auf 1.7rem.

### Typografie-Regeln

- **Body-Zeilenhöhe immer 1.7+** – nie eng setzen, Atemraum ist Teil der Marke.
- **Headlines in `--text-dark`** (`#2d2d2d`), nicht reines Schwarz.
- **Italic** nur in Zitaten und Zwischenhinweisen (`<em>`) – Fraunces hat eine ausdrucksstarke Kursive, sparsam einsetzen.
- **Niemals fett UND uppercase UND farbig** – maximal zwei Hervorhebungen kombinieren.

---

## 5. Formen und Geometrie

Die Marke arbeitet mit **runden, weichen Kanten** – keine harten 90°-Ecken außerhalb von Tabellenstrukturen.

### Border-Radius-System

| Wert | Verwendung |
|---|---|
| `6px` | Navigation-Items |
| `8px` | Buttons, Form-Inputs |
| `12px` | Symptom-Karten, Icon-Container, Info-Boxen (rechte Seite) |
| `16px` | Benefit-Cards, Course-Cards, Split-Bilder |
| `20px` | Hero-Bild, Badges (pill-förmig) |
| `50%` | Logo-Icon (perfekter Kreis) |

### Schatten

Subtile, weiche Schatten – nie hart oder dramatisch.

```
--shadow: rgba(0, 0, 0, 0.08);  /* Standard */
0 4px 20px var(--shadow)         /* Karten */
0 10px 40px var(--shadow)        /* Hover-Lift */
0 20px 60px rgba(0,0,0,0.15)     /* Hero-Bild (etwas tiefer) */
```

### Bewegung

- **Hover-Lift:** `transform: translateY(-2px)` (Buttons) bzw. `-4px` (Karten).
- **Übergänge:** durchgehend `0.3s ease`. Keine sprunghaften Animationen.
- **Scroll-Animation:** `.fade-in` (opacity 0→1 + 20px Translate) – 0.6 s.

---

## 6. Komponenten-Sprache

### Buttons

- **Primär:** olivgrün gefüllt, weißer Text, weiche Schatten beim Hover.
- **Sekundär:** transparent mit olivgrünem Rand (2 px), füllt sich beim Hover.
- Pfeil-Glyph `→` als Vorwärts-Indikator (z. B. „Nächster Kurs →").

### Karten

- **Benefit-Cards:** weiß, zentriert, runder Sage-Light-Icon-Container.
- **Course-Cards:** weiß mit grünem Verlaufs-Header (Titel + Datum).
- **Info-Boxen:** Sage-Light-Hintergrund mit 4 px Olive-Border-Left – wie ein Zitat.

### Icons

- **Emoji-basiert** – warm, niedrigschwellig (🧘 💆 🌱 ❤️ 🛡️ 📅 📍).
- Eingefasst in Sage-Light-Container (12 px oder 16 px Radius).
- Niemals geometrische Outline-Icons mischen.

### Listen

- Bullets durch `•` (oliv) oder Häkchen `✓` (oliv) ersetzt – nie Standard-Discs.

---

## 7. Bildwelt

### Bildmotive (Soll-Zustand)

- **Naturnah, weich, ruhig:** Pflanzen, natürliche Texturen, Steine, Holz.
- **Atmosphärisch statt darstellerisch:** keine grell ausgeleuchteten Stockfotos.
- **Authentisch persönlich:** ein echtes Porträt-Foto von Andrea Weißmantel statt generischer Symbolbilder.

### Bildbehandlung

- Abgerundete Ecken (16–20 px), weiche Schatten.
- Gedämpfte Sättigung – passend zur Salbei-/Cream-Palette.
- **Keine externen Bild-CDNs** (DSGVO) – alle Bilder lokal hosten.

---

## 8. Stimme und Tonalität

### Anrede

**„Sie"** – freundlich-formell, respektvoll. Niemals Du.
**„Ich"** für die Kursleiterin – persönlich, nicht „wir" / „unser Team".

### Tonale Leitplanken

| ✅ Wir sind | ❌ Wir sind nicht |
|---|---|
| ruhig, klar, warm | reißerisch, marketingschwer |
| evidenzbasiert (Studien, Zahlen) | esoterisch, mystifizierend |
| persönlich („mein Anliegen") | unpersönlich, distanziert |
| konkret (Termine, Preise, Orte) | vage, „bald", „demnächst" |
| respektvoll im Versprechen | Heils- oder Heilungsversprechen |

### Wortschatz

**Bevorzugt verwenden**
finden · erfahren · entdecken · lernen · wahrnehmen · erkennen · einladen · begleiten · vermitteln · Praxis · Haltung · Erfahrung · Gegenwart · Achtsamkeit

**Vermeiden**
„revolutionär", „lifechanging", „in nur 8 Wochen zu …", „endlich stressfrei", „Geheimnis", „Hack", „Game-Changer", übermäßige Ausrufezeichen.

### Satzbau

- Kurze bis mittlere Sätze.
- Aktive Sprache: „Sie lernen …" statt „Es wird gelernt …".
- Keine Schachtelsätze über drei Zeilen.
- Listen nutzen, wenn drei oder mehr Punkte aufeinanderfolgen.

### Beispiele aus der bestehenden Website

> ✅ „Mein Anliegen ist es, die Haltung der Achtsamkeit erfahrbar zu machen und in alle Lebensbereiche zu integrieren."
>
> ✅ „Finden Sie innere Ruhe und Gelassenheit mit MBSR – dem wissenschaftlich fundierten Programm zur Stressreduktion."
>
> ✅ „Eine Meta-Analyse von Khoury et al. (2015) wertete 29 Studien mit 2.668 Teilnehmenden aus und stellte für MBSR große Effektstärken bei der Stressreduktion fest."

### Umgang mit MBSR-Fachbegriffen

Englische Termini wie *Body Scan*, *Mindfulness*, *Mindfulness-Based Stress Reduction* werden **kursiv oder beim ersten Vorkommen erklärt**. Keine Übersetzung, wenn der englische Begriff Standard ist.

### Zitate

Zitate (z. B. Thich Nhat Hanh, Britta Hölzel) werden in der quote-section in **Fraunces Italic, 1.5 rem, weiß auf Salbei-Verlauf** gesetzt. Sie sind seltene Höhepunkte – sparsam einsetzen.

---

## 9. Layout-Prinzipien

- **Max-Width 1200 px** für Hauptcontainer, **800 px** für Lesetexte.
- **Section-Padding:** 80 px vertikal (50 px mobil).
- **Großzügiger Weißraum** – Sektionen wechseln Cream-/Weiß-/Sage-Light-Hintergründe ab.
- **Grid-basiert:** häufig zwei- oder dreispaltig auf Desktop, einspaltig mobil.

---

## 10. Barrierefreiheit & DSGVO

Diese Punkte sind Teil der Marke – sie kommunizieren Sorgfalt und Vertrauen.

- **Skip-Link** zum Hauptinhalt
- **Korrekte ARIA-Labels** für Navigation, Hamburger, FAQ
- **Schema.org-Daten** für lokale Suche (Course, LocalBusiness, Person)
- **Lokale Schriften** (kein Google Fonts)
- **Lokale Bilder** (kein Unsplash-CDN)
- **Hosting transparent** in der Datenschutzerklärung

---

## 11. Don'ts

- **Keine** Stockfotos lächelnder Menschen am Laptop.
- **Keine** kalten Blau-/Grautöne.
- **Keine** Sans-Serif-Headlines (Fraunces ist obligatorisch).
- **Keine** Buzzwords wie „transformativ", „lebensverändernd".
- **Keine** harten 90°-Ecken in primären Komponenten.
- **Kein** „Wir-Plural", wenn nur eine Person dahinter steht.
- **Keine** externen Tracker, Analytics-Tools oder Embedded-Player ohne Consent.

---

## 12. Quick Reference – Design-Tokens

```css
/* Farben */
--sage: #becd9c;
--sage-light: #d4dfc0;
--sage-dark: #8a9a5b;
--olive: #6b7b3a;
--olive-dark: #4a5a28;
--cream: #faf9f6;
--white: #ffffff;
--text-dark: #2d2d2d;
--text-body: #444444;
--text-light: #666666;

/* Schriften (lokal als Variable Fonts) */
--font-heading: 'Fraunces', Georgia, serif;
--font-body: 'Inter', 'Segoe UI', Arial, sans-serif;

/* Layout */
--max-width: 1200px;
--section-padding: 80px 0;
--shadow: rgba(0, 0, 0, 0.08);
```
