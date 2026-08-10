# Lạc Việt Media Agency — GĐ2 SVG Master

Status: `MASTER_READY`
Mode: `SVG_MASTER`
Approved direction: `PA1_BLACK_GOLD_LUXURY_CORPORATE`
Version: `1.0`

## Canonical frames

- `design/master/svg/01_Home_WEB_MASTER.svg` — reference viewport 1920px
- `design/master/svg/01_Home_MOBILE_MASTER.svg` — reference viewport 1080px

The SVGs are structured masters, not screenshot wrappers. Sections/components use stable IDs and normal UI copy remains live text.

## Canonical design contracts

- `design/master/tokens.json`
- `design/master/typography.json`
- `design/master/font-manifest.json`
- `design/master/component-system.json`
- `design/master/component-states.json`
- `design/master/responsive.json`
- `design/master/SVG_QA_REPORT.json`
- `assets/source/logos/SOURCE_MANIFEST.json`

## Visual language

- Near-black matte background.
- Restrained metallic-gold highlights.
- Premium Vietnamese-inspired identity derived from the supplied Lạc Việt logo.
- Elegant borders and low-intensity glow; no neon cyberpunk, gamer styling or generic blue SaaS look.
- Desktop and mobile are separate compositions, not simple proportional scaling.
- UI/body typography uses the locked Inter family contract; the supplied brand wordmark is never rebuilt with type.

## Core composition

1. Header / mobile header
2. Hero + primary consultation CTA
3. Platform/trust strip
4. Proof metrics
5. Service grid
6. Digital-account/software area
7. Why choose Lạc Việt
8. Five-step process
9. Testimonials / trust proof
10. Final CTA
11. Footer

## Source authority

The user-supplied raster logo remains the authoritative brand source until an original AI/SVG/EPS/PDF vector is supplied. Its exact dimensions and SHA-256 are locked in `assets/source/logos/SOURCE_MANIFEST.json`.

The GĐ2 master intentionally does not redraw the logo by eye. Actual binary placement/binding belongs to GĐ3 production asset packaging and is not a remaining design decision.

## Placeholder rule

The user explicitly authorized demo data during design. Customer counts, handled-account counts, success rates, years of experience, testimonials, product/account examples and contact details remain `PLACEHOLDER` until replaced before production.

## Copy/compliance rule

Public recovery copy is framed as legitimate appeal/support for the rightful account owner. Do not claim bypassing platform security, unauthorized access, guaranteed recovery, or unauthorized/shared credentials.

## GĐ2 acceptance

- Approved direction locked: PASS
- WEB master: PASS
- MOBILE master: PASS
- Design tokens: PASS
- Typography/font acquisition contract: PASS
- Component coverage: PASS
- Interactive visual states: PASS
- Responsive composition: PASS
- Source authority: PASS
- SVG structural/fidelity review: PASS with GĐ3 logo-binary binding required

`MASTER_READY = true`

GĐ2 is complete. Next phase is GĐ3 — production asset decomposition, placement maps, manifests, handoff/lock and validator gate.
