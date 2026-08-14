# Native text against a vision pass, measured on three pages

The plan says a page with a real text layer is read with `pdftotext` and everything else goes through a vision model. That is a claim about both cost and quality, and until M2 it was only ever an assumption. This is what happened when the same page went both ways.

The three pages are the January 2007 issue, which is born digital, at file page 12 and file page 24, and sheet 0040 of the January 1975 issue, which is a scan and has no other option. The vision pass renders the PDF page with `pdftoppm -r 200 -png` and sends the image to ChatGPT for a verbatim transcription. Everything below was run once per page in August 2026 on one lane.

## Time

| Step | Time |
| --- | ---: |
| `pdftotext` over a whole 64 page issue | 0.4 s |
| `pdftotext` over one page | 0.03 s |
| `pdftoppm -r 200 -png`, one page | 1.0 s |
| vision transcription, 2007 page 12 | 133 s |
| vision transcription, 2007 page 24 | 84 s |
| vision transcription, 1975 sheet 0040 | 148 s |

The native path is roughly four thousand times faster per page and costs nothing. That ratio is why textguard exists: the 145 born digital issue PDFs cover 9726 pages, and the difference between reading them and photographing them is a fortnight of lane time.

The three vision calls average 122 seconds, which is close enough to the 148 seconds a page the estimate in `paths.md` assumes that the wall clock figures there can stand until M3 measures a whole issue.

## Prose

Page 12 is a physics article, one column of prose with five display equations. Comparing the Russian words of the two transcriptions, ignoring the mathematics:

| | native | vision |
| --- | ---: | ---: |
| Russian words | 509 | 505 |
| agreement | | 96.6% |

Every difference on that page is one word. The vision pass read стратостата as стратосата eleven times, always the same way, in a word that appears in nearly every sentence of the article. The native text got it right eleven times out of eleven. Two of the four remaining differences are junk the native text picked up off figure labels, which the vision pass correctly ignored.

That is the useful shape of the result. A vision error is not random noise sprinkled through a page, it is one wrong decision about one shape applied consistently, and a spellchecker over the finished page finds it in a second. It is also the reason publisher text gets diffed against a vision pass rather than trusted: the same argument runs the other way.

## Layout

Page 24 is the problems page, two columns, five problems with illustrations between them, a footnote and a vertical illustrator credit.

Both transcriptions hold the same 188 Russian words, and they agree on 84% of the sequence. All of the disagreement is order. `pdftotext` follows the order the objects sit in the file, so it prints problem 1, jumps to the top of the right column for the tail of problem 3, and comes back. The vision pass gives problem 1, 2, 3 with its continuation joined on, then 4 and 5, then the footnote, then the credit, which is the order a reader reads them in.

This is the finding that changes the plan. Native text is more accurate word for word and is wrong about what order the words come in, and page order is not something a later pass can repair from the text alone. Two columns with a continuation across them is not a corner case in this magazine, it is the house style.

The vision pass also read the illustrator credit Гришуковой as Гришукковой, a doubled letter in a name set vertically at 90 degrees in six point type.

## Mathematics

This is where the two paths separate properly. The equation on page 12 is

```
V=\frac{4}{3}\pi r^2r_{\max}=\frac{4}{3}Sr_{\max}.
```

in the vision pass, and this in the native text:

```
4
4
V = πr 2rmax = Srmax .
3
3
```

The numerator and the denominator of a fraction are separate lines in the text layer, in the order they were drawn, and nothing in the string says which is which. Rebuilding that into mathematics is guesswork. The vision pass hands over LaTeX that is already right.

One warning for whoever builds the OCR stage. The transcription comes back as rendered HTML, and reading the rendered text loses exactly this: the LaTeX is flattened into a run of loose symbols with zero width spaces in it. The real LaTeX is in the `data-math-source` attribute on each math node, six of them on page 12 and one on page 24, and it has to be read out of the HTML rather than out of the text. The same applies to numbered lists, which come back renumbered from 1.

## The scan

Sheet 0040 of January 1975 is what most of this project actually looks like: a 1200 by 1861 JPEG of a page printed in 1975. There is no native text to compare against, so this one is a check that the vision pass holds up on the real input rather than on a rendering of a modern PDF. It came back clean, in 148 seconds, with the rubric heading, the standing editorial note and the problem statements all in place and no visible dropouts.

## What this changes

- Native stays the default wherever there is a text layer, on speed and on word accuracy.
- Native cannot be trusted on reading order. The native path needs `-layout` and a column aware reorder, and pages that look like two columns need checking against a vision pass on a sample.
- Formulas on native pages have to be recovered from the page geometry, not from the text stream, or the page has to go to vision. This is M6's problem and it is bigger than it looked.
- A vision transcription of a page with mathematics is worth having as LaTeX, which means the OCR stage reads the math source out of the response HTML and never out of the rendered text.
- One page is about two minutes on one lane. The estimate in `paths.md` stands.
