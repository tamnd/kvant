---
id: 1991-7-konvey-odin-staryiy-fakt-i-neskolko-novyih-100a19a3
issue: kvant_1991_7
year: 1991
number: "7"
title: One old fact and several new ones
authors:
  - Конвей Дж.
rubric: raznoe
rubric_sub: Разное
page_first: 66
page_last: 68
page_labels: 64-66
lang: en
source: kvant_digital
extraction: vision
content_sha256: 9640586b56d68767f33ff2b083a41ee90ceb2a665280c7d93aace5334fcb8845
prompt_sha256: draft-1
translated_from: content/ru/1991/07/articles/21_konvey-odin-staryiy-fakt-i-neskolko-novyih-100a19a3.md
source_content_sha256: ca26826b20eb8253b22cf0d41ed0ead10517433df77d5b51d147103211069a08
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 64⟧

---
running_head:
folio:
---

One old fact and several new ones
NEW
(Another journey into the world of figurative numbers and numerical figures: puzzling numbers that can bewitch you)

J. CONWAY

Add the first $n$ of odd numbers, starting with 1. What do you get?

$$
\begin{array}{l}
1 = 1, \\
1 + 3 = 4, \\
1 + 3 + 5 = 9, \\
1 + 3 + 5 + 7 = 16, \\
1 + 3 + 5 + 7 + 9 = 25.
\end{array}
$$

In the third issue of the magazine, we began publishing translations of articles from the Soviet-American magazine «Kvant». Today we bring to your attention the next article in this series.

Do you recognize these numbers? Certainly! These are “square” numbers (remember from what follows why the squares of integers are called that way):

$$
1 = 1 \cdot 1, \quad 4 = 2 \cdot 2, \quad 9 = 3 \cdot 3, \quad 16 = 4 \cdot 4, \quad 25 = 5 \cdot 5, \dots
$$

And this is our old fact. Can it be explained? Summarize? Is it possible to obtain "cubic" numbers in a similar way?

$$
1 = 1 \cdot 1 \cdot 1, \quad 8 = 2 \cdot 2 \cdot 2, \quad 27 = 3 \cdot 3 \cdot 3, \quad 64 = 4 \cdot 4 \cdot 4, \dots?
$$

Well, there are many different explanations, and they lead to many different facts. Let's try to look first

From an algebraic point of view

We must prove that the differences between successive squares 0, 1, 4, 9, 16, 25,... are exactly the odd numbers 1, 3, 5, 7, 9, 11,...

But this is simple: obvious algebraic calculation shows that such a difference in general form is equal to

$$(n + 1)^2 - n^2 = (n^2 + 2n + 1) - n^2 = 2n + 1,$$

In the same way, you can verify that the differences between successive values ​​of any polynomial are the values ​​of some polynomial one less than the degree. For example, neighboring cubes differ by numbers of the form $3n^2 + 3n + 1$, i.e., by mysterious numbers

$$
1, 7, 19, 37, 61, \dots
$$

The cubes are the sums of the first few numbers of this sequence:

$$
1 = 1, \quad 1 + 7 = 8, \quad 1 + 7 + 19 = 27, \dots
$$

Melancholy!.. Why should one be interested in these mysterious numbers?

Let's try again.

From an arithmetic point of view

The sum of several numbers is equal to the product of their number and their arithmetic mean. So, for example, the sum of $1 + 3 + 5 + 7 + 9$ is $5 \times 5$. Medium

⟦folio 65⟧

---
running_head:
folio:
---

arithmetic sums
1, 1+3, 1+3+5, 1+3+5+7,...
are the half sums of the first and last terms, and it is clear that they are equal
1, 2, 3, 4,...
This brings us to a beautiful way to obtain cubes. Instead of always taking the sums of the first $n$ odd numbers, we'll take the next $n$ numbers, starting where we left off.
Then together the equalities
$$
\begin{align*}
1 &= 1^2, \\
1+3 &= 2^2, \\
1+3+5 &= 3^2,
\end{align*}
$$
we will have
$$
\begin{align*}
1 &= 1^3, \\
3+5 &= 2^3, \\
7+9+11 &= 3^3,
\end{align*}
$$
This is better, but let's try another idea.

From a geometry point of view
Take a look at this pattern:

It shows very clearly how a square number breaks down into successive odd numbers. Can we look at our mystery numbers 1, 7, 9, 37, 61 as patterns of dots? Seven coins that naturally fit into a neat figure can tell us... Well, of course! Our mysterious numbers

are known in combinatorics as “hex numbers” (“six” in Greek; do not confuse with the term “hexagonal” - hexagonal numbers, let’s introduce something else).

Is it true that the sum of the first few hex numbers is a real cubic number? Right! And to see this, it is quite simpler to check several lines - and

patterns of dots turn into cubic cells that can be nested inside each other to form a cube filled with dots.

My board has hexagonal "cubes" like the ones shown in figure, which she used to build hexagonal paramides. How many cubes did she need for a paramida with $n$ floors?

It seems that there are indeed many different generalizations of our basic fact, and that is fine, or it means that there is always hope of finding something new. However, some of the most striking ones were discovered only recently.

⟦folio 66⟧

---
running_head:
folio:
---

Let's start with squares. Let's write down the first few natural numbers, circle every second one and add the rest:
1 2 3 4 5 6 7 8 9 ...
$\textcircled{1}$ $\textcircled{4}$ $\textcircled{9}$ $\textcircled{16}$ $\textcircled{25}$...

Of course, it turns out to be squares.
Now let's change the process - circle every third number in the top row, form the next row, as before, circle every second number in it and add up the uncircled numbers.
The amounts will be the third row:
1 2 3 4 5 6 7 8 9 ...
1 3 7 12 19 27 ...
$\textcircled{1}$ $\textcircled{8}$ $\textcircled{27}$...

Storpriz! Cubes have appeared! Can you prove that this will continue?
This seems to apply to all other degrees as well. Say, if we circle every fifth number in the first row, every fourth in the second, etc., we will get it right at least for the first five powers.

1 2 3 4 5 6 7 8 9 10 11 ...
1 3 6 10 16 23 31 40 51 ...
1 4 10 26 49 80 131 ...
1 5 31 80 211 ...
$\textcircled{1}$ $\textcircled{32}$ $\textcircled{243}$...

Can you check that this pattern will always hold true?
In general, you can circle any set of numbers in the top row, breaking the remaining numbers into series. In subsequent rows, the last number of each series is circled, forming a new row from the sums of uncircled numbers, etc.
We saw that if we circle the numbers in the top row
1+1, 2+2, 3+3, 4+4, ...
then squares arise, i.e. numbers
1·1, 2·2, 3·3, 4·4,...

And circling the numbers
1+1+1, 2+2+2, 3+3+3, ...
we get cubes
1·1·1, 2·2·2, 3·3·3, ...

What happens when you circle "triangular" numbers?
1, 1+2, 1+2+3, 1+2+3+4,
1+2+3+4+5,...?

Answers
Of course, my daughter needed $n^3$ cups for the 6-story high.
Yes, when we continue the top line we will get all the consecutive cubes in the bottom (third) line. This is not at all difficult to prove by writing down sequences of numbers in general form:
... $3n-1$ $3n+1$ $3n+2$ $3n+3$
$3n^2$ $3n^2+3n+1$ $3(n+1)^2$
$n^3$ $(n+1)^3$

It is somewhat more difficult to prove that the rule for the $k$th degree works for all $k$. We will publish the best evidence submitted.
Triangular numbers
1, 1+2, 1+2+3, 1+2+3+4,
1+2+3+4+5

The added Messner transformation converts (of course!) into factorials:
1, 1·2, 1·2·3, 1·2·3·4,
1·2·3·4·5, ...

Publication prepared
V. Dubrovsky
