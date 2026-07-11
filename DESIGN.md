# Vulna design system

## Theme
Dark only. Scene: a homelabber at 11pm in a dim office lit by rack LEDs, clicking through from a GitHub README.

## Color (OKLCH, Committed strategy: teal carries the surface)
- Brand teal (logo, drench band): #006666 ≈ oklch(0.47 0.09 194)
- Background: oklch(0.16 0.012 210)
- Raised surface: oklch(0.20 0.016 205)
- Border: oklch(0.30 0.02 200)
- Text: oklch(0.93 0.008 190)
- Muted text: oklch(0.68 0.02 195)
- Accent (bright teal, links/highlights on dark): oklch(0.80 0.12 185)
- Never pure #000/#fff; all neutrals tinted toward hue 195-210.

## Typography
- Single committed family: Archivo (Google Fonts), weights 400-800, tight tracking on display sizes. Industrial-signage sturdiness fits the appliance/hardware story.
- JetBrains Mono for code, terminal output, spec values (literal terminal register, not costume).
- Fluid clamp() heading scale, ratio ≥ 1.25. Body line length ≤ 70ch.

## Layout
- Left-aligned, asymmetric hero (copy left, topology SVG right: dashboard + scouts).
- Features as numbered rows, not card grids.
- Deployment tiers (VulnaDash / VulnaScout) as a spec-sheet table.
- Quickstart band drenched in #006666.

## Motion
- Subtle staggered entrance on hero, pulse animation along diagram links. ease-out-quart. Respect prefers-reduced-motion.

## Bans (inherited)
No gradient text, no side-stripe borders, no identical icon-card grids, no repeated uppercase kicker labels, no em dashes in copy.
