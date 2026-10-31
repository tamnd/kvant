---
id: 1976-5-resheniya-zadach-m340-m342-1833175c
issue: kvant_1976_5
year: 1976
number: "5"
title: Solutions to problems M340—M342
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 52
page_last: 57
page_labels: 50, 52, 54, 55
tag: 4N5Y
lang: en
source: kvant_digital
extraction: vision
content_sha256: 43997ed77dfd2f9f035d5b916ae5e4d68b3619a235a8fa7bebc1b1bbc9e31e22
prompt_sha256: draft-1
translated_from: content/ru/1976/05/articles/11_resheniya-zadach-m340-m342-1833175c.md
source_content_sha256: c42f6c2fdc31330db3d2fbad3224515ae9367c6b3067b3febe80970e167628d6
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 50⟧

Xia of the atom (this phenomenon is called the Doppler phenomenon). As a result, due to the thermal motion of atoms, the spectral lines become broadened. Estimate the temperature of Ne atoms, knowing that a red line of frequency $f_0 = 4,8 \cdot 10^{14} \text{ e} \mu$, the width of which is $\Delta f = 1,6 \cdot 10^9 \text{ e} \mu$, is detected in its emission spectrum.

S. Kozel

F394. The design of a routine medical thermometer is shown in figure 3. A thin capillary is soldered to a can of rue, at the bottom of which there is an “overload” - a section with a diameter of approximately 30 microns. What role does this overload play? Estimate what acceleration must be imparted to the thermometer in order to “shake it off” after measuring the temperature.

F395. Why does measuring temperature with a medical thermometer take a long time (about 10 minutes), but you can “shake off” the thermometer almost immediately after measuring the temperature?

G. Kosourov

F396. A vessel of varying diameter is immersed upward in a vessel directed by water, motionlessly attached to a large vessel and partially filled with water (Fig. 4). A piece of ice floats on the surface of the water inside the changing vessel. What happens to the water levels in the vessels when the ice melts? How will the answer change if the changing vessel is not attached to the larger one and floats on the surface of the water?

A. Glinsky

F397. There is the following project of a flying machine. The upper surface of a large flat plate is maintained at a constant temperature $0 \text{ °C}$, and the lower surface at a constant temperature $100 \text{ °C}$. The inventor claims that such a plate will float in the air like an airship. Explain why? Estimate the order of magnitude of the lifting force of such a plate with area $1 \text{ m}^2$ at air temperature $20 \text{ °C}$.

Problem solutions

M340—M342

M340. A real number is written in each cell of a rectilinear mabiliza. A certain cell of a mabiliza is called its saddle cell if the number in it is not less than the other numbers in its number and not more than the main one.

a) Let the table have dimensions $m \times n$ and $m \geq n$ (rows no longer than 100 cm long). Let us select the maximum element in each column. The average of such elements is minimal. It is possible that in this way we will define not one element, but several (equal to each other). Let's mark them with crosses. The distance from any of the elements marked with a cross is $c_{ij}$, located in the $i$th line and $j$th column. If it is minimal in its row, then cell $(i, j)$ is the desired one. Otherwise

⟦folio 52⟧

> $\frac{\alpha}{\beta}; 2^\circ$ from $\frac{\alpha_1}{\beta_1} < \frac{\alpha}{\beta}, \frac{\alpha_2}{\beta_2} < \frac{\alpha}{\beta}$ it follows that $\frac{\alpha_1 + \alpha_2}{\beta_1 + \beta_2} < \frac{\alpha}{\beta}$ (see Fig. 3). That's why

$$\frac{a_{i_1} + b_{j_1}}{p_{i_1} + q_{j_1}} > \frac{a_{i_1} + a_{i_2} + b_{j_1} + b_{j_2}}{p_{i_1} + p_{i_2} + q_{j_1} + q_{j_2}},$$

$$\frac{a_{i_2} + b_{j_2}}{p_{i_2} + q_{j_2}} > \frac{a_{i_1} + a_{i_2} + b_{j_1} + b_{j_2}}{p_{i_1} + p_{i_2} + q_{j_1} + q_{j_2}},$$

and that means

$$\frac{a_{i_1} + a_{i_2} + b_{j_1} + b_{j_2}}{p_{i_1} + p_{i_2} + q_{j_1} + q_{j_2}} > \frac{a_{i_1} + a_{i_2} + b_{j_1} + b_{j_2}}{p_{i_1} + p_{i_2} + q_{j_1} + q_{j_2}},$$

which is impossible. A contradiction has been obtained. Consequently, any table $2 \times 2$ has a saddle cell, and the statement of problem 6) follows from point a).

L. Leemans

Let us give one more proof of point 6), independent of a).

Let's consider two functions:

$$f(t) = \max_i (a_i - p_i t),$$

And

$$g(t) = \max_j (q_j t - b_j),$$

defined for all $t$. (Such functions are called piecewise linear; their graphs are broken lines.) The function $f$ is strictly killing, and the function $g$ is strictly increasing (since the numbers $p_i$ and $q_j$ are positive). Therefore, there is a number $t_0$ such that $f(t_0) = g(t_0)$ — Fig. 4.

Let us show that this number $t_0$ is an element of our table. Indeed, for some indices $i_0, j_0$ we have:

$$a_{i_0} - p_{i_0} t_0 = q_{j_0} t_0 - b_{j_0},$$

where

$$t_0 = \frac{a_{i_0} + b_{j_0}}{p_{i_0} + q_{j_0}}.$$

Let us prove that this element $t_0$ is a saddle element for our table. From the definition of function $f$ it follows that

$$a_i - p_i t_0 \leq a_{i_0} - p_{i_0} t_0 = q_{j_0} t_0 - b_{j_0},$$

and, therefore,

$$t_0 \geq \frac{a_i + b_{j_0}}{p_i + q_{j_0}},$$

i.e. the element $t_0$ is not less than the numbers in the same column with it (with the number $j_0$). And from the definition of the function $g$ it follows that

$$q_j t_0 - b_j \leq q_{j_0} t_0 - b_{j_0} = a_{i_0} - p_{i_0} t_0,$$

where

$$t_0 \leq \frac{a_{i_0} + b_{j_0}}{p_{i_0} + q_{j_0}},$$

i.e. the element $t_0$ is no greater than the numbers on the same line with it (with the number $i_0$). The proof is legal.

N. Vasiliev

⟦folio 54⟧

Fig. 7. Volleyball championship $n=8$, $k=3$. Teams 6, 7, 8 are European; Euro champion - team 6. Added teams $A$ and $B$.

Fig. 8. a) European teams - 5 and 6. Euro champion - team 5. b) European teams - 4 and 5. Euro champion - team 4.

For $l \geq 4$, the most integer value of $k$ that satisfies (3) is equal to $2l-5$; indeed, for $k=2l-5$ the inequality is valid, and for $k \geq 2l-4$ its left-hand side is positive (make sure of this).

If $l=3$, then from (3) we obtain $k^2-k-2 \leq 0$, i.e. $k \leq 2$.

If $l=2$, then $k^2+k-2 \leq 0$ and $k \leq 1$.

Since $2l-5=n-5$ for even $n$ and $2l-5=n-4$ for odd $n$, we can write the results as follows:

1) $k \leq n-4$ if $n \geq 7$ and $n$ are odd;
2) $k \leq n-5$ if $n \geq 8$ and $n$ are odd;
3) $k \leq 2$ if $n=6$ and $n=5$;
4) $k \leq 1$ if $n=4$ and $n=3$.

Now we will prove that in all the obtained inequalities it is possible to achieve equality.

Let's start with cases 1) and 2).

Figures 6 and 7 show examples of tour tables for the case $n=7$ and $k=3$; $n=8$ and $k=3$; these tables will serve as the beginning of the induction.

We carry out further constructions according to indications, sequentially adding two European teams.

Note, first of all, that for $k=2l-5$ $x=y=l-2$ is indispensable.

Indeed (see (2')), $y \geq \frac{(k-1)(k+2)}{2k}$, i.e.

$y \geq \frac{k}{2} + \frac{1}{2} - \frac{1}{2k}$, or $y \geq l-2 - \frac{1}{2(2l-5)}$,

and since $l \geq 4$ and $y$ are integers, then $y \geq l-2$, whence $y=x=l-2$.

This means that our Euros champion will definitely lose everything to non-European teams.

Let's say that in a tournament of $n=2l$ teams, the first 5 teams are non-European, the rest $n-5$ are European, and the Euro champion took last place.

Let's add two more European teams - $(n+1)$ - the 1st team $A$ and the $(n+2)$ team $B$.

We will assume that team $A$ wins against the 1st, 3rd, ..., $(n-1)$ teams, loses to the others and wins against $B$.

Team $B$ wins against 2nd, 4th,..., $n$th and loses to the rest.

As a result, each of the $n$ first teams receives one more point, so their relative position in the standings does not change.

The Euro champion now has $l-1$ points, the team has $A-l+1$ points; The team has $B-l$ points, so the “old” Europa champion remains in last place.

In games with European teams, team $A$ receives $l-2$ points ($l-3$ points in games with “old” teams and one point in games with team $B$).

Team $B$ will score $l-2$ points in games with European teams, so the “old” Euro champion will retain its value.

If $n=2l-1$ is odd, the reasoning is similar to the wave, only you need to assume that team $B$ wins over $A$ (do the proof yourself).

With $n=6$ and $n=5$ it is easy to construct examples with $k=2$ (Fig. 8, a and b). The cases of $n=4$ and $n=3$ are trivial.

A. Egorov

⟦folio 55⟧

M342. a) Prove that from the digits 1 and 2 it is possible to form $2^{n+1}$ numbers, each of which is $2^n$-digit and each two of which differ in at least $2^{n-1}$ digits.

6) Prove that it is impossible to form more than $2^{n+1}$ maximum $2^n$-digit numbers.

Fig. 9.

We will solve this problem using the method of mathematical induction. Base and indexes. With $n = 1$, every two of the four two-digit numbers 11, 12, 21, 22 differ in at least one digit.

Step of induction Let us assume that $2^{n+1}$ numbers are made up of ones and twos, each of which is $2^n$-digit and each two of which differs in at least $2^{n-1} \times$ digits. Let's make a table $A$ of size $2^{n+1} \times 2^n$ from these numbers (the rows of the table are the numbers themselves, the columns are the digits of the numbers). Let us assign to each number $a$ of the table $A$ on the right the same number $a$; the resulting $2^{n+1}$ numbers, each of which is already $2^{n+1}$-digit, form the table $AA$. Then to each number $a$ of the table $A$ we will add the opposite number $a$ to the right (we will replace ones with twos, and twos with ones).

Consider a table of size $2^{n+2} \times 2^{n+1}$ (see Fig. 9), the rows of which contain $2^{n+2}$ numbers, each of which is $2^{n+1}$-valued. Let us prove that every two of these numbers differ by at least $2^n$ digits.

In fact, by the induction hypothesis, any two numbers taken from the upper “half” of our table (part $AA$) differ in at least $2 \cdot 2^{n-1} = 2^n$ digits. Tono, any two numbers taken from the “lower” half of the table (from part $A\bar{A}$, since the numbers from table $\bar{A}$ differ in exactly the same digits as the corresponding numbers from table $A$) also differ. If we take two numbers from different “halves” of the table - $aa$ from the top and $b\bar{b}$ from the bottom, then they will differ exactly in $2^n$ digits: if the numbers $a$ and $b$ differ in $k$ digits, then the numbers $a$ and $b$ differ in the rest $2^n - k$ digits.

6) Let's assume the opposite: let's say we managed to compose $2^{n+1} + 1$ the number as required in the problem. Then among them there are $2^n + 1$ numbers with the same first digit. Let's look at these numbers.

In each of the remaining $2^n - 1$ digits at least $2^{n-2}$ pairs of these numbers match. Indeed, if in some rank (over all these numbers) there are $2^{n-1} - k$ ones ($k \ge 0$) and $2^{n-1} + k + 1$ twos (in total there are $2^n + 1$ numbers), then the number of matches is equal to

$$C_{2n-1}^{2} + C_{2n-1}^{2} + k + 1 = 2^{2n-2} + k^2 + k \ge 2^{2n-2}.$$

Thus, the number of $N$ matches in all digits is at least

$$C_{2n+1}^{2} + (2^n - 1)2^{2n-2} = 2^{3n-2} + 2^{n-2} + 2^{n-1}.$$

On the other hand, if each of the $2^n + 1$ numbers under consideration differs in at least $2^{n-1}$ digits, then there are no more matches

$$C_{2n+1}^{2} \cdot 2^{n-1} = 2^{3n-2} + 2^{2n-2}.$$

Since (1) is greater than (2), we have come to the opposite, which is what was required.

For those who are familiar with the understandable multidimensional inclusion space, we present an outline of another proof. Let us replace “twos” in the condition with “minus ones”. Theler's statement of the problem follows from a general fact, which is easy to prove by induction on $k$: among the $(2k + 1)$ $k$-dimensional vectors there are two with a non-negative scalar product.

I. Klumova,
S. Fomin
