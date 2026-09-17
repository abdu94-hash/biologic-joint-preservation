# Biologic Joint Preservation — Clinic Companion

Free companion to *Biologic Joint Preservation: The Clinical Guide to PRP in Osteoarthritis — Science, Evidence, Controversy, and Patient-Centered Practice* — Dr. Hafez Selim, MD, PhD; Dr. Abir Hegazy, MB BCh, MSc (PM&R); Gana Sharafeldin, MB BCh BAO (Selim Medical Press).

**Live site:** https://abdu94-hash.github.io/biologic-joint-preservation/

## What it does

Seven screens, all running entirely in the browser, built from the book's Clinic Quick Guide, summary tables and appendices:

1. **Consultation** — selection worksheet (QG3), alternatives (QG4), shared decision and teach back (QG5), medication and procedure plan (QG6); builds a consultation note and handover (QG11) and lists open documentation items. No score is produced.
2. **Product & dose** — absolute platelet dose and fold enrichment with unit handling; refuses to calculate from a kit label; full product and procedure record (QG7, A3).
3. **Review & next step** — declared outcome measure and criterion, change from baseline, the five-pattern reassessment pathway, and the before-any-repeat-course checklist (QG8, QG9, S4).
4. **Safety triage** — post-procedure warning features mapped to the level of response; contact details flow into patient page B2 (QG10). Does not diagnose.
5. **Teaching cases** — the eight branching cases from Appendix E, with feedback on every option.
6. **At a glance** — summary tables S1–S4, evidence labels and sources Q1–Q6 (QG12).
7. **Patient pages** — printable B1 (making your treatment choice) and B2 (after PRP: your plan and when to get help).

## Design constraints

- **Single file.** No build step, no dependencies, no framework.
- **No network.** Zero external requests, no analytics, no tracking, no cookies, no web fonts.
- **No storage.** Nothing is saved or transmitted. Reloading discards everything.
- **Acceptance gate.** The companion will not open until the 15-clause terms of use are accepted.
- **Print bands.** Printed output carries the not-medical-advice / not-a-medical-device banner.

## Deployment

1. Create a public repository named `biologic-joint-preservation`.
2. Upload `index.html`, `og-image.png`, `robots.txt`, `sitemap.xml`, `404.html`, `.nojekyll`, and this README.
3. Settings → Pages → Source: **Deploy from a branch** → Branch `main`, folder `/ (root)` → Save.
4. The site appears at `https://abdu94-hash.github.io/biologic-joint-preservation/` within a few minutes.

## Legal

Educational aid for licensed healthcare professionals. **Not medical advice. Not a medical device. No clinical recommendation is produced.** Worksheets, pathways and cases are author-designed practice frameworks, not validated instruments. Platelet-rich plasma is not approved or cleared for the treatment of osteoarthritis by the FDA or any comparable authority known to the authors.

The views expressed are the authors' own and do not represent those of any current or former employer, client, institution, professional society, or regulatory authority.

Tools reviewed: 16 September 2026. Re-verify before relying on anything here.

Corrections: abdu94@gmail.com

© 2026 Abdulhafez A. Selim. Published by Selim Medical Press.
