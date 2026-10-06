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
and a command palette (`Cmd/Ctrl+K`). The hero contains a miniature developer
workspace: a laptop terminal connected to data, agent, and API modules, built
with inline SVG and CSS 3D transforms. Drag with a mouse to rotate both axes;
horizontal touch gestures rotate while vertical swipes scroll the page.
Arrow keys rotate the focused illustration, and Home or “Reset view” restores
the starting angle. The view stays where you leave it.

Decorative motion stops offscreen or in a hidden tab and follows both the pause
control and the device's reduced-motion setting. Direct rotation still works
with motion disabled. No external 3D library is required. The expandable action
preview below the illustration is a simulation with no backend connection.

The résumé is embedded once as a base64 data URL in the contact download link.
When changing the PDF, update both that embedded copy and `GauravRuhelaCV.pdf`.

## Live site

[Open the portfolio](https://gauravruhela07.github.io/portfolio/).

GitHub Pages publishes the `main` branch from `/(root)` after each commit.
The site needs no build command. Its canonical and social preview metadata point
to the live Pages URL and the included `og-image.png`.

## Fonts

Space Grotesk and IBM Plex Mono are embedded under the SIL Open Font License.
Their license notices are included in `index.html`.
