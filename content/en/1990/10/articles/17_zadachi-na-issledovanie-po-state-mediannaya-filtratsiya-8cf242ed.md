---
id: 1990-10-zadachi-na-issledovanie-po-state-mediannaya-filtratsiya-8cf242ed
issue: kvant_1990_10
year: 1990
number: "10"
title: Research tasks for the article “Median filtering”
rubric: raznoe
page_first: 49
page_last: 53
page_labels: 47, 49, 50, 51
lang: en
source: kvant_digital
extraction: vision
content_sha256: 8861d693f33c57c40a09b16f3f2c5130be7c9bc2d7c55f4c1aa51ca59d8cc2c2
prompt_sha256: draft-1
translated_from: content/ru/1990/10/articles/17_zadachi-na-issledovanie-po-state-mediannaya-filtratsiya-8cf242ed.md
source_content_sha256: 7afa5e2c26afc78614f40d6eb48de968140bb768500062c9e1feb19395669d7a
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 47⟧

Research task on the statistic “Median filtering”

(see p. 8)

1. Prove that if the sequence $x_n$ is invariant under a median filter with window width $2k+1$ and its terms take at least three different values, then it is invariant under any median filter with a smaller window width.

When marking e. The second condition is essential. For example, the “saw” $x_n=(-1)^n$ is invariant with respect to filters with even $k$ and non-invariant with respect to filters with odd $k$.

2. The finite sequence continues to the infinite by repeating the extreme elements to the left and right of the corresponding one. Prove that if the length of the sequence is $l$, then after $\left[\frac{l-1}{2}\right]$ applying the median filter with a window width $2k+1$, an invariant sequence is obtained (here [] is the integer part of the number).

Check that the way the sequence continues is significant (for example, at $l=2$).

3. A recursive median filter is a median filter in which the first $k$ numbers of the sliding window are taken from the filtered sequence, i.e. the sequence $x_n$ is transformed into a sequence $y_n=m(y_{n-k}, y_{n-k+1}, \dots, y_{n-1}x_n, x_{n+1}, \dots, x_{n+k})$ (it is considered that $x_n \equiv x_0$ when $n<0$).

a) Prove that a sequence is invariant under a recursive median filter if and only if it is invariant under a general median filter.

b) Prove that any sequence after passing through a recursive median filter once becomes invariant.

4. We will say that the sequence $x_n$ has a midpoint equal to $a$ if for any $\varepsilon>0$ there is a $M$ such that for any $n$ and $m>M$

$$|m(x_{n-m}, x_{n-m+1}, \dots, x_n, \dots, x_{n+m-1}, x_{n+m}) - a| < \varepsilon.$$

Prove that the median filter preserves the midpoint, i.e., the sequence obtained from $x_n$ at the filter's output has the same midpoint $a$.

5. We will say that the sequence $x_n$ has level $a$ if for any $\varepsilon>0$ there is a $M$ such that for any $n$ and $m>M$

$$|x_{n-m}+x_{n-m+1}+\dots+x_n+\dots+x_{n+m-1}+x_{n+m}| - a| < \varepsilon.$$

Is it true that a) median filter, b) sliding conditions preserve the level of consistency?

⟦folio 49⟧

---
running_head:
folio:
---

or analysis - who wins? And Yu. Nesterenko turned out to be a witness to this dispute. My opponents were ardent geometers, and I had to do it. But my rivals still did not win a clear victory. This is described in my book “Stories about Maximums and Minimums” (Library «Kvant», issue 56, M., Nauka, 1986, pp. 134-139). And then (as the author himself told me) Yu. Nesterenko began to look for a problem where geometric fantasy would triumph over analytical tediousness with a clear advantage. And he actually came up with it! The problem was presented at the 19th All-Union Olympiad for schoolchildren in 1985. Here is its wording.

Given a cube $ABCD_1B_1C_1D_1$ from side two. Let us draw two circles: one circumscribed around the triangle formed by non-adjacent vertices $AB_1C$, the other circumscribed into the face $ABCD$. It is required to find the minimum distance between these circles (Fig. 1).

And indeed - now we will see this - it can be solved “in two words”, but finding them is quite difficult (especially in the context of an Olympiad or an exam). We will touch on this interesting topic at the end of the article, and now let’s move on to the solution.

First, the pro-verbal “two words.” The small circle lies on a sphere of radius $\sqrt{2}$ with center at the center of the cube, the larger circle lies on a sphere of radius $\sqrt{3}$ with the same center, which means the shortest distance between the circles is not less than $\sqrt{3} - \sqrt{2}$. But the trace on the larger sphere of a cone with the apex in the center of a cube containing a small circle intersects (as is easy to understand) the larger circle (Fig. 2), i.e. there are two points on different circles, the distance between which is $\sqrt{3} - \sqrt{2}$.

This means that the minimum distance is equal to $\sqrt{3} - \sqrt{2}$! Everything has been proven. But, keeping in mind further comparisons, let’s describe these “two words” in a little more detail. So, we present two solutions for your consideration - geometric and analytical. To make it easier for you to compare the “advantages” and “disadvantages” of these solutions, we saw the main points in each of them (“moves”, “steps” - as you like) with a number in square brackets. If a move seems like an “insight” to us, we put it next to the number! (or even!!).

Solution of the first (geometric). We denote the circumscribed circle by $O_1$, the circumscribed circle by $O_2$, and the center of the cube by $O$. Then:

[1]. Circle $O_1$ lies on a sphere with center at $O$ and radius $\sqrt{3}$.
[2]. Circle $O_2$ lies on a sphere with center at $O$ and radius $\sqrt{2}$.
[3!]. From the above it follows that the required minimum distance is $\rho \geqslant \sqrt{3} - \sqrt{2}$.

Fig. 1.

Fig. 2.

⟦folio 50⟧

---
running_head:
folio:
---

[4]. Let us construct a conical surface with a vertex at the center $O$, connecting it with rays to the points of the circle $O_2$.

[5]. Then the generatrix of the cone—the ray $OU'$ (Fig. 2)—lies below $O_1$.

[6]. The generatrix of the cone $OV'$ (Fig. 2) lies above $O_1$ (easy counting).

[7!!]. From the last two statements and continuity messages it follows that the existing point $E$ on $O_2$ is such that the ray $OE$ “produces” the circle $O_1$ at the point $E'$,

[8] and therefore the distance from $E$ to $E'$ is equal to $\sqrt{3} - \sqrt{2}$, i.e. $\rho \leqslant \sqrt{3} - \sqrt{2}$.

[9]. Thus, $\rho = \sqrt{3} - \sqrt{2}$.

Wonderful red solution, isn't it? You would like it even more if you found it yourself. The number of people who solved this problem at the Olympiad was not so small - five to ten people - and they all solved it like this, geometrically. But we have a different path ahead of us.

But before moving on to a similar solution, I must introduce you to one very important method in analysis for studying the extremum problem, discovered by Lagrange (I devoted a significant part of my above-mentioned book to this method - see the story of the day). It was with the help of Lagrange that I stood up for part of the similar ones under certain conditions that connect the variables $x, y, z$, $u$. For example,

$$f_1(x, y, z, u) = 0,$$
$$f_2(x, y, z, u) = 0,$$
where $f_1$ and $f_2$ are function data.

Then (says Lagrange) the solution, if it exists, can be found using the following method.

Let $\lambda_0, \lambda_1$ and $\lambda_2$ be some (not yet known to us) numbers, not all equal to 0.

Consider the function

$$L = \lambda_0 f_0 + \lambda_1 f_1 + \lambda_2 f_2.$$

Let $L_x, L_y, L_z$ And $L_u$ - arbitrary function $L$ by variables $x, y, z, u$. Then point $(x_0, y_0, z_0, u_0)$, in which the minimum (maximum) of the function is achieved $f_0$, is given by the system of equations

$$\begin{cases} f_1(x, y, z, u) = 0, \\ f_2(x, y, z, u) = 0, \\ L_x = L_y = L_z = L_u = 0. \end{cases}$$

(Note that this is a system of 6 equations with 7 unknowns, from which the numbers are found $x_0, y_0, z_0, u_0$ And $\lambda_0, \lambda_1, \lambda_2$.)

This example is universal, technically very simple and for its application nothing is required except an arbitrary concept. Let's use it to solve our problem.

[1]. Circumference $O_2$ presents in the form $x = \cos \varphi, y = \sin \varphi, z = -1, -\pi \leqslant \varphi \leqslant \pi$.

[2]. Circumference $O_1$ set in the form of the intersection of a sphere $x^2 + y^2 + z^2 = 3$ and planes $x - y + z = -1$.

$$f_0(x, y, z, \varphi) = (x - \cos \varphi)^2 + (y - \sin \varphi)^2 + (z + 1)^2$$

$$f_1(x, y, z) = x - y + z + 1 = 0,$$
$$f_2(x, y, z) = x^2 + y^2 + z^2 - 3 = 0.$$

[4]. It is easy to understand that it is enough to consider the sector $-\frac{\pi}{2} \leqslant \varphi \leqslant \frac{\pi}{2}$.

[5]. Let's construct the Lagrange function

$$L = \lambda_0 ((x - \cos \varphi)^2 + (y - \sin \varphi)^2 + (z + 1)^2) + \lambda_1 (x - y + z + 1) + \lambda_2 (x^2 + y^2 + z^2 - 3)$$

and calculate its arbitrary ones:

$$L_\varphi = 2\lambda_0 ((x - \cos \varphi) \sin \varphi) - (y - \sin \varphi) \cos \varphi) = 0,$$

$$L_x = 2\lambda_0 (x - \cos \varphi) + \lambda_1 + 2\lambda_2 x = 0,$$

$$L_y = 2\lambda_0 (y - \sin \varphi) - \lambda_1 + 2\lambda_2 y = 0,$$

$$L_z = 2\lambda_0 (z + 1) + \lambda_1 + 2\lambda_2 z = 0.$$

⟦folio 51⟧

---
running_head:
folio:
---

[6]. Now let's solve the resulting system (1) - (4). If we assume that $\lambda_0 = 0$, then from (2) - (4) and the coupling equation we obtain that $\lambda_1 = \lambda_2 = 0$, and this contradicts the assumption that $\lambda_0^2 + \lambda_1^2 + \lambda_2^2 \neq 0$.

It is clear that the numbers $\lambda_0, \lambda_1, \lambda_2$ can be determined up to proportionality, so we assume $\lambda_0 = \frac{1}{2}$. Then from (1) it follows
$$x \sin \varphi = y \cos \varphi.$$ (5)

Denoting $a = -\frac{\lambda_1}{1+2\lambda_2}$, $b = \frac{\lambda_1}{1+2\lambda_2}$ (assumption $1+2\lambda_2=0$ leads to a very low-weight system), we obtain
$$x = a + b \cos \varphi, y = -a + b \sin \varphi, z = a - b.$$ (6)

[7]. From (6) and (5) it immediately follows that $a(\cos \varphi - \sin \varphi) = 0$, and this leads to the alternative
$$i) a = 0, (ii) \sin^2 \varphi + \cos \varphi = 0 (\Leftrightarrow \varphi = -\frac{\pi}{4}).$$ (7)

[8]. If (i), then from (6) (for $a=0$) and $x^2+y^2+z^2=3$ we obtain
$$b^2(\cos^2 \varphi + \sin^2 \varphi + 1) = 3 \Rightarrow b = \pm \sqrt{\frac{3}{2}}.$$ (8)

[9]. If (ii), then (easy to calculate)
$$(x_0, y_0, z_0) = \left( \frac{1}{3}, -\frac{1}{3}, \frac{5}{3} \right).$$ (9)

[10]. In case (i)
$$(x - \cos \varphi)^2 + (y - \sin \varphi)^2 + (z + 1)^2 = (b - 1)^2(\cos^2 \varphi + \sin^2 \varphi + 1) = (\sqrt{3} - \sqrt{2})^2.$$

[11]. In case (ii), the distance between points $\left( \frac{1}{\sqrt{2}}, -\frac{1}{\sqrt{2}}, -1 \right)$ and $\left( \frac{1}{3}, -\frac{1}{3}, \frac{5}{3} \right)$ is greater than $\sqrt{3} - \sqrt{2}$. Answer: $\rho = \sqrt{3} - \sqrt{2}$.

Well, now let’s philosophize a little. We touched on two topics: 1) who will win? and 2) are there problems that have a simple solution that is nevertheless very difficult to find?

So is the solution already beautiful? There can be no doubt about it, and I will immediately become one millionth winner. But may I be allowed, having humbly accepted my defeat, to still say a few words.

First of all, I ask you to pay attention, my dear friends (or judges?), to the fact that I not only found the answer, but also received the solution. Indeed, in case (i), which led us to the answer, from correspondences (2) - (4) for $a=0$ and from the expression for $b$, we obtain that $\cos \varphi - \sin \varphi = 1 - \sqrt{\frac{2}{3}}$, from which the desired $\varphi$ is immediately found. And you, dear geometers, still have to work a little. But that's true, by the way.

Secondly, I want to give the analysis credit for the fact that there are no exclamation marks in the analysis of the solution. “How is this?” - you ask. Remember: - I used exclamation marks (as in a chess game) to indicate especially beautiful, unexpected moves. So, I give analysis credit for precisely the fact that it made it possible to arrive at the goal in a standard, routine way, without any “revelation.” True, it’s a little longer (eleven moves instead of eight, but a lot of trivial, standard, completely elementary). And this path was, mind you, universal. After all, if you slightly change the problem, then it would happen that you, my dear geometer, would again be forced to wait for inspiration, and the standard road (maybe with the help of a computer) would definitely lead to the goal. However, mind me: why am I suddenly starting to wonder. The dispute is not over, it cannot be over! The next move is yours, my dear geometry fan!

Now - about the second topic. Yes, as it turns out, there are problems with very simple solutions, which are extremely difficult to find. We are discussing - from among them (if we do not assume the possibility of an analytical approach). A characteristic feature of such tasks is the presence of “exclamation marks”. If we break down the evidence of most

(For the ending see p. 62)
