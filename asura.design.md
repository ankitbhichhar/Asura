# Asura Design Document

## Selected Design System
Domain Tag: Gaming
Color Palette: Option 1
Typography: Option 1
Rationale: Asura is a terminal-based AI game setup agent — the neon purple + rose palette and bold Russo One / Chakra Petch pairing match the dark, techy, gaming aesthetic perfectly. The terminal green accent reinforces the command-line identity.

## Palette

| Role | Hex | Usage |
|------|-----|-------|
| Primary | #9453EE | CTAs, badges, accent borders, stat numbers |
| Secondary | #B095F7 | Links, hover states, subtle highlights |
| Accent | #F1324B | Hot tags, hover backgrounds, error states |
| Background | #191835 | Page background |
| Foreground | #E2E8F0 | Body text, headings |
| Card | #1D1C2E | Card surfaces |
| Muted | #272632 | Terminal header, form fields |
| Muted Foreground | #94A3B8 | Secondary text, metadata |
| Border | #4C1D95 | Card borders, dividers |
| Ring | #7C3AED | Focus outlines |
| Terminal Background | #0D0D1A | Terminal windows, footer |
| Terminal Foreground | #00FF88 | Terminal text, success states |
| Section Alt | #14142B | Community, Contact section backgrounds |

## Typography

- **Headings**: Russo One — bold, impactful, gaming-forward
- **Body**: Chakra Petch — technical, readable, complements the terminal aesthetic
- **Type Scale**: Major Third (1.250)
  - xs: 0.64rem | sm: 0.8rem | base: 1rem | md: 1.25rem
  - lg: 1.563rem | xl: 1.953rem | 2xl: 2.441rem | 3xl: 3.052rem | 4xl: 3.815rem

## Style Direction

**Dark OLED / Gaming Terminal hybrid**
- Near-black backgrounds with deep purple tones
- Neon terminal green for code/success states
- Sharp borders with purple glow on hover
- Monospace terminal window in the hero
- No glassmorphism — solid, grounded surfaces

## Sections

1. **Nav** — Sticky, blurred backdrop, logo + links
2. **Hero** — Split layout: headline + CTA left, animated terminal right
3. **Games** — 6-card grid of repacks with tags and metadata
4. **Features** — 6 feature cards with inline SVG icons
5. **Community** — Stats grid + CTA
6. **News** — 3 article cards with images
7. **Contact** — Split: info + form
8. **Footer** — 4-column: brand + 3 link columns + socials

## Interactions

- Cards fade in on scroll via IntersectionObserver
- Buttons lift + glow on hover
- Terminal cursor blink animation
- Mobile hamburger menu
- All motion respects `prefers-reduced-motion`
