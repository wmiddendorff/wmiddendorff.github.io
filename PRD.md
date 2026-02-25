# PRD: wmiddendorff.github.io Main Landing Page

## Problem
The root GitHub Pages domain (wmiddendorff.github.io) returns 404. All 5 deployed tools live under this domain. We need a professional landing page that ties everything together.

## Solution
Build a single-page landing page at wmiddendorff/wmiddendorff.github.io repo.

## Requirements

### Hero Section
- "Bridgette Enterprises" or "Wes Middendorff" branding
- Tagline: "AI tools, services, and insights for builders"
- CTA: Explore Tools / Book a Service

### Free Tools Section
- Card for each tool with description + link:
  1. AI Agent Configurator → /agent-configurator/
  2. AI Prompt Library → /prompt-library/
  3. AI ROI Calculator → /ai-roi-calculator/

### Services Section
- Cards linking to /bridgette-services/:
  1. Competitive Intelligence Report ($299)
  2. AI Readiness Assessment ($499)
  3. Agent Configuration Service ($199)

### Products Section
- 3 Gumroad products with prices and links

### Newsletter Section
- "AI in the Weeds" Substack signup
- Working email capture via Formspree (action="https://formspree.io/f/{id}" — use placeholder FORMSPREE_ID that I'll replace)

### Footer
- Links to all pages, Substack, GitHub, Twitter @BridgetteC23222

### Analytics
- Include GoatCounter script: `<script data-goatcounter="https://bridgette-enterprises.goatcounter.com/count" async src="//gc.zgo.at/count.js"></script>`
- This same script should be added to ALL other tools too

### Design
- Dark theme, consistent with existing tools (glassmorphism, dark bg, purple/blue accents)
- Fully responsive, mobile-first
- Single index.html file, no build step
- SEO: proper title, meta description, OG tags, canonical URL
- Favicon

## Technical
- Repo: wmiddendorff/wmiddendorff.github.io (this is the special GitHub Pages repo)
- Single index.html file
- Deploy via push to main branch (GitHub Pages auto-deploys)

## Success Criteria
- Professional, cohesive landing page
- All tools, services, and products linked
- Working email capture form
- Analytics tracking
- Mobile responsive
