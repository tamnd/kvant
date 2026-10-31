---
id: 1975-10-manevich-slutskin-evm-v-konstruktorskom-byuro-e7f6965e
issue: kvant_1975_10
year: 1975
number: "10"
title: Computer in the design bureau
authors:
  - Маневич М. А.
  - Слуцкин М. М.
rubric: raznoe
page_first: 26
page_last: 31
page_labels: 24-29
tag: DYOM
lang: en
source: kvant_digital
extraction: vision
content_sha256: 7364d3ab7cecf01b8fb8581269f18963b6cf48ee1e1114e599e51f2a6f68697c
prompt_sha256: draft-1
translated_from: content/ru/1975/10/articles/14_manevich-slutskin-evm-v-konstruktorskom-byuro-e7f6965e.md
source_content_sha256: 9fda681d8b29bcf7d0c6362d4a5a2ee25a129edba5dc4d52715dd60c209e4492
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 24⟧

At present, in connection with the advent of drawing machines controlled by electronic digital computers, a real possibility has arisen of automating many graphic works carried out in design bureaus. Such work includes process drawings of mechanical engineering parts, surface developments, axonometric (volumetric) images, etc. The use of automatic drawing machines and computers provides an invaluable service to design engineers developing surface drawings of technical forms.

Epirus Monge
Let us first explain how a projection drawing is constructed.
Let us choose a rectangular Cartesian coordinate system $Oxyz$ (Fig. 1, a) in space. Let us denote the coordinates of the plane $xOy, xOz, yOz$, respectively, by $H, V, W$, and we will call them projection planes.
Let us lower onto them from an arbitrary point $A$ inside the first octane $x \geq 0, y \geq 0, z \geq 0$ the perpendiculars $Aa, Aa'$ and $Aa''$: a - horizontal, a' - frontal, a' - profile projections of point $A$. By rotating the planes $H$ and $W$ around the axes $Ox$ and $Oz$, we combine them with the plane $V$. Then in one plane $V$ we will receive an image of the spatial coordinate system $Oxyz$ and the projections of the point $A$ (Fig. 1, 6; in the future we will denote space points in capital letters, and their projections in the same lowercase letters with primes). The projections of figures are constructed in a similar way - points can be drawn.

Analyzing figure 1, we come to the conclusion that the point $A$ of space is completely defined by two properties, for example, $a$ and $a'$. This

⟦folio 25⟧

follows from the fact that its abscissa $x = Oa_x$, ordinate $y = a_x a'$ and applicate $z = a_x a'$ are uniquely determined from the drawing. Thus, to define a figure, it is enough to have its projections.

The drawing obtained by the described method is called a projection drawing, Monge diagram*) or a complete drawing.

Construction of lines of intersection of surfaces

The designer is standing behind the culm. He draws an image of some detail. In some places the surface of the part has sharp transitions, ledges, holes, and notches. Here appeared in the drawing images of two cylindrical surfaces, which are formed like a step in the part. The designer stayed. "What's the matter?" - you ask. “We hit the crossing line again, but it doesn’t matter! Now I’ll build several points that belong to two surfaces, and then I’ll draw a smooth curve through them along the pattern,” says the designer. And so individual points of intersection lines began to appear on the drawing.

From the point of view of graphic operations, constructing lines of intersection of a surface to finding its individual points. For this

*) Gaspard Monge (1746-1818) - French geometer.

Fig. 2.

Data surfaces $\Phi_1$ and $\Phi_2$ (Fig. 2) cut the third auxiliary surface T (if bracing surfaces intersect, then spheres and planes are most often used as auxiliary surfaces), and then determine the intersection lines $m$ and $n$ of the auxiliary surface T with two data $\Phi_1$ and $\Phi_2$ and the intersection point K constructed lines. This technique is repeated many times so that the resulting points can be connected with a smooth line.

Example 1. Construct the intersection lines of a sphere and a straight steep cone specified in the projection drawing (Fig. 3).

Let us choose an arbitrary plane T parallel to the horizontal projection plane. This plane cuts the sphere and cone along the circles $m$ and $n$ respectively, intersecting at points $K_1$ and $K_2$. By constructing these circles on the horizontal projection plane, we obtain points

⟦folio 26⟧

$k_1$ and $k_2$, belonging to the horizontal projection of the lines of intersection (Fig. 3). The frontal projections $k'_1$ and $k'_2$ of points $K_1$ and $K_2$ will coincide in this case. Having done this for a number of auxiliary planes parallel to $T$, we obtain points common to the sphere and cone, and by connecting them with smooth curves on each projection, we obtain approximate projections of the intersection lines. The more points are plotted, the more accurate the curve will be.

But no matter how hard we try, the accuracy of such constructions is limited, the resulting intersection line is far from ideal, and the time spent is significant. These shortcomings can be eliminated with the help of a computer and a drawing machine. Indeed, a computer performs millions of actions in a matter of seconds, and some modern drawing machines draw straight sections longer than 300 mm in one second.

When automating the process of constructing intersection lines in a drawing, the following steps are performed.

1) The equations of the surfaces specified in the drawing are written.

2) Using a computer, the coordinates $x$, $y$, $z$ of individual points of the intersection lines are determined (from an analytical point of view, determining the intersection lines is a property of solving a system of equations).

3) The coordinates of the obtained points are fed to the drawing machine in the form of special pen movement commands.

Each stage is an independent task, sometimes not easy. Let us explain them in more detail using example 2, similar to example 1. For simplicity of further reasoning, we choose a coordinate system so that the $Oz$ axis aligns with the cone axis, and the $x$ axis passes through the center of the sphere.

Example 2. Names of lines of intersection of a sphere of radius $r=50$, center

which has coordinates $x_0=30$, $y_0=0$, $z_0=0$ in the Cartesian direct coordinate system $Oxyz$, and a right circular cone, the vertex of which lies on the $Oz$ axis at the point $x_1=y_1=0$, $z_1=70$, the axis coincides with the $Oz$ axis, and the diameter of the base touching the sphere is 120 (this data is taken from figure 4, scale at figure indicated).

First stage. Let us first consider a sphere with center at the origin and radius $r$ (Fig. 5). Let us take an arbitrary point $M$ on its surface. Let its coordinates be $x$, $y$, $z$. It is not difficult to prove (using the Pythagorean theorem) that for the point $M$ the following equality will hold:

$$x^2 + y^2 + z^2 = r^2.$$

This equality is satisfied by the coordinates of any point lying on the surface of the sphere, and not by the coordinates of points not lying on the surface of the sphere. This equality is the equation of the sphere.

⟦folio 27⟧

Fig. 5.

The equation of a sphere of radius 50, the center of which is 30 units higher along the $Ox$ axis (this is the sphere given in example 2), will be

$$(x-30)^2+y^2+z^2=50^2.$$

It can be shown that

$$x^2+y^2-\frac{1}{4}(z-70)^2=0$$

is the equation of a right circular cone given on figure 4. For a fixed $z=z_0$, it takes the form $x^2+y^2=\frac{(z_0-70)^2}{4}$ and defines the circularity - the section of the cone by the plane $z=z_0$.

In this example, we quickly wrote the surface equation due to its simplicity. But, generally speaking, the equation of the surface specified in the drawing must be derived. This is the task of the first stage.

So we have the following system of equations:

$$\begin{cases}
x^2+y^2-\frac{1}{4}(z-70)^2=0, \\
(x-30)^2+y^2+z^2=50^2.
\end{cases}$$

Second stage. Let us subtract the second from the first equation of the resulting system. After simple transformations we obtain the expression

$$x=\frac{1}{48}z^2-\frac{7}{12}z-\frac{75}{12},$$

which is the equation of the frontal projection of the lines of intersection.

Equation (*) defines the paraboly, part of which is depicted in figure 4.

Considering now the horizontal projection, from the system we obtain:

$$x^2+y^2-\frac{1}{4}(V\sqrt{50^2-(x-30)^2-y^2}-70)^2=0.$$

You can’t tell right away which line this equation describes.

To construct both curves on the projections, the variable $z$ in equations (*) will be given sequential values ​​(for example, with a step $\Delta z=0,1$) within the limits of - 42.5 $\leq z \leq 46,5$ (these limits correspond to the extreme points $1'$ and $2'$ on the frontal projection, see Fig. 4). For each value of the variable $z$, we first calculate the value of the variable $x$ using the formula (*), and then (from the equation of the sphere) find the value $y$ using the formula

$$y=\pm \sqrt{50^2-z^2-(x-30)^2}.$$

This calculation process is easily carried out on a computer. Thus, the computer will calculate and print the coordinates $x, y, z$ of more than 200 points of intersection lines in a short period of time. These coordinates must be sent as a command to the drawing machine. The third stage begins.

Drawing machine

There are different types of drawing machines that interface with computers in different ways. Modern drawing machines (they are often called *strapho-builders*) such as Itecan (USSR), Benson (France; see Fig. 6), Digigraph (Czechoslovakia) can operate from both punched paper tape and magnetic tape, to which a computer outputs information. A drawing machine can be interfaced with a computer through a special electronic device connection.

Most existing drawing machines are made with linear

⟦folio 28⟧

Fig. 6.

linear and circular interpolation. This means that if you specify the coordinates of two points $A$ and $B$, then the pen of the drawing machine can draw either a straight line segment $AB$ or a circular arc passing through points $A$ and $B$ (in this case, its center is additionally specified). Since the computer calculates the coordinates of a sufficiently large number of points, the broken line drawn with the machine's pen (hereinafter in the form of segments) turns out to be quite smooth.

Construction of aconometric images

When designing various dies, it is necessary to draw not only a projection drawing, but also an aconometric image of the surface. How to teach a drawing machine to draw an aconometric image?

figure 7 shows an image of an arbitrary point $A$ in the aconometric axes $Ox, Oy, Oz$. This point has three coordinates, and its image is constructed according to certain geometric rules. But the drawing machine does not know these rules, nor what the aconometric coordinates $x, y$ and $z$ are. It works on two axes, for example $x'$ and $y'$. An arbitrary point $A (x, y, z)$ has some two coordinates along these axes. Obviously, there must be a connection between the coordinates $x'$

and $y'$ and aconometric coordinates $x, y, z$ for an arbitrary point on the plane. This connection is known and written as follows:

$$x' = a_{11}x + a_{12}y + a_{13}z,$$
$$y' = a_{21}x + a_{22}y + a_{23}z,$$

(**)

where $a_{ij} (i=1,2; j=1,2,3)$ are numbers that take on certain values ​​for a given choice of axes.

For example, for isometrics (in this case, the axes are drawn at angles $120^\circ$ to each other), equations (**) take the following form:

$$x' = -\frac{\sqrt{3}}{2}x + \frac{\sqrt{3}}{2}y,$$
$$y' = -\frac{1}{2}x - \frac{1}{2}y + z.$$

Thus, the computer must reread the coordinates $x, y, z$ using formulas (**) and submit them in the required sequence to the drawing machine, which draws the aconometric image.

Construction of surface developments

Let us imagine the surfaces as a flexible, but unbreakable, curved film. There are surfaces that can be deformed and aligned with the plane so that there are no breaks or folds. Such surfaces are called developing surfaces, and the figure obtained after combining them with a plane is called a development.

⟦folio 29⟧

Fig. 8.

The idea of ​​graphically constructing a surface development is as follows: a diverse surface F fits into the surface, the flat faces of which are usually triangles. Then all life-size faces are constructed on the plane in a certain sequence.

Example 3. Construct a development of an inclined cone with a circular base specified in the projection drawing (Fig. 8).

We proceed as follows. We divide the base of the cone with points $A_1, A_2, \dots$ into $n$ equal parts, for example, into 16, and connect them with the vertex $S$. Then in the drawing we will get two projections of an inclined paramid (with triangular faces) inscribed in a cone. Now we need to construct the faces of the paramid in full size. Let's consider the face $SA_1A_2$. Its horizontal projection will be $s_a1a_2$, frontal - $s'a'1a_2$. It is easy to see that $s'a'1$ is the natural value of the side $SA_1, a_1a_2$ is the natural value of the side $A_1A_2$. To find the natural size of the side $SA_2$, we cover it around the vertical axis passing through the vertex $S$, so that it becomes parallel to the frontal plane of the projection $V$ ($s_a2$ on the horizontal projection). From the resulting point $a_2$ we draw a connection line until it intersects with the frontal projection of the base of the cone at the point $a_2'$ - $s'a'2'$ and the natural size of the side $SA_2$ will be. The lines side $SA_3, SA_4$, etc. are found similarly.

Now, on a separate sheet of paper, we will construct the face $SA_1A_2$ (Fig. 9), attach the face $SA_2A_3$ to it, etc. As a result, we will obtain a development of an inclined paramid, which will be an approximate development of an inclined cone.

As the number of faces of the inscribed paramid increases, the development becomes more and more accurate, but its construction manually becomes practically impossible. The position decreases by the computer, which, according to a given program, calculates the coordinates of the point $A_1, A_2, A_3, \dots$ in a certain coordinate system and sends them to the drawing machine in the form of a pen movement command. If there are a large number of points, the segments of the broken line will be small, and the line drawn by the machine will be a smooth curve.
