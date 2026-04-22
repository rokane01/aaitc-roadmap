# Arbor AI Roadmap — AAITC, ARLO & ACE

Internal strategic roadmap covering the Arbor AI Tool Chest (AAITC), ARLO deployment layer, and ACE AI-powered CRM communication layer.

## Deploy to Vercel (Claude Code)

From this folder:

```bash
vercel --prod
```

Or for a preview deploy first:

```bash
vercel
```

First time? Link the project:

```bash
vercel link
vercel --prod
```

## File structure

```
arbor-ai-roadmap/
├── index.html       # The roadmap (single-file, self-contained)
├── vercel.json      # Clean URLs + security headers
└── README.md        # This file
```

No build step. No dependencies. Static HTML with inline CSS and web fonts from Google Fonts CDN.

## Version

v0.5 — Sources: Grain Ryan↔Mike 04/20, Project(s) Alignment 04/21, Patty Charter 04/16.

## Updating

Replace `index.html` with the new version and redeploy:

```bash
vercel --prod
```

Vercel keeps every deploy history at its own URL, so prior versions remain accessible via the dashboard.

## Audience

- Internal: full URL share with Jason, Patty, Shirley, Jess, Mike
- External: generate PDF via Chrome Print → Save as PDF (print CSS is already optimized)
