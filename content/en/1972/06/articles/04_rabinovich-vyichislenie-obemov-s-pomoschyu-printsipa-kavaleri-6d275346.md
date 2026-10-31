---
id: 1972-6-rabinovich-vyichislenie-obemov-s-pomoschyu-printsipa-kavaleri-6d275346
issue: kvant_1972_6
year: 1972
number: "6"
title: Calculating volumes using the Cavalieri principle
authors:
  - Рабинович В. Л.
rubric: osnovnye-stati
page_first: 11
page_last: 13
page_labels: 9-11
tag: MN99
lang: en
source: kvant_digital
extraction: vision
content_sha256: 532101bb094db56cd19eb044daed164779c44cce07efa4690b5927bc6020f73e
prompt_sha256: draft-1
translated_from: content/ru/1972/06/articles/04_rabinovich-vyichislenie-obemov-s-pomoschyu-printsipa-kavaleri-6d275346.md
source_content_sha256: d64b7a3fd4a819656dfbd825dcc3b5e05111ec44c0858cb81f05afe5289d7398
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 9⟧

CALCULATION OF VOLUME
WITH THE HELP OF PRINCIAC CAVALIERI

V. L. Rabinovich

What is volume? How to calculate the volume of a specific body? Already to answer the first of these questions, even for such a “simple” case as a rectangular paralleliped, at least one of the dimensions of which is not commensurate with a fixed unit of length, one comes to use reasoning associated in one form or another with the transition to the preposition of an infinite sequence. When moving on to more complex questions - about the definition and calculation of the exchange of an arbitrary paralleliped, then an arbitrary prism, then (a very important step!) a primid, and finally, “round” bodies: cylinders, a sphere and spherical segments - we have to use more and more new transitions to limits, literally piling them on top of each other.

These arguments, on the one hand, are burdened with a lot of subtleties and difficulties, on the other hand, they seem (outwardly) to be quite “standard”. And the failure to take into account all these subtleties and twists in the school mathematics course, and the deceptive “similarity” of all these discussions about limits equally lead to the fact that they (in the discussion) often begin to look at them as inevitable ritual spells, without thinking about it and without trying to construct their true meaning and purpose. Simply skipping them is also somehow “inconvenient”, “indecent”: after all, it’s mathematics! . . .

So, isn’t it possible, at least until better times, to get rid of all this dirty talk about limits with one max? It turns out that it is very possible. To do this, it is enough to accept as a prostate (axiom) the so-called Cavalieri principle *. It is to accept, not to prove. This, of course, does not mean that this principle cannot be proven and justified at all. Moreover, reasoning about the “indivisibles”, with the help of which Cavalieri himself approached his formulation (in many ways, by the way, strikingly anticipated by Archimedes with his “method of exhaustion”), were already quite close to the methods of integral calculus of Newton and Leibniz, by means of which in our time volumes are determined “with all rigor”. But since our goal at this stage was precisely to get rid of all sorts of limits, indivisible, infinitely small, etc., then it would be wiser and more honest not to use any substitutes. After all, we know that geometry is built on the basis of axioms. So there will be one more axiom. (As we go along, we see that we actually have to use a couple more axioms, which, however, can also be perceived as definitions.)

So, we formulate the Cavalieri principle:

If, at the intersection of two bodies **) F and F₁ (see Fig. 1) planes parallel to the same plane α, figures are always obtained whose area is

*) Bonaventura Cavalieri (1598-1647) - Italian mathematician, student of Galiel.

**) By “body” we everywhere understand “something having volume”, without trying to more precisely define the words enclosed in quotation marks.

⟦folio 10⟧

in constant relation $\lambda(\lambda > 0)$:
$$S = \lambda S_1$$
The themes of these melikhs are in the same relation:
$$V(F) = \lambda(F_1)^*$$

The word “volume” here first appears not in “suggestive” reasoning, but as part of a strictly formulated sentence; Therefore, we can also understand our axiom as a definition of volume - of course, only for such bodies $F$ that for them there are corresponding $F_1$, for which the concept of volume has already been previously defined (see below).

Let us now apply Cavalieri's principles to derive formulas for the volumes of some bodies. First, however, we will have to recall that the volume of a cube whose edge is equal to one unit of length is assumed to be equal to one (such a cube is called a unit cube**).

*) In general, in the literature, the Cavalieri principle is a proposition that is a special case of the one given, when the ratio of cross-sectional areas referred to in the proposition is equal to one. However, Cavalieri himself presents and uses the principles in the indicated more general form.

**) This is the first of the additional conditions mentioned above, which can be understood either as an axiom about the volume of a unit cube, or as a definition of this volume.

Fig. 1.

Fig. 2.

a) Arbitrary signs and cylinder. First consider a rectangular paralleled with variations equal to 1, 1 and $h$ (h can be either a rational or an irrational number). Let (Fig. 2) be in the parallelend $AC_1$ $AB = AA_1 = 1$, $AD = h$. Consider a single cube $MP_1$, the base of which is located on the same plane $\alpha$ on which the parallel base $ABCD$ is located. It is easy to see that the cross-sectional areas $S_1$ and $S$ of a paralleled cube and a cube by any plane parallel to the plane $\alpha$ are in a constant ratio $h$, that is, $S_1 = h \cdot S$. Therefore, according to Cavalieri's principle
$$V(AC_1) = h \cdot V(MP_1) = h \cdot 1 = h^*$$.

Let now an arbitrary feature (or cylinder) $F$ (Fig. 3) with base area $S$ and height $h$ be given. Let us position the paralleled $AC_1$ with changes 1, 1, $h$ so that its face $ABB_1A_1(AB = 1, AA_1 = 1)$ is in the same plane $\alpha$ as the base of this feature $F$. Since $AD = h$, then both the upper bases of this sign and the paralleled $AC_1$ lie in the same plane. Then, in the section of features $F$ by any plane parallel to $\alpha$ and intersecting the feature, a figure will be obtained equal to the base of the feature. The area of ​​this figure is therefore $S$. Also the plane in section with

*) If we take as a postulate the above-mentioned special case of the Cavalieri principle at $\lambda = 1$, then instead of the just given “axiom of the unit cube” (see the previous note), we take this correspondence as the “axiom of right-angled parallelism”.

⟦folio 11⟧

parallelepiped gives a square of area 1.

The conditions of Cavalieri's principle are fulfilled. Means,

$$V(F) = SV(AC_1).$$

But we found that $V(AC_1) = h$. So,

$$V(F) = Sh.$$

6) Arbitrary parameters and cone. Let's look at a special case first. The cube $AC_1$ with edge equal to $h$ (Fig. 4) can be divided into three quadrangular parameters $A_1ABCD$, $A_1BCC_1B_1$ and $A_1DCC_1D_1$. These parameters are equal to each other. Indeed, the first parameters can be combined so that their bases (equal squares $ABCD$ and $B_1C_1CB$) and equal edges $AA_1$ and $B_1A_1$ coincide. Then the parameters will match. The equality of the last two parameters is shown similarly *). This means that the volume of each of the second parameters is less than the cube $AC_1$:

$$V(A_1ABCD) = \frac{1}{3}h^3$$

Let now be given an arbitrary parameter $F$ (or cone) with area

*) The necessary combinations of any pair of these three parameters can be realized, for example, by rotating one of the parameters about the $A_1C$ axis at an angle of 120°.

**) Here we use the last of the additional definitions (axioms): the volume of a collection of several chalks (in this case, a cube) is equal to the sum of the volume of these chalks (paramids). The equality of the volume of equal bodies (paramids) easily follows from Cavalieri’s principle.

Fig. 3.

base $S$ and height $h$. Let us position this parameter so that its base is in the same plane $\alpha$ in which the base of the quadrangular parameter $A_1ABCD$ just considered is located (we will denote it $F_1$ for brevity). We can assume that the vertices of these parameters are located on one side of the plane $\alpha$. Then, using the theorem on the section of parameters by a plane parallel to the base, it is easy to obtain that the areas of sections of both bodies by a plane parallel to the plane $\alpha$ will be related to the areas of their bases. Therefore, Cavalieri's principle can be applied:

$$V(F) = V(F_1) \cdot \frac{S}{h^2} = \frac{S}{h^2} \cdot \frac{1}{3}h^3 = \frac{1}{3}Sh.$$

c) Ball, spherical segment. Consider a hemisphere with center at $O$ and radius $R$. Let us extend the plane $\alpha$ of the great circle bounding this hemisphere and place on this plane with its base a cube with edges equal to $R$ (Fig. 5). If we separate from this cube the quadrangular parameter $BA_1B_1C_1D_1$, which has the upper vertex $B$ of the cube, and the base is the upper base of the latter, then we obtain a certain body, which we will denote by $F_1$. Let us intersect both bodies of some plane $\alpha'$, parallel to the plane $\alpha$
