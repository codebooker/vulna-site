# Vulna design system

## Direction

An editorial security operations site: composed, technical, and visibly useful.
The product interface is the hero rather than an abstract cyber illustration.
The visual language borrows from field equipment, high-quality technical
publishing, and a modern network operations center without falling into neon
"hacker" styling.

## Color

- Ink: `#07110f`
- Raised ink: `#101f1c`
- Paper: `#edf3ee`
- Paper secondary: `#d9e3dc`
- Brand teal: `#18b7a0`
- Deep teal: `#08796c`
- Signal lime: `#c8f46b`
- Warning amber: `#f0b95a`
- High-risk coral: `#ee806d`

Teal identifies product structure and active state. Lime is reserved for safe,
live, or ready states and primary calls to action. Coral and amber appear only
inside product evidence, never as decoration.

## Typography

- Manrope for product and editorial text, weights 400 through 800.
- IBM Plex Mono for scope, state, identifiers, controls, and terminal content.
- Display headings use tight tracking and short line lengths. Body copy stays at
  comfortable reading measure with generous line height.

## Layout and components

- The hero pairs an assertive editorial headline with a realistic scan workspace.
- Architecture is explained before the full feature set so Local Scout,
  VulnaScout, and VulnaRelay are never confused.
- Capabilities use an asymmetric operations board rather than repeated icon cards.
- Light "paper" sections create major chapter changes inside the dark shell.
- Borders, spacing, and typography carry hierarchy. Decorative icons are avoided.

## Motion

- Short reveal transitions and a restrained live-status pulse.
- No scroll hijacking, parallax, or continuous canvas effects.
- `prefers-reduced-motion` removes all meaningful motion.

## Voice

Direct, technically honest, and calm. No fake customer counts, vanity metrics,
open-core ambiguity, or "book a demo" language. Pre-1.0 status, Linux endpoint
requirements, local data boundaries, and authorized-use constraints stay visible.
