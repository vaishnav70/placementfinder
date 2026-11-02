# Vishi Talent Hub — Static Preview

This repository contains a **static preview only** of the new Vishi Talent Hub site.

- `index.html` is a design preview of the Customer/Viewer login page and the dashboard (light rounded-card layout, sidebar, timeline, progress cards, and stage cards).
- **Login, Google Sign-In, Google Authenticator, jobs, and applications do not work in this GitHub copy.** There is no backend or database here, and the preview shows honest empty states (0 jobs, 0 applications) — no fake jobs or demo data presented as real.
- The live, working version — with email + password login, Google Authenticator two-factor sign-in, Google Sign-In (once the owner saves a real Google Cloud OAuth Client ID), a hidden owner entry, and a real jobs/applications dashboard — is hosted separately in Muse, not from this repository.
- The previous static recruitment site remains in this repository's git history (commit 4cff9342).

## What the live site includes

- Customer/Viewer login and account creation, with sessions that persist and sign-out
- Owner-only admin entry (not linked on the public page), with the single-admin first-setup rule
- Google Authenticator (TOTP) setup by QR code, 6-digit codes, and 10 one-time recovery codes
- Owner dashboard: add, edit, close and delete jobs; move candidates Applied → Shortlisted → Interview → Offer → Hired
- Customer dashboard: browse jobs, apply once per job, withdraw, and track application stage
