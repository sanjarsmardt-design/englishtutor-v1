# Fun English for Kids — Ra'no Turg'unova

Responsive static website for an English grammar and speaking tutor in Chilonzor, Tashkent.

## Important: images are embedded in the HTML
Both Tashkent photographs are embedded directly in `index.html`. This avoids broken image paths if you accidentally upload the HTML without the `assets` folder. The original image files are also included in `assets/`.

## Preview locally
Extract the ZIP and open `index.html` in a browser.

## Publish with GitHub + Vercel
1. Extract the ZIP.
2. Create a GitHub repository, e.g. `fun-english-for-kids`.
3. Upload `index.html`, `styles.css`, `script.js`, `README.md`, and the `assets` folder. Keep the folder structure intact (the embedded images will still work even if the assets folder is missed).
4. If a previous version is deployed, make sure the updated `index.html` is committed to GitHub. In Vercel, open the project and choose **Deployments → Redeploy** (or push a new commit).
5. Vercel deploys this static site without a build command. Open the public `*.vercel.app` URL.
6. Later, connect your custom domain in **Project → Settings → Domains** and follow Vercel's DNS instructions.

Google Fonts may load from the internet; images do not depend on external image services.
