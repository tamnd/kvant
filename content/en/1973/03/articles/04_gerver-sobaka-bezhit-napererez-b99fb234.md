---
id: 1973-3-gerver-sobaka-bezhit-napererez-b99fb234
issue: kvant_1973_3
year: 1973
number: "3"
title: The dog runs across
authors:
  - Гервер М. Л.
rubric: osnovnye-stati
page_first: 17
page_last: 18
page_labels: 15-16
tag: Q20Z
lang: en
source: kvant_digital
extraction: vision
content_sha256: 6a4fc49f34e8d2961810e85033662084f3500e5d119a02b3ccf14f3e6e2001da
prompt_sha256: draft-1
translated_from: content/ru/1973/03/articles/04_gerver-sobaka-bezhit-napererez-b99fb234.md
source_content_sha256: 921f0b2c1ffd8c1a1f3eea27e4f40bb91e3c8e369ca57ef84aa5e477267ba0ea
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 15⟧

The dog is beating in the wrong direction

M. L. Gerver

Do you remember in «Kvant» No. 2 for 1973 there was a note “About the fox and the dog”? The fox walked along a straight line l at a constant speed, and the dog walked straight at the fox with the same speed from some point C₀. The question was asked at what C₀ the dog will kill the fox.

The note proved that the fox always runs away from the dog, except for the only case when C₀ is located on the straight line l, in front of the fox.

“Okay,” the reader might say after reading the note, “all this is good, but the dog is very stupid!” Bezkala would be right...》

§ 1. Statement of the problem

Okay, the dog can take a path like an angle, not necessarily straight towards the fox. But then the fox does not live in a straight line, but as he wants. The speeds of the fox and the dog are still assumed to be equal in magnitude. And we also need to assume that everything will happen in a fenced area *).

If we change the conditions this way, then we have a method for the famous chase problem, invented by P. Rado. Only in Rado's problem were foxes and dogs paired with a lion and a man. In the book of the English mathematician J. Littlewood “Mathematical Mixture” this problem is formulated as follows: “A lion and a man, located in a fenced round arena, have the same

*) Otherwise, if the initial positions of the fox and the dog are L₀ and C₀, then the fox will simply run in a straight line C₀Л₀ from C₀.

maximum speed. What strategy should a lion follow in order to be confident in his meal?》 An ingenious, but too bloodthirsty formulation - so we will call the participants in the chase, as before, a dog and a fox.

At first glance, it seems that the fox cannot be saved if the dog chooses the following strategy. First, she takes a place in the center of circle O, and then lies down so that she is always at radius OL, while trying to get as close as possible (as speed allows) to the fox. It’s as if the fox has no choice but to run around in a circle (she shouldn’t run into the dog herself!). What happens in this case can be seen from figure 1.

When the dog occupied center O, the fox was at point L₀. Let us denote by A₁ a point on the circle such that the angle A₀OL₁ = π/2. On the segment OL₁ we will construct, as on the diameter, an auxiliary circle s. We denote the original (twice as large) circle as S. Let the fox run from L₀ to L₁ along the circle S, and the path L is an arbitrary point on the arc L₀L₁, and C is the intersection point of the radius OL and the circle s. Then the arcs L₀L and OC have (check this!) the same length. Thus, the dog (guided by the chosen strategy) will run from O to L₁ along the circle s; at point L₁ she appears as a fox.

An unexpected change of direction to the opposite will not help the fox: if the fox runs to point A (Fig. 2), and then rushes back to point A₂, then the dog (in accordance with

⟦folio 16⟧

its strategy) will run from $C$ to $\ell_2$ along an arc symmetrical to $C\ell_1$ relative to the radius $O\ell$.

So, the only chance for salvation for the face is with soy from the circle $S$. Towards the dog? This seems pointless, and it must have been believed for a time that the fox could not escape the position.

Relatively recently, Professor A. S. Beznikovich refuted this misconception. Below we present its solution, first in the case when the dog adheres to the radius $O\ell$, and then in the case of completely arbitrary behavior of the dog. In both cases, the fox does not need to immediately run into the circle. It must retreat from some inner point of the circle very gradually, changing direction many times, along an intricate spiral path.

§ 2. Two sums

When presenting the solution, we will construct broken lines consisting of an infinite number of increasingly shorter links. It will be necessary that these broken lines have an infinite length, but fit entirely inside the circle. In order not to overdo the exposition later, let us carry out some calculations in advance. Let's write down two amounts:

$$L_n = \frac{1}{2} + \frac{1}{3} + \dots + \frac{1}{n},$$

$$K_n = \frac{1}{2^2} + \frac{1}{3^2} + \dots + \frac{1}{n^2}.$$

How do they behave as $n$ increases? They increase - this is clear (because all new positive terms are added). But will they increase indefinitely or remain below a certain number? It turns out that the first sum grows without limit as $n$ grows, and the second sum grows without limit for any $n$ less than 1.

Proof
1. Let's use the inequalities

$$\frac{1}{3} + \frac{1}{4} > \frac{1}{4} + \frac{1}{4} = \frac{1}{2},$$

$$\frac{1}{5} + \frac{1}{6} + \frac{1}{7} + \frac{1}{8} > \frac{1}{8} + \frac{1}{8} + \frac{1}{8} +$$

$$+ \frac{1}{8} = \frac{4}{8} = \frac{1}{2},$$

$$\frac{1}{9} + \dots + \frac{1}{16} > \frac{8}{16} = \frac{1}{2}$$, etc.

Hence $L_4 > 1$, $L_8 > \frac{3}{2}$, $L_{16} > 2$ and in general for $n = 2^k$, $L_n > \frac{k}{2}$. If $k$ is equal to two million, then $L_n$ is greater than a million. If $k = 2 \cdot 10^9$, then $L_n$ is greater than a billion, etc. In general, whatever number $N$ is taken, there is a $n$ such that $L_n > N$ (it is enough to put $n = 2^2M$, where $M$ is a natural number, greater than $N$, for $m > n$ the inequality $L_m > N$ is fulfilled even more so). So, $L_n$ increases without limit as the number $n$ increases.

2. Let us prove that $K_n < 1$ for any $n$.

Let's calculate the sum $S_n = \frac{1}{2 \cdot 1} + \frac{1}{3 \cdot 2} + \dots$

$$\dots + \frac{1}{n(n-1)}.$$

Since $\frac{1}{m(m-1)} = \frac{1}{m-1} - \frac{1}{m}$, then $S_n = \left(1 - \frac{1}{2}\right) + \left(\frac{1}{2} - \frac{1}{3}\right) + \dots + \left(\frac{1}{n-1} - \frac{1}{n}\right).$

Opening the brackets and rearranging the terms, we get $S_n = 1 + \left(-\frac{1}{2} + \frac{1}{2}\right) + \left(-\frac{1}{3} + \frac{1}{3}\right) + \dots + \left(-\frac{1}{n-1} + \frac{1}{n-1}\right) - \frac{1}{n} = 1 - \frac{1}{n}$.

Since $\frac{1}{m^2} < \frac{1}{m(m-1)}$, then $K_n < S_n$. So, for any $n$

$$K_n = \frac{1}{2^2} + \dots + \frac{1}{n^2} < 1.$$

Consequence. Let $O$ be the center of a circle of radius $r$. $\ell_0$ is a point at a distance of $r_0$ from the center, $r_0 < r$. Let's put $a = \sqrt{r^2 - r_0^2}$ and construct the broken line $L$ like this (Fig. 3): $\ell_0\ell_1 = \frac{a}{2}$, $\ell_0\ell_1 \perp O\ell_0$; $\ell_1\ell_2 = \frac{a}{3}$,

Fig. 3.
