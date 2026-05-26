# Meeting Room MR — Design System

## Overview
A premium, modern design system for a luxury event venue in Thessaloniki. The aesthetic is "Dark Luxury" — combining moody charcoal/black backgrounds with warm golden accents and crisp white typography.

---

## 🎨 Color Palette

### Primary Colors
- **Background (Main):** `#121212` (Charcoal Black)
- **Background (Secondary):** `#1A1A1A` (Lighter Charcoal)
- **Accent (Gold):** `#C8A864` (Metallic Gold)
- **Accent (Gold Hover):** `#D4BB80` (Lighter Gold)

### Typography Colors
- **Heading/Body Primary:** `#FFFFFF` (Pure White)
- **Body Secondary:** `#B0B0B0` (Soft Gray)
- **Accent Text:** `#C8A864` (Gold)

### Functional Colors
- **Surface (Glass):** `rgba(255, 255, 255, 0.05)`
- **Border:** `rgba(200, 168, 100, 0.2)` (Subtle Gold Border)

---

## Typography

**Headings:** `Playfair Display` (Serif)
- Luxurious, elegant, and classic.
- Weights: 600 (Semi-bold), 700 (Bold).
- Usage: Hero titles, Section headers.

**Body:** `Inter` (Sans-serif)
- Modern, clean, and highly readable.
- Weights: 400 (Regular), 500 (Medium).
- Usage: Paragraphs, UI elements, buttons.

### Scale
- **H1 (Hero):** 64px / 1.2 line-height
- **H2 (Section):** 48px / 1.3 line-height
- **H3 (Sub-header):** 32px / 1.4 line-height
- **Body Large:** 18px / 1.6 line-height
- **Body Regular:** 16px / 1.6 line-height
- **Small/Label:** 14px / 1.5 line-height

---

## 📏 Spacing & Grid

- **Base Unit:** 8px
- **Container Max-Width:** 1200px
- **Section Padding:** 120px (Desktop), 80px (Mobile)
- **Grid:** 12-column grid with 24px gutters.

---

## ✨ Glassmorphism Specs

To be used for cards, navigation, and overlays to create depth.

- **Background:** `rgba(255, 255, 255, 0.03)`
- **Backdrop-filter:** `blur(12px)`
- **Border:** `1px solid rgba(255, 255, 255, 0.1)`
- **Box-shadow:** `0 8px 32px 0 rgba(0, 0, 0, 0.8)`

---

## 🎬 Animation Guidelines

- **Transitions:** `300ms cubic-bezier(0.4, 0, 0.2, 1)` for all hover states.
- **Scroll Reveals:** Fade-in from bottom (20px) with 0.8s duration.
- **Parallax:** Subtle background movement on the Hero and CTA sections.
- **Hover States:** Buttons should scale slightly (1.02) and brighten.

---

## 🧩 Component Design Specs

### Buttons (Primary)
- **Background:** `#C8A864` (Gold)
- **Text:** `#121212` (Black)
- **Border-radius:** 0px (Sharp, luxury aesthetic)
- **Padding:** 16px 32px
- **Font:** Inter, 600, All-caps, 1px Letter-spacing

### Buttons (Secondary/Ghost)
- **Background:** Transparent
- **Border:** 1px solid `#C8A864`
- **Text:** `#C8A864`
- **Hover:** Gold background with black text.

### Cards (Gallery/Services)
- **Style:** Minimalist, full-bleed images or glassmorphism containers.
- **Hover:** Image zoom (1.1x) with a gold overlay or border reveal.

### Navigation
- **Style:** Sticky, glassmorphism background.
- **Logo:** Left-aligned, gold text or SVG.
- **Links:** Right-aligned, Inter, 500, white, gold underline on hover.

---

## 🖼️ Visual Assets
All images generated for this project are located in `/home/team/shared/images/`.
- `hero-bg.png`: Main hero background
- `gallery-1.png` - `gallery-4.png`: Venue feature images
- `about.png`: About section image
- `cta-bg.png`: Call-to-action background
- `venue-overview.png`: General aesthetic shot
