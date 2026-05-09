# Nnaemeka Opara — Portfolio

Personal portfolio website for Nnaemeka Opara: Product Manager, Engineer, and Content Creator.

## Deploy on Vercel

1. Push this repo to GitHub
2. Go to [vercel.com](https://vercel.com) → New Project → Import your GitHub repo
3. Vercel will auto-detect as a static site — just click **Deploy**

That's it. No build step needed.

## Structure

```
portfolio/
├── index.html     # Entire site — self-contained, all images embedded as base64
├── vercel.json    # Vercel deployment config
└── README.md
```

## Updating

- Edit `index.html` directly for content changes
- To swap photos: replace the base64 strings (search for `data:image/jpeg;base64,`)
- To add your resume PDF download: replace the `href="#"` on the Resume footer link with your hosted PDF URL
