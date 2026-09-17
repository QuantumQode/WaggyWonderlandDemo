# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Users

Dog owners in North West London (and parts of North/West London) who need reliable, personal dog walking, sitting, or boarding. They care about their dog being treated as an individual, not run through a group service, and want to trust the person handling their pet (safety, background checks, familiarity).

## Product Purpose

A marketing/showcase website for Waggy Wonderland, a London dog walking and sitting service. It presents the business, services, pricing, and team, and drives visitors to get in touch (call, WhatsApp, or free meet & greet) to book care for their dog.

This build is a **visual demo/portfolio redesign**, not a production deployment: interactive elements (booking flow, contact form, etc.) should look and behave like the real thing but do not need a working backend. No live submissions, payments, or real calendar logic are required.

## Positioning

Exclusive one-on-one dog care instead of group walks — every visit is personalized to the individual dog. Reinforced by a DBS-checked team, free meet-and-greet before booking, and (per current site copy) EV pickup for walks. Positioned as trustworthy, personal, and premium rather than a budget/volume dog-walking operation.

## Operating Context

Full multi-page site structure (matching the current IA, refreshed): Home, Our Services, Pricing, Meet the Team, About, Contact. Blog is optional/lower priority. Primary conversion paths are: free meet & greet booking, and direct contact via phone/WhatsApp/email.

## Capabilities and Constraints

- Visual demo only: no real backend. Forms, booking flows, and "dynamic features" should be fully realized in the UI/UX and feel functional (e.g. multi-step booking UI, animated states, success confirmations) without actually persisting or sending data anywhere.
- Real business contact details should be used (not placeholders), since the demo should look authentic and could go live later with minimal changes:
  - Phone: +44 7949 051202
  - Email: wonderlandwaggy@gmail.com
  - Service area: NW11 0AA — North West London, and parts of North & West London
  - Hours: Mon–Fri 8am–8pm, Sat–Sun 9am–6pm
  - Social: Instagram & TikTok @waggywonderlandd, WhatsApp

## Brand Commitments

- Name: **Waggy Wonderland**
- Logo: use the original brand mark — a minimalist continuous-line illustration of a sitting dog, at `images/img_14.png` (1000×1000, transparent PNG).
- Existing real content to reuse (not invent): services, pricing, team bios, testimonial, and copy already extracted into `site-scrape/SITE_CONTENT.md` and `images/`.

## Evidence on Hand

Scraped from the live site (https://www.waggywonderland.com/) and saved locally:
- `site-scrape/SITE_CONTENT.md` — full text content: services, weekly pricing plans, about/mission copy, team bios (8 people incl. founder Rojan), one testimonial ("Milo H."), contact form fields, blog post titles, old-site brand colors/fonts, and known issues in the old site.
- `images/` — 26 real images pulled from the old site: logo mark (`img_14.png`), dog/team photos, and per-hour/per-night pricing card graphics (`img_13.png`, `img_15.png`, `img_18.png` — Dog Walking £22/hr small, £28/hr medium-large; Dog Sitting £18/hr for 1–3 hrs; Dog Boarding £65/night small, £70/night medium-large, for 1–7 nights). These per-unit rates supplement (don't necessarily replace) the weekly package pricing already in SITE_CONTENT.md — reconcile which pricing model to feature during design.
- No case studies, press, or additional testimonials exist beyond the one quoted above — do not invent more.

## Product Principles

1. Preserve real business facts (services, pricing figures, team identities, contact info, service area) — this is a redesign of presentation, not an invented business.
2. Personal and trustworthy over corporate or generic — the one-on-one/individual-dog framing is the core differentiator and should shape tone, not just be a line of copy.
3. It's a demo: prioritize a polished, dynamic, convincing front-end experience over backend completeness.
4. Keep the original logo mark as the anchor of visual identity even as the rest of the visual world is rebuilt.

## Accessibility & Inclusion

No product-specific requirement established beyond standard web accessibility practice.
