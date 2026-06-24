# Alexandre Iuri Witczak — Executive Portfolio

Static, responsive executive career portfolio built with HTML, CSS, and vanilla JavaScript.

## Run locally

Open `index.html` directly in a browser. No installation or build step is required.

For a local web server, run one of these commands from the project folder:

```bash
python -m http.server 8000
```

or:

```bash
npx serve .
```

Then open the address shown in the terminal.

## Publish

### GitHub Pages

1. Push the project files to a GitHub repository.
2. Open **Settings → Pages**.
3. Select **Deploy from a branch**, then choose `main` and `/ (root)`.

### Netlify

Drag the project folder into [Netlify Drop](https://app.netlify.com/drop), or connect the GitHub repository. No build command is needed; use the project root as the publish directory.

### Cloudflare Pages

Connect the GitHub repository in Cloudflare Pages. Select a static HTML project, leave the build command blank, and use `/` as the output directory.

## Files

- `index.html` — content, metadata, and page structure
- `styles.css` — visual system and responsive layouts
- `script.js` — mobile navigation, current year, and scroll reveals
- `assets/` — reserved for future local images or documents
