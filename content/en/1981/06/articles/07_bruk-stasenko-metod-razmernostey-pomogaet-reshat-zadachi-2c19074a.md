---
id: 1981-6-bruk-stasenko-metod-razmernostey-pomogaet-reshat-zadachi-2c19074a
issue: kvant_1981_6
year: 1981
number: "6"
title: The dimensional method helps solve problems
authors:
  - Брук Ю. М.
  - Стасенко А. Л.
rubric: osnovnye-stati
page_first: 13
page_last: 20
page_labels: 11-18
tag: KEUR
lang: en
source: kvant_digital
extraction: vision
content_sha256: 9ebaf4cd1df9ee3444d71f71ea2996879e4684d3e4f2172ce4000dda52abb358
prompt_sha256: draft-1
translated_from: content/ru/1981/06/articles/07_bruk-stasenko-metod-razmernostey-pomogaet-reshat-zadachi-2c19074a.md
source_content_sha256: 4f4426bb0074749ba514e2d600f04265c3cf78ec6a869182ecc7701f5de29bf9
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 11⟧

Y. Brook, A. Stasenko

The dimensional method places problems to be solved

In physics... there is no place for empty thoughts... Indeed, the concept of the nature of this or that phenomenon must receive basic laws from the messages of dimension.

E. Fermi

Introduction. Key Ideas

Almost every presentation at scientific seminars or conferences where new theoretical or experimental work is discussed begins with a qualitative description and assessment of the effect that the speaker wants to talk about. Further, in a very detailed report, lecture or article, it is not possible to talk about all the experimental details or all the theoretical tricks that were essential for performing the work itself, for solving this or that problem. But there are questions that always need to be said, without being proven by questions from servants or readers.

Such questions always and primarily include assessment of the order of magnitude of the expected effect, simple limiting cases and the nature of the functional connection of determining the phenomenon of magnitude. All these questions are closely related to each other, their analysis is essentially what we call a qualitative description of the physical situation.

One of the most effective methods of such analysis is the dimensional method. We will look at its basics in this article. It would not be an exaggeration to say that the dimensional method has “maximum efficiency,” saving mountains of paper for theoreticians and money and time for experimenters. Quick assessment of the scale of the phenomena under study,

⟦folio 12⟧

constructing a fundamental diagram of an experiment, obtaining qualitative and functional dependencies, restoring forgotten formulas in exams - these are just some of the advantages and applications of the dimensional method.

Dimensional analysis has been used in physics since the time of Newton. It was Newton who formulated the principle of similarity, closely related to the method of dimensions, which we will now illustrate with a very simple and well-understood example.

Let's imagine that a body with mass $m$ moves in a straight line under the action of a constant force $F$. If the initial speed of the body is zero, and the speed at the end of the completed segment of length $s$ is equal to $v$, then we can write the equality expressed by the law of conservation of energy: $mv^2/2 = Fs$. Between the values ​​$v$, $F$, $m$ and $s$ exists. Very often (but, of course, not always!) the functional dependence of a physical quantity has power-law characteristics. Let's assume that this is the case in our example. We can say this in other words: we believe that the formula defining the speed $v$ as a function of $F$, $m$ and $s$ has the power form $v \sim F^x m^y s^z$.

Here $x$, $y$ and $z$ are some numbers that we have yet to determine. The sign ~ means that the left side of the formula is proportional to the right, that is, $v = kF^x m^y s^z$, where $k$ is a numerical coefficient. Since $k$ is a dimensionless quantity, it is naturally impossible to determine this coefficient using the dimensional method.

The left and right sides of the correspondence (*) must, of course, vary by the same units, that is, they have the same dimensions. We will change $v$ to “m/s”, $F$ to “H”, $m$ to “kg” and $s$ to “m”.

In other words, we choose the dimensions of the quantities $v$, $F$, $m$ and $s$ as follows: $[v] = m/c = m \cdot c^{-1}$, $[F] = H = k \cdot m \cdot c^{-2}$, $[r] = k \Gamma$, $[s] = m$. (The symbol [A] denotes the dimension of the quantity $A$.) Let us write down the conditions that the dimensions of the left and right sides of the correspondence (*) are the same:

$$m \cdot c^{-1} = k \Gamma^x \cdot m^x \cdot c^{-2x} \cdot k \Gamma^y \cdot m^z = k \Gamma^{x+y} \cdot m^{x+z} \cdot c^{-2x}.$$

Notice that now we have already written equality. There are no kilograms on the left side at all, so there shouldn’t be any on the right. This means that

$$x + y = 0.$$

On the right, meters are in powers of $x + z$, and on the next - in powers of 1, therefore $x + z = 1$.

Similarly, from comparing the exponents of seconds, $-2x = -1$ follows.

The equations we obtained make it possible to find the numbers $x$, $y$ and $z$:

$$x = 1/2, \quad y = -1/2, \quad z = 1/2.$$

Now we just have to write down the final formula

$$v \sim \left( \frac{F}{m} \right)^{1/2} s^{1/2}.$$

By squaring the left and right sides of this correspondence, we find that $v^2 \sim \frac{F}{m} s$, or $mv^2 \sim Fs$. In the last formula, the reader can easily recognize the law of conservation of energy, although without a numerical coefficient.

The principle of similarity, formulated by Newton, is that the ratio $v^2/s$ is directly proportional to the ratio $F/m$. Let us take, for example, two bodies with different masses $m_1$ and $m_2$; we will act on them with different forces $F_1$ and $F_2$, but such that the ratios $F_1/m_1$ and $F_2/m_2$ will be the same. Under the influence of these forces, the body begins to move. If the initial velocities of the bodies of work are zero, then the velocities acquired by the bodies on a segment of path of length $s$ will be equal. We came to the law of similarity using the equality of dimensions of the right and left sides of the formula describing the power relationship of the value

⟦folio 13⟧

connection of final speed with values ​​of force, mass and path length.

It is worth mentioning here that, although the method of dimensions was essentially introduced already during the construction of the foundations of classical mechanics, its effective use for solving physical problems began at the end - at the beginning of our century. Much credit for promoting this method and solving a number of interesting and important problems with it goes to the physicist John William Strutt (Lord Rayleigh). In 1915, Rayleigh wrote: “I am often surprised at the little attention paid to the great principle of similarity even by many great scientists. It often happens that the results of painstaking research are presented as newly discovered “laws”, which, nevertheless, could be obtained experimentally within a few minutes.”

In our physics one can no longer be accused of neglect or insufficient attention to the principle of similarity and to the method of dimensions. We will examine below two classical problems, often called Rayleigh problems. There are, of course, much more problems considered by Rayleigh, including with the help of the dimension message, but those that we will talk about are quite typical. Using these and other examples, we will learn more about when and how the dimensional method can be used to solve problems.

Rayleigh's problem about the oscillations of a ball on a string

Let a struya be stretched between points A and B. The tension force of the string is F. In the middle of this string at point C there is a heavy ball. The length of the segment AC (and the corresponding CB) is equal to l. The mass M of the ball is much greater than the mass of the string itself. The string is pulled back and released. It's pretty clear that the ball will oscillate. If the amplitude of these oscillations is much less than the length of the string, then the process will be harmonic.

Rayleigh showed how to find the dependence of the frequency of these oscillations ω on the tension of the string F, the mass of the ball M and the size l. We will now reproduce his reasoning.

Let us assume that the quantities ω, F, M and l are related by a power law:

$$\omega \sim F^x M^y l^z.$$  (**)

The exponents x, y and z are the numbers we need to determine. As in the problem discussed above, we write down the dimensions of the quantities we are interested in in some system of units, for example, in the SI system:

$$[\omega] = c^{-1}, [F] = H = \kappa \Gamma \cdot M \cdot c^{-2}, [M] = \kappa \Gamma, [l] = m.$$

If formula (**) expresses a real physical pattern, then the dimensions of the right and left sides of this formula must coincide, that is, they must satisfy the equality

$$c^{-1} = \kappa \Gamma^x \cdot M^x \cdot c^{-2x} \cdot \kappa \Gamma^y \cdot M^z = \kappa \Gamma^{x+y} \cdot M^{x+z} \cdot c^{-2x}.$$

The left side of this equation does not include meters and kilograms at all, and seconds are included to the power of -1. This means that the following conditions must be satisfied for the numbers x, y and z:

$$x + y = 0, x + z = 0, -2x = -1.$$

Solving this system, we find:

$$x = 1/2, y = -1/2, z = -1/2.$$

Hence,

$$\omega \sim F^{1/2} M^{-1/2} l^{-1/2}.$$

We have already said earlier that due to the insignificance of the numerical coefficient, we have to replace the equal sign with a proportionality symbol. It is interesting to note

⟦folio 14⟧

however, the exact formula for the frequency differs from what we found by only $\sqrt{2}$ times ($\omega^2 = 2F/Ml$). In other words, in this case we can consider that we obtained an estimate for $\omega$ not only qualitatively (in the sense of the nature of the dependence on the value of $F$, $M$ and $l$), but also quantitatively. In order of magnitude, the found power-law combination of $F$, $M$ and $l$ gives the correct frequency value. We will continue to be interested in order of magnitude estimates. In simple problems, quite often coefficients that cannot be determined by the dimensional method can be considered numbers of order one. It should be borne in mind, of course, that this is not a strict rule. The final conclusion about the value of the numerical coefficient can only be drawn from some additional messages. (Note, by the way, that in the example discussed in the “Introduction”, the numerical coefficient in the formula defining the speed $v$ as a function of force, mass and path length is also a number of the order of unity.)

It goes without saying that when solving the problem of the number of strings, we could from the very beginning introduce together the frequencies $\omega$, the oscillation period $T = 2\pi/\omega$ uniquely associated with it, and look for the power-law dependence of the period $T$ on the tension of the string $F$, mass $M$ and size $l$. The factor $2\pi$ here does not “spoil” at all (but does not “improve” either!) the formula obtained from the message of dimensions - after all, we still cannot write a numerical coefficient without an exact solution of the vibration equation.

It is curious that in another, very simple and well-known example - about the quantity of a mathematical matrix - for the frequency of oscillations, already from the dimension messages we would have received the exact formula $\omega^2 = g/l$. The undefined method of dimensions, the numerical coefficient is equal to one in this case. If from the very beginning we would look for the connection between the period of oscillation of the mathematical matrix and its length $l$ and the free fall acceleration $g$, then we would arrive at the formula $T \sim \sqrt{l/g}$, which differs from the exact one by a factor $2\pi$. But even from this example it does not at all follow that when using the dimensional method, the oscillation frequency has some kind of presence of a period; the origin of the factor $2\pi$ is connected only with the definition of $\omega = 2\pi/T$.

Let us return to the consideration of the Rayleigh problem and once again formulate the assumptions that made it possible to solve it using the dimensional method.

First, we assumed that there is a real connection between the quantities $\omega$, $F$, $M$ and $l$. Secondly, we believed that the formula expressing this relationship has a power form: $\omega \sim F^x M^y l^z$.

The dimensional method helps to find the significance function between different physical quantities, but only for those situations where these significances are degrees. Fortunately, there are quite a lot of such values ​​in nature, and the method of dimensions should be our good help.

**Rule $N—K=1$**

The concept of the dimension of a physical quantity is introduced when some basic physical quantities have already been selected and units for their measurement have been established. In mechanics, we consider mass, length and time to be the traditional basic quantities. In the SI system, these quantities are measured in kilograms, meters and seconds, respectively, in the GHS system - in grams, centimeters and seconds.

Let us recall that the main units of measurement in each system (the main dimensions) are the measurements (dimensions) of the main quantities. Units of measurement of all other, non-basic quantities are expressed through basic units of measurement. For example, in the SI system, the unit of force “Newton” is $\text{kg} \cdot \text{m/c}^2$, the unit of energy “Joules” is $\text{kg} \cdot \text{m}^2/c^2$; in the GHS system these are, respectively, “dyna” - $\text{г} \cdot \text{cm/c}^2$ and “ergg” - $\text{г} \cdot \text{cm}^2/c^2$. Such units are called arbitrary.

If we consider problems in which non-mechanical quantities are physicalized (for example, electric charge, temperature, etc.), we can increase the number of basic quantities. In the SI system, the main quantities include current (measured in Amperes), temperature (unit of measurement - Kelvin), etc.

In general, basic quantities and units for their measurement can be chosen in different ways. Much depends on convenience, tradition and existing standards and conventions. It is very important for us to note that the dimensional method can be used in any system of units. Each time, of course, expressions for the dimensions of a quantity must be written in the same pre-selected system.

Let's imagine that in some problem we need to find a significance function between $N$ quantities. Assuming that this significance has a power-law characteristic, we can try to solve the problem using the dimensional method. If the dimensions of all $N$ quantities are expressed through the dimensions of $K$ basic quantities and if this is $N—K=1$, then there is a unique formula that specifies the power relationship between $N$ quantities,

⟦folio 15⟧

and this formula can be found by the method of dimensions.

It is not difficult to verify this. We write the general form of the original formula as follows: on the left side there is one of the quantities raised to the power of 1, and on the right side there is the product of the power powers of the remaining $N-1$ quantities. The exponents are not yet known. The total number of unknown indicators is also $N-1$. To determine these indicators we need $N-1$ equations. We obtain each of the equations by comparing the exponents on the left and right of one of the main dimensions. If our problem contains exactly $N-1$ basic dimensions, we will get exactly as many equations as we need. These equations are linear, and the existence and uniqueness of a solution to a system of such equations guarantees us the existence and uniqueness of the original power formula. This rule is well illustrated by the examples above. When writing formulas $v \sim F^x m^y s^z$ or $\omega \sim F^x M^y l^z$, each time we name $N=4$ quantities, the number of unknown indicators $N-1=3$ coincided with the number of basic dimensions $K=3$ (kg, m, s). Systems of three linear equations for three unknown names are the only solutions, the final formulas for $v$ and $\omega$ were also the only possible ones. Thus, for four functioning communication quantities, only one formula can always be constructed if the number of basic dimensions encountered in the problem is three.

Rayleigh's problem on the oscillations of a spherical droplet

Let a drop flow out of the round hole. It is quite natural to assume that in equilibrium the drop should have a spherical shape - the surface energy is minimal, and any system tends to get into a state with minimal energy. Further, very small deformations of the drop will lead to the fact that the forces of surface tension will “force” it to pulsate - the shape of the drop will be periodic.

Fig. 2.

change physically. We assume that the oscillations continue for a long time and their attenuation is small. We are interested in the question of the frequency (or period) of the process. This frequency may depend, very much, on the magnitude of the surface tension of the liquid $\sigma$, the density of the liquid $\rho$ and the radius of the drop $r^*$. We will look for this dependence in the form

$$\omega \sim \sigma^x \rho^y r^z.$$

Let us write down the dimensions of all quantities in the SI system:

$$[\omega] = c^{-1}, [\sigma] = H \cdot M^{-1} = \kappa \Gamma \cdot M \cdot c^{-2} \cdot M^{-1} = \kappa \Gamma \cdot c^{-2},$$

$$[\varrho] = \kappa \Gamma \cdot M^{-3}, [r] = M.$$

The number of quantities, the connection between which we are looking for, is again one greater than the number of basic dimensions. The $N-K=1$ rule tells us that the formula for frequency must produce a unique one. The equation for determining $x, y$ and $z$ is obtained from the correspondence:

$$c^{-1} = \kappa \Gamma^x \cdot c^{-2x} \cdot \kappa \Gamma^y \cdot M^{-3y} \cdot M^z = \kappa \Gamma^x + y \cdot c^{-2x} \cdot M^{-3y + z}.$$

For three unknown numbers there are three equations:

$$-2x = -1, x + y = 0, -3y + z = 0.$$

This system has only one solution

$$x = 1/2, y = -1/2, z = -3/2.$$

Finally, the formula we are interested in for the oscillation frequency is written as follows:

$$\omega \sim \sqrt{\frac{\sigma}{q r^3}}.$$

This formula also suggests the possibility of a method for experimentally determining the value of $\sigma$. To do this, you need to know the density of the liquid $\rho$, the radius of the drop $r$ and determine the frequency $\omega$ using the experiment. The fact that we do not know the numerical coefficient in this formula should not be a service disadvantage. We can define it, for example, continue to drink with liquid, for which it is great

*) Perhaps at this point you have a question: why not assume that the frequency may also depend on the gravitational force acting on the drop? This question is very natural, and we will definitely discuss it. But a little later.

⟦folio 16⟧

The surface tension is known.

Essentially, we are now faced with a simple modeling case - the oscillations of a drop of the liquid under study can be simulated by the oscillations of a drop of liquid with known σ and q. We can also talk here about the similarity of vibrations of the formula of a drop in two different liquids.

You can integrate the formula for the oscillation frequency ω in another way. Let's rewrite it like this: $(\sigma/\rho) \sim r^3 \omega^2$.

Considering σ and q to be parameters characterizing the liquid and therefore identical for drops of this liquid having different sizes, we come to the conclusion that the periods $T_1 = 2\pi/\omega_1$ and $T_2 = 2\pi/\omega_2$ of oscillations of two drops of the same liquid and the radii $r_1$ and $r_2$ of these drops are related by the correspondence

$$\frac{T_1^2}{T_2^2} = \frac{r_1^3}{r_2^3}$$

— the squares of the oscillation periods of two drops are treated as the cubes of their sizes! Doesn't this remind you of one of Kepler's laws? The analogy is far, please, but in both cases we are talking about periodic processes!

Let's make one more remark. Already when writing out a set of quantities, the connection between which we want to find, we need to be aware of what is essential and what is not essential for a specific physical phenomenon. If we are talking about dynamics (for example, vibrations), then force and mass characteristics should appear in the problem. The role of the first of them in the problem of drop oscillations was played by the quantity σ, the role of the second was played by the liquid density q. Essentially, we believed that vibrations were determined only by surface tension. The solution we obtained is certainly suitable if the drop is oscillating in the cabin of a spacecraft. Is it suitable near the Earth? Shouldn't we also take into account the gravitational force acting on the drop?

Let's think like this. The gravitational force is $F_T \sim \rho r^3 g$, and the surface tension force is $F_{n,h} \sim \sigma r$. It is clear that at sufficiently small $r$ the surface tension force is greater than the gravitational force. Omitting factors, we write down an inequality expressing the condition under which one can run over the force of gravity: $\sigma r \gg \rho r^3 g$. This inequality is equivalent to: $r \ll (\sigma/\rho g)^{1/2}$. It can be argued that for sufficiently small droplets, gravity should not affect the oscillations. Estimate for yourself what the maximum sizes of water drops are at which you can still use the formula we obtained above for the oscillation frequency.

At what frequency do atomic nuclei vibrate?

It turns out that the answer to the question posed can be obtained by using the formula for the frequency of oscillations of a drop.

In the droplet model of the atomic nucleus, the nucleus is considered as a droplet of nuclear matter - a “liquid”, consisting of protons and neutrons. The droplet core is kept from disintegration by the force of surface tension.

Nucleons (protons and neutrons) are inside the nucleus in a bound state. This means that in order to “uncouple” them from each other, you need to expend a certain amount of energy. Per nucleon, this energy is equal to $\varepsilon \approx 13 \cdot 10^{-13}$ J/nucleon. The radius of the nucleus is $r \approx 10^{-14}$ m, the mass of the proton is $m_p \approx 1,7 \cdot 10^{-27}$ kg. Let's try to use all this information to calculate the characteristic frequencies at which atomic nuclei—droplets of nuclear matter—oscillate*).

For the frequency of oscillations of a droplet of nuclear matter, we could use the same formula as for the oscillations of droplets of physical liquid, if only we had taught

*) We are now only interested in the qualitative dependence of the oscillation frequency on the parameters of the nucleus and the quantitative estimate by order of magnitude; therefore, we can ignore the difference between a proton and a neutron and consider the mass of a nucleon equal, for example, to the mass of a proton.

⟦folio 17⟧

tried to calculate the surface tension of the “nuclear liquid”. The total surface energy in the droplet model must be the same order of magnitude as the binding energy of all particles located inside the droplet. If the number of nucleons in the nucleus is $A$ (this number is called the “mass number”), then the total binding energy of all nucleons is $A\varepsilon$ and the surface energy of the droplet nucleus is also $A\varepsilon$ in order of magnitude. Dividing it by the surface area of ​​the drop $S=4\pi r^2$, we obtain an estimate for the surface tension: $\sigma \sim A\varepsilon/4\pi r^2$. The mass of a nucleus of $A$ nucleons is of the order of $Am_p$, the volume of the nucleus is $\frac{4}{3}\pi r^3$; therefore, the density of the “nuclear liquid” is equal in order of magnitude to $\omega \sim 3Am_p/4\pi r^3$. Substituting the resulting expressions for σ and q into formula $\omega \sim (\sigma/\rho)^{1/2}r^{-3/2}$, we arrive at the result that interests us:

$$\omega \sim \frac{1}{\sqrt{3}r} \left( \frac{\varepsilon}{m_p} \right)^{1/2} \sim \frac{1}{r} \left( \frac{\varepsilon}{m_p} \right)^{1/2}.$$

Typical “nuclear” particles are of order $10^{22}c^{-1}$. Check that the written formula gives a close result, a numerical coefficient not determined by us - of the order of unity.

Meters “along” and “across”
The problems that we have considered so far have been solved essentially, identically and unambiguously. Don't think that this is always the case. There are situations when the rule $N-K=1$ is not satisfied, and then it comes to resorting to new ideas. One such idea is that one can try to increase the number of fundamental quantities, that is, essentially move on to studying the problem in a system with a large number of fundamental dimensions.

To illustrate this idea, consider two simple problems.

The first is, of course, well known to everyone. Let's imagine that a ball falls from a table of height $H$ to the floor. The speed of the ball at the moment it leaves the table is horizontal and equal to $v_0$. Its flight range can, of course, be associated with $H$ and $v_0$. We suggest that the reader continue with these simple calculations now before reading further in this article. Did you do it? Now think about it: is it possible to find the connection between $H$ and $v_0$ using the dimensional method? Let's try. Let the further flight be equal to $x_0$. In addition to $H$ and $v_0$, the acceleration of free fall $g$ is undoubtedly an essential value for specifying. The answer should not depend on the mass of the ball - after all, this is a purely kinematic problem. So we have four values ​​- $x_0$, $v_0$, $H$ and $g$. In the expression for the dimensions of all these quantities, only meters and seconds are included, that is, $N=4$, $K=2$ and $N-K=2>1$! If we write $x_0 \sim v_0^a H^\beta g^\gamma$, then for three unknown numbers $\alpha$, $\beta$, $\gamma$ we can write only two equations. How is life?

Let's introduce separate units for measuring vertical and horizontal distances: distances along the vertical axis $Y$ will be measured in “vertical” meters - $M_y$, and distances along the horizontal axis $X$ - in “horizontal” meters - $M_x$. Then the dimensions are:

$$[g] = M_y c^{-2}, [v_0] = M_x c^{-1}, [H] = M_y, [x_0] = M_x.$$

Fig. 3.

⟦folio 18⟧

Now for $N=4$ it is already $K=3$ - the main dimensions are $M_x$, $M_y$ and $c$. The formula $x_0 \sim v_0^\alpha H^\beta g^\gamma$ results in the correspondence
$$M_x = M_x^\alpha \cdot c^{-\alpha} \cdot M_y^\beta \cdot M_y^\gamma \cdot c^{-2\gamma} = M_x^\alpha \cdot c^{-\alpha-2\gamma} \cdot M_y^\beta+y.$$
Control system
$$\alpha=1, -\alpha-2\gamma=0, \beta+\gamma=0$$
has only one solution
$$\alpha=1, \beta=1/2, \gamma=-1/2,$$
and we get an exception response:
$$x_0 \sim v_0 \sqrt{\Pi}/g.$$
Compare this solution with the one you got from an exact calculation.
The second problem, illustrating the same idea, relates to the kinetic theory of gases. Gas molecules have finite sizes and can stick together even in a rarefied gas. The average distance traversed by molecules between two successive collisions is called the free length. We are interested in how the free length $l$ depends on the size of molecules $r$ and their concentration $n$.
Let's write down the dimensions: $[n] = M^{-3}, [l] = M, [r] = M$. It is clear that, trying to connect $l, r$ and $n$, we will again find that the $N-K=1$ rule does not hold: $N=3$, and $K=1$ - there is only one main dimension in the problem - $M$.
In this case, it is also convenient to enter “longitudinal” and “transverse” lengths. Let us conditionally consider the molecules to be balls and keep track of one of these balls. Let’s agree to measure the distance along the trajectory of the ball-molecule with “longitudinal meters” - $M_\parallel$. It is clear that those molecules that fall into a cylinder, the generatrix of which is parallel to the trajectory, and the base is the cross section of the spherical molecules perpendicular to the trajectory, can “place” the movement of the molecule we have chosen. The area of ​​this section is proportional to $r^2$. It is natural to assume in such a situation that $r$ is measured in “transverse meters” - $M_\perp$. Then the volume is measured in units of $M_\parallel \cdot M_\perp^2$ and the dimension of $n$ is $M_\parallel^{-1} \cdot M_\perp^{-2}$. After these differences, we have two main dimensions - $M_\parallel$ and $M_\perp$ - for three values ​​$l, r$ and $n$. This is already enough to obtain an unambiguous formula connecting them. It is easy to check that this formula is:
$$l \sim 1/nr^2.$$
Objectives and recommendations
We have become acquainted above with the basic elements of problem analysis using the dimensional method. Once again, we emphasize that formulas obtained from such differences usually allow one to make quantitative estimates. Here, of course, a certain amount of caution is needed, and nevertheless, it is simply a sin not to take advantage of the fact that the numerical coefficients in formulas often turn out to be of the order of unity.
It goes without saying that assessments, the construction of simple models and the use of analgies are always only the first stage of the study of physical processes. This stage should be followed by a more accurate and, if possible, accurate study of the phenomena under discussion. We would not at all want you to get the impression that the method of measurement is fun. Before using it in one form or another, we need to build a clear picture of the physical process and think carefully about the characteristics that interest us. Only under these conditions can one hope for success.
Below we offer you tasks for independent dimensions.

Tasks
1. Find a formula that describes the relationship between the mass of the planet $M$, its radius $R$ and the minimum period of rotation of the planet around its axis. Please note that the very existence of such granite “balls”, which are planets, is due to the interaction of granite in particular, of which the “balls” also consist. What is the minimum rotation period for a planet with the same mass and radius as Earth? You need to get an order of magnitude estimate.
2. The linear dimensions of two geometric similar steel camerons differ threefold. How are the frequencies of these Camerons different?
3. Find the dependences of the pulsation period of a gas pulse formed during a deep underwater precise explosion, if it is known that the explosion released energy $E$ and the water pressure is $p$. Try to also estimate the maximum size of the gas pulse. How does pulsation depend on depth $H$?
