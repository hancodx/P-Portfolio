# Hind Sameut — Research Portfolio

A simple, fast, dependency-free portfolio site (HTML, CSS, vanilla JS), written in English and oriented toward PhD applications. It works on GitHub Pages with no build step.

## Structure

```
index.html                       Page content (all sections)
css/style.css                    Styles, light and dark themes
js/main.js                       Theme toggle, mobile menu, scroll effects
assets/favicon.svg               Site icon
files/Hind_Sameut_CV_Research.pdf  CV linked from the "Download CV" buttons
.nojekyll                        Tells GitHub Pages to serve files as-is
```

## Deploy on GitHub Pages

**Option A — new repository (recommended, keeps your old site intact)**

1. Create a new public repository on GitHub, for example `phd-portfolio`.
2. Upload the contents of this folder (not the folder itself) to the repository root, so that `index.html` sits at the top level.
3. Go to **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, select the `main` branch and the `/ (root)` folder, then save.
4. After a minute the site is live at `https://hancodx.github.io/phd-portfolio/`.

**Option B — replace the current site**

Upload these files into the existing `portfolio-website` repository, overwriting `index.html`. The address stays `https://hancodx.github.io/portfolio-website/`. Keep a copy of the old files first if you want to go back.

**Option C — user site**

Name the repository `hancodx.github.io` and the site is served at `https://hancodx.github.io/`.

## Customize

- **Text:** edit `index.html`. Each section is marked with a comment.
- **Publications:** a ready-to-use block is commented out in the "Research projects" section. Uncomment it and fill it in when a paper or report is available.
- **CV:** replace `files/Hind_Sameut_CV_Research.pdf` with a newer version, keeping the same file name.
- **Colors:** change the variables at the top of `css/style.css` (`--accent` is the main color).
