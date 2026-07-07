---
version: alpha
name: Dilan Grijalva Portfolio
description: Editorial minimal design system for a personal software developer portfolio without project case studies.
colors:
  primary: "#111418"
  secondary: "#6F6F68"
  tertiary: "#FF4F00"
  neutral: "#FBFAF7"
  background: "#FBFAF7"
  surface: "#FFFFFF"
  text: "#111418"
  muted: "#6F6F68"
  border: "#D9D7D0"
  accent: "#FF4F00"
  accent-soft: "#FFF0E8"
  on-accent: "#111418"
typography:
  headline-display:
    fontFamily: 'ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif'
    fontSize: 72px
    fontWeight: 650
    lineHeight: 1.02
    letterSpacing: 0px
  headline-lg:
    fontFamily: 'ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif'
    fontSize: 36px
    fontWeight: 620
    lineHeight: 1.14
    letterSpacing: 0px
  body-lg:
    fontFamily: 'ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif'
    fontSize: 20px
    fontWeight: 400
    lineHeight: 1.55
    letterSpacing: 0px
  body-md:
    fontFamily: 'ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif'
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.6
    letterSpacing: 0px
  label-sm:
    fontFamily: '"SFMono-Regular", "Roboto Mono", "JetBrains Mono", Consolas, monospace'
    fontSize: 12px
    fontWeight: 600
    lineHeight: 1.2
    letterSpacing: 0px
rounded:
  none: 0px
  sm: 4px
  md: 6px
  lg: 8px
  full: 9999px
spacing:
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 40px
  xxl: 72px
  page-x: 48px
components:
  page:
    backgroundColor: "{colors.background}"
    textColor: "{colors.text}"
    typography: "{typography.body-md}"
  surface-panel:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.text}"
    rounded: "{rounded.md}"
    padding: 24px
  muted-copy:
    backgroundColor: "{colors.background}"
    textColor: "{colors.muted}"
    typography: "{typography.body-md}"
  accent-link:
    backgroundColor: "{colors.background}"
    textColor: "{colors.primary}"
    typography: "{typography.body-md}"
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.neutral}"
    typography: "{typography.body-md}"
    rounded: "{rounded.sm}"
    padding: 14px
  button-primary-hover:
    backgroundColor: "{colors.accent}"
    textColor: "{colors.on-accent}"
  section-rule:
    backgroundColor: "{colors.border}"
    textColor: "{colors.primary}"
    height: 1px
  portrait:
    backgroundColor: "{colors.accent-soft}"
    textColor: "{colors.primary}"
    rounded: "{rounded.md}"
    size: 240px
---

# Dilan Grijalva Portfolio Design System

## Overview

The portfolio should feel like a quiet editorial profile, not a generated product landing page. The design is for hiring teams who need to understand Dilan's practical strengths quickly: mobile development, backend work, maintainable code, and product-minded execution.

The page should be honest about not having public projects to feature. Replace project-grid pressure with credible proof: current focus, technical stack, working principles, location, availability, and direct email contact.

## Colors

The palette is almost entirely warm paper, ink, and soft gray. Orange remains from the existing portfolio but becomes a rare detail instead of the visual identity.

- **Primary / Text (#111418):** Main headlines, body text, navigation, and primary buttons.
- **Neutral / Background (#FBFAF7):** Warm page canvas, softer than pure white.
- **Surface (#FFFFFF):** Reserved for small contained surfaces when content needs separation.
- **Muted (#6F6F68):** Secondary copy, captions, and metadata.
- **Border (#D9D7D0):** Thin dividers and structural rules.
- **Accent (#FF4F00):** Sparse interaction and emphasis only; use it for dots, rules, underlines, and hover fills with dark text.

## Typography

Use a system sans-serif stack for almost everything. It should read clean, fast, and mature. JetBrains Mono may appear only in small labels or metadata, never as the dominant voice.

Headlines should be large enough to establish confidence, but not inflated into a marketing hero. Body copy should stay readable at 16-20px with comfortable line height. Letter spacing remains `0px`.

## Layout

Use one centered page column with a maximum width around 1120px and fluid side gutters. Favor horizontal rules, whitespace, and clear alignment over cards.

The first viewport should show the identity, location, focus, email action, and a hint of the next section. Desktop layout may use a text/photo split; mobile should stack naturally without reordering content into a novelty layout.

## Elevation & Depth

The design is flat. Do not use drop shadows, glass effects, gradients, or decorative glows. Hierarchy comes from scale, whitespace, type weight, borders, and restrained contrast.

## Shapes

Use sharp or lightly softened corners only. Rectangular interactive elements should use 4px radius, portrait frames 6px, and repeated UI surfaces no more than 8px.

## Components

Navigation links are plain text with a subtle accent underline on hover and focus. Primary email actions use an ink fill with warm-paper text, shifting to an orange fill with dark text only on hover.

Sections use border-top rules and compact labels. Stack items and principles should read as editorial rows, not pills or feature cards. The portrait is a restrained identity anchor with a thin border and no decorative treatment.

## Do's and Don'ts

- Do present Dilan as a practical software developer for hiring teams.
- Do use the orange accent sparingly for hover states, focus rings, underlines, and small graphic marks.
- Do make the absence of public projects feel intentional and honest.
- Don't invent case studies, testimonials, metrics, client logos, or project thumbnails.
- Don't use bento dashboards, gradient blobs, dark terminal themes, oversized hero cards, or generic AI landing-page composition.
- Don't add motion beyond subtle entrance, hover, and focus transitions.
