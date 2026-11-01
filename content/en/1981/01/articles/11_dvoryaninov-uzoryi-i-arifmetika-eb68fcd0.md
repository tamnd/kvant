---
id: 1981-1-dvoryaninov-uzoryi-i-arifmetika-eb68fcd0
issue: kvant_1981_1
year: 1981
number: "1"
title: Patterns and... arithmetic
authors:
  - Дворянинов С. В.
rubric: kvant-dlya-mladshih-shkolnikov
rubric_sub: «Квант» для младших школьников
page_first: 36
page_last: 38
page_labels: 34-36
tag: CZH2
lang: en
source: kvant_digital
extraction: vision
content_sha256: 0b3e98cd997e33b2fee0a5573c5a46e93e1a88065e7edc6d93eab6b5a3517807
prompt_sha256: draft-1
translated_from: content/ru/1981/01/articles/11_dvoryaninov-uzoryi-i-arifmetika-eb68fcd0.md
source_content_sha256: bd6d19855541e83238bf17a4074e13f994637826e682a6902e1083d0092dd77c
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 34⟧

S. Dvoryaninov

Patterns and...
arithmetic

The Figure you see in front of you (Fig. 1) was obtained using a simple device called a spirograph. And although the spirograph is sold in toy stores, it is of interest not only to elementary school students, but also to high school students and older people. It can be used to draw a variety of curves. Probably, many, after receiving several beautiful figure, will want to figure out how they turn out?

The spirograph consists of a set of wheels and two wheels with teeth of the same size. They are made from random plastic. Wheels have 24, 32, 52, 60, 63, 72 and 80 teeth. There are 96 teeth on the inside of one ring, 144 on the outside; on the other ring there are 105 and 150 teeth respectively. Each wheel and ring has several small holes. To activate the spirograph, you need to press the ring to the paper with one hand or secure it with pins on the tablet, place the wheel inside the ring (or outside it) and align their teeth (Fig. 2). Then you should strengthen the point of the ballpoint pen in one

Fig. 1

⟦folio 35⟧

from the counter in the wheel and rotate the wheel without slipping along the ring. In this case, the tip of the pen will draw a certain curve on the paper. After a few revolutions the curve will close. We will now explain why this is so.

Let $R$ be the radius of the ring, $r$ the radius of the wheel, $\varphi$ the distance from the center of the wheel to the answer in which the handle is fixed. When the wheel is rotated, the tip of the pen will move along the sheet of paper in a certain stake area. Its outer radius is $R_{\text{внешн.}} = R - r + \varphi$, its inner radius is $R_{\text{внутр.}} = R - r - \varphi$. From the last formula it is clear that if, for example, $r = \frac{3}{4}R$, $\varphi = \frac{1}{4}R$, then the curve will no longer be in a ring, but in a circle, since in this case $R_{\text{внутр.}} = 0$.

Let there be $N$ teeth on the ring and $n$ on the ring. Suppose that after the wheel has made $K$ revolutions around the center and $k$ revolutions around the ring, it has returned to its original position, and the tip of the handle is at the starting point. In this case, the drawn curve is closed, and with further rotation of the wheel, a new curve will not be obtained - the tip of the pen will repeat the path already taken. It is easy to report that at the moment when the curve is closed, the equality

$$Kn = kN = D. \quad (*)$$

Since for any natural numbers $N$ and $n$ there are numbers $K$ and $k$ that satisfy equality (*), any curve drawn using a spirograph will turn out to be closed. Moreover, the numbers $K$ and $k$ are the smallest integers for which equality (*) holds, and $D$ is the least common multiple of the numbers $N$ and $n$. Based on this, one could calculate the LCM of two numbers $m$ and $M$: make a wheel with $m$ teeth, a stake with $M$ and, turning the wheel inside the ring until the curve closes, count how many revolutions the wheel makes around its own center (number $K$), or how many revolutions - according ring (number $k$). Then, using formula (*), the values ​​$D = \text{НОK}(m, M)$ are calculated.

Given $N$ and $n$, the shape of the curve depends on $\varphi$. In Figures 3 and 4, $N = 96$, $n = 60$, $K = 8$, $k = 5$, but at figure 3 the magnitudes $\varphi$ are greater than at figure 4. Gradually increasing or decreasing $\varphi$, that is, using different answers in the wheel, you can see how the resulting curves are deformed when the value of $\varphi$ changes.

The number $K$ can be easily determined by figure - it coincides with the number of points of the curve furthest from the center of the ring. In Figures 3 and 4, these points are lined in the order in which they are passed.

When drawing curves, it is better to do the opposite. In cases where $N$ and $n$ have few common factors (e.g. $N = 105$, $n = 72$), the wheel must make more revolutions to obtain a closed curve. To determine the moment when the curve closes, you should count the number $K$ in advance and roll the wheel around the ring so many times.

Those familiar with irrational numbers can imagine an ideal spirograph - there are no teeth on the wheel and ring, but the wheel

⟦folio 36⟧

moves around the ring without skipping
calling. Let $l$ be the circumference of the wheel, $L$ be the circumference of the ring along which the wheel moves. If the numbers $l$ and $L$ are not the same (for example, the number $l$ is rational, $L$ is irrational), then the drawn curve will never close, because for no natural numbers $K$ and $k$ the equality $Kl=kL$ corresponding to (*) cannot be satisfied. However, the mark from the tip of the pen has a finite width, and therefore after a sufficiently large number of revolutions of the wheel we will get a completely painted ring on the paper. A similar picture will arise for large coprime numbers $N$ and $n$ (for example, 105 and 52). If we assume that the trace from the tip of the pen is an ideal mathematical line, then the resulting curve for incommensurable $l$ and $L$ will be located in the corresponding annular region *densely everywhere* (that is, the trajectory of the tip of the pen approaches any point inside the region as angularly close). Similar trajectories arise in various mathematical problems and are studied, for example, in the theory of differential equations.

In cases where the value of $q$ is close to $r$, the trajectories described by the spirograph are close to known curves that have special names*). When the wheel rolls on the inside of the ring, the result is *zipoclopda*. In particular, with $N=96$, $n=24$ we get *astrode* (Fig. 5). If the wheel rolls along a ring from the outside or on another wheel, then the drawn curve is close to *epcclopde* (with $q$ close to $r$; Fig. 6). *Cardioid* (Fig. 7) is obtained by using two identical wheels. If we force the wheel to roll without slipping in a straight line, and take the value $q$ still close to $r$, then we will get a curve similar to a *cyclops*.

And in conclusion, some advice for those who want to make a spirograph themselves. The ring can be cut from thick rubber or linoleum, the wheels can be made from plexiglass, some plastic, or made from other materials that have a fairly high coefficient of friction. You just need to calculate the ratio $L:l$ in advance; for example, you can take the ratio to be 4:3, 3:1, 7:5. In the wheels, at different distances from the center, you should drill a handle rod that is somewhat responsible for the diameter.

*) More details about these curves can be read in the following issues «Kvant»: 1975, No. 8, No. 12; 1977, no. 12.
