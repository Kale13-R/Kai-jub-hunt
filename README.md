# Kai's Job Hunt 🌊 — LMSW Edition

A personal job-finding tool for a **licensed LMSW** (Louisiana State Board of Social Work Examiners, MSW from Tulane) looking for social work jobs in **New Orleans, Chicago, and Southern California**.

It's a single, self-contained web page — no installs, no accounts, no server. All your data stays in your own browser.

## How to use it

**Option A — just open it:** download `index.html` and double-click it. That's it.

**Option B — host it free with GitHub Pages:** in this repo go to *Settings → Pages → Branch: main → root → Save*, and it'll be live at `https://<username>.github.io/Kai-jub-hunt/` on any device.

## What's inside

- **🔎 Find Jobs** — pick a city (New Orleans, Chicago, LA, Orange County, San Diego, Inland Empire, or **💻 Remote**) and a role type (forensic/juvenile justice, case manager, medical SW, behavioral health, school SW, hospice, crisis, and a "search by license" mode). It builds pre-tuned searches on Indeed, LinkedIn, Idealist, GovernmentJobs, NASW JobLink, ZipRecruiter, SimplyHired, and USAJOBS, with entry-level filters applied where the board supports them. A **Remote only** toggle works with any city choice — it swaps the location to "Remote" and layers on each board's real remote filter where one exists (LinkedIn `f_WT=2`, Indeed's remote attribute, Idealist's `locationType=REMOTE`, USAJOBS' remote indicator); boards with no such filter just search on the "Remote" location text instead.
- **✍️ Tailor** — automates per-role application prep. Pick a role type (Forensic / Juvenile Justice is the default — it matches the strongest resume experience) and get: a role-specific professional summary built from your profile, ATS keywords to weave in, resume bullets built from real experience, an **ATS keyword scanner** (paste a job description and see which keywords your resume hits vs. misses), and a full **cover letter generator**.
- **🚀 Auto Apply** — the batch pipeline, now with a **⚡ Fast Apply** mode as the default. Select saved jobs from the Tracker (💻 Remote OK jobs sort to the top, and a Remote-only filter narrows the picker to just those), and for each one it auto-detects the right role kit from the job title (or uses the role type you set), builds a **tailored resume** plus a **cover letter** with keywords pulled from the pasted job description. Fast Apply walks you through the selected jobs one at a time — copy resume, copy letter, open the posting, mark applied & auto-advance to the next one (with keyboard shortcuts `R`/`L`/`O`/`Enter`) — instead of scrolling through every packet at once. The old **📋 All at once** view is still there as a toggle for anyone who prefers it. A static page can't press "Submit" on employer sites, so it prepares everything and gets you to about a minute per application.
- **🏥 Employers** — a curated directory of 50+ LMSW-friendly employers across the three regions plus a **💻 Remote / Nationwide** category (national teletherapy platforms, EAP providers, and remote crisis/care-coordination organizations — flagged where a role needs independent LCSW-level licensure vs. where LMSW qualifies), filterable by type.
- **📋 Tracker** — log every application, tag it with a role type for tailoring and a **Remote OK** flag, move it through Saved → Applied → Interviewing → Offer, add notes, export to CSV/JSON. Saved jobs feed the Auto Apply tab.
- **🪪 Licensing** — Louisiana LMSW is ✅ in hand (License #19787, exp. 08/2026): renewal/CE reminders and the supervised path to LCSW, plus how to add Illinois (LSW by endorsement) and California (ASW registration) later, with board links.
- **👤 My Profile** — pre-loaded with the real resume: contact info, license number and expiration, bio, interests, field experience, and the full plain-text resume. Everything is editable, auto-saves, exports/imports as JSON, and powers the elevator pitch generator and every other tab.

## Your info is pre-loaded

The Profile tab ships pre-filled from Kai's resume (license #, experience, full resume text) — edit anything there and every generator updates. Use **Export JSON** to back up your profile and tracker, and **Import JSON** to restore them on another browser or computer.

> ⚠️ Data lives in your browser's localStorage — clearing site data clears it, so export a backup once in a while.
