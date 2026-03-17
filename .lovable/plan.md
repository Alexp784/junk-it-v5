

# JUNK IT V5 — High-Conversion Junk Removal Landing Page

## Overview
A single-page, mobile-first junk removal site with aggressive industrial styling (neon green #39FF14 on dark backgrounds), mirroring the layout/CTA flow of burrhauling.com. Every button functional (tel, sms, mailto, form submit).

## Sections (in order)

### 1. Sticky Header
- Logo left, CTA cluster right (Call, Text, Get a Quote)
- Semi-opaque dark bg with neon green bottom border glow
- Mobile: hamburger menu, persistent bottom action bar with Call/Text

### 2. Hero (2-column)
- Left: "NEED JUNK REMOVAL?" headline (Oswald/Anton, uppercase, neon green), checklist with neon check icons, trust sentence, 3 CTA buttons (Call Now, Text Us, Get Free Quote)
- Right: Trailer image with neon glow backdrop
- Quick contact text below image

### 3. Contact Strip
- Full-width neon green bar with phone + email (clickable)

### 4. About / Owner Note
- Short personal paragraph + portrait placeholder with desaturated neon vignette treatment

### 5. Services Grid
- 6 cards (Furniture, Appliance, Electronics, Garage Cleanouts, Construction Debris, Full Property Cleanouts)
- Icon + title + description + "Learn More" link to #quote
- Hover: green glow + lift animation

### 6. Why Choose Us
- 4 columns: Fast & Reliable, Same-Day Service, Affordable Pricing, Professional & Friendly
- Icons + supporting text

### 7. Reviews / Social Proof
- Sample testimonial cards with star ratings (placeholder for future Google Reviews)

### 8. Quote Form (#quote)
- Fields: Name, Phone, Email, Address, Description (textarea), Image upload (up to 5), Preferred contact method (radio), Consent checkbox
- Formspree integration with placeholder ID
- Success modal: "MISSION RECEIVED. WE'LL CONTACT YOU SHORTLY."

### 9. Ready CTA Band
- Bold band with Call Now, Text Now, Get Free Quote buttons

### 10. Footer
- Phone, email, nav links, copyright © 2026 JUNK IT V5

## Design System
- Colors: #0b0d0a bg, #1a2f1a surfaces, #39FF14 primary, #b7ff66 accent, #d6d6d6 text
- Fonts: Oswald (headings, uppercase, heavy), Inter (body)
- Borders: 1px with neon glow, rounded-sm or rounded-none
- CSS concrete texture overlay, neon box-shadows, radial green glow behind hero
- Framer Motion: fade-up on scroll, button hover scale/glow, 50ms card stagger

## Animations
- Scroll-triggered fade-up for all sections
- Button hover: scale(1.03) + neon glow + brightness boost
- Smooth scrolling for all anchor links
- Service cards: staggered entrance

## Accessibility
- WCAG AA contrast on all CTAs
- aria-labels on tel/sms/mailto links
- Min 48px tap targets on mobile
- Lazy-loaded images

## Form Delivery
- Formspree placeholder (instructions in README for swapping ID + forwarding to junkitv5@gmail.com)
- File upload accepts image/* up to 5 files, 8MB each

## No backend needed
- Pure frontend with Formspree for form handling

