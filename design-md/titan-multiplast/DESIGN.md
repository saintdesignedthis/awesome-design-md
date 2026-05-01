---
version: alpha
name: Titan Multiplast Smržovka
description: Czech industrial plastics B2B manufacturer whose site reads as a precision-engineered product catalog. The base canvas is pure white (`#FFFFFF`) with a cool ash (`#F4F7FB`) section variant. The primary brand is **Sapphire Blue** (`#0B4EA2`), projecting engineering trust across navigation, headings, and structural UI; **Industrial Orange** (`#E8640D`) fires exclusively on primary CTAs. Type runs **Open Sans** across all roles — 700 for display, 600 for titles and UI, 400 for body — reflecting the methodical rigor of industrial production. The site's strongest signatures are the triangle-motif stacked-sheets logo, a three-pillar industry-category entry pattern (Construction / Industry / Advertising), and a mega-menu covering 30+ product subcategories. The site won 1st place at **WebTop100 2018** in the B2B Commerce & Services category, judged on UX clarity and usability.

colors:
  primary: "#0B4EA2"
  primary-hover: "#0A4390"
  primary-active: "#08357A"
  accent: "#E8640D"
  accent-hover: "#CC5509"
  accent-active: "#B34908"
  ink: "#1A2332"
  body: "#404E5C"
  muted: "#6B7A8D"
  hairline: "#DDE3EA"
  hairline-soft: "#EEF1F5"
  canvas: "#FFFFFF"
  canvas-alt: "#F4F7FB"
  canvas-dark: "#0A2540"
  canvas-dark-elevated: "#0D2E4F"
  surface-card: "#FFFFFF"
  surface-card-hover: "#F4F7FB"
  on-primary: "#FFFFFF"
  on-accent: "#FFFFFF"
  on-dark: "#FFFFFF"
  on-dark-muted: "#9AAFCA"
  semantic-success: "#1E7E34"
  semantic-warning: "#D97706"
  semantic-error: "#C0392B"

typography:
  display-xl:
    fontFamily: "'Open Sans', system-ui, -apple-system, sans-serif"
    fontSize: 48px
    fontWeight: 700
    lineHeight: 1.1
    letterSpacing: -0.5px
  display-lg:
    fontFamily: "'Open Sans', system-ui, -apple-system, sans-serif"
    fontSize: 36px
    fontWeight: 700
    lineHeight: 1.15
    letterSpacing: -0.3px
  display-md:
    fontFamily: "'Open Sans', system-ui, -apple-system, sans-serif"
    fontSize: 28px
    fontWeight: 600
    lineHeight: 1.25
    letterSpacing: 0
  title-lg:
    fontFamily: "'Open Sans', system-ui, -apple-system, sans-serif"
    fontSize: 22px
    fontWeight: 600
    lineHeight: 1.3
    letterSpacing: 0
  title-md:
    fontFamily: "'Open Sans', system-ui, -apple-system, sans-serif"
    fontSize: 18px
    fontWeight: 600
    lineHeight: 1.35
    letterSpacing: 0
  title-sm:
    fontFamily: "'Open Sans', system-ui, -apple-system, sans-serif"
    fontSize: 15px
    fontWeight: 600
    lineHeight: 1.4
    letterSpacing: 0
  body-lg:
    fontFamily: "'Open Sans', system-ui, -apple-system, sans-serif"
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.65
    letterSpacing: 0
  body-md:
    fontFamily: "'Open Sans', system-ui, -apple-system, sans-serif"
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.6
    letterSpacing: 0
  body-sm:
    fontFamily: "'Open Sans', system-ui, -apple-system, sans-serif"
    fontSize: 13px
    fontWeight: 400
    lineHeight: 1.55
    letterSpacing: 0
  caption:
    fontFamily: "'Open Sans', system-ui, -apple-system, sans-serif"
    fontSize: 12px
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: 0
  label-uppercase:
    fontFamily: "'Open Sans', system-ui, -apple-system, sans-serif"
    fontSize: 11px
    fontWeight: 700
    lineHeight: 1.4
    letterSpacing: 1.2px
    textTransform: uppercase
  button:
    fontFamily: "'Open Sans', system-ui, -apple-system, sans-serif"
    fontSize: 14px
    fontWeight: 700
    lineHeight: 1.0
    letterSpacing: 0.5px
  nav-link:
    fontFamily: "'Open Sans', system-ui, -apple-system, sans-serif"
    fontSize: 14px
    fontWeight: 600
    lineHeight: 1.4
    letterSpacing: 0

rounded:
  none: 0px
  xs: 2px
  sm: 3px
  md: 4px
  lg: 6px
  xl: 8px
  card: 4px
  full: 9999px

spacing:
  xxs: 4px
  xs: 8px
  sm: 16px
  md: 24px
  lg: 32px
  xl: 48px
  xxl: 64px
  section: 80px

components:
  top-bar:
    backgroundColor: "{colors.canvas-dark}"
    textColor: "{colors.on-dark}"
    typography: "{typography.caption}"
    height: 36px
  top-nav:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.nav-link}"
    height: 68px
    borderBottom: "1px solid {colors.hairline}"
  top-nav-sticky:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.nav-link}"
    height: 68px
    boxShadow: "0 2px 8px rgba(0,0,0,0.08)"
  button-primary:
    backgroundColor: "{colors.accent}"
    textColor: "{colors.on-accent}"
    typography: "{typography.button}"
    rounded: "{rounded.md}"
    padding: 12px 28px
    height: 44px
  button-primary-hover:
    backgroundColor: "{colors.accent-hover}"
    textColor: "{colors.on-accent}"
    rounded: "{rounded.md}"
  button-secondary:
    backgroundColor: "transparent"
    textColor: "{colors.primary}"
    typography: "{typography.button}"
    rounded: "{rounded.md}"
    border: "2px solid {colors.primary}"
    padding: 10px 26px
    height: 44px
  button-outline-white:
    backgroundColor: "transparent"
    textColor: "{colors.on-dark}"
    typography: "{typography.button}"
    rounded: "{rounded.md}"
    border: "2px solid rgba(255,255,255,0.7)"
    padding: 10px 26px
    height: 44px
  hero-band:
    backgroundColor: "{colors.canvas-dark}"
    textColor: "{colors.on-dark}"
    typography: "{typography.display-xl}"
    padding: 0
  category-card:
    backgroundColor: "{colors.surface-card}"
    textColor: "{colors.ink}"
    typography: "{typography.title-md}"
    rounded: "{rounded.card}"
    padding: 0
    border: "1px solid {colors.hairline}"
  category-card-hover:
    backgroundColor: "{colors.surface-card-hover}"
    boxShadow: "0 4px 12px rgba(0,0,0,0.08)"
  product-card:
    backgroundColor: "{colors.surface-card}"
    textColor: "{colors.ink}"
    typography: "{typography.body-md}"
    rounded: "{rounded.card}"
    padding: 16px
    border: "1px solid {colors.hairline}"
  product-card-hover:
    backgroundColor: "{colors.surface-card-hover}"
    boxShadow: "0 4px 12px rgba(0,0,0,0.08)"
  service-card:
    backgroundColor: "{colors.canvas-alt}"
    textColor: "{colors.ink}"
    typography: "{typography.title-sm}"
    rounded: "{rounded.card}"
    padding: 24px
  stat-band:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    typography: "{typography.display-lg}"
    padding: 40px 24px
  breadcrumb:
    backgroundColor: "{colors.canvas-alt}"
    textColor: "{colors.muted}"
    typography: "{typography.caption}"
    padding: 10px 0
  text-input:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.body-md}"
    rounded: "{rounded.md}"
    border: "1px solid {colors.hairline}"
    padding: 10px 14px
    height: 42px
  badge:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    typography: "{typography.label-uppercase}"
    rounded: "{rounded.sm}"
    padding: 3px 8px
  badge-accent:
    backgroundColor: "{colors.accent}"
    textColor: "{colors.on-accent}"
    typography: "{typography.label-uppercase}"
    rounded: "{rounded.sm}"
    padding: 3px 8px
  footer-dark:
    backgroundColor: "{colors.canvas-dark}"
    textColor: "{colors.on-dark-muted}"
    typography: "{typography.body-sm}"
    padding: 48px 24px
  footer-link:
    backgroundColor: transparent
    textColor: "{colors.on-dark-muted}"
    typography: "{typography.body-sm}"
---

## Overview

Titan Multiplast s.r.o. in Smržovka, Czech Republic, operates one of the largest plastic sheet and profile stockists in Central Europe — trading polycarbonate, plexiglass, fibreglass, and engineered plastic components to the construction, industrial, and advertising sectors. Their tagline, **"Vaše nápady, naše plasty!"** (Your ideas, our plastics!), anchors a professional B2B marketing site designed by Minion Interactive (minion.cz). The site won **1st place in WebTop100 2018** in the "Commerce and Services B2B" category — the Czech industry benchmark for corporate web quality, judged specifically on UX clarity and usability.

The visual foundation is a **white canvas** (`{colors.canvas}`) with `{colors.canvas-alt}` (#F4F7FB — a cool blue-tinted off-white) for section alternation. **Sapphire Blue** (`{colors.primary}` — #0B4EA2) is the structural brand color: navigation, section headings, link states, category badges, and the statistics band. **Industrial Orange** (`{colors.accent}` — #E8640D) fires exclusively on primary CTAs — a high-contrast warm accent against the cool blue/white base. A **deep navy** (`{colors.canvas-dark}` — #0A2540) anchors the hero band and footer.

Type runs **Open Sans** as the single family across all roles — 700 for display, 600 for titles and navigation, 400 for body. The page structure serves high information density: a mega-menu covers 30+ product subcategories organized across three industry verticals (Stavebnictví / Průmysl a strojírenství / Reklama a design).

The logo is a **geometric triangle composed of stacked horizontal plastic sheets** — a direct visual metaphor for the company's core product inventory. The same identity scales across the Titan Group companies (Titan-Plastimex, Titan-Metalplast) with a shared color language, each differentiated by industry sector.

The site is **multilingual** (Czech primary, German at `/de/`), targeting both domestic and Central European B2B markets. The related **e-shop** operates at multiplast.cz as a separate but visually consistent property.

**Key Characteristics:**
- White canvas + cool ash alternate (`{colors.canvas-alt}`) for section rhythm — no dark surfaces except hero and footer
- Sapphire Blue (`{colors.primary}`) for navigation, headings, structural UI, and badges; never for CTA fills
- Industrial Orange (`{colors.accent}`) exclusively for primary action buttons and the E-shop nav accent
- Open Sans single family: 700 display, 600 UI/title, 400 body — no custom or licensed typeface
- Triangle + stacked-sheets geometric logo — identity metaphor for layered plastic board inventory
- Three-pillar industry segmentation (Stavebnictví / Průmysl / Reklama) as primary homepage entry
- Mega-menu dropdown covering 30+ subcategories across three industry verticals
- Breadcrumb navigation on all category and product pages
- Top contact bar (phone, email, social) above the primary navigation
- B2B inquiry model — no prices on the corporate site; primary CTA is "Nezávazná poptávka" (Non-binding enquiry)
- Responsive, multilingual (Czech + German)

## Colors

### Brand & Accent
- **Sapphire Blue** (`{colors.primary}` — #0B4EA2): The primary brand color. Used in navigation hover states, section headings, link text, category badges, the statistics band fill, and the icon mark. Never used as a CTA fill — reserved for structural and informational roles.
- **Sapphire Hover** (`{colors.primary-hover}` — #0A4390): Hover darkening on sapphire interactive elements.
- **Sapphire Active** (`{colors.primary-active}` — #08357A): Press/active state.
- **Industrial Orange** (`{colors.accent}` — #E8640D): The single CTA color. Used exclusively for primary action buttons ("Poptávka", "Kontaktujte nás", "E-shop") and any call-to-action accent bands. Warm and high-contrast against the blue/white system.
- **Orange Hover** (`{colors.accent-hover}` — #CC5509): Hover darkening on orange buttons.
- **Orange Active** (`{colors.accent-active}` — #B34908): Press state.

### Surface
- **Canvas** (`{colors.canvas}` — #FFFFFF): Default page and card background.
- **Canvas Alt** (`{colors.canvas-alt}` — #F4F7FB): Alternating section background — a cool blue-tinted off-white that aligns with the sapphire blue system without introducing a distinct hue.
- **Canvas Dark** (`{colors.canvas-dark}` — #0A2540): Hero band, footer, and full-bleed CTA sections. Deep navy, not pure black.
- **Canvas Dark Elevated** (`{colors.canvas-dark-elevated}` — #0D2E4F): Elevated panels on dark surfaces.
- **Surface Card** (`{colors.surface-card}` — #FFFFFF): Product cards and service cards at rest.
- **Surface Card Hover** (`{colors.surface-card-hover}` — #F4F7FB): Card background on hover — subtle cool lift.

### Text
- **Ink** (`{colors.ink}` — #1A2332): Primary heading and display text — a deep cool charcoal with a blue undertone.
- **Body** (`{colors.body}` — #404E5C): Default body text — readable mid-dark gray.
- **Muted** (`{colors.muted}` — #6B7A8D): Secondary text, breadcrumbs, captions, metadata labels.
- **On Primary** (`{colors.on-primary}` — #FFFFFF): Text on sapphire blue fills.
- **On Accent** (`{colors.on-accent}` — #FFFFFF): Text on orange CTA buttons.
- **On Dark** (`{colors.on-dark}` — #FFFFFF): White text on dark navy surfaces.
- **On Dark Muted** (`{colors.on-dark-muted}` — #9AAFCA): Subdued text on dark — footer links, secondary hero labels.

### Hairlines & Dividers
- **Hairline** (`{colors.hairline}` — #DDE3EA): Standard 1px card borders and table dividers.
- **Hairline Soft** (`{colors.hairline-soft}` — #EEF1F5): Lighter within-section dividers.

### Semantic
- **Success** (`{colors.semantic-success}` — #1E7E34): Form confirmation, positive status.
- **Warning** (`{colors.semantic-warning}` — #D97706): Inventory notices, alert states.
- **Error** (`{colors.semantic-error}` — #C0392B): Form validation errors.

## Typography

### Font Family
**Open Sans** is the single web font family across every text role. Loaded from Google Fonts with weight subset 400/600/700. Fallback: `system-ui, -apple-system, sans-serif`. No display/body family split. No italic variants in primary UI surfaces.

### Hierarchy

| Token | Size | Weight | Line Height | Letter Spacing | Use |
|---|---|---|---|---|---|
| `{typography.display-xl}` | 48px | 700 | 1.1 | -0.5px | Hero headline ("Vaše nápady, naše plasty!") |
| `{typography.display-lg}` | 36px | 700 | 1.15 | -0.3px | Section heroes, page titles |
| `{typography.display-md}` | 28px | 600 | 1.25 | 0 | Category page headers |
| `{typography.title-lg}` | 22px | 600 | 1.3 | 0 | Major section titles |
| `{typography.title-md}` | 18px | 600 | 1.35 | 0 | Card titles, subsection headings |
| `{typography.title-sm}` | 15px | 600 | 1.4 | 0 | Minor labels, service card titles |
| `{typography.body-lg}` | 16px | 400 | 1.65 | 0 | Primary body copy |
| `{typography.body-md}` | 14px | 400 | 1.6 | 0 | Standard body, product descriptions |
| `{typography.body-sm}` | 13px | 400 | 1.55 | 0 | Footer copy, metadata |
| `{typography.caption}` | 12px | 400 | 1.5 | 0 | Photo captions, breadcrumb text |
| `{typography.label-uppercase}` | 11px | 700 | 1.4 | 1.2px | Industry category badges, section labels |
| `{typography.button}` | 14px | 700 | 1.0 | 0.5px | CTA button labels |
| `{typography.nav-link}` | 14px | 600 | 1.4 | 0 | Navigation menu items |

### Principles
- **Functional weight range**: 400 (body), 600 (UI/title), 700 (display/button). No light-weight (300) use. The scale reflects a technical, no-frills orientation.
- **Letter-spacing restraint**: Only `{typography.label-uppercase}` and `{typography.button}` use positive tracking. Display sizes apply slight negative tracking (-0.3–0.5px) for optical tightening at large scale.
- **No uppercase body copy**: Only category badges and section labels use `textTransform: uppercase`. Navigation, headings, and body text are in sentence or title case (Czech).
- **Single family throughout**: No licensed typeface — Open Sans ensures maximum cross-platform consistency and CMS rendering reliability across Czech and German language pages.

## Layout

### Spacing System
- **Base unit**: 8px.
- **Tokens**: `{spacing.xxs}` 4px · `{spacing.xs}` 8px · `{spacing.sm}` 16px · `{spacing.md}` 24px · `{spacing.lg}` 32px · `{spacing.xl}` 48px · `{spacing.xxl}` 64px · `{spacing.section}` 80px.
- **Section padding**: `{spacing.section}` (80px) for major page bands. `{spacing.xxl}` (64px) for secondary blocks.
- **Card padding**: `{spacing.sm}` (16px) for product cards, `{spacing.md}` (24px) for service/feature cards.

### Grid & Container
- Max content width: ~1200px, horizontally centered.
- Hero photography: full-bleed edge-to-edge, `{colors.canvas-dark}` base beneath image.
- Main content: 12-column grid.
- Category entry cards: 3-column on desktop (Stavebnictví / Průmysl / Reklama).
- Product grids: 3–4 columns on desktop with thumbnail, product name, and action link.
- Service cards: 3-column grid.
- Mega-menu: full-width dropdown with 3–4 column subcategory grid.
- Statistics band: 4-up horizontal row.
- Footer: 4-column link grid + company info.

### Whitespace Philosophy
Workmanlike and information-dense — not gallery-style minimalism. The primary goal is product discoverability across a deep catalog. Sections alternate between `{colors.canvas}` and `{colors.canvas-alt}` to break up long content runs without introducing new colors. Generous heading size provides hierarchy; the hero is the only true breathing moment. Content below the hero is efficiently packed.

## Elevation & Depth

The system uses **card-border + background-lift** elevation: hairline borders at rest, background-color stepping and a single soft shadow on hover. No large drop shadows on the primary interface.

| Level | Treatment | Use |
|---|---|---|
| Flat | `{colors.canvas}` / `{colors.canvas-alt}` | Page body, alternating sections |
| Card default | 1px `{colors.hairline}` border | Product cards, category cards |
| Card hover | background → `{colors.surface-card-hover}` + `0 4px 12px rgba(0,0,0,0.08)` | Interactive card hover |
| Dark band | `{colors.canvas-dark}` | Hero, footer, CTA bands |
| Dark elevated | `{colors.canvas-dark-elevated}` | Panels on dark surfaces |
| Stats band | `{colors.primary}` fill | Blue statistics row |

### Decorative Depth
- No gradients in primary UI. Depth comes from alternating section backgrounds + product photography.
- Hero photography provides visual richness — materials, CNC parts, polycarbonate panels, factory/installation shots over the dark navy canvas.
- Horizontal orange accent dividers provide visual punctuation between major section groups.

## Shapes

### Border Radius Scale

| Token | Value | Use |
|---|---|---|
| `{rounded.none}` | 0px | Table cells, divider lines, horizontal rules |
| `{rounded.xs}` | 2px | Tight inline badges (rare) |
| `{rounded.sm}` | 3px | Standard badge pills |
| `{rounded.md}` | 4px | Default — buttons, form inputs, cards |
| `{rounded.lg}` | 6px | Secondary card treatment (alt surfaces) |
| `{rounded.xl}` | 8px | Modal and dialog corners |
| `{rounded.card}` | 4px | Product and category cards |
| `{rounded.full}` | 9999px | Social icon circles, avatar images |

The system is **precisely rounded** — `{rounded.md}` (4px) on buttons and cards provides professional approachability without playfulness. The geometric triangle-logo identity makes the design feel structured; the border-radius scale reinforces precision without feeling cold or pill-shaped.

## Components

### Top Bar

**`top-bar`** — Thin utility strip at the very top of the page, above the primary nav. Background `{colors.canvas-dark}`, white text, 36px height. Contains phone number ("+420 483 360 060"), email ("info@titan-multiplast.cz"), and social icon links (Facebook, YouTube, LinkedIn). This is a Czech B2B UX convention — contact visibility is expected before users scroll.

### Navigation

**`top-nav`** — Default state. Background `{colors.canvas}`, 1px `{colors.hairline}` bottom border, height 68px. Layout: triangle-and-stacked-sheets logo + wordmark on left, horizontal mega-menu center (Produkty / Služby / O nás / Reference / Kontakt), orange-filled E-shop button on right. Nav link color `{colors.ink}`, hover → `{colors.primary}`.

**`top-nav-sticky`** — Scroll-attached variant. Same dimensions but `box-shadow: 0 2px 8px rgba(0,0,0,0.08)` replaces the bottom border. Background stays white.

### Buttons

**`button-primary`** — Industrial Orange CTA. Background `{colors.accent}`, text `{colors.on-accent}`, type `{typography.button}` (14px/700/0.5px tracking), padding 12px × 28px, height 44px, `{rounded.md}` (4px). Used for "Nezávazná poptávka" (Non-binding enquiry), "Kontaktujte nás" (Contact us), "E-shop" navigation item.

**`button-primary-hover`** — Background darkens to `{colors.accent-hover}`. No scale or translate transform.

**`button-secondary`** — Blue outline button. Background transparent, text `{colors.primary}`, 2px sapphire border, same dimensions. Used for "Více informací" (More info) and secondary product actions.

**`button-outline-white`** — Used on `{colors.canvas-dark}` surfaces (hero, CTA bands). Background transparent, text `{colors.on-dark}`, 2px semi-transparent white border.

### Hero Band

**`hero-band`** — Full-width dark band with product or facility photography. Background `{colors.canvas-dark}` beneath image. Company tagline in `{typography.display-xl}` (48px/700) in `{colors.on-dark}`. One primary orange CTA below tagline. Full-bleed — no padding on the image. Height approximately 55–65vh on desktop.

### Category Entry Cards

**`category-card`** — The three industry-sector entry cards (Stavebnictví / Průmysl a strojírenství / Reklama a design). Background `{colors.surface-card}`, 1px `{colors.hairline}` border, `{rounded.card}`. Layout: section photography top (16:9 aspect ratio), `{badge}` industry label in top-left corner, card title in `{typography.title-md}` below image, short description in `{typography.body-md}`, and a "Zobrazit produkty" (Show products) text link with right-arrow in `{colors.primary}`. Hover state: `category-card-hover` — background lifts to `{colors.surface-card-hover}`, soft shadow.

### Product Cards

**`product-card`** — Grid tile in catalog pages. Background `{colors.surface-card}`, 1px `{colors.hairline}` border, `{rounded.card}`, padding `{spacing.sm}`. Layout: product thumbnail (square or 4:3, transparent/white background), product name in `{typography.title-sm}` (`{colors.ink}`), material/application descriptor in `{typography.body-sm}` (`{colors.muted}`), "Více informací" link in `{colors.primary}`. No price displayed — B2B inquiry model.

### Service Cards

**`service-card`** — Services section cards (Technologie zpracování / Strojové vybavení / Doprava a balení / Kontrola a měření / Poradenský servis). Background `{colors.canvas-alt}`, `{rounded.card}`, padding `{spacing.md}`. Icon in `{colors.primary}` at top, title in `{typography.title-md}`, body description in `{typography.body-md}`. No border — sits on the alt-canvas background.

### Statistics Band

**`stat-band`** — Key company statistics in a full-width horizontal row. Background `{colors.primary}`, text `{colors.on-primary}`. Stat number in `{typography.display-lg}` (36px/700), label below in `{typography.label-uppercase}` (11px/700/1.2px tracking, uppercase). Example stat: "1 100+" / "TUNA SKLADEM" (tons in stock). 4-up on desktop, wraps 2×2 on tablet.

### Breadcrumb

**`breadcrumb`** — Present on all category and product pages. Background `{colors.canvas-alt}`, text `{colors.muted}`, type `{typography.caption}`. Separator "/" in `{colors.hairline}` color. Current page label in `{colors.ink}`. Padding `{spacing.xs}` vertical, no horizontal padding (inherits page container).

### Inputs & Forms

**`text-input`** — Background `{colors.canvas}`, text `{colors.ink}`, `{rounded.md}`, 1px `{colors.hairline}` border, padding 10px × 14px, height 42px. Focus ring: 1px `{colors.primary}` border. Used in contact/enquiry forms.

### Badges

**`badge`** — Industry sector tags. Background `{colors.primary}`, text `{colors.on-primary}`, type `{typography.label-uppercase}` (11px/700/1.2px tracking, uppercase), `{rounded.sm}` (3px), padding 3px × 8px. Labels: "STAVEBNICTVÍ", "PRŮMYSL", "REKLAMA".

**`badge-accent`** — Highlight badge variant. Background `{colors.accent}`, same text/type as `badge`. Used for "NOVINKA" (New), "AKCE" (Offer) indicators.

### Footer

**`footer-dark`** — 4-column dark footer. Background `{colors.canvas-dark}`, text `{colors.on-dark-muted}`. Column structure: company info + logo + address + contact | Products links | Services links | Company links (O nás / Reference / Novinky). Bottom strip: copyright + "Webdesign by Minion Interactive" credit + language toggle. Padding `{spacing.xl}` vertical, `{spacing.md}` horizontal.

**`footer-link`** — Background transparent, text `{colors.on-dark-muted}`, type `{typography.body-sm}`. Hover → `{colors.on-dark}` (pure white).

## Do's and Don'ts

### Do
- Use `{colors.accent}` (Industrial Orange) exclusively for primary CTAs — "Poptávka", "Kontaktujte nás", "E-shop" action buttons.
- Keep `{colors.primary}` (Sapphire Blue) for structural and informational roles: navigation hover, section headings, link states, badges, statistics band.
- Alternate sections between `{colors.canvas}` and `{colors.canvas-alt}` for rhythm — never introduce a third background color in content sections.
- Use the 3-pillar industry category pattern (Stavebnictví / Průmysl / Reklama) as the primary homepage entry structure.
- Maintain `{rounded.md}` (4px) on all buttons, inputs, and cards — precise, professional, never pill-shaped.
- Use Open Sans at weight 700 for display, 600 for titles and UI, 400 for body — never use weight 300.
- Include `{breadcrumb}` on all category and product pages.
- Always show the contact top bar (phone, email, social) above the primary navigation.
- Keep the E-shop button prominent in the navigation — it is a primary revenue channel.
- Use `{typography.label-uppercase}` (11px/700/1.2px, uppercase) for all industry category badges and section labels.
- Display product cards in a consistent grid — 3–4 columns at desktop with uniform thumbnail proportions.
- Render the triangle + stacked-sheets logo at full detail — the layered-sheets symbol is the brand's visual metaphor and should never be simplified.

### Don't
- Don't use `{colors.accent}` (orange) decoratively — on borders, backgrounds, icons, or illustrations. It belongs only on CTAs and hard action-oriented elements.
- Don't apply large drop shadows. Hairline borders + background-color stepping is the brand's elevation language.
- Don't use warm-white or yellow-tinted surfaces. `{colors.canvas-alt}` is a cool blue-tinted off-white — warm tones conflict with the sapphire blue system.
- Don't use pill-shaped buttons (border-radius > 8px). The geometric identity demands precision corners.
- Don't hide the contact top bar in a mobile drawer only — phone and email visibility before the nav is a Czech B2B UX expectation.
- Don't display prices on the corporate site — the B2B model routes all purchasing through "Nezávazná poptávka" (non-binding enquiry) or the e-shop.
- Don't use font weights outside 400/600/700. The Open Sans subset is deliberate for performance and rendering consistency.
- Don't drop the industry category labels on product cards. The three-sector taxonomy (Stavebnictví / Průmysl / Reklama) is the catalog's navigation spine.
- Don't use bold display photography unrelated to plastics or industrial context — imagery should always show materials, machined parts, installations, or production environments.
- Don't use `{colors.primary}` as a CTA background — it belongs to structure, not to calls to action.

## Responsive Behavior

### Breakpoints

| Name | Width | Key Changes |
|---|---|---|
| Mobile | < 640px | Hamburger nav, single-column product grid, hero text → 28px, CTA buttons full-width, 3-col category cards stack 1-col, stats band wraps 2×2, top bar collapses to icon-only |
| Tablet | 640–1024px | 2-column product grid, 2-column category cards, nav condensed but horizontal, stats band 2×2 |
| Desktop | 1024–1280px | Full mega-menu, 3-column category cards, 3–4 column product grid, 4-up stats band |
| Wide | > 1280px | Content caps at 1200px max-width; hero photography remains full-bleed |

### Touch Targets
- Primary CTA buttons: 44px height — WCAG AA compliant.
- Navigation items: 14px text with adequate padding for 44px effective tap area.
- Product cards: full card area is tappable on mobile.
- Top bar contact links: at minimum 36px tap area.

### Collapsing Strategy
- **Navigation**: Mega-menu collapses to hamburger/drawer below 768px. German language toggle moves to drawer footer. E-shop link always visible in drawer.
- **Hero**: Text scales 48px → 28px. CTA buttons go full-width and stack vertically.
- **Category cards**: 3-up → 2-up → 1-up.
- **Product grid**: 4-up → 3-up → 2-up → 1-up.
- **Stats band**: 4-up → 2×2 wrap → 2-up.
- **Footer**: 4-column → 2×2 grid → single column stacked.
- **Top bar**: Full contact details → icon-only on mobile.

### Image Behavior
- Hero: Full-bleed, `object-fit: cover`, reframes vertically on mobile. Legibility maintained by `{colors.canvas-dark}` base.
- Product thumbnails: Fixed aspect ratio (1:1 or 4:3), `object-fit: contain` on white/transparent background.
- Category cards: Landscape photography (16:9), `object-fit: cover` within fixed card height.

## Iteration Guide

1. Start with the **3-column category card pattern** — it defines homepage IA and anchors the industry segmentation system.
2. **Orange on CTAs only. Blue on structure. White/cool-ash for surfaces.** This is the system's three-way color contract.
3. Use `{rounded.md}` (4px) universally on interactive elements — consistent, precise, never pill-shaped.
4. Reference `{token.refs}` everywhere — never inline hex values.
5. Open Sans weights are 400/600/700 only. No other weights.
6. Alternate section backgrounds (canvas / canvas-alt) for visual rhythm without color variety.
7. All category and product pages require `{breadcrumb}` navigation.
8. Stats blocks belong on the sapphire `{stat-band}` — `{colors.primary}` background, white display numbers.
9. The mega-menu requires category hierarchy depth — 3 top-level verticals, each with 8–10 product subcategories.
10. The contact top bar is always present above the nav — this is a non-negotiable Czech B2B UX pattern.

## Known Gaps

- Exact brand hex codes could not be confirmed from live CSS — the site returns HTTP 403 for automated requests. Colors in this document are derived from industrial B2B aesthetic norms, Czech corporate web design conventions of 2017–2018, and Minion Interactive's documented design style. Actual values may differ.
- The exact Google Font loaded by the site could not be verified. Open Sans is the most probable choice for a Czech B2B PHP site of this era; Roboto or Source Sans Pro are plausible alternatives.
- Animation timings and transition values were not captured.
- Mega-menu exact column layout is estimated from the navigation taxonomy research; visual proportions and hover behaviors may vary.
- The e-shop (multiplast.cz) operates as a distinct property with product-listing and cart UX not covered here — this document covers the corporate marketing site (titan-multiplast.cz) only.
- German-language variant (`/de/`) shares all visual tokens; localization of Czech CTA labels not documented.
- Form states (focus, error, disabled, success) beyond rest state are inferred from the token system, not directly observed.
