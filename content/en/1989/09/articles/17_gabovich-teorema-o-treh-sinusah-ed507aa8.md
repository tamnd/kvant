---
id: 1989-9-gabovich-teorema-o-treh-sinusah-ed507aa8
issue: kvant_1989_9
year: 1989
number: "9"
title: Three Sine Theorem
authors:
  - Габович И. Г.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 73
page_last: 74
page_labels: 71-72
tag: WNEE
lang: en
source: kvant_digital
extraction: vision
content_sha256: 66070c574f86f64db1834af1ebaa3f010adb145a8688fab04f37aab6c4349eb4
prompt_sha256: draft-1
translated_from: content/ru/1989/09/articles/17_gabovich-teorema-o-treh-sinusah-ed507aa8.md
source_content_sha256: a787a203ee6bca2086051951676918cf89109546254c61b230eb9532b352a92b
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 71⟧

Teorema
about three sins

I. G. GABOVICH

In many stereometric problems, it is often necessary to determine the angle between a straight line and a plane. This is conveniently done using the three sinus theorem, which you will learn if you solve the following problem.

1. In one of the faces of a dihedral angle of magnitude α, a straight line is drawn that makes an angle β with the edge of this angle. Determine the angle that this straight line makes with the other edge.

Solution. Let ∠ABC be the linear angle of a given dihedral angle equal to α (Fig. 1) and let ∠ADB=β. Let's lower the pendant AC to the other side of the corner; then ∠ADC is original. Let us denote ∠ADC by γ and set AD=x. Triangle ABD is a right triangle, so AB=x sin β. Triangle ABC is also a right triangle, so AC=AB sin α = x sin α sin β. Finally, from triangle ADC it is found that AC=x sin γ. So,

sin γ = sin α sin β.

This is the theorem about three sinus, which is connected in solving problems.

Fig. 1.

⟦folio 72⟧

2. In a regular triangular prism $ABCA_1B_1C_1$ the base is equal to the height. Find the angle between diagonal $AB_1$ and plane $AA_1C_1C$.

Solution. The dihedral angle at edge $AA_1$ is $\frac{\pi}{3}$ (Fig. 2). Diagonal $AB_1$ makes an angle with edge $AA_1$ equal to $\frac{\pi}{4}$. Let $\gamma$ be the magnitude of the desired angle. Then, by the theorem of three sines

$$\sin \gamma = \sin \frac{\pi}{3} \sin \frac{\pi}{4} = \frac{\sqrt{3}}{2} \cdot \frac{\sqrt{2}}{2} = \frac{\sqrt{6}}{4}.$$

So, $\gamma = \arcsin \frac{\sqrt{6}}{4}$.

Here's the last task.

3. The angle between the plane of the square $ABCD$ and some plane m is equal to $\alpha$, and the angle between the sides $AB$ and the same plane is $\beta$. Find the angle between sides $AD$ and plane $\tau$.

Solution. We will assume that the vertex $A$ of the square lies on the edge of the dihedral angle under consideration - see figure 3. Angles $BFB_1$ and $DED_1$ are linear angles of this dihedral angle: $\angle BFB_1 = \angle DED_1 = \alpha$. The segments $AB_1$ and $AD_1$ are the projections of the sides $AB$ and $AD$ onto the plane $\tau$. According to the conditions, $\angle BAB_1 = \beta$.

Let $\angle BAF = \varphi$ and $\angle DAD_1 = \gamma$. By the theorem about three sines $\sin \beta = \sin \alpha \sin \varphi$, we open $\sin \varphi = \frac{\sin \beta}{\sin \alpha}$. Hence,

$$\cos \varphi = \sqrt{1 - \frac{\sin^2 \beta}{\sin^2 \alpha}} = \frac{1}{\sin \alpha} \sqrt{\sin^2 \alpha - \sin^2 \beta} =$$

Obviously $\angle DAE = 90^\circ - \varphi$. Therefore, from the theorem of three sines it follows

$$\sin \gamma = \sin \alpha \sin (90^\circ - \varphi) = \sin \alpha \cos \varphi = \sqrt{\sin(\alpha + \beta) \sin(\alpha - \beta)}.$$

So,

$$\gamma = \arcsin \sqrt{\sin(\alpha + \beta) \sin(\alpha - \beta)}.$$

The following problem was proposed for the entrance exam to MIPT.

5. The sides $AB$ and $AC$ of an equilateral triangle are located respectively in the faces $P$ and $Q$ of the acute dihedral angle $\varphi$. Side $AB$ forms an acute angle $\alpha$ with the edge of the dihedral angle. Find the angle between the plane $ABC$ and the face $Q$.

Solution. Let's make a drawing - figure 4. The vertex $A$ of an equilateral triangle is adjacent to the edge $MN$, the sides $AB$ and $AC$ lie in the faces $P$ and $Q$; according to the condition, $\angle BAM = \alpha$. Let's draw $BO \perp Q$ and connect the points $O$ and $A$. Let us denote $\angle BAO$ by $\varphi$, and by $\omega$ we denote the desired angle that the plane $ABC$ forms with $Q$.

Applying the three-sine theorem twice, we get

$$\sin \gamma = \sin \varphi \sin \alpha$$

And

$$\sin \gamma = \sin \omega \sin \frac{\pi}{3}.$$

So,

$$\sin \omega = \frac{2}{\sqrt{3}} \sin \varphi \sin \alpha$$
