# RAILS website

The site for rails010.nl, built by GitHub Pages (Jekyll).

**Edit words and pictures at app.pagescms.org.** They live in `_data/`:

- `content.yml` – the home page
- `past_events.yml` – the Past events page (posters and photos go in `assets/uploads/`)
- `resources.yml` – the Resources page (sections of clickable link cards)
- `majors.yml` – the "Find your track" train page (one carriage per major). Hidden for now: `published: false` in `majors.html`

Code, for when something needs to change beyond the words:

- `_layouts/default.html` – header, menu and footer shared by every page
- `assets/site.css` – all styling
- `index.html`, `past-events.html`, `resources.html`, `majors.html` – the pages
