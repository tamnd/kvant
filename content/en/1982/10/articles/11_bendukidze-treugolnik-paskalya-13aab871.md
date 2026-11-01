---
id: 1982-10-bendukidze-treugolnik-paskalya-13aab871
issue: kvant_1982_10
year: 1982
number: "10"
title: Pascal's triangle
authors:
  - Бендукидзе А. Д.
rubric: kvant-dlya-mladshih-shkolnikov
rubric_sub: «Квант» для младших школьников
page_first: 47
page_last: 49
page_labels: 45-47
tag: 19WV
lang: en
source: kvant_digital
extraction: vision
content_sha256: fdb5f03445ba7d9c8f7b76515b692904de5667a27eb90886716377c0e8eb205a
prompt_sha256: draft-1
translated_from: content/ru/1982/10/articles/11_bendukidze-treugolnik-paskalya-13aab871.md
source_content_sha256: 7a21c31785027e834127d0c3b72e17b36b294440c6a36fa7518621c3c493719a
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 45⟧

A. Bendukidze

Pascal's triangle

Take a sheet of paper and draw on it a square table of 100 cells (ten rows and the same number of columns). When choosing the size of the table, keep in mind that you will have to enter numbers into its cells, some of which will be three-digit.

So, are you ready?

Great! Start filling out the table.

In the cells of the first column we put the number 1, and in the cells of the first row, except, of course, the leftmost one, in which there is already a unit, there is the number 0. Fill in the remaining cells of the table in turn, moving from left to right and top to bottom, according to the transition law shown in figure 1.

Now look at the resulting table. Its zero elements form a triangle, two sides of which (vertical and oblique) are made up of units, and the third (horizontal) has the form

1 9 36 84 126 126 84 36 9 1

(Of course, the construction can be continued further or interrupted before reaching the tenth line.)

The resulting triangle is called Pascal's triangle, in honor of the great French scientist Blaise Pascal (1623-1662), who invented and studied it. What is this triangle replaced with? And this is what we will see now.

Let's follow the subsets

Consider the set $M_4$, consisting of four different balls - tennis, volleyball, football and basketball (Fig. 2). Let us find all its subsets (including the empty $\varnothing$ and all the sets $M_4$), groups

Fig. 1. Fig. 2.

Ozelementov 1 element 2 element 3 element 4 element

Fig. 3.

⟦folio 46⟧

Fig. 4.

sorting them by the number of elements (Fig. 3), and write down on a line how many subsets there are in each group:

1 4 6 4 1

Is this line familiar? Yes, it turned out to be the fifth line of Pascal's triangle. This is no coincidence. If we took the set $M_3$ of three elements, we would thus get 1 3 3 1 - the fourth row of Pascal's triangle. In general, if you take a set $M_n$ of $n$ elements and make a row from the number of its 0-element subsets, the number of 1-element subsets, the number of (n-1)-element subsets and the number of n-element subsets, you get the $(n+1)$th row of Pascal’s triangle.

Let's check this again for $n=0, 1, 2$. Indeed, everything is in order (Fig. 4).

To prove this in the general case, it is enough to check that each line is obtained from the previous one according to the same transition law as Pascal’s triangle. And this is really true.

For example, let's see how the number of 2-element subsets $M_4$ is obtained. To do this, let's temporarily hide a tennis ball in our pocket - polluch the set $M_3$. It already has three 2-element subsets:

Fig. 5.

To get the rest, you need to take a tennis ball out of your pocket and add it to the 1-element subsets $M_3$:

Fig. 6.

We get $3+3=6$, as expected according to the transition law. It is clear that this reasoning is general; it can be carried out to find the law of transition to the number of $k$-element subsets of $n$ elements for any $k \leq n$.

Now, to establish the number of subsets of, say, five elements into a set of, say, eight elements, there is no need to perform complex enumerations. The ready answer (70) is written in the fifth place of the ninth line of Pascal's triangle.

No, Pascal's triangle is useful for more than just that.

Let's open the brackets

By successively opening the brackets and driving similar terms, it is not difficult to find that

$$(1+x)^2=1+2x+1x$$
$$(1+x)^3=1+3x+3x^2+1x^3$$
$$(1+x)^4=1+4x+6x^2+4x^3+1x^4$$

Finding $(1+x)^5$ in this way is already more difficult, and the most industrious of you will not want to count $(1+x)^8$. But is it necessary to count? Isn't the answer prepared according to the line of Pascal's triangle?

⟦folio 47⟧

At the beginning of the odds line
1 2 1
1 3 3 1
1 4 6 4 1

coincide with the initial rows of Pascal's triangle. To prove that this will continue to be the case, it is enough to find the transition law operating here. But, for example,
$(1+x)^5 = (1+x)(1+x)^4 = (1+x)(1+4x+6x^2+4x^3+1x^4)$;
the coefficient, say, for $x^3$ is obtained (when opening the last brackets) as the sum of the coefficients for $x^2$ and $x^3$ from the previous line - we get $10=6+4$, as in Pascal’s triangle. It is clear that this reasoning is general.

We have established that the sequence of coefficients for increasing powers $x$ in the expansion of the bilen $(1+x)^n$ coincides with the $(n+1)$th row of Pascal’s triangle.

Once again, Pascal’s triangle saves us time: by looking at it, we can immediately write without calculation
$(a+b)^9 = a^9 + 9a^8b + 36a^7b^2 + 84a^6b^3 + 126a^5b^4 + 126a^4b^5 + 84a^3b^6 + 36a^2b^7 + 9ab^8 + b^9$.

Properties of Pascal's triangle

By discarding the zeros, our table can be rewritten in a more symmetrical, triangular form:

Fig. 7.
2. How many a) two-digit b) three-digit numbers are there, the digits of which are in descending order?
3. A triangular number is the number of points in triangles of the same type as in figure 8. How to find triangular numbers in Pascal's triangle?

Fig. 8.
4. Present as a sum of monomials a) $(a-b)^6$; 6) $(x-2y)^5$.
