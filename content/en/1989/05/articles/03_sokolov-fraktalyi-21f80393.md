---
id: 1989-5-sokolov-fraktalyi-21f80393
issue: kvant_1989_5
year: 1989
number: "5"
title: Fractals
authors:
  - Соколов И. М.
rubric: osnovnye-stati
page_first: 8
page_last: 15
page_labels: 6-13
tag: WAVV
lang: en
source: kvant_digital
extraction: vision
content_sha256: 7e19d923b8e8ae6c97b8e5f0d9a7b29e3c79d74c87e1ed0b587f0db58a00b84a
prompt_sha256: draft-1
translated_from: content/ru/1989/05/articles/03_sokolov-fraktalyi-21f80393.md
source_content_sha256: 68160d26131d7387fd7268a672fe0b444d66577a7993e3161d5080026a783624
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 6⟧

FRACTALS

Candidate of Physical and Mathematical Sciences
I. M. SOKOLOV

The objects we now call facts first appeared in the imagination of mathematicians in the early centuries. And then it could hardly have occurred to us that in the nature surrounding us we could find anything similar to these unusual and exquisite curves. And although in this article we will talk mainly about physical systems, we will have to start with a small and very non-rigorous mathematical introduction.

Self-similar geometric objects

We will call a self-similar geometric figure (body) a figure that can be cut into a finite number of identical figures similar to itself. Examples - on figure 1: segment, equilateral triangle, square, cube.

The self-similar object at figure 2 looks somewhat more complicated. But it is quite simple to construct. Starting with an equilateral triangle on side $l_0$, we will repeat (ad infinitum) the following process: we will divide each segment connecting the vertices of the broken line into three parts and replace the middle part with two segments of length $l/3$, where $l$ is the length of the original segment. The first few stages of constructing such a curve are shown at figure 2. At the $n$th stage of construction, the curve is represented by a broken line of $N = 3N = 3 \cdot 4^n$ segments of length $l_0/3^n$ each, its full length

$$L = 3l_0(4/3)^n.$$

This broken line is called the Triditch Koch curve (named after the Swedish mathematician who invented this object).

Each initial segment of the Triditch Koch curve consists of four

⟦folio 7⟧

procedures for throwing out the middle of a square divided into 9 parts.

Let's return to the Koch curve. Let's try, for example, to determine its length using a compass. Having set the calculation of the compass equal to $\lambda$, we will rearrange the compass along the curve, counting the number of its permutations $n$. The length of the curve will be approximately equal to $L \approx \lambda n$. We will call the quantity $\lambda$ the scale of measurement.

Measuring, say, the length of a circle with a radius of $R = 1$ m, we obtain that the measured length $L = \lambda n$ at $\lambda = 1$ m is 3.0 m, at $\lambda = 0,1$ m $L = 6,2$ mm, at $\lambda = 0,01$ m $L = 6,28$ m, and at $\lambda \rightarrow 0$ the length $L$ tends to the limit $2\pi R = 6,28318\dots$ m.

Having tried to perform a similar procedure with the Koch curve, we will be convinced that there is no limit that could be considered the length of this curve. By choosing the scale $\lambda = l_0/3^n$, we obtain that the measured length of the curve will be equal to the length of the broken line corresponding to the $n$th stage of its construction - $L = 3l_0(4/3)^n$.

Attempts to measure the lengths of other self-similar curves would lead to a similar result - as the measurement scale decreases, the length of the curve increases without limit.

Let us note one very important factor that distinguishes a real self-similar object from an ideal mathematical one: real objects have a minimum measurement scale $\lambda_{\min}$.

Consider, for example, the actual process of constructing a Koch curve using pencil and paper. Let us construct a curve with an initial side length of $l_0 = 1$ m with a pencil leaving a line of thickness $a_0 = 0,1$ mm = $10^{-4}$ m. From a mathematical point of view, the procedure for constructing a curve can continue indefinitely. The real procedure will stop as soon as the length of the segment between two adjacent break points is equal to the thickness of the line. It is easy to calculate that this is the process at step number $n = \ln(l_0/a_0)/\ln 3 \approx 9$. The length of our line will be $L \approx 40$ m. So, realizing a self-similar curve has a finite length.

Now let's return to ideal mathematical objects. The formula for the length of the Koch curve can be written as follows:

$$L = A\lambda^{-\alpha}, \text{ где } A = 3l_0^{\ln 4/\ln 3}, \alpha = \frac{\ln 4}{\ln 3} - 1.$$

(We hope that you yourself, knowing the rules for handling logarithms, will be able to verify that this entry is equivalent to the formula $L = 3l_0(4/3)^n$.) The exponent a appearing in the formula is related to the dimension of the curve.

What is dimension?

There are several definitions of dimension, corresponding to different concepts. Let's try to get an idea about some of them.

Fig. 3.

⟦folio 8⟧

The first definition is related to the minimum number of coordinates required to unambiguously determine the position of a point. In our space this number is equal to trem, on a plane two coordinates are enough, on a line - just one. In this sense, space is three-dimensional, the plane is two-dimensional, and lines are one-dimensional. Naturally, in this definition, the dimension is always an integer.

The second definition is related to the following obstructive. To cut a rectangle into two parts, it is enough to eliminate one point. A set consisting of a finite (countable) number of points will be considered zero-dimensional. The dimension of any set will be assumed to be one greater than the dimension of the cut dividing it into two disconnected parts. With this definition of dimension, a line is one-dimensional, a plane (to cut which it is necessary to make a cut along a certain line) is two-dimensional, and a three-dimensional geometric body is three-dimensional. This dimension - it is called topological - can also only be integer.

Let us now move on to the third, most interesting for us, definition of dimension, or more precisely, to the definition of a whole class of understandable dimensions that are close in meaning. The simplest of them is the self-similarity dimension.

The self-similarity dimension $D$ can be determined by the formula

$$D = \frac{\ln N}{\ln n},$$

where $N$ is the number of identical parts into which a given self-similar object is divided, having an exchangeable spatial size of $n$. Look at figure 1. By making cuts as shown in figure, we will divide the square into $N = 4$ squares from a side that is $n = 2$ times smaller than the original. The cube on side 1 consists of $N = 8$ cups on side $1/2 (n = 2)$. So the self-similarity dimension for a square is $\ln 4/\ln 2 = 2$, for a cube - $\ln 8/\ln 2 = 3$; very/no that the dimension of the segment is 1.

The growth of “snowflakes” on a computer display under different conditions.

Calculating the dimensions of the objects shown in Figures 2 and 3 in the same way, we will see that the dimension of each section of the Koch curve (and the dimension of the entire curve)

⟦folio 9⟧

is correct $D=\ln 4/\ln 3=1,2618$, the Sierpiski triangular curve is $\ln 3/\ln 2=1,5849$, the “Sierpiski carpet” is $\ln 8/\ln 3=1,8727$. These pages curves have a non-integer dimension.

Now let's return to the formula for the length of the Koch curve. Using the definition of the dimension $D$ just given, we can rewrite this formula as

$$L=3l_0^D\lambda^{1-D}.$$

The increase in changes in the length of a self-similar curve as the measurement scale decreases is an indicator of its non-integer dimension:

$$D=1+\alpha.$$

How to change the dimension?

The dimension of self-similarity can be determined only for very regular objects, constructed according to strictly defined rules. If deviations from regularity are not large, the object can be considered approximately self-similar. What if they are big?

Let us use another definition of dimension, which is often

Fig. 4.

cut into cells of size $\lambda$ (for example, puts a square grid on a plane photograph of an object from side $\lambda$). Counts the number of cells in which the object points. The division is repeated, the scale used is $\lambda'<\lambda$, etc. (Fig. 4). The dependence of the number of cells in which the object points on the size of the cell is given by the law $N=A\lambda^{-D}$, where $D$ is the required dimension. Considering the flat area of ​​the plane $S$ (triangle on Fig. 4), it is easy to verify that $N \approx S/\lambda^2$, so $D=2$. For the segment $N=BL/\lambda$, where $L$ is the length of the segment and $B$ is the coefficient, depends on its orientation. The dimension of the segment is $D=1$. If we do the same procedure with the objects shown in Figures 2 and 3, we obtain values ​​$D$ that coincide with their self-similarity dimension. To determine the dimension of real objects, figure depends from $\ln N$ on -$\ln \lambda$. This graph is drawn as a straight line, the slope of which gives us the value $D$.

"Fractal Geometry of Nature"

In 1961, the work of the English researcher L. Richardson (1881-1953) was published, devoted to measuring the length of birch lines. The author found that the measured length of the coast increases with decreasing measurement scale according to the law

2 Quantum No. 5

⟦folio 10⟧

A fractal classer that emerged during computer simulation of diffusion-controlled aggregation.

$$L = A \lambda^{-\alpha}$$ (Richardson's law), where the indicator $\alpha$ is, for example, 0.24 for the west coast of Britain, and 0.13 for the coast of Australia. And although this law greatly informed the formulas for the lengths of self-similar curves, Richardson’s work is significant in itself. There were a number of other physical examples that “reached” self-similar objects. But everything was scattered...

A significant change will occur with the appearance of a book by the French mathematician Benya Mandelbort (now working in the USA), published in 1975 in French and in 1977 in English. The book brought together many of these mathematical and physical examples, making them available for scientific use. But Mandelbort's main merit was that he came up with the name of all this.

The reader will probably remember that Atoc's main contribution to the events described in Dumas's novel Twenty Years Later was the invention of the navigation system for Operation Family Affair. This contribution was considered equivalent to d'Artanne's sword and Portoc's money. Coming up with good navigation is a big achievement.

For objects of fractional dimension, or more precisely, for objects whose French dimension is greater than their topological dimension, Mandelbrot came up with the “fractal” navigation. This word comes from the Latin fractus - fractional, cut. One very witty person passed his navigation into Russian with the word “drobnik”.

Mandelbort's first book was called Fractals: Form, Chance, Dimension. The second, published in 1982, was already called: “Fractal Geometry of Nature.” This name perfectly reflects the real situation.

Multi-geographical objects have fractal properties - ocean and sea coasts, rivers, mountains and mountain gorges. The borders of states, if only they follow natural landmarks and are not drawn with a ruler on the map and only then determined on the ground (such as, for example, the border between Egypt and Sudan), are also fractals. The length of the borders between Portugal and Spain (given in the Portuguese reference book) and the length of the borders between Spain and Portugal (given in the Spanish official information) differ by 20% because they are modified using different scales. This once again confirms that the concept of length for French curves is not very meaningful.

⟦folio 11⟧

It turned out that curves like the Koch curve are the rule rather than the exception in nature. It is clear that the self-obscurity of real, natural objects is violated by random deviations from the structure of regularity. For example, different sections of the coast are not the same, but only similar to each other. And all real systems have a minimum scale of measurement. These circumstances must be taken into account when analyzing the physical situation.

In order to be able to talk about the actual properties of the system, it is necessary that the difference between the minimum and maximum scales be sufficiently large. If we are talking about a sea or ocean coast, then the maximum scale $l_0$ will be of the order of $1000$ km $= 10^6$ m, and the minimum, determined directly by the boundaries due to incoming waves, tides, etc., will be of the order of $1 - 10$ m. These scales differ a million (!) times.

Another example of actual curves is the visible boundaries of clouds. The difference between the minimum and maximum scales here is even greater than in the case of coasts: there is data on areas ranging in size from hundreds of meters with visible details on the order of a meter to the size of the Earth (cyclopole regions). The dimension of the cloud boundary is $D = 1,35$.

So far we have considered mainly only actual curves - highly convoluted lines similar to the Koch curve, and our geographical examples were rather of a circular nature. There are many physical processes that give rise to more complex and important actual structures.

Many of you have probably grown crystals from a saturated solution. If the solution is not too oversaturated and is mixed well enough, then a regularly shaped red crystal will grow from the seed suspended on a thread. The crystal grows due to the fact that in its tell motion the molecules somehow approach those places on its surface where they can “stick”, occupying the most favorable position from an energetic point of view. Of course, most molecules end up in places that are not entirely suitable, but sooner or later they again turn into dissolve or melt due to insufficient connection with the rest of the crystal. As a result of such equilibrium growth, a crystal is obtained without internal voids, with ideally smooth flat edges.

In the absence of equilibrium between crystallization and dissolution (i.e., during rapid crystallization from a highly supersaturated solution or during crystallization from the gas phase), crystals of a completely different type appear. You, of course, have seen a coat of snow growing on the refrigerator freezer or frosty patterns on the windows. These rather fishy formations are caused by the precipitation of water in the air. First, separate clusters of molecules are formed - the so-called classers; Gradually growing and connecting, the classers form patterns. Conditions similar to those that occur during the growth of classers also exist during the growth of snowflakes in the region.

This growth process, called diffusion-controlled aggregation, results in the formation of crystals of the actual shape - endrites. The actual size of hendrite crystals is determined by the specific mechanisms of their growth. Depending on the interaction of the molecules that form the crystal and on the size of the crystal itself, hendrite can be random, irregular in shape or, on the contrary, appear to be a perfectly regular figure, like snowflakes that are well known to everyone. In fact, we can talk about the correct shape of snowflakes only on fairly large scales (the size of the snowflake itself), and on small scales there is no regularity - this reflects the random processes that lead to their formation.

The existence of a minimum scale (which in this case may

⟦folio 12⟧

A real classer that forms Nb Ge₂ upon condensation onto a cold substrate.

be of the order of or much larger molecular sizes) leads to the fact that the total number of molecules in a crystal (or the mass of the crystal) depends on its size according to the law $N_{molекул} \sim M \sim l^D$. Based on the dependence of the mass of dendritic crystals on their size, their dimension can thus be determined.

Figures very similar to dendritic crystals arise during electrical testing of dielectrics. If a strong electric spark strikes a dielectric plate, a clearly visible pattern remains on its surface - the so-called Lichtenberg figures (named after the German experimental physicist G. Lichtenberg (1742-1799), who discovered these figures). The similarity between Lichtenberg figures and dendritic crystals is not accidental - their appearance in theory is described by similar equations.

The fragile dimension is a very important and measurable characteristic of a physical system. This value can also be calculated using various theoretical models. Comparing the measured and calculated values ​​allows you to decide which of these models is better. In addition, when calculating the physical properties of fragal systems (for example, the elasticity of net and other loose materials), you can use a mathematical apparatus specially developed for this case.

The fragmental properties of the region provide many systems that have long been used for very practical purposes. For example, the surface of active carbon used as a sorbent (absorber) in gas masks is fragile. The dimension of this surface is greater than 2: it has an extremely large shape - infinite, in the same sense in which the length of the Koch curve is infinite) area and recesses of all scales, capable of appearing and reliably holding a particle of any size - from dust to a large molecule. The surface of many solid catalysts used in chemistry is also fragmental. Their catalytic activity depends on the fragility properties of the surface, which are determined by the method of preparation and processing.

We became acquainted with a large number of non-integer-dimensional objects. I would like to ask the question: is the very space in which we live three-dimensional? This question can be given a very specific answer. The fact is that the fragmental dimension of space determines the form of many physical laws that attract us. For example, the exponent 2 in the denominator of Coulomb's law $F = \frac{1}{4\pi\varepsilon_0} \frac{q_1 q_2}{r^2}$ is in fact.

Lichtenberg figure.

⟦folio 13⟧

D - 1, where D is the actual dimension of the space. Analysis of data on testing physical laws, the form of which depends on the dimension of space, showed that its dimension differs from 3 by no more than $10^{-10}$. Our space is actually “very three-dimensional.”

Instead of a conclusion

The history of studying actual systems is quite impressive. Appearing at first as a mind game of pure mathematicians, these objects are of little interest to natural scientists. At the same time, there were a number of little understood factors.

Sergey Alekseevich Chaplygin

(For the beginning, see p. 2)

Subsequently, when the speaker carefully checked his calculations, they found out that Sergei Alekseevich was actually right. There were many such legends.

In the fall of 1941, the decision was made to move TsAGI to Kazan and Novosibirsk. Chaplygin began to head the Novosibirsk branch of TsAGI. In the shortest possible time, he managed to launch targeted work in a new place. Projects were again developed and aerodynamic laboratories were built, and intensive scientific work was carried out. But the years and those endured make themselves felt more and more. On October 8, 1942, Sergei Alekseevich died.

The name of Sergei Alekseevich Chaplygin continues to live in the works of his students, in the works of all scientists who develop and generalize his ideas.
