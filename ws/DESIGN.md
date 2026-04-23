# Design System (Warm Tech Variant)
*Inspired by Claude's color palette, driven by Space Grotesk*

## 1. Visual Theme & Atmosphere

This interface is a modern, warm tech lab reimagined as a product page — approachable, precise, and quietly innovative. The entire experience is built on a parchment-toned canvas (`#f5f4ed`) that deliberately evokes the feeling of high-quality paper rather than a sterile digital surface. Where most tech-forward designs lean into cold, futuristic aesthetics, this design radiates human warmth while maintaining a distinct geometric edge.

The signature move is the **Space Grotesk** typeface — a proportional sans-serif derived from Space Mono. It gives every headline a slightly quirky, geometric, and tech-forward character. Combined with the warm, earthy palette of terracotta (`#c96442`), charcoal, and muted green, the visual language says "approachable innovation" rather than "intimidating tool." The Space Grotesk headlines breathe at tight-but-comfortable line-heights (1.10–1.30), creating a cadence that feels distinctly modern and structured.

What makes this design truly distinctive is the contrast between the highly structured, geometric Space Grotesk font and the warm neutral palette. Every gray has a yellow-brown undertone (`#5e5d59`, `#87867f`, `#4d4c48`) — there are no cool blue-grays anywhere. Borders are cream-tinted (`#f0eee6`, `#e8e6dc`), shadows use warm transparent blacks, and even the darkest surfaces (`#141413`, `#30302e`) carry a barely perceptible olive warmth.

**Key Characteristics:**
- Warm parchment canvas (`#f5f4ed`) evoking premium paper, not screens
- **Space Grotesk** type family: For all headings, large text, and prominent UI elements, providing a geometric tech edge.
- Terracotta brand accent (`#c96442`) — warm, earthy, deliberately un-tech
- Exclusively warm-toned neutrals — every gray has a yellow-brown undertone
- Ring-based shadow system (`0px 0px 0px 1px`) creating border-like depth without visible borders
- Modern tech pacing with generous section spacing and crisp sans-serif hierarchy

## 2. Color Palette & Roles

| Color | Name | Hex Code | Role |
| :---: | :--- | :--- | :--- |
| ⬛ | **Brand Black** | `#000000` | Primary Dark Surface |
| 🟪 | **Brand Navy** | `#4C4C80` | Secondary Dark Surface / Accents |
| 🟥 | **Brand Rose** | `#E11D48` | Primary CTA & Gradient Accent |
| 🟧 | **Brand Orange** | `#F97316` | Secondary Gradient Accent |
| 🟨 | **Parchment** | `#f5f4ed` | Primary Light Canvas |
| ⬜ | **Ivory** | `#faf9f5` | Light Surface Canvas |
| ⬛ | **Near Black** | `#141413` | Primary Text |

### Primary
- **Warm Near Black** (`#141413`): The primary text color.
- **Brand Black** (`#000000`): The primary dark section background. It provides maximum contrast against the vibrant gradients.
- **Brand Navy** (`#4C4C80`): Secondary dark elements and accents.
- **Brand Rose** (`#E11D48`): A vibrant primary CTA and accent color. Used prominently in gradients.
- **Brand Orange** (`#F97316`): A vibrant secondary accent. Frequently paired with Brand Rose to create striking gradients.

### Secondary & Accent
- **Error Crimson** (`#b53333`): A deep, warm red for error states — serious without being alarming.
- **Focus Blue** (`#3898ec`): Standard blue for input focus rings — the only cool color in the entire system, used purely for accessibility.

### Surface & Background
- **Parchment** (`#f5f4ed`): The primary page background. The emotional foundation of the entire design.
- **Ivory** (`#faf9f5`): The lightest surface — used for cards and elevated containers.
- **Pure White** (`#ffffff`): Reserved for specific button surfaces and maximum-contrast elements.
- **Warm Sand** (`#e8e6dc`): Button backgrounds and prominent interactive surfaces.
- **Dark Surface** (`#30302e`): Dark-theme containers, nav borders, and elevated dark elements.
- **Deep Dark** (`#141413`): Dark-theme text color and deep UI elements.

> **Note:** The primary dark section background is **Brand Black (`#000000`)**, not Deep Dark or Dark Surface. Use `#000000` for all full-width dark sections.

### Neutrals & Text
- **Charcoal Warm** (`#4d4c48`): Button text on light warm surfaces.
- **Olive Gray** (`#5e5d59`): Secondary body text — a distinctly warm medium-dark gray.
- **Stone Gray** (`#87867f`): Tertiary text, footnotes, and de-emphasized metadata.
- **Dark Warm** (`#3d3d3a`): Dark text links and emphasized secondary text.
- **Warm Silver** (`#b0aea5`): Text on dark surfaces.

### Semantic & Accent
- **Border Cream** (`#f0eee6`): Standard light-theme border.
- **Border Warm** (`#e8e6dc`): Prominent borders, section dividers, and emphasized containment.
- **Border Dark** (`#30302e`): Standard border on dark surfaces.
- **Ring Warm** (`#d1cfc5`): Shadow ring color for button hover/focus states.
- **Ring Subtle** (`#dedc01`): Secondary ring variant for lighter interactive surfaces.
- **Ring Deep** (`#c2c0b6`): Deeper ring for active/pressed states.

## 3. Typography Rules

### Font Family
- **Headline / Prominent UI**: `Space Grotesk`, with fallback: `system-ui, sans-serif`
- **Body Standard**: `Poppins` (or similar geometric sans-serif), with fallback: `system-ui, sans-serif`
- **Code**: `Space Mono`, with fallback: `monospace`

*Note: Space Grotesk is a Google Font (https://fonts.google.com/specimen/Space+Grotesk). It gives the warm palette a modern, tech-focused edge.*

### Hierarchy

| Role | Font | Size | Weight | Line Height | Letter Spacing | Notes |
|------|------|------|--------|-------------|----------------|-------|
| Display / Hero | Space Grotesk | 64px (4rem) | 600 | 1.10 (tight) | -1px | Maximum tech impact |
| Section Heading | Space Grotesk | 52px (3.25rem) | 600 | 1.20 (tight) | -0.5px | Feature section anchors |
| Sub-heading Large | Space Grotesk | 36px (~2.3rem) | 500 | 1.30 | normal | Secondary section markers |
| Sub-heading | Space Grotesk | 32px (2rem) | 500 | 1.20 | normal | Card titles, feature names |
| Sub-heading Small | Space Grotesk | 24px (1.5rem) | 500 | 1.30 | normal | Smaller section titles |
| Body Large | Space Grotesk | 20px (1.25rem) | 400 | 1.60 | normal | Intro paragraphs, impactful text |
| Body Standard | Poppins | 16px (1rem) | 400 | 1.60 | normal | Dense reading paragraphs |
| Nav / Buttons | Space Grotesk | 16px (1rem) | 500 | 1.00–1.20 | 0.5px | Navigation links, primary UI |
| Body Small | Poppins | 14px (0.88rem) | 400 | 1.50 | normal | Compact body text |
| Label | Space Grotesk | 12px (0.75rem) | 600 | 1.20 | 1px | Badges, small upper-case labels |
| Overline | Space Grotesk | 11px (0.68rem) | 600 | 1.40 | 1.5px | Uppercase overline labels |
| Code | Space Mono | 15px (0.94rem) | 400 | 1.60 | normal | Inline code, terminal |

### Principles
- **Geometric quirks for personality, clean sans for dense utility**: Space Grotesk carries all headline content and prominent UI elements (buttons, nav, badges). Its structured, mono-derived letterforms contrast beautifully with the warm, soft colors. Poppins is used for standard body text, providing a highly readable geometric sans-serif that complements Space Grotesk perfectly.
- **Slight negative tracking on large headings**: Space Grotesk looks incredibly modern when tightly tracked (-1px to -0.5px) at large display sizes (52px+).
- **Expanded tracking on small labels**: Badges and overlines use uppercase Space Grotesk with generous letter-spacing (1px to 1.5px) for a technical, precise look.
- **Tight-but-not-compressed headings**: Line-heights of 1.10–1.30 for headings keep the geometric shapes neatly stacked.

## 4. Component Stylings

### Buttons

**Warm Sand (Secondary)**
- Background: Warm Sand (`#e8e6dc`)
- Text: Charcoal Warm (`#4d4c48`), Space Grotesk, 500 weight
- Padding: 0px 12px 0px 8px (asymmetric — icon-first layout)
- Radius: comfortably rounded (8px)
- Shadow: ring-based (`#e8e6dc 0px 0px 0px 0px, #d1cfc5 0px 0px 0px 1px`)

**White Surface**
- Background: Pure White (`#ffffff`)
- Text: Warm Near Black (`#141413`), Space Grotesk, 500 weight
- Padding: 8px 16px 8px 12px
- Radius: generously rounded (12px)
- Hover: shifts to secondary background color

**Brand Solid (Primary)**
- Background: Brand Rose (`#E11D48`)
- Text: Pure White (`#ffffff`), Space Grotesk, 500 weight
- Radius: 8–12px
- Shadow: `0 4px 14px rgba(225, 29, 72, 0.4)`
- The primary CTA — vibrant, unmissable, and modern

**Dark Primary**
- Background: Warm Near Black (`#141413`)
- Text: Warm Silver (`#b0aea5`)
- Padding: 9.6px 16.8px
- Radius: generously rounded (12px)
- Border: thin solid Dark Surface (`1px solid #30302e`)

### Cards & Containers
- Background: Ivory (`#faf9f5`) or Pure White (`#ffffff`) on light surfaces; Dark Surface (`#30302e`) on dark
- Border: thin solid Border Cream (`1px solid #f0eee6`) on light; `1px solid #30302e` on dark
- Radius: comfortably rounded (8px) for standard cards; generously rounded (16px) for featured.
- Shadow: whisper-soft (`rgba(0,0,0,0.05) 0px 4px 24px`) for elevated content
- Ring shadow: `0px 0px 0px 1px` patterns for interactive card states

### Navigation
- Sticky top nav with warm background
- Logo: Space Grotesk, 600 weight, Warm Near Black
- Links: Space Grotesk, 500 weight, mix of Near Black (`#141413`) and Olive Gray (`#5e5d59`)
- Nav border: `1px solid #30302e` (dark) or `1px solid #f0eee6` (light)
- Hover: text shifts to foreground-primary, no decoration

### Distinctive Components

**Model / Feature Comparison Cards**
- Border Warm (`#e8e6dc`) separation between items
- Titles in Space Grotesk 32px
- Technical badges in uppercase Space Grotesk with 1px letter-spacing

**Dark/Light Section Alternation**
- The page alternates between Parchment light (`#f5f4ed`) and **Brand Black (`#000000`)** dark sections.
- Brand Navy (`#4C4C80`) may be used as a secondary container or accent surface within dark sections, but the primary dark background is always `#000000`.
- Space Grotesk pops exceptionally well against the black background.
- Dark cards use translucent white (`rgba(255, 255, 255, 0.05)`) with backdrop-filter blur for a modern glassmorphism effect over the dark background.

**Solid Accents**
- Hero text and prominent graphics utilize solid colors (Near Black or Brand Rose) for a clean, flat appearance without gradients.

## 5. Layout Principles

### Spacing System
- Base unit: 8px
- Scale: 4px, 8px, 12px, 16px, 24px, 32px, 48px, 64px, 96px, 128px
- Card internal padding: approximately 24–32px
- Section vertical spacing: generous (estimated 80–120px between major sections)

### Grid & Container
- Max container width: approximately 1200px, centered
- Hero: centered with structured, geometric layout

## 6. Depth & Elevation

| Level | Treatment | Use |
|-------|-----------|-----|
| Flat (Level 0) | No shadow, no border | Parchment background, inline text |
| Contained (Level 1) | `1px solid #f0eee6` (light) or `1px solid #30302e` (dark) | Standard cards, sections |
| Ring (Level 2) | `0px 0px 0px 1px` ring shadows using warm grays | Interactive cards, buttons, hover states |
| Whisper (Level 3) | `rgba(0,0,0,0.05) 0px 4px 24px` | Elevated feature cards |

**Shadow Philosophy**: Depth is communicated through **warm-toned ring shadows** rather than traditional drop shadows.

## 7. Do's and Don'ts

### Do
- Use **Space Grotesk** for all headings to establish the modern tech personality.
- Use Parchment (`#f5f4ed`) as the primary light background — the warm cream tone contrasts beautifully with the geometric font.
- Use Terracotta Brand (`#c96442`) only for primary CTAs and the highest-signal brand moments.
- Keep all neutrals warm-toned — every gray should have a yellow-brown undertone.
- Apply tight letter-spacing (-1px to -0.5px) on massive Space Grotesk display text.
- Apply loose letter-spacing (1px+) on small Space Grotesk badges and overlines.
- Use generous body line-height (1.60).

### Don't
- Don't use cool blue-grays anywhere — the palette is exclusively warm-toned.
- Don't introduce saturated colors beyond Terracotta.
- Don't apply heavy drop shadows.
- Don't use pure white (`#ffffff`) as a page background.
- Don't mix in serif fonts — the identity relies on the contrast between warm colors and the geometric Space Grotesk sans-serif.

## 8. Agent Prompt Guide

### Quick Color Reference
- Brand CTA / Accent: "Brand Rose (#E11D48)" & "Brand Orange (#F97316)"
- Dark Section Background: "Brand Navy (#4C4C80)"
- Page Background: "Parchment (#f5f4ed)"
- Card Surface: "Ivory (#faf9f5)"
- Primary Text: "Warm Near Black (#141413)"
- Secondary Text: "Olive Gray (#5e5d59)"

### Example Component Prompts
- "Create a hero section on Parchment (#f5f4ed) with a headline at 64px Space Grotesk weight 600, line-height 1.10, letter-spacing -1px. Use Warm Near Black (#141413) text. Add a subtitle in Olive Gray (#5e5d59) at 20px Space Grotesk with 1.60 line-height."
- "Design a feature card on Ivory (#faf9f5) with a 1px solid Border Cream (#f0eee6) border and comfortably rounded corners (8px). Title in Space Grotesk at 24px weight 500, description in Olive Gray (#5e5d59) at 16px Poppins. Add a whisper shadow (rgba(0,0,0,0.05) 0px 4px 24px)."

## 9. Graphic Standards Manual (GSM) Supplement

### Logo Usage & Clear Space
- **Clear Space**: Maintain a minimum clear space around the logo equal to the height of the capital "W" in the WS logo mark. No other graphical elements or text should enter this zone.
- **Minimum Size**: Do not reproduce the logo smaller than `24px` in height for digital use to preserve legibility.
- **Color Restrictions**: The logo must only appear in Warm Near Black (`#141413`) on light backgrounds, or Ivory (`#faf9f5`) on dark backgrounds. Do not apply gradients or outlines to the core logo mark.
- **Aspect Ratio**: Never stretch, skew, or distort the logo proportions.

### Grid System & Breakpoints
- **Desktop Grid**: 12-column flexible grid with a maximum container width of `1200px` and a minimum `24px` gutter between columns. Margin is automatic to center the container.
- **Tablet Grid (max-width: 1024px)**: 8-column flexible grid. Gutter shrinks to `16px`. Container padding `2rem` on both sides.
- **Mobile Grid (max-width: 768px)**: 4-column flexible grid. Container padding `1rem` on both sides. Stack all flex/grid elements vertically by default.

### Brand Voice & Tone
- **Tone**: Technical, clear, structured, but fundamentally warm and human-centric.
- **Voice**: We speak as experts who build tools for other experts. We avoid corporate jargon ("synergize", "leverage") and prefer straightforward, engineering-focused terminology.
- **Formatting**: Use Title Case for UI buttons and primary headings. Use sentence case for subheadings and body copy.

### Iconography Guidelines
- **Style**: Line icons only (never solid/filled unless denoting an active state in a navigation bar).
- **Weight**: 2px constant stroke width (`stroke-width="2"`).
- **Radius**: Soft, rounded caps and joins (`stroke-linecap="round" stroke-linejoin="round"`) to align with the warm aesthetic.
- **Sizing**: Standard inline icons must be exactly `24x24px`. Smaller descriptive list icons can scale to `18x18px`.

### Animation & Transitions
- **Interaction Duration**: Standard hover states (buttons, links, cards) use a `200ms` duration (`transition: all 0.2s ease`).
- **Easing**: Use the standard browser `ease` curve (equivalent to `cubic-bezier(0.25, 0.1, 0.25, 1)`) for snappy, responsive feedback.
- **Motion Distance**: Elements being elevated via hover (like cards or buttons) should move on the Y-axis by no more than `-2px` (`transform: translateY(-2px)`). Keep motions subtle; do not over-animate.
