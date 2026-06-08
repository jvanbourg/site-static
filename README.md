# Starlight Manufacturing LLC — site-static

Static one-page site for **starlightmanufacturing.com**, hosted via GitHub Pages
(see `CNAME`).

## Files

| File | Purpose |
| --- | --- |
| `index.html` | The page. Contains all SEO metadata + JSON-LD structured data. |
| `background.jpg` | Optimized hero background (~400 KB, was a 4 MB PNG). |
| `og-image.jpg` | 1200×475 social/search preview image. |
| `favicon.svg` | Site icon. |
| `robots.txt` | Allows all crawlers, points to the sitemap. |
| `sitemap.xml` | Single-URL sitemap for search engines. |
| `CNAME` | Custom domain for GitHub Pages. |

## SEO work done

- **Title + meta description** built around the exact brand name *Starlight Manufacturing LLC*.
- **Canonical URL** set to `https://starlightmanufacturing.com/`.
- **Open Graph + Twitter Card** tags with a dedicated preview image.
- **JSON-LD structured data** (`Organization` with `legalName`, plus `WebSite`)
  so Google can show a rich brand result / knowledge panel.
- **Performance:** hero image reduced ~90% (4 MB → 400 KB), fonts preconnected,
  hero image preloaded. Good Core Web Vitals → ranking benefit.
- **Crawlability:** `robots.txt` + `sitemap.xml`.
- Semantic HTML (`main`, `section`, `footer`), accessible links, `tel:` link.

## What YOU still need to do to rank #1 for "Starlight Manufacturing LLC"

On-page SEO is only half the battle. For a brand-name search, ranking #1 is
very achievable, but Google has to know the site exists and trust it:

1. **Deploy** these changes (push to `main`; GitHub Pages auto-publishes).
2. **Verify the domain in [Google Search Console](https://search.google.com/search-console)**
   (`starlightmanufacturing.com`).
3. In Search Console, **submit `sitemap.xml`** and use **URL Inspection →
   "Request indexing"** on the homepage. This is the fastest path to getting
   crawled.
4. **Confirm HTTPS** is enforced (GitHub Pages: enable "Enforce HTTPS").
5. **Build a few authoritative citations** that link to the site and use the
   exact name "Starlight Manufacturing LLC" — e.g. Google Business Profile,
   LinkedIn company page, state business registry listing, industry directories.
   Consistent name + URL across these is the strongest signal for a brand query.
6. Optionally add a real business address/hours and switch the JSON-LD
   `Organization` to `LocalBusiness` for a richer local result.

Items 2–3 typically get a brand-name site to the top within days to a couple of weeks.
