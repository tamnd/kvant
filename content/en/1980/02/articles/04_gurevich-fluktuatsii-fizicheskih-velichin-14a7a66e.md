---
id: 1980-2-gurevich-fluktuatsii-fizicheskih-velichin-14a7a66e
issue: kvant_1980_2
year: 1980
number: "2"
title: Fluctuations of physical quantities
authors:
  - Гуревич В.
rubric: osnovnye-stati
page_first: 12
page_last: 18
page_labels: 10-16
tag: YXT0
lang: en
source: kvant_digital
extraction: vision
content_sha256: 0b9cb68dfcc58c014792026543025a0d3d65d4d1b776250299617b06231fa9d6
prompt_sha256: draft-1
translated_from: content/ru/1980/02/articles/04_gurevich-fluktuatsii-fizicheskih-velichin-14a7a66e.md
source_content_sha256: f9cfc140390bac5872e2985af75bb85342ae6570e22db27f5fc1633ae938c011
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 10⟧

V. Gurevich

Fluctuations of physical quantities

Consider a physical system consisting of a very large number of atoms or molecules. Such systems are called macrosoppech systems. A gas filling a vessel, a liquid saturated into a vessel, a solid crystal are all examples of macrosoppech systems.

Let's imagine that we need to change some physical quantity that characterizes the macroscopic system. This could be, for example, its mass, electric charge, pressure or temperature.

Any physical change is made with a certain precision. We have come to the conclusion that the accuracy of the change is, as a rule, determined by the design of the changing device. “Bad” devices give low accuracy, “good” ones give high accuracy. For example, analytical balances provide a mass accuracy of approximately ten thousand times greater than a conventional cake scale.

But is the accuracy of the change always determined by the design of the changing device? Is it possible to infinitely increase the accuracy of changes in physical quantities by improving this design? Or are there fundamental limitations, rooted in the very nature of things, that set a limit to the possible precision of changes?

In order to understand what the answer to this question might be, let's look at a simple example. Consider a vessel filled with gas. Let the gas be at atmospheric pressure and room temperature, and the volume of the vessel is two liters. Let us mentally divide the vessel into two parts, right and left, and observe the gas, for example, in the left half of the vessel. How many gas molecules are there in this half of the container? You can calculate that approximately 2.5·10²². Can we calculate or change this number more accurately? For example, is it possible in principle to indicate all 23 digits of this number, assuming that both the temperature and pressure of the gas are known with sufficient accuracy?

⟦folio 11⟧

To understand this, imagine that there is a very precise measuring device that can determine how many gas molecules there are at a given moment in a selected half of the vessel. On the other hand, we know that gas molecules undergo random, chaotic motion (the so-called thermal motion) in all directions, from time to time colliding with each other and with the walls of the vessel. Therefore, by repeating measurements many times, we will, as a rule, obtain different numbers each time. This is not surprising: the molecules move randomly, and their number in each half of the vessel will most likely change from experiment to experiment. We cannot specify the exact number of molecules in advance. But you can always calculate the probability that there will be some definition of their number. Below we will calculate this confidence. But first, let’s try to answer a simpler question: at what number of molecules is this probability most important, that is, what is the most reliable distribution of molecules between the two halves of the vessel?

Most readers will probably say that there is no need to think about the answer to such a question. If the molecules are denoted by 2N, then they will most likely be distributed equally between both halves of the vessel, so that each of them contains N molecules.

What is the probability of this most important distribution? To understand how to calculate such probabilities, we start with the simplest case, when N = 1, that is, there are only two molecules in the vessel. These molecules can be distributed between both halves of the vessel in four ways, which are depicted in figure 1. In two cases out of four, there is one molecule in each half of the vessel. If the molecules can be considered non-interacting, then their positions are independent, and each of the four methods depicted is equally probable. Therefore, the probability of an equal distribution of molecules is $\frac{1}{2}$.

When the total number of molecules is 2N, then the number of ways to distribute them between the two halves of the vessel is $2^{2N}$. The number of methods leading to uniform distribution, when there are N molecules in each half of the vessel, is equal to the number of combinations of 2N by $N:C_{2N}^V = \frac{(2N)!}{(N!)^2}$. The probability of intersecting our own obtaining, if the number of ways that carry out an equal distribution between both halves is divided by the total number of ways:

$$w = \frac{(2N)!}{2^{2N}(N!)^2}.$$

For N=1, this general formula gives the already obtained value $\frac{1}{2}$.

The probability is easy to calculate using formula (1) when N is equal to a small number. But how to calculate it when N is about 10$^{22}$? In this case, a significantly approximate formula for N!, which “works” the more accurately, the larger the number N. Calculations made using this formula in the Appendix give

$$w = \frac{1}{\sqrt{\pi N}}.$$

For any real vessel with gas, this is a very small value. If, as in our example, N=2.5·10$^{22}$, then $\omega = 3,7·10^{-12}$. And this is an insignificant number. Why is the most likely distribution perfect? To understand this, calculate the probability $w(n)$ of such a distribution when on the left half of the vessel the number of parts is slightly different from N, namely, equal to N+n, and in the right half, corresponding to N—n. The words “slightly different” means that we will calculate the probability $w(n)$ only for those n that are less than N in the absolute value of the city.

The calculations made in the Appendix give for this case

$$w(n) = \frac{1}{\sqrt{\pi N}} e^{-n^2/N},$$

where e=2.71... is the base of natural logarithms.

The graph of this function is shown at figure 2. It is symmetrical about the ordinate axis and has a maximum

⟦folio 12⟧

at $n=0$. Near the maximum, the curve changes smoothly, and then begins to decline sharply. Rapid decreases are usually characterized by the so-called half-width of the maximum. This is the irrigation of the distance between the abscissas of those points of the curve whose ordinates are $e$ times lower than the ordinates of the maximum. The half-width of the curve at figure 2 is $\sqrt{N}$. When $n$ exceeds $\sqrt{N}$, $w(n)$ is much less than its maximum value.

Now remember that the total probability of all possible events is, by definition, equal to one:

$$\sum_{n=-N}^{N} w(n) = \frac{1}{\sqrt{\pi N}} \sum_{n} e^{-n^2/N} = 1.$$

How many terms should be taken into account in this sum? It would seem that the question does not make much sense. It is enough to look at the summation limit to see that there are $2N+1$ terms in total. In fact, by asking such a question, we want to understand how many terms actually contribute to the sum as a replacement contribution. Indeed, for $n^2$, cities larger than $N$, the terms become very small, and they can simply be discarded. The number of terms in this sum exists is of the order of $\sqrt{N}$. This means that if we take the total number of terms several times greater than $\sqrt{N}$, then the error allowed, that is, the difference between the sum and unity, will be very small.

There's some interesting physics behind this project math fact. By repeatedly changing the number of molecules in a given half of the vessel, we most likely will not obtain the number $N$. Each time a new number of molecules will be obtained - sometimes a little more $N$, sometimes a little less $N$.

How can the magnitude of such fluctuations be characterized? After all, $n$ takes on different meanings, positive and negative. Therefore, it is natural to use the following quantities to describe fluctuations. We will perform averaging over a large number of changes or, which is the same thing, over a fairly large period of time - after all, we can imagine that changes are made sequentially, one after another, during this period. Averaging will be indicated by a line over the value being averaged. Our goal is to find a quantity measure of the magnitude of fluctuations, that is, some number that would characterize their “span”, so that we can compare the magnitudes of fluctuations in different cases. Could the average value $\bar{n}$ serve as such a measure? What to find $\bar{n}$, what value $n$ must be multiplied by the probability of occurrence of this value and summed over all $n$. As a result we get:

$$\bar{n} = \sum_{n=-N}^{N} nw(n) = \sum_{n} \frac{1}{\sqrt{\pi N}} ne^{-n^2/N}.$$

It is easy to see that this sum is zero. Indeed, for each number $n$ there can be a “pair” with number $-n$, and two such terms add up to zero. This means that $\bar{n}$ cannot serve as a measure of the fluctuation intensity. This also means that $N$ is not only the most probable number of parts in a given half of the vessel, but also their average number.

A measure of the fluctuation intensity can be the average squared fluctuation of the number of the part, that is, the average value $n^2$, equal to

$$\bar{n}^2 = \sum_{n=-N}^{N} n^2w(n).$$

This quantity is equal to $N/2$*, so formula (3) can now be rewritten as

$$w(n) = w(0)e^{-n^2/2n^2},$$

where $w(0) = \frac{1}{\sqrt{\pi N}} = \frac{1}{\sqrt{2\pi n^2}}$. The square root of $n^2$ is called the mean square fluctuation of the part number. In our case, the mean square

*) We will calculate this value in the Appendix.

⟦folio 13⟧

fluctuation is equal to

$$\sqrt{n^2} = \frac{\sqrt{N}}{\sqrt{2}}$$

This quantity has a clear physical meaning: if you change the number of particles in one half of the vessel, then it will most likely differ from the average number of particles by values ​​on the order of the root-mean-square fluctuation (and the sign of the corresponding difference can be any).

Thus, the more particles in the system, the greater the mean square fluctuation. However, as the number of particles increases, the mean square fluctuation does not grow proportionally to $N$, but much more slowly—proportionally to $\sqrt{N}$.

Now it is clear with what maximum accuracy it makes sense to change the number of molecules in a given half of the vessel. This accuracy is determined by the magnitude of the mean square fluctuation. In our case (when the volume of half the vessel is equal to one liter), the root mean square fluctuation is approximately $2.2 \cdot 10^{11}$. This means that the expression for the number of molecules must be kept to at most the first 11 significant digits. If you perform a series of changes with greater accuracy, then the first 11 digits will be repeated in almost all changes (fluctuations significantly exceeding the average value have a very low probability), while the other digits will change from one change to another in a random manner.

In the example given, the maximum number of significant digits that can be kept in the answer is very large, and in reality, of course, the limit to the accuracy of the change is set by the design of the device. However, this number can be small if the average number of gas molecules in a small volume is changed. So, for example, the average number of molecules in one cubic micron ($10^{-18}M^3$) is equal to $2.5 \cdot 10^7$ under the same conditions. The mean square fluctuation in this case is approximately $4 \cdot 10^3$, so it makes sense to determine the number of molecules in such a volume to at most four significant figures.

The phenomenon of fluctuations can be looked at from a slightly different point of view. Let's consider a thought experiment in which a certain number of $n$ molecules move from the right half of the vessel to the left, not as a result of spontaneous fluctuation, but under the influence of an external force. (The number $n$ is small compared to $N$.) What work is done during such a movement?

The answer to the question posed in this form is given below. The work done depends on how the molecules are moved, and even on the shape of the container. The fact is that depending on the experimental conditions, first of all, on the speed of gas movement, we will have to do different work against the friction forces that prevent the gas from flowing under pressure from one half of the vessel to the other. Since the magnitude of the friction forces in a gas is proportional to the speed, the lower the speed, the less work has to be done against the friction forces. The least work $A_{\min}$ will be done if the gas is moved extremely slowly. And if we say that we want to calculate exactly this smallest work, then the problem will be formed as follows.

How would it be possible to move the specified number of gas molecules? Let's imagine that a thin piston enters a vessel containing gas. It divides the entire volume not exactly in half, but in such a way that there are $N + n$ molecules from it, and $N - n$ to the right. Let's start moving the piston to the left, as shown by the arrow at figure 3, until it reaches the half-way shown by the dotted line, at which point it divides the volume of the vessel in half. It is required to calculate the work done by the piston against gas pressure forces.

What happens when the piston moves? Moving to the left, the piston compresses the gas on the left side of the vessel and expands it on the right. As a result, the pressure on the left increases, and the pressure on the right decreases. The force acting on the piston is equal to the product of its area $S$ and the difference in pressure between the left and right parts of the vessel. According to the conditions, $n$ is much less than $N$, which means that the distance passed by the piston is small compared to the size of the vessel. Therefore, to a first approximation, the pressure difference can be considered proportional to this path. (Try to evaluate for yourself the accuracy with which this statement is true.) Then work $A_{\min}$

Fig. 3.

⟦folio 14⟧

The product of the path and the average force is calculated. The average force is equal to half the force acting on the piston at the end of its movement, that is, half the value $(p_1 - p_2)S$, where $p_1$ and $p_2$ are the corresponding final values ​​of pressure in the left and right halves of the vessel. Hence the work

$$A_{\min} = \frac{1}{2} (p_1 - p_2) v,$$

where $v$ is the volume of the cloud, bounded by the solid and dotted lines on figure 3.

Let us denote the total volume of the vessel by 2V. According to the Boyle-Marutt law

$$p_1V = p(V + v), \quad p_2V = p(V - v),$$

where

$$p_1 - p_2 = 2p \frac{v}{V}.$$

Thus,

$$A_{\min} = p \frac{v^2}{V}.$$

Given the Clapeyron–Mendeleev equation, which we write as $pV = NkT$, and considering that $v : V = n : N$, we can express the expression for $A_{\min}$ in the following final form:

$$A_{\min} = kT \frac{n^2}{N}.$$

(6)

Let us now return to formula (3) for $w(n)$. Comparing (3) and (6), we see that (3) can be rewritten as follows:

$$w(n) = w(0) e^{-A_{\min}/kT}$$

(7)

(recall that $w(0) = 1/\sqrt{\pi N}$). For the probability $w(n)$ we have one expression - through the average Vadartinian formula for the number of the part (see (5)):

$$w(n) = w(0) e^{-n^2/2n^2}.$$

(recall that the mean Vadartin formula is $\sqrt{n^2}$). Comparing this expression with (7), we find that

$$\frac{n}{\sqrt{n^2}} = \sqrt{\frac{2A_{\min}}{kT}}.$$

(8)

Relation (8) means that each formulated corresponds to some work that is required to create the given formulated deviation with the help of external forces! The source of this work in the case of spontaneous formulations is the thermal energy stored in the system. In our example, this is the energy of the otic movement of gas molecules. The more work $A_{\min}$, the less likely the formula (7)

Fig. 4.

⟦folio 15⟧

is presented in a general form, independent of the specific device of the physical system, so that, using it, one can calculate fluctuations of any physical quantity. To do this, you only need to obtain a formula for the operation of $A_{\min}$, which must be touched to create the fluctuation deviation data. We will now see how this is done using several examples.

Let's start by considering fluctuations in the number of parts in a volume $V$ containing on average $N$ parts of gas. But at the same time, we will assume that it does not communicate with others of the same volume, but is a small part of a large vessel with gas. How should the average variation of the fluctuation of the part number change in this case compared to the cases considered above?

From physical reports it is clear that it should increase: additional opportunities have appeared for the preparation of molecules into the volume $V$ or the outflow from it. But for how long?

Let's calculate the work $A_{\min}$ that needs to be done to move $n$ molecules into volume $V$. It is considered essentially the same as above. The only difference is that the external pressure $p_2$, which is established after the movement, can be considered with sufficient accuracy equal to the initial pressure $p$; since the volume of the entire city vessel must be greater than the volume $V$, the change in pressure in the city vessel must be less than the change in pressure in the volume $V$, and it can be avoided. Carrying out calculations, we find that

$$A_{\min} = \frac{1}{2} kT \frac{n^2}{N},$$

that is, we get values ​​that are half as high as above. Using formula (8), we find the average vartansion fluctuation of the number of the part:

$$\sqrt{n^2} = \sqrt{N}.$$

This value is $\sqrt{2}$ times greater than the previously obtained value of the average vartant fluctuation of the number of parts in the polyvine vessel.

As another example, consider fluctuations in the electrical circuit shown in figure 5. The circuit consists of a capacitor $C$ and a resistor with resistance $R$ connected in a closed loop. Electric charges in the resistor undergo thermal movement, as a result of which a fluctuation current flows through the resistor, which means a fluctuation electric charge appears on the capacitor.

We want to calculate the mean square fluctuation of this charge.

Let's calculate the work $A_{\min}$ that must be expended in order to impart a charge $Q$ to the capacitor, that is, charge it to a voltage $Q/C$. Average voltage during charging

$$w(Q) = w(0)e^{-Q^2/2CkT},$$

and by analogy with (8) we can immediately write an expression for the average charge fluctuation:

$$\sqrt{Q^2} = Q \sqrt{\frac{kT}{2A_{\min}}} = \sqrt{CkT}.$$

As another example, let’s find the average speed of the part participating in the movement of some axis, for example, the $X$ axis. We denote the projection of velocity onto this direction by $v_x$. Obviously, in this case $A_{\min}$ is equal to the kinetic energy of the part $mv_x^2/2$, where $m$ is the mass of the particle. We can calculate the average speed immediately - by analogy with formula (8). It is equal

$$\sqrt{v_x^2} = \sqrt{\frac{kT}{m}}.$$

So, if the mass of a particle is $10^{-15}$ kg, at room temperature $\sqrt{v_x^2} \approx 0,002$ m/s.

In conclusion, let us pay attention to one interesting and important circumstance. Both the average charge fluctuation on the capacitor and the average velocity fluctuation are greater the higher the temperature. This is natural, since temperature is a measure of the intensity of the random thermal movement of molecules, which serves as a pleasant fluctuation. For a gas, the average fluctuation in the number of molecules does not depend on temperature. But formula (5) itself is true

⟦folio 16⟧

only at sufficiently high temperatures. When the temperature decreases, the gas condenses into liquid, and formula (5) becomes inapplicable, because the movements of individual molecules cannot be considered independent.

Let's summarize some results. An important conclusion follows from the above. Not all physical quantities are, in principle, determined with very high precision. In principle, it is possible, for example, to measure with any accuracy the mass, charge or number of atoms of any isolated body. These quantities do not fluctuate unless the body exchanges particles with other bodies.

Here we have encountered examples of quantities that can fluctuate. In principle, it makes no sense to specify their values ​​with unlimited accuracy. We have seen that it makes sense to specify the number of molecules in each part of a vessel with a gas only with an accuracy of the mean square fluctuation. The same can be said regarding the gas pressure on the wall of the vessel. Temperature also fluctuates, and therefore by its very nature cannot be changed with too high precision. The smaller the size of a physical system or the number of atoms in it, the greater the relative fluctuations of the physical quantities characterizing it and the less relative accuracy they can be set or changed.

Application

To obtain expression (1), we use the approximate Stirling formula for $N!$, which is valid for large values ​​of $N$. This formula looks like:

$$N! = \sqrt{2\pi N} e^{N(\ln N-1)},$$

where $\ln$ denotes the logarithm taken to base $e$. The higher the number $N$, the higher the relative accuracy of this formula; it can be shown that the relative error it gives is less than $\frac{1}{8N}$. Let's use it to calculate probability (1), we get expression (2).

Apply the same formula to calculate the probability

$$w(n) = \frac{(2n)!}{2^{2N}(N+n)!(N-n)!},$$

we get

$$w(n) = \frac{\sqrt{N}}{\sqrt{\pi(N^2-n^2)}} \times e^{2N\ln 2N-(N+n)\ln(N+n)-(N-n)\ln(N-n)}$$

In the expression under the root, we have preserved the small value $n^2$ in comparison with the larger value $N^2$; then the coefficient before the exponential turns out to be equal to $\frac{1}{\sqrt{\pi N}}$. In order to calculate the expression in the exponent, we present a formula that is valid for any small positive or negative $x$ in abscise value:

$$\ln(1+x) = x - \frac{x^2}{2}$$

(for example, at $|x| < 0,1$ this formula gives an error not exceeding 0.4$x^3$). The result is expression (3), given in the text.

We still have to prove that the mean square of the fluctuation in the number of particles (see (4)) is equal to $N/2$. The idea of ​​the proof is simple. First, let's remember how the known correspondence is proved.

$$\sum_{n=-N}^{N} C_{2N}^{n+n} = 2^{2N}.$$

To do this, we consider the biominal expansion of the function $f(x) = (1+x)^{2N}$. She looks like

$$f(x) = \sum_{n=-N}^{N} C_{2N}^{n+n} x^{n+n}.$$

It immediately follows that the sum of $\sum C_{2N}^{n+n}$ is $f(1)=2^{2N}$.

In our case, to calculate the sum (4),

equal to $2^{-2N} \sum_{n=-N}^{N} n^2 C_{2N}^{n+n}$, we need to find a function whose biominal expansion would have the form

$$g(x) = \frac{1}{2^{2N}} \sum_{n=-N}^{N} C_{2N}^{n+n} n^2 x^n.$$

Then $g(1)$ gives the desired average value $n^2$. Check for yourself that $g(x)$ has the form

$$g(x) = \frac{N}{2^{2N}x^N} (1+x)^{2N-2} [N(1+x)^2-2(2N-1)x].$$

Hence $g(1)=\frac{N}{2}$.
