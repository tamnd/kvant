---
id: 1975-12-vilenkin-mordkovich-chto-takoe-proizvodnaya-855e8753
issue: kvant_1975_12
year: 1975
number: "12"
title: What is a derivative
authors:
  - Виленкин Н. Я.
  - Мордкович А. Г.
rubric: osnovnye-stati
page_first: 12
page_last: 19
page_labels: 10-17
tag: 8H76
lang: en
source: kvant_digital
extraction: vision
content_sha256: 1b8ea50dd17d27f4d9035733c853afb401acca50dd64e201d82a0aead3e3a242
prompt_sha256: draft-1
translated_from: content/ru/1975/12/articles/03_vilenkin-mordkovich-chto-takoe-proizvodnaya-855e8753.md
source_content_sha256: cb9b2e79565096ed417284c7afa22d18cd6647ab6c645512d7d84b545ab1b659
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 10⟧

1. Secrets of planetary orbits

Ancient Greek scientists were able to solve only weak kinematics problems - they could calculate either uniform rectilinear motion or uniform rotation around an axis. But it was not possible to describe the movement of planets using columnar methods.

The planets moved along the most intricate curves, sometimes moving quickly forward, and sometimes slowing down their movement and even going back. To brighten things up, the Alexandrian astronomer Ptolemy, who lived in the 3rd century. BC e., came up with a very complex system of circles; the centers of the small circles of the uniform rotated around the larger ones, and the planets of the uniform rotated around the small circles. But Ptolemy’s system did not agree with observations, and it had to be complicated all the time. Only in the 17th century did the German scientist Jurann Kepler manage to formulate the laws of planetary motion on the basis of the gel-centric system of the world created by the great Polish astronomer Nicolaus Copernicus.

It turned out that the planets move not in circles, but in ellipses, and unevenly. Kepler could not explain why this was so - at that time neither the general laws of mechanics nor mathematical methods were known that made it possible to study curvilinear and uneven motion.

Only at the end of the 17th century, Isaac Newton discovered the laws of dynamics, formulated the law of universal gravitation and developed mathematical methods that allowed the properties of non-uniform to uniform, non-uniform to homogeneous, curvilinear to rectilinear. It was based on a simple idea - the movement of any body over a short period of time can be approximately considered as rectilinear and uniform.

Methods developed by Newot for the occurrence of a given law of motion of a body, find its speed and acceleration at any moment of time, and also solve the inverse problem - given a given acceleration, first find the speed, and then the law of motion of the body. And if we remember that, according to the second law of Ubior, the acceleration of a body of constant mass is proportional to the force acting on it, then it will become clear that the new methods established a connection between the movement of the body and the forces acting on it, that is, they solved the main problem of mechanics.

At the same time as Newoth, the German philosopher and mathematician Gottfried Wilhelm Leibniz studied how to draw tangents to arbitrary

crooked. He also developed a new calculus, which turned out to be essentially identical to that built by Newton. The notation introduced by Leibniz turned out to be so successful that it has been preserved to this day.

The new mathematics of Newton and Leibniz consisted of two large parts - differential and integral calculus. The first of them talked about how, by studying a small part of a phenomenon, to reduce the uneven to the uniform, and in the second, how to construct a complex uneven phenomenon from small uniform parts.

Multivolume monographs are devoted to differential and integral calculus and their further development (calculus of variations, differential equations, theory of functions of a complex variable, etc.). In this article we will talk only about the basic concepts of differential calculus - derivative and differential.

**2. Property of “linearity in the small”**

The three lines on figure 1 are parts of the same parabola $y = x^2$, drawn at different scales. Figure *a* is made on a small scale, figure *b* - on a larger scale, figure *c* - on an even larger scale.

⟦column⟧

her. In all figures, the same point $M\,(1;\,1)$ of the parabola is taken so that the behavior of the curve in the vicinity of this point can be studied.

At figure 1, *a* it is clearly visible that the parabola is curved. On figure 1, *b* this curvature is already less noticeable, and on figure 1, ​​*c* it is practically absent - the graph of the function $y = x^2$, made on a large scale, is almost indistinguishable by eye from a straight line. The larger we choose the scale, the less the graph of the function $y = x^2$ will differ from some straight line passing through the point $M\,(1;\,1)$. The same would happen if we began to build a graph of the function $y = x^2$ in the neighborhood of any other point on an ever-increasing scale.

Not only does a parabola “resemble” a straight line near any of its points, this property is shared by a circle, a hyperbola, a sinusoid, etc. It can be called the property of *linearity in the small* (the term is explained by the fact that a straight line is a graph of a linear function $y = kx + b$). But the geometric language in which we have expressed this property is vague. Therefore, let’s try to formulate it in a rather dry, but precise language of formulas.

**3. Function increment**

figure 2 shows a square with side length $a$; area $y$ of such

⟦figure⟧
Fig. 1. *a)* *b)* *c)*

⟦folio 11⟧

⟦folio 12⟧

square is equal to $a^2$. If the length of the side of the square is increased by $p$, then the area will increase - by the area of ​​the figure shaded by figure 2. This area is called the increase in the area of ​​the square. It is equal to $(a+p)^2-a^2$, that is, $2ap+p^2$.

Let us put $p=\Delta x$ (read “delma x”), and denote the increment in the area of ​​the square by $\Delta y$. We get

$$\Delta y=2a \cdot \Delta x+(\Delta x)^2.$$ (1)

In the same way, you can define the concept of increment for any function $y=f(x)$: to calculate the increment of a function when moving from point $a$ to point $a+\Delta x$, you need:

a) find the value $f(a)$ of the function at point $a$;
b) find the value $f(a+\Delta x)$ of the function at point $a+\Delta x$;
b) subtract the first from the second value.

In other words, the increment of the function when moving from point $a$ to point $a+\Delta x$ is equal to $\Delta y=f(a+\Delta x)$—$f(a)$.

For example, the increment of function $y=x^3$ when moving from point $a$ to point $a+\Delta x$ will be

$$\Delta y=(a+\Delta x)^3-a^3=
=3a^2 \cdot \Delta x+3a \cdot (\Delta x)^2+(\Delta x)^3.$$ (2)

Fig. 2.

The words “argument increment” and “function increment” are deceptive: it may seem that both the argument and the function are increasing. In fact, both $\Delta x$ and $\Delta y$ can be negative numbers. Perhaps it would be better to say “change” together with “increment,” but we will stick to traditional terminology.

4. Differentiable functions

Now we can more accurately explain why the graph of the function $y=x^2$ “straightens out” when we increase the scale. Since all the figures $1, a-\beta$ are the same size, as the scale increases, smaller and smaller parts of the curve appear on them. This means that we consider our function for smaller and smaller values ​​of $\Delta x$. Thus, the “straightening” of the graph of a function is associated with the special behavior of the increment of this function when the increment of the argument decreases.

To understand this, let us express the increment of the function $y=x^2$ at the point $M(1; 1)$ in terms of the increment of the argument. We will receive:

$$\Delta y=(1+\Delta x)^2-1=2 \cdot \Delta x+(\Delta x)^2.$$

We see that the increment of the function consists of two terms: $2 \cdot \Delta x$ and $(\Delta x)^2$. The first of them is proportional to $\Delta x$, and the second has the following feature: if $\Delta x \rightarrow 0$, then it tends to the city zero faster than $\Delta x$. For example, if $\Delta x=0,1$, then $(\Delta x)^2=0,01$; if $\Delta x=0,001$, then $(\Delta x)^2=0,000001$, etc. Thus, $\Delta y$ for small $\Delta x$ is almost equal to $2 \cdot \Delta x$. Since $\Delta y=y-1$, $\Delta x=x-1$, then $y-1 \approx 2(x-1)$, that is, $y \approx 2x-1$. But $y=2x-1$ is the equation of a line with an angular coefficient equal to 2. This means that the smaller the neighborhood of the point $M(1; 1)$ we take, the darker in this neighborhood the parabola is adjacent to the line $y=2x-1$. The parabola $y=x^2$ is said to be tangent to the line $y=2x-1$ at the point $M(1; 1)$.

So, the “straightening” of the graph of the function $y=x^2$ with increasing mass

⟦folio 13⟧

headquarters turned out to be associated with the possibility of decomposing the increment of functions into two terms, one of which is proportional to the increment of the argument, and the second, for small values ​​of Δx, is negligible compared to Δx. But the words “negligibly small” still need to be taught.

We will say that the value β is negligible compared to Δx as Δx tends to zero, if its ratio to Δx tends to zero: β=α·Δx, where limα=0.

Now we can formulate the basic definition.

About the limit 1. A function y=f(x) is called differentiable at point a if its increment at this point can be represented as the sum of two terms, the first of which is proportional to the increment Δx of the argument, and the second is negligible compared to Δx. In other words,

$$\Delta y = A \cdot \Delta x + \alpha \cdot \Delta x,$$

(3)

where A is a number and α tends to zero as Δx tends to zero.

Let's consider the increment of functions y=x³ at the point x=a. From equality (2) we obtain Δy = 3a²·Δx + [3aΔx + (Δx)²] Δx. The term 3a²·Δx is proportional to Δx, and the second term [3a·Δx + (Δx)²] Δx is the product of Δx and the factor 3a·Δx + (Δx)², which tends to zero as Δx goes to zero. This means that the function y=x³ is differentiable, and for it A=3a².

The coefficient A in equality (3) depends on the point at which we calculate it. For example, for the function y=x³ at the point a=1 we have A=3, and at the point a=2 we have A=12. If we consider the value of the argument for which coefficient A is calculated to be variable, then it is convenient to denote it by the letter x. As x changes, the coefficient A is a function of x. This function is called the product of the function y=f(x) and is denoted:

$$f'(x), \text{ или } y'$$ (read “efficisimom x”, “erekitimix”).

The term A·Δx, that is, f'(x)·Δx is called the differential of the function y=f(x) and is denoted dy. Thus, dy=f'(x)Δx. In general, Δx is denoted by dx and written dy=f'(x)dx.

From Definition 1 it follows that for values ​​of Δx close to zero, the increment by the differential of the function Δy is almost proportional to the increment of the argument. More precisely, for such a function Δy=(A+α)Δx, where the term α, characterizing the deviation from the “exact” proportionality, tends to zero when Δx tends to zero. This “almost proportionality” of the increment of the function to the increment of the argument underlies the “straightening” of the graph when the image scale is increased.

One should not think that all functions are differentiable at any point. Let's differentiate, speaking visually, check out the graph of a function in the vicinity of a point on a straight line. If the graph of a function has a break at some point, and even more so a discontinuity, then the function will not be differentiable at such a point. For example, the function y=|x| is not differentiable at the point O (0; 0) (Fig. 3).

Intuition suggests that the points at which a given function y=f(x) is not differentiable cannot lie too densely - the curve cannot have an

⟦folio 14⟧

scrap at every point! In many mathematics textbooks of the 19th century, this statement was formed in this way. What a study it was for scientists when, in the second half of the 19th century, the German mathematician Karl Weierstrass published an example of functions that are continuous at all points, but not differentiable anywhere! The graph of this function had a break at each point. Later they found out that a few years before Weierstrass, a function with the same property was constructed by the Czech mathematician Bernard Bolzano; This work of Bolzano was published only many years after his death.

5. Derivative

Let's return to the consideration of differentiable functions - the "good" functions that are studied in high school, and those that are most often found in applications of mathematics, are usually differentiable. For these functions, from the main equality (3) we obtain that $\frac{\Delta y}{\Delta x} = A + \alpha$. If we now direct $\Delta x$ to zero, then in equality (3) $\alpha \rightarrow 0$, whence

$$A \equiv f'(x) = \lim_{\Delta x \to 0} \frac{\Delta y}{\Delta x}.$$

The notation $\frac{dy}{dx}$ is sometimes used to denote a derivative. This notation preserves the memory of the increment ratio $\frac{\Delta y}{\Delta x}$, from which the derivative was obtained by passing to the limit.

The operation of finding the derivative of a given function is called differentiation.

In the textbook “Algebra and the Beginnings of Analysis” for the 9th grade, published under the editorship of Academician A. N. Kolmogorov in 1975, the reader will find a selection of formulas and rules of differentiation that allow arbitrary selection of any fractional-rational function. Below we will show how formulas for differentiating exponents and triune functions are derived. To do this, let us first dwell on the geometric meaning of the derivative.

6. Geometric meaning of derivative

We have seen that in a small neighborhood of the point at which the function is differentiated, its graph is almost indistinguishable from some straight line. This line is called the tangent to the graph of the function at a given point. For points on this line, the equality $\Delta y = A \cdot \Delta x$ is no longer approximate, but exact. Since $\Delta y = y - b$, $\Delta x = x - a$, then the equality $y - b = A(x - a)$ holds for all tangent points. This means that the slope of the tangent is $A$. But $A = f'(a)$, therefore, the value of the derivative at a given point is equal to the slope of the tangent to the graph of the function at this point. This is the geometric meaning of the derivative.

Let's return to the tangent equation: $y - b = A(x - a)$. Since $A = f'(a)$ and $b = f(a)$, the equation of the tangent to the graph of the function differentiated at the point $(a, b)$ can be written in the following form:

$$y - f(a) = f'(a)(x - a).$$

For example, the equation of the tangent to the parabola $y = x^2$ at the point where $x = 3$ is $y = 6x - 9$ (check this).

7. Derivative exponent of a function

When writing the laws of physics related to the exponent function, it is convenient to use a special number - the number $e$. This number can be determined as follows.

Let us draw the graphs of the functions $y = 2^x$, $y = 3^x$, $y = 5^x$ (Fig. 4) in the Cartesian straight line coordinate system. We see that the larger the base, the smaller the angle with the $Oy$ axis exactly

⟦folio 15⟧

ke $M(0;1)$ forms the graph of the function (the angle between the curve $y=f(x)$ and the axis $Oy$ is the angle between the tangent to the curve $y=f(x)$ at point $M(0;f(0))$ and the axis $Oy$). The angle between the $Oy$ axis and the graph of the $y=2^x$ function is approximately $55^\circ$, and the angle between the $Oy$ axis and the $y=3^x$ function graph is approximately $42^\circ$. It turns out that between the numbers 2 and 3 there is such a number that the graph of the exponential function, the base of which is this number, intersects the $Oy$ axis at an angle $45^\circ$. This number is denoted by the letter $e$. It is irrational, the calculations show that $e=2,7182818284590$...

By definition, the tangent to the graph of the function $f(x)=e^x$ at point $M(0;1)$ forms an angle $45^\circ$ with the axis $Oy$, and therefore with the axis $Ox$. Therefore, for the function $f(x)=e^x$ we have $f'(0)=\text{tg}45^\circ=1$. Let us now consider the function $g(x)=e^{x-a}$. The graph of this function is obtained from the graph of the function $e^x$ by $|a|$ to the right if $a>0$, and to the left if $a<0$ (Fig. 5). During a shift, the tangent drawn to the graph of the function $y=e^x$ at point $M(0;1)$ will turn into a tangent drawn to the shifted curve at the point whose abscissa is equal to $a$. Hence,

**8. Derivative is speed!**

In the second half of the 19th century, the course of mathematical physics at the University of Cambridge was taught by the famous scientist William Thomson, who later received the title of Lord Kelvin for his scientific merits (the Kelvin cabinet was named in part in his honor), and the course of “pure mathematics” was taught by Professor Todgenter. However, upon entering the classroom, Thomson addressed the students with a question: what is $\frac{dx}{dt}$? In response, he received all the thoughts of a strict logical definition. They all responded: “Oh, leave this Todgenter, $\frac{dx}{dt}$ is speed!”

Here the reader may be surprised - the derivative has just appeared

as the slope of the tangent to the graph of the function, and now it is declared as speed. Nevertheless, both answers to the question: “*what is a derivative?*” are correct, only the first time explained the geometric meaning of the derivative, and the second - its physical meaning. To make it clearer what relation the derivative has to the speed of movement, consider a point moving in a straight line.

Let us choose the origin, unit of measurement and direction on this straight line. Then the position of the point on the straight line will be determined by its coordinate $x = f(t)$ (the law of motion of the point). The average speed of movement over a period of time in physics is usually called a value equal to the ratio of the movement of a point to the period of time during which the movement occurred. Movement is not the distance traveled, but a change (increment) in the coordinates of a moving point. If, say, a point during the time interval from $t_1$ to $t_2$ went from $A$ to $B$ and returned back to $A$, then the displacement is zero, and the average speed is $v_{\mathrm{cp}} = 0$. In general we have $v_{\mathrm{cp}} = \dfrac{x_2 - x_1}{t_2 - t_1}$, or

$$v_{\mathrm{cp}} = \frac{f(t_2) - f(t_1)}{t_2 - t_1}.$$

If we put $t_1 = t$, $t_2 = t + \Delta t$, then the average speed over the interval $[t,\ t + \Delta t]$ will be equal to

$$v_{\mathrm{cp}} = \frac{f(t + \Delta t) - f(t)}{\Delta t} = \frac{\Delta x}{\Delta t}.$$

*Instantaneous speed at time $t$* is the limit of the average speed of movement for the period of time $[t,\ t + \Delta t]$, when $\Delta t \to 0$. Means,

$$v_{\mathrm{мгн}} = \lim_{\Delta t \to 0} v_{\mathrm{cp}} = \lim_{\Delta t \to 0} \frac{\Delta x}{\Delta t}.$$

But $\lim\limits_{\Delta t \to 0} \dfrac{\Delta x}{\Delta t}$ is the derivative of coordinate $x$ with respect to time $t$. This means that the numerical value of the instantaneous speed

⟦folio 16⟧

⟦column⟧

of a rectilinearly moving point actually turned out to be equal to the derivative of the displacement with respect to time.

**9. Curvilinear speed**

In order to study the movement of cannonballs and planets, parts of mechanisms and machines, the method outlined above is not enough - after all, all these bodies move along curved lines, and we can only cope with rectilinear movement. But by designing the position of a moving point on the coordinate axis, it is possible to reduce the curvilinear movement to two rectilinear ones. Moreover, if the trajectory of motion is flat, then the law of motion is given by two functions that give the values ​​of the coordinates of the point at the moment of time $t: x = x(t)$, $y = y(t)$. However, you can take one function, but it takes not numeric, but vector values. To do this, draw a directed segment from the origin $O$ to the moving point $M$ and denote $\overrightarrow{OM}$ by $\vec{r}(t)$. From figure 6 it is clear that the expansion of the vector $\vec{r}(t)$ into the unit vectors $\vec{i}$ and $\vec{j}$ has the form

$$\vec{r}(t) = x(t)\,\vec{i} + y(t)\,\vec{j}.$$

The instantaneous speed of point $M$ is determined in exactly the same way as in the case of rectilinear motion: take

⟦figure⟧
Fig. 6

⟦folio 17⟧

time period $[t, t + \Delta t]$, the distance the point $M$ moves during this period of time, divide it by $\Delta t$ and direct $\Delta t$ to zero. The only difference is that the movement of point $M$ is expressed not by the number $\Delta x$, but by a vector going from the position of point $M$ at time $t$ to its position at time $t + \Delta t$ (Fig. 7). This vector denotes $\Delta r$, and it is equal to $\vec{r}(t + \Delta t) - \vec{r}(t)$, which is $\Delta xi + \Delta yj$. When divided by $\Delta t$, we obtain a vector parallel to the vector $\Delta r$, but having a different length. It shows the average speed of a point over a period of time $[t, t + \Delta t]$, $\vec{v}_{cp} = \frac{\Delta r}{\Delta t}$.

If we direct $\Delta t$ to zero, then the resulting vector $\vec{v}_{cp}$ will rotate around the point $M$, and in the limit it will be directed tangentially in the direction of the point’s movement. The vector $\lim_{\Delta t \to 0} \vec{v}_{cp}$ denotes $\vec{v}_{mfr}$ and is called the vector of exchange rate at time $t$. Thus,

$$\vec{v}_{mfr} = \lim_{\Delta t \to 0} \vec{v}_{cp} = \lim_{\Delta t \to 0} \frac{\Delta r}{\Delta t} = \frac{dr}{dt}.$$

In other words, the exchange vector

**Fig. 7.**

skorisi are the derivative of the vector function $\vec{r}(t)$. Alternatively, it can be written like this:

$$\vec{v}_{mfr} = x'(t)\vec{i} + y'(t)\vec{j}.$$

Since the vector $\vec{v}_{mfr}$ is directed tangent to the trajectory of the point, the ratio $\frac{y'(t)}{x'(t)}$ is equal to the slope of this tangent: $k_{kac} = \frac{y'(t)}{x'(t)}$.

The length of the vector $\vec{v}_{mfr}$ has a clear meaning. It expresses the linear speed of motion of a point at time $t$. In other words, if denotes the length of other trajectories covered during the time interval $[t, t + \Delta t]$, through $\Delta l$, then

$$|\vec{v}_{mfr}| = \lim_{\Delta t \to 0} \frac{\Delta l}{\Delta t} = \frac{dl}{dt}.$$

No, according to the Pythagorean theorem, the length of the vector $x'(t)\vec{i} + y'(t)\vec{j}$ is equal to $\sqrt{(x'(t))^2 + (y'(t))^2}$. Means,

$$\frac{dl}{dt} = \sqrt{\left(\frac{dx}{dt}\right)^2 + \left(\frac{dy}{dt}\right)^2},$$

that is

$$dl = \sqrt{dx^2 + dy^2}.$$

Formula (4) is the basis for calculating the length of various curves. For example, it can be used to find the length of a cyclode (a curve obtained by rolling a circle in a straight line), an involute of a circle (a curve obtained by blurring a thread wound around a circle), etc.

**10. Derivative trigonometric functions**

Let us show how, using physical considerations, one can find derivatives of trigonometric functions. Let a point move along a circle of unit radius with unit angular velocity, and let it be at the initial moment of time
