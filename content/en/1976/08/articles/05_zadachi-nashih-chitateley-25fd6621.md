---
id: 1976-8-zadachi-nashih-chitateley-25fd6621
issue: kvant_1976_8
year: 1976
number: "8"
title: Tasks for our readers
rubric: smes
page_first: 18
page_last: 18
tag: GZ6A
lang: en
source: kvant_digital
extraction: vision
content_sha256: 69a13c193526768597efb1552cd31ee064a0a376f5f56ede499e43bca9f0a003
prompt_sha256: draft-1
translated_from: content/ru/1976/08/articles/05_zadachi-nashih-chitateley-25fd6621.md
source_content_sha256: 515c228dbde0bd0032dfaeb9157de7be553467fc38a64554502f88b1e9a1f78c
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio none⟧

in the product of irreducible polynomials:
$$\bar{q} = \bar{q}_1 \cdot \dots \cdot \bar{q}_s.$$
The degree of each polynomial $q_i$ is less than the degree of the polynomial $q$. Then $\bar{u} \cdot \bar{v} = q \cdot \bar{q}_1 \cdot \dots \cdot \bar{q}_s$. By induction, if $\bar{u} \cdot \bar{v}$ is divisible by $\bar{q}_i$ (for each $i$), it follows that either $\bar{u}$ or $\bar{v}$ is divisible by $\bar{q}_i$. Successively canceling the product $u \cdot v$ by $\bar{q}_1, \dots, \bar{q}_i$, we obtain the equality $\tilde{u} \cdot \tilde{v} = q$ ($\tilde{u}$ and $\tilde{v}$ are polynomials obtained from $u$ and $v$ by corresponding reductions to the polynomials $\bar{q}_i$). But $q$ is an irreducible polynomial, so either $\tilde{u} = c \cdot q$ or $\tilde{v} = c \cdot q$. However, these equalities cannot be satisfied (due to the degree of the polynomials under consideration). Therefore, the assumption that $\bar{u} \cdot \tilde{v} \neq 0$, i.e., that $\bar{q} \neq 0$, is incorrect; this means either $\bar{u} = 0$ or $\tilde{v} = 0$, and the statement is proven.

Докажем теперь однозначность разложения в произведение неприводимых многочленов. We have:

$$p_1 \cdot p_2 \cdot \dots \cdot p_l = q_1 \cdot q_2 \cdot \dots \cdot q_s.$$
Putting $u = p_1$, $v = p_2 \cdot \dots \cdot p_l$, we obtain that either $u$ is divisible by $q_1$, and then $p_1 = cq_1$, since $p_1$ is irreducible; or $v$ is divided by $q_1$. In the second case we put $p_2 = u_1$, and $p_3 \cdot \dots \cdot p_l = v_1$; we find that either $p_2 = c \cdot q_1$ or $p_3 \cdot \dots \cdot p_l$ is divisible by $q_1$, and so on until we find the number $i$ for which $p_i = c \cdot q_1$. Doing the same thing with $q_2$, we find a $k$ such that $p_k = c \cdot q_2$, etc., for all $m = 1, \dots, s$. From here we also obtain that $l = s$.

B. Let us show that if the product of pairwise intertropic polynomials $p_1 \cdot p_2 \cdot \dots \cdot p_k$ is equal to the $n$th degree of some polynomial $q$: $p_1 \cdot p_2 \cdot \dots \cdot p_k = q^n$, then each polynomial is the $n$th degree of some polynomial $f_i : p_i = f_i^n$.

Let us decompose the polynomial $q$ into non-conductible polynomials: $q = q_1 \cdot q_2 \cdot \dots \cdot q_m$. Then $q^n = q_1^n \cdot q_2^n \cdot \dots \cdot q_m^n$. Take the polynomial $p_1$, and let $p_{11}$ be an irreducible polynomial included in its expansion. Due to the uniqueness of the decomposition into irreducible polynomials, $p_{11}$ coincides with some polynomial $q_l$, that is, the polynomial $p_1$ is divisible by $q_l$. But the polynomials $p_i$, where $i \neq 1$, are not divisible by $q_l$ (since $p_1, \dots, p_k$ are pairwise intertrophic), and then the polynomial $p_1$ is also divisible by $q_l^n$, that is, $p_1 = q_l^n \cdot \bar{p}_1$. Applying similar reasoning to the polynomial $\bar{p}_1$, we find that $p_1 = q_l^n \cdot q_s^n \cdot \dots \cdot q_r^n = f_i^n$, where $f_1 = q_l \cdot q_s \cdot \dots \cdot q_r$. We will do the same with the remaining polynomials $p_i$; $i \neq 1$.

Tasks
our
readers

1. Given a triangle $ABC$ with side $a, b, c$ and medians $m_a, m_b, m_c$. Prove her equality

a) $\frac{m_a^2}{a^2} + \frac{m_b^2}{b^2} + \frac{m_c^2}{c^2} \geq \frac{9}{4}$;

b) $\frac{m_a}{a} + \frac{m_b}{b} + \frac{m_c}{c} \geq \frac{3\sqrt{3}}{2}$.

When is equality achieved in these herequalities?

2. Given an arbitrary convex quadrilateral $ABCD$ (possibly degenerate - two of its vertices can coincide). Points $P, K, S, N$ are the midpoints of side $AB, BC, CD, DA$, respectively. Let $(AK) \cap (BN) = L; (KD) \cap (NC) = M; (PC) \cap (BS) = Q; (AS) \cap (PD) = T$. Prove that

a) $\frac{S_{KMN}}{S_{ABCD}} \leq \frac{1}{3}$;

b) $\frac{1}{3} \leq \frac{S_{KMN} + S_{PQST}}{S_{ABCD}} \leq \frac{1}{2}$.

3. Again $ABCD$ is an arbitrary convex quadrilateral, points $E, F, G, H$ are the midpoints of side $AB, BC, CD, DA$, respectively. Let's denote it by $(AF) \cap (BG) = K; (BG) \cap (CH) = L; (CH) \cap (DE) = M; (DE) \cap (AF) = N$. Prove that

$$\frac{1}{6} \leq \frac{S_{KLMN}}{S_{ABCD}} \leq \frac{1}{5}.$$

V. Matizen
(Novosibirsk)
