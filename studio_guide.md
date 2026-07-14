# Alejandro Ramírez — Studio Guide

Version 0.2

Last updated: 2026-07-14

---

## Purpose

This document is the memory of the project.

It records the principles, decisions and questions that guide the evolution of the website.

Whenever an important decision is made, it is added here.

---

## Vision

A static studio website that presents my image-making practice through film, photography and writing.

The website is not a portfolio.

It is a studio: an architectural space that one enters. A place to encounter my way of seeing, thinking and making; to discover my work, and to connect with potential clients, collaborators and anyone interested in the ideas that shape my practice.

Visitors move through rooms rather than pages.

---

## Design Language

The website should feel:

- generous
- cinematic
- confident
- warm
- materially simple
- never decorative

Interactions should be subtle.

Motion should feel alive, never flashy.

The interface should recede behind the work.

Playfulness should emerge naturally through the work and small interactions, never through decoration.

---

## Principles

- Static website.
- HTML and CSS first.
- Minimal interface.
- Fast loading.
- No unnecessary technology.
- The Image Room is a moving-image room.
- Stills, films and installations have equal status.
- Editing is more important than chronology.
- The interface should disappear behind the work.
- Lowercase naming throughout the project.

---

## Structure

```
index.html

↓

foyer.html

↓

images-room.html
```

External rooms

- Journal → FOOD is Everywhere (Substack)
- Kitchen → La Cocina Archive

---

## HTML Style Guide

Every room follows the same structure.

```
head

↓

body

↓

main

↓

identity

↓

content
```

### Principles

- HTML describes structure.
- CSS describes appearance.
- Reuse existing CSS classes whenever possible.
- Avoid inline styles.
- Write readable HTML.

### Formatting

When an element contains multiple attributes, place each attribute on its own line.

Example:

```html
<img
    class="medium left"
    src="images/example.jpg"
    alt="">
```

Example:

```html
<video
    class="hero center"
    autoplay
    muted
    loop
    playsinline>

    <source
        src="images/example.mp4"
        type="video/mp4">

</video>
```

---

## Image Room Language

Scale

- hero
- large
- medium
- small

Position

- left
- center
- right

These classes describe the role of a work within the sequence, not its importance or aspect ratio.

---

## CSS Structure

Keep a single stylesheet.

Organize it into sections:

1. Base
2. Shared Identity
3. Foyer
4. Image Room
5. Animations
6. Responsive

Every CSS rule has one home.

Avoid duplicated selectors.

---

## Collaboration

When generating code:

- Read this guide first.
- Respect existing architecture.
- HTML first.
- CSS only when requested.
- Reuse existing classes whenever possible.
- Never duplicate CSS rules.
- Implement before redesigning.

---

## Technical Decisions

### 2026-07-14

✓ Static website.

✓ HTML and CSS first.

✓ Lowercase naming.

✓ Cinema uses a slow RGB animation.

✓ Mobile places "Say Hello" beneath Cinema.

✓ JPEG exports

- 2500 px
- Quality 75–80
- sRGB

✓ Video exports

- MP4
- H.264
- 1080p
- Rec.709

---

## Editorial Decisions

### 2026-07-14

✓ The Image Room is edited rather than chronological.

✓ Commercial and personal work coexist.

✓ Stills and moving image have equal status.

✓ Image scale and position are editorial decisions.

---

## Open Questions

- Should the Image Room use captions?
- Should projects remain anonymous?
- Should videos autoplay only when visible?
- How playful should the interface become?

---

## Next

- Build Image Room v0.1.
- Test image scale.
- Test visual rhythm.
- Evaluate desktop.
- Adapt for mobile.