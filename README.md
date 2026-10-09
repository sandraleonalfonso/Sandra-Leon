# Sandra León: personal website

Academic website of Sandra León, published with GitHub Pages
(https://sandraleon.eu).

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

## Domain

The site is served at https://sandraleon.eu. The `CNAME` file tells GitHub Pages the domain;
`url` in `_config.yml` must match it. DNS at Namecheap: four `A` records for `@`
(185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153) and a `CNAME`
record for `www` pointing to `sandraleonalfonso.github.io`.

## Preview locally (optional)

    bundle install
    bundle exec jekyll serve
