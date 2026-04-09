# Noval Website — Claude Code Instructions

## Project
Static HTML/CSS website for Noval Consulting. No framework, no build step, no bundler.
Live at: https://noval.ie (custom domain, registered via Blacknight, DNS points to GitHub Pages)
GitHub Pages fallback: https://eoinlane.github.io/noval-website
Repo: https://github.com/eoinlane/noval-website

## Stack rules
- Pure HTML and CSS only — do not introduce JavaScript frameworks, npm, or a build step
- All CSS is inline per-page (in `<style>` tags) — no separate stylesheet
- No external CSS frameworks (no Tailwind, Bootstrap, etc.)

## Pages
- `index.html` — homepage
- `about.html` — Eoin Lane bio
- `contact.html` — Formspree contact form (ID: xlgpavqa)
- `case-studies.html` — Diotima EdTech case study

## Brand assets
Brand guidelines and assets live in `brand/`:
- `brand-spec.html` — full brand guidelines (open in browser to view)
- `icon-preview.html` — side-by-side SVG vs PNG logo comparison
- `logo/` — vector logo assets:
  - `noval-icon.svg` — vector logo (traced in Inkscape)
  - `noval-wordmark.svg` / `noval-wordmark-white.svg` — wordmarks
  - `colour-palette.svg` — visual swatch reference
- `linkedin/` — LinkedIn banner assets:
  - `linkedin-banner.html` / `linkedin-banner-company.png` — company page banner (1584x396)
  - `linkedin-banner-personal.html` / `linkedin-banner-personal.png` — personal profile banner (1584x396)

The original logo PNG is `noval-icon.png` (1024x1024). The favicon (`favicon.png`) is a 32x32 resize of this.

## CSS specificity note
`.nav-links a` has higher specificity than `.btn-primary` alone (class+element vs class). All pages include `.nav-links a.btn-primary` override to ensure the nav CTA button renders correctly (solid green, white text).

## Design system
All pages share the same nav, footer, and CTA section pattern. Keep these consistent.

**Colours:**
- `--deep-forest: #1B4332`
- `--emerald: #2D6A4F`
- `--sage: #52B788`
- `--mint: #D8F3DC`
- `--warm-gold: #B68D40`
- `--gold-light: #D4A853`

**Fonts:** DM Serif Display (headings), Inter (body), JetBrains Mono (labels/mono)

**Buttons:**
- `btn-primary` (dark green) — primary action on light backgrounds
- `btn-white` — primary action on dark backgrounds
- `btn-gold` — all secondary actions

**CTA wording:** Always "Book a Consultation" (not "Book a Free Consultation")

**Meta tags:** All pages have `<meta name="description">` and Open Graph tags (`og:title`, `og:description`, `og:image`, `og:url`) for social sharing.

**Footer:** All pages use the same footer structure with Company links: About, Case Studies, Insights, Contact.

## About Eoin Lane
- Founder & CEO, Noval Consulting (Oct 2024–present)
- Adjunct Professor, Trinity Business School (Sep 2025–present) — AI strategy, responsible AI, digital transformation
- Research Fellow, ADAPT Centre (Jun 2025–present) — co-leading DCC/ADAPT Generative AI Lab
- Former Global Head of Data Science & AI, BNY Mellon (Feb 2020–Nov 2024)
- Former Director, Emerging Analytics, Dun and Bradstreet (Jan 2016–Feb 2020)
- IBM Master Inventor; 12 years at IBM (2003–2015)
- Ph.D. in Chemistry, University College Cork
- 70+ patents; 20+ publications
- Gartner Eye on Innovation 2020 — WON (not shortlisted)
- Gartner Eye on Innovation 2022 — shortlisted
- 30+ enterprise AI solutions; $100M+ revenue delivered at BNY Mellon
- Contact: info@novalconsultancy.com | +353 83 027 0372
- LinkedIn: https://www.linkedin.com/in/laneeoin/

## Marketing & content
Q2 2026 bi-weekly content plan is active. Key upcoming work:
- Insights section on website needs to become a real blog (articles, not just cards)
- Lead capture: Mailchimp newsletter signup form to be embedded on homepage (in progress)
- Diotima white paper (https://github.com/eoinlane/diotima-whitepaper) to be published and linked from site
- Case study page needs improvement before Diotima white paper is promoted

## Business tools
- CRM: Pipedrive (novalconsultancy.pipedrive.com) — configured with 6-stage pipeline ✅
- Email marketing: Mailchimp (eoin@novalconsultancy.com) — account created, setup in progress (audience name, address, signup form still to do)
- Contact form: Formspree (ID: xlgpavqa) on contact.html
- Calendar: Q2 content schedule added to Google Calendar (syncs to Apple Calendar) ✅
- Task management: Apple Reminders

## Working approach
- Confirm before making changes across multiple files
- Commit after each logical chunk of work
- Keep responses short and direct
