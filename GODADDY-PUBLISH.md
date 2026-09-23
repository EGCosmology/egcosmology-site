# GoDaddy — publish this static site (shortest path)

Package folder: `egcosmology-site/`  
Zip handoff: `egcosmology-site-v2.zip`  
Contact that must appear everywhere: **tom@young01.xyz**

GoDaddy’s site editor in a desktop browser may be blocked; use **File Manager** (or phone app) from your GoDaddy account.

---

## Option A — Hosting + File Manager (preferred for this zip)

1. Unzip `egcosmology-site-v2.zip` on your computer. You should see `index.html`, `css/`, `js/`, etc. at the **root** of the upload set (not nested inside an extra empty folder if you can avoid it).
2. GoDaddy → your product → **Web Hosting** → **File Manager** (or cPanel File Manager).
3. Open the web root for egcosmology.com — usually `public_html` (or the domain folder).
4. **Back up** existing files (download a zip, or rename the old folder to `old-site-backup`).
5. Upload **all** files and folders from this package into the web root:
   - `index.html`, `what-is-egc.html`, `predictions.html`, `compare.html`, `reading.html`, `faq.html`, `contact.html`
   - `css/styles.css`, `js/nav.js`, `favicon.svg`
6. If the host expects `index.html` at the root, keep it there (not inside a subfolder).
7. Visit https://egcosmology.com/ and spot-check: Home, What is EGC, both DOI links, Contact shows **tom@young01.xyz**, mobile menu works.

---

## Option B — Websites + Marketing / Website Builder (custom HTML)

If you cannot replace the whole site via File Manager:

1. Prefer switching the domain to **hosted files** (Option A) when possible — Builder often strips CSS/JS.
2. If you must stay in Builder: create pages matching the site map and paste **body content** carefully; re-attach or paste critical styles if external CSS is stripped.
3. Set every contact / form notification address to **tom@young01.xyz** only (old address expired).
4. Replace any “paper click” stubs with:
   - https://doi.org/10.6084/m9.figshare.29429852  
   - https://doi.org/10.6084/m9.figshare.29874398  

---

## After upload — 60-second checklist

- [ ] `index.html` loads at the domain root  
- [ ] Relative links work (`css/styles.css`, all nav pages)  
- [ ] Mailto opens **tom@young01.xyz**  
- [ ] If a GoDaddy contact form remains, its notify-to address is **tom@young01.xyz**  
- [ ] Mobile: menu opens; text readable  

No server, PHP, or database required.
