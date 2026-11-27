# Bloom Tuition Centre

Website for Bloom Tuition Centre, BDS Nagar, Kothanur, Bengaluru.

**Live site:** https://bloom-tuition-centre.vercel.app

## What's here

The whole site is one file, `index.html`, with its styles and scripts inline. There's no build step.

## Updating the site

1. Edit `index.html`.
2. Commit and push to `main`.

Vercel deploys every push to `main` automatically, and the live site updates within a minute.

## Quick edits

- **WhatsApp number:** change `WA_NUMBER` in the script near the bottom of `index.html` (country code first, no `+` or spaces).
- **Timings:** update both the timetable list (`#timetable`) and `HOURS` in the script. `HOURS` sets each day's start and end in minutes after midnight, so 5:30 pm is `1050`, and `null` means closed. It drives the "Open now" status.
- **Classes and subjects:** edit the cards in the `#classes` section.
