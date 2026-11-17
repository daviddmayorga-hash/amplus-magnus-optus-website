# AMO Consulting — GitHub Pages website

Single-page static site. No build process or dependencies required.

## Deploy
1. Create a public GitHub repository, e.g. `amo-website`.
2. Upload `index.html`, `styles.css`, `script.js`, and the `assets/` folder to the repository root.
3. Open repository **Settings → Pages → Build and deployment**; select **Deploy from a branch**, branch `main`, folder `/ (root)`; save.
4. Wait for the GitHub Pages URL to become available and test it.
5. In **Settings → Pages → Custom domain**, enter `amo.business`.
6. At your DNS provider, add apex `A` records for GitHub Pages: `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`. Remove conflicting apex A/AAAA records. Optional `www` CNAME → `<your-github-username>.github.io`.
7. Once DNS and certificate provision, enable **Enforce HTTPS**. Test `https://amo.business` and `https://www.amo.business` if configured.

## Before launch
- **Confirm inquiry email**. The `mailto:` link currently uses `info@amplusmagnusoptus.com` as an UNVERIFIED placeholder; replace with the correct address. The page visibly flags this.
- Replace the future-content placeholders in Perspectives when podcasts/articles exist.
- Review positioning and legal language.
- Optionally add analytics and a form service (static GitHub Pages cannot process forms itself).

## Edit
Text and metadata: `index.html`; colors and spacing: `styles.css`; mobile menu: `script.js`; logo: `assets/amo-logo.png`.

## Brand naming
Use **AMO Consulting** for the public-facing brand. The full legal name **Amplus Magnus Optus LLC** remains in the footer and structured metadata.
