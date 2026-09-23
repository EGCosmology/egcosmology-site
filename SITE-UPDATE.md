# Site update summary — egcosmology.com

**Draft location:** `/workspace/egcosmology-site/`  
**Zip:** `/workspace/egcosmology-site-v2.zip`  
**Date:** 2026-09-23 (PT)  
**Contact locked to:** `tom@young01.xyz` only  
**X handle:** `@universerethink` (consistent with live site)

## v2.6 — CMB map reference (+ redshift residual hook)

Public data-reference page for Planck PR3 SMICA (and companion Pantheon+ residual map section) used in planned offline CMB↔redshift work. No correlation results or p-values.

### New / updated

| Path | Role |
|------|------|
| `cmb-map.html` | CMB map reference: product links, Mollweide plots, top-10 hot/cold extrema; Pantheon+ residual section |
| `images/cmb-smica-mollweide.png` | Masked SMICA, 1° FWHM |
| `images/cmb-smica-mollweide-largescale.png` | Masked SMICA, 5° FWHM |
| `images/cmb-smica-mollweide-unmasked.png` | Full-sky 1° (optional asset) |
| `images/pantheonplus-residual-mollweide*.png` | Pantheon+ δμ maps (companion section) |

### Method (CMB)

- Product: `COM_CMB_IQU-smica_2048_R3.00_full` (I_STOKES); mask `COM_Mask_CMB-common-Mask-Int_2048_R3.00`
- Ud_grade NSIDE 2048→512; FWHM 1° for extrema; 10° exclusion; units µK
- PR3 working baseline; PR4/NPIPE noted as cross-check
- Nav: “CMB map” on all main pages + outline

### Untouched (by design)

- No EGC correlation claims / p-values on the page  
- Contact remains `tom@young01.xyz`

---

## v2.5 — Visitor voice (no internal memo / no internal labels)

Tom Young: *“You have written like you are talking to yourself. Fix it.”* Plus hard rule: internal collaborator filing labels must not appear in any public / visitor-facing text (HTML, SITE-UPDATE, CMB outline HTML/MD). Refer only to collaborator notes / working manuscripts / research notes.

### Voice changes

- Dropped meta taxonomy: door / face / hierarchy / fight / “how this site organises” / “How to read this page” as filing narration.
- Ordinary labels: **Start here · Concepts · Observational tests · Working notes · Draft study outline**.
- Home “How to read this site” → **Explore** (cards describe content, not taxonomy).
- Reading page: suggested order concepts → tests → maths notes → draft CMB–redshift study; no architecture lecture; no collaborator-file policy asides.
- “Scaffolding” no longer used as a brand; exploratory / preliminary maths may be labelled once.
- Third person / impersonal; science kept (OU/TU/OUEH, External Gravitational Forces, Planck/Pantheon+/etc.).
- Collaborator source binaries under the private source tree remain **not rewritten**.

### Pages / files touched (v2.5)

| Path | Change |
|------|--------|
| `index.html` | Explore cards; observational-program copy; latest-reading card |
| `reading.html` | Suggested reading order; quieter notes |
| `predictions.html` | About-these-checks; priority draft study; survey-notes wording |
| `faq.html` | Maths status; datasets; where-to-start order |
| `what-is-egc.html` | Claims + glossary; suggested order |
| `compare.html` | Maths/data row wording |
| `papers/egc-cmb-redshift-correlation-outline.html` | Related material; focused-test wording |
| `/workspace/egc-source/drafts/EGC_CMB_redshift_correlation_outline.md` | Matching tone scrub |
| `SITE-UPDATE.md` | This note; internal filing labels removed from public text |

### Untouched (by design)

- Collaborator source binaries in the private source tree — not rewritten  
- No invented physics beyond Figshare + collaborator roadmap summaries  
- Contact remains `tom@young01.xyz`

---

## v2.4 — Elevate research path + CMB↔redshift outline

Tom Young (EGC author) agreed the strategy and said “make it so.”

### Public path (now ordinary labels in v2.5)

1. **Concepts** — manifesto / *Rethinking the Universe* lineage, summarised in site voice  
2. **Working notes** — exploratory mathematical modeling (not finished theory)  
3. **Observational tests** — *Toward Testing External Gravity Cosmology* (Planck, Pantheon+, SDSS/CatWISE, DESI/Euclid, JWST, GW)  
4. **Draft study outline** — CMB temperature/anisotropy ↔ directional redshift residuals, with explicit null / falsification  

### New artifacts

| Path | Role |
|------|------|
| `papers/egc-cmb-redshift-correlation-outline.html` | Site-voice draft paper outline (Young framing) |
| `/workspace/egc-source/drafts/EGC_CMB_redshift_correlation_outline.md` | Plain markdown twin of the outline |

Outline includes: title, abstract sketch, EGC motivation, datasets, method sketch, **null + falsification**, systematics, deliverables, “not claimed yet” boundaries.

### Pages touched (v2.4)

| Page | Key changes |
|------|-------------|
| `reading.html` | Research path grid; link to CMB outline |
| `predictions.html` | Next empirical focus callout; primary check links outline |
| `index.html` | Explore / path cards; latest-reading card |
| `what-is-egc.html` | Test-program claim + glossary note link outline |
| `faq.html` | Reading path + roadmap / proof FAQs point to outline |
| `SITE-UPDATE.md` | This note |

### Untouched (by design)

- Collaborator source binaries in the private source tree — not rewritten  
- No invented physics beyond Figshare + collaborator roadmap summaries  
- Contact remains `tom@young01.xyz`  
- Redshift-mechanism debates not hammered; site describes external gravity / testable correlations without restyling collaborator manuscripts  

## v2.3 — Collaborator / roadmap fold-in (site voice only)

Source extracts (text only; originals not modified) under `/workspace/egc-source/state-of-things/extracts/`:

- Collaborator / research notes: Tom-edits extract, milestone1, mathematical_modeling, milestone3, milestone4, Secrest_2021  
- Top drafts: `EGC_short_version.docx.txt`, `Dark_Energy_actual_state_2.txt`, `Dark_Energy_misperception.txt`, `Grok_summary_3_21_2025.txt`, `Conversation_dark_energy_matter.txt`, `Universal_Rethink_The_Book.txt`, `conversation_Grok_1_CoPilot.txt`

**Voice rule:** Collaborator articles/manuscripts keep their original wording and tone. The site summarises ideas in its own professional academic voice or points readers to request documents — it does **not** paste rewritten collaborator prose or restyle collaborator source files.

### Folded in (new themes)

- Careful Secrest et al. (2021) / CatWISE quasar-dipole context as **already cited** in the EGC Figshare short paper — motivating anisotropy literature, not an EGC proof claim
- Cosmological-principle tension framed as expected under anisotropic TU (compare + FAQ)
- Exploratory mathematical notes status (Φ / directional δz~δTCMB program) labelled exploratory / preliminary, not finished theory
- Distributed research roadmap datasets: Planck, Pantheon+, SDSS/CatWISE, DESI/Euclid, JWST, longer-term GW anisotropy (predictions + FAQ + reading notes)
- Reading page notes path: concepts → notes → roadmap → invitation (summary only)

### Pages touched (v2.3)

| Page | Key changes |
|------|-------------|
| `what-is-egc.html` | Abstract to impersonal site voice; claims + glossary for anisotropy literature, maths notes, CP context |
| `index.html` | State-of-argument items for Secrest-cited dipole context + data program |
| `predictions.html` | Secrest caution on dipole check; new survey cross-check + GW-horizon proposals |
| `compare.html` | Rows for cosmological principle + math/data program |
| `faq.html` | New Qs: Secrest/CP, math status, roadmap datasets |
| `reading.html` | Reading notes + Secrest DOI as cited literature pointer |
| `SITE-UPDATE.md` | This note |

`contact.html` unchanged in substance (email already `tom@young01.xyz`).

### Deliberately left out

- No rewritten / restyled collaborator manuscript text on the site
- No tired-light / tired-gravity framing as EGC’s identity (redshift kept as observed fact / mechanism-open)
- Informal Grok chat logs, book outlines, recruiting/personal chatter, vulgar draft language
- Hawking / “renewal” speculation beyond the existing labelled FAQ note
- Overclaim that Secrest (or any single dipole paper) proves EGC
- Asserting gravitational-redshift equations as settled site doctrine (exploratory notes only)

## v2.2 — OneDrive draft enrichment (not published)

Authoritative framing sources (already extracted under `/workspace/egc-source/`):

1. `Dark_Energy_actual_state.txt` — External Gravitational Forces as unifying answer; OU / The Universe / OUEH; JWST high-z SMBHs as edge/older objects; CMB as averaged mass-energy "hum" / forest-trunks analogy; redshift↔CMB overlay as proof path; neighbourhood mapping beyond OUEH. Renewal/rebirth musing labelled **speculation** only (short FAQ note; omitted from core claims).
2. `Document_1.txt` — Vocabulary recap (The Universe / Our Universe / OUEH; uneven pulls; redshift as motion toward horizon; early giants as edge-dwellers; acceleration from closing on external masses). Personal/recruiting chatter (virologist hunt, etc.) **excluded**. Handle normalised to `@universerethink`.
3. Existing site pages + `egc-short.txt` (Figshare short-paper abstract) — scientific claims unchanged; vernacular polished for academic/professional public tone.

### Pages touched (v2.2)

| Page | Key additions |
|------|----------------|
| `index.html` | "State of the argument" lead (External Gravitational Forces); how-the-pieces-fit cards; sharpened briefing (OU/TU/OUEH, CMB hum, closing-on-masses); primary check = redshift↔CMB overlay |
| `what-is-egc.html` | EGF answer lead; core vocabulary cards; claims for uneven pulls, acceleration from closing distances, edge-dwellers; glossary entry for External Gravitational Forces |
| `predictions.html` | Primary proof path = redshift↔CMB overlay; high-z as edge-dwellers; new neighbourhood-mapping check |
| `compare.html` | Rows sharpened for EGF pull-not-push, CMB hum, edge-dwellers, beyond-horizon mapping |
| `faq.html` | New Qs on EGF, redshift, JWST edge-dwellers, neighbourhood mapping; labelled speculation FAQ on renewal; reading path updated |
| `css/styles.css` | `.answer-lead`, `.state-list`, `.vocab-grid` / `.vocab-card` |
| `SITE-UPDATE.md` | This note |

Contact, reading, and publish kit pages unchanged in substance (`contact.html`, `reading.html`, `GODADDY-PUBLISH.md`, `GITHUB-PAGES.md`, `CNAME`).

## v2 redo (vs v1 draft)

1. **Expanded IA** — New pages: `predictions.html`, `compare.html`, `faq.html`. Nav covers Home · What is EGC · Predictions · Compare · Reading · FAQ · Contact.
2. **Clearer structure** — Home now leads claim → why it matters → evidence/proposal → reading, plus an Explore path and latest-reading CTAs.
3. **Glossary** — OU, TU, OUEH, EGC on What is EGC.
4. **Predictions page** — CMB↔IR, anisotropy/dipoles, high-z timing framed as proposals with "supports / pressures" hedges — not completed proofs.
5. **ΛCDM contrast** — Careful table: what each posits; EGC labelled alternative proposal.
6. **FAQ** — Orientation questions from existing framing (CMB interpretation, dark energy, proof status, reading path, etc.).
7. **Design bar raised** — Deep navy/ink, Palatino/Georgia serif headings, ~18px body, larger whitespace, cards/tables, sticky header + mobile hamburger, skip link, accessible contrast. Self-contained fonts (no CDN).
8. **Contact** — Prominent `tom@young01.xyz`; mailto-only form UI; explicit note to update GoDaddy form destination.
9. **Publish kit** — `GODADDY-PUBLISH.md` + zip handoff.

## Still true vs live GoDaddy site (from v1)

- Removed repeating tagline noise and business-hours / "customers" copy.
- Working DOI CTAs (no broken paper stubs).
- Abstract preserved from Figshare short version; claims unchanged.
- No fabricated citations or metrics.

## Contact rule

All mailto + displayed email addresses: **tom@young01.xyz** only.

## Not done (by design)

- Not published live (GoDaddy browser blocked; phone editor is Tom's).
- No analytics, cookies, or third-party widgets.
- No new physics beyond published EGC framing / author drafts (polished vernacular only).

## v2.1 — GitHub Pages handoff

- Added `CNAME` (`egcosmology.com`) and `GITHUB-PAGES.md` (free Pages + GoDaddy DNS).
- Publish target: GitHub Pages only (no paid hosting).
- Zip refreshed: `/workspace/egcosmology-site-v2.zip`.
