---
id: 1975-5-resheniya-zadach-m286-m290-f296-f298-d5bfbc7a
issue: kvant_1975_5
year: 1975
number: "5"
title: Solutions to problems M286—M290; F296—F298
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 54
page_last: 58
page_labels: 52-56
tag: XTGK
lang: en
source: kvant_digital
extraction: vision
content_sha256: 1d8060d3cb799cdb461988d644f8e05c71d63e5f620cba2d39f9a102b4ac5399
prompt_sha256: draft-1
translated_from: content/ru/1975/05/articles/10_resheniya-zadach-m286-m290-f296-f298-d5bfbc7a.md
source_content_sha256: 7ce9720b6e36f153a1fc551ba6c5312b14315b73503f6c92e22c3d115ce6e038
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 52⟧

Problem solutions

M286. There are N points on the plane. Let's mark all the midpoints of the segments with ends at these points. What is the smallest number of points on the plane that can be displaced?

Let's consider as many distances as possible between a given N points and choose the largest among these distances - let this be the distance between some two points A and B. Let's connect points A with the remaining N - 1 points; we get N-1 segments. The midpoints of these segments are different and all lie inside or on the boundary of a circle centered at point A of radius $\frac{1}{2} |AB|$ (Fig. 1).

Similarly, by connecting points B with the remaining N-1 points, we obtain N-1 swollen points (midpoints) located inside or on the border of a circle of the same radius with a center at point B.

The two circles constructed have only one point - the middle of the segment AB. Consequently, there are always at least 2 (N-1) - 1 (since we count the midpoint of the segment AB twice) swollen midpoints, that is, at least (2N-3) swollen points.

Let us show that 2N—3 is the smallest number of swollen points. Let the given N points lie on the same line, and the distances between neighboring points are the same (Fig. 2). It is easy to see that in this case the number of swollen points - middles (on figure 2 these are red points) is equal to (N-2) + N-1 = 2N-3. Thus everything is proven.

In conclusion, we invite readers to think about the following problem. For what N can N points be placed on the plane so that they do not lie on the same straight line and so that the number of swollen midpoints of segments with ends at these points is equal to 2N-3?

S. V. Konyazin

M287. Is there a sequence of natural numbers such that any smallest number 1, 2, 3,... can be represented as the difference of two numbers in this sequence in a unit way?

Such a sequence exists. Let us briefly explain how to build it.

Suppose we have constructed a finite sequence with the following properties:

1) all pairwise differences between members of this sequence are different;
2) the numbers 1,2,..., k can be represented as the difference of its two terms;
3) the number k+1 cannot be represented as the difference of its two terms.

Let the maximum term of this sequence be equal to M. Let us now “add” this sequence: add to it the numbers 2M and 2M+k+1. Check for yourself that the new sequence satisfies property 1.2 (with the replacement of k by k+i, where i is some natural number, depends on the first present of the sequence, i≥1) and property 3 (with the replacement of the number k+1 with the number k+i+1). Applying the description “adding,” for example, to the numbers 1,2, we obtain an infinite sequence that satisfies the conditions of the problem.

L. G. Limanov

⟦folio 53⟧

**M288.** *Scientists, including friends, gathered at the congress. It turned out that no two scientists who have an equal number of friends at the congress have mutual friends. Prove that there is a scientist who has exactly one friend.*

**M289.** *N weights, each weighing an integer number of grams, are arranged into K piles of equal weight. Prove that it is possible to remove one of the weights in at least K different ways so that the remaining (N - 1) weights can no longer be divided into K piles of equal weight.*

⟦figure⟧
Fig. 3.

**M290.** *For what n does there exist a closed disjoint broken line of n links such that any straight line containing one of the links of this broken line contains at least one more link?*

⟦column⟧

Let's take scientist $A$, whose number of friends is the maximum (if there are several such scientists, let's take any of them); let's denote this number by $N$. If none of scientist $A$'s $N$ friends has exactly one friend, then since scientist $A$ has the maximum number of friends, each of his friends can have $2, 3, \ldots, N$ friends—a total of $N-1$ possibilities. Since the number of friends of scientist $A$ is equal to $N$, it means that two of the friends of scientist $A$ have an equal number of friends and, in addition, a common friend - scientist $A$. But this contradicts the conditions of the problem, and, therefore, at least one of the scientists (friends of the scientist $A$) has *exactly one* friend.

*WITH. Landau*

◆

Let's take two boxes and arrange our weights in them so that the first box contains less than $K$ weights. We will arrange the weights as follows.

First, let's take weights whose weights are not divisible by $K$. If there are less than $K$ such weights, then put them in the first box and move on to the next step. If there are more such weights $K$, then we put all the weights in the second box.

In the first case, we take those weights whose weights are divisible by $K$, but not divisible by $K^2$. If they fit in the first box, then put them there; if not, then put all the weights that are not in the first box in the second.

If the first case occurs again, then we take those weights whose weights are divisible by $K^2$, but not divisible by $K^3$, and so on. Since there are at least $K$ weights in total, some of the weights will definitely end up in the second box. Let the first group of weights that do not fit in the first box be weights whose weights are divisible by $K^r$, but not divisible by $K^{r+1}$. The second box will contain those weights whose weights are divisible by $K^r$, and the first box will contain those whose weights are not divisible by $K^r$.

According to the conditions of the problem, the weights can be divided into $K$ groups of equal weight. Since there are less than $K$ weights in the first box, all $K$ groups cannot be represented in it, which means that there exists a group, all of which are in the second box. Consequently, the total weight of this (and therefore each) group is divided by $K^r$. Since we have a total of $K$ groups of equal weight, the total weight of the weights is divided by $K^{r+1}$.

Now suppose that we removed some weight, and the remaining weights could be divided into $K$ groups of equal weight. As before, we find that the sum of the weights of the remaining weights is divided by $K^{r+1}$.

The weight of the weight that we removed is equal to the difference in the total weights of all the weights and the remaining weights; therefore, the weight of this weight is divided by $K^{r+1}$ (note that $r$ may turn out to be zero; this corresponds to all the weights ending up in the second box, leaving the first empty). This means that if we removed a weight whose weight is not divisible by $K^{r+1}$, then the remaining weights could not be divided into $K$ groups of equal weight. But by virtue of the choice of the number $r$ of weights, the weights of which are not divisible by $K^{r+1}$, are not less than $K$, since otherwise they would all be placed in the first box. Thus everything is proven.

*WITH. V. Konyagin.*

◆

Let us immediately note that the number of links $n$ must be quite large, in any case, $n > 8$. Let us first prove (taking into account the remark already made) that any non-self-intersecting closed broken line with an odd number of links not exceeding 13 has the property that there is always a straight line containing exactly one link of this broken line. Let us assume the opposite, that is, that for such

⟦folio 54⟧

broken line ($n = 2k + 1, n \leqslant 13$) there is no straight line containing exactly one link. Then at least three links of our broken line must lie on one of the straight lines. These three links have six ends, and from each end comes a broken link, that is, a total of six new links, and no two of these links lie on the same straight line. Therefore, each straight line containing one of these six polygonal links must, by virtue of the assumption made, contain at least one more link different from the RANES already considered ($3 + 6$ links); This means that the broken line in question must have at least six more links. We find that the number of links in such a broken line must be no less than $3 + 6 + 6 = 15$ - a contradiction.

Let us now show that for any even $n \geqslant 10$ and odd $n \geqslant 15$ broken line referred to in the problem, there exist $n \geqslant 10$ these are the well-known $\frac{n}{2}$ finite stars (figure 3; on this figure $n = 10$ and $n = 12$). It is more difficult to construct a non-self-intersecting closed polyline with an odd number of links greater than 13, which has the indicated property. A broken line with 15 links is depicted at figure 4. By cutting off a line from it in succession at two angles, we obtain a broken line with 17 links, 19, and so on (Fig. 5).

S. Lando

F296. Each of $k$ different capacitors with extrema $C_1, C_2, \dots, C_k$ is charged to the difference of marks $U$. Then all the capacitors are connected in series with strips of different sizes into a closed circuit. A name on each capacitor in this circuit.

Before connecting the capacitors into a circuit, their charges were $q_1 = C_1U, q_2 = C_2U, \dots, q_i = C_iU, \dots, q_k = C_kU$. Let us denote the charges of the capacitors after connecting them into the corresponding circuit by $q'_1, q'_2, \dots, q'_k$. The distribution of charges on the capacitor plates will be as shown in figure 6. From the law of conservation of charge it follows that the sum of the charges of capacitors connected to each other by a plate (one of such sections of the circuit is highlighted on figure 6 with a dotted line) must be equal to the total charge that was on these plates before connecting the capacitors. That is (taking into account the signs of charges)

$$q'_2 - q'_1 = q_2 - q_1 = (C_2 - C_1)U,$$

$$q'_3 - q'_2 = q_3 - q_2 = (C_3 - C_2)U,$$

$$q'_k - q'_{k-1} = q_k - q_{k-1} = (C_k - C_{k-1})U.$$

In addition, the work of crossing a charge along a closed counter in a power plant field is zero, therefore the sum of the direction on individual capacitors is equal to zero: $U_1 + U_2 + \dots + U_k = 0$, or

$$\frac{q'_1}{C_1} + \frac{q'_2}{C_2} + \dots + \frac{q_k}{C_k} = 0.$$

From the system of equations (*) and (**) we determine the new charges of the capacitors, and then the directions to them. First of all, let's express all the charges through the charge $q'_1$ of the first capacitor. From the first equation of system (*) it follows that $q'_2 = q'_1 + (C_2 - C_1)U$. Adding the first and second equations of system (*), we obtain $q'_3 = q'_1 + (C_3 - C_1)U$.

⟦folio 55⟧

Similarly, for the charge of the $i$th capacitor we obtain
$$q'_i = q'_1 + (C_i - C_1) U.$$
Let us substitute the resulting expressions into equation (**):
$$\frac{q'_1}{C_1} + \left[ \frac{q'_1}{C_2} + \left( 1 - \frac{C_1}{C_2} \right) U \right] + \dots + \left[ \frac{q'_1}{C_k} + \left( 1 - \frac{C_1}{C_k} \right) U \right] = 0,$$
or
$$q'_1 \left( \frac{1}{C_1} + \frac{1}{C_2} + \dots + \frac{1}{C_k} \right) + kU - C_1 U \left( \frac{1}{C_1} + \frac{1}{C_2} + \dots + \frac{1}{C_k} \right) = 0.$$
Hence $q'_1 = (C_1 - kC_0) U$, where $C_0$ is the capacitance of the balancing connections of the capacitor:
$$\frac{1}{C_0} = \frac{1}{C_1} + \frac{1}{C_2} + \dots + \frac{1}{C_k}.$$
Since $q'_i = q'_1 + (C_i - C_1) U$, then
$$q'_i = (C_1 - kC_0) U + (C_i - C_1) U = (C_i - kC_0) U.$$
This means that the voltage across the $i$-th capacitor is
$$U'_i = \frac{q'_i}{C_i} = \left( 1 - k \frac{C_0}{C_i} \right) U.$$

F297. We close two holes at once with a conical plug in a flat vessel filled with p. Hole radii R and r. Determine the total force acting on the plug from the liquid. We do not take into account the field of softness.

Fig. 6.

Fig. 7.

Each small element of the lateral surface of the plug with area $\Delta s_i$ is acted upon by a fluid pressure force $\Delta F_i = p \Delta s_i$, directed perpendicular to the lateral surface of the plug (Fig. 7). From symmetry it is clear that the horizontal components of such forces acting on various small elements of the surface of the cork, adding up, will mutually destroy each other. Therefore, the resultant of the pressure forces is vertical and equal to the sum of the vertical components of these forces. That is
$$F = \Sigma F_i \sin \alpha = \Sigma p \Delta s_i \sin \alpha = p \Sigma \Delta s_i \sin \alpha.$$
The product $\Delta s_i \sin \alpha$ is the projection of the area of ​​the element onto a plane parallel to the walls of the vessel. Consequently, the sum $\Sigma \Delta s_i \sin \alpha$ is equal to the area of ​​the projection of the lateral surface of the plug onto this plane, i.e. $\pi (R^2 - r^2)$. That's why
$$F = p \pi (R^2 - r^2).$$
Let us give another solution to this problem. Let us consider a plane similar to that given in the task, equal to the volume of the plug between the walls of the vessel (Fig. 8). Since the allocated volume of liquid is in equilibrium, the resultant of all forces acting on it is equal to zero. What forces act on the released volume of liquid? These are reaction forces from the walls of the vessel, equal in absolute value $N_1 = p \pi R^2$ and $N_2 = p \pi r^2$, and the resultant $F$

⟦folio 56⟧

Fig. 8.

F298. Inside the camera, peredicular to the homoplate, there is a flat mirror, the length of which DB is equal to half the focal length of the object (Fig. 9). Image A of the Vega star is located from the center of the homoplate at a distance half the radius of the object. How many times is the illumination of the “reflected image” C of star Vega less than the illumination of its image A in the presence of a mirror?

Pressure force from the surrounding fluid directed vertically upward. Since $N_1 - N_2 = \pi p (R^2 - r^2)$.

Obviously, the same force acts on the plug from the liquid side.

♦

Let us find the ratio of light fluxes coming from a distant star and falling on the photographic plate at points A and C (Fig. 9). At point A, those rays that pass through the lens of the object below point G, the point of intersection of straight line AD with the lens, are collected. Rays coming above point G fall on the mirror and, reflected from it, are collected at point C.

Consideration of the lens of an object by a plane perpendicular to the incident ray of rays (Fig. 10). The straight line EK divides the lens into two segments, through which the rays reach point A or point C. Since the lens is uniformly illuminated by the light of the star, the ratio of luminous fluxes is equal to the ratio of the areas of the corresponding segments. Let's find this relation.

The photographic plate is located in the focal plane of the object, the length of the mirror is equal to half the focal length of the object, therefore $DB = OD$ (see Fig. 9) and $\Delta GDO = \Delta ADB$. Therefore, $GO = AB = R/2$, where $R$ is the radius of the object.

Fig. 10.

object. Then (see Fig. 10) $\angle GKO = 30^\circ$, $\angle KOG = 60^\circ$ and $\angle EOK = 120^\circ$. Let us now express the area of ​​segments $S_1$ and $S_2$ through the area of ​​the corresponding sectors and triangle EOK:

$$S_1 = \frac{\pi R^2}{360} \cdot 120 - R^2 \frac{\sqrt{3}}{4} \quad \text{и} \quad S_2 = \frac{\pi R^2}{360} \cdot 240 + R^2 \frac{\sqrt{3}}{4}.$$

The ratio $S_1/S_2$ is equal to

$$\frac{S_1}{S_2} = \frac{\pi R^2/3 - R^2}{\pi R^2/3 + R^2} \cdot \frac{\sqrt{3}}{4} = \frac{4\pi - 3\sqrt{3}}{8\pi + 3\sqrt{3}} \approx 0,25.$$

I. Sh. Slovodechkiy
