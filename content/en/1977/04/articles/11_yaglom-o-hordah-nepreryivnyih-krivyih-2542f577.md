---
id: 1977-4-yaglom-o-hordah-nepreryivnyih-krivyih-2542f577
issue: kvant_1977_4
year: 1977
number: "4"
title: On chords of continuous curves
authors:
  - Яглом И. М.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 29
page_last: 31
page_labels: 27-29
tag: URYZ
lang: en
source: kvant_digital
extraction: vision
content_sha256: a9fd489527223d9f1d40b70c923ad1bfdfeb0f95d711959bc11e6f778ffef033
prompt_sha256: draft-1
translated_from: content/ru/1977/04/articles/11_yaglom-o-hordah-nepreryivnyih-krivyih-2542f577.md
source_content_sha256: 3e3855e871be06dab81fb35820f766db9cb05586e033c562c8a97014a9206beb
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 27⟧

On chords of continuous curves

Generalizing the concept of a chord of a circle, we will call a chord of an arbitrary curve α any segment whose ends belong to α. For example, for the curve α shown in figure 1, the chords are not only the segments PQ and RS, but also the segment TU, which is part of the curve α.

1. About problem M413

In this problem («Kvant», 1976, No. 11) we are presented to find out for which positive numbers α the following statement is true: for any function f defined on the interval [0, 1], continuous at each point of this interval and maximizing that f(0)=f(1)=0, the equation

$$f(x+a)-f(x)=0$$

(1) has a solution.

Let's solve it. Let us rewrite equation (1) in equal form

$$f(x+a)=f(x).$$

We believe (see the problem statement) that in equations (1), (2) a>0, and the function f is defined on the interval [0, 1], is continuous at each point of this interval and f(0)=f(1)=0.

The graph of α function f is a continuous curve connecting the points A〈0, 0〉 and B·〈1, 0〉. The graph β of the function y=f(x+a) is obtained by parallel transfer of the curve α along the abscissa axis to the left (since a>0) to a (Fig. 2).

The existence of a solution to equation (2) means that the graphs of α and β intersect: if f(x₀+a)=f(x₀)=y₀, then the point with coordinates〈x₀, y₀〉 belongs to both α and β (Fig. 3).

It turns out that in order for the curves α and β to intersect, it is necessary and sufficient that α has a chord of length a parallel to the abscissa axis. This statement follows from the following lemma (prove it yourself):

Lemma. Curve α, connecting points A and B,_MODEA and milk_MODEA have a parallel AB chord of length r, where the curve β, obtained from α by parallel translation in the direction of BA at a distance r, intersects with α.

Thus, we can “translate” problem M413 into the “language of chords”: we need to find out for what positive α the graph of any function f defined on the segment [0, 1] is continuous at each point of this segment and maximizing that f(0)=f(1)=0, we have a chord of length a parallel to the abscissa axis.

2. “Position” of the number: a≠1/n.

Let us show that for any positive α not equal to $\frac{1}{n}$ (n=1, 2, 3, 4, ...), there is a function of the described form, the graph of which does not have a chord of length a parallel to the x-axis.

Obviously, any such function for any chord CD of its graph parallel to the abscissa axis has |CD|≤|AB|=1 (Fig. 4). Therefore, we can assume that 0<a<1.

If $\frac{1}{2}<a<1$, draw through A and B any lines u₁||u₂ and through the midpoint R₁ of the segment AB - any line v₁ intersecting them. It is easy to see that the function f₂, whose graph is the broken line α₂=AP₁Q₁B (Fig. 5), is the desired one, since for any chord CD of its graph parallel to the abscissa axis, |CD|≤1.

Let now $\frac{1}{3}<a<\frac{1}{2}$. Let us divide the segment AB by points R₁, R₂ into three equal parts and, regardless of this, by point S₁—in half. Let's carry out

⟦folio 28⟧

through $A$, $S_1$ and $B$ any parallel lines $u_1 \parallel u_2 \parallel u_3$ and through $R_1$, $R_2$ any parallel lines $v_1 \parallel v_2$ intersecting them. The function $f_3$, whose graph is the broken line $\alpha_3 = AP_1Q_1P_2Q_2B$ (Fig. 6), is the required one: for any chord $CD$ of its graph, parallel to the x-axis, either $|CD| \leq \frac{1}{3}$ or $|CD| \geq \frac{1}{2}$. Indeed. If points $C$ and $D$ lie on adjacent links of the broken line $\alpha_3$ (i.e. on $AP_1$ and $P_1Q_1$ or on $P_1Q_1$ and $Q_1P_2$, etc.), then, obviously, $|CD| \leq \frac{1}{3}$. If points $C$ and $D$ lie “through one link”, then either $|CD| = \frac{1}{3}$ (when $C \in P_1Q_1$, $D \in P_2Q_2$) or $|CD| = \frac{1}{2}$. In other cases $|CD| > \frac{1}{2}$.

Similarly, we construct the broken line $\alpha_n$ (graph of the function $f_n$), connecting $A$ and $B$ and not containing any parallel to the abscissa axis of the chord $CD$ such that $\frac{1}{n} < |CD| < \frac{1}{n-1}$. Let us divide the segment $AB$ by points $R_1, R_2, \dots, R_{n-1}$ into $n$ equal parts and, regardless of this, by points $S_1, S_2, \dots, S_{n-2}$ into $n-1$ equal parts. Let us draw through $A, S_1, S_2, \dots, S_{n-2}$ and $B$ any parallel lines $u_1, u_2, \dots, u_n$ and through $R_1, R_2, \dots, R_{n-1}$ any parallel lines $v_1, v_2, \dots, v_{n-1}$ intersecting them. The broken line $\alpha_n = AP_1Q_1P_2Q_2 \dots P_{n-1}Q_{n-1}B$ (at figure 7 the broken line $\alpha_6$ is shown) is the required one. This is established again by enumerating various possible positions of points $C$ and $D$ (check!).

Condensation 1. Check that for $n = 2, 3, 4, \dots$ the graph of function $g_n$:
$$g_n(x) = \sin(2\pi(n-1)x)$$
on the segment $[0, 1]$ does not have a chord of length $\frac{1}{n} < a < \frac{1}{n-1}$ parallel to the x-axis. Draw this graph.

2. Prove that for any positive $a$ not equal to $\frac{1}{n}(n=1,2,3,4,\dots)$, the graph of the function $h_a$:
$$h_a(x) = \sin^2\left(\frac{\pi}{a}x\right) - \sin^2\left(\frac{\pi}{a}\right)x$$

⟦folio 29⟧

3. 《Good》numbers: $a = \frac{1}{n}$

We will prove that for $a = \frac{1}{n}$ ($n = 1, 2, 3, 4, \dots$) the graph of any function $f$ considered has a chord of length $a$ on the interval [0, 1] parallel to the abscissa axis.

Indeed: the path $M_0$ and $N_0$ are points on the graph of the function $f$, corresponding to the largest and smallest values ​​of this function. Let us draw through $M_0$ and $N_0$ the straight lines $m$ and $n$, parallel to the abscissa axes. It is clear that the entire graph of the function $f$ is located in the strip $\Delta$, bounded by the lines $m$ and $n$ (Fig. 8).

Let us now assume that the graph of the function $f$ does not have a chord of length $a = \frac{1}{n}$ parallel to the x-axis.

Let us denote by $\alpha_0$ the graph of the function $f$ under consideration, and by $\alpha_h$ the line obtained from $\alpha_0$ by parallel translation in the direction of the x-axis to the right at a distance $ka$ ($k = 1, 2, \dots, n$).

According to the lemma, the curves $\alpha_0$ and $\alpha_1$ have no common points. Arc $M_0N_0$ of graphics $\alpha_0$ (on figure 8 it is highlighted in bold) divides stripe $\Delta$ into two parts - right and left. Since the curve $\alpha_1$ does not intersect with $\alpha_0$ and is not interrupted, it is entirely located in the right of these parts.

Consequently, if $M_kN_k$ is the arc of the line $\alpha_k$, obtained from $M_0N_0$ by parallel transfer, then at $l > k$ the entire line $\alpha_l$ is located in the strip $\Delta$ to the right of the arc $M_kN_k$, and at $l < k$ - to the left of $M_kN_k$.

In particular, line $\alpha_0$ is located in strip $\Delta$ to the left of $M_1N_1$, and line $\alpha_n$ is located to the right of $M_1N_1$, and therefore

neither $\alpha_0$ and $\alpha_n$ have common points.

On the other hand, the line $\alpha_n$ is obtained from $\alpha_0$ by parallel translation to a distance $na = 1$. In this case, the transfer of point $A \in \alpha_0$ goes to point $B$, that is, $B \in \alpha_n$. Since, in addition, $B \in \alpha_0$, then the lines $\alpha_0$ and $\alpha_n$ have a common point.

The resulting contradiction proves that the line $\alpha_0$ has a chord of length $1/n$ parallel to the x-axis. Thus, the M413 problem is completely solved.

U pravanke 3. Prove that this statement (about the existence of a chord of length $1/n$, parallel to the abscissa axis) is true not only for the line $\alpha_0$, which is a graph and a function, but also for an arbitrary continuous curve connecting the points $A = < 0, 0>$ and $B = < 1, 0>$.

4. Generalization

The reasoning carried out in the previous paragraph can be interpreted as follows. Let $\alpha_0$ be an arbitrary continuous curve connecting the points $A$ and $B$. Let us assume that the number $a = \frac{1}{n}$ is “bad” for this curve, that is, when parallelly transferred to a distance $a$, the result is a line $\alpha_1$ that does not have common points with $\alpha_0$. Then the numbers $2a, \dots, na$ are also “bad” for the line $\alpha_0$, hence the contradiction that completes the proof.

The reader can independently verify (by repeating the same reasoning) that the following more general statement is true:

If a continuous curve $\alpha$ connecting $A$ and $B$ does not have a parallel AB chord of length $p$ and does not have a parallel AB chord of length $q$, then it also does not have a parallel AB chord of length $p + q$.
