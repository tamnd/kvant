---
id: 1991-2-malaya-i-bolshaya-teoremyi-ferma-43f16540
issue: kvant_1991_2
year: 1991
number: "2"
title: Fermat's Little and Great Theorems
rubric: smes
page_first: 66
page_last: 66
page_labels: "64"
lang: en
source: kvant_digital
extraction: vision
content_sha256: e6d96439d96f4cf428f62cbfa036acd377def5fd5914af257fc41114b388a440
prompt_sha256: draft-1
translated_from: content/ru/1991/02/articles/19_malaya-i-bolshaya-teoremyi-ferma-43f16540.md
source_content_sha256: d1c23e7747208f2e9a279d66dc126fa3e38ecc981ac46ff2538a8eb4ec442320
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 64⟧

Fermat's Little and Great Theorems

At the Polish Mathematical Olympiad 1970-71. It is proposed to prove the following statements about Fermat's equations: if the natural numbers $x, y, z$ satisfy the condition $x^n+y^n=z^n$, then $x \geq n^*$).

*) This is problem 130 from the book “Polish Mathematical Olympids” by S. Strashevich and E. Brovkin. M.: Mir, 1978.

(Recall that Fermat’s “Last Theorem” that such solutions do not exist for $n>2$ has not yet been proven or disproved; it is easy to see that it is enough to study it only for simple $n$).

Our reader V.P. Kuznetsov from the village of Mamontovka near Moscow sent the following elegant reasoning, which makes it possible to confirm this result, namely, to prove that if $p$ is prime, $p>3$ and $x^p+y^p=z^p$ for some natural $x, y, z$, then $x>6p$.

Let us use Fermat's Little Theorem: if $p$ is prime, then $a^p-a$ is divisible by $p$ for any integer $a$. Note that if $p>3$ is odd, then $a^{p-1}-1$ is divisible by $a^2-1=(a-1) \times (a+1)$, so $a^p-a$ is divisible by the product of three consecutive numbers $(a-1)a(a+1)$, and therefore divisible by 6; and if $p>3$ is prime, then 6 is coprime to $p$, hence $a^p-a$ is divisible by 6p. If $x^p+y^p=z^p$, then very $x<z, y<z, x+y>z$, and the expression $x+y-z=z^p-z-(x^p-x)$ - $(y^p-y)$ must be divisible by 6p. Since $x+y-z \geq 6p$ and $z-y>0$, we get $x>6p$.
