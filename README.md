# Alejandro García Vegas — Personal CV / Portfolio

Static, single-page portfolio built with plain HTML and CSS. Ready to deploy on GitHub Pages, Netlify, Vercel, or any static host.

## Structure

```
cv-web/
├── index.html      # Main page
├── style.css       # All styles
└── README.md       # This file
```

## Local preview

Open `index.html` directly in your browser, or serve it with a tiny local server:

```bash
cd cv-web
python3 -m http.server 8000
# then open http://localhost:8000
```

## Deploy on GitHub Pages

1. Create a new GitHub repository named `agvegas.github.io` (replace `agvegas` with your GitHub username).
2. Push these files to the `main` branch:

   ```bash
   cd cv-web
   git init
   git add .
   git commit -m "Initial portfolio"
   git branch -M main
   git remote add origin git@github.com:agvegas/agvegas.github.io.git
   git push -u origin main
   ```

3. In the repo, go to **Settings → Pages** and make sure the source is `main` branch / root.
4. After a minute, your site will be live at `https://agvegas.github.io/`.

## Deploy on Netlify (drag & drop, no Git)

1. Go to [https://app.netlify.com/drop](https://app.netlify.com/drop).
2. Drag the `cv-web` folder onto the page.
3. Done — you'll get a random `https://xxx.netlify.app` URL.

## Custom domain

Once deployed, you can attach a custom domain (e.g. `alejandrogv.com`) from your DNS provider / GitHub Pages settings.

## Editing

- Content lives in `index.html`.
- Visual tweaks live in `style.css` (CSS variables at the top: colors, radius, max width).
