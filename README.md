# Frijolito Labs site

Support and privacy pages for all three apps, published free with GitHub Pages at **https://frijolitolabs.github.io**.
Support email: frijolitolabs@gmail.com (also set in each app's `ios/project.yml`).

| App | Support URL | Privacy policy URL |
|---|---|---|
| Lotería Mexicana: Cantor | https://frijolitolabs.github.io/loteria/ | https://frijolitolabs.github.io/loteria/#privacy |
| Anytrack | https://frijolitolabs.github.io/anytrack/ | https://frijolitolabs.github.io/anytrack/#privacy |
| Bower | https://frijolitolabs.github.io/bower/ | https://frijolitolabs.github.io/bower/#privacy |

## Publish (first time)
1. Signed in to GitHub as `frijolitolabs`, create a **public** repository named exactly `frijolitolabs.github.io`
   (github.com/new; no README, no licence). A repo with that name is served at the root URL automatically.
2. From this folder: `git push -u origin main` (the remote is already set). GitHub asks you to sign in the first time.
3. Wait a minute, then open https://frijolitolabs.github.io. Settings → Pages shows the deploy status.

## Update
Edit, then `git commit -am "…" && git push`. Plain HTML and one stylesheet: no build step, no scripts, no trackers.
