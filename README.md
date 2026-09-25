# Skyhook support and legal pages

Static HTML pages for GitHub Pages. No build tools, JavaScript, tracking scripts, or external fonts are needed.

- `index.html` — support/contact page
- `privacy.html` — privacy policy
- `terms.html` — terms of use
- `styles.css` and `assets/` — shared presentation and locally hosted display font

## Publish

1. Upload this folder's contents into the root of a GitHub Pages repository (or a `skyhook` subfolder in your existing website repository). Keep `styles.css` and `assets/` alongside the HTML files. Unzip the provided package before uploading it.
2. For a new repository, open **Settings → Pages → Deploy from a branch**, choose the branch containing the files and **/(root)**, then save. For an existing Pages site, keep its current publishing setup.
3. Open the published site and test its Privacy, Terms and email links.
4. Use the published `privacy.html` address as the App Store privacy-policy URL and `index.html` as the support URL. Share the final addresses so the game can link to them in a later build.

All site links are relative, so the same files work at a domain root or inside a project/subfolder. Do not upload the private Godot project or its `exports` folder to publish these pages.

Developer/contact: Bo Jacobson — bjacobson26@me.com.

The policy describes Skyhook 1.0.0, including production AdMob ads, privacy choices, and the optional one-time Remove Ads purchase. Review and update it whenever data practices change. The Terms supplement Apple's standard app license; this package is not a custom EULA for the App Store license field. A qualified legal professional should review the documents before a public commercial launch.

GitHub publishing reference: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

Limelight is distributed under the SIL Open Font License; see `assets/limelight-OFL.txt`.
