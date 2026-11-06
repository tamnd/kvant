---
id: 1990-8-resheniya-zadach-m1211-m1215-f1223-f1227-f3ce64c1
issue: kvant_1990_8
year: 1990
number: "8"
title: Solutions to problems M1211—M1215; F1223—F1227
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 46
page_last: 48
page_labels: 44-46
lang: en
source: kvant_digital
extraction: vision
content_sha256: a8fc6a48bd4e3700d0d6d046ff8702bcf5312cd10215a82bb96106890d561fbb
prompt_sha256: draft-1
translated_from: content/ru/1990/08/articles/06_resheniya-zadach-m1211-m1215-f1223-f1227-f3ce64c1.md
source_content_sha256: 727883b67c2b95e4d5cc67916d0f1ed848c30977cba7635ccb86ec53095aa727
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 44⟧

K. Zuev

Problem solutions
M1211—M1215, F1223—F1227

We will consider the selected plane to be horizontal. Let us draw two horizontal planes touching the ball and construct a terrahedron in which two opposite edges lie in these planes, are mutually perpendicular and equal to $a$ (Fig. 1); we will choose the correspondence between $a$ and the radius $R$ of the ball below.

A section of a ball by a horizontal plane located at a distance $R—h$ from the center of the ball, i.e. at a distance $h$ from one of the tangent planes and $2R—h$ from the other, is a circle of area $\pi(R^2—(R—h)^2)=\pi h(2R—h)$ (Fig. 2).

A section of a terrahedron by the same plane is a rectangle from the sides $ah/2R$ and $a(2R—h)/2R$ (it is clear that the length of each side of the rectangle is expressed

⟦folio 45⟧

---
running_head:
folio:
---

linear function of $h$, which at the ends of the segment $0 \leq h \leq 2R$ takes values ​​0 and $a$). The area of ​​this section is $a^2 h(2R - h)/4R^2$. So, it is enough to take $a = 2\sqrt{\pi}R$ so that the areas of the corresponding sections are equal.

N. Vasiliev

M1212. The set of all integers is divided into pairwise disjoint infinite arithmetic progressions with positive differences $d_1$, $d_2$, $d_3$, ... Could it happen that

$$\frac{1}{d_1} + \frac{1}{d_2} + \frac{1}{d_3} + \dots < 0,9?$$ (*)

Let's consider two cases: a) the number of progressions is finite;
b) the number of progressions is infinite (in this case, the condition (*) means that the sum of any finite number of terms on the left side (*) is less than 0.9).

Let the number of progressions be finite and equal to $k$. Let us prove that the sum of $1/d_1 + 1/d_2 + \dots + 1/d_k$ is equal to 1. Let $M$ be some (for example, the smallest) common multiple of the numbers $d_1$, $d_2$, ..., $d_k$. Consider any segment of $M$ consecutive integers; it will have $M/d_i$ terms of the $i$th progression with a difference of $d_i$ ($i = 1, 2, \dots, k$). Therefore $M/d_1 + M/d_2 + \dots + M/d_k = M$.

6) Answer: maybe.

Let us give an example of an infinite number of progressions for which the sum $1/d_1 + 1/d_2 + 1/d_3 + \dots$ is less than 0.9. Let us take as $d_1$, $d_2$, $d_3$, ... the numbers 4, 8, 16, ..., $d_k = 2^{k+1}$, ...; then $1/4 + 1/8 + 1/16 + \dots \leq 1/2$. We will build progressions sequentially, by induction. The first progression is numbers that are multiples of 4. For each $k > 1$, assuming that the first $k - 1$ have already been constructed, we will choose as one of the terms of the $k$th progression with a difference $d_k = 2^{k+1}$ the smallest modulo integer not included in the already constructed ones. Since $d_k$ is divisible by every $d_i$ ($i < k$), the $k$th progression does not intersect with the previous ones. On the other hand, progressions contain all integers without exception: in no more than $2k$ steps we will include in the progression every integer not exceeding modulo $k - 1$.

Similarly, for any $\varepsilon > 0$ one can construct an example in which $1/d_1 + 1/d_2 + 1/d_3 + \dots < \varepsilon$.

A. Tolpygo, N. Konstatinov

M1213. a) Prove that if a convex hexagon can be cut into parallelgrams, then it has center symmetry. b) Prove that if a convex hexagon in which each diagonal connecting opposite vertices is parallel to two sides can be cut into $N$ para-
a) Consider all parallelgrams of the partition in which one of the sides is parallel to another side $a$ of the hexagon. They form a “flow”, the section of which of any line parallel to $a$ has the same total width (Fig. 1). In fact, each parallel $a$ segment, consisting of one or more parallel sides, is adjoined above and below by a “flow” of the same width. Therefore, the second side of the hexagon, on which this flow comes out, will be parallel and equal to $a$.

(In passing, we see that each side of any parallelgram included in the partition is parallel to one

⟦folio 46⟧

---
running_head:
folio:
---

palelograms of equal area, then N is divided by 3.

Fig. 1.

Fig. 2.

one of the sides of the hexagon: it is also included in some of the "flow" that goes to the border of the hexagon.)

Analogous reasoning shows that the other four sides of the hexagon are divided into two pairs of parallel and equal sides. Obviously, parallel sides are opposite.

It remains to note that a convex hexagon with parallel and equal opposite sides necessarily has a center of symmetry: its three larger diagonals connecting opposite vertices intersect at one point - the common middle of these diagonals.

6) Now let the hexagon be such that its diagonals are parallel to its sides. According to the solution to problem a), they intersect at the center of symmetry of the hexagon, so they divide it into six triangles of equal area (Fig. 2). Let S be the area of ​​each of these triangles and s the area of ​​each of the N parallel frames into which the hexagon is divided, then Ns=6S. The total area of ​​the parallelrams of each thread connecting two opposite sides of the hexagon is 4S: it is equal to the area of ​​the two parallelrams protected by figure 2. Therefore, the thread must include 4S/s=2N/3 parallelrams. It follows that N is divisible by 3.

V. Proizvolov

M1214*. In some cells of a rectangular table of n rows and m>n columns, asterisks are placed so that each column contains at least one asterisk. Prove that there is an asterisk such that there are more asterisks in its row than in its column.

From the original table A with asterisks, we will build two new tables - “red” and “blue”, in which the asterisks are replaced by numbers: in the red table these numbers are equal to 1/k, where k is the number of asterisks in accordance with the column, and in blue these numbers are equal to 1/l, where l is the number of asterisks in accordance with the column. Then the sum of all red numbers is equal to m - the number of columns (in each column the sum is 1), and the sum of all blue numbers is no more than n - the number of rows (in each row the sum is 0 or 1). Since m>n, then there is an asterisk such that the corresponding red number 1/k is greater than the blue number 1/l: 1/k>1/l, whence k<l, i.e., the required condition is met for this asterisk.

In the same way, one can prove a stronger statement: in the conditions of the problem there is an asterisk for which
