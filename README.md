# AnjouHealth LMS

Workplace Health & Safety Learning Management System — Corporate Edition 2023–2026.

## Pages

| Page | URL | Description |
|------|-----|-------------|
| Main LMS | `/` | 11 courses, 27 modules covering all campaigns 2023–2026 |
| SA Deep Course | `/sa` | Situational Awareness deep-dive with interactive games |

## Deploy to Vercel

### Option A — Vercel CLI (fastest)
```bash
npm i -g vercel
cd /path/to/this/folder
vercel
```
Follow the prompts. Your site goes live in ~30 seconds.

### Option B — Vercel Dashboard (no CLI needed)
1. Go to [vercel.com](https://vercel.com) → **Add New Project**
2. Import from GitHub (push this folder to a repo first), **or** drag-and-drop this folder into the Vercel dashboard
3. Framework: **Other** (static site — no build step needed)
4. Click **Deploy**

### Option C — GitHub + Vercel auto-deploy
1. Create a new GitHub repo
2. Push this folder:
   ```bash
   git init
   git add .
   git commit -m "Initial deploy: AnjouHealth LMS"
   git remote add origin https://github.com/YOUR_USERNAME/anjouhealth-lms.git
   git push -u origin main
   ```
3. In Vercel dashboard → **Add New Project** → import from GitHub
4. Every future `git push` auto-deploys

## Local Preview
Open `index.html` directly in any browser — no server needed.

## Contents
- `index.html` — Main LMS (11 courses)
- `sa-deep-course.html` — Situational Awareness Deep Course
- `vercel.json` — Vercel routing config
- `.gitignore` — Git ignore rules
