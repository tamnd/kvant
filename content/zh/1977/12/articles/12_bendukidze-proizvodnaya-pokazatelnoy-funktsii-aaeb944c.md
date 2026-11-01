---
id: 1977-12-bendukidze-proizvodnaya-pokazatelnoy-funktsii-aaeb944c
issue: kvant_1977_12
year: 1977
number: "12"
title: 指数函数的导数
authors:
  - Бендукидзе А. Д.
rubric: po-stranitsam-shkolnyh-uchebnikov
rubric_sub: По страницам школьных учебников
page_first: 42
page_last: 44
page_labels: 40, 42
tag: GJO6
lang: zh
source: kvant_digital
extraction: vision
content_sha256: cb8f2b5c6bf096e808ae15b3af7fc3b5d710a078ae4261c90bba645a2e41fe53
prompt_sha256: draft-1
translated_from: content/ru/1977/12/articles/12_bendukidze-proizvodnaya-pokazatelnoy-funktsii-aaeb944c.md
source_content_sha256: 439cc2392ec4e572bf16b8f6d6917efd686bc257371de1bb71112fd8d76ec073
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 40⟧

A·本杜基泽

函数的导数指数

“函数$\exp_{10}$的图形看起来像一条“平滑”曲线。在本章中，该图形在每个点处都有一条切线，其斜率为正。因此，很自然地假设函数$\exp_{10}$对于任何参数值都有正积。这个假设是正确的，正如在更完整的分析过程中所证明的那样。我们将接受函数$\exp_{10}$在点0处具有正积。换句话说，让我们假设有一个限制

$$\lim_{\Delta x \to 0} \frac{10^0 + \Delta x - 10^0}{\Delta x} = \lim_{\Delta x \to 0} \frac{10^{\Delta x} - 1}{\Delta x} \cdot (1)$$

接下来的一切都将相对简单地从这里进行。

第109段是这样开始的——“函数的导数指标。数字$e$”十年级教科书——“代数和分析的开始”。此外，在本段中，给出了函数$\exp_{10}$的导数公式的选择，以及函数$\exp_a$的导数的更一般公式，其中$a > 0, a \neq 1$。

事实上，所有这一切都非常简单地从极限（1）的存在性得出。

但好奇的学生，当然是读者«Kvant»，可能会有一个问题：“那么，极限（1）的存在性和正性如何证明？”正如手册中所述，这一事实的证明可以在完整的分析课程中找到。证明了一个更普遍的事实，即：对于任何正数$a \neq 1$，都有一个极限

$$\lim_{h \to 0} \frac{a^h - 1}{h},$$

如果$a > 1$为正，如果$0 < a < 1$为负。但事实是，这一点的证明通常依赖于许多初步引理和定理，而这些引理和定理并不总是容易理解。建议给出不确定的证明。下面给出这样的证明。

1. 令 $a$ 为大于 1 的任意数。考虑序列 $(x_n)$，其通项由以下公式给出

$$x_n = n \left( \frac{1}{a^n} - 1 \right).$$

让我们证明$(x_n)$是一个加法序列并且它的极限是正数。

让我们从收敛问题开始，检查一下维尔斯特拉斯定理的条件。对于任何自然$n$

$$a^{-\frac{1}{n(n+1)}} - 1 > -1,$$

根据伯努利不等式的 posnomu

$$a^{-\frac{1}{n}} = \left( 1 + \left( a^{-\frac{1}{n(n+1)}} - 1 \right) \right)^{n+1} > 1 + (n+1) \left( a^{-\frac{1}{n(n+1)}} - 1 \right).$$

将这个不等式乘以 $a^{\frac{1}{n}}$，我们得到

$$1 > a^{\frac{1}{n}} + (n+1) \left( a^{\frac{1}{n+1}} - a^{\frac{1}{n}} \right)$$

或者，有什么相同之处，

$$n a^{\frac{1}{n}} + 1 > (n+1) a^{\frac{1}{n+1}}.$$

很容易将这个不等式表示为以下形式：

$$n \left( a^{\frac{1}{n}} - 1 \right) > (n+1) \left( a^{\frac{1}{n+1}} - 1 \right).$$

⟦folio 42⟧

因此我们有
$$\begin{cases}
n \left( \frac{1}{n+1} - 1 \right) < \frac{a^h - 1}{h} < \\
< (n+1) \left( \frac{1}{n} - 1 \right), \text{ если } h > 0, \\
\frac{n \left( \frac{1}{n+1} - 1 \right)}{a^{n+1}} < \frac{a^h - 1}{h} < \\
< (n+1) \left( \frac{1}{n} - 1 \right), \text{ если } h < 0.
\end{cases}$$

让我们引入以下符号：
$$n \left( \frac{1}{n+1} - 1 \right) = u_n,$$
$$(n+1) \left( \frac{1}{n} - 1 \right) = v_n,$$
$$\frac{u_n}{a^{n+1}} = u'_n, \quad \frac{v_n}{a^{n+1}} = v'_n.$$

那么由此产生的不平等将采取以下形式：
$$\begin{cases}
u_n < \frac{a^h - 1}{h} < v_n, \text{ если } h > 0, \\
u'_n < \frac{a^h - 1}{h} < v'_n, \text{ если } h < 0,
\end{cases}$$

对于任何 $h$，模 $1/n$，

$$u'_n < \frac{a^h - 1}{h} < v_n.$$ (5)

现在让$n \rightarrow +\infty$。然后
$$\lim_{n \rightarrow +\infty} u_n = \lim_{n \rightarrow +\infty} v_n = \lim_{n \rightarrow +\infty} u'_n =$$
$$= \lim_{n \rightarrow +\infty} v'_n = \varphi(a).$$

事实上，自从
$$u_n = (n+1) \left( \frac{1}{n+1} - 1 \right) - \left( a^{n+1} - 1 \right) = x_{n+1} - \left( a^{n+1} - 1 \right),$$
$$v_n = n \left( a^{n+1} - 1 \right) + \left( a^{n+1} - 1 \right) = x_n + \left( a^{n+1} - 1 \right),$$

然后根据等式(3)和(4)
$$\lim_{n \rightarrow +\infty} u_n = \lim_{n \rightarrow +\infty} x_{n+1} - \lim_{n \rightarrow +\infty} \left( a^{n+1} - 1 \right) =$$
$$= \lim_{n \rightarrow +\infty} x_{n+1} = \varphi(a).$$

进一步，根据同样的等式(4)
$$\lim_{n \rightarrow +\infty} a^n = \lim_{n \rightarrow +\infty} a^{n+1} = 1,$$
因此
$$\lim_{n \rightarrow +\infty} u'_n = \lim_{n \rightarrow +\infty} \frac{u_n}{a^{n+1}} =$$
$$= \lim_{n \rightarrow +\infty} u_n = \varphi(a), \lim_{n \rightarrow +\infty} v'_n =$$
$$= \lim_{n \rightarrow +\infty} \frac{v_n}{a^{n+1}} = \varphi(a).$$

请注意，序列 $\{v_n\}$ 单调杀死，$\{u'_n\}$ 返回。

因此，我们得出以下结论（参见图）：如果$0 < |h| \leq 1$，那么我们感兴趣的关系，即$(a^h - 1):h$，可以被“压缩”到区间$]u_n, v'_n$[(if$h > 0$)或区间$]u'_n, v'_n$[(if$h < 0$)，并且有以下趋势： $n \rightarrow +\infty$ 这些区间的末端趋向于相同的数字$\varphi(a)$。很明显，否则比率趋于相同的数字，即
$$a > 1 \Rightarrow \lim_{h \rightarrow 0} \frac{a^h - 1}{h} = \varphi(a) > 0.$$

事实上，任何$\varepsilon > 0$都是可能的，我们将寻找一个$\delta > 0$使得
$$|h| < \delta \Rightarrow |\varphi(a) - \frac{a^h - 1}{h}| < \varepsilon.$$

（根据函数极限的定义，这意味着$\lim_{h \rightarrow 0} (1/h) \times (a^h - 1) = \varphi(a)$）。

由于序列$\{u'_n\}$和$\{v'_n\}$收敛于$\varphi(a)$，而且，第一个增加，第二个杀死，那么对于给定的数字$\varepsilon > 0$，可以找到一个数字$N$，使得
$$-\varepsilon < u'_N - \varphi(a) \text{ и } v_N - \varphi(a) < \varepsilon.$$ (6)

现在让我们取$\delta = 1/N$。如果$|h| < \delta = 1/N$，那么我们有（参见（5））不等式
