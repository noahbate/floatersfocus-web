---
version: alpha
name: Floaters Focus — Clean Clinical
description: Apple-like clinical minimalism for an evidence-based eye-health brand. All-sans typography on cool white surfaces, one restrained accent, precise geometry, generous whitespace. Reads like a precision instrument — the medical-grade counterpart to the editorial direction.
colors:
  primary: "#3F6B4F"
  primary-dark: "#2E4F3A"
  on-primary: "#FFFFFF"
  ink: "#0F1214"
  ink-soft: "#3D4348"
  muted: "#6E767C"
  faint: "#9AA1A7"
  paper: "#FFFFFF"
  paper-cool: "#F5F6F7"
  paper-deep: "#EBEDEF"
  border: "rgba(15, 18, 20, 0.10)"
  gold: "#B8860B"
  red-flag: "#B3261E"
  red-soft: "#FBEDEC"
  blue-info: "#1F5F8B"
  blue-soft: "#EDF4F9"
  green-ok: "#276B2C"
  green-soft: "#EDF5EE"
  amber-watch: "#8F5300"
  amber-soft: "#FBF3E4"
  dark-ink: "#E8EAEC"
  dark-ink-soft: "#B9BEC3"
  dark-muted: "#8A9198"
  dark-paper: "#0E1012"
  dark-paper-cool: "#14171A"
  dark-paper-deep: "#1A1E21"
  dark-border: "rgba(232, 234, 236, 0.12)"
  dark-primary: "#84B792"
  dark-on-primary: "#0C120E"
typography:
  display:
    fontFamily: Inter
    fontSize: 3.25rem
    fontWeight: 600
    lineHeight: 1.08
    letterSpacing: "-0.03em"
  h1:
    fontFamily: Inter
    fontSize: 2.5rem
    fontWeight: 600
    lineHeight: 1.12
    letterSpacing: "-0.025em"
  h2:
    fontFamily: Inter
    fontSize: 1.875rem
    fontWeight: 600
    lineHeight: 1.2
    letterSpacing: "-0.02em"
  h3:
    fontFamily: Inter
    fontSize: 1.375rem
    fontWeight: 600
    lineHeight: 1.3
    letterSpacing: "-0.01em"
  lead:
    fontFamily: Inter
    fontSize: 1.1875rem
    fontWeight: 400
    lineHeight: 1.65
    letterSpacing: "0em"
  body:
    fontFamily: Inter
    fontSize: 1.0625rem
    fontWeight: 400
    lineHeight: 1.7
    letterSpacing: "0em"
  body-sm:
    fontFamily: Inter
    fontSize: 0.9375rem
    fontWeight: 400
    lineHeight: 1.6
    letterSpacing: "0em"
  label:
    fontFamily: Inter
    fontSize: 0.75rem
    fontWeight: 600
    lineHeight: 1.3
    letterSpacing: "0.06em"
  mono:
    fontFamily: "JetBrains Mono"
    fontSize: 0.875rem
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: "0em"
rounded:
  sm: 8px
  md: 14px
  lg: 20px
  xl: 24px
  pill: 9999px
spacing:
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 40px
  xxl: 64px
  section: 96px
components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    rounded: "{rounded.sm}"
    padding: 14px 24px
    typography: label
  button-primary-hover:
    backgroundColor: "{colors.primary-dark}"
  button-primary-dark:
    backgroundColor: "{colors.dark-primary}"
    textColor: "{colors.dark-on-primary}"
    rounded: "{rounded.sm}"
    padding: 14px 24px
    typography: label
  button-secondary:
    backgroundColor: "{colors.paper-cool}"
    textColor: "{colors.ink}"
    rounded: "{rounded.sm}"
    padding: 14px 24px
    typography: label
  button-secondary-dark:
    backgroundColor: "{colors.dark-paper-cool}"
    textColor: "{colors.dark-ink}"
    rounded: "{rounded.sm}"
    padding: 14px 24px
    typography: label
  card:
    backgroundColor: "{colors.paper}"
    textColor: "{colors.ink}"
    rounded: "{rounded.md}"
    padding: 28px
  card-dark:
    backgroundColor: "{colors.dark-paper}"
    textColor: "{colors.dark-ink}"
    rounded: "{rounded.md}"
    padding: 28px
  badge-watching:
    backgroundColor: "{colors.amber-soft}"
    textColor: "{colors.amber-watch}"
    rounded: "{rounded.pill}"
    padding: 4px 12px
    typography: label
  badge-skeptical:
    backgroundColor: "{colors.red-soft}"
    textColor: "{colors.red-flag}"
    rounded: "{rounded.pill}"
    padding: 4px 12px
    typography: label
  badge-proven:
    backgroundColor: "{colors.green-soft}"
    textColor: "{colors.green-ok}"
    rounded: "{rounded.pill}"
    padding: 4px 12px
    typography: label
  callout-red:
    backgroundColor: "{colors.red-soft}"
    textColor: "{colors.ink}"
    rounded: "{rounded.md}"
    padding: 14px 18px
  callout-red-dark:
    backgroundColor: "#3A2223"
    textColor: "{colors.dark-ink}"
    rounded: "{rounded.md}"
    padding: 14px 18px
  nav-link:
    textColor: "{colors.ink-soft}"
    typography: body-sm
  nav-link-active:
    textColor: "{colors.primary}"
    typography: body-sm
  nav-link-dark:
    textColor: "{colors.dark-ink-soft}"
    typography: body-sm
  footer-bg:
    backgroundColor: "{colors.paper-deep}"
  footer-bg-dark:
    backgroundColor: "{colors.dark-paper-deep}"
  border-dark:
    backgroundColor: "{colors.dark-border}"
---

## Overview

Floaters Focus is an evidence-first eye-health resource — floaters, PVD, macular health, dry eye,
macular pucker. The audience arrives anxious and leaves calmer. This is the **clean clinical**
direction: precision over warmth, instrument over letter.

The design language is Apple-like restraint: an all-sans typographic system (Inter everywhere),
cool white surfaces, hairline borders, generous whitespace, and exactly one restrained accent
(sage) doing all interactive work. Where the editorial direction used serif voice and warm paper,
this direction uses **geometry and white space** — the interface should feel like a precision
instrument that happens to be reading you your eye health.

A real clinical asset anchors the identity: the hero leads with an actual OCT retina scan —
a genuine diagnostic image that instantly says "this is about real eyes, real medicine, real
evidence," without a single illustration.

Every layout decision follows this rule: **the evidence is the hero, the interface is the
instrument showing it to you.**

## Colors

- **Primary (#3F6B4F)** — "Sage" — the single restrained accent: buttons, links, active nav.
  Darker (#2E4F3A) for hover; lightens to #84B792 on dark surfaces.
- **Ink (#0F1214)** — near-black with a cool cast. Headings and body.
- **Paper (#FFFFFF)** — pure white canvas. paper-cool (#F5F6F7) for section alternation,
  paper-deep (#EBEDEF) for footers and wells. Cool neutrals only — no warm undertones.
- **Gold (#B8860B)** — star ratings and affiliate-accent moments only.
- **Semantic set** — red-flag (#B3261E), green-ok (#276B2C), amber-watch (#8F5300),
  blue-info (#1F5F8B), each with tinted soft backgrounds for callouts and badges.

## Typography

- **Inter** (Google Fonts) — the entire system, one family, three jobs:
  - Display/headings: weight 600, tight line-height (1.08–1.3), aggressive negative tracking
    (-0.03em at display, relaxing to -0.01em at h3). Apple-style compressed headlines.
  - Body: weight 400, line-height 1.7, no tracking.
  - Labels: 12px, weight 600, +0.06em tracking — used for buttons, kickers, badges.
- **JetBrains Mono** — DOIs and citations only (evidence-first: "mono = verifiable").
- Scale: 3.25rem display → 2.5 h1 → 1.875 h2 → 1.375 h3 → 1.1875 lead → 1.0625 body.
  Mobile: display scales to 2.25rem, h1 to 2rem.

## Layout

- 8px base spacing scale (xs 4 / sm 8 / md 16 / lg 24 / xl 40 / xxl 64 / section 96).
- Max content width ~1200px; reading measure ~65ch.
- **Section rhythm:** 96px vertical padding (64px mobile). Alternation is white → paper-cool →
  white — cool, quiet, and structural, never decorative.
- **Hairline borders** (1px, 10% ink) on cards, dividers, and images. Hard rules: borders
  exist to delineate, not decorate.
- Grids: condition cards 4-up on xl, 2-up on lg, single column on mobile (never 2-up at phone
  width — user QA rule).

## Elevation & Depth

- Shadows are minimal and functional — this direction favors **borders over shadows**.
- Level 0: flat — page backgrounds, text.
- Level 1: hairline border — cards, images, dividers.
- Level 2: soft card — single subtle shadow (0 1px 2px rgba(15,18,20,0.04), 0 8px 24px
  rgba(15,18,20,0.06)) for content cards.
- Level 3: featured — the OCT hero image and the ebook card get a deeper shadow
  (0 24px 48px rgba(15,18,20,0.10)) — reserved for the two most important surfaces.
- Dark mode: shadows nearly vanish; separation comes from surface tone steps
  (dark-paper → dark-paper-cool → dark-paper-deep).

## Shapes

- sm 8px: buttons, inputs.
- md 14px: cards, images, containers.
- lg 20px: hero panels, feature blocks.
- xl 24px: the ebook card, large media.
- pill 9999px: verdict badges, tags, avatars.
- **Never mix radii within a component.** Cards 14px everywhere; buttons 8px everywhere.

## Components

- **button-primary** — sage fill, white text, 14×24 padding, 8px radius, label type.
  Hover darkens. Active scale(0.98). Focus ring: 2px primary at 30% + 2px offset.
- **button-secondary** — paper-cool fill, ink text, hairline border, same metrics.
- **card** — white, hairline border, 14px radius, 28px padding, level-2 shadow.
  Hover: border darkens slightly + shadow deepens a step.
- **verdict badges** (signature element) — pill, 4×12 padding, 12px/600 +0.06em:
  - **Watching** = amber-soft / amber-watch
  - **Skeptical** = red-soft / red-flag
  - **Wait-and-see** = amber variant
  - **Proven** = green-soft / green-ok
- **callout** — tinted surface (red-soft for red flags, amber-soft for cautions), 14×18 padding,
  14px radius, hairline border in the tint's darker tone. Red-flag wording stays red (user rule).
- **hero** — two-column: headline + CTA left, **real OCT scan image right** (CC BY 2.0,
  Wikimedia Commons "Retina-OCT800.png", credited) framed in a hairline border with
  level-3 shadow. The scan is the visual anchor of the entire design.
- **nav** — white, hairline bottom border, subtle blur + shadow on scroll. Links 15px Inter 500;
  active = sage.
- **footer** — paper-deep surface, muted text, mono DOI links.

## Do's and Don'ts

Do:
- Let whitespace and hairlines do the structuring — this is a precision instrument, not a poster.
- Use Inter for everything; tracking compression at display sizes is the signature move.
- Keep sage as the *only* saturated interactive color; gold only for stars.
- Lead with the real OCT scan — real clinical imagery is the brand's credibility anchor.
- Keep red-flag language red (user rule), even in dark mode (#E5484D for dark red-flag text).
- Use mono for DOIs and citations — evidence-first branding.
- Maintain WCAG AA (4.5:1) on all text; ink-on-white is ~17:1 (AAA).

Don't:
- Don't use serifs anywhere — this direction is all-sans by definition.
- Don't use gradients on buttons or cards.
- Don't use illustrations of eyes where a real scan exists — NEI diagrams and OCT scans only.
- Don't exceed one accent color per screen; sage is the accent.
- Don't put 2-up grids at phone width — single column on mobile, always.
- Don't make the design louder than the evidence — no parallax on article pages, no auto-motion.
- Don't use emoji as design elements (site convention: text + SVG icons).
