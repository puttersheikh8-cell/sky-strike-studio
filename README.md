# Sky Strike Studio — Static Website

Ready for GitHub Pages and custom domain `skystrikestudio.site`.

## Upload
1. Extract ZIP. Upload **the contents** of this folder to the root of a GitHub repository (not the ZIP itself and not an extra enclosing folder).
2. Repository Settings → Pages → Deploy from a branch → main → /(root) → Save.
3. Settings → Pages → Custom domain: `skystrikestudio.site`.
4. Configure domain DNS with the GitHub Pages A records and `www` CNAME for **your actual GitHub username**. Check GitHub's current documentation.
5. Wait for DNS verification, then enable Enforce HTTPS.

## Pages
- `/` Home
- `/about/` About Us
- `/privacypolicy/` Privacy Policy
- `/contact/` Contact Us

## Important before launch
- `contact@skystrikestudio.site` is a **placeholder** until you create and verify this mailbox. Replace it if your business email differs.
- Review and adapt the privacy policy to reflect your actual data practices, especially if you add analytics or use this for game-specific policies.
- This site uses Google Fonts (third-party font requests). Remove the `@import` in `assets/style.css` if you prefer system fonts only.
- Keep the paths and filenames as provided.
