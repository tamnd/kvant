# Sign-off for Квант 1975 №1

This is the first issue taken all the way through the pipeline, and it is the one the rest of the corpus is measured against. Everything below was run in August 2026.

## What was checked, and by what

The milestone asks for five pages read against the scan by a human. That is not what happened and the report should say so. The five pages were read by Claude Code, one page at a time, with the rendered scan image and the written page file side by side. The pages are named below so that a person can repeat the check in an hour and disagree with it.

The rest of the report is machine measurement, and those numbers stand on their own.

## The issue

| | |
| --- | ---: |
| sheets in the scan | 84 |
| page files written | 84 |
| articles assembled | 27 |
| rows in the manifest contents | 27 |
| pages carrying a folio line | 84 |

`kvant audit --issue kvant_1975_1` reports no failures. It reports eight warnings: six orphan pages and two shared pages. Both kinds are correct and are explained at the end.

## Which lane read it

Two lanes were run over the same 84 sheets.

| | GLM-OCR on a 4090, 6 at once | Claude CLI, 6 at once |
| --- | ---: | ---: |
| wall clock for the issue | 3 m 19 s | 6 m 20 s |
| pages the rules accepted | 71 | 84 |
| pages that died after three tries | 13 | 0 |
| words mixing two alphabets | about 1.2 a page | 0 |

The card is twice as fast and it did not finish the issue. Thirteen sheets failed three times each, and because the sampling is pinned at temperature zero a failed page comes back identically failed, so those thirteen were never going to be read by trying again.

The gap is wider than the accept rate makes it look. Sheet 17 was accepted by every rule on the card lane and is not a transcription of the page. Reading it against the scan turned up the formula numbers (11) and (12) missing from both display equations, the verb dropped out of one sentence, `единиц` written as `единниц` five times, `атом` written as the Latin word `atom`, `гравитационную` written half in Latin, `см` and `эрг` written as `cm` and `erg`, decimal commas turned into decimal points, and one Han character welded into the middle of `сантиметр`. The same sheet on the other lane matches the page word for word, keeps both formula numbers, and marks the column break.

So the issue is written by the slower lane. The card stays in the code with its measurements, because 34000 pages is a different problem from 84, but nothing it produced is in this issue.

## The five pages

| sheet | printed page | what is on it | result |
| --- | ---: | --- | --- |
| 0003 | 1 | masthead, editorial board, contents, cover note | matches |
| 0017 | 15 | two columns of physics prose with seven display formulas | matches |
| 0041 | 39 | end of an article, then three short items from the miscellany | matches |
| 0043 | 41 | the problems page, M301 to M305, two figures | matches |
| 0074 | 72 | a book review, dense with names and initials | matches |

All twenty seven rows of the manifest contents produced an article and the audit found nothing wrong with any of them, so the page numbering holds end to end and not only at the five places it was read closely.

Two things worth writing down from the close read.

Sheet 3 gives the surname of one editor as Березип. The scan prints a damaged glyph there and the transcription followed the page rather than the name, which is the behaviour the prompt asks for. The name is Березин. A pass that fixes obvious typography against the scan belongs later and not in the extraction.

Sheet 41 marks `Головоломки`, `Равенства из спичек` and `Задачи` as ordinary headings rather than rubric banners, which is correct. They are the titles of three short items inside the miscellany and not standing section banners.

Eight sheets do carry a rubric banner: 38, 42, 56, 68, 70, 72, 75 and 79. Six of the eight match a rubric the manifest names. The two that do not are sheet 68 and sheet 79, and those are the same two places the assembly left pages orphaned, so the banners on the page and the holes in the contents agree about where the mirror's data stops.

## The warnings

Six pages are claimed by no article: sheets 1, 68 and 79 through 82. None of them is a body page that went missing, but two of the three reasons are worth knowing about.

Sheet 1 is the front cover.

Sheet 68 is printed page 66, and it carries the banner of the `Спрашивайте — отвечаем` rubric and the editors' introduction to it. The manifest starts the item under that banner at printed page 67, which is the next sheet, so the opening page belongs to no row.

Sheets 79 through 82 are printed pages 77 to 80, the answers and hints section. The magazine lists it in its own printed contents at page 77. The manifest contents this corpus was built from stops at printed page 74 and does not list it at all, so four real pages of the issue are transcribed and assembled into nothing. That is a gap in the mirror's data rather than in the read, and it is the kind of thing worth counting across a year before M4 goes wide.

Two warnings say sheet 41 is claimed more than once. It is. Three short items from the miscellany end and begin on that one page, which is what a miscellany page is, and the audit is right to mention it and right not to fail on it.

## What this issue changed in the code

Three things.

The requests were sending no temperature at all, so the server sampled at 1.0. The first full run of this issue came back with 836 words carrying two alphabets across 83 of the 84 sheets, and every one of those pages passed rules 1 through 7 because they were the right length, in Russian, correctly paginated and balanced in their mathematics. Sampling is now pinned at zero for a served engine, and the same nine sheets went from 14.3 such words a page to 1.3.

Rule 8 rejects a page whose words mix two alphabets, so that failure can never pass quietly again. It was widened from Latin to any alphabet after the close read of sheet 17, where the Latin version could not see the Han character in the middle of a Russian word. The audit asks the same question of a corpus that is already written, since a run accepted before the rule existed is only found by looking.

The printed page number is now found rather than guessed. It used to be cropped from a fixed band above the foot, and that fails because the number moves between 2.7 and 6.5 per cent of the page height across an issue. Searching up from the bottom edge for the last line of ink reads 81 of these 84 sheets correctly with nothing read wrongly, against 74 correct and 2 wrong for the best fixed band. The three it does not read are two colour inserts that print no number and one page that answered in letters.
