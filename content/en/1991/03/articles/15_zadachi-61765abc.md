---
id: 1991-3-zadachi-61765abc
issue: kvant_1991_3
year: 1991
number: "3"
title: Tasks
rubric: konkurs-imeni-a-p-savina
rubric_sub: Конкурс имени А. П. Савина
page_first: 50
page_last: 51
page_labels: 48-49
lang: en
source: kvant_digital
extraction: vision
content_sha256: 242dfdf6f759a8dfa5a48ab89b5c2495bd8f1a43ca689d03d75da20425e8b2fc
prompt_sha256: draft-1
translated_from: content/ru/1991/03/articles/15_zadachi-61765abc.md
source_content_sha256: e7af640bb052c5c49933e5c87b3887f2c382d03fa637f55eb5ce77f8d1716292
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 48⟧

Tasks

19. An equilateral triangle ABC is located on a plane. Indicate all points $M$ of this plane for which both triangles ABM and ASM are equilateral.

A. Savin

20. Andrey divides at his discretion a pile of 200 matches into 6 piles (each of them containing at least one match), and then Boris. equalizes the number of matches in two of these piles, take several matches from one pile. We call the number of matches taken by Boris Andrey. Boris strives to take as few matches as possible. How should Andrey play so that he can ensure the maximum possible win for himself?

X. Khaimov

21. On a chessboard, the horizontal and vertical lines are numbered from 1 to 8. There are 8 rooks placed on it so that they are not next to each other. For each rook, we calculate the product of the numbers of the horizontal and vertical lines on which it stands. Let's take the sum of these products. Prove that for an arrangement of rooks that is centrally symmetric to a given one, the sum obtained in a similar way is equal to the original one.

V. Proizvolov

⟦folio 49⟧

---
running_head:
folio:
---

In fact, the minimum of the total function $f(x)+g(x)$ is achieved at some point of the segment $[a; b]$. At this point, the values ​​of the function $f(x)$ and $g(x)$ are not less than their minimums. It is clear that inequality turns into equality if the minima $f(x)$ and $g(x)$ are reached at the same point.

The situation is exactly the same in the case of the $n$ function:

$$\min f_1(x) + \dots + \min f_n(x) \leqslant \leqslant \min (f_1(x) + \dots + f_n(x)).$$

The proof is easy to obtain by induction. On the right side we will select one function at a time: $\min (f_1(x) + \dots + f_n(x)) \geqslant \min (f_1(x) + \dots + f_{n-1}(x)) + \min f_n(x)$ and so on.

Minima of quadratic functions and quadratic inequalities

Let's start with a quadratic function of the form $f(x)=ax^2+2bx$, where $a>0$. To find the minimum, select a complete square

$$ax^2+2bx=a\left(x^2+2\frac{b}{a}x+\frac{b^2}{a^2}-\frac{b^2}{a^2}\right)=a\left(\left(x+\frac{b}{a}\right)^2-\frac{b^2}{a}\right)=a\left(x+\frac{b}{a}\right)^2-\frac{b^2}{a}.$$

So, the minimum is reached at $x=-\frac{b}{a}$ and is equal to $f\left(-\frac{b}{a}\right)=-\frac{b^2}{a}$.

Now to the $n$ function

$$f_1(x)=a_1x^2+2b_1x,$$
$$f_2(x)=a_2x^2+2b_2x,$$
$$\dots$$
$$f_n(x)=a_nx^2+2b_nx$$

Let us accept our basic inequality. The function $f(x)$ has a minimum at $x=$
