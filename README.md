# Marketing Unit Economics

An interactive calculator that shows how revenue turns into profit per customer. It walks through discounts, COGS, selling and delivery costs, the cost to win a customer (CAC), the cost to keep them, and AI costs.

It covers DTC, B2C and B2B, each as a one-time sale, repeat purchases or a subscription.

It's a single static page. There's no build step and nothing else to install.

## Files

| File | Purpose |
|---|---|
| `index.html` | The page itself, with all CSS and JavaScript inline |
| `favicon.ico`, `favicon.svg`, `favicon-16x16.png`, `favicon-32x32.png` | Browser tab icons |
| `apple-touch-icon.png`, `icon-192.png`, `icon-512.png` | Home-screen icons for iOS and Android |
| `site.webmanifest` | App name and icons for "Add to home screen" |
| `og-image.png` | 1200×630 preview image shown when the link is shared on LinkedIn, X, Slack and iMessage |
| `robots.txt`, `sitemap.xml` | Tell search engines how to crawl and index the page |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are |

## Publish on GitHub Pages

**Option A: its own repo.** The site will be at `jameschrisa.github.io/unit-economics/`.

1. Create a repo named `unit-economics`.
2. Upload everything in this folder to the repo root, including the hidden `.nojekyll` file.
3. Go to Settings → Pages → Build and deployment. Set the source to "Deploy from a branch", the branch to `main` and the folder to `/ (root)`.

**Option B: a folder in your user site.** Copy this folder into your `jameschrisa.github.io` repo as `/unit-economics/`.

## If you use a different URL

The address `https://jameschrisa.github.io/unit-economics/` appears in these places:

- `index.html`: the canonical link, `og:url`, `og:image`, `twitter:image` and the JSON-LD block
- `robots.txt`
- `sitemap.xml`

Find and replace it in those files. Social previews need the full absolute URL for `og-image.png`.

## Notes

- Fonts load from Google Fonts. Everything else is self-contained.
- Visitors' slider settings are saved in their own browser (localStorage). No data leaves the page.
- Sample numbers are illustrative, not benchmarks.
