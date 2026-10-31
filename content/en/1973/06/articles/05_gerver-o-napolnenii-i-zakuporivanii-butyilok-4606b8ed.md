---
id: 1973-6-gerver-o-napolnenii-i-zakuporivanii-butyilok-4606b8ed
issue: kvant_1973_6
year: 1973
number: "6"
title: About filling and capping bottles
authors:
  - Гервер М. Л.
rubric: osnovnye-stati
page_first: 22
page_last: 29
page_labels: 20-27
tag: 8M1F
lang: en
source: kvant_digital
extraction: vision
content_sha256: 8aee9bc44cb43d67db43b08bedf51ac5ad50affdfb16aa87097a53d9ec6872bb
prompt_sha256: draft-1
translated_from: content/ru/1973/06/articles/05_gerver-o-napolnenii-i-zakuporivanii-butyilok-4606b8ed.md
source_content_sha256: ce0db42994653b605bf63597e793f65429de1ab0020a1d0a1053373448f2af58
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 20⟧

About filling and purchasing bottles

M. L. Gerver

Everyone's done: he's warmed up dinner,
Vystro sat down - sat down for his lessons,
«Kvant» read - trampled on football...
Mill. "Misty-fisty, or tales about the arrowhead"

A person does a lot of different things every day. He goes to school in the morning (if he is a schoolboy), returns home - lunch is warmed up, etc. (see epigraph). You can usually swap things around: first play football - then do your homework, first eat lunch - then warm it up...

Stop! Something didn't work out with dinner - not everything in the world can be rearranged.

This also applies to completely service things: a high-altitude crane has nothing to do at a construction site until the foundation of the house is laid; You can’t plow, net and thresh at the same time “to reduce time”...

The fact that a delay in one task may prevent the start of others must be taken into account when planning - for example, when estimating how much time a large set of interrelated works will require. The substitution uses a humorous example to show what kind of mathematical problems can be encountered in this case.

1. Statement of the problem

They brought bottles to the automatic line, a lot: N pieces. And there are 2 machines on the line: I and II. I fills bottles, II – purchases

⟦folio 21⟧

roars. The bottles are different: with a wide neck and with a narrow, high one, pot-bellied ones are non-standard. For each bottle we know how long it takes to fill it and how long it takes to seal it.

How long will the automatic line work from the moment the first bottle begins to be filled until the last one is capped? This depends on the order in which the bottles will fall into the machines (for example, for 6 bottles there are $P_6=720$ such orders). Thus, two questions arise:

How to quickly determine the order at which the operating time of the line will be the shortest? And what is the number for this shortest time?

2. Numerical example

Let's start with an example: the path of a batch of 6 bottles is characterized by table 1.

Let's try to feed the bottles into the machines exactly in the order in which they are indicated in the table: first the 1st, then the 2nd, and so on until the 6th. Then the machines will work like this.

After 7 seconds, the filling machine will fill the 1st bottle (Fig. 1), after 7 + 9 = 16 s. - 2nd, after 16 + 3 = 19 s. - 3rd, after 19 + 2 = 21 s. - 4th, after 21 + 11 = 32 s. - 5th, after 32 + 5 = 37 s. - 6th*).

The capping machine will finish the 1st bottle in 7 + 10 = 17 s. and only then will he be able to take the second bottle (which, thereby, will be filled for a whole second). He will finish the 2nd bottle in 17 + 8 = 25 s. (so the 3rd bottle will be forgiven while waiting for the cork for 6 seconds). After 25 + 1 = 26 s. the 3rd bottle will be corked in 26 + 4 = 30 s. - 4th. Now the sealing machine could take the 5th bottle, but that one, as we know, is not full yet, so the machine takes 2 s. forgive without doing anything. After 32 + 6 = 38 s. the 5th bottle will be corked, and after 38 + 12 = 50 s., finally, the 6th.

Let's build auxiliary table 2.

*) It is believed that, having filled the bottles, the machine can, without wasting a second, begin filling the next time.

⟦folio 22⟧

The numbers in its first column are already familiar to us: it is written here in how many seconds the machine I will fill the first bottle, the first two bottles, the first three bottles, etc. This column is obtained by sequential addition (from top to bottom) of the numbers in the second column of table 1. It is more convenient to read the second column of table 2 from top to bottom: in such an order to get this column, add up the numbers from the third column of table 1. Third column 2 is the sum of its first two columns.

The second column of Table 2 has the following meaning: if machine II had worked without scanning, it would have capped all the bottles in 41 s; if he corked all the bottles starting from the 2nd without looking, he would have spent 31 s.; It takes 23 seconds to cork without going through all the bottles, starting from the 3rd. etc.

In our example, machine II worked without viewing only after the 5th bottle hit it. It was then filed (see row 5 of Table 2) after 32 s. after the start of work of the automatic line; after that, machine II worked for 18 s, so that the entire line operation lasted 50 s. (see third column of Table 2).

In paragraph 5 we will return to this example, and now we will show how to calculate the operating time of an automatic line in the general case - provided that the order of feeding bottles on the line is specified.

3. Automatic line operating time

In our example, 50 s. is the largest number in the third column of Table 2. This is not accidental: the following is true.

Statement 1. Let the time of filling and capping bottles be given by table 3, and let the bottles fall into the machine in the order in which they are indicated in this table. Let's build auxiliary table 4 based on table 3 (similar to how above, table 2 was built from table 1).

Then the operating time of the automatic line is equal to the largest number in the third column of Table 4.

Proof. Let’s draw two horizontal lines: I and II (Fig. 2.) On line I we’ll put aside (next-

⟦folio 23⟧

to the right) segments $P_0P_1, P_1P_2, \dots, P_{N-1}P_N$ (with lengths $a_1, a_2, \dots, a_N$). On the straight line $II$ we plot (also from left to right) the segments $H_1K_1, H_2K_2, \dots, H_NK_N$ (with lengths $b_1, b_2, \dots, b_N$). We will place point $H_1$ on the same vertical with $P_1$, and then - for any $i$, $1 < i \leq N$ - we will place point $H_i$ on the same vertical with the more right ones from points $P_i$ and $K_{i-1}$ (this corresponds to the fact that the machine $II$ begins to clog next bottle when it is full and when the previous bottle is corked). Let us orthogonally project on the horizontal time axis $t$ the points $P_0, P_1, \dots, P_N$ into the points $O, A_1, \dots, A_N$ and the point $K_N$ into the point $T_N$. It is clear that $T_N$ is the operating time of the automatic line in the case we are considering.

The length of the segment $A_iT_N$ on the axis $t$ will be denoted by $C_i$ $i=1, \dots, N$; then $T_N = A_i + C_i$.

There may be gaps between the segments $H_1K_1, H_2K_2, \dots, H_NK_N$ on the line $II$, and the point $H_i$ is located either on the same vertical with $P_i$, or to the right; therefore $C_i \geqslant B_i = b_i + b_{i+1} + \dots + b_N$. Therefore, $T_N \geqslant A_i + B_i$ ($i=1, \dots, N$).

Let's take the rightmost gap between the segments $H_iK_i$. To its right are the segments $H_nK_n, H_{n+1}K_{n+1}, \dots, H_NK_N$, forming one “solid” (without gaps) segment *) of length $B_n$. Since $H_n$ does not coincide with $K_{n-1}$ (they are separated by a gap), then $H_n$ lies on the same vertical with $P_n$ and $A_n$. So, $T_N = A_n + B_n$.

Thus, $T_N$ is equal to the maximum of the numbers $A_i + B_i$ ($i=1, \dots, N$). Statement 1 has been proven.

Table 4 is built from given table 3 extremely quickly: the first two columns

$$\begin{array}{c c c}
a_1 = A_1 & B_2 + b_1 = B_1 & A_1 + B_1 \\
A_1 + a_2 = A_2 & B_3 + b_2 = B_2 & A_2 + B_2 \\
A_2 + a_3 = A_3 & B_4 + b_3 = B_3 & A_3 + B_3 \\
\dots & \dots & \dots \\
A_{N-3} + a_{N-2} = A_{N-2} & B_{N-1} + b_{N-2} = B_{N-2} & A_{N-2} + B_{N-2} \\
A_{N-2} + a_{N-1} = A_{N-1} & B_N + b_{N-1} = B_{N-1} & A_{N-1} + B_{N-1} \\
A_{N-1} + a_N = A_N & b_N = B_N & A_N + B_N
\end{array}$$

⟦folio 24⟧

4. Best order

First, consider the case when there are two bottles.

Let for one of them the filling and purchasing times be equal to $a$ and $b$, and for the other, respectively, $c$ and $d$. Which order is better then - the one indicated in table 5 or the one indicated in table 5'?

The operating time of the line in the first option (Table 5) corresponds to $t$. In Table 4 notation for $N = 2$

$$A_1 = a, \quad B_1 = b + d$$
$$A_2 = a + c, \quad B_2 = d.$$

According to Statement 1, the time $t$ is equal to the larger of the numbers $A_1 + B_1$ and $A_2 + B_2$:

$$t = \max(A_1 + B_1, A_2 + B_2) = \max(a + b + d, a + c + d).$$

Let us denote the sum $a + b + c + d$ by $S$. Then the formula for $t$ can be rewritten as follows:

$$t = \max(S - c, S - b) = S - \min(b, c)$$

(if the numbers $b$ and $c$ differ from $S$, then the numbers $S - b$ and $S - c$ will be greater).

A similar formula, of course, is valid for $t'$, where $t'$ is the line operating time in the second option (Table 5'):

$$t' = S - \min(a, d).$$

So, if $\min(a, d) \geq \min(b, c)$, then $t \geq t'$.

In other words, for $N = 2$ the best order is determined by the following rule: choose the most from the numbers $a, b, c$ and $d$; if it is $a$ or $d$, then the first option is better (Table 5), but if it is $b$ or $c$, then the second one (Table 5'). That is, when $N = 2$ in the table indicating the best order, most of the numbers should be in the upper left or lower right.

In the case of arbitrary $N$, the last sentence is generalized as follows.

Statement 2. The “best” order can be determined by the following rules. Let us choose the most of the numbers $a_1, b_1, \dots, a_N, b_N^*$ in Table 3. If this number is $a_k$, then the $k$th bottle must be served on the line of the very first one; if this number is $b_k$, then the $k$th bottle must be served last on the line. Find out as much as possible the fate of the $k$th bottle by deleting the $k$th line from Table 3. Among the remaining numbers $a_i, b_i$ ($1 \leq i \leq N, i \neq k$), we again choose the most from the numbers $*$. If it is equal to $a_l$, then the $l$th bottle will be sent to the beginning of the queue, and if it is equal to $b_l$, then the $l$th bottle will be sent to the end of the queue (which is formed by all bottles except the $k$th). So until the last bottle.

We will prove statement 2 in paragraph 6, and now apply statements 1 and 2 to our example.

*) If there are several such numbers, you can take any of them.

⟦folio 25⟧

5. Numerical example (end)

The name from the numbers indicating the times in Table 1 is 1. This is the time for corking the 3rd bottle. Therefore, we will send the 3rd bottle to the very end of the queue. Let's cross out the 3rd line from table 1 and again find the name number. This time it is equal to 2 - this is the time to fill the 4th bottle. According to our rules, we send the 4th bottle to the beginning of the queue. Continuing to proceed in the same way, we obtain table 1′.

How long will the line work under the new order? Let us compose, as usual, table 2′.

The maximum number in its 3rd column is 44. This is the work line time. Compared to the old order, we gained 6 seconds.

Note: Let's rearrange the last two rows in table 1 (that is, place the 3rd and 5th bottles). The first four lines in tables 1′ and 2′ will not change, but the last two will become the same as in tables 1″ and 2″ on page 26.

According to Statement 1, the operating time of the ruler will still be 44 s. Thus, it can be said that several different orders are “best”. Statement 2 allows you to quickly find one of them.

6. Proof of Statement 2

Let's select some two rows in Table 3, one after the other, and swap them (see Tables 6 and 6′).

Let's see how Table 4 changes. If we rearrange the rows with numbers i and (i+1), then for k < i and for k > i + 1 the numbers $A_k$ and

Table 2′

⟦folio 26⟧

Table 1"

| 3 | 3 | 1 |
| :--- | :--- | :--- |
| 5 | 11 | 6 |

Table 2"

| 23+3=26 | 6+1=7 | 26+7=33 |
| :--- | :--- | :--- |
| 26+11=37 | 6 | 37+6=43 |

Table 3'

| $i$ | $a$ | $b$ |
| :--- | :--- | :--- |
| $i+1$ | $c$ | $d$ |

$B_k$ does not change. Changes will occur only in lines numbered $i$ and $i+1$ (see tables 7 and 7').

Thus
$$A_i + B_i = (A_{i-1} + B_{i+2}) + a + b + d,$$
$$A'_i + B'_i = (A_{i-1} + B_{i+2}) + b + c + d,$$
$$A_{i+1} + B_{i+1} = (A_{i-1} + B_{i+2}) + a + c + d,$$
$$A'_{i+1} + B'_{i+2} = (A_{i-1} + B_{i+2}) + a + b + c.$$

Denoting $A_{i-1} + B_{i+2}$ by $H$ and using the formulas for $t$ and $t'$ from step 4, we find
$$\max(A_i + B_i, A_{i+1} + B_{i+1}) = H + t,$$
$$\max(A'_i + B'_i, A'_{i+1} + B'_{i+1}) = H + t'.$$

The largest of the numbers $A_k + B_k$ (at $k \neq i$ and $k \neq i+1$) we denote by $K$. Line operating time in two comparisons

We denote the variants that are mutually exclusive by $T$ and by $T'$. Then, according to Statement 1,
$$T = \max(K, H + t),$$
$$T' = \max(K, H + t').$$

It is clear that if $t \geq t'$ then $T \geq T'^*$.
In section 4 we proved that $t \geq t'$ if $\min(a, d) \geq \min(b, c)$.

Therefore, the result just obtained can be formulated as follows:
Lemma. Let us select two arbitrary adjacent rows in Table 3 (see.

*) Note that if $t > t'$, then not necessarily $T > T'$. One can obey that $\max(K, H + t, H + t') = K$ and then $T = T'$ regardless of which of the numbers $t$ and $t'$ is greater.

Table 4**

| $A_i - 1 + a = A_i$ | $B_{i+1} + b = B_i$ | $A_i + B_i$ |
| :--- | :--- | :--- |
| $A_i + c = A_{i+1}$ | $B_{i+2} + d = B_{i+1}$ | $A_{i+1} + B_{i+1}$ |

Table 5'

| $A'_i - 1 + c = A'_i$ | $B'_i + 1 + d = B'_i$ | $A'_i + B'_i$ |
| :--- | :--- | :--- |
| $A'_i + a = A'_i + 1$ | $B'_i + 2 + b = B'_i + 1$ | $A'_i + 1 + B'_i + 1$ |

26

⟦folio 27⟧

6). If for them
min (a, d) ≥ min (b, c),
then these lines can be rearranged (see Table 6'), and the line operating time will not increase.

This already implies statement 2 from point 4. Let’s prove it.
Let's start with two simple notes.
1) The order we arrive at, applying the rules of paragraph 4, does not depend on the order in which they were initially arranged. Therefore, it is enough to prove Statement 2 in the case when the order indicated in Table 3 was already “cryed” (more precisely, one of the “cryed” *).
2) Let us assume that, consistently applying the rules of step 4, we decided (at some steps) to move some bottle closer to the end of the queue: from the i-th place to the (i + s)-th. then this can be done in s stages: first move the selected bottle to the (i + 1)th place, then to the (i + 2)th place, etc. The same is true if we have to move some bottle closer to the beginning of the queue: this can also be done in several stages, swapping only nearby bottles. If you make sure that the lemma is applicable at each stage, then it will be proven that following the rules of step 4 does not increase the operating time of the line. According to the previous remark, this is the only thing left to verify in order to prove Statement 2.

Listen, when a bottle is moved to the beginning or end of the queue, the perfect is considered in the same way. Let's consider, for example, the second of them.

Let, according to the rules of point 4, at some step it was decided to transfer some bottle from the i-th to the (i + s)-th place, and let at this step the i-th and (i + 1)-th rows be specified by Table 6. Then the number b is the smallest among

*) See note at the end of paragraph 5.

numbers indicating the filling and capping time for all bottles that have not yet been placed in their final places at this time. In particular, b = min(a, b, c, d). Thus, min (a, d) ≥ min (b, c). This means that the lemma is applicable. In the same way, it is proven that it is applicable at any stage. Thus, the proof is completely completed.

At the difference
1. In paragraph 3, we calculated that if the order of supplying bottles to the automatic line is specified, then the operating time of the line is calculated in 3N - 2 additions (where N is the number of bottles). How many actions do you need to perform to determine the “who cried” order?

If we call “action” the selection of the smallest number in a table of two columns and an arbitrary number of rows, then N actions will be required (see statement 2 in paragraph 4). As long as N is not large, this definition of “action” is reasonable - for example, we can assume that when compiling table 1' from table 1 in paragraph 5, we actually consumed N actions (N = 6). For large N, finding the smallest number in the table will clearly rearrange the bottle by an elementary act, so “action” is more reasonably called comparing two numbers (and choosing the smallest of them). How many such comparison actions are required to determine the smallest order?

2. You can consider the “bottle problem” not for two, but for n machines. (In the mathematical literature, solving the problem in the future is known as the “Johnson problem for n = 2.”)

For n > 2 (further for n = 3) this problem has not yet been solved. This is largely explained by the following. When n = 2, adding the (N + 1)th bottles to the N bottles already arranged by presence does not affect the relative order of the first N bottles. For n > 2, this seems to be true: already for n = N = 3, you can set the time a_i, b_i, c_i (i = 1, 2, 3) for processing three bottles in such a way that “in the presence of the 3rd bottle,” the 1st bottle should be fed to the line equal to the 2nd, and “in the absence of the 3rd bottle,” on the contrary, the 2nd bottle should be fed to the line equal to the 1st. Give an example to support this.

3. Check that, for n = 3, the bottles, arranged in the best possible manner, are fed to each of the machines in the same order. For n > 3, this is no longer necessarily the case: in order to minimize the operating time of the line, it may sometimes come across another bottle processed by the incomplete machine A, and feed it to the next machine B after the bottle that comes out of machine A later than this one. Give a relevant example.
