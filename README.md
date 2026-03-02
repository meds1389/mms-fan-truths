# M&M'S Fan Truths — Interactive Exploration

An interactive microsite presenting 11 Fan Truths uncovered through ethnographic consumer research with M&M'S fans.

**Client:** Mars Wrigley Confectionery (M&M'S)  
**Agency:** Bluedog Design  
**Date:** March 2026

## What's Inside

- **Home** — Overview of the three-chapter Fan Truth story (Evoke, Express, Connect)
- **The Truths** — Deep-dive into each of the 11 Fan Truths with consumer quotes and video placeholders
- **Fan Stories** — Video gallery (11 videos, one per truth — coming soon)
- **Appendix** — Methodology, research process, and the Fan Truths framework

## Deployment

This is a self-contained `index.html` file with all dependencies (React 18) bundled inline. No external CDN dependencies. No build step required.

### GitHub Pages

1. Upload `index.html` and `README.md` to the repository root
2. Go to **Settings → Pages**
3. Source: Deploy from branch → `main` → `/ (root)`
4. Save — site will be live at `https://[username].github.io/[repo-name]/`

### Local Preview

Double-click `index.html` to open in any browser.

### Embed in Squarespace or Other Sites

```html
<iframe src="https://[username].github.io/[repo-name]/" width="100%" height="800" style="border:none; border-radius:8px;" allowfullscreen></iframe>
```

## Videos

Video placeholders are labeled `Fan Truth #1` through `Fan Truth #11`. When video files are ready, they can be hosted externally (Box, Vimeo, etc.) and referenced by URL in the source code.

Suggested naming convention for video files:
```
mms-fantruth-01.mp4
mms-fantruth-02.mp4
...
mms-fantruth-11.mp4
```

## Brand Implementation

- **M&M'S branding** (Home, Truths, Stories): Zilla Slab display font, chocolate brown (#3a1f04), candy red (#b11224) accent, warm cream backgrounds
- **Bluedog branding** (Appendix, Footer): Helvetica Neue, Bluedog Blue (#0000F2) accent, clean/corporate

## Technical Details

| Detail | Value |
|--------|-------|
| Bundle size | ~247KB |
| Dependencies | React 18 (bundled inline) |
| External requests | Google Fonts only |
| Build tool | esbuild + Babel CLI |

## Source

The editable source artifact (`fan-truths-microsite.jsx`) lives in the Claude project. To make changes, edit the `.jsx` in Claude, then re-bundle to `index.html` for deployment.

---

*Built by Bluedog Design × Claude*
