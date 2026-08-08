---
name: Artesano Editorial
colors:
  surface: '#faf9f6'
  surface-dim: '#dbdad7'
  surface-bright: '#faf9f6'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f3f1'
  surface-container: '#efeeeb'
  surface-container-high: '#e9e8e5'
  surface-container-highest: '#e3e2e0'
  on-surface: '#1a1c1a'
  on-surface-variant: '#4d4540'
  inverse-surface: '#2f312f'
  inverse-on-surface: '#f2f1ee'
  outline: '#7e756f'
  outline-variant: '#d0c4bd'
  surface-tint: '#655d57'
  primary: '#17120d'
  on-primary: '#ffffff'
  primary-container: '#2c2621'
  on-primary-container: '#968c86'
  inverse-primary: '#d0c4bd'
  secondary: '#974725'
  on-secondary: '#ffffff'
  secondary-container: '#fe9970'
  on-secondary-container: '#772f0e'
  tertiary: '#161305'
  on-tertiary: '#ffffff'
  tertiary-container: '#2c2717'
  on-tertiary-container: '#968e78'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ece0d8'
  primary-fixed-dim: '#d0c4bd'
  on-primary-fixed: '#201b16'
  on-primary-fixed-variant: '#4d4540'
  secondary-fixed: '#ffdbce'
  secondary-fixed-dim: '#ffb598'
  on-secondary-fixed: '#370e00'
  on-secondary-fixed-variant: '#78310f'
  tertiary-fixed: '#ece2c9'
  tertiary-fixed-dim: '#cfc6ae'
  on-tertiary-fixed: '#201b0c'
  on-tertiary-fixed-variant: '#4c4634'
  background: '#faf9f6'
  on-background: '#1a1c1a'
  surface-variant: '#e3e2e0'
typography:
  display-lg:
    fontFamily: Libre Caslon Text
    fontSize: 64px
    fontWeight: '400'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Libre Caslon Text
    fontSize: 40px
    fontWeight: '400'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Libre Caslon Text
    fontSize: 32px
    fontWeight: '400'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-sm:
    fontFamily: Hanken Grotesk
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.0'
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 20px
  section-gap: 120px
---

## Brand & Style
The design system is built on a "Neo-Bistro" aesthetic—merging the traditional warmth of an artisanal bakery with the sharp, editorial sophistication of a modern vermouth bar. The visual language is high-contrast yet warm, evoking the sensory experience of freshly baked bread (*Pan*), rich coffee (*Café*), and the social ritual of the aperitif (*Vermut*).

The style is **Minimalist-Editorial**. It prioritizes high-quality food photography as the primary atmospheric driver, using expansive white space (or cream space) to frame content like a luxury lifestyle magazine. Interaction should feel intentional and rhythmic, mirroring the slow-paced, premium gastronomic culture of Córdoba.

## Colors
The palette is grounded in the raw materials of the craft. 
- **Espresso (#2C2621):** The primary ink color. A deep, desaturated charcoal used for typography and structural elements to provide "weight" and authority.
- **Terracotta (#D97B54):** The accent color. Used sparingly for calls to action, active states, and highlighting artisanal details. It evokes fired clay and crust.
- **Wheat (#F2E8CF):** A soft, mid-tone neutral for secondary backgrounds, cards, and dividers, providing a warm "paper" feel.
- **Cream (#FAF9F6):** The primary canvas color. It is softer than pure white, reducing digital glare and feeling more organic.

## Typography
The typography strategy relies on the tension between a romantic, historical Serif and a sharp, contemporary Sans-Serif.

- **Headlines:** Use **Libre Caslon Text**. It provides a literary, established feel. Optical sizing is crucial; large displays should use tighter letter spacing to emphasize the elegant curves of the glyphs.
- **Body:** Use **Hanken Grotesk**. It is exceptionally clean and professional, ensuring that long menus or descriptions remain legible without competing with the headlines.
- **Labels:** Use uppercase **Hanken Grotesk** with generous letter spacing (0.1em) for categories, overlines, and small metadata to create an organized, architectural feel.

## Layout & Spacing
The layout follows a **Fixed-Fluid Hybrid** model. Content is contained within a 1280px max-width container on desktop to maintain the editorial "column" feel, while vertical spacing is unusually generous to evoke a sense of luxury and calm.

- **Grid:** Use a 12-column grid for desktop and a 4-column grid for mobile.
- **Negative Space:** Sections should be separated by large gaps (`section-gap`) to allow the high-quality photography to breathe.
- **Asymmetry:** Occasionally break the grid with offset images or floating text blocks to mimic the layout of a physical gastropub menu or a boutique magazine.

## Elevation & Depth
In keeping with the artisanal and flat-print aesthetic, this design system avoids heavy drop shadows. 

- **Tonal Layering:** Depth is achieved through color blocks (e.g., a Wheat card on a Cream background) rather than shadows.
- **Soft Insets:** For interactive elements like input fields, use a subtle 1px border in Espresso at 10% opacity.
- **Floating Images:** To emphasize photography, use a very soft, large-radius "ambient" shadow (0% offset, 40px blur, 4% Espresso opacity) to give the impression of paper resting on a table.

## Shapes
Shapes are predominantly **Soft (0.25rem)**. This slight rounding removes the harshness of digital "stiffness" while maintaining a precise, professional look. 

- **Containers:** Cards and image containers use `rounded-lg` (0.5rem) to feel approachable.
- **Buttons:** Use sharp corners or very small radii (4px) to maintain the premium, high-fashion aesthetic. 
- **Decorative Elements:** Use perfectly circular crops for secondary food imagery (like coffee or vermouth garnishes) to contrast with the rectangular grid.

## Components
- **Buttons:** Primary buttons are solid Espresso with Cream text. Secondary buttons are outlined Espresso. Interaction involves a subtle color shift to Terracotta. Avoid heavy rounded corners; stick to a refined 4px radius.
- **Cards:** Use a "No-Border" approach. Define card boundaries using the Wheat background color. Images within cards should have a subtle zoom-on-hover effect.
- **Lists (Menus):** Menu items should use a classic dot-leader style (Item ............. $Price) using the Headline font for the item name and the Label font for the description.
- **Input Fields:** Minimalist. Only a bottom border (1px Espresso) that thickens or changes to Terracotta on focus.
- **Chips/Badges:** Small, uppercase labels with a light Terracotta background (15% opacity) to denote "New," "Specialty," or "Vegan."
- **Featured Component (The "Platter"):** A large-scale horizontal component that pairs a high-res image on one side with an editorial quote and a CTA on the other, used to highlight the *Pan, Café,* or *Vermut* pillars.