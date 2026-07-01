# TEDx 7.0 — KAIROS · TEDxMDIGurgaon

Landing page for **TEDxMDIGurgaon 7.0**, built for the TEDx induction task.

A single, self-contained `index.html` — no build step, no dependencies. Open it directly or host it as a static file.

## Sections
- **Hero** — featured 5–10s clip from TEDx 6.0 (*"Beyond Brick and Mortar"*, Dr. Dheeraj Dogra), looping via the YouTube IFrame API, with the speaker credit and a memorable quote.
- **Act 01 · Theme reveal** — *KAIROS*, the decisive moment. Scroll-driven letter fill with a travelling TED-red dot.
- **Act 02 · Speakers** — the 7.0 line-up, with hover-to-reveal talk titles.
- **Act 03 · Tickets** — live countdown, ticket tiers, and a booking form with validation.

## Design
Official TEDx palette (red `#EB0028` / black / white). Type: Anton · Archivo · Space Mono.
Built with the [frontend-design](https://github.com/anthropics/skills/tree/main/skills/frontend-design) and [ui-ux-pro-max](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) design skills.

## Run locally
```bash
python3 -m http.server 4173
# then open http://localhost:4173
```

## Customize
At the top of the inline `<script>` in `index.html`:
- `CLIP_START` / `CLIP_END` — the featured clip window (seconds).
- `EVENT_DATE` — the countdown target.
