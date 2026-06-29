# Tiger Transit — GSU Office of Student Transportation

A responsive website for **Tiger Transit**, the free shuttle service of the
Grambling State University Office of Student Transportation.

## Pages

- **`site/index.html`** — home: hero, student shuttle, airport & break travel
  (with live reservation forms), destinations, services, and the staff team.
- **`site/who-we-are.html`** — the office's mission, vision, core values, and
  goals & objectives.

## Run it

Open `site/index.html` in a browser, or serve the folder locally:

```bash
cd site
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Build notes

- Plain HTML + CSS, no build step. Brand: Grambling black `#0B0B0B` + gold
  `#EAA921`, Oswald (display) and Inter (body) via Google Fonts, Lucide icons.
- Real form links (Microsoft Forms / PDF) and staff photos are sourced from
  `gram.edu/student-life/services/transportation/`.
- The hero and destination imagery in `site/images/` can be swapped freely.

## Repository layout

- `site/` — the production website (HTML, CSS, and images).
