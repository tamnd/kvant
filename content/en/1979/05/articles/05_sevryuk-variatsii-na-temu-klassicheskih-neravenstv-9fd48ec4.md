---
id: 1979-5-sevryuk-variatsii-na-temu-klassicheskih-neravenstv-9fd48ec4
issue: kvant_1979_5
year: 1979
number: "5"
title: Variations on the theme of classical inequalities
authors:
  - Севрюк М. Б.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 20
page_last: 22
page_labels: 18-20
tag: BKFN
lang: en
source: kvant_digital
extraction: vision
content_sha256: f506b28081595d76e90a96caf9ba6ddf9cb1566486aafb3bec2bf47cafabc6f0
prompt_sha256: draft-1
translated_from: content/ru/1979/05/articles/05_sevryuk-variatsii-na-temu-klassicheskih-neravenstv-9fd48ec4.md
source_content_sha256: abba9462a930ff67d0dfa9baba6b6a4757307714873df878c61bde5c6edc2950
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 18⟧

Variation on the theme of classical inequalities

This note was written by tenth-grader Misha Sevriok based on his report at the conference of the Moscow School No. 2. It proves the inequalities found by the author, visible and generalized inequalities about the arithmetic mean and the geometric mean. They are, of course, not new: in the classical areas of mathematics there are practically no “blank spots” that can be achieved without server training. Proofs of the mentioned inequalities are contained, for example, in the wonderful, but difficult to access book of Hardy, Leathwood and Polyan *); however, M. Sevriok's purely combinatorial proofs are original and noticeably simpler.

Inequalities of this type are also of interest to many of our other readers. In addition to the note by M. Sevriok, in this issue we publish in the form of a problem (M565) the Maclaurin inequalities, interesting proofs of which were sent by M. Rosenberg, as well as a problem by P. Vinokur, showing the applicability of inequalities of this type in a wide variety of situations.

In our age of electronic computers, it is nice to know that the living art of algebraic transformations has not lost its appeal and has not ceased to be useful...

Even the ancient Greeks knew that the geometric mean $\sqrt{ab}$ of two non-negative numbers does not exceed their arithmetic mean $\frac{a+b}{2}$. This theorem is valid for any number of non-negative numbers $a_1, a_2, \dots, a_n$:

$$\frac{1}{n} (a_1 + \cdots + a_n) \geq (a_1 \dots a_n)^{1/n}$$

(equality occurs only when all $a_i$ match); it will serve as the basis for everything that follows.

First series of inequalities

Here, as before, $a_1, a_2, \dots, a_n$ are arbitrary non-negative numbers. In addition to the sum $S_1$ of all $a_i$ separately, as in inequality (1), we will be interested in the sum of their possible pairwise products $S_2 = a_1 a_2 + a_1 a_3 + \dots + a_{n-1} a_n$,

the sum of their possible products of three

$$S_3 = a_1 a_2 a_3 + a_1 a_2 a_4 + \dots + a_{n-2} a_{n-1} a_n$$

and in general the sum $S_k$ of their products over $k$ components ($k \leq n$). Similarly, in addition to the product $P_1$ of all $a_i$ separately, we will be interested in the product of all possible pairwise sums

$$P_2 = (a_1 + a_2) (a_1 + a_3) \dots \dots (a_{n-1} + a_n)$$

product of sums of three

$$P_3 = (a_1 + a_2 + a_3) (a_1 + a_2 + a_4) \dots \dots (a_{n-2} + a_{n-1} + a_n)$$

and in general the product $P_k$ of their sums over $k$ terms ($k \leq n$).

It turns out that the quantities $S_k$ and $P_k$ for $k=1, 2, \dots, n$ can be given the following upper and lower bounds (in terms of $S_1 = a_1 + \dots + a_n$ and $P_1 = a_1 \dots a_n$):

$$C_n^k \left( \frac{S_1}{n} \right)^k \geq S_k \geq C_n^k P_k^{\frac{k}{n}}$$

$$\left( \frac{k}{n} \right)^{C_n^k} S_1^{C_n^k} \geq P_k \geq k^{C_n^k} P_1^{\frac{k}{n}}$$

Expand the recording of these formulas looks very internal. Don't shoot yourself! Better decipher one of these formulas (for specific, not too large values ​​of $k, n$) and you will see that all this is not so scary. For example, with $k=3, n=4$, the form

⟦folio 19⟧

mula $(I_2)$ looks like this:

$$4 \left( \frac{a_1 + a_2 + a_3 + a_4}{4} \right)^3 \geq a_1 a_2 a_3 + a_1 a_2 a_4 + a_1 a_3 a_4 + a_2 a_3 a_4 \geq 4 \left( a_1 a_2 a_3 a_4 \right)^{3/4}.$$

At $k=1$ the inequalities $(I_2)$, $(II_1)$ turn into $(1)$; $(I_1)$ and $(II_2)$ become $(1)$ at $k=n$ (check!). Thus, all four inequalities $(I)$, $(II)$ can be considered as generalizations of inequality $(1)$.

Proof of the inequality $(I_2)$. For brevity, let us put $C = C_n^k$, and by $\tilde{p}_1, \tilde{p}_2, \dots, \tilde{p}_{C_n^k}$ we denote the terms of the sum $S_k$ (there are, in fact, $C = C_n^k$ of them). Since $\frac{S_k}{C}$ is the arithmetic mean of the numbers $\tilde{p}_1, \tilde{p}_2, \dots, \tilde{p}_c$, according to (1)

$$\frac{S_k}{C} \geq \left( \tilde{p}_1 \tilde{p}_2 \dots \tilde{p}_c \right)^{1/C}.$$

Each $a_i$ is a component of exactly $C_{n-1}^{k-1}$ of the numbers $\tilde{p}_1, \tilde{p}_2, \dots, \tilde{p}_c$. So, $\left( \tilde{p}_1 \tilde{p}_2 \dots \tilde{p}_c \right)^{1/C} = P_1^v$, where $v = \frac{C_{n-1}^{k-1}}{C} = \frac{C_{n-1}^{k-1}}{C_n^k} = \frac{k}{n}$. Therefore, $\frac{S_k}{C} \geq P_1^{k/n}$, that is, $S_k \geq CP_1^{k/n}$, which is what was required.

Equality in $(I_2)$ occurs when $k=n$, when $a_1 = \dots = a_n$, or when at least $n-k+1$ numbers from the set $\{a_1, a_2, \dots, a_n\}$ are equal to zero.

Proof of the inequality $(II_2)$. Let us denote by $\tilde{s}_1, \tilde{s}_2, \dots, \tilde{s}_C$ the components of the product $P_k$ (as before $C = C_n^k$). Let us put $q = k^C$ for brevity. On the left side of our inequality, i.e. in the expression $P_k$, we open the brackets. We obtain a sum of $q$ terms, each of which is the product of $C$ numbers from the set $\{a_1, a_2, \dots, a_n\}$, taken one from each $\tilde{s}_i$. In the product of these terms, each $a_i$ contains a component, due to symmetry, the same number of times (we denote this number by $\mu$). Therefore this product is equal to $P_1^\mu$, whence

$$\frac{P_k}{q} = \left( P_1^\mu \right)^{1/q},$$

moreover, equality takes place if and only if all our $q$ terms are equal, which, in particular, occurs for $a_1 = \dots = a_n$; use this, find $\mu$.

Let $a_1 = a_2 = \dots = a_n = 2$. Then in (2) the equality $\tilde{s}_1 = \tilde{s}_2 = \dots = \tilde{s}_C = 2k, P_1 = 2^n$ holds, hence $\frac{(2k)^C}{q} = \left( 2^n \right)^{\frac{\mu}{q}}, 2^C = 2^{\frac{n\mu}{q}}, \mu = \frac{Cq}{n}$.

Substituting this value into (2), we obtain $(II_2)$.

It is clear that equality occurs either when $k=1$, or when $a_1 = \dots = a_n$, or when at least $k$ numbers from the set $\{a_1, a_2, \dots, a_n\}$ are equal to zero.

To prove the inequality $(I_1)$ we will need the Maclaurin inequality. Let's put $S_k = \frac{S_k}{C_n^k}$. Then

$$\bar{S}_1 \geq \bar{S}_2^{\frac{1}{2}} \geq \bar{S}_3^{\frac{1}{3}} \geq \dots \geq \bar{S}_n^{\frac{1}{n}}$$

(if all $a_i$ are positive and not all $a_i$ are the same, then enter a stop sign >).

Proof of this inequality can be found in HLP, page 69 *).

The proof of the inequality $(I_1)$ immediately follows from (3). Indeed $S_k C^{-1} = \bar{S}_k, S_1 n^{-1} = \bar{S}_1$, since $C_n^k = n$. This means that $(I_1)$ takes the form $\bar{S}_1 \geq \bar{S}_k^{\frac{1}{k}}$, and this is contained in (3).

Prove it yourself using Maclaurin's inequality also for $(I_2)$.

The inequality $(II_1)$ is proved in a similar way to $(I_2)$; We leave this proof to the reader.

Condition for equality in $(I_1)$: $a_1 = a_2 = \dots = a_n$ or $k=1$, in $(II_1)$: $a_1 = a_2 = \dots = a_n$ or $k=n$.

*) Another proof sent by M. Rosenberg will be published as solution problem M565.

⟦folio 20⟧

Second series of inequalities

Here $a_1, a_2, \dots, a_n - n$ are positive x numbers. Let us introduce the following notation (we assume that $k \leq n - 1$):

$$\Sigma_i = \frac{\tilde{s}_i}{S_1 - \tilde{s}_i},$$

$$\Pi_i = \frac{\tilde{p}_i}{P_1 - \tilde{p}_i} \left( i = 1, 2, \dots, C = C_n^k \right).$$

We are interested in the boundaries of changes in the value $^*$ $\Sigma_1 + \Sigma_2 + \dots + \Sigma_C, \Pi_1 + \Pi_2 + \dots + \Pi_C, \Sigma_1 \Sigma_2 \dots \Sigma_C, \Pi_1 \Pi_2 \dots \Pi_C$. It turns out that these bounds for the expression $\Sigma_1 \Sigma_2 \dots \Sigma_C$ depend on $k$; exactly:

$$\text{при } k \in \left[ 1, \frac{n}{2} \right] \quad \text{имеем}$$
$$\Sigma_1 \dots \dots \Sigma_C \in \left[ 0, \left( \frac{k}{n-k} \right)^C \right], \quad (\text{III}_1)$$

$$\text{при } k = \frac{n}{2} \quad \text{(если } n \text{ четно)}$$
$$\Sigma_1 \dots \dots \Sigma_C = 1, \quad (\text{III}_2)$$

$$\text{при } k \in \left[ \frac{n}{2}, n-1 \right] \quad \text{имеем}$$
$$\Sigma_1 \dots \dots \Sigma_C \in \left[ \left( \frac{k}{n-k} \right)^C, +\infty \right]. \quad (\text{III}_3)$$

Proof of statement (III$_3$). Let's call relations of the first kind the relations from $n$ numbers $a_1, a_2, \dots, a_n$ to $k$, relations of the second kind - relations from the same numbers to $n-k$. There will also be $C$, since $C_n^k = C_n^{n-k}$. The interior of a relation of the second kind in an arbitrary order, and the sum of the numbers in the $i$th relation of the second kind will be denoted by $\tilde{s}_i'$. It is clear that $\tilde{s}_1' \cdot \tilde{s}_2' \dots \tilde{s}_C' = \left( S_1 - \tilde{s}_1 \right) \times \left( S_1 - \tilde{s}_2 \right) \dots \left( S_1 - \tilde{s}_C \right)$. Let us consider an arbitrary relation of the first kind with number $i - \left( a_{i_1}, a_{i_2}, \dots, a_{i_k} \right)$. From $k > \frac{n}{2}$ it follows that $k > n-k$ and from the numbers included in this relation, it is possible to compose $C_n^{n-k}$ relations of the second kind (with some numbers $\gamma_1, \gamma_2, \dots, \gamma_R$, where $R = C_n^{n-k}$), and each number from the set $\{ a_{i_1}, a_{i_2}, \dots, a_{i_k} \}$ will be included in exactly $C_n^{n-k-1}$ such relations of the second kind. So, $C_n^{n-k-1} \tilde{s}_i = \tilde{s}'_{\gamma_1} + \tilde{s}'_{\gamma_2} + \dots + \tilde{s}'_{\gamma_R}$.

From (1) and (4) it follows that $C_n^{n-k-1} \tilde{s}_i \geq R \left( \tilde{s}'_{\gamma_1} \tilde{s}'_{\gamma_2} \dots \tilde{s}'_{\gamma_R} \right)^{1/R}$. (5)

*) These quantities are interesting for some questions in probability theory (ed.).
