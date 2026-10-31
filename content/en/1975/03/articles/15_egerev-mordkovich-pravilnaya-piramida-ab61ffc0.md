---
id: 1975-3-egerev-mordkovich-pravilnaya-piramida-ab61ffc0
issue: kvant_1975_3
year: 1975
number: "3"
title: Correct pyramid
authors:
  - Егерев В. К.
  - Мордкович А. Г.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 63
page_last: 67
page_labels: 61, 62, 64, 65
tag: O49A
lang: en
source: kvant_digital
extraction: vision
content_sha256: 7c7a32ef0fed7363c5bb0d3505d78eaa7b820d26500231609dd8591a2bbb471c
prompt_sha256: draft-1
translated_from: content/ru/1975/03/articles/15_egerev-mordkovich-pravilnaya-piramida-ab61ffc0.md
source_content_sha256: 50f9f644a6aabe83388106292ceeb28b52f6b10a212dbf1a592ac8b51b921242
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 61⟧

Correct paramid
V. K. Egerev, A. G. Mordkovich

The solution of many geometric problems has an inherent nature of artificiality, which led to the century-old German philosopher Arthur Schopenhauer reproaching geometrics for using “mousetrap proof.” Indeed, the solution of geometric problems contains few patterns and often gives the impression of a trick. It is all the more important to know that small arsenal of “standard” techniques that are nevertheless used in solving these problems. Some techniques have already been discussed on the pages of our magazine (see, for example, the article by I. A. Kushi ir “Method of an auxiliary element”, «Kvant», 1974, No. 2). This article talks about another such technique.

2. Relationship between angles in a paramid

figure 1 shows a part of a regular n-gonal paramide SABCD..., SH—height, SK—apothem. Let us introduce the following notation:

α—angle between the side edge and the plane of the base;
β—angle between the side edge and the base plane;
γ—angle between cross-cut lateral ribs;
φ—angle between cross-cut side faces.

1. "The saucepan method"
Let's start with a small parable. Andrey was explained how to boil an egg: “Remove the saucepan from the nail, pour water into it, put the egg, light the gas, put the saucepan on the gas stove and remove it 5 minutes after the water boils.” Andryusha did just that, everything worked out well. But one day we woke up in the morning, Andrei saw that water had already been poured into the pan and the gas was burning. After thinking, he turned on the gas, poured out the water and hung the saucepan on the nail, and then did as he was taught.

Despite every absurdity of such behavior, the method of returning

⟦figure⟧
| Angles | Ratios | | Angle change area | Connections between angles |
|---|---|---|---|---|
| α; φ | $\sin \alpha = \mathrm{ctg}\dfrac{\varphi}{2}\,\mathrm{ctg}\dfrac{\pi}{n}$ | (1) | $0 < \alpha < \dfrac{\pi}{2}$ | |
| α; γ | $\cos \alpha = \sin\dfrac{\gamma}{2}\Big/\sin\dfrac{\pi}{n}$ | (2) | $0 < \beta < \dfrac{\pi}{2}$ | $\gamma < \pi - 2\alpha$ |
| α; β | $\mathrm{tg}\,\alpha = \mathrm{tg}\,\beta \cdot \cos\dfrac{\pi}{n}$ | (3) | $0 < \gamma < \dfrac{2\pi}{n}$ | $\alpha < \beta$ |
| β; γ | $\cos \beta = \mathrm{tg}\dfrac{\gamma}{2}\,\mathrm{ctg}\dfrac{\pi}{n}$ | (4) | $\pi - \dfrac{2\pi}{n} < \varphi < \pi$ | |
| β; φ | $\mathrm{tg}\,\beta = \dfrac{\sqrt{2}\cos\dfrac{\varphi}{2}}{\sqrt{-\cos\varphi - \cos\dfrac{2\pi}{n}}}$ | (5) | | $\varphi > \pi - 2\beta$ |
| γ; φ | $\sin\dfrac{\gamma}{2} = \dfrac{\sqrt{-\cos\varphi - \cos\dfrac{2\pi}{n}}}{\sqrt{2}\sin\dfrac{\varphi}{2}}$ | (6) | | |

If one of these angles is known in a regular pyramid, then the other three can be found. Six ratios are shown in the table. Let's prove some of them.

(1) (α; φ). Considering triangles $LMC$ and $LMD$, we obtain

$\mathrm{tg}\dfrac{\varphi}{2} = \dfrac{CL}{LM}$, $\sin \alpha = \dfrac{LM}{LD}$. Means,

$\mathrm{tg}\dfrac{\varphi}{2}\sin\alpha = \dfrac{CL}{LD} = \mathrm{tg}\,\angle CDL =$

$= \mathrm{tg}\left(\dfrac{\pi}{2} - \dfrac{\pi}{n}\right) = \mathrm{ctg}\dfrac{\pi}{n}$.

(2) (α; γ). Considering triangles $AHS$ and $AKS$, we obtain

$\cos\alpha = \dfrac{AH}{AS}$, $\sin\dfrac{\gamma}{2} = \dfrac{AK}{AS}$. Means,

$\dfrac{\sin\dfrac{\gamma}{2}}{\cos\alpha} = \dfrac{AK}{AH} = \sin \angle AHK = \sin\dfrac{\pi}{n}$.

(3) (α; β). Considering triangles $AHS$ and $SHK$, we obtain $\mathrm{tg}\,\alpha =$

$= \dfrac{SH}{AH}$, $\mathrm{tg}\,\beta = \dfrac{SH}{KH}$. So, $\dfrac{\mathrm{tg}\,\alpha}{\mathrm{tg}\,\beta} =$

⟦column⟧

$= \dfrac{KH}{AH} = \cos \angle AHK = \cos\dfrac{\pi}{n}$.

Let us note some consequences from these formulas.

From (1) it follows that $\mathrm{ctg}\dfrac{\varphi}{2} = \sin\alpha \times$

$\times\, \mathrm{ctg}\left(\dfrac{\pi}{2} - \dfrac{\pi}{n}\right)$. But $\sin\alpha < 1$ means

$\dfrac{\varphi}{2} > \dfrac{\pi}{2} - \dfrac{\pi}{n}$ or $\varphi > \pi - \dfrac{2\pi}{n}$.

From (2) it follows that $\sin\dfrac{\gamma}{2} = \cos\alpha \sin\dfrac{\pi}{n}$.

But $\cos\alpha < 1$ means $0 < \dfrac{\gamma}{2} < \dfrac{\pi}{n}$ or

$0 < \gamma < \dfrac{2\pi}{n}$. From the same formula it follows,

$$\dfrac{\sin\dfrac{\gamma}{2}}{\sin\left(\dfrac{\pi}{2} - \alpha\right)} = \sin\dfrac{\pi}{n} < 1,$$

What

that is,

$\dfrac{\gamma}{2} < \dfrac{\pi}{2} - \alpha$ or $\gamma < \pi - 2\alpha$.

From (3) it follows that $\dfrac{\mathrm{tg}\,\alpha}{\mathrm{tg}\,\beta} = \cos\dfrac{\pi}{n} < 1$,

where does $0 < \alpha < \beta$ come from (which is generally speaking obvious).

⟦folio 62⟧

⟦folio 64⟧

Problem 6. Find $S$, knowing $a$ and $\gamma$.

The problem is easily solved using the “saucepan method”: using formulas (4) and (8), we get

$$S = \frac{na^2\, \mathrm{ctg}\dfrac{\gamma}{2}}{4}.$$

But perhaps it’s even easier to solve the problem directly:

$$S = n \cdot S_{\triangle ASB} = n \cdot \frac{1}{2}AB \cdot SK =$$

$$n \cdot \frac{1}{2}a \cdot \frac{a}{2}\mathrm{ctg}\frac{\gamma}{2} = \frac{na^2\, \mathrm{ctg}\dfrac{\gamma}{2}}{4}.$$

Problem 7. Find $S$, knowing $a$ and $\alpha$.

From formula (3) follows the relation

$$\cos\beta = \frac{\cos\dfrac{\pi}{n}}{\sqrt{\mathrm{tg}^2\alpha + \cos^2\dfrac{\pi}{n}}}$$

(check it out!). Hence,

$$S = \frac{na^2\sqrt{\mathrm{tg}^2\alpha + \cos^2\dfrac{\pi}{n}}}{4\sin\dfrac{\pi}{n}}$$

Problem 8. Find $S$, knowing $a$ and $\varphi$.

From formula (5) it follows that

$$\cos\beta = \frac{\sqrt{-\cos\varphi - \cos\dfrac{2\pi}{n}}}{\sqrt{2}\sin\dfrac{\pi}{n}}$$

(check!). Using formula (8), we obtain

$$S = \frac{\sqrt{2}\, na^2\cos\dfrac{\pi}{n}}{4\sqrt{-\cos\varphi - \cos\dfrac{2\pi}{n}}}.$$

## 5. Calculating the radius of a circumscribed sphere

Problem 9. Find $R$, knowing $a$ and $\alpha$.

As is known, it is always possible to describe a ball near a regular pyramid; its center $O$ lies at the point of intersection of the height $SH$ of the pyramid with the perpendicular

⟦column⟧

dicular $FO$ to the lateral edge, drawn through the middle $F$ of edge $AS$ (see Fig. 2). Then $\angle SOF =$
$= \angle SAH = \alpha$. We have $AS = \dfrac{AH}{\cos\alpha} =$
$= \dfrac{a}{2\sin\dfrac{\pi}{n}\cos\alpha}$; $\quad R = OS = \dfrac{FS}{\sin\alpha} =$
$= \dfrac{AS}{2\sin\alpha};$

$$R = \frac{a}{2\sin\dfrac{\pi}{n}\sin 2\alpha}. \tag{9}$$

Problem 10. Find $R$, knowing $a$ and $\beta$.

From formula (3) it follows that

$$\sin 2\alpha \cdot \frac{2\,\mathrm{tg}\,\alpha}{1+\mathrm{tg}^2\alpha} = \frac{2\,\mathrm{tg}\,\beta\cos\dfrac{\pi}{n}}{1+\mathrm{tg}^2\beta\cos^2\dfrac{\pi}{n}}.$$

Using formula (9), we obtain

$$R = \frac{a\left(1+\mathrm{tg}^2\beta\cos^2\dfrac{\pi}{n}\right)}{2\sin\dfrac{2\pi}{n}\,\mathrm{tg}\,\beta}.$$

Problem 11. Find $R$, knowing $a$ and $\gamma$.

From formula (2) it follows that

$$\sin\alpha = \frac{\sqrt{\cos\gamma - \cos\dfrac{2\pi}{n}}}{\sqrt{2}\sin\dfrac{\pi}{n}} \text{ (проверь-}$$

those!), and $\sin 2\alpha = 2\sin\alpha\cos\alpha =$

$$= \frac{\sqrt{2}\sin\dfrac{\gamma}{2}\sqrt{\cos\gamma - \cos\dfrac{2\pi}{n}}}{\sin^2\dfrac{\pi}{n}}.$$

Means,

$$R = \frac{a}{2\sin\dfrac{\pi}{n}\sin 2\alpha} =$$

$$= \frac{\sqrt{2}\,a\sin\dfrac{\pi}{n}}{4\sin\dfrac{\gamma}{2}\sqrt{\cos\gamma - \cos\dfrac{2\pi}{n}}}$$

⟦folio 65⟧

Fig. 2. Fig. 3.

Formula

$$R = \frac{\sqrt{2} \sin \frac{\varphi}{2} \mathrm{tg} \frac{\varphi}{2} \mathrm{tg} \frac{\pi}{n}}{4 \sqrt{1 - \cos \varphi - \cos \frac{2\pi}{n}}},$$

expressing $R$ through $a$ and $\varphi$, proof.

6. Calculating the radius of an inscribed ball

As is known, a ball can always be inscribed in a regular paramid; its center $O$ lies at the point of intersection of the height $SH$ of the paramid with the bisector of the angle $SKH$ (Fig. 3). Therefore, it is easiest to calculate the radius of an inscribed ball in the case when the angle $\beta$ is given; from this case we will teach.

Problem 12. Find $r$, knowing $a$ and $\beta$.

We have $r = OH = KH \cdot \mathrm{tg} \frac{\beta}{2}$;

$$r = \frac{a}{2} \mathrm{ctg} \frac{\pi}{n} \mathrm{tg} \frac{\beta}{2}. \tag{10}$$

Problem 13. Find $r$, knowing $a$ and $\alpha$.

From formula (3) it follows that

$$\mathrm{tg} \frac{\beta}{2} = \frac{\sqrt{\cos^2 \frac{\pi}{n} + \mathrm{tg}^2 \alpha - \cos \frac{\pi}{n}}}{\mathrm{tg} \alpha}.$$

From formula (10) we now obtain

$$r = \frac{a}{2} \mathrm{ctg} \frac{\pi}{n} \mathrm{tg} \frac{\beta}{2} =$$

$$\frac{a \mathrm{ctg} \frac{\pi}{n} \left( \sqrt{\cos^2 \frac{\pi}{n} + \mathrm{tg}^2 \alpha - \cos \frac{\pi}{n}} \right)}{2 \mathrm{tg} \alpha}.$$

Problem 14. Find $r$, knowing $a$ and $\gamma$.

From formulas (4), (10) we obtain

$$r = \frac{a}{2} \mathrm{ctg} \frac{\pi}{n} \cdot \frac{\sin \left( \frac{\pi}{n} - \frac{\gamma}{2} \right)}{\sin \left( \frac{\pi}{n} + \frac{\gamma}{2} \right)}.$$

Find the expression $r$ through $a$ and $\varphi$ yourself.

U right

1. (MEPhI, 1973). Find the dihedral angle between the base and the lateral face of a regular triangular paramid if the dihedral angle between the lateral faces of this paramid is equal to $\alpha$.
2. (UDN, 1973). The dihedral angles at the lateral edges of a regular 4-gonal paramid are equal to $\alpha$. Find the dihedral angles at the lateral edge equal to $2\alpha$. Find the volume of the paramid.
4. (USU, 1973). The height of a regular triangular paramid is $h$, and the distance from the base of the height to the side edge is $a$. Determine the dihedral angle between the lateral faces of the paramid.
5. (MATI, 1973). Each of the equal angles of the lateral face of a regular hexagonal paramid is equal to $\varphi$. The distance from the middle of the height to the side edge is $l$. Find the height of the paramid.
6. (MAI, 1973). The height of a regular tetragonal paramid is $h$, and the plane angle between adjacent lateral faces is $\varphi$. Find the lateral surface area.
7. (UDN, 1973). The side of the base of a regular tetragonal paramid circumscribed about a ball of radius $R$ is equal to $a$. Find the complete surface of the paramid.
8. (NSU, mechanics, 1969). The dihedral angle at the lateral edge of a regular 4-gonal paramid is equal to $\alpha$, the radius of the inscribed ball is $R$. Find the complete surface of the paramid.
9. (YAPI, 1973). A regular tetragonal paramidian is inscribed in a ball of radius $R$, whose plane angle at the vertex is equal to $\alpha$. Find the volume of the paramid.
10. (From readers’ letters) Find the volume of the paramid $SABC$, if the height is inclined to the base plane at an angle $30^\circ$, $\triangle ABC$ is equilateral, a circle of radius $r$ is inscribed in it, and $SC = OC$ and $SO \perp BA$.

G. M-va
