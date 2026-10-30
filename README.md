# Pocketfolio website

The marketing site for Pocketfolio, the personal wealth platform for Australians building wealth.

Live at **https://pocketfolio.com.au**

## What's in here

| Path | What it is |
|---|---|
| `index.html` | Home page, including the app demo (opens from "See how it works") |
| `terms/`, `privacy/`, `cdr-policy/` | Legal pages, each at its own URL |
| `404.html` | "Page not found" page |
| `people/` | Photos for the "Who it's for" section (Unsplash, free licence) |
| `fonts/` | Host Grotesk, self-hosted |
| `og.png` | Share image for social links (1200×630) |
| `favicon.svg`, `favicon-32.png`, `apple-touch-icon.png`, `icon-192.png`, `icon-512.png`, `site.webmanifest` | Browser and phone icons |
| `robots.txt`, `sitemap.xml` | Search engine files |
| `CNAME` | Custom domain for GitHub Pages |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are |

No build step. Every file is ready to serve as-is.

## Publish with GitHub Pages

1. Push these files to the root of a repository (for example `pocketfolio-site`).
2. In the repository, go to **Settings › Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, branch `main`, folder `/ (root)`, and save.
4. Under **Custom domain**, confirm `pocketfolio.com.au` (it's read from the `CNAME` file).
5. At your domain registrar, add these DNS records:
   - `A` records for `@` pointing to `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - a `CNAME` record for `www` pointing to `<your-github-username>.github.io`
6. Once the domain shows as verified, tick **Enforce HTTPS**.

## After launch

- Submit your own email in the sign-up form once and confirm the email Formspree sends you. The form posts to `https://formspree.io/f/xrppqnqg`.
- In Formspree, restrict the form to `pocketfolio.com.au`.
- Add the site to Google Search Console and submit `https://pocketfolio.com.au/sitemap.xml`.
- Optional: put a short video named `hero.mp4` in the root and it can be used behind the hero card.

## Contact

support@pocketfolio.com.au · Instagram [@pocketfolioapp](https://www.instagram.com/pocketfolioapp/)
