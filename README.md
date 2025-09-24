# HomeNetIQ — Website Starter (homenetiq.ca)

This bundle contains:
- `index.html` — your one-page website (static, secure) branded for **HomeNetIQ**.
- `_headers` — security headers for Netlify/Vercel (GitHub Pages ignores this file).
- This README with deploy steps for your **homenetiq.ca** domain.

## Deploy on GitHub Pages — $0/month

1. Create a free account at https://github.com and make a new **public** repo (e.g., `homenetiq-site`).
2. Upload `index.html` (and `_headers` if you later use Netlify/Vercel).
3. Repo → **Settings → Pages** → Source: **Deploy from a branch**; Branch: `main`; Folder: `/ (root)`.
4. Visit the URL GitHub gives you. Enable **Enforce HTTPS** when available.

### Connect your domain (homenetiq.ca)
- In **Settings → Pages**, add your custom domain: `homenetiq.ca` (and optionally `www.homenetiq.ca`).
- At your registrar’s DNS:
  - CNAME: `www` → `<your-username>.github.io`
  - Apex/root (`homenetiq.ca`): point via ALIAS/ANAME or A-records per GitHub Pages docs.
- Back in GitHub Pages, ensure **Enforce HTTPS** is enabled after the certificate is issued.

## Optional: Netlify (also $0/month)
- Drag-and-drop `index.html` to Netlify → deploys instantly.
- Put the contents of `_headers` into a file named `_headers` at site root to enable strict security headers.
- Built-in **Netlify Forms** collects submissions from the form in `index.html`.

## Editing Content Later
- Open `index.html` in the repo → click the pencil icon → edit text in **Services**, **About**, and **Contact**.
- Commit changes; the site updates shortly.

## Replace Placeholders
- Swap `YOUR@EMAIL` with your preferred inbox (e.g., `hello@homenetiq.ca`).
- Update the “Serving Alberta” text or service areas as needed.

---
Generated 2025-09-23 23:13 UTC
