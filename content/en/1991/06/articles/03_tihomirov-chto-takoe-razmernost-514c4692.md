---
id: 1991-6-tihomirov-chto-takoe-razmernost-514c4692
issue: kvant_1991_6
year: 1991
number: "6"
title: What is dimension?
authors:
  - Тихомиров В. М.
rubric: osnovnye-stati
page_first: 4
page_last: 11
page_labels: 2-9
lang: en
source: kvant_digital
extraction: vision
content_sha256: bc4e5cb29649623966cbe967520df26686c067b82ef0a8a510fad6d5df71c768
prompt_sha256: draft-1
translated_from: content/ru/1991/06/articles/03_tihomirov-chto-takoe-razmernost-514c4692.md
source_content_sha256: 1f7709a083b86fed1966d4360215b356b2bff8392ff9ed7bafec01f2fc117ff6
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 2⟧

---
running_head:
folio:
---

Doctor of Physical and Mathematical Sciences
V. TIKHOMIROV

"I see it, but I don't believe it"

One of the last articles of the great scientist Anir Poincaré (1854-1912), published in the collection “Last Thoughts” published after his death, was called “Why does space have three dimensions?” In this article, Poincaré ponders the question of what is the number of dimensions, or what is dimension.

When did people start thinking about this? Point, line, surface - how do they differ from each other? This was first written about in the very first lines of the very first of the additional books on mathematics before us - in Euclid’s “Elements” (IV-III centuries BC) *). Here they are, these first lines.

"Oh the limit

1. A point is something that has no parts.
2. A line is a length without width.
3. The ends of the line are points.
4. A surface is something that has only length and width.
5. The ends of the surface are lines.”

For many, these words can cause a smile: they are so unlike what is now commonly called definite, but here lies an attempt to comprehend the most important concepts, and we see how many cases of the first words of Euclid’s book with Poincaré’s “Last Thoughts” are present. But first things first. We will start now from a much later time than the third century BC. The starting point of our journey is Germany, centuries have passed since then. A young mathematician, Georg Cantor (1845-1918), is trying to prove that there are “more” points in a square than in a segment. But in the end he came to the post unexpectedly

to this result, he writes to his colleague with some confusion: “I see it, but I don’t believe it.”

What mathematical fact were we talking about here?

Is dimension a quantity?

Let two sets be given. When can you say that one of them has the same number of points as the other? Everything perfect is obvious for finite sets. Each of them can be recalculated, and if the numbers obtained during recalculation turn out to be the same, then this will mean that the number of elements in the two given sets is the same.

But for infinite sets everything is not so simple. Galileo also noted that the square of natural numbers is “the same” as mere numbers. Indeed, you can build two series of numbers

so that each natural number (the number in the top row) corresponds to one and only one number in the bottom row - the square of the number in the top row.

Cantor called two sets equal (or equivalent) if a one-to-one correspondence can be established between their elements (that is, a correspondence in which each element of one set corresponds to one and only one element of the other and vice versa). Equivalence is a term that for finite sets means that the given sets consist of the same number of elements, and for infinite sets equivalence by limit means that the sets are the same in the “number” of elements.

⟦folio 3⟧

---
running_head:
folio:
---

Equally powerful sets of the natural are combined into one class, attributing to them something common that is characteristic of all of them. This property, called power by Kant, characterizes, as it were, the “number of elements” in any set of a given class. Thus, the set of a set consisting of $n$ elements is equal to $n$. We have already seen that an infinite set can have as many elements as its subset (this is completely unthinkable for finite sets).

Let's look at two more examples.

Theorem 1. The set of pairs of natural numbers is equal to the set of all natural numbers.

Proof. Let us denote the set of pairs of natural numbers by $N^2$. The interaction between $N$ and $N^2$ can be established in many ways. Here is one of the simplest ones.

If $n = 2^{n_1-1}(2n_2-1)$, then the number $n$ is assigned the pair $(n_1; n_2)$. Since every natural number is uniquely decomposed into the product of a power of two and an odd number (say, $48 = 2^4 \cdot 3$), this interaction-to-interaction correspondence leads to the following arrangement in a series of pairs $(n_1; n_2)$:

$$
\begin{array}{c c c c c c}
1 & 2 & 3 & 4 & 5 \\
(1; 1) & (2; 1) & (1; 2) & (3; 1) & (1; 3) \\
6 & 7 & 8 & 9 & 10 \\
(2; 2) & (1; 4) & (4; 1) & (1; 5) & (2; 3) \\
\dots
\end{array}
$$

In this case, each pair of natural numbers $(p; q)$ receives the number $n = 2^{p-1}(2q-1)$. For example, the pair $(3; 4)$ is numbered $n=28$, the pair $(1; 50)$ is numbered 99.

It can be built differently. Let's arrange all the pairs in a table and number the pairs sequentially, going around them along the arrows (in this case, for example, the pair $(2; 3)$ will receive the number 8).*

Exercises
1. Specify the described method of numbering pairs using an explicit formula. What number will the pair $(99; 100)$ get?

*) This table is depicted on one of the obelisks associated with the memory of Cantor.

2. Establish the interaction between $N$ and the set of all rational numbers.

3. Establish the interaction a) between two segments; b) between the segment [0; 1] and interval (0; 1).

Let us now prove that the set of numbers in the interval $(0; 1)$ is equal to the entire number line $R$.

Indeed, the function $y = \text{ctg} x$ assigns to each $x \in (0; 1)$ one and only one $y \in R$ and vice versa. Another example of the equal power of a set and its part!

The question immediately arises: is it not possible to reread all the elements of any set in the same way as we reread the set $N^2$? It turns out that this is not always the case.

We call an infinite set $A$ countable if it can be reread and odd otherwise.

Theorem 2 (Cantor). The interval $(0; 1)$ is odd.

Proof. Let's argue by contradiction. Let the passage be re-read. Let's write each point of the segment as a decimal fraction. Such a notation, generally speaking, is insignificant $(0,1=0,0999...)$, but it becomes unambiguous if we agree that finite fractions of the form 0.1, 0.25, etc. are written as 0.0 (9) (nine per period) 0.24 (9), etc., i.e. finite decimal fractions are written

⟦folio 4⟧

---
running_head:
folio:
---

through nines in the period. So, the empty numbers from $I$ are listed, i.e.
$I = \{x_1, x_2, \ldots\}$, where
$$x_1 = 0, x_{11}x_{12} \ldots x_1 n \ldots,$$
$$x_2 = 0, x_{21}x_{22} \ldots x_2 n \ldots,$$
......

and $x_{ij}$ take values ​​from zero to nine and there are no numbers that, starting at some point, have one zero.

Consider the decimal fraction $\alpha = 0, y_1y_2 \ldots$, where $y_i = 1$ if $x_{ii} \neq 1$, and $y_i = 2$ if $x_{ii} = 1$ (this process is called diagonal because we consider the numbers $x_{ii}$ on the diagonal and change them). The number $\alpha$, is placed, takes $I$. If $I$ can be enumerated, then $\alpha$ must have some number, say $N$, i.e. $\alpha = x_N$. But then $\alpha = 0, x_{N1} \ldots x_{NN}$, which is not the case, or by construction, $y_N \neq \bar{x}_{NN}$.

The resulting contradiction proves the theorem.

So maybe the dimension is related to the number of points? After all, it seems clear that there are more points in a square than in a segment, and more in a cube than in a square. But no! Cantor proves the theorem that the number of all points in a segment and in a square are the same.

It was about this theorem that it was said: “I understand this, but I don’t believe in it!”

Theorem 3. The segment $I$ and the square $I^2$ are of equal size.

Let us outline the proof of this theorem. Consider a square $I^2$ consisting of points $(x_1; x_2), 0 \leqslant x_1 \leqslant 1, 0 \leqslant x_2 \leqslant 1$. As before, let us decompose the numbers $x_1$ and $x_2$ into decimal fractions, where the final decimal fractions are written through nines in the period:

$$x_1 = 0, \alpha_1 \ldots \alpha_n \ldots,$$
$$x_2 = 0, \beta_1 \ldots \beta_n \ldots,$$

and put in accordance with pale $(x_1; x_2)$ the number

$$y = 0, \alpha_1 \beta_1 \alpha_2 \beta_2 \ldots \alpha_n \beta_n \ldots.$$

In this case, different parameters correspond to different numbers, i.e., the set of all pairs is equivalent to some subset of the segment $I$, and therefore the cardinality of $I^2$ does not exceed the cardinality of the segment $I$. On the other hand, the power of $I^2$ is not less than the power of $I$ (the square contains how many angle segments), so $I$ and $I^2$ are equivalent.

Here we have implicitly used the statement that the cardinality of a subset is not greater than the cardinality of the set itself, and the fact that cardinalities can be compared.

Emphasizing
4. Prove that a square and a circle are equivalent.
5. Prove that the segment $I$ is equivalent to the Poincaré system.

He writes: “What is the oppositeness of $n$ dimensions, how does it differ from the oppositeness with a greater or lesser number of dimensions? Let us first recall some results recently obtained at Cantor's school. It is possible to establish a one-to-one correspondence between points on a line and a plane*). This is possible as long as we do not bind ourselves to the conditions that two close points on a straight line correspond to close points on the plane and on the other side.”

From these words it is clear that Poincaré considered it impossible to have a mapping $x \rightarrow F(x)$ that would map the segment $I$ onto a square and would at the same time be one-to-one and continuous in both directions (i.e., both the mapping itself and its inverse must be continuous). Let's continue counting.

“I want to base the definition of the number of dimensions on the concept of section. Let us imagine a closed curve, that is, the opposite of one dimension. If we mark any points on this curve through which we forbid crossing, then the curve will be cut into two parts and it will be impossible to move from one part to another without crossing the given points.

*) This is precisely what was discussed in Theorem 3.

⟦folio 5⟧

---
running_head:
folio:
---

Let us take, on the contrary, a closed surface that forms an extension of two dimensions. We can place one, two, or any number of forbidden points on it, without this the surface being broken into parts.”

The words of Poincaré given here form the content of the following theorem.

Theorem 4. There is no one-to-one and continuous in both directions mapping of a segment to a square.

Proof. Let such a mapping $\hat{F}$ exist. Let us consider in a square the images $\hat{F}(0)$, $\hat{F}(1/2)$ and $\hat{F}(1)$ of three points: 0, 1/2 and 1. Let us connect $\hat{F}(0)$ and $\hat{F}(1)$ with a broken line lying entirely in the square and not passing through the point $\hat{F}(1/2)$, which is obviously always possible (at figure 1 $\hat{F}(0)$ and $\hat{F}(1)$ are connected by a segment). We will now move along this broken line from $\hat{F}(0)$ to $\hat{F}(1)$. Our path along the broken line into a square corresponds to a continuous path on the segment from zero to one. But on this path it is necessary to meet point 1/2, and on the path along the broken line (due to the choice of this broken line) point $\hat{F}(1/2)$ will not be encountered. We have arrived at a contradiction. The theorem has been proven.

Poincaré further writes: “Let us now turn to the case of space. It cannot be divided into several parts, neither by prohibiting crossing individual points, nor by prohibiting crossing individual lines. It will be necessary to prohibit transitions through individual surfaces, that is, certain sections of two dimensions. Here

Fig. 1.

⟦folio 6⟧

---
running_head:
folio:
---

mathematician Menger and (to the most extent) Soviet mathematicians Pavel Samuilovich Urson (who tragically died in 1924 at the age of 26) and Pavel Sergeevich Aleksadrov.

But it turned out that the inductive method of determining dimension is not the only one. Another completely unexpected approach to answering the question of why space has three dimensions is possible. This approach is associated with the names of remarkable mathematicians of the 20th century - the French mathematician A. Lebesgue and the already mentioned L. Brouwer.

**Lebesgue-Brower theorem**

Suppose you need to divide a large round (or square) plot of land between several tenants, and in order to avoid scandals, you want as few tenants as possible to be adjacent to each other at the same time. So, on figure 2, a tenants A, B, C, D are adjacent to each other, on figure 2, b (brick class) no more than 3 tenants are adjacent to each other in pairs. The question arises: is it possible to arrange the division in such a way that there are no three tenants adjacent to each other in pairs?

Note that with a similar division of the road, such a division is possible (Fig. 3).

It may seem that a round section can be divided as needed by cutting it “into noodles”, as in figure 4. But this is inconvenient - the sections are too long.

For the purpose of definition, let the radius of a circular plot be 1 km, and the diameter (the largest distance between two points) of each plot should be less than, say, 250 m.

Then, no matter how you try to divide a round plot into “allotments”, it is necessary to find another at least 3 tenants whose allotments are adjacent in pairs, like plots A, B, B on figure 2, and this statement is the content of the theorem, first proven by A. Lebesgue.

**Theorem 5. For any partition of an n-dimensional cube (sphere) into parts of sufficiently small diameter, there will be n+1 parts that have a common boundary point. (We have n=1, 2, 3, under the n-dimensional cube it is clear that the corresponding segment, square and cube.)

This theorem allows us to define dimension.

Determined. A given set A lying on a plane (or in space) has dimension n if, for any partition of it into parts of sufficiently small diameter, there are n+1 parts that have a common boundary point, and for any ε>0 there is a partition into parts with a diameter less than ε such that no n+2 parts have a common boundary point.

From this definition, the considered examples and Theorem 5 it immediately follows that the dimension of the segment is equal to 1,

**Fig. 2.**

**Fig. 4.**

⟦folio 7⟧

---
running_head:
folio:
---

The dimension of a square is 2, the dimension of a cube is 3.

Lebesgue's proof of Theorem 5 contained problems that Brouser was able to solve using the amazing fixed point theorem he proved.

Theorem 6. When a circle is continuously mapped into itself, it has a fixed point*).

Let's explain this. Imagine that you invited guests to your place, and they indulged in such fun. From a round table, entirely covered with a well-stretched tablecloth, your guests tore the tablecloth and began to stretch it, peel it off, fold it, and finally threw it back onto the table, where it was crumpled, where it was crumpled, where it was rolled up, where it was stretched out, a piece of materials that had previously been your tablecloth. Then (Browser’s theorem states), if this piece was not torn anywhere and fit entirely on the table, at least one point of the tablecloth did not change its position.

As a matter of fact, we will not even need Browser’s theorem itself, but also a corollary from it. Let's say that after the disgrace that your guests did to the tablecloth, you threw out the old tablecloth and in the middle of the bed stood a small round napkin - with the center in the center of the table. But again the guests got angry and began to pull the napkin in different directions (and also fold it, peel it off, etc., without tearing it). Then, if no point on the napkin has shifted by more than half its radius, you can be sure that the center was covered by what was previously your poor napkin. And not only the center, but also any point less than half the radius of the napkin from the center.

This statement is easy to believe as it is, but it’s quite easy to derive it from Browser’s theorem. Indeed, the path of our napkin is a circle of unit radius and, by the will of the guests, each point $X$ of this circle is continuously placed in correspondence with a point of the plane $F(x)$ so that the length of the segment $[X; F(x)]$ is less than 1/2. Let us assume that some points $x_0$, located at a distance less than 1/2 from the center of the circle, are not covered, i.e., for every $x$ the correspondence $F(x) \neq X_0$ is satisfied. Then we will construct the following continuous mapping of our circle: to point $X$ we will associate point $G(x)$ on the border of the circle so that point $X_0$ lies inside the segment $[F(x); G(x)]$ (Fig. 5). It is possible to prove that such a mapping is indeed continuous (and even give an explicit formula for $G(x)$). It follows from the construction, of course, that the distance from $F(x)$ to $G(x)$ is greater than 1/2. But, on the other hand, it is clear that no point of the circle when displaying $X \rightarrow G(\bar{x})$ can be fixed, or the fixed point $\bar{x}$ must lie on the boundary circle and then, by construction, the distance from $\bar{x}$ to $F(\bar{x})$ (and this is the same as the distance from $G(\bar{x})$ to $F(\bar{x})$ (for $\bar{x} = G(\bar{x})$) was greater than 1/2, which contradicts the main assumption. But such a continuous mapping of a single circle into itself, according to Browser’s theorem, has not been proven.

And now it’s time to move on to the proof of the Lebesgue-Browser theorem itself, i.e., to an explanation of the fact that the dimension of a circle is equal to two.

It is clear that the dimension of a circle is no more than two, or with a “brick class” it is possible to divide any circle into several angularly small parts so that they intersect no more than three at a time. Thus, it remains that the dimension of the circle is not equal to one.

⟦folio 8⟧

---
running_head:
folio:
---

Let's assume that it is still equal to one. Imagine yourself then in the role of chairman of a dacha cooperative, which has been allocated a round plot of land (with a radius of, say, one kilometer), and you need to cut out plots for shareholders. It is possible that if you learned that the dimension of a circle is equal to one, you would be very concerned: after all, it would make you aware that it is possible to cut up areas so that no three shareholders would simultaneously be neighbors of each other and all would be neighbors only in twos. Isn’t it great: there are fewer reasons for disputes and disagreements!

Alas, this turns out to be impossible unless we require that the diameter of each section be small enough, say, no more than 250 m. This is exactly what we will prove.

Let there be two plots of land somewhere that belonged to neighbors - Andrei and Boris. Both of them are civilized people and therefore did not divide their territories with a fence, but from between, dividing their areas by law, they each retreated somewhat in their own direction, drew new boundaries and declared the territory between them common (see Fig. 6, a). The following simple construction is the epicenter of the entire proof. Let’s select some point on Andrey’s plot and designate it by the letter $A$, and on Boris’ plot we’ll choose point $B$. Let us now construct a mapping of common areas (both Andrey and Boris) onto the segment $AB$ according to the following rule. If each point lies on Andrey’s territory and is not common, it is displayed in $A$, similarly, a non-common point on Boris’ territory is displayed in $B$. If the point $X$ is “common”, then the point of the segment $AB$ is assigned to it, making this segment in relation to $d(X, A):d(X, B)$, where $d(X, A)$ is the distance from $X$ to the Andreevsky site, and $d(X, B)$ is the distance from $X$ to the Boris site.

And now we are almost there. Let’s say we managed to divide that circular section of a kilometer radius so that the sections are adjacent only in pairs and the diameters of the sections are less than 250 m.

Let's take a point on each of the sections - let it be the points $A_1, A_2, ..., A_s$ (on figure 6, b these are the vertices of the red triangles) - and for any two neighboring sections we will construct sequentially the same mappings that we just carried out for the sections of Andrey and Boris. It is only necessary to take care that points common to three neighbors do not appear - for this “deviation” from the boundary between

⟦folio 9⟧

---
running_head:
folio:
---

when allocating a common territory, they should be quite small*).

From the construction it is clear that any point will be compressed by no more than 500 m (prove it!) and the entire larger circular area with a radius of a kilometer will be mapped into a certain set of segments $[A_i; A_j]$. These set of segments cannot, of course, cover any circle, but according to the corollary of Browser’s theorem, we would have to cover a whole circle with a radius of 500 m. We have arrived at a contradiction. This means that the dimension of the circle is two.

This completes the proof of the Lebet–Browser theorem for $n=2$. Case $n=3$ is similar.

Exercise 6. Think for yourself and get an answer to the question posed by Poincaré: why does space have three dimensions?

In conclusion, there is little left to say. The central point in the argument - the construction of a continuous mapping of two areas onto a segment - is a two-new property of Pavel Sergeevich Aleksandrov. P. S. Aleksandrov owes his worldwide fame and his position as a recognized leader of Soviet topologists, which he occupied for several decades, to a large extent to the insight that came to him (according to him, while thinking through a certain Poincaré construction) and led to a construction, the grain of which we have reproduced. With the help of this construction, it was possible to understand a lot, and in particular, as we see, to prove the Lebet-Browser theorem.

And it seemed to me a remarkable idea to tell you in a short and relaxed conversation about a complex that has not only mathematical, but also general cultural significance, about the solution to a problem that has occupied scientists for twenty-three centuries, about the inclusion of Euclid, Cantor, Lebesgue, Browser and Alexandrov in this solution, about the question that Ani Poincaré was thinking about in the last years of his life.
