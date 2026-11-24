# Jayesh — Digital Marketing Portfolio

A responsive, multi-page portfolio built with plain HTML, CSS and JavaScript. It is designed for GitHub Pages and does not require a framework, build step, paid hosting or backend.

## Pages included

- `index.html` — homepage and featured project highlights
- `about.html` — introduction and approach
- `projects.html` — featured Netzwerk Academy case studies and other projects
- `case-study-tracking.html` — conversion tracking and analytics case study
- `case-study-campaign.html` — two-month campaign case study
- `skills.html` — skills and tools
- `contact.html` — contact information
- `404.html` — not-found page

## Before publishing — personal details to update

1. **Name:** Search for `Jayesh` in the HTML files and replace it with the name you want displayed.
2. **Email:** In `contact.html`, replace `YOUR_EMAIL@example.com` with your real email address in both the visible link and the `mailto:` links.
3. **LinkedIn:** In `contact.html`, replace `YOUR-LINKEDIN` with your LinkedIn profile slug and URL.
4. **Profile photo:** The homepage currently uses a typographic avatar (`J`) so it looks finished even without a photo. If you want a photo, add it under `assets/img/` and replace the `.avatar` block in `index.html` with an `<img>` element; keep descriptive alt text.
5. **Evidence and results:** Add approved screenshots, exact campaign dates, budget, lead counts, cost figures and verified outcomes only when you have source evidence and permission to share it.
6. **Case-study status:** The two Netzwerk Academy pages are written as practical case studies/frameworks. Before claiming that changes were deployed on a live client account, confirm the work was actually implemented and add supporting evidence. Do not present hypothetical or practice results as real campaign results.

## Publish on GitHub Pages

1. Create a new public repository on GitHub, for example `jayesh-portfolio`.
2. Upload **the contents of this folder** (the HTML files and the `assets` folder) to the repository root. Do not upload the parent folder as an extra nested directory.
3. Open the repository's **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then save.
6. Wait for GitHub Pages to publish the site and open the URL displayed in Settings → Pages.

## Test locally

For a local preview, open a terminal in this folder and run:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000` in your browser. You can also open the HTML files directly, but using a local server is a better preview of a hosted static site.

## Design and technical notes

- Soft sage, muted teal, mist blue and warm-neutral palette; no light/dark mode toggle.
- Responsive navigation and layouts for mobile, tablet and desktop.
- No external JavaScript libraries or build tools.
- Includes keyboard skip link, labelled mobile menu, reduced-motion support and basic page descriptions.
- The contact links are placeholders until you add your real contact details.
- GitHub Pages is static hosting: the site does not send contact-form data or store visitor submissions.
