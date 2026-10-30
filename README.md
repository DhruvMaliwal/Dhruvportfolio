# Dhruv Maliwal — portfolio

Single-file static site: `index.html`. No build step, no dependencies beyond Google Fonts.

## Deploy

**GitHub Pages:** Settings → Pages → Source "Deploy from a branch", pick this branch, folder `/ (root)`.
The site will be at `https://dhruvmaliwal.github.io/Dhruvportfolio/`.

**Vercel (personal account):** `npx vercel --prod` in this folder. Framework preset "Other", no build command,
output directory is the root. Make sure Deployment Protection is off so the page is public.
