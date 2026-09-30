# Morning Pages Legal & Support

Static legal and support pages for Morning Pages, ready for GitHub Pages.

## Structure

- `index.html`: legal and support directory
- `privacy/index.html`: Privacy Policy
- `terms/index.html`: Terms of Service
- `account-deletion/index.html`: account and local-data deletion instructions
- `support/index.html`: support page
- `styles.css`: shared Morning Pages presentation and responsive layout
- `script.js`: current-year enhancement
- `.nojekyll`: serves the site directly through GitHub Pages

All internal links are relative, so the site works at a repository subpath or a custom domain.

## Preview locally

From this directory:

```bash
python -m http.server 4173
```

Then open `http://127.0.0.1:4173`.

## Publish with GitHub Pages

Push the contents of this directory to the publishing repository. In the repository settings, open **Pages**, select **Deploy from a branch**, then choose the publishing branch and the root folder.

When app behavior or legal terms change, update the relevant page and its effective date.
