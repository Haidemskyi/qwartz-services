# QWARTZ SERVICES — OFFICIAL BRAND BOOK
### Qwartz LLC · Version 1.0 · 2025

---

> **Document Purpose:** This Brand Book defines the visual identity, communication standards, and design language for Qwartz Services (legal entity: Qwartz LLC). It is intended for use by developers, designers, and marketing agencies. All visual decisions must align with the standards defined herein.

---

## 01 — BRAND ESSENCE

### Mission
To provide homeowners, renters, and small businesses with a single, reliable point of contact for moving, furniture assembly, and IT support — delivered by a licensed, accountable LLC.

### Core Values

| Value | Expression |
|-------|-----------|
| **Reliability** | We show up. Every time. On time. |
| **Transparency** | Flat pricing. No hidden fees. No jargon. |
| **Efficiency** | One call. All services. Zero runaround. |
| **Accountability** | Licensed, insured, professionally responsible. |

### Brand Personality
**Confident · Professional · Approachable · Trustworthy**

Qwartz is not a faceless corporation. It's a real, licensed business run by real people — but with the polish and reliability of an enterprise service. The brand speaks directly, avoids fluff, and backs every claim with action.

### Positioning Statement
> *"Qwartz LLC is the all-in-one service company for people who need the job done right — without the chaos of juggling multiple vendors."*

---

## 02 — LOGO GUIDELINES

### Logo Anatomy
The Qwartz wordmark is set in a **Geometric Sans-Serif** typeface (Inter Black / 900 weight) with tight letter-spacing (`-0.03em`). The logo features a **blue accent dot** placed after the wordmark — serving as both a punctuation mark and a visual symbol of precision and finality.

```
  Qwartz.
  ───────┘
         └── Accent dot: #3B82F6 (Electric Blue)
             Wordmark: #FFFFFF on dark backgrounds
```

### The Dot — Design Intent
The **blue dot (`.`)** is not decoration. It signals:
- **Completeness** — "The job is done."
- **Precision** — A single, deliberate mark.
- **Brand recognition** — The dot is the brand's most compressed identifier.

### Logo Variants

| Variant | Usage |
|---------|-------|
| `Qwartz.` (White + Blue dot) | Primary — use on all dark backgrounds |
| `Qwartz.` (Dark + Blue dot) | Inverted — use on light/white backgrounds |
| `Q.` (Monogram) | App icons, favicons, social profile images |

### Clear Space Rule
Maintain a minimum clear space equal to the **height of the capital "Q"** on all four sides of the logo. Never place other logos, text, or graphic elements within this zone.

### Minimum Size
- **Digital:** 120px wide minimum
- **Print:** 30mm wide minimum

### Logo Don'ts
- ❌ Do not stretch or distort the wordmark
- ❌ Do not change the blue dot to any other color
- ❌ Do not use on a mid-tone background where contrast is less than 4.5:1
- ❌ Do not add drop shadows or effects to the wordmark
- ❌ Do not use the logo without the dot

---

## 03 — COLOR PALETTE

### Primary Colors

#### Deep Midnight (Primary Background)
The foundational dark color. Used for page backgrounds, navbar, and footer.

| Format | Value |
|--------|-------|
| **HEX** | `#060E1E` |
| **RGB** | `rgb(6, 14, 30)` |
| **HSL** | `hsl(222, 67%, 7%)` |
| **CMYK** | `C: 80% M: 53% Y: 0% K: 88%` |
| **CSS Token** | `--blue-950` |

---

#### Navy Core (Secondary Background)
Section backgrounds, cards, overlays.

| Format | Value |
|--------|-------|
| **HEX** | `#0A1628` |
| **RGB** | `rgb(10, 22, 40)` |
| **HSL** | `hsl(220, 60%, 10%)` |
| **CMYK** | `C: 75% M: 45% Y: 0% K: 84%` |
| **CSS Token** | `--blue-900` |

---

#### Card Blue (Surface)
Form backgrounds, service cards, modals.

| Format | Value |
|--------|-------|
| **HEX** | `#0D1F3C` |
| **RGB** | `rgb(13, 31, 60)` |
| **HSL** | `hsl(220, 64%, 14%)` |
| **CMYK** | `C: 78% M: 48% Y: 0% K: 76%` |
| **CSS Token** | `--blue-800` |

---

### Accent Colors

#### Electric Blue (Primary Accent) ⭐
The brand's signature accent. Used for CTAs, links, highlights, icons, and the logo dot.

| Format | Value |
|--------|-------|
| **HEX** | `#3B82F6` |
| **RGB** | `rgb(59, 130, 246)` |
| **HSL** | `hsl(217, 91%, 60%)` |
| **CMYK** | `C: 76% M: 47% Y: 0% K: 4%` |
| **CSS Token** | `--accent` / `--blue-300` |

---

#### Royal Blue (Button / Interactive)
Primary button fill. Hover states, gradients.

| Format | Value |
|--------|-------|
| **HEX** | `#2563B8` |
| **RGB** | `rgb(37, 99, 184)` |
| **HSL** | `hsl(217, 68%, 43%)` |
| **CMYK** | `C: 80% M: 46% Y: 0% K: 28%` |
| **CSS Token** | `--blue-400` |

---

#### Deep Royal (Button Base)
CTA button base color in gradients.

| Format | Value |
|--------|-------|
| **HEX** | `#1E4D91` |
| **RGB** | `rgb(30, 77, 145)` |
| **HSL** | `hsl(216, 65%, 34%)` |
| **CMYK** | `C: 79% M: 47% Y: 0% K: 43%` |
| **CSS Token** | `--blue-500` |

---

### Neutral / Text Colors

| Name | HEX | Usage |
|------|-----|-------|
| White | `#FFFFFF` | Primary text, headings |
| Slate 300 | `#CBD5E1` | Secondary text, body |
| Slate 400 | `#94A3B8` | Subtitles, descriptions |
| Slate 500 | `#64748B` | Placeholders, disabled |
| Slate 600 | `#475569` | Muted text, captions |

---

### Semantic / Special Colors

| Name | HEX | Usage |
|------|-----|-------|
| Gold / Amber | `#F59E0B` | Trust badges, star ratings, premium markers |
| Accent Glow | `rgba(59,130,246,0.25)` | Box shadows, focus rings, glow effects |

---

### Color Usage Rules

```
Dark background sections:   --blue-950 to --blue-900
Card surfaces:              --blue-800 with border rgba(59,130,246,0.15)
CTA buttons:                gradient(135deg, --blue-500, --blue-400)
Text on dark:               --white (primary), --slate-300/400 (secondary)
Accent highlights:          --blue-300 / --accent (#3B82F6)
```

---

## 04 — TYPOGRAPHY SYSTEM

### Font Family
**Primary:** Inter (Google Fonts)
**Fallback:** `-apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif`

```html
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800;900&display=swap" rel="stylesheet">
```

**Why Inter?**
Inter is a Geometric Sans-Serif designed for screens. Its optical clarity at all sizes, wide range of weights (300–900), and open letterforms align perfectly with Qwartz's modern, professional identity.

---

### Type Scale

| Style | Size | Weight | Line Height | Color | Usage |
|-------|------|--------|-------------|-------|-------|
| **H1** | `clamp(40px, 6vw, 72px)` | 900 (Black) | 1.1 | `--white` | Hero title |
| **H2** | `clamp(28px, 4vw, 42px)` | 800 (ExtraBold) | 1.18 | `--white` | Section titles |
| **H3** | `18–22px` | 800 (ExtraBold) | 1.3 | `--white` | Card titles |
| **H4** | `16–18px` | 700 (Bold) | 1.4 | `--white` | Sub-headings |
| **H5** | `14–15px` | 700 (Bold) | 1.5 | `--slate-300` | Labels, eyebrows |
| **H6** | `12px` | 700 (Bold) | 1.5 | `--blue-300` | Section labels (uppercase, tracked) |
| **Body** | `15–17px` | 400 (Regular) | 1.65–1.75 | `--slate-400` | Paragraphs, descriptions |
| **Body SM** | `13–14px` | 400 (Regular) | 1.6 | `--slate-500` | Captions, disclaimers |
| **Button** | `16px` | 700 (Bold) | 1 | `--white` | CTA buttons |
| **Button SM** | `14px` | 600 (SemiBold) | 1 | `--white` | Secondary buttons, links |
| **Label** | `12px` | 700 (Bold) | 1 | `--blue-300` | Uppercase, `letter-spacing: 0.14em` |

---

### Special Typographic Rules

- **Section Labels:** Always uppercase, tracked at `0.14em`, preceded by a `22px × 2px` blue line rule
- **Hero H1:** Two-tone — first line `--white`, accent word `--blue-300`
- **Highlighted spans:** Blue accent color `--blue-300` used inside H2s for the emphasized word
- **Letter spacing:** `-0.03em` on logo/brand name only; neutral on body copy

---

## 05 — UI / UX VISUAL LANGUAGE

### Button System

#### Primary CTA Button
```css
background: linear-gradient(135deg, #1E4D91, #2563B8);
color: #FFFFFF;
font-size: 16px;
font-weight: 700;
border-radius: 10px;
padding: 15px 32px;
box-shadow: 0 4px 20px rgba(37, 99, 184, 0.4);
transition: transform 0.28s, box-shadow 0.28s;

/* Hover */
transform: translateY(-2px);
box-shadow: 0 8px 32px rgba(37, 99, 184, 0.6);
```

#### Secondary / Ghost Button
```css
background: rgba(30, 77, 145, 0.18);
border: 1px solid rgba(59, 130, 246, 0.35);
color: #FFFFFF;
border-radius: 10px;
padding: 14px 28px;

/* Hover */
background: rgba(30, 77, 145, 0.32);
border-color: rgba(59, 130, 246, 0.6);
```

#### Text Link / Arrow Link
```css
color: #3B82D6;
font-size: 14px;
font-weight: 600;
display: inline-flex;
align-items: center;
gap: 6px;
/* Arrow icon inline SVG */
```

---

### Card System

#### Service Cards
- Background: `linear-gradient(145deg, --blue-800, --blue-900)`
- Border: `1px solid rgba(59, 130, 246, 0.12)`
- Border Radius: `16px`
- Padding: `32px 28px`
- Hover: `border-color rgba(59, 130, 246, 0.35)`, `box-shadow 0 12px 48px rgba(6,14,30,0.35)`, `translateY(-4px)`

#### Why-Us Cards (Small)
- Background: `rgba(13, 31, 60, 0.5)`
- Border: `1px solid rgba(59, 130, 246, 0.1)`
- Border Radius: `12px`
- Padding: `24px 20px`

---

### Form Elements

```css
/* Input / Select / Textarea */
background: rgba(6, 14, 30, 0.6);
border: 1px solid rgba(71, 85, 105, 0.5);
border-radius: 8px;
padding: 12px 14px;
color: #FFFFFF;
font-family: 'Inter', sans-serif;

/* Focus */
border-color: #2563B8;
box-shadow: 0 0 0 3px rgba(37, 99, 184, 0.2);
```

---

### Icon System
- **Style:** Line icons (stroke-based, not solid fills)
- **Weight:** `stroke-width: 2 to 2.5`
- **Size:** 16–20px inline, 22–28px standalone
- **Color:** Matches context — white on dark, blue-300 for accent
- **Corner style:** `stroke-linecap: round; stroke-linejoin: round`

Recommended icon library: **Lucide Icons** or **Heroicons (outline)**

---

### Layout & Grid

| Property | Value |
|----------|-------|
| Max container width | `1160px` |
| Container padding | `0 24px` |
| Section padding | `80–120px vertical` |
| Card grid | `repeat(auto-fit, minmax(300px, 1fr))` |
| Grid gap | `24–32px` |
| Section spacing | `80px between major sections` |

---

### Motion & Animation

| Property | Value |
|----------|-------|
| Transition easing | `cubic-bezier(0.4, 0, 0.2, 1)` |
| Transition duration | `0.28s` |
| Hover lift | `translateY(-2px)` to `translateY(-4px)` |
| Scroll reveal | `opacity 0→1, translateY(24px→0), 0.65s ease` |
| Reveal threshold | `0.12` intersection, `rootMargin: -40px` |
| Float animation | `translateY -14px`, `infinite`, `ease-in-out` |

---

### Depth & Shadow

```css
/* Card shadow */
--shadow-card: 0 4px 24px rgba(6, 14, 30, 0.18);

/* Large shadow */
--shadow-lg: 0 8px 40px rgba(6, 14, 30, 0.28);

/* Glow (accent) */
box-shadow: 0 4px 20px rgba(37, 99, 184, 0.4);

/* Focus ring */
box-shadow: 0 0 0 3px rgba(37, 99, 184, 0.2);
```

---

### Border Radius Scale

| Token | Value | Usage |
|-------|-------|-------|
| `--radius` | `14px` | Cards, modals |
| `--radius-sm` | `8px` | Inputs, small elements |
| `10px` | — | Buttons |
| `12px` | — | Small cards, badges |

---

## 06 — TONE OF VOICE

### Brand Voice Pillars

| Pillar | Description |
|--------|-------------|
| **Direct** | Say what you mean. No filler words or corporate fluff. |
| **Confident** | State facts, not opinions. "We show up" not "We try to show up." |
| **Human** | Friendly but not casual. Professional but not cold. |
| **Reassuring** | Address anxiety. Customers are stressed — give them certainty. |

---

### Writing Rules

✅ **DO:**
- Use short, punchy sentences in headlines
- Lead with the customer's benefit, not the service feature
- Use "we" and "you" — direct and personal
- Back claims with specifics: "within 2–4 hours", "7 days a week"
- End CTAs with clear next step: "Get a Free Quote", "Book Now"

❌ **DON'T:**
- Use jargon or technical language (especially in IT descriptions)
- Make vague promises ("we do our best")
- Use exclamation marks excessively
- Use passive voice ("it will be done" → "we'll do it")

---

### Headline Formulas

**Hero:** `[Bold claim]. + [Qualification]`
> "One Company. Every Job Done. Right."

**Service intro:** `[Pain point removed] + [How]`
> "Skip the instruction manual headache."

**Trust statement:** `[Fact] + [Implication]`
> "Qwartz LLC is a registered, licensed company built on accountability."

---

### Ad Copy Guidelines

#### Facebook / Instagram Ads

**Format:** Hook → Problem → Solution → CTA

```
Hook:    "Still juggling 3 different contractors?"
Problem: "Moving, furniture assembly, AND tech setup shouldn't
          require 3 separate companies and 3 separate headaches."
Solution: "Qwartz handles it all — licensed, insured, one call."
CTA:     "Get your free quote → qwartz.net"
```

**Tone:** Conversational, slightly informal, empathetic. Feels like a friend recommending a service.

#### Google Search Ads

**Format:** Keyword-led, benefit-focused, urgency optional

```
Headline 1: Moving + Assembly + IT — One Company
Headline 2: Licensed LLC | Free Quote Today
Headline 3: Same-Day Availability | Qwartz Services
Description: Skip the runaround. Qwartz handles your move, furniture 
             assembly & tech support. Licensed, insured, reliable. 
             Get a free no-commitment quote.
```

**Tone:** Direct, professional, keyword-conscious. Focus on trust signals ("Licensed LLC", "Insured").

---

## 07 — BRAND ASSET CHECKLIST

For any design agency or developer receiving this document, the following assets are required:

- [ ] Logo SVG (dark background version)
- [ ] Logo SVG (light/inverted version)
- [ ] Logo PNG exports (1x, 2x, 3x)
- [ ] Favicon ICO + PNG (16, 32, 180, 512px)
- [ ] Color palette swatch file (ASE / SCSS variables)
- [ ] Inter font loaded via Google Fonts CDN
- [ ] Icon set: Lucide Icons or Heroicons (outline)
- [ ] Brand Book PDF (this document)

---

## 08 — QUICK REFERENCE

```
Brand:        Qwartz Services (Qwartz LLC)
Website:      qwartz.net
Primary Font: Inter (Google Fonts)
Background:   #060E1E  (Deep Midnight)
Surface:      #0D1F3C  (Card Blue)
Accent:       #3B82F6  (Electric Blue)
CTA Button:   gradient(#1E4D91 → #2563B8)
Text Primary: #FFFFFF
Text Body:    #94A3B8
Border:       rgba(59, 130, 246, 0.15)
Radius:       14px (cards), 10px (buttons), 8px (inputs)
Transition:   0.28s cubic-bezier(0.4, 0, 0.2, 1)
```

---

*Qwartz LLC Brand Book v1.0 — Prepared by Antigravity Design System*
*Last updated: April 2025*
*All rights reserved. For internal and agency use only.*
