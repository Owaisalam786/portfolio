# Owais Alam — Cinematic Developer Portfolio

A responsive, dark-first personal portfolio for Python development, data analytics, projects, learning resources, and certificates. The hero includes a lazily loaded Three.js sculpture with a CSS fallback; the rest of the site uses lightweight HTML, CSS, and vanilla JavaScript.

## Run locally

No package installation or build step is required.

1. Clone the repository:
   ```bash
   git clone https://github.com/Owaisalam786/portfolio.git
   ```
2. Open the folder in VS Code.
3. Open `index.html` in a browser, or use the VS Code Live Server extension.

The 3D hero imports Three.js from jsDelivr when it approaches the viewport, so the 3D effect needs an internet connection. If WebGL or the CDN is unavailable, the CSS orb remains as a fallback.

## Publish with GitHub Pages

1. Open [Repository Pages settings](https://github.com/Owaisalam786/portfolio/settings/pages).
2. Under **Build and deployment**, select **Deploy from a branch**.
3. Select branch `main` and folder `/(root)`, then click **Save**.
4. Wait for the deployment to complete and use the live URL shown in Pages settings.

## Features

- Cinematic dark interface with blue, violet, and cyan accents
- Interactive Three.js hero sculpture, loaded lazily with a CSS fallback
- Responsive About, Skills, Projects, Learning Resources, Certificates, Contact, and Footer sections
- Dark/light theme toggle and responsive mobile navigation
- Active section navigation and scroll progress indicator
- Subtle pointer-driven project card tilt
- Keyboard focus states and `prefers-reduced-motion` support
- Metadata for search and social sharing
- No framework or build step required

## Keep portfolio details authentic

- Project ideas are labeled as ideas, not completed work. Replace them only with real repositories, demos, and verified details.
- Skills are presented as learning areas; update them as practical experience grows.
- The Certificates section links to [Owaisalam786/certificates](https://github.com/Owaisalam786/certificates). Ensure that repository is public and contains the intended certificate files.
- Add LinkedIn and email links only after confirming the correct public profile/address.

## Main file

The portfolio is intentionally maintained in `index.html` for straightforward editing and GitHub Pages deployment.
