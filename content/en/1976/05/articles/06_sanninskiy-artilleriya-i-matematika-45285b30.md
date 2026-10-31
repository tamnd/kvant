---
id: 1976-5-sanninskiy-artilleriya-i-matematika-45285b30
issue: kvant_1976_5
year: 1976
number: "5"
title: Artillery and mathematics
authors:
  - Саннинский В. Я.
rubric: osnovnye-stati
page_first: 35
page_last: 40
page_labels: 33-38
tag: Y1FC
lang: en
source: kvant_digital
extraction: vision
content_sha256: 4c9a044485dc8900c3da58011f695ddc66b63c1eb4d796336ba0026b1a959f1f
prompt_sha256: draft-1
translated_from: content/ru/1976/05/articles/06_sanninskiy-artilleriya-i-matematika-45285b30.md
source_content_sha256: 864fa7523202d47287a76462a0e623b58f31f920755fae30d4f5cf4966095ed5
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 33⟧

In this article, a veteran of the Great Patriotic War talks about the mathematical problems that he had to solve while commanding a battery of 120 mm mortars that fired at a range of up to 6 km. More than 30 years have passed since then. Many tasks related to fire control are now solved by computers. However, their mathematical suspense remained the same.
It is assumed that the reader knows what a geographic map is, geographic coordinates of a point on the earth's surface, geographic and magnetic poles, the equator, meridians, parallels and azimuths.

Firing an artillery battery at objects in the enemy camp involves preparing data - determining the range and direction of the arrow. To find these values, you must first “link” the battery and the target - namely, determine their geographical coordinates.

Let's explain what this means. Let us introduce some concepts; we will need them later.

Topographic maps

A topographic map (topographic map) is a large-scale geographic map. Topographic map sheets depict relatively small areas of the earth's surface, so the curvature of the earth cannot be studied (below we always consider the earth to be a sphere).

The main topographic map is a map of scale 1:1000000; it is called the international millionth topographic map. The millionth topo map sheets are equal-volume trapezoids, which are obtained like this. First, the earth's surface is covered with parallels every 4° from the equator to the pole - rows are obtained. Then the surface of the Earth is covered with meridians every 6° from the meridian opposite the Grivisian one, in the eastern direction - columns are obtained. Intersecting, rows and columns form tra-

⟦folio 34⟧

spices, which are depicted on the sheets of the millionth topographic map.

Each sheet of the millionth topographic map has a “geographical address” consisting of two characters - a nomenclature. The first character indicates that the sheet belongs to a specific row, the second - to a specific column. In this case, the rows are numbered with letters of the Latin alphabet (A, B, C, D,...) from the equator to the poles, and the columns are numbers (1, 2, 3, 4, ...) from the meridian opposite the Grivich one, in the direction to the east. Thus, point $M$ of the earth's surface with geographic coordinates $75^\circ 54'$ east longitude and $13^\circ 12'$ north latitude belongs to the millionth topo map sheet with the nomenclature $D-43$ ([13°12' :4°] + 1 = 4 - the fourth row from the equator - the letter $D$, and the 43rd column from the specified meridian:

$$\left[ \frac{180^\circ + 75^\circ 54'}{6^\circ} \right] + 1 = 43^*$$

For further calculations, we use the arc length of the globe at $1^\circ$ along the equator and along the meridian equal to 111.0 km. then the dimensions of the section of the earth's surface shown on sheet $D-43$ will be as follows: the bases of the trapezoid are 653.6 km and 640.2 km, the height of the trapezoid is 444.0 km (the first two values ​​are calculated as 6-degree arcs $12^\circ$ and $16^\circ$ parallels:

$$653,6 = 6 \cdot 111 \cdot \cos 12^\circ,$$
$$640,2 = 6 \cdot 111 \cdot \cos 16^\circ,$$

and the third value is 4.111 - like the 4-degree arc of the great circle of the globe).

By successively dividing sheets of millionths of a topographic map into parts equal in longitude and latitude, topographic maps of smaller scales are obtained: 1:100000, 1:50000, 1:25000 and 1:10000. To get a 1:100000 topo map, millionth topo map sheet

*) Here $[x]$ is the integer part of $x$ - the integer closest to $x$, not exceeding $x$ (see article “Antje”, p. 43).

⟦folio 35⟧

divided into 12 parts by longitude and 12 parts by latitude: 144 “pieces” are obtained. To get a 1:50000 topographic map, you need to divide one of the resulting 144 pieces into 2 more equal in longitude and 2 equal in latitude parts (see Fig. 1). If one of the resulting pieces is again divided into 2 parts equal in longitude and 2 parts equal in latitude, we get a topo map of 1:25000. Repeat the same operation (dividing into even “pieces”) with this topographic map, we get a topographic map of 1:10000.

When dividing the parts of each topographic map sheet, they are numbered: “left - right - down” (Fig. 1). To designate parts, a new index is added to the nomenclature of the original millionth topographic map each time: one - if the map is 1:100000: a number from 1 to 144 (Fig. 1, a); two - if the map is 1:50000: the index of the sheet of the hundred-meter topographic map from which it was obtained, plus one of the first four capital letters of the Russian alphabet A, B, B, Γ (Fig. 1, ​​b); three - if the card is 1:25000: the index of the corresponding fifty-thousandth card, plus one of the letters a, b, c, d (Fig. 1, c), and finally, four - if the card is 1:10000: the index of the corresponding card 1:25000 plus one of the numbers 1, 2, 3, 4 (Fig. 1, e).

When preparing initial data for arrows, topographic maps on a scale of 1:10000 are usually used. A map sheet of this scale, containing the above-mentioned point M (given by geographic coordinates), has the nomenclature D-43-104-B-g-3; check it out. It can be calculated that this sheet cultivates a trapezoid-shaped section of the earth's surface with a center line of 6.8 km and a height of 4.6 km.

Topographic coordinates

The coordinate system used in topography is different from Cartesian. In this system, the X axis is the middle geographic Myrdian of each column, parallel to 500 km to the west, and the Y axis is the equator. Let us find, for example, in this reporting system the coordinates of our point M - they are called monoeffective coordinates, and are measured in meters. Point M is located at a distance of 1465.2 km from the equator and at a distance of 97.26 km to the right of the middle meridiana of column number 43. Therefore, for it

$$\begin{cases} X_M = 1465200, \\ Y_M = 597260. \end{cases}$$

On the territory of each country, special, visible pre-state training points have been installed. All of them, like other tall structures on the earth's surface, have precisely defined topographic coordinates; These coordinates are stored in special directories that are used only for service purposes.

For educational purposes, the conditions are satisfied with the coordinates. coordinates of the first, starting point of the area, given arbitrarily. The necessary items are “attached” to it. The result is a flat system of points defined by coordinates, corresponding to the actual system of terrain points. Find out, if necessary, the topographic coordinates of one of the points of this system, we can find the actual coordinates of the entire network of points.

Insert it at some point in the northern hemisphere with the corresponding topographic map and try to sort it by cardinal direction. Three meridians pass through each point: magnetic, geographic and topographic (parallel to the median geographic meridian for the main sheet of the corresponding topographic map). To mention the meridians, generally speaking, they do not coincide. They intersect at certain angles. These angles are relatively small, and we imprene

⟦folio 36⟧

we cut. We will consider all meridians at the point coinciding with the magnetic one, that is, with the direction to the north of the magnetic compass needle.

Everyone has to use a compass. Therefore, we can assume that we know how to orient the desired topographic map in the direction to the north.

In what follows we will use the following notation:

$X_A$ and $Y_A$ are monographic coordinates of point $A$ on the ground;

$|AB|$ — distance between points $A$ and $B$ (in meters);

$[AB]$ is the azimuth of the direction from $A$ to $B$, that is, the angle between $AB$ and the direction north, measured clockwise.

Tasks

Let us now consider the main tasks on coordinates that come to be solved in the process of preparing the initial data for the arrow.

Problem 1. (Direct coordinate problem.) Given: $X_A$, $Y_A$, $|AB|$ and $[AB]$. Name: $X_B$, $Y_B$.

This means that the distance $|AB|$ (in meters) will be found using a measuring tape, the angle $[AB]$ - using a compass or theodolite (without taking into account corrections for angles between meridians).

From figure 2 is

$$X_B = X_A + \Delta X$$

And

$$Y_B = Y_A + \Delta Y,$$

where $\Delta X = |AB| \cdot \cos [AB]$ and $\Delta Y = |AB| \cdot \sin [AB]$.

Task 1 allows us to “tie” point $B$ of the terrain (determine the topographic coordinates of point $B$) using the “tethered” point $A$.

When solving specific coordinate problems, it is customary to use 5-digit mathematical tables *). For example, solve this problem:

*) You can use Bradis tables.

Fig. 2.

1. Find $X_B$ and $Y_B$ if $X_A = 53\ 817$, $Y_A = 38\ 629$, $|AB| = 2182$ and $[AB] = 321^\circ 14'$.

Task II. (Inverse coordinate problem.) Given: $X_A$, $Y_A$, $X_B$, $Y_B$. Name: $[AB]$, $|AB|$.

From the same figure 2 there are $\Delta X = X_B - X_A$ and $\Delta Y = Y_B - Y_A$. Next we have

$$tg[AB] = \frac{\Delta Y}{\Delta X}.$$

According to the calculated value $tg[AB]$, taking into account the sign of location, the angle $[AB]$.

Finally, from $\Delta ABC$ we have

$$|AB| = \frac{|\Delta Y|}{\sin [AB]} = \frac{|\Delta X|}{\cos [AB]}.$$

The calculation of $|AB|$ is carried out using both formulas. The coincidence of results is a certain guarantee of the safety of derivative calculations.

Now solve a specific problem:

2. Find $[AB]$ and $|AB|$ if $X_A = 12\ 850$, $Y_A = 98\ 713$, $X_B = 13\ 519$ and $Y_B = 97\ 314$.

Having solved it, you can give the command to the battery: “Battery, to battle! Range..., azimuth...!” The gunner of each battery gun, having received such a command, will use a device to properly aim his gun vertically (one division of the sight is 50 m) and horizontally (one division of the protractor is 3.6').

The teacher may be confused. At point $A$ the first weapon is located, the others are at a certain distance from it, to the left. Means

⟦folio 37⟧

Only the first ordine will fall into $B$. In fact, if the whole $B$ area is significant, then everything will be fine (why?). But what about when the whole mala is concentrated at point $B$? In this case, the mentioned command is additionally indicated: “upward-centered” (if the target $B$ is large in area, then the command is: “upward parallel”), and the commanders, depending on their distance from the first, calculate and make corrections to the azimuth indicated to the battery.

The reader can do the corresponding computational work himself for the commander of the second order, considering his distance from the first, for example, equal to 50 m (under the conditions of the same specific task II). It can be assumed that the front of the battery is perpendicular to the direction of fire of the first ord.

So, we have already worked for both the battery commander and the ordnance commander. However, we have not yet taught the most important thing: after all, in order to shoot from $A$ to $B$, you must first “bind” these points. In war conditions, point $A$ is located on our territory, and point $B$ is on enemy territory: you can’t get there with a measuring tape. This gives rise to a new task - the task of “tying” an inaccessible point in the area.

Task III. (Straight notch from two points.) Given: $X_A, Y_A, X_B, Y_B$, intact $\alpha$ and $\beta$ (see Fig. 3). Name: $X_C, Y_C$.

This means that points $A$ and $B$ of the terrain are already “linked”. It is necessary to “bind” item $C$ on the condition that the values ​​$\alpha$ and $\beta$ can be found by unrepresented change.

If we know the quantities $[AC]$ and $|AC|$, or $[BC]$ and $|BC|$, then our problem will be reduced to Problem I. Let us determine these quantities.

For $\Delta ABC$ (see Fig. 3) by the sine theorem we have

$$\frac{|AC|}{\sin \beta} = \frac{|BC|}{\sin \alpha} = \frac{|AB|}{\sin (\alpha + \beta)}$$

From here

$$|AC| = \frac{|AB|}{\sin (\alpha + \beta)} \cdot \sin \beta$$

and $|BC| = \frac{|AB|}{\sin (\alpha + \beta)} \cdot \sin \alpha$.

Also, $[AC] = [AB] - \alpha$ and $[BC] = [AB] + \beta$.

The quantities $|AB|$ and $[AB]$ are found in the same way as in Problem II.

Coordinates for control are calculated in two ways: both at point $A$ and at point $B$.

Now solve a specific problem:

3. Find $X_C$ and $Y_C$ if $X_A = 12850, Y_A = 98713, X_B = 13519, Y_B = 97314, \alpha = 39^\circ43', \beta = 82^\circ25'$.

Problem III comes to be solved in the following situation. Let $A$ and $B$ be a pair of observed points located at a distance of 1.5–2.5 km from each other, not far from the front edge of the defense. These points are “linked” in advance, and the enemy is observed from them. When a target $C$ appears in the enemy camp, it is observed that it is “spotted”, that is, the angles $\alpha$ and $\beta$ will be measured in any way. All that remains is to solve the triangle $ABC$ by side $AB$ and two adjacent angles $\alpha$ and $\beta$: analytical, as described above, or graphic - on a tablet.

Finally, another coordinates problem.

Task IV. (Backcut from three points.) Given: $X_A, Y_A, X_B, Y_B, X_C, Y_C, ADC = \alpha, BDC = \beta$

⟦folio 38⟧

(see Fig. 4). Find: $X_D, Y_D$.*

The coordinates of the point $D$ can be calculated through the increments of the coordinates of either point: $A, B$ or $C$. To avoid errors, it is customary to find them through increments from two points, for example, points $A$ and $B$.

We already know how to calculate the quantities $[AC]$ and $|AC|$, $[BC]$ and $|BC|$. By doing this, we can find the angle $\widehat{ACB}$:

$$\widehat{ACB} = [AC] - [BC].$$

Let's put $\widehat{CAD} = \gamma$ and $\widehat{CBD} = \delta$. Let's determine these angles.

From the quadrilateral $ACBD$ we have

$$\frac{\gamma + \delta}{2} = 180^\circ - \frac{\alpha + \beta + \widehat{ACB}}{2}.$$

From triangles $ACD$ and $BCD$ using the sine theorem we find

$$\frac{|CD|}{|AC|} = \frac{\sin \gamma}{\sin \alpha}$$

$$\frac{|CD|}{|BC|} = \frac{\sin \delta}{\sin \beta}.$$

Eliminating the quantities $|CD|$ from these equalities, we obtain

$$\frac{\sin \delta}{\sin \gamma} = \frac{|AC| \sin \beta}{|BC| \sin \alpha}.$$

Let's put it here

$$\frac{|AC| \sin \beta}{|BC| \sin \alpha} = \text{tg} \lambda.$$

Having calculated $\text{tg} \lambda$ using this formula, we find the auxiliary angle $\lambda$.

*) This problem is known as the Pomenon problem. They were already told in «Kvant» - see, article by L. S. Khrenov, «Kvant», 1973, No. 4, p. 30.

Now

$$\frac{\sin \gamma}{\sin \delta} = \frac{1}{\text{tg} \lambda},$$

where

$$\frac{\sin \gamma + \sin \delta}{\sin \gamma - \sin \delta} = \frac{1 + \text{tg} \lambda}{1 - \text{tg} \lambda},$$

that is

$$\text{tg} \frac{\gamma - \delta}{2} = \text{tg} \frac{\gamma + \delta}{2} \cdot \text{ctg} (45 + \lambda).$$

All quantities on the right side are known. Therefore, we can find the half-difference of the desired angles $\gamma$ and $\delta$.

Knowing them, we obtain the half-sameness and easily find these angles themselves.

Then from triangles $ACD$ and $BCD$ using the sine theorem we find

$$|AD| = \frac{|AC| \sin (\alpha + \gamma)}{\sin \alpha}$$

$$|BD| = \frac{|BC| \sin (\beta + \delta)}{\sin \beta}.$$

Azimuths $[AD]$ and $[BD]$ are found using the formulas

$$[AD] = [AC] + \gamma$$

$$[BD] = [BC] - \delta.$$

Next, as in Problem I, find $X_D$ and $Y_D$.

Here's the specific task:

4. Find $X_D$ and $Y_D$ if $X_A = 12850$, $Y_A = 98713$, $X_B = 13519$, $Y_B = 97314$, $X_C = 12406$, $Y_C = 96956$, $\alpha = 72^\circ 28'$, $\beta = 31^\circ 46'$.

A resection from three points usually “ties” the observed points and batteries. You can “link” the goal in this way. But for this you need to have your own representative on enemy territory. Like the previous ones, the last problem can be solved graphically: to do this, you need to construct a point from which these two segments are visible at these angles.

This concludes our story about the tasks that artillery comes to solve. Let us only add that “mathematics in artillery” is far from being exhausted by the problems analyzed.
