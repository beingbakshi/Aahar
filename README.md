# Aahar AI — Indian Diet Planner

AI-powered personalised Indian diet plans with regional food preferences, health analysis, and nutritionist chat.

## Deploy to Vercel

1. **Push to GitHub** (or connect your repo to Vercel)

2. **Import project** at [vercel.com/new](https://vercel.com/new)

3. **Add Environment Variable:**
   - Go to **Project Settings → Environment Variables**
   - Add `GEMINI_API_KEY` with your [Google Gemini API key](https://aistudio.google.com/app/apikey)

4. **Deploy** — Vercel will auto-detect the project and deploy.

## Local Development

```bash
# Install Vercel CLI
npm i -g vercel

# Run locally (serves index.html + API routes)
vercel dev
```

Then open http://localhost:3000

## Project Structure

```
├── index.html          # Main app (served at /)
├── api/
│   └── claude.js       # Serverless API proxy for Anthropic
├── aaharai_logo.png
├── favicon_io/
├── vercel.json
└── .env.example        # Template for ANTHROPIC_API_KEY
```
