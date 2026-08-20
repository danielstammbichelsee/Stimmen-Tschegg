---
name: Aura Harmony
colors:
  surface: '#0b1326'
  surface-dim: '#0b1326'
  surface-bright: '#31394d'
  surface-container-lowest: '#060e20'
  surface-container-low: '#131b2e'
  surface-container: '#171f33'
  surface-container-high: '#222a3d'
  surface-container-highest: '#2d3449'
  on-surface: '#dae2fd'
  on-surface-variant: '#bec8d2'
  inverse-surface: '#dae2fd'
  inverse-on-surface: '#283044'
  outline: '#88929b'
  outline-variant: '#3e4850'
  surface-tint: '#89ceff'
  primary: '#89ceff'
  on-primary: '#00344d'
  primary-container: '#0ea5e9'
  on-primary-container: '#003751'
  inverse-primary: '#006591'
  secondary: '#7bd0ff'
  on-secondary: '#00354a'
  secondary-container: '#00a6e0'
  on-secondary-container: '#00374d'
  tertiary: '#bdc2ff'
  on-tertiary: '#131e8c'
  tertiary-container: '#8792fe'
  on-tertiary-container: '#17228f'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#c9e6ff'
  primary-fixed-dim: '#89ceff'
  on-primary-fixed: '#001e2f'
  on-primary-fixed-variant: '#004c6e'
  secondary-fixed: '#c4e7ff'
  secondary-fixed-dim: '#7bd0ff'
  on-secondary-fixed: '#001e2c'
  on-secondary-fixed-variant: '#004c69'
  tertiary-fixed: '#e0e0ff'
  tertiary-fixed-dim: '#bdc2ff'
  on-tertiary-fixed: '#000767'
  on-tertiary-fixed-variant: '#2f3aa3'
  background: '#0b1326'
  on-background: '#dae2fd'
  surface-variant: '#2d3449'
  vocal-pure: '#f0f9ff'
  harmony-teal: '#2dd4bf'
  surface-navy: '#1e293b'
typography:
  display:
    fontFamily: Syne
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Syne
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Syne
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 34px
  headline-md:
    fontFamily: Syne
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-sm:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.05em
  label-caps:
    fontFamily: JetBrains Mono
    fontSize: 10px
    fontWeight: '700'
    lineHeight: 12px
    letterSpacing: 0.1em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 4px
  gap-sm: 8px
  gap-md: 16px
  gap-lg: 32px
  margin-mobile: 20px
  margin-desktop: 40px
  gutter: 16px
---

## Brand & Style

The design system is tailored for vocal ensembles and choral communities, focusing on the "Stimmencheck" (vocal analysis) experience. The brand personality is professional, cheerful, and welcoming—moving away from high-intensity industry management toward a supportive, artistic atmosphere. It evokes the feeling of a bright rehearsal hall where precision meets passion.

The visual style is **Modern / Glassmorphic**, utilizing a deep navy foundation to ground the design, while vibrant blue accents and soft, translucent layers provide a sense of lightness and clarity. It emphasizes the fluid nature of sound and the technical beauty of vocal harmonics without feeling sterile.

## Colors

This system utilizes a "Deep Azure" palette optimized for focus and clarity during vocal practice and analysis.

- **Primary (Energetic Blue):** Represents the lead melody. Used for critical actions, brand identity, and active vocal data paths.
- **Secondary (Sky Blue):** Represents harmony. Used for secondary UI elements, interactive states, and supporting visualizations.
- **Tertiary (Soft Indigo):** Used for auxiliary information, subtle accents, and differentiating vocal ranges (e.g., Alto/Bass).
- **Neutral (Deep Navy):** Provides a rich, professional backdrop that reduces eye strain and allows the bright blue tones to feel welcoming rather than aggressive.

## Typography

The typography is structured to facilitate both artistic expression and technical feedback.

- **Headlines (Syne):** Chosen for its avant-garde and rhythmic quality. It mirrors the unique character of individual voices. Use for section titles and "Stimmencheck" results.
- **Body (Hanken Grotesk):** Provides an approachable and highly legible reading experience for vocal tips, feedback, and educational content.
- **Technical Labels (JetBrains Mono):** Used for precise vocal metrics, frequency data (Hz), and time-stamped feedback. The monospaced nature emphasizes accuracy in vocal analysis.

## Layout & Spacing

The system follows a **4px baseline rhythm** to ensure alignment across complex data visualizations. It utilizes a **fluid grid** model that adapts to the user's focus.

- **Mobile:** 4-column grid with a 20px margin. Layouts are vertically stacked to allow for easy one-handed navigation during vocal exercises.
- **Tablet/Desktop:** 12-column grid that allows for side-by-side comparison of vocal takes and analysis charts.
- **Rhythm:** Generous white space is encouraged to keep the interface feeling "airy" and approachable, reflecting a clear vocal tone.

## Elevation & Depth

Depth is used to represent the layers of a choir. We avoid heavy, dark shadows in favor of **Tonal Layering** and **Luminous Glassmorphism**.

- **Surface Levels:** The base is the darkest navy. Successive surfaces (cards, sidebars) use slightly lighter navy tones with subtle 1px borders in a low-opacity primary blue.
- **Glass Effects:** Modals and overlay panels use backdrop blurs (20px-30px) with a semi-transparent blue tint. This keeps the user connected to the vocal analysis visualization even when a menu is open.
- **Interaction Glow:** Active states should use a soft outer "aura" glow using the primary blue to signify energy and resonance.

## Shapes

The shape language is defined as **Rounded (0.5rem)**, moving away from sharp edges to create a friendlier, more welcoming environment for singers.

- **Standard Elements:** Buttons and input fields use a 0.5rem (8px) radius.
- **Analysis Cards:** Use 1rem (16px) for larger containers to soften the visual impact of data-heavy screens.
- **Vocal Indicators:** Waveforms and progress indicators should use fully rounded (pill-shaped) caps to suggest the smoothness of a well-supported vocal line.

## Components

- **Buttons:** Primary buttons are bright blue (#0ea5e9) with white text, featuring a subtle gradient to a slightly darker blue. Secondary buttons use a transparent background with a blue border.
- **Vocal Analysis Cards:** These feature high-contrast waveforms against a navy surface. Use translucency for historical data overlays.
- **Inputs:** Fields are dark navy with a soft blue border. On focus, the border glows and the label shifts to the energetic primary blue.
- **Chips/Tags:** Used for vocal ranges (Soprano, Alto, Tenor, Bass) and "Stimmencheck" attributes. These should be pill-shaped with soft, low-contrast background fills.
- **Progress Indicators:** Use fluid, rounded bars. When showing "Vocal Accuracy," use a gradient from Secondary Blue to Harmony Teal.
- **Lists:** Feedback lists should be separated by soft blue dividers (10% opacity) with generous vertical padding to maintain the "cheerful and open" vibe.