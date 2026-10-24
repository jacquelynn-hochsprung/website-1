# Oritura — Brand Tokens for Engineering (V9.0)

**Governing canon:** Oritura — Master Canonical & Business Bible V9.0 (Notion, declared Oct 13, 2026) and Master Brand Bible, Persona Journeys & Developer Canon V9.0 (Drive). The consolidated reading copy is **Oritura — Product Brand Bible, V9.0 Consolidated Edition (Oct 24, 2026)** in Drive `ORITURA/00 Command & Canon/Canon — V9 (current)`. The Bible wins on any conflict. Do not reintroduce retired names, colors, or type from this repo's history.

> Correction Oct 24, 2026: the first version of this file carried tokens that are not in V9.0 (JetBrains Mono, Champagne `#F3E5AB`, Cobalt `#1A3A8F`, "FirmataGlo"). They are removed below. The code in this repo already used IBM Plex Mono; the document now matches the code and the canon.

## Architecture (two doors)
- **Door 1 — Worker App** (`oritura.app`; domain ownership under founder review, `oritura.us` is owned): Aria (free vault, journaling, hashed capture) → AriaLit (paid statutory/scenario lens) → Clareo (drafting drawer inside the app, not a separate portal) → Lavita / Summit (post-case) with TrueExit (record-integrity audit) inside Lavita.
- **Door 2 — FirmataPro by Oritura** (`oritura.legal`): legal-partner portal. Flat-fee SaaS. Two-stage conflict-first intake (Model Rule 1.18).
- **Ignita** is the rule-based engine beneath both doors. Named in attorney-facing reports and investor technical material only; never a navigation tile.

## Five safeguards (product rules, not copy)
1. Legal information, not legal advice — UPL boundary on every drafted output.
2. No predictive claim scores and no directives to file or sue.
3. Mandatory governance stamp on every Ignita-assisted screen and export: `Preview. Not legal advice. Attorney-reviewed: false.`
4. Conflict-first handoff; worker authorizes transfer with granular redaction.
5. Hash-chained evidence integrity — SHA-256 per item (client-side on capture, server-side on upload), Bates prefix `ORI-` by default.

## Typography (Cormorant Elegance Canon)
| Role | Face | Spec |
|---|---|---|
| Display / headlines / masthead | Cormorant Garamond | 600–700 |
| Italic pivot phrases | Cormorant Garamond Italic | 400/600 italic — true italic, never synthetic oblique |
| Kickers, timestamps, hashes, Bates, disclaimers | IBM Plex Mono | Bold, uppercase, tracking 0.22em |
| Editorial body (marketing) | Georgia 18–20px or Inter 16–18px; Cormorant 18–22px for pull quotes | |
| App UI and tables (/app) | Inter | 400–600 |

Retired: Playfair Display, DM Sans, JetBrains Mono. Inter is never a display face.

## Color tokens
```css
:root {
  /* surfaces */
  --bg-cream:       #FAF7F2; /* Editorial Light canvas (worker app, standard marketing) */
  --ink:            #1A1A1A; /* primary text on light */
  --navy:           #003A70; /* brand primary, structural anchors on light */
  --navy-deep:      #0A1628; /* dark canvas end stop */
  --obsidian:       #050505; /* dark canvas start stop (hero, Ignita, cinematic) */
  --muted:          #6B7280;

  /* action */
  --cta-cyan:       #00F2FE; /* BEGIN IN PRIVATE pill, 16px diffuse glow */
  --cta-cyan-alt:   #4ECCA3;

  /* modules */
  --aria-yellow:    #F6D15B;
  --ignita-amber:   #B45309;
  --ignita-ember:   #FF6B1A;
  --clareo-slate:   #475569;
  --firmata-navy:   #1E3A5F;
  --lavita-amethyst:#7C4DFF; /* Lavita / TrueExit surfaces only */
  --lavita-amethyst-soft: #9B82C0;
  --lavita-lavender:#C8B5E8;
  --lavita-ice:     #A3C2DF;

  /* accents */
  --brand-berry:    #C2185B; /* corporate callout only; never parent equity; never with --ignita-ember on one surface */
  --fuchsia-alert:  #D946EF; /* alerts only */
}
```
Dark canvas: `linear-gradient(135deg, #050505, #0A1628)`. Light canvas: `#FAF7F2`, never `#FFFFFF`.

Retired: Champagne `#F3E5AB` · Cobalt `#1A3A8F` and `#0047AB` · Midnight Navy `#0D1B2A` as mandatory ground · Warm Dusk Ivory `#DFD3C3` · Electric Teal / Spark-Flame / Sun Gold module palettes (V7.x–V8.x).

## Motion
Easing `cubic-bezier(0.16, 1, 0.3, 1)`; hover 180ms, enter 300–400ms, drawers 350–500ms. Never `transition: all`. Scroll reveals: opacity + clip-path only, no translateY. Embers honor `prefers-reduced-motion: reduce`.

## Naming (do / don't)
| Use | Never |
|---|---|
| FirmataPro by Oritura | Oritura Pro · FirmataGlo |
| Clareo (drafting drawer) | Clareo Portal · Revela |
| Worker App / Aria / AriaLit | Voce |
| Lavita · Summit · TrueExit (inside Lavita) | Nascita · TrueExit as a standalone module |
| Ignita (engine) | Ignita as a portal or tile |

## Voice (locked lines only)
Tagline *Built for those about to rise.* · Masthead *A new operating system for truth. Where story becomes experience.* · Hero counter-weight *Some exits aren't endings.* · Sub-footer `SHE FOUND HER ARIA. THAT IS ORITURA. ● THE PLATFORM THAT WATCHES BACK.` Never: "Truth and resolve. Watching back." as lockup · "Dignity. Courage. On the Rise." · "Dignity. Bravery. Watching back." · "victim" · emojis.

## Pricing surfaces
AriaLit $19/mo · FirmataPro $499/mo per firm license. Flat-fee SaaS only; no referral, lead, or success-fee language.

## Footer standard
PORTALS: Aria · Clareo · Firmata · Lavita · TrueExit Badge — ENGINE: ● Ignita — AUDIENCES: For plaintiffs · For attorneys · For agencies · For partner voices — LEGAL & TRUST: Privacy · Terms · UPL & Professional Responsibility · Security & encryption · Chain of custody (FRE 901). Safe-harbor box verbatim from the Bible §5.5.
