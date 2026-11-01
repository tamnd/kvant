---
id: 1979-4-gindikin-arifmetika-na-kletchatoy-bumage-9d916a6a
issue: kvant_1979_4
year: 1979
number: "4"
title: Arithmetic on checkered paper
authors:
  - Гиндикин С. Г.
rubric: kvant-dlya-mladshih-shkolnikov
rubric_sub: «Квант» для младших школьников
page_first: 40
page_last: 44
page_labels: 38-42
tag: AGZF
lang: en
source: kvant_digital
extraction: vision
content_sha256: a3321cbc857311d5e6e71eb7970d51de909484f5b06da2abaae1863f969c0f09
prompt_sha256: draft-1
translated_from: content/ru/1979/04/articles/15_gindikin-arifmetika-na-kletchatoy-bumage-9d916a6a.md
source_content_sha256: a8a767f73270dbde164dc1a645c1a531c9c7d6666562c12296c9ec2abb76f5f7
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 38⟧

S. Gindikin

Arithmetic on checkered paper

Why is the math notebook squared? This question is sometimes asked by first-graders who are not very comfortable writing numbers in the boxes. Then they learned that it is convenient to make geometric drawings on checkered paper. It turns out that by drawing various numbers on checkered paper, you can learn a lot of interesting things about arithmetic.

The method of representing numbers with figures on checkered paper goes back to ancient times - to the mathematics of Ancient Babylon, Egypt, and Greece. Of course, then mathematicians did not line clay tablets or papiers into squares, but made figures from dots. We will use checkered paper.

In Ancient Greece, a number equal to the product of two natural factors was called a flat number: it was associated with points located in the form of a rectangular lattice (Fig. 1). We will agree to depict a flat number as a rectangle on checkered paper and count the number of cells in it.

Properties of multiplication good or constructed by drawings. For example, the distributive law (the rule for opening parentheses) corresponds to cutting a rectangle into smaller rectangles (Fig. 2). The name “flat number” is now obliterated, and the word “square”, denoting the product of equal simulators, has been preserved to this day.

Squares and gnomons

Odd numbers were depicted in Ancient Greece using angular only

3×(2+2)=3×2+3×2
(1+3)×(2+4)=1×2+1×4+3×2+3×4

Fig. 1.

Fig. 2.

⟦folio 39⟧

tire in one cell - economy (Fig. 3). The first argument we will give concerns squares and gnomons; it belongs to Nicomachus of Geraz, who lived around the 1st century.

Let's draw several squares and gnomons in a row (Fig. 4). Isn't it true, every gnomon wants to add a square to some; this will result in the following square (Fig. 5). This observable means that every odd number is spread apart by two consecutive squares.

Now let's add several gnomons in a row, starting with the smallest. The result will be a square (Fig. 6). This means that the sum of consecutive odd numbers, starting from the first, is a square: 1+3=4, 1+3+5=9, 1+3+5+7=16, etc.

Pythogoras and the Pythogoreans

The gifted sage Pythogor (VI century BC), loved to travel, and in his teaching I draw a lot from eastern wisdom.

The Pythogoreans are characterized by a mystical attitude towards numbers. They collected all kinds of numerical “curiosities,” seeing in them a manifestation of lateral forces. With the help of numerical images, the Pythogoreans were able to express their thoughts and feelings. Even numbers are called feminine, odd numbers are called masculine. The Pythogoreans especially valued the number 10=1+2+3+4 (Fig. 7), calling it excellent or metrade, and swore by “the one who put the tetrad into our soul - the source and root of eternal nature.” Numbers equal to the sum of their (corresponding to x) divisors (6=1+2+3) were called perfect, and Nicomachus knew four perfect numbers: 6, 28, 496, 8128. The friend was symbolized by pairs of other locative numbers, each of which is the sum of the (own) divisors of another number. For example, the numbers 284 and 220 are different: 284=1+2+4+5+10+20+11+22+44+55+110,220=1+2+4+71+142.

But since there are “good” numbers, there must also be “bad” ones. It's "bad" if a number has no merit; it's even worse if it's surrounded by interesting numbers. The fear of the number 13 - the “devil's dozen” - is striking in its immortality. But it's a bit packed. Here is what Plutarch writes: “The Pythogoreans have an aversion to the number 17. For 17 lies precisely divided between the number 16, which represents a complete square, and the number 18, which is a double square; both of these numbers are the only flat numbers for which the perimeter (of a rectangle) is equal to its area...” In other words, ut-

⟦folio 40⟧

Fig. 7.

Fig. 8. Ancient Babylonian clipart text.

It is said that if the product of two numbers (natural numbers, of course) is equal to their double sum, then it is either a pair of 3 and 6, or a pair of 4 and 4 (why?).

Pythagoron triples

There is a legend according to which Pythagoras, in honor of one of his discoveries, sacrificed either one bull or his own bulls. Vitruiny claims that the table appeared to Pythagoras as the discovery of two squares, the sum of which is equal to the third square *). We are talking about matching $3^2+4^2=5^2$. Teleri triples of natural numbers $a, b, c$ for which $a^2+b^2=c^2$ are usually called *Pythagorean* triples. It turns out that the Pythagorons already knew the triples in Babylon (Fig. 8). Gradually, Greek mathematicians also found them.

Let's try to understand how we can find the Pythagorons of the triple. Let's remember

*) However, other sources indicate other reasons. There is also an opinion that there was no sacrifice at all, since sacrifices contradicted the philosophy of the Pythagoreans.

that every odd number is represented as the difference of two consecutive squares. Then the odd square, together with the squares of which it is the difference, form a Pythagorean triple. For example, $3^2=9=2\cdot4+1=5^2-4^2$ (Fig. 9). This produces the triple 3, 4, 5. Similarly, $5^2=25=2\cdot12+1=13^2-12^2$, whence $12^2+5^2=13^2$; $7^2=49=2\cdot24+1=25^2-24^2$, from where $24^2+7^2=25^2$. This way we get all the Pythagorons of the triple $a, b, c$ that have $c=a+1$. Their general appearance:

$$a = \frac{m^2-1}{2}, \quad b = m, \quad c = \frac{m^2+1}{2}$$

(m is odd!). Prove it. How to find all the Pythagorons of the triple?

General problem of Pythagorean triplets

The accumulated experience suggests that it is necessary to investigate the difference of any two x (and not just adjacent) squares $c^2-a^2$, where $c>a$. The result is a “thick gnomon” with a thickness of $c-a$ cells (Fig. 10). The problem, therefore, indicates a description of all possible ways of transforming (without changing the number of cells!) the square $b^2$ into some “thick gnomon”.

The first observation is that the "fat gnomon" can be transformed into a rectangle (flat number!) from the length side $m=c-a$ and $n=c+a$ (Fig. 11; we got a geometric proof of the formula $c^2-a^2=(c-a)(c+a)$). The question arises which flat numbers can be converted into “fat gnomons”. It is clear that the numbers $m=c-a$ and $n=c+a$ are not equal to each other and are either both even and odd at the same time - there are no other restrictions. So, if there is a rectangle that is not a square, the side lengths $m$ and $n$ have the same parity, then it can be transformed into a “thick gnomon”, which is the difference of squares

$$c^2 = \left( \frac{m+n}{2} \right)^2 \quad \text{и} \quad a^2 = \left( \frac{m-n}{2} \right)^2$$

(under our assumptions, the numbers $m+n$ and $m-n$ are even and non-zero).

⟦folio 41⟧

Fig. 9.

So, we have reduced the problem of finding Pythagorean tracks to the question of how the square $b^2$ can be transformed into a rectangle with sides of length $m, n$ of the same parity ($m \neq n$). This problem can be easily solved. Let $r \neq b$ be a divisor of $b^2$ (but not necessarily a divisor of $b$) for which $\frac{b^2}{r}$ has the same parity as $r$. In this case, $r$ must be of the same parity as $b$, although this condition is not sufficient (why?). Then a rectangle with sides of lengths $m = r$ and $n = \frac{b^2}{r}$ can be transformed into a “thick gnomon”, which is the difference of squares

$$c^2 = \left[ \frac{b^2/r + r}{2} \right]^2 \text{ и } a^2 = \left[ \frac{b^2/r - r}{2} \right]^2.$$

Note that $r$ can equal 1 and that we can limit ourselves to the divisor $r < b$ (why?).

So, all Pythagorean trikes have the form

$$a = \frac{b^2 - r^2}{2r}, \quad b, \quad c = \frac{b^2 + r^2}{2r},$$

where $1 \leq r < b$ is a divisor of $b^2$ such that $r$ and $b^2/r$ have the same parity (the same as the parity of $b$). Use Pythagoras tracks automatically. Try this; for control we provide a table -

In the table there are triples $a, b, c$, differing only by the permutation of the numbers $a$ and $b$; this is explained by the fact that in the Pythagorean trifecta $a$ and $b$ can be interchanged. Moreover, we see that there is no Pythagorean triple with $b=2$: in this case there is no suitable divisor $r$

⟦folio 42⟧

Fig. 13.
(the condition $r < 2$ is satisfied only by the natural number $r=1$, but one is an odd number). For all other $b$ at least one Pythagorean triple exists. If $b$ is odd, then we can take $r=1$; in this case it turns out $a$ and $c$, perfectly drained by one (we considered this case at the very beginning). If $b \neq 2$ is even, then we can take $r=2$; this produces triplets with $c-a=2$ (why?).

Triangular numbers
In clipart tablets the sum of the first $n$ natural numbers is calculated: $1+2+3+\dots+n$. Such sums began to be called triangular numbers, since a triangle can be formed from the points corresponding to the terms (Fig. 12). It is more convenient to draw a figure on checkered paper, for example a ladder (Fig. 13): in each next row of the ladder there is one more square than in the previous one. To make up the number of cells in the ladder (equal to the required amount), let’s draw another similar ladder, but turn it upside down; after which we “twist” both ladders (Fig. 14). The teeth of the stairs are connected and you get a rectangle, the length of one side is $n$, and the other is $n+1$. In such a rectangle there are $n(n+1)$ cells; on the stairs -

Fig. 14.
half as much, i.e. $\frac{n(n+1)}{2}$
Thus,
$$1+2+3+\dots+n=\frac{n(n+1)}{2}.$$
Problem 1. Using ladders, find the sum $1+3+5+\dots+(2k+1)$ of odd numbers; the sum $2+4+6+\dots+2k$ of odd numbers, the sum $1+4+7+\dots+3k+1$ of numbers of the form $3k+1$ (we have already found the first of these sums using gnomons).

The next problem is related to another interesting observation of Nicomachus:
Problem 2. Make sure that the gnomon, which is the difference square of adjacent triangular numbers, is a cube, more
$$\left[\frac{n(n+1)}{2}\right]^2-\left[\frac{(n-1)n}{2}\right]^2=n^3.$$
From this relation Nikomakh obtained a formula for the sum of cubes
$$1^3+2^3+\dots+n^3=\left[\frac{n(n+1)}{2}\right]^2.$$
To prove it, it is enough to collect all the gnomons corresponding to the neighboring triangular number.
