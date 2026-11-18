# fabiscionti.github.io

Personal website of Fabiana Scionti. Plain HTML and CSS, no build step, hosted on GitHub Pages.

## Files

- `index.html` – the home page (About, Experience, Writing, Contact)
- `styles.css` – all styling (colors live at the top under `:root`)
- `writing/` – one HTML file per post

## Preview locally

Double-click `index.html` to open it in your browser, or run:

```bash
python3 -m http.server 8000
```

and open http://localhost:8000.

## Publish a change

```bash
git add -A
git commit -m "Describe the change"
git push
```

GitHub Pages redeploys automatically within a minute or two.
