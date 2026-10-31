---
id: 1974-8-toom-vstupitelnaya-kontrolnaya-rabota-v-vzmsh-v-1974-godu-resheniya-zadach-e3e8ff2b
issue: kvant_1974_8
year: 1974
number: "8"
title: Introductory test at VZMSH in 1974. Problem solutions
authors:
  - Тоом А. Л.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 42
page_last: 45
page_labels: 40-43
tag: ITUM
lang: en
source: kvant_digital
extraction: vision
content_sha256: 616cde4aab15c36a4161aad10949e6ad3b1b025079b37d65eff51d579c5ea292
prompt_sha256: draft-1
translated_from: content/ru/1974/08/articles/09_toom-vstupitelnaya-kontrolnaya-rabota-v-vzmsh-v-1974-godu-resheniya-zadach-e3e8ff2b.md
source_content_sha256: 1593b6d08c82cd185f6b0fe341dd8b1f66db1c346b3b5ac6e0da4377d533eea6
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 40⟧

Entrance test at VZMSH in 1974
Problem solutions
A. L. Toom

In this issue we publish solutions to the most interesting problems from the introductory work at the VZMSH in 1974 (see «Kvant», 1974, No. 1, p. 73).

Task 1. Three other cheeses played several games of chess, and each two played the same amount of games against each other. They began to decide who won.

The first one said: “I have more than each of you above.” The second one said: “I have less than each of you, simpletons.” But when the points were counted, it turned out that the prime minister scored the most points (winners - 1 point; draw - 1/2 point, drives - 0). Could there be a poppy? If not, prove it; if yes, give an example.

Yes, that could be the case. Here is an example that proves this. Let each two cheese 7 games, and of them:

the first won two games against the second;

the second won three games against the third;

the third won four games against the third.

The remaining games ended in draws.

Task 2. Are there three positive integers a, b, c such that a is less than 1974, b is 1575 less than c and a² + b² = c²?

Yes, such numbers exist. We could simply write them out, but we'll explain how to find them and show that this trio of numbers is unique.

According to the conditions,
$$\begin{cases} c^2 - b^2 = a^2, \\ c - b = 1575, \\ a < 1974. \end{cases}$$

From this system it is clear that $a^2$ is divisible by 1575=3²·5²·7. Therefore $a$ is divisible by 3·5·7=105.

Let's put $a = 105$ k. From inequality $a < 1974$ it follows that $1 \leq k \leq 18$. Then
$$c = \frac{1}{2} (7k^2 + 1575),$$
$$b = \frac{1}{2} (7k^2 - 1575),$$
whence $k > 15$. With $k = 16$ and $k = 18$ the number $b$ is not an integer. Only $k = 17$ remains. Then
$$a = 1785, b = 224, c = 1799.$$

It is easy to verify that these numbers satisfy the conditions.

Task 6. Point $D$ lies on the bissertrix of angle ACB. We chose points $A_1$ and $A_2$ on ray AC, and points $B_1$ and $B_2$ on ray CB, assuming that the integral points $A_1$, $C$, $B_1$, $D$ lie on the same circle and the integral points $A_2$, $C$, $B_2$, $D$ lie on the same circle. Prove that $A_1A_2 = B_1B_2$.

Let us introduce the following notations: $CD = a$, $\rightarrow ACD = \rightarrow BCD = \alpha$. We need to do two similar constructions. In order not to write the same thing twice, we introduce the variable $n$, which takes two values: 1 and 2, and describe the construction once, using the variable $n$ (see Fig. 1). Let's continue

⟦folio 41⟧

Fig. 1.

AC beyond point C to segment CEₙ = CBₙ. Let us plot on arc CBₙD arcs DFₙ equal to arc CBₙ. Obviously, ⇒CDFₙ = α and DFₙ = CBₙ = CEₙ. Therefore, taking into account the correspondence ⇒AₙCD = ⇒CDFₙ, we obtain that CDFₙEₙ is a parallelogram, and EₙFₙ = CD = α. Further, ⇒CAₙFₙ = ⇒CDFₙ, since they rest on one arc CFₙ; therefore ⇒EₙAₙFₙ = α.

Thus, in the triangle EₙFₙAₙ
EₙFₙ = FₙAₙ = α,
⇒EₙFₙAₙ = 180° - 2 α.

Posibly, the triangles E₁F₁A₁ and E₂F₂A₂ are equal according to the first criterion.

Fig. 2.

Then
E₁A₁ = E₂A₂,
B₁C + A₁C = B₂C + A₂C,
B₁C - B₂C = A₂C - A₁C,

whence B₁B₂ = A₁A₂, which is what needed to be proved.

Task 7. 1974 numbers were written out for construction. Every two numbers written by two adjacent digits (in the order in which they are written) are divisible by 17 or 23.

a) Last digit 1. What is the first?
b) The first digit is 9. What is the last one?

It is convenient to draw a “graph” (a diagram of arrows) as shown in figure 2. In it, an arrow from the number x to the number y means that y can follow x, that is, with two numbers xy is divided by 17 or 23.

We see that only 5 can be in front of 1, only 8 can be in front of 5, and so on, each digit uniquely determines the previous one. Moreover, if we follow the arrows back from the number 1, then the numbers starting from 6 are repeated with a period of 5. Therefore, if the 1974th number is 1, then the 1971st number is 6, and since then there is a repetition with a period of 5, then the first number is also 6.

Now let the first number be 9. Let's follow the arrows forward. After 9 there can only be 2, after 2 only 3, after 3 only 4, after 4 only 6, but after 6 there can be both 9 and 8.

But after 8 there should be 5, 1, 7, but after 7 nothing can appear.

Thus, 8 can appear no earlier than in the 1971st place, and until then only 9 can appear after 6. The number 6 first appeared in the 5th place and will be repeated with period 5. This means that in the 1970th place there will be a 6. In 1971, as we found out, there may be 9 or 8, and in the 1974th place there may be 4 or 7.

Task 8. The perimeter of a convex quadrilateral ABCD is 10, its sides AB and CD are parallel.

⟦folio 42⟧

Find the lengths of all sides if it is known that the bisectors of angles A and B of the quadrant divide side CD into three equal parts, and the bisectors of angles C and D divide side AB into three equal parts.

In this problem, four cases are possible, schematically depicted in Figures 3, 4, 5, 6. Figure do not reproduce the actual lengths of the sides or the magnitude of the angles, only the order of the intersection points of the bisectors $AE$, $BH$, $CK$, $DM$ from the side is shown.

Case I (Fig. 3). Let $AM = MK = KB = a$. Note that $\Rightarrow AMD = \Rightarrow CDM = \Rightarrow ADM$. (*) Pozny $AD = a$. Same as $BC = DE = EH = HC = a$. The postural perimeter is tetrachrologically equal to 8 $a$, whence $a = 5/4$. The answer for this and other cases is given in the table.

Case II (Fig. 4). Let $AK = KM = MB = a$. Equalities (*) are true again, so $AD = 2 $ $a$, and similarly $BC = DE = EH = HC = 2 $ $a$. Perimeter is 13 $a$, hence $a = \frac{10}{13}$.

Case III (Fig. 5) is similar to case II.

IV case (Fig. 6). Let $AK = KM = MB = a$. Using the same angle equality (*), we obtain: $AD = BC = 2 $ $a$, $DE = HC = 2 $ $a$, whence $DH = HE = EC = a$. The perimeter is 10 $a$, hence $a = 1$.

Task 9. a) List all possible rectangles whose side lengths are greater than 10 and which can be cut into 28 rectangles of size $3 \times 5$.

6) Is it possible to fill some rectangular box $a \times b \times c$, where $a \geq b \geq c \geq 10$ is, with 28 bars of size $3 \times 5 \times 10$?

a) Obviously, the area of ​​such a rectangle is $28 \cdot 3 \cdot 5 = 420$. The lengths of its sides are integers. This means that we need to divide the number $420 = 2^2 \cdot 3 \cdot 5 \cdot 7$ into two integer factors, each of which is greater than 10. Consider the set that is divisible by 7.

⟦folio 43⟧

Fig. 7.

It is greater than 10 and less than 42 (otherwise the second factor is not greater than 10).

We get four cases: 1) $14 \times 30$; 2) $21 \times 20$; 3) $28 \times 15$; 4) $35 \times 12$.

We have found that no straight edge other than the four listed is suitable. Are these four suitable?

Note that if the length of one side of a rectangle is divisible by 3, and the other by 5, then such a rectangle can be cut into rectangles of size $3 \times 5$. It immediately follows that rectangles of sizes $21 \times 20$ and $35 \times 12$ are suitable.

We first cut the rectangle of size $14 \times 30$ into two rectangles: $9 \times 30$ and $5 \times 30$. Both of them can be cut into $3 \times 5$ rectangles, so a $14 \times 30$ rectangle is also suitable.

The rectangle of size $28 \times 15$ can be cut into rectangles $25 \times 15$ and $3 \times 15$.

This means that all four straight edges are suitable.

6) Yes, you can. Let's give an example that proves this. Let
$$a = 20, b = 15, c = 14.$$
Let's cut this box of size $20 \times 15 \times 14$ into two: sizes $20 \times 15 \times 9$ and $20 \times 15 \times 5$.

In each of the two resulting boxes, one dimension is divided by 3, the other by 5, and the third by 10. Therefore, each of them, of course, can be filled with bars $3 \times 5 \times 10$. There will be 28 bars in total.

Problem 10. Is there a nine-digit number, written as 1, 2, 3, 4, 5, 6, 7, 8, 9, from which it is impossible to cross out five digits so that the remaining four digits are in ascending or descending order?

Yes, it exists. Let us prove, for example, that the following number is suitable:

321 654 987.

It is easy to check that if any two digits of this number are in descending order (the smaller story is to the right of the larger one), then they are necessarily from the same triple. This means that in this number it is impossible to select the major three digits in descending order, since all these digits must be in one triple.

If some digits of this number are in the air in the same order, then they are necessarily from different triplets. Since only three are required, it is impossible to select more than three numbers in the air in the same order.

There are other examples. For example, a suitable number:

638 159 274,

prove it yourself.

Problem 11. Is it possible to indicate an internal triangle with sides 3, 4, 5, the distances from the composition to each of the sides of the triangle: a) less than 2; b) less than 1?

a) Yes, the center of the inscribed circle is suitable (its radius is 1).

Answer to question 6): no, you can't. Let's prove it. Let us draw from the center O of the inscribed circle of radius to all points of tangency on the side and denote by direct numbers the parts into which our triangles will be divided (see Fig. 7). It is easy to prove that if the desired point M is in part I (including the border), then the distance from M to AB is not less than 1. Similarly, if M is in part II, then the distance from M to BC is not less than 1, and if M is in part III, then the distance from M to AC is not less than 1.
