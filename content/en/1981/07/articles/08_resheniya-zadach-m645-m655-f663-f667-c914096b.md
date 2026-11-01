---
id: 1981-7-resheniya-zadach-m645-m655-f663-f667-c914096b
issue: kvant_1981_7
year: 1981
number: "7"
title: Solutions to problems M645—M655; F663—F667
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 23
page_last: 33
page_labels: 21-31
tag: GM2G
lang: en
source: kvant_digital
extraction: vision
content_sha256: 4221e0df28d2a2e2926075e086fee770439ff51a85701ade36868efb7d892963
prompt_sha256: draft-1
translated_from: content/ru/1981/07/articles/08_resheniya-zadach-m645-m655-f663-f667-c914096b.md
source_content_sha256: 1f59cc383ff157a0ceefe6f669c6c4a4e32f2e32cc864f1427b81af7e8453f91
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 21⟧

Problem solving

M645. There are three corridors in the basement (figure 1; $|OA| = |OB| = |OC| = l$), all exits from which are closed. Inspector Warnicke and a representative are there. Warnicke replaces the representative if the distance between them does not exceed $r$. He knows that the representative's maximum speed is half his own maximum speed. At the initial moment, the inspector is at point $O$ and does not see the representative. How should Warnicke act to be sure to catch the representative if $a) r = l/3, 6) r = l/4, \text{в})^* r > l/5, \text{в}) r > l/7$. Neglect the width of the corridors and the size of people. (Warnicke must come up with such a plan of action that, even if the representative knows about it in advance, he will still not be able to perform the service).

Fig. 1.

Fig. 2.

1. Solution of the problem at $r > l/5$ (in part, at $r = l/3$ and $r = l/4$).
First, Warnicke “combs” the corridor $OC$. Having made sure that the representative is not there, Warnicke retreats to corridor $OA$ at a distance $2r$ and then returns to point $O$, moving at maximum speed (hereinafter it will be assumed that the inspector always moves at maximum speed). Suppose that, having returned to point $O$, the inspector did not see the representative; What does he know in this case about the possible whereabouts of the representative?

1) The offender cannot be in corridor $OC$: it is easy to check that if during the absence of the inspector at point $O$ he tried to run from corridor $OB$ to corridor $OC$, then by the time the inspector returned to point $O$ the distance from the representative to $O$ would be no more than $r$.

2) If the offender is in the corridor $OA$, then at a distance from $O$, more than $2r$: indeed, when the inspector was in the corridor $OA$ at a distance $2r$ from $O$, then the offender (if he is in $OA$) was at a distance from $O$, more than $3r$, and by the time the inspector returned to point $O$, the distance from the offender to $O$ could have decreased by no more than $r$ (Fig. 2).

If $r \geq l/3$, then the offender cannot be in $OA$ at all, and thus problem a) is solved: to reap the offender, the inspector only needs to explore the corridor $OB$ to the end.

If $r < l/3$, then the meaning of the inspector’s further actions is to go deeper into the corridor $OB$, then into the corridor $OA$ to an increasingly greater distance, but so that the offender will not be able to run across to the corridor $OC$. Each such “deepening” together with the subsequent return to point $O$ will be called a cycle. The first cycle has already been described. In the second cycle, the inspector goes to the corridor $OB$ at a distance $3r$. Returning to point $O$ and not seeing the offender, the inspector knows that

1) there is no offender in corridor $OC$ (if the offender is in corridor $OA$, then he is at a distance from $O$, more than $2r$, and therefore until Warnicke returns to point $O$, when he is removed at a distance $3r$ into corridor $OB$, the offender will not be able to run across to the corridor $OC$ so as to be at a distance from $O$, more than $r$);

2) if the offender is in the corridor $OB$, then the distance from him to $O$ is greater than $5r/2$ (more than $(3r + r) - 3r/2$).

If $r \geq l/4$, then the offender cannot be in the corridor $OB$ at all (since then its length is greater than $3r + r = 4r \geq l$ - a contradiction); This solves problem 6).

Let the inspector know after the cycle with number $n$ that there is no offender in corridor $OC$, and in corridor $OX$ (where $X = A$ for $n$ odd and $X = B$ for $n$ even) the offender cannot be at a distance from $O$, less than or equal $y_n$. Then in the next cycle the inspector goes to another corridor at a distance of $y_n + r$ (Fig. 3). Returning to point $O$, the inspector knows that

1) there is no offender in the corridor $OC$;

2) in the corridor just explored, the intruder cannot be at a distance from $O$, less than or equal to $y_n + r \geq l - r$, then in the explored corridor there is no intruder at all.

Let's find the formula for $y_n$. Since $y_n + 1 = \frac{y_n + 3r}{2}, 3r - y_n + 1 = \frac{3r - y_n}{2}$, whence $3r - y_n = \frac{3r - y_1}{2^{n-1}} = \frac{r}{2^{n-1}}$, that is

⟦folio 22⟧

Fig. 3.

$$y_n = 3r - \frac{r}{2^{n-1}}.$$

The criminal is caught if $y_n + r \geqslant l - r$ is at some $n$, that is, $\frac{r}{2^{n-1}} \leqslant 5r - l$. From this we can see that if $5r > l$, then after a sufficiently large number of cycles it is caught.

2. The solution to the problem at $l/7 < r \leqslant l/5$ uses the following new idea: after a sufficiently large number of cycles described in Section 1, the inspector must go deeper into the next corridor at a distance not $y_n + r$, but $l - r$ (that is, “read” it to the end), not paying attention to the fact that the criminal can run into the corridor $OC$.

Let's put $\varepsilon = \frac{7r - l}{2}$. The inspector must proceed as described in Section 1 until inequality $y_n \geqslant 3r - \varepsilon$ is satisfied. After this, the inspector goes deeper into the next corridor (say, $OA$) at a distance of $l - r$. Returning to point $O$ and not seeing the criminal, the inspector knows that there is no criminal in corridor $OA$, and in corridor $OC$ the criminal cannot be at a distance from $O$, more than $(l - r) - (3r - \varepsilon) = 3r - \varepsilon$. The inspector then goes deeper into the corridor $OC$ to a distance of $4r - 2\varepsilon$. Having returned to point $O$ and not seeing the criminal, the inspector knows that there is no criminal in the corridor $OC$ (since otherwise the criminal would have been discovered, being in the corridor $OC$ from Warnicke at a distance less than $(3r - \varepsilon) + (4r - 2\varepsilon)/2 - (4r - 2\varepsilon) = r)$, and in the corridor $OA$ the criminal cannot be at a distance from $O$, more $3r - 2\varepsilon = (4r - 2\varepsilon) - r$ Then the inspector goes to the corridor $OA$ at a distance $4r - 4\varepsilon$, then to the corridor $OC$ at a distance $4r - 8\varepsilon$, again to the corridor $OA$ at a distance $4r - 16\varepsilon$, etc. When the inspector sees that he needs to go to the fingerprint distance, he must conclude that the criminal is in the corridor $OB$.

Then eeee. It was possible to prove that at $r \leqslant l/7$ there is no way to definitely understand the criminal. The evidence of this fact, taken by I. Golubchka and V. Prasolova, is complex and therefore is not given here.

V. Drinfeld,
V. Sokolov

**M646. From the point $O$ on the plane there are 2n vectors of length 1. They are colored alternately in red and blue. Let $\vec{s} - \vec{c}$ be the sum of $n$ red vectors, $\vec{r} - \vec{c}$ the sum of $n$ blue vectors. Prove that $|\vec{s} - \vec{r}| \leqslant 2$.

Vector direction $\vec{s} - \vec{r}$

$$\left( \frac{a^2 - b^2}{2} \right)^2 \geqslant \sqrt{\frac{a^2 - b^2}{2}} - \frac{a + b}{2}.$$

Let us represent the vector $\vec{s} - \vec{r}$ as a sum of $n$ black vectors (see figure), each of which is the difference of the red vector and the blue vector close to it (clockwise). Black vectors rest on pairwise disjoint arcs of a circle of radius $1$ centered at point $O$.

Let us now assume that the vector $\vec{s} - \vec{r}$ is non-zero (everything has been proven). Let us project the resulting black vectors onto the direction of vector $\vec{s} - \vec{r}$. It is easy to notice that projections whose directions coincide with the direction of the vector $\vec{s} - \vec{r}$ do not intersect and decrease along the diameter of the circle. Therefore, the sum of their lengths does not exceed 2. On the other hand, the length of the vector $\vec{s} - \vec{r}$ does not exceed this sum. Therefore $|\vec{s} - \vec{r}| \leqslant 2$.

E. Shustin

First decision. Let us distance the function $f(x) = x^2 + \sqrt{x}$. Having calculated its second product $f''(x) = 2 - \frac{1}{4}x^{-3/2}$, we see that $f''(x) \geqslant 0$ at $x \in \left[ \frac{1}{4}; +\infty \right]$. It follows that on the interval $\left[ \frac{1}{4}; +\infty \right]$ the function $f$ is downward convex (for integration).

⟦folio 23⟧

shaft see “Algebra and principles of analysis 10”, paragraph 79); figure shows her graph. Therefore («Kvant», 1980, No. 3, p. 21) for any points $x, y$ of this interval

$$\frac{f(x) + f(y)}{2} \geq f\left(\frac{x+y}{2}\right).$$

Applying the last inequality to the points $a^2, b^2$, we obtain the statement of the problem.

Second solution. Again, replace $a^2$ with $x$ and $b^2$ with $y$. Let's consider the function

$$\varphi(x, y) = \left(\frac{x-y}{2}\right)^2 - \sqrt{\frac{x+y}{2}} + \frac{\sqrt{x} + \sqrt{y}}{2}.$$

We will assume that $x \geq y \geq 1/4$ and examine the function $\varphi(x, y)$ for “monotonicity in $x$”, considering the variable $y$ to be a parameter.

$$\varphi'_x(x, y) = \frac{x-y}{2} - \frac{1}{2\sqrt{2(x+y)}} + \frac{1}{4\sqrt{x}} =$$

$$= \frac{1}{2} \left(x-y + \frac{\sqrt{2(x+y)} - 2\sqrt{x}}{2\sqrt{x} \cdot \sqrt{2(x+y)}}\right) =$$

$$= \frac{x-y}{2} \cdot \left(1 - \frac{1}{\sqrt{x} \cdot \sqrt{2(x+y)} \cdot (\sqrt{2(x+y)} + 2\sqrt{x})}\right) \geq$$

$$\geq \frac{x-y}{2} \cdot \left(1 - \frac{1}{\frac{1}{2} \cdot 1 \cdot 2}\right) = 0,$$

that is, the function $\varphi(x, y)$ is a nondecreasing function with respect to $x$.

Since at $x=y=\frac{1}{4}$ the function $\varphi$ vanishes, $\varphi(x, y) \geq 0$ at $x \geq y \geq \frac{1}{4}$, which gives us the required inequality.

I. Klumova

**M648. Prove that if the diagonals of an inscribed quadrilateral are perpediculars, then the midpoints of its sides and the bases of the perpediculars dropped from the point of intersection of its diagonal onto the sides lie on the same circle.**

Fig. 1.

Fig. 2.

First of all, we note that if $ABCD$ is an inscribed quadrilateral with perpedicular diagonals (Fig. 1), then similar triangles $AKB$ and $CKD$ (K is the point of intersection of the diagonals) are located in such a way that the extension of the altitude dropped to the hypotenuse of one of them is the median of the other. (This fact, immediately following from the equality of the angles marked on figure 1, has essentially already been used in solving problems M546 and M592 - see «Kvant», 1980, No. 1, 8.)

Next: the midpoints $L, P, M, Q$ of the sides of the quadrilateral $ABCD$, being the vertices of a straight bow (Fig. 2), lie on the same circle. Let us show that the center $O_1$ of this circle bisects the segment $OK$ (O is the center of the circle in which our quadrilateral is inscribed).

To do this, it is enough, for example, to show that the quadrilateral $LKMO$ is a parallelogram. Since $LK$ is the median of triangle $AKB$, its extension is the altitude of triangle $CKD$, that is, $(LK) \perp (DC)$. But also $(OM) \perp (DC)$ (diameter passing through the middle of the chord); therefore the segments $LK$ and $OM$ are parallel. The parallelism of the segments $LO$ and $KM$ is proved in a similar way.

Now, to complete the solution of the problem, it is enough for us to establish, for example, that $|O_1M| = |O_1H|$, where $H$ is the base of the peredicular, lowered from the point $K$ to the side $CD$. But this follows from the fact that $O_1$ is the middle of the hypotenuse $LM$ of a straight bow (Fig. 3).

So, all eight points mentioned in the problem statement lie on the same circle. Interestingly, the radius of this “circle of eight points” is entirely determined by the radius $R$ of the given circle and the value $|OK| = a$. In fact, the desired radius is equal to half the length [LM], and

$$|LM|^2 = |LP|^2 + |PM|^2 = \frac{1}{4} \left(|AC|^2 + |BD|^2\right) =$$

$$= \frac{1}{4} \left((|AK| + |KC|)^2 + (|BK| + |KD|)^2\right) =$$

⟦folio 24⟧

Fig. 3.

Fig. 4.

Fig. 5.

Fig. 6.

Fig. 7.

$$\frac{1}{4}(|AB|^2 + |CD|^2 + 2(|AK| \cdot |KC| + |BK| \cdot |KD|)) =$$

$$\frac{1}{4}(|AB|^2 + |CD|^2 + 4(R^2 - a^2)) = \frac{1}{4}(4R^2 + 4(R^2 - a^2)) = 2R^2 - a^2.$$

[In this calculation, we first took advantage of the fact that the product of the lengths of segments of chords intersecting at the same point is constructed:

$$|AK| \cdot |KC| = |BK| \cdot |KD| = (R - a)(R + a)$$

(Fig. 4), and then saying that

$$90^\circ = \widehat{BCA} + \widehat{DBC} = \frac{AB + CD}{2},$$

and complement $CD$ to the half-possibility of another, congruent $AB$, we obtain the equality

$$|AB|^2 + |CD|^2 = (2R)^2 = 4R^2,$$

see figure 5.]

Let's outline another solution. Let us complete our calculations of points with a center at point $K$ and coefficient 2. Then the statement of problem **M648** turns into the following theorem: Let two mutually redistributing rays with a beginning at point $K$ inside a given circle, curving around $K$, intersect the circle at variable points $P$ and $Q$. Then the quadruple vertex $T$ of the rectangle $PKQT$ (the point symmetrical to the point $K$ relative to the midpoint [PQ]), as well as the point $S$, symmetrical to the point $K$ relative to the straight line $PQ$, are called along the circle congruent with the given one (Fig. 6). The second fact (about $S$) follows from the first, since $S$ is symmetrical to the point $T$ with respect to the midpoint of the redistribution to [PQ], and the first (about $T$) establishes the solution to the problem **M539** («Kvant», 1979, No. 11).

This “resurgence theorem” allows the following stereometric generalizations:

If three mutually redistributing rays with a beginning at a fixed point $K$ inside a given sphere, healing around $K$, intersect the sphere at variable points $A$, $B$ and $C$, then the point of intersection of the medians of the triangle $ABC$ and the base of the redistribution dropped from $K$ to the plane $ABC$ are determined by a sphere whose center is located at point $O_1$ of the segment $OK$ (O is the center of this sphere) such that $|O_1K| = \frac{1}{3}|OK|$, and the radius is $\frac{1}{3}\sqrt{3R^2 - 2a^2}$, where $a = |OK|$, $R$ is the radius of this sphere.

This can be proven, for example, using the following notation:

Let $D$ be the vertex of the parallelepiped defining by the segments $KA$, $KB$ and $KC$, diagonally opposite to $K$. All points $D$ lie on a sphere with a center at the same point $O$ as the original sphere and radius $\sqrt{3R^2 - 2a^2}$ (see solution to problem **M639** - «Kvant», 1979, No. 11). In this case, with center $K$ and coefficient $\frac{1}{3}$, point $D$ will always go to the point of intersection of the medians of the triangle $ABC$ (prove it!), and point $O$ will go to point $O_1$. Thus, the point of intersection of the medians of the triangle $ABC$ always lies on the indicated sphere.

It remains to show that the projection of the point $K$ onto the plane of the triangle $ABC$ also always lies on this sphere. Since the segments $KA$, $KB$ and $KC$ are mutually redistributed, the projection of the point $K$ coincides with the point $H$ of intersection of the altitudes of the triangle $ABC$. The statement will be proven if, for example, we obtain the equality $|O_1H| = |O_1M|$, where $M$ is the point of intersection of the medians of the triangle $ABC$. To do this, we note that the center of the sphere $O$ is projected into the center $Q$ of the circle circumscribed around the triangle $ABC$, and use the following well-known fact: points $Q$, $M$ and $H$ lie on the same straight line (Euler’s straight line), point $M$ is between the points $Q$ and $H$, with $2|QM| = |MH|$. (If you do not know this fact, prove it.) The rest easily follows from figure 7: flat

⟦folio 25⟧

M649. Prove equality
$$\frac{1}{2} c_n^2 + (c_n - c_1)^2 + (c_n - c_2)^2 + \dots + (c_n - c_{n-1})^2 = \frac{n}{2},$$
food $c_1 = 1, c_2 = 1 + \frac{1}{3},$
$c_3 = 1 + \frac{1}{3} + \frac{1}{5}, \dots,$
$c_n = 1 + \frac{1}{3} + \frac{1}{5} + \dots + \frac{1}{2n-1}$.

Let's prove that
$$c_n^2 + 2(c_n - c_1)^2 + 2(c_n - c_2)^2 + \dots + 2(c_n - c_{n-1})^2 = n.$$
To do this, substitute the values ​​$c_i$ ($i = 1, \dots, n$) into the left side:
$$\left(1 + \frac{1}{3} + \frac{1}{5} + \dots + \frac{1}{2n-1}\right)^2 + 2\left(\frac{1}{3} + \frac{1}{5} + \dots + \frac{1}{2n-1}\right)^2 + 2 \cdot \left(\frac{1}{5} + \frac{1}{7} + \dots + \frac{1}{2n-1}\right)^2 + \dots + 2 \cdot \left(\frac{1}{2n-1}\right)^2 = 1 \cdot \left(\left(1 + \frac{1}{3} + \dots + \frac{1}{2n-1}\right)^2 - \left(\frac{1}{3} + \frac{1}{5} + \dots + \frac{1}{2n-1}\right)^2\right) + 3 \cdot \left(\left(\frac{1}{3} + \frac{1}{5} + \dots + \frac{1}{2n-1}\right)^2 - \left(\frac{1}{5} + \frac{1}{7} + \dots + \frac{1}{2n-1}\right)^2\right) + 5 \cdot \left(\left(\frac{1}{5} + \frac{1}{7} + \dots + \frac{1}{2n-1}\right) - \left(\frac{1}{7} + \frac{1}{9} + \dots + \frac{1}{2n-1}\right)^2\right) + \dots + (2n-1) \cdot \left(\frac{1}{2n-1}\right)^2 = 1 \cdot \left(1 + \frac{2}{3} + \frac{2}{5} + \dots + \frac{2}{2n-1}\right) + 3 \cdot \frac{1}{3} \cdot \left(\frac{1}{3} + \frac{2}{5} + \frac{2}{7} + \dots + \frac{2}{2n-1}\right) + 5 \cdot \frac{1}{5} \cdot \left(\frac{1}{5} + \frac{2}{7} + \frac{2}{9} + \dots + \frac{2}{2n-1}\right) + \dots + \frac{1}{2n-1} = 1 + \frac{3}{3} + \frac{5}{5} + \frac{7}{7} + \dots + \frac{2n-1}{2n-1} = 1 + 1 + 1 + \dots + 1 = n.$$
S. Manukyan

M650. Is there a sequence
$$a_1, a_2, a_3, \dots, a_n, \dots$$
a) natural numbers such that any natural number can be uniquely written as the sum of several of its terms:
$$a_{i+1} + \dots + a_{i_k} \quad (i_1 < \dots < i_k, k \ge 1);$$
b) natural numbers such that 1 cannot be represented in the form (*), and any integer other than 0 can be represented in the form (*) in a unique way;
c) integers such that 0 cannot be represented in the form (*), and any integer other than 0 can be represented in the form (*) in a unique way;
f) integers such that 0 and 1 are not represented in the form (*), and any integer other than 0 is represented in the form (*) in a unique way?

Let's prove that
$$c_n^2 + 2(c_n - c_1)^2 + 2(c_n - c_2)^2 + \dots + 2(c_n - c_{n-1})^2 = n.$$
To do this, substitute the values ​​$c_i$ ($i = 1, \dots, n$) into the left side:
$$\left(1 + \frac{1}{3} + \frac{1}{5} + \dots + \frac{1}{2n-1}\right)^2 + 2\left(\frac{1}{3} + \frac{1}{5} + \dots + \frac{1}{2n-1}\right)^2 + 2 \cdot \left(\frac{1}{5} + \frac{1}{7} + \dots + \frac{1}{2n-1}\right)^2 + \dots + 2 \cdot \left(\frac{1}{2n-1}\right)^2 = 1 \cdot \left(1 + \frac{2}{3} + \frac{2}{5} + \dots + \frac{2}{2n-1}\right) + 3 \cdot \frac{1}{3} \cdot \left(\frac{1}{3} + \frac{2}{5} + \frac{2}{7} + \dots + \frac{2}{2n-1}\right) + 5 \cdot \frac{1}{5} \cdot \left(\frac{1}{5} + \frac{2}{7} + \frac{2}{9} + \dots + \frac{2}{2n-1}\right) + \dots + \frac{1}{2n-1} = 1 + \frac{3}{3} + \frac{5}{5} + \frac{7}{7} + \dots + \frac{2n-1}{2n-1} = 1 + 1 + 1 + \dots + 1 = n.$$
B) induction step. Let us assume, for definiteness, that for $2^n$ the sign is “plois” (that is, $n$ is odd) and that from the set $(-1, 2, -4, \dots, \pm 2^n)$ one can uniquely obtain in the form (*) all integers (except zero) from the interval from $-1$ to $-4$ to $-16$ — — (the last negative member of the set) to $2 + 8 + 32 + \dots + (последний положительный член набора). Базис индекции ($n = 1$) оченьiden.

Иndукции шаг. Предположим, для определенияности, что при $2^n$ знак «плоис» (то есть $n$ нечетное) и что из набора $(-1, 2, -4, \dots, \pm 2^n)$ можно единственным образом получить в виде (*) все целые числа (кроме нуля) из промежутка от $-1$ до $-4$ до $-16$ — — (последний отрицательный член набора) до $2 + 8 + 32 + \dots + (last positive member of the set). The statement has been proven.
d) Such a sequence does not exist.

The proof exists and let $a_1$ be its term different from $-1$. Then the numbers $1 + a_1$ and $1 - a_1$ are represented as (*)

⟦folio 26⟧

M651. The date rented out a sofa, a suitcase, a luggage, a basket, a painting, cardboard and a small dog at the bases. The sofa weighed as much as a suitcase and luggage combined, and as much as a painting, basket and cardboard combined. The painting, the basket and the cardboard weighed equally, and which one weighed more than the dog. When they unloaded the bases, the lady stated that the dog was the wrong breed. When checking, it turned out that the dog moves the sofa if you add a dog carrier or a suitcase to it. Prove that the lady's claim was fair.

Let a sofa, a suitcase, a luggage bag and a small dog weigh D, H, S and M kilograms, respectively, and a painting, a basket and cardboard - K kilograms each (by assumption, they weigh the same). Let's write the stripping data in these notations:
(1) D=H+C; (2) D=3K; (3) K>M; (4) M+C>D; (5) M+H>D. From (1)–(3) we obtain
(6) H+C>3M.

Then adding up inequalities (4)–(6), taking into account (1), we arrive at the inequality M<0, which is impossible, so the lady’s claim is valid.

Note that the M651 task is not very realistic. According to the condition, it turns out that cardboard is only three times lighter than a sofa. (We have to assume that the card contains not hats, but something heavier.) In addition, in the solution we believe that the dog weighs the same before and after the journey (if the conditions did not contradict each other, the dog must have grown at least one and a half times during the journey, which, of course, is unlikely).

V. Gutenmacher

M652. My wife cut a convex cardboard polyorganic into edges (along the edges) and sent this set of edges by mail to Vita. Vita skeletaled a convex polyorganic from all these faces. Could it be that the polyorganics of Zhenya and Vitya are not congenial?

Yes, it can work that way. One example of such a set of eight faces, from which two convex polyorganics of different shapes can be glued, is given in figure 1. The corresponding polyorganics are identical irregular quadrangular straight lines, glued together in different ways by a common base - a rectangle measuring 2 × 5; one of these polyorganics is symmetrical relative to the plane of this rectangle, and the other is symmetrical relative to its center (Fig. 2).

Think about what is the smallest number of faces that a set can consist of that admits non-concussive polyorganics. Do Zhenya's and Vite's polyorganics necessarily have equal volumes?

Note that if all the edges of the polyorganic had different lengths or were simply designated by different rooms.

Tasks M651-M655 are taken from the book “Correspondence Mathematical Algebra”, (M., “Nauka”, 1981).

⟦folio 27⟧

Kami on the faces - so that it would be known exactly which edge to glue with which - then the polyhedra of Zhenya and Vitya would definitely turn out to be congested. This is far from a simple Cauchy theorem on convex polyhedra; its proof can be read in the book by L. A. Lyusternik “Convex figures and polyhedra” (the second edition of this book should be published this year in the Library «Kvant»).

N. Vasiliev

M653. There is a ruler with two divisions. Using a ruler, you can draw arbitrary straight lines and segments of a certain length. Use it to construct a) some right angle; b) a line perpendicular to a given line.

We will consider the length of this segment between the marks to be equal to 1.

a) Let us draw two intersecting lines and plot on them from the point of their intersection O the segments OA, OB, OC, OD of length 1. Then all the angles of the quadrilateral ABCD will be right (each of them rests on the diameter AC or BD of a circle of radius 1 with center O).

b) On a given line from point O, plot the segments OA and OC of length 1. Then, on some lines passing through O, plot the segments OE and OF of length 1 in the same half-plane (see figure). Let us now draw lines AE and CF intersecting at some point B, and lines AF and CE intersecting at some point H. Then line BH will be perpendicular to this line, since the three altitudes of a triangle always intersect at one point (points E and F serve as the vertices of right angles based on the diameter AC of a circle of radius 1 with center O).

The theory of geometric constructions with a ruler and a standard of length is discussed in detail in D. Hilbert’s landmark book “Foundations of Geometry” (Moscow, Gostekhidat, 1948) in connection with the analysis of the system of axioms. These tools are used to solve multi-Greek construction problems (in part, through a given point you can draw a line parallel to a given one; from a given straight line you can plot an angle congruent to a given one), but, it turns out, not all those problems that can be solved with the help of a compass and a ruler.

V. Gutenmacher

M654. Is the following statement true: from any six natural numbers, you can choose three numbers, each two of which do not have a common factor greater than 1, or three numbers that have a common factor greater than 1?

This statement is incorrect. Here is an example of six numbers, among which no three have a common divisor (greater than 1) and no three are pairwise prime: 70, 165, 247, 286, 323, 357; one more example, with a smaller number: 14, 15, 18, 33, 55, 63. Let's show how to build similar examples.

Let's represent our numbers with six dots; those that have a common multiplier are contained by an “edge” (arc) and we write this common multiplier on the edge. In this case, it is necessary that all the written multipliers be coprime - say, these can be different prime numbers (otherwise three of our numbers will have a common multiplier) - and, in addition, that from each three points at least two are connected by an edge (otherwise we will find three pairwise coprime numbers). It is not difficult to construct such a graph—to connect the sixth point with edges so that the last condition is satisfied; for this it is not at all necessary to draw all 15 edges between six points - you can go around all or even six edges (figure a), b) corresponds to the two examples above); remains a variable number on all edges approaching each of the six vertices, and the example is ready.

Some readers made a mistake in solving this problem, citing the following fact (we present it in a formulation proposed in one of the old Hungarian optimizations and has since become classic): from six people you can choose three pairwise acquaintances or three pairwise strangers. This fact is true, but the point is that three integers that pairwise have a common multiplier are not required to have a common multiplier (greater than 1) for all of them.

N. Vasiliev

⟦folio 28⟧

M655. On the table of the official of the Ministry of Circumstances there are n volumes of the British Cyclopedia, several stacks of them. Every day, when arriving at work, the clerk takes one volume from each pile and puts the taken volumes in a new pile, then arranges the piles by the number of volumes (in non-ascending order) and fills out a statement in which he indicates the number of volumes in each pile. Apart from what was said above, the cynovnik does nothing.
a) What entry will be made in the statement in a month if the total number of volumes is n=3, n=6, n=10 (initial location is arbitrary)?
b) Prove that if the total number of volumes is n=k(k+1)/2, where k is a natural number, then, starting from a certain day, the statement will be filled with identical entries.
c) Investigate what will happen after many days of work for other values ​​of n.

Fig. 1.
n=3, m=3, T=2

Fig. 2.

When n=3 there are only three possible locations:
(1,1,1) - three stacks of one volume;
(3) - one stack of three volumes;
(2,1) - one stack of two and one of one volume.

The arrows on figure1 show what each location goes to the next day. From figure it is clear that, no matter where we start, no later than two days later (which is written as T=2), the arrangement (2,1) will arise and then it will repeat. figure 2 shows a similar graph for n=6. The number m of possible arrangements (vertices of the graph) here is 11. No later than T=6 days after the start of work, the arrangement (3,2,1) will arise, and then it will repeat. A similar graph for n=10 has m=42 vertices (to save space it is not drawn); in this case, no later than T=12 days after the start of work arising from the same graph, the same distribution of vertices.

Of course, not every oriented graph, from each vertex of which there is one arrow, has a single “final” vertex, that is, not always, and for this arrows, we will arrive at the same vertex and stay there (Fig. 3). The graph can break up into separate parts that are not connected by any arrow, and it can contain cycles. Therefore, the fact that for n=$\frac{k(k+1)}{2}$, starting from a certain day, the same arrangement (k, k-1, ..., 3, 2, 1) is obtained is not at all very significant, and we will now prove it, thereby solving point 6) of the problem conditions. Let's immediately consider an arbitrary value of n.

Let us imagine four infinite sheets of checkered paper (Fig. 4), the cells of which are arranged in pairs of natural numbers from left to right and from top to bottom: the cell with number (x,y) is in the column with number x and in the row with number y.

Let's make n figures and place them in the cells of our paper as follows: in the first column there is a column of figures, how many volumes are in the first stack, in the second column a column of figures, how many volumes in the second pile, etc. Placing figures on figure 4 means that there are 8, 3, 3, 1, 1, 1 volumes in the corresponding columns. The transformation that the mat-maker makes every day on his table can be represented on our sheet in the form of the following three operations:

1. Let's remove the figures located in the very bottom line (at figure 4 they are placed with figures in numbers).
2. Let's move the remaining fizek (they are placed in Latin letters) one cell down and one cell to the right.
3. Now let’s put the removed figures on paper, but not on the bottom line from where they were taken, but on the leftmost (vacated) column in the order from top to bottom in which they lay in the line from left to right.

As a result of these operations, figure 4 will go into figure 5. However, the result of our three operations differs from what the mat does, in that the stacks can be arranged in a different order than needed: on figure 5 there are 6 volumes in the leftmost column, and 7 volumes in the next one. This can be easily corrected by moving the figure M one cell to the left (as shown by the arrow on figure 5), but we will not do such movements for now, but will limit ourselves to a transformation consisting of the three described operations. In this case, the transformation of the fizek that was in the cell (x,y) goes to the cell (1,x), if y=1, or (x+1,y-1), if y>1.

Let's call the i-th diagonal the set of those cells (x,y) for which x+y=i+1. Under the influence of our transformation, the fizek located on the i-th diagonal does not contain it, but will move along it according to the rules:

$$\begin{align*}
(1,i) &\rightarrow (2,i-1) \rightarrow (3,i-2) \rightarrow \dots \rightarrow (i,1)
\end{align*}$$

Now let's complete our transformation:

4. In each line, where possible, move all fiseks one space to the left.

The additional transformation already exactly matches what the mat does. Now for some exercisers

⟦folio 29⟧

the value of $x+y$ can decrease, but it still cannot increase. But the quantity $x+y$ is a natural number. Therefore, it cannot decrease infinitely many times. Someday, for all chips, the value $x+y$ will no longer decrease. Let us prove that then for any $i$ the following conditions will be satisfied: if the $i$-th diagonal is not completely filled with chips, then there is not a single chip in the $(i+1)$-th diagonal.

Let us prove this by contradiction: let there be an empty square in the $i$th diagonal, and a token in the $(i+1)$th diagonal. The pieces on the $i$ diagonal (if any) move, ending up in their original places every $i$ steps. The piece on the $(i+1)$ diagonal moves, ending up in its original place every $(i+1)$ steps. Let's see what happens at moments 0 (counting origin), $(i+1), 2(i+1), 3(i+1), ..., i(i+1)$. The chip on the $(i+1)$-th diagonal at these moments ends up in the same place where it was at the zero moment. Let the place on the $i$-th diagonal seem to move along with the chips, and at the moments of time listed above it will be on all the cells of the $i$-th diagonal, including being to the left of the cell where the chip is located. But then this piece moves to the left, and we assumed that all such movements have already ended. The statement has been proven.

What kind of arrangement of chips is this, in which only an empty one can follow an incomplete one diagonally? If $n = \frac{k(k+1)}{2}$, then there is only one such arrangement: all diagonals from the 1st to $k$ are filled with chips, and all subsequent diagonals are empty. Let now $n \neq \frac{k(k+1)}{2}$. Then there exists $k$ such that $\frac{k(k+1)}{2} < n < \frac{(k+1)(k+2)}{2}$.

Let's put $r=n-\frac{k(k+1)}{2}$. In this case, the arrangement of chips, in which the incomplete diagonal is followed by empty ones, is as follows: all diagonals from the 1st to the $k$th are filled with chips, on the $(k+1)$th diagonal there are $r$ chips, and the following diagonals are empty. The pieces located on the $(k+1)$ diagonal move along it, ending up in their original places every $(k+1)$ steps. This is the answer to question c).

If the number of chips on the $(k+1)$-th diagonal is determined only by the total number of chips, then their location depends on the initial location of the chips, therefore, with $n \neq \frac{k(k+1)}{2}$, depending on the initial location of the volumes, different sets of periodic repeating records of the official can be obtained (including with the same $n$, different period lengths can be obtained).

It is interesting to find out, in addition, what is the delivery time to reach the described one from any initial state with $n$ chips. For simplicity, the constraint $n = \frac{k(k+1)}{2}$ and denote by $T(k)$ the shortest time in which the arrangement $(k,k-1,...,3,2,1)$ is obtained from any initial arrangement of volumes.

Let us prove that $T(k) \geq k(k-1)$. To do this, we present for each $k$ a specific distribution of $\frac{k(k+1)}{2}$ volumes in stacks, which turns into final only in $k(k-1)$ steps: $(k-1,k-1,k-2,k-3,k-4,...,3,2,1,1)$. Its depiction on our checkered paper differs from the depiction of the final distribution only in that one chip is in the wrong place: in cell $(k+1,1)$ together with cell $(1,k)$. Under the influence of our transformation, only the chip on the $(k+1)$th diagonal and the “hole” (that is, “lack of a chip”) on the $k$th diagonal each begin to move along its own diagonal. Since the $k$th diagonal is shorter than the $(k+1)$th diagonal by one, the hole will support the counter and catch up with it in $(k+1)$ steps.

⟦folio 30⟧

F664.*) When photographing a distant exact source in the photograph, due to the need for the qualities of the object and the use of photographic material, a light circle with a diameter of $d=0,1$ mm is obtained. From what maximum distance can two precise sources be formed under the same conditions, located at a distance of $l=1$ cm from each other, so that their images do not overlap in the photograph? The focal length of the object is $F=5$ cm.

The further away the sources are located from the camera, the smaller the distance between the centers of spots on the film. Minimum distance between spot centers
$\Delta l=d=0,1$ mm

(in this case, the spots touch each other without overlapping) many times less than the distance $l$ between the sources; Consequently, the sources are located far from the camera, and the images can be considered to lie in the focal plane of the object. Then the required distance $L$ can be determined from the correspondence
$$\frac{L}{F} = \frac{l}{\Delta l} = \frac{l}{d} \Rightarrow L = \frac{Fl}{d} = 500 \text{ см.}$$

At shorter distances, the spots on the film will partially overlap.

A. Zilberman

F665. In a thermally insulated state, there are two liquids with specific thermal capacities $c_1$ and $c_2$, separated by a heteroconducting partition. Liquid temperatures vary. The partition is removed, and after thermal equilibrium is established, the difference between the initial temperature of one of the liquids and the temperature established in the state turns out to be half the difference in the initial temperature of the liquid. Find the ratio of masses $m_1$ and $m_2$ of the first and second liquid.

Let, as a result of mixing the liquid, the initial temperatures of which were $t_1$ and $t_2$, the temperature of the mixture in the vessel became equal to $t$. Since the vessel is thermally insulated ($\Delta Q=0$),
$$c_1 m_1 (t-t_1) + c_2 m_2 (t-t_2) = 0;$$
from here
$$\frac{m_1}{m_2} = \frac{c_2}{c_1} \frac{t-t_2}{t_1-t}.$$
According to the conditions of the problem
$$2 (t_1-t) = t_1-t_2 \Rightarrow t-t_2 = t_1-t \Rightarrow \frac{t-t_2}{t_1-t} = 1.$$
Thus,
$$\frac{m_1}{m_2} = \frac{c_2}{c_1}$$

— the ratio of liquid masses is equal to the inverse ratio of the heat capacity.

A. Buzdin

F666. The radius of the inner area of ​​the ball bearing is $r$, and the outer area is $R$ (see figure). How many revolutions will the ball make between this rim if the outer rim makes $n_1$ and the inner rim makes $n_2$ revolutions around the axis?

The conditions are to consider the number of revolutions made by each wallpaper counterclockwise as positive, and clockwise as negative.

In accordance with the principle of independence of motion, the final position of the ball will be the same for any sequence of rotations of each of the cages. It is only important that the total angle of rotation of the outer ring is equal to $\varphi_1 = 2\pi n_1$, and that of the inner one - $\varphi_2 = 2\pi n_2$. Therefore, we represent each of the angles as the sum of two terms
$$\varphi_1 = \alpha + \beta, \quad \varphi_2 = \alpha + \gamma.$$

Rotation of the ball by the same angle $\alpha = 2\pi n_0$ corresponds to the movement $\alpha \frac{R+r}{2}$ of the center of the ball along an arc

*) You will find the solution problem F663 in S. Krotov’s note “Mathematical math book in an inertial reporting system” (p. 32).

⟦folio 31⟧

circle of radius $(R+r)/2$. In this case, the point at which the ball contacts the holder does not move along it. In other words, there is no rolling of the ball on the surface of the cages, and relative to the stationary reporting system, the ball rotates together with the cages at the same angle $\alpha$.

We choose the angles $\beta = 2\pi n_3$ and $\gamma = 2\pi n_4$ in such a way that at $\alpha = 0$ successive rotations of the outer frame by the angle $\beta$, and the inner one by the angle $\gamma$ returns the center of the ball to the starting point. In this case, the ball will roll along the surface of the cages.

The problem allows an unambiguous solution only if there is no scaling. This means that the lengths of the arcs, which are traces of the points of contact on the ball and on the clips, must be the same, that is

$$|\beta|R = |\gamma|r = |\Theta|\frac{R-r}{2} \text{ и } \beta R + \gamma r = 0.$$

Here $\Theta$ is the angle of rotation of the ball relative to the stationary reporting system at $\alpha = 0$, and $\frac{R-r}{2}$ is the radius of the ball. From the written equations it follows:

$$n_1 = n_0 + n_3, \ n_2 = n_0 + n_4, \ n_3R + n_4r = 0.$$

From here we find the number of revolutions of the ball center around the axis of the clips:

$$n_0 = \frac{n_1R + n_2r}{R + r}.$$

During the same period of time, the ball will rotate relative to the stationary reporting system by an angle $\varphi = \alpha - \Theta$, where $\Theta = \beta \frac{2R}{R-r}, \ \varphi = 2\pi n.$

Consequently, if the outer race makes $n_1$, and the inner one - $n_2$ revolutions, the ball, which does not slip through the rings, will make

$$n = \frac{n_1R - n_2r}{R - r}$$

revolutions relative to stationary observing.

V. Bukhovtsev

F667. The electron is located inside the salt at a distance of $r$ from its axis. In a short time $\Delta t$, the field induction inside the salt increased from $B$ to $2B$. How did the speed of the electron change? How small must the value $\Delta t$ be for the solution to be correct?

When the magnetic field changes, an output electric field occurs. The intensity $E$ of this field at points located at a distance $r$ from the axis of the solenoid can be found by knowing the induced emf in the circuit, which represents a circle of radius $r$ and equal in absolute value $a = \frac{\Delta v}{\Delta t} = \frac{eE}{m}$.

Thus, in a short time $\Delta t$ the speed of the electron changes by values ​​$\Delta t$, that is, $\frac{eBr}{2m} \ll c.$

When solving the problem, we did not study the effect of a magnetic field on a moving electron. The force acting from the magnetic field imparts an increase to the electron, directed along the radius of the soleud. For the above solution to be correct, the following condition must be met: during the time $\Delta t$ the change $\Delta v_r$ of the speed along the radius
