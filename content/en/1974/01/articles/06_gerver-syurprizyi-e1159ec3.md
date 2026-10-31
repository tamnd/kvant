---
id: 1974-1-gerver-syurprizyi-e1159ec3
issue: kvant_1974_1
year: 1974
number: "1"
title: Surprises
authors:
  - Гервер М. Л.
rubric: osnovnye-stati
page_first: 15
page_last: 23
page_labels: 13-21
tag: 7T9S
lang: en
source: kvant_digital
extraction: vision
content_sha256: 89548a2f39a38eb9037731d838738617fe53a0019110c611deb0d620a5fc8a0d
prompt_sha256: draft-1
translated_from: content/ru/1974/01/articles/06_gerver-syurprizyi-e1159ec3.md
source_content_sha256: 619229a4fbdc009ce5b0e0e569e6b5fe8a3aed8a8895f4752cf3416729116248
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 13⟧

A few words about the name.
First, we will analyze problem M195 from the Kvant Problem Book. It will be found that it is closely related to one classical construction of geometric circles. Then other unexpected connections and facts will emerge.
The most important sorry... But, shhh! Otherwise, what kind of sorry will it be?

§ 1. The problem of three quadrilaterals
M195. Dan $\Delta ABC$. How many points $D$ are there such that the perimeters of the quadrilaterals ADBC, ABDC and ABCD are the same*)?

Solution. Let's construct three circles ($\alpha$, $\beta$ and $\gamma$) with centers $A$, $B$ and $C$, which touch each other externally in pairs (Fig. 1).

*) Only points $D$ are considered that lie in the plane $\Delta ABC$.

The radii of these circles $a, b$ and $c$ are determined from the system of equations
$$a + b = AB, a + c = AC, b + c = BC.$$
Thus,
$$a = p - BC, b = p - AC, c = p - AB,$$
where $p$ is the half-perimeter $\Delta ABC$.

Let $D$ be the center of circle $\delta$, which externally touches circles $\alpha$, $\beta$ and $\gamma$. The radius $\delta$ is denoted by $d$.

We assume it is known that the circle $\delta$ exists. The construction of such a circle is the content of the meaning of Apollonius’s task*), solved by Apollo of Perga in the 3rd century BC. e.

From figure 1 it is immediately clear that each of the three quadrilaterals ADBC, ABDC and ABCD has a perimeter $2(p+d)=2(a+b+c+d)$. Thus, although one Izsky point $D$ exists.

Can there be more than one such point? Moving on to solving this issue, first of all we will make sure that if the parameters ADBC, ABDC and ABCD are equal, then the point $D$ lies outside the circles $\alpha$, $\beta$ and $\gamma$ and it makes them equal. Let's put $AD=x, BD=y, CD=z$. then the equality of the perimeters of the quadrilaterals under consideration will be written as follows:
$$2p - AB + x + y = 2p - AC + x + z = 2p - BC + y + z.$$ (2)

Subtracting equality (2) term by term from the number $p+x+y+z$, we obtain
$$z - (p - AB) = y - (p - AC) = x - (p - BC).$$

*) I already talk about this problem in the article by Savin A.P., Inversion and the Apollonius problem. «Kvant», 1971, No. 8.

⟦folio 14⟧

Using formulas (1), we find
$$z-c=y-b=x-a.$$

According to (3), the numbers $x-a, y-b$ and $z-c$ have the same sign. Moreover, $x-a>0$, if the point $D$ lies outside $\alpha$, and $x-a\leq 0$, if $D$ lies inside or on $\alpha$; the signs $y-b$ and $z-c$ have a similar meaning. Since no point immediately belongs to all those circles bounded by circles $\alpha$, $\beta$ and $\gamma$, it follows
$$x-a=y-b=z-c\leq 0$$
will be excluded. Means,
$$x-a=y-b=z-c>0,$$
$D$ lies outside $\alpha$, $\beta$ and $\gamma$ and is equal to them.

Operation on this, we will prove the only point $D$.

Let (for definition) $\alpha$ be the smallest of the circles $\alpha$, $\beta$ and $\gamma$:
$$a\leq b, a\leq c.$$ Using radii $b-a$ and $c-a$ we describe circles $\beta'$ and $\gamma'$ with centers $B$ and $C$. The point $D$, which lies outside $\alpha$, $\beta$ and $\gamma$ and is equal to them, is also equal to the point $A$ and the circle $\beta'$ and $\gamma'$ (Fig. 2). Let's construct three more circles ($\alpha''$, $\beta''$ and $\gamma''$) with centers $A$, $B$ and $C$ and radii $AD$, $BD$ and $CD$. Let $T$ be an arbitrary point lying inside $\alpha''$ or on $\alpha''$ and different from $D$. Then (Fig. 2) $T$ lies either outside $\beta''$, or outside $\gamma''$, or outside both of these circles. Thus, $T$ is located closer to $A$ than to one of the circles $\beta'$ or $\gamma'$.

The last reasoning shows that two distinct points $D_1$ and $D_2$ cannot be equidistant from $A$, $\beta'$ and $\gamma'$: assuming the opposite (the empty $D_1$ and $D_2$ are such points, and $AD_1\geq AD_2$) and denoting $D_1$ by $D$, $a$ $D_2$ through $T$, we immediately come to opposition.

The only point $D$ has been proven.

§ 2. Dual problem

In § 1 I discovered a technical connection between the problem of three quadrilaterals and Apollo's problem. The formulation of the latter (“Construct a circle tangent to three given circles”) does not indicate whether the tangency should be external or internal. In § 1, the circle $\delta$ touched $\alpha$, $\beta$ and $\gamma$ externally. Let us denote by $\epsilon$ the circle that all three circles $\alpha$, $\beta$ and $\gamma$ touch from the inside; we call its center $E$ (Fig. 3).

He asks: isn’t finding the point $E$ a solution to some problem, similar to the problem of three quadrilaterals? (Before reading further, try, of course, to come up with such a problem yourself.)

Let us put $AE=x, BE=y, CE=z$, and denote the radius of the circle $\epsilon$ by $e$. Then (Fig. 3) $x+a=y+b=z+c=e$. Hence $x+y+a+b=2e$, that is $x+y+AB=2e$. It is also established that $x+z+AC=y+z+BC=2e$. The quantities $x+y+AB, x+z+AC$ and $y+z+BC$ are the perimeters of triangles $AEB, AEC$

Fig. 2.

Fig. 3

⟦folio 15⟧

and WEIGHT. Thus, the center $E$ of the circle e turns out to be a solution to the problem of “three triangles of equal perimeter”, which is similar to the original problem of quadrilaterals.

Point of formulation of the new problem:

“Dan $\Delta ABC$. How many maxims $E$ are there such that the perimeters of triangles $AEB, AEC$ and $BEC$ are the same*)?>

Above we established that at least one such point $E$ exists.

U pravannya
1. Prove that there are no other such points.
2. Prove the converse of the statement above: let the point $E$ be such that the perimeter of each of the triangles $AEB, AEC$ and $BEC$ is equal to $2e$, then $\alpha$, $\beta$ and $\gamma$ are tangent from the inside to a circle of radius $e$ with center $E$.

In the problems of three quadrilaterals and three triangles, we not only proved the existence and uniqueness of the points $D$ and $E$, but also found formulas for the perimeters: $2(p+d)=2(a+b+c+d)$ and $2e$. He asks: is it possible to calculate these perimeters, knowing the sides $\Delta ABC$? The radii $a, b$ and $c$ are calculated using simple formulas (1). Are $d$ and $e$ expressed by $a, b$ and $c$?

A positive answer to this question is given in § 3.

§ 3. Frederick Soddy's formula

We have already noted that Apollonius’ problem was solved in the 3rd century BC. It would seem that these days she can no longer contain anything new and unexpected. However, relatively recently, a beautiful formula was obtained showing how the dimensions of a circle correspond to each other in Apollonius’ problem.

This formula makes typing even worse when you find out it wasn't created by a professional.

*) Considers only points $E$ that lie in the plane $\Delta ABC$.

mathematician, and chemist - Frederick Soddy.

Let us denote by $k, l, m$ and $n$ the reciprocals of the radii of circles $\alpha, \beta, \gamma$ and $\delta$ from § 1:

$k=1/a, l=1/b, m=1/c, n=1/d$.

Then

$2(k^2+l^2+m^2+n^2)=(k+l+m+n)^2$.

This elegant relationship is Soddy's formula.

It can be considered as a quadratic equation for $n$ (the numbers $k, l$ and $m$ are considered known). Solving this equation, we get

$n_{1,2}=k+l+m\pm 2\sqrt{kl+lm+mk}$.

The positive root $n_1$ is, of course, $1/d$. What is $n_2$?

It turns out that $n_2=-1/e$, where $e$ is the radius of the circle from § 2.

What is the meaning of the plus and minus signs: why is $1/d$ taken with a flat, and $1/e$ with a minus?

The reciprocal of the radius has a special name: “curvature”. The larger the radius, the more smoothly the circle “curves” - the less its curvature.

A straight line (the limiting case of a circle - “a circle of infinite radius”) has zero curvature. It would be natural to use signs to distinguish between the curvatures of “convex” and “concave” curvatures. But what are convex and concave circles?

All circles are, of course, “the same.” But when it is outside the circle, then it is natural to consider it convex, and if it is inside the same circle, then it appears concave. Thus, “from the point of view of circles $\alpha, \beta$ and $\gamma$” the circle and it are reasonable to consider “different”: the first is convex, the second is concave.

We will present the derivation of Soddy's formula in § 6.

§ 4. Main sorpiriz

We have already had several challenges: in § 1 the problem of quadrilaterals with equal perimeters was suddenly reduced to a special case of Apollonius’ problem, in § 2 it is necessary to show the order of action - we first solved and then formulated the problem of triangles with equal perimeters, in § 3 we will give the form -

⟦folio 16⟧

mulu, which a modern chemist has embellished one of the oldest geometric problems.

But the main controversy will be presented now.

In our proofs we used the following “obvious” geometric facts:

I. Let three circles $\alpha$, $\beta$ and $\gamma$ touch each other externally in pairs. Then there is exactly one circle $\delta$ that touches $\alpha$, $\beta$ and $\gamma$ externally, and exactly one circle $\varepsilon$ that $\alpha$, $\beta$ and $\gamma$ touch internally.

II. Let three circles $\alpha''$, $\beta''$ and $\gamma''$ pass through one point $D$. Then any point $T$ lying inside $\alpha''$ is located either outside $\beta''$ or outside $\gamma''$ (or outside both of these circles).

Both facts are... incorrect. (Posny and solution problem M195 is also incorrect.)

§ 5. Major repairs

figure 4 shows circles $\alpha$, $\beta$ and $\gamma$ for which there are two circles ($\delta_1$ and $\delta_2$) touching $\alpha$, $\beta$ and $\gamma$ externally, and for which there is no circle $\varepsilon$ that has $\alpha$, $\beta$ and $\gamma$ internal touch.

Figure 5 defines “fact” II.

Of course, the conclusions based on “facts” I and II are also incorrect—all data built on a shaky foundation collapses!

Fortunately, the destruction is not that catastrophic.

Theorem. Let circles $\alpha$, $\beta$ and $\gamma$ touch each other externally in pairs. Then three (and only three) cases are possible:

I. There is exactly one circle $\delta$ which touches $\alpha$, $\beta$ and $\gamma$ externally, and exactly one circle $\varepsilon$ which $\alpha$, $\beta$ and $\gamma$ touch internally.

II. $\alpha$, $\beta$ and $\gamma$ have a common tangent (and lie along one line from it), while exactly one circle $\delta$ touches $\alpha$, $\beta$ and $\gamma$ externally, and not a single circle $\alpha$, $\beta$ and $\gamma$ do not touch from the inside.

III. There are exactly two circles $\delta_1$ and $\delta_2$, each of which touch $\alpha$, $\beta$ and $\gamma$ externally, and there is no circle that $\alpha$, $\beta$ and $\gamma$ touch internally.

A few words about inversion.

To prove this theorem, we will use the inversion method*).

Let us recall the definition and some properties of inversion.

About the limit. Let $Q$ be a circle with center $O$ of radius $R$, lying in the plane $P$. The inversion with respect to the circle $Q$ is called the following transformation of the plane $P$: each point of the $M$ plane

*) Savin A.P., Inversion and the Apollo problem. «Kvant», 1971, No. 8.

Fig. 4.

Fig. 5.

⟦folio 17⟧

Fig. 6.

$\Pi$, lying at a positive distance $r$ from $O$, goes to a point $M'$, lying on the ray $OM$ at a distance $r'$ from $O$, such that $rr' = R^2$; $O$ is called the center of inversion, $R^2$ is the inversion coefficient.

Properties 1. If $M$ belongs to $Q$, then $M' = M$; if $M$ lies inside $Q$ and is different from $O$, then $M'$ lies outside $Q$; if $M$ lies outside $Q$, then $M'$ lies inside $Q$.

2. Straight lines and circles transform during inversion into straight lines and circles, and:

a) points lying on a line passing through $O$ go to points on the same line;

b) a straight line not passing through $O$ goes into a circle passing through $O$;

b) a circle passing through $O$ goes into a line not passing through $O$;

d) a circle not passing through $O$ goes into a circle not passing through $O$; in this case $O$ lies either outside of both of these circles or inside of both of these circles.

3. If two circles (or a line and a circle) touch at a point $M$ other than $O$, then their images $^*$) also touch at a point $M'$; if the point of tangency coincides with $O$, then these circles (or a straight line and a circle) turn into parallel straight lines.

*) That is, what they turn into after inversion.

Fig. 7.

For those who learned about inversion for the first time, we recommend either proving the listed properties on their own, or reading the above-mentioned article by A.P. Savin.

As a control that will help you find out how well you know the inversion method, we suggest finding an error in the “solution” of the following problem.

Let circles $\alpha$ and $\beta$ touch externally at point $O$ (Fig. 6). Let us denote the geometric location of a point by $\Gamma$. When inverting with the center of inversion $O$, circles $\alpha$ and $\beta$ will turn into parallel lines $\alpha'$ and $\beta'$ (Fig. 6). Circles $\gamma$ touching $\alpha$ and $\beta$ will turn into circles $\gamma'$ touching $\alpha'$ and $\beta'$. The dotted line $\Gamma'$ on figure 6 is the locus of the point that is the center of the circles $\gamma'$. So, the curve $\Gamma$ turned into a straight line during inversion. This means that $\Gamma$ is either a circle or a straight line.

If you find an error in the above “solution”, it’s time to move on to the proof of the theorem formulated at the beginning of § 5.

Proof of the theorem. Circles $\alpha$, $\beta$ and $\gamma$ by condition are pairwise externally tangent to each other (Fig. 7, a). The point of contact between $\alpha$ and $\beta$ will be denoted by $O$.

⟦folio 18⟧

Let us take an arbitrary circle $Q$ with center $O$ and take the inversion of the relative circle (Fig. 6).

During inversion, circles $\alpha$ and $\beta$ will turn into parallel lines $\alpha'$ and $\beta'$, and circle $\gamma$ into circle $\gamma'$, tangent to these lines (Fig. 7, b). The center of inversion $O$ is located (check it!) in the band between lines $\alpha'$ and $\beta'$ outside the circle $\gamma'$.

There are obviously exactly two circles touching both $\alpha'$, $\beta'$, and $\gamma'$ (Fig. 7, f). In this case, three cases are possible:

I. The point $O$ lies inside one of these circles (and outside the other).

II. The point $O$ lies on one of them (and outside the other).

III. Point $O$ lies outside both of these circles.

In cases I and II, we denote the circles under consideration by $\delta'$ and $\varepsilon'$ (and by $\delta'$ - the one outside which the point $O$ lies), in case III we denote them by $\delta'_1$ and $\delta'_2$.

Any circle or line tangent to both $\alpha$, $\beta$, and $\gamma$ is reshaped when inverted into a circle tangent to $\alpha'$, $\beta'$, and $\gamma'$. In case I, circles $\delta'$ and $\varepsilon'$ have crossed circles—let’s call them $\delta$ and $\varepsilon$. In case II, $\delta'$ has passed a circle (let’s call it $\delta$), and $\varepsilon'$ has passed a straight line (that is, $\alpha$, $\beta$ and $\gamma$ have a common tangent in this case, while $\alpha$, $\beta$ and $\gamma$ obviously lie on one side of it). In case III, $\delta'_1$ and $\delta'_2$ crossed circles (let's call them $\delta_1$ and $\delta_2$).

So, the circles touching $\alpha$, $\beta$, and $\gamma$ are either two or one. In the case of point I, $O$ lies outside $\delta$ and inside $\varepsilon$, that is, $\delta$ has external tangency with $\alpha$, $\beta$ and $\gamma$, and $\varepsilon$ has internal tangency. In case of point II, $O$ lies outside $\delta$ - again $\delta$ has external tangency with $\alpha$, $\beta$ and $\gamma$. In case III, the points lie both outside $\delta_1$ and outside $\delta_2$, so that they both touch $\alpha$, $\beta$ and $\gamma$ externally.

The theorem is proven.

Corollary 1. In the case of $I$ and $II$ the problem of three quadrangles we have a unique solution (center $D$ of the circle $\delta$), in the case of $III$ we have two solutions (centers $D_1$ and $D_2$ of the circle $\delta_1$ and $\delta_2$).

Corollary 2. In the case of $I$ the problem of three quadrangles we have a unique solution (center $E$ of the circle $\varepsilon$), in the case of $II$ and $III$ the solutions are German.

Sweeping. In §3 we argued (in accordance with the incorrect theory developed in §§1 and 2) that $n_1 = 1/d$ and $n_2 = -1/e$. This is true in case I. In this case $n_2 < 0$. In case II $n_2 = 0$ (this corresponds to the fact that the line - the common tangent of $\alpha$, $\beta$ and $\gamma$ - has zero curvature). In case III, $n_1 = 1/d_1$, and $n_2 = 1/d_2$, where $d_1$ and $d_2$ are the radii of circles $\delta_1$ and $\delta_2$; in this case $n_2 > 0$. We will verify the validity of the statements just made in § 6.

Given the triangle's sides $ABC$, we can calculate $n_{1,2}$ and determine which of the three cases occurs.

Sometimes you can do without such calculations - we will talk about this in § 7.

§ 6. Derivation of Soddy's formula

1. Let $U, V$ and $W$ be three arbitrary non-negative numbers whose sum is $π$. Then
$$\sin^2 U = \sin^2 V + \sin^2 W - 2 \sin V \sin W \cos U.$$
Proof. Let's construct a triangle with angles $U, V$ and $W$. Let the lengths of the opposite sides be $u, v$ and $w$. By the cosine theorem
$$u^2 = v^2 + w^2 - 2 vw \cos U.$$
According to the theorem of sines
$$u/\sin U = v/\sin V = w/\sin W.$$
From here the necessary formula is obtained for any non-zero angles. If at least one of the angles $U, V$ and $W$ is 0, the formula is checked directly.

⟦folio 19⟧

2. Let $A, B, C$ and $D$ be four arbitrary points of the plane. Then
$$\sin^2 \frac{\angle ADB}{2} + \sin^2 \frac{\angle ADC}{2} - \sin^2 \frac{\angle BDC}{2})^2 = 4\sin^2 \frac{\angle ADB}{2} \times \sin^2 \frac{\angle ADC}{2} \cos^2 \frac{\angle BDC}{2}.$$
Proof. There are (Fig. 8) four cases of relative position of the point $A, B, C$ and $D$. In each of them we will select $U, V$ and $W$ in accordance with the table below. In any case, $U \geq 0$, $V \geq 0$, $W \geq 0$ and $U + V + W = \pi$ so, according to point 1,
$(\sin^2 V + \sin^2 W - \sin^2 U)^2 = 4\sin^2 V \cdot \sin^2 W \cdot \cos^2 U$.
It remains to take advantage of the fact that in any case
$$\sin U = \sin \frac{\angle BDC}{2}, \\
\sin V = \sin \frac{\angle ADC}{2}, \\
\sin W = \sin \frac{\angle ADB}{2}, \\
\cos^2 U = \cos^2 \frac{\angle BDC}{2}.$$
3. Let one of the angles of the triangle be $\theta$, the opposite side $-u$, adjacent $-v$ and $w$, we get the meter of the triangle $-q$. Then
$$\cos^2 \frac{\theta}{2} = \frac{q(q - u)}{v \cdot w}, \quad \sin^2 \frac{\theta}{2} = \frac{(q - v)(q - w)}{v \cdot w}.$$
Proof. By the cosine theorem
$$u^2 = v^2 + w^2 - 2vw \cos \theta, \quad \cos \theta = (v^2 + w^2 - u^2)/2vw.$$
Means,
$$\cos^2 \frac{\theta}{2} = \frac{1 + \cos \theta}{2} = \frac{(v + w)^2 - u^2}{4v \cdot w} = \frac{(v + w + u)(v + w - u)}{4v \cdot w} = \frac{q(q - u)}{v \cdot w},$$

⟦folio 20⟧

$$\sin^2 \frac{\theta}{2} = \frac{1 - \cos \theta}{2} = \frac{u^2 - (v - w)^2}{4v \cdot w} = \frac{(u + v - w)(u + w - v)}{4v \cdot w} = \frac{(q - w)(q - v)}{v \cdot w}.$$

4. Let circles $\alpha, \beta, \gamma$ and $\delta$ with centers $A, B, C$ and $D$ and radii $a, b, c$ and $d$ touch each other externally in pairs. Then
$$\cos^2 \frac{\angle BDC}{2} = \frac{(b + d + c)d}{(b + d)(d + c)},$$
$$\sin^2 \frac{\angle BDC}{2} = \frac{bc}{(b + d)(d + c)},$$
$$\sin^2 \frac{\angle ADB}{2} = \frac{ab}{(a + d)(d + b)},$$
$$\sin^2 \frac{\angle ADC}{2} = \frac{ac}{(a + d)(d + c)}.$$

Proof. In $\triangle BDC$ we express the sides and half-perimeter through $b, d$ and $c$:
$$BC = b + c, \quad BD = b + d, \quad DC = d + c,$$
$$\frac{1}{2}(BC + BD + DC) = b + d + c$$

and use the formulas of point 3. We obtain the other two formulas similarly from $\triangle ADB$ and $\triangle ADC$.
4'. Let circles $\alpha, \beta, \gamma$ with centers $A, B, C$ and radii $a, b, c$ touch each other externally in pairs, and let all three touch each other from the inside with center $E$ and radius $e$. Then
$$\cos^2 \frac{\angle BEC}{2} = \frac{(b - e + c)(-e)}{(b - e)(-e + c)},$$
$$\sin^2 \frac{\angle BEC}{2} = \frac{bc}{(b - e)(-e + c)},$$
$$\sin^2 \frac{\angle AEB}{2} = \frac{ab}{(a - e)(-e + b)},$$
$$\sin^2 \frac{\angle AEC}{2} = \frac{ac}{(a - e)(-e + c)}.$$

The proof is the same as in point 4.
5. Under the conditions of point 4, we set $k = 1/a, l = 1/b, m = 1/c, n = 1/d$.

Then
$(-k + l + m + n)^2 = 4(lm + mn + nl).$

Proof. According to paragraphs 2 and 4
$$\left[ \frac{ab}{(a + d)(d + b)} + \frac{ac}{(a + d)(d + c)} \right]^2 = 4 \frac{ab}{(a + d)(d + b)} \times \frac{ac}{(a + d)(d + c)} \cdot \frac{(b + d + c)d}{(b + d)(d + c)}.$$

Multiplying both sides of the equality by $[(a + d)(b + d)(c + d)/abcd]^2$, we get
$$\left[ \frac{c + d}{cd} + \frac{b + d}{bd} - \frac{a + d}{ad} \right]^2 = 4 \frac{b + d + c}{bdc},$$

or finally
$(-k + l + m + n)^2 = 4(lm + mn + nl).$

Sweeping. The formulas of paragraph 4' are obtained from the formulas of paragraph 4 if we replace $d$ with $(-e)$. Therefore, the formula proved in paragraph 5 is also true under the conditions of paragraph 4' for $n = -1/e$.

6. The curvatures $k, l, m$ and $n$ of the circles $\alpha, \beta, \gamma$ and $\delta$ are pairwise tangent to each other externally, related by Soddy’s formula
$(k + l + m + n)^2 = 2(k^2 + l^2 + m^2 + n^2).$

The same formula is true if $n$ is the curvature of the circle $\varepsilon$ that $\alpha, \beta$ and $\gamma$ touch from the inside.

Proof. Let's transform the identity
$(k + l + m + n)^2 = (-k + l + m + n)^2 + 4k(l + m + n)$

taking into account point 5:
$(k + l + m + n)^2 = 4(kl + km + kn + lm + ln + mn).$

Taking advantage of the identity
$(k + l + m + n)^2 - (k^2 + l^2 + m^2 + n^2) = 2(kl + km + kn + lm + ln + mn),$

we get
$(k + l + m + n)^2 = 2[(k + l + m + n)^2 - (k^2 + l^2 + m^2 + n^2)].$

Bringing similar terms, we obtain Soddy's formula.

7. From the statement proven in paragraph 6 it immediately follows

⟦folio 21⟧

Corollary 1. Let us put (as in § 3)
$$n_{1,2} = k + l + m \pm 2\sqrt{kl + lm + mk}.$$
Then, in terms of § 5, if case I occurs, then $n_2 < 0$, and if case III occurs, then $n_2 > 0$.

Exercise 3. Prove that in case II $n_2 = 0$.

Combining Corollary 1 and the exercise, we get

Corollary 2. If $n_2 < 0$, then case I occurs, if $n_2 = 0$, then case II, if $n_2 > 0$, then case III.

§ 7. Another necessity

In June, problem M209 was published in the Problem Book «Kvant».

For any triangle ABC you can calculate the following sum:
$$S = \text{tg}^2 \frac{A}{2} + \text{tg}^2 \frac{B}{2} + \text{tg}^2 \frac{C}{2}.$$
Prove that:
a) $S < 2$ for all acute and right triangles;
b) $S > 2$ for obtuse triangles with an obtuse angle greater than 2 arc tan $^4/3$;
b) for any φ such that $\frac{\pi}{2} < \varphi < 2\arctg \frac{4}{3}$, among the obtuse triangles with an obtuse angle equal to $\varphi$, there are those such that $S > 2$ and those such that $S < 2$.

At first glance, problems M195 and M209 say completely different things. But it turns out—another surprise—there is a deep connection between them.

Using § 6 (points 3 and 4), it is easy to prove the following:

Statement 1. Let circles $\alpha, \beta, \gamma$ with centers A, B, C and radii a, b, c pairwise touch each other externally, and let $a + b + c = p$. Then
$$\text{tg}^2 \frac{A}{2} = \frac{bc}{ap}, \text{tg}^2 \frac{B}{2} = \frac{ac}{bp},$$
$$\text{tg}^2 \frac{C}{2} = \frac{ab}{cp}.$$

Thus, $(a + b + c)S = \frac{bc}{a} + \frac{ac}{b} + \frac{ab}{c}$. Dividing both sides of this equality by abc, we get
$$S \left( \frac{1}{ab} + \frac{1}{bc} + \frac{1}{ca} \right) = \frac{1}{a^2} + \frac{1}{b^2} + \frac{1}{c^2}$$
or $S(kl + lm + mk) = k^2 + l^2 + m^2$. Using the identity $k^2 + l^2 + m^2 = (k + l + m)^2 - 2(kl + lm + mk)$, we find: $(S + 2)(kl + lm + mk) = (k + l + m)^2$.

So, the following conditions are pairwise equivalent:
$$S < 2 \text{ и } (k + l + m)^2 < 4(kl + lm + mk),$$
$$S = 2 \text{ и } (k + l + m)^2 = 4(kl + lm + mk),$$
$$S > 2 \text{ и } (k + l + m)^2 > 4(kl + lm + mk).$$

Let's remember the formula
$$n_{1,2} = (k + l + m) \pm 2\sqrt{kl + lm + mk},$$
we get it from here.

Statement 2. The conditions S<2, S=2 and S>2 characterize (correspondence to) cases I ($n_2 < 0$), II ($n_2 = 0$) and III ($n_2 > 0$).

Therefore, the result of problem M209 allows a fairly part in the form of △ ABC to say which of cases I, II, III holds: if △ ABC is acute or rectangular, then case I (problem M195 has in this case exactly one solution D), if △ ABC is “very obtuse-angled” ($\varphi > 2\arctg^4/3$), then case III (problem M195 has two solutions D$_1$ and D$_2$). The “watershed” (case II) runs along “not too obtuse” triangles ($\pi/2 < \varphi < 2\arctg^4/3$). You will receive some additional information about this “watershed” by solving problem M209 or reading its solutions in “Problem Book «Kvant»”.
