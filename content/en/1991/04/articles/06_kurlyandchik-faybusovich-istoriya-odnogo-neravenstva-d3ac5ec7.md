---
id: 1991-4-kurlyandchik-faybusovich-istoriya-odnogo-neravenstva-d3ac5ec7
issue: kvant_1991_4
year: 1991
number: "4"
title: The story of one inequality
authors:
  - Курляндчик Л. Д.
  - Файбусович А.
rubric: osnovnye-stati
page_first: 16
page_last: 20
page_labels: 14-18
lang: en
source: kvant_digital
extraction: vision
content_sha256: cb8c3999eed8e96313e01314a431e9899cdb6fc12618d963b89e15d10d308e12
prompt_sha256: draft-1
translated_from: content/ru/1991/04/articles/06_kurlyandchik-faybusovich-istoriya-odnogo-neravenstva-d3ac5ec7.md
source_content_sha256: 91483fcc90a0097db1297611af9ead109a0b438142ab5a35a3a8e8499e8c3d6b
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 14⟧

---
running_head:
folio:
---

We'll talk about inequality
$$\frac{x_1}{x_2+x_3} + \frac{x_2}{x_3+x_4} + \dots + \frac{x_{n-1}}{x_n+x_1} + \frac{x_n}{x_1+x_2} \geq \frac{n}{2}),$$
which was first proposed by the American mathematician Shapiro in the pages of The American Mathematical Monthly in 1954. This problem has attracted the attention of many mathematicians around the world. A very significant contribution to its solution was made by a northern schoolboy (reader «Kvant»!) Volodya Drinfeld, who subsequently became a Fields Medal laureate **).
In 1958, Professor Mordell of Cambridge proved this inequality for $n \leqslant 6$. Faced with fundamental difficulties in the case of $n=7$, he conjectured that the inequality for $n=7$ is not true. It is curious that if he managed to prove his hypothesis, that is, find seven numbers $x_1, x_2, \dots, x_7$ for which such a sum would be less than 7/2, then it would immediately follow that the inequality is not true for all $n \geqslant 7$. Let's prove it. First we introduce the notation
$$f_n(x_1, x_2, \dots, x_n) = \frac{x_1}{x_2+x_3} + \dots + \frac{x_n}{x_1+x_2},$$
which will save us a lot of space. Then we note that
$$f_n(x_k, x_{k+1}, \dots, x_n, x_1, x_2, \dots, x_{k-1}) = f_n(x_1, x_2, \dots, x_n),$$
that is, the left side of the inequality does not change if the numbers included in its left side are rearranged around the cycle. Therefore, this inequality and others,
*) All variables in this article are non-negative and the denominator is positive.
**) «Kvant» spoke about the Fields Award and its laureates in No. 6, 1990.

possessing this property are called cyclic.
Check that
$$f_{n+2}(x_1, x_2, \dots, x_n, x_1, x_2) = f_n(x_1, x_2, \dots, x_n) + 1.$$
It follows that if
$$f_n(x_1, x_2, \dots, x_n) < \frac{1}{2} n,$$
That
$$f_{n+2}(x_1, x_2, \dots, x_n, x_1, x_2) < \frac{1}{2} (n+2).$$
Now check that
$$f_{n+1}(x_1, \dots, x_i, x_i, \dots, x_n) - f_n(x_1, x_2, \dots, x_n) - \frac{1}{2} = \frac{(x_i - x_{i-1})(x_i - x_{i+1})}{2x_i(x_i + x_{i+1})},$$
in this case, it should be assumed that $x_{n+1} = x_1$ and $x_{n+2} = x_2$. It follows that if
$$(x_i - x_{i-1})(x_i - x_{i+1}) \leqslant 0,$$
That
$$f_{n+1}(x_1, \dots, x_i, x_i, \dots, x_n) < \frac{1}{2} (n+1)$$
at $f_n(x_1, x_2, \dots, x_n) < \frac{1}{2} n$.

But in the case of odd $n$, it is necessary to find a $i$ for which $(x_i - x_{i-1})(x_i - x_{i+1}) \leqslant 0$, because if for all $i$ the inequality $(x_i - x_{i-1})(x_i - x_{i+1}) > 0$ were satisfied, then, variable of these inequalities, we would get $(x_1 - x_2)^2(x_2 - x_3)^2 \dots (x_n - x_1)^2 < 0$. Since 7 is an odd number, the inequality would not be true for $n=8$ and all even $n$, and the previous reasoning would ensure this result for the odd $n$.

However, in 1961, Djekovic, a mathematician from Belgrade, refuted this assumption.

⟦folio 15⟧

---
running_head:
folio:
---

Mordell position, proving the inequality for $n=8$. And in 1967, the Brazilian mathematician Novosad published a proof for $n=10$. In 1974, Soviet mathematicians V. I. Levin and E. K. Godunova proved the inequality for $n=12$.

In those years, no mathematician tried to prove inequality in a general form. Already in 1956, the English mathematician Lighthill established that, generally speaking, the inequality is not true. He managed to construct a set of twenty numbers $x_1, \dots, x_{20}$ such that $f_{20}(x_1, \dots, x_{20}) < 10$. And after some time, he and, independently of him, the Scottish mathematician Zulauf managed to find corresponding examples for $n=14$. Here is one of them: 50, 5, 48, 3, 48, 1, 50, 0, 52, 1, 54, 4, 53, 6.

In the case of odd $n$ things are much more complicated. In 1958, Rankin, a mathematician from Glasgow, proved that the inequality does not hold for sufficiently large odd $n$.

In 1959, Zulauf, already mentioned by us, proved that the inequality is not true for odd $n \geqslant 53$. In 1961, Diananda, a scientist from Singapore, provided a countermeasure for $n=27$. A refuting example for $n=25$ was constructed by the English mathematician Deikin in 1971.

Two schoolchildren from the mathematical boarding school at Leningrad University (students of one of the authors), R. Alekseev and E. Foshkin, using a computer, managed to independently construct a countermeasure for $n=25$:
32, 0, 37, 0, 43, 0, 50, 0, 59, 8, 62, 21, 55, 29, 44, 32, 33, 31, 24, 30, 16, 29, 10, 29, 4.

More recently, in October 1989, the American mathematician Trosch published a proof of the inequality for all other $n$, namely for 13, 15, 17, 19, 21 and 23. However, for this it was enough to prove the inequality for $n=23$, which he did.

Since 1956, when it was established that the inequality $f_n \geqslant \frac{n}{2}$ is false, it has been investigated in two directions. The first thing is to find out for which $n$ the inequality is true. We have already reported on the status of this issue. We will now move on to talk about another direction of research.

In 1957, Rankin proved that the inequality $f_n \geqslant \frac{2\sqrt{2}-1}{6} n = \frac{n}{2} \cdot 0,609$ is true. In 1961, he slightly improved his result: $f_n \geqslant \frac{n}{2} \cdot 0,661$. In the same year, Diananda was able to prove that $f_n \geqslant \frac{2\sqrt{2}-1}{2} \cdot \frac{n}{2} = \frac{n}{2} \cdot 0,914$. In 1962 he proved that $f_n \geqslant \frac{n}{2} \times 0,922$. i.e., he inserted the question of what is the largest number $\gamma$ for which the inequality $f_n \geqslant \gamma \cdot \frac{n}{2}$ is true for any natural $n$. It was this problem that Volodya Drinfeld solved.

It all started with the fact that in 1969, at the Third All-Union Mathematical Optimization, it was proposed to prove the inequality $\frac{x_1}{x_2+x_3} + \dots + \frac{x_n}{x_1+x_2} > \frac{n}{4}$. Of all the participants, one student was able to solve it - a student at the mathematical boarding school at Leningrad University, A. Berzinsh, a three-time winner of the All-Union Optimization.

The solution here is this. Let $x_{i_1}$ be the largest of the numbers $x_1, x_2, \dots, x_n$; $x_{i_2}$ — the greater of the two numbers following $x_{i_1}$; $x_{i_3}$ is the greater of the two numbers following $x_{i_2}$ and so on. Let $k$ be such that the maximum of the two numbers following $x_{i_k}$ is $x_{i_1}$. It is clear that $k \geqslant \frac{n}{2}$, and therefore
$\frac{x_1}{x_2+x_3} + \dots + \frac{x_n}{x_1+x_2} > \frac{x_{i_1}}{2x_{i_2}} +$
$\frac{x_{i_2}}{2x_{i_3}} + \dots + \frac{x_{i_k}}{2x_{i_1}} \geqslant \frac{k}{2} \geqslant \frac{n}{4}$.

That the last sum is not less than $\frac{k}{2}$ follows from Cauchy’s inequality $a_1+a_2+\dots+a_k \geqslant k^k \sqrt{a_1a_2 \dots a_k}$.

⟦folio 16⟧

---
running_head:
folio:
---

One of the winners of this optimization was Kharkov schoolboy Voloda Drinfeld. As part of the Soviet Union team, he took part in the International Mathematical Optimization. The scientific leader of the team was one of the largest Soviet experts on naravavents, Professor V.I. Levin. He told the guys about cyclic inequality, and in the same 1969 Volod managed to find the desired value $\gamma$. It's okay that $\gamma=0,989$...

Before telling the idea of ​​V. Drinfeld’s work, we will show how to obtain weaker results formulated in problem M1250. Let us recall the conditions of this problem.

M1250. Prove that if $x_1, x_2, \dots, x_n$ are positive numbers, then $\frac{x_1}{x_2+x_3} + \frac{x_2}{x_3+x_4} + \dots + \frac{x_n}{x_1+x_2}$ is greater than $a$ ($\sqrt{2}-1)n$; b) $\frac{5}{12}n$; c) if the numbers $x_1, x_2, \dots, x_n$ form a monotonic sequence, then this sum is not less than $\frac{n}{2}$.

Solution
a) Each of the problems
$\frac{x_i}{x_{i+1}+x_{i+2}} (i=1, 2, \dots, n)$ will be represented in the form
$\frac{x_i+\frac{1}{2}x_{i+1}}{x_{i+1}+x_{i+2}} + \frac{\frac{1}{2}x_{i+1}+x_{i+2}}{x_{i+1}+x_{i+2}} -1$.

We will get $2n$ problems and group them by parameter - the first fraction with $2n$th; second with third; fourth with fifth and so on. Let’s immediately estimate the sum of numbers forming a pair:
$\frac{1}{2}x_i+x_{i+1} + \frac{x_i+\frac{1}{2}x_{i+1}}{x_{i+1}+x_{i+2}} \geq$
$\geq 2\sqrt{\frac{\left(\frac{1}{2}x_i+x_{i+1}\right)\left(x_i+\frac{1}{2}x_{i+1}\right)}{(x_i+x_{i+1})(x_{i+1}+x_{i+2})}}$
$= 2\sqrt{\left(\frac{1}{2}+\frac{x_i+x_{i+1}}{4(x_i+x_{i+1})^2}\right)\frac{x_i+x_{i+1}}{x_{i+1}+x_{i+2}}}$
$> \sqrt{2} \cdot \sqrt{\frac{x_i+x_{i+1}}{x_{i+1}+x_{i+2}}}$.

Since the product of $n$ numbers
$\sqrt{\frac{x_1+x_2}{x_2+x_3}}, \sqrt{\frac{x_2+x_3}{x_3+x_4}} \dots, \sqrt{\frac{x_n+x_1}{x_1+x_2}}$ is equal to 1, then from Cauchy’s inequality it follows that their sum is not less than $n$. Therefore the original sum is greater than $\sqrt{2n}-n=(\sqrt{2}-1)n$.

6) When proving point a) we added one to each fraction. But why do you need to add exactly one? Let's add an arbitrary number $\alpha$ and select $\beta$ so that the equality holds
$\frac{x_i}{x_{i+1}+x_{i+2}} + \alpha = \frac{x_i+\beta x_{i+1}}{x_{i+1}+x_{i+2}} +$
$+\frac{\alpha(\beta x_{i+1}+x_{i+2})}{x_{i+1}+x_{i+2}}$.

It is clear that $\beta+\alpha\beta=\alpha$, i.e. $\beta=\frac{\alpha}{\alpha+1}$. Hence,
$\frac{x_i+\beta x_{i+1}}{x_{i+1}+x_{i+2}} + \frac{\alpha(\beta x_{i+1}+x_{i+1})}{x_{i+1}+x_{i+2}} \geq$
$\geq 2\sqrt{\alpha \frac{\left(x_i+\beta x_{i+1}\right)\left(\beta x_{i+1}+x_{i+1}\right)}{(x_i+x_{i+1})(x_{i+1}+x_{i+2})}}$
$= 2\sqrt{\alpha \frac{\beta(x_i+x_{i+1})^2+(\beta-1)^2x_i x_{i+1}}{(x_i+x_{i+1})(x_{i+1}+x_{i+2})}}$
$> 2\sqrt{\alpha \beta \frac{x_i+x_{i+1}}{x_{i+1}+x_{i+2}}} = \frac{2\alpha}{\sqrt{\alpha+1}} \sqrt{\frac{x_i+x_{i+1}}{x_{i+1}+x_{i+2}}}$.

Means,
$\frac{x_1}{x_2+x_3} + \frac{x_2}{x_3+x_4} + \dots + \frac{x_n}{x_1+x_2} >$
$> \frac{2\alpha}{\sqrt{\alpha+1}} \left(\sqrt{\frac{x_1+x_2}{x_2+x_3}} + \sqrt{\frac{x_2+x_3}{x_3+x_4}} + \dots \right.$
$... + \sqrt{\frac{x_n+x_1}{x_1+x_2}}) - \alpha n >$
$> \frac{2\alpha}{\sqrt{\alpha+1}} n - \alpha n = \left(\frac{2\alpha}{\sqrt{\alpha+1}} - \alpha\right) \cdot n$.

If we put $\alpha=\frac{5}{4}$, then $\frac{2\alpha}{\sqrt{\alpha+1}} - \alpha=\frac{5}{12}=0,416$... and the statement of point 6) is proven. Recall that part a) is obtained by putting $\alpha=1$.

⟦folio 17⟧

---
running_head:
folio:
---

Consider the case $x_1 \geqslant x_2 \geqslant \dots \geqslant x_n$. Let us show that here there is a correspondence
$$f_n(x_1, x_2, \dots, x_n) \geqslant$$
$$\geqslant f_{n-1}(x_1, x_2, \dots, x_{n-1}) + \frac{1}{2}.$$
Indeed, the same thing holds:
$$f_n(x_1, x_2, \dots, x_n) - f_{n-1}(x_1, x_2, \dots, x_{n-1}) =$$
$$= \frac{(x_{n-2} - x_{n-1})(x_1 - x_n)}{(x_{n-1} + x_n)(x_1 + x_{n-1})} +$$
$$+ \frac{(x_1 - x_n)(x_{n-1} - x_n)(x_1 - x_{n-1})}{2(x_{n-1} + x_n)(x_1 + x_{n-1})} +$$
$$+ \frac{(x_{n-1} - x_n)(x_2 - x_n)}{(x_1 + x_2)(x_1 + x_n)} + \frac{1}{2}.$$
But all terms are non-negative (from the monotonicity of the sequence $x_1, x_2, \dots, x_n$). So,
$$f_n(x_1, x_2, \dots, x_n) \geqslant f_{n-1}(x_1, x_2, \dots, x_{n-1}) +$$
$$+ \frac{1}{2} \geqslant f_{n-2}(x_1, x_2, \dots, x_{n-2}) + 1 \geqslant \dots$$
$$\geqslant f_2(x_1, x_2) + \frac{n-2}{2} =$$
$$= \frac{x_1}{x_1 + x_2} + \frac{x_2}{x_2 + x_1} + \frac{n-2}{2} = \frac{n}{2}.$$
Now consider the case $x_1 \leqslant x_2 \leqslant \dots \leqslant x_n$. Note that
$$f_n(x_1, x_2, \dots, x_n) = \frac{x_1 + x_2}{x_2 + x_3} + \dots + \frac{x_n + x_1}{x_1 + x_2} -$$
$$- n + \frac{x_2}{x_1 + x_2} + \frac{x_3}{x_2 + x_3} + \dots + \frac{x_n}{x_n + x_1}.$$
But the first sum is not less than $n$, since the product of all terms is equal to 1. Therefore, it is enough to show that
$$g_n(x_1, x_2, \dots, x_n) = \frac{x_2}{x_1 + x_2} +$$
$$+ \frac{x_3}{x_2 + x_3} + \dots + \frac{x_n}{x_{n-1} + x_n} + \frac{x_1}{x_n + x_1} \geqslant \frac{n}{2}.$$
To do this, we will show that
$$g_n(x_1, x_2, \dots, x_n) - g_{n-1}(x_1, x_2, \dots, x_{n-1}) -$$
$$- \frac{1}{2} = \frac{x_n}{x_{n-1} + x_n} + \frac{x_1}{x_n + x_1} - \frac{x_1}{x_{n-1} + x_1} -$$
$$- \frac{1}{2} = \frac{(x_{n-1} - x_1)(x_n - x_{n-1})(x_n - x_1)}{2(x_{n-1} + x_n)(x_n + x_1)(x_1 + x_{n-1})} \geqslant 0.$$
So,
$$g_n(x_1, x_2, \dots, x_n) \geqslant$$
$$\geqslant g_{n-1}(x_1, x_2, \dots, x_{n-1}) + \frac{1}{2} \geqslant$$
$$\geqslant g_{n-2}(x_1, x_2, \dots, x_{n-2}) + 1 \geqslant \dots$$
$$\dots \geqslant g_2(x_1, x_2) + \frac{n-2}{2} =$$
$$= \frac{x_2}{x_1 + x_2} + \frac{x_1}{x_2 + x_1} + \frac{n-2}{2} = \frac{n}{2}$$
Now we will present V. Drinfeld’s proof of his result. It rests on two remarkable inequalities.
The first involves two sets of $n$ positive numbers $a_1, a_2, \dots, a_n$ and $b_1, b_2, \dots, b_n$. Consider the expression $a_1b_1 + a_2b_2 + \dots + a_nb_n$. The claim is that this expression takes on a maximum value if the numbers are numbered such that $a_1 \geqslant a_2 \geqslant \dots \geqslant a_n$ and $b_1 \geqslant b_2 \geqslant \dots \geqslant b_n$, and a minimum value if
$$a_1 \geqslant a_2 \geqslant \dots \geqslant a_n, a b_1 \leqslant b_2 \leqslant \dots \leqslant b_n.$$
The second inequality, called Jensen's inequality, is related to convex functions. A function $\varphi(x)$ is said to be convex on the segment $[a; b]$ if its values ​​on any segment $[x_1; x_2]$ of $[a; b]$ lie lower on the graph than the segment connecting the points $(x_1; \varphi(x_1))$ and $(x_2; \varphi(x_2))$ (Fig. 1). This definition can be written as the inequality
$$\varphi(\alpha x_1 + (1 - \alpha)x_2) \leqslant \alpha \varphi(x_1) + (1 - \alpha) \varphi(x_2).$$

⟦folio 18⟧

---
running_head:
folio:
---

Jensen's inequality states that for any function $\varphi(x)$ that is convex on the interval $[a; b]$, an arbitrary set of points $x_1, x_2, \ldots, x_n$ from this interval, as well as an arbitrary set of positive numbers $p_1, p_2, \ldots, p_n$, the sum of which is equal to $1 (p_1 + p_2 + \ldots + p_n = 1)$, the relation holds

$$\varphi(p_1 x_1 + \ldots + p_n x_n) \leqslant \leqslant p_1 \varphi(x_1) + \ldots + p_n \varphi(x_n).$$

Let's proceed to presenting the proof. Let us denote $\frac{x_{i+1}}{x_i} = k_i$, and $\frac{x_1}{x_n} = k_n$. Let us arrange the resulting numbers $k_i$ in ascending order, and denote the integers of the resulting sequence by $m_j$. Now consider two sequences:

$$\frac{1}{m_1}, \frac{1}{m_2}, \ldots, \frac{1}{m_n} \text{ и} \frac{1}{1 + m_n}, \frac{1}{1 + m_{n-1}}, \ldots, \frac{1}{1 + m_2}, \frac{1}{1 + m_1}.$$

One monotonously kills, and the second monotonously increases. Using our first inequality, we get that

$$\frac{x_1}{x_2 + x_3} + \frac{x_2}{x_3 + x_4} + \ldots + \frac{x_n}{x_1 + x_2} = \frac{1}{k_1(k_2 + 1)} + \frac{1}{k_2(k_3 + 1)} + \ldots + \frac{1}{k_n(k_1 + 1)} \geqslant \frac{1}{m_1(m_n + 1)} + \frac{1}{m_2(m_{n-1} + 1)} + \ldots + \frac{1}{m_n(m_1 + 1)}.$$

(*)

We denote $m_i \cdot m_{n-i+1} = c_i$ and

$$r_i = \frac{1}{m_i(m_{n-i+1} + 1)} + \frac{1}{m_{n-i+1}(m_i + 1)},$$

Then

$$r_i = \frac{1}{c_i} \left(1 + \frac{c_i - 1}{(1 + m_i)(1 + m_{n-i+1})}\right).$$

Since $(1 + m_i)(1 + m_{n-i+1}) \geqslant (1 + \sqrt{c_i})^2$, then

$$r_i \geqslant \left\{ \begin{array}{l l} \frac{1}{c_i}, & c_i \geqslant 1, \\ \frac{2}{c_i + \sqrt{c_i}}, & c_i < 1. \end{array} \right.$$

Let's put $c_i = e^{y_i}$. From inequalities (*) and (**) we have

$$\frac{2}{n} \sum_{i=1}^{n} \frac{x_i}{x_{i+1} + x_{i+2}} \geqslant \geqslant \frac{1}{n} \left( \sum_{c_i \geqslant 1} e^{-y_i} + \sum_{c_i < 1} 2\left(e^{\frac{x}{2}} + e^{y_i}\right)^{-1} \right).$$

Let $g$ be the most convex function not exceeding the functions of $y = e^{-x}$ and $y = 2\left(e^{\frac{x}{2}} + e^{x}\right)^{-1}$. Then from inequality (***), due to Jensen’s inequality, we have

$$\frac{2}{n} \sum_{i=1}^{n} \frac{x_i}{x_{i+1} + x_{i+2}} \geqslant \geqslant \frac{1}{n} \sum_{i=1}^{n} g(y_i) \geqslant g\left(\frac{y_1 + y_2 + \ldots + y_n}{n}\right) = g(0).$$

This proves that $\gamma \geqslant g(0)$.

Further, with rather elegant explanations, it is proved that $g(0) = \gamma$.

Let the common tangent connect the points $(x_1; e^{-x_1})$ and $(x_2; 2\left(e^{\frac{x}{2}} + e^{x_2}\right)^{-1})$ (Fig. 2). The graph of the function $g$ consists of three parts: $y = e^{-x}$ at $x \geqslant x_1$, $y = 2\left(e^{x} + e^{\frac{x}{2}}\right)^{-1}$ at $x \leqslant x_2$ and their common tangent at $x_2 \leqslant x \leqslant x_1$. The ordinate of the point of intersection of the tangent with the ordinate axis is $\gamma$.
