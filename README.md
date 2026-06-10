# Genshin Impact Guide Website

A complete, responsive, SEO-optimized English guide website for Genshin Impact mobile game.

**Domain:** https://genshinguide.info

## Quick Start

1. Open `test.html` in your browser to see the navigation hub
2. Click any link to browse the different sections
3. The site is fully responsive - try resizing your browser window

## Site Structure

```
genshin-guide/
├── index.html                 # Homepage with featured content
├── test.html                  # Test & navigation page
├── robots.txt                 # SEO crawler instructions
├── sitemap.xml                # XML sitemap for search engines
│
├── builds/                    # Character Builds section
│   └── index.html            # All character builds listing
│
├── abyss/                     # Spiral Abyss section
│   └── index.html            # Floor 12 guide & team recommendations
│
├── beginner/                  # Beginner Guide section
│   └── index.html            # Starting tips, primogem farming, redeem codes
│
├── news/                      # Version Updates section
│   └── index.html            # Latest patches, new characters, events
│
├── css/                       # Stylesheets
│   ├── style.css             # Global styles (responsive design)
│   ├── builds.css            # Character builds page styles
│   ├── abyss.css             # Spiral Abyss page styles
│   ├── beginner.css          # Beginner guide page styles
│   └── news.css              # News page styles
│
├── js/                        # JavaScript
│   └── main.js               # Mobile menu, smooth scroll, interactions
│
└── images/                    # Image assets (placeholder directory)
```

## Features

### SEO Optimization
- **Meta Tags**: Proper title, description, keywords for each page
- **Open Graph**: Facebook/Twitter social sharing optimization
- **Structured Data**: JSON-LD schema markup for rich snippets
- **Canonical URLs**: Prevents duplicate content issues
- **Semantic HTML5**: Proper heading hierarchy and landmark elements
- **Mobile-First**: Fully responsive design passes Google's mobile-friendly test
- **Fast Loading**: Optimized CSS, minimal JavaScript, no external dependencies
- **Sitemap**: Complete XML sitemap with priority and changefreq
- **Robots.txt**: Proper crawler instructions

### Content Sections

#### 1. Homepage (`index.html`)
- Hero section with call-to-action buttons
- Featured character builds (6 popular characters)
- Spiral Abyss quick access
- Beginner guide highlights
- Latest version updates
- Quick resource links
- Statistics banner

#### 2. Character Builds (`builds/index.html`)
- Filterable character database (by element, rarity, role)
- Organized by element: Pyro, Hydro, Electro, Dendro, Cryo, Anemo, Geo
- Each character card shows: role, weapon type, best artifact set
- Links to detailed build guides (placeholder pages)
- Additional resources: weapon tier list, artifact guide, stat priority

#### 3. Spiral Abyss (`abyss/index.html`)
- Floor 12 complete walkthrough
- Chamber-by-chamber enemy lineups
- Strategy tips for each chamber
- Recommended team compositions
- 4 meta team builds with member details
- Rewards table
- General abyss tips

#### 4. Beginner Guide (`beginner/index.html`)
- Getting started checklist
- Element reactions visual guide (8 reaction types)
- Primogem farming routes and income table
- Active redeem codes section
- FAQ section
- Resource management tips

#### 5. Version Updates (`news/index.html`)
- Featured latest version (5.8)
- News article cards with dates and tags
- Upcoming content roadmap
- Newsletter signup form
- Categorized by: version updates, farming guides, exploration, events

### Design System

**Color Palette:**
- Primary: #4A90E2 (Blue)
- Secondary: #F5A623 (Orange/Gold)
- Element colors: Pyro (red), Hydro (cyan), Anemo (green), Electro (purple), Dendro (lime), Cryo (light blue), Geo (yellow)

**Typography:**
- Body: System font stack (-apple-system, BlinkMacSystemFont, Segoe UI, Roboto)
- Headings: Georgia serif for elegance

**Responsive Breakpoints:**
- Desktop: 1200px max-width container
- Tablet: ≤768px (mobile menu activates)
- Mobile Small: ≤480px (single column layouts)

### Key SEO Keywords Targeted

Based on the provided keyword research:

1. **Character Build Keywords:**
   - "Genshin Impact [character] build"
   - "best [character] team comp"
   - "[character] artifacts"
   - "[character] weapon tier list"

2. **Spiral Abyss Keywords:**
   - "Spiral Abyss floor 12 guide"
   - "Genshin Abyss best teams current"
   - "Genshin Abyss [month] [year]"

3. **Beginner Keywords:**
   - "Genshin Impact beginner guide 2026"
   - "Primogem farming route"
   - "Genshin redeem codes"

4. **Version Update Keywords:**
   - "[version number] release date"
   - "[new character] materials farming"
   - "new region exploration guide"

## Deployment Checklist

Before deploying to https://genshinguide.info:

- [ ] Add actual character images to `/images/` directory
- [ ] Create individual character build pages (e.g., `/builds/hu-tao/`)
- [ ] Set up Google Analytics tracking code
- [ ] Add favicon files (favicon-16x16.png, favicon-32x32.png, apple-touch-icon.png)
- [ ] Create Open Graph image (og-image.jpg, 1200x630px)
- [ ] Configure SSL certificate (HTTPS)
- [ ] Set up 301 redirects if migrating from old domain
- [ ] Submit sitemap to Google Search Console
- [ ] Submit sitemap to Bing Webmaster Tools
- [ ] Test page speed with Google PageSpeed Insights
- [ ] Verify mobile-friendliness with Google's Mobile-Friendly Test
- [ ] Add newsletter backend integration
- [ ] Set up CDN for static assets (optional)

## Browser Support

- Chrome/Edge (latest 2 versions)
- Firefox (latest 2 versions)
- Safari (latest 2 versions)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance

- No external dependencies (all CSS/JS inline or local)
- Minimal JavaScript (only for mobile menu and smooth scroll)
- Optimized CSS with variables for easy theming
- Lazy loading ready (add `loading="lazy"` to images when added)

## Next Steps for Content Expansion

1. Create individual character build detail pages
2. Add interactive team builder tool
3. Add wish calculator
4. Create artifact optimizer
5. Add searchable database
6. Implement user comments/reviews
7. Add video embeds for guides
8. Create printable farming route maps

## License

This is a fan-made guide site. Genshin Impact is a registered trademark of miHoYo/HoYoverse.
This site is not affiliated with miHoYo/HoYoverse.

---

**Built:** June 2026
**Version:** 1.0
**Domain:** genshinguide.info
