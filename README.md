# Nupur Patil — SAP Fiori / UI5 / BTP Portfolio

A responsive, interactive, static portfolio designed for GitHub Pages. It uses plain HTML, CSS and JavaScript—no build process, npm install or backend required.

## Preview locally
Open `index.html` in a browser. For best behavior, use a local static server or GitHub Pages. Theme preference is saved in the browser's local storage.

## Publish on GitHub Pages
1. Create a repository, for example `nupurpatil.github.io` for a user site, or any repository name for a project site.
2. Upload `index.html`, `README.md`, and the `assets/` directory to the repository root.
3. In the repository, open **Settings → Pages**.
4. Under build and deployment, select **Deploy from a branch**, choose the default branch (usually `main`) and folder `/ (root)`, then save.
5. Wait for the published URL shown in the Pages settings.

Official guide: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site

## Add project screenshots permanently
The screenshot upload controls in the website are temporary browser previews only. They do not upload files to GitHub. To publish an image:
1. Put an approved, sanitized screenshot in `assets/projects/`, e.g. `stocklist-dashboard.png`.
2. In `index.html`, find the relevant project image container such as `id="image-stocklist"`.
3. Replace the placeholder artwork with:
   `<img src="assets/projects/stocklist-dashboard.png" alt="Stocklist Fiori application screenshot">`
4. Commit and push the change.

Do not publish employer/client confidential data, internal system URLs, customer or employee information, access tokens, credentials, or screenshots that you are not authorized to share. Use synthetic or redacted data.

## Customize before sharing with recruiters
- Check the employment dates and exact years of experience.
- Update project summaries to distinguish delivered work from POCs and planned learning projects.
- Adjust skill labels to reflect your real hands-on level.
- Add a PDF resume link only after adding your resume PDF to the repository (for example `assets/Nupur-Patil-Resume.pdf`) and adding a link in the hero section.
- Add a LinkedIn/GitHub profile link if you want it public.
- The CDS snippets are illustrative examples for learning and must be validated for your ABAP release, CDS model type and authorization design.

## Included interactions
- Responsive mobile navigation
- Light/dark theme toggle
- Scroll reveal animations
- Skill category filters
- Searchable and filterable project cards
- Local screenshot preview
- Switchable CDS code snippets and copy-to-clipboard
- Email copy action
