---
id: 1977-2-hinchin-geometricheskiy-smyisl-proizvodnoy-5e49808b
issue: kvant_1977_2
year: 1977
number: "2"
title: Geometric meaning of derivative
authors:
  - Хинчин А. Я.
rubric: po-stranitsam-shkolnyh-uchebnikov
rubric_sub: По страницам школьных учебников
page_first: 37
page_last: 38
page_labels: 35-36
tag: 9ZVY
lang: en
source: kvant_digital
extraction: vision
content_sha256: c8e2988b3fee3f56b4d6c7379791a581600b1eb910597a7fdb2cb60a1eb13dab
prompt_sha256: draft-1
translated_from: content/ru/1977/02/articles/13_hinchin-geometricheskiy-smyisl-proizvodnoy-5e49808b.md
source_content_sha256: e980a18f7c80b35b558c070f267e31b171454868abac7c54a9ce23d8e1faf211
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 35⟧

A. Khinchin

Geometric meaning of derivative

In ninth grade, during algebra lessons, you learned the definition of the derivative of a function. The concept of derivative is one of the main ones in mathematical analysis. We are presenting a story about the geometric illustration of the derivative, which is equally important for both analysis and geometry, which is given little time in school (see “Algebra 9”, paragraph 52). We took this story from the “Short Course in Mathematical Analysis” by the famous Soviet mathematician and teacher Aleksandr Yakovlevich Khinchin (1894-1959)*.

The geometric representation of a function serves as an extremely valuable tool for their study, primarily because the many details in the behavior of the function, which were difficult to read when it was specified using a formula (and even more so a table), appear on the graph with complete clarity and are absent to the eye. Any feature of a given function, when depicted graphically, should act as a certain geometric property of the depicted curve. In particular, we can imagine in advance that a drawing depicting a function also gives us a visual representation of its derivative.

Let us represent the function $y=f(x)$ in the Cartesian coordinate system $(x; y)$ (Fig. 1). Let us mark the points $M(x; y)$ and $N(x+\Delta x; y+\Delta y)$ on the curve. Let's take MP pa-

*) A. Ya. Khinchin, “Short course in mathematical analysis”, M., Gostekhidat, 1957.

axis $OX$. Obviously, in the right triangle $MNP$ the legs are $MP=\Delta x$ and $NP=\Delta y$. Therefore, the ratio $\frac{\Delta y}{\Delta x}$ is equal to the tangent of the angle $\varphi$ formed by the chord $MN$ with the positive direction of the axis $OX$.

Let us now make $\Delta x$ tend to zero. In this case, point $M$ will remain motionless, and point $N$ will approach it indefinitely. The chord $MN$ will change its direction, and at each moment of this process the angular coefficient of this chord is

$$tg\varphi=\frac{\Delta y}{\Delta x};$$

if a given function has a derivative at the point $x$, i.e. if there exists

$$\lim_{\Delta x\to 0}\frac{\Delta y}{\Delta x}=f'(x)=y',$$

then geometrically this means that the direction of the chord $MN$ tends to a certain limiting direction $MT$, forming an angle $\alpha$ with the positive direction of the axis $OX$, and

$$tg\alpha=\lim_{\Delta x\to 0}tg\varphi=\lim_{\Delta x\to 0}\frac{\Delta y}{\Delta x}=y'.$$ (1)

The primula $MT$, which can be defined purely geometrically as the limiting position of the secant $MN$ connecting the point $M$ with another point $N$ infinitely close to it, is called the poop to the given curve at the point $M$. Equality (1) shows that the derivative function $f(x)$ at point $x$ is equal to the slope

Fig. 1.

⟦folio 36⟧

Fig. 2.

shallow to the corresponding curve at the point with the abscissa $x$. If, as is usually done, we assume (in good agreement with our visual representation) that the direction of the tangent characterizes for us the direction of the curve itself at a given point, then we immediately see that if the curve (with increasing $x$, i.e. from left to right) rises, then its derivative is non-negative, and the steeper the rise, the greater the value of the derivative; Having directed, where the curve (from left to right) descends, the derivative is non-positive, and here, too, the abscissa value of the derivative is greater, the steeper the descent.

The geometric image of the derivative that we have found allows us to clearly understand examples of the absence of a derivative. Figure 2 gives us the graph of the function $y = |x|$, and figure 3 gives us the graph of the function $y = x \sin \frac{1}{x}$. In the first case, the line $y = |x|$ with $x = 0$ has a certain direction to the right and a certain direction to the left, but these two directions are different from each other; in the second case, the curve $y = x \sin \frac{1}{x}$ at point $x = 0$ has no definite direction either to the right or to the left (absence of a tangent): as $|x|$ becomes smaller and smaller, the direction of the secant again and again fluctuates between straight lines $y = x$ and $y = -x$ and therefore cannot tend to any limiting direction.

Finally, from the point of view of the geometric interpretation of the derivative, it is easy to understand why this should prevail in that every continuous function must

Fig. 3.

it has a derivative (except, perhaps, at some special points): indeed, it is very difficult to imagine a continuous curve that would not have a tangent at any point; and even now, when the existence of such curves is clearly established, we can only very approximately imagine their course; such a curve in the neighborhood of each of its points is located approximately the same as the curve figure 3 in the neighborhood of the point $O$. Be that as it may, such curves are significant, and their discovery was one of the most striking examples in the history of mathematics of how the intuition that has dominated for centuries can all turn out to be wrong.

Let us also note that knowing the value of the derivative $y'$ at the point $x$ obviously allows us, using elementary examples, to construct the tangent to the curve $y = f(x)$ at the point $M$. Elementary geometry teaches us to construct tangents to a circle, in analytical geometry we learn to find tangents to all second-order curves, but only differential calculus allows us to pose and solve the general problem of drawing a tangent to a derivative of a curve at any given point.

And now, as an exercise, we offer readers several problems on tangents to curves.

Quests

1. $y$ parabolas $y = \frac{4x - x^2}{4}$ tangents are drawn at points $(0; 0), (2; 1), (4; 0)$. Find their angles of inclination to the $Ox$ axis. (9 grades)

2. Find the angle of inclination of the tangent to the hyperbola $xy = a^2$ at point $(a; a)$. (9 grades)

3. a) At what angle does the curve $y = \ln x$ intersect the axis $Ox$?
