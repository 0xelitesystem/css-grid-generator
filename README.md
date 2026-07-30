# CSS Grid Generator

A visual CSS Grid builder. Set columns, rows, track sizes, and gaps, preview the grid live, name a few areas, and copy the generated CSS. No server, no tracking, no third-party scripts.

**Live demo:** https://0xelitesystem.github.io/css-grid-generator/

## Use

Open `index.html` in any modern browser, or visit the GitHub Pages link in the repo description.

- Set the number of columns and rows.
- Size each track with `fr`, `px`, `%`, `em`, `rem`, `auto`, `min-content`, or `max-content`.
- Set the column and row gaps in pixels.
- Watch the live preview update as you type.
- Optionally tick "Name and place grid areas" to add named rectangular areas. Each area spans a range of columns and rows.
- Copy the generated `display: grid` rule with the Copy button.

Invalid area setups (missing names, invalid identifiers, duplicates, or overlaps) show a clear inline error, and the preview falls back to a plain numbered grid so the page never breaks.

## Why this exists

Grid template syntax is easy to forget and tedious to hand-write, especially `grid-template-areas`. This gives you a quick visual way to shape a grid and get correct, copy-ready CSS, all in a single file with no dependencies.

## Privacy

Everything runs in your browser. Nothing you enter is uploaded. Verify by viewing the page source or by opening DevTools and watching the network tab, no requests are made.

## Run locally

```bash
git clone https://github.com/0xelitesystem/css-grid-generator
cd css-grid-generator
# Open index.html in your browser, or:
python -m http.server 8000
```

## Build

There is no build. It is a single HTML file.

## More

Part of a catalog of single-file browser tools and plain-language references, all MIT licensed and dependency-free: [0xelitesystem.github.io](https://0xelitesystem.github.io/). Built by [elitesystem.ai](https://elitesystem.ai).

## License

MIT.

## Related

- [gradient-generator](https://github.com/0xelitesystem/gradient-generator), build CSS gradients visually
- [meta-og-tag-generator](https://github.com/0xelitesystem/meta-og-tag-generator), generate Open Graph and meta tags
- [json-to-typescript](https://github.com/0xelitesystem/json-to-typescript), turn JSON into TypeScript types
