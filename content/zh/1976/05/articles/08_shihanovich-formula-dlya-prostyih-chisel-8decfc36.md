---
id: 1976-5-shihanovich-formula-dlya-prostyih-chisel-8decfc36
issue: kvant_1976_5
year: 1976
number: "5"
title: 素数的公式
authors:
  - Шиханович Ю. А.
rubric: smes
page_first: 44
page_last: 44
page_labels: "42"
tag: TQEU
lang: zh
source: kvant_digital
extraction: vision
content_sha256: b5ef5fa0ca0f8ee88ca79a1e79c16c2aa566ee283ee2240b033db0d01f6d09b9
prompt_sha256: draft-1
translated_from: content/ru/1976/05/articles/08_shihanovich-formula-dlya-prostyih-chisel-8decfc36.md
source_content_sha256: 5557cf9ad53fee213edb31bedf31801136e9596d0b32f1d42f3b10fa8f53c79c
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 42⟧

公式
对于素数

让我们用 $p_n$ 表示按升序排列的第 $(n+1)$ 个质数：$p_0 = 2, p_1 = 3, p_2 = 5, p_3 = 7, p_4 = 11, p_5 = 13$ 等。

人们普遍认为没有公式可以表达公式（1），可见构造的$a$就是在纸张中传播的正波长！

所以，实验很清楚：从振荡管的一端，一个圆波在纸张上传播，被纸张边缘反射，相位不变；入射波和反射波是正确的，因此发生干涉；锰钾晶体从振荡强度的最大值（驻波的波腹）处脱落，并在最小值（节点）处聚集，其完美代表了双曲线族。

总之，我们为您提供了一个不那么普通的任务：在文章中找到那些没有证明的陈述，并尝试通过实验证明它们。

$$sg(n) = \begin{cases} 1, \text{ если } n > 0, \\ 0, \text{ если } n \leqslant 0, \end{cases}$$

这样的公式是如何写出来的（右上角，这里$E(x)$是数字$x$的整数部分）。莫斯科甜点班老师V. Gugin也给编辑发了一份类似的配方。

问题是这样的公式没什么用处。首先，使用它们的计算并不比使用Eratovsen sieve算法的计算短（«Kvant»，1973年，第4期，第1页。 72 和 1974 年，没有。 1，p。 77）。其次，在他们的帮助下，很难研究一组“无穷大”素数的“行为”（即，在 $n \rightarrow +\infty$ 或者，正如数学家所说，一组素数的“渐近行为”。

不过，显然，给出的公式可以满足一小部分读者的需求«Kvant»。

如何证明所提出的公式？在数论中，$\pi(m)$表示不超过$m$的素数个数。易于组装

$$sg(n + 1 - \pi(m)) = \begin{cases} 1, \text{ если } m < p_n, \\ 0, \text{ если } m \geqslant p_n. \end{cases}$$

现在让$\mu$是$p_n$的任意“上限估计”，即对于所有$n$我们有$p_n \leqslant \mu(n)$的函数。

然后

$$p_n = \sum_{m=0}^{n^2+1} sg(n + 1 - \pi(m)).$$

进一步让 $\chi - \chi_{\text{карактическая функция}}$ 可表示，即一个函数使得

$$\chi(k) = \begin{cases} 1, \text{ если } k - \text{ простое число}, \\ 0, \text{ если } k - \text{ составное число}. \end{cases}$$

明显地，

$$\pi(m) = \sum_{k=2}^{m} \chi(k).$$

然后

$$p_n = \sum_{m=0}^{n^2+1} sg(n + 1 - \sum_{k=2}^{m} \chi(k)).$$

为了从式（1）中得到具体的公式，需要将函数$x$和$\mu$的表达式代入其中。

我们的公式是根据$\mu(n) = n^2 + 1$的公式（1）精确得出的（在数论中已经证明$p_n \leqslant n^2 + 1$对于所有$n$）并且

$$\chi(k) = \frac{[(k - 1)!]^2 - k \cdot E \left( \frac{[(k - 1)!]^2}{k} \right)}{2}.$$

公式(2)由威尔逊定理得到：如果$k - \text{ простое число},$则$(k - 1)! + 1$能被$k$整除。
