# Swing Theory website

Static marketing, support, and privacy pages for the native iPhone game. This folder is its own Git repository, excluded from the parent app repository.

- `index.html`: gameplay, controls, features, native screenshot.
- `privacy.html`: app data practices, local scores/preferences, support correspondence, website hosting.
- `support.html`: contact information and practical game FAQs.
- `assets/`: local CSS, original icon, actual native app capture. No external runtime scripts or fonts.

Open `index.html` to preview locally. To host on GitHub Pages, push this repository to a GitHub repository and enable Pages for the root of the `main` branch. The `.nojekyll` file keeps this a plain static site. All internal paths are relative, so project Pages hosting works without edits.

After deployment, enter the public root, `support.html`, and `privacy.html` URLs in App Store Connect. Once the game has a public App Store URL, add its real link to the home page; the site does not currently claim the app is publicly released.

Contact: debuggersociety@zohomail.com. The website has no analytics or ads. Its future hosting provider may process request metadata as described in the privacy page.
