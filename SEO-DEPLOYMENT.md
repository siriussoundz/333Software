# SEO deployment note

The GitHub Pages site is a review deployment, not the production identity. Every public page is intentionally marked `noindex, nofollow, noarchive`, and no canonical or `og:url` is set while `333software.co.uk` is inactive.

When `333software.co.uk` is activated, make these bounded changes in one release:

1. Remove the preview `robots` meta tags from all six public pages and update `robots.txt` for indexing.
2. Add one self-referencing production canonical URL and matching `og:url` to each public page.
3. Replace the six sitemap origins with `https://333software.co.uk` and submit the sitemap through the chosen search-console property.
4. If a share image is later approved, add absolute `og:image` and `twitter:image` URLs using the production domain.

Do not perform those production-domain actions before the domain and deployment routing are live.
