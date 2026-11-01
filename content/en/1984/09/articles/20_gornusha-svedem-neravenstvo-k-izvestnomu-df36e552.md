---
id: 1984-9-gornusha-svedem-neravenstvo-k-izvestnomu-df36e552
issue: kvant_1984_9
year: 1984
number: "9"
title: Let's reduce the inequality to the known
authors:
  - Горнуша П. П.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 51
page_last: 53
page_labels: 49, 51
tag: 32W0
lang: en
source: kvant_digital
extraction: vision
content_sha256: b98f33f38c8962615684cdd6198fb7893a9eb93660630ea376e851f7e01e3716
prompt_sha256: draft-1
translated_from: content/ru/1984/09/articles/20_gornusha-svedem-neravenstvo-k-izvestnomu-df36e552.md
source_content_sha256: 9f61d923de9c94a6a6990d89885a65b59cfe8fd93b4c587caebf40ed6c739181
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 49⟧

Let's reduce the inequality to the known

P. P. GORNUSH

Many problems on proving inequalities offered in entrance exams can be solved, their properties to auxiliary inequalities (obvious or previously known) with the help of childhood transformation points. We will consider such problems here*). Auxiliary inequalities are highlighted in color, but not for memorization. You need to be able to use them (and put inequalities) and be able to derive them as needed.

Every schoolchild knows that the square of a number (or the sum of the squares of numbers) is a non-negative number:

$$a^2 \geq 0, a^2 + b^2 \geq 0, a^2 + b^2 + c^2 \geq 0, \dots$$

(1)

This simple fact is the key to solving many problems. Let's start with a very simple one.

Task 1 (KPI, 1981). Prove that for any real x, y, z, t the following inequality holds:

$$4x^2 + 3y^2 + 4z^2 + 5t^2 + 4ax + 3ay + 4az + 5at + 4a^2 \geq 0.$$

Solution. We rearrange the terms on the left side of the inequality to obtain the sum of squares:

$$(4x^2 + 4ax + a^2) + (3y^2 + 3ay + 3a^2/4) + (4z^2 + 4az + a^2) + (5t^2 + 5at + 5a^2/4) \geq 0,$$

$$(2x + a)^2 + 3(y + a/2)^2 + (2z + a)^2 + 5(t + a/2)^2 \geq 0.$$

*) Assignments offered in different years at Kiev, Leningrad and Moscow State Universities (KSU, Leningrad State University and Moscow State University); at the Moscow Institutes of Electronic Engineering and Automotive Engineering (MIEM, MATI) and at the Kiev Polytechnic Institute (KPI); We indicate the year in which the task was proposed next to the abbreviation of the university.

The last inequality is very similar (this is a variation of (1)), and since it is equivalent to the given one, it is a solution problem.

Inequality (1) suffers in many different areas; for example $(x + y + z)^2 \geq 0, (\sqrt{a} - \sqrt{b})^2 \geq 0, (t - 1)^2 \geq 0$. The penultimate inequality can be rewritten as $a + b > 2\sqrt{ab}$ (for $a > 0, b > 0, a \neq b$) or

$$\frac{1}{\sqrt{ab}} > \frac{2}{a + b}$$

(2)

It is important to be able to see this simple inequality when it appears in a “disguised” form, such as in the following problem.

Problem 2 (LSU, 1978). Determine the sign of the difference

$$\left( \frac{1}{\sqrt{1 \cdot 1978}} + \frac{1}{\sqrt{2 \cdot 1977}} + \dots + \frac{1}{\sqrt{k \cdot (1978 - k + 1)}} + \frac{1}{\sqrt{1978 \cdot 1}} \right) - 2 \cdot \frac{1978}{1979}.$$

Solution. Using inequality (2) 1978 times, we can write:

$$\frac{1}{\sqrt{1 \cdot 1978}} > \frac{2}{1 + 1978} = \frac{2}{1979};$$

$$\frac{1}{\sqrt{2 \cdot 1977}} > \frac{2}{2 + 1977} = \frac{2}{1979};$$

$$\frac{1}{\sqrt{1978 \cdot 1}} > \frac{2}{1978 + 1} = \frac{2}{1979}.$$

Adding these inequalities, we get

$$\frac{1}{\sqrt{1 \cdot 1978}} + \frac{1}{\sqrt{2 \cdot 1977}} + \dots + \frac{1}{\sqrt{k \cdot (1978 - k + 1)}} > 2 \cdot \frac{1978}{1979}.$$

This means that this difference is positive.

Here is another variation on the theme $(\sqrt{a} - \sqrt{b})^2 \geq 0$. Adding the expression $(\sqrt{a} + \sqrt{b})^2$ to both sides of this inequality, we obtain

$$(\sqrt{a} + \sqrt{b})^2 \leq (\sqrt{a} - \sqrt{b})^2 + (\sqrt{a} + \sqrt{b})^2 = 2(a + b),$$

⟦folio 51⟧

the solution to which is immediately found.
Answer: $p=3; t=\pi+2k\pi \ (k \in \mathbb{Z})$.
The monotonous decrease of xine from 0 to π is played out many times in the following problem (each time we use it, we see the corresponding inequality in color).
Problem 6 (MIEM, 1980). At $n=1, 2, 3$, compare numbers
$\sin^2 1^\circ + \sin^2 4^\circ$ and $\sin^2 2^\circ + \sin^2 3^\circ$.
Solution. 1) $n=1$. Let's transform the sum of sines into a product:
$\sin 1^\circ + \sin 4^\circ = 2 \sin 2, 5^\circ \cos 1, 5^\circ$,
$\sin 2^\circ + \sin 3^\circ = 2 \sin 2, 5^\circ \cos 0, 5^\circ$.
Now you can see that the second number is greater than the first, either $\sin 2, 5^\circ > 0$ and
$\cos 0, 5^\circ > \cos 1, 5^\circ$.
2) $n=2$. Let's express the square of the sine through the cosine of the double angle
$\sin^2 1^\circ + \sin^2 4^\circ = \frac{1-\cos 2^\circ}{2} + \frac{1-\cos 8^\circ}{2}$,
$\sin^2 2^\circ + \sin^2 3^\circ = \frac{1-\cos 4^\circ}{2} + \frac{1-\cos 6^\circ}{2}$.
Let us show that now the first number is larger. To do this, it is enough to establish the inequality
$\cos 4^\circ + \cos 6^\circ > \cos 2^\circ + \cos 8^\circ$,
and it is equivalent to inequality
$2 \cos 5^\circ \cos 1^\circ > 2 \cos 5^\circ \cos 3^\circ$,
which immediately follows from the fact that $\cos 5^\circ > 0$ and
$\cos 1^\circ > \cos 3^\circ$.
3) $n=3$. Let us show that here again the first number is greater. Let's use the formula
$\sin^3 \alpha = \frac{3 \sin \alpha - \sin 3 \alpha}{4}$, (6)
which is easy to check (expand $\sin 3\alpha$ as $\sin(2\alpha + \alpha)$, then apply the formulas for $\cos 2\alpha$ and $\sin 2\alpha$). Then the problem reduces to proving the (equivalent) inequalities
$\sin 9^\circ - \sin 3^\circ + \sin 6^\circ - \sin 12^\circ >$
$> 3 \sin 3^\circ - 3 \sin 1^\circ + 3 \sin 2^\circ - 3 \sin 4^\circ$;
$2 \cos 6^\circ \sin 3^\circ - 2 \cos 9^\circ \sin 3^\circ >$
$> 6 \cos 2^\circ \sin 1^\circ - 6 \cos 3^\circ \sin 1^\circ$;
$\sin 3^\circ \sin 7, 5^\circ \sin 1, 5^\circ >$
$> 3 \sin 1^\circ \sin 2, 5^\circ \sin 0, 5^\circ$.
Transforming the sines of triple angles on the left side according to formula (6) and using the positivity of $\sin 1^\circ$, $\sin 2, 5^\circ$, $\sin 0, 5^\circ$, we see that it is enough to prove the inequality
$(3 - 4 \sin^2 1^\circ) (3 - 4 \sin^2 2, 5^\circ) \times (3 - 4 \sin^2 0, 5^\circ) > 3,$
which transforms to the equivalent form
$(1 + 2 \cos 2^\circ) (1 + 2 \cos 5^\circ) \times (1 + 2 \cos 1^\circ) > 3,$
and this is conclusively true - the left side is even greater than 8, because
$\cos 1^\circ > \cos 2^\circ > \cos 5^\circ > \frac{1}{2}$.
Perhaps the analyzed examples are not correct - after all, before each problem, we were more satisfied with the inequalities that were being solved and looked at the results in its solution. The art and difficulty of solving such problems lies precisely in seeing the necessary inequality in the process of analyzing the problem. Therefore, we offer several tasks for you to solve on your own (the most difficult ones are marked with asterisks at the end of the data log). But before you begin to solve them, we advise you to look at similar examples again in order to understand how, based on their appearance, it was possible to solve the problem.

Tasks
7 (KPI, 1981). Find the smallest value of the expression
$x^2 + 4y^2 + 3z^2 + t^2 - 2x - 12y - 6z - 2t$
provided that $x, y, z$ and $t$ take any real values.
8 (KPI, 1981). Find the largest value of the function
$y = \frac{11}{2} - \frac{1}{2} \cos 4x - \frac{4 \mathrm{tg} x}{1 + \mathrm{tg}^2 x}$.
9 (MIEM, 1980). At $n=1, 2, 3$ compare numbers
$\cos^2 1^\circ + \cos^2 4^\circ$ and $\cos^2 2^\circ + \cos^2 3^\circ$.
10 (MSU, 1980). Prove that for any real $p$ and $q$ the following inequality holds:
$2(2p - 1)^4 + 1 + (1 - 2(2p - 1))^4 \sin 2t \geq 0$,
and find all pairs of numbers $(p, t)$ for which this inequality turns into an equality.
11* (KPI, 1976). Prove that the polynomial $a^4 - 5a^3 - 6a^2 - a + 9$
cannot have negative roots.
12* (MIEM, 1982). Which of the intervals [2; 3], [3,1; 3.3], [3.6; 4.5] belongs to the number
$a = \log_6 7 \sqrt[3]{6} - \log_7 \frac{1}{8 \sqrt[3]{49}} + \log_8 \frac{9}{8}$?
13 (MIEM, 1979). Arrange in number order
a) $0; \sqrt{0,8}; 1,2; \frac{11}{30}; 0,91846; \ln \frac{7}{5}$;
b) $1; 0,37; \frac{65}{63}; \frac{61}{59}; \tg 33^\circ; \tg(-314^\circ).$
