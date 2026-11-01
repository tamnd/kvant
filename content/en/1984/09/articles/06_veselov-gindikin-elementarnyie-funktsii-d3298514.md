---
id: 1984-9-veselov-gindikin-elementarnyie-funktsii-d3298514
issue: kvant_1984_9
year: 1984
number: "9"
title: Elementary functions
authors:
  - Веселов А. П.
  - Гиндикин С. Г.
rubric: osnovnye-stati
page_first: 11
page_last: 16
page_labels: 9-14
tag: IBOE
lang: en
source: kvant_digital
extraction: vision
content_sha256: 66de144b5788f79bce7226f7280934ff24a393707aff3ffb8d0612d6a565b237
prompt_sha256: draft-1
translated_from: content/ru/1984/09/articles/06_veselov-gindikin-elementarnyie-funktsii-d3298514.md
source_content_sha256: 8443342b29d47c77a876f1fc39c7478567459e98aeefb1ef95d869932bb68629
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 9⟧

Elementary functions

Candidate of Physical and Mathematical Sciences
A. P. VESELOV
Candidate of Physical and Mathematical Sciences
S. G. GINDIKIN

This article covers exponential, logarithmic, and trionometric functions. These functions belong to the class of elemental functions (which also includes the linear function $y=ax+b$, power function $y=x^n$, as well as all possible combinations of the listed functions - sums, differences, products, quotients and compositions). These functions are called so because they were the first functions that were studied in mathematics, and for a long time basic mathematicians did not go beyond these functions.

We will look at the two main approaches to defining exponential, logarithmic and trionometric functions: aximatic and kinematic, make sure that these approaches lead to the same functions, and discuss their relationship with kinol definitions.

Aximatic definition of exponential function

An exponential function $a^x$ is a function $y=f(x)$ such that the following conditions are satisfied:

1) $f$ is defined for all $x$;

2) $f(1)=a>0$ ($a\neq 1$);

3) for any $x$, $y$ the correspondence is satisfied

$$f(x+y)=f(x)f(y);$$

4) $f(x)$ is a monotonic function.

The school theory of the exponential function consists in constructing a function that satisfies the four listed properties; the important thing is that there is only one function that has these properties. Otherwise, in school it is only proved that 2), 3) determine $f$ uniquely for rational $x$; the statement about the unique continuation to all $x$ from rational $x$ under condition 4) is given without proof (the proof can be found in the article by R.K. Gordin “What is degree”, Kvant, 1981, No. 2).

Such definitions of an object by enumerating its characteristic properties are called aximatic. It is necessary to understand that the aximatic definition of the exponential function is essentially no different from the school definition. Relation (2) is called the functional equation for the exponential function. Functional equations relate the values ​​of a function at different points, and their solutions are called the functions that correspond to them. In this case, the exponential functions are solutions to the functional equation (2) (and if the additional restrictions indicated above are met, there are no other solutions).

Problem 1. Prove that in the case of solution (2), the definition for all $x$ is or

⟦folio 10⟧

identical zero or an everywhere positive function (and therefore an everywhere defined exponential function exists only for non-negative bases $a$).

Today's pleasant aximatic approach to defining the exponential function did not arise immediately. It is noteworthy that the exponential function appears for the first time as a solution to a differential equation. This story deserves to be remembered.

Kinematic definition of exponential function

At the very beginning of the 17th century, Galileo (1564-1642) wanted to discover the law according to which free fall occurs. He hoped to discover this law purely speculatively, guided only by messages of simplicity. Therefore, he assumed that the free fall should be proportional to the distance traveled:

$$\dot{s} = \lambda s.$$

(3)

According to physical messages $\lambda > 0$ (the movement is accelerated) and $s(0) = 0$ (at the initial moment the body will accumulate). After some time, Galileo discovered with great surprise that the differential equation (3) could not have a solution with $s(0) = 0$ other than $s \equiv 0$ (an impossible motion with the properties that Galileo had originally attributed to free fall).

Task 2. Prove Galileo's statement. Note. Let $\lambda > 0$; then the speed $\dot{s}$ returns with an increase in $s$. If at some moment of time $t_0$ we have: $s(t_0) = c > 0$, then $\dot{s}(t_0) = \lambda c$; $\dot{s}(t) < \lambda c$ with $t < t_0$, which means $t_0 > 1/\lambda$ is independent of $c!$. From here it is easy to deduce that $s \equiv 0$.

This observation prompted Galileo to change the supposed law to $\dot{s} = gt$, which led him to the discovery of the law of free fall, and he was no longer interested in motion according to law (3). You can read more about this in the book by S. G. Gindikin “Stories about Physics and Mathematics” (M., “Nuka”, 1981).

We must remember another remarkable mathematician - John Napier, Baron Merchiston (1550-1617), who, almost in the same years as Galileo, studied motion according to the law (3) using different methods. If Galileo sought to obtain a mathematical description of a real mechanical phenomenon, then Napier moved in exactly the opposite direction: he wanted to give a mechanical interpretation to purely mathematical procedures. Even before Napier, mathematicians tried to take advantage of the connection between the argumentative and geometric progressions to simplify calculations (replacing multiplication with addition!). To increase accuracy, more “frequent” progressions were required, and Napier’s great insight was that this should be taken to the end and replaced discrete progressions with continuous values ​​- functions. Considering for this purpose the imaginary movement according to the law (3) and interpreting time as a continuous analogue of an argumentative progression, Napier convinces that then let it be an analogue of a geometric progression. Namely, if time $t$ is increased by $k$ unit, then let it be multiplied by $q^k$ for some $q$; if we move to smaller units of time, then, as before, time shifts $t$ correspond to transformations according to the law of geometric progression.

The main difference between Napier's approach and Galileo's approach is that it removes the $s(0) = 0$ constraint. Let $\lambda$ be fixed. An important property of motion (3) follows from Galileo's statement. Movement according to law (3) for a fixed $\lambda$ is completely determined by the value of $s$ at any fixed moment of time $t_0$. Indeed, if $s_1(t), s_2(t)$ are two movements with $s_1(t_0) = s_2(t_0)$, then for $s(t) = s_1(t) - s_2(t)$, which is also a solution to (3), we have: $s(t_0) = 0$, that is, $s \equiv 0$; by Galileo's theorem and $s_1(t) = s_2(t)$. Further, if $s$ is a solution to (3), then $s_1(t + t_0)$ is also a solution, which means that all solutions (3) differ only by a constant factor. Also, if $s$ is a solution, then $s_1(t) = s(t + t_0)$ is also a solution (for a fixed $t_0$).

Let $S_\lambda(t)$ be a solution of (3) such that $S_\lambda(0) = 1$. Let's take $s_1(t) = S_\lambda(t + t_0)$, $s_2(t) = S_\lambda(t) S_\lambda(t_0)$. Both of these functions will be solutions to (3), taking the same value $S_\lambda(t_0)$ for $t = 0$, and then must coincide. We get that

⟦folio 11⟧

$$S_{\lambda}(t+t_0) = S_{\lambda}(t) S_{\lambda}(t_0).$$

Further, the function $S_{\lambda}$ is differentiable, which means it is continuous. According to Halley's theorem, it does not vanish anywhere, which means it has the same sign everywhere, that is, $S_{\lambda}(t) > 0$ ($S_{\lambda}(0) = 1$). By virtue of (3), then $S_{\lambda}(t)$ has the same sign everywhere as $\lambda$, that is, it increases at $\lambda > 0$, kills at $\lambda < 0$.

So, the solution to equation (3) with $s(0) = 1$ is necessarily an exponential function. If we now differentiate (4) with respect to $t_0$ and put $t_0 = 0$, we get

$$S_{\lambda}(t) = S_{\lambda}(t) S_{\lambda}(0).$$

This means that the exponential function (assuming that it is differentiable) is a solution to (3), $\lambda = S_{\lambda}(0)$. The differentiability of the exponential function is proven directly (see “Algebra and the beginnings of analysis 9-10”, paragraph 65).

One more issue needs to be discussed. We investigated solution (3) under the assumption that they exist. This assumption follows from a general fact about differential equations, which we will not prove here*). If we accept it, then we obtain the exponential existence of an exponential function, different from that realized above. On the other hand, the solvability of equation (3) follows from the existence and differentiability of the exponential function.

Number $e$ (non-first number)

We now have two approaches to defining the exponential function. With an axiomatic definition, exponential functions are naturally distinguished by their bases $f(1) = a$. If we proceed from equation (3), then the more natural one is based on the coefficient $\lambda$. How are these CONSTANTS related?

First of all, using the natural kinematic approach, select the exponential function corresponding to $\lambda = 1$. Its base is usually denoted by $e$ and called a non-prime number, and the function itself is sometimes denoted expr $t$ (after the beginning of the word “exponent”). So, for a movement occurring according to the law $\dot{s} = s$, for which $s(0) = 1$, we have: $s(t) = e^{\dot{s}}$ ($= \exp t$).

Let's explore the number $e$. This is the distance from the beginning at which the point appears at time $t = 1$. Since the movement occurs with a speed greater than 1, and the movement begins at a distance of 1 from the beginning, we obtain that at $t = 1$ the distance is $e > 1 + 1 = 2$. Let us show that, on the other hand, $e < 3$ (the point will not have time to go beyond mark 3). To do this, we will divide it from 1 to 3 into 8 equal parts (the length of one part is 1/4). The point will pass through the first segment with a speed not exceeding its value at the right end of the segment, where, by virtue of (3), it is equal to 5/4; therefore, the time required for this segment is at least 1/5. Similarly, the second segment will take at least 1/6, the third - at least 1/7, etc. The total time on the path from 1 to 3 is no less than $\frac{1}{5} + \frac{1}{6} + \frac{1}{7} + \frac{1}{8} + \frac{1}{9} + \frac{1}{10} + \frac{1}{11} + \frac{1}{12}$, and this sum is greater than 1. This means that point $e$ lies close to 3.

If we now divide the time segment $[0, 1]$ into $n$ equal parts, then in the first time segment the speed is greater than 1, the point will travel $\Delta t = 1/n$ a distance longer than $1/n$ and turns out to be farther from the beginning than $1+1/n$ with a speed exceeding the segment $\Delta = 1/n$ it will travel a path greater than $(1+1/n)/n$, and the point turns out to be at a distance greater than $(1+1/n)^2$ from the beginning with a speed greater than $(1+1/n)^2$, etc., at the moment of time $t = 1$ - at a distance $(1+1/n)^n$ from the beginning.

From this reasoning, it seems correct that as $n$ increases, the value $a_n = (1+1/n)^n$ increases (prove that this is true!) and tends to $e$. In the textbook “Algebra and the beginnings of analysis 9-10” (§22, paragraph 113) he proves that

$$e = \lim_{n \to \infty} \left(1 + \frac{1}{n}\right)^n,$$

from which, in particular, $e$ can be determined with any accuracy. Recall that $e = 2,718281828459045\dots$. Similarly, it is proved that

$$e' = \lim_{n \to \infty} \left(1 + \frac{t}{n}\right)^n.$$

Consider the kinematic interpretation of this equality.

Problem 3. Give a kinematic proof of the inequality

⟦folio 12⟧

$$e < \left(1 + \frac{1}{n}\right)^{n+1}.$$

Note. Divide the path segment $[1, \left(1 + \frac{1}{n}\right)^{n+1}]$ into $(n+1)$ segments of the form $[\left(1 + \frac{1}{n}\right)^{k-1}, \left(1 + \frac{1}{n}\right)^k]$. Then, when moving along the $k$-th segment of length $\frac{1}{n+1}\left(1 + \frac{1}{n}\right)^k$, according to the law $\dot{s} = s$, the speed does not exceed $\left(1 + \frac{1}{n}\right)^k$, and the time spent is correspondingly greater than $1/n+1$, that is, the total time is greater than 1.

Let's return to the question with which our conversation about the number $e$ begins. Let $S_\lambda(t) = a^t$. How are $\lambda$ and $a$ related? Noting that if $s(t)$ is a solution to (3) for some $\lambda$, then $s(ct)$ is a solution to (3) with $\lambda' = c\lambda$ and the same value at zero, that is, $S_{\lambda c}(t) = S(ct)$, whence $S_\lambda(t) = a^t$, where $a = e^\lambda$.

Thus, the connection between $a$ and $\lambda$ is very simply expressed through a non-nuclear number.

Let us summarize the consideration of equation (3). We have proven that the general solution to this equation is $s(t) = s_0 \exp(\lambda t), s_0 = s(0)$.

Equation (3) is called the equation of exponential (or exponential) growth (or decrease at $\lambda < 0$). It describes many processes found in nature: radioactive decay, changes in temperature over time and pressure with altitude, the laws of biological and social development and other processes. The most important characteristic of the exponential function, manifested in the phenomena it describes, is its rapid growth (at $\lambda > 0$). In particular, exponential growth (at $\lambda > 0$) exceeds any degree of growth, and exponential decrease (at $\lambda < 0$) exceeds degrees of decrease, namely

$$\lim_{t \to +\infty} \frac{t^k}{\varepsilon^{\lambda t}} = 0 \quad (\lambda > 0), \quad \lim_{t \to +\infty} e^{\lambda t} t^k = 0 \quad (\lambda < 0)$$

(“Algebra and the beginning of analysis 9-10”, § 22, paragraph 117).

Logarithmic function $\log_a x$, $a > 0, a \neq 1$

This function is defined as the inverse of the exponential function $a^x$, $a \neq 1$, and all its properties follow directly from this definition.

It is defined at $x > 0$, its range is the entire line, $\log_a x$ increases at $a > 1$ and decreases at $a < 1$, $\log_a 1 = 0$, but most importantly, it has a functional equation (called the “basic property of the logarithm” in school)

$$\log_a xy = \log_a x + \log_a y,$$

(7) which follows directly from the functional equation for the exponential function (1) (why?). A logarithmic function can also be described as a nomatic function: $\log_a x$ is a monotonic function equal to 1 for $x = a$, satisfying (7) and defining for all $x > 0$ (prove!). Note that when passing over the logarithmic function we essentially use the strict monotonicity of $a^x$ for $a \neq 1$ (this ensures the existence of the inverse function); for this reason, $a = 1$ is excluded.

The natural logarithm $\ln x$ is defined as the inverse of $e^x$, that is, the time it takes for a point moving according to $\dot{s} = s$ to get from 1 to $x$.

It can be said that it was the logarithmic function, and not the exponential, that was Napier's goal. However, the picture he constructed was somewhat complicated. He considered equation (3) with $\lambda = 10^{-7}$ and took its solution with $s(0) = 10^7$, that is, $s(t) = 10^7 \exp(10^{-7} t)$; Accordingly, the inverse function - the Neper logarithm - had the form $t = \text{Ner} \log x = 10^7 \ln 10 + 10^7 \ln x$, and for it it is not true that $t(x \cdot y) = t(x)t(y)$, $t(1) = 0$. Towards the end of twenty years of compiling the table of logarithms, Napier undoubtedly felt dissatisfaction with the system he had adopted. He already had the idea of ​​decimal logarithms, but did not have the strength to carry out direct calculations.

⟦folio 13⟧

stump The corresponding tables were compiled longitudinally by the mathematician Henry Briggs, who had the opportunity to discuss the idea of ​​decimal logarithms with Napier in his later years. Decimal logarithms are still sometimes called Brissian logarithms (Briggs’ book “The Arithmetic of Logarithms,” published in 1624, was dedicated to them). Natural logarithms appeared in 1619 in the book of the small-scale mathematics teacher Speidel (a small anonymous table appeared a year earlier in the appendix to the second edition of Napier’s book).

From the kinematic definition of logarithms according to the rule of differentiation of the inverse function we obtain

$$\left( \ln x \right)' = \frac{1}{x}.$$

Further, the above connection between λ and the solution base $S_\lambda(t)$ means that $(a^t)' = \ln a \cdot a^t$, whence

$$\log_a x)' = \frac{1}{x \ln a}.$$

Problem 4. Find the maximum average of numbers of the form $\sqrt[n]{n}$ (n is a natural number).
Note. Examine the extremum of a function

$$f(x) = x^{\frac{1}{x}} = \exp \left( \frac{\ln x}{x} \right)$$

or, equivalently, $g(x) = \ln x/x$.

The function $\ln x$ is convenient for calculating various indicators of processes described by equation (3). Thus, if we take the time $\tau$, during which the value is reduced (or halved), as a characteristic of growth (decrease), then since $e^{\lambda \tau} = 2$, we obtain $\tau = \frac{\ln 2}{\lambda}$ for $\lambda > 0$

and $\tau = -\frac{\ln 2}{\lambda}$ at $\lambda < 0$. In the case of radioactive decay, $\tau$ is called the half-life ($\lambda < 0$).

Problem 5. The time deposit in a savings bank increases by 3% over the year. In how many years will it double?

Finally, we note that due to the fact that the function exponent grows very quickly, the logarithmic function, by direction, grows extremely slowly. It grows slower than any positive power $x$:

$$\lim_{x \to +\infty} \frac{\ln x}{x^a} = 0, \quad a > 0.$$

Trinometric functions

Both paths we discussed in connection with the exponential function (active)

Graphs of some trionometric functions.

simatically and kinematically) are also available for trionometric functions. However, not one of them was the first source. The first is natural to define trionometric functions through the ratio of sides in a triangle or trionometric circle. True, in this case, functions arise that take numeric values, while their argument takes angular, not numeric, values. To move on to numerical argument functions, you need to learn how to change angles. It must be said that although trionometrics has been developing since the 2nd century BC. e., and it was given great importance in connection with astronomical calculations, the current definition of trionometric functions appeared only in the 18th century (largely from Euler). Before this, we made do with all sorts of tables, for example, of chords corresponding to angles. It must not be forgotten that for a long time, for most mathematicians, functions did not go beyond algebraic functions and it did not occur to them that trionometry was somehow connected with analysis.

Let us dwell on the kinematic definition of trionometric functions. Let's consider one of the simplest laws: acceleration (or force) is proportional to distance, or

$$\ddot{x} + \omega^2 x = 0.$$

This equation is called the equation of harmonic oscillations (it describes the movement of the ball outside, the swing of the pendulum around the equilibrium position, etc.). Let us first limit ourselves to the ray $\omega = 1$

$$\ddot{x} + x = 0.$$

We know that the solutions to this equation are $\sin t$ and $\cos t$, but try to get their independent definition

⟦folio 14⟧

Lenin. First of all, we need to obtain an analogue of Galileo’s theorem for (3)—the uniqueness theorem. We must prove that the only solution to (9) with $x(0)=\dot{x}(0)=0$ is $x=0$. Please note that we are faced with a problem of two conditions for $t=0$, which is due to the fact that (9) includes a second arbitrary one. The proof follows from the conservation of the value $E=\frac{1}{2}(\dot{x}^2+x^2)$ (check that $\dot{E}=0$ by virtue of equation (9)).

Let us denote by $s(t)$ the solution (9) with $s(0)=0$, $\dot{s}(0)=1$. Let's explore the properties of this solution (which is actually the same as sin $t$, but we want to derive all the properties from equation (9)).

1) Let $c(t)=\dot{s}(t)$; then $c(t)$ is a solution to (9) with initial conditions $c(0)=1$, $\dot{s}(0)=0$ (checked by unrepresented differentiation: $\ddot{c}=\dot{s}=-\dot{s}=-c$, $\dot{c}=-s$).

2) $s(t)=-s(-t)$, $c(t)=c(-t)$ (it is enough to check that $x(t)=-s(-t)$) is a solution to (9) with the same conditions for $t=0$ as $s(t)$; similarly for $c(t))$.

3) The addition theorems $s(t+t_0)=s(t)c(t_0)+s(t_0)c(t)$, (10) $c(t+t_0)=c(t)c(t_0)-s(t)s(t_0)$ hold. (11) It is enough to verify that the left and right sides for a fixed $t_0$ are solutions to (9) with the same initial ones for $t=0$.

Many new trionometric formulas can be derived from addition theorems (in fact, almost all of them, but we’ll talk about that later). For example, putting $t_0=-t$ in (11), we obtain $c^2(t)+s^2(t)=1$. (12)

From (12) it follows that $|c(t)|\leqslant 1$, $|s(t)|\leqslant 1$.

4) It can be shown that $c(t)$ vanishes for some positive value of the argument.

If this were not the case, then $c(t)$ would be positive at $t>0$, meaning that the function $s(t)$ is monotonically increasing and therefore at $t>0$ takes a positive value. Let us fix some moment of time $t=t_0>0$, and at the same time $s(t_0)=s_0>0$. The equality $c(t)=-s(t)$ means that the rate of decrease of $c(t)$, starting from time $t_0$, is greater than $s_0$, and, therefore, $c(t)$ will vanish no later than after time $c(t_0)/s(t_0)$, which contradicts the assumption of a positive counting problem.

Problem 6*. Let $s(t)$ and $c(t)$ be functions that: 1) determine for all $t$; 2) $s(0)=0$, $c(0)=1$; 3) satisfies the function of equations (10) and (11); 4) continuous. Then $c(t)=\cos \omega t$, $s(t)=\sin \omega t$ for some real number $\omega$.

Note. Take advantage of the fact that a continuous function is completely determined by the properties of the value at points of the form $t=\frac{m}{2^k}t_0$ ($m, k$ are integers, $t_0$ is an arbitrary function of a real number that is not equal to zero).
