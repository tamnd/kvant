---
id: 1983-3-boltyanskiy-metod-iteratsiy-1eff98af
issue: kvant_1983_3
year: 1983
number: "3"
title: Iteration method
authors:
  - Болтянский В. Г.
rubric: novosti-nauki
rubric_sub: Новости науки
page_first: 18
page_last: 23
page_labels: 16, 17, 21
tag: VS5M
lang: en
source: kvant_digital
extraction: vision
content_sha256: d43637ce74e79a0efb03f0c55738e411ae3268c85f98a94f09088ffe2d728e57
prompt_sha256: draft-1
translated_from: content/ru/1983/03/articles/06_boltyanskiy-metod-iteratsiy-1eff98af.md
source_content_sha256: 5177e3d0cc65eba0f725c2be3c2556b4be50c21f6d2d4641f921f1555de70e1f
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 16⟧

Interaction method

Corresponding Member of the Academy of Pedagogical Sciences of the USSR
V. G. BOLTYANSKY

I

Several thousand years ago in Ancient Babylon, a simple method was invented to approximately calculate square roots.

Let us want to calculate $\sqrt{a}$ (where $a > 0$), that is, find the positive root of the equation $x^2 = a$.

This equation is equivalent to the following:

$$x = \frac{a}{x}.$$

(1)

Let us now assume that we have some approximation $x_0$

numbers $\sqrt{a}$. According to (1), $x_0$ must be compared with the number $\frac{a}{x_0}$: after all, if $x_0$ and $\frac{a}{x_0}$ coincide, then $x_0$ is the exact value of $\sqrt{a}$. If, however, $x_0 \neq \sqrt{a}$, then one of the numbers $x_0$, $\frac{a}{x_0}$ is less, and the others are greater than $\sqrt{a}$ (since the product of these numbers is $a$), that is, $\sqrt{a}$ lies between $x_0$ and $\frac{a}{x_0}$. It can be suggested that the arithmetic mean of these numbers

$$x_1 = \frac{1}{2} \left( x_0 + \frac{a}{x_0} \right)$$

is a better approximation of the number $\sqrt{a}$ than the original approximation $x_0$.

This approximation $x_1$ can be improved in the same way, that is, taking the arithmetic mean of the numbers $x_1$ and $\frac{a}{x_1}$

$$x_2 = \frac{1}{2} \left( x_1 + \frac{a}{x_1} \right),$$

then you can take the average approximation

$$x_3 = \frac{1}{2} \left( x_2 + \frac{a}{x_2} \right)$$

and so on.

What is the accuracy of the Vivilon method? To answer this question, we perform the following calculations:

$$x_n - \sqrt{a} = \frac{1}{2} \left( x_{n-1} + \frac{a}{x_{n-1}} \right) - \sqrt{a} =$$

⟦folio 17⟧

$$\frac{1}{2} \left( \sqrt{x_{n-1}} - \sqrt{\frac{a}{x_{n-1}}} \right)^2 = \frac{1}{2x_{n-1}} \left( x_{n-1} - a \right)^2. \quad (2)$$

Equality (2) makes it possible to express the error of the approximation $x_n$ (that is, the number $|x_n - \sqrt{a}|$) in terms of the error of the previous approximation $x_{n-1}$.

Exercise
1. Prove that all approximations of the number $\sqrt{a}$ found using the Babylonian method, except perhaps the initial approximation $x_0 > 0$, are approximations with excess.
2. Prove that for any $x_0 > 0$ the sequence of $(x_n)$ approximations found using the Babylonian method tends to $\sqrt{a}$.
3. To what limit will this sequence tend if some negative number is taken as $x_0$?

To estimate how quickly the numbers $x_0, x_1, x_2, \dots$ approach $\sqrt{a}$, we calculate $\sqrt{19}$ by taking the initial guess $x_0 = 4$. Armed with a microcalculator$^*$), we find

$$x_0 = 4,0000000; \quad x_1 = 4,3750000; \quad x_2 = 4,3589285; \quad x_3 = 4,3588989; \quad x_4 = 4,3588989.$$

As we can see, the fourth approximation does not differ (in calculations with seven decimal places) from the third. It is natural to accept that $\sqrt{19} \approx 4,3588989$.

The reader may argue that there was no need to “fence the garden”: having a microcalculator in hand, one could dial the number 19 and then, by pressing just one button $\sqrt{19}$, immediately get the same result $\sqrt{19} \approx 4,3588989$. However, you will agree that we were interested not so much in the meaning of $\sqrt{19}$ as in the merits of the Babylonian method. They turned out to be quite significant: already after the third repetition of the odotype operation (or, as they say, after the third utepashi) we received the value $\sqrt{19}$ with seven correct signs (see problem 4).

$^*$ For those who do not have a microcalculator at hand, they will have to either count by hand or believe what is written.

3 tasks
4. Let us, using the Babylonian method, calculate successive approximations $x_0 > 0, x_1, x_2, \dots$ of the number $\sqrt{a}$ with $k$ decimal places, that is, we round off the $(k+1)$ digit each time. Prove that if the approximations stabilize at the point $x_n$ (that is, $x_{n+1} = x_n$ to within $10^{-k}$, but $x_n \geq x_{n-1} + 10^{-k}$), then the error of the approximation $\sqrt{a} \approx x_n$ is less than 0.75 $\cdot 10^{-k}$.
5. How many interesting things do you need to do to carry out the calculation using the Babylonian method with $k$ decimal places, to get the number $\sqrt{a}$ with $k$ correct decimal places?

To show the reader the superiority of human intelligence over any machine (in particular, over a microcalculator, which only carries out the will of a person, is his help), we will carry out calculations with fifteen decimal places. For this purpose, we use the found approximation of the number $\sqrt{19}$ for the new initial approximation $x_0$ (that is, we put $x_0 = 4,3588989$) and calculate the next approximation $x_1 = \frac{1}{2} \left( x_0 + \frac{19}{x_0} \right)$ using the Babylonian method. Let's put $\frac{19}{x_0} = x_0 + h$, that is

$$19 = (x_0)^2 + x_0 h. \quad (3)$$

We have

$$(x_0)^2 = (4,3588989)^2 = (4,358 + 8,989 \cdot 10^{-4})^2 = 4,358^2 + 2 \cdot 4,358 \cdot 8,989 \cdot 10^{-4} + 8,989^2 \cdot 10^{-8}.$$

Since our microcalculator accurately calculates the product of two four numbers, we add the right side to calculate exactly. Now, having signed one under the other the three resulting decimal fractions

$$18,992164 \quad 0,0078348124 \quad 0,00000080802121$$

we can (manually, which is not at all difficult) find their sum.

$$(x_0)^2 = 19 - 37,957879 \cdot 10^{-8}$$

and therefore, substituting into (3), we have

$$4,3588989 h = 37,957879 \cdot 10^{-8},$$

from where (using microcalculus-

⟦folio 21⟧

incremental approximations - in this state, another reason is that when solving practical problems, calculators are limited to finding steady-state values ​​using computers that perform calculations with a sufficiently large number of signs. It’s hard to say which is better: spending expensive computer time on checking the accuracy of the solution as one problem or solving a large number of practical problems, “usually” getting a good accuracy of the solution...

Task and

14. Apply the integration method to control (6), where $f(x)=0,9999x+0,0004$. Prove that if the interactional solution process, carried out with four decimal places, stops at the point $x_n$, then the error of the approximation $x^* \approx x_n$ applied is equal to one, that is, not only the decimal places are ambiguous, but also the entire part of the approximation $x_n$. (These messages were used to construct Example 1; in this example $0,9999<f'(x)<1$ at $x>0,12$.)

15. Let the function $f$ satisfy conditions $f(a)>a$, $f(b)<b$ and $|f'(x)|<q<1$ for $x \in [a; b]$. Then equation (6) has a unique root $x^*$ on the interval $[a; b]$. Prove that when solving equation (6), the integration method

$$|x_{n+1}-x_n| \leq |x_1-x_0| \cdot q^n$$

$$|x^*-x_n| \leq |x_1-x_0| \cdot \frac{q^n}{1-q}.$$

16. Apply these estimates to function (5).

17. Solve the integration method of equation $0,6095+0,274 \sin x=x$ (using a microcalculator). After how many iterations does the process stop? How many correct signs does the resulting approximation have?

18. Solve the integration method of equation $\sqrt{1+x}=x$ by taking $x_0=0$. Compare the result obtained with the root obtained by “calculating” the solution to this irrational equation. Prove that the $n$th approximation has the form

$$x_n = \sqrt{1 + \sqrt{1 + \ldots + \sqrt{1}}} \quad (n \text{ единиц}).$$

IV

Problems 8, 10 and 15 indicate the conditions under which the integration method is completed and leads to the goal. What if these conditions are not met?

Let us consider the equation $g(x)=0$, where $g(a)<0$, $g(b)>0$, the function $g$ has a continuous derivative on the interval $[a; b]$ and $g'(x)>0$ at $x \in [a; b]$. Thus, the function $g$ returns on the interval $[a; b]$, and the equation $g(x)=0$ has a single root $x^*$ on this interval. To do this, we can apply the integration method, let us denote by $p_1$ and $p_2$ such positive numbers that $p_1 \leq g'(x) \leq p_2$ on the segment $[a; b]$. Then the tempo is now equation $g(x)=0$ by the equivalent equation $x+a \cdot g(x)=x$, where $a$ is selected so that the function

$$f(x)=x+a \cdot g(x)$$

satisfied the conditions of problem 15. (Check that this will be, for example, for $a=-\frac{2}{p_1+p_2}$, $q=\frac{p_2-p_1}{p_2+p_1}$.) Thus, we replaced the equation $g(x)=0$ with the equivalent equation $f(x)=x$, to which the method of integration is already applicable.

If $g'(x)<0$ at $x \in [a; b]$ the same technique applies. (In this case, $p_1$ and $p_2$ are negative, and $a=-\frac{2}{p_1+p_2} > 0$.)

Example 2. Let's solve the equation integration method

$$x^2-x=\cos x.$$

For $0 \leq x \leq 1$ the left side is non-positive, and the right side is positive; therefore, there are no roots on the segment $[0; 1]$. Rewriting the equation as

$$x^2-x-\cos x=0,$$

we note that the function $g$, which is on the left side, has a derivative $g'(x)=2x-1+\sin x$, which at $x \geq 1$ is positive, that is, $g$ returns to $[1; +\infty]$. Since $g(1)<0$ and $g(2)>0$, on the ray $[1; +\infty]$ there is exactly one root of the equation under consideration, and it is located on the segment $[1, 2]$. Using a microcalculator on the segment $[1, 2; 1, 3]$. The function $g'$ returns $[1; +\infty]$ (since its derivative $g''(x)=2+cos x$ is positive). Therefore, $p_1 \leq g'(x) \leq p_2$ on the segment $[1, 2; 1, 3]$, where $p_1=g'(1,2) \approx 2,332$, $p_2=g'(1,3) \approx 2,564$. Thus, $a=-\frac{2}{p_1+p_2} \approx -0,401$. Taking $a=-0,4$ for simplicity, we obtain the equation (For the ending, see p. 37)
