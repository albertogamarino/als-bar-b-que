# Al's Bar-B-Que — GitHub Update v9

## What changed

### New effects
- Scroll reveal: IntersectionObserver on all sections — elements fade + slide up as they enter viewport
- Hero entrance: staggered animation per element on page load (label → h1 → copy → buttons)
- Marquee ticker: "LOW & SLOW ★ NO SHORTCUTS ★ EST. 2014 ★ BACKYARD CRAFT BBQ" scrolling band between hero and content — pure CSS
- Hero parallax: photo translates subtly on scroll (desktop only, passive listener)
- Photo scale: split section photos scale to 1.04 on hover
- Stars pulse: gentle opacity animation on Coming Soon ★★★
- Nav underline: sliding underline from left on hover

### Process section redesigned
- Giant typographic numbers (01–04) as decorative elements (opacity .10)
- 4-column horizontal grid with rust line divider per step
- long-smoke.jpg as dimmed background (opacity 7%) for visual depth
- Much more editorial — less "list on a website"

### Statement section
- Title size increased significantly (up to 8rem on desktop)
- New two-column layout: large title left, body text right aligned to baseline
- More sculptural, more impactful

### Footer
- Simplified to 2-column: brand left, links right
- Bottom bar with © line
- Less template-like

### Other
- Removed "Slow evenings" caption from Private section
- Cut card images also scale on hover (combined with tilt)

## Deploy
Static site — upload folder contents to GitHub repo root, Vercel autodeploys.
