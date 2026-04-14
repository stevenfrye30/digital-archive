# Digital Archive

A free, online reader for public-domain and Creative-Commons scriptures,
philosophy, and world literature — 1,100+ texts from Project Gutenberg,
SacredTexts.com, Suttacentral, eBible, and the Internet Archive.

**Read it online:** https://stevenfrye30.github.io/digital-archive/

## What's inside

- Parallel translations side by side
- Sortable translator index
- Full-text search across the corpus
- Attribution manifest with license per translation
- Permalinks down to the passage level

All texts are either public domain (pre-1929 or Project Gutenberg verified)
or Creative Commons (Suttacentral). Copyrighted works are excluded from
distribution.

## For tinkerers

The reader is a static site — plain HTML + JSON. Data files are shipped
pre-gzipped (`*.json.gz`) and decompressed in the browser via
`DecompressionStream`. Everything else happens client-side.
