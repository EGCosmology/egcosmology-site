# egcosmology.com — static site v2

Publish-ready multi-page static package for **External Gravity Cosmology (EGC)** by Tom Young.
Local files only until published. Preferred free path: **GitHub Pages** (see `GITHUB-PAGES.md`).

## Contents

| File | Purpose |
|------|---------|
| `index.html` | Hero, key claims, claim → why → proposal → reading, briefing, CTAs |
| `what-is-egc.html` | Formal abstract, structured claims, glossary (OU, TU, OUEH, EGC) |
| `predictions.html` | Proposed observational checks (not claimed proofs) |
| `compare.html` | Careful ΛCDM vs EGC contrast table |
| `reading.html` | Both DOIs, how to cite, X link |
| `faq.html` | 8 FAQs from existing framing |
| `contact.html` | **tom@young01.xyz** + mailto UI + GoDaddy form note |
| `css/styles.css` | Scholarly dark-ink theme (serif headings, ~18px body, mobile nav) |
| `js/nav.js` | Mobile menu toggle |
| `favicon.svg` | Simple mark |
| `CNAME` | `egcosmology.com` (GitHub Pages custom domain) |
| `GITHUB-PAGES.md` | Free GitHub Pages + GoDaddy DNS setup |
| `GODADDY-PUBLISH.md` | Optional: host files on GoDaddy instead of Pages |
| `SITE-UPDATE.md` | v1 → v2 redo notes |

**Contact email (only):** `tom@young01.xyz`  
**X:** [@universerethink](https://x.com/universerethink)

**Papers:**

- https://doi.org/10.6084/m9.figshare.29429852  
- https://doi.org/10.6084/m9.figshare.29874398  

## Preview locally

```bash
cd /workspace/egcosmology-site
python3 -m http.server 8080
```

Open http://127.0.0.1:8080/

Handoff zip: `/workspace/egcosmology-site-v2.zip`

## Publish (free — GitHub Pages)

See **`GITHUB-PAGES.md`** for create-repo → Pages → custom domain `egcosmology.com` / `www` → GoDaddy DNS (A/AAAA + CNAME). Zero paid hosting plans.

Optional legacy notes: `GODADDY-PUBLISH.md` (only if you ever host files on GoDaddy instead of Pages).

Do not publish from the agent environment unless Tom asks. Parent handles `gh` auth and repo create.

## Editorial constraints

- No invented physics, metrics, citations, or observational “results.”
- Expand presentation of existing EGC framing only; hedge proposals as proposals.
- en-CA spelling where relevant (e.g. neighbours).
- Serious independent-researcher tone — no retail CMS fluff.
