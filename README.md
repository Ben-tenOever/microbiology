# Microbiology Resources

One landing page for every resource shared at the 2026 Department of Microbiology address.
Live at **https://ben-tenoever.github.io/microbiology/**. Pages is published from `main` / root.

The page links to: shared equipment, the department intranet (SharePoint), funding opportunities (`/grants` and its
fellowship pages), the podcast, and the seminar series.

## Adding a resource
Copy one `<article class="card res">` block in `index.html`, change the text, link and id, and add a matching
link to the `<nav>`. Make its QR code with `segno`: `python -c "import segno; segno.make('URL', error='q').save('qr-NAME.svg', scale=10, border=2, dark='#2a1a49')"`.

`qr-hub*.{svg,png}` point to this page. Never change the repo name, or the QR codes already in the deck will break.
