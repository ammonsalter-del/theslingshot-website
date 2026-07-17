# Slingshot per-page head tags: canonical, Open Graph, Twitter

The Slingshot pages have titles and descriptions but no canonical, Open Graph or Twitter tags (the homepage already has the game JSON-LD schema, which is good). Add the block below to each page's `<head>`, changing the three marked values. Reuse each page's existing `<title>` and `meta description` text for og:title and og:description so nothing contradicts.

Canonical tags matter most: they tell search engines which URL is authoritative.

## Template (paste into <head>, edit the three marked values)

```html
<!-- Canonical -->
<link rel="canonical" href="https://slingshotsim.org/PAGE">

<!-- Open Graph -->
<meta property="og:site_name" content="The Slingshot">
<meta property="og:type" content="website">
<meta property="og:url" content="https://slingshotsim.org/PAGE">
<meta property="og:title" content="PAGE TITLE">
<meta property="og:description" content="PAGE DESCRIPTION">
<meta property="og:image" content="https://slingshotsim.org/SOCIAL-IMAGE">
<meta property="og:locale" content="en_GB">

<!-- Twitter -->
<meta name="twitter:card" content="summary_large_image">
<meta name="twitter:title" content="PAGE TITLE">
<meta name="twitter:description" content="PAGE DESCRIPTION">
<meta name="twitter:image" content="https://slingshotsim.org/SOCIAL-IMAGE">
```

## Canonical URL per page

- index.html → `https://slingshotsim.org/`
- about.html → `https://slingshotsim.org/about.html`
- educators.html → `https://slingshotsim.org/educators.html`
- how-to-play.html → `https://slingshotsim.org/how-to-play.html`
- uk-ecosystem.html → `https://slingshotsim.org/uk-ecosystem.html`
- classroom.html → `https://slingshotsim.org/classroom.html`
- screenshots.html → `https://slingshotsim.org/screenshots.html`
- accessibility.html → `https://slingshotsim.org/accessibility.html`
- security.html → `https://slingshotsim.org/security.html`
- play/index.html → `https://slingshotsim.org/play/`

## og:image

Set `SOCIAL-IMAGE` to a real image on the site (the Slingshot logo, or a purpose-made 1200×630 card). If there is no suitable hosted image yet, omit the two image lines rather than point at a missing file.
