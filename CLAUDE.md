# Short Form 30 — working rules for Claude

## Always ask first
Before starting any new request, ask Kevin a short series of clarifying questions
and wait for answers. Do not fill gaps with assumptions about the business,
offer, copy, pricing, or design. If something is still unknown after asking,
leave a clearly marked placeholder rather than inventing content.

## Brand
Brand guidelines (logo, colors, fonts) live in `BRAND.md`. Read it before
making anything visual and follow it exactly.

## Site build process
1. **Reference structure** — study example sites Kevin provides (links or
   screenshots) and mirror their structure.
2. **Brand** — apply `BRAND.md`.
3. **Design skills** — use the design skills Kevin has installed.
4. **Three versions** — plan first, then produce 3 HTML versions of the page.
   Kevin picks one before anything is built out.
5. **Stack** — plain HTML, CSS, and a little JavaScript. No frameworks.
6. **Hosting** — code lives in this GitHub repo; Vercel deploys on push.
7. **Applications** — Tally form embedded on `/apply`. Every Apply button on
   the site points to `/apply`.
8. **Booking** — after a Tally submission, redirect to Kevin's Cal.com link.
   Flow: landing page → Tally application → booked call.
9. **Launch test** — on desktop and phone: submit a real test application,
   confirm it arrives in Tally, confirm the Cal.com redirect, check every
   Apply button, and check the link preview when pasted.
