# Alejandro Ramírez — Studio Bible

Version 1.0

Last updated: 2026-07-17

---

## Purpose

This document is the shared memory of the project.

It records the principles and architectural decisions that define the website.

New entries are added only when they change how the website is conceived or built.

---

## Vision

A static studio website presenting my image-making practice through film, photography and writing.

The website is not a portfolio.

It is a studio: an architectural space that visitors enter to encounter a way of seeing, thinking and making.

Visitors move through rooms rather than pages.

---

## Design Language

The website should feel:

- cinematic
- generous
- confident
- materially simple
- warm
- never decorative

The interface recedes behind the work.

Motion should feel alive, never flashy.

Editing always takes precedence over decoration.

---

## Principles

- Static website.
- HTML and CSS first.
- Minimal interface.
- Fast loading.
- One stylesheet.
- Reuse before creating.
- Lowercase naming throughout.
- HTML describes structure.
- CSS describes appearance.
- The interface should disappear behind the work.

---

## Structure

```
index

↓

foyer

↓

images-room
```

External rooms

- Journal → FOOD is Everywhere
- Kitchen → La Cocina Archive

---

## The Image Room

The Image Room is a composed visual score rather than a gallery.

Projects are movements within that score.

Each movement occupies one horizontal band and establishes its own rhythm, density and colour palette.

A band may contain:

- moving image
- still image
- text
- colour
- sketches
- process material

The composition is fixed.

The browser frames the score but never composes it.

Desktop is the master composition.

Mobile is a re-edit of the same score rather than a scaled copy.

---

## Media Standards

Media is produced as a small set of canonical masters.

The architecture determines the framing.

CSS implements it.

### Images

Square

2500 × 2500 px

Landscape

2560 × 1440 px (16:9)

Portrait

1440 × 2560 px

### Video

Landscape

1920 × 1080 px (16:9)

Square

1080 × 1080 px

---

## Collaboration

When generating code:

- Read this guide first.
- Respect the existing architecture.
- Implement before redesigning.
- HTML first.
- CSS only when requested.
- Never duplicate CSS.
- Reuse existing classes whenever possible.

Every design decision should strengthen the sequence rather than add complexity.

---

## Architectural Decisions

### 2026-07-14

✓ Static website.

✓ HTML and CSS first.

✓ Lowercase naming throughout.

✓ The landing page uses a slow RGB animation for **cinema**.

✓ Moving and still images have equal editorial status.

---

### 2026-07-15

✓ The Image Room is a score rather than a gallery.

✓ Editing takes precedence over chronology.

✓ Every project occupies one horizontal band.

✓ Colour fields are editorial elements.

✓ Project titles belong to the project band.

✓ Every tile has an intentional position.

---

### 2026-07-17

✓ Every project band is an independent composition.

✓ Each band has its own rhythm, scale and spacing.

✓ Colour belongs to the project rather than individual tiles.

✓ Titles are anchored within their project band.

✓ Desktop is the master composition.

✓ Mobile is a re-edit rather than a scaled copy.

✓ The website is edited like a film: every modification should strengthen the sequence.

---

## Open Questions

- Should the Image Room use captions?
- Should projects remain anonymous?
- Should videos autoplay only when visible?
- How playful should the interface become?