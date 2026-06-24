---
name: Citrus Zest Modern
colors:
  surface: '#f9f9f9'
  surface-dim: '#dadada'
  surface-bright: '#f9f9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f4'
  surface-container: '#eeeeee'
  surface-container-high: '#e8e8e8'
  surface-container-highest: '#e2e2e2'
  on-surface: '#1a1c1c'
  on-surface-variant: '#3d4a39'
  inverse-surface: '#2f3131'
  inverse-on-surface: '#f0f1f1'
  outline: '#6d7b67'
  outline-variant: '#bccbb4'
  surface-tint: '#006e0a'
  primary: '#006e0a'
  on-primary: '#ffffff'
  primary-container: '#32cd32'
  on-primary-container: '#005105'
  inverse-primary: '#4ce346'
  secondary: '#62603d'
  on-secondary: '#ffffff'
  secondary-container: '#e9e4b8'
  on-secondary-container: '#686643'
  tertiary: '#5a632e'
  on-tertiary: '#ffffff'
  tertiary-container: '#afb87a'
  on-tertiary-container: '#414917'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#75ff68'
  primary-fixed-dim: '#4ce346'
  on-primary-fixed: '#002201'
  on-primary-fixed-variant: '#005306'
  secondary-fixed: '#e9e4b8'
  secondary-fixed-dim: '#ccc89e'
  on-secondary-fixed: '#1e1c03'
  on-secondary-fixed-variant: '#4a4828'
  tertiary-fixed: '#dfe8a6'
  tertiary-fixed-dim: '#c3cc8c'
  on-tertiary-fixed: '#191e00'
  on-tertiary-fixed-variant: '#434b18'
  background: '#f9f9f9'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
typography:
  display-lg:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Montserrat
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  section-gap: 80px
  container-max: 1200px
  gutter: 24px
  margin-mobile: 16px
---

## Brand & Style

The design system is centered on a "Natural Vibrance" narrative, specifically tailored for the modern Indian middle-class household. It evokes feelings of hygiene, refreshing vitality, and premium care. 

The style is **Corporate Modern with a Minimalist lean**, utilizing heavy whitespace to emphasize cleanliness. We incorporate subtle **Glassmorphism** for card elements to mimic the transparency of the liquid product and the translucency of lemon slices. The aesthetic is bright, airy, and clinical yet approachable, ensuring the product feels both like a household essential and a sensory treat.

## Colors

The palette is derived directly from the freshness of lime and lemon. 
- **Primary (Lime Green):** Used for primary actions, success states, and brand-heavy iconography. It represents growth and germ protection.
- **Secondary (Soft Yellow):** Used for background highlights, subtle section transitions, and secondary buttons. It adds warmth and a citrus "glow."
- **Tertiary (Deep Olive):** A darker green used exclusively for high-contrast typography to ensure legibility while staying within the organic color family.
- **Neutral (Crisp White):** The foundation of the UI, providing a sterile, clean canvas that allows the product photography to pop.

## Typography

The typography strategy pairs the geometric confidence of **Montserrat** for headlines with the friendly, open counters of **Plus Jakarta Sans** for body text. 

Headlines should use a tight letter-spacing to feel modern and "editorial." Body text uses a generous line-height to ensure readability for all age groups within the family demographic. For mobile, display sizes are scaled down to maintain hierarchy without overwhelming the smaller viewport.

## Layout & Spacing

This design system utilizes a **Fluid Grid** model with a 12-column structure for desktop and a 4-column structure for mobile. 

- **Vertical Rhythm:** Built on an 8px baseline grid. Section spacing is aggressive (80px+) to maintain the "Minimalist" feel and provide breathing room.
- **Grid:** On desktop, the content is contained within a 1200px max-width container. On mobile, margins are reduced to 16px to maximize real estate for product imagery.
- **Alignment:** Content is primarily center-aligned for hero sections to create a premium "landing page" feel, shifting to left-aligned for informational feature blocks.

## Elevation & Depth

Hierarchy is established through **Tonal Layers** and **Ambient Shadows**. 

Instead of harsh drop shadows, we use "Citrus Glows"—soft, diffused shadows with a slight #32CD32 (Lime Green) tint at 5-10% opacity. This makes elements appear as if they are floating on a clean, sunlit surface. 

**Glassmorphism** is applied to floating feature chips (e.g., "99.9% Germ Protection") using a 12px backdrop blur and a thin 1px white border at 20% opacity. This creates a "water-droplet" effect consistent with the hand wash category.

## Shapes

The shape language is **Rounded (Level 2)**. 

Curves are used to echo the organic silhouette of the Valley Lemon bottle and the circularity of lemon slices. 
- **Buttons:** 0.5rem (8px) radius for a sturdy but approachable feel.
- **Product Cards:** 1rem (16px) radius to soften the layout.
- **Icon Containers:** Soft circles or "squircular" shapes to maintain the friendly family-focused aesthetic.

## Components

- **Buttons:** Primary buttons use a solid Lime Green fill with white text. Secondary buttons use a Soft Yellow fill with Deep Olive text. All buttons feature a subtle scale-up transition (1.02x) on hover.
- **Feature Chips:** Small, pill-shaped badges with a light green tint and a dark green border, used to highlight key benefits like "Deep Cleansing" or "Natural Fragrance."
- **Input Fields:** Minimalist design with only a bottom border that transforms into a Lime Green highlight on focus.
- **Cards:** Glassmorphic backgrounds with soft shadows. Used for customer testimonials and "How to Use" steps.
- **Product Display:** Images should feature high-quality photography of the bottle with natural lighting and water droplet overlays to emphasize the "fresh" value proposition.