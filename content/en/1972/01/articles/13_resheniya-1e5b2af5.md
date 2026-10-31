---
id: 1972-1-resheniya-1e5b2af5
issue: kvant_1972_1
year: 1972
number: "1"
title: Solutions to problems M77—M83; F89—F91
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 41
page_last: 51
page_labels: 39, 40, 41, 42, 43, 47, 48, 49
tag: 0KHK
lang: en
source: kvant_digital
extraction: vision
content_sha256: 489fc13af71a8d0cea6b4b62a0d10b51aad8a5292f292311b945c7ff00d8a04b
prompt_sha256: draft-1
translated_from: content/ru/1972/01/articles/13_resheniya-1e5b2af5.md
source_content_sha256: 266ec7e4286ea75ebe387033c0ee5079efaf6c3cfe17d59493ed5935f0dafa3e
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 39⟧

Solutions

In this issue we publish solutions to problems M77—M83

M77

The lengths of the two sides of the triangle are 10 and 15. Prove that the bisector of the angle between them is not greater than 12.

We received a lot of different solutions to this problem from readers. Let's give just three.

I. Let's carry out $DE \parallel BC$ (Fig. 1). Then triangle $CDE$ is equilateral, therefore $CE=ED=x$, and $x$ one can find similarities of triangles $ABC$ and $ADE$:

$$\frac{15-x}{15} = \frac{x}{10}, \text{ поэтому } x=6 \text{ и } CD < CE + ED = 2x=12.$$

II. By the property of the bisector $BD/DA = BC/CA = \frac{2}{3}$. Draw $BK \perp CD$ and $DL \perp CD$ until they intersect with side $AC$ (Fig. 2). Then $AK=AC - KC=AC - BC=5$, and $KL/LA=BD/DA = \frac{2}{3}$, therefore $KL=2$, and $CD < CL=12.$

III. (In two stats “Area Method” «Kvant» No. 12, 1971, p. 41). Let $\Rightarrow BCD = \Rightarrow ACD = \alpha$, then (Fig. 3) ​​$S_{\triangle ACD} + S_{\triangle BCD} = S_{\triangle ABC} \langle = \rangle al \sin \alpha + bl \sin \alpha = ab \sin 2\alpha,$

Fig. 1. Fig. 2. Fig. 3.

⟦folio 40⟧

because

$$l = \frac{2ab}{a+b} \cos \alpha = \frac{2 \cdot 10 \cdot 15}{25} \cos \alpha = 12 \cos \alpha < 12.$$

(Many people also used other formulas for the bisector:

$$l^2 = ab - mn = ab - \frac{abc^2}{(a+b)^2} = \frac{4abp(p-c)}{(a+b)^2}.$$

Either of these methods can be used to prove that the bisector $l$ of a triangle enclosed between the sides $a$ and $b$ does not exceed $\frac{2ab}{a+b}$ (the harmonic mean of the numbers $a$ and $b$). This estimate is unimprovable: for any $l < \frac{2ab}{a+b}$ one can construct a triangle with sides $a$ and $b$ and a bisector $l$ between them (make sure of this!).

Try to prove the following two statements that generalize the problem:

1) If in a triangle $ABC$, where $BC = a, AC = b$, the point $D$ divides side $AB$ in relation to $BD : DA = m : n$, then $\frac{|mb - na|}{m + n} < CD < \frac{mb + na}{m + n}$. (In our problem $m : n = a : b$).

2) If the segment $CD$ divides the angle $BCA$ in relation to $\Rightarrow BCD : \Rightarrow DCA = p : q$, then $CD < \frac{(p+q)ab}{pa + qb}$. (In our problem $p : q = 1$; here for the proof we can use the following lemma: if $0 < \alpha < \beta < \pi$, then $\frac{\sin \alpha}{\alpha} > \frac{\sin \beta}{\beta}$).

**M78**

Prove that every non-negative integer can be represented as $\frac{(x+y)^2 + 3x + y}{2}$, where $x$ and $y$ are non-negative integers, and what is the singular representation.

Let us denote the sum $x+y$ by $s$ and rewrite this formula as follows:

$$n = \frac{(x+y)^2 + 3x + y}{2} = \frac{s^2 + s}{2} + s.$$ (1)

The conditions that $x$ and $y$ are integers, $x \geq 0$ and $y \geq 0$ are equivalent to the following: $x$ and $s$ are integers, $x \geq 0$, $s \geq x$. For a given $s$, the value $x$ can take the following values: $0, 1, \ldots, s$; the corresponding value $n$, defined by formula (1), takes the following values: $\frac{s^2 + s}{2}$, $\frac{s^2 + s}{2} + 1$, $\ldots$, $\frac{s^2 + s}{2} + s$. So, each $s = 0, 1, 2, \ldots$ corresponds to a segment of $s+1$ non-negative integers $n$. Note that the last number of the segment corresponding to $s$ is exactly one less than the first number of the segment corresponding to $s+1$:

$$\left( \frac{s^2 + s}{2} + s + 1 \right) = \frac{(s+1)^2 + (s+1)}{2}.$$

Therefore, the segments will also contain all non-negative integers $n$, and each $n$ falls into only one segment, that is, it will correspond to exactly one pair of values ​​$s$ and $x$ (Fig. 4).

Solution problem. We have proven that formula (1) allows us to “inline” all points $(x, y)$ with non-negative integer coordinates with numbers $n=0, 1, 2, \ldots$. figure 5 shows how these numbers are arranged in order.

The correct solution to the addition A. Abdulaev, M. Bukhanov, A. Gritsoryan, A. Zaslavsky, M. Illarionov, N. Kortsenko,

⟦folio 41⟧

L. Knizhnerman, V. Lozinov, V. Krivitsky, G. Makarov, A. Martynov, M. Praeger, M. Perelmuter, M. Rozov, V. Servakh, A. Slinkin, E. Turkevich, A. Udaltsov, V. Faitelevich, G. Filkovsky, A. Chernyak, K. Shilov, I. Sharlinsky. Some of those who prove the statement of the problem by induction point out that it is not always possible to move from the point $(x, y)$ to $(x+1, y-1)$: if $y=0$, then it is necessary to take $(0, x+1)$ as the next point after $(x, 0)$.

E. Turkevich gives in his solution a formula similar to (1), which allows us to enumerate sets not of two, but of $k$ non-negative integers $(x_1, x_2, \dots, x_k)$:

$$n = C_{s_k}^{k+k-1} + C_{s_{k-1}}^{k-1} + k-2 + \dots + + C_{s_1}^{1},$$

where $s_i = x_1 + x_2 + \dots + x_i$,

$$C_p^q = \frac{p(p-1)\dots(p-q+1)}{1\cdot2\cdot\dots\cdot q}.$$

For example, for $k=3$ the formula is

$$n = \frac{s_3(s_3+1)(s_3+2)}{6} + \frac{s_2(s_2+1)}{2} + s_1 = \frac{1}{6}[(x_1+x_2+x_3)^3 + 3(x_1+x_2+x_3)^2 + 3(x_1+x_2)^2 + 11x_1 + 5x_2 + 2x_3].$$

Try to generalize the problem in another direction: find a formula that establishes a correspondence between all points $(x, y)$ on the plane with integer coordinates and all integer (or non-negative integer) numbers $n$. Is it also possible to write the formula as a polynomial of the second degree $n=f(x, y)$, like formula (1)?

**M79**

Two points $P$ and $Q$ move along two intersecting lines with the same constant speed $v$. Prove that there is a fixed point $A$ on the plane, the distances from which to the points $P$ and $Q$ at any time are equal.

Let $O$ be the point of intersection of these lines; $P_0$ and $Q_0$ are the positions of the point at that moment of time $t_0$, when they are at the same distance from the point $O$ ($t_0$ is exactly in the middle between the moments of time when one and the other point pass through the point $O$); $A$ is the point of intersection of perpendiculars to the given lines, restored respectively at points $P_0$ and $Q_0$.

**Fig. 6.**

Let us prove that the point $A$ is the same fixed point whose existence is stated in the conditions.

The special case where the points $P_0, Q_0$ (and $A$) coincide with $O$ is very special. In the general case (Fig.6) it is clear that triangles $AP_0O$ and $AQ_0O$ are equal, so $AP_0=AQ_0$. Let $P$ and $Q$ be the positions of the point at an arbitrary instant $t$ (different from $t_0$). Then $PP_0=QQ_0$ (the points move at the same speed), triangles $PP_0A$ and $QQ_0A$ are equal along two legs, therefore $AP=AQ$.

From our solution it is clear that in fact a stronger statement is true than the equality of the distances from the point $A$ to the corresponding points $P$ and $Q$: if you rotate one of the given lines around the point $A$ (by an angle $P_0AQ_0$) so that it coincides with the other, then at any moment in time the point $P$ coincides with the corresponding point $Q$.

**M80**

Table $m \times n$ deals with arbitrary numbers. It is allowed to simultaneously change the sign of all numbers in one column or all numbers in one row. Prove that by repeating this operation several times, you can obtain a table in which the numbers in any column and the sum of the numbers in any row are non-negative.

We will change the signs of rows or columns, in which by changing the signs the total sum of numbers in the table increases. Therefore, one and the other points pass through the point $O$; $A$ is the point of intersection of perpendiculars to the given lines, respectively restored at points $P_0$ and $Q_0$.

⟦folio 42⟧

numbers in each row and in each column is non-negative.

It can be proven that in fact the table $m \times n$ can always be bypassed by at most $\frac{m+n}{2}$ operations.

Correct solutions were sent by: V. Kopylov, E. Rodionov, I. Ivanova, M. Ilarionov, V. Krivitsky, A. Zhumadildaev, A. Chernyak, A. Volbereg, N. Kornienko, E. Turkevich.

M81

An arbitrary point $P$ is taken inside the square $A_1A_2A_3A_4$. From vertex $A_1$ a perpendicular is dropped onto line $A_2P$, from vertex $A_2$ to $A_3P$, from $A_3$ to $A_4$ to $A_1P$. Prove that all four perpendiculars (or their extensions) intersect at one point.

Let's rotate the square (Fig. 7) around its center at $90^\circ$ so that the vertex $A_2$ goes to $A_1$, $A_3$ to $A_2$, $A_4$ to $A_3$ and $A_4$. Then each of the lines $A_2P$, $A_3P$, $A_4P$, $A_1P$ will go into the corresponding perendlukular (after all, it will turn to $90^\circ$!), therefore, all four perpendiculars will go through one point $P'$, into which the point goes when turning $P$.

M82

On the ring automatic road there are several identical automatic ones. It is known that if all the gasoline available in these automatic cars were poured into one, then this car

![Diagram](image)

Fig. 7.

M83

Prove that the numbers 1, 2,..., $n$ for any $n$ cannot be divided into two groups so that the product of numbers in one group is equal to the product of numbers in the other.

As many readers have noticed, the statement of the problem follows from the following theorem: for $n$

*) E. B. Dynkin, S. A. Molchanov, A. L. Rosenthal., Mathematical contemporaries. Arithmetic and algebra, “Science”, additional series “Libraries of the Physics and Mathematics School” vol. 3*, 1970.

⟦folio 43⟧

Any $x > 1$ between $x$ and $2x$ contains at least one prime number. The first proof of this theorem (“Bertrand’s procedure”), obtained by P. L. Chebyshev, was described in «Kvant» No. 5, 1970.

Let us take a prime $p$ such that $\frac{n}{2} < p < n$. It can only be included in one group of numbers, and there is nothing to “balance” it, since $2p > n$. The further confirmation of the problem follows from the theorem on the uniqueness of decomposition into prime factors.

We have not received solutions that do not use the Bertrand prostate.

N. V. Vasiliev

In this issue we publish solutions to problems F89—F91

F89

The intense electric field in an electromagnetic wave of frequency $\omega = 2 \cdot 10^{16} \text{сек}^{-1}$, modulated in amplitude with frequency $\Omega = 2 \cdot 10^{15} \text{сек}^{-1}$, changes with time according to the law $E = a (1 + \cos \Omega t)$ cos $\omega t$, where $a$ is a constant. Determine the energy of the electrons knocked out by this wave from the atoms of gaseous hydrogen with energy ionization $W = 13,5 \text{яб}$.

An atom absorbs monochromatic light of frequency $\omega$ in portions (quanta) of energy equal to $\hbar \omega$, where $\hbar = 1,05 \cdot 10^{-27} \text{эрэ} \cdot \text{сек}$ is Planck’s constant divided by $2\pi$.

Since $E = a (1 + \cos \Omega t)$ cos $\omega t = a \cos \omega t + \frac{1}{2} a \cos [(\omega - \Omega) t] + \frac{1}{2} a \cos [(\omega + \Omega) t]$, our amplitude-modified wave is the sum of three monochromatic waves with frequencies $\omega$, $\omega_1 = \omega - \Omega$ and $\omega_2 = \omega + \Omega$. The energy quanta corresponding to these waves correspond to

$$W_1 = \hbar \omega = 1,05 \cdot 10^{-27} \cdot 2 \cdot 10^{16} = 2,1 \cdot 10^{-11} \text{эрэ},$$
$$W_2 = \hbar \omega_1 = 1,05 \cdot 10^{-27} \cdot 1,8 \cdot 10^{16} = 1,89 \times 10^{-11} \text{эрэ},$$
$$W_3 = \hbar \omega_2 = 1,05 \cdot 10^{-27} \cdot 2,2 \cdot 10^{16} = 2,31 \cdot 10^{-11} \text{эрэ}.$$

At the same time, the nomization energy of the hydrogen atom is

$$W = 13,5 \text{яб} = 13,5 \cdot 1,6 \cdot 10^{-12} \text{эрэ} = 2,16 \times 10^{-11} \text{эрэ}.$$

This energy is greater than $W_1$ and $W_2$. Therefore, the first and second waves cannot change the hydrogen atom. Only the third wave can do this. The energy of the electrons $W_9$ knocked out of it from hydrogen atoms will be equal to the value $W_9 - W = 1,5 \times 10^{-12} \text{эрэ}.$

The correct solution was sent by $T$. Ros-mozueva (Kokand, Uzbek USSR).

F90

An ideal gas of mass $m$, located at a temperature $T$, is cooled isochorically so that the pressure drops $n$ times. The gas then expands at constant pressure. In the final state its temperature is equal to the initial one. Determine the work done by the gas. The molecular weight of the gas is $\mu$.

The process diagram is shown at figure 8. The work done by the gas is $A = p_2 (V_2 - V_1)$. Since points 1 and 3 lie on the same isotherm, then $p_1 V_1 = p_2 V_2$ and $V_2 = V_1 \frac{p_1}{p_2}$.

Pozny

$$A = p_2 V_1 \left( \frac{p_2}{p_1} - 1 \right) = \frac{1}{n} p_1 V_1 (n - 1).$$

But $p_1 V_1 = \frac{m}{\mu} RT$ therefore

$$A = \frac{m}{\mu} RT \left( \frac{n - 1}{n} \right).$$

This task turns out to be easy and its correct solution was sent in by more than 70 readers of our magazine.

Fig. 8.

⟦folio none⟧

To power the device, the voltage at its input must be set as accurately as possible. For this, two rheostats are used, connected as shown in figure 9. The lengths of the rheostats are the same, and the resistance of one of them is 10 times greater than the resistance of the other. What should I do to set the voltage as accurately as possible? How many times will the accuracy of voltage setting be greater than in the case when only a single circuit is used?

How should rheostats be turned on if, to power the device, it is necessary to set not the voltage, but the current as accurately as possible?

Rheostat $R_1$ has little effect on the voltage on the device. Therefore, it is clear that you first need to set the voltage on the device using resistance $R_2$ and then adjust it with rheostat $R_1$.

Indeed, if the length of the rheostat is equal to $l$, and the accuracy in setting the rheostat is $\Delta l$, then the accuracy in the resistance of the rheostat $R_2$ is equal to $\Delta l \frac{R_2}{l} = \frac{\Delta l}{l} R_2$, and the accuracy

Fig. 9.

Fig. 10.

The accuracy in setting the resistance of the rheostat $R_1$ is equal to $\frac{\Delta l}{l} R_1 = \frac{1}{10} \frac{\Delta l}{l} R_2$, that is, 10 times less than the accuracy of setting the resistance of the rheostat $R_2$. Therefore, with the tactics we talked about, it was possible to select the resistance of the rheostats 10 times more accurately than when using only one resistance $R_2$. The voltage drop across the rheostats and the voltage drop across the device will be determined just as much more accurately.

Since it is not very clear in advance which direction we will go wrong when setting the resistance $R_2$, that is, what we will have to do with the help of the rheostat $R_1$ - increase or decrease the resistance, then before installing the rheostat $R_2$ rheostat engine $R_1$ we need to install the last rheostat.

If we need to establish as accurately as possible not the voltage on the device, but the current flowing through it, then in this case the rheostats should be connected in parallel to the device as a shunt, and the main one in this case will be the rheostat with the lower resistance: it is through it that the most point will flow.

The second rheostat with high resistance must be connected in parallel with the persim (Fig. 10) and the current setting is as follows: first install the rheostat slider $R_2$ last, then set the current using rheostat $R_1$ and adjust it using rheostat $R_2$.

Since the current flowing through the rheostat is equal to $I = \frac{U}{R}$, then if the rheostat resistance is set inaccurately $\Delta R$, the inaccuracy in setting the point is $\Delta I = \frac{U}{R} - \frac{U}{R + \Delta R} = \frac{U}{R(R + \Delta R)} \approx \frac{U}{R^2} \Delta R$.

Using resistance $R_1$, we will get the accuracy of setting the point equal to $\frac{U}{R_2} \frac{\Delta l}{l} = \frac{1}{10} \frac{U}{R_1} \frac{\Delta l}{l}$, that is, it will be 10 times less than when using only rheostat $R_1$.

The correct solution was sent by A. Alexandrov (Glazov, UASSR), V. Kovalev (Kommunarsk, Voroshilovgrad region), A. Demidov (Moscow), N. Fedin (Omsk).

I. Sh. Slovodechkiy

⟦folio none⟧

In 1972, on pages «Kvant» the publication of materials will continue under the direction of the “Enrollee Practice”. The receipt of the letter to the editor shows that this section is of keen interest to many readers of the magazine. We are grateful to everyone who gave us their comments and suggestions.

Of course, there is no way to cover all the questions included in the program of entrance exams in mathematics and physics. Yes, there is no need for this - these issues are studied at school and discussed in detail in school textbooks. Therefore, the editors of our text also include topics that, in one form or another, are most often used when solving competitive problems and cause difficulties for applicants.

We propose, for example, to talk about problems involving combinations of spatial bodies, about the requirements for mathematical definition, about solving a problem in stereometry and the reasonable use of drawings in geometric problems. In physics, articles will be published relating to such issues as the law of conservation of momentum, solving the problem of tell processes, current laws and others.

The theoretical issues considered in these articles are accompanied by an analysis of specific examples, taken, as a rule, from versions of entrance exam papers. At the end of each article there will be problems for independent solution, helping readers to check how successful they are in what they read. These tasks are also mainly taken from the entrance exam versions of recent years.

Taking into account the numerous wishes of readers, for information purposes we will continue to include variants of problems offered in written exams at various universities across the country in 1971. Familiarization with these materials will allow applicants to concretely imagine what a written sample exam is, and to try their hand at solving a set of problems in advance in a limited time (usually 4 hours). For example, you can recommend that page applicants take an independent “exam” by solving the entire option in 4 hours and recording it. Such training, as close as possible to the exam conditions, turns out to be especially effective. We only note that you need to attend it having studied the theoretical sections well enough.

⟦folio 47⟧

2. Solve the equation
$$\sqrt{5x-6} = x.$$
ODZ: $x \geqslant \frac{6}{5}$. For such values ​​of $x$ both sides of the equation are non-negative. Therefore, according to Theorem 2 (we take the ODZ as the set $M$), only those roots of the equation $5x-6 = x^2$ that lie in the ODZ serve as solutions to this equation. Since the roots $x_1=2, x_2=3$ of this quadratic equation satisfy the inequality $x \geqslant \frac{6}{5}$, then both of them are roots of the original equation. And in this case, checking the obtained values ​​by substituting into the original equation is not necessary.

3. Solve the equation
$$\sqrt{x^2-3} = \sqrt{x-1}.$$
ODZ is determined by a system of inequalities
$$\begin{cases} x^2-3 \geqslant 0, \\ x-1 \geqslant 0, \end{cases}$$
whence $x \geqslant \sqrt{3}$. By squaring both sides of the equation and using formulas for transforming radicals, we arrive at the quadratic equation $x^2-x-2=0$, whence $x_1=2, x_2=-1$. Odz determines only the value of $x_1=2$; it is the only root of the original equation.

4. Solve the equation
$$\sqrt{x+1} = 8-\sqrt{3x+1}.$$ (1)
ODZ: $x \geqslant -\frac{1}{3}$. The left side of this equation is positive (in ODZ), but the right side can take both positive and negative values. Therefore, you should not rush to square both sides of the equation - as a result, roots may appear.

This is easy to avoid - just rewrite equation (1) in the form
$$\sqrt{x+1}+\sqrt{3x+1} = 8.$$
Here both sides are already non-negative, and squaring will not lead to the appearance of the constructed solutions. The task, thus, coincides with finding the roots of the equation belonging to the ODZ
$$\sqrt{3x^2+4x+1} = 31-2x.$$ (2)

We again have to square both sides of this equation, and again we face the same danger - the construction of a solution may appear (the right side of equation (2) takes on the values ​​of different icons in the ODZ).

One thing we note is that not a single value of $x$ for which $31-2x < 0$ can serve as a root of equation (2) (any positive number would be equal to a negative one!). In other words, all roots of equation (2) satisfy the inequality $x \leqslant 31/2$; we are only interested in those roots for which condition $x \geqslant -1/3$ is satisfied.

Consequently, we must look for solutions to equation (2) that belong to the interval $-\frac{1}{3} \leqslant x \leqslant 31/2$. Based on Theorem 2, we can be sure that on this interval equation (2) is equivalent to the equation
$$3x^2+4x+1 = (31-2x)^2.$$
Only one root $x=8$ of the best quadratic equation satisfies the condition $-\frac{1}{3} \leqslant x \leqslant 31/2$; it serves as a solution to equation (1). Testing by substitution is obviously not needed.

5. Solve the equation
$$\sqrt{x^2+x-5}+\sqrt{x^2+8x-4} = 5.$$ (3)
ODZ is defined as the solution to a system of inequalities
$$\begin{cases} x^2+x-5 \geqslant 0, \\ x^2+8x-4 \geqslant 0. \end{cases}$$
We, however, may not solve this system, but remember that any root of equation (3) must satisfy the general inequalities (4).

Of course, all the conditions of Theorem 2 are satisfied - you can square equation (3) without fear of the appearance of constructed solutions. But alas! In this country this operation

⟦folio 48⟧

inappropriate. Square both sides of equation (3) and you will see how complex the equation becomes.

It is much more convenient to do this: we rewrite equation (3) in the form

$$\sqrt{x^2+x-5} = 5 - \sqrt{x^2+8x-4}$$

and square both of its parts. Of course, now Theorem 2 does not apply, and this transformation can lead to the appearance of constructed roots. Therefore, we will need to do a check - it will eliminate the construction of the solution (if they appear).

So, let's square both sides of equation (5); we get

$$10\sqrt{x^2+8x-4} = 7x + 26.$$

We apply the same operations to this equation again. But first we note that all its roots must satisfy the condition $7x+26 \geq 0$, that is, $x \geq -26/7$.

As a result, we arrive at the equation

$$51x^2+436x-1076 = 0,$$

whence $x_1=2, x_2=-\frac{538}{51}$. Note that $x_2 < -\frac{26}{7}$, it remains to check the value of $x_1=2$ by direct substitution into the original equation (3). It turns out that it is the root of equation (3).

Please note: during the solution, we did not need to solve the system of inequalities (4) describing the ODZ of the original equation.

Introduction of auxiliary unknowns

Successfully introduced auxiliary unknowns sometimes make it possible to obtain a solution faster and easier.

6. Solve the equation

$$(x+5)(x-2)+3\sqrt{x(x+3)}=0.$$

Let's rewrite the equation like this:

$$x^2+3x-10+3\sqrt{x^2+3x}=0.$$

It can be seen that if the auxiliary unknown is $y=\sqrt{x^2+3x}$, then the equation takes the form $y^2+3y-10=0$, hence $y_1=-5, y_2=2$.

Now the problem reduces to solving equation $\sqrt{x^2+3} = -5$ and equation $\sqrt{x^2+3x} = 2$. The first of these equations has no solution, but from the second we obtain $x_1=-4, x_2=1$.

7. Solve the equation

$$\sqrt{47-2x}+\sqrt{35+2x}=4.$$

Raising both sides of this equation to the fourth power does not promise anything good. If we put

$$y=\sqrt{47-2x}, z=\sqrt{35+2x},$$

then equation (6) is rewritten as follows:

$$y+z=4.$$

Since we have introduced two new unknown functions, we need to find another equation relating $y$ and $z$. To do this, we raise equalities (7) to the fourth power and note that $y^4+z^4=82$.

So, we need to solve the system of equations

$$\begin{cases} y+z=4, \\ y^4+z^4=82; \end{cases}$$

it has two (real) solutions: $y_1=1, z_1=3; y_2=3, z_2=1$. It remains to solve the system (of two equations with one unknown!)

$$\begin{cases} \sqrt{47-2x}=3, \\ \sqrt{35+2x}=1 \end{cases}$$

and systems

$$\begin{cases} \sqrt{47-2x}=1, \\ \sqrt{35+2x}=3; \end{cases}$$

the first of them gives $x_1=-17$, the second gives $x_2=23$.

Multiplying both sides of an equation by a function

Sometimes an irrational equation can be solved quite quickly if both sides are multiplied by a well-chosen function. Of course, when both sides of the equation are multiplied by some function, a solution may appear, or this may turn out to be zeros

⟦folio 49⟧

functions*). Therefore, the proposed method requires mandatory research of the resulting values.

8. Solve the equation
$$\frac{1}{4} x = (\sqrt{1+x} - 1)(\sqrt{1-x} + 1).$$
(8)

Let's multiply both sides of the equation by the same function $h(x) = \sqrt{1+x} + 1$. The expression $\sqrt{1+x} + 1$ is called the conjugate of the expression $\sqrt{1+x} - 1$. The purpose of such multiplication, it seems, is clear: to use the fact that the product of two conjugate expressions no longer contains radicals.

As a result of this multiplication and very significant transformations, we arrive at the equation

$$x(\sqrt{1+x} - 4\sqrt{1-x} - 3) = 0.$$

It has a single root $x=0$, since the equation $\sqrt{1+x} - 4\sqrt{1-x} - 3 = 0$ has no solutions (check it out!).

Substitution into equation (8) shows that $x=0$ is a root. Otherwise, you can do without substitution: the equation $h(x)$where does not vanish, and therefore multiplying the general equation (8) by this function does not lead to the appearance of the constructed solutions.

9. Solve the equation
$$\sqrt{2x^2+3x+5} + \sqrt{2x^2-3x+5} = 3x.$$ (9)

Multiply both sides of the equation by the expression
$$\sqrt{2x^2+3x+5} - \sqrt{2x^2-3x+5},$$
conjugation for the expression on the left side. After estimated transformations we obtain

$$x(\sqrt{2x^2+3x+5} - \sqrt{2x^2-3x+5}) = 2x.$$

*) See «Kvant» No. 5, 1970, pp. 49-50.

This equation has a root $x=0$, but this value does not satisfy the original equation (9). Therefore, we can assume that $x \neq 0$, and reduce both sides of the last equation by $x$:

$$\sqrt{2x^2+3x+5} - \sqrt{2x^2-3x+5} = 2.$$ (10)

Adding equations (9) and (10), we obtain the equation.

$$2\sqrt{2x^2+3x+5} = 2 + 3x,$$

the solution of which does not seem more difficult. It has the root $x=4$ (make sure of this!).

The check required in this case shows that this value satisfies equation (9).

Exercises

Solve equations:

1. $$\sqrt{25-x} = 2 - \sqrt{9+x}.$$
2. $$\sqrt{x+2} - \sqrt{3x+2} = 0.$$
3. $$\frac{\sqrt{12+x}}{x} + \frac{\sqrt{12+x}}{12} = \frac{64}{3}\sqrt{x}.$$
4. $$\frac{(5-x)\sqrt{5-x} + (x-3)\sqrt{x-3}}{\sqrt{5-x} + \sqrt{x-3}} = 2.$$
5. $$\sqrt{x-2} + \sqrt{x+2} = 2.$$
6. $$\frac{\sqrt{x+4} + \sqrt{x-4}}{2} = x + \sqrt{x^2-16} - 6.$$
7. $$\sqrt{3\sqrt{4-4x+x^2}} + \sqrt{3\sqrt{49+14x+x^2}} = 3 + \sqrt{3\sqrt{14-5x-x^2}}.$$
8. (MSU, physicist, 1968.) For each active number $a$, find all real solutions to the equation $x + \sqrt{x} = a$.
9. (MSU, physicist, 1968.) For each active number $a$, find all real solutions to the equation $a\sqrt{1+x} + \frac{a}{x}\sqrt{1+x} = \sqrt{x}$.
