---
id: 1990-3-lev-poglyadim-na-diagrammu-a58cb71f
issue: kvant_1990_3
year: 1990
number: "3"
title: Let's look at the diagram
authors:
  - Лев В.
rubric: osnovnye-stati
page_first: 14
page_last: 18
page_labels: 12-16
lang: en
source: kvant_digital
extraction: vision
content_sha256: ab39f4f18c1a309b42765a4e5c666749c0653c2a55a4c77f609efb8d266e62d0
prompt_sha256: draft-1
translated_from: content/ru/1990/03/articles/02_lev-poglyadim-na-diagrammu-a58cb71f.md
source_content_sha256: 618ea1b42ecad9f1a79138dc6c918617b7dc31c0e42393ded6bdc494977e8cfa
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 12⟧

---
running_head:
folio:
---

in double digits? A generalization of the problem suggests itself: consider numbers in the number system with base $q$, consisting of exactly $q$ digits. The conventions simply call them "$q$-numbers" for brevity.

Let's create a problem for ourselves!

Quite naturally, we will start with the statement of the problem that we are going to write down. And it gives us a hint from a simple reformulation of the original problem.

Let's consider some $q$-number. Let's construct a new $q$-number from it as follows: the first digit of this new number will be equal to the number of ones in the original number, the second - the number of two,..., the penultimate - the number of digits "$q$ - 1", the last - the number of zeros in the original number. Thus, we defined some mappings on $q$-numbers; This display is propylostrated at figure 1.

The initial task is to find the “fixed point” of such a mapping, i.e., such a $q$-number that in this mapping transforms into itself (such as, for example, the number 12002 on figure 1).

Let us now try to trace the fate of some $q$-number in our display. Although there are not so few $q$-numbers (think about how many), there are still a finite number of them. Therefore, successive images of the original $q$-number cannot all be different. This means that, starting from a certain place, these images begin to repeat periodically - a cycle will arise similar to those depicted on the right in figure 1. The non-moving point is, of course,

$$\begin{array}{c c c c c}
8010071741 & 3001003 & 1020004 \\
3001002103 & 1101004 \\
212000005 & 12002 & 111003 \rightarrow 301002
\end{array}$$

Fig. 1.

 cycle of unit length. But it is also interesting to describe all the cycles of such a mapping. This is exactly what our problem will be!

Exercise. Let us associate with the $q$-number $A = (a_1 a_2 \dots a_q)$ the quantities $s(A) = a_1 + a_2 + \dots + a_q$; $m(A) = a_1 + 2a_2 + \dots + (q-1)a_{q-1}$. Prove that if the $q$-number $A$ is the image of some other $q$-number $B$ under our mapping, then $s(A) = q$. Also, $s(B) = m(A)$.

Young diagrams

Readers of «Kvant» are probably already familiar with such diagrams; errors often arise in connection with questions about the division of natural numbers into terms. Several examples are depicted in figure 2, where next to each diagram its order is indicated - the total number of squares in all columns of the diagram. The height of the columns increases from right to left.

We will call a group of columns the set of all columns of a chart of a given height, unless the number of such columns is less than two; We will call all other columns (i.e. those that are not included in any group) separate columns.

Why do we need them?

It's time to explain how our problem relates to Young diagrams. First of all, by indicating a method that assigns to any $q$-number a certain order diagram $q$. Here is this undead method: rearrange the numbers in the $q$-number so that the same numbers are in a row, combine them into horizontal rectangles and then “rotate” these rectangles, placing them vertical; take a look at figure3!

Of course, the same diagram can correspond to different $q$-numbers: for example, if these numbers are obtained from each other by certain permutations and redesignating digits (see figure 4). The converse is also obvious: if two $q$-numbers have the same Young diagram, then each of them can be obtained from the other by such permutations

⟦folio 13⟧

---
running_head:
folio:
---

Puc. 2. $q=11, q=14, q=4, q=3, q=5$.

8 0 1 0 0 7 1 7 4 1
0 0 0 1 1 1 7 7 4 8

1 1 1 0 0 3
1 1 1 0 0 3

Puc. 3.

320013 → 0 0 3 3 1 2
045451 → 4 4 5 5 0 1
123434 → 3 3 4 4 1 2

Puc. 4.

Puc. 5.

Puc. 6.

⟦folio 14⟧

---
running_head:
folio:
---

and redesignate. Note now that their images in our mapping of $q$-numbers are obtained from each other by simply rearranging the digits (be sure to check this!), and therefore these images also have the same diagram. We have proven the following:

if two $q$-numbers correspond to the same Young diagram, then their images also correspond to the same Young diagram.

This statement, despite its simplicity, is of decisive importance for us. Under no circumstances should you read any further in this article until it becomes completely clear to you!

What follows from this?

Let us take some Young diagram of order $q$ and consider any $q$-number generating it. Let us then find the image of this $q$-number and, in turn, construct a diagram corresponding to this image; The "blue" statement (see above) means that this last diagram is completely determined by the one taken at the beginning. Thus, the mapping we introduced above onto the set of $q$-numbers defines a certain mapping onto the set of Young diagrams of order $q$. Examples of this latter mapping are given at figure 5.

Any cycle of mapping onto $q$-numbers will, of course, define some cycle of mapping onto Young diagrams of order $q$. This allows us to move from searching for cycles on $q$-numbers to searching for cycles on Young diagrams. Of course, then you will need to “go back” by finding for each cycle on the Young diagrams all the corresponding cycles on $q$-numbers. However, this makes it quite easy; We will return to this issue at the end.

So, our transformation task is as follows:

find all cycles on Young diagrams of order $q$ defined by the diagram mapping introduced above.

Let's find out...

“how it works” the display of Young diagrams we constructed. Each individual column of the original diagram corresponds to a series of digits of the original number, which has a “unique” length, and therefore corresponds to some unique digit of the image number, i.e., in the end, corresponds to a column of the image diagram, which has a unit height. In exactly the same way, each group of columns of the original diagram corresponds to one column of the image diagram, the height of which is equal to the width of the base of this group of columns. In addition, the digits 0 of the image number do not correspond to the lower rows of digits of the original number. These zeros generate another column of the image diagram, which we will call `дополнительным`.

In order to map the source diagram into an image diagram, you must:

1) draw a “long” rectangle with a height of one and a length of $q$ cells, aligning its left side and base with the left side and base of the original diagram;

2) break the “long” rectangle into several short vertical sides, limiting groups of columns and individual columns of the original diagram;

3) Place the resulting short rectangles vertically, making a new Young diagram from them. This will be the image diagram.

A mapping of Young diagrams of order $q$ can be completely described by a graph showing which diagram will go into which. For values ​​$q<7$ such graphs are depicted in figure 7. It can be seen, for example, that for $q=2$ and $q=6$ there is exactly one cycle each, consisting of two diagrams; at $q=5$ and $q=7$ there is one each, and at $q=4$ there are two fixed points; cycles of three diagrams have only for $q=3$ and $q=7$ (as we will prove a little later, there are no such cycles for any other values ​​of $q$).

⟦folio 15⟧

---
running_head:
folio:
---

and now we are completely ready for this. Since the case $q < 7$ has already been resolved into figure 7, we will assume that $q > 7$. An attentive reader could already agree on what our main idea is: remember, when describing the display on Young diagrams, we said that “each group of columns of the original diagram corresponds to one column of the image diagram”? This means that, as a rule, the number of columns when moving to an image diagram can only decrease. More precisely, the number of columns can only increase if all the columns of the original diagram are separate; the number of columns can remain unchanged only if the diagram contains exactly one group

Fig. 7.

py, consisting of two columns, and all other columns must be separated. Our decision will be based on this: after all, if we take any cycle in Young diagrams, then either all diagrams of this cycle will contain the same number of columns, or at least one diagram of the cycle will contain strictly fewer columns than its image. In other words, in each cycle, either all diagrams contain one group of two columns and a certain (constant for all diagrams of the cycle) number of individual columns; or there is a diagram consisting only of individual columns. We will now consider these two possibilities in turn.

A. Let all the diagrams of our cycle include a group of two columns and a certain number of individual columns, the same for all diagrams of the cycle.

Let's look at some cycle diagram. Its image diagram, also belonging to a cycle, will consist of a column of height 2, a certain number of columns of height one and an additional column; since this diagram obeys the general rule - “a group of two and a certain number of separate columns” - it is easy to check that the number of columns of unit height is exactly 2, and the additional column has a height of at least three cells (in this case, the condition $q > 7$ must be taken into account). But then the next loop diagram will consist of a column of height 2, two columns of unit height, and an additional column of height $q - 4$; All subsequent diagrams will have the same form, i.e., in fact, our cycle consists of only one element - it is a fixed point in the display of Young diagrams of order $q$ (see Fig. 8 on the left).

B. Let one of the diagrams of our cycle consist only of individual columns.

Then the following diagram consists of columns of unit height and

⟦folio 16⟧

---
running_head:
folio:
---

an additional column whose height is greater than 1 (the latter is obvious, since the height of the additional column is equal to the number of cells in the original diagram, which is “not lower than the second floor” of the diagram). In turn, the image of this diagram will include three columns, one of which is of the same height. All three of these columns can't be the same height (why?); if some two heights coincide, then the next cycle diagram will still consist of three columns with different heights; the following chart will consist of three columns of a single height and an additional column of height $q-3$; the next is a new one of three columns with different heights (equal to 3, 1 and $q-4$: we new uses the condition $q>7$), etc., - we come to a cycle consisting of two diagrams (see Fig. 8 on the right).

Our task is to solve. We have shown that to map to Young diagrams order $q>7$ has exactly two cycles: one fixed point and one cycle of length 2.

Back to the $q$-numbers!

In order to completely complete our small study, it remains to return from Young diagrams to $q$-numbers, to determine which cycles on $q$-numbers can generate the two cycles we found on Young diagrams for $q>7$. Luckily, it's not difficult to keep going.

Let's start with a cycle of length 1 - a fixed point in the display of Young diagrams. The number generating the unique diagram of this cycle includes a group of $(q-4)$ identical digits, a group of two digits, and some other two different digits;

therefore, the image of this number will consist of the digits $(q-4)$, 2, 1, 1, and all other digits of the image will be zeros; but then the next image will have the first digit 2, the second digit 1, the $(q-4)$th digit 1, the last digit $(q-4)$, and the remaining digits zeros; All subsequent images will look the same. So, the only cycle on $q$-numbers that generates a fixed point of the Young diagram map is itself a fixed point: it consists of a single number 210...010...0 $(q-4)$ (the second unit is in the $(q-4)$ place). At $q=10$ you have already encountered this number at the very beginning of the article.

A cycle of length 2 is treated in exactly the same way. We will leave the details to the interested reader, but here we will report only the result: this cycle is also generated by exactly one cycle per $q$-number, consisting of two elements: 30...0100 $(q-4)$ and 1010...01000 $(q-3)$.

And in conclusion - an unsolved problem

So we know that every $q$-number will eventually end up in either a fixed point or a cycle of length two. But how to predict the “fate” of a specific $q$-number? There is probably a sign that allows one to determine by the type of number which of the two implementation possibilities. The author was unable to find such a sign. Maybe one of the readers can solve this problem?
