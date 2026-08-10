---
version: alpha
name: Floaters Focus — Editorial Health
description: Warm editorial premium for an evidence-based eye-health brand. Serif display headlines over warm paper, a confident sage accent, whisper-thin borders, generous vertical rhythm. Trustworthy like a $200/yr health publication, warm like a letter from a friend who's been through it.
colors:
  primary: "#3F6B4F"
  primary-dark: "#2E4F3A"
  on-primary: "#FFFFFF"
  ink: "#1C211D"
  ink-soft: "#4A524B"
  muted: "#7A8379"
  paper: "#FDFCF9"
  paper-warm: "#F6F3EC"
  paper-deep: "#EFEAE0"
  border: "rgba(28, 33, 29, 0.10)"
  gold: "#B8860B"
  gold-soft: "#F7EDD8"
  red-flag: "#B3261E"
  red-soft: "#F9E7E5"
  blue-info: "#1F5F8B"
  blue-soft: "#E7F0F6"
  green-ok: "#276B2C"
  green-soft: "#E8F2E9"
  amber-watch: "#8F5300"
  amber-soft: "#F9EFDC"
  dark-ink: "#EDEAE2"
  dark-ink-soft: "#C9C5BA"
  dark-muted: "#8F938A"
  dark-paper: "#161A17"
  dark-paper-warm: "#1D221E"
  dark-paper-deep: "#242A25"
  dark-border: "rgba(237, 234, 226, 0.12)"
  dark-primary: "#7FAF8D"
  dark-on-primary: "#0E1410"
typography:
  display:
    fontFamily: Fraunces
    fontSize: 3.5rem
    fontWeight: 600
    lineHeight: 1.05
    letterSpacing: "-0.015em"
  h1:
    fontFamily: Fraunces
    fontSize: 2.75rem
    fontWeight: 600
    lineHeight: 1.1
    letterSpacing: "-0.01em"
  h2:
    fontFamily: Fraunces
    fontSize: 2rem
    fontWeight: 600
    lineHeight: 1.15
    letterSpacing: "-0.005em"
  h3:
    fontFamily: Fraunces
    fontSize: 1.5rem
    fontWeight: 600
    lineHeight: 1.25
    letterSpacing: "0em"
  lead:
    fontFamily: Inter
    fontSize: 1.25rem
    fontWeight: 400
    lineHeight: 1.6
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
    letterSpacing: "0.08em"
  mono:
    fontFamily: "JetBrains Mono"
    fontSize: 0.875rem
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: "0em"
rounded:
  sm: 6px
  md: 12px
  lg: 20px
  xl: 28px
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
    padding: 12px 20px
    typography: label
  button-primary-hover:
    backgroundColor: "{colors.primary-dark}"
  button-primary-dark:
    backgroundColor: "{colors.dark-primary}"
    textColor: "{colors.dark-on-primary}"
    rounded: "{rounded.sm}"
    padding: 12px 20px
    typography: label
  button-secondary-dark:
    backgroundColor: "{colors.dark-paper-warm}"
    textColor: "{colors.dark-ink}"
    rounded: "{rounded.sm}"
    padding: 12px 20px
    typography: label
  nav-link-dark:
    textColor: "{colors.dark-ink-soft}"
    typography: body-sm
  footer-bg-dark:
    backgroundColor: "{colors.dark-paper-deep}"
  border-dark:
    backgroundColor: "{colors.dark-border}"
  button-secondary:
    backgroundColor: "{colors.paper-warm}"
    textColor: "{colors.ink}"
    rounded: "{rounded.sm}"
    padding: 12px 20px
    typography: label
  button-secondary-hover:
    backgroundColor: "{colors.paper-deep}"
  card:
    backgroundColor: "{colors.paper}"
    textColor: "{colors.ink}"
    rounded: "{rounded.md}"
    padding: 24px
  card-hover:
    backgroundColor: "{colors.paper-warm}"
  card-dark:
    backgroundColor: "{colors.dark-paper}"
    textColor: "{colors.dark-ink}"
    rounded: "{rounded.md}"
    padding: 24px
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
    padding: 16px 20px
  callout-amber:
    backgroundColor: "{colors.amber-soft}"
    textColor: "{colors.ink}"
    rounded: "{rounded.md}"
    padding: 16px 20px
  nav-link:
    textColor: "{colors.ink-soft}"
    typography: body-sm
  nav-link-active:
    textColor: "{colors.primary}"
    typography: body-sm
  footer-bg:
    backgroundColor: "{colors.paper-deep}"
---

## Overview

Floaters Focus is an evidence-first eye-health resource — floaters, PVD, macular health, dry eye,
macular pucker. The audience arrives anxious and leaves calmer. The design must do two jobs at once:

1. **Signal credibility** — this is a health-information brand; it must feel researched, precise,
   and worth trusting (like a well-designed medical journal meets a modern health publication).
2. **Signal warmth** — the author has lived through every condition on the site. The design should
   feel like it was written by a person, for a person — never sterile, never corporate, never clinical.

The result is **warm editorial premium**: serif display headlines (Fraunces) carry the voice and
humanity; Inter body text carries the density and readability of a long-form reading experience;
warm paper backgrounds (never cold gray) give everything a tactile, book-like feel; and a single
confident sage green handles interaction, exactly as one accent should.

Every layout decision follows this rule: **the content is the hero, the design is the frame.**

## Colors

- **Primary (#3F6B4F)** — "Sage" — the only saturated color in the core UI. Buttons, links,
  active nav, checkmarks. Darker variant (#2E4F3A) for hover. On dark mode it lightens to
  #7FAF8D so it keeps contrast against dark surfaces.
- **Ink (#1C211D)** — near-black with a green undertone, never pure black. Headings and body.
  In dark mode it inverts to warm off-white (#EDEAE2).
- **Paper (#FDFCF9)** — the canvas. Warm white with a faint cream cast. Alt surfaces:
  paper-warm (#F6F3EC) for section alternation, paper-deep (#EFEAE0) for footers.
- **Gold (#B8860B)** — reserved for star ratings and affiliate-accent moments only.
- **Semantic set** — red-flag (#B3261E, red flags stay red — user rule), green-ok (#2E7D32),
  amber-watch (#A05E03), blue-info (#1F5F8B). Each has a soft tint background for callouts
  and verdict badges.

## Typography

- **Fraunces** (Google Fonts) — display serif for h1/h2/h3 and hero. Optical size axis on,
  weight 600, tight line-height (1.05–1.25), subtle negative tracking. This is where the
  "editorial premium" identity lives.
- **Inter** (Google Fonts) — everything else: body, UI, labels. Line-height 1.7 for reading
  comfort; labels are 12px, weight 600, +0.08em tracking, all-caps optional.
- **JetBrains Mono** — reserved for DOIs, citations, and any code-adjacent text (matches the
  evidence-first brand; DOI strings in mono signal "this is verifiable").
- Scale: 3.5rem display → 2.75 h1 → 2rem h2 → 1.5rem h3 → 1.25 lead → 1.0625 body.
  Mobile: display scales to 2.5rem, h1 to 2.25rem.

## Layout

- 8px base spacing scale (xs 4 / sm 8 / md 16 / lg 24 / xl 40 / xxl 64 / section 96).
- Max content width ~1200px; reading measure ~65ch for article text.
- **Section rhythm:** generous vertical padding (96px desktop, 64px mobile). Sections
  alternate paper → paper-warm → paper to create rhythm without borders.
- **No hard section borders** — separation comes from background shifts and whitespace,
  Notion-style. Whisper borders (1px, 10% ink) only on cards, images, and dividers.
- Grids: condition cards 4-up on xl, 2-up on lg, single column on mobile (never 2-up on
  phone-width — user QA rule).

## Elevation & Depth

- Depth is felt, not seen: layered multi-stop shadows with individual opacity ≤ 0.05.
- Level 0: flat — page backgrounds, text.
- Level 1: whisper border — cards, images, dividers.
- Level 2: soft card — 3–4 layer shadow stack (max 0.04) for content cards, guide cards.
- Level 3: deep card — 5-layer stack (max 0.06, 52px blur) for modals, hero panels, the
  ebook download card (the single most important conversion element).
- Dark mode: shadows reduce further; depth comes from surface tone differences
  (dark-paper → dark-paper-warm → dark-paper-deep) instead.

## Shapes

- sm 6px: buttons, inputs, small interactive elements.
- md 12px: standard cards, images, containers.
- lg 20px: hero cards, feature panels.
- xl 28px: the ebook card, large media.
- pill 9999px: verdict badges, tags, status labels, avatars.
- **Never mix radii within a component.** Cards are 12px everywhere; buttons 6px everywhere.

## Components

- **button-primary** — sage fill, white text, 12×20 padding, 6px radius, 12px/600 label type.
  Hover darkens to #2E4F3A. Active scale(0.98). Focus ring: 2px primary at 30% + offset.
- **button-secondary** — paper-warm fill, ink text, same metrics. Hover paper-deep.
- **card** — paper, whisper border, 12px radius, 24px padding, soft shadow. Hover: paper-warm
  fill + slightly stronger shadow. Image cards: image flush to top, 12px top radius only.
- **verdict badges** (signature element) — pill, 4×12 padding, 12px/600 tracking+0.08em:
  - **Watching** = amber-soft bg / amber-watch text (saffron, astaxanthin, manuka honey)
  - **Skeptical** = red-soft bg / red-flag text (bilberry)
  - **Wait-and-see** = amber variant (ginkgo)
  - **Proven** = green-soft bg / green-ok text (AREDS2, anti-VEGF)
- **callout** — tinted surface (red-soft for red flags, amber-soft for cautions), 16×20
  padding, 12px radius, whisper border in the tint's darker tone. Red-flag callouts keep the
  word "red flag" in red (user rule).
- **nav** — paper background, subtle blur + border on scroll. Links 15px Inter 500, ink-soft;
  active = sage. Right-aligned CTA.
- **footer** — paper-deep surface, muted text, mono DOI links.

## Do's and Don'ts

Do:
- Let whitespace do the separating — sections breathe, borders whisper.
- Use Fraunces for every heading; it is the brand's voice.
- Keep sage as the *only* saturated interactive color; gold only for stars.
- Use pill badges for verdicts — they're the site's signature trust signal.
- Keep red-flag language red (user rule), even in dark mode (#E5484D for dark red-flag text).
- Use mono for DOIs and citations — evidence-first branding.
- Maintain WCAG AA (4.5:1) on all text; ink-on-paper is ~14:1 (AAA).

Don't:
- Don't use pure black (#000) or pure gray — warm everything.
- Don't use gradients on buttons or cards (medical credibility ≠ fintech glow).
- Don't use stock-photo clip art of eyes — custom SVG illustrations or public-domain
  diagrams (NEI) only.
- Don't exceed one accent color per screen; sage is the accent.
- Don't put 2-up grids at phone width — single column on mobile, always.
- Don't make the design louder than the content — no auto-playing motion, no parallax
  on article pages.
- Don't use emoji as design elements (site convention: text + SVG icons).
