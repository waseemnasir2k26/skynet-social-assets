# 2026.09 — Maintenance release

- Maintenance review of skynet-social-assets — a public asset bucket holding the images, carousels, PDFs and videos SkynetLabs links to from social posts.
- Status: 51 files, loosely organised by campaign and date rather than by a scheme — `aeo/` (dated AEO carousel slides and cafe-work stills), `images/` (Claude-Code video-system cards, a Kimi K3 card, an 8-slide Opus 5 IG carousel in both PNG and JPEG), `launch-2026-06-20/`, `reelforge/`, `pdfs/SkynetLabs-Autopublish-Blueprint.pdf`, and `videos/` (the Claude autopublish final cut and a 9:16 coffee vlog with a CDN variant and thumbnail). The most recent commit notes the IG carousel was re-exported to JPEG because Instagram rejects PNG.
- Reviewed September 2026: a README was added (the repo had none), a CHANGELOG started, and the repo released as v2026.09. No assets added, replaced or removed.
- Known gaps: no README existed before this release and there is still no manifest mapping each asset to the post or campaign that uses it, so an unreferenced file cannot be distinguished from a live one.
- Known gaps: layout is inconsistent — some assets sit at the repo root while others are foldered by date or campaign, and both PNG and JPEG copies of the same carousel are kept.
- Repo hygiene: no LICENSE file, which matters more here than usual because the repo is public and serves media; no CI workflow; no package manifest, so no machine-readable version to bump.
