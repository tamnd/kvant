---
id: 1977-4-shirshov-ob-uravnenii-cnm-cn1m1-a5fbaa84
issue: kvant_1977_4
year: 1977
number: "4"
title: 关于方程 C_n^m = C_n+1^m-1
authors:
  - Ширшов А. И.
rubric: osnovnye-stati
page_first: 23
page_last: 24
page_labels: 21-22
tag: XJIO
lang: zh
source: kvant_digital
extraction: vision
content_sha256: a8f0e0314edfdbaeb94fa87b7e6c24ce94b5df4d371c94f73b7eb501cd850070
prompt_sha256: draft-1
translated_from: content/ru/1977/04/articles/07_shirshov-ob-uravnenii-cnm-cn1m1-a5fbaa84.md
source_content_sha256: 5e62f3bf2a8f73fcf648302c7e5d545f6df3f4c43868fee98ba718aaeb5c433c
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 21⟧

关于方程
$$C_n^m = C_{n+1}^{m-1}$$

A·希尔绍夫

我通过考虑帕斯卡三角形的第 14 条线得出了标题中所示的方程：
1, 14, 91, 364, 1001, 2002, 3003, 3432, 3003, 2002, 1001, 364, 91, 14, 1.

帕斯卡三角形在教科书《代数与基本分析9》的第7和8段中讨论过。

让我们为那些还不熟悉他的人简单介绍一下他。

在帕斯卡三角形的第n行中，第m-m处有数字$C_n^m$，并且行和每行中的数字的编号都从零开始（帕斯卡三角形的前15行在图处给出）。

要理解这篇文章，只需要了解数字$C_n^m$的一件事就足够了：
$$C_n^m = \frac{n!}{m!(n-m)!}$$

($n! = 1 \cdot 2 \cdot \dots \cdot n; 0! = 1$)。由(1)容易推出
$$C_n^m + C_{n+1}^{m+1} = C_{n+1}^{m+1}.$$

利用这种对应关系，您可以构造帕斯卡三角形，而无需使用公式（1）（参见图）。

第14行引人注目的是1001+2002=3003，即
$$C_{14}^4 + C_{14}^5 = C_{14}^6.$$

鉴于(2)，这个等式可以重写如下：
$$C_{15}^5 = C_{14}^6.$$

等式（3）表明对（6, 14）是标题中所示方程的解。

该方程的解还有哪些其他数字对？文章给出了这个问题的答案。为了让答案更漂亮，我们将方程中的 m 替换为 y，将 n 替换为 x-1。那么下面的定理成立。方程 $C_x^{y-1} = C_x^{-1}$ 的所有解都具有以下形式
$$x_k = \gamma_{2k} \gamma_{2k+1}; \quad y_k = \gamma_{2k-1} \gamma_{2k}, \quad k = 1, 2, 3, \dots, \text{еде } \gamma_n - n-\text{й член последовательности Фибоначчи}^*): 1, 1, 2, 3, 5, 8, 13, 21, 34, \dots$$

证明。
1. 让我们使用公式（1）并重写我们的方程：
$$\frac{x!}{(y-1)!(x-y+1)!} = \frac{(x-1)!}{y!(x-y-1)!}.$$

经过明显的变换后，它简化为以下形式：
$$(x-y+1)(x-y)=xy.$$

让我们用 w 表示数字 x 和 y 的最公约数。那么 x=uw, y=vw，其中 u 和 v 互质。将x、y的表达式代入式(4)，用w消去后，可得$(u-v)[(u-v)w+1]=uvw.$

数字 u 和 v 互质。因此 u-v 和 uv 也是互质的。数 w 和 $(u-v)w+1$ 也互质。但以下等式必须成立：
$$\begin{cases} (u-v)w+1=uv, \\ u-v=w. \end{cases}$$

*) 对于此序列 $\gamma_n = \gamma_{n-1} + \gamma_{n-2}$，n > 2。

⟦folio 22⟧

该系统等价于以下系统：

$$\begin{cases} v^2 + vw - w^2 = 1, \\ v + w = u. \end{cases}$$

因此，我们方程的解与方程的解一致

$$v^2 + vw - w^2 = 1$$

在自然数中。

2. 让我们做三个简单的改变来求解方程（7）。令 $\langle v, w \rangle$ 为方程 (7) 的解。然后

a) $v$ 和 $w$ 互质；
b) 如果$v = w$，则$v = w = 1$；
c) $v \leq w < 2v$;
d) $\langle v + w, v + 2w \rangle$ 和$\langle 2v - w, w - v \rangle$ 对是方程的解。

回想一下，$v$和$w$是自然数。

c）由等式$w = \frac{v + \sqrt{5v^2 - 4}}{2}$得出，如果将（7）视为$w$的方程，则得到，并且d）可以通过将相应的对代入方程（7）来验证。

使用变换

$$\langle v, w \rangle \Rightarrow \langle v + w, v + 2w \rangle,$$

基于解$\langle 1, 1 \rangle$，我们构建了一系列解$\langle 2, 3 \rangle, \langle 5, 8 \rangle, \langle 13, 21 \rangle, \langle 34, 55 \rangle, \dots$。

书面解决方案的形式为

$$v_h = \gamma_{2h-1}, w_h = \gamma_{2h}.$$

让我们证明方程(7)没有其他解。让我们假设$\langle v, w \rangle$对是方程（7）的解。让我们证明它是 (8) 对之一。
