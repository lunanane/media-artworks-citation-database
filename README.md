# Media artworks citation database

What media artists say their work is for, in their own words.

196 contemporary media artworks made since 2020, with 865 verbatim
statements by their artists (81 of them questions), each linked to the page
it was copied from (884 distinct sources). It is the text layer of
*Why Make This*, a map that places the works by what their artists said about
them. Exported 2026-11-18.

## Licence

The compilation, structure and summaries are licensed under
[Creative Commons Attribution 4.0 International (CC BY 4.0)](LICENSE): reuse
freely, with credit to "Media artworks citation database, LNX Studio". The
quoted statements remain the work of the people who said or wrote them and
are not covered by this licence; cite them with their original source.

- [WORKS.md](WORKS.md): every work, one page each
- [data/works.json](data/works.json): one record per work, quotes nested
- [data/quotes.csv](data/quotes.csv), [data/works.csv](data/works.csv): flat tables

## What is and isn't the artists'

- **Quotes** are copied character for character from a page that was opened,
  with that page's URL. Nothing inside quote marks is paraphrased. `kind` is
  `question` only when the artist's own words ask one.
- `about` says whether a quote is about this work, the artist's practice, or
  another work. `voice` marks unsigned project text (venue or press copy).
- **Summaries** are editorial: written from the sources to say plainly what a
  visitor meets. They are not the artists' words.
- **Not included:** the map's islands (groupings of similar statements) and
  their names. Those are the studio's own reading, not part of the record.
- No images. Artwork documentation is linked at its source, not copied.

## Rights and corrections

The quoted words belong to the people who said or wrote them. They are quoted
here, with attribution and a source link, for research and discussion of the
works.

If you are one of the artists and want a quote corrected, added to, or
removed, open an issue or contact the studio; it will be changed.

## How it was made

Festival, press, interview and artist pages were searched for each work, and
quotes were copied verbatim with their URLs; every quote was checked against
the fetched page by script.
