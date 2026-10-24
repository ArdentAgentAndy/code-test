# A Little Surprise

A tiny birthday page: tap the present, confetti and fireworks explode, and a drawing + poem burst out from it to the top of the page.

## Adding the real drawing

Right now the reveal shows a placeholder ("a drawing is on its way"). To swap in the real artwork:

1. Save the image as `drawing.jpg` in this same folder (next to `index.html`).
   - If it's a `.png` instead, rename it to `drawing.jpg`, or edit the `src="drawing.jpg"` in `index.html` to match your file's extension.
2. Commit and push — GitHub Pages will redeploy automatically within a minute or two.

## Swapping in the real poem

The poem section currently shows a placeholder classical Chinese quatrain (杜牧's 清明) so you can see the layout. To swap in your own 4-line, 7-character poem, edit the `<div class="poem" id="poem">` block in `index.html` — replace the text inside each `<p class="poem-line">...</p>` (one line per `<p>`).

## Local preview

Just open `index.html` in a browser, or run a tiny local server:

```
cd code-test
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.
