---
id: 2024-10-klimov-zadacha-o-razbienii-pryamougolnikov-na-poloski-e105ae72
issue: kvant_2024_10
year: 2024
number: "10"
title: The problem of dividing rectangles into strips
authors:
  - Климов А. В.
rubric: raznoe
rubric_sub: Разное
page_first: 25
page_last: 26
page_labels: "24"
tag: OYKE
lang: en
source: kvant_digital
extraction: native
content_sha256: 73cebd538fa1485d5fadceca79972c422526afb1802b70601a6b88a05eee643d
prompt_sha256: draft-1
translated_from: content/ru/2024/10/articles/01_klimov-zadacha-o-razbienii-pryamougolnikov-na-poloski-e105ae72.md
source_content_sha256: ba1fee8df3caf4d8fd87656c7257917ca4b2840abca9135d4f078b06742e351d
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio none⟧

PROBLEM WITH HISTORY

The problem of dividing a rectangle into strips

A. KLIMOV

AT THE MOSCOW MATHEMATICAL Olympiad in 1974, the following problem was proposed in two senior classes. A rectangular sheet of paper measuring a u b cm is cut into rectangular strips, each of which has a side of 1 cm. The cut lines are parallel to the sides of the original sheet. Prove that at least one of $чисел^{a} или^{b}$ is an integer. The history of its appearance is interesting. First, let's make a short digression about the circumstances of life in those years. At that time, many old buildings were demolished in Moscow, in which there was a lot of value from the point of view of art. Kolya $Константинова^{1}$ (well known in Olympiad circles) had a friend (like even a classmate) - the artist Vitya Galkin. He was obsessed with the idea of ​​saving and preserving what was valuable in these destroyed houses. These are not only objects (like lamps or samovars), but also parts of furniture and the buildings themselves - handles, balusters, window sills, panels and much more. Kolya helped him, inspiring us, students, to participate in this. When it became known that in a day or two some wonderful house would be destroyed, we would go there, sometimes at night, so that everything that was still valuable could be unscrewed, torn off, torn out and loaded onto a car. Viti had a fairly large house in the village of Gryzlovo, located near the Lopasnya River. We stored our “loot” in this house. And then we helped him sort it all and put it in order.

1 Nikolai Nikolaevich Konstantinov – high-

a gifted organizer of mathematics education. Read the interview with him in «Kvant» No. 1 for 2010.

⟦column⟧

And then one day I had to deal with a bunch of small square tiles of the same size, about 2 x 2 cm. It was necessary to pack them more tightly in a wooden box with dimensions, of course, not multiples of the side of the tile. Moreover, the tiles were of very different thicknesses - from 3 to 8 mm. Therefore, I decided to place them on edge in one layer, so that later I could put a second layer on them, etc. Finishing the layer, I saw that there was an unfilled piece left, and such an area that 1-2 more tiles would fit there. I started trying to change the orientation of the tiles, but it was all in vain. I had to leave an empty space. And only the next day, already in Moscow, I realized that there was a certain mathematical fact hidden in this. This is how the above problem came about. Moreover, of course, I was also interested in the minimum area of ​​the remainder for given non-integer a and b. There was another Olympics coming up, and this would be a good challenge for her. However, it took a long time to solve the problem. Finally, a rather complex solution was found that they agreed to accept. I was hoping that one of the participants could find a simpler solution. But this expectation did not come true. The problem was given in two senior classes, 9 and 10. And as far as I remember, there were only 2 or 3 works in which it was possible to see a prototype of a possible proof with a big stretch. In one of these works - written by Andrei Korobov from the 10th grade of the 179th mathematical school - there was a sketch of a proof for the case when both sides of the sheet are rational, i.e. exactly multiples of 1 n for some integer n. The sizes of the strips were also assumed to be rational. It was also assumed that all cuts follow grid lines with a step of 1 n. The cells were painted on the diagonals drawn in the original rectangle with a step of n cells (i.e. 1 cm). It turned out that in each elementary strip of size 1 u n cells there is exactly 1 shaded cell in any position or orientation. Therefore, each strip of size m u n (cells) contains exactly m colored cells, i.e. their number is strictly proportional to the total number of cells in it mn. Now it remained to make sure that if both sides of the original sheet are not divisible by n (in the sense of the number of cells),

⟦folio 24⟧

KV A NT 2024/No. 10

then for the area of ​​the entire sheet this proportionality is not observed. All that now remained for me was to go to the limit at n o f and obtain the following elementary (i.e., school, without infinities) solution for $любых^{a} и^{b.}$ We will solve the problem in a broader formulation. Considering any incomplete coverings of the sheet a u b without overlaps with rectangular strips of width 1 with sides parallel to the sides of the sheet, we prove that $если^{a} и^{b}$ are both not whole, then there will always be an uncovered part of the sheet. We will also try to estimate from below the size of the remainder depending on $от^{a} и^{b.}$ We will draw on the original sheet a series of diagonal (at 45q to the side) straight lines of the same direction (blue lines on figure), spaced 1 cm from each other along

^a ` ^ b ` is less than (or equal to) 1, then none

⟦column⟧

it does not contain a secant fragment, since the corner of the sheet lies below the diagonal of the complemented unit square (shown by the dotted line). As a result, all secants are covered by the cut strips, which means their total area is equal to L. And even if in this case a piece of area ^ a `  ^ b ` remains uncovered, then with any other covering no less will remain. Further, if ^a ` ^ b `! 1, then the length of the projection of the secant in this rectangle will be ^ a ` ^ b ` 1, ​​so the residual area for any coverage will be at least

^ a `  ^ b ` ^ a ` ^ b ` 1

1 ^ a `  1 ^ b `! 0.

Thus, we have found the lower limit of the area of ​​the uncovered part of the sheet:

min ^ a `  ^ b `, 1 ^ a `  1 ^ b `.

vertically and horizontally. We will call them secants. Every strip of size 1 u l covers fragments of secants with total length l 2 or $просто^{l,}$ if we measure the lengths of the fragments by their projections onto $сторону^{l.}$ Thus, this conditional “length” is equal to the area of ​​the strip. (Indeed, these projections exactly cover $сторону^{l}$ without overlap.) Let L be the sum of the “lengths” of all secants on the sheet. For any covering, the total area of ​​the strips cannot be greater than L. Let one of the secants pass through the lower left corner of the sheet, as in figure. Consider the following reference cutting and coating. Let's cut full (from edge to edge) strips of width 1 on the left at the maximum, and then short strips of height 1 from the bottom, as shown in figure. They cover the entire sheet with the exception of a small rectangle at the top right of size ^a ` u ^ b `. Here ^ x ` is the fractional part of $числа^{x.}$ If the sum of the sides of this rectangle

This number is obviously greater than $0, когда^{a} и^{b}$ both are not integers. Moreover, when ^a ` ^ b ` 1, the first argument of the minimum is minimal and vice versa. The question arises whether the resulting lower bound is achieved at ^ a ` ^ b `! 1? If one of the sides of the sheet is less than 1, then a strip of width 1 can only be cut on the other side (if it is greater than 1), and therefore the remainder will always be ^ a `  ^ b `. But if both sides are greater than 1, then the bound 1 ^ a `  1 ^ b ` is reachable. We leave it to the reader to find the corresponding cut himself (for example, when 1 a, b 2 and a b! 3 ).
