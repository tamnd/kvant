---
id: 1981-10-koen-metrika-konya-b8712586
issue: kvant_1981_10
year: 1981
number: "10"
title: Knight metric
authors:
  - Коэн Д.
rubric: osnovnye-stati
page_first: 15
page_last: 18
page_labels: 13-16
tag: ZC9G
lang: en
source: kvant_digital
extraction: vision
content_sha256: b457c735826d0b973d378ba61f217d70e3cb91986303edc7c8d6018be28ecb7c
prompt_sha256: draft-1
translated_from: content/ru/1981/10/articles/05_koen-metrika-konya-b8712586.md
source_content_sha256: 5837367e0af25d26af345ddd68e7b37c7486536016aae893bb497804396d2c1e
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 13⟧

D. Cohen

Knight metric

Here we will be interested in the moves of the knight on the chessboard, which we will initially propose to be infinite. Let us denote the cells of the board of parametric numbers (by the coordinates of the center of the cell - see Fig. 1). The move of a knight located at the origin of coordinates (0;0) is a transition to one of 8 cells with coordinates (±1; ±2), (±2; ±1). If the knight is in the cell (x; y), then one move transfers it to one of the cells (x±1; y±2), (x±2; y±1).

Let us define the distance from cell P to cell Q as the min and small number of knight moves required to move from P to Q. Let us denote this number by q (P, Q). For example,

The author, an American mathematician, wrote this article for «Kvant» in English. Translation edited by A. Sosinsky.

Fig. 1.

Mer, the distance from the beginning O(0;0) to the cell E(1;0) is equal to the distance from the beginning to the cell F(3;6) - both of them are equal to 3. The function q, defined on a set of pairs (P, Q) of cells, has three basic properties of distance*):

q(P, Q) > 0, for P ≠ Q; q(P, P) = 0;
q(P, Q) = q(Q, P); (II)
q(P, R) ≤ q(P, Q) + q(Q, R). (III)

The first two properties are very idic, but the third—called the triangle inequality—follows from the fact that one can find a path from P to R that does not pass through Q and is shorter than any path from P to R that passes through Q.

This distance—the metric of the horse—gives rise to a very unteachable “geometry.” In it, we can define the concept of a segment [AB]** as a set of cells M such that q(A, M) + λ(M, B) = q(A, B), but the segments turn out to be very ugly (two segments can intersect in several cells). You can also define circles of radius r, which look somewhat more decent (at least for r ≥ 5).

For now, let us note the following estimated property of the function q:

q((x; y), (x'; y')) =
= q((0; 0), (x' − x; y'' − y)). (*)

it allows, together, the function q from pairs of cells to study the function from one cell - the distance from the beginning:

d(P) = q(O, P).

Let us put in each cell P the value of the function d(P). Let's imagine that we did this on a piece of tracing paper. Then property (*) means that if we parallelly draw a tracing paper and combine O with point P at the beginning, q(P, Q) will be written on the tracing paper above point Q.

On figure 2 all values ​​of d(P) less than or equal to 4 are celebrated. Figure suggests the following:

*) See “Geometry 6-8”, paragraph 4 - approx. ed.
**) See “Geometry 6-8”, paragraphs. 5-6 - approx. ed.

⟦folio 14⟧

Distance formula $d((a; b))$
Due to properties (1) and (2), it is sufficient to calculate $d((a; b))$ in the case when $0 \leq a \leq b$. Also, to avoid confusion, exist near the origin, we will assume that $a+b \geq 6$. The distance is two cases depending on whether the cell $P(a; b)$ lies in the horizontal strip of the $n$-th belt, that is, $2a \leq b$. For a fixed $d=d((a; b))$, the point $P$ has 4 different possible ones.

The first case: cell $P(a; b)$ lies in the horizontal strip of the $n$-th belt, that is, $2a \leq b$. For a fixed $d=d((a; b))$, the point $P$ has 4 different possible ones.

* We offer proof, slightly different from the author’s (ed.)

Fig. 2.
Here are the properties of the function $d$:
$$d((a; b))=d((b; a)),$$
(1)
$$d((a; b))=d((|a| |b|)),$$
(2)
numbers $d((a; b))$ and $a+b$
have the same parity, (3) which obviously follows from the definition.

Let's further note that on figure 2 inside the red line there are numbers 0, 1, 2, 3, 4, which are fairly rearranged, although symmetrically located (due to properties (1) and (2)). In order between the red and blue lines there are only fours and the $\times$ (actually $\times=5$) icon. In the next such belt there will be only 5 and 6, in the next - 6 and 7, etc. (Fig. 3). figure 4 shows only the first quarter of $(x, y \geq 0)$. This figure also shows the $n-20$ section of the belt, which contains only the numbers $n$ and $n+1$.

Roughly speaking, the $n$-th belt has the shape of a square boundary (on the side of length $4n+1$) with medial corners (equally angled right triangles are cut off on the side of length $n-1$). The belt is composed of horizontal and vertical strips of thickness 2 and four diagonal sections in the form of a ladder; one of them is highlighted in figure.

Thus, if we ignore the confusion that exists near the origin, the geometric picture of the knight metric becomes clearer. However, this is not enough for us: we want to learn how to find $d((a; b))$ purely analogously - using the numbers $a$ and $b$. In short, we need

Fig. 3.
Fig. 4.

⟦folio 15⟧

ity depending on its vertical level (Fig. 5). At the highest level, point $P$ is reached with a minimum integer of $d$ moves, increasing the second coordinate by 2; at the next level - a whole of $d-1$ moves of this type and one move increasing the second coordinate by 1; the next level requires $d-2$ and 2 moves of these types; at the lower level - $d-3$ and 3, respectively. In these cases, the height of $b$ is $2d$, $2(d-1)+1=2d-1$, $2(d-2)+2=2d-2$, $2(d-3)+3=2d-3$, respectively. From here we could express $d$ in terms of $b$, but $b$ is an integer, and we cannot write down the answer without knowing the parity of $b!$ How would we?

It turns out that the correct answer is given by one of the numbers $[(b+1)/2]$ or $[(b+1)/2]+1$ (here the square brackets denote the integer part), namely the one whose parity coincides with the parity of the number $a+b$ (see property (3)). The reader can easily check this by using figure 5 and its caption.

Second case: cell $P(a; b)$ lies on the diagonal section of the $n$-th belt, that is, $2a>b$. It is easy to see that at any point of the diagonal section of the first quarter of the $n$-th belt one can reach the minimum by a sequence of knight moves so that on each move the sum of the coordinates increases by exactly 3 (that is, by moves $(a; b) \rightarrow (a+1; b+2)$ and $(a; b) \rightarrow (a+2; b+1)$). Therefore $a+b=3n$ or $a+b=3(n+1)$, hence $d((a; b)) = [(a+b+1)/3]$ or $d((a; b)) = [(a+b+1)/3]+1$. Which of these two numbers can be taken is clear from the parity messages (see (3)).

Let us summarize our study of the function $d((a; b))$. Under conditions $0 \leq a \leq b$ and $a+b \geq 6$, the number $d((a; b))$ has the same parity as $a+b$, being $[(b+1)/2]$ or $[(b+1)/2]+1$ in the case of $2a \leq b$, $[(a+b+1)/3]$ or $[(a+b+1)/3]+1$ in the case of $2a>b$.

In fact, these formulas give the correct answer for $a+b<6$ everywhere except for cells (0; 1) and (2; 2), where they give 1 and 2, respectively, together with the correct 3 and 4 (see Fig. 2).

Metrics of a horse on a straight board

Let us now limit our infinite chessboard: we will consider the moves of the knight on the rectangular board $a \times b$ ($a \leq b$). With $a=1$ there is nothing to consider (“Comrade grandmaster, the knight doesn’t move like that!”), with $a=2$ everything is very simple. We will leave the more meaningful cases $a=3$ and $a=4$ to the reader, and move on to case $5 \leq a \leq b$. Turns out,

At $5 \leq a \leq b$ there are knight moves of length $d((a; b))$ inside the rectangle from the sides $x=0$, $x=a$, $y=0$, $y=b$ connecting points (0; 0) and $(a; b)$, and this path is the shortest.

Indeed, we start from a point in the $n$-th belt and make one towards the beginning. Then we remain inside the rectangle and end up in the $(n-1)$th belt. Continuing this process, we will reach the fourth belt. Next, it remains to check the validity of our statement for cells of the fourth

⟦folio 16⟧

Belt. We leave this search to the reader.

Knight metric on a square board
Consider now a square board $n \times n$, say, bounded by a rectangle $x=0, x=n-1, y=0, y=n-1$. The isozem with the diameter of this board is the greatest distance (in the sense of the horse metric) between its cells. Leaving the case of small sizes again to the reader, we consider the case $n \geq 5$. From the previous one it is easy to see that the diameter will be the distance from the cell (0; 0) to one of the cells $(n-1; n-1)$ or $(n-1; n-2)$. Using this remark and previously obtaining the distance formula, we show that
The diameter of the chessboard $n \times n$ is equal to the number $2n/3$ rounded to the nearest integer.

Indeed, according to the distance formula, $d((n-1; n-1))$ is equal to $[(2n-1)/3]$ or $[(2n-1)/3] + 1$ (namely, whichever of these numbers is even); and $d((n-1; n-2))$ equals $[(2n-2)/3]$ or $[(2n-2)/3] + 1$ (odd). Let's consider three cases depending on the remainder when dividing the number $n$ by 3.

First case: $n=3k$. Then
$$[(2n-1)/3] = [(2n-2)/3] = 2k-1,$$
so the distance to $(n-1; n-1)$ is $2k$ and to $(n-1; n-2)$ is $2k-1$. The diameter is $2a$, which is $2n/3$ without any rounding.

Second case: $n=3k+1$. Then
$$[(2n-1)/3] = [(2n-2)/3] = 2k,$$
so the distances to $(n-1; n-1)$ and $(n-1; n-2)$ are respectively $2k$ and $2k+1$. The diameter is equal to $2k+1$, which is a rounded number $2n/3$.

Third case: $n=3k+2$. Then
$$[(2n-1)/3] = 2k+1,$$
so the distances we are interested in are respectively $2k+2$ and $2k+1$. This means that the diameter is equal to $2k+2$, which is again a rounded number $2n/3$.

Note that the greatest distance is realized in this case by cells that do not lie on the main diagonal.

Other formulas
The function $d((a; b))$ has already been studied before, and other (more complex) similar expressions have been obtained for it (for $a+b \geq 8$, $0 \leq a \leq b$). M. Goldberg (USA) found
$$d((a; b)) = \begin{cases} b-a-2[(b-2a)/4] \\ \text{при } 2a \leq b, \\ b-a+[(8a-4b+2)/3] - [(4a-2b)/3] \\ \text{при } 2a > b, \end{cases}$$

and D. Cvetkovic and S. Simch (Yugoslavia) found
$$d((a; b)) = \begin{cases} a+b-2\left[\frac{b}{2}\right] - \left[\frac{a-[b/2]}{2}\right] \\ \text{при } 2a \leq b, \\ a+b-2\left[\frac{a+b}{3}\right] \end{cases}$$

It can be shown that these formulas are equivalent to ours, but it is more interesting to try to guess what reasoning their authors used to arrive at them.

In conclusion, we offer the reader the following task: find the area of ​​a circle of radius $r$, that is, the number of cells $(a; b)$ for which $d((a; b)) \leq r$.

Tournament named after M. V. Lomonosov
According to updated data, this year the tour (see «Kvant», 1981, No. 8, p. 51) is in Moscow on October 25 at 10.00 in the premises of the following flights: MAI, MATI, MGPI, MIIGAIK, MINHIGP, MISS, MISIS; Students in grades 6-9 are invited.
