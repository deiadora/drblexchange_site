[drbl-exchange-README.md](https://github.com/user-attachments/files/29910595/drbl-exchange-README.md)
# drblexchange.com

> DRBL Exchange — drop in · recognise · build · launch. Where people working the arcs find each other.

## What this is

The practice circle on Discord: needs meet offers, 48-hour moves, 2-week sprints, ship over debate. Built for recognition (networking's missing third move), eight tenets of mutuality, invite + vouch entry.

## Stack

Single-file static site — one `index.html`, no build step, no frameworks, no dependencies beyond Google Fonts.

Shared deiadora ecosystem design system:
- CSS custom properties; Cormorant Garamond / Exo 2 / DM Sans
- Three themes (default, dark, light) with system-preference tracking, persisted via `localStorage`
- A/A text-size toggle (115% scaling), persisted via `localStorage`
- WCAG AA contrast verified for all text/background pairs in all three themes
- Skip link, semantic sections, `prefers-reduced-motion` support

## Deploy

Cloudflare Pages. No build command; root directory as output. Replace placeholder links (mail subjects, audio files, or invite URLs) noted in HTML comments where present.

## Ecosystem

Part of the deiadora ecosystem — ten sites, one design system, one author. Front door: [deiadora.com](https://deiadora.com).

© Deiadora Blanche. All rights reserved.
