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
workspace: a laptop connected to data, agent, and API modules, built with inline
SVG and CSS 3D transforms. Its four display layers fan apart during dragging.
Hover smoothly tilts the workspace; a quick drag continues with damped inertia,
then settles back into the hover range. Horizontal touch gestures rotate while
vertical swipes scroll. External direction buttons and arrow keys provide a
keyboard alternative; Home or “Reset view” restores the starting angle.

The object uses recognizable symbols and graphical code lines, with readable
descriptions outside the 3D view. The three work areas cycle every 3.5 seconds,
with a rolling phrase, synchronized descriptions and staggered checklist.
Connector lines follow the actual projected positions, and mouse input leaves
a brief dotted trail.

Decorative motion stops offscreen or in a hidden tab and follows both the pause
control and the device's reduced-motion setting. Direct rotation still works
with motion disabled, without fan-out or inertia. No external 3D library is
required. The expandable action
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
