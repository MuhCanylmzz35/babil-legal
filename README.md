# babil-legal — ARCHIVED

> ⚠️ This repo is **archived**. It is no longer the source of `babilfinance.com`.

## Current production site

The live `babilfinance.com` is now served from:
**[MuhCanylmzz35/babil-site](https://github.com/MuhCanylmzz35/babil-site)**

That repo contains the proper multi-file React source (landing.jsx, app-screens.jsx, pages.jsx, styles.css, assets/) that this repo used to ship as a single 1.6 MB inlined HTML bundle.

## History

- **2026-05-16** — repo created with `Babil Standalone.html` (the Claude Design bundled export) renamed to `index.html`. Also held `privacy.html` and `terms.html`.
- **2026-05-27** — domain `babilfinance.com` migrated to `babil-site`. This repo kept as a backup only.

## Why keep this?

Rollback safety. If `babil-site` ever breaks badly and needs to be reverted, this repo can be re-pointed to the domain in Vercel (Settings → Domains).
