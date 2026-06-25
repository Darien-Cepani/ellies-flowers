# Anja's Flowers — Brand Guidelines

## 1. Brand Identity
Anja's Flowers is a classic, warm, garden-fresh florist in the heart of Tirana. The brand is built on abundant roses, tulips, and mixed seasonal bouquets, hand-crafted fresh every morning. Where many flower brands lean cool and minimal, Anja's leans into warmth: coral and terracotta tones, generous blooms, and a friendly, timeless welcome.

* **Brand Personality:** Classic, warm, friendly, timeless, and generous.
* **Core Vibe:** A sun-warmed garden in full bloom — coral and terracotta hues, abundant roses and tulips, and the unhurried elegance of a neighbourhood atelier you return to year after year.
* **Promise:** Hand-crafted fresh daily, with same-day delivery across Tirana.
* **Instagram:** [@anjasflowers](https://instagram.com/anjasflowers)
* **Location:** Sheshi Wilson, Tirana, Albania.

---

## 2. Logo
The primary logo pairs a warm garden-bloom mark with the wordmark **ANJA'S** set in widely tracked Montserrat-style capitals.

* **Mark:** A coral rose/garden bloom (`#C56B5A`) with deeper terracotta detail (`#9E4031`).
* **Wordmark:** `ANJA'S` in uppercase, generously letter-spaced, in warm ink (`#2B1A16`).
* **Tagline lock-up:** `FLOWERS & ROSES · TIRANA` in terracotta (`#9E4031`), sitting beneath a thin hairline rule.
* **Clear space & background:** The logo lives on the soft warm-cream background (`#FBF3EC`). Preserve generous clear space around the mark; never crowd the wordmark.
* **Asset:** `Brand/logo.svg` (≈520×260).

---

## 3. Color Palette
A warm coral & terracotta garden palette, token-based across the site (Tailwind `brand.*`).

| Token | Hex | Role |
| --- | --- | --- |
| `brand.dark` | `#2B1A16` | Primary ink / body text |
| `brand.night` | `#1A0F0C` | Deepest backgrounds (loader, hero, footer) |
| `brand.gold` | `#C56B5A` | Signature accent — warm coral |
| `brand.deep` | `#9E4031` | Darker accent for text & hairlines on white |
| `brand.champagne` | `#FBF3EC` | Soft warm-cream section background |
| `brand.red` | `#A3382B` | Highlight / notification accent |
| — | `#FFFFFF` | Primary page background |

---

## 4. Typography (Google Fonts)
A classic serif voice warmed by clean, modern sans-serifs.

* **Display & Headlines:** **`Cormorant Garamond`** — an elegant, romantic serif for hero titles, section headings, and editorial quotes.
* **Logo, Eyebrows & UI Labels:** **`Montserrat`** — uppercase, widely tracked, for the wordmark, navigation, taglines, and buttons.
* **Body & Interface Text:** **`Inter`** — clean, highly legible, and modern for paragraphs and small UI text.

---

## 5. Website Style & Layout
The site reads like a warm, editorial extension of the shop — abundant, friendly, and timeless.

* **Hero:** Full-screen floral video with warm legibility overlays, a coral eyebrow, and a `Cormorant Garamond` headline.
* **Navigation:** Sticky top bar — transparent over the hero, morphing to solid white with a champagne hairline on scroll.
* **Marquee:** An infinite-scrolling band on the warm-cream background tying the page together.
* **Collections Grid:** Editorial cards for bouquets, roses, arrangements, and weddings with gentle hover lift and image zoom.
* **Visit & Map:** A desaturated, warm-toned map with a custom coral marker pinned at Sheshi Wilson, Tirana.
* **Footer:** Spacious, with shop hours, collections, and a newsletter ("Bloom Club") signup.
* **Bilingual:** Every UI string is available in English (`en`) and Albanian (`sq`).

---

## 6. Technical Implementation
A high-performance, animated React prototype.

* **Framework:** React via Vite.
* **Styling:** Tailwind CSS, fully token-based (`brand.*` colour system).
* **Animations:** GSAP (GreenSock) + `@gsap/react` — page-load reveals and `ScrollTrigger` parallax/fade-ins.
* **Map:** Leaflet + OpenStreetMap tiles, desaturated to match the warm editorial aesthetic.
* **Icons:** `lucide-react` for clean, minimalist SVG icons.
