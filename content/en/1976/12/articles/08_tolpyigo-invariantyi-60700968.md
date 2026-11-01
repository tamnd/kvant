---
id: 1976-12-tolpyigo-invariantyi-60700968
issue: kvant_1976_12
year: 1976
number: "12"
title: Invariants
authors:
  - Толпыго А. К.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 21
page_last: 26
page_labels: 19, 21, 22, 24
tag: HIKB
lang: en
source: kvant_digital
extraction: vision
content_sha256: 5f7e6d7481d1f3fed11ec816beef2f30eca3925f47a559e5ee81b3c71dc8b39b
prompt_sha256: draft-1
translated_from: content/ru/1976/12/articles/08_tolpyigo-invariantyi-60700968.md
source_content_sha256: af98cfd9d62726e3b76cf52876b7f030bad5ac662d26ebb4f54d3cfbe8a4c02b
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 19⟧

Invariants

In «Kvant» it was already written about solving the problem using the selection of an invariant (1976, No. 2, p. 32). This article discusses the concept of an invariant and a number of possible questions in connection with it.

1. General statement of the problem

With the help of invariants, problems of the following type are solved: the data of the set $M$ (we will call its elements “positions”) and the rules by which we move from one position to another; Is it possible to move from a given position $\alpha$ in a few steps to another given position $\beta$? A more general problem: how can we determine for an arbitrary pair of positions $\alpha$, $\beta$ whether it is possible to go from $\alpha$ to $\beta$ in several steps?

Obviously, the described situations have the following property: if from position $\alpha$ one can go to position $\beta$ and from $\beta$ one can go to position $\gamma$, then from $\alpha$ one can go to $\gamma$. This property is called transiminity.

Let's consider a specific task.

Problem 1. The circle is divided into sectors in which $n$ chips are somehow considered. It is possible to simultaneously move any two chips: one - one sector clockwise, the other - one sector in the opposite direction. Is it possible to move from position $\mu$, in which there is one chip in each sector, from position $\alpha$ to any other position belonging to the same

*) «Kvant», 1972, № 2, c. 2.

⟦folio 21⟧

The point is that if $f$ is an invariant, then, generally speaking, nothing follows from $f(\alpha) = f(\beta)$. If $f(\alpha) \neq f(\beta)$, then the positions $\alpha$ and $\beta$ are not equivalent (this follows from (1)). If $f(\alpha) = f(\beta)$, then the positions $\alpha$ and $\beta$ can be either equivalent or non-equivalent: the invariant is not prohibited from taking the same values ​​on different orbits. (For example, a constant function, i.e. a function that takes the same value on all elements from $M$, is also invariant.)

How can this be? Try for each $n$ type 4 $k$ to move from position $\mu$ to position $v$... For some reason it doesn’t work. Let's try to find another, more subtle invariant.

Zanuterum sectors (say, clockwise) from 1 to $n$. For an arbitrary arrangement of $\alpha$ fizek in sectors, let us denote by $a_k(\alpha)$ the number of fizek in the $k$-th sector with the arrangement $\alpha$. Let us now consider the following function $q$:
$$q(\alpha) = 1 \cdot a_1(\alpha) + 2 \cdot a_2(\alpha) + 3 \cdot a_3(\alpha) + \dots + n \cdot a_n(\alpha).$$

Is the function $q$ invariant? An arbitrary permissible movement (Fig. 5) affects 4 terms of the sum (2):
$$\dots + i \cdot a_i(\alpha) + (i + 1) \cdot a_{i+1}(\alpha) + \dots + (j - 1) \cdot a_{j-1}(\alpha) + j \cdot a_j(\alpha) + \dots$$

With the movement depicted at figure 5, the sum (3) turns, very indo, into the sum
$$\dots + i \cdot [a_i(\alpha) - 1] + (i + 1) \cdot [a_{i+1}(\alpha) + 1] + \dots + (j - 1) \cdot [a_{j-1}(\alpha) + 1] + j \cdot [a_j(\alpha) - 1] + \dots$$

It is easy to check that both sums are equal. So, $q$ is an invariant! No, we stated that the $n$th sector borders the first. This means there are 3 more possibilities (Fig. 6-8). A calculation similar to that just made shows that in the case shown in Fig. 6, $q(\alpha)$ will decrease by $n$, and in the case of figure 7 it will increase by $n$. In the third case, $q(\alpha)$, of course, will not change. So, in one move the value of the function $q$ can change, but only by $n$. Sledova-

⟦folio 22⟧

Hence, $q(v) = l \cdot n$ and $r(v) = 0$ (whatever $n$ and $l$ are). On the other side,
$$a_1(\mu) = a_2(\mu) = \dots = a_n(\mu) = 1.$$
Means,
$$q(\mu) = 1 + 2 + 3 + \dots + n = \frac{n(n+1)}{2}.$$
If $n = 2m$, then $q(\mu) = n \cdot m + m$ and $r(\mu) = m \neq 0$. Therefore, if $n$ is even, we get $r(\mu) \neq r(v)$. So, for even $n$, the positions $\mu$ and $v$ are not equivalent.
If $n = 2m + 1$, then $q(\mu) = n \cdot (m+1)$ and $r(\mu) = 0$. Thus, for even $n$ we again have: $r(\mu) - r(v)$. It turns out that for even $n$ the question of the equivalence of positions $\mu$ and $v$ again remains open.

3. Universal invarant

Let us call the invarant $f$ universal if it takes different values ​​at non-equivalent positions:
if $\alpha \neq \beta$, then $f(\alpha) \neq f(\beta)$.
Thus, for the universal invarant $f$
if $f(\alpha) = f(\beta)$, then $\alpha \sim \beta$.
The universal invarant takes on its own value on each orbit. Since for a universal invariant
$$\alpha \sim \beta \iff f(\alpha) = f(\beta),$$
a universal invarant for any pair of positions allows us to establish whether they are equivalent or not.
How to check that the neokot invarant $f$ is universal? There is no general method. The following simple theorem can help.
If $a)$ there are positions $\delta_1, \delta_2, \dots, \delta_l$ such that each position $\alpha \in M$ is equivalent to one of them and the $b)$ invarant $f$ takes at least $l$ different values, then $f$ is a universal invarant and positions $\delta_i, \delta_j (i \neq j)$ are not pairwise equivalent.
From $a)$ it follows that there are at most $l$ orbits. From $b)$ it follows that there are at least $l$ orbits. Therefore, there are exactly $l$ orbits. Again from $b)$ it now follows that the invarant $f$ takes exactly $l$ values ​​and values, $f$ is universal. Finally, from $a)$ it follows that the positions $\delta_1, \delta_2, \dots, \delta_l$ take different orbits and, thus, are not pairwise equivalent.

Task 1 (end). Let us prove that the invarant $r$ is universal. Let us denote by $\delta_i$ the following arrangement of physics: one physic is in the $i$ sector, all the rest are in the $n$ sector. Under $\delta_n$ we will, of course, pair the arrangement in which all $n$ physicals are in the $n$ sector.

It is easy to report that any arrangement is equivalent to one of the positions $\delta_1, \delta_2, \dots, \delta_n$. In fact, $a$ is empty - an arbitrary arrangement of physical units. Let's try to collect all the $n$ physical units in the $n$ sector. To do this, we will turn the first fizek until we drive it into the $n$-th sector; at the same time, in accordance with the rules, we will move the second fizek in the opposite direction. Then we will drive the second fizek into the $n$th sector, moving the third fizek in the opposite direction, and so on - up to the $(n-1)$th fizek. When we drive the $n-1$ physical into the $n$ sector, the $n$ physical will be in some $i$ sector $(i=1, 2, \dots, n)$. This means that $\alpha \sim \delta_i$.

Let's count $r(\delta_i)$. At $i \neq n$:
$$\begin{cases} a_1(\delta_i) = a_2(\delta_i) = \dots = a_{i-1}(\delta_i) = \\ = a_{i+1}(\delta_i) = \dots = a_{n-1}(\delta_i) = 0, \\ a_i(\delta_i) = 1, \\ a_n(\delta_i) = n-1. \end{cases}$$
Therefore, $q(\delta_i) = i \cdot 1 + n \cdot (n-1)$ and $r(\delta_i) = i$. Also, $q(\delta_n) = n \cdot n$ and $r(\delta_n) = 0$. So the invarant $r$ takes at least $n$ values.

By the theorem, the invarant $r$ is universal and the positions $\delta_1, \delta_2, \dots, \delta_n$ are not pairwise equivalent.

Since $r$ is a universal invarant,
$$\alpha \sim \beta \iff r(\alpha) = r(\beta).$$

⟦folio 24⟧

take place simultaneously if and only if the positions α and β are equivalent.

What is the essence of this definition? If the positions α and β are equivalent, then, since $f_1, f_2, \dots, f_k$ are invariants, each of the equalities of system (5) is still satisfied. “In this direction” the canvas has nothing to do with it. If the invariants $f_1, f_2, \dots, f_k$ were universal, then the equivalence of the positions α and β would follow from any equality of system (5). We are not given their universal, but then it is required that the simultaneous execution of system (5) inflects the position of α and β. This is precisely the essence of the concept of the canvas. Thus, although some of the invariants $f_1, f_2, \dots, f_k$ can take the same value at non-equivalent positions α, β, the values ​​of the set $\langle f_1, f_2, \dots, f_k \rangle$ on them are different.

A complete system of invariants is a generalization of the concept of a universal invariant: if $f$ is a universal invariant, then the system $\langle f \rangle$, consisting of one invariant, is of course complete.

Problem 3. Integers are written in a 2x2 table. It is allowed, firstly, in any table simultaneous: add 2 to one number, derive 2 from another, and secondly, simultaneously in any row: add 3 to one number, derive 3 from another. Which tables are equivalent?

Let's consider three functions: for any table

$$\alpha = \begin{pmatrix} a & b \\ c & d \end{pmatrix}$$

let us denote by $p(\alpha)$ the sum $a + b + c + d$, by $q(\alpha)$ the remainder of the number $a + b$ divided by 2, and by $r(\alpha)$ the remainder of the number $a + c$ divided by 3. The functions $p, q, r$ are invariants. It is not very difficult to prove that an arbitrary table α is equivalent to the table

$$\begin{pmatrix} 0 & q(\alpha) \\ r(\alpha) & p(\alpha) - q(\alpha) - r(\alpha) \end{pmatrix}.$$

Therefore, from the equalities

$$\begin{cases} p(\alpha) = p(\beta), \\ q(\alpha) = q(\beta), \\ r(\alpha) = r(\beta) \end{cases}$$

(6)

it follows that tables α and β are equivalent to the same table and, therefore, equivalent to each other. And conversely: the equivalence of tables α and β is equality (6), since $p, q$ and $r$ are invariants. Thus, $\langle p, q, r \rangle$ is a complete system.

Rule 8. Solve the problem for the table $n \times n$, in which the same transformations are allowed as in Problem 3. It is natural to expect a complete system of 2$n$-1 invariants.

Rule 9. If $f_1, f_2, \dots, f_k$ are invariants and $g$ is a numerical function of $k$ arguments, then the function $h$:

$$h(\alpha) = g(f_1(\alpha), f_2(\alpha), \dots, f_k(\alpha))$$

(7) is an invariant (cf. Exercise 2). Check it out.

Rule 10. If $h$ is an invariant and $\langle f_1, f_2, \dots, f_k \rangle$ is a complete system of invariants, then there is also a numerical function $g$ of $k$ arguments, which satisfies (7) (cf. Exercise 3). Prove it.

Rule 11. The set $M$ is the set of points of the number plane, that is, the set of pairs $\langle x, y \rangle$ of real numbers. The only valid transition is $\langle x, y \rightarrow \langle y, x \rangle$. Let

$$\begin{cases} f_1(x, y) = xy, \\ f_2(x, y) = x + y. \end{cases}$$

Prove that $\langle f_1, f_2 \rangle$ is a complete system of invariants.

Rule 12. The set $M$ is a set of points in space or a set of tracks $\langle x, y, z \rangle$ of real numbers. Transitions $\langle x, y, z \rightarrow \langle y, x, z \rangle$ and $\langle x, y, z \rightarrow \langle x, z, y \rangle$ are allowed. Let

$$f_1(x, y, z) = xyz,$$

$$f_2(x, y, z) = xy + yz + zx,$$

$$f_3(x, y, z) = x + y + z.$$

Prove that $\langle f_1, f_2, f_3 \rangle$ is a complete system of invariants.

Rule 13. The set $M$ consists of all possible sets (or tuples) $\langle x_1, x_2, x_3, \dots, x_n \rangle$ of real numbers (n is fixed). It is allowed to swap places of any two adjacent numbers. Find a complete system of invariants.
