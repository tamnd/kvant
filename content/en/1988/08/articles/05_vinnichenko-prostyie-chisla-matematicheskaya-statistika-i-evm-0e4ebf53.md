---
id: 1988-8-vinnichenko-prostyie-chisla-matematicheskaya-statistika-i-evm-0e4ebf53
issue: kvant_1988_8
year: 1988
number: "8"
title: Prime numbers, mathematical statistics and... Computers
authors:
  - Винниченко А. П.
rubric: raznoe
page_first: 21
page_last: 24
page_labels: 19-22
tag: S34Z
lang: en
source: kvant_digital
extraction: vision
content_sha256: 998f3b6fb499d040e84c11e22d3ec8e3958d1b2de2c6985de1d8bca125f16e76
prompt_sha256: draft-1
translated_from: content/ru/1988/08/articles/05_vinnichenko-prostyie-chisla-matematicheskaya-statistika-i-evm-0e4ebf53.md
source_content_sha256: 1a9c2154c72be15896f12359d630a592613326660ff0e75f74bf11e6cdc7e84d
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 19⟧

PRIME NUMBERS
MATHEMATICAL
STATISTICS AND... COMPUTER

Candidate of Physical and Mathematical Sciences
A. P. VINNICHENKO

Editorial. In recent years, with the growth in the power and availability of computers, experimentation, which until recently was the almost undivided domain of physics, chemistry and other natural sciences, has begun to play an increasing role in the work of mathematics. Mathematicians were able to identify new hypotheses based on the results of fast computer processing of huge arrays. Sometimes patterns emerge that harm individuals could have been discovered in the “good old days.”
In the following note you will not find a single theorem or proof. Here we talk about an experiment on prime numbers, allowing us to formulate an interesting proposal about their distribution. Perhaps one of our readers will be able to prove or disprove it.
Even the ancient Greeks saw among the many positive integers “indivisible atoms”, i.e. numbers that cannot be decomposed into smaller factors, and called them “simple”. A prime number is divisible only by one and itself, and all other numbers are obtained from these elements of the kirichki of the world

POISSON

2*

19

⟦folio 20⟧

numbers by multiplication. The beginning of a series of prime numbers is 2, 3, 5, 7, but there is no end to it - the simplest number does not exist. We will consider the only even prime number 2 to be an “error of nature” and consider the series starting from 3. Let us subject this series to the procedure of difference analysis*) - we will be the differences of two neighboring terms:

$$\begin{align*}
3, & 5, 7, 11, 13, 17, 19, 23, 29, 31, 37 \\
2 & 2 4 2 4 2 4 2 4 2 6
\end{align*}$$

The differences are repeated - there are many twos, there are fours, and sixes have also appeared. It’s as if points are rolling out on a dice: two, two, four, two again... It’s a heretical idea to look at this strictly deterministic series as the results of measurements of some random variable and try to process them using the method of mathematical statistics.

Let us take prime numbers not exceeding $N$ for processing; in example (1) $N=40$. First of all, let’s write down in ascending order all the observed values ​​$x_1=2, x_2=4, \dots$ of our “random variable” (in example (1) the number of these values ​​is $n=3$), and below it - the frequency $\omega_1, \omega_2, \dots$ with which they appear (i.e., the ratio of the number of occurrence $x_i$ to the total number of the observed one, which for us is 10):

$$\begin{align*}
1 & 4 & 9 & 16 & 25 & 36 \\
3 & 5 & 7 & 9 & 11 & \dots \\
2 & 2 & 2 & 2 & \dots ;
\end{align*}$$

respectively, $(x^2)^{n/2}=\text{const.}$

Next, we will compile a table of “accumulated frequencies” $v_i=\omega_1+\omega_2+\dots+\omega_i$, i.e., under each value $x_i$ we will write the sum of the frequencies of all values ​​not exceeding $x_i$:

$$\begin{align*}
x_i & 2 & 4 & 6 \\
\omega_i & 0,5 & 0,3 & 0,2
\end{align*}$$

Let us plot the results of these calculations as a graph of the step function $F_N(x)$ (Fig. 1), called the empirical distribution function: $F_N(x)$ is equal to the sum of $\omega_i$ over all $i$ such that $x_i \leqslant x$. Our goal is to compare the graphs of $F_N(x)$ for different $N$ and try to catch some pattern in their behavior for $N \to \infty$. True, if you take on this without appropriate preparation, nothing good will come of it. The fact is that the further away, the more common prime numbers are and the larger, on average, the gaps between them will be. Therefore, the graphs $F_N$ with an increase in $N$ will spread to the right. To compensate for this melting, we apply to them a procedure familiar to us from detective novels. When merging photographs with cellulose ones, whether they depict the same whole, forensic scientists determine or reduce them so that the distances between the frames in the common portraits become the same, and then combine them frame by frame. We will do something similar with empirical distribution functions.

⟦folio 21⟧

Let us calculate for each $N$ the arithmetic mean $\bar{x}$ of all observed values ​​$x_i$, called the mean value. It's easy to see that $\bar{x} = \sum_{i=1}^{n} x_i \omega_i$.

This value characterizes the shift of the horizontal distribution function. The second quantity we need is

$$\sigma_x = \sqrt{\sum_{i=1}^{n} (x_i - \bar{x})^2 \omega_i}$$

- called the standard deviation. It serves as a measure of the dispersion of observed values ​​relative to the mean value $\bar{x}$—the smaller $\sigma_x$, the more closely spaced the values ​​$x_i$ are. In our detective analogue, the size $\sigma_x$ corresponds to the size of the photographer. Let us give the values ​​of $\bar{x}$ and $\sigma_x$ for different $N$.

| $N$ | 40 | $10^2$ | $10^3$ | $10^4$ | $10^5$ | $10^6$ |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| $\bar{x}$ | 3,40 | 4,10 | 5,98 | 8,12 | 10,42 | 12,73 |
| $\sigma_x$ | 1,56 | 1,84 | 3,54 | 5,86 | 8,02 | 10,28 |

As one would expect, both of these characteristics increase with increasing $N$, which indicates that the $F_N$ graphs are spreading. To prevent positioning, we move each graph $x$ to the left and create $\sigma_x$ times to the ordinat axis. To do this, we replace the values ​​$x_i$ with new values ​​$y_i = (x_i - x)/\sigma_x$ and recalculate the table of accumulated frequencies:

| $y_i$ | $-0,90$ | $0,38$ | $1,67$ |
| :--- | :--- | :--- | :--- |
| $v_i$ | 0,50 | 0,80 | 1 |

Using this table, we will draw a graph of the distribution function $\bar{F}_N(y)$ of the value $y_i$ (Fig. 2). It is easy to see that the average value and standard deviation of the value $y_i$ for all $N$ will be equal to 0 and 1. We will compare these graphs $\bar{F}_N$. Of course, for large $N$ this work must be entrusted to a computer. In 20 minutes of work, we achieved 300 thousand operations per second, highlighting the graphs shown in figure 3 (for $N = 10^3$, $10^4$, $10^5$ and $10^6$). Does it really look like these step graphs are approaching the flat graph drawn in black? This is a graph of the so-called exponential distribution

$$F(y) = \begin{cases} 1 - e^{-y-1} & \text{при } y \geq -1, \\ 0 & \text{при } y < -1 \end{cases}$$

with zero mean and unit standard deviation. The calculation carried out on a computer confirms our critical value. Whether it is true that at $N \to \infty$ the graphs of $\bar{F}_N(y)$ tend to $F(y)$ is unknown. For now this is just a hypothesis. However, the hypothesis is confirmed for the set of 78,497 first prime numbers. And this huge job was completed in just 20 minutes!

It is interesting to note that the same distribution is also given by the intervals between neighboring signals in a Poisson flow (see the end of the article “How the Poisson distribution arises”). We can show this by recalling that, as shown in this article, the probability $P_0(t)$ that no signal will arrive during time $t$ is $e^{-\lambda t}$. Consequently, the probability that the next signal

⟦folio 22⟧

Starting from an arbitrary moment $t_0$, it will appear until the moment $t_0 + t$, equal to $1 - e^{-\lambda t}$. After the appropriate shift and slope, the distribution function given by equality (2) is obtained.

You can try to discover the property of distances between neighboring prime numbers using some of their known properties. For example, there is an estimate for the quantity $N$, first proven by the French mathematician J. Hadamard and the Belgian mathematician S.-J. Vallée Poussin in 1896: $\pi(N) \approx N/\ln N$. Let's consider the so-called quasi-prime numbers: the roots of the equations $n_i/\ln n_i = i + 3, i = 1, 2, 3...$, the number of which on the interval from 1 to $N$ is very convenient, is also approximately equal to $N/\ln N$. Let's write out $n_1, n_2, ..., n_6$ and apply difference analysis:

$$8,61 \quad 12,71 \quad 17,00 \quad 21,47 \quad 26,10 \quad 30,87 \quad 4,10 \quad 4,29 \quad 4,47 \quad 4,63 \quad 4,77 \quad 0,19 \quad 0,18 \quad 0,16 \quad 0,14$$

It can be seen that the distances between neighboring quasi-primes $n_i$ and $n_{i+1}$ return, but more and more slowly as $i$ increases. Try, based on this observation, to prove that for quasi-prime numbers the empirical distribution function is downward convex and therefore cannot coincide with the exponential distribution function. Therefore, our hypothesis cannot be justified simply by estimating the number $\pi(N)$. If it is true, then its proof must use some deeper facts.

Orders accepted...

(For the beginning, see p. 18)

Information, programming

52. Samarsky A. A., Gulin A. V. Numerical methods. 1 rub. 90 k.

Modern numerical methods for solving applied problems, designed for the use of high-speed computers, are presented. The theory of interpolation, quadratic formulas, approximation of functions, numerical methods of algebra, etc. are considered.

90. Introduce the Corvette personal computer. 95 k.

Contains a description of one of the first personal computers in our country, the Corvette. The features of computer architecture, rules of use, and software are considered.

128. Abramov S. A., Zima E. V. Fundamentals of computer science. 1 rub.

Contains a systematic presentation of the basic concepts and methods of computer science (computing technology, programming, numerical methods, sorting and searching). The basics of programming are presented in Pascal.

129. Arsak J. Programming and voice loco. Per. from fr. 90 k.

Methods for programming various meaningful games and voice locks with numbers, geometric functions, etc. are considered.

154. Novoseltsev V.N. Organism in the world of technology: cybernetic aspect. 70 k.

It tells how today's cybernetics allows us in many ways to give a complete picture of life processes in the body.

155. Dyakovov V.P. Handbook of calculations on microcalculators. 1 rub. 20 k.

Contains a description of modern reporting and foreign microcalculators, languages ​​and basic programming.

156. Pilshikov V. N. Collection of controls on the Pascal language. 40 k.

The collection is based on the manual “Exercises in the Pascal Language”, which we use when teaching programming to students at the Faculty of Computational Mathematics and Cybernetics at Moscow University.

159. Nikolov R., Sendova E. Beginnings of informatics: Transl. from Bulgarian 60 k.

The experience of teaching children to work with personal computers is reflected. You will get the basics of learning with a computer in dialogue mode in the LOGO language.
