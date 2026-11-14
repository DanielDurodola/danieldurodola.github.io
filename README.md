# DanielDurodola.github.io
# Daniel Durodola

Personal site of Daniel Durodola, physics undergraduate at the University of Lagos, working on computational physics and N-body simulation. Static: one HTML file, one photo, no build step and no dependencies.

```
index.html      the whole site (styles and structured data inline)
photo.jpg       profile photo
.nojekyll       tells GitHub Pages to serve the files as-is
README.md       this file
```

## Publish to GitHub Pages

On GitHub, create a public repository named exactly `DanielDurodola.github.io` under the `DanielDurodola` account. Upload the files above. The site goes live at https://danieldurodola.github.io/ within a minute or two.

For a user site, GitHub Pages turns itself on automatically from the default branch. If the site hasn't appeared after five minutes, check that **Settings → Pages** shows "Deploy from a branch", branch `main`, folder `/ (root)`.

## Updating it later

Open `index.html` on GitHub, tap the pencil icon, make the change, and tap **Commit changes**. The site refreshes in a minute or two.

## Editing notes

- **Colours and fonts** are in the `<style>` block at the top of `index.html`.
- **Profile photo:** replace `photo.jpg` with a square image. Keep the same file name, or update both places that mention it (the `<img>` tag and the `image` field in the structured data).
- **Links:** the "Find me online" list and the `sameAs` list in the structured data should always match. Add a new profile to both.
- **Structured data:** the `application/ld+json` block tells Google who the page is about (name, university, profiles). Keep the name identical to every other profile.
- **CV:** add a file named `cv.pdf` to the repository and link it from the page.

## Elsewhere

- GitHub: https://github.com/DanielDurodola
- LinkedIn: https://www.linkedin.com/in/daniel-durodola-98581839b
- ORCID: https://orcid.org/0009-0009-7171-4901
