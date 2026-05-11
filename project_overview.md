# 📋 Project Overview — TinDog Landing Page

## 🎯 Goal
Clones a **Tinder-style app landing page** using Bootstrap 5. This is one of the more complex static projects in the collection — it has 5 distinct sections, uses many Bootstrap components, and layers custom CSS on top of Bootstrap defaults.

## 🧠 Page Architecture (Sections)

### 1. `#title` — Hero Section
```html
<section id="title" class="gradient-background">
```
Uses Bootstrap's **Hero** pattern with a reversed column layout (`flex-lg-row-reverse`):
- Right column: iPhone mockup image
- Left column: Heading + two download buttons (Apple/Google Play)

The gradient background is defined in `css/style.css`.

### 2. `#features` — Feature Cards 
```html
<section id="features">
```
Three horizontally arranged feature items using `row-cols-1 row-cols-lg-3`. Each item has:
- An SVG Bootstrap Icon in a square icon box
- Heading and description

### 3. `#testimonial` — Quote Section
```html
<section id="testimonial">
```
A full-width hero-style quote block (`p-5 text-center bg-body-tertiary`) with:
- The dog quote (Pebbles, New York)
- A circular dog profile image (styled with custom `.profile-img` class)
- Four press/media logos in a responsive row

### 4. `#pricing` — Pricing Cards
```html
<section id="pricing">
```
Three Bootstrap cards using `row-cols-1 row-cols-md-3`:
| Plan | Price | Style |
|---|---|---|
| Chihuahua | $0/mo | Outline button |
| Labrador | $15/mo | Dark filled button |
| Mastiff | $29/mo | Dark header card |

### 5. `#footer` — Footer
Same gradient background as the hero, with a `row-cols-md-5` layout of navigation columns.

## 🎨 Custom CSS (css/style.css)
Two key CSS additions on top of Bootstrap:
1. **`.gradient-background`** — Applied to hero and footer. A colorful gradient that defines TinDog's brand.
2. **`.profile-img`** — Circular crop for the dog testimonial photo using `border-radius: 50%`.

## 📊 Difficulty Level
| Aspect | Rating |
|---|---|
| HTML | ⭐⭐⭐ (many nested Bootstrap classes) |
| Bootstrap Knowledge | ⭐⭐⭐⭐ (multiple components) |
| Custom CSS | ⭐ (minimal — gradient + circle) |
| Overall | ⭐⭐⭐ Intermediate |

## 💡 Next Steps
- Add Bootstrap carousel to the testimonials section
- Make pricing highlight the "Labrador" plan as "Most Popular"
- Add a real nav bar at the top with smooth scroll
- Animate the iPhone image entrance with CSS keyframes
- Deploy to GitHub Pages
