# Oritura — Brand Tokens for Engineering (V9.0)

**Governing canon:** Oritura — Master Brand Bible, Persona Journeys & Developer Canon V9.0 (declared October 13–14, 2026). This file is a developer-facing extract; the Bible wins on any conflict. Do not reintroduce retired names, colors or type from earlier versions found in this repo's history.

## Architecture (two doors)
- **Door 1 — Worker App** (`oritura.app`): Aria (journaling) → AriaLit (paid tier) → Clareo (drafting layer inside the app, not a separate portal) → FirmataGlo (transparent hand-off) → Lavita (post-resolution).
- **Door 2 — FirmataPro** (`oritura.legal`): legal-partner portal. Positioned as an intake *feed* into firm tools (Filevine / Clio / Eve-compatible exports).
- **Ignita** is background intelligence. It never appears as a user-facing surface or navigation label.

## Five safeguards (product rules, not copy)
1. No legal advice — UPL boundary on every drafted output.
2. No prediction of outcomes — organize and map evidence; never show a predictive "case strength" score to workers.
3. Worker owns the data — export and delete are first-class.
4. Attorney holds judgment — hand-off, not recommendation.
5. Hash-chained evidence integrity — SHA-256 per item, neutral Bates prefix `ORI-`.

## Typography
| Role | Face | Notes |
|---|---|---|
| Display / headlines | Cormorant Garamond | 600–700 |
| UI / body | Inter | 400–600 |
| Metadata / hashes / timestamps | JetBrains Mono | 400 |

Playfair Display, DM Sans and IBM Plex Mono are retired.

## Color tokens
```css
:root {
  --ori-navy:      #0A1628; /* canvas */
  --ori-champagne: #F3E5AB; /* wordmark, primary accent on navy */
  --ori-cobalt:    #1A3A8F; /* Firmata / FirmataPro identity */
  --ori-lavender:  #C8B5E8; /* Lavita identity */
  --ori-ink:       #F5F3EE; /* primary text on navy */
  --ori-muted:     #9AA3B2; /* secondary text on navy */
}
```
Retired: Brand Magenta `#C2185B` as a parent color; Warm Dusk Ivory `#DFD3C3`; Electric Teal / Spark-Flame / Sun Gold portal palettes from V7.x unless re-approved in V9.x.

## Naming (do / don't)
| Use | Never |
|---|---|
| FirmataPro | Oritura Pro |
| Clareo (drafting layer) | Clareo Portal, Revela |
| Worker App / oritura.app | Voce |
| "Built for those about to rise." (if a tagline is required) | "Truth and resolve. Watching back." · "Dignity. Courage. On the Rise." |

## Motion & tone
Cinematic, restrained: slow fades, no bounce, no decorative icons. Plain-language, warm, never clinical toward workers; precise and data-dense toward firms.

## Pricing surfaces (for copy and plan pages)
AriaLit $19/mo · FirmataPro $499/mo per firm seat. Do not hard-code other prices from older specs.

_Source of truth: V9.0 Bible (Notion) and the V9.0 Master Artifact & Brand Index, Drive `ORITURA/00 Command & Canon/Canon — V9 (current)`._
