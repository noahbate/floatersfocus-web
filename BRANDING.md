# Floaters Focus — Brand Standards

Version: 1.0 · Author: NP Bate, Ed.S. · Last updated: 2026-08-12
Live site: **floatersfocus.org**

This is the **brand-level** standards document: identity, voice, and the rules for
using the brand. It works alongside two other documents:

| Document | Role |
|----------|------|
| `DESIGN.md` | Token-level design spec (exact colors, type scale, radii, shadows). The source of truth for *values*. |
| `BRANDING.md` (this file) | Human-level brand standards: *what we are, how we sound, what we allow and refuse.* |

`DESIGN.md` changes when the palette or type scale changes. `BRANDING.md` changes
when the brand's identity, voice, or standards change. Keep the two in agreement —
a token change should usually be mirrored as a note here.

---

## 1. Brand identity

**One-line:** *Evidence-backed guidance for floaters, macular health, and eye
discomfort — every claim linked to the actual paper.*

**Positioning:** A calm, precise, clinical counterpart to a scary subject. We are
the plain-spoken friend who read the studies so the reader doesn't have to. We
reduce fear with facts, not with reassurance that isn't earned.

**Three brand pillars**
1. **Evidence first.** Every claim that asserts a fact is graded and linked to the
   source paper. Weak evidence is labeled weak evidence. If it didn't survive a
   trial, we say so.
2. **Human, not automated.** First-person, specific, personal. The site reads like
   someone who actually had PVD show up uninvited in 2020 — because that's who wrote
   it. No dictionary-definition openers, no template voice, no corporate cheer.
3. **Calm precision.** Cool clinical surfaces, one restrained accent, generous
   whitespace. It looks like a precision instrument because the content is
   precision-checked.

**Audience:** Adults 20–45 with floaters/PVD (Instagram-forward), and 55+ with AMD
and dry eye (Facebook groups). The reader is anxious and often already being sold
to. We are the credible exception.

**Author / reviewer:** The site is authored and medically reviewed by NP Bate, Ed.S.
Every page carries a visible "Reviewed by NP Bate, Ed.S." line and last-reviewed
date. This is a credibility asset — never obscure it.

---

## 2. Voice & tone

**Default register (locked):** the PVD survival guide — first-person, personal,
specific, reassuring but never falsely soothing.

> "Take a deep breath. You are not alone, and you are not going blind."

**The voice rules (hard):**
- **One human sentence before every template block.** Structure serves the
  evidence hierarchy, but never let a section open with a dry heading and bullets.
- **Kill repeated slogans.** A slogan repeated across pages is not a voice; it's a
  tell. Vary it per surface.
- **No negative parallelism** ("not X, just Y") as filler.
- **No headers restated by their body.** If the body just restates the heading, the
  body is wrong.
- **No dictionary-definition openers.** Open a supplement section with the cultural
  hook, not "Extract of the maidenhair tree's leaves."
- **Prose over bullets** where the content doesn't *need* a list. Bullets are for
  evidence hierarchies and checklists, not for everything.

**Tone targets:** calm · direct · plain-spoken · modestly opinionated (it's OK to
say "I'd actually spend money on this" or "great folklore, bad evidence") · never
cheerleading, never fear-mongering, never condescending.

**Tone to avoid:** AI-slop tells — see `references/content-voice-audit.md` for the
full list. In short: no repeated slogans, no fragmented headers, no template
uniformity, no dictionary openings, no gratuitous checkmark lists.

**Red-flag urgency is real and specific:** emergency symptoms are written with
urgency but no panic — "That's an ER visit, not a Google search." The word **red**
stays red, even in dark mode (see §5).

---

## 3. Wordmark & logo

- **Wordmark:** the text "Floaters Focus" in Inter (the display weight). No symbol
  or icon currently exists; the OCT B-scan hero image serves as the brand's visual
  anchor, not a logo.
- Do **not** invent a logo, mascot, or emoji glyph as a stand-in. Emoji-as-icon
  grids were explicitly rejected.
- The header renders the wordmark in ink on light backgrounds and light cream on
  dark backgrounds. Always verify both.

---

## 4. Color

The authoritative values live in `DESIGN.md` and in the tokens in
`src/styles/global.css`. The brand-level meaning:

| Token | Brand meaning | Use |
|-------|--------------|-----|
| **Sage** `#3F6B4F` | The single accent — clinical, calm, trustworthy | Primary buttons, links, key CTAs. Never more than one accent at a time. |
| **Ink** `#0F1214` | Readable, honest | Primary text. |
| **Cream / paper** `#F5F6F7` / `#FFFFFF` | Cool clinical surface | Backgrounds, cards. Cool, never warm. |
| **Red-flag** `#B3261E` | Emergency / seek care now | Only for genuinely urgent clinical signals. The word "red flag" stays red. |
| **Amber** (verdict WATCHING) | Low-risk, watching | Treatment verdict pills. |
| **Terracotta** | Secondary accent (used sparingly) | Secondary CTA. |

**Rules:**
- **One accent at a time.** Sage is the brand accent; terracotta is the secondary.
  Do not introduce a rainbow.
- **Semantic colors keep their hue.** In dark mode, accent text is *brightened*
  (lighter same-hue variant), never re-hued. Red stays red, sage stays sage.
- **Cream text on dark stays cream** — do not remap it to ink.
- **Buttons need a dark-mode surface override** — brighten the button surface in
  dark mode, not just the text.

---

## 5. Typography

- **Inter** — all UI text and headings. The only typeface for prose and titles.
- **JetBrains Mono** — reserved for *verification signals*: DOI links, citation
  lines, anything machine-verifiable. "Mono = verifiable."
- **Compressed display tracking** (`-0.03em`) on large display headings — the
  Apple-style compressed look.
- Weights: display/h1/h2/h3 use 600 (semibold); body uses 400. Tight line-height
  on headings (1.08–1.2), comfortable leading on body.
- No serif, no script, no decorative face. All-sans is a brand commitment.

---

## 6. Imagery

- **Hero:** the live OCT B-scan (`oct-scan.png`, Wikimedia Commons, **CC BY 2.0 —
  attribution credited**). Keep the attribution. Never hotlink a copyrighted
  retinal image (AAO's are off-limits).
- **Eye diagram:** `eye-diagram-side-view.png` — National Eye Institute, NIH,
  **public domain**, credited anyway.
- **Amsler grid:** site-generated grids are original; the wavy variant is the real
  NEI image (public domain). Never hotlink copyrighted sources.
- **Rule:** images must be our own, public domain, or clearly-licensed (CC). Never
  a copyrighted hotlink. Credit licenses visibly.

---

## 7. Evidence & citation standards (brand-critical)

This is the brand's whole reason to exist. Non-negotiable:
- **Every data-backed claim links to the actual paper** — DOI → `https://doi.org/<doi>`
  as a clickable "View study" link, rendered in mono.
- **Evidence hierarchy** (about page): what the evidence actually says → what's a
  waste of money and why → when you need a doctor → products that match the science.
- **Weak evidence is labeled weak.** Single small trials are "hypothesis-generating."
  A meta-analysis that says no is reported as no. We never inflate.
- **No FDA-approval claims.** Supplements are "investigational, not FDA-approved,
  not replacements for observation."
- **Verify every DOI via CrossRef before shipping.** A wrong DOI is worse than a
  missing one. Never ship a DOI recalled from memory.
- **Do not resample evidence detail** — keep exact study specs (N, design, doi,
  effect sizes) verbatim from the papers.
- **Every claim's author:** we are a nurse practitioner with personal skin in the
  game (2020 PVD, glaucoma-suspect watchlist, macular pucker). Personal history is
  used to shape framing but **not published without explicit consent.**

---

## 8. Layout & behavior rules (do / don't)

**Do:**
- Stack two-column lists/prose into single-column with colored left borders on
  phones — do not let side-by-side grids break at narrow widths.
- Single-column card grids below `lg` (1024px). 2-col at `lg` minimum, 3–4 col only
  at `xl` (1280px).
- Icon rows: `items-start` + wrapper for long wrapping text; `items-center` only for
  short single-line rows. Icons in headings get `items-start` + top offset.
- Token-only colors; no hardcoded hex in components.
- Verify BOTH light and dark mode on every theme change (computed-style scan,
  target: 0 invisible-text elements).

**Don't:**
- No emoji-as-icon grids.
- No stray comments after layout components.
- No gradient hero backgrounds on inner pages (plain white + hairline border).
- No opacity-modifier utility (`.bg-white/90`, `.bg-ink/10`) without its own dark
  override.
- No `!important` link/text-color rule that can clobber buttons (buttons are
  `<a class="btn">` site-wide; scope link rules with `:not(.btn)`).
- No affiliate/storefront content ahead of its evidence context (evidence-before-
  storefront is mandatory).

---

## 9. Content structure conventions

- **Section order on condition pages (mandatory):** Evidence-Based Treatments →
  Amsler grid (where relevant) → Low-Risk Adjunctive Options → Products with Data
  Behind Them → What Doesn't Work. The reader sees the science and caveats for an
  ingredient *before* any affiliate link for it.
- **Red flags** are visually distinct, urgent, and kept genuinely red.
- **Verdict pills:** WATCHING (amber) / SKEPTICAL (red) for supplements. Both theme
  variants are defined.

---

## 10. Contact & commerce

- **Contact is mailto: only.** No backend API. Submitting opens the visitor's email
  client pre-filled.
- **Affiliate links** are disclosed ("We may earn a commission... at no extra cost
  to you"). Keep the disclosure visible.
- **Amazon links** must be well-formed search URLs (`/s?k=<terms>`) — never bare
  paths or malformed path+query hybrids. Verify each resolves before shipping.

---

## 11. Change process

- Brand **standards** changes → edit this file.
- **Design spec** (tokens) changes → edit `DESIGN.md` and re-lint with
  `npx -y @google/design.md lint DESIGN.md` (0 errors, 0 WCAG failures required).
- After any content/design change: rebuild, verify routes, run the alignment
  watchdog, and confirm the live site + ebook PDF are current before reporting
  success. See the `floatersfocus-web` skill for the full deploy + verification
  recipe.
- This file lives at `frontend/BRANDING.md` and is versioned with the site. Keep it
  accurate — it is the durable record of *what the brand is* so future edits stay
  on-brand.
