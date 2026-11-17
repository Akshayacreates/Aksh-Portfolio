# Akshaya · Creative Portfolio

This folder is ready to publish with **GitHub Pages**.

## Files
- `index.html` — the website
- `assets/` — 30 images and QR-code images extracted from the supplied HTML
- `.nojekyll` — tells GitHub Pages not to run Jekyll processing

## Publish on GitHub Pages
1. Create a new GitHub repository (for example, `akshaya-portfolio`).
2. Upload **all contents of this folder** to the repository root. Make sure `index.html` is at the root, not inside another folder.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/(root)`, then click **Save**.
6. Wait for GitHub Pages to publish and open the website URL shown on that Pages screen.

## Important notes
- The 30 image assets are included locally, so they do not depend on the original chat session.
- The website loads Three.js and Google Fonts from their public CDNs, so visitors need an internet connection.
- The supplied HTML referred to 8 video files using private `/_blob/...` paths, but those video files were not included in the upload. Their cards now show a clear placeholder instead of a broken player. To restore them, add the original video files to `assets/` and update the corresponding `VID`, `VIDH`, `VIDK`, and `VID4` paths in `index.html` to `assets/your-video.mp4` (or `.webm`).
- Open `index.html` through GitHub Pages after publishing. You can also test it locally with a simple local web server; some browsers restrict WebGL or media behavior when opening files directly.
