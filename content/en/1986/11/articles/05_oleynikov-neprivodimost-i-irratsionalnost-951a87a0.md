---
id: 1986-11-oleynikov-neprivodimost-i-irratsionalnost-951a87a0
issue: kvant_1986_11
year: 1986
number: "11"
title: Irreducibility and irrationality
authors:
  - Олейников В. А.
rubric: osnovnye-stati
page_first: 14
page_last: 18
page_labels: 12, 13, 14, 16
tag: YEUB
lang: en
source: kvant_digital
extraction: vision
content_sha256: b16e2882e35d86d6202683ead68ac7a14a996139c016d6b4d5179a6adc3de24e
prompt_sha256: draft-1
translated_from: content/ru/1986/11/articles/05_oleynikov-neprivodimost-i-irratsionalnost-951a87a0.md
source_content_sha256: fc729adbf30638d10e1cddf88b058f6e8c8b1376397760651465ae4bed77b513
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 12⟧

Irreducibility and irrationality

V. A. OLEINIKOV

In the last issue the author talked about many
centuries-old history of irrational radicals
and non-driven polynomials, about the sign
Eisenstein. Here we will talk about achieving
development of the 20th century in this area, but more
visual geometric language.

Created at the turn of the XIX and XX
centuries of algebraic number theory
became a new incentive for studying
non-driving polynomials. The algebraic number α is simply a co-
polynomial with integer coefficients
in cents:

$$P(\alpha) = a_0 + a_1\alpha + \ldots + a_n\alpha^n = 0.$$

⟦folio 13⟧

All radicals that we looked at in the previous article are algebraic numbers. However, the concept of an algebraic number is much broader: even at the beginning of the last century, P. Ruffini (1765-1822) and N. G. Abel (1802-1829) showed that not every equation of degree above the fourth is solvable in radicals. Algebraic numbers, thus, do not exhaust irrational radicals and rational numbers.

But these algebraic numbers are closely related to irreducible polynomials. Namely, any algebraic number is the root of a unique (up to a numerical factor) irreducible polynomial. This follows from THEOREM («Kvant» No. 10, p. 7).

The property of irreducibility has become the subject of close attention of many outstanding mathematicians. Along with the search for general properties (such as in THEOREM), researchers were haunted by Eisenstein's sign. It was felt that behind this sign there was some general principle hidden, the identification of which makes it possible to obtain new, more general signs. This is exactly what it turned out to be. Further progress here is connected with the possibility of translating the property of irreducibility into the language of geometric images. The foundation of this language was laid by Vlik Newot 200 years before the events described and bears his name.

Newton's diagram

To construct a Newoton diagram of a polynomial $P(x)$ given a prime $p$ it is necessary:

1) OKM coordinate plane (OK is the horizontal axis and OM is the vertical axis);
2) ruler, nails, hammer;
3) a little patience.

Because first the base is applied - each year $a_k x^k$ from $P(x)$ is assigned a point with coordinates $(k; l)$; $l$ is the most power of $p$ at which $a_k$ is divisible by $p^l$. The set of all such points $(k=0, 1, ..., n)$ is the basis of the diagram.

On figure 1 is the basis of the polynomial $P(x) = 12 + 2x + 4x^2 + x^4 + x^5 + 2x^6 + 4x^7$

at $p=2$. The free term $a_0$ is divisible by $p^2$, but is no longer divisible by $p^3$ - we have the point (0; 2), $a_1$ is divided by $p$ - the point (1; 1), $a_2$ gives the point (2; 2).

Attention! If $a_k=0$, then we do not apply the base point at all.

In our case, $a_3=0$ does not give a base point.

If $a_k$ is not divisible by $p$, then $l=0$ and point $(k; 0)$ falls on the OK axis.

In our case, $a_4$ and $a_5$ are not divisible by $p$, $a_6$ is divisible by $p$, $a_7$ is divisible by $p^2$ (see Fig. 1).

We will assume that, together with the leading coefficient $a_n$ of the polynomial $P(x)$, the free term $a_0$ is also non-zero. Otherwise, $P(x)$ is always given (prove it!) and therefore is not interesting to us. Thus, at least two points will be plotted on the OKM plane:

the starting point of the base is (0; 2) and its ending point is (7; 2)

And now the diagram (Fig. 2). We take a hammer and knock out nails at all points of the base, then place a vertical ruler against the nail driven into the starting point. We rotate it counterclockwise until it rests on another base nail (we have (1; 1)). Connecting these points with a segment, we get the first link of the diagram. To obtain the next link, you need to rotate the ruler around the second nail (1; 1) until it meets a new base point.

We rotate the ruler further and apply the remaining links until, finally, we add to the end point of the base and get the last link.

Newton's diagram is ready and shown on figure 2. It appears as a concave upward broken line and always has at least one link.

⟦folio 14⟧

Construct your own Newton diagram for the polynomial
$$Q(x) = 16 + 4x + 8x^2 + 2x^3 + 8x^6$$
simply $p = 2$.

Extra points (for us - (2; 2)) should not displace the reader - in any sustainable production one cannot do without waste.

About the links. They come in three varieties:

Compound, simple, applied

A link in a Newton diagram is called simple if, apart from its ends, there are no other points with integer coordinates. Otherwise, if there is one inside a link, we will call it composite (Fig. 3). Further, we call a simple link applicable if the length of its projection on the horizontal axis OK is equal to one.

That's it. Familiarity with the figurative language of irreducibility is legitimate. It's time to start speaking it. We are rewarded for all our efforts in producing Newton's diagram

Dumas sign

If for some prime $p$ the diagram of the polynomial $P(x)$ consists essentially of one simple link, then such a polynomial is irreducible.

Gistav Dumas lived in Switzerland and was actively involved in the problem of irreducibility at the beginning of this century. He obtained this sign in 1906.

The Dumas sign allows... to draw the Eisenstein sign,

understand it more deeply and remember it.

According to the Eisenstein criterion, all coefficients of the polynomial $P(x)$, except the old one, are divisible by $p$, and the free term $a_0$ is divisible by $p$ and not divisible by $p^2$. This situation is reflected by figure.

The 20th century does not tolerate stops *) and sadness about missed opportunities.

Signs, signs, signs...

At figure 4 there is another sign.

Enclosed in verbal form, it acquires “greater weight”:

If for a polynomial $P(x)$ of odd degree $2n+1$ one can specify a prime number $p$ such that the leading coefficient $a_{2n+1}$ is not divisible by $p$, and all other coefficients
$a_k$ are divided into $p$, $k=0, 1, ..., 2n$, but additional coefficients
$a_k$ with $k=0, 1, ..., n$ are also divisible by $p^2$, and the free term
$a_0$, divisible by $p^2$, is not divisible by $p^3$, then such a polynomial $P(x)$ is irreducible.

The Dumas sign is not exhausted! Anyone can become the owner of their own sign, raising the end of the link higher and higher and making sure that it remains simple.

The conclusion is obvious: mass production of traits is a promising and at the same time absolutely safe business**).

Irrationality again

The average abundance of signs of irreducibility also found a place for the sign of irrationality (proof in the Appendix on p. 16).

If for some prime $p$ the diagram of the polynomial $P(x)$ does not contain applied links (composite partitions into primes), then among its roots there cannot be rational ones.

*) The slow-witted reader will find something about the proof of Dumas’s sign in the Appendix on p. 16.
**) But it is unlikely to bring us Eisenstein’s laurels.

⟦folio 16⟧

The algorithmic direction originated during the time of L. Kronecker (1823-1891), a famous German mathematician, when the most accurate (but not the fastest) way was invented to find out whether a given polynomial is reducible or not (very similar to the one discussed in our first example: p. 15). Enriched with ideas of half-baked signs, this direction is gaining momentum. Most recently (in 1982), it was expressed as a masterpiece by the masters of the Dutch school (A. Lenstra, G. Lenstra, L. Lovas) called “The Reduced Basis Algorithm,” which resolved the speed issue in principle.

The gathering of a turbulent era echoed loudly in the silence of the office and, in the end, forced the irreducible polynomial to serve man. He works in allebraic coding theory, and it is possible that error-correcting codes helped identify problems in the display of telecasts from the Mexican World Cup this summer. And in the theory and practice of random processes, the irreducible polynomial creatively stands guard over state secrets, turning them into pseudo-random scenes and protecting them from the sensitive ear.

The first step has been taken into the country of irreducible polynomials - we have become acquainted with its recognized leaders. But its other representatives - both known and unexplored - remained behind the scenes. The country of irreducible polynomials is full of mysteries, and every new step into it gives rise to new questions.

Application

Here we present a general attempt to prove Dumas's sign. But first, disassembly and assembly. Newton's diagram provides important information about the polynomial $P(x)$. It is convenient to store it in disassembled form.

Disassembly rule. Let's break the diagram into links, draw arrows at the end and intersect them parallel to ourselves (like vectors) at the starting point (Fig. 8). So it turns out

Fig. 8.

connective of a polynomial by prime $p$. If the base point lies inside the link (we have point (6; 1) on the last link), then the link should not be broken at this point.

Assembly rule. Moving upward (counterclockwise), we lay out the connection vectors one after another (see Fig. 8). So: A given Newton diagram corresponds to exactly one connective, and from a given diagram it can be reconstructed uniquely.

It remains to note that the location on the OM axis of the point of application of the connection does not play a significant role. By multiplying $P(x)$ by a suitable power $p'$ (which does not change the irreducibility property), one can arbitrarily move the entire diagram, and with it the starting point, along the OM axis.

Dumas's theorem. The product connective $P(x)Q(x)$ is the union of the connective connectors $P(x)$ and $Q(x)$ (Fig. 9).

Fig. 9.

Here $Q(x)=b_0+b_1x+\dots+b_mx^m$ is another polynomial of some kind ($Q(x)$ with pages 14 is also suitable). Its base, diagram and link are red.

Dumas' theorem shows how, knowing the diagrams of the polynomials $P(x)$ and $Q(x)$ from the same prime $p$, construct a diagram of their product. To do this, you should superimpose bundles of components on top of each other, aligning their starting points, and then build a broken line according to the assembly rules (Fig. 10).

Fig. 10.

Addition. If in the connection of the product $P(x)Q(x)$ two links partially or completely coincide, then one of them should be pulled out of the connection and placed after the other.

The secret of Dumas's prism is now simple - if $P(x)$ is reducible, then by Dumas' theorem its connective always consists of either several links or one, but then it is indispensable (see Addition again).

To prove the principle of the ingredients theorem THEOREM («Kvant» No. 10, p. 7), write the diagram of linear motion (it consists of exactly one primitive link) and derive the statement from Dumas’ theorem:

If all simple connections have a projection onto the OK axis of length > k, then all divisors of the polynomial $P(x)$ have degrees > k.

The proof of Dumas' theorem is based on the fact that the multiplication of the polynomial $P(x)$ by one $b_kx^k$ corresponds on the RCM plane to the transfer of the basic $P(x)$ to a vector with coordinates $(k; l)$, where $(k; l)$ is the point of the basis $Q(x)$, corresponding uniquely $b_kx^k$. Further considerations (quite elementary) were not included in the scope of this article and we omit them.
