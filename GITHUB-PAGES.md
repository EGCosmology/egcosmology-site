# Free publish — GitHub Pages + egcosmology.com

Zero paid plans. Parent/agent creates the repo; you (or parent) push this folder and set DNS at GoDaddy.

## 1. Create the repo (free)

1. GitHub → New repository (e.g. `egcosmology-site` or `egcosmology.com`).
2. Public is simplest for free Pages. Private Pages also works on a free personal account for user/org sites in current GitHub product rules — public is the usual path.
3. Do **not** initialize with a README if you will push this folder as the root.

## 2. Push this site to `main` (site at repo root)

The publish root must contain `index.html`, `CNAME`, `css/`, `js/`, etc.

```bash
cd egcosmology-site   # or unzip egcosmology-site-v2.zip first
git init
git add .
git commit -m "Publish EGC static site for GitHub Pages"
git branch -M main
git remote add origin git@github.com:USER/REPO.git
git push -u origin main
```

(Parent handles `gh` auth / repo create if you use the agent pipeline.)

## 3. Enable GitHub Pages (free)

1. Repo → **Settings** → **Pages**.
2. **Build and deployment** → Source: **Deploy from a branch**.
3. Branch: **main** → folder: **/ (root)** → Save.
4. Wait for the green “Your site is live” check.
5. Under **Custom domain**, enter `egcosmology.com` and save.
6. Enable **Enforce HTTPS** after DNS validates (may take minutes to hours).
7. Optionally add `www.egcosmology.com` as well (GitHub can redirect www ↔ apex once DNS is set).

The repo already includes a **`CNAME`** file with `egcosmology.com` so Pages keeps the custom domain across pushes.

## 4. GoDaddy DNS → GitHub Pages (free DNS on your domain)

In GoDaddy → **Domain** egcosmology.com → **DNS** / Manage DNS.

### Apex (`egcosmology.com`) — A records

Remove conflicting apex A/AAAA/CNAME records, then add GitHub’s current apex **A** records (verify against [GitHub Docs: managing a custom domain](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site) if these ever change):

| Type | Name | Value | TTL |
|------|------|-------|-----|
| A | `@` | `185.199.108.153` | 600 |
| A | `@` | `185.199.109.153` | 600 |
| A | `@` | `185.199.110.153` | 600 |
| A | `@` | `185.199.111.153` | 600 |

Optional IPv6 (AAAA), same docs page:

| Type | Name | Value |
|------|------|-------|
| AAAA | `@` | `2606:50c0:8000::153` |
| AAAA | `@` | `2606:50c0:8001::153` |
| AAAA | `@` | `2606:50c0:8002::153` |
| AAAA | `@` | `2606:50c0:8003::153` |

### www — CNAME

| Type | Name | Value | TTL |
|------|------|-------|-----|
| CNAME | `www` | `USER.github.io` | 600 |

Use your GitHub username (user site) or `USER.github.io` / org Pages host as shown in the repo’s Pages settings. For a project site it is often `USER.github.io` still as the CNAME target when GitHub documents that pattern; prefer the exact target GitHub shows under Pages → Custom domain instructions for your repo.

**Do not** point DNS at GoDaddy Website Builder if you want this static Pages site to answer on the domain.

## 5. After DNS propagates

1. Open https://egcosmology.com/ and https://www.egcosmology.com/  
2. Check: Home, What is EGC, Predictions, Compare, Reading, FAQ, Contact  
3. Contact / mailto = **tom@young01.xyz** only  
4. Both DOIs open  
5. Mobile menu works  

## Cost

- GitHub account + Pages: **free** for this static site  
- Domain renews at GoDaddy separately (you already own it)  
- No Netlify/Vercel/GoDaddy hosting plan required  

## Contact rule

Every published page must keep **tom@young01.xyz** as the only email.
