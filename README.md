# Mostafizur Rahaman — Academic Website

Personal academic website for Dr. Mostafizur Rahaman, Research Scientist at IBM Quantum Division.

## Deployment (GitHub Pages)

1. **Create a new GitHub repository** named `yourusername.github.io` (or any name for project pages)
2. **Upload all files** from this folder to the repository root
3. Go to **Settings → Pages** → Source: Deploy from branch → `main` → `/root`
4. Your site will be live at `https://yourusername.github.io`

## Files

| File | Purpose |
|------|---------|
| `index.html` | Main single-page website (all content) |
| `_config.yml` | Jekyll configuration |
| `README.md` | This file |

## Features

- 🎨 Fujitsu-inspired red-pink gradient design
- 📱 Fully responsive (mobile, tablet, desktop)
- ✨ Scroll-reveal animations
- 🎠 Infinite awards marquee strip
- 🍔 Hamburger menu on mobile
- ⚡ Zero dependencies (pure HTML/CSS/JS)
- 🔗 Direct links to Google Scholar & LinkedIn

## Customization

All styles use CSS variables at the top of `index.html`:
```css
:root {
  --red:   #D90032;
  --pink:  #FF4475;
  --rose:  #FF7DA0;
  ...
}
```
Change these to update the color palette site-wide.

## Sections

1. **Hero** — Name, title, affiliations, stats card
2. **About** — Bio, research interests, career timeline
3. **Research** — Selected publications (9 papers)
4. **Patents** — Full IP portfolio (7 patents)
5. **Talks** — Invited talks & keynotes
6. **Teaching** — Academic teaching roles
7. **Awards** — Scrolling marquee + grid
8. **News** — Recent updates
9. **Press** — Media coverage

---
Built with Jekyll + pure HTML/CSS/JS. No external dependencies except Google Fonts.
