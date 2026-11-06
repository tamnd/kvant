---
id: 1990-12-resheniya-zadach-m1231-m1235-f1243-f1247-363cace5
issue: kvant_1990_12
year: 1990
number: "12"
title: Solutions to problems M1231—M1235; F1243—F1247
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 23
page_last: 31
page_labels: 21-29
lang: en
source: kvant_digital
extraction: vision
content_sha256: 344196de5aef6ac0fb77ae639bb158a7e4101f040cce3750f857ffde7447f820
prompt_sha256: draft-1
translated_from: content/ru/1990/12/articles/07_resheniya-zadach-m1231-m1235-f1243-f1247-363cace5.md
source_content_sha256: f2fd08628350eca40d13af97803e0a108eb162a8dc4b21e113e5ed8bd4dc000d
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 21⟧

Problem solutions

M1231 — M1235, F1243 — F1247

M1231. What is the maximum number of parts that the graphs $n$ of square trinomials of the form $y = ax^2 + bx + c$ ($n=1, 2, 3, \dots$) can divide the Oxy plane?

Answer: $n^2 + 1$.
Let us prove by induction that the number of parts does not exceed $n^2 + 1$. For $n=1$ this is clear: the parabola divides the plane into at most $(n-1)^2 + 1$ parts. Let's run the last, $n$-th chart. It intersects with each of the $n-1$ previous maxima at two points, i.e. it will be divided into no more than $2(n-1)+1=2n+1$ pieces (including the two extreme ones that go to infinity). Each of these pieces of parabolas divides one of the existing parts of the plane into two. Thus, when carrying out the last paraboles, the number of parts will increase by no more than $2n+1$, i.e., does not exceed $(n-1)^2 + 1+2n+1=n^2 + 1$.

An example can be easily constructed when all graphs intersect in pairs at two points (see figure) - this will result in the maximum number of parts specified in the answer.

In exactly the same way, you can calculate the maximum number of parts into which the plane $n$ of straight lines, $n$ of circles, etc. is divided.

N. Vasiliev

⟦folio 22⟧

---
running_head:
folio:
---

M1232. The hostess baked a threshold for the guests. There can be either p people or q people at the table. What is the minimum number of pieces (not necessarily equal) that the threshold must be cut into in advance so that in any case it can be distributed in portions? Consider the following cases:
a) p and q are relatively prime numbers,
b) p and q have the most common divisor d.

Fig. 1.

Fig. 2.

Answer: a) $p+q-1$; b) $p+q-d$.

To give an example of the required cutting, let us imagine the threshold in the form of a segment divided by $p-1$ points into $p$ equal parts and $q-1$ points into $q$ equal parts. With mutually prime $p$ and $q$, there will be a total of $p+q-2$ division points, and with GCD ($p, q)=d$, a total of $p+q-d-1$ different division points are drawn ($d-1$ of the division points coincide), so that the segment will fall exactly on the number of parts indicated in the answer. (It is clear that the threshold can be cut in the same way: if it has the shape of a right angle, it is sufficient to carry out cuts parallel to the side.)

For example, on figure 1, where $p=5, q=3$, all 6 division points are different, and the segment is divided into 7 pieces, and on figure 2, where $p=15, q=12$ and $d=3$, there are 23 different division points and the segment is divided into 24 pieces.

Let us give two different proofs that the number of pieces indicated in the answer is minimal.

We will present the first proof immediately for the general points of the problem.

Let the threshold be cut into several pieces so that the conditions of the problem are met. Let us select $p$ guests of the first group and $q$ guests of the second group as points on the plane and connect with segments those guests who are sufficiently the same piece (see examples in the figures). We will get a system of vertices and edges of a certain graph. Let's consider some connected component of this graph (the set of all vertices in which one can be added along the edges of the graph). Let's put together the pieces corresponding to the edges of this component. From them we can collect some integer number of $k$ parts of $1/p$ porgs and some integer number of $m$ parts of $1/q$ porgs. But if $k/p=m/q$, then $k$ must be divisible by $p/d$, and $m$ by $q/d$, thus, in this component pieces are collected that make up at least one inch of the $d$ parts of the porg. If $p$ and $q$ are coprime, $d=1$ and there is only one component, in the general case there are at most $d$. But in each component the number of vertices is no more than 1 greater than the number of edges. (By removing some edges, you can get a tree from it - a graph in which one path leads from each vertex to any other. For it, the number of vertices is 1 greater than the number of edges.) Thus, the total number of pieces does not exceed $p+q-d$.

We present the second proof, which is shorter, only for point a), i.e., for the case when $p$ and $q$ are coprime. Note here that our problem is equivalent to the following: to prove that the smallest number of numbers that must be placed in the cells of the table $p \times q$ so that the sums in the rows are equal to $1/p$, and the sums in the columns are $1/q$, is equal to $p+q-1$.

Let us prove a more general fact. Let $a_1, a_2, \dots, a_p$ and $b_1, b_2, \dots, b_q$ be two sets of positive numbers with the same sum and such that no subsum of the numbers of the first set is equal to any subsum of the second. Then the number of numbers that can be written in the cells of the table $p \times q$ so that the sums in the rows and columns respectively equal the number of these two sets is not less than $p+q-1$. Applying this fact to sets of numbers

⟦folio 23⟧

---
running_head:
folio:
---

1/p,..., 1/p and 1/q,..., 1/q (the mutual simplicity of p and q guarantees the fulfillment of the subsum condition), we obtain the desired result.

Let's carry out induction on p+q (for p=q=1 everything is very/no). Let p>q. Then in some row of the table there is only one number from the first group (otherwise the total number of numbers in the table is not less than 2p>p+q-1) - let it be the number a₁, standing in the first row and first column, b₁ - the sum of the numbers in this column. Having crossed out the first line, we apply the statement to the sets a₂, a₃,..., a_p and b₁-a₁, b₂,..., b_p - for it the number of numbers is 1 less and the condition about subsums is very satisfied. By the induction hypothesis, the table (p-1)×q must contain at least (p-1)+(q-1)=p+q-2 numbers. By adding the discarded number a₁, we get the desired estimate p+q-1 for the p×q table.

A. Tolpygo, D. Fomin

M1233. In ABCD, the diagonal AC is equal to the lateral side BC, H is the middle of the base AB. Let l be a line passing through H, and P and Q be the points of intersection of line l with lines AD and BD, respectively. Prove that angles ACP and QCB are equal or add up to 180°.

Let K be the point of intersection of lines l and CD, M and N be the points of intersection of lines CP and CQ with line AB, respectively. Let's prove the equality AM=BN. From here the statement of the problem will follow: the angles ACM and BCN are equal, and the angles we need ACP and BCQ are respectively equal to these angles or their complementary ones up to 180°. From the similarity of triangles we find

$$\frac{DC}{AM} = \frac{DP}{AP} = \frac{DK}{AH}, \frac{DC}{BN} = \frac{DQ}{BQ} = \frac{DK}{BH}.$$

Since AH=BH, this implies the desired equality AM=BN.

You can prove this equality without any calculations, by going into space. Let's consider the central projection of our plane onto some other plane p containing the straight line AB, and choose the center of the projection O so that the OCD plane is parallel to p. With such a central projection (image Fig. 1 - Fig. 2) all lines passing through points C will be parallel to each other and all lines

⟦folio 24⟧

---
running_head:
folio:
---

passing through $D$, - too; therefore, the images $P'$ and $Q'$ of the points $P$ and $Q$ will be symmetrical with respect to $H$, and therefore the points $M$ and $N$ too.

I. Sharyzin, V. Dubrovsky

M1234. Can any triangle be divided a) into 7, 6)* into 5 similar triangles?

Fig. 1.

Fig. 2.

$\alpha = a_{11}X + a_{12}Y + a_{13}Z,$
$\beta = a_{21}X + a_{22}Y + a_{23}Z,$
$\gamma = a_{31}X + a_{32}Y + a_{33}Z.$

It is easy to obtain a division into 7 triangles - just cut the triangle into 4 parts using the middle lines and cut one of the resulting triangles again into 4 with the middle lines (Fig. 1). Note that it is just as easy to obtain expansion by 6, 8, or any larger number of similar ones (Fig. 2) by adding 3 triangles to the existing ones.

Let us prove that not every triangle can be divided into 5 similar ones. We will give two proofs, each for some triangles with different (and non-right) angles $\alpha > \beta > \gamma$. Both lead to the fact that the partition triangles must be similar to the original one - it has the same angles $\alpha, \beta, \gamma$. Further reasoning is not difficult. If similar triangles are cut off from a triangle at the corners, the remaining part can be cut into two triangles only if it is a triangle or a quadrilateral (Fig. 3). But in general cases, such a cut turns out to have two angles that add up to $180^\circ$, while among the angles $\alpha, \beta, \gamma$ there are no such angles.

Let us present two arguments. The first is purely algebraic (belonging to the first author). Consider a triangle whose angles $\alpha, \beta, \gamma$ are rationally independent, i.e., there are no non-zero integers $k, l, m$ such that $k\alpha + l\beta + m\gamma = 0$. Let all the vertices converge at one or several angles of triangles whose magnitudes are $X, Y, Z$. Then the equalities indicated in the fields are satisfied, where the coefficients $a_{ij}$ are non-negative integers. If all the coefficients of one of the angles $X, Y$ or $Z$ are equal to 0, then it can be shown (by expressing the remaining two angles from the first two equations in terms of $\alpha$ and $\beta$ and substituting them into the third equation) that $\alpha, \beta, \gamma$ are rationally dependent, so this case is impossible. But if, after adding the three equations, we find that the coefficients of $X, Y, Z$ are all positive, then they must all be equal to 1, since

$$\alpha + \beta + \gamma = X + Y + Z = 180^\circ.$$

From here it is clear that in each equation there is only one coefficient 1, and the other two are equal to 0 - this was what needed to be proven.

The second is a geometric proof (his idea was proposed by I. Arzhantsev, a participant in the American-Soviet summer mathematics camp where this problem was discussed), please, even simpler.

Let among the angles $\alpha, \beta, \gamma$ of our triangle $\alpha$ be many (more than 5 times) greater than $\beta$, and $\beta$ much greater than $\gamma$. Let's assume that it is divided into 5 similar ones. Let some of its vertices be broken and $\alpha_1, \beta_1, \gamma_1$ —

⟦folio 25⟧

---
running_head:
folio:
---

the largest of the parts making up the angles $a$, $b$ and $\gamma$ respectively. Since each corner is divided into no more than 5 parts, $\alpha_1 > \beta_1 > \gamma_1$. Thus, these are the angles of the partition triangle, their sum is equal to $180^\circ$, and, therefore, they are respectively equal to $a$, $b$, $\gamma$; thus, there are actually no segments coming out of the corners.

A. Soifer (USA), N. Vasiliev

M1235*. Let $p = 2 \cdot q + 1$ be a prime number. Prove that the number $2^{3q} q! - (-1)^q (2q-1)!!$ is divisible by $a$) $p$; $b$) $p^2$; $\epsilon$) $p^3$ (at $p > 3$). (Here $q! = 1 \cdot 2 \cdot \dots \cdot q$; $(2q-1)!! = 1 \cdot 3 \cdot 5 \cdot \dots \cdot (2q-1)$.)

$p = 5$: 1
11
121
1331
14141
100001

$p = 7$: 1
11
121
1331
14641
153351
1616161
10000001

Pascal's triangles modulo $p$.

Statement a) is relatively easy to prove based on the simple properties of the numbers $C_n^k$ - the coefficients of the expansion of the binomial degree

$(1+x)^n = 1+nx + \dots + C_n^k x^k + \dots + x^n$. (*)

From the formula $C_n^k = n(n-1) \dots (n-k+1)/k!$ it follows that with a prime $n$ all coefficients $C_n^k$, except the two extreme ones, are divisible by $n$, and the fact that in Pascal’s triangle (where in the $n$ line there are numbers $C_0^n = 1$, $C_1^n$, $C_2^n$, ..., $C_n^n = 1$) each number is equal to the sum of the two above it: $C_n^k + C_n^{k+1} = C_n^{k+1}$. Since $2^q q! (2q-1)!! = (2q)! = C_2^q q!^2$, $2^q (2^{3q} q! - (-1)^q (2q-1)!!) = q! (2^{4q} - (-1)^q C_2^q)$, and the numbers $2^q$ and $q!$ are coprime to $p=2q+1$, it is sufficient to prove that the number in the last parentheses is divisible by $p$.

We will consider numbers “modulo $p$”, in particular, “remainder - 1” will mean the same as “remainder $p - 1$”. Let us prove that the remainder of division of $C_2^q$ by $p$ is equal to $(-1)^q$. If in Pascal's triangle we replace the numbers with their remainders when divided by $p$, then the $p$-th line will have the form 1 0 0...0 1, and, therefore, the previous $2q$-th (consisting of $2q+1$ numbers) -

$$1 - 1 1 - 1 \dots 1 - 1 1,$$

so its average is $C_2^q = (-1)^q$ (examples of Pascal's triangles modulo $p$ for $p=5$ and $p=7$ are given in the margin). This same line will also be useful to us to find the remainder for degree 2.

Substituting $x=1$, $n=2q$ into formula (*), we see that modulo $p$ the number $2^{2q}$ is equal to 1 (this is a special case of Fermat’s Little Theorem), therefore, the difference $2^{4q} - (-1)^q C_2^q$ that interests us modulo $p$ is equal to $1 - (-1)^{2q} = 1 - 1 = 0$.

The proof of statement 6) was obtained as a by-product at the end of Chapter VIII of the wonderful book “Introduction to the number theory” by G. Hardy and F. Wright, which, unfortunately, has not yet been translated into Russian. We will give a shorter proof. (Of course, for $p=3$ statement 6) is obvious: $2^3 + 1 = 3^2$. Below we assume that $p>3$, i.e. $q>1$.

⟦folio 26⟧

---
running_head:
folio:
---

Fermat's little theorem. If $p$ is a prime number, $a$ is a natural number and is not divisible by $p$, then $a^{p-1}-1$ is divisible by $p$.

Let's imagine the product $2^{3q}q!(2q-1)!!$ as a “polynomial in $p^2$”:
$$2^{3q}q!(2q-1)!! = 2^{2q}(2q)! = 2 \cdot 4 \cdot \dots \cdot (p-1)(p+1)...(2p-2) = (p-(p-2))...(p-1)(p+1)...(p+(p-2)) = (p^2-(p-2)^2)...(p^2-(2k-1)^2)...(p^2-1)^2 = (p^2-(2q-1)^2)...(p^2-(2k-1)^2)...(p^2-1)^2 = p^{2q}-S_1 p^{2q-2} + \dots + (-1)^k S_k p^{2q-2k} \dots$$
... $-(-1)^q S_{q-1} p^2 + (-1)^q S_q$. (**)

Here $S_k$ is the sum of all products of $k$ numbers $1^2, 3^2, 5^2, \dots, (2q-1)^2$, in part,
$$S_1 = 1^2 + 3^2 + \dots + (2q-1)^2,$$
$$S_{q-1} = 3^2 \dots (2q-1)^2 + 1^2 \cdot 5^2 \dots (2q-1)^2 + \dots + 1^2 \cdot 3^2 \cdot 5^2 \dots (2q-3)^2 = S_q(1+1/3^2+...+1/(2q-1)^2),$$
$$S_q = (2q-1)!!^2$$ is the product of all $q$ squares of the numbers $1, 3, \dots, (2q-1)$.

Obviously, all terms of the last sum (**), except the last one, are divisible by $p^2$. It follows that the difference $2^{2q}(2q)! - (-1)^q(2q-1)!!^2$ is divisible by $p^2$, and since $p$ is prime, removing the extra factors $(2q-1)!!$, is not divisible by $p$, we get what we need, the difference is divisible by $p^2$.

Let us now present the proof of the last, most powerful statement in), each discovery of the amazing (examples for $p=5, 7, 11, 13$ are given in the margins).

All terms of the sum $S_1$ give different remainders when divided by $p$, since the difference $i^2-j^2 = (i-j)(i+j)$ is not divisible by $p$ for odd $i, j$, $1<i<j<p$. The same can be said about the amount $S_{q-1}$. But squares of natural numbers that are not multiples of $p$ can only give $(p-1)/2=q$ different remainders when divided by $p$ (since the squares $i$ and $p-i$ give the same remainders). All these remainders appear once in both sums $S_1$ and $S_{q-1}$, consisting of the same number of $(p-1)/2=q$ terms, so both sums give equal remainders when divided by $p$.

The first sum is easy to calculate - it is equal to $p(p-1)(p-2)/6$ (you can use induction) and is divisible by $p$ when $p>3$. Thus, the second sum is divided by $p$.

(We can prove that the sum $S_k$ of all products by $k$ of the squares of the numbers $1, 3, 5, \dots, 2q-1$ for each $k<q$ is divisible by $p$, but we don’t need this.)

Since $S_{q-1}$ is divisible by $p$, the difference
$$2^{2q}(2q)! - (-1)^q(2q-1)!!^2$$
is divisible by $p^3$. Having removed the extra factors that are not divisible by $p$, we get what we need, the difference is divisible by $p^3$.

I. Vainshtein

⟦folio 27⟧

---
running_head:
folio:
---

F1243. A cockroach and two beetles can use a large horizontal table. Each beetle can reach speeds of up to $v=1$ cm/s. At the first moment, the insects are at the vertices of an equilateral triangle. What speed should a cockroach be able to develop so that even with any changes in the beetles the triangle remains equilateral?

Consider a short period of time $\Delta t$, after which the first beetle moved to $\vec{s}_1=\vec{v}_1\Delta t$, and the second to $\vec{s}_2=\vec{u}_2\Delta t$. Let's find what the mixture of the cockroach should be so that the triangle connecting them remains equilateral.

Let us reason sequentially. Let us first assume that the first beetle is motionless, and the second has made a movement $\vec{s}_2$ (Fig. 1). For the triangle $J_1J_2T'$ to be equilateral, the cockroach must move to $\vec{T'T'}$, and

$$|\vec{T'T'}|=|\vec{s}_2|=v_2\Delta t.$$

Let the second beetle now be motionless, and the first one be mixed up at $\vec{s}_1$. Then the cockroach will have to mix

Fig. 1.

Fig. 2. Fig. 3.

move to $T'T''$, while

$$|\vec{T'T''}|=|\vec{s}_1|=v_1\Delta t.$$

So, if one beetle moves to $\vec{s}_1$, the second - to $\vec{s}_2$, then the cockroach should move to

$$\vec{T'T'}+\vec{T'T''}=\vec{T'T''}.$$

From the triangle $TT'T''$ (Fig. 2) we get

$$|\vec{T'T'}| \leqslant |\vec{T'T'}|+|\vec{T'T'}|=(v_1+v_2)\Delta t.$$

This means that the speed that a cockroach should develop is related to the speed of beetles, respectively

$$v_\tau=\frac{|\vec{T'T'}|}{\Delta t} \leqslant v_1+v_2 \leqslant 2v.$$

Equality corresponds to the case when the mixtures of the cockroach $TT'$ and $T'T''$ are directed in the same direction. To do this, the speeds of the beetles must be directed, for example, as shown in figure 3.

A. Korshkov

F1244. A household refrigerator maintains a constant temperature $-12^\circ\text{C}$ in the chamber. At temperature

The temperature difference $\Delta T$ outside and inside the refrigerator and the long pause $\tau_2$ are related respectively

$$\tau_2\Delta T=\text{const.}$$

(1)

⟦folio 28⟧

---
running_head:
folio:
---

For an ideal refrigeration machine, the following equality holds:
$$\frac{A}{Q} = \frac{\Delta T}{T},$$
where $A$ is the engine operation, $Q$ is the amount of heat optimized from the contents of the refrigeration chamber, $T$ is the temperature of the chamber. It is obvious that the work done by the motor is proportional to the time $\tau_1$ of the motor operation -
$$A \sim \tau_1,$$
and the optimal amount of heat is proportional to the total “periodу” $(\tau_1 + \tau_2)$ and the temperature difference -
$$Q \sim (\tau_1 + \tau_2) \Delta T,$$
can be written in a meaningful way
$$\frac{\tau_1 + \tau_2}{\tau_1} (\Delta T)^2 = T = \text{const.}$$

Substituting into equalities (1) and (2) the values ​​$\tau_1$ and $\tau_2$ for the first case, and $\Delta T$ for both cases, we find new values ​​$\tau'_1$ and $\tau'_2$ for the second case:
$$\tau'_1 = 2 \text{ min}, \tau'_2 = 4,1 \text{ min.}$$

The maximum possible temperature in the room is $\tau''_2 = 0$:
$$\Delta T_{\text{max}} = \Delta T \sqrt{8/5} = 46,8 \text{ K},$$
$$t_{\text{max}} = 34,8 \text{ °C.}$$

R. Alexandrov

F1245. In the circuit at figure, the ammeter shows a current of 10 mA, the voltmeter shows a direction of 2 V. After the resistor was disconnected from the voltmeter and connected in parallel with the ammeter, the displayed ammeter decreased to 2.5 mA. Using these data, determine the resistance of the voltmeter? Is it possible to determine the resistance of the ammeter and the direction of the battery from this data? The battery is considered ideal.

In the first case, the direction across the resistor $R_x$ is equal to
$$U_1 = U_{Rx1} = U \frac{RR_x/(R + R_x)}{r + RR_x/(R + R_x)} = U \frac{RR_x}{r + R_x(R + r)},$$
where $U$ is the direction of the battery, $R$ is the resistance of the voltmeter, $r$ is the resistance of the ammeter.

In the second case, the ammeter and voltmeter are swapped, so the direction across the resistor will be equal
$$U_{Rx2} = U \frac{rR_x}{rR + R_x(R + r)}.$$
It is not at the same time a direction on the ammertra; this means the current through it is equal to
$$I_2 = \frac{U_{Rx2}}{r} = \frac{UR_x}{rR + R_x(R + r)} = \frac{U_1}{R}.$$
From here you can find the resistance of the voltmeter:
$$R = \frac{U_1}{I_2} = 0,8 \text{ кОм.}$$

Then the resistance of the resistor is

⟦folio 29⟧

---
running_head:
folio:
---

$$R_x = \frac{U_1}{I_1 - U_1/R} = \frac{U_1}{I_1 - I_2} \approx 0.27 \text{ кОм.}$$

The amperor resistance and battery voltage cannot be found from the problem data.

A. Zilberman

F1246. Two identical LC circuits are located far from each other. In the first, oscillations are excited with the voltage amplitude on the capacitor $U_0$. At the moment when the voltage on the capacitor turns out to be zero, connect the second circuit (Fig. 1) with wires. Analyze the processes in the circuit after connection. What will change if the connection is made at the moment when the voltage on the capacitor is maximum?

Fig. 1.

Fig. 2.

Let's start with the second case, when at the moment the switch is closed, the voltage on the first capacitor is maximum, i.e., all the charge is concentrated on the capacitor $C_1$, and there is no current in the coil $L_1$. Immediately after closing the switch, the voltage on the capacitors is equal to $U_1 = U_0$ and $U_2 = 0$. $U_0$ is applied to the connecting wires, and since their resistance is very low, a rapid (compared to the oscillation period) process of charge redistribution between the capacitors occurs in the system. Since the capacitances are equal, the charge is divided equally, i.e.

$$U_1' = U_0/2 \text{ и } U_2' = U_0/2.$$

Coils are not involved in the process.

After charge redistribution, both circuits find themselves in the same initial state - the voltage on the capacitor is $U_0/2$, there is no current in the coil, and their joint synchronous oscillations begin with frequency $\omega = 1/\sqrt{LC}$ and voltage amplitude $U_0/2$:

$$u_1(t) = u_2(t) = U_0/2 \cos \omega t.$$

These processes are not affected by the jumper between the circuits; after the exchange of charges, it could be removed.

Now let's discuss the first case, when at the initial moment the voltage on the first capacitor is zero. This situation is more complicated.

So, at the moment the switch is closed, the voltage on the capacitor $C_1$ is zero, and through the coil $L_1$ the current flows $I_0 = \sqrt{C/L} U_0$ (this is obtained from the equality $LI_0^2/2 = CU_0^2/2$). To describe further processes in the circuit, we note that after closing the key, a direct current can circulate along circuit $L_1 - L_2$, which does not create any voltage (we neglect the active resistance of the coils). Let us imagine the distribution of currents in the coils as shown in figure 2.

In coils $L_1$ and $L_2$ equal and equally stressed points $i_1 = i_2 = I_0/2$ flow, and a direct current $i = I_0/2$ circulates along the circuit $L_1 - L_2$. Then

$$I_1 = i_1 + i, \quad I_2 = i_2 - i.$$

Further reasoning is similar to the first case. Indeed, if we temporarily forget about direct current $i$, which does not create voltage and, therefore, does not affect other processes in the circuit, then the circuits end up in the same initial
