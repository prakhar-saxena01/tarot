# ✦ The Arcana Academy — Tarot Learning Website

A complete interactive tarot curriculum — from first card to mastery.

---

## Deploy to Cloudflare Pages

### Option A — Drag & Drop (Fastest)

1. Go to [pages.cloudflare.com](https://pages.cloudflare.com)
2. Click **"Create a project"** → **"Direct Upload"**
3. Name your project (e.g. `arcana-academy`)
4. Drag and drop this entire **folder** (or zip it first)
5. Click **Deploy** — your site is live in seconds

Your URL will be: `https://arcana-academy.pages.dev`

---

### Option B — GitHub (Recommended for updates)

1. Push this folder to a GitHub repository
2. Go to [pages.cloudflare.com](https://pages.cloudflare.com) → **"Create a project"** → **"Connect to Git"**
3. Select your repository
4. Set **build settings**:
   - Framework preset: `None`
   - Build command: *(leave empty)*
   - Build output directory: `/` (root)
5. Click **Save and Deploy**

Every push to `main` will auto-deploy.

---

### Option C — Wrangler CLI

```bash
npm install -g wrangler
wrangler login
wrangler pages deploy . --project-name=arcana-academy
```

---

## File Structure

```
arcana-academy/
├── index.html       ← The entire site (self-contained)
├── _headers         ← Cloudflare security headers
├── _redirects       ← URL redirects
├── wrangler.toml    ← Wrangler CLI config
└── README.md        ← This file
```

## Features

- 78-card tarot reference (Major + Minor Arcana)
- 8 complete learning modules
- Interactive quiz (10 questions)
- Tarot journal (saves to browser localStorage)
- Spreads: daily draw, 3-card, Celtic Cross, custom
- Advanced: numerology, astrology, Kabbalah, ethics
- Zero dependencies — no build step required
