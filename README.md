# Tennissaiten Bespannung – Webseite

A simple one-page website for a local tennis racket stringing service in Schulzendorf.
Bilingual (German first, English subtext). No build tools — just edit the files and publish.

## Files

- `index.html` — all the text and content. Look for `<!-- EDIT HERE -->` comments.
- `style.css` — the design (colors, layout). Optional to touch.
- `README.md` — this file.

## What to edit before publishing

Open `index.html` and find every `<!-- EDIT HERE -->` marker:

1. **WhatsApp number** (appears twice — hero and footer).
   Replace `49 152 02514940` with your number: country code + number, no `+`, no spaces.
   Example: for `+49 151 2345678` you write `491512345678`.
2. **Business / display name** — the big `<h1>` at the top.
3. **Prices** — the table rows. Replace each `XX €` with your price. Add or delete rows freely.
4. **Turnaround time** — currently "24–48 Stunden".
5. **About text** — one or two lines about you.

To change colors, edit the values at the top of `style.css` (the `:root` block).

## How to publish for free with GitHub Pages

1. Create a new repository on GitHub, e.g. `tennis-stringing` (make it **Public**).
2. Upload `index.html`, `style.css`, and `README.md` to the repo
   (drag-and-drop via "Add file" → "Upload files", then commit).
3. Go to the repo's **Settings → Pages**.
4. Under "Build and deployment", set **Source** to "Deploy from a branch".
5. Choose branch **main** and folder **/ (root)**, then **Save**.
6. Wait ~1 minute. Your site will be live at:
   `https://YOURUSERNAME.github.io/tennis-stringing/`

Any time you edit a file in the repo and commit, the live site updates automatically.

## QR code for your flyer

Once the site is live, generate a free QR code pointing to your URL
(search "QR code generator", paste your GitHub Pages link) and print it on cards
you pin at local tennis clubs.
