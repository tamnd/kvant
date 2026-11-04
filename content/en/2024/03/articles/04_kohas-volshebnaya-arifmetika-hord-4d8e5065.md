---
id: 2024-3-kohas-volshebnaya-arifmetika-hord-4d8e5065
issue: kvant_2024_3
year: 2024
number: "3"
title: Magic arithmetic of chords
authors:
  - Кохась К. П.
rubric: osnovnye-stati
page_first: 15
page_last: 25
page_labels: 14-23
lang: en
source: kvant_digital
content_sha256: 0e617b0528b03ffc84b9e0a532749db7ebfcb4a7a32515ffe2bdb2626e6869fb
prompt_sha256: draft-1
translated_from: content/ru/2024/03/articles/04_kohas-volshebnaya-arifmetika-hord-4d8e5065.md
source_content_sha256: b5d1626b7c19636cba2146be69d06344f0cf7e30f0c8be1d5cd048c7cf96d19e
translation_model: draft
translation_run: en-draft-2026-11-03
translation_quality: draft
---

⟦folio none⟧

---
running_head:
folio:
---

Magic arithmetic of chords
K.KOKHAS

Eppiclopidae and Hippoclopidae
Let a red one be fixed on the plane
circle, and a black ok-
circle, the radius of which is d times smaller.
A feather is placed at one of the points of the black circle, leaving a blue mark on the plane. A curve constructed in this way is called an epicyclopedia.
When d = 1, this curve has its own name - cardioid (Fig. 1), when d = 2 the curve is called nephroid.
Now let’s consider a similar construction: a red circle is fixed on a plane, and a black circle, the radius of which is d times smaller, rolls along it from the inside. A pen is placed at one of the points of the black circle, leaving a blue curve on the plane called zuno-cyclops. When d = 3 the curve is called delmodoi (Fig. 2), when d = 4 it is called astrodoi.
When mentioning these curves, we will indicate the parameter d as a prefix. As is easy to see, d-eppicclopda and d-hippospiclopda have a pointed d when d is integer. But d can also be taken purposefully. With rational d = m/n (irreducible fraction), the black circle will have to roll over the red circle n times before

Fig. 1
Fig. 2

DOI: https://doi.org/10.4213/kvant20240301

2-eppiclopda
7-eppiclopda
3/2-epiclopda
5/3-epiclopda
4-hipposptsclopda
2-hippospiclopda
5/2-hipposclopda
7/5-hippospclopda
Fig. 3

will return to its original location. The resulting curves are m pointed and make n turns around the red circle (Fig. 3). For irrational d, the curve does not loop and turns around the red circle infinitely many times.

First experiment
Let a regular n-gon A₀A₁A₂...Aₙ-1 be given. On the cards we will draw the circumcircle of the n-gon in green, and we will not specially highlight the vertices in any way (except for the very first card). At the same time, we consider

⟦folio 14⟧

---
running_head:
folio:
---

we understand that the vertex $A_0$ is always the most
the right point is considered a circle.
(Winnie the Pooh would call it the eastern pole-
som.)

So, an experiment. Well, yes, why hide it?
Well, computer. For each $i$ from 1 to
$n-1$ will be drawn in our $n$-gon diago-
nal $A_i A_{2i}$, where the number of the second vertex
calculated modulo $n$ (Fig. 4; here
$n=120$). Every this curve we are somewhere
I've already seen it.

Fig. 4

Theorem. The body we see
at figure 4, – cardioid.

Proof. Consider a cardioid whose radii are red and black
circles (see Fig. 1) 3 times smaller
radius of the circumscribed circle of the $n$-gon, and fix the position of the moving
of a circle, when from the point of contact
with the red circle, an arc of magnitude $\alpha$ (Fig. 5) remains to the tip of the cardioid.

Let us successively mark the angles $\alpha$, then $\alpha/2$, and finally $\pi-\alpha$ on this map. Angle $BOC$ is also equal to $\pi-\alpha$. Thus, the chord $BC$ greater than the circle connects the point $B$ with the angular coordinate $\pi-\alpha$ and the point $C$ with the angular coordinate $2(\pi-\alpha)$. These are exactly the chords we carried out in the experimental polygon.

Let's check that the line $BC$ is tangent to the cardioid. To do this, we will use “mechanical” messages: the direction of the tangent to the curve coincides with the direction of the velocity vector of the point drawing this curve. Let it be black

⟦folio 15⟧

MAGICAL

ARITHMETIC

The theorem has been proven. Let us note, just in case, that in fact on figure 4 the cardioid itself is not drawn, but only a family of segments for which the cardioid is an envelope is drawn. We will not comment here on the term “envelope” - the name successfully speaks for itself, and for details the reader can refer to the books [4, 5]. Since there are many segments, the eye smoothes out the broken line made up of their fragments, and it seems to us that we see a smooth curve. If we draw diagonals $A_{i} A_{di}$, for i = 3, 4, …, we will similarly obtain d 1 -epicycloids (Fig. 7; for d 3, 4, 10 and n 120). It is also easy to understand

CHORD

⟦column⟧

⟦figure⟧

Fig. 8.

⟦figure⟧

Fig. 9.

⟦figure⟧

Fig. 10

⟦figure⟧

Fig. 7

Note that when you try to experiment with linear expressions $A_{i} A_{di} l$ you will only get rotated epicycloids. For example, A i A i 5 A i 5 5 A 2 i 5 5, i.e. by shifting the vertex numbering by 5, we get the original doubling rule.

Second experiment

Inspired by the first experiment, let's try to draw diagonals of the form $A_{i} A_{2} i$ in an n-gon, where the index 2i is again calculated modulo n. Here is an example of the resulting pictures for n 120 (Fig. 8) and n 119 (Fig. 9).

⟦figure⟧

Fig. 11

As we can see, the chords quite regularly fill the circle and are not grouped around the envelopes. Although... they are not grouped inside the circle. Let's continue them in a suitable way (Fig. 10; for n 120). We will see a nice “curvilinear” triangle - a deltoid. A similar picture will be obtained if we draw diagonals of the form $A_{i} A_{3} i$ (Fig. 11).

⟦folio 16⟧

KVANT 2024/№3

⟦column⟧

⟦figure⟧

Fig. 14

⟦figure⟧

Fig. 12

⟦figure⟧

Fig. 13

Continuing them appropriately outward (Fig. 12; for n 120), we obtain an astroid. This time we “stumbled upon” hypocycloids. The curve at figure 10, enveloping the family of our chords $A_{i} A_{2} i$, is a deltoid, and the curve at figure 12 is an astroid. Increasing k, we obtain in the picture with diagonals $A_{i} A_{ki}$ hypocycloids with an increasing number of teeth (Fig. 13). Interestingly, at figure 13 at n 100, k 9 both 10-hypocycloids and 10-epicycloids are visible. This is due to the fact that the relation 9 11 { 1 mod100 is satisfied, i.e. modulo 100, the operations of multiplication by 9 and 11 are mutually inverse and the set of pairs of the form i, 9 i coincides with the set of pairs 11 j, j. figure 14 shows a similar picture for n 109, k 9, since 9 12 { 1 mod109, but the epicycloids and hypocycloids are “not synchronized.” It is clear that for a fixed n we cannot make the number of teeth too large. figure 15 shows an extreme example in this sense: a 30-hypocycloid with n 120, k 29. It seems that there are fewer segments here than in the neighboring pictures. This is because for i multiples of 4 the comparison 29 i { i mod120 is made, and therefore every fourth chord here is degenerate, on figure these chords are depicted as blue dots. When i { 2 mod 4 the chords coincide with the diameters (this means the coincidence of the chords,

Fig. 15

⟦folio 17⟧

---
running_head:
folio:
---

emerging from diametrically opposite points) and these diameters serve as the boundaries of the sectors in which the hypopiclopid denticles are inscribed.

Note also that a 2-hypopyclopid is a degenerate curve, which is a segment (see Fig. 3). Following the pattern we found - a picture with chords of the form $A_i A_{-ki}$ generates a $(k+1)$-hypopyclopid, we can assume that the parallel chords in the degenerate picture at $n=120$, $k=-1$ (Fig. 16) are trying, to the best of their modest strength, to depict this very segment. It doesn’t turn out very well, because if you draw a tangent to a segment without being on the same line with it, it’s a hopeless matter.

**Theorema. The figure we see at figure 12 is an astrude.**

**Proof.** Let us use the following characteristic property of astrud (see [4, 5]). Let us consider all possible segments of length $l$, the vertices of which are on the sides of a right angle. It turns out that the astrude is a generalization of this family of segments (Fig. 17).

Let $R$ be the circumradius of the $n$-gon. Let us check for the right quadrant of the figure on figure 12 that the straight segments containing our chords, cut out by a red right angle, we have

**Fig. 17**

have a constant length $2R$. This means that the ognioshaya of our chords is astruda. Let the point $M$ be one of the vertices $A_i$ corresponding to the central angle $\angle A_0OM = \varphi \in \left(0; \frac{\pi}{4}\right)$, and the point $S$ be the vertex $A_{-3i}$ (Fig. 18). Let us draw red rays from the origin, inclined at an angle $\pm \frac{\pi}{4}$ to the horizontal axis, and mark the intersection points $P$ and $Q$ of the straight line $MS$ with these rays. In the resulting picture we can easily find that the triangle $OMP$ is equilateral with acute angles $\frac{\pi}{4} - \varphi$. It immediately follows that $M$ is the midpoint of the hypotenuse of the right angled triangle $OPQ$. And then $PQ=2OM=2R$.

**Theorema has been proven.**

We leave it to the reader to find a proof that figure 10 depicts a delutica, similar to the proof from the first experiment.

**Third experiment**

In the first and second experiments, we carried out diagonals $A_i A_{ki}$ in the $n$-gon and found two different coefficients - for small positive $k$ (i.e. close to 0) ogniors of this family of diagonals is an epicyclope, and for small negative ones (i.e. close to $n$, since our calculations are modulo $n$) values $k$ ognioshaya – hypopyclopda. Somewhere in the middle there must be a “phase transition” from one picture to another. Let's try to find this place.

Let's take $n=120$ and see what happens at $k=61, 60$ and 59 (Fig. 19, 20 and 21).

⟦folio 18⟧

---
running_head:
folio:
---

Primo, let's say, these paintings are significantly poorer. If you look closely, you can come up with a plot that they show us. The first picture (see Fig. 19) depicts the fact that $61^2 \equiv 1 (\bmod 120)$, and the second (see Fig. 20) - that the set of values of the mapping $m \mapsto 60m \bmod 120$ consists of two points - 0 and 60. After such comments, the third picture for $k = 59$ (see Fig. 21) with all its independence looks quite mysterious. Let us also note that in the first experiment we did not draw pictures for $k = 0$ and $k = 1$ - they are also “not too mature”.

On the other hand, figure 19 is a development of the idea contained in figure 15. Still $n = 120$, compare this picture with your ideas about what the dial of a regular watch with hands looks like. Notice? There are only 60 radii here, as on the minute dial (only with mixing into polynuts), and the remaining 60 points give us 60 degenerate single-point chords $A_{2i}A_{2i}$, because

$$61 \cdot 2i \equiv 2i (\bmod 120).$$

Thus, the diagonals of the 120-gon, drawn in this picture, are trying to suck in the 60-hypopiclonde. On average, there are only 2 vertices per one curl of the hypopyclonde (one pole and two “halves”): each radius describes the boundary of the sector where the petal is inscribed - this is the tangent at the point of cusp, and the degenerate chord between the two radii tries to depict the tangent to the hypopyklond “at the usual point.” To the same extent and in approximately the same way, this figure also depicts the 60-hypopyclonde for $k = 61$, $n = 120$ (Fig. 22). For clarity, we present a similar “larger” picture for $k = 11$, $n = 20$ (Fig. 23).

Fourth experiment

So, we have found the “phase transition” points. Alas, visually they turned out to be not very interesting. Let's look again at the case of $k = 62$ and $k = 58$ with $n = 120$ (Fig. 24).

In the left picture two cardionds are visible. The right picture is completely different, but in style it fully corresponds to the pictures from the second experiment (see Fig. 8 and 11). And indeed, continuing the approach with the image of the chord $A_iA_{58i}$ for even and odd $i$, we obtain the familiar images

⟦folio 19⟧

---
running_head:
folio:
---

Bom can also explain the degenerate picture on figure 21: if we believe that figure 16 depicts us a 2-hypocycloid, then figure 21 with $n = 120$, $n = \frac{k}{2} - 1 = 59$ tries to show us two 2-hypocycloids!

Let’s also look “just in case” at what happens with odd $n$. For example, for $n = 121$ at $k = 62$ and 63 (Fig. 28, 29). We see here $\frac{1}{2}$ and $\frac{3}{2}$-eppcycloids - the black circle from the beginning of our stat must make two turns, lining the red one, before the line closes. This is also a kind of doubling, only instead of getting two figures in one turn, we get here one figure, but in two turns.

Well, we have stumbled upon a new phenomenon, let's interpret it. Let $n$ be even, $k = \frac{n}{2} + 2$, and assume that we have drawn the chord $A_i A_j$, where $j \equiv \left(\frac{n}{2} + 2\right) i \pmod n$. Let's see where the chord leads from point $A_{i+2}$:
$$\left(\frac{n}{2} + 2\right)(i + 2) = \left(\frac{n}{2} + 2\right)i + 4 \equiv j + 4 \pmod n.$$ (*)

So, the chord from point $A_{i+2}$ leads to point $A_{j+4}$. In other words, the beginning of the chord rotates through a certain angle, and the end through twice the angle. This means that the drawn lines obey the pattern from the first experiment and should draw us a cardonde. Since $n$ is even, moving along the vertices with a step of 2, we obtain two families of chords $A_i A_{ki}$ – for even and for odd $i$. This family corresponds to cardionds, differing by a half-turn:

⟦folio 20⟧

---
running_head:
folio:
---

of one cardiond, the starting point corresponds to the degenerate chord $A_0A_0$, while the neighboring chord $A_1A_{\frac{n}{2}+2}$ from the second family almost coincides with the diameter of the circle, i.e. draws the tip of the second cardiond.

For $k = \frac{n}{2} - 2$ we obtain hypocyclopes analytically.

Now the path $n$ is odd, $n = 2m + 1$, and the number $k$ is slightly larger than $\frac{n}{2}$ (as on Fig. 28):
$k = m + 2 = \frac{n}{2} + \frac{3}{2}$. Here it is analytically observed (*) that an increase in the index $i$ by 2 leads to an increase in the index $j$ by 3. But due to the oddness of $n$, the chords are no longer divided into two families.

Moreover, consider the chord $A_iA_j$, where $j = ki = \left(\frac{n}{2} + \frac{3}{2}\right)i$. Note that for the odd model $n$ the operation of division by 2 is well defined and that

$$2j = 2\left(\frac{n}{2} + \frac{3}{2}\right)i \equiv 3i(\bmod n).$$

In other words, $j \equiv \frac{3}{2}i(\bmod n)$. It turns out that the pattern that we discovered in the first experiment also works for fractional epicyclopes!

Let's be more precise: in the first experiment we discovered that if we take the natural number $d$ and draw the chord $A_iA_{ki}$, where $k = d + 1$, then a $d$-epcyclops is visible in the picture. Now let $d$ be rational:

$$d = \frac{p}{q}$$. If the numbers $q$ and $n$ are mutually prime, then according to the model $n$ the remainder $q^{-1}$, “inverse to $q$”, is uniquely determined, i.e. such that $q \cdot q^{-1} \equiv 1(\bmod n)$. In this case, to obtain a $d$-epcyclops, one should draw chords $A_iA_{ki}$, where $k = pq^{-1} + 1(\bmod n)$. So, for figure 29 we have $p = 3$, $q = 2$, $q^{-1} = 2^{-1} = 61(\bmod 121)$ and, therefore, for drawing

⟦folio 21⟧

---
running_head:
folio:
---

MAGIC ARITHMETICS OF CHORDS
21

Fig. 32. One $\frac{8}{3}$-hypopyiclopida, $k = 38, n = 119$

Fig. 35. Three cardiopiids, $k = 62, n = 180$

Fig. 33. Two $\frac{1}{2}$-epicyclopiids, $k = 62, n = 242$

Fig. 36. Seven 2-hypopyiclopidae, $k = 22, n = 161 = 7 \cdot 23$. There are few chords here because $22^2 \equiv 1(\text{mod } 161)$. As you can easily see, when you move one end of the chord by +7, the other end will play by -7. Therefore, the chords are divided into 7 families of parallel lines

⟦folio 22⟧

---
running_head:
folio:
---

22
KVANT · 2024 / No. 3

Fig. 37. One $\frac{1}{3}$-epicclopda, $k = 41$, $n = 119$;
$\frac{1}{4}$-epicclopda, $k = 3$, $n = 119$; $\frac{1}{6}$-epicclopda,
$k = 21$, $n = 119$

Fig. 39. Four delons at $k = 28$, $n = 120$

Fig. 38. Case $k = 16$, $n = 119$. It's still possible here
see both the phantom $\frac{1}{8}$-epiclopda and
15-epicklopdu. And six families are parallel
ny lines hint at a collection of 2-hypopyx-
LOPD

Fig. 40. Here $k = 24$, $n = 161 = 23 \cdot 7$ (left) and
$n = 207 = 23 \cdot 9$ (right). When dividing $n$ by
$k - 1$ makes a small number (7 or 9).
The angular magnitude of the $i$th chord $A_i A_{ki}$ is
$\frac{i}{7}$ or $\frac{i}{9}$ from full turn and picture
preserved when rotated to $\frac{2\pi}{23}$. Therefore we
we see circles

⟦folio 23⟧

MAGICAL

ARITHMETIC

CHORD

⟦column⟧

The author accidentally learned about the beautiful pictures from the first experiment (see Fig. 4, 7) and received their justification by looking at the book [3]. As it turned out, «Kvant» had already written about these pictures at the dawn of its existence [2] and at a later time [1]. A detailed selection of problems and results on epi and hypocycloids is contained in [5]. An excellent visualization of the first experiment can be viewed on the website “Mathematical Etudes” [6]. Having become interested, the author began to experiment further, and then decided to share the results. The reader can do experiments himself; the Mathematical Constructor program can help with this [7].

References

⟦figure⟧

Fig. 41. Cases k 71, n 265 and k 71, n 274. You can look at these pictures endlessly

1. A. Akopyan. Cardioid geometry. – «Kvant», 2012, No. 3. 2. V. Berezin. Cardioid. – «Kvant», 1977, No. 12. 3. G.N. Berman. Cycloid. – M.: Nauka, 1980. 4. V.G. Boltyansky. Envelope. – M.: Fizmatgiz, 1961. 5. N.B. Vasiliev, V.L. Gutenmacher. Straight and curved. – M.: MTsNMO, 2006. 6. Mathematical studies. https: etudes.ru models cardioid-nephroid 7. Mathematical constructor. https: obr.1c.ru mathkit

You can subscribe to the magazine «Kvant» from any number at any post office. Our subscription index in the “Press $России»^{–}$ 90964” catalog. It is possible to buy the magazine «Kvant» in the “Mathematical Book” store of the publishing house MCNMO (online store address: biblio.mccme.ru), as well as in the Moscow bookstores “Biblio-Globus”, “Young Guard”, “Moscow House of Books” and in the editorial office of the magazine. An archive of published issues of the magazine «Kvant» is available on the website http://kvant.ras.ru

To the attention of our readers
