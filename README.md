# kvant

*Квант* as Markdown: every printed page, with permanent tags, translations, and worked solutions.

The code that builds this lives in `tamnd/kvant-solver`. This repo is the corpus only.

## What is in scope

*Квант* is the popular physics and mathematics monthly of the Soviet, later Russian, Academy of Sciences. It began in January 1970, ISSN 0130-2221, and is published by the Russian Academy of Sciences with the Steklov and Lebedev institutes.

The scope is the whole magazine and not the problem section. The archive holds 516 issues over 57 years at a mean of 66 printed pages an issue, so roughly 34000 pages. About two thirds of that is articles. The other third is material an article level scraper never sees: the answer columns, the kaleidoscope spreads, the chess page, the olympiad results, the editorial notices, the book reviews, the photographs and their captions, and the unattributed fillers at the foot of a column.

That is why the corpus is page first. Every printed page has a complete transcription under `content/ru/<year>/<issue>/pages/`, and articles under `articles/` are assembled from those pages rather than fetched separately. Both are committed. The duplication is deliberate: the page files are the only place the non article material survives, and an article can be reassembled after a splitting bug without spending a single model call.

## Identifiers

```
issue     kvant_1975_1        year and printed number, a joined number keeps the dash
page      kvant_1975_1_p0007  position in the scan, zero padded to four
article   1975-1-bronshteyn-ellips
problem   M1234 / F1234       as printed in Задачник «Кванта»
tag       0A3F                four characters, permanent, never reused, never edited
```

The tag idea is lifted from the [Stacks Project](https://stacks.math.columbia.edu/). `tags/tags` is append only, one `TAG,label` line per object. A tag follows its object through a rename and the old label goes to `tags/aliases`, so a citation still resolves after a reextraction, a resplit or a change of source.

M and F numbers are already permanent identifiers in the wild, since the problems are cited by number across the Russian olympiad literature, so they stay as the primary key for problems and carry a tag only for internal cross referencing.

## Three extraction paths

What a page costs depends on what its own text layer is worth.

| Path | Applies to | Pages | Method |
| --- | --- | --- | --- |
| native | the 145 issue PDFs measured as born digital | 9726 | `pdftotext` gives real text, so no model reads these pages |
| publisher | where the archive already carries text | 23% of 1975, unevenly elsewhere | fetched, then checked against the scan |
| vision | everything else | about 19000 | page image through vision OCR |

The native row is measured and not assumed, which is the whole point of `kvant textguard`. The mirror carries a full issue PDF for 146 of the 516 issues, and 145 of those turn out to be born digital. They run 2005 to 2025 rather than 2007 onward: 2005 and 2006 are set type as well, and 2011 to 2013 have no PDF on the mirror at all. Four of the files hold their Russian in a font with no ToUnicode map, so `pdftotext` hands back the CP1251 bytes as Latin-1 letters and the text has to be read back through the right table. One file, April 2023, has its type converted to outlines and carries no text at all. The measurement per file is in `manifests/paths.yaml` and the summary is in `reports/paths.md`.

Publisher text is never trusted blind. It is diffed against a vision transcription on a sample, because its provenance is unknown and this corpus is meant to be better than its sources rather than equal to them.

Native text is not trusted blind either. It is faster and more accurate word for word, and it gets the reading order of a two column page wrong, which a later pass cannot repair from the text alone. The measurement behind that is in [reports/ocr-audit.md](reports/ocr-audit.md).

## Layout

```
content/ru/1975/01/pages/0007.md              page complete transcription
content/ru/1975/01/articles/06_bronshteyn-ellips.md
content/ru/1975/01/issue.md                   masthead, TOC, cover, colophon
content/ru/problems/m/1234.md                 condition and the published solution
content/{en,vi,zh,ja}/...                     the same tree, translated
content/solutions/{lang}/problems/m/1234.md   our worked solutions, verified
manifests/                                    issues, TOC, page maps, rubrics, personalia, problems, glossary, refs
tags/                                         the permanent tag index
figures/                                      cropped diagrams, small, committed
reports/                                      audit, coverage, translation staleness, scorecards
```

`pdf/`, `images/` and `work/` are gitignored. Nothing large and nothing copyrighted is committed.

## Coverage

<!-- BEGIN COVERAGE -->
| Year | Issues | Pages | Transcribed | Articles | Problems | Tagged |
| --- | --- | --- | --- | --- | --- | --- |
| 1970 to 2026 | 516 | 34000 | 0 | 0 | 0 | 0 |
<!-- END COVERAGE -->

`kvant coverage` regenerates that block. A row is complete when transcribed equals pages, every TOC row has an article, and the audit is clean. Partial rows are the honest state and are never rounded up.

## Licence

See [LICENSE.md](LICENSE.md). Short version: *Квант* is copyright the Russian Academy of Sciences and its authors, this is a derivative work held for personal study, and no scans or PDFs are committed here.
