---
id: 1978-2-semenov-rukopis-naydennaya-v-saragose-d80ec67a
issue: kvant_1978_2
year: 1978
number: "2"
title: Manuscript found in Zaragoza
authors:
  - Семёнов С.
rubric: osnovnye-stati
page_first: 12
page_last: 15
page_labels: 10-13
tag: UOMA
lang: en
source: kvant_digital
extraction: vision
content_sha256: a51a4de38a0391a75e61fdcbfb5ccb0d873b461f5e4c03145d67c808b77d0163
prompt_sha256: draft-1
translated_from: content/ru/1978/02/articles/05_semenov-rukopis-naydennaya-v-saragose-d80ec67a.md
source_content_sha256: 1c8c00fe45870f97fccaf1e35be9bb942fa6ef6e7bbd4baff4af0a73c235df5e
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 10⟧

Manual found in Zaragoza

Quite recently, during excavations in the Spanish city of Zaragoza, an ancient library was archaeologically discovered that belonged to the once famous trading family of Suarskoe. Among other books there was a family history. We will now introduce the reader to one of the fragments of this manuscript, since it contains the formulation of an interesting and modern mathematical problem. So...

“Having reached the age when a prudent person should take care of the successor and continuator of the business, Suarrez decided to take in his sons, Alonso and Lopez, to find out how capable they were of replacing him. The sons did not appear, and Suarrez addressed them with the following words: “Children! I intend to contribute 100,000 reais on behalf of each of you for a period of ten years to some reliable enterprise. This business will bring everyone a 20% increase every day, and you can manage only this amount, but not the capital itself. You can add part of this money to your capital at the end of the year, and spend the rest as you please. Your goal will be to spend as much money as possible on your needs in 10 years, or it is worth making money only to spend it later. Tell me, how will you manage your income?”

The first response was from the eldest son Alonso, known far beyond the city for his frivolity and extravagance: “Father! I would spend all my income at once because I don't

⟦folio 11⟧

I see no point in worrying about increasing capital that doesn’t belong to me!”

Lopez, on the contrary, was a modest and virtuous youth. He answered his father this way: “For 9 years I would make do with only what we are doing at home now, father, and add my income to my capital. In the tenth year I will spend 20% on preparations. I hope that this will be a significant amount, since the capital, thanks to my investments, will increase significantly.”

Hearing the answers of his sons, the venerable merchant frowned, and it was clear that he was dissatisfied with the answers. When his sons began to ask him for advice, he said: “Extreme wastefulness, my children, is as unreasonable as extreme frugality, but the correct solution is found between these extremes. Taking this into account, I would add half of the income to the capital, taking care of its increase, and spend half on my needs. You, as I found out, are not yet intelligent enough and, alas, are not capable of replacing me in business.” The next day, Suarez ordered his sons to get ready for the journey through the Pyrenees, to distant Paris, and study mathematics and other sciences from famous Parisian scientists...”

Here we will translate the quote from the “historical document”, since the problem we are interested in has already been formulated and even three different options for its solution have been proposed. First, let's compare the effectiveness of these solutions. It is easy to calculate (preferably they can do this on their own, and the rest can use formulas (2) and (3) of this article) the amount of money spent by Oto (S), Alonso (A) and Lopez (L) over 10 years. Namely,

$$S = \left( \left( 1 + \frac{1}{10} \right)^{10} - 1 \right) 10^5 \approx 159374 \text{ реал},$$
$$A = 2 \cdot 10^5 = 200000 \text{ реал}$$
$$L = \frac{1}{6} \left( \left( 1 + \frac{1}{5} \right)^5 \right)^2 10^5 \approx 103169 \text{ реал}.$$

The comparison results are paradoxical. The thrifty Lopez, who turned out to be, proposed the worst solution, and the frivolous Alonso disposed of his income better than his prudent and experienced parent! Make sure seemingly plausible arguments turn out to be deceptive. Perhaps our best solution is different from all three proposed? Let's try to figure this out.

So, let us denote the amount of capital (after the absence of interest and, possibly, an additional contribution) at the end of the $k$-th year (counting from the moment of the first deposit) through $x_k$, $k=0, \dots, N$. In our problem, $N=10$, and the value of the initial contribution is $x_0=10^5$. In the $(k+1)$ year the value $ax_k$ will approach (we have $a=\frac{1}{5}$), and if the $\lambda_k$ share of this value was added to the capital at the end of the $(k+1)$ year, then its increase for the year is $x_{k+1}-x_k=\lambda_k ax_k$ ($k=0, \dots, N$). (1) The remaining parts of the approximation $(1-\lambda_k)ax_k$ will be spent.

Our ability to influence the process of capital growth or, in other words, control this process, is the ability to choose a vector - an ordered set of numbers $\bar{\lambda} = (\lambda_0, \dots, \lambda_{N-1})$, $0 \leqslant \lambda_i \leqslant 1$. Such vectors will be further called control $\bar{\lambda}$ and will completely determine the value of the objective function $F$ - the total amount of money spent over $N$ years:

$$F(\bar{\lambda}) = (1-\lambda_0)ax_0 + (1-\lambda_1)ax_1 + \dots + (1-\lambda_{N-1})ax_{N-1}.$$ (2) The problem is to find the best, optimal control $\lambda^{\text{опт}}$, i.e. such a control $\lambda^{\text{опт}}$ such that for any other control $\bar{\lambda}$

$$F(\bar{\lambda}) \leqslant F(\bar{\lambda}^{\text{опт}}).$$

Let us remember that the optimal control was proposed by Alonso $(0, \dots, 0)$, Lopez - $(1, \dots, 1, 0)$, and the venerable merchant - $\left(\frac{1}{2}, \dots, \frac{1}{2}\right)$.

Perhaps the reader has an external impression that such treasures of management are needed only by those who receive a rich inheritance? Of course not! Here's another example. The farm breeds Blackburg Lips. We will denote the number of farms by $x_k$, where $k=0, 1, \dots, N$ is the year number (we are interested in the fate of the farm in the coming

⟦folio 12⟧

N years). The offspring at the beginning of the $(k+1)$ year is $ax_k$ (where $a > 0$ is a known number), and the $\lambda_k$ share of this offspring remains on the farm, and the rest is sent to harvest forest. Thus, relation (1) is valid, and the number of skins obtained in $N$ years is expressed by formula (2). As you can see, here too we have a controlled process, the state of which at each moment $k = 0, 1, \dots, N$ is characterized by the value $x_k$, and we can influence the course of this process by choosing the control action $\lambda_k$ from the “control area”, which in this case is the segment [0, 1]. The task is to find a control in which the set goal would be achieved in the best possible way - the objective function $F$ would reach its maximum. Similar problems of “optimal control” of processes occurring in “discrete time” arise when studying production problems in factories (in this case $k$ is the number of a completed production cycle or a planned month, etc.), when describing the operation of several chemical reactors connected in series ($k$ is the reactor number), etc.

The branch of mathematics in which methods for solving such problems are developed is called optimal control theory. Over the past two decades, this theory has transformed into a powerful modern mathematical science, impressing with both deep theoretical results and efficiency in solving applied problems of process control. The development of this direction of mathematical thought is associated with the names of such famous mathematicians as L. S. Pontryagin, R. Bellman, V. G. Boltyansky, R. V. Gamkrelidze, E. F. Mishenko, N. N. Krasovsky. We will not, however, present the general theory of optimal control created by these authors, but will study our problem using elementary mathematics.

Let us transform formula (1) to the form $x_{k+1} = (1 + a\lambda_k)x_k$, $(k = 0, \dots, N-1)$. (3)

Variables of equality (3)term by term for $k = 0, \dots, n-1$, we obtain in explicit form the dependence of $x_n$ on control $\bar{\lambda} = (\lambda_0, \dots, \lambda_{N-1})$
$$x_n = (1 + a\lambda_0)(1 + a\lambda_1) \dots (1 + a\lambda_{n-1})x_0.$$ (4)

Proposition I. Let $\bar{\lambda} = (\lambda_0, \dots, \lambda_{i+1}, \dots, \lambda_{N-1})$ be some control, $0 \leq i \leq N-2$, $\lambda_i < \lambda_{i+1}$, and let control $\bar{\lambda}$ differ from $\bar{\lambda}$ by a permutation of the numbers $\lambda_i$ and $\lambda_{i+1}$. Then $F(\bar{\lambda}) > F(\bar{\lambda})$.

To prove it, it is enough to trace how the terms of the sum (2) are transformed when the numbers $\lambda_i$ and $\lambda_{i+1}$ are transferred. By virtue of formula (4), the terms $(1 - \lambda_k)ax_k$ under $k \leq i-1$ do not depend at all on $\lambda_i$ and $\lambda_{i+1}$ and are very expensive and do not change with such a rearrangement. The terms $(1 - \lambda_k)ax_k$ with $k > i+1$ due to formula (4) have the form:
$$(1 - \lambda_k)ax_0(1 + a\lambda_0) \dots (1 + a\lambda_{i+1}) \times (1 + a\lambda_{i+1}) \dots (1 + a\lambda_{k-1}),$$
and, therefore, also do not change when transmitting the numbers $\lambda_i$ and $\lambda_{i+1}$. Thus, we only have to consider the sum of the remaining terms:
$$(1 - \lambda_i)ax_i + (1 - \lambda_{i+1})ax_{i+1} = (1 - \lambda_i)ax_i + (1 - \lambda_{i+1})(1 + a\lambda_i)ax_i = ax_i[(2 - \lambda_i - \lambda_{i+1}) - a\lambda_i\lambda_{i+1}] + a\lambda_i.$$

The value of $x_i > 0$ is independent of $\lambda_i$ and $\lambda_{i+1}$, the expression in parentheses does not change when passed, and the second term in square brackets is returned. Therefore, $F(\bar{\lambda}) > F(\bar{\lambda})$.

Proposition II. Let $\bar{\mu}$ be some control. Then for any $n = 0, \dots, N$ there is a maximal control $\bar{\mu}^{(n)} = (\mu_0^{(n)}, \dots, \mu_N^{(n)})$ such that $1^\circ \mu_n^{(i)}$ is 0 or 1 for any $i < n$, $2^\circ F(\bar{\mu}^{(n)}) \geqslant F(\bar{\mu})$.

Let's prove this statement using the method of mathematical induction. For $n = 0$ this statement is obvious, since we can put $\bar{\mu}^{(0)} = \bar{\mu}$ and the statement $1^\circ$ and $2^\circ$ will be satisfied automatically.

Suppose that for $n = k$ the control exception exists $\bar{\mu}^{(k)} = (\mu_0^{(k)}, \dots, \mu_N^{(k)})$. Let us consider the function $y(t)$ of one variable $t$, whose definite is the segment [0, 1], given by the formula
$$y(t) = F(\mu_0^{(k)}, \dots, \mu_{k-1}^{(k)}, t, \mu_{k+1}^{(k)}, \dots, \mu_N^{(k)}).$$
From formulas (2) and (4) it is immediately clear that $y(t)$ is a linear function of $t$, i.e.
$$y(t) = At + B$$
for some $A$ and $B$. Note that a linear function on the interval [0, 1] reaches a maximum at zero if $A < 0$, at one if $A > 0$, and at $A = 0$ it is a constant function. By-

⟦folio 13⟧

put it down now
$$\mu_k^{(k+1)} = \begin{cases} 0, & A \leqslant 0, \\ 1, & A > 0, \end{cases}$$

and $\mu_k^{(k+1)} = \mu_i^{(k)}$ at $i \neq k$, $0 \leqslant i \leqslant (N-1)$. Control $\overline{\mu}^{(k+1)}$ satisfies conditions $1^\circ$ and $2^\circ$ for $n = k + 1$. Indeed, the numbers $\mu_k^{(k+1)}$ with $i < k$ are zeros or ones by the assumption of indication, and $\mu_k^{(k+1)}$ is zero or one by definition. Further, since by definition of the number $\mu_k^{(k+1)}$ for any $t$, $0 \leqslant t \leqslant 1$
$$y(t) \leqslant y(\mu_k^{(k+1)}),$$
then $F(\overline{\mu}^{(k+1)}) \geqslant F(\overline{\mu}^{(k)})$. By the indicative assumption $F(\overline{\mu}^{(k)}) \geqslant F(\overline{\mu})$, and therefore $F(\overline{\mu}^{(k+1)}) \geqslant F(\overline{\mu})$. The proof is complete.

Let us now highlight among all the controls some special, simplest type. Namely, consider a control $\overline{\theta}^{(m)}$ such that
$$\theta_i^{(m)} = \begin{cases} 1 & \text{при } i < m, \\ 0 & \text{при } i \geqslant m, \end{cases}$$
for some $m$, $0 \leqslant m \leqslant N$. A set of controls of this type—we will further call them stepwise—contains a $(N+1)$ element. It turns out that in our problem it is enough to look for optimal control among step ones.

Theorem. For any control $\overline{\lambda}$ there is a control $\overline{\omega}$ such that $F(\overline{\omega}) \geqslant F(\overline{\lambda})$.

Indeed, by Proposition II, there exists a control $\overline{\mu} = (\mu_0, \dots, \mu_{N-1})$ such that $\mu_i$ is zero or one for any $i = 0, \dots, N-1$ and $F(\overline{\mu}) \geqslant F(\overline{\lambda})$. Further, we note that if there is a 0 among the numbers $\mu_0, \dots, \mu_{N-1}$, then by swapping it with the number following it, we will not reduce the value of the objective function $F$ by virtue of Proposition I. By such permutations, all zeros can be moved to the end of the set defining the control, i.e., go to some step control $\overline{\omega}$, and the inequalities will be satisfied $F(\overline{\omega}) \geqslant F(\overline{\mu}) \geqslant F(\overline{\lambda})$. The theorem has been proven.

Let us now choose the optimal one among the step controls. By virtue of formulas (2) and (4)
$$F(\overline{\theta}^{(m)}) = (N - m)a(1 + a)^m x_0.$$
Magnitude
$$C_m = \frac{F(\overline{\theta}^{(m+1)})}{F(\overline{\theta}^{(m)})} = (1 + a)\left(1 - \frac{1}{N - m}\right)$$
decreases when $m$ occurs. Let us denote by $M$ the first integer greater than or equal to zero and $N-1 - \frac{1}{a}$.
Then, due to the definition of the numbers $C_m$ and the choice of the number $M$, the inequality
$$C_0 > C_1 > \dots > C_{M-1} > 1 \geqslant C_M > C_{M+1} > \dots > C_{N-1}.$$
Hence,
$$F(\overline{\theta}^{(0)}) < \dots < F(\overline{\theta}^{(M)}) \geqslant F(\theta^{(M+1)}) > F(\overline{\theta}^{(M+2)}) > \dots > F(\overline{\theta}^{(N)}).$$
Thus, control $\overline{\theta}^{(M)}$ can be chosen as optimal.
Let's return to our problem from the “ancient manuscript”. For her $N = 10$, $u = \frac{1}{5}$ and $M = 4$. Thus, control $\overline{\theta}^{(4)} = (1, 1, 1, 1, 0, \dots, 0)$ will be optimal, and the value of the objective function - the total amount of money spent over ten years - when choosing control in this way is
$$F(\overline{\theta}^{(4)}) = \left(1 + \frac{1}{5}\right)^4 \times 10^5 \frac{6}{5} \approx 248832 \text{ реал.}$$

Thus, the solutions to the problem proposed by our main heroes are indeed not optimal. Note that control $\overline{\theta}^{(5)}$ is also optimal, since the zeros are chosen among the step ones, in general, not in the only way.

Problem 1. What conditions on $a$ and $N$ ensure the uniqueness of the optimal control among step ones?

Problem 2. Is it true that for our problem optimal control must necessarily be stepwise?

Problem 3. Find the smallest number of years $N > 10$ such that the management of the thrifty Lopez $(1, \dots, 1, 0)$ still turns out to be more profitable than the management $(0, 0, \dots, 0)$ proposed by the wasteful Alonso.
