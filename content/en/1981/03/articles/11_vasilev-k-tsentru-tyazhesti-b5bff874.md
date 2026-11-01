---
id: 1981-3-vasilev-k-tsentru-tyazhesti-b5bff874
issue: kvant_1981_3
year: 1981
number: "3"
title: Toward the center of gravity
authors:
  - Васильев Н. Б.
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 35
page_last: 35
page_labels: "33"
tag: 1BIJ
lang: en
source: kvant_digital
extraction: vision
content_sha256: 28a4ef26f431ef0bd8473e01cb9313f945b883ad3a8a932313f60da1656d3b5b
prompt_sha256: draft-1
translated_from: content/ru/1981/03/articles/11_vasilev-k-tsentru-tyazhesti-b5bff874.md
source_content_sha256: 984095cf853260ae74d95c3e4045646c4ebf2a0e174ebaa936dca06edcf5892a
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 33⟧

Toward the center of gravity

In the first case
$$\frac{I_{(1)}}{I_0} = 1 + \frac{L_1}{L_2}.$$
The energy of the system at the end of the process in this case is equal to
$$E_{(1)} = \frac{L_2 I_1^2}{2} = \frac{L_1 + L_2}{2} I_0^2 \left(1 + \frac{L_1}{L_2}\right) = E_0 \left(1 + \frac{L_1}{L_2}\right),$$
where
$$\frac{E_{(1)}}{E_{(0)}} = 1 + \frac{L_1}{L_2}.$$
In the second case
$$\frac{I_{(2)}}{I_0} = 1 - \frac{L_1}{L_2}.$$
$$E_{(2)} = \frac{L_2 I_2^2}{2} = \frac{(L_2 - L_1)^2}{2 L_2} I_0^2,$$
$$\frac{E_{(2)}}{E_0} = \frac{(L_2 - L_1)^2}{L_2 (L_1 + L_2)}.$$
P. Zubkov

Toward the center of gravity

How does a system of identical parts behave, the rules of movement of each of which depend only on a small number of axles? Such questions arise in many mathematical models of physical, chemical, and biological objects, and answers to them, as a rule, are very difficult to obtain. In this note we will solve one problem of this type (M604 from the Problem Book «Kvant»), where the rules of particle motion are expressed by lines and functions, which allows us to obtain a simple answer: the particles merge towards a common center of gravity.

Problem formulation
a) Andrey, Victor, Sergey, swimming under water, simultaneously choosing at points $A_0, B_0, C_0$ and immediately dived again, and Andrey decided to swim a third of the way to Victor in a minute, Victor - a third of the way to Sergey, Sergey - a third of the way to Andrey. A few minutes later they chose again (points $A_1, B_1, C_1$ - see Fig. 1) and decided to repeat this maneuver - already in half a minute; then in a quarter of a minute, etc.

Where and when will they meet?
b) Inside a sphere of radius 1 km there are a million points numbered from 1 to a million. What second simultaneously does each point move to the next numbered 1/3 of the distance to this point; the last point of the exact same moves towards the first. Prove that after some time all points will be inside a certain sphere of radius 1 cm.

Solution to problem a)
Let us prove that all points $A_k, B_k$ and $C_k$ tend in the limit to the center of gravity. Q triangle - the point of intersection of its medians; in this sense, we can say that Andrey, Victor and Sergey will meet in $1 + \frac{1}{2} + \frac{1}{4} + \frac{1}{8} + \ldots = 2$ minutes at point $Q$ (although, of course, even the dolphins would not be able to turn and tumble as quickly as our swimmers do at the end of the second minute).

Taking $Q$ as the origin of coordinates and using the vector notation of the transformation $(A_k, B_k, C_k) \rightarrow (A_{k+1}, B_{k+1}, C_{k+1})$.

As is easy to see (Fig. 2), for each $k = 0, 1, 2, \ldots$
$$\vec{Q}A_{k+1} = \frac{2\vec{Q}A_k + \vec{Q}B_k}{3},$$
$$\vec{Q}B_{k+1} = \frac{2\vec{Q}B_k + \vec{Q}C_k}{3},$$
$$\vec{Q}C_{k+1} = \frac{2\vec{Q}C_k + \vec{Q}A_k}{3}.$$
From these formulas it follows that the point $Q$ is the common center of gravity of all triangles $A_k B_k C_k$: $\vec{Q}A_k + \vec{Q}B_k + \vec{Q}C_k = \vec{0}$ (Fig. 3).

Moreover, the transformation $L^2 = L \cdot L$, as can be seen from the formulas
$$\vec{Q}A_{k+2} = \frac{4\vec{Q}A_k + 4\vec{Q}B_k + \vec{Q}C_k}{9} = -\frac{\vec{Q}C_k}{3},$$
$$\vec{Q}B_{k+2} = -\frac{\vec{Q}A_k}{3},$$
$$\vec{Q}C_{k+2} = -\frac{\vec{Q}B_k}{3},$$
— prepared with coefficient $(-1/3)$ and center $Q$ (see Fig. 1). Thus, if triangle $A_0 B_0 C_0$ lies in a circle of radius $R$ centered at point $Q$, then triangle $A_{2k} B_{2k} C_{2k}$ and all subsequent triangles will be
