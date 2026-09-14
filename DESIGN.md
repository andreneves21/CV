---
name: Technical Precision
colors:
  surface: '#f7f9fb'
  surface-dim: '#d8dadc'
  surface-bright: '#f7f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f6'
  surface-container: '#eceef0'
  surface-container-high: '#e6e8ea'
  surface-container-highest: '#e0e3e5'
  on-surface: '#191c1e'
  on-surface-variant: '#45464d'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#76777d'
  outline-variant: '#c6c6cd'
  surface-tint: '#565e74'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#131b2e'
  on-primary-container: '#7c839b'
  inverse-primary: '#bec6e0'
  secondary: '#505f76'
  on-secondary: '#ffffff'
  secondary-container: '#d0e1fb'
  on-secondary-container: '#54647a'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#001f26'
  on-tertiary-container: '#0090a9'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dae2fd'
  primary-fixed-dim: '#bec6e0'
  on-primary-fixed: '#131b2e'
  on-primary-fixed-variant: '#3f465c'
  secondary-fixed: '#d3e4fe'
  secondary-fixed-dim: '#b7c8e1'
  on-secondary-fixed: '#0b1c30'
  on-secondary-fixed-variant: '#38485d'
  tertiary-fixed: '#acedff'
  tertiary-fixed-dim: '#4cd7f6'
  on-tertiary-fixed: '#001f26'
  on-tertiary-fixed-variant: '#004e5c'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  name-heading:
    fontFamily: Inter
    fontSize: 36px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  section-title:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '700'
    lineHeight: 20px
    letterSpacing: 0.1em
  job-title:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
  body-main:
    fontFamily: Inter
    fontSize: 11pt
    fontWeight: '400'
    lineHeight: '1.6'
  metadata:
    fontFamily: Inter
    fontSize: 10px
    fontWeight: '500'
    lineHeight: 14px
  code-label:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  page-margin: 2rem
  section-gap: 2.5rem
  entry-gap: 1.5rem
  gutter: 1.5rem
  badge-padding: 0.25rem 0.75rem
---

## Brand & Style

The design system is engineered for the modern IT professional. It prioritizes information density and clarity through a **Corporate/Modern** aesthetic with hints of **Minimalism**. The target audience includes technical recruiters and engineering managers who value efficiency and structured data. 

The emotional response should be one of confidence, technical competence, and meticulous organization. Visual interest is generated through precise alignment, generous whitespace to prevent cognitive overload, and a vibrant accent color that guides the eye to key achievements and contact information.

## Colors

The palette is anchored in a deep slate "Primary" for headings and body text to ensure maximum contrast and professional weight. 
- **Primary (#0F172A):** Used for names, section headers, and primary content.
- **Secondary (#64748B):** A muted slate gray for dates, metadata, and secondary descriptions.
- **Tertiary (#06B6D4):** A vibrant Cyan used sparingly for links, bullet points, and high-impact skill highlights.
- **Neutral (#F8FAFC):** A crisp, cool white used for the page background and card surfaces.
- **Accent Surfaces:** Use a 10% opacity version of the Tertiary color for subtle background fills on badges or decorative elements.

## Typography

This design system uses a dual-font approach. **Inter** serves as the workhorse for all prose and headings, providing a systematic and neutral feel. **JetBrains Mono** is introduced for technical labels and skill badges to lean into the "tech-oriented" narrative.

- **Scale:** Maintain a strict hierarchy. Names should be the largest element on the page.
- **Readability:** Body text is set at 11pt (standard for CVs) with a generous 1.6 line height to facilitate skimming.
- **Mobile:** For digital viewing on mobile devices, `name-heading` should scale down to 28px, and `job-title` to 16px to prevent awkward line breaks.

## Layout & Spacing

The design system utilizes a **fixed-width layout** optimized for A4 or US Letter dimensions. A two-column asymmetrical grid is recommended:
- **Sidebar (33%):** Houses contact info, skills, education, and technical stack.
- **Main Body (66%):** Houses the profile summary and work experience.

**Breakpoints:**
- **Desktop/Print:** Fixed 800px or 8.5in width. 
- **Tablet:** Fluid with 40px margins.
- **Mobile:** Single-column reflow where the Sidebar stacks above the Main Body.

Use a base-4 vertical rhythm. Elements should be spaced in multiples of 4px to maintain a rigid, technical structure.

## Elevation & Depth

This design system avoids heavy shadows to maintain a clean, "printed" feel even in digital formats.
- **Tonal Layers:** Use a subtle background fill (#F1F5F9) for sidebar sections to create separation from the main body.
- **Low-contrast Outlines:** Skill badges and input fields (if applicable) use a 1px solid border in the secondary color at 20% opacity.
- **No Shadows:** Do not use box-shadows on cards or badges. Depth is conveyed through color blocks and rule lines (0.5pt hairlines).

## Shapes

The shape language is **Soft** but disciplined. 
- **Badges/Chips:** Use `rounded-lg` (0.5rem) to differentiate them from the squared-off layout containers.
- **Experience Timeline:** Use circular nodes (8px) on a vertical hairline to represent milestones.
- **Images:** Profile photos should be clipped to a square with a slight `rounded-xl` (0.75rem) corner radius for a modern professional look.

## Components

### Skill Badges
Technical skills are displayed as chips. They feature a light grey background (#F1F5F9) and the `code-label` typography. High-priority skills use the Tertiary color as the text color.

### Experience Timeline
A vertical 1px line in Secondary color. Job titles are anchored by a 8px solid circle. The vertical line should be broken between different companies but continuous between roles at the same company.

### Profile Header
The name is set in `name-heading`. Below the name, a horizontal bar in the Tertiary color (width: 40px, height: 4px) provides a visual anchor. Contact icons should be simple SVG paths in the Secondary color, paired with `metadata` text.

### Progress Bars (Optional)
For language or specific tool proficiency, use a dual-tone bar: a 4px tall light gray track with a Tertiary color fill indicating the level.

### Cards
For projects, use a simple container with a 1px hairline border at the top only. This creates a "listing" effect that is cleaner than fully boxed cards.