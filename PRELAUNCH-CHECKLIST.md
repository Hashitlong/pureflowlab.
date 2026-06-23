# PureFlow Lab Prelaunch Checklist

## Publish Blockers

- Replace every `?tag=[NEWTAG]` placeholder with the real affiliate tag before launch.
- Replace `[YOUR NAME]` and `[YOUR STATE]` in `about.html`.
- Decide the exact canonical production domain, including whether you are using `https://pureflowlab.com` or `https://www.pureflowlab.com`.

## Domain-Dependent SEO Tasks

- Add a canonical URL to every indexable page.
- Add Open Graph and Twitter image metadata to every page.
- Add JSON-LD:
  - `Organization` and `WebSite` on `index.html`
  - `CollectionPage` on `reviews.html`, `buying-guides.html`, and `guides.html`
  - `Article` plus `BreadcrumbList` on article pages
- Generate a `robots.txt` that allows crawling and points to the live sitemap URL.
- Generate a `sitemap.xml` with full absolute URLs.

## Crawlability And Indexation

- Verify there is no staging `noindex` header or meta tag at the hosting layer.
- Make sure the final host resolves one canonical version only:
  - force HTTPS
  - force either `www` or non-`www`
  - redirect `/index.html` to `/` if your host serves both
- Submit the sitemap in Google Search Console after launch.
- Manually test these URLs in the live environment:
  - `/`
  - `/reviews.html`
  - `/buying-guides.html`
  - `/guides.html`
  - 2 money pages
  - 2 info pages

## Internal Linking Strategy

- Keep the three main hubs strong:
  - `reviews.html`
  - `buying-guides.html`
  - `guides.html`
- Every article should link to:
  - its category hub
  - 2 to 4 sibling articles in the same cluster
  - 1 to 2 adjacent commercial or informational next-step pages
- Keep these query paths intact because they match search intent well:
  - `what-is-reverse-osmosis-water.html` -> `is-reverse-osmosis-water-good-for-you.html` -> `best-reverse-osmosis-system.html`
  - `whole-house-vs-under-sink-ro.html` -> `whole-house-ro-cost.html` -> `best-whole-house-reverse-osmosis-system.html`
  - brand reviews -> relevant buying guide -> affiliate click

## Content Quality Risks

- Validate every `Updated June 2026` statement against the actual review cycle you want to claim.
- Double-check brand-specific factual claims, especially certifications, capacities, and dealer pricing ranges.
- Add original photography, test photos, or comparison graphics over time. The written content is stronger than most affiliate sites already, but unique media will help credibility.

## Post-Launch

- Set up Google Search Console and Bing Webmaster Tools on the live domain.
- Track which informational pages earn impressions first; they will likely index before the harder money terms.
- Watch coverage, canonical, and crawl stats in the first 2 to 4 weeks.
