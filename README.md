# Sandra León: personal website

Academic website of Sandra León, published with GitHub Pages
(https://sandraleonalfonso.github.io/Sandra-Leon/ until the .com domain is connected).

## How it is organized

- `index.html`, `research.md`, `publications.md`, `teaching.md`, `engagement.md`, `contact.md`: one page per section (English).
- `_papers/`: one file per journal article; each becomes its own page under `/publications/`, with Google Scholar citation tags.
- `_config.yml`: name, email, photo and profile links (Google Scholar, ORCID, CSIC/IPP, LinkedIn).
- `_data/i18n.yml`: menu labels and other interface text in English and Spanish.
- `assets/`: stylesheet and images.

## Adding Spanish

Spanish pages go under `es/` with `lang: es` and the same `ref` as their English page,
for example `es/publicaciones.md` with `ref: publications` and `permalink: /es/publicaciones/`.
The EN | ES switch, the hreflang tags and `sitemap.xml` pick them up automatically.

## Connecting the .com domain

In `_config.yml` set `url` to the domain (for example `https://www.example.com`) and `baseurl` to `""`,
then add the domain under Settings → Pages → Custom domain.

## Preview locally (optional)

    bundle install
    bundle exec jekyll serve
