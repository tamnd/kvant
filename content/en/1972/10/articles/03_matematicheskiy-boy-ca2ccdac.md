---
id: 1972-10-matematicheskiy-boy-ca2ccdac
issue: kvant_1972_10
year: 1972
number: "10"
title: Math fight
rubric: smes
page_first: 18
page_last: 22
page_labels: 18, 20
tag: JOKV
lang: en
source: kvant_digital
extraction: vision
content_sha256: 6f45e55420b48c3e4d248d619dbb2aaced486c1949ca3b49fed1638e11559310
prompt_sha256: draft-1
translated_from: content/ru/1972/10/articles/03_matematicheskiy-boy-ca2ccdac.md
source_content_sha256: 8d57276f5a5b9e6ccac97a3348d5db161546df26e5bb4db91855b0df2c51d0cc
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio none⟧

MATHEMATICAL BATTLE

Below are the problems proposed at a mathematical battle held during a rally of students from a physics and mathematics school in Leningrad on January 7, 1972 (its rules are described in the article on page 71.)

1. Find integers $x$ and $y$ such that $(((x^x - y)^y)x - y)^x + x + y = 1972 + 1000x$.

2. Prove that from any 1972 integers one can choose exactly 972 whose sum is divisible by 972.

3. Is it possible to color points in three-dimensional space in three colors so that there is not a single segment entirely painted in one color?

4. Prove that the product of all numbers from $n+1$ to $2n$ is divisible by $2n$ and not divisible by $2^{n+1}$.

5. Construct a circle that divides each of three given equal circles into two equal parts.

6. Among the trigons of a given area, find the triangle with the greatest sum of relative medida to the corresponding bisectors.

7. The ticket has a six-digit number. A ticket is called a frequent Polingrad ticket if the sum of its first three digits is equal to the sum of the last three digits. A ticket is called a Vyshborsky-style ticket if its number is divisible by 11. Which tickets are more numerous: Leningrad-style or Vyshborsky-style tickets?

8. Is it possible to tile the plane of a quadrilateral equal to the given one?

9. Is it possible to obtain a regular pentagon using a plane of a cube?

⟦folio 18⟧

Indefinitely, from the definition of the integral it follows that the product function $S$ is the integral of the numerical function $f$. In particular, the area of ​​the entire subgraph of the function $f$ is equal to $\int_{A}^{B} f(x) \, dx$. The derived formula for the subgraph shows the geometric meaning of the integral: the integral of a non-negative function is the area of ​​the subgraph of this function. This is the basis for using the integral to calculate areas.

As an example, let us find the area of ​​the function cut off from the paraboles $y = x^2 + 1$ of the straight line $y = 2x + 1$.

The parabola and the straight line intersect at points whose coordinates (0, 1) and (2, 5) are found as solutions to the system of equations $y = x^2 + 1$, $y = 2x + 1$.

The required area (Fig. 6) is equal to the difference between the areas of the subgraphs of the function $x \rightarrow 2x + 1$ and $x \rightarrow x^2 + 1$, defined on the interval [0, 2]:

$$S = \int_{0}^{2} (2x + 1) \, dx - \int_{0}^{2} (x^2 + 1) \, dx =$$

$$= \int_{0}^{2} (2x - x^2) \, dx = 2 \int_{0}^{2} xdx - \int_{0}^{2} x^2 \, dx = \frac{4}{3}.$$

In general, if the graphs of the function $f$ and $g$ intersect at the points with the abscissa $A$ and $B$, and for all numbers $x$ of the segment $[A, B]$ the inequality $f(x) \geq g(x)$ is satisfied, then the area of the function enclosed between these subgraphs (Fig. 7) is equal $\int_{A}^{B} (f(x) - g(x)) \, dx$.

Exercise 1. a) Calculate the area of ​​the subgraph of the function $x \rightarrow x^2$ on the interval [0,1].

b) Calculate the area bounded by the sinus arch and the abscissa axis (Fig. 8).

2. Rotation body volume

Suppose that the subgraph of the non-negative function $f$, defining on the segment $[A, B]$, rotates around the x-axis. Let us associate each segment $[a, b]$ contained in the segment $[A, B]$ with the number $V [a, b]$—the volume of the part of the resulting rotation body enclosed between the planes $x = a$ and $x = b$ (Fig. 9).

⟦folio none⟧

We obtain an additive interval function $V$.

From figure 9 it is clear that the selected part of the body of revolution contains a straight circular cylinder, the height of which is the segment $[a, b]$, and the base radius is $\min f$ and is contained in a cylinder with the same height and base radius $\max f$. Since the volumes of these cylinders are equal to $\pi (b-a)(\min f)^2$ and $\pi (b-a)(\max f)^2$, respectively, then

$$\pi (b-a)(\min f)^2 \leq V [a, b] \leq \pi (b-a)(\max f)^2.$$

But $\pi (\min f)^2$ is the smallest value of the function $\pi f^2$ on the segment $[a, b]$, and $\pi (\max f)^2$ is its largest value on this segment. Consequently, $V$ is the integral of this function, so the volume of the entire body of revolution is equal to

$$\int \limits_A \pi f^2(x) \, dx.$$

As an example, let's calculate the volume of a right circular cone and the volume of a sphere.

A primordial circular cone of height $H$ can be considered as the result of rotating the subgraph of the linear function $x \rightarrow kx$ defined on the segment $[0, H]$ (Fig. 10). If the radius of the base of the cone is $R$, then

$$kH = R,$$

where

$$k = \frac{R}{H}.$$

Fig. 9.

Fig. 10.

⟦folio 20⟧

§ 2. PHYSICAL APPLICATIONS
INTEGRAL

In conclusion, we give several examples of the application of the integral in physical problems.

Task 1. Let us find the static interaction between a material point of mass m located on the same straight line and a homogeneous rod of length l and mass M. The distance from the point to the nearest end of the rod is c.

You, of course, know the law of universal gravitation, which states that the force of gravitational interaction between two exact masses is proportional to the product of these masses and inversely proportional to the square of the distance between them. However, in our case, one of the mass interactions is not exact.

If the rod is divided into several parts, then the sum of the forces of interaction of these parts with mass m is equal to the force of interaction of the entire rod with this mass. Generally, physicists further write: “divide the rod into very small segments of length Δx. A force $\frac{mM\Delta x}{lx^2}$ acts on a segment located at a distance x from point m, the sum of these forces is equal to...”

Let us show how one can formulate such strict dissections and use our definition of an integral.

Let us turn the straight line on which the rod and the point lie into a numerical reference by choosing as the starting point the point at which the mass m is placed and directing the axis so that the rod is on the positive strip. The rod will then enter the segment $[c, c + l]$ of this axis. For each segment $[a, b]$ contained in segment $[c, c + l]$, we assign a number F $[a, b]$—the magnitude of the interaction forces between this segment of the rod and the mass m. It is clear that F is an additive function of the interval. It is clear that this force will increase if the total mass of the segment $[a, b]$, equal to $\frac{M}{l}(b - a)$, is concentrated at end a of this segment close to the mass m, and will decrease if this mass is concentrated at point b. But in any case, we will come to the interaction of two exact masses. In the first case, the interaction force turns out to be equal to $\frac{\gamma mM}{la^2}(b - a)$, in the second case $-\frac{\gamma mM}{lb^2}(b - a)$. Therefore, $\frac{\gamma mM}{lb^2}(b - a) \leq F[a, b] \leq \frac{\gamma mM}{la^2}(b - a)$.

But $\frac{\gamma mM}{lb^2} = \min_{[a, b]} \frac{\gamma mM}{lx^2}, a \frac{\gamma mM}{la^2} = \max_{[a, b]} \frac{\gamma mM}{lx^2}$.

Therefore, the additive function of the interval $F$ is the integral of the function $x \rightarrow \frac{\gamma mM}{lx^2}$. The entire force of gravitational attraction between the rod and the point is equal to

$$\int_{c}^{c+l} \frac{\gamma mM}{lx^2} dx = \frac{\gamma mM}{l} \int_{c}^{c+l} x^{-2} dx = \frac{\gamma mM}{l} (-1) \left[ (c+l)^{-1} - c^{-1} \right] = \frac{\gamma mM}{l} \left( \frac{1}{c} - \frac{1}{c+l} \right) = \frac{\gamma mM}{c(c+l)}$$

You know that the force of gravitational attraction is also calculated according to the law of universal gravitation. The proof is valid for spherical masses of the same formula as for exact ones, subsequent for Newton as one of the points towards the creation of the integral number.

Task 2. Find the kinetic energy of a homogeneous disk of radius R and mass M, which is moving with a constant angular velocity w of velocities, passing through the center of the disk and perpendicular to its plane.

The kinetic energy of a moving point depends on mass and speed. Although the disc is treated with constant
