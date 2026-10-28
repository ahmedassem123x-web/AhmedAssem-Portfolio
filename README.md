# Ahmed Samir Abdulaziz Assem — Personal Portfolio

One-page bilingual (English / Arabic, full RTL) portfolio for Ahmed Samir Abdulaziz
Assem — Digital Marketing Specialist & Web Developer.

Open `index.html` in any browser: no build step, no dependencies. The page is
fully self-contained (all assets inlined).

## Repository structure

This repository is the single home of the whole portfolio project:

```
AhmedAssem-Portfolio/
├── index.html                  # the live site (root → GitHub Pages-ready)
├── README.md                   # this file
├── data/
│   └── content.json            # structured CV content (skills, certificates,
│                               #   campaigns) — reference copy
├── docs/
│   ├── master-prompt.md        # master build specification for the site
│   └── real-data-intake.md     # intake sheet for real campaign results,
│                               #   certificate scans and profile links
└── control-panel/
    ├── README.md               # how the private control panel works
    └── portfolio-content.json  # the panel's current content export — the
                                #   single source of truth (15 campaigns,
                                #   8 certificates, 3 testimonials, display
                                #   settings, identity, hero badges, software
                                #   icons, appearance settings)
```

- `index.html` — the complete portfolio website (latest version, October 2026):
  animated hero with cursor-click intro, certificates with folder-slide viewer,
  experience, campaign results (Awareness / Engagement / Traffic / Leads /
  Sales carousels with swipe), services, testimonials, contact, day (pearl
  white) and night themes, and Meta/Google certification badges.
- `control-panel/` — documentation and the content export of the separate
  private control panel. The panel's application code and database are NOT in
  this repository by design: the panel is a private Muse app and is never
  published with the website.

## How updates flow

1. Edit in the private control panel (per-section editors, image uploads from
   device or URL).
2. Export `portfolio-content.json` from the panel's Publish module and refresh
   the copy in `control-panel/` here.
3. Apply the export to `index.html` and re-publish at the same public link
   (only after Ahmed's approval).

## History note

An earlier copy of the site (October 23 version, inside a `site/` folder)
remains in the previous repository `ahmed-sameer-assem-portfolio` as an
archive, together with its original TypeScript project. This repository is the
canonical home of the project from October 28, 2026 onward.

## Live site

https://muse.ai/s/personal-portfolio-lxa6axkxbxpxxrjxr/0-utzM7EvqLMC17TEpvbgZJj05A7WRQmZUKl-wlwOdI

## Notes

- Contact links: WhatsApp and email are real (from the CV); social profile
  links are placeholders until real ones are supplied.
- Campaign numbers and testimonials are the site's current content; real
  replacements are swapped in through the control panel when available.
