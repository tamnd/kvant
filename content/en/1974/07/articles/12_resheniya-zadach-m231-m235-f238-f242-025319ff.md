---
id: 1974-7-resheniya-zadach-m231-m235-f238-f242-025319ff
issue: kvant_1974_7
year: 1974
number: "7"
title: Solutions to problems M231—M235; F238—F242
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 40
page_last: 49
page_labels: 38, 39, 40, 41, 42, 43, 44, 46, 47
tag: E6L3
lang: en
source: kvant_digital
extraction: vision
content_sha256: 7e6e922b5a951bfae45da0d29c9a5ec59d3cf1d4da825e37d51f3118414d8861
prompt_sha256: draft-1
translated_from: content/ru/1974/07/articles/12_resheniya-zadach-m231-m235-f238-f242-025319ff.md
source_content_sha256: 0d71b36ba443c5ad2fa9108387aa2be49591bcd2e5a100b3a9efb4018ef87028
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 38⟧

Problem solutions

M231. Find all natural number solutions to the equation
$$n^x + n^y = n^z.$$
Obviously, $n$ must be at least two. Counting $x \leq y \leq z$, we rewrite our equation in the form
$$n^{z-x} - n^y-x = 1.$$ (*)
If we assume that $y$ is strictly greater than $x$, then from (*) it will follow that the unit is divisible by $n$ ($n \geq 2$); but this is not true, which means $y = x$. Taking this equality into account, we obtain:
$$n^{z-x} = 2,$$
whence $n = 2$, $z - x = 1$.
So, this equation has an infinite number of solutions in natural numbers: $n = 2$, $y = x$, $z = x + 1$, $x$ - any natural number.
R. Yegoryan.

M232. a) Prove that to a finite set of points on a plane that has the property that any three points from this set are the vertices of a non-degenerate polygonal triangle, one can always add one more point so that this property is preserved.
b) Is a similar statement true for an infinite set of points on a plane?

a) Note that for given points $A$ and $B$, the point $C$, lying outside the line $AB$ and outside the strip formed by perpendiculars to the line $AB$ at points $A$ and $B$, forms from the points $A$ and $B$ a non-singular obtuse triangle (see Fig. 1). For each pair of points from a given finite set, we construct a strip and a straight line in accordance with figure 1. A finite number of strips of finite width and straight lines, very indo, will not cover the entire plane, therefore, there is a point that forms an obtuse triangle with each pair of points from a given set, which is what we needed to prove.
b) Answer: generally speaking, not on the right or in.
Let's take the following example. Distance is a set consisting of a semicircle point without one end diameter (Fig. 2). It's easy to see what a set is

⟦folio 39⟧

Fig. 6.

satisfies the conditions of the problem. Let us prove that it is impossible to add a single point to it (this is almost very indo). Indeed, if a point lies inside a semicircle on its diameter (Fig. 3, point X), then it is always possible to find a point C on the semicircle such that triangle ACX is acute. The same holds for all points lying in a non-semicircle or inside but outside its diameter (Fig. 4, points X' and X''; the corresponding points B', C' and B''', C'' are chosen “close enough”). If the point is chosen on the diameter in a non-semicircle (Fig. 5, point M), then the inverse occurs - at figure 5 the points M, N, K are on the same straight line.

P. S. Pankov

M233. At the end of the segment two units are written. The halfway point between them is their sum - the number 2. Then the halfway point between each two adjacent numbers is their sum and a maximum of 1973 times. How many times will the number 1973 be written?

Let's write down in a row the lines of numbers that form as a result of the next step - a total of 1973 lines (Fig. 6). Let's get some table. Let's try to find out how many times the number n appears in the nth row of this table (it is clear that in each subsequent row - with a number greater than n - the number n will appear exactly the same number of times as in the nth: all new generating numbers will be greater than n).

We will say that our table contains a pair of natural numbers (a, b) if the numbers a and b are next to each other on the same line, with b to the right of a. Let us prove the following statement:

If 1973 is simple (check!). Therefore it occurs 1972 times.

N. B. Vasiliev

⟦folio 40⟧

M234. Given a square with side 1. Four parts are cut off from it - four triangles, each of which has two sides running along the sides of the square and making up 1/3 of their length. With the resulting 8-pleaser, the same can be done: from each vertex, cut off a triangle, two sides of which are 1/3 of the corresponding sides of the 8-pleaser, and so on. The result is a sequence of polygons (each contained in the previous one). Let's find the area of ​​the figures that are the intersection of all these polygons (that is, formed by the points belonging to all polygons).

Let us denote by $M_0$ the original square, and by $M_1, M_2, M_3, \dots$ the polygons obtained from $M_0$ by successive cutting off the corners. It is convenient to also consider the polygon $N_h$, the vertices of which are the midpoints of the side $M_h$ ($k = 0, 1, 2, \dots$).

Let $A$ be an arbitrary vertex of the polygon $M_h$, and $B$ and $C$ be its neighboring vertices. To obtain a polygon $M_h+1$ from a polygon $M_h$, you need to cut off a triangle $B_2AC_2$ from each vertex $A$ of a polygon $M_h$ (see Fig. 8) such that the points $B_2$ and $C_2$ divide, respectively, the segments $[AB]$ and $[AC]$ in a ratio of 1:2. Let $B_1$ and $C_1$ be the midpoints of the segments $[AB]$ and $[AC]$, that is, adjacent vertices of the polygon $N_h$; Then

$$\begin{align*}
|AC_2| &= \frac{2}{3}|AC_1|, \\
|AB_2| &= \frac{2}{3}|AB_1|.
\end{align*}$$

When moving from the polygon $N_h$ to the polygon $N_{h+1}$, the points $B_1$ and $C_1$ remain its vertices, but are no longer adjacent: a new vertex $A_1$—the middle of the segment $[B_2C_2]$—appears between them. Thus, the polygon $N_{h+1}$ is obtained from the polygon $N_h$ by adding a triangle of type $B_1A_1C_1$ to each of its sides $[B_1C_1]$.

Fig. 8.

⟦folio 41⟧

It starts from the previous one by sloping down to the point $a$ $4\frac{1}{2}$ times. Thus, point $a$ is the only common point of all these segments. (It is possible to write down exact formulas for $x_h$ and $y_h$: $x_h = \frac{5}{7} - \left(\frac{2}{9}\right)^k \times \frac{3}{14}$, $y_h = \frac{5}{7} + \left(\frac{2}{9}\right)^k \cdot \frac{2}{7}$; but we did not come across them. The reader familiar with the concept of the limit of a sequence, of course, noticed that $a$ is the general limit of the sequences $x_h$ and $y_h$; in essence, this is exactly what we have proved.) From here we have already it follows that the area of the desired figure $M$ (which is the intersection of all polygons $M_h$) is equal to $a$; indeed, $M$ is contained in any $M_h$ and contains any $N_h$ (prove it!)*); therefore, the area of ​​$M$ must be enclosed between $x_h$ and $y_h$ (for all $k$), and this requirement is satisfied by a single number: $a = \frac{5}{7}$.

It would be possible to solve this problem without introducing the polygons $N_h$, using only the correspondence defining the sequence $y_0 = 1$, $y_1 = \frac{5}{9}$, $y_2$, $y_3$, ...

$$y_h - y_{k+1} = \frac{1}{9} (y_h - y_{k-1}).$$

In this case, the area $M$ is found as the limit of the areas $M_h$ (the sequence $(y_h - y_{k-1})$ is an infinite decreasing geometric progression).

*) This number is a set-theoretic fact: if $M_h \supset M_{k+1} \supset N_{k+1} \supset N_h$ for each $k = 0, 1, 2, \dots$, and $M = \bigcap_k M_h$, then $M \supset N_h$.

A. Zelensky (Shakhtersk) generalized problem M234 to the case when the segments constituting $\frac{1}{p}$ of this side are cut off from each side, where $p$ is any number greater than 2. In this case, the area of ​​the resulting figure is $\frac{p^2 - 2p + 2}{p^2 - 2p + 4}$; for $p = 3$ we get the answer $\frac{5}{7}$.

C. Konyazin

M235. A lion is running along the argen of a circular circus with a radius of 10 m. Moving along a broken line, he ran 30 km. Prove that the sum of all the angles at which it turns is $\alpha_1, \dots, \alpha_{k-1}$ (a total of $k$ segments and $k-1$ rotation). Let's imagine the lion's movement as follows.

Let us denote the segments that the lion runs through $x_1, x_2, \dots, x_h$, and the angles through which he turns at the same time as $\alpha_1, \dots, \alpha_{k-1}$ (in total there are $k$ segments and $k-1$ turns). Let's imagine the lion's movement as follows.

Let the lion run the segment $AA_1 = x_1$. Let us rotate its vector (that is, the vector of the point $A_1$) arena by the angle $\alpha_1$ so that the segment $x_2$ turns out to be a continuation of the segment $x_1$. After the lion has run through the segment $A_1 A_2 = x_2$, we rotate its arena vector by an angle $\alpha_2$ so that the segment $x_3$ becomes a continuation of the segment $x_2$ and so on. Then the lion will run in a straight line and cover the segment $AA_k = 30000(m)$, where $A$ is the starting point and $A_k$ is the end point.

Let's follow the movement of the center of the arena - point $O$. First, the point $O$ rotates the vector of the point $A_1$ by the angle $\alpha_1$, then the vector of the point $A_2$ by the angle $\alpha_2$ and so on. Each time the center of the arena $O$ is no more than 10 $m$ from the center of rotation, since the center of rotation is the lion located inside the arena. Therefore, during the first rotation, the point $O$ will move no more than $\alpha_1 \cdot 10(m)$, during the second - no more than $\alpha_2 \cdot 10(m)$, and so on ($\alpha_1, \dots, \alpha_{k-1}$ are measured in radians). All points $O$ move

Fig. 10.

⟦folio 42⟧

Fig. 11.

goes no more than $(\alpha_1 + \dots + \alpha_{k-1}) \cdot 10(m)$, that is
$$O'O'' \leq (\alpha_1 + \dots + \alpha_{k-1}) \cdot 10(m)$$
(see Fig. 11 - here $O'$ is the initial position, $O''$ is the final position of the point $O$).

Since $O'A \leq 10(m)$, $O''A_k \leq 10(m)$ and $AA_k = 30000(m)$, then $O'O'' \geq 29980(m)$. From here
$$\alpha_1 + \dots + \alpha_{k-1} \geq \frac{O'O''}{10} \geq 2998(m)$$

I. N. Bernishtein

F238. There are two square wires made of the same material. The cross-sectional side of one wire is $a_1 = 1$ mm, and the other is $a_2 = 4$ mm. In order to melt the first wire, a current $I_1 = 10$ a must be passed through. How much current must be passed through the second wire to melt it?

Show that the amount of body released into the environment in 1 s is proportional to the temperature difference between the wire and the environment and the surface area of ​​the wire, and the coefficient is proportional to the aspen for both wires.

If the wire is in thermal equilibrium with the medium (its temperature does not change), then the amount of tell that is released in the wire during the passage of current per unit time is equal to the amount of tell that is released in the surrounding medium. If the current increases so that the wire begins to melt, the additional amount of tell released by the current will go to melting. Therefore, we need to find the current that corresponds to the melting temperature of the wire.

The number of bodies trimmed by wire fibers per unit time is equal to $Q_1 = k S_1 \Delta T = 4ka_1 l \Delta T$ and $Q_2 = k S_2 \Delta T = 4ka_2 l \Delta T$, where $k$ is the proportion coefficient

⟦folio 43⟧

is directed perpendicular to the speed $v$ of the point and is equal in absolute value to $\frac{v^2}{R}$, where $R$ is the radius of this circle. Therefore, it is clear that we can determine $R$ if we know the speed of the point $v$ and its acceleration $a$ in the direction perpendicular to this speed.

First, let's find the velocities of points $A$ and $B$ relative to the Earth. This can be done, for example, by adding the linear velocities of rotation of points in a coordinate system associated with the center of the wheel and moving translationally parallel to the horizontal plane, with the speed of movement of this coordinate system, that is, with the speed of the center of the wheel relative to the plane. You can use a less invasive, much simpler method. At the moment of time we are considering, the point $C$, touching the plane, is motionless relative to the plane, and we can assume that the entire wheel rotates relative to this point (the instantaneous center of rotation). The angular velocities of rotation of all points of the wheel relative to the instantaneous center of the rotation are the same and equal, in particular, to the angular velocity of rotation of the center of the wheel:

$$\omega = \frac{v_0}{r}$$

($v_0$ is the speed of the wheel center). This means that the speed of point $B$, perpendicular to the segment $BC$, is equal to

$$v_B = \omega \cdot BC = \frac{v_0}{r} BC.$$

From the triangle $BCD$ it is clear that $BC = 2r \cos \frac{\alpha}{2}$. Hence,

$$v_B = 2v_0 \cos \frac{\alpha}{2}.$$

Similarly, the speed of point $A$ $v_A$, perpendicular to $AC$, is equal in absolute value

$$v_A = \omega \cdot AC = 2v_0 \cos \frac{\pi}{4} = v_0 \sqrt{2}.$$

Now let’s find the accelerations of points $B$ and $A$, perpendicular to the velocities of these points. The total accelerations of these points are obviously the centripetal accelerations $a_\mu$ in the coordinate system associated with the center of the wheel. Indeed, since the wheel moves relative to a uniform plane, the accelerations of a point of the wheel in the coordinate system associated with the plane coincide with their accelerations in the coordinate system moving translationally with the center of the wheel. Therefore, the centripetal accelerations of points

$$A$$ and $B$ are directed towards the center of the wheel and are equal in absolute value to $a_\mu \cdot A = a_\mu \cdot B = \frac{v_0^2}{r}$.

The accelerations of points $A$ and $B$, perpendicular to the velocities $v_A$ and $v_B$, are projections of the acceleration $a_\mu \cdot A$ and $a_\mu \cdot B$ in the direction perpendicular to $v_A$ and $v_B$. They are equal to the corresponding ones.

$$a_A = a_\mu \cdot A \cos \frac{\pi}{4} = \frac{v_0^2}{2r} \sqrt{2},$$

$$a_B = a_\mu \cdot B \cos \frac{\alpha}{2} = \frac{v_0^2}{r} \cos \frac{\alpha}{2}.$$

Thus, at this moment the points $A$ and $B$ are moving in a circle, the radius of which is determined from the correspondences

$$\frac{v_A^2}{R_A} = \frac{v_0^2}{2r} \sqrt{2}$$

and $$\frac{v_B^2}{R_B} = \frac{v_0^2}{r} \cos \frac{\alpha}{2},$$

or

$$\frac{(v_0 \sqrt{2})^2}{R_A} = \frac{v_0^2}{2r} \sqrt{2}$$

and $$\frac{(2v_0 \cos \frac{\alpha}{2})^2}{R_B} =$$

$$= \frac{v_0^2}{r} \cos \frac{\alpha}{2}.$$

From here

$$R_A = 2r \sqrt{2}$$ and $$R_B = 4r \cos \frac{\alpha}{2}.$$

F240. The balloon-probe, which has an inextensible shell, has risen to the maximum height and makes a small flask, squeezing that at the maximum height the air density $\rho$ kills with height evenly by the values ​​of $\delta = 1,2 \cdot 10^{-2}$ $\rho$ every $h = 100$ m.

First of all, we will show that the balloon actually oscillates. Two forces act on it: the gravitational force $mg$ and the buoyant Archimedean force $F_B$. Both forces are directed vertically, but in opposite directions. Obviously, in the equilibrium position

$$mg = F_B,$$

where $m$ is the mass of the ball, $F_B = \rho Vg$ ($V$ is the volume of the ball).

If, due to some random objects, the ball moves from its equilibrium position, the magnitude of the buoyant force will change. Moreover, when moving the ball up $F_B$

*) Since the wheel rolls without slipping, the linear speeds of rotation of all points on the wheel rim are equal to the speed of the construction movement of the center of the wheel.

⟦folio 44⟧

decreases, and when mixed down, it increases. Thus, in both cases an equal force will arise, equal to the change in the buoyant force and directed towards the equilibrium position. Let's find its magnitude.

Let the ball move from its equilibrium position at $x$. Since air density changes uniformly with height, then

$$\frac{\Delta \rho}{\delta} = \frac{x}{h},$$

where $\Delta \rho$ is the change in air density at height $x$. Then

$$\Delta F_B = -\Delta \rho Vg = \frac{-\delta Vg}{h} x$$

(the minus sign indicates that the force $\Delta F_B$ is always directed towards the equilibrium position).

We see that the equal force acting on the ball is directed towards the equilibrium position and is proportional to the deviation of the ball from the equilibrium position. This means that the ball performs a harmonious oscillation, similar to the oscillations of the load outside (for which $F = kx$). The role of the spring stiffness coefficient in this case is played by the quantities

$$k' = \frac{\delta Vg}{h}.$$

The postural period of the ball's oscillations is equal to

$$T = 2\pi \sqrt{\frac{m}{k'}} = 2\pi \sqrt{\frac{mh}{\delta Vg}}.$$

Since $m = \rho \cdot V$, then

$$T = 2\pi \sqrt{\frac{h\rho}{\delta g}} = 2 \cdot 3,14 \sqrt{\frac{100 \cdot \rho}{1,2 \cdot 10^{-2} \rho \cdot 10}} \approx 180$$ (s).

F241. A ring of mass $m$ can slide along a rod of length $L$. The strength of the claim between him is $F$. Determine what minimum speed $v_0$ the rod needs to communicate so that it breaks through the flask if the flask breaks first.

The experiment is carried out in zero gravity.

The solution problem is exactly the same as problem F228 (see «Kvant», 1974, No. 5). That's why

$$v_0 = \sqrt{2LF \frac{M + m}{Mm}},$$

where $M$ is the mass of the rod.

F242. A camera obscura is a rectangular box with a round hole in one of its walls. The illumination of the image Colnca, which is obtained on the opposite wall of the camera - the screen, nada input when moving from the center of the image to the edge by 0.9 radius of the image. How many times is the illumination on the front wall of the camera greater than the illumination in the center of the image?

Each point of the Coln image is illuminated not by the entire Coln, but only by that portion of it that is visible from this point in a small solid angle limited by the pinhole camera opening. Since the camera aperture is small and Colnce is very far away, we can assume that this solid angle is the same for all points of the Colnce image. It is clear that the illumination of the Colnc image point is proportional to the Colnc plane that is visible from this point.

The change in image illumination is due to the fact that as a point moves away from the center of the image, the section of the Coln that illuminates this point approaches the edge of the Coln, and when the section “goes” beyond the edge of the Coln, its area decreases. The illumination of the image of a point drops by half when the area of ​​the Coln area “illuminating” the point is halved. In this case, as can be seen from figure 13, at this point the beam comes from the edge of the Coln and passes through the center of the chamber opening. This allows you to find the angle at which Colnce is visible from the point of the front wall of the pinhole camera:

$$\frac{\alpha}{2} \approx tg \frac{\alpha}{2} = \frac{0,9R}{l},$$

where $l$ is the length of the pinhole camera. The angle is Fig. 13.

⟦folio 46⟧

P. Katsylo (Moscow) 16, 26-29; P. Kirsanov (Moscow) 26; L. Klimenok (Moscow) 27; M. Kobozev (Kyiv) 21, 22, 27; V. Kobiletsky (Baku) 16, 18, 20, 26, 27; A. Kolodin (Kolomya, Ivano-Frankivsk region) 21, 22, 24, 26, 27; S. Kolyada (Kyiv) 16, 21, 22, 24, 27, 30; L. Konytkovsky (Luninets, Brest region) 27; S. Kortsunov (Monino, Moscow region) 16, 17; V. Kostmanyan (Baku) 27; S. Kostmena (Chelyabinsk) 27; A. Komanov (Tsalka village, GSSR) 27; L. Kofman (Tallinn) 16; I. Kryukov (Old Sambir, Lviv region) 21, 22; N. Kudrin (Kolomna, Moscow region) 27; A. Kukushi (Kyiv) 26, 27, 30; A. Kumakhov (s. II Lesen KBASSR) 27; A. Kurlyandik (Vilnius) 26, 27; A. Kutyrkin (Penza) 21, 22; S. Lapasikov (Oboyan, Kursk region) 26, 28, 30; M. Levin (Vitebsk) 17, 18, 27; M. Levin (Tallinn) 23; S. Lifsts (Kharkov) 16, 21; Yu. Loban (Evpatoria) 26, 27; M. Lyubi (Kharkov) 16, 19-23, 25-27, 29, 30; S. Lyapin (Petrikov, Gomel region) 16, 17, 21, 27; G. Mavzimov (village of Srednie Chelny TASSR) 27; M. Malyan (Yerevan) 27; A. Makariev (Lvov) 16-18, 20-22, 24, 26-29; S. Makarov (Saratov) 26-28; S. Malinsky (Poltava) 21—24, 27, 28, 30; G. Mamedov (Baku) 27; A. Markov (Moscow) 26, 27, 29; S. Melnik (Kharkov) 16, 18, 20—26, 28, 29; A. Mekhovich (Vladivostok) 27; V. Milman (Minsk) 26, 27; A. Miroshinchenko (Kharkov) 18; Yu. Mikhailov (Leningrad) 21-23; L. Mikhlin (Kursk) 16, 18, 20-22, 27-30; A. Morozov (Novosibirsk) 21; Yu. Muranov (Moscow) 21; G. Mustafaev (Sizan Az. USSR) 27; K. Mkhitaryan (Yerevan) 16-22, 25-28; A. Navasardi (Yerevan) 27; Yu. Neretin (Moscow) 26, 27; N. Nechemayev (Leningrad) 16, 20-23, 25-28, 30; A. Nikolaev (Moscow) 20; I. Novikov (Kuibyshev) 16, 18, 21, 23-25, 27-30; S. Okhitin (Orenburg) 16, 20, 26-28; I. Panin (Apatity) 16, 20—23, 26, 27; E. Pasike (Kharkov) 26, 27; V. Pelinenko (Voronezh) 26-29; O. Pechersky (Ordzhonnikdze) 16; Yu. Pinelis (Kzyl-Orda) 16-18, 20, 26, 27, 29, 30; M. Polovinnik (Mena, Chernigov region) 16; A. Ponosov (Perm) 21, 22, 24-30; V. Porzein (Rostov-on-Don) 18, 21, 24, 27, 30; R. Portnoy (Chernivtsi) 21, 27, 29, 30; D. Potsshivili (Tbilis) 27; V. Prasolov (Voroshilovgrad) 26, 27, 29; Yu. Promas (Cahul MSSR) 18, 23, 27; S. Putintsev (Kemerovo) 16, 18, 20, 22, 23, 25-28; L. Rabinovich (Tula) 21-23, 25-30; A. Razulev (Klin, Moscow region) 18, 20—23, 25, 27; A. Rashkovsky (Kharkov) 26, 27; A. Reznikov (Kyiv) 16, 21, 22, 26, 27; A. Reptsein (Kramatorsk, Donetsk region) 16, 18-21; G. Rodin (Leningrad) 21, 23; R. Rozhkov (Moscow) 26, 27; F. Rozhkov (Ryazan) 26, 27; M. Rozhkova (Kyiv) 18; E. Romanovsky (Kyiv) 26-28, 30; V. Rubaevsky (Kyiv) 20, 21, 27, 28; N. Rundkovist (Sverdlovsk) 16; A. Rybakov (Murom)

⟦folio 47⟧

Here is a list of readers who sent solutions to problems F223—F242. Almost all readers solved Problem F223 and F233 correctly; the correct solutions to the remaining problems were added (bold numbers after the last name are the last two digits of the number of the solved problem):

N. Abramenko (Mogilev) 30, 36, 38, 40; D. Azov (Chelyabinsk) 38; S. Akmertsev (Moscow) 28, 34; A. Amelchenko (Magnitogorsk) 25, 32, 36, 37; I. Ankudinov (Nalchik) 34, 36, 37; P. Antsferov (Fatezh) 34, 36, 38, 39, 40; V. Bakurov (Novosibirsk) 25, 28, 29, 32, 34, 36, 38, 40; A. Baraov (Moscow) 24, 28, 34, 40; A. Barsukov (Pyatigorsk) 28, 39; R. Basyrov (D. Karakityany Tat. ASSR) 28, 38, 40; M. Belkin (Pinsk) 24—29, 30, 32, 34, 36, 38—41; A. Belusov (Moscow) 28, 30, 32, 34; V. Bellev (Moscow) 28, 38, 40, 41; V. Benkhan (Kalinin) 37; S. Berezin (Kimry) 38; Yu. Blyakher (Dushanbe) 28; L. Bozemolov (Odessa) 33, 41; S. Borozdin (Novgorod) 25, 28, 29, 32; A. Braslavets (Novosibirsk) 34—36, 38, 40; I. Bramovskaya (Novosibirsk) 24; J. Buchinskas (Shilbsky district Lit. SSS) 34, 36, 38-40; I. Vandakurov (Leningrad) 28; S. Vasiliev (Leningrad) 22, 38-40; I. Vinyar (Oregev) 28, 38; A. Voletsov (Sverdlovsk) 36; P. Volokhov (village Criulani Mold. SSS) 40; A. Voskanyan (Yerevan) 24, 25, 28, 29, 34, 36; R. Gabdulin (Kazan) 37; D. Gabrilyan (Belaya Kalitva) 40; V. Gavrilok (Minsk) 40, 41; M. Gazda (Klevan village, Rivne region) 24-27; V. Galtsev (Orenburg) 38; A. Galochenko (Kharkov) 29, 30, 32, 34, 36; S. Garkusha (TASHKENT) 40; A. German (Voronezh) 25; S. Hertz (Khust) 32, 40; R. Girdyanis (Vilnos) 40, 41; Yu. Gladyo (Ternovol) 24; L. Glazman (Kharkov) 25, 26, 29, 30, 34-38; 40, 41; A. Grioriev (Grozny) 28; A. Griebere (Chisinau) 29, 40; S. Grishin (Vyazyvam) 36; M. Gulyansky (Magnitogorsk) 25, 30, 32, 38; A. Gurevich (Minsk) 25, 26, 28—32, 38, 40, 41; S. Davtyan (Oktemberyan) 34, 36, 38, 40, 41; A. Davydov (Magnitogorsk) 25, 29—32, 34, 36; S. Darkembaev (Alma-Ata) 26; S. Demidov (village of Sosnovka, Vologda region) 36; O. Denisov (Baku) 37; Yu. Dokuaev (Leningrad) 28-30, 38; N. Dubrovsky (Omsk) 38-41; R. Yegoryan (Yerevan) 25, 28, 31; G. Erkhanpetyan (Yerevan) 29, 31, 32; K. Zhakunbekov (village of Barshatas, Semipalatinsk region) 40; V. Zhelezov (Oktyabrsky village, Amur region) 36, 38, 40; V. Zhuk (Grozny) 27-29, 31, 32, 36, 38-41; S. Zazovsky (Novomoskovsk) 38; M. Zaks (Perm) 40; S. Zenovich (TASHKENT) 40; E. Zubko (Ivanov-Frankovsk) 25, 28, 29, 32, 34, 38, 40; V. Ivanov (Zheleznodorozhny) 28; V. Nenatev (Volgograd) 24-27; A. Izmailov (Baku) 34, 40; A. Ilkun (Zelenodolsk) 25, 38, 40; A. Kazkov (Rudny) 24; S. Kalyaev (Sosnovy Bor) 38; V. Kanzova (Deproederzhinsk) 24, 26; V. Karlin (Volokolamsky district, Moscow region) 24; V. Kachman (Mytschits) 38; M. Kachanovsky (Vishnevchi village, Brest region) 24, 25; V. Kovalevsky (Vitebsk) 24; L. Koran (Leningrad) 40; Y. Koran (Glazov) 24, 25, 32, 40; S. Korneev (Novokuznetsk) 25-27; S. Korshunov (Monno village, Moscow region) 24, 25, 38, 40, 41; L. Kofman (Tallinn) 24, 34, 40; I. Kotsearova (Rybinsk) 28; G. Koyava (Tskhinvali) 32, 36, 38; S. Krivonos (Dnepropetrovsk) 24, 25; I. Kryukov (Stayy Sambir) 28; N. Kudrin (Kolomna) 38, 40, 41; A. Kudryashov (Saratov) 36; V. Kuzmin (Grozny) 24, 40; P. Kuzmin (Ulan-Ude) 28-32; A. Kumanov (Frunze) 24; A. Kumiliumarov (Khorezm region. Uzbek SSS) 27, 27; I. Kutsik (Yaroslavl) 28, 30, 31, 36, 40, 41; R. Kucharov (Khorezm region. Uzbek SSS) 28, 32; Yu. Lavrov (Kanevskaya station, Krasnodar region) 32, 40; A. Levitas (Kyiv) 36; A. Lektsinov (Mines) 24, 28; A. Lukyanov (Dubovsky) 36; P. Lyedenov (Kizhinga village) 40; A. Lvov (Saratov) 28; S. Lyapin (p/o Blokorovich, Zhytomyr region) 24; V. Mazalov (Siauliai) 36, 40; M. Mashil (Yerevan) 24; A. Makartsev (Livov) 24, 34, 36-38, 40; A. Makarov (Kharkov) 36; S. Makarov (Saratov) 24, 26, 38-40; S. Maksimov (Alma-Ata) 37; G. Mamedov (Baku) 34—38, 40; Yu. Markin (Kharkov) 38; A. Markov (Moscow) 38, 42; S. Melnik (Kharkov) 24, 28, 32, 38, 40, 41; E. Mett (Leningrad) 36, 38, 40; L. Mirodoshvili (Tbilisi) 38-40; A. Molotkov (p/o Kubinka, Moscow region) 36, 38, 40; V. Momkovsky (Kyiv) 34; R. Musin (village Nikitino, Orenburg region) 24; R. Nazarudlov (Sterlitamak) 28, 29; I. Nikitin (Leningrad) 29; I. Nikitin (Severomorsk) 28; A. Nikolaev (Moscow) 24, 26, 28, 29, 31-32, 34, 36, 38-41; G. Odanisan (V. Artashat Arm. SSS) 36; A. Okun (Odesca) 28; S. Omelchenko (Zaporozhye) 36; S. Ochuntsin (Perm) 38, 40; R. Ospanov (Bayram-Ali) 25, 28, 31, 32; S. Ostrovskaya (Kharkov) 34, 38; A. Parovichnikov (Obninsk) 24; Yu. Perfilyev (Saratov) 36, 40; Yu. Pinelis (Kzyl-Orda) 24, 26, 28-30, 40-42; K. Piraminsky (Chisinau) 36, 40; O. Povalyaev (Podolsk) 24, 34, 36, 38-40; A. Poedulya (Ufa) 24, 34, 36; M. Polikarpov (Moscow) 24, 35, 36, 38, 40; V. Polyakov (Petropavlovsk) 37; A. Polyyansky (Chelyabinsk) 34; S. Polyarush (Zhabinka) 40; V. Prasolov (Voroshilovgrad) 31; V. Razin (Belorets) 38; A. Reznikov (Kyiv) 24; A. Remeev (TASHKENT) 33, 34, 36, 38-40; S. Rendzink (Stry) 34, 36, 37; V. Reshetnyak (Kyiv) 34, 40, 41; A. Reshetnyak (Kyiv) 34, 40, 41; Y. Ryapisov (Lomonosov) 25, 38, 40; Sh. Samtsev (Dangara district of Taj. SSS) 28, 29; V. Sviridov (Soronezh region) 39; R. Sereev (village of Perebrodye, Vitebsk region) 38; V. Sergeanov (village Sredne-Belyaya
