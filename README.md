# Ben’s academic website

A static portfolio for Hongfa “Ben” Xue. No installation or build step is needed.

## Publish on GitHub Pages

1. Create a repository named `ben-website` (or use `YOUR-USERNAME.github.io` for an account-level website).
2. Upload the contents of this folder to the repository root, including `index.html`, `style.css`, and `favicon.svg`. Do not upload the ZIP itself.
3. In Settings → Pages, choose **Deploy from a branch**.
4. Select **main** and **/(root)**, then Save.
5. GitHub will display the website address in the Pages settings once publishing finishes.

## Edit directly on GitHub

- Open **index.html** and select the pencil icon to change the page text. Section comments mark the bio, research, publications, experience, education, and contact sections.
- Open **style.css** to change colors, fonts, spacing, and layout.
- Select **Commit changes** to save. Changes on the publishing branch trigger a site update.
- Edit the words between HTML tags while keeping the tags intact. Use `&amp;` for an ampersand.
- To add a publication, copy one complete `<article class="paper">...</article>` block, then change its title, authors, venue, year, summary, and both publication links.
- To change the photo, replace `headshot.jpg` with another photo using the same filename.
- To update the downloadable CV, replace `cv.pdf` with the new PDF using the same filename.
- LinkedIn and Google Scholar links are in the profile-links section.
- Personal interests are in the About section.
- Roboto is loaded from Google Fonts, with Aptos and Arial as fallbacks.

## Review before publishing

Ben should review the biography, research interests, job dates, publication metadata, and email. The page contains his professional email. The supplied downloadable CV is included unchanged and contains his address and phone number.

## Files

- `index.html`: page text and structure
- `style.css`: appearance and responsive layout
- `favicon.svg`: browser tab icon
- `.nojekyll`: serves the files without Jekyll processing

GitHub documentation: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

- `headshot.jpg`: Ben’s profile photo
- `cv.pdf`: downloadable academic CV
