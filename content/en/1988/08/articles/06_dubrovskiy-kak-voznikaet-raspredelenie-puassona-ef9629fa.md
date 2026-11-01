---
id: 1988-8-dubrovskiy-kak-voznikaet-raspredelenie-puassona-ef9629fa
issue: kvant_1988_8
year: 1988
number: "8"
title: How does the Poisson distribution arise?
authors:
  - Дубровский В. Н.
rubric: raznoe
page_first: 25
page_last: 28
page_labels: 23-26
tag: QYFL
lang: en
source: kvant_digital
extraction: vision
content_sha256: 1d44b26f98301d55cb573add9ba94e29fe36a5aa09989eed3f94c3838184cd9f
prompt_sha256: draft-1
translated_from: content/ru/1988/08/articles/06_dubrovskiy-kak-voznikaet-raspredelenie-puassona-ef9629fa.md
source_content_sha256: a1247318f4824dcf1615994c20b6f03a7b259b86ca2e4070c967b4c10df12ab8
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 23⟧

HOW IT ARISES
POISSON DISTRIBUTION

Candidate of Physical and Mathematical Sciences
V. N. DUVROVSKY

Every chance you can catch the beginning of the summer rain, when the ground is still dry and only here and there are rare dark spots from the first drops visible. These specks are an almost perfect model of the "randomly scattered dots" mentioned in the Poisson Distribution article. Let's try, using this visual model, to formulate mathematical hypotheses that describe randomly scattered points, and to derive from them,

*) Involuntarily, we are forced to do without a definition of the concept of probability - those who wish can find it, for example, in the book by A. N. Kolmogorov, I. G. Zhurbenko, A. V. Prokorov “Introduction to the Theory of Probability” (M., Nauka, 1978). We hope that a small amount of common sense will be enough to understand the article.

that the number of points that fall within a given area during the definition of time is subject to the Poisson distribution.

Let $P_k$ be the probability*) that $k$ drops will fall on the area we have chosen. First of all, it is clear that

1) the probability $P_k$ is determined only by the area s of this area and does not depend on its shape and location.

Therefore, we will look for $P_k$ as a function of the area of ​​the site, i.e. in the form of $P_k(s)$. The second natural hypothesis is that

2) the number of drops falling on a given area does not depend on the number of drops falling on any other area that does not intersect with the first.

⟦folio 24⟧

In other words, the probability $P_0, P_1, P_2, \dots$ for a given area does not depend in any way on how many drops end up in some other area. The mathematical expression of the condition of independence is the rule of probability multiplication: the probability of the simultaneous occurrence of two independent events is equal to the product of their probabilities. For example, if $S$ and $T$ are two disjoint sections of $P_1(s) \cdot P_1(t)$. Similarly, the event “2 drops fell on areas $S$ and $T$” has a probability of $P_2(s) \cdot P_0(t) + P_1(s) \cdot P_1(t) + P_0(s) \cdot P_2(t)$ (this event is divided into three: on area $S$ 2 drops fell, and on $T$ - none; on area $S$ 1 drop fell and on $T$ - 1 drop; on area $S$ got 0 drops, and $T$ got 2 drops; its probability is equal to the sum of the probabilities of these three components). We emphasize that the rule for multiplying probabilities is not proven - this is a definition of independence, but it is not difficult to explain why this definition is accepted.

One of the fundamental principles of probability theory (the law of large numbers) states that the frequency with which an event occurs in a sufficiently long series of experiments approaches its probability. Let the events $A$ and $B$ be observed in a series of $n$ experiments, and the event $B$ occurred $m$ times and both events occurred simultaneously $k$ times; then the frequency $m/n$ of event $B$ is approximately equal to its probability $P(B)$, and the frequency $k/n$ of the simultaneous occurrence of events $A$ and $B$ is the corresponding probability $P(AB)$. The independence of events $A$ and $B$ must be in the fact that information about the occurrence of event $B$ cannot influence the probability of the occurrence of event $A$. Consequently, the frequency of $k/m$ experiments in which event $A$ occurred, among those experiments in which event $B$ was recorded, should be the same as in the series of all experiments in general: $k/m \approx P(A)$. Thus,

$$P(AB) \approx \frac{k}{n} = \frac{k}{m} \cdot \frac{m}{n} \approx P(A) \cdot P(B).$$

In the limit (at $n \to \infty$) these approximate equalities turn into exact ones. We receive confirmation that the “probability multiplication rule” correctly reflects our intuitive idea of ​​​​the independence of events.

Let's return, however, to raindrops. The third hypothesis describing their loss is as follows:

3) the probability $P_{>1}(h)$ that at least 2 drops will fall on a small area $h$ is negligible compared to the probability $P_1(h)$ that 1 drop will fall on this area, i.e. $P_{>1}(h)/P_1(h) \to 0$ with $h \to 0$.

In other words, drops do not fall into the same place twice. Now the conditions are fully formed and you can start getting the next one.

First of all, let's find $P_0(s)$. Distance area $s+t$ and divide it into two areas - area $s$ and area $t$. If the larger section $(s+t)$ remained dry, then no drops fell on both its pieces $s$ and $t$, and due to condition 2) independence of the sections for any $s, t \geqslant 0$ we obtain $P_0(s+t) = P_0(s)P_0(t)$.

From this equation we need to find the function $P_0$, about which we additionally know that $0 \leqslant P_0(s) \leqslant 1$ and $P_0(s) - убывающая функция. Докажем, что $P_0(s) = e^{-\lambda s}$ при некотором $\lambda > 0$. Пусть $f is a decreasing function satisfying $f(s+t) = f(s) \cdot f(t)$. For any $s > 0$ and any natural $n$ $f(ns) = f(s + (n-1)s) = f(s)f((n-1)s) = \dots = (f(s))^n$.

Substituting $s = \frac{1}{n}$ here and putting $f(1) = e^{-\lambda}$, we get $f(1/n) = e^{-\lambda/n}$. Now we substitute $s = 1/m$ and we get $f(n/m) = (f(1/m))^n = e^{-\lambda n/m}$, i.e. for any rational $s > 0$ we have $f(s) = e^{-\lambda s}$. Now, obtaining the monotency function $f(s)$

⟦folio 25⟧

and $e^{-\lambda s}$, it is easy to prove that the last equality holds for all $s > 0$.

Note that $P_0(h) \approx 1 - \lambda h$ for small $h$ (the notation $u(h) \approx v(h)$ will mean that $(u(h) - v(h))/h \rightarrow 0$ for $h \rightarrow 0$). Indeed, the product of the function $e^{-\lambda s}$ with $s = 0$ is equal to $-\lambda e^{-\lambda h} = -\lambda$, i.e. $(P_0(h) - 1)/h = (e^{-\lambda h} - 1)/h \rightarrow -\lambda$ with $h \rightarrow 0$. Therefore, $P_1(h) + P_{>1}(h) = 1 - P_0(h) \approx \lambda h$ for small $h$. And since, by virtue of condition 3, $P_{>1}(h)$ is negligible compared to $P_1(h)$, for small $h$ $P_1(h) \approx \lambda h$, $P_k(h) \approx 0$ for $k > 1$.

Now we can create differential equations from which we will find $P_k(s)$. Let's consider a plot of area $s$ and add to it a plot of small area $h$. Repeating the above equal derivation, we obtain

$$P_k(s + h) = P_k(s)P_0(h) + P_{k-1}(s)P_1(h) + (P_{k-2}(s)P_2(h)) + \dots + P_0(s)P_k(h).$$

Since $P_0(h) \approx 1 - \lambda h$, $P_1(h) \approx \lambda h$, and the entire expression in parentheses are negligible compared to $h$,

$$P_k(s + h) \approx P_k(s) (1 - \lambda h) + \lambda hP_{k-1}(s);$$

hence,

$$P_k'(s) = \lim_{h \rightarrow 0} \frac{P_k(s + h) - P_k(s)}{h} = -\lambda P_k(s) + \lambda P_{k-1}(s),$$

or

$$P_k'(s) + \lambda P_k(s) = \lambda P_{k-1}(s), \quad k = 1, 2, \dots$$

To solve this equation, consider the function $f_k(s) = P_k(s)e^{\lambda s}$. Let's find her product: $f_k'(s) = P_k'(s)e^{\lambda s} + \lambda P_k(s)e^{\lambda s}$. Multiplying equation (*) by $e^{\lambda s}$, we obtain

$$f_k'(s) = \lambda f_{k-1}(s),$$

with $f_k(0) = P_k(0) = 0$ at $k > 1$.

Now it is easy to find all the functions $f_k$ one after another: $f_1'(s) = \lambda P_0(s)e^{\lambda s} = \lambda$, therefore $f_1(s) = \lambda s$ (we taught that $f_1(0) = 0$); $f_2'(s) = \lambda f_1(s) = \lambda^2 s$, therefore $f_2(s) = \lambda^2 s^2/2$, ..., $f_k(s) = \lambda^k s^k/k!$. And finally, we can write down the desired expression

$$P_k(s) = \frac{(\lambda s)^k}{k!}e^{-\lambda s},$$

valid for all $k = 0, 1, 2, \dots$.

Let's summarize. If points on the plane are randomly selected so that conditions 1–3 are met, then the number of points falling on an area of ​​area $s$ has a Poisson distribution with parameter $\lambda s$, where $\lambda > 0$ is a parameter characterizing the average density of points (cf. formula (2) in the article “Poisson distribution”).

Of course, everything that has been said can be transferred almost completely to the case of points in space or on a line. The latter case deserves special mention, because it occurs most often in practice. In this case, the straight line on which the points are located serves as the time axis, and the points themselves are the moments of arrival of some random signals that obey conditions similar to conditions 1-3. Standard examples of such “signal flows,” called simple or Poissian flows in probability theory, are, for example, particles emitted by a radioactive substance and calls arriving at a telephone exchange.

We have touched upon only one side of the question posed in the title of the article. With other readers, if he happens to know everything - the theory of probability and random processes.

Dear readers!

In the future, 1989, the magazine «Kvant», as before, will be distributed only by subscription. You can sign up for an annual subscription until November 1, 1988. Subscriptions are accepted without restrictions at Soyuzpechat agencies, post offices and post offices. Journal index «Kvant» in the Soyuzpechat catalog 70465.

⟦folio 26⟧

The federal issue of our magazine featured three photographers of ski tracks. The photos were taken at the same time, and the ski tracks were located nearby. But they are so different from each other...
We invited readers to think about what explains such a variety of types of ski tracks.

Probably everyone who became interested in this issue realized that it is impossible to do without physics. And physics is always physics, both in March and in August. Therefore, we continue the conversation about ski tracks today, when the growing snow has already melted, and new snow is still far away.
