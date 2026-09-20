# Three Rivers Comfort Co. — HVAC Website Demo

A three-page, mobile-first FireWorks storefront website for a fictional Pittsburgh HVAC company.

## Pages

- `/` — conversion-focused homepage with an emergency request form beside the main CTA
- `/services` — heating, cooling, heat pump, maintenance, replacement, and indoor-air-quality services
- `/request-service` — detailed service request form plus emergency safety guidance

## Local development

```bash
npm run check
npm run build
npx serve dist
```

## Important demo safeguards

- The company, phone number, email address, and service claims are fictional.
- Forms validate in the browser but do not transmit or store information.
- Every page is `noindex, nofollow`, and `robots.txt` blocks crawling.
- Replace fictional details, connect an approved form provider, confirm the canonical domain, and remove noindex directives only when a real customer approves the site.

See `FIREWORKS-PROJECT.md` for the complete handoff.
