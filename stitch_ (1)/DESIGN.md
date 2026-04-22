---
name: Warm Tea House
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
  on-surface-variant: '#554434'
  inverse-surface: '#2f3131'
  inverse-on-surface: '#f0f1f1'
  outline: '#887361'
  outline-variant: '#dbc2ad'
  surface-tint: '#8b5000'
  primary: '#8b5000'
  on-primary: '#ffffff'
  primary-container: '#ff9800'
  on-primary-container: '#653900'
  inverse-primary: '#ffb870'
  secondary: '#636037'
  on-secondary: '#ffffff'
  secondary-container: '#e7e1ae'
  on-secondary-container: '#67643b'
  tertiary: '#77574d'
  on-tertiary: '#ffffff'
  tertiary-container: '#cfa89c'
  on-tertiary-container: '#593d34'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdcbe'
  primary-fixed-dim: '#ffb870'
  on-primary-fixed: '#2c1600'
  on-primary-fixed-variant: '#693c00'
  secondary-fixed: '#eae4b1'
  secondary-fixed-dim: '#cdc897'
  on-secondary-fixed: '#1e1c00'
  on-secondary-fixed-variant: '#4b4822'
  tertiary-fixed: '#ffdbd0'
  tertiary-fixed-dim: '#e7bdb1'
  on-tertiary-fixed: '#2c160e'
  on-tertiary-fixed-variant: '#5d4037'
  background: '#f9f9f9'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
typography:
  display-lg:
    fontFamily: plusJakartaSans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: plusJakartaSans
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  title-sm:
    fontFamily: plusJakartaSans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: '1.4'
  body-md:
    fontFamily: plusJakartaSans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  body-sm:
    fontFamily: plusJakartaSans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.5'
  label-caps:
    fontFamily: plusJakartaSans
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1.0'
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1200px
  gutter: 24px
  section-padding: 80px
  element-gap: 16px
---

## Brand & Style
The brand personality centers on the concept of "lingering flavors" and "shared moments." It evokes the atmosphere of a sun-drenched afternoon in a contemporary tea house. The target audience includes urban dwellers seeking a peaceful dining respite and families looking for a welcoming, approachable environment.

The design system adopts a **Modern Minimalist** style infused with **Soft Tactile** elements. It prioritizes clarity and whitespace to keep the focus entirely on food photography, while using warm color washes to prevent the interface from feeling cold or clinical. The visual language is intentional, rhythmic, and deeply hospitable.

## Colors
The palette is designed to stimulate appetite and provide a sense of comfort. 
- **Primary Orange (#FF9800)** is reserved strictly for high-priority calls to action, such as booking a table or ordering. 
- **Secondary Light Yellow (#FFF9C4)** serves as the "brand glow," utilized in hero sections and large visual containers to create a sunlit effect. 
- **Tertiary Dark Brown (#5D4037)** replaces pure black for typography and iconography to maintain a "warm brew" aesthetic.
- **Surface White (#FFFFFF)** ensures the content areas remain legible and feel hygienic and fresh.

## Typography
This design system utilizes **Plus Jakarta Sans** for its friendly, rounded terminals that mirror the approachable nature of the restaurant. For Traditional Chinese typesetting, use a high-quality system sans-serif (such as Microsoft JhengHei or PingFang TC) paired with the English font to ensure a seamless "Modern Sans" look. 

The type hierarchy prioritizes generous line heights (1.6 for body text) to ensure readability for a wide age demographic. Headlines should utilize a slightly tighter tracking to maintain a strong visual anchor.

## Layout & Spacing
The layout follows a **Fixed Grid** model centered within the viewport, creating a "contained" and intimate feel like a well-set table. 

- **Grid:** A 12-column grid system with 24px gutters.
- **Rhythm:** An 8px base unit governs all spatial relationships. 
- **White Space:** Large section-level padding (80px+) is used to separate menu categories and brand storytelling blocks, preventing the user from feeling rushed.
- **Margins:** On mobile, a minimum 20px side margin is maintained to ensure content does not touch the bezel.

## Elevation & Depth
Depth in this design system is achieved through **Tonal Layers** rather than heavy shadows. 

- **Level 0 (Floor):** Pure White (#FFFFFF) for the main content background.
- **Level 1 (Submerged):** Light Yellow (#FFF9C4) for large-scale hero areas or section headers.
- **Level 2 (Raised):** Cards and interaction elements use a subtle, "Ambient Glow"—a low-opacity shadow tinted with the tertiary brown (e.g., `rgba(93, 64, 55, 0.08)`) to maintain warmth. 

Avoid high-contrast black shadows which contradict the "cozy" brand pillars.

## Shapes
The shape language is organic and soft. A **Rounded (0.5rem)** base is applied to all standard components like input fields and small buttons. 

Larger containers, such as product cards or image carousels, utilize **rounded-lg (1rem)**, while decorative background elements or specialized "Dish of the Day" tags may use **rounded-xl (1.5rem)** or full pill-shapes. Sharp 90-degree corners should be avoided entirely to sustain the friendly visual tone.

## Components
Consistent component styling ensures a fluid user journey:

- **Primary Action Buttons:** Solid Orange (#FF9800) with white text. High roundedness (Level 2). Use a subtle lift on hover rather than a color change.
- **Menu Cards:** White backgrounds with a very thin, soft-brown border (1px, 10% opacity). Featured items may use a Light Yellow background.
- **Chips / Tags:** Use the Light Yellow as a background for "Recommended" or "New" tags with Dark Brown text.
- **Input Fields:** Soft grey borders that turn Orange on focus. Labels always sit above the field in a bold, smaller font.
- **Reservation Widget:** A persistent, high-contrast floating button or a dedicated section that uses the brand's primary orange to draw immediate attention.
- **Food Gallery:** Large-scale imagery with rounded corners, accompanied by minimal descriptions to keep the focus on the culinary visuals.