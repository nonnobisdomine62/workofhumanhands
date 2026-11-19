# Work of Human Hands: A Theological Critique of the Mass of Paul VI

A website for the book Work of Human Hands by Rev. Anthony Cekada (Second
edition, SGG Resources, 2015). This website includes the main content of the
fourteen chapters tracing the history and theology of the Mass of Paul VI —
the liturgical movement, the creation of the New Mass, the vernacular
translations, the General Instructions of 1969 and 1970, the art and
architecture, and each rite of the revised Order of Mass (introductory rites,
orations, liturgy of the word, preparation of the gifts, eucharistic prayer,
communion rite) — together with the author's preface, the appendix on which
Missal to use, the bibliography, and the index. Each chapter includes the full
text with its section headings, quotations, tables, and footnotes.

## Features

- Browse by chapter (table of contents with front and back matter)
- Full chapter text with headings, quotations, tables, and footnotes
- Search
- Liturgical paper-and-ink theme with rubric-red accent (light/dark)
- Responsive design

## Development

No build step — the site is fully static (`index.html` + `book.json`).
Serve the folder locally:

```
python3 -m http.server 8000
```

or

```
npx serve .
```

Then open http://localhost:8000.

## Deploy on Render

The included `render.yaml` preconfigures the static site (publish directory
`.`, no build command) and the rewrite of all routes to `index.html`. Push
this folder to a GitHub repository and import it on render.com as a Blueprint,
or create a Static Site connected to the repo. With the service name
`workofhumanhands`, the site is available at workofhumanhands.onrender.com.
