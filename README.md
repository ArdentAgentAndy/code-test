# A Little Surprise

A tiny birthday page: tap the present, confetti explodes, and a drawing + message reveal underneath.

## Adding the real drawing

Right now the reveal shows a placeholder ("a drawing is on its way"). To swap in the real artwork:

1. Save the image as `drawing.jpg` in this same folder (next to `index.html`).
   - If it's a `.png` instead, rename it to `drawing.jpg`, or edit the `src="drawing.jpg"` in `index.html` to match your file's extension.
2. Commit and push — GitHub Pages will redeploy automatically within a minute or two.

## Local preview

Just open `index.html` in a browser, or run a tiny local server:

```
cd code-test
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.
