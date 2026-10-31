---
id: 1971-7-bendukidze-arhimed-i-kvadratura-parabolyi-c0489705
issue: kvant_1971_7
year: 1971
number: "7"
title: Archimedes and the quadrature of the parabola
authors:
  - Бендукидзе А. Д.
rubric: osnovnye-stati
page_first: 10
page_last: 12
page_labels: 8, 10
tag: E7C7
lang: en
source: kvant_digital
extraction: vision
content_sha256: 954917ed3ba9b98fa2fadada8623be9d1c2dffe4900b0b4165ca7dd25c7f4700
prompt_sha256: draft-1
translated_from: content/ru/1971/07/articles/02_bendukidze-arhimed-i-kvadratura-parabolyi-c0489705.md
source_content_sha256: b3032a6f3dea2d4c82cc6bde904819132e55ae9a806a49279d911acf7e390512
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 8⟧

Fig. 1.

We will introduce the reader to the contents of the second part of the work.

1. Let us formulate one remarkable property of the parabola *), on which the entire subsequent presentation is based.

If the line $AB$ touches the parabola at the point $P$ and the chords $A_1B_1, A_2B_2, A_3B_3$, ... are parallel to this tangent, then the midpoints of the chords - points $C_1, C_2, C_3$, ... - lie on the same straight line; this line is parallel to the axis of the parabola and passes through the point $P$ (Fig. 1).

Besides,

$$\frac{A_1C_1^2}{PC_1} = \frac{A_2C_2^2}{PC_2} = \frac{A_3C_3^2}{PC_3} = \dots$$ (1)

Try to prove these properties of a parabola yourself.

2. Let us now consider a parabolic segment bounded by another parabola $APB$ and a chord $AB$ (Fig. 2).

The point of the parabola $P$, the tangent at which is parallel to the chord $AB$, is called the vertex of the segment, and the sum of the chord $AB$ is the base of the segment. Middle of the base. According to property (1), the straight line $PC$ is parallel to the axis of the parabola.

*) Recall that a parabola is the locus of points on a plane that are equidistant from a certain point and do not pass through a line. In accordance with the definition of a parabola, a point on the parabola is a point where the distance from the vertex to the focus is equal to the distance from the focus to the directrix.

⟦folio 10⟧

Let us prove one remarkable property of this sequence, namely, we will prove that for any $n$ the following equalities hold:

$$s_1 + s_2 + \dots + s_{n-1} + s_n + \frac{4}{3} s_n = \frac{4}{3} s_1.$$

(6)

In fact, since $4(s_1 + s_2 + \dots + s_{n-1} + s_n) = 4s_1 + (4s_2 + 4s_3 + \dots + 4s_{n-1} + 4s_n)$, it follows from correspondences (5) that $4(s_1 + s_2 + \dots + s_{n-1}) + 4s_n = 4s_1 + (s_1 + s_2 + \dots + s_{n-1})$, that is, $3(s_1 + s_2 + \dots + s_{n-1}) + 4s_n = 4s_1$.

Equality (6) is obtained from here by dividing by 3.

6. Now we can prove that the area of ​​the parabolic segment is $S = \frac{4}{3} s_1$.

Archimedes proves this equality by the so-called “method of exhaustion.” This method, which belonged to one of the greatest Greek mathematicians, Eudoxus (IV century BC), replaced the method of passage to the limit during the time of Archimedes.

Let's assume $S > \frac{4}{3} s_1$ or $S < \frac{4}{3} s_1$.

Let us prove that this is impossible.

Let us first assume that $S > \frac{4}{3} s_1$.

We have already noted that by continuing the process of inscription, it is possible to ensure that the sum of the areas of the remaining segments is as small as possible. This means that by selecting $n$ appropriately, the difference $S - (s_1 + s_2 + \dots + s_{n-1} + s_n)$ can be made less than any predetermined positive number. Let us select $n$ so that the equality $S - (s_1 + s_2 + \dots + s_{n-1} + s_n) < S - \frac{4}{3} s_1$ holds. Then $s_1 +$

$s_2 + \dots + s_{n-1} + s_n > \frac{4}{3} s_1$, and this, according to equality (6), is impossible *. Thus, inequality (7) is false.

Let us now assume that

$$S < \frac{4}{3} s_1.$$

(8)

Since the terms of sequence (4) tend to zero, $n$ can be chosen so that the following equality holds:

$$\frac{4}{3} s_n < \frac{4}{3} s_1 - S.$$

From this inequality, taking into account equality (6), we obtain

$$S < s_1 + s_2 + \dots + s_{n-1} + s_n$$

which, of course, is impossible.

So, inequality (8) is also false. This proves that $S = \frac{4}{3} s_1$.

7. In conclusion, let us make the following remark.

As is known, the ancient Greeks understood by squaring a figure the construction of a square equal in size to this figure. The problem of quadrature in the “Greek sense” does not always have a solution. It has been proven, for example, that for a circle it is unsolvable. That is, it is impossible to construct (using a compass and ruler) a square equal in size to a given circle.

The result obtained by Archimedes is also remarkable in the sense that it shows the possibility of a positive solution to the problem of quadrature of a parabolic segment: knowing the base and height of a segment, it is always possible to construct a square equal in size to this segment.

*) We assumed that $S > \frac{4}{3} s_1$, therefore $S - \frac{4}{3} s_1$ is a positive number.
