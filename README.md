# RETME Website — GitHub Pages

## Upload correctly
This ZIP is structured so that the website files are at the repository root.
1. Download and extract this ZIP.
2. Open the extracted folder.
3. Upload **the contents of this folder** (index.html, catalogue.html, product.html, styles.css, main.js, products.js, assets/) directly into the root of your GitHub repository.
4. Do not upload the outer folder as a nested directory.
5. In GitHub: Settings → Pages → Deploy from a branch → `main` → `/(root)` → Save.

Your repository root should look like:
- index.html
- catalogue.html
- product.html
- styles.css
- main.js
- products.js
- assets/
  - retme-logo.png
  - products/

## Contact details configured
- Phone / WhatsApp: +91 80978 31025
- Email: retmebath@gmail.com
- Instagram: https://www.instagram.com/retme.bath/

## Image troubleshooting
All image references use relative paths beginning with `./assets/`. Keep the `assets` folder in the same repository root as `index.html`. GitHub Pages is case-sensitive: do not rename `assets`, image files, or folders using different capitalisation. Upload the complete `assets` folder and its subfolders, preserving their names.

If images still do not load:
- Open the published site, right-click a broken image and choose "Open image in new tab".
- Check that the resulting URL ends in the exact path and filename that exists in the repository.
- Confirm the `assets/` folder is committed to the `main` branch, not just present on your computer.
- After uploading, allow GitHub Pages a minute or two to redeploy, then hard-refresh with Ctrl+Shift+R.

## Add a product
Add its image inside `assets/products/`, then add a product object to `products.js`. Use an image path beginning `./assets/products/your-image.jpg`.
