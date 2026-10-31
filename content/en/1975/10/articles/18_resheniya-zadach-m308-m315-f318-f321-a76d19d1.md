---
id: 1975-10-resheniya-zadach-m308-m315-f318-f321-a76d19d1
issue: kvant_1975_10
year: 1975
number: "10"
title: Solutions to problems M308—M315; F318—F321
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 42
page_last: 49
page_labels: 40-47
tag: WJRI
lang: en
source: kvant_digital
extraction: vision
content_sha256: c6dbd887dda8da6e1a49de97fa0729f0a3fa5608cced4e120f6da1fe8ceac819
prompt_sha256: draft-1
translated_from: content/ru/1975/10/articles/18_resheniya-zadach-m308-m315-f318-f321-a76d19d1.md
source_content_sha256: 72ee6443ab6b5a868d4155536ae9456d29660f171a98b3dd82510c68c559d577
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 40⟧

Problem solutions
M308-M315; F318-F321

M308. If for any $x$ $a_1\cos x + a_2\cos 2x + \dots + a_n\cos nx \geq -1$, then for the numbers $a_1, a_2, \dots, a_n$ the inequality $a_1 + a_2 + \dots + a_n \leq n$ holds. The proof is this statement: a) for $n = 2$; b) for $n = 3$; c) for any natural $n$.

a) It is enough to put $x = \frac{2\pi}{3}$.

b) Put $x = \frac{\pi}{2}, x = \pi, x = \frac{3\pi}{2}$ in succession and add the resulting inequalities.
b) Let us first prove the following formula: if $\varphi = -\frac{2k\pi}{n+1}$, where $k$ and $n$ are integers, and $k$ is not divisible by $n+1$, then
$$\cos \varphi + \cos 2\varphi + \cos 3\varphi + \dots + \cos n\varphi = -1. \quad (*)$$
Let the given points be $O$ and $A_0$. Rotate point $A_0$ by angle $\varphi$ relative to point $O$, we obtain point $A_1$. From point $A_1$ with the same rotation we obtain point $A_2$, from point $A_2$ - point $A_3$ and so on. Since $(n+1)\varphi = 2k\pi$, the point $A_{n+1}$ coincides with the point $A_0$. The sum of the vectors $\overrightarrow{OA_0}, \overrightarrow{OA_1}, \overrightarrow{OA_2}, \dots, \overrightarrow{OA_n}$ is equal to the null vector. Indeed, when each of these vectors is rotated through an angle $\varphi$ relative to the point $O$, a vector equal to their sum must also rotate through the same angle. Since, on the other hand, a vector equal to the sum of vectors $\overrightarrow{OA_0}, \overrightarrow{OA_1}, \dots, \overrightarrow{OA_n}$ will not change during this rotation (for point $A_0$ will go to point $A_1$, point $A_1$ to point $A_2$, ..., point $A_n$ to point $A_0$), then it is equal to the null vector.
Let us now assume that the point $O$ is the origin and the vector $\overrightarrow{OA_0}$ has length 1 and is directed along the x-axis. Since the projection of the sum of vectors onto any axis is equal to the sum of their projections onto this axis, then the sum of the projections of the vectors $\overrightarrow{OA_1}, \overrightarrow{OA_2}, \dots, \overrightarrow{OA_n}$ onto the abscissa axis is equal to -1 (the projection of the vector $\overrightarrow{OA_0}$ onto the abscissa axis is equal to 1). But these projections are obviously equal to $\cos \varphi, \cos 2\varphi, \dots, \cos n\varphi$, the absence of which follows from formula (*).

Formula (*) can be proven in another way by multiplying both sides by $2\sin \frac{\varphi}{2}$ and using the formula
$$2\sin \frac{\varphi}{2}\cos k\varphi = -\sin \left(k - \frac{1}{2}\right)\varphi + \sin \left(k + \frac{1}{2}\right)\varphi,$$
- do it yourself.

Let's move on to solving problem c).
Taking an arbitrary number $x_1$, we put $x_2 = 2x_1, x_3 = 3x_1, \dots, x_n = nx_1$. For $x = x_1, x = x_2, x = x_3, \dots, x = x_n$ we obtain the following inequalities:
$$a_1\cos x_1 + a_2\cos 2x_1 + a_3\cos 3x_1 + \dots + a_n\cos nx_1 \geq -1,$$

⟦folio 41⟧

$$a_1 \cos x_2 + a_2 \cos 2x_2 + a_3 \cos 3x_2 + \dots + a_n \cos nx_2 \geq -1,$$
$$a_1 \cos x_3 + a_2 \cos 2x_3 + a_3 \cos 3x_3 + \dots + a_n \cos nx_3 \geq -1,$$
$$\dots$$
$$a_1 \cos x_n + a_2 \cos 2x_n + a_3 \cos 3x_n + \dots + a_n \cos nx_n \geq -1.$$

Given that $kx_l = klx_1 = lkx_1 = lx_k$, these inequalities can be rewritten as follows:

$$a_1 \cos x_1 + a_2 \cos x_2 + a_3 \cos x_3 + \dots + a_n \cos x_n \geq -1,$$
$$a_1 \cos 2x_1 + a_2 \cos 2x_2 + a_3 \cos 2x_3 + \dots + a_n \cos 2x_n \geq -1,$$
$$a_1 \cos 3x_1 + a_2 \cos 3x_2 + a_3 \cos 3x_3 + \dots + a_n \cos 3x_n \geq -1,$$
$$\dots$$
$$a_1 \cos nx_1 + a_2 \cos nx_2 + a_3 \cos nx_3 + \dots + a_n \cos nx_n \geq -1.$$

Adding these inequalities and putting $x_1 = \frac{2\pi}{n+1}$ (then $x_2 = \frac{4\pi}{n+1}$, $x_3 = \frac{6\pi}{n+1}$, $\dots$, $x_n = \frac{2n\pi}{n+1}$), we arrive at the inequality

$$-a_1 - a_2 - a_3 - \dots - a_n \geq -n,$$

where

$$a_1 + a_2 + a_3 + \dots + a_n \leq n^*).$$

Yu. I. Nokin

**M309. a) For what $n$ is the polynomial $x^{2n} + x^n + 1$ divisible by $x^2 + x + 1$?**

b) At what $n$ number

$$1 \underbrace{0 \dots 0}_{n} \underbrace{1 \dots 0}_{n}$$

divisible by 37?

a) Consider three cases corresponding to different remainders when $n$ is divided by 3.

1°. Let $n=3k$; Then

$$x^{6k} + x^{3k} + 1 = (x^{6k} - 1) + (x^{3k} - 1) + 3 =$$
$$= (x^3 - 1)(x^{6k} - 3 + x^{6k} - 6 + \dots + 1) +$$
$$+ (x^3 - 1)(x^{3k} - 3 + x^{3k} - 6 + \dots + 1) + 3 =$$
$$= (x^2 + x + 1) \cdot Q(x) + 3,$$

where $Q(x) = (x - 1)[(x^{6k} - 3 + x^{6k} - 6 + \dots + 1) + (x^{3k} - 3 + \dots + 1)]$.

Therefore, if $n=3k$, then the polynomial $x^{2n} + x^n + 1$ when divided by $x^2 + x + 1$ gives remainder 3.

2°. Let $n=3k + 1$. We have

$$x^{6k + 2} + x^{3k + 1} + 1 = (x^{6k + 2} - x^2) + (x^{3k + 1} - x) +$$
$$+ (x^2 + x + 1) = x^2(x^{6k} - 1) + x(x^{3k} - 1) + (x^2 + x + 1)$$

In 1° we showed that the polynomials $(x^{6k} - 1)$ and $(x^{3k} - 1)$ are divisible by $(x^3 - 1)$, hence also by $(x^2 + x + 1)$; therefore, at $n=3k + 1$ the polynomial $x^{2n} + x^n + 1$ is divisible by $x^2 + x + 1$.

3°. Let $n=3k + 2$. Then

$$x^{6k + 4} + x^{3k + 2} + 1 = x^1(x^{6k} - 1) + x^2(x^{3k} - 1) + x^4 + x^2 +$$
$$+ 1 = x^4(x^{6k} - 1) + x^2(x^{3k} - 1) + x^3 - 1 + (x^2 + x + 1) = (x^2 + x + 1)[(x - 1)R(x) + 1],$$

where $R(x) = x^4(x^{6k} - 3 + \dots + 1) + x^2(x^{3k} - 3 + \dots + 1) + x$, and the polynomial $x^{2n} + x^n + 1$ is again divisible by $x^2 + x + 1$.

*) This problem is solved similarly in the book by Paulin and Sethe “Problems and Theorems from Analysis”.

⟦folio 42⟧

So the answer in problem a) is:
the polynomial $x^{2n} + x^n + 1$ is divisible by $x^2 + x + 1$ unless $n$ is a multiple of three.

6) When solving this problem, you can use the result of point a), since all polynomials obtained during division - partial and remainders - have integer coefficients. Indeed, for $x = 10$ we obtain the corresponding
$$x^2 + x + 1 = 111, x^{2(n+1)} + x^{(n+1)} + 1 = 1 \underbrace{0 \ldots 0}_{n} \underbrace{1 \ldots 0}_{n}.$$
On the other hand, $10^{2m} + 10^m + 1$ is divisible by 3 for all $m$, and asking whether $10^{2m} + 10^m + 1$ is divisible by 37 is equivalent to asking whether $10^{2m} + 10^m + 1$ is divisible by 37.3 = 111. The answer to this problem is: $\underbrace{10 \ldots 0}_{n} \underbrace{10 \ldots 0}_{n}$ is divisible by 37 if $n$ is a multiple of 3 or if $n$ leaves a remainder of 1 when divided by 3.
F. G. Shleifer

**M311.** *) From one bacterium 1000 were obtained in the following way: first the bacterium was divided into two, then one of the two resulting bacteria was divided into two, then one of the three resulting bacteria was divided into two, and so on. Let us prove that at some points there existed such a bacterium, the number of offspring of which in the environment of 1000 bacteria, resulting in the end, is between 334 and 667.

Fig. 1.

**M312.** In the parallelogram $P_1$ there is a parallelogram $P_2$, in which in turn there is a parallelogram $P_3$, and the sides $P_3$ are parallel to the sides $P_1$. Let us prove that at least one side of the parallelogram $P_3$ is no less than half the length of the side $P_1$ parallel to it.

Let a certain bacterium, which has $N$ streams of medium 1000 bacteria, split into two, which have $N'$ and $N''$ streams respectively. Then $N = N' + N''$, and therefore one of the numbers $N'$ and $N''$ is not less than $N/2$.

Consider the sequence of bacteria $A_1, A_2, A_3, \ldots, A_m$, where $A_1$ is the very first bacterium, $A_{k+1}$ (for $k = 1, 2, \ldots, m-1$) is the one of the two bacteria resulting from the division $A_k$ that has at least as many fluxes as its sister, and $A_m$ is one of the 1000 bacteria that resulted at the end. Let $A_k$ have $N_k$ streams. Then the sequence
$$N_1 = 1000, N_2, N_3, \ldots, N_{m-1}, N_m = 1$$
decrease, but each term in it is no less than half of the previous one: $N_k > N_{k+1} \geq N_k/2$. (At figure 1, which depicts the process of dividing a bacterium in the form of a “family tree,” the chain of bacteria $A_1, A_2, \ldots, A_m$ is shown; here $N_1 = 16, N_2 = 9, N_3 = 5, N_4 = 3, N_5 = 2, N_6 = 1$.) If we choose $j$ so that $N_{j-1} \geq 668$ and $N_j < 668$, then we get $334 \leq N_j \leq 667$, that is, bacterium $A_j$ will satisfy given condition.

In the same way, one can prove that if in the end the result is $M$ bacteria, then for any natural $c$ there is a bacterium whose number of offspring $N$ satisfies the condition $c \leq N < 2c$.

N. B. Vasiliev

Let us note first of all that if the parallelogram $ABCD$ hangs into the parallelogram $KLMN$ (see Fig. 2), then they have a common center of symmetry $O$. This follows from the fact that when symmetry is relative to $O$, the parallelogram $KLMN$ goes into itself, and the side $AB$ of the parallelogram $ABCD$ goes over

*) The solution to problem M310 is contained in the article by G. A. Gurevich and “Repetitionless sequences («Kvant», 1975, No. 9).

⟦folio 43⟧

into a parallel segment of equal length with ends on the corresponding sides of the parallelogram KLMN, that is, into a segment CD.

Therefore, the parallelographs $P_1, P_2$ and $P_3$ have a common center of symmetry. From this we obtain that the four shaded parallelographs located at angles $K, L, M$ and $N$ are congruent; Let us denote the lengths of their sides by $x$ and $y$, respectively.

Let $a$ and $b$ be the side lengths of the parallelograph $P_3$. Then the lengths of the side of the parallelograph $P_1$ are equal to $(a + 2x)$ and $(b + 2y)$. We need to prove that either $a \geq \frac{a + 2x}{2}$ or $b \geq \frac{b + 2y}{2}$, that is, that either $a \geq 2x$ or $b \geq 2y$. This will be true if we prove the following inequality: $ab \geq 4xy$.

Consider a parallelograph whose three vertices are the points $A, L$ and $B$. Since the diagonal $AB$ divides it and the angular parallelographs - lower left and upper right - into congruent triangles, then the areas of the parallelographs shaded on figure 2 cm are equal. In the same way, the areas of parallelograms shaded in yellow, red and green are equal: all shaded parallelographs are equal in size. It is obvious (see Fig.ok) that the total area of ​​the shaded parallelographs does not exceed the area of ​​the parallelograph $P_3$. But the area of ​​one shaded parallelograph is $xy \cdot \sin \alpha$, and the area of ​​the parallelograph $P_3$ is $ab \cdot \sin \alpha$; Means,

$$ab \geq 4xy,$$

which is what was required.

I. N. Klumova

**M313. Given an angle with vertex O. Consider a set of four vertices M of ONML parallelograms, vertices N and L of which lie on the sides of a given angle, and the area is equal to a constant value. (This set is called a synerbola.) Prove that on the bisserps this is an angle and on its extension there are also points $F_1$ and $F_2$ ($2de |F_1O| = |F_2O|$), for which the difference in distance

$$||F_1M| - |F_2M||$$

does not depend on the point $M$.**

Let $2\alpha$ be a given angle, $A$ be the vertex of the hyperbola (the point of its intersection with the bisserpse), $A'$ be a symmetric point with respect to $O$, $KMQ$ be the perpendicular to this bisserpse passing through $M$ (K lies on the bisserpse, $Q$ - on the side of the corner, see Fig. 3).

Let us introduce the following notations: $r_1 = |F_1M|$, $r_2 = |F_2M|$, $a = |OA| = |OA'|$, $x = |ON|$, $y = |OL|$, $r = |OM|$, $\varphi = \widehat{AOM}$, finally, $c$ is the required distance of the points $F_1$ and $F_2$ from the vertex $O$ of the corner (center hyperboles). (For those who mean analytical geometry: $x$ and $y$ are the oblique coordinates of the point; $M$, $a$ and $\varphi$ are its polar coordinates.)

⟦folio 44⟧

According to the conditions of the problem, the blue and yellow parallelograms must have the same area:

$$k = xy \sin 2\alpha = \left( \frac{a}{2 \cos \alpha} \right)^2 \sin 2\alpha,$$

where

$$xy = \frac{a^2}{4 \cos^2 \alpha}. \tag{1}$$

We need to find such a position of $F_1$ and $F_2$ (that is, such a value of $c$) that the difference $r_2 - r_1$ is the same for all points $M$ of the hyperbola. In particular, for its vertex $A$ this difference $|F_1A| - |F_2A|$, due to the symmetry of $(|F_2A| = |F_1A'|)$, is equal to $|A'A| = 2a$ (the axis of the hyperbola). This means that this difference must be equal to

$$r_2 - r_1 = 2a. \tag{2}$$

Let's find the expressions $r_1$ and $r_2$ through the constants $a, c$ and $\alpha$ (these expressions will, of course, also include some variable quantities). Applying the cosine theorem for triangles $F_1MO, F_2MO$ and $OMN$, we have:

$$r_{1,2}^2 = c^2 + r^2 \pm 2cr \cos \varphi \tag{3}$$

(upper sign for $r_1$, lower sign for $r_2$) and

$$r^2 = x^2 + y^2 + 2xy \cos 2\alpha. \tag{4}$$

Angle $\varphi$ can be immediately used from formula (3): from the drawing it is clear that

$$r \cos \varphi = |OK| = |OQ| \cos \alpha = (|OL| + |LQ|) \cos \alpha =$$

$$= (|OL| + |LM|) \cos \alpha = (x + y) \cos \alpha;$$

follow,

$$r_{1,2}^2 = c^2 + r^2 \pm 2c(x + y) \cos \alpha. \tag{3'}$$

Substituting (4) into (3') and using conditions (1) and the identities $\cos 2\alpha = 2 \cos^2 \alpha - 1$ and $x^2 + y^2 = (x + y)^2 - 2xy$, we obtain:

$$r_{1,2}^2 = c^2 + (x + y)^2 - 2xy + 2xy \cos 2\alpha \pm 2c(x + y) \cos \alpha =$$

$$= c^2 + (x + y)^2 - \frac{a^2}{2 \cos^2 \alpha} +$$

$$+ \frac{a^2}{2 \cos^2 \alpha} (2 \cos^2 \alpha - 1) \pm 2c(x + y) \cos \alpha =$$

$$= \left[ c^2 - \frac{a^2}{2 \cos^2 \alpha} \right] + \left[ (x + y)^2 + a^2 \pm 2c(x + y) \cos \alpha \right]. \tag{5}$$

Do схх since $c$ was arbitrary. Let us now select it so that formula (5) takes on a simpler form. Let's put $c = \frac{a}{\cos \alpha}$ (then $|OF_2| = |OB|$, see figure). Then formula (5) takes the following form:

$$r_{1,2}^2 = (x + y)^2 + a^2 \pm 2(x + y) a = [(x + y) \pm a]^2.$$

From figure it is clear that $x + y > a$ ($|OQ| > |OA|$); hence,

$$r_1 = (x + y) + a, \quad r_2 = (x + y) - a.$$

This gives us $r_1 - r_2 = 2a$. It is interesting to note that $r_1 + r_2 = 2(x + y)$, i.e., from any power of a hyperbola is considered until its foci are different variable parallelogram lying in a certain hyperbola.

⟦folio 45⟧

M315. *) On each edge of a convex polyorganic an arrow is placed so that at least one arrow enters and leaves each vertex of the polyorganic. Let us prove that there are at least two faces of a polyorganic, each of which can be walked around the perimeter, moving in accordance with the direction of the arrows on its sides.

Fig. 4.

Fig. 5.

F318. At what $C_1$ the capacitance of the capacitor system shown in figure 6 is: a) $C$; b) $kC$ ($k \neq 1$); c) $C_1$?

Let's call the sequence
$$A_1A_2, A_2A_3, \dots, A_{t-1}A_t$$
polyorganic ribs by
$$P = A_1A_2 \dots A_t$$
if on all these edges the arrows are directed in the same direction: either from $A_1$ to $A_2$, from $A_2$ to $A_3$, ..., from $A_{t-1}$ to $A_t$, or from $A_t$ to $A_{t-1}$, from $A_{t-1}$ to $A_{t-2}$, ..., from $A_2$ to $A_1$.

Since, by condition, at least one arrow enters and leaves each vertex of the polyorganic, any path can be removed in both directions by attaching new edges to its ends.

Starting with an arbitrary edge $A_1A_2$ of the polyorganic (it is, very/no, a path), we will sequentially build paths $A_1A_2A_3, A_1A_2A_3A_4$ and so on, until we get a path in which one of the vertices meets twice: $A_s = A_t$, $1 \leq s < t$. Thus, we obtain a closed path $P_0 = A_sA_{s+1} \dots A_t$ (all of its vertices, except the extreme ones, $A_s = A_t$, are different, Fig. 4).

Since the polyorganic is convex, the path $P_0$ divides its surface into two regions $D$ and $D'$. Let us show that in each region there is at least one face that can be walked around the perimeter, moving in accordance with the direction of the arrows on its sides.

Let's take the area $D$; path it consists of $k_0 \geq 1$ faces of the polyorganic. If $k_0 = 1$, then this region (bounded by path $P_0$) is the desired face. If $k_0 > 1$, then in the region $D$ there is an edge $A_iB$ that is not included in the path $P_0$ (and $A_i$ is included in $P_0$). Starting from this edge, we will build a path through the vertex $B$ inside the region $D$ until we get a path in which one of the vertices meets twice (if we go to the boundary of the region $D$, then further along the path $P_0$ will return to $A_i$). This way we get a new closed path $P_1$ (Fig. 5). Path $P_1$ lies inside region $D$ and does not coincide with $P_0$; This means that the region bounded by path $P_1$ consists of $k_1 < k_0$ faces of the polyorganic. If $k_1 = 1$, then $P_1$ limits the required edge; if $k_1 > 1$, then in the same way we will construct a closed path $P_2$, limiting the area that consists of $k_2 < k_1$ faces, and so on. Since all the numbers $k_i$ are natural numbers and $k_{i+1} < k_i$, then in a finite number of steps we obtain a closed path $P_0$, limiting exactly one desired face.

The second required edge can be found in the same way by looking at $D'$ - the second required one from the region on which the path $P_0$ divided our polyorganic.

A. M. Zubkov

◆ Let the system of capacitors under consideration be connected to a source with voltage $U$. From the messages of symmetry it follows that the charges of the capacitors em bones $kC$ will be the same. Let's denote them by $Q$. Similarly, the charges $q$ of the embone capacitors $C$ are equal. The charge of the capacitor $C_1$ is denoted by $q_1$. Consider the charges of individual capacitors (see Fig. 6).

The charge $Q_x = Q + q$ of a system of capacitors is related to the voltage $U = U_2 + U_3 = \frac{q}{C} + \frac{Q}{kC}$ applied to the system, corresponding to $Q_x = C_xU$, where $C_x$ is the capacitance of the system, that is
$$Q + q = C_x \left( \frac{q}{C} + \frac{Q}{kC} \right).$$

*) The solution to problem M314 will be published in the next issue of the journal.

⟦folio 46⟧

The work done by the power field forces to cross any, and therefore single, charge along a closed trajectory is always zero. Bypassing, for example, the upper contour (see Fig. 6) counterclockwise, we get

$$U_1 - U_2 + U_3 = \frac{q_1}{C_1} - \frac{q}{C} + \frac{Q}{kC} = 0.$$

Let us also use the law of conservation of charge. The part of the system shown in figure 6 in red (you can also see the area shown in this color) was neutral before the system was connected to the source. Since this part is isolated, its total charge will remain zero:

$$q + q_1 - Q = 0.$$

From equation (1)—(3) it follows that

$$C_x = \frac{2kC + (1+k)C_1}{2C_1 + (1+k)C} C.$$

From here it is easy to obtain that

a) $C_x = C$ with $C_1 = -C$, which is impossible;
b) $C_x = kC$ ($k \neq 1$) for $C_1 = -kC$, which is also impossible;
b) $C_x = C_1$ at $C_1 = \sqrt{k} C.$

F319. Looking at 2F from the collecting line L1 with focal consideration F we find a luminous object. The illumination of the image of the object on the screen is equal to $E_0$. Between the screen and line L1, a scattering line L2 was placed with a focal length of 2F. To obtain an image of an object, the screen had to be switched to a consideration equal to F. Determine the illuminance of the image of the object in the second case.

From the conditions of the problem it follows that the image of the object created by lens L1 is located at a distance of 2F from it (this is easy to check using the lens formula). Let the diffuse lens L2 be placed at a distance x from the line L1 (Fig. 7). Obviously, to get a clear image, the screen had to move the data away from the line. The previous image created by lens L1 can be considered as a minimum object for line L2. Then the distance from the “object” to line L2 will be 2F - x, and the distance from the image to this line will be 3F - x. From the lens formula

$$-\frac{1}{2F-x} + \frac{1}{3F-x} = -\frac{1}{2F}$$

x can be found. Calculations give x = F.

Now let’s find the linear magnification of lens L2:

$$\Gamma = \frac{H}{h} = \frac{3F-x}{2F-x} = 2.$$

**F320.** *In an evacuated vessel with a capacity of $V = 1$ l there is 1 g of uranium hydride $\mathrm{UH_3}$. When heated to a temperature of $t_1 = 400^\circ\mathrm{C}$, the hydride completely decomposes into uranium (atomic weight $A = 238$) and hydrogen. Find the pressure of hydrogen in the vessel at this temperature.*

**F321.** *Fine sand is poured onto the horizontal membrane. The membrane oscillates with a frequency of $\nu = 500$ Hz in the vertical plane. What is the amplitude of the membrane vibration if the sand grains jump to a height of $h = 3$ mm relative to the equilibrium position of the membrane?*

⟦figure⟧
Fig. 8.

⟦column⟧

Consequently, if the entire light flux that fell on the lens $\mathrm{Л_1}$ passes through the lens $\mathrm{Л_2}$, then in the second case this flux is distributed over an area $\Gamma^2 = 4$ times larger. Therefore, the illumination of the image will be four times less, that is, $E = E_0/4$.

◆

The decomposition reaction of uranium hydride follows the equation
$$2\mathrm{UH_3} = 2\mathrm{U} + 3\mathrm{H_2},$$
that is, from 482 *g* (two moles) of uranium hydride, 476 *g* (two moles) of uranium and 6 *g* (three moles) of hydrogen are obtained. Accordingly, from 1 *g* uranium hydride you will get $m = 6/482$ *g* hydrogen. Considering hydrogen an ideal gas, we find its pressure under given conditions ($T = 673^\circ\mathrm{K}$, $V = 10^{-3}$ *m³*). From the equation of state of an ideal gas

$$p = \frac{m}{\mu}\frac{RT}{V} \approx 35\cdot 10^3 \ \ \textit{н/м}^2.$$

◆

Let the membrane oscillate according to the law
$$x = A \sin \omega t,$$
where $x$ is the displacement from the equilibrium position, $A$ is the amplitude, $\omega = 2\pi\nu$ is the cyclic frequency of oscillations. At the initial moment of time $t = 0$ the membrane and the grains of sand on it are in an equilibrium position. The membrane is then moved away from the equilibrium position, for example upward.

A grain of sand moving along with the membrane is acted upon by two forces: the force of gravity $mg$ and the force $\mathbf{N}$ of the membrane reaction (Fig. 8). Let us write down the equation of motion of a grain of sand:
$$N - mg = ma.$$
At the moment of separation of the grain of sand, the reaction force $N$ becomes zero, and, consequently, the acceleration of the grain of sand $a = -g$. Thus, a grain of sand breaks away from the membrane at that moment of time $t_0$ when its acceleration is equal to $-g$. Then the grain of sand continues to move to a height $h$ as a body thrown vertically upward at a height $h_0$, equal to the deviation of the membrane from the equilibrium position at the moment $t_0$, with an initial speed $v_0$, equal to the speed of the membrane at the same moment $t_0$ (see Fig. 8). According to the law of conservation of mechanical energy

$$mgh_0 + \frac{mv_0^2}{2} = mgh. \qquad (*)$$

Let us now consider the movement of the membrane in more detail and relate the quantities $h_0$ and $v_0$ with the amplitude of membrane oscillations.

The speed of the membrane at any moment of time is $v = \omega A \sin(\omega t + \pi/2) = \omega A \cos \omega t$, and the acceleration is $a = -\omega^2 x = -\omega^2 A \sin \omega t$. At the moment of separation $t_0$

$$v = v_0 = \omega A \cos \omega t_0,$$
$$a = -g = -\omega^2 A \sin \omega t_0,$$
$$x = h_0 = A \sin \omega t_0.$$

From the acceleration equation $\sin \omega t_0 = \dfrac{g}{\omega^2 A}$, therefore $h_0 = g/\omega^2$ and $v_0 = \omega A \cos \omega t_0 = \sqrt{\omega^2 A^2 - g^2/\omega^2}$

Substituting the values ​​$h_0$ and $v_0$ into equation $(*)$, we get

$$A = \frac{\sqrt{2gh\omega^2 - g^2}}{\omega^2} \approx 77{,}2\cdot 10^{-6} \ \textit{м} \approx 0{,}077 \ \textit{мм}.$$

*B. B. Bukhovtsev*

⟦folio 47⟧
