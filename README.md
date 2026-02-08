# WeAntz Site

A simple, static site for **Know Your Rights** information and trusted local resources.

## Pages
- Home: `index.html`
- Know Your Rights: `know-your-rights.html`
- Peaceful Action: `peaceful-action.html`
- States directory: `states.html`
- Support: `support.html`

## Global Navigation Header
This site uses a shared navigation header styled by `nav.css`.

### Add to every HTML page (root pages)
1. In `<head>`:
```html
<link rel="stylesheet" href="nav.css">
```
2. Immediately after `<body>`:
Paste the navigation header markup (see `INSTALL.txt`).

### States pages (inside `/states/`)
Use `../nav.css` and `../` links.

## Development
Open the HTML files directly, or serve locally:
- `python3 -m http.server`

