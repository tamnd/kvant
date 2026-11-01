---
id: 1988-10-bendukidze-ferma-ischet-ekstremumyi-2387deb5
issue: kvant_1988_10
year: 1988
number: "10"
title: The farm is looking for extremes...
authors:
  - Бендукидзе А. Д.
rubric: shkola-v-kvante
page_first: 47
page_last: 50
page_labels: 45-48
tag: 6XMF
lang: en
source: kvant_digital
extraction: vision
content_sha256: 4f42b6f39a96af2d234632dcd7f27eb8702aabe901803a85160cd7ac965d6599
prompt_sha256: draft-1
translated_from: content/ru/1988/10/articles/12_bendukidze-ferma-ischet-ekstremumyi-2387deb5.md
source_content_sha256: 804b8495448a8faae76856ade74d9fcd0fbc7c548b239bb77d970d4a4227c5f1
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 45⟧

Math 9, 10

The publishing note is addressed to the 10th and 10th classics students.

The farm is looking for extremes...

Candidate of Physical and Mathematical Sciences
A. D. BENDUKIDZE

There are many problems that require finding the most or most value of some variable. Let's take the following problem for example. Using a fence 4a long, you need to fence off a straight section of the largest area. What should be the size of the plot?

Solving this problem is not difficult. In fact, let the length of the section be x. Then its width will be 2a-x, and its area x(2a-x). The point is to find x, for which the function S(x)=2ax-x² takes on the greatest value. And for this it is enough to replace that S(x)=a²-(x-a)²≤a²,

Moreover, equality is achieved only for one value of x: for x=a. But then 2a-x=a, i.e. the area should have the shape of a square.

It is not always possible, however, to solve such problems using elementary methods. Here is an example: find the dimensions of a right parallelepid of the largest volume with a square base if the sum of the length of the side of this square and the height of the parallelepid is equal to a.

It is clear that if the length of the side of the base is denoted by x, then the volume of the parallelepid will be equal to x²(a-x). So, it is necessary to find a value of x (0<x<a) for which the function v(x)=x²(a-x)

takes on the most meaning. How

⟦folio 46⟧

It is impossible to solve this problem in an elementary way. What to do?

The reader is probably thinking: why split hairs? Let's calculate $v'(x)$, solve the equation $v'(x)=0$, find the critical points and see at which of the found points our function has the most value - it's very simple!

According to this, the easiest way is to follow the scheme outlined in the textbook “Algebra and the beginnings of analysis.” Of course, using an arbitrary entity makes it easier to study the function - finding intervals of increasing and decreasing, extrema, as well as the largest values.

But still, is it possible to do without the free program? Is it possible that earlier, before the invention of the arbitrary program, scientists did not solve problems of this type? We decided in a way we never decided! But often it was necessary to resort to very clever transformations or geometric constructions. In other words, for the time being there was no single method suitable, if not for all, then at least for a fairly broad class of problems.

The first to find such a method was the general French mathematician Pierre Fermat, whose life and work were discussed more than once in «Kvant». For example, in the article by I. G. Bashmakova “Pierre Fermat” («Kvant», 1976, No. 8) the well-known Fermat rule for finding extrema is given, which the author himself successfully applied to draw tangents. If we use modern symbols, this rule can be written as follows.

To find the extremum of some function $f$, depends on $x$, next find $f(x+h)$, where $h$ is small enough, and write the approximate equality $f(x+h) \approx f(x)$. Simplify the resulting equality and divide it by $h$ or by the highest possible degree $h$, you should discard the terms that still contain $h$, and replace the approximate equality with an exact one. We obtain an equation whose roots will be exactly those values ​​of $x$ for which $f$ can have an extremum.

Having formed this rule, and it was arbitrary no later than 1629, Fermat solves the following problem as an example: “Divide the segment $AC$ by the point $E$ so that the rectangle on the sides $AE$ and $EC$ is the largest in area.” The reader, of course, agreed that this is exactly the problem that we solved at the beginning.

Let's see how it is solved using Fermat's rules.

Let us keep the same notation: the empty lengths of the segments $AC$ and $AE$ are equal to 2$a$ and $x$, respectively. Equating (in Fermat’s sense!) $S(x+h)$ and $S(x)$, where $S$ is the area of ​​the rectangle, we obtain:

$$(x+h)(2a-x-h) \approx x(2a-x).$$

After moving the rules of the part to the left, opening the brackets and reducing it to $-h$ we get: $2x-2a+h \approx 0$. Dropping the term containing $h$ and replacing the approximate equality of the point, we find: $x=a$. The required rectangle is a square.

Let's get acquainted with another problem considered by Fermat: “Calculation of a given line $AC$ at point $B$ so that the body constructed as a square from side $AB$ and with height $BC$ is the largest.”

It is clear that the Truss has a right parallelepid of the largest volume with a square base, provided that the sum of the side of the base and the height is given. And this is the task formulated above! For it $v(x)=x^2(a-x)$, and, according to Fermat’s instructions, we have:

$$(x+h)^2(a-x-h) \approx x^2(a-x),$$
$$2axh-3x^2h-3xh^2+ah^2-h^3 \approx 0,$$
$$2ax-3x^2=0.$$

So, $x=0$ or $x=2a/3$. The first root is not suitable - after all, it was said above that $0<x<a$. The second remains, i.e. the parallelepid has the largest volume if the sides of the base are twice the height.

Is the result obtained correct? To answer this question, we are prematurely correcting Fermat's rule itself. Next

⟦folio 47⟧

It is worth noting that Fermat at first only formulated the formulation of his rule, but later substantiated it. Using the example of the function $v$, let us trace the course of Fermat’s calculation.

Let $v$ reach its maximum value at the value of the argument $x_0$. Then for any how small positive $h$ there must be:

$$\begin{cases} v(x_0) \geq v(x_0 - h), \\ v(x_0) \geq v(x_0 + h). \end{cases}$$

Recall that $v(x) = ax^2 - x^3$, after elemental transformations and reduction by $h$, the system can be represented in the following form:

$$\begin{cases} (2ax_0 - 3x_0^2) - (a - 3x_0 + h)h \geq 0, \\ (2ax_0 - 3x_0^2) + (a - 3x_0 - h)h \leq 0. \end{cases}$$

Let us prove that these relations imply the equality $2ax_0 - 3x_0^2 = 0$. Indeed, let $2ax_0 - 3x_0^2 \neq 0$. Let's take $h$ small enough to be $h|a - 3x_0 \pm h| < |2ax_0 - 3x_0^2|$.

This, due to the arbitrary smallness of $h$, can always be achieved. But then the expressions

$$(2ax_0 - 3x_0^2) - (a - 3x_0 + h)h$$

And

$$(2ax_0 - 3x_0^2) + (a - 3x_0 - h)h$$

either both positive (if $2ax_0 - 3x_0^2 > 0$) or both negative (if $2ax_0 - 3x_0^2 < 0$). And this contradicts system (1). So, $x_0$ must be the root of the equation $2ax - 3x^2 = 0$, which proves the correctness of the result obtained (the existence of an exceptional parallelepiped is beyond doubt!).

Fig. 1.

As you can see, the Fermat rule is quite simple and at the same time effective. But more importantly, these Fermat rules actually lead to derivatives!

In fact, after all, he is after the correct zero expression

$$\frac{f(x+h) - f(x)}{h}$$

discards terms containing $h$ or its higher powers, and replaces the approximate equality with an exact one. And this is equivalent to going to the prelude in expressions (2) provided that $h$ tends to zero, i.e. finding an arbitrary $f'(x)$. In other words, Fermat’s rule can be represented as the following diagram:

$$f(x+h) \approx f(x),$$
$$f(x+h) - f(x) \approx 0,$$
$$\frac{f(x+h) - f(x)}{h} \approx 0,$$
$$\lim_{h \to 0} \frac{f(x+h) - f(x)}{h} = 0,$$
$$f'(x) = 0.$$

So, the necessary condition for the existence of an extremum, expressed by the mentioned rule, is nothing more than the well-known to us... Fermat's theorem!

By the way, Lagrange, Laplace and Fourier believed that Fermat’s rule was the beginning of the creation of differential calculus. They did not know the opinion of the great Newton - I share that in one letter, first published only in the thirties of our degree (more than two hundred years after the death of its author!), Newton unequivocally states: “I received a hint of the method from Fermat’s method of drawing tangents; By applying it to abstract direct and inverse equations, I made it general.” It should be noted here that the method mentioned by Newton is his fluxey method, i.e., what we now call differential and integral calculus, and the method is nothing more than his rule, which we discussed above. Let's look at how it can be used to draw tangents.

⟦folio 48⟧

Let a line $y=f(x)$ and a point $P=(x_0, y_0)$ on it be given, and we need to check the tangent to the line at this point. Let us assume that the tangent $PT$ has already been drawn (Fig. 1). Let's take another point $Q=(x_0+\Delta x, y_0+\Delta y)$ on the line and denote the point of intersection of the vertical line $BQ$ with the tangent by $C$. From the similarity of triangles $TAP$ and $TBC$ we have:

$$\frac{TB}{TA} = \frac{BC}{AP}.$$

In this proportion, we replace the segment $BC$ with $BQ$. We get:

$$\frac{TB}{TA} \approx \frac{BQ}{AP},$$

or, what is the same,

$$\frac{TA+AB}{TA} \approx \frac{BD+DQ}{AP}.$$

But $BD=AP$, which means

$$\frac{AB}{TA} \approx \frac{DQ}{AP}.$$

Considering that $AB=\Delta x$, $AP=y_0$, $DQ=\Delta y=f(x_0+\Delta x)-f(x_0)$, the resulting approximate equality can be rewritten as follows:

$$\frac{y_0}{TA} \approx \frac{f(x_0+\Delta x)-f(x_0)}{\Delta x}.$$

(3)

It remains to apply Fermat's rule. Namely, in the expression

$$\frac{f(x_0+\Delta x)-f(x_0)}{\Delta x}$$

perform division, discard terms that still contain $\Delta x$, and replace approximate equality (3) with exact one. Thus, we will find the length of the segment $TA$, and therefore the point $T$, after which drawing a tangent is not difficult.

Let's look at a specific example.

Let this line be the parabola $y^2=2px$ (Fig. 2). For it, equality (3) has the following form*):

$$\frac{y_0}{TA} \approx \frac{\sqrt{2p(x_0+\Delta x)}-\sqrt{2px_0}}{\Delta x}.$$

Let us transform the rule part of this equality:

$$\frac{\sqrt{2p(x_0+\Delta x)}-\sqrt{2px_0}}{\Delta x} =$$

$$= \frac{2p(x_0+\Delta x)-2px_0}{\Delta x(\sqrt{2p(x_0+\Delta x)}+\sqrt{2px_0})} =$$

$$= \frac{2p}{\sqrt{2p(x_0+\Delta x)}+\sqrt{2px_0}}.$$

Discarding the term containing $\Delta x$ in the last expression, substituting the result in (4), and replacing the approximate equality with an exact one, we obtain:

$$\frac{y_0}{TA} = \frac{p}{\sqrt{2px_0}}.$$

But $y_0=\sqrt{2px_0}$, which means $TA=2x_0$, i.e. $T=(-x_0, 0)$; remains more vertical than the points $P$ and $T$. Problem solution!

*) For definition, let $y_0>0$.

To our readers

Subscription to the magazine «Kvant» for 1989 continues.

The magazine is intended for students in grades 6–10. It is useful for teachers, especially those who teach clubs and extracurricular activities, and for all lovers of mathematics and physics.

In the new year, the volume of the magazine increases and the sections expand.

The journal index in the Soyuzpechat catalog is 70465.

The subscription price for one issue is 45 kopecks.

Subscriptions are accepted without restrictions throughout the year and from any number at Soyuzpechat agencies, post offices and post offices.
