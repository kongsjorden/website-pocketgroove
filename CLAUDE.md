# PocketGroove Website

Marketing website for PocketGroove, an iOS rhythm training app.

## Tech Stack
- **Framework**: Astro 5
- **Styling**: Tailwind CSS 4
- **Fonts**: Outfit (display) + Plus Jakarta Sans (body) via Google Fonts

## Commands
- `npm run dev` — Start dev server (localhost:4321)
- `npm run build` — Build to `dist/`
- `npm run preview` — Preview production build

## Project Structure
```
src/
├── styles/global.css       # Tailwind + Rust & Groove theme tokens
├── layouts/Layout.astro    # HTML shell with fonts, meta, animations
├── components/
│   ├── Header.astro        # Fixed nav with mobile menu
│   ├── Footer.astro        # Footer with links
│   ├── Hero.astro          # Hero with phone mockup carousel
│   ├── FeatureCard.astro   # Feature card with SVG icons
│   ├── PhoneMockup.astro   # iPhone device frame
│   └── FaqAccordion.astro  # Expandable FAQ item
└── pages/
    ├── index.astro         # Home page
    ├── features.astro      # Features detail
    ├── faq.astro           # FAQ
    ├── support.astro       # Support channels
    └── privacy.astro       # Privacy policy
```

## Color Palette (Rust & Groove)
| Token | Hex | Usage |
|-------|-----|-------|
| background | `#1A1714` | Page background |
| background-light | `#2A2520` | Alternate sections |
| surface | `#33302B` | Cards, nav |
| primary | `#C4652A` | Rust — buttons, accents |
| primary-hover | `#E07830` | Hover states |
| secondary | `#D4A030` | Amber — stars, highlights |
| text | `#E8DCC8` | Cream — primary text |
| text-muted | `#B8A890` | Secondary text |
| border | `#4A4238` | Borders |

## Screenshots
6 app screenshots in `public/screenshots/` (01-levels through 06-pocket-profile).

## Deployment
Static site. Domain: pocketgroove.kongsjorden-studio.no
GitHub: https://github.com/kongsjorden/website-pocketgroove
