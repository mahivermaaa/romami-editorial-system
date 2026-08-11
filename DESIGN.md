---
name: Romami Editorial System
colors:
  surface: '#fff8f6'
  surface-dim: '#f1d4cd'
  surface-bright: '#fff8f6'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fff1ed'
  surface-container: '#ffe9e4'
  surface-container-high: '#ffe2db'
  surface-container-highest: '#fadcd5'
  on-surface: '#271814'
  on-surface-variant: '#4e453d'
  inverse-surface: '#3e2c28'
  inverse-on-surface: '#ffede9'
  outline: '#80756c'
  outline-variant: '#d1c4ba'
  surface-tint: '#715a44'
  primary: '#715a44'
  on-primary: '#ffffff'
  primary-container: '#fadbbf'
  on-primary-container: '#765f49'
  inverse-primary: '#dfc1a6'
  secondary: '#7b5455'
  on-secondary: '#ffffff'
  secondary-container: '#fecbcb'
  on-secondary-container: '#7a5354'
  tertiary: '#984254'
  on-tertiary: '#ffffff'
  tertiary-container: '#ffd7dc'
  on-tertiary-container: '#9e4759'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#fcddc1'
  primary-fixed-dim: '#dfc1a6'
  on-primary-fixed: '#281807'
  on-primary-fixed-variant: '#57432e'
  secondary-fixed: '#ffdad9'
  secondary-fixed-dim: '#ecbaba'
  on-secondary-fixed: '#2f1314'
  on-secondary-fixed-variant: '#613d3e'
  tertiary-fixed: '#ffd9dd'
  tertiary-fixed-dim: '#ffb2bd'
  on-tertiary-fixed: '#400014'
  on-tertiary-fixed-variant: '#7a2b3d'
  background: '#fff8f6'
  on-background: '#271814'
  surface-variant: '#fadcd5'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 72px
    fontWeight: '700'
    lineHeight: 80px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 52px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '600'
    lineHeight: 48px
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '500'
    lineHeight: 40px
  body-lg:
    fontFamily: DM Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: 0.01em
  body-md:
    fontFamily: DM Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0.01em
  label-caps:
    fontFamily: DM Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.15em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  page-margin-desktop: 80px
  page-margin-mobile: 24px
  gutter: 24px
  section-gap: 120px
  element-gap: 16px
---

## Brand & Style

This design system embodies a "Contemporary Epicurean" aesthetic, blending the high-end sophistication of a luxury fashion editorial with the warmth of a boutique culinary brand. The personality is curated, romantic, and artisanal, prioritizing visual storytelling over functional density.

The style is a synthesis of **Minimalism** and **Editorial Elegance**. It utilizes generous whitespace, asymmetric layouts, and delicate organic details to create a sense of "quiet luxury." The emotional response should be one of indulgence and refined comfort, making the user feel like they are flipping through a limited-edition art book rather than a standard food application.

## Colors

The palette is anchored in warm, fleshy tones that evoke appetite and tactile comfort. 

- **Primary (Warm Peach):** Used for soft background washes and subtle container fills.
- **Secondary (Blush Pink):** Used for decorative elements, secondary backgrounds, and soft UI highlights.
- **Tertiary/Brand Accent (Deep Raspberry):** The primary color for high-impact typography, primary action buttons, and active states. It provides the necessary contrast against the softer background tones.
- **Neutral (Dark Espresso Brown):** Used exclusively for body text and structural lines to maintain a softer, more organic feel than pure black.
- **Supporting (Cream):** The base canvas for the entire experience, providing a premium, "paper-like" quality.
- **Accent (Golden Tones):** Used sparingly for micro-details, ratings, and special artisanal icons.

## Typography

The typography is the core of the editorial identity. 

- **Display & Headlines:** Utilize **Playfair Display**. For large editorial titles, mix regular and italic weights within the same sentence to create a rhythmic, magazine-style flow. Use tight letter-spacing for large headlines to maintain a high-fashion look.
- **Body & Navigation:** Utilize **DM Sans**. This modern sans-serif provides a functional counterpoint to the decorative serif. Body copy should maintain a generous line-height to ensure readability against the tinted backgrounds. 
- **Labels:** Small labels and navigational links should always be set in uppercase with increased letter spacing to evoke a clean, organized structure.

## Layout & Spacing

The layout follows an **Editorial Fluid Grid**. It breaks away from rigid vertical columns to allow for "white space as a feature."

- **Layout Model:** A 12-column grid is used for structure, but content frequently overlaps or sits off-center. Sections are separated by large vertical gaps (`120px+`) to allow the brand to breathe.
- **Responsive Behavior:** On desktop, use wide margins and staggered image placements. On mobile, transition to a single-column layout but maintain the oversized typography and generous vertical padding.
- **Organic Lines:** Use very thin (0.5pt to 1pt) horizontal lines in **Dark Espresso Brown** at 20% opacity to separate sections or categories, mimicking the layout of a physical newspaper or ledger.

## Elevation & Depth

This design system avoids traditional drop shadows in favor of **Tonal Layers** and **Flat Depth**.

- **Surface Strategy:** Depth is communicated through color blocking rather than shadows. A "Deep Raspberry" button sits flat on a "Warm Peach" surface. 
- **Glassmorphism:** Use subtle background blurs (10px - 15px) for navigation bars when scrolling over imagery, maintaining the "Soft Apricot" tint at 80% opacity.
- **Borders:** Instead of shadows, use delicate 1px borders in the "Deep Raspberry" color for cards and inputs to define boundaries without adding visual weight.
- **Imagery:** Large, full-bleed photography creates a sense of "z-axis" depth. Images should use a subtle inner-glow rather than an outer shadow.

## Shapes

The shape language is primarily linear and architectural, punctuated by organic, hand-drawn flourishes.

- **UI Elements:** Buttons and input fields use a **Soft (0.25rem)** corner radius. This maintains a clean, modern edge that aligns with the editorial aesthetic.
- **Artisanal Elements:** Custom hand-drawn illustrations (hearts, stars, pasta silhouettes) should appear in the margins or as "stickers" overlapping images to break the rigid grid.
- **Image Frames:** Most photography should be sharp-edged or slightly rounded, but select "feature" images can use an organic, hand-drawn mask shape.

## Components

- **Buttons:** Primary buttons are solid "Deep Raspberry" with "Cream" uppercase text. Secondary buttons are "Soft Apricot" with "Deep Raspberry" text. Both use a soft transition on hover (subtle scale up).
- **Cards:** Product and article cards should be "border-only" or "no-border," relying on the "Warm Peach" background color to define the container. Text is always left-aligned.
- **Inputs:** Minimalist style. A single bottom border in "Deep Raspberry" with placeholder text in "Dark Espresso Brown" (at 50% opacity).
- **Interactive States:** Use "smooth zooms" (1.05x) on image hover. Navigation links should have a thin underline that expands from the center upon hover.
- **Chips/Labels:** Small, pill-shaped tags in "Muted Warm Yellow" with brown text are used for dietary indicators (e.g., "Gluten-Free," "Vegan").
- **Lists:** Menu items should be presented with the item name in serif italics and the price in sans-serif, connected by a thin dotted line.