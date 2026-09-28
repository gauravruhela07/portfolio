# Gaurav K Ruhela — Portfolio

A single-page portfolio covering backend systems, procurement infrastructure,
and applied AI work.

## Preview

Open `index.html` in a browser, or serve this directory:

```sh
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Files

- `index.html` — complete site, including inline CSS and JavaScript, embedded
  fonts, and an embedded résumé download. No install or build step is required.
- `GauravRuhelaCV.pdf` — standalone résumé download.
- `og-image.png` — 1200 × 630 social-preview image.
- `.nojekyll` — lets GitHub Pages serve the files as plain static assets.

## Editing

Edit `index.html` directly. It is the website source in this repository.

The page supports dark/light themes, reduced-motion preferences, mobile
navigation, an interactive project timeline, source notes for impact numbers,
and a command palette (`Cmd/Ctrl+K`). Its hero demo is a simulation with no
backend connection.

The résumé is embedded once as a base64 data URL in the contact download link.
When changing the PDF, update both that embedded copy and `GauravRuhelaCV.pdf`.

## Deploy

This repository is ready for static hosting on GitHub Pages, Cloudflare Pages,
Netlify, or Vercel. It does not need a build command.

For GitHub Pages, choose **Settings → Pages → Deploy from a branch**, then
select **main** and **/(root)**. For this repository, the default project-site
address would be `https://gauravruhela07.github.io/portfolio/`.
Publishing the repository alone does not enable Pages.

Before publishing, add the final URL to the canonical link and `og:url`,
`og:image`, and `twitter:image` metadata in `index.html`. Use the absolute URL of
`og-image.png`, and change `twitter:card` to `summary_large_image`.

## Fonts

Space Grotesk and IBM Plex Mono are embedded under the SIL Open Font License.
Their license notices are included in `index.html`.
