# Swiggy IPE Job Evaluation

A self-assessment tool based on the Mercer IPE methodology, calibrated to Swiggy's B6–B11 levelling framework.

## Deploy to Vercel (2 ways)

### Option A — Drag & drop (no CLI needed)
1. Go to [vercel.com/new](https://vercel.com/new)
2. Click **"Deploy from template"** → skip, or just drag the project folder
3. Drop the entire `swiggy-ipe` folder onto the Vercel dashboard
4. Click **Deploy** — done in ~30 seconds

### Option B — Vercel CLI
```bash
npm i -g vercel
cd swiggy-ipe
vercel
```
Follow the prompts. Your app will be live at a `.vercel.app` URL.

### Option C — GitHub + Vercel (recommended for ongoing updates)
1. Push this folder to a GitHub repo
2. Go to [vercel.com/new](https://vercel.com/new) → Import Git Repository
3. Select your repo → Deploy
4. Any future push to `main` auto-deploys

## What's in the app
- 5 Mercer IPE factors mapped to Swiggy pillars
- 6 band levels per factor (B6–B11)
- Live IPE total score + band recommendation
- Radar chart of factor scores
- Light/dark mode support
- Mobile responsive
