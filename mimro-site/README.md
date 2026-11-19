# Mimro.org

Static website for Mimro (HTML and CSS only, no scripts, no PHP).

## Files
- `index.html` the home page
- `about.html` motto, vision and mission
- `resources.html` list of books and study material (PDF links to be added)
- `activities.html` seminars, farming, meetings and outreach (photos to be added)
- `style.css` all styling
- `404.html` shown for missing pages
- `CNAME` tells GitHub Pages to serve this repo at mimro.org
- `.nojekyll` stops GitHub from processing the files

## Deploy on GitHub Pages
1. Upload all files to the root of the `main` branch.
2. Settings > Pages: Source = Deploy from a branch, Branch = main, Folder = / (root).
3. Custom domain = mimro.org, then tick Enforce HTTPS.
4. Add the DNS records at the domain registrar (see GitHub's Pages docs).

## Security checklist
- Two-factor authentication on GitHub and the domain registrar.
- Never add `.php` files or copy files straight from old backups or archives.
- Review every pull request or change before merging to `main`.

## Syriac font
The site asks for the Serto Jerusalem font. To show it to every visitor, place the font file in `fonts/` (see `fonts/README.txt`). Without it, devices that don't have the font fall back to another Serto-style or Syriac font.
