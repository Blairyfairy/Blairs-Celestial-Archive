# The Celestial Archive — by Blair Page

An interactive, responsive celestial portfolio universe with eight discoverable worlds. Purple / pink brand identity, animated starfield, orbiting planets, celestial lighting, interactive navigation, skill details, and links to the existing Blair Page portfolio.

## GitHub Pages: deploy without building

1. Create a repository named `Blair-Celestial-Archive`.
2. Upload **the contents of this ZIP**, not the enclosing folder, to the repository root (`index.html` must appear at the top level).
3. Open **Settings → Pages**.
4. Set **Source: Deploy from a branch**, **Branch: main**, **Folder: /(root)**, then Save.
5. Visit `https://blairyfairy.github.io/Blair-Celestial-Archive/` once Pages finishes publishing.

No Node.js, Next.js, React, npm, external APIs, CDN or GitHub Actions required. The celestial scene is a native Canvas rendering of 3D-projected worlds, designed to keep working when WebGL/CDNs are blocked. It is **not** a React Three Fiber or Next.js build. It prioritizes a working GitHub Pages experience.

## Features
- Mouse/touch drag to orbit; mouse wheel zoom; clickable worlds.
- Eight worlds with career details, skills, and real portfolio/project links.
- Directory search, pause motion, optional synthesized ambient audio, keyboard-accessible navigation.
- Mobile layout and reduced-motion support.
- Original branding images provided by Blair Page; portrait used in site.

## Files
- `index.html` — page and UI
- `style.css` — responsive Blair Page brand theme
- `app.js` — native celestial scene, interactions, portfolio content
- `assets/portrait.jpg` — branded portrait
- `assets/brand-banner.jpg` — supplied banner artwork
- `assets/favicon.svg` — custom purple celestial star
- `worlds.json` — structured data mirror for future extensions

© 2026 Blair Page. By Blair Page.
