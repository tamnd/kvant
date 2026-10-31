---
id: 1972-2-kamnev-irratsionalnost-summyi-radikalov-0d2781f5
issue: kvant_1972_2
year: 1972
number: "2"
title: Irrationality of the sum of radicals
authors:
  - Камнев П. Н.
rubric: osnovnye-stati
page_first: 28
page_last: 28
page_labels: "26"
tag: L24N
lang: en
source: kvant_digital
extraction: vision
content_sha256: 342465c2852874ccf4770561142f82b80c7925ee26b4f64878835052baf60bc5
prompt_sha256: draft-1
translated_from: content/ru/1972/02/articles/06_kamnev-irratsionalnost-summyi-radikalov-0d2781f5.md
source_content_sha256: 6d7f0a007fe3996282064e9351d825faa7ab6185657a7cd5d3e6971eee41cec5
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 26⟧

Recall that a number is called rational if it is equal to $\frac{m}{n}$, where $n$ and $m$ are integers, and rational otherwise. Everyone knows that the number $\sqrt{2}$ is irrational. It is easy to prove a more general statement: if the natural number $k$ is not a perfect square, then the number $\sqrt{k}$ is irrational. Note that $k$ can be represented as $b^2a$, where $a$ and $b$ are natural numbers, and $a$ is not divisible by the square of an integer (as they say, “free from squares”), that is, $a$ is equal to a prime number or the product of different prime numbers: $a=p_1p_2...p_r$; $r \ge 1$. The statement that the number $\sqrt{k}=b\sqrt{a}$ is irrational properties the following: there are no non-zero integers $b_1$ and $b_2$ such that $b_1\sqrt{a}+b_2=0$. Indeed, if such $b_1$ and $b_2$ exist, then $b_1^2a=b_2^2$. But this equality contradicts the theorem on the uniqueness of the decomposition of a natural number into prime factors: $p_1$ enters the right side to an even degree, and the left side to an odd degree.

In this note we will prove that if $b_1, b_2,..., b_n$ are non-zero integers, $a_1, a_2,..., a_n$ are square-free natural numbers, then $b_1\sqrt{a_1}+b_2\sqrt{a_2}+\dots+b_n\sqrt{a_n} \neq 0$.

Up to $n=4$ this is easy to prove by contradiction by raising both parts (grouped approaches in a manner) into a square several times. In the general case, we will carry out a proof of induction on the number of distinct prime numbers $p_1,..., p_N$ that make at least one of the numbers $a_i$. As is often the case, it is more convenient to prove by induction a stronger statement (interesting in itself):

there are integers $c_1, d_1, c_2, d_2,..., c_e, d_e$ such that $d_i \neq 0$, $c_i \ge 1$, all prime divisors of the numbers $c_i$ are contained among the numbers $p_1,..., p_N$ and the product

$$\left(d_1\sqrt{c_1}+\dots+d_e\sqrt{c_e}\right)\times\left(b_1\sqrt{a_1}+\dots+b_n\sqrt{a_n}\right)$$

is a non-zero integer.

Let us denote $b_1\sqrt{a_1}+\dots+b_n\sqrt{a_n}$ by $S$, and eliminate the sum $d_1\sqrt{c_1}+\dots+d_e\sqrt{c_e}$ by $S'$.

If $N=1$, then s has the form $b_1\sqrt{p_1}+b_2\sqrt{p_2}-b_2$: we proved above that $SS'=b_1^2p_1-b_2^2 \neq 0$. Let us now assume that $N \ge 2$ and that our statement is valid for all smaller values ​​of $N$.

We will denote by letters $S_1, S_2,..., S_8$ sums of the form $\beta_1\sqrt{\alpha_1}+\dots+\beta_m\sqrt{\alpha_m}$, where $\beta_i$ are integers, $\alpha_i$ are square-free natural numbers, all of whose prime divisors are contained among the numbers $p_1,..., p_{N-1}; S_1, S_2,..., S_8$, unless otherwise stated, can be equal to zero.

The sum $S$ can be written as $S=S_1+S_2\sqrt{p_N}$, where $S_2 \neq 0$. By the induction hypothesis, there is a sum $S_3$ such that $f=S_3S_2$ is a nonzero integer. Produced
