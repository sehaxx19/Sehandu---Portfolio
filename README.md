# Sehandu Kurukularatne — Portfolio

A single-file static site (`index.html`) with a résumé at `assets/resume.pdf`. No build step needed — it deploys as-is.

## Deploy to Vercel

1. Go to [vercel.com/new](https://vercel.com/new), sign in with GitHub, and import this repo.
2. Leave all settings at their defaults (Framework Preset: "Other") and click **Deploy**.
3. Every future push to `main` auto-redeploys the site.

Or with the Vercel CLI: `npm install -g vercel`, then `vercel` (preview) or `vercel --prod` (production) from the repo root.

## Custom domain
In the Vercel dashboard → your project → **Settings → Domains** → add your domain and follow the DNS instructions (usually one CNAME record).

## Making changes
Everything — layout, styles, and behavior — lives in `index.html` (CSS in the `<style>` tag, JS in the `<script>` tag at the bottom). Edit it directly, then redeploy with `vercel --prod` or a `git push`.

To swap the résumé PDF, replace `assets/resume.pdf` with the same filename.
