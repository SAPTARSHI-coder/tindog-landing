# TinDog — App Marketing Landing Page

A full multi-section marketing landing page for **TinDog**, a fictional dog social networking app styled as a Tinder parody. Built with Bootstrap 5 and a custom gradient theme, the page demonstrates realistic app marketing page structure and Bootstrap component composition.

## Overview

The page contains five sections:
- **Hero**: Gradient background, app mockup image, tagline, and App Store / Google Play download buttons
- **Features**: Three feature cards — "Easy to Use", "Elite Clientele", "Guaranteed to Work"
- **Testimonial**: Pull quote with press logo grid (TechCrunch, Mashable, etc.)
- **Pricing**: Three tier cards named after dog breeds — Chihuahua (free), Labrador ($15/mo), Mastiff ($29/mo)
- **Footer**: Multi-column navigation footer with a gradient background

## Tech Stack

| Technology | Role |
|---|---|
| HTML5 | Page structure and semantics |
| Bootstrap 5.3 (CDN) | All layout, grid, and components |
| Custom CSS (`css/styles.css`) | Gradient theming and profile image styling |
| Bootstrap Icons (SVG) | App store download button icons |

## Project Structure

```
tindog-landing/
├── index.html          — Full landing page
├── solution.html       — Reference implementation
├── css/
│   └── styles.css      — Custom gradient and image overrides
├── images/             — iphone.png, dog-img.jpg, press logos
└── goal images/        — Reference screenshots
```

## Getting Started

Open `index.html` in any browser. An internet connection is required for Bootstrap and its icon font.

## Key Concepts

- Section-based page composition with `<section id="...">` anchors
- Bootstrap **grid system**: `row-cols-1 row-cols-lg-3` for responsive card rows
- Bootstrap **Cards** for pricing plan display
- Full-page gradient background layered under Bootstrap utilities
- Custom CSS overriding Bootstrap defaults without breaking responsiveness

---
*Made with love by Saptarshi Sadhu*

