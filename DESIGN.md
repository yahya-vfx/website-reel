---
name: Obsidian VFX Portfolio
colors:
  surface: '#101319'
  surface-dim: '#101319'
  surface-bright: '#363940'
  surface-container-lowest: '#0b0e14'
  surface-container-low: '#191c22'
  surface-container: '#1d2026'
  surface-container-high: '#272a30'
  surface-container-highest: '#32353b'
  on-surface: '#e1e2ea'
  on-surface-variant: '#c6c6cb'
  inverse-surface: '#e1e2ea'
  inverse-on-surface: '#2d3037'
  outline: '#909095'
  outline-variant: '#45474b'
  surface-tint: '#c6c6cc'
  primary: '#c6c6cc'
  on-primary: '#2f3035'
  primary-container: '#0f1115'
  on-primary-container: '#7b7c82'
  inverse-primary: '#5d5e63'
  secondary: '#d2bbff'
  on-secondary: '#3f008e'
  secondary-container: '#6001d1'
  on-secondary-container: '#c9aeff'
  tertiary: '#4cd7f6'
  on-tertiary: '#003640'
  tertiary-container: '#001419'
  on-tertiary-container: '#0089a0'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e2e2e8'
  primary-fixed-dim: '#c6c6cc'
  on-primary-fixed: '#1a1c20'
  on-primary-fixed-variant: '#45474b'
  secondary-fixed: '#eaddff'
  secondary-fixed-dim: '#d2bbff'
  on-secondary-fixed: '#25005a'
  on-secondary-fixed-variant: '#5a00c6'
  tertiary-fixed: '#acedff'
  tertiary-fixed-dim: '#4cd7f6'
  on-tertiary-fixed: '#001f26'
  on-tertiary-fixed-variant: '#004e5c'
  background: '#101319'
  on-background: '#e1e2ea'
  surface-variant: '#32353b'
typography:
  display-lg:
    fontFamily: Sora
    fontSize: 72px
    fontWeight: '700'
    lineHeight: 80px
    letterSpacing: -0.04em
  display-lg-mobile:
    fontFamily: Sora
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Sora
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-caps:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
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
  unit: 8px
  container-max: 1440px
  gutter: 32px
  margin-desktop: 80px
  margin-mobile: 24px
  section-gap: 160px
---

## Brand & Style

This design system is built for a VFX artist portfolio, emphasizing the "mysterious" and the "unseen." The brand personality is enigmatic, high-end, and technically sophisticated. It aims to evoke an emotional response of awe and curiosity, positioning the work as a series of digital artifacts discovered in a void.

The visual style is a fusion of **Minimalism** and **Glassmorphism**, set against a high-contrast dark environment. We utilize immense negative space to act as a "stage" for visual effects content, ensuring the interface never competes with the artistry. Elements appear as if they are floating in deep space, utilizing subtle metallic sheen and neon light-leak accents to guide the user's eye toward calls to action.

## Colors

The palette is anchored in near-black depths to provide maximum contrast for VFX showreels.

- **Primary (Obsidian):** `#0F1115` serves as the canvas, providing a "bottomless" feel.
- **Secondary (Electric Violet):** `#7C3AED` is used for high-energy interaction points and hover states, mimicking a neon glow.
- **Tertiary (Cyber Cyan):** `#06B6D4` is used for technical data, metadata, and secondary accents.
- **Neutral (Midnight Blue):** `#1A1D23` is used for container surfaces and subtle structural divisions.
- **Accents:** Use pure white (`#FFFFFF`) sparingly for high-readability text and metallic silver (`#94A3B8`) for secondary labels.

## Typography

This design system uses a dual-font approach to balance character with utility. **Sora** provides a futuristic, geometric edge for headlines, suggesting technical precision. **Inter** is used for body copy to ensure effortless readability against high-contrast backgrounds. **JetBrains Mono** is introduced for "technical metadata" (e.g., frame rates, software used, timestamps) to reinforce the VFX/Developer aesthetic.

Large display type should utilize tight letter-spacing to feel cohesive and "impactful," while labels should be widely tracked to feel like sophisticated instrumentation.

## Layout & Spacing

The layout follows a **Fixed Grid** model on desktop to maintain cinematic proportions, transitioning to a fluid model on mobile devices. 

- **Desktop (1440px):** 12-column grid with 32px gutters. Massive top/bottom margins (160px+) are encouraged to separate distinct projects.
- **Tablet (768px):** 8-column grid with 24px gutters.
- **Mobile (375px):** 4-column grid with 16px gutters.

The "immersion" comes from the use of extreme vertical padding between sections, forcing the user to focus on one visual asset at a time. Elements should often span 8-10 columns, leaving "void" space on the edges to enhance the mysterious theme.

## Elevation & Depth

Depth is not communicated through traditional shadows, but through **Tonal Layering** and **Luminance**.

1.  **Level 0 (The Void):** The deepest primary color (`#0F1115`).
2.  **Level 1 (Floating Planes):** Semi-transparent surfaces using the neutral color with a 20px backdrop blur (Glassmorphism). These should have a 1px "inner stroke" or "rim light" (white at 10% opacity) to define edges against the dark background.
3.  **Level 2 (Active Elements):** Interactive components emit a soft glow (Box-shadow: 0 0 30px) using the Secondary or Tertiary accent colors, simulating light emitting from a screen or neon tube.

Avoid using drop shadows that suggest a physical light source from above; instead, treat every element as if it is self-illuminated or backlit.

## Shapes

The shape language is sharp and precise. A "Soft" (`0.25rem`) corner radius is applied to standard UI elements like buttons and input fields to prevent the interface from feeling too aggressive, while maintaining a sleek, modern technical feel. 

Large-scale containers (like video cards) should remain sharp or use minimal rounding. Buttons may occasionally use a "clipped corner" aesthetic (simulated via 45-degree linear gradients) to lean into the sci-fi/VFX aesthetic.

## Components

- **Buttons:** Primary buttons are ghost-style with a 1px metallic border. On hover, they fill with a vibrant Electric Violet gradient and a subtle outer glow.
- **Cards:** Project cards are borderless with high-resolution video thumbnails. Metadata appears on hover using a glassmorphic overlay that slides up from the bottom.
- **Chips/Tags:** Small, rectangular tags using **JetBrains Mono**. These identify software (e.g., "Houdini", "Nuke") and use a subtle Tertiary (Cyan) border.
- **Cursor:** A custom "precision" cursor—a small dot with a larger, delayed trailing ring—enhances the immersive, interactive feel of the portfolio.
- **Progress Bars:** Thin, 2px lines using the Tertiary color, appearing at the top of the viewport during page transitions or as video scrubbers.
- **Inputs:** Minimalist bottom-border only, glowing when focused to indicate "system ready" status.