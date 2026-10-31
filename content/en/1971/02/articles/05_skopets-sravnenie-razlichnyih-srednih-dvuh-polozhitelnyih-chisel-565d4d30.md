---
id: 1971-2-skopets-sravnenie-razlichnyih-srednih-dvuh-polozhitelnyih-chisel-565d4d30
issue: kvant_1971_2
year: 1971
number: "2"
title: Comparing different averages of two positive numbers
authors:
  - Скопец З. А.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 22
page_last: 25
page_labels: 20-23
tag: F205
lang: en
source: kvant_digital
extraction: vision
content_sha256: 972e21c9e72ceb1358da6c07f6da1a674580e1be0230073c44c8589265589519
prompt_sha256: draft-1
translated_from: content/ru/1971/02/articles/05_skopets-sravnenie-razlichnyih-srednih-dvuh-polozhitelnyih-chisel-565d4d30.md
source_content_sha256: b58de987b7777e6156724bf8e4094c9b891053c126ce80a58690175aa28eddc0
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 20⟧

COMPARISON
DIFFERENT MEDIUMS
TWO POSITIVE
NUMBERS

3. A. Skopets

It is well known that two positive numbers $a$ and $b$ or two segments of lengths $a$ and $b$ are associated with their arithmetic mean $\frac{a+b}{2}$ and geometric mean $\sqrt{ab}$, with $\sqrt{ab} \leq \frac{a+b}{2}$ (the equality holds only for $a=b$). The algebraic proof of this inequality is extremely simple:

$$(a-b)^2 \geq 0, (a+b)^2 \geq 4ab,$$
$$ab \leq \left(\frac{a+b}{2}\right)^2 \text{ и } \sqrt{ab} \leq \frac{a+b}{2}.$$

The geometric proof is based on one metric relationship between the elements of a right triangle: the height of a right triangle, lowered to the hypotenuse, is the geometric mean of the projections of the legs onto the hypotenuse. This height does not exceed the radius of the circle circumscribed about the triangle, while the arithmetic mean of the segments of the hypotenuse is exactly equal to the radius of this circle.

In addition to the indicated two interseno means, two more frequently occurring means are considered: the quadratic mean $\sqrt{\frac{a^2+b^2}{2}}$ and the harmonic mean $\frac{2}{\frac{1}{a}+\frac{1}{b}} = \frac{2ab}{a+b}$.

Let us give an algebraic and then a geometric proof that

$$\frac{2ab}{a+b} \leq \sqrt{ab} \leq \frac{a+b}{2} \leq \sqrt{\frac{a^2+b^2}{2}},$$

and in all cases the equal sign holds if and only if $a=b$. Let us denote the averages written out in (1) alternately by the letters $M, N, K, L$. We have already checked the inequality $N \leq K$. It remains to prove that 1) $K \leq L$; 2) $M \leq N$.

1) $K^2 - L^2 = \left(\frac{a+b}{2}\right)^2 - \frac{a^2+b^2}{2} = -\frac{1}{4} (a-b)^2 \leq 0,$

that is, $K \leq L$, and $K=L$ only for $a=b$;

2) $M^2 - N^2 = \frac{4a^2b^2}{(a+b)^2} - ab = -\frac{ab (a-b)^2}{(a+b)^2} \leq 0,$

that is, $M \leq N$, and $M=N$ at $a=b$.

The validity of inequalities (1) has been proven *).

We will now look at the geometric proof of these inequalities, which may turn out to be

*) These inequalities have already been discussed in the article by A. P. Savin “Maximum, minimum and the theorem on averages” («Kvant» No. 11, 1970).

⟦folio 21⟧

Useful in solving geometric problems.

Let the given two segments be $a$ and $b$. If $a=b$, then by checking we are convinced of the validity of inequalities (1). Assume $a>b$ and construct a trapezoid $ABCD$ with bases $AB$ and $CD$ equal to the correspondence of $a$ and $b$ (Fig. 1). Let us draw a secant line $l$ so that it is parallel to the bases of the trapezoid and cuts it into two equal trapezoids $T_1(ABL_2L_1)$ and $T_2(L_1L_2CD)$. Let us calculate the length of the segment $L_1L_2$, which we denote by $x$. From the equivalence of trapezoids $T_1$ and $T_2$ it follows that $(a+x)h_1=(x+b)h_2$, or

$$h_1:h_2=(x+b):(a+x),$$

(2) where $h_1$ is the height of trapezoid $T_1$, and $h_2$ is the height of trapezoid $T_2$. From the similarity of triangles $AL_1U$ and $DL_1V$ it follows that

$$h_1:h_2=(a-x):(x-b).$$

(3) Comparing (2) and (3), we obtain

$$\frac{x+b}{a+x}=\frac{a-x}{x-b},$$

where is that $x^2-b^2=a^2-x^2$ from, and finally

$$x=\sqrt{\frac{a^2+b^2}{2}}.$$

So, it has been proven that $L_1L_2=\sqrt{\frac{a^2+b^2}{2}}.$

Considering (2), we have $h_1<h_2$, so the segment $L_1L_2$ lies closer to the larger base $AB$ of the trapezoid than its midline $K_1K_2$, which is equal to $\frac{a+b}{2}$. The length of the segment $x$, parallel to the bases of the trapezoid, the ends of which lie on the lateral sides of the trapezoid, is enclosed between the lengths of its bases (this follows from the properties of similarity). So, at $a>b$ we have $\frac{a+b}{2}<\sqrt{\frac{a^2+b^2}{2}}$. This inequality remains in force for $a<b$ (it is enough to change the notations: $a$ to $b$ and $b$ to $a$). Therefore, for any $a$ and $b$ we have $\frac{a+b}{2}\leq\sqrt{\frac{a^2+b^2}{2}}.$

Let's move on to the comparison of $N$ and $K$. To do this, we draw a secant line $n$ so that it cuts the given trapezoid into two similar (homothetic) trapezoids $T_1'(ABN_2N_1)$ and $T_2'(N_1N_2CD)$ (Fig. 2). Let us denote the length of the segment $N_1N_2$ by $y$. From the similarity of trapezoids $T_1'$ and $T_2'$ it follows that $a:y=y:b$, or

$$y=\sqrt{ab}.$$

Therefore, $N_1N_2=\sqrt{ab}$. From the similarity of trapezoids (taking into account (4)) it also follows that

$$AN_1:N_1D=a:y=\sqrt{\frac{a}{b}}>1.$$

This means that line $n$ is further from the base $AB$ of the trapezoid,

⟦folio 22⟧

Than the middle line is $K_1K_2$, and therefore $N_1N_2 < K_1K_2$. So, for any $a$ and $b$ we have

$$\sqrt{ab} \leq \frac{a+b}{2}.$$

Finally, let us draw a line $m$ through the intersection point $O$ of the diagonals of this trapezoid, parallel to its bases and intersecting the lateral sides at points $M_1$ and $M_2$ (Fig. 3). Obviously $AM_1:M_1D = AO:OC = a:b$.

But $\frac{a}{b} > \sqrt{\frac{a}{b}}$, because $a > b$. Therefore, taking into account (5), we conclude that the segment $M_1M_2$ is close to the smaller base of the trapezoid than the segment $N_1N_2$, and therefore $M_1M_2 < N_1N_2$. On the other side,

$$M_1O:a = DO:DB = CO:CA = OM_2:a.$$

This means $M_1O = OM_2$. Next,

$$\frac{M_1O}{a} + \frac{OM_2}{b} = \frac{DO}{DB} + \frac{BO}{DB} = 1.$$

From this it follows that $M_1M_2 = 2M_1O = 2\frac{1}{a} + \frac{1}{b}$, and therefore $M_1M_2 = \frac{2ab}{a+b}$. So, $M < N$ if $a > b$. Similarly, it is proved that $M < N$ if $a < b$. Therefore, for any $a$ and $b$ we have

$$\frac{2ab}{a+b} \leq \sqrt{ab}.$$

This correctly proves inequality (1).

So all four are average

$$M_1M_2 = M = \frac{2ab}{a+b}; \quad N_1N_2 = N = \sqrt{ab};$$

$$K_1K_2 = K = \frac{a+b}{2}; \quad L_1L_2 = L = \sqrt{\frac{a^2+b^2}{2}}.$$

below the two segments $a$ and $b$ received a geometric origin: if these two segments serve as the bases of a trapezoid, then close to the larger base of the trapezoid is the quadratic mean, followed by the arthmetic mean, then comes the geometric mean and, finally, the harmonic mean (Fig. 4). Obviously, the lengths of these segments do not depend on the shape of the trapezoid - for all trapezoids with given lengths $a$ and $b$ bases, the indicated averages of the corresponding ones are equal. When $a = b$, the trapezoid turns into a parallelogram and all four middle ones coincide and become equal to $a$.

It remains to construct these four averages over the given segments $a$ and $b$. We give such constructions so that one can be convinced of the truth of inequalities (1) in another way.

Let us plot on the straight line on one side of the point $O$ the segments $OA = a$, $OB = b$, where $a < b$. Let $S$ be the midpoint of the segment $AB$ (Fig. 5). Then

$$OS = a + \frac{b-a}{2} \text{ или } OS = \frac{a+b}{2} = K.$$

⟦folio 23⟧

Fig. 5.

$$OC = M = \frac{2ab}{a+b};$$
$$OP = N = \sqrt{ab};$$
$$OS = K = \frac{a+b}{2};$$
$$OE = L = \sqrt{\frac{a^2+b^2}{2}};$$
$$M < N < K < L.$$

Let us construct a circle on the segment $AB$, as on a diameter, and draw tangents $OP$ and $OQ$ ($P, Q$ are points of tangency) to it from point $O$. Let us use the relationship between the secant and tangent segments drawn from the point $O$ to the circle:
$$OP^2 = ab.$$ Therefore, $OP = \sqrt{ab} = N$, and $N < K$. Next, let $PQ$ intersect $OS$ at $C$. Then $OP^2 = OS \cdot OC$ and
$$OC = ab: \frac{a+b}{2} = \frac{2ab}{a+b} = M,$$
and $M < N$.

Finally, we construct the radius $SE$ perpendicular to $AB$. We have
$$OE^2 = \left(\frac{a+b}{2}\right)^2 + \left(\frac{a-b}{2}\right)^2,$$
$$OE = \sqrt{\frac{a^2+b^2}{2}} = L,$$
and $K < L$. So, if $a \neq b$, then $M < N < K < L$.

Exercises
1. On a straight line on one side of the point $O$, the segments $OA = a, OB = b, a < b,$ are laid out and a circle $k$ of diameter $AB$ with center $S$ is constructed. Next, $k_1$ with a center $O$ of radius $OP$ and $k_2$ with a diameter $OS$ are constructed.

Prove that if the line passing through $O$ intersects part of the lines $g, k_1$ and $k_2$ located inside $k$ at points $C_1, P_1, S_1$, and the circle $k$ at points $A_1$ and $B_1$, then
$$OC_1 = \frac{2a_1b_1}{a_1+b_1},$$
$$OP_1 = \sqrt{a_1b_1},$$
$$OS_1 = \frac{a_1+b_1}{2} \quad (a_1 = OA_1, b_1 = OB_1).$$

2. Find even ratios connecting each three averages of two numbers $a$ and $b$:
$$M = \frac{2ab}{a+b},$$
$$N = \sqrt{ab},$$
$$K = \frac{a+b}{2},$$
$$L = \sqrt{\frac{a^2+b^2}{2}}.$$

3. Prove the truth of the following inequalities:
a) $N - M \leqslant K - N,$
b) $K - M \leqslant L - N,$
b) $L - K \leqslant K - N.$

4. A circle with center $S$ on the x-axis of the right angular coordinate system intersects the axis at points $A(a, 0)$ and $B(b, 0), a > 0, b > 0, a < b$. A secant line passing through the origin $O$ intersects the circle at points $A_1$ and $B_1$. Write an equation of the lines to which those points $C_1(x, y)$ on the secants belong, for which
$$(OC_1)^2 = \frac{1}{2} \left[ (OA_1)^2 + (OB_1)^2 \right].$$

5. On the continuation of side $AB$ of triangle $ABS$ beyond point $A$ there is a bottom point $O$, through which a line is drawn intersecting $AS$ and $BS$ corresponding at points $B_1$ and $A_1$. Through the intersection point $P$ of lines $AA_1$ and $BB_1$, a line $SP$ is drawn, intersecting $AB$ at point $C$. Prove that $c = \frac{2ab}{a+b}$, where $OA = a, OB = b, OC = c$.

6. Given a parallelogram $OABC$ and a midline $MN$ of a triangle $ABC$ parallel to $AC$. A straight line is drawn through vertex $O$; intersecting the lines $BC, CA, AB, MN$ of the corresponding one at points $A_0, B_0, C_0, D_0$. Prove that $\frac{1}{a} + \frac{1}{b} + \frac{1}{c} = \frac{3}{d}$, where $OA_0 = a, OB_0 = b, OC_0 = c, OD_0 = d$; point $A_0, B_0, C_0, D_0$ is located on one side of $O$ ($d$ is the harmonic mean of the segment $a, b, c, d$).

How does the stated equality change if the points $A_0, B_0, C_0, D_0$ do not lie on the same side of $O$?
