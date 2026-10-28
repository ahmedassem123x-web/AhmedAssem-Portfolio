# Portfolio Control Panel (Private)

Ahmed's portfolio is managed from a **separate private control panel app** built in
Muse (artifact slug: `portfolio-control-panel`, fullstack — it persists its own data).

## Why it is separate

The public website (`../index.html`, also served from the public Muse link) is a
static page. It contains **no settings UI, no admin routes and no trace of the
panel** — visitors only ever see the portfolio itself. The panel runs privately
for Ahmed only and can never be published at a public link.

## How editing flows

1. Ahmed edits content (texts EN/AR, campaigns, certificates, testimonials),
   display settings (element scale/position/rotation/visibility — globally or as
   per-device overrides for phone / iPad / laptop / desktop) and identity tokens
   (colors, fonts) inside the panel. Everything autosaves in the panel's storage,
   with a change log.
2. In the panel's Publish module he exports `portfolio-content.json` — the single
   source that describes the site's content and settings.
3. That export is applied to the static portfolio, which is then re-published at
   the **same** public link.

## Modules

Dashboard · Content · Campaigns (5 boards CRUD) · Certificates & Testimonials ·
Display Designer (per-device overrides) · Identity · Live Preview (phone/tablet/
laptop frames) · Publish & Export · Change Log.
