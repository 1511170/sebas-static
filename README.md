# sebas-static

Static export of **Sebas.co** generated with [Astro](https://astro.build).

- **Repo:** [github.com/1511170/sebas-static](https://github.com/1511170/sebas-static)
- **Branch:** `main` (default for deploy)

## Contents

- **Home** – `/` (index.html)
- **KOL / Influencers** – `/kol/`
- **Professional Trader** – `/trader/`
- **Funds (Institutional)** – `/fund/`
- **Platform / Communities** – `/platform/`

## Deploy

Upload this folder to any static host:

- **Cloudflare Pages** – drag & drop or connect Git
- **Vercel** – import and set root to this directory
- **Netlify** – publish directory: `.` or `sebas-static`
- **GitHub Pages** – push to a branch and enable Pages
- **AWS S3 + CloudFront** – sync the folder to a bucket

No build step required; serve the files as-is.

## Source

Built from the main [sebas](.) monorepo:

```bash
cd sites/sebas
npm run build
# Output: dist/ → copied here
```

## License

Same as the parent Sebas.co project.
