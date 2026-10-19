# Languagly website

The website for **Languagly**, a Mac menu-bar app that translates Thai ↔ English and proofreads
your English, on the device and offline.

**Live at <https://learn57130.github.io/languagly-site/>**

One static page: `index.html` with its styles and script inline, the app icon (`icon.svg`,
`apple-touch-icon.png`), and nothing to build. GitHub Pages serves this branch as it is.

The app's source is not in this repository. Every number on the page comes from the app's own
measurements and carries its date; the example sentences and answers come from its test corpora.

## Preview locally

```bash
python3 -m http.server 8765
```

Then open <http://localhost:8765>.
