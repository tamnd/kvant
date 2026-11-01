---
id: 1984-7-dubrovskiy-moment-inertsii-v-geometrii-d3a603cd
issue: kvant_1984_7
year: 1984
number: "7"
title: Moment of inertia in geometry
authors:
  - Дубровский В. Н.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 35
page_last: 40
page_labels: 33, 34, 35, 36, 38
tag: 3WEY
lang: en
source: kvant_digital
extraction: vision
content_sha256: 67fef0f1729f2226f8503345f35a7006fe91ec2d794d549fe8b4bd5b0529fa2f
prompt_sha256: draft-1
translated_from: content/ru/1984/07/articles/12_dubrovskiy-moment-inertsii-v-geometrii-d3a603cd.md
source_content_sha256: f5f562d2b56ce3264d40db84c03fd6fee3317ea08d6f22603cfbbf607ba5e857
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 33⟧

Moment of inertia in geometry

Candidate of Physical and Mathematical Sciences
V. N. DUBROVSKY

Everyone knows well that mathematics is constantly used in physics. Rezhka encounters and therefore is less known about the opposite - the use of physical concepts in mathematics. One striking example of this kind - the center of mass in geometry - was discussed in a recent article by M. B. Balk and V. G. Boltyansky («Kvant» No. 4, p. 18). In our article, the main role is also played by a concept taken from mechanics - the moment of inertia.

But when a mathematician begins to work with a concept taken from physics, he quickly forgets its physical meaning and sees in it only a useful mathematical formula. Thus, the concept of a material POINT A of mass m, which a physicist perceives as “a body of mass m of negligibly small dimensions for a given problem,” is defined formally by a mathematician as “a pair (A, m)” consisting of a point A (geometric) and a real number m∈R.” A physicist will think twice before using “negative mass”, and a mathematician will consider as if nothing had happened the “material point”/(A, m), for which m<0! And, moreover, with a user for business (see the statue cited above, for example task 5 on p. 19). In a similar way, we here define the moment of inertia in purely mathematical terms. And the withdrawn one

⟦folio 34⟧

then Lagrange's formula for calculating the moment of inertia will become the key to a kind of cabinet of curiosities of geometry, with many outlandish theorems and formulas. This is our story.

Anticipating a possible question from an inquisitive reader, let us still understand the physical meaning of the moment of inertia. This is easy to do, starting from Newton's second law. By rotating motion, Newton’s second law is written in the form $M=I\alpha$, where $M$ is the moment of the applied force, $\alpha$ is the angular acceleration, and $I$ is precisely the moment of inertia (see «Kvant», 1971, No. 1, p. 6). Comparing this formula with $F=ma$, we see that the moment of inertia is a measure of the inertia of a rotating body, just as mass is a measure of inertia in translational motion.

What you need to know about the center of mass

Let us briefly recall all the information we need about the center of mass (details can be found in the mentioned article by M. B. Balk and V. G. Boltyansky).

Consider a system of $n$ material points (or exact masses), that is, $n$ pairs $(A_1, m_1), ..., (A_n, m_n)$, where $A_i$ are arbitrary points in space, $m_i$ are real numbers (“masses” concentrated at these points); a shorter and more convenient notation for this system is $m_1A_1, ..., m_nA_n$. If the total mass is $m=m_1+...+m_n\neq 0$, then

1) there is also a unique point $Z$ such that

$$m_1\overrightarrow{ZA}_1+...+m_n\overrightarrow{ZA}_n=\overrightarrow{0};$$

this point is called the center of mass of the system $m_1A_1, ..., m_nA_n$;

2) for any point $P$ the equality holds

$$\overrightarrow{PZ}=\frac{1}{m}(m_1\overrightarrow{PA}_1+...+m_n\overrightarrow{PA}_n);$$

(1)

Fig. 1.

3) (grouping theorem) when replacing part of the materials of points of the system $m_1A_1, ..., m_nA_n$, for example points $m_1A_1, ..., m_kA_k$, with their center of mass $C$, in which their total mass $m'=m_1+...+m_k$ is placed, the position of the center of mass of the entire system does not change, that is, the centers of mass of the system $m'C, m_{k+1}A_{k+1}, ..., m_nA_n$ and $m_1A_1, ..., m_nA_n$ coincide.

It follows vaguely from the definition that the center $Z$ of two exact masses $m_1A_1$ and $m_2A_2$ is located according to the well-known lever rule: the point $Z$ lies on the spicy part - the proportionality coefficient of two collinear vectors).

Tasks

1. Let $a, b, c$ be the lengths of sides $BC, CA, AB$ of triangle $ABC$. Prove that the center of its incircle is the center of mass of the system $aA, bB, cC$. (Hint: user that the bissertis of a triangle divides its side into segments proportional to the adjacent sides $^*$), prove that, for example, the barycenter of the materials of the points at $bB$ and $cC$ is the base of the bissertis of the angle $A$; apply the grouping theorem.)

2. Consider three outer circles of the triangle $ABC$—circles touching (from the outside) one of the sides of the triangle and the extension of the other two sides (Fig. 1). Let $A_1, B_1, C_1$ be the points of their tangency on the side $BC, CA, AB$. Prove that a) the segments $AA_1, BB_1$ and $CC_1$ intersect at one point $N$ (Nadel point), b) the point of intersection of the medians $M$ of the triangle lies on the segment $ZN$, where $Z$ is the center of the inscribed circle, and $|ZM|:|MN|=1:2$.

Moment of inertia and Lagrange formula

Moment of inertia of the point material system

$$m_1A_1, m_2A_2, ..., m_nA_n$$

relative to a fixed point $P$ is the number

$$I_P=m_1|PA_1|^2+m_2|PA_2|^2+...+m_n|PA_n|^2.$$

This concept was first introduced by L. Euler (1707-1783).

For physics lovers, we note that in mechanics, strictly speaking, the moment of inertia of a system of points relative to

*) See, for example, the article by S. R. Sefibekov “Four proofs of the bissertis theorem” (Kvant, 1983, No. 8, p. 37).

**) See also the book by N. N. Vorobyov “Fibonacci Numbers” (M.: Nauka, 1978, p. 15).

⟦folio 35⟧

The main ones from the point $A_i$ to this axis (its product by the angular velocity of rotation of the system around the axis is equal to the moment of impulse of the system).

It coincides with $I_P$, when the point $P$ and all points $A_i$ lie in the same plane, and its redistribution axis passes through $P$.

Formula (2) can be written more briefly by denoting the distance from $A_i$ to $P$ by $r_i$ and using the sum sign $\Sigma^*$):

$$I_P = \sum_i m_i r_i^2.$$

(3)

Formula (3) and (2) can be given another form. Let $P$ and $Q$ be two arbitrary points, then

$$I_P = \sum_i m_i |PA_i|^2 = \sum_i m_i (\overrightarrow{PQ} + \overrightarrow{QA_i})^2$$

$$= \sum_i m_i |PQ|^2 + 2\sum_i m_i \cdot \overrightarrow{PQ} \cdot \overrightarrow{QA_i} + \sum_i m_i |QA_i|^2,$$

that is

$$I_P = I_Q + m |PQ|^2 + 2\overrightarrow{PQ} \cdot (\sum_i m_i \overrightarrow{QA_i}).$$

(4)

If we now take the center of mass $Z$ of our system as $Q$, then since $\sum_i m_i \overrightarrow{ZA_i} = \overrightarrow{0}$ (by definition of the center of mass), we get

$$I_P = I_Z + m |PZ|^2.$$

(5)

At the end of the article we will show that the moment of inertia about the center of mass is expressed, if $m \neq 0$, by the following beautiful formula:

$$I_Z = \frac{1}{m} \sum_i m_i m_j |A_i A_j|^2$$

(6)

and therefore for any point $P$

$$I_P = \left( \frac{1}{m} \sum_i m_i m_j |A_i A_j|^2 \right) + m |PZ|^2.$$

(7)

Formulas (5)–(7) are called Laerange’s formulas; everything further is based on them.

*) This sign allows us to briefly write sums from many terms: together with $A_1 + A_2 + A_3 + \dots + A_n$ we write $\sum_i A_i$ or simply $\sum_i A_i$ (when the number of terms $n$ is clear from the context). Likewise, $\sum_i m_i r_i^2$ is short for $m_1 r_1^2 + m_2 r_2^2 + \dots + m_n r_n^2$, etc.

Fig. 2.

Mathematics - this is a calculus called things the same, and the same - differently

The humorous aphorism in the title has a deep meaning. Mathematical theorems reflect the most general laws, so the same theorem in different areas can occur to us in situations that at first glance have nothing in common. A good, albeit very elementary, example is formula (5).

Let us rewrite it in “neutral” notation, abstracting from the meaning of the quantities included in it. Let $x_1, \dots, x_n$ be some set of vectors, $c_1, \dots, c_n$ be a set of numbers, $c = c_1 + \dots + c_n \neq 0$, $x_0 = (c_1 x_1 + \dots + c_n x_n) / c$, $y_i = x_i - x_0$ for $i = 1, \dots, n$. Then

$$c_1 x_1^2 + \dots + c_n x_n^2 = (c_1 y_1^2 + \dots + c_n y_n^2) + cx_0^2$$

(8)

($x_i^2, y_i^2$ should be understood as the folded squares of the vectors $x_i, y_i$). We no longer need to prove this formula, because we can always assume that $x_i = \overrightarrow{PA_i}$, then $x_0 = \overrightarrow{PZ}$, where $Z$ is the magnetic system of materials of points $c_1 A_1, \dots, c_n A_n$, $y_i = \overrightarrow{ZA_i}$ and formula (8) turns into Laerange’s formula (5).

Now we give three more interpretations of this formula.

1) Let $x_1, \dots, x_n$ be the vectors of redistributors dropped from points $A_1, \dots, A_n$ onto the axis $l$ (Fig. 2), $c_1, \dots, c_n$ be the masses placed at these points. Then $x_0$ is the vector of redistribution from their barycenter $Z$ to the axis $l$ (why?), and $y_i$ are the vectors of redistribution from points $A_i$ to the axis $l_0$, drawn through

⟦folio 36⟧

point $Z$ parallel to $l$. In this case, (8) takes the form of Steiner’s theorem:

$$I_l = I_{l_0} + md^2$$

(here $I_l$ and $I_{l_0}$ are the moments of inertia of the system $c_1A_1$, ..., $c_nA_n$ relative to the axes $l$ and $l_0$, $m=c$ is the total mass, $d$ is the distance between the axes).

2) Let $n$ particles $A_1$, ..., $A_n$ with masses $m_1$, ..., $m_n$ move uniformly and rectilinearly with speed $\vec{v}_1$, ..., $\vec{v}_n$ relative to some reporting system $S$. Then their center of mass moves in the $S$ system with a speed $\vec{v}_0 = (m_1\vec{v}_1 + \dots + m_n\vec{v}_n) / m$ ($m = m_1 + \dots + m_n$). The speed of the particle $A_i$ in the rest frame of the center of mass, according to the rule of addition of velocities, is equal to $\vec{u}_i = \vec{v}_i - \vec{v}_0$. Let $E$ and $E_0$ be the total kinetic energies of all parts in the $S$ system and in the center of mass system, that is, $E = \frac{m_1v_1^2}{2} + \dots + \frac{m_nv_n^2}{2}$, $E_0 = \frac{m_1u_1^2}{2} + \dots + \frac{m_nu_n^2}{2}$. Using $x_i = \vec{v}_i$, $c_i = m_i/2$ in (8), we obtain Könz’s theorem on kinetic energy:

$$E = E_0 + \frac{mv_0^2}{2}$$

(the total kinetic energy of the system of parts is equal to the energy of their motion relative to the center of mass of the plane; the energy of motion of the center of mass).

The last example is from a completely different field - probability theory.

3) Suppose that in some experiment with a random outcome, a certain value $X$ is measured, for example, they throw a needle dice and determine the number of points that fall out. Let us assume that, depending on the result of the experiment, the value $X$ can take $n$ values $x_1$, ..., $x_n$ (in the example with the dice - 6 values 1, 2, ..., 6), and the value $x_i$ is accepted with a probability $p_i$ (the numbers $p_i$ are non-negative and add up 1; in our example, very indo, all values are equally likely, that is, $p_1 = p_2 = \dots = p_6 = 1/6$). The number $p_1x_1 + \dots + p_nx_n$ is called the mean (or mathematical expectation) of the random $X$ and is denoted $MX$ (in our example $MX = (1 + \dots + 6)/6 = 3,5$). Thus, from the point of view of probability theory, the expressions included in (8) (at $c_i = p_i$, $c = \Sigma p_i = 1$) can be interpreted as follows*):

$$p_1x_1^2 + \dots + p_nx_n^2 = MX^2$$

— the average value of the random variable $X^2$ or, as they say, the second moment (again “moment”!) of the random variable $X$; $y_i = x_i - x_0 = x_i - MX$ — deviations of random values ​​$X$ from the average value;

$$p_1y_1^2 + \dots + p_ny_n^2 = MX(X - MX)^2$$

— the average value of the squared deviation $X$ from $MX$; this is a very important characteristic of a random variable, showing the degree of its “scatter” around the average value, it is called dispersion and is denoted $DX$; $x_0^2 = (MX)^2$.

As a result, (8) turns into a formula for calculating the variance, which is available in all probability theory textbooks (though not bearing any sonorous names):

$$DX = MX^2 - (MX)^2$$

Is it easy to recognize Lagrange's formula here?

Problem 3. Find the variance of the number of windows when throwing a dice.

**Geometric consequences**

Stoyart's formula. Find the distance $d$ from the vertex $A$ of the triangle $ABC$ to the point $D$ on the side $BC$, knowledge of the lengths $a$, $b$, $c$ of the sides of the triangle and the lengths of the segments $BD$ and $DC$ (Fig. 3). Let $p = |BD| : |BC|$, $q = |DC| : |BC|$, then $D$ is the center of mass of the system of materials of points $qB$, $pC$. Calculating the moment of inertia of this system relative to point $A$, we obtain (see (7))

* Formula (8) is also true in the case when $x_i$ are numbers: we can simply consider them vectors with coordinates $(x_i; 0; 0)$. On the other hand, it can be applied to random variables that take on value vectors.

⟦folio 38⟧

For proof, note that $Z$ is the center of mass of the system of material points $aA, bB, cC$ (see Problem 1). Let us find the moments of inertia of this system relative to $Z$ (see (6)):

$$I_Z = \frac{abc^2 + bca^2 + cab^2}{a+b+c} = abc = 2R \sin \hat{A} \cdot bc = 4RS = 4Rrp,$$

and relative to 0:

$$\Pi \text{ формуле (5)} |OZ|^2 = (I_O - I_Z)/2p = R^2 - 2Rr.$$

One of the most beautiful theorems of triangle geometry states that the midpoints of the triangle, the bases of its altitudes and the midpoints of the segments connecting the point of intersection of the altitudes with the vertices lie on one circle - the so-called “circle of nine points” (see «Kvant» 1981, No. 8, p. 34). But it will make an even greater impression.

Feuerbach's theorem. The circle of nine points touches four “remarkable” circles - the inscribed one and the three outer ones.

We will prove this theorem only for the inscribed circle (the rest can be solved similarly - see Problem 8), and it will be enough for us to know that the circle of nine points passes through the midpoints $A_1, B_1$ and $C_1$ side of the triangle $ABC$.

Triangle $A_1B_1C_1$ is similar to triangle $ABC$ by a factor of 1/2, so its circumradius is $R/2$; Let's denote its center by $F$. It is convenient to write and prove the condition for this circle to touch the inscribed one in the form:

$$|FZ|^2 = \left(\frac{R}{2} - r\right)^2.$$

Let us place masses $a, b, c$ at the vertices $ABC$ of the triangle (their center of mass will be point $Z$), divide each mass into two parts: $a = (p-b) + (p-c), b = (p-c) + (p-a), c = (p-a) + (p-b)$ and group these parts in pairs, as shown in figure 6; the center of mass remains in place. The center of mass of system $(p-a)B, (p-a)C$ is at point $A_1$, system $(p-b)A, (p-b)C$ is at point $B_1$, and system $(p-c)A, (p-c)B$ is at point $C_1$, therefore, point $Z$ is the center of mass of system $(p-a)A, (p-b)B_1, (p-c)C_1$ (we simultaneously halved the masses obtained after grouping). Let us find the moments of inertia of this system relative to points $F$ and $Z$:

$$I_F = ((p-a) + (p-b)) + (p-c)) \cdot \left(\frac{R}{2}\right)^2 = \frac{R^2}{a} \cdot p,$$

$$I_Z = \frac{1}{p} ((p-a)(p-b)\left(\frac{c}{2}\right)^2) + (p-b)(p-c)\left(\frac{a}{2}\right)^2) + (p-a)(p-b)\left(\frac{b}{2}\right)^2).$$

Problem 7. Prove that for any triangle the point $(p-a)(p-b)c^2 + (p-b)(p-c)a^2 + (p-c)(p-a)b^2 = abcp^2 - 4S^2$ is true.

Using the current action of this problem (its solution is given at the end of the journal), completing the proof is quite easy: using formula (5)

$$|FZ|^2 = \frac{I_F - I_Z}{P} = \frac{R^2}{4} - \frac{abc}{4p} + \frac{S^2}{p^2} = \frac{R^2}{4} - \frac{abc}{4Rp} R + \left(\frac{S}{p}\right)^2 = \frac{R^2}{4} - rR + r^2 = \left(\frac{R}{2} - r\right)^2,$$

which is what was required.

Problem 8. Prove the statement of Feuerbach's theorem for inscribed circles. (Hint: the center of the incircle touching (outside) side $a$ serves as the center of mass of the system $(-a)A, bB, cC$. Collect these masses at the middle side, use equalities $a = (p-b) + (p-c), b = p - (p-b), c = p - (p-c).$)

Distance to the center of mass and derivation of Lagrange's formula

To prove formulas (7) and (6), we will derive a formula expressing the distance from an arbitrary point $P$ to the center of mass $Z$ of the system of material points $m_1A_1, \dots, m_nA_n$ through the distances from this point to the points of the system: $r_i = |PA_i|$, and pairwise distances between

(For the end see page 48)
