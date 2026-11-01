---
id: 1984-10-boltyanskiy-eksponenta-7ff4dd41
issue: kvant_1984_10
year: 1984
number: "10"
title: Exhibitor
authors:
  - Болтянский В. Г.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 22
page_last: 26
page_labels: 20-24
tag: 4WCW
lang: en
source: kvant_digital
extraction: vision
content_sha256: df1d4a401c09050ae1e6b95b313a51edc2f695a5cafaf184b0e3fa3b11022ce0
prompt_sha256: draft-1
translated_from: content/ru/1984/10/articles/09_boltyanskiy-eksponenta-7ff4dd41.md
source_content_sha256: 5818213399aa2c72b2b8b555f79aa58ddaf995dc1a855bcea436ea751faeb315
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 20⟧

Exhibitor

Corresponding Member of the Academy of Pedagogical Sciences of the USSR
V. G. BOLTYANSKY

In any school textbook, the presentation of the topic about the exponential function and the number e contains unproven statements, briefly stated passages. This is explained by the complexity of the topic. Here we will talk about a different approach to these concepts, exploring their meaning and connection with differential equations. With this method of presentation, there are also unproven statements (the general theorem of nouns and uniqueness for differential equations and the property of a continuous function to take intermediate values). However, these unproven statements have a simple visual meaning and are of fundamental importance for all mathematics.

1. Problem about a body falling in a resistive environment

The descending parachutist is affected by the force of gravity and the force of air resistance (the remaining possibilities for differential equations and the property of a continuous function to take intermediate values). The force of air resistance can be considered proportional to the speed $v$, that is, equal in magnitude to $qv$ (the coefficient $q$ depends mainly on the diameter and shape of the parachute). Thus,

$$ma = mg - qv,$$

where $a = v'$ is the acceleration value (the minus sign in front of $qv$ is due to the fact that the air resistance force acts opposite to the direction of fall; Fig. 1). Dividing by $m$ we get

$$v' = -\frac{q}{m} v + g.$$ (1)

Correspondence (1) is a linear differential equation: the derivative of the unknown function $v = v(t)$ (which needs to be determined from this equation) is expressed as a first-degree polynomial of this unknown function. Denoting the unknown function by $y = y(x)$, and the coefficients by $a$ and $b$, we write the differential equation in the form

$$y' = ay + b.$$ (2)

This differential equation describes not only the fall of a body in a resisting medium, but also multi-dimensional physical processes.

2. Existence and uniqueness theorem

Theorem 1. Whatever the real numbers $x_0, y_0$, there is only one function $y = y(x)$, which is a solution to equation (2) and satisfies the corresponding equation $y(x_0) = y_0$. This solution is defined on the entire number line.

The relation $y(x_0) = y_0$ is called the naal condition. Thus, Theorem 1 means that equation (2) for any given nal condition has a solution (and, moreover, a unique one).

Let's present the geometric theory of this theorem, and consider the special case when $a = 1$, $b = 2$, that is, take the equation

$$y' = y + 2.$$ (3)

At the points where $y = 0$ (on the axis $x$), we have, according to (3), $y' = 2$, that is, the graph of the original function $y(x)$ should have a tangent slope equal to 2 at these points. Let us outline the direction of the tangent (Fig. 2) with short lines drawn at the points of the abscissa axis. Further, for $y = 1$ we have, according to (3), $y' = 3$, that is, at the points of the straight line $y = 1$ the graph of the original function must have a tangent slope equal to 3; Let us mark the direction of the tangent at the points of the straight line $y = 1$ with short dashes. We can then mark lines on other lines parallel to the x-axis (Fig. 2). Now the behavior of the “field lines” of this “directional field” becomes clear. At each point, the “line of force” touches the corresponding line, that is, its tangent has an angular coefficient of $y'$, which, due to the construction of the line, is equal to $y + 2$. This means that the "field line" is the graph of a function satisfying equation (3). From the drawing it is clear that through each point $(x_0; y_0)$ there is a “line of force” and, moreover, only one. This provides a clear confirmation of the validity of Theorem 1. Its proof

⟦folio 21⟧

3. Exhibitor

A function satisfying the differential equation $y'=y$ and the initial condition $y(0)=1$ is called an exponential and is denoted by the symbol expr.

Note that the equation $y'=y$ is a partial random equation of equation (2); therefore, its solution with the initial condition $y(0)=1$, by virtue of Theorem 1, exists and is uniquely determined, and the domain of definition of this solution (that is, the exponential) is a straight line.

It follows directly from the definition that the exponential is a differentiable function and its derivative coincides with the same function (since it is a solution to the equation $y'=y$):

$$\text{exp } x' = \text{exp } x.$$  (4)

Theorem 2. The values ​​of the function expr are positive, that is, expr $>0$, for any real $x$.

Proof. Let us assume that expr $x_0=0$ for some $x_0$. Then the function $y=\text{exp } x$ satisfies the equation $y'=y$ and the condition $y(x_0)=0$. The function $y\equiv 0$ also satisfies the equation $y'=y$ and the condition $y(x_0)=0$. Moreover, the function $y=\text{exp } x$ and $y\equiv 0$ are different (for example, expr $0=1$, that is, expr $0\neq 0$). But then it turns out that the equation $y'=y$ has two different solutions under the initial condition $y(x_0)=0$, which contradicts Theorem 1. So, the equality expr $x=0$ cannot take place for any $x$.

Let us now assume that for some $x_1$ we have expr $x_1<0$. The function expr is differentiable and therefore continuous; therefore, between two points at which it takes values ​​of different signs ($\text{exp } x_1<0$, expr $0=1$), this function must vanish (Fig. 3). But this, as we have seen, is impossible.

So, the exponent can take neither zero nor negative values; hence expr $x>0$ for any $x\in R$.

Consequence. An exponential is an increasing function.

⟦folio 22⟧

Indeed, the derivative function exp (that is, this function itself) takes, according to Theorem 2, only positive values, and therefore the function exp is increasing.

Theorem 3. For any p, q ∈ R we have

$$\exp(p+q) = \exp p \cdot \exp q.$$ (5)

Proof. Consider the function y = exp(p+x). We have

$$y' = (\exp(p+x))' = \exp(p+x) = y$$

(see (4)), that is, this function satisfies the equation y'=y. In this case y(0) = exp p.

Let us now consider the function y = exp p · exp x. We have

$$y' = \exp p \cdot (\exp x)' = \exp p \cdot \exp x = y$$

that is, this function also satisfies the equation y'=y. In this case y(0) = exp p. According to Theorem 1, the functions under consideration coincide:

$$\exp(p+x) = \exp p \cdot \exp x.$$

In particular, for x=q we obtain (5).

4. Number e

Exp function value. when x=1 is denoted by the letter e, that is, e=exp 1. To find the approximate value of the number e, you can proceed as follows. Let's divide the segment [0; 1] into n equal parts (each of them has a length Δx=1/n). Through the point A0 (0; 1) we draw a “dash” corresponding to the equation y'=y; it has an angular coefficient k1=y, that is, k1=1. We will consider this “dash” over the segment [0; 1/n]. Its right end A1 has coordinates x=1/n, y=1+k1Δx=1+1·1/n=1+1/n (Fig. 4).

Through A1 we draw a new “dash”, also corresponding to the equation y'=y; its angular coefficient is equal to y (the ordinate of point A1), that is, equal to k2=1+1/n. We will consider this “dash” over [1/n; 2/n]. Its right end A2 has coordinates

$$x = \frac{2}{n}, y = \left(1 + \frac{1}{n}\right) + k_2 \Delta x =$$

$$= \left(1 + \frac{1}{n}\right) + \left(1 + \frac{1}{n}\right) \cdot \frac{1}{n} = \left(1 + \frac{1}{n}\right)^2$$

Through A2 we again draw a “dash” corresponding to the equation y'=y. Its angular coefficient k3 is equal to the ordinate of point A2, that is, k3=(1+1/n)^2, and the right end of A3 has coordinates x=3/n, y=(1+1/n)^2+k3Δx = (1+1/n)^3.

Continuing, we obtain the broken line A0A1A2...An - the Euler broken line for the equation y'=y (on Fig. 4, for convenience, different scales are taken on the axes); point An has coordinates x=1, y=(1+1/n)^n. This broken line gives an approximate idea of ​​the solution to the equation y'=y passing through the point A0, that is, the function y=exp x (red graph on figure 4); in particular, point An is close to the graph point y=exp x, which has an abscissa x=1, that is, to point (1; e). In other words, (1+1/n)^n≈e. The larger n, the more accurate this approximate equality is, and therefore

$$\lim_{n \to \infty} \left(1 + \frac{1}{n}\right)^n = e.$$ (6)

For example, taking n=1,000,000, that is, performing the action 1.0000011000000 (this is easy to do with a microcalculator), we find e=2.7182818...

5. Notation e^x

Lemma. For any rational x the equality is true

$$\exp x = e^x.$$ (7)

Piss. 4.

⟦folio 23⟧

Proof. Consistently applying formula (5), we find
$$\exp 2x = \exp (x+x) = \exp x \cdot \exp x = (\exp x)^2,$$
$$\exp 3x = \exp (2x+x) = \exp 2x \cdot \exp x = (\exp x)^2 \cdot \exp x = (\exp x)^3$$
etc. So, for the natural $n$ we have
$$\exp nx = (\exp x)^n,$$
whence $\exp x = (\exp nx)^{1/n}$. The field here is $x=m/n$ (where $m$ is a natural), we get
$$\exp \frac{m}{n} = (\exp m)^{1/n} = (\exp m \cdot 1)^{1/n} = \left((\exp 1)^m\right)^{1/n} = (\exp 1)^{m/n} = e^{m/n}$$
This means that for a positive rational number $x=m/n$ the lemma being proved is valid. It is easy to check that it remains valid for negative rational numbers (as well as for $x=0$).
The conditions are to assume by definition that correspondence (7) is valid for any real number $x$. In other words, we assume that $e^x$ is simply another form of writing for $\exp x$ (and for rational $x$ this form of writing is consistent, by virtue of the proven lemma, with an understandable formula with a rational exponent). When using this notation, formula (5) takes on the familiar form $e^{p+q} = e^p e^q$. Note that in the mathematical literature both formulas for writing exponents are used: $y=e^x$ and $y=\exp x$.

6. Solving differential equations

When writing solutions to differential equations, the notation $e^x$ is often used rather than $\exp x$. We will adhere to this tradition.

Theorem 4. For $a \neq 0$, the solution to differential equation (2) with initial conditions $y(0)=y_0$ has the form
$$y = -\frac{b}{a} + ce^{ax},$$
(8)
$$e\delta e = b/a + y_0.$$
Proof. Since (according to Theorem 1) the elimination of the only one, it is enough to only check that function (8) (for the specified value of $c$) satisfies equation (2) and the required initial condition. We have
$$y' = (ce^{ax})' = c(e^{ax})' = cae^{ax} = a(ce^{ax}) = a(y + \frac{b}{a}) = ay + b,$$
that is, function (8) indeed satisfies equation (2) (for any value of the constant $c$). Next,
$$y(0) = -\frac{b}{a} + ce^0 = -\frac{b}{a} + c = -\frac{b}{a} + \left(\frac{b}{a} + y_0\right) = y_0.$$
This means that for the specified value $c$ the function $y$ also satisfies the required initial condition.

The proven theorem is promised to be applied as follows. The term $y = -b/a$ is easy to remember: it is obtained if $y'$ is equal to zero; further, the coefficient $a$ for the unknown function in (2) becomes the coefficient for the argument in the exponent. As for 常态ы $c$, its value (indicated in Theorem 4) is usually not remembered, and in each specific example $c$ is found using the initial conditions.

Example 1. The mass $m(t)$ of a radioactive substance present in a piece of rock at moment $t$ decreases over time, that is, the derivative $m'(t)$ (decay rate) is negative. If necessary, the amount of radioactive substance, the decay rate is proportional to the mass of the radioactive substance:
$$m' = -km$$
(where the coefficient $k > 0$ depends on the type of radioactive substance). Find the law of change of mass $m(t)$ over time, if at the initial moment $t=0$ the mass of the available radioactive substance was equal to $m_0$.

Solution. By Theorem 4 we have $m(t) = ce^{-kt}$. Substituting $t=0$, we get $m_0 = ce^0$, hence $c = m_0$. The final result is $m(t) = m_0e^{-kt}$.

Example 2. After what period of time $T$ will the amount of radioactive substance decrease by exactly half?

Solution. We need to find $T$ from the equation $m_0/2 = m_0e^{-kT}$, that is, $e^{-kT} = 1/2$, or $e^{kT} = 2$. This corresponds to the equilibrium of the following: $\ln 2 = kT$, whence $T = (\ln 2)/k \approx 0.7/k$.

The value $T = (\ln 2)/k$ is called the half-life. It depends on $k$ (i.e. radioactive substance); for example, for radium $T \approx 1600$ years.

⟦folio 24⟧

Example 3. Find the law of the fall of a body in a resisting medium, knowing that at $t=0$ the speed of fall was equal to $v_0$.

Solution. From equation (1) we find by Theorem 4:

$$v(t) = \frac{mg}{q} + ce^{-\frac{q}{m}t}.$$

Substituting $t=0$, we get $v_0=mg/q+ce^0$, hence $c=v_0-mg/q$. Thus, we finally have

$$v(t) = \frac{mg}{q} + \left(v_0 - \frac{mg}{q}\right)e^{-\frac{q}{m}t}.$$

Since $e^{-\frac{q}{m}t} \to 0$ at $t \to \infty$, then $v(t) \to mg/q$, it would become, the rate of fall is gradually established. For example, a parachutist falling in a long jump at high speed, after opening the parachute, quickly acquires an approximately constant speed $mg/q$ (depending on the mass of the parachute and the parameters of the parachute). This allows the parachute to be calculated so that the landing is safe.

Exercise
1. Prove that for any $x \neq 0$ the equation $x > x+1$ is valid.
2. Using the inequality $\exp \frac{1}{n} > 1 + \frac{1}{n}$ (see Problem 1), prove that $e > (1+1/n)^n$.
3. Using the inequality $\exp \left(-\frac{1}{n+1}\right) > 1 - \frac{1}{n+1}$ (see Problem 1), prove that $e > (1+1/n)^n$, that is, $e < (1+1/n)^{n+1}$.
4. Using the inequalities obtained in problems 2 and 3, prove equalities (6).
5. Prove that the solution to equation (2) with the initial condition $y(x_0)=y_0$ has the form (8), where $c=(b/a+y_0)e^{-ax_0}$.
6. At moment $t=t_0$ the mass of the radioactive substance present in the piece of rock was equal to $m_0$, and at moment $t=t_1$ it turned out to be equal to $m_1$. Determine the half-life.
7. When one gram of radioactive material decays, $d$ grams of decay product are produced. The half-life $T$ of this radioactive substance is known. Determine the age of a piece of rock if it contains $p$ grams of the radioactive substance in question and $q$ grams of its decay product.
8. As a result of heat exchange with the environment, the heated body gradually cools, that is, its temperature $t(\tau)$ decreases with time $\tau$. According to Newton's law of cooling, the cooling rate is proportional to the difference in temperature between the body and the environment: $t'(\tau) = -k(t(\tau) - t_{cp})$. Assuming the temperature of the medium $t_{cp}$ to be constant, derive the formula for the cooling law.
9. The strength of the current $I(t)$ flowing in the $RL$-cell (Fig. 5) varies according to the rule $LI' + RI = E$, where $L$ is the inductance of the coil, $R$ is the resistance of the resistor. Determine the law $I(t)$ of current change if at the moment of circuit closure ($t=0$) the current was zero.
10. In the $RL$-circuit (Fig. 6) at the moment $t=0$ current $I_0$ flowed. Determine the value of the current flowing in the circuit at $t>0$.
11. The voltage $u(t)$ (potential difference on the capacitor plates) changes in the $RC$-target (Fig. 7) according to the rule $Cu' + u/R=0$. Determine the characteristic of the voltage change if at the moment $t=0$the voltage was equal to $u_0$.
12. Considering the Euler polyline for the equation $y'=y$ with the initial condition $y(0)=1$, show that for a fixed $x>0$ the sequence $(1+x/n)^n$ returns and is bounded.
13. Using Weierstrass's theorem on a bounded increasing sequence and Problem 12, establish the existence of the limit $(1+x/n)^n$ for fixed $x \geq 0$, and then for $x<0$.
14*. Prove the existence of the exponent. Note. Putting $y(x)=\lim_{n \to \infty} (1+x/n)^n$ (see Problem 13), calculate the product $y'(x)$ and the established fact that $y'(x)=\lim_{n \to \infty} (1+x/n)^n$; Deduce from this that $y(x)$ is a solution to equation $y'=y$ with initial condition $y(0)=1$. (When calculating $y'(x)$, use Newton’s biome formula.)
15*. Prove the only exponent. Note. Assume the opposite (the existence of two different exponentials) and consider their difference.
