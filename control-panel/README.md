# Portfolio Control Panel (Private)

Ahmed's portfolio is managed from a **separate private control panel app** built
in Muse (artifact slug: `portfolio-control-panel`, fullstack — it persists its
own data). The panel's application code and database live in Muse only: they
are deliberately NOT in this repository, and the panel can never be published
at a public link.

## Why it is separate

The public website (`../index.html`, also served from the public Muse link) is
a static page. It contains **no settings UI, no admin routes and no trace of
the panel** — visitors only ever see the portfolio itself. The panel runs
privately for Ahmed only.

## What lives in this folder

- `portfolio-content.json` — the panel's current content export (the single
  source of truth for the site's content and settings): 15 campaigns across
  the 5 boards, 8 certificates, 3 testimonials, display settings, identity
  tokens, hero data (including the Meta/Google badge editors), the 12
  Software & Icons entries, and Appearance & Features settings (default
  theme, day-mode toggle, intro replay on language switch). Refresh this file
  from the panel's Publish module whenever content changes, so the repo always
  mirrors the live panel state.
- This README — how the panel works.

## How editing flows

1. Ahmed edits inside the panel, organised **per site section** — Hero, About,
   Certificates, Experience, Campaign Results, Services, Testimonials,
   Contact, Software & Icons, Appearance — each section screen shows all of
   its own editing options (texts EN/AR, images, visibility, order).
2. Every image slot uses one image field: upload from the device (auto
   compressed and stored with the site data, so it survives export) or paste a
   URL, with live preview and remove. This covers campaign images, certificate
   images, portrait/avatar, hero badges and software icons.
3. Display settings (element scale/position/rotation/visibility — globally or
   as per-device overrides for phone / iPad / laptop / desktop) and identity
   tokens (colors, fonts, spacing) are edited in their own sections.
   Everything autosaves in the panel's storage, with a change log and undo.
4. In the panel's Publish module he exports `portfolio-content.json` — the
   file in this folder.
5. That export is applied to the static portfolio (`../index.html`), which is
   then re-published at the **same** public link (only after his approval).

## Modules

Dashboard (incl. empty-image-slot tracking) · Per-section content editors ·
Campaigns (5 boards CRUD) · Certificates & Testimonials · Software & Icons ·
Hero badge editor · Display Designer (per-device overrides) · Identity ·
Appearance & Features · Live Preview (phone/tablet/laptop frames) · Publish &
Export · Change Log with undo.
