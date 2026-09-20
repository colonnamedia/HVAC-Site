# FIREWORKS PROJECT HANDOFF

## Project

- Storefront name: Three Rivers Comfort Co. — HVAC Website
- Industry: Residential HVAC / heating and cooling
- Market scaffold: Pittsburgh and South Hills, Pennsylvania
- Repository: https://github.com/colonnamedia/HVAC-Site
- Production Vercel URL: https://hvac-site-delta.vercel.app/
- Package: Tier 1 storefront website — $699.99 setup + $39.99/month hosting
- Status: Fictional demo; not approved for search indexing or live lead delivery

## Build scope

- Three static pages: Home, Services, Request Service
- Distinct navy, cool-blue, and warm-orange visual system
- Responsive navigation and mobile-first layouts
- Homepage emergency request form positioned beside the primary CTA
- Full request form with service, urgency, timing, equipment, and problem details
- Forms validate but intentionally do not transmit or store information
- Emergency safety language for gas odors and carbon-monoxide alarms
- Pittsburgh/South Hills local SEO content scaffold
- Unique metadata, canonical URLs, Open Graph, Twitter cards, semantic headings, sitemap, and schema markup
- HVACBusiness, Service, and ContactPage JSON-LD
- Demo-safe `noindex, nofollow` plus crawl blocking in `robots.txt`
- Stock-photo source record in `STOCK-PHOTOS.md`

## Customer customization checklist

1. Replace fictional company name, phone, email, address, business hours, and service area.
2. Confirm whether the company truly offers emergency or after-hours service and rewrite all availability language accordingly.
3. Replace stock photography with customer photos when available.
4. Confirm actual services, brands, financing, warranties, maintenance-plan terms, licenses, certifications, and guarantees. Do not add unverified claims.
5. Connect standard and emergency forms to an approved destination such as email, CRM, scheduling, or dispatch.
6. Add spam protection, privacy policy, consent language, and retention rules appropriate to the selected provider.
7. Replace canonical, Open Graph, and sitemap URLs with the final customer domain.
8. Add verified Google Business Profile, map, social accounts, and consistent NAP information.
9. Remove page-level `noindex, nofollow` and change `robots.txt` only after all details are real and the customer approves indexing.
10. Test mobile navigation, calls, form delivery, confirmation states, analytics, Search Console, and production redirects.

## Integrations

- Current site: no database, authentication, payment, CRM, or form provider
- Recommended Tier 1 launch: Vercel hosting plus approved email/form delivery
- Optional upgrades: CRM or dispatch routing, call tracking, online scheduling, maintenance-plan payments, Stripe, Supabase/Neon lead storage, analytics dashboard
- Never add credentials to the repository. Use hosting environment variables.

## Agent prompt for a new project thread

Continue the FireWorks project for the Three Rivers Comfort Co. HVAC website in `colonnamedia/HVAC-Site`. Read `FIREWORKS-PROJECT.md`, `README.md`, and `STOCK-PHOTOS.md` first. Preserve the three-page scope, Pittsburgh local-SEO scaffold, emergency safety language, mobile experience, demo-only non-transmitting forms, and noindex safeguards until verified customer information and an approved form provider are supplied. Run `npm run check` and `npm run build` before every deployment.
