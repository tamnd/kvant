---
id: 1990-1-bashmakov-o-postulate-bertrana-1dfbbf88
issue: kvant_1990_1
year: 1990
number: "1"
title: About Bertrand's postulate
authors:
  - Башмаков М. И.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 61
page_last: 64
page_labels: 59-62
lang: en
source: kvant_digital
extraction: vision
content_sha256: 2f0ee9761616a76a0e9618077499d4be387cf47ce61372bd16b3c8264c806bc5
prompt_sha256: draft-1
translated_from: content/ru/1990/01/articles/14_bashmakov-o-postulate-bertrana-1dfbbf88.md
source_content_sha256: 3e4c9002bab11faa20f58765f1b3761a683d7ad1b84653ffc8f9b2dbaad184e9
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 59⟧

---
running_head:
folio:
---

About the postulate
Bertrand
Doctor of Physical and Mathematical Sciences
M. BASHMAKOV

Among the 69 works of Pafnuty Lvovich Chebyshev, two works played a particularly important role in the development of number theory. These works: “On Determining the Number of Prime Numbers Not Exceeding a Given Value” and “On Prime Numbers,” written by him in his youth, are devoted to the most difficult question in number theory, the distribution of prime numbers.

The second of them contains inequalities that make it possible to calculate quite accurately the number of prime numbers that do not exceed a given value.

The reader may be wondering, what do logarithms have to do with prime numbers? This is the merit of Chebyshev, that he pointed out how

but to estimate the number of prime numbers in a given segment of the natural series, and, in particular, the following fact has been proven: between x and 2x (where x > 1) there is always at least one prime number. This statement was made by the famous French mathematician Bertrand, who tested it within the existing tables of prime numbers, but was unable to prove it and accepted it as an excuse.

We will trace Chebyshev's main ideas that led him to these estimates, and then propose a series of problems whose solutions will allow readers (fairly familiar with the property of logarithms) to reconstruct Chebyshev's proof of Bertrand's pardon and obtain an inequality for the number of prime numbers not exceeding a given value.

The reader may be wondering, what do logarithms have to do with prime numbers? This is the merit of Chebyshev, that he pointed out how

⟦folio 60⟧

---
running_head:
folio:
---

You can use general functions of analysis - roots, logarithms - when studying problems about integers. If we want to find out whether there is at least one prime number on the interval from $n$ to $2n$, then we can proceed as follows:

1) come up with some function $y=f(x)$ of the real argument $x$, which would not change its value while $x$ runs through the segment between neighboring prime numbers, and would take on more value when passing over a prime number;

2) prove inequalities for the relative function $f$, which would help to accurately estimate the rate of its growth.

For a function chosen in this way, the difference $f(2n)-f(n)$ will be a positive number if and only if the function $f$ returns when moving from $n$ to $2n$, that is, if there is at least one prime number between $n$ and $2n$.

The first condition is easy to satisfy. We can consider the following function: let us denote by $\pi(x)$ the number of prime numbers not exceeding $x$.

For example, $\pi(1)=0$ (one is not considered a prime number), $\pi(3)=2$, $\pi(9)=4$, $\pi(9,5)=4$, $\pi(10,9)=4$, $\pi(11)=5$, etc.

Of course, if we could prove that

$$\pi(2x)-\pi(x)>0,$$

we would prove and Bertrand will act, since

$$\pi(2x)-\pi(x)$$

precisely denotes the number of prime numbers contained between $x$ and $2x$. However, it is not easy to give exact estimates for $\pi(x)$, and to solve this problem Chebyshev proposed to consider a function that, when passed over, would return a prime number not by one, like $\pi(x)$, but more erroneously. He investigated the function

$$\theta(x)=\log 2+\log 3+\log 5+\ldots=\sum_{p\leqslant x}\log p$$

($\theta(x)=0$ at $x<2$)

- the sum of the logarithms of all prime numbers, not exceeding the previous one, Bertrand’s procedure is equivalent to the following inequality:

$$\theta(2x)-\theta(x)>0.$$

(1)

To estimate the function $\theta(x)$ and prove (1), Chebyshev used the auxiliary function $T(x)$:

$$T(x)=\log 2+\log 3+\ldots=\sum_{n\leqslant x}\log n.$$

The function $T(x)$ is the logarithm of the product of all integers, not exceeding them. Chebyshev showed that the function $\theta(x)$ and $T(x)$ are related by the following remarkable identity:

$$T(x)=\theta(x)+\theta(\sqrt{x})+\theta(\sqrt[3]{x})+\ldots$$

$$+\theta\left(\frac{x}{2}\right)+\theta\left(\sqrt{\frac{x}{2}}\right)+\theta\left(\sqrt[3]{\frac{x}{2}}\right)+\ldots$$

$$+\theta\left(\frac{x}{3}\right)+\theta\left(\sqrt{\frac{x}{3}}\right)+\theta\left(\sqrt[3]{\frac{x}{3}}\right)+\ldots$$

(2)

where the sum of the object is when the argument $\sqrt[k]{x/m}$ becomes less than two and the value $\theta(\sqrt[k]{x/m})$ becomes zero. The function $T$ has been known since the time of Euler, and long before Chebyshev, inequalities were proven that make it possible to fairly accurately estimate the order of growth of $T$.

From these inequalities, Chebyshev obtains inequalities for $\theta(x)$ of the form

$$Ax+v_1(x)<\theta(x)<\frac{6}{5}Ax+v_2(x),$$

(3)

where $A$ is some constant, and the additional terms $v_1(x)$ and $v_2(x)$ for large $x$ are significantly less than $x$. This is already enough to prove the inequality $\theta(2x)-\theta(x)>0$ for $x$ greater than some $x_0$ (in Chebyshev $x_0=160$). For $x$, smaller $x_0$, fair

*) Here and everywhere below, logarithms are taken to the base $e$ - these are the so-called natural logarithms.

⟦folio 61⟧

---
running_head:
folio:
---

Further development of human ideas led to the following result: for $x \geq 48$ $\theta\left(\frac{9}{8}x\right) - \theta(x) > 0$, that is, starting from the indicated place, between $x$ and $\frac{9}{8}x$ there is always at least one prime number.

You can follow Chebyshev's argument in more detail by solving problems 1-5 below.

In order to express $T(x)$ in terms of $\theta(x)$, it is convenient to introduce another auxiliary function. Let $p^{a_p}$ be the highest degree of $p$ not exceeding $x$. Let's define the function $\psi$ like this:

$$\psi(x) = a_2 \log 2 + a_3 \log 3 + a_5 \log 5 + \dots = \sum_{p \leq x} a_p \log p.$$

It is clear that $\psi(x)$ is the logarithm of the least common multiple of all integers, not exceeding $\psi$. Problem 1. Prove that

$$T(x) = \psi(x) + \psi\left(\frac{x}{2}\right) + \psi\left(\frac{x}{3}\right) + \dots$$

Now we need to connect the function $\psi$ and $\theta$.

Problem 2. Prove that

$$\psi(x) = \theta(x) + \theta\left(\sqrt{x}\right) + \theta\left(\sqrt[3]{x}\right) + \theta\left(\sqrt[4]{x}\right) + \dots$$

Having solved problems 1 and 2, you will also establish the real number $e$, which for all natural numbers $n$

$$\left(\frac{n+1}{e}\right)^n < n! < n\left(\frac{n}{e}\right)^n$$

(where $n! = 1 \cdot 2 \cdot 3 \cdot \dots \cdot n$).

To solve this problem it is useful to show that each of the numbers

$$a_n = \left(\frac{n+1}{n}\right)^n$$

variable of each number

$$b_n = \left(\frac{n+1}{n}\right)^{n+1};$$

it follows that there is a number $e$ that is greater than all $a_n$ and less than all $b_n$. This is the number we are looking for (some of its properties were discussed on the last page of our magazine No. 1, 1971).

Having solved this problem, you will also obtain inequalities for $T(x)$:

$$(x-1)(\log(x-1) < T(x) < (x+1)\log x-x).$$

Chebyshev himself used more precise inequalities.

From the estimate for $T(x)$, Chebyshev obtains estimates for $\psi(x)$ and then for $\theta(x)$.

To express $\psi$ in terms of $T$, Chebyshev replaces the following. Let's consider the amount

$$S = T(x) - T\left(\frac{x}{2}\right) - T\left(\frac{x}{3}\right) - T\left(\frac{x}{5}\right) + T\left(\frac{x}{30}\right).$$

Let’s use the result of Problem 1 and reduce this sum to the following form:

$$S = A_1 \psi(x) + A_2 \psi\left(\frac{x}{2}\right) + A_3 \psi\left(\frac{x}{3}\right) + \dots$$

Problem 4. Check that the coefficients $A_1, A_2, A_3$, ... change with a period of 30 and that for the first thirty values ​​$n$ the coefficients $A_n$ form the following sequence:

1, 0, 0, 0, 0, -1, 1, 0, 0, -1, 1, -1, 1, 0, -1, 0, 1, -1, 1, -1, 0, 0, 1, -1, 0, 0, 0, 0, 1, -1, 1.

From this we can see that the sum $S$ is written as an alternating series $S = \psi(x) - \psi\left(\frac{x}{6}\right) + \psi\left(\frac{x}{7}\right) - \psi\left(\frac{x}{10}\right) + \psi\left(\frac{x}{11}\right) - \dots$.

Since $\psi$ is a non-decreasing function,

$$S = \psi(x) - \left(\psi\left(\frac{x}{6}\right) - \psi\left(\frac{x}{7}\right)\right) - \left(\psi\left(\frac{x}{10}\right) - \psi\left(\frac{x}{11}\right)\right) \dots \leqslant \psi(x).$$

Analogino

$$S = \psi(x) - \psi\left(\frac{x}{6}\right) + \left(\psi\left(\frac{x}{7}\right)\right) - \psi\left(\frac{x}{10}\right) + \dots \geqslant \psi(x) - \psi\left(\frac{x}{6}\right).$$

From (2) we immediately obtain an inequality for $\psi$, which estimates its size, since we know the inequalities for $T$ and obtained an estimate for $\psi$ through $S$, i.e., a combination of values ​​$T$. This estimate will have the following form: $\psi(x) \geqslant A_1(x) + \omega_1(x)$, where $\omega_1$ grows more slowly than $x$, i.e.

$$\lim_{x \to \infty} \frac{\omega_1(x)}{x} = 0.$$

To get an estimate from above, you need to get rid of $\psi\left(\frac{x}{6}\right)$. Applying inequality (6) to $\frac{x}{6}, \frac{x}{6^2}, \frac{x}{6^3}$, etc. and adding, we find an inequality for $\psi(x)$ of type $\psi(x) \leqslant A_2x + w_2(x)$, where $w_2$ grows more slowly than $x$.

Problem 5. Prove that

$$\psi(x) - 2\psi\left(\sqrt{x}\right) \leqslant \theta(x) \leqslant \psi\left(\sqrt{x}\right).$$

From this we already obtain the necessary estimates (3).

Chebyshev’s results not only implied that Bertrand’s actions were correct, but, more importantly, they yielded inequalities that allow a good estimate of the function $\pi(x)$:

$$c_1 \frac{x}{\log x} < \pi(x) < c_2 \frac{x}{\log x},$$

where $c_1$ and $c_2$ are non-positive.

⟦folio 62⟧

---
running_head:
folio:
---

constants *). You can prove such inequalities by solving the following problem.

Problem 6. Prove that
$$\frac{\psi(x)}{\log x} < \pi(x) < \frac{\psi(x) + \theta(x)}{\log x}.$$

*) The logarithm here can be to any base $a$ greater than one; only the values ​​of the constants $c_1$ and $c_2$ depend on $a$, since $\log_b x$ is obtained from $\log_a x$ by multiplying by the constant number $\log_a b$. It is more natural to use the natural logarithm, because it is the function $x/\log_e x$ that is equivalent to $\pi(x)$ for large $x$, i.e. $$\lim_{x \to \infty} \frac{\pi(x)}{x/\log_e x} = 1.$$ This was proven much later, and from the work of Chebyshev himself it only followed that the ratio of $\pi(x)$ to $x/\log_e x$ is between 0.921 and 1.106 and that if the limit at $x \to \infty$ exists, then it is equal to one.

Waves on the water and “Overseas Guests” by N. Roerich

(See beginning on p. 24)

What about the angle $\alpha$? All those interviewed agreed that it lies somewhere in the range of $90^\circ < 2\alpha < 180^\circ$ (the ship in the picture is quite typical). Thus,
$$\frac{\sqrt{2}}{2} = \sin 45^\circ < \sin \alpha < \sin 90^\circ = 1.$$ (7)

Now we have everything to make estimates of the ship's speed and surface waves.

Results

Substituting the values ​​$h$, $\lambda$ and $\sin \alpha$ from (5), (6), (7) into formulas (1) and (2), we obtain
$$v \geq \sqrt{\frac{2 \cdot 9,8 \text{ m/c}^2 \cdot 0,26 \text{ m}}{1 \div \sqrt{2}/2}} \approx 5,1 \div 7,25 \text{ m}^2/\text{c}^2 \approx 2,25 \div 2,7 \text{ m/c},$$ (8)

$$u = \sqrt{\frac{9,8 \text{ m/c}^2 \cdot 0,34 \text{ m}}{2\pi}} \approx 0,7 \text{ m/c}.$$ (9)

Now we are surprised to notice that correspondences (8) and (9) are incompatible with inequality (4). Indeed, judging by the height of the bow wave, the ship floats at a speed $v$ no different than 2.25 m/s, and if we focus on the circular surface of the waves, which are almost concentric in the picture, the speed of the ship should be much less than the speed of these waves $u = 0,7 \text{ m/c}$, which is already less than $v$.

With a certain appearance, you will find many similar physical inaccuracies in other works of art (apparently, this is due to the fact that he has his own set of rules and laws). Then you can not only put them down and get aesthetic satisfaction, but also talk with your little brother about the laws of physics, using very attractive illustrations.
