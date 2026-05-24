# Website Audit Report: Leask & Company

**Audit Date**: 2026-05-15
**Site**: `/workspace/sites/leask-plumbing/`
**Builder Skill**: `/workspace/.opencode/skills/website-builder/SKILL.md`

## Summary
- Total checks: 47 | PASS: 47 | FAIL: 0 | Overall: ✅

## Findings

| # | Requirement | Source Line | Status | Evidence |
|---|-------------|-------------|--------|----------|
| 1 | Hero section (bold headline, tagline, CTA) | 22 | ✅ PASS | `id="hero"`, headline, tagline, "Get a Quote" CTA |
| 2 | What We Do section | 23 | ✅ PASS | `id="what-we-do"`, description + visual element |
| 3 | Services — alternating two-column layout | 24, 31-43 | ✅ PASS | `service-row` and `service-row reverse` classes |
| 4 | Pricing omitted (no data) | 25 | ✅ PASS | No pricing section present |
| 5 | Why Choose Us section | 26 | ✅ PASS | `id="why-choose-us"`, 6 benefit cards |
| 6 | Reviews — 3 customers, 5 stars, first names | 27 | ✅ PASS | 3 reviews with Chantelle, Coleman, Meighan |
| 7 | Contact/Hours with map embed | 28 | ✅ PASS | Address, phone, hours, Google Maps iframe |
| 8 | Footer with copyright + attribution | 29 | ✅ PASS | Dynamic year, "Viso Solutions" attribution |
| 9 | No "Who It's For" or "How It Works" | 18 | ✅ PASS | Not present (trades business) |
| 10 | Footer attribution: "Made with love by Viso Solutions" | 60-72 | ✅ PASS | Present with link to design.withviso.com |
| 11 | No photos with visible human faces | 76 | ✅ PASS | All images show tools, pipes, equipment |
| 12 | Images from specified Pexels plumbing collection | 80-88 | ✅ PASS | All 5 images from collection t8pdbjt |
| 13 | Lucide icons via unpkg CDN | 92-95 | ✅ PASS | Using `<img>` tags with lucide-static URLs |
| 14 | Filled star SVGs for reviews | 98-105 | ✅ PASS | SVG polygons with yellow fill |
| 15 | Sticky header | 109-112 | ✅ PASS | `position: sticky; top: 0; z-index: 1000` |
| 16 | scroll-margin-top on sections | 112 | ✅ PASS | `calc(var(--header-h) + var(--banner-h))` = 114px |
| 17 | Mobile navigation toggle | 113 | ✅ PASS | `menu-toggle` button + `mobile-nav` dropdown |
| 18 | Fade-in scroll animations | 114 | ✅ PASS | IntersectionObserver on `.fade-in` elements |
| 19 | Hero full-width background + dark overlay | 116 | ✅ PASS | Background image with `brightness(0.35)` |
| 20 | Google Fonts (Inter) | 117 | ✅ PASS | Inter loaded via Google Fonts |
| 21 | Pure HTML/CSS/JS — no external frameworks | 118 | ✅ PASS | No Bootstrap, Tailwind, jQuery, React, Vue |
| 22 | Text-based logo acronym "LC" | 132-134 | ✅ PASS | `.logo-mark` with "LC", styled distinctly |
| 23 | No favicon (no logo provided) | 135 | ✅ PASS | No favicon links present |
| 24 | Header logo/nav fits all viewports | 137 | ✅ PASS | Responsive with media queries, no overflow |
| 25 | Google Maps embed (fallback method) | 152-160 | ✅ PASS | Address-based embed with correct attributes |
| 26 | Claim banner below header | 164 | ✅ PASS | `<header>` then `<div class="claim-banner">` |
| 27 | Claim text correct | 165 | ✅ PASS | "Hi Leask & Company! Do you like the website?" |
| 28 | Claim banner links to design.withviso.com | 166 | ✅ PASS | `<a>` with correct href |
| 29 | "Contact us to make it yours" in `<u>` tags | 167 | ✅ PASS | Proper `<u>` tag usage |
| 30 | Claim banner styled with brand primary color | 168 | ✅ PASS | Background: var(--primary) = #1a4b8c |
| 31 | Header/banner z-index | 169-170 | ✅ PASS | 1000 and 999 respectively |
| 32 | GTM script in head | 179-181 | ✅ PASS | `GTM-TBD8TFCF` script in `<head>` |
| 33 | GTM noscript in body | 184-186 | ✅ PASS | Noscript iframe after `<body>` |
| 34 | SEO noindex meta | 193-194 | ✅ PASS | `name="robots" content="noindex"` |
| 35 | Responsive — mobile breakpoints | 110 | ✅ PASS | 768px, 900px, 480px breakpoints |
| 36 | Services: 3 services, 4 bullets each | 35-39 | ✅ PASS | Plumbing(4), Heating(4), AC(4) |
| 37 | Each service has Pexels photo | 36 | ✅ PASS | Unique photo per service from collection |
| 38 | Each service has Lucide icon + heading | 37 | ✅ PASS | wrench, flame, snowflake icons |
| 39 | Services properly alternate | 33 | ✅ PASS | L/R/L alternating pattern |
| 40 | No website link in contact section | 28 | ✅ PASS | Only icon CDN URLs and Maps embed |
| 41 | Smooth scroll behavior | 111 | ✅ PASS | `scroll-behavior: smooth` |
| 42 | Same font family for attribution | 67 | ✅ PASS | Inherits Inter from body |
| 43 | Footer divider for visual separation | 68 | ✅ PASS | `<hr class="footer-divider">` |
| 44 | Mobile nav closes on link click | 113 | ✅ PASS | JS event listeners on `.mobile-link` |
| 45 | CTA button in hero | 22 | ✅ PASS | "Get a Quote" button |
| 46 | Nav CTA present | - | ✅ PASS | "Contact" nav item with `nav-cta` class |
| 47 | Claim banner has padding | 173 | ✅ PASS | `padding: 10px 20px` |

## Fixes Applied

No fixes needed — all checks passed on first audit.

## Conclusion

✅ **All 47 checks PASS**. The website meets all requirements of the website-builder skill.
