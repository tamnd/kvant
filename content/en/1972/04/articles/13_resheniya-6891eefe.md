---
id: 1972-4-resheniya-6891eefe
issue: kvant_1972_4
year: 1972
number: "4"
title: Solutions to problems M96—M100; F108—F115
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 44
page_last: 54
page_labels: 42, 43, 44, 45, 48, 49, 51, 52
tag: U9OT
lang: en
source: kvant_digital
extraction: vision
content_sha256: 45f3820aa9d048769bc68b789dcd581452b28ca4810dedbf61506c6e5099f362
prompt_sha256: draft-1
translated_from: content/ru/1972/04/articles/13_resheniya-6891eefe.md
source_content_sha256: 578c4d5b93a0f2487395e9dfb036395cbc2881800982bdfff7d2f57a390ba796
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 42⟧

SOLUTIONS

In this issue we publish solutions to problems M96—M100

M96

It is known about five positive numbers that if the sum of any three of them is subtracted from the sum of the other two, the difference will be positive. Prove that the product of all ten such differences does not exceed the square of the product of the given five numbers.

Let $a_1, a_2, a_3, a_4, a_5$ be the given numbers Then $(a_1+a_2+a_3-a_4)(a_1+a_3+a_4-a_2-a_5)=a_1^2-(a_2+a_5-a_3-a_4)^2\leq a_1^2$.

Similarly, it is proved that $(a_2+a_3+a_1-a_4-a_5)\times(a_2+a_4+a_5-a_3-a_1)\leq a_2^3$,
$(a_3+a_4+a_2-a_5-a_1)\times(a_3+a_5+a_1-a_4-a_2)\leq a_3^2$,
$(a_4+a_5+a_3-a_1-a_2)\times(a_4+a_1+a_2-a_5-a_3)\leq a_4^2$,
$(a_5+a_1+a_4-a_2-a_3)\times(a_5+a_2+a_3-a_1-a_4)\leq a_5^2$.

It remains to multiply these inequalities, and the problem is solved.

Prove a more general statement: if given $2n+1$ positive numbers, the difference between the sum of any $n+1$ numbers and the sum of $n$ remaining positive numbers, then the product $B$ of all $C_{2n+1}^n$ such differences and the product $A$ of all $2n+1$ given numbers are related by the inequality

$$B^n\leq A^{C_{2n+1}^n}$$

M97

In the trapezoid $ABCD$ with bases $AB=a$ and $CD=b$ a segment $A_1B_1$ is drawn connecting the midpoints of the diagonals. In the resulting trapezoid $A_1B_1CD$, the segment $A_2B_2$ is again drawn, connecting the midpoints of the diagonals, and so on (Fig. 1). Is it possible for a number to appear twice in the sequence of segment lengths $AB, A_1B_1, A_2B_2, \dots$? Will this sequence be monotonic (increasing or decreasing?) Does it tend to some limit?

Let $A_1$ and $B_1$ be the midpoints of the diagonals $AC$ and $BD$ of the trapezoid, $E$ and $F$ the midpoints of the side-

⟦folio 43⟧

the outer sides AD and BC (Fig. 2). Since $A_1F$ is the midline of triangle ACB, and $B_1F$ is the midline of triangle DCB, then points $A_1$ and $B_1$ lie on the segment EF and

$$a_1 = A_1B_1 = |A_1F - B_1F| = \left| \frac{a-b}{2} \right|.$$

(This formula is true no matter which of the numbers $a$ and $b$ is greater.) In the same way it is proved that

$$a_{n+1} = \left| \frac{a_n - b}{2} \right|,$$

(1)

where $a_n = A_nB_n$ ($n=1, 2, 3, \dots$) is the sequence of interest to us. Thus, the problem is reduced to an algebraic problem about the sequence determined by the correspondence of (1) with the original term $a_0 = a > 0$.

If $a_n > b$, then $a_{n+1} = \frac{a_n - b}{2} < a_n - b$.

Therefore, if $a > b$, then each term of the sequence will be less than the previous one by at least $b$ until a term $a_m$ is encountered such that $a_m \leq b$ (if $a \leq b$, then we put $m=0$, $a_m = a_0 = a$; many readers have considered only this case; only it is considered in the book “Mathematical Problems” *).

So, we will now consider only $n \geq m$.

If $a_n \leq b$, then $a_{n+1} = \frac{b - a_n}{2} \leq \frac{b}{2} < b$.

Thus, all terms of the sequence following $a_m$ will be less than $b$ and therefore for all $n \geq m$

$$a_{n+1} = \frac{b - a_n}{2}.$$

(2)

Fig. 2.

*) E. B. Dynkin, S. A. Molchanov, A. L. Rosenthal, A. K. Tolygu, “Mathematical problems”, ed. 3rd, “Science”, 1971, problem 147.

Fig. 3. The terms of the sequence $a_n$, defined by the condition $a_0 = a$, $a_{n+1} = \left| \frac{a_n - b}{2} \right|$ are the abscissas of the vertices of the broken line surrounded in green. The links of this broken line are alternately parallel to the axes $Ox$, $Oy$, and its vertices lie alternately on the straight line with the equation $y = x$ and on the graph of the function $y = \left| \frac{x - b}{2} \right|$.

Fig. 4.

The equation $x = \frac{b - x}{2}$ has a unique solution $x = \frac{b}{3}$. Therefore, if there is a limit on the sequence $\{a_n\}$, then it is equal to $\frac{b}{3}$.

Let $a_m \neq \frac{b}{3}$. Let's put $a_n = \frac{b}{3} + \delta_n$. Then from (2) it follows that $\frac{b}{3} + \delta_{n+1} = \frac{b}{3} - \frac{\delta_n}{2}$, that is

$$\delta_{n+1} = -\frac{\delta_n}{2}$$

(3)

— when moving from $n$ to $n+1$, the difference $a_n - \frac{b}{3} = \delta_n$ changes sign and is halved in abscissa value. Now everything is clear: in the sequence $a_n$ no number can appear twice, the last term of each being $\frac{b}{3}$ than the previous one. This sequence is not monotonic, but tends to the limit $\frac{b}{3}$ (Fig. 3, 4).

⟦folio 44⟧

Fig. 5.

Unfortunately, some readers write: “Since the sequence is not monotane, it does not tend to the limit.”
This reasoning is, of course, incorrect. Let us prove, using the definition of a limit, that

$$\lim_{n \to \infty} a_n = \frac{b}{3}.$$

Let $\varepsilon > 0$ be given. Then if $n > N$, where $N = N_{(\varepsilon)}$ is the smallest integer for which $2^N \varepsilon > 2^m |\delta_m|$, then $\left| a_n - \frac{b}{3} \right| = |\delta_n| = \frac{|\delta_m|}{2^n - m} < \frac{|\delta_m|}{2^N - m} < \varepsilon$.

Thus (4) is proven.

Of course, the limit is equal to $\frac{b}{3}$ even in the case when $a_m = \frac{b}{3}$ - in this case, all subsequent terms are also equal to $\frac{b}{3}$. Let us find out at what values ​​of $a$ this case occurs. If $m = 0$, then $a = \frac{b}{3}$. If $m = 1$ and $a_1 = \frac{a - b}{2} = \frac{b}{3}$, then $a = \frac{5b}{3}$.

Fig. 6.

In general, if $a_m = \frac{b}{3}$, then $a = a_0$ is obtained from $a_m = \frac{b}{3}$ after applying the formula $a_{n-1} = 2a_n + b$ $m$ times. Thus, as is easy to check, the values ​​$a$ for which $a_m = \frac{b}{3}$ constitute the sequence $\frac{b}{3}, \frac{5b}{3}, \frac{13b}{3}, \ldots, \frac{(2^k - 3)b}{3}$,... For these (and only these) values ​​$a$ the sequence turns out to be monotonic (and from some point constant).

We have not seen separately the case when $a_m = b$ (at the same time $a_{m+1} = 0, a_{m+2} = \frac{b}{2}, \ldots$) - from an algebraic point of view, nothing applies, but the corresponding $n = m$ and $n = m+1$ trapezoids degenerate into a parallelogram and into a triangle (points $B_{m+1}$ and $C_{m+1}$ coincide, Fig. 5); starting with $n = m+2$, the trapezoidal pressure is obtained, and, as always, $a_n$ tends to the limit $\frac{b}{3}$.

M98

Prove that in the table

1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1

where each number is equal to the sum of the three above it, each line (starting from the third) has an even number. Does each line (except the first two) contain a number divisible by three?

Let us first examine the question of divisibility by two. In our table we will write 0 together, and instead of odd numbers - 1. Then the table of 0 and 1 will need to be compiled according to the same rule (each number is obtained as the sum of the three above it in the previous line), only addition must be performed “modulo two” - according to the rules $0+0=0, 0+1=1+0=1, 1+1=0$.

The first is based on such a combination: the last even numbers in each row depend only on what the last even numbers in the previous row are, and therefore it is not surprising that this quadruple is periodic repeating (with a period of 4, see Fig. 6) *).

*) A similar solution is given in the book by D. O. Shklyarsky, N. N. Chentsov and I. M. Yaglom “Selected problems and theorems of elementary mathematics,” ed. 4th, “Nuka”, 1965, problem 10.

⟦folio 45⟧

Another solution proposed by a number of readers is proof by contradiction. Let's assume that some string consists entirely of ones:

111 ... 111

Then the previous line, as is easy to see, can only be like this:

100100 ... 001001,

and the one going in front of her is just like this:

110000110000 ... 000011000011.

But this is impossible, since each row of our table has an odd number of numbers.

As for divisibility by 3, as you can easily see, already in the next, fourth row of the table (it is convenient to assign the number 0 to the top row of one unit)

1 4 10 16 19 16 10 4 1

Not a single number is divisible by 3 (and all leave a remainder of 1 when divided by three). Having understood the structure of our table “modulo 3” (on Fig. 7 the numbers that give remainder 0, 1 and 2 when divided by three are replaced by yellow, black and red circles, respectively), you can notice that the same property will have rows with numbers 1, 1+3=4, 1+3+3^2=13, 1+3+3^2+3^3=40, etc.

Readers report in their letters about other properties of the numbers in this table. Many different properties can be deduced; use the fact that the nth row of our table contains the coefficients of the polynomial

$$(1+x+x^2)^n = \sum_{k=0}^{2n} B_n^k x^k$$

(actions are approximately the same as in the article “Arithmetic of biomp coefficients”, “Quant” No. 6, 1970). For example, it is immediately clear that $\sum_{k=0}^{2n} B_n^k = 3^n$, $\sum_{k=0}^{2n} (-1)^k B_n^k = 1$, and it is not difficult to prove that $\sum_{k=0}^{n} (B_n^k) = B_{2n}^n$ (see problem 61 in the book by A. M. and I. M. Yaglomov “Non-elementary problems in elementary presentation”, Gostekhidat, 1954). Check that

**Fig. 7.**

Fig. 8.

if $p$ is prime, $s < p$ and $r < p$, then

$$B_{lp+s}^l B_{m+r}^m \equiv B_{l}^l B_{m}^s + B_{l-1}^l B_{m}^s + p$$ (mod $p$)

(if $k > 2n$, then $B_{n}^k$ is considered equal to 0).

Solutions to problems **M96 - M98** were sent by reader polynomials. At least two of these problems were solved by A. Grizoryan (Baku), S. Konyazin (Saratov), A. Merkuryev (Leningrad), M. Rozov (Minsk), M. Preezer (Tomsk), A. Slinkin (Moscow), A. Chernyak (Minsk), E. Turkevich (Chernivtsi), S. Komanov (Tsalka village of the Georgian SSR), G. Timofeev (Saratov), Yu. Kisin (Stranaia Russa), V. Nadezhko (Leningrad), A. Blyukhin (Kiselevsk, Kemerovo region), E. Gundur (Voroshilgovryad), A. Makarytsev (Lvov), I. Shparlinsky (Moscow).

**M99**

In triangle ABC, side AC is the longest. Prove that for any point M of the plane AM+CM is not less than BM. In what cases is equality possible?

Let us first prove this lemma.

Lemma. For any four points A, B, C, M on the plane

$$AC \cdot BM \leq AB \cdot CM + BC \cdot AM$$ (1)

Equality holds if and only if ABCM is a convex cyclic quadrilateral (or when one of the terms on the right-hand side is zero due to the fact that some two points coincide).

Proof of the lemma. Let us choose a point P such that $\Rightarrow BAP = \Rightarrow CAM$ and $\Rightarrow MAP = \Rightarrow CAB$, and PA = $\frac{AB \cdot AM}{AC}$ (Fig. 8). Then $\triangle BAP \sim \triangle CAM$ (the first one gets -

⟦folio 48⟧

which the straw will rotate will not coincide with its middle.

The frictional force of each piece of straw is proportional to the weight of these pieces

$$F_1 = m \frac{l - x}{l} gk, \quad F_2 = m \frac{x}{l} gk.$$

Now we can write the condition for the moments of forces to be equal to zero relative to point 0:

$$F(l - x) - F_1 \left( \frac{l - x}{2} \right) - F_2 \frac{x}{2} = 0.$$ (1)

Substituting the values ​​$F_1$, $F_2$ and $F \approx mgk$ (since by conditions $F$ is only slightly less than $mgk$), we find that

$$x = \frac{l}{\sqrt{2}}.$$

This distance is less than half the length of the straw. Thus, the straw does not rotate around the middle, but around a point close to one of the ends. Turn the straw to $180^\circ$, the ants will see it at some distance. Now the entire operation can be repeated, only with the straw at the other end. And so on.

Let us also examine formula (1). Substituting $F_1 = m \frac{l - x}{2} gk$ and $F_2 = m \frac{x}{l} gk$ into it and denoting $\alpha = \frac{F}{mgk}$, we get

$$\alpha = \frac{2x^2 + l^2 - 2lx}{2l(l - x)}.$$

Those who know how to find the minimum of a function and equate its derivative to zero can find that $\alpha$ is minimal at $x = l \left( 1 - \frac{\sqrt{2}}{2} \right) \approx 0,3l$. It is equal to 0.43. Thus, in order to twirl the straw, the ants only need to apply a force equal to 0.43 $mgk$ to one of the ends.

The correct solution of the addition: V. Belov (Vologda), I. Bramovskaya (Usolye-Sibirskoye, Irkutsk region), M. Weinhacher (Krivoy Rog); F. Galtsev (Tashkent); E. Golubev (Mamonov, Kaliningrad region), D. Grak (Smolevich, Minsk region), E. Gromak (Novokuznetsk); G. Zaitsev (Gagra); L. Knizherman (Moscow); S. Kuzmchi (Zhitomir); E. Latyshev (Baku), A. Levykin (Raigakhinsk, Amur region), S. Legushiin (Dnepropetrovsk), M. Preer (Tomsk), A. Redchenko (the village of Novopetrovka, Sumy region), A. Renkov (the village of Polomshnoye, Kemerovo region), L. Salina (Blagoveshchensk), V. Servakh (Frunze), N. Fedin (Omsk), M. Flerov (Moscow), G. Shepenko (David-Gorodok, Brest region), M. Yudson (Volgograd), S. Chekmarev (Moscow).

F109

The experiment found that the temperature $m=142$ e of ice water in a light state, suspended in the middle of the room, rose by $\Delta t=4^\circ$ C in half an hour. When the same amount of ice was available, it took 10 hours to pull it. Based on this experiment, what is the specific heat of fusion of ice? Specific heat of water $c_B=1$ cal/g.

Let's find the amount of heat $Q$ that is supplied to the vessel in half an hour. Since this amount of heat was sufficient to heat the water, then

$$Q = c_B m \Delta t.$$

In 10 hours, 20 times more heat is supplied to the vessel. That's why

$$\lambda m = 20 c_B m \Delta t.$$

From here

$$\lambda = 20 c_B \Delta t = 80 \text{ кал/г}.$$

The correct solution to this problem has gained about 100 readers.

F110

If the voltmeter is connected parallel to the upper resistance $r_1$ (Fig. 11), then it shows $u_1=6$v, if parallel to the lower resistance $r_2$, then $u_2=4$v, and if it is connected to points $A$ and $B$, then it shows $u=12$v. What are the actual voltage drops across resistances $r_1$ and $r_2$?

The internal resistance of the source is negligibly small.

When a voltmeter is connected to points $A$ and $B$, its reading is equal to ed. With. source. Therefore, if a voltmeter is connected to resistance $r_1$, and the internal resistance of the voltmeter is $r$, then current flows through the circuit

$$I = \frac{u}{r_2 + \frac{r_1 r}{r_1 + r}}.$$ (1)

This means that

$$u_1 = \frac{u}{r_2 + \frac{r_1 r}{r_1 + r}}.$$ (1)

Fig. 11.

⟦folio 49⟧

Exactly the same

$$u_2 = \frac{u}{r_1 + \frac{r_2 r}{r_2 + r}} \frac{r_2 r}{r_2 + r}.$$

Dividing the final equation (1) by equation (2), we obtain

$$\frac{u_1}{u_2} = \frac{r_1}{r_2}.$$

Thus, $$\frac{r_1}{r_2} = \frac{6}{4} = \frac{3}{2}.$$

When the voltmeter is turned off, the direction drop across resistances $r_1$ and $r_2$ is equal to $u=12$ in. Since the resistance ratio is known, it is not difficult to find the drop in direction $u'_1$ and $u'_2$ on the resistances:

$$u'_1 + u'_2 = u, \quad \frac{u'_1}{u'_2} = \frac{r_1}{r_2}.$$

From here

$$u'_1 = \frac{u r_1}{r_1 + r_2} = \frac{u}{1 + \frac{r_2}{r_1}} = 7,2b;$$

$$u'_2 = u - u'_1 = 4,8b.$$

The correct solution was sent by: P. Anenko (Totskoe village, Orenburg region), E. Doltsov (Moscow), A. Kachilson (Novomoskovsk, Tula region), S. Kuzmchi (Zhitomir), E. Lamyshev (Baku), A. Levykin (Raigakhinsk, Amur region), A. Mamula (Dybintsy village, Kyiv region), V. Peresedov (Pohvistnevo), M. Preezer (Tomsk), L. Rudtser (Kharkov), L. Salnitsa (Blagoveshchensk), A. Sboev (Medvedok settlement, Kirov region), P. Sereev (Grozny), Sh. Slenoy (Chernivtsi), N. Tkachenko (Dnepropetrovsk), I. Turishchev (Kropotkin, Krasnodar Territory), N. Fedin (Omsk), G. Tsibenko (Slavyansk, Donetsk region), L. Tsiferblat (Lvov), V. Shabunin (Moscow), E. Shakhnovich (Kalinin region), R. Shzaanov (Lyubertsy, Moscow region), I. Yurtsenko (Kyiv).

F111

There is a homogeneous cord with an explosive substance. The burning speed of the cord is $v$, the speed of propagation of the blast wave along the impact is $c$. Find the shape of the line along which you need to spread the cord so that the waves from all points of the cord flow to a given point simultaneously.

Is it possible to do the same with an explosive surface and get a descending spherical wave with a high energy density?

If the speed of propagation of the blast wave is greater than the burning speed of the cord, then it is impossible to spread the cord so that the blast waves from all points of the cord flow to a given point simultaneously. If $v=c$, then the cord, which is very long, must be extended along a straight line passing through a given point. In the case of $v>c$ the answer is not so much.

Let's look at this case in more detail.

Let the red curve at figure 12 be the line along which the cord must be spread so that the blast waves rush to point $O$ simultaneously. Let us choose two close points on the line $A$ and $B$ such that the curve $AB$ can be considered a straight line (for this, the segment $AB$ must be much less than the distances $r_0$ and $r_1$ from the point $O$ to the points $A$ and $B$). The time during which the section of cord $AB$ builds will be denoted $\tau$. Then $AB=v\tau$. The smallness of $AB$ means that $\tau$ is small. At $\tau \rightarrow 0$, point $B$ “tends” to point $A$, and the direction of the segment $AB$ - to the direction of the tangent to the red curve at point $A$.

Let's find the angle $\alpha$ that forms the segment $AB$ with radius $OA$. To do this, turn off the segment $OC$ at radius $OA$, equal to the length of radius $r_2$, and draw the segment $BC$. Since the segment $AB$ is small, the segment $BC$ coincides with another circle of radius $r_1$ with the center at the point $O$ and the angle $ACB$ is close to a straight line (and at $\tau \rightarrow 0$ $\Rightarrow ACB \rightarrow \frac{\pi}{2}$). This means that

$$\cos \alpha = \frac{AC}{AB}.$$

But $AB=v\tau$, and $AC=r_0-r_1$. Since the time of propagation of the blast wave from point $B$ should be m less than the time of propagation of the wave from point $A$, then $r_1=r_0-c\tau$. Therefore, $AC=r_0-r_0+c\tau=c\tau$ and

$$\cos \alpha = \frac{c\tau}{v\tau} = \frac{c}{v}.$$

Thus, the angle subtended by the tangent to the red curve and the radius drawn to the point of the curve from the point $O$ does not depend on the distance of the curve to the point $O$, and the red curve intersects all the rays leaving the point $O$ at the same angle $\alpha = \arccos \frac{c}{v}$. Such a property

⟦folio 51⟧

Fig. 14.

incidence and refraction of the ray for each of the planes, we obtain that the angle at which the ray travels in each of the planes is the same as if the light falls on it from the air

$$\frac{\sin \beta_1}{\sin \gamma_i} = n_i$$

From here, in particular, it follows that after passing through the entire stack of planes, the ray will come out parallel to its original direction:

$$n_{k+1} = 1 \text{ и } \frac{\sin \beta_1}{\sin \gamma_{k+1}} = 1, \text{ то есть}$$

$$\beta_1 = \gamma_{k+1}$$

The mixing of the beam is obviously equal to the sum of its mixing in individual planes

$$h = h_1 + h_2 + \dots + h_k$$

Let's find the mixture $h_i$ (Fig. 14). To do this, first find $AB$ from triangle ADB:

$$AB = \frac{AD}{\cos \gamma_i} = \frac{d}{\cos \gamma_i}$$

Now from triangle ACB we get

$$h_i = AB \cdot \sin (\beta_1 - \gamma_i)$$

$$= d \frac{\sin (\beta_1 - \gamma_i)}{\cos \gamma_i}$$

$$= d (\sin \beta_1 - \cos \beta_1 \mathrm{tg} \gamma_i)$$

Since $tg \gamma_i = \frac{\sin \gamma_i}{\sqrt{1 - \sin^2 \gamma_i}}$

$$= \frac{\sin \beta_1}{n_i} \sqrt{1 - \left(\frac{\sin \beta_1}{n_i}\right)^2} = \frac{\sin \beta_1}{\sqrt{n_i^2 - \sin^2 \beta_1}}$$

then $h_i = d \sin \beta_1 \left(1 - \frac{\cos \beta_1}{\sqrt{n_i^2 - \sin^2 \beta_1}}\right)$

$$= d \cos \alpha \left(1 - \frac{\sin \alpha}{\sqrt{n_i^2 - \cos^2 \alpha}}\right)$$

The total beam mixing is

$$h = h_1 + h_2 + \dots + h_k$$

$$= d \cos \alpha \left( k - \frac{\sin \alpha}{\sqrt{n_1^2 - \cos^2 \alpha}} - \frac{\sin \alpha}{\sqrt{n_2^2 - \cos^2 \alpha}} - \dots - \frac{\sin \alpha}{\sqrt{n_k^2 - \cos^2 \alpha}} \right)$$

$$= d \cos \alpha \left( k - \sin \alpha \sum_{i=1}^{k} \frac{1}{\sqrt{n_i^2 - \cos^2 \alpha}} \right)$$

The correct solution was sent by V. Belov (Vologda), E. Dollov (Moscow), A. Mamula (Dybintsy, Kyiv region), V. Mukhanov (Kanash UASSR), S. Pomashev (Ulyanovsk), M. Premer (Tomsk), L. Rudtser (Kharkov), A. Sboev (Medvedok village, Kirov region), P. Sereev (Grozny), Sh. Blind (Chernivtsi), N. Tkachenko (Dnepropetrovsk), A. Udaltsov (Kaliningrad, Moscow region), N. Fedin (Omsk), S. Fillenko (Zaporozhye), G. Filkovsky (Baku), M. Flerov (Moscow), S. Chekmarev (Moscow), G. Shenemko (David-Gorodok, Brest region).

F113

The vessel is half filled with water in which a piece of ice floats. Kerosene is poured over the ice, the upper level of which is set at a height of $h$ from the bottom of the sauce (Fig. 15). How will this height change when the ice melts?

In the case where a piece of ice is completely covered with kerosene (as shown in figure), the problem is solved very simply.

Let us mentally fix the shell enclosing a piece of ice and melt the ice. Obviously, the volume of water formed will be less than the volume of ice. Consequently, the overall liquid level in the vessel will decrease.

Now suppose that the kerosene does not cover the ice.

It is clear that if there were only water and ice in the vessel, then after the ice melted the water level would not change. Indeed, since the force of pressure on the bottom of the sauce is equal to the weight of the contents of the sauce, and it does not change when the ice melts, the force of pressure on the bottom of the sauce does not change. This means that the pressure at the bottom of the sauce does not change. But the ice does not exert direct pressure on the bottom - it floats. Therefore, the pressure at the bottom is equal to the water pressure

$$P = \rho_B g h_B$$

After the ice melts, the pressure is also equal to the water pressure

$$P = \rho_B g h_B'$$

This means $h_B = h_B'$.

⟦folio 52⟧

Fig. 15.

In our case, the pressure on the bottom does not change either. But now it is equal to the sum of the pressure of so many water and kerosene

$$P = \rho_B g h_1 + \rho_K g (h - h_1) = (\rho_B - \rho_K) g h_1 + \rho_K g h'$$

If the water level in the vessel after the ice melts is $h'_1$, and the kerosene level is $h'$, then

$$(\rho_B - \rho_K) g h'_1 + \rho_K g h' = (\rho_B - \rho_K) g h_1 + \rho_K g h'$$

Let the volume of ice in water be equal to $V_1$, the volume of ice in kerosene equal to $V_2$, and the mass of ice equal to $m$. Let's imagine that, having removed the ice, we left its weightless shell and poured water and kerosene into it so that their level in the shell coincides with the level of water in the vessel. It is clear that this shell will be in equilibrium. But this means that the shell of water is subject to the Archimedean buoyant force $F$, equal to the weight of the liquid poured into the shell

$$F = \rho_B g V_1 + \rho_K g V_2$$

If ice itself is placed in the shell, then the force $F$ will not change. But the ice floats. This means that $F = mg$ and

$$\rho_B g V_1 + \rho_K g V_2 = mg.$$

If there were only ice and water in the vessel, then there would be such a volume of ice $V'_1$ in the water that

$$\rho_B g V'_1 = mg.$$

From formulas (1) and (2) it follows that in our case there is a volume $V_1$ in the water, which is less than $V'_1$, that is, less than the ice that was immersed in water in the absence of kerosene above it. But in the latter case, as we have shown, the water level in the vessel would not change. This means that the water formed when the ice melts would fill exactly the volume $V'_1$ of the submerged part of the ice.

In our case, the volume of water formed when ice melts is the same, but the volume
