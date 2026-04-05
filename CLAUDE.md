# Noval Website — Claude Code Instructions

## Project
Static HTML/CSS website for Noval Consultancy. No framework, no build step, no bundler.
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

## About Eoin Lane
- Founder, Noval Consultancy (2025–present)
- Former Global Head of Data Science and AI, BNY Mellon (2020–2025)
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
- Lead capture (newsletter or EU AI Act briefing form) needed on homepage before content goes live
- Diotima white paper (https://github.com/eoinlane/diotima-whitepaper) to be published and linked from site
- Case study page needs improvement before Diotima white paper is promoted

## Working approach
- Confirm before making changes across multiple files
- Commit after each logical chunk of work
- Keep responses short and direct
