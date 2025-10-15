# AGS Systems – Landing Page (Vercel)

This is a static site ready for deploy to Vercel.

## Files
- `index.html` — the landing page
- `logo.png` — your logo (centered in hero)
- `favicon.png` — tab icon
- `vercel.json` — optional config (clean URLs + security headers)

## Deploy (GUI)
1. Go to https://vercel.com/new
2. Drag & drop this folder (or the ZIP) into the upload area.
3. Project name: `ags-systems-landing` (or anything you like).
4. Framework preset: **Other** (static).
5. Click **Deploy**. Your site will be live at a Vercel URL.

## Deploy (CLI)
```bash
npm i -g vercel
vercel login
vercel /path/to/ags-systems-landing
```
Accept defaults; you'll get a live URL.

## Custom domain
1. In your Vercel project, go to **Settings → Domains**.
2. Add your domain (e.g., `agssystems.co`). 
3. Follow the DNS instructions Vercel gives (usually a CNAME to `cname.vercel-dns.com`).

