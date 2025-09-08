# petroulak.github.io

This repository hosts the static mirror of https://chatgpt19.godaddysites.com for GitHub Pages.

- Fully local assets: images, fonts, and scripts are vendored under `img1.wsimg.com/`.
- No Jekyll processing: `.nojekyll` prevents Jekyll from altering paths.

Local preview:

- `python3 -m http.server --directory . 8000`
- Open http://localhost:8000

Deploy:

1. Create a public repo named `petroulak.github.io` on GitHub.
2. Push these contents to the `main` branch.
3. GitHub Pages will serve https://petroulak.github.io automatically.

Notes:
- External links (Google Drive, social sites, etc.) remain external by design.
- Some GoDaddy builder scripts reference dynamic resources; we’ve pointed them to local copies when possible.
