# Laxmi Khata

## Use on this laptop

Open `Laxmi Khata.url`, then copy that shortcut to your Desktop or pin it to the Start menu. Your data stays in this browser on this laptop.

## Use on iPhone

Publish the `expense-tracker` folder to a secure (`https`) static website. Open its URL in Safari, tap Share, then choose **Add to Home Screen**. The saved icon opens Laxmi Khata directly and supports offline use after the first visit.

## Future changes

The whole app is contained in `index.html`, with `manifest.webmanifest`, `sw.js`, and `icon.svg` alongside it. Make changes in this folder and publish the updated files to the same site; the app checks for the new version the next time it is opened online.

For a stable link and easy future updates, GitHub Pages is the recommended host: keep this folder in a repository and publish the repository’s main branch through Pages. Cloudflare Pages or Netlify work equally well if preferred.
