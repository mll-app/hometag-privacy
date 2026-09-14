# HomeTag Website

Public, static site for the HomeTag app — hosted via GitHub Pages, no build step. Intentionally contains only these pages, separate from the app's own source code, which stays private elsewhere.

## Pages

| Page | URL | Used for |
|---|---|---|
| Marketing / landing | https://mll-app.github.io/hometag-privacy/ | App Store Connect "Marketing URL" |
| Support | https://mll-app.github.io/hometag-privacy/support.html | App Store Connect "Support URL" |
| Privacy policy | https://mll-app.github.io/hometag-privacy/privacy.html | App Store Connect "Privacy Policy URL" |

All three share `style.css` and `icon.png`, and a language toggle (Chinese/English) whose choice persists across pages via `localStorage`.

## Updating

Edit the relevant `.html` file and push to `main`; GitHub Pages redeploys automatically within a minute or two.
