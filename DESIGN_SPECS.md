# Design Specifications & Mockup Guide

---

## STATIC AD (Instagram/LinkedIn/Google Ads)

### Dimensions & Format
- **Size:** 1080 × 1350 px (vertical) or 1200 × 628 px (horizontal)
- **Safe zone:** Leave 20px padding all sides
- **File:** PNG or JPG, RGB, 72 DPI

### Layout Structure
```
┌─────────────────────────────┐
│  [PADDING]                  │
│  ┌─────────────────────────┐│
│  │ HEADLINE (top third)    ││
│  │ Large, bold, white      ││
│  │ "Stop Missing Meetings" ││
│  ├─────────────────────────┤│
│  │                         ││
│  │ [PRODUCT IMAGE]         ││
│  │ (center third)          ││
│  │ Smart display showing   ││
│  │ calendar, clean desk    ││
│  │                         ││
│  ├─────────────────────────┤│
│  │ SUPPORTING TEXT         ││
│  │ (bottom third)          ││
│  │ "Your calendar.         ││
│  │  Always visible.        ││
│  │  Always on."            ││
│  │                         ││
│  │ [CTA BUTTON]            ││
│  │ "Shop Now →"            ││
│  └─────────────────────────┘│
│  [PADDING]                  │
└─────────────────────────────┘
```

### Typography
- **Headline:** Bold sans-serif (e.g., Inter Bold, Montserrat Bold)
  - Size: 54–64 px
  - Color: White (#FFFFFF)
  - Line height: 1.2
  - Text: "Stop Missing Meetings"

- **Sub-headline:** Regular sans-serif
  - Size: 28–32 px
  - Color: Light gray (#E0E0E0)
  - Text: "Your calendar. Always visible. Always on."

- **Body text:** Regular sans-serif
  - Size: 16–18 px
  - Color: White (#FFFFFF)
  - Text: "Real-time sync with Google Calendar. On your desk. Always."

- **CTA button text:** Bold sans-serif
  - Size: 18–20 px
  - Color: White on colored button
  - Text: "Shop Now →"

### Color Palette
- **Background:** Dark navy or charcoal (#1A1A2E or #0F0F1E)
- **Accent/Button:** Teal or bright blue (#00D4FF or #0066FF)
- **Text:** White (#FFFFFF) and light gray (#E0E0E0)
- **CTA Button:** Bright accent color with slight gradient or shadow

### Product Image Guidelines
- **What to show:** Smart display on a minimalist desk, showing a calendar interface
- **Style:** Clean, professional, aspirational but realistic
- **Lighting:** Soft, natural or warm white light; no harsh shadows
- **Composition:** Display is center-right, shows calendar grid clearly, desk is visible but not cluttered
- **Alternative:** Close-up of just the display screen showing calendar, high-quality and crisp

### CTA Button Design
- **Shape:** Rounded rectangle (8–12 px border radius)
- **Padding:** ~16 px vertical, 32 px horizontal
- **Hover state:** Slightly brighter or add subtle shadow
- **Placement:** Bottom center or bottom right of ad

---

## CAROUSEL (5–7 Slides, Instagram/Facebook)

### Dimensions
- **Size:** 1080 × 1350 px (vertical, portrait orientation)
- **Format:** PNG or JPG, RGB, 72 DPI
- **File naming:** carousel_slide_1.png, carousel_slide_2.png, etc.

### Slide-by-Slide Breakdown

#### Slide 1: Problem Hook
- **Headline:** "You have 47 meetings this week."
- **Sub-text:** "And you're about to double-book Tuesday at 3 PM."
- **Visual:** Chaos visual — calendar grid with red X's, overlapping calendar notifications, frazzled professional
- **Color:** Red accent on neutral background
- **Goal:** Grab attention, make audience nod in recognition

#### Slide 2: Aha Moment / Product Intro
- **Headline:** "Meet your new desk assistant."
- **Sub-text:** "A beautiful 7.5\" display that shows your calendar. Always."
- **Visual:** Hero shot of the smart display on a clean desk, calendar visible and clear
- **Color:** Teal/blue accent, clean white space
- **Goal:** Introduce solution calmly

#### Slide 3: Real-Time Sync
- **Headline:** "Real-time sync with Google Calendar."
- **Sub-text:** "Add a meeting on your phone → it appears instantly on your desk."
- **Visual:** Split screen: phone adding event + display updating in real-time (arrows between them)
- **Color:** Blue accent
- **Goal:** Demonstrate key feature with visual flow

#### Slide 4: All-Day View / Peace of Mind
- **Headline:** "No more 'am I free at 2 PM?'"
- **Sub-text:** "Your entire day, visible at a glance. No phone, no laptop required."
- **Visual:** Wide calendar view on display, person at desk looking relieved/calm
- **Color:** Neutral with soft green accent (calm, trust)
- **Goal:** Emotional benefit — peace of mind

#### Slide 5: Integrations (Optional, or combine with Slide 6)
- **Headline:** "Works with your existing tools."
- **Sub-text:** "Google Calendar. Slack. Notion. Your workflow, unchanged."
- **Visual:** Logos of integrations arranged neatly, or icon grid
- **Color:** Gray/white background with colored logos
- **Goal:** Remove friction — no need to switch tools

#### Slide 6: Feature Callout (Battery/Customization)
- **Headline:** "30-day battery. Infinite customization."
- **Sub-text:** "Works offline. Syncs when you're back online."
- **Visual:** Display showing different screens (calendar, weather, to-do list, custom art)
- **Color:** Teal accent
- **Goal:** Show versatility and reliability

#### Slide 7: CTA & Social Proof (Final Slide)
- **Headline:** "Ready to reclaim your calendar?"
- **Sub-text:** "Join 500+ professionals who stopped missing meetings."
- **Visual:** 3–4 testimonial quotes OR product image with CTA button overlay
- **Color:** Bold accent (match Slide 2), CTA button prominent
- **CTA:** "Shop Now" or "Learn More"
- **Goal:** Convert — clear, confident CTA

### Carousel Design Notes
- **Consistency:** Same logo, color palette, and font family across all slides
- **Text readability:** White or dark text on light backgrounds (or vice versa); high contrast
- **Pacing:** Each slide tells one idea; avoid text overload
- **Visual flow:** Use icons, arrows, or diagrams to show relationships (esp. Slide 3, 5)
- **Branding:** Include small logo in corner of each slide (or on Slide 1 only)

---

## INTERACTIVE HTML MOCKUPS (for reference)

See STATIC_AD_MOCKUP.html and CAROUSEL_MOCKUP.html in the work/ folder.

---

## Tools to Use for Design
1. **Figma** (free): Most flexible, easy to export
2. **Canva Pro** (free tier available): Templates, quick turnaround
3. **Adobe Express** (free): Similar to Canva
4. **Photoshop/Illustrator** (if you have access): Full control

---

## Export Checklist
- [ ] Static ad: 1080×1350 or 1200×628 px, PNG/JPG, RGB
- [ ] Carousel: 7 slides × 1080×1350 px, PNG/JPG, RGB
- [ ] All text is readable at web resolution (test by zooming out)
- [ ] CTAs are visible and clickable-looking
- [ ] File sizes < 5 MB each (compress if needed)
- [ ] No broken images or missing fonts

---

## Next: See STORYBOARD.md for video/reel details
