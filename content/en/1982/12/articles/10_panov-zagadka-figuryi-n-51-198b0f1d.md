---
id: 1982-12-panov-zagadka-figuryi-n-51-198b0f1d
issue: kvant_1982_12
year: 1982
number: "12"
title: Figure Mystery No. 51
authors:
  - Панов А.
rubric: kvant-dlya-mladshih-shkolnikov
rubric_sub: «Квант» для младших школьников
page_first: 36
page_last: 39
page_labels: 34, 36, 37
tag: RRDF
lang: en
source: kvant_digital
extraction: vision
content_sha256: d55150e1ba92e744284f1b196cf891f53db9ceacb7904bffd75e27739cc936e4
prompt_sha256: draft-1
translated_from: content/ru/1982/12/articles/10_panov-zagadka-figuryi-n-51-198b0f1d.md
source_content_sha256: 16e3c82d4b7a82f478823ab6a7f5e6ae681b4da1d599438ef35aa4d6f55966cd
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 34⟧

A. Panov

Figure Mystery No. 51

Cut a square out of cardboard and divide it into parts as shown in figure 1 - you get the “tangram” puzzle, invented several thousand ago in China and now known throughout the world. Using all seven elements of the tangram, you can create many elegant figures; try to compose, for example, “a woman with a head” (Fig. 2).

No, the original square can be cut in another way, for example, as into figure 3. This is exactly how it is divided in the “Pythagoras” puzzle, produced in our country. figure 4 shows figure No. 51 from the instructions for the Pythagoras specimen, which was made in Kuznetsk; The instructions suggest making this figure from the seven elements of Pythagoras.

I tried for a long time to make figure No. 51. The closest thing to it that I succeeded in is shown on figure 5. In the end I doubted: is it possible to do this?

M. Gardner’s book “Mathematical Puzzles and Entertainment” (M., “Mir”, 1971) helped me find the answer. Us. 329 talks about how the problem of listing convex polygons that can be composed of seven tangram elements was solved:

“Two Chinese mathematicians, Fu Tren-wang and Chuan Chi-hsun, published a paper in 1942 in which they considered this problem. Their approach to the solution was weighty and ingenious. Each of the heels of the large parts of the tangram (two large triangles, one smaller triangle, a square and a parallelogram) can be divided into equilateral right triangles, congruent with the two smallest triangles. In total, you will get 16 completely identical equilateral right triangles. Using subtle calculations, the authors showed that from these 16 triangles it is possible to construct 20 different convex polygons (polygons that transform into each other during rotations and reflections are not considered different). From here it is not difficult to prove that only 13 of those found

⟦folio 36⟧

sovereign, you need to indicate 4 more non-negative integers $x, y, z$ and $w$ - the lengths of the legs of the angles to be cut off (see Fig. 8). Knowing these six numbers, it is easy to calculate the area of ​​a polygon:

$$S = ab - \frac{1}{2} (x^2 + y^2 + z^2 + w^2).$$

For exclusion polygons, it must coincide with the total area of ​​16 equilateral right triangles with legs of length 1: $S = 16 \cdot \frac{1}{2} = 8$.

So, our problem has undergone an amazing transformation: from a purely geometric problem about composing polygons, it turned into a purely arithmetic problem about finding non-negative integer solutions to the equation

$$2ab - 16 = x^2 + y^2 + z^2 + w^2. \quad (1)$$

In this case, of course, it is also necessary that the sum of the lengths of the legs of the cut off corners adjacent to one side of the rectangle should not be greater than the length of this side. In other words, the numbers $a, b, x, y, z$ and $w$ must satisfy additional conditions

$$x + y \leq a, y + z \leq b, z + w \leq a, w + x \leq b. \quad (2)$$

From now on, geometry and arithmetic will go hand in hand.

First of all, let's find out what the dimensions of a rectangle can be.

On the one hand, its area must be no less than the area of ​​the exclusive polygon:

$$ab \geq 8. \quad (3)$$

(This inequality is easy to obtain directly from equation (1).)

On the other hand, if you cut off the corners of the most total area from a rectangle, then the area of ​​the remainder should be no more than 8. From figure 9 it is clear that the total area of ​​the corners adjacent to one side of the rectangle is less than the area of ​​an isosceles right triangle, the legs of which are congruent to this side. Therefore, a small (non-empty) remainder is obtained by cutting off the corners from the rectangle as at figure 10, $a$ at $a < b$ and as at figure 10, $b$ at $a = b$. In the first case, we will be left with a parallelogram of area ($b - a$) $a$, in the second - a trapezoid of area $a - \frac{1}{2}$. Therefore, at $a < b$

$$(b - a)a \leq 8, \quad (4)$$

and at $a = b$

$$a - \frac{1}{2} \leq 8. \quad (5)$$

(Try to derive these inequalities from conditions (1) and (2)!)

Pairs of natural numbers ($a, b$) satisfying inequalities (3) and (4) or (3) and (5) can be easily found by simple search. For example, for $a = 1$ we find that $b \geq 8$ and $b - 1 \leq 8$, that is, $b = 8$ or 9, for $a = 2$ we find that $b = 4$, 5 or 6, etc. There are 19 such pairs in total: (1, 8), (1, 9), (2, 4), (2, 5), (2, 6), (3, 3), (3, 4), (3, 5), (4, 4), (4, 5), (4, 6), (5, 5), (5, 6), (6, 6), (6, 7), (7, 7), (7, 8), (8, 8), (8, 9).

For each of these pairs, it is necessary, according to equation (1), to find all representations of the number $2ab - 16$ in the form of a sum of four squares $x^2 + y^2 +$

⟦folio 37⟧

+z²+w², and then check inequalities (2), or draw a rectangle a×b and find all ways of cutting off the corners, which leaves a polygon of area 8.
(By the way, for some of the 19 pairs (a, b) the numbers x, y, z, w cannot be found.) The results of such calculations are summarized in a table containing a list of all 20 convex polygons that

$$\begin{array}{cccccccc}
a & b & x & y & z & w & T & \Pi \\
1 & 8 & 0 & 0 & 0 & 0 & 0 & 0 \\
1 & 9 & 0 & 1 & 0 & 1 & 0 & 1 \\
1 & 9 & 0 & 1 & 1 & 0 & 0 & 0 \\
2 & 4 & 0 & 0 & 0 & 0 & + & + \\
2 & 5 & 0 & 0 & 0 & 2 & + & + \\
2 & 5 & 1 & 1 & 1 & 1 & + & + \\
2 & 6 & 0 & 2 & 0 & 2 & + & + \\
2 & 6 & 0 & 2 & 2 & 0 & + & + \\
3 & 3 & 0 & 0 & 1 & 1 & + & + \\
3 & 3 & 0 & 1 & 0 & 1 & + & + \\
3 & 4 & 0 & 2 & 0 & 2 & + & + \\
3 & 4 & 0 & 2 & 2 & 0 & + & + \\
3 & 5 & 0 & 3 & 1 & 2 & + & + \\
3 & 5 & 0 & 3 & 2 & 1 & + & + \\
4 & 4 & 0 & 0 & 0 & 4 & + & + \\
4 & 4 & 2 & 2 & 2 & 2 & + & + \\
4 & 6 & 0 & 4 & 0 & 4 & + & + \\
5 & 5 & 0 & 3 & 0 & 5 & + & + \\
5 & 5 & 1 & 4 & 1 & 4 & + & + \\
8 & 9 & 0 & 8 & 0 & 8 & + & + \\
\end{array}$$

List of readers who sent correct solutions

(For the beginning, see p. 32)

(Ryazan) 32; K. Knol (Odeska) 30; E. Kovalchik (Kyiv) 22, 33; M. Kreal (Donetsk) 32, 35; I. Kopylets (Karlovka) 28; D. Korshunov (Novosibirsk) 22, 23, 30, 32, 33; A. Kostok (Berdtseve) 22; K. Kokhas (Leningrad) 23, 32, 33; Yu. Kochetkov (Vinnitsa) 28; E. Kochkin (Volzhsky, Volgograd region) 32, 33; I. Kulyatsin (Sverdlovsk) 32; M. Lev (Sverdlovsk) 22; B. Leeb (Kelheim, Germany) 28, 30; M. Levkin (Dushanbe) 22, 23, 25, 28; D. Lokshin (Moscow) 32; O. Mazurov (Novosibirsk) 23; I. Markev (Moscow) 22, 23; A. Markovic (Belgrade, SFRY) 23, 25, 28, 35; O. Matveev (Sverdlovsk) 25; L. Naimark (Leningrad) 23; P. Finally (Krivoy Rog) 25; S. Nekrasov (Cherpovets) 25; A. Nenov (Pleven, Belarus) 22, 23; Yu. Nikolaevsky (Kharkov) 25; A. Olenko (Uman) 22, 25; D. Orlov (Vladimir) 22, 25; D. Persheev (Moscow) 23; K. Poraiko (Vinnitsa) 28, 35; A. Rodtsov (Moscow) 22, 23, 33; V. Romanov (Moscow) 22, 23, 33, 35; L. Rudy (Kirovsk, Murmansk region) 23, 25, 33, 35; E. Rukhlin (Vinnitsa) 28; V. Sadovsky (Tashkent) 23, 32, 33; A. Sviridov (Moscow) 25, 28, 32, 33, 35;

A. Semenov (Saratov) 23; F. Serzhenko (Zaporozhye) 25; P. Sefibekov (village of Kashkent DASSR) 32; O. Smirnov (Island) 23; B. Starobin (Severodonets) 32; S. Strukov (Voronezh) 22, 25, 28, 30, 32; A. Surkov (Leningrad) 23; I. Teretsak (Strazhcke, Czechoslovakia) 30; S. Tiptsov (Kyiv) 23, 25, 30; M. Titarenko (Vinnitsa) 35; H. Titarenko (Vinnitsa) 28; P. Ugrinovsky (Khmilnik) 25, 28; N. Fedin (Omsk) 25; B. Friedman (Moscow) 22, 33; S. Khirman (Kyiv) 23; L. Christoph (Sofia, Belarus) 32, 33; B. Khrytskov (Sevastopol) 23; S. Tsonev (Sofia, Belarus) 23, 25, 32; S. Chernyshev (Aleksaandrov) 32; B. Shabunin (Moscow) 23, 25; S. Shkarin (Moscow) 25, 28, 30; E. Shulman (Volgoda) 22; Y. Emus (Tyuki village, ESSR) 25, 32; L. Erdets (Budaletst, Hungary) 22, 28, 33, 35; S. Yurovsky (Mytnits) 23, 25, 32, 33, 35.

Physics

Most of the readers who submitted solutions coped with problems F748, F754 and F761. Other tasks: O. Andreev (Kyiv) 59, 60; A. Babayan (Moscow) 49, 52, 56, 60, 62; L. Bayrak (Belgorod) 57; B. Baranov (Donetsk) 52, 55, 56, 59-62; Yu. Bril (Dnepropetrovsk) 50, 55—57, 59, 60; M. Broditsky (Kiinnev) 53; B. Budilov (Kirovo-Chepetsk) 55-57; B. Bulavas (Panevzys) 49,

(Continued on page 41)
