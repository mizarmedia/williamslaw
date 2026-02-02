# Williams Law Website

## Project Overview
Professional homepage for Matthew C. Williams, Attorney at Law (mattwilliams.law).
This is a pitch site to win the client with a modern redesign.

## Tech Stack
- **Astro 5.x** - Static site generator
- **Tailwind CSS v4** - Utility-first styling
- **TypeScript** - Type safety
- **Cloudflare Pages** - Deployment target

## Architecture
Single-page site with component-based structure. No complex architecture needed.

## Commands
```bash
npm run dev      # Start dev server at localhost:4321
npm run build    # Build to dist/
npm run preview  # Preview build locally
```

## File Structure
```
src/
├── layouts/Layout.astro     # Base layout with SEO, schema.org markup
├── components/
│   ├── Header.astro         # Sticky nav with mobile menu
│   ├── Hero.astro           # Main hero with Idaho mountain bg
│   ├── Problem.astro        # Problem/solution positioning
│   ├── PracticeAreas.astro  # 3-card practice area grid
│   ├── WhyChoose.astro      # 6 differentiators
│   ├── Results.astro        # Case results
│   ├── About.astro          # Attorney bio
│   ├── Testimonials.astro   # Client reviews (placeholder)
│   ├── Contact.astro        # Contact form + map
│   └── Footer.astro         # Site footer
└── pages/index.astro        # Homepage
```

## Design System
- **Navy Primary**: #1a365d (trust, authority)
- **Gold Primary**: #c9a227 (premium, approachable)
- **Fonts**: Playfair Display (headings), Inter (body), Cormorant Garamond (quotes)
- **Idaho imagery**: Mountain landscapes with navy overlay
- **Topographic patterns**: Subtle texture representing Idaho terrain

## SEO
- Schema.org markup: Attorney, LegalService, LocalBusiness
- Target keywords: "criminal defense attorney Eagle Idaho", "family law lawyer Meridian"
- Meta optimization built into Layout.astro

## Key Selling Points Built In
1. Former prosecutor (2004-2013) - knows prosecution strategy
2. 24+ years experience (licensed 2000)
3. Personal attention (solo practitioner)
4. Local community roots (state championship coach)
5. Proven track record (Southwest Airlines settlement, civil rights wins)

## Deployment
```bash
npx wrangler pages deploy dist
```

## TODO for Client Pitch
- [ ] Get real testimonials to replace placeholders
- [ ] Get professional office photos
- [ ] Verify Google Maps embed coordinates
- [ ] Set up contact form backend (Formspree, Netlify Forms, etc.)
- [ ] Configure Cloudflare Pages custom domain
