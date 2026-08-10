# Lạc Việt Media Agency — Claude Implementation Contract

> **ENTRY GATE:** Do not begin implementation until `.webby/HANDOFF.json` status is `UI_SETUP_COMPLETE` and `.webby/WEBBY_LOCK.json` identifies the active UI revision.

## Authority

The visual design is complete and approved by the user. ChatGPT owns visual truth. You are the implementation executor, not the visual designer.

Do not redesign, substitute approved assets, replace typography, recolor the system, change approved spacing/layout because another option is easier, or invent missing visual decisions.

## Read before coding

1. `.webby/HANDOFF.json`
2. `.webby/WEBBY_LOCK.json`
3. `.webby/route-map.json`
4. `.webby/section-map.json`
5. `.webby/component-map.json`
6. `.webby/asset-manifest.json`
7. `.webby/placement-map.json`
8. `.webby/typography.json`
9. `.webby/tokens.json`
10. `.webby/responsive.json`
11. `.webby/interactions.json`
12. `design/master/MASTER_SPEC.md`
13. WEB/MOBILE SVG masters and production assets

## Implementation order

1. Static visual parity for `/` at desktop reference width.
2. Independent mobile composition following the mobile master/responsive contract.
3. Visual states and accessibility states.
4. Contact/nav interactions.
5. Only after static parity: optional motion/UX enhancements that obey the contract.

## Content placeholders

Metrics, testimonials, product catalog and contact destinations are explicit demo placeholders. Keep them clearly replaceable in data/config and do not represent them as verified facts.

## Compliance copy

Account recovery/appeal content must remain framed as legitimate support for rightful account owners. Do not add bypass/security-evasion claims, guaranteed recovery, unauthorized access language, or unverified inventory claims.

## Missing UI rule

If a required approved visual decision/resource is absent, create `.webby/requests/REQUEST-###.json` instead of guessing.

## Delivery receipt

After implementation milestone, publish `.webby/implementation/IMPLEMENTATION_RECEIPT.json` with consumed UI revision/commit, implementation commit, routes/components implemented, build/test status, blockers and preview reference if available.
