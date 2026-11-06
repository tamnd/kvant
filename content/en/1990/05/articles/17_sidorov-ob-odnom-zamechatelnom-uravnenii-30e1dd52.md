---
id: 1990-5-sidorov-ob-odnom-zamechatelnom-uravnenii-30e1dd52
issue: kvant_1990_5
year: 1990
number: "5"
title: About one wonderful equation
authors:
  - Сидоров Ю. В.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 60
page_last: 64
page_labels: 58-62
lang: en
source: kvant_digital
extraction: vision
content_sha256: 2924c5efacd4055eadcaa861eebc711125fd0789f7d5c05c6ebceb64720f2f4f
prompt_sha256: draft-1
translated_from: content/ru/1990/05/articles/17_sidorov-ob-odnom-zamechatelnom-uravnenii-30e1dd52.md
source_content_sha256: 228bf07c989b141a46496bd3fc1209dd0c7b33593e618f082f4615aee55e83d5
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 58⟧

---
running_head:
folio:
---

About one wonderful equation

Candidate of Physical and Mathematical Sciences Y. SIDOROV

Let's start with a problem that, according to rumors, was once offered to an applicant during an oral entrance exam.

How many roots does the equation have?

$$\left( \frac{1}{16} \right)^x = \log_{\frac{1}{16}} x?$$

If you draw a sketch of the graphs of the functions $y = a^x$ and $y = \log_a x$ for $0 < a < 1$ (Fig. 1), it may seem that these graphs necessarily intersect at one point, and this point lies on the straight line $y = x$.

However, it is immediately clear that equation (1) has two roots: $x = \frac{1}{2}$ and $x = \frac{1}{4}$ (check this by substitution), and the intersection points of the graphs corresponding to these roots do not lie on the straight line $y = x$. Thus, equation (1) has at least three roots.

This fact surprises most high school graduates and, unfortunately, many teachers, although the problem is quite “old” and is often given as an example showing that the graphical method of solving an equation must be used with great caution. The secret of the incorrect solution to the problem is simple: figure 1 shows very rough sketches of graphs and this led to an incorrect conclusion about the number of roots of equation (1).

figure 2 shows more accurate graphs constructed using a computer. Of this figure non-

⟦folio 59⟧

---
running_head:
folio:
---

It is possible to see how many roots equation (1) has, since the curves are not perfectly thin and therefore practically merge at some interval.

The graphs for figure 3 were also constructed using a computer. This figure already clearly shows that the equation
$$\left(\frac{1}{64}\right)^x = \log_{\frac{1}{64}} x$$
has exactly three roots.

If you use a computer to construct the same graphs $y = \left(\frac{1}{16}\right)^x$ and $y = \log_{\frac{1}{16}} x$, choosing, for example, 100 cm as a unit, then, as with figure 3, you can see that equation (1) has (we do not have the opportunity to place figure here, made by a machine) exactly three roots. However, no computer can construct perfectly accurate graphs. Therefore, proof using only figure cannot be trusted and the structure of mathematical reasoning is necessary.

We will study the general equation:
$$a^x = \log_a x$$
for different values ​​of $a$ (of course, here $a > 0, a \neq 1$).

Note that for any $a$ equation (2) is equivalent to the equation
$$a^{a^x} = x.$$

Together with equation (2'), we consider the equation
$$a^x = x.$$

Let $x_0$ be the root of equation (3).

Then $a^{a^x} = a^{x_0} = x_0$, i.e. $x_0$ is also the root of equation (2') and (2).

So, if equation (3) has at least one root, then equation (2) also has roots.

Let's make one more remark. At $a > 1$ the function $f(x) = a^x$ increases. Equation (2') can be written as follows: $f(f(x)) = x$, and equation (3) takes the form $f(x) = x$.

Lemma. If the function $y = f(x)$ is increasing, then the equations $f(f(x)) = x$ and $f(x) = x$ are equivalent.

Proof. Let $x_0$ be the root of the equation $f(x) = x$. Then $f(f(x_0)) = f(x_0) = x_0$, so $x_0$ is the root of the first equation. Conversely, let $f(f(x_0)) = x_0$, and $x_0 \neq f(x_0)$. Then either $x_0 > f(x_0)$ or $x_0 < f(x_0)$, and since the function $f$ is increasing, we find that in the first case $f(x_0) > f(f(x_0)) = x_0$, and in the second case $f(x_0) < f(f(x_0)) = x_0$. Contradiction.

From the lemma and the remarks made earlier, (2) is equivalent to the equation $a^x = x$.

Exercises
1. Solve the equation
$$2\sqrt{2x-1} = x^3 + 1.$$

2. For each value of $a$, solve the equation
$$\sqrt{a + \sqrt{a + x}} = x.$$

Study of the equation $a^x = x$
First, let us formulate one remarkable theorem, which has already been discussed in the journal «Kvant».

Fig. 1. Fig. 2. Fig. 3.

⟦folio 60⟧

---
running_head:
folio:
---

Theorem (Bolzano - Weierstrass). If the function $y = f(x)$ is defined and continuous on the interval $[a; b]$, and $f(a) < 0$, $f(b) > 0$, then the equation $f(x) = 0$ has a root belonging to the interval $(a; b)$.

This theorem is proven in the course of mathematical analysis. However, its meaning is clearly clear: the continuous curve shown in figure 4 necessarily intersects the $Ox$ axis. We will use it many times in the future.

In particular, if a given function returns or kills on the interval $[a; b]$, then the equation $f(x) = 0$ has a unique root belonging to the interval $(a; b)$.

Now let's examine equation (3). It is equivalent to the equation

$$\ln a = \frac{\ln x}{x}.$$  (3')

Let's plot the function $h(x) = \frac{\ln x}{x}$. Since $h' = \frac{1 - \ln x}{x^2}$, function $h$ returns at $x < e$ and kills at $x > e$, and at point $x = e$ reaches a maximum of $\frac{1}{e}$ (Fig. 5, a). Therefore, equation (3') has no roots if $\ln a > \frac{1}{e}$ (i.e. at $a > e^{\frac{1}{e}}$) and has a single root $x = e$ at $a = e^{\frac{1}{e}}$. Exercises

3. Prove that for $0 < \ln a < \frac{1}{e}$, i.e. for $1 < a < e^{\frac{1}{e}}$, equation (3') has exactly two roots.

4. Use the graph of figure 5, and show that the graph of the function $y = x^{\frac{1}{x}}$ has the form shown in figure 5, b, and examine the equation $x^{\frac{1}{x}} = a$.

5. Graph the function $y = x^x$ and examine the equation $x^x = a$.

So, finally, for $1 < a < e^{\frac{1}{e}}$ equation (2) has exactly two roots, for $a = e^{\frac{1}{e}}$ it has one root $x = e$ and has no roots for $a > e^{\frac{1}{e}}$.

⟦folio 61⟧

---
running_head:
folio:
---

For 0 < a < 1, the equation $a^x = x$ has a single root $x_0$.
Consider the function
$$f(x) = a^x - \log_a x$$
and study her behavior. To do this, we calculate its derivative
$$f'(x) = a^x \ln a - \frac{1}{x \ln a} = \frac{xa^x \ln^2 a - 1}{x \ln a}.$$
Let us now consider the numerator of the resulting fraction $\varphi(x) = xa^x \ln^2 a - 1$. Its denominator is negative for all $x > 0$ and therefore the sign $f'(x)$ is opposite to the sign $\varphi(x)$.
Exercise 6. Prove that the function $\varphi(x)$ decreases at $x < -\frac{1}{\ln a}$, returns at $x > -\frac{1}{\ln a}$ and takes its highest value $\varphi_{\max}$ at $x = -\frac{1}{\ln a}$.
From Exercise 6 it follows that if $\varphi_{\max} \leq 0$ for all $x$, then the function $f(x)$ returns for all $x > 0$, so $x_0$ is the only root of equation (2) (Fig. 6, a, b).

Solving the inequality $\varphi_{\max} = -\frac{\ln a}{e} - 1 \leq 0$, we obtain $a \geq e^{-e}$. So, for $e^{-e} \leq a < 1$, equation (2) has exactly one root $x = x_0$.

If $0 < a < e^{-e}$, then $\varphi_{\max} > 0$, and the graph of the function $\varphi$ has the form shown in figure 6, c. To justify this, it is enough to note that $\varphi(0) = -1$, and $\varphi(1) < 0$. Graphs of the function $f(x) = a^x - \log_a x$ for $e^{-e} < a < 1$ and $a = e^{-e}$ are shown in Figures 7, a, b.

Exercise 7. Prove that $\varphi(1) = a \ln^2 a - 1 < 0$ when $0 < a < e^{-e}$. Note. Find the maximum of the function $g(a) = a \ln^2 a$.

From Exercise 7 it follows that the function $\varphi(x)$ is equal to zero at two points $\alpha$ and $\beta$, and $0 < \alpha < -\frac{1}{\ln a}$ and $-\frac{1}{\ln a} < \beta < 1$.

This means that the function $f$ returns at $x \in (0, \alpha)$, decreases at $x \in (\alpha; \beta)$ and returns again at

Puc. 7.

Puc. 8.

Puc. 9.

Puc. 10.

⟦folio 62⟧

---
running_head:
folio:
---

$x \in (\beta; 1)$. Thus, the points $\alpha$ and $\beta$ are the correspondence: $\alpha$ is the maximum point, and $\beta$ is the minimum point of the functions $f$ (the graph of this function is shown in figure 7, $\theta$).

To complete our study, we prove that $\alpha < x_0 < \beta$.

Exercise 8. Prove that $x_0 < \frac{1}{e}$ when $0 < a < e^{-e}$. Note. Assuming that $x_0 > \frac{1}{e}$, we get $x_0 = a^{x_0} < a^{\frac{1}{e}} < \frac{1}{e}$ - a contradiction!

Let us now calculate $\varphi(x_0) = x_0^2 \ln^2 a - 1 = \ln^2 a x_0 - 1 = \ln^2 x_0 - 1$. Since $\ln x_0 < -1$, we immediately get $\varphi(x_0) > 0$, so $f'(x_0) < 0$, i.e. $\alpha < x_0 < \beta$.
