---
name: Luminous Path
colors:
  surface: '#171214'
  surface-dim: '#171214'
  surface-bright: '#3f373a'
  surface-container-lowest: '#120d0f'
  surface-container-low: '#201a1d'
  surface-container: '#241e21'
  surface-container-high: '#2f282b'
  surface-container-highest: '#3a3336'
  on-surface: '#ecdfe3'
  on-surface-variant: '#d5c1c9'
  inverse-surface: '#ecdfe3'
  inverse-on-surface: '#352f31'
  outline: '#9d8c93'
  outline-variant: '#514349'
  surface-tint: '#ffaeda'
  primary: '#ffcfe6'
  on-primary: '#541a3f'
  primary-container: '#f9a8d4'
  on-primary-container: '#78395f'
  inverse-primary: '#8a486f'
  secondary: '#e2c62d'
  on-secondary: '#393000'
  secondary-container: '#c1a800'
  on-secondary-container: '#483d00'
  tertiary: '#bbe99f'
  on-tertiary: '#133801'
  tertiary-container: '#a0cd85'
  on-tertiary-container: '#31581d'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffd8ea'
  primary-fixed-dim: '#ffaeda'
  on-primary-fixed: '#3a0329'
  on-primary-fixed-variant: '#6f3157'
  secondary-fixed: '#ffe24c'
  secondary-fixed-dim: '#e2c62d'
  on-secondary-fixed: '#211b00'
  on-secondary-fixed-variant: '#524600'
  tertiary-fixed: '#c1f0a4'
  tertiary-fixed-dim: '#a6d38b'
  on-tertiary-fixed: '#072100'
  on-tertiary-fixed-variant: '#2a5016'
  background: '#171214'
  on-background: '#ecdfe3'
  surface-variant: '#3a3336'
  space-obsidian: '#000000'
  space-charcoal: '#121212'
  floral-pink: '#F472B6'
  ethereal-purple: '#A855F7'
  luminous-gold: '#FBBF24'
  glass-border: rgba(255, 255, 255, 0.45)
typography:
  display-lg:
    fontFamily: Instrument Serif
    fontSize: 88px
    fontWeight: '400'
    lineHeight: '0.8'
    letterSpacing: -4px
  display-lg-mobile:
    fontFamily: Instrument Serif
    fontSize: 56px
    fontWeight: '400'
    lineHeight: '0.9'
    letterSpacing: -2px
  headline-lg:
    fontFamily: Instrument Serif
    fontSize: 64px
    fontWeight: '400'
    lineHeight: '0.9'
    letterSpacing: -3px
  headline-md:
    fontFamily: Instrument Serif
    fontSize: 40px
    fontWeight: '400'
    lineHeight: '1.0'
    letterSpacing: -1px
  body-lg:
    fontFamily: Barlow
    fontSize: 18px
    fontWeight: '300'
    lineHeight: '1.4'
    letterSpacing: 0px
  body-md:
    fontFamily: Barlow
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
    letterSpacing: 0px
  label-md:
    fontFamily: Barlow
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.0'
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Barlow
    fontSize: 11px
    fontWeight: '400'
    lineHeight: '1.0'
    letterSpacing: 0px
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  container-max: 1280px
  gutter: 1.5rem
  margin-desktop: 5rem
  margin-mobile: 1.5rem
  section-gap: 8rem
---

## Brand & Style

The design system embodies a "Cinematic Space-Travel" meets "Ethereal Path" aesthetic. It positions the product as a visionary mentor—professional yet deeply supportive. The UI should evoke a sense of calm confidence and high-tech wonder, simulating a journey through a sun-drenched, cosmic forest where the "light" represents career clarity and opportunity.

The visual style is **Liquid-Glass Minimalism**. It relies on deep, obsidian surfaces contrasted with highly refined glassmorphism. Light is treated as a physical material, manifesting through "sun-drenched" glows, chromatic reflections, and ultra-smooth blurring. The interface feels weightless, with elements appearing as floating crystalline panes guided by a cinematic, editorial sense of typography.

## Colors

The palette is rooted in a "Deep Space" foundation of blacks and charcoals, providing a high-contrast stage for "sun-drenched" light effects.

- **Foundational Neutrals:** `space-obsidian` is used for total immersion backgrounds, while `space-charcoal` provides subtle depth for secondary containers.
- **Luminous Accents:** Derived from the sunset floral reference, these colors are primarily used for interactive states, inner glows, and atmospheric background blurs. `floral-pink` and `ethereal-purple` represent growth and wisdom, while `luminous-gold` acts as the "guiding light" for primary calls to action.
- **Glass Logic:** All glass elements use white at varying opacities (1% to 15%) for fills to maintain a neutral transparency that adopts the colors of the light-blooms behind them.

## Typography

The typography system creates an editorial, premium feel by pairing a high-character serif with a functional, technical sans-serif.

- **Heading Hierarchy:** `Instrument Serif` must always be used in its **italic** variant for headings. This conveys a sense of speed, sophistication, and human touch. Extreme negative letter-spacing is applied to larger sizes to create a "tight" cinematic lockup.
- **Body Hierarchy:** `Barlow` is used for all functional text. The "Light" (300) weight is preferred for long-form descriptions to maintain the airy, ethereal feel, while "Medium" (500) is used for UI labels and navigation.
- **Interaction:** Larger headings should utilize a "BlurText" entrance animation, where words transition from a 10px blur to clear focus, mimicking eyes adjusting to a bright light.

## Layout & Spacing

The layout philosophy follows a **Fluid Cinematic Grid**. Content is often centered or arranged in wide-spanning containers to allow the background "environment" (video or glows) to breathe.

- **Grid:** Use a 12-column grid for desktop with wide margins (80px) to push content toward the center "path."
- **Sectioning:** Vertical transitions between sections use custom crossfades rather than hard cuts. Elements should feel like they are floating in a 3D space, with significant vertical padding (section-gap) to prevent visual clutter.
- **Rhythm:** Spacing between glass cards and content blocks follows a consistent 24px (1.5rem) unit to maintain a systematic, "engineered" feel amidst the organic background visuals.

## Elevation & Depth

Depth is achieved through **Liquid-Glass layering** rather than traditional shadows.

- **The Ground Layer:** Deep #000 black, occasionally broken by soft, blurred radial gradients of pink, gold, and purple that appear to exist "miles" behind the UI.
- **Glass Panes:** Surfaces use `backdrop-filter: blur(4px)` for standard depth and `blur(50px)` for high-priority depth (Primary CTAs).
- **Edge Definition:** Every elevation level is defined by a "Liquid" border—a 1.4px gradient stroke that mimics light hitting the edge of a lens. These borders should be brightest at the top and bottom, fading out on the sides to create a realistic refraction effect.
- **Inner Glow:** High-elevation components (Cards, Primary Buttons) feature a `box-shadow: inset 0 1px 1px rgba(255,255,255,0.15)` to give the glass thickness and "weight."

## Shapes

The design system favors **Pill-shaped geometry** to maintain an approachable, friendly, and aerodynamic feel.

- **Global Radius:** By default, all buttons, chips, and small containers are fully rounded (9999px).
- **Large Containers:** Cards and major section containers use a "Super-ellipse" inspired radius of 1.25rem to 1.5rem, providing a softer, more modern aesthetic than standard corners.
- **Consistency:** Avoid sharp corners entirely to maintain the "supportive and visionary" brand personality.

## Components

### Buttons & CTAs
- **Primary:** `liquid-glass-strong` with a white fill and black text for maximum "liftoff" contrast. Includes an `ArrowUpRight` icon to signify career progression.
- **Secondary:** Bare text with a Play or Arrow icon, utilizing `floral-pink` on hover.

### Liquid-Glass Cards
- Floating panes with `rounded-[1.25rem]`. 
- **Header:** Features a nested 44x44px glass square for icons and a cluster of small pill-shaped "Metadata Tags" in the top-right.
- **Interaction:** Subtle scale-up (1.02x) on hover with an increase in the inner glow opacity.

### Navigation & Chips
- **Navbar:** A floating glass pill centered at the top of the viewport.
- **Badge Chips:** Small pills with a high-contrast "New" or "Status" indicator (Solid White) followed by glass-filtered text.

### Form Inputs
- Minimalist glass fields with `0.5px` white borders. 
- Focus state triggers a soft `luminous-gold` outer glow, simulating light leaking from the input.

### AI Feedback Indicators
- Pulse animations using `ethereal-purple` glows to indicate when the "AI Copilot" is thinking or listening during an interview simulation.