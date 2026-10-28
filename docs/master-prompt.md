# MASTER PROMPT — Ahmed Samir Portfolio (Reference-Matched Rebuild)

## Goal
Rebuild Ahmed Samir's one-page portfolio to match, section by section and shape by
shape, the reference portfolio screenshots the user sent (deep-blue scrapbook /
Y2K-collage digital-marketer portfolio: "Victor / PORTFOLIO 2026" style), filled
with Ahmed's real CV data, his real portrait photo, and clearly-labelled demo
campaign data. Luxury ("فخم") finish, Figma-level layout, After Effects-level motion.

## Reference images (study their layout exactly)
- workspace/user/files/79024_0_ix7w.png — Folder hero + About/ID-card page
- workspace/user/files/79031_1_z7vi.png — Brand identity detail, laptop mockup, typography card
- workspace/user/files/79030_2_l7o7.png — Photos collage, phone-in-hand mockup, INTRODUCTION
- workspace/user/files/79029_3_6oli.png — Floating tilted job cards + big section title + laptop
- workspace/user/files/79028_4_cs77.png — Floating tilted job cards (detail)
- workspace/user/files/79032_5_ewrp.png — Content Direction section, stacked browser-window cards

## Design language of the reference (replicate faithfully)
- Palette: near-black navy background (#020617 / #030B2E) melting into vivid royal
  blue (#0057FF / #0066FF) gradients; white cards; Meta-blue accents; sticker white outlines.
- Scrapbook collage: tilted stickers with white borders and drop shadows, paper
  clips, binder clips, tape banners, sticky notes, sparkle/star shapes, pixel cursor.
- Chunky bold display typography for "PORTFOLIO", outline/ghost huge numbers (01, 02)
  and ghost background words, blue marquee strips with ✳ separators repeating a
  section word (ABOUT ME ✳ / EXPERIENCES ✳ / MY WORKS ✳).
- Pill tab headers on sections (dark pill + thin line), tabbed tops like
  "Branding / Content Direction" pill switchers.

## Page structure (in this order)
1. HERO — giant blue file-folder graphic centered (folder tab on top, papers
   peeking out), "Digital Marketing" on the paper, huge chunky "PORT —
   FOLIO" with a "2026" pill, rotating circular stamp text "THE LIFE OF A
   DIGITAL MARKETER •", a memoji-style 3D cartoon avatar of Ahmed (built from
   his portrait: dark wavy hair, beard, suit) peeking at bottom-left of the
   folder, tape banner "Call me Ahmed!", floating stickers: tilted blue square
   "Hi, I'm a digital marketer", oval "Branding", oval "Website", paper clips,
   binder clip, small memo note with thumbs-up icon, pixel mouse cursor.
   Dark navy-to-blue gradient background. "Discover More ↓" pill button.
2. MARQUEE strip: "ABOUT ME ✳ ABOUT ME ✳ ..."
3. ABOUT — LEFT: ID-badge card hanging from a lanyard clip at the top, dark
   frame, his real portrait photo inside, vertical blue strip "PORTFOLIO 2026",
   blue name banner "AHMED SAMIR", phone + email at the bottom of the card.
   RIGHT: dark glass panel, pill header "ABOUT ME", his real CV summary in 2–3
   paragraphs. BELOW: 3 dark panels — PERSONAL INFO (full name, location,
   languages) / EDUCATION (B.Sc. IT, Al-Hikma University 2021–2025, GPA-style
   line: high-school 81.13%) / CONTACT (address Sana'a Yemen, email, phone).
   BELOW: SOFTWARE panel with tool icon tiles (Meta, Google Ads, Google
   Analytics, Tag Manager, WordPress, Excel, Canva-style, etc.) and SKILLS
   panel with tilted sticker tags (Meta Ads, Google Ads, Content Creation,
   Marketing Planning, SEO, A/B Testing, Retargeting, Visual Communication).
4. MARQUEE strip: "EXPERIENCES ✳ ..."
5. EXPERIENCES — floating tilted folder-cards in dark space (like refs 4–5):
   01 Electronics Store — Digital Marketing Officer (Nov 2025),
   02 Rahiq Doan Honey — Web Developer & Digital Marketer (Jul–Aug 2025),
   03 Auto Parts Store — Google Ads Marketer (Apr–Jun 2026); each card blue
   gradient wave, date pill, small stickers ("Hi, I'm a digital marketer",
   "Branding"), rotating circular badge "LET'S BUILD SOMETHING TOGETHER ↗",
   stars and globe icon.
6. MY WORKS big title band "01. CAMPAIGN RESULTS" with ghost text behind.
   INTRODUCTION paragraph + a 3D laptop mockup (build the laptop shape in
   CSS/SVG — silver laptop, tilted in perspective, screen showing a Meta Ads
   dashboard mock) — image slots inside screens are placeholders the user
   will replace later.
7. CAMPAIGN RESULTS — the 5 consecutive carousel cards from before
   (Awareness, Engagement, Traffic, Leads, Sales), restyled to the reference
   language: stacked browser-window cards with traffic-light dots (like the
   Content Plan windows in ref 6), Coverflow motion, animated SVG charts,
   demo metrics clearly labelled "Demo data".
8. SERVICES / CONTENT DIRECTION — pill tab switcher (Services / Process /
   Content Direction) like the reference tabs; Content Direction shows
   Overview bullets, Pillar 50/30/20 bars, Tone & Mood.
9. CERTIFICATES — two groups styled as folder cards: Academic Certificates
   (B.Sc. IT — Al-Hikma University; High School Diploma 81.13%) and
   Professional Certificates (HubSpot, Meta via Coursera, Coursera Career
   Track, Udemy diplomas, YALI English).
10. TESTIMONIALS carousel (demo, labelled) + CONTACT CTA with phone mockup
    (build the phone frame; screen shows a Facebook-page-style profile for
    Ahmed — placeholder image slots), WhatsApp and email real links, footer.

## Shapes the assistant must BUILD (user explicitly said so)
Laptop mockup, phone mockup, ID-badge card + lanyard, folder hero, memoji-style
avatar of Ahmed, stickers, paper clips, tape, rotating stamp badges, marquees.
Photo/image slots inside mockups = labelled placeholders he will swap later;
his real portrait MUST be used in the hero avatar base and the ID card.

## Language
Bilingual with a visible EN / عربي toggle. English is the DEFAULT first
version (LTR, exactly like the reference); switching to Arabic translates ALL
content and flips to RTL without breaking the layout.

## Motion (After Effects level)
Choreographed hero timeline (folder rises, stickers pop with spring physics,
stamp rotates continuously), floating idle animation on stickers/cards,
parallax on scroll, marquee loops, masked reveals, magnetic buttons, 3D tilt
with glare on cards, Coverflow carousels, self-drawing SVG charts, animated
counters. Transform/opacity only, 60fps, prefers-reduced-motion respected,
zero horizontal overflow on mobile.

## Data rules
Real from CV: name Ahmed Samir Abdulaziz Assem, title Digital Marketing
Specialist & Web Developer, Sana'a Yemen, +967 775652828,
ahmedassem775@gmail.com, 3 jobs, education, certificates, skills,
+30% online sales, +50% engagement. Campaign numbers & testimonials = demo,
labelled as such. Social links except WhatsApp/email stay placeholders until
the user sends his real profile links.

## Revision 2 (2026-10-22, user-approved direction)
- Fully responsive: phone / iPad (portrait+landscape) / laptop / desktop breakpoints, designed layouts per device.
- Arabic localization 100%: every visible string translated in AR mode; full RTL via logical properties, correct Arabic typography (no letter-spacing, line-height ~1.9), LTR isolation for numbers/phones/emails.
- Fonts changed to modern digital: Arabic "Readex Pro"; English display "Sora"/"Space Grotesk" + body "Manrope"/"Inter"; per-language font systems.
- Hero tape banner: ONLY "Call me!" / «اتصل بي!» — never with his name.
- Organized icon system: uniform tiles/strokes, icon-size tokens per breakpoint (20/24/28/32).
- Polished tabs and unified section names in both languages.

## Revision 3 (2026-10-22, from user's phone screenshots)
- Hero folder headline: «ملف تسويق رقمي» / "Digital Marketing Portfolio".
- His title in ALL labels: «مختص تسويق رقمي» / "Digital Marketing Specialist".
- Marquee strip before EVERY section, repeating that section's own name (عنّي/خبراتي/نتائج الحملات/خدماتي/شهاداتي/آراء العملاء/تواصل معي).
- Zero tolerance at phone widths: no tag/sticker/stamp/card may tilt or float outside its frame, no overlaps, no clipped text; stamp must never cover stickers; language toggle lives ONLY in the header (never a floating mid-page pill).
- Percentages in Arabic render as LTR-isolated Latin runs: "+30%", "+50%" in that exact order.
- Carousels clip cleanly inside their card frame at 360-430px; no slide or metric text may be cut.

## Revision 4 (2026-10-23)
- Section order: Hero → About → CERTIFICATES → Experience → Campaign Results → Services → Testimonials → Contact.
- Certificate viewer: click any certificate → modal where the certificate slides out of a folder like a paper sheet; zoom +/- , download button, X close (+ backdrop/Esc).
- Hero intro on ALL devices incl. phone: animated cursor moves FIRST, clicks, then folder pops and hero elements stagger in.
- No section-name pill/kicker above ghost numbers anywhere — the marquee strip already names each section.
- Language toggle at the header's side edge, never centered.

## Revision 5 (2026-10-23, user review feedback)
- Certificate opening animation must be unmistakable: sheet starts hidden inside the folder pocket (clipped), rises out over ~1.4–1.8s with the pocket in front of its bottom edge, then settles into the viewer. No generic modal fade.
- Skills tags must fill the whole Skills card evenly — justified rows edge-to-edge, balanced on both halves, all widths/languages.
- Hero timeline: avatar pops with the folder, ~100–200ms after the cursor click, before stickers/stamp/tape — never last.
