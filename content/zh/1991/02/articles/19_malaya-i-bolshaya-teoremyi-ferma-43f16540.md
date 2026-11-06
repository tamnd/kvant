---
id: 1991-2-malaya-i-bolshaya-teoremyi-ferma-43f16540
issue: kvant_1991_2
year: 1991
number: "2"
title: 费马小定理和大定理
rubric: smes
page_first: 66
page_last: 66
page_labels: "64"
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 456967e2f1e137f62f4d26a38b7643e152164a5bd4d0708568b16bef9f36aaf8
prompt_sha256: draft-1
translated_from: content/ru/1991/02/articles/19_malaya-i-bolshaya-teoremyi-ferma-43f16540.md
source_content_sha256: d1c23e7747208f2e9a279d66dc126fa3e38ecc981ac46ff2538a8eb4ec442320
translation_model: draft
translation_run: zh-draft-2026-11-06
translation_quality: draft
---

⟦folio 64⟧

费马小定理和大定理

1970-71 年波兰数学奥林匹克竞赛。 It is proposed to prove the following statements about Fermat's equations: if the natural numbers $x, y, z$ satisfy the condition $x^n+y^n=z^n$, then $x \geq n^*$).

*) 这是 S. Strashevich 和 E. Brovkin 所著《波兰数学奥林匹克》一书中的第 130 题。 M.：米尔，1978。

（回想一下费马的“大定理”指出，这样的解决方案 $n>2$ 不存在，尚未被证明或反驳；很容易看出，仅仅为了简单的目的而研究它就足够了 $n$).

我们的读者 V.P. Kuznetsov from the village of Mamontovka near Moscow sent the following elegant reasoning, which makes it possible to confirm this result, namely, to prove that if $p$ is prime, $p>3$ and $x^p+y^p=z^p$ for some natural $x, y, z$, then $x>6p$.

让我们使用费马小定理：如果$p$是素数，那么对于任何整数$a$，$a^p-a$可以被$p$整除。请注意，如果$p>3$是奇数，则$a^{p-1}-1$可被$a^2-1=(a-1) \times (a+1)$整除，因此$a^p-a$可被三个连续数$(a-1)a(a+1)$的乘积整除，因此可被6整除；如果 $p>3$ 是素数，则 6 与 $p$ 互质，因此 $a^p-a$ 可以被 6p 整除。如果$x^p+y^p=z^p$，则非常$x<z, y<z, x+y>z$，并且表达式$x+y-z=z^p-z-(x^p-x)$ - $(y^p-y)$ 必须能被 6p 整除。从$x+y-z \geq 6p$和$z-y>0$开始，我们得到$x>6p$。
