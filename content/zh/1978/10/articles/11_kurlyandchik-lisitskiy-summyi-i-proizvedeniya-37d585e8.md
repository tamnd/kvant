---
id: 1978-10-kurlyandchik-lisitskiy-summyi-i-proizvedeniya-37d585e8
issue: kvant_1978_10
year: 1978
number: "10"
title: 和与积
authors:
  - Курляндчик Л. Д.
  - Лисицкий А. Д.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 33
page_last: 38
page_labels: 31, 32, 33, 34, 36
tag: YV0W
lang: zh
source: kvant_digital
extraction: vision
content_sha256: bcf92b2a58c6063d196b3d52f943a4388ba370f41d02f16c7c4ed1ebed71e8ca
prompt_sha256: draft-1
translated_from: content/ru/1978/10/articles/11_kurlyandchik-lisitskiy-summyi-i-proizvedeniya-37d585e8.md
source_content_sha256: d340c61fc65a50b5870a361dae1a98d95aa1c38e7d1ab91e7e431a9f05157d41
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 31⟧

通常，我们使用符号简单地编写公式

$$\sum_{k=1}^{n} a_k = a_1 + a_2 + \dots + a_n,$$

$$\prod_{k=1}^{n} b_k = b_1 \cdot b_2 \cdot \dots \cdot b_n,$$

$$n! = 1 \cdot 2 \cdot \dots \cdot n.$$

我们建议那些尚未学会如何使用它们来更详细地描述计算的人。

1. 残差极值

该标题由以下等式解释：

$$(a_2 - a_1) + (a_3 - a_2) +$$

$$+ (a_4 - a_3) + \dots + (a_n - a_{n-1}) +$$

$$+ (a_{n+1} - a_n) = a_{n+1} - a_1$$

(1)

或者

$$\sum_{k=1}^{n} (a_{k+1} - a_k) = a_{n+1} - a_1,$$

(1')

由此，通过不同方式选择序列$(a_k)$，我们可以得到很多不太好的等式。

例1. 代入$a_k = -\frac{1}{k}$，得到$\sum_{k=1}^{n} \frac{1}{k(k+1)} = \frac{n}{n+1}$；很难找到一本不包含这个例子的代数问题书。

示例 2. 输入 $a_k = k(k-1)d/2$。由于 $a_{k+1} - a_k = kd$，等式 (1) 采用 $\sum_{k=1}^{n} kd = (n+1) \cdot n \cdot d/2$ 的形式。通过将 $a - d$ 添加到迹和的每个成员上，并将 $n(a - d)$ 添加到右侧的和中，我们得到了众所周知的等差数列 $n$ 项之和的公式：$a + (a + d) + \dots + (a + (n-1)d) = n(a - d) + (n+1)nd/2 = na + n(n-1)d/2$。

练习1. 将$a_k = (2k-1)^3/24$代入(1)，得到$\sum_{k=1}^{n} k^2$的公式。

⟦folio 32⟧

示例 3. 令 $m$ 为自然数。让我们输入$a_k = \frac{1}{(m+2)} \times (k-1)k(k+1) \dots (k+m)$。然后$a_{k+1} - a_k = \frac{1}{m+2}k \cdot (k+1) \dots (k+m) + 1 + m) - \frac{1}{m+2}(k-1)k \dots (k+m) = k(k+1) \dots (k+m)$。在这种情况下，等式（1）写成如下：
$$\sum_{k=1}^{n} k(k+1) \dots (k+m) = \frac{1}{m+2}n(n+1) \dots (n+m+1).$$
等式（1）可以用另一种方式使用。让我们需要证明
$$\sum_{k=1}^{n} f(k) = g(n).$$
我们来尝试证明一下等式
$$g(k) - g(k-1) = f(k).$$
如果我们成功了，那么（2）也将被证明。事实上，考虑辅助序列
$$\left\{ \begin{array}{l} a_1 = 0, \\ a_{k+1} = g(k). \end{array} \right.$$
对于这个序列，等式 (1) 的形式为
$$\sum_{k=1}^{n} [g(k) - g(k-1)] = g(n),$$
鉴于(3)，其等价于(2)。
例如，让我们用这种方式证明等式
$$\sum_{k=1}^{n} C_{l+k-1}^{l+1} = C_{l+n}^{l+1}.$$
根据已经说过的内容，为此检查等式 $C_{l+n}^{l+1} - C_{l+n-1}^{l+1} = C_{l+n-1}^{l+1}$ 或 $C_{l+n-1}^{l+1} + C_{l+n-1}^{l+1} = C_{l+n}^{l+1}$ 就足够了，它是从众所周知的点 $C_n^m + C_n^{m+1} = C_n^{m+1}$ 得出的（“代数和分析原理 9”，第 8 段）。在第3节中，我们将以不同的方式证明第(4)点。
以上所有内容都适用于工作。让我们首先写出等式（1）的乘法模拟：
$$\frac{a_2}{a_1} \cdot \frac{a_3}{a_2} \cdot \frac{a_4}{a_3} \dots \frac{a_n}{a_{n-1}} \cdot \frac{a_{n+1}}{a_n} = \frac{a_{n+1}}{a_1}$$
(*) $n!!$ 表示 1 到 $n$ 之间的自然数的乘积，它们与 $n$ 具有相同的奇偶性。例如，$8!! = 2 \cdot 4 \cdot 6 \cdot 8, 9!! = 1 \cdot 3 \cdot 5 \cdot 7 \cdot 9$。

⟦folio 33⟧

4. $$\sum_{k=1}^{n} k \cdot k! = (n+1)! - 1.$$
5. $$\prod_{k=1}^{n} k^k \cdot k! = (n!)^{n+1}.$$
6. $$a_1 + (a_1+1) a_2 + (a_1+1) (a_2+1) \times a + \ldots + (a_1+1) (a_2+1) \ldots (a_{n-1}+1) \times a_n = (a_1+1) (a_2+1) \ldots (a_n+1) - 1.$$
7. $$\sum_{k=1}^{n} \frac{1}{k(k+1) \ldots (k+m)} = \frac{1}{m} \left( \frac{1}{m!} - \frac{1}{(n+1)(n+2) \ldots (n+m)} \right).$$
8. $$\sum_{k=1}^{n} \frac{x^k \cdot k!}{(x+1)(2x+1) \ldots (kx+1)} = \frac{1}{x-1} \frac{x^{n+1}(n+1)!}{(x+1) \ldots (nx+1)} + \frac{x}{1-x}.$$
9. $$\sum_{k=0}^{n-1} \frac{p_0 \cdot p_1 \ldots p_k q_{k+1}}{(p_1+q_1) \ldots (p_{k+1}+q_{k+1})} = 1 - \frac{p_1 p_2 \ldots p_n}{(p_1+q_1) \ldots (p_n+q_n)}.$$
（这里$(p_k)$和$(q_k)$是两个序列，$p_0 = 1$。）
不幸的是，该指示方法仅适用于总和$$\sum_{k=1}^{n} b_k$$中的项$b_k$不依赖于$n$的情况。在下一节中，我们将证明其中项取决于 $n$ 的等式。

2. 来回法

这个方法的名称（但不是方法本身）是作者的发明。数学史家声称，正是在他的帮助下，小高苏迪快速求出了从1到100的自然数之和，从而击败了学校老师。让我们用例子来演示一下“来回”方法的用法。

让我们证明对于奇数 $n$
$$\sum_{k=0}^{n} (-1)^k \sqrt{C_n^k} = 0.$$
让我们用两种方式写出总和$S_n$
$$S_n = \sqrt{C_n^0} - \sqrt{C_n^1} + \sqrt{C_n^2} - \ldots + \sqrt{C_n^{n-1}} - \sqrt{C_n^n} \text{ (туда)},$$

$$S_n = -\sqrt{C_n^0} + \sqrt{C_n^1} + \ldots - \sqrt{C_n^n} + \sqrt{C_n^0} \text{ (назад)}$$

在我们的求和中，$$\sqrt{C_n^n}$$之前有一个负号，因为$n$是奇数。让我们将两个结果表达式相加：

$$2S_n = \left( \sqrt{C_n^0} - \sqrt{C_n^n} \right) + \left( -\sqrt{C_n^1} + \sqrt{C_n^{n-1}} \right) + \ldots + \left( -\sqrt{C_n^n} + \sqrt{C_n^0} \right).$$

很容易看出每个括号都包含一个零，因为$C_n^m = C_n^{n-m}$。因此$2S_n = 0$，因此$S_n = 0$。

另一个例子：

$$\sum_{k=0}^{2n+1} \frac{(-1)^k}{C_{2n+1}^k} = 0.$$

它的工作原理是一样的：

$$S_n = \frac{1}{(C_{2n+1}^0)^2} - \frac{1}{(C_{2n+1}^1)^2} + \ldots - \frac{1}{(C_{2n+1}^n)^2} \text{ (туда)},$$

$$S_n = -\frac{1}{(C_{2n+1}^0)^2} + \frac{1}{(C_{2n+1}^1)^2} - \ldots + \frac{1}{(C_{2n+1}^n)^2} \text{ (назад)}$$

添加这些表达式并考虑到$C_{2n+1}^k = C_{2n+1}^{2n+1-k}$，我们得到$2S_n = 0$。因此$S_n = 0$。

这是关于同一主题的一个更复杂但也更有趣的示例：

$$\sum_{k=0}^{n} \frac{(-1)^k}{C_n^k} = \frac{n+1}{n+2} (1 + (-1)^n).$$

解决这个问题和前两个一样简单，不用删除。让我们用 $S_n$ 表示 $$\sum_{k=0}^{n} \frac{(-1)^k}{C_n^k}$$。如果$n$是奇数，你可以很容易证明$S_n = 0$。偶数$n$的情况将减少为奇数。仔细观察这是如何完成的。

⟦folio 34⟧

让我们用 $T_n$ 表示 $\sum_{k=0}^{n} \frac{(-1)^k (k+1)}{C_n^k}$。

让我们用两种方式写 $T_n$：

$$T_n = \frac{1}{C_n^0} - \frac{2}{C_n^1} + \dots + \frac{n+1}{C_n^n} \text{ (туда)},$$

$$T_n = \frac{n+1}{C_n^n} - \frac{n}{C_n^{n-1}} + \dots + \frac{1}{C_n^0} \text{ (назад)}.$$

加起来，我们得到$2T_n = (n+2) \times \left( \frac{1}{C_n^0} - \frac{1}{C_n^1} + \dots + \frac{1}{C_n^n} \right) = (n+2) \times S_n$。另一方面，$T_n = \sum_{k=0}^{n} \frac{(-1)^k (k+1) k! (n-k)!}{n!} = (n+1) \sum_{k=0}^{n} \frac{(-1)^k}{C_n^{k+1}} = (n+1) (1 - S_{n+1})$。

但由于$S_{n+1} = 0$（$n+1$是奇数），$T_n = n+1$。我们已经证明了$S_n = \frac{2}{n+2} T_n$。所以，$S_n = \frac{2(n+1)}{(n+2)}$。

需要注意的是$\frac{n+1}{n+2} (1 + (-1)^n) = \left\{ \begin{array}{l} 0, n нечетно, \\ \frac{2(n+1)}{n+2}, n четно. \end{array} \right.$

平等证明

$$\sum_{k=0}^{n} \frac{1}{C_n^k} = \frac{n+1}{2^{n+1}} \sum_{k=1}^{n+1} \frac{2^k}{k}. \tag{9}$$

比前面所有的都更困难，但也很有启发性。

让我们引入以下符号：

$$\sum_{k=0}^{n} \frac{1}{C_n^k} = D_n; \quad \sum_{k=0}^{n} \frac{k+1}{C_n^k} = E_n;$$

$$\frac{n+1}{2^{n+1}} \sum_{k=1}^{n+1} \frac{2^k}{k} = F_n.$$

首先，使用“来回”的方法，我们将金额写两次

$$E_n = \frac{1}{C_n^0} + \frac{2}{C_n^1} + \dots + \frac{n+1}{C_n^n} \text{ (туда)},$$

$$E_n = \frac{n+1}{C_n^n} + \frac{n}{C_n^{n-1}} + \dots + \frac{1}{C_n^0} \text{ (назад)}.$$

让我们添加这些等式：$2E_n = (n+2) \times \sum_{k=0}^{n} \frac{1}{C_n^k} = (n+2) D_n$。所以，$D_n = \sum_{k=0}^{n} \frac{1}{C_n^k} = (n+2) E_n$。现在，继续类似于我们在解决上一个问题时进行的计算，我们将通过$D_{n+1}$表达$E_n$。

即$E_n = \sum_{k=0}^{n} \frac{k+1}{C_n^k} = (n+1) \times \sum_{k=0}^{n} \frac{1}{C_n^{k+1}} = (n+1) (D_{n+1} - 1)$，我们可以用$D_n$来表达$D_{n+1}$：

$$D_{n+1} = \frac{2}{n+2} E_n = \frac{2}{n+2} (n+1) (D_{n+1} - 1),$$

在哪里

$$D_{n+1} = 1 + \frac{n+2}{2(n+1)} D_n.$$

现在，数学归纳法的使用者，让我们证明对于所有整数 $n \geqslant 0$ $D_n = F_n$。很容易看出$D_0 = 1$和$F_0 = 1$。我们假设$D_s = F_s$。然后$D_{s+1} = 1 + \frac{s+2}{2(s+1)} D_s = 1 + \frac{s+2}{2(s+1)} F_s = 1 + \frac{s+2}{2(s+1)} \cdot \frac{s+1}{2^{s+1}} \sum_{k=1}^{s+1} \frac{2^k}{k} = 1 + \frac{s+2}{2^{s+1}} \sum_{k=1}^{s+1} \frac{2^k}{k} = F_{s+1}$。

这意味着所有整数 $n \geqslant 0$ 都是 $D_n = F_n$。解决问题。

证明了等式（8）和（9）后，我们求解了���题 M470（«Kvant»，1977，No.10）。等式（9）使我们能够提出一个新的解决方案���题 M434（«Kvant»，1977，第12号）。

设$\sum_{k=1}^{n} \frac{2^k}{k} = \frac{p_n}{q_n}$，其中$p_n, q_n$互质。让我们用 $v(n)$ 表示可整除 $p_n$ 的 2 的最高次方。让我们证明$v(n) \geqslant \frac{n-3}{2}$。

来自 (9)$\sum_{k=0}^{n} \frac{1}{C_n^k} = \frac{n+1}{2^{n+1}} \frac{p_{n+1}}{q_{n+1}}$。这就是为什么$\frac{p_{n+1}}{q_{n+1}} = \frac{2^{n+1}}{n+1} \sum_{k=0}^{n} \frac{1}{C_n^k}$或$\frac{p_n}{q_n} = \frac{2^{n}}{n} \sum_{k=0}^{n-1} \frac{1}{C_n^k}$。因此$\frac{p_n}{q_n} = \frac{2^{n}}{n}! \times ((n-1)! + 1! (n-2)! + 2! (n-3)! + \dots + (n-1)!)$。在$n!$中，数字2包含在$\left[ \frac{n}{2} \right] + \dots \leqslant$幂中

⟦folio 36⟧

多项式
$$f(x) = (1+x)^n (x+1)^n = \left( C_n^0 + C_n^1 x + C_n^2 x^2 + \dots + C_n^n x^n \right) \times \left( C_n^0 x^n + C_n^1 x^{n-1} + C_n^2 x^{n-2} + \dots + C_n^n \right).$$

该乘积中$x^n$的系数显然等于$\sum_{k=0}^{n} \left( C_n^k \right)^2$。

另一方面，$f(x) = (1+x)^2n$。其中$x^n$的系数等于$C_{2n}^n$。由定理我们得到$\sum_{k=0}^{n} \left( C_n^k \right)^2 = C_{2n}^n$。

现在我们来求$\sum_{k=0}^{n} (-1)^k \left( C_n^k \right)^2$。

在解决上一个问题时，我们考虑了多项式$f(x) = (1+x)^n (x+1)^n$。显然，这里有必要采用正多项式，但要保证其中系数的符号是​​线性的。让我们尝试考虑多项式 $g(x) = (1+x)^n (x-1)^n = \left( C_n^0 + C_n^1 x + \dots + C_n^n x^n \right) \left( C_n^0 x^n - C_n^1 x^{n-1} + \dots + (-1)^n C_n^n \right)$。

该乘积中$x^n$的系数等于$\sum_{k=0}^{n} (-1)^k \left( C_n^k \right)^2$。另一方面，$g(x) = (1+x)^n (x-1)^n = (-1)^n (1-x^2)^n = (-1)^n \times \sum_{k=0}^{n} (-1)^k C_n^k x^{2k}$。在此总和中，奇次方$x$的系数等于0。因此，如果$n$是奇数，则$x^n$的系数等于0。如果$n$是偶数，则$x^n$的系数等于$(-1)^{n+\frac{n}{2}} C_n^{\frac{n}{2}} = (-1)^{\frac{n}{2}} C_n^{\frac{n}{2}}$。所以$\sum_{k=0}^{n} (-1)^k \left( C_n^k \right)^2 = \left\{ \begin{array}{l} 0, n \text{ нечетно}, \\ (-1)^{\frac{n}{2}} C_n^{\frac{n}{2}}, n \text{ четно}. \end{array} \right.$

练习

14. 求总和 $\sum_{k=0}^{n} \frac{C_n^k}{k+1}$。 （答案：$\frac{2^{n+1}-1}{n+1}$。）

15. 让我们用$B_n^k$表示多项式$(1+x+x^2)^n$中$x^k$的系数。求总和 $\sum_{k=0}^{2n} \left( B_n^k \right)^2$。 （答案：$B_{2n}^n$）。

乍一看，这种方法看起来很做作，因为每个人都不明白如何学习选择正确的多项式。不幸的是，在本文中我们无法更详细地讨论这个问题。

但是，我们认为在完成建议的练习后，您可以自己解决类似的问题。

4. 阿贝尔变换

让我们得到总和$S_n = a_1 b_1 + a_2 b_2 + \dots + a_n b_n$，其中$a_1, a_2, \dots, a_n, b_1, b_2, \dots, b_n$是两个序列。让我们用 $B_1, B_2, \dots, B_n$ 来表示 $b_1, b_1 + b_2, \dots, b_1 + b_2, \dots, b_1 + b_2 + \dots + b_n$ 的总和。那么$b_1 = B_1, b_k = B_k - B_{k-1}$与$k > 1$和$\sum_{k=1}^{n} a_k b_k$可以变换如下：

$$\sum_{k=1}^{n} a_k b_k = a_1 B_1 + a_2 (B_2 - B_1) + \dots + a_n (B_n - B_{n-1}) = (a_1 - a_2) B_1 + (a_2 - a_3) B_2 + \dots + (a_{n-1} - a_n) B_{n-1} + a_n B_n = \sum_{k=1}^{n-1} (a_k - a_{k+1}) B_k + a_n B_n.$$

这种变换称为阿贝尔变换（数学家 Nils Henrik Abell 的显着阶，参见 1976 年的«Kvant» No. 5）。

使用阿贝尔变换，我们找到总和 $\sum_{k=1}^{n} kq^{k-1}$。

让我们在点 (10) 处设置 $a_1 = 1, a_2 = 2, \dots, a_n = n; b_1 = 1, b_2 = q, \dots, b_n = q^{n-1}$。然后是$B_k = \frac{q^k - 1}{q-1}$和$a_1 - a_2 = a_2 - a_3 = \dots = a_{n-1} - a_n = -1$。波佐托穆

$$\sum_{k=1}^{n} kq^{k-1} = \sum_{k=1}^{n-1} (-1) \frac{q^k - 1}{q-1} +$$
