---
id: 1972-5-limanov-o-chisle-e-i-n-02ac77e0
issue: kvant_1972_5
year: 1972
number: "5"
title: 关于数字 e 和 n！
authors:
  - Лиманов Л. Г.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 16
page_last: 21
page_labels: 14, 15, 16, 18
tag: YNV0
lang: zh
source: kvant_digital
extraction: vision
content_sha256: a71e8836747e2e5ab037c32d5c15099218fb4e126119b38c1d4fd1a848eeaf8e
prompt_sha256: draft-1
translated_from: content/ru/1972/05/articles/04_limanov-o-chisle-e-i-n-02ac77e0.md
source_content_sha256: c3a0815a4d01d792946f6e0a0c627ea58e2f4726c450a2980de7d5d0c522d0e8
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 14⟧

关于数字 e 和 n！
L·G·利马诺夫

在这篇文章中，我们将分析 M.I. 的问题。巴什马科夫的文章《论伯特兰的到来》（见«Kvant»第5期，1971）。

回想一下，伯特兰的过程被称为以下迭代：如果$x > 1$，则$x$和$2x$之间有一个素数。

这个说法是法国数学家贝特朗提出的，但他无法找到证据。切比雪夫成功地做到了这一点，而且做得非常简单。确实，他使用了一个非基本公式 - 斯特林公式：

$$n! = \sqrt{2\pi n} \left(\frac{n}{e}\right)^n e^{\theta_n/12n},$$

其中$0 < \theta_n < 1$。

这个公式包括两个也许是最引人注目的数字。第一个是众所周知的数字$n$——圆的周长与其直径的比率。第二个数字是数字$e$——当$n$趋于无穷大时，序列$\left(\frac{n+1}{n}\right)^n$的极限。切比雪夫需要这个公式来估计 $n! = 1 \cdot 2 \cdot \dots \cdot n$ 的值。

事实上，为了证明 Bertrand 的行为，我们可以使用不太准确的值 $n$ 估计！

Bashmakov 的文章（任务 3）要求读者证明这些估计。我们将通过分析这个问题来教您。

这是它的措辞：

证明存在一个实数$e$，使得对于所有自然$n$、大的非科摩罗$n_0$，

$$\left(\frac{n+1}{e}\right)^n < n! < n \left(\frac{n}{e}\right)^n.$$

$\left(\frac{n+1}{e}\right)^n < n! < n \left(\frac{n}{e}\right)^n$ 不等式可以与斯特林公式一起使用。当然，它们不太准确，但更容易证明。

事实上，本文中剩下的问题是切比雪夫对伯特兰程序的证明的引理。解决它们比问题 3 容易得多。切比雪夫的优点不在于他解决了它们——这并不难——而是他阐述了它们，并找到了如何使用这些陈述来估计不超过 $x$ 的素数乘积（以及数量），并证明伯特兰程序。

问题3的解决方案，尚未证明的接收，数字$e$是多少，对于所有自然的$n$，

$$\left(\frac{n+1}{n}\right)^n < e < \left(\frac{n+1}{n}\right)^{n+1},$$

确实存在。 （下面将给出存在性证明。）

⟦folio 15⟧

我们想证明 $\left(\frac{n+1}{e}\right)^n < n! < n \left(\frac{n}{e}\right)^n$ 或（这是相同的）
$\frac{(n+1)^n}{n!} < e^n < \frac{n^n}{(n-1)!}$ $n$ 大于某些 $n_0$。

让某些$k$证明$\frac{(k+1)^k}{k!} < e^k$。但
$\frac{(k+2)^{k+1}}{(k+1)!} / \frac{(k+1)^k}{k!} = \left(\frac{k+2}{k+1}\right)^{k+1} < e$。因此$\frac{(k+2)^{k+1}}{(k+1)!} < e^{k+1}$。

因此，我们的陈述对于 $k+1$ 成立，因此对于 $k+2, k+3$ 等也成立。同样，根据假设

$$e^k < \frac{k^k}{(k-1)!}$$

结论是

$$e^{k+1} < \frac{(k+1)^{k+1}}{(k)!}.$$

真的吗，

$$\frac{(k+1)^{k+1}}{k!} / \frac{k^k}{(k-1)!} = \left(\frac{k+1}{k}\right)^{k+1} > e.$$

还需要证明$e$存在并找到每个不等式中$n$的初始值

$$\left(\frac{n+1}{e}\right)^n < n!, n! < n \left(\frac{n}{e}\right)^n.$$

$e$存在的证明

调用满足不等式$a \leqslant x \leqslant b$的实数集$x$的条件为具有端点$a$和$b$的线段（具有端点$a$和$b$的线段由$[a, b]$表示）。

在证明数字$e$的存在性时，我们将使用实数的以下性质：如果存在一个线段序列$[a_i, b_i]$，其中$a_i \leqslant a_{i+1} < b_{i+1} \leqslant b_i$（$i=1, 2, \dots$）（这样的序列称为嵌套线段序列），则存在所有这些线段共有的点$\alpha$。

我们不会证明这个性质。事实是，有了我们对实数集的理解的明确定义，这个（或一些等效的）属性就被接受为公理。

练习

1. 检查实数的以下属性是否等效；如果您在没有证据的情况下接受其中任何一个，那么其余的都将从中推断出来。
a) 每个嵌套段序列至少有一个公共点。
b) 每个有界单调递增序列都有一个极限。
b) 任何序列$\{a_i\}(i=1, 2, \dots)$，其中对于任何$\varepsilon > 0$，可以指定一个$N$（当然，取决于$\varepsilon$），使得$m, n > N$的$|a_n - a_m| < \varepsilon$有极限。 （这样的序列称为柯西序列。）
r) 上面有界的每组实数都有一个精确版本的 grana，也就是说，我们可以指定一个数字 $\alpha$，使得属于该组的所有数字不大于 $\alpha$，但对于任何小于 $\alpha$ 的数字 $\beta$，我们可以从该组中找到一个大于 $\beta$ 的数字。
d) 从覆盖线段$[a, b]$的任何线段族中，我们可以选择覆盖线段$[a, b]$的有限线段族。 （如果对于属于段$[a, b]$的每个$x$，系统$M$中存在一个包含$x$的段，我们就说段系统$M$覆盖了段$[a, b]$。）

⟦folio 16⟧

现在让我们证明序列 $\left(\frac{n+1}{n}\right)^n$ 是单调递增的。为此，任何 $n\left(\frac{n+1}{n}\right)^n$ 都必须小于 $\left(\frac{n+2}{n+1}\right)^{n+1}$。

$$\left(\frac{n+1}{n}\right)^n < \left(\frac{n+2}{n+1}\right)^{n+1}$$

借助简单的变换，这种不等式可以简化为以下形式：

$$[(n^2+2n+1)^n - (n^2+2n)^n](n+1) < (n^2+2n)^n.$$

[这里是中间不等式：$(n+1)^{2n+1} < (n+2)^{n+1}n^n$和$(n^2+2n+1)^n(n+1) < (n^2+2n)^n(n+2)$。]使用公式$a^k - b^k = (a-b)(a^{k-1} + a^{k-2}b + \ldots + ab^{k-2} + b^{k-1})$，我们得到：$(n^2+2n+1)^n - (n^2+2n)^n < n(n^2+2n+1)^{n-1}$。因此，如果我们证明以下不等式，则不等式（1）得以证明：

$$(n^2+2n+1)^{n-1}(n+1) < (n^2+2n)^{n-1}(n+2).$$

这反过来（事实证明是完全相同的）由不等式得出

$$(n^2+2n+1)^{n-2}(n+1) < (n^2+2n)^{n-2}(n+2).$$

重复这些论证，我们确信不等式 (1) 由明显的不等式得出

$$n+1 < n+2.$$

更简单地证明对于任何自然数 $n$

$$\left(\frac{n+1}{n}\right)^{n+1} > \left(\frac{n+2}{n+1}\right)^{n+2}.$$

事实上，不等式（2）等价于不等式

$$(n+1)^{2n+3} > (n+2)^{n+2}n^{n+1}.$$

波兹尼只要证明这一点就足够了

$$[(n^2+2n+1)^{n+1} - (n^2+2n)^{n+1}](n+1) > (n^2+2n)^{n+1}.$$

但

$$(n^2+2n+1)^{n+1} - (n^2+2n)^{n+1} > (n^2+2n)^{n+1}(n+1),$$

在哪里

$$[(n^2+2n+1)^{n+1} - (n^2+2n)^{n+1}](n+1) > (n^2+2n)^{n+1}(n+1)^2 > (n^2+2n)^{n+1}(n^2+2n) = (n^2+2n)^{n+1},$$

也就是说，不等式 (3) 以及因此不等式 (2) 已被证明。

这样，我们就证明了序列$a_n = \left(\frac{n+1}{n}\right)^n$是单调递增的，序列$b_n = \left(\frac{n+1}{n}\right)^{n+1}$是单调杀戮的。另外，从 $\frac{n+1}{n} > 1$ 开始，$a_n < b_n$。因此，端点为$a_i$、$b_i$的线段序列是一个嵌套线段序列，第$k$线段的长度等于$\left(\frac{k+1}{k}\right)^k \cdot \frac{1}{k}$，即随着$k$的增长，它趋于于零。因此，所有这些片段都有一个共同点。相应的数字称为数字$e$。

您可以根据需要计算数字 $e$ 的小数位数。这是前几个：$e=2,71828...$

⟦folio 18⟧

1. 证明
$$T(x) = \psi(x) + \psi\left(\frac{x}{2}\right) + \psi\left(\frac{x}{3}\right) + \dots$$

2. 证明
$$\psi(x) = \theta(x) + \theta(\sqrt{x}) + \theta(\sqrt[3]{x}) + \theta(\sqrt[4]{x}) + \dots$$

利用问题1的结果，$S(x)$可以写成如下：
$$S(x) = A_1\psi(x) + A_2\psi\left(\frac{x}{2}\right) + A_3\psi\left(\frac{x}{3}\right) + \dots$$

3. 检查系数 $A_1, A_2, A_3, \dots$ 随周期 30 变化，并且对于前 30 个值 $n$，系数 $A_n$ 形成以下序列：1, 0, 0, 0, 0, -1, 1, 0, 0, -1, 1, -1, 1, 0, -1, 0, 1, -1, 1, -1, 0, 0, 1、-1、0、0、0、0、1、-1。

4. 证明系数$A_1, A_2, A_3, \dots$随周期30变化，并且对于$n$的前三十个值，系数$A_n$形成以下序列：1, 0, 0, 0, 0, -1, 1, 0, 0, -1, 1, -1, 1, -1, 0, 0, 1, -1, 1, -1, 0, 0, 0, 0, 1, -1。

5. 证明
$$\psi(x) - 2\psi(\sqrt{x}) \leq \theta(y) \leq \psi(x) - \psi(\sqrt{x}).$$

6. 证明
$$\frac{\psi(x)}{\log x} < \pi(x) < \frac{\psi(x) + \theta(x)}{\log x}.$$

问题的解决方案1.注意$a_p = [\log_p x]$。我们计算$\log p$用什么系数进入总和$\psi(x) + \psi\left(\frac{x}{2}\right) + \dots$ 在$\psi\left(\frac{x}{i}\right)$中，对数$p$用系数$\left[\log_p \frac{x}{i}\right]$进入，这意味着$\log p$的总系数等于$\sum_{i=1}^{\infty} \left[\log_p \frac{x}{i}\right]$。让我们从每一项中减一并对其进行变换：$\left[\log_p \frac{x}{i}\right] - 1 = \left[\log_p \frac{x}{i} - 1\right] = \left[\log_p \frac{x_1}{i}\right]$，其中$x_1 = \frac{x}{p}$。因此$\sum \left[\log_p \frac{x}{i}\right] = \left[\frac{x}{p}\right] + \sum \left[\log_p \frac{x_1}{i}\right]$。重复我们的变换，我们得到以下等式：
$$\sum \left[\log_p \frac{x}{i}\right] = \sum_{i=1}^{\infty} \left[\frac{x}{p^i}\right].$$

因此，$\psi(x) + \psi\left(\frac{x}{2}\right) + \dots$之和中$\log p$的系数等于$\sum_{i=1}^{\infty} \left[\frac{x}{p^i}\right]$。现在让我们注意，$T(x) = \sum_{i \leq x} \log i$也可以用这种形式表示：$T(x) = \sum_{p \leq x} c_p \log p$，其中$p$是素数。

练习

12. 证明如果$k$是自然数，则$\left[\frac{x}{k}\right] = \left[\frac{x}{k}\right]$对于$x > 1 [\log_h[x]] = [\log_hx]$也成立。

⟦folio none⟧

13. 确保系数$c_p$等于

$$\sum_{i=1} \left[ \frac{[x]}{p^i} \right].$$

笔记。将$T(x)$表示为$\log([x])$。

完成练习12和13后，完全解决问题1。

问题2的解决方案。该问题的解决方案与问题1的解决方案类似：需要确保$\theta(x) + \theta(\sqrt{x}) + \cdots$之和中$p$的系数等于$[\log_p x]$。这很容易遵循。如果$\sqrt{x} \geq p$，即$\log_p x \geq i$，则$\log p$作为术语包含在$\theta(\sqrt{x})$中。因此，在 $\sum \theta(\sqrt{x})$ 中，对数 $p$ 作为一项包含 $k$ 次，其中 $k$ 由不等式 $k + 1 > \log_p x \geq k$ 确定，即 $[\log_p x]$ 次。

问题4的解法。这个问题与问题M92非常相似（参见1971年«Kvant»第7期）。

事实上，它可以表述如下：

在去马津的第一趟火车上，佩蒂亚给自己买了很多小巧克力。他决定在无聊的日子里他应该吃三块巧克力，在那些他只忙于一件事的日子里——两块，而在其余的日子里——一块。那么 $A_i + 2$ 等于 Petya 在第 $i + 1$ 天吃的巧克力数量。 （回想一下，Petya 每两天去游泳一次，每三天去一次 Maazin，每五天解决一次数学问题）。

这是 $A_i$ 的公式：

$$A_i = 1 - [2^{[i/2] - i/2}] - [2^{[i/3] - i/3}] - [2^{[i/5] - i/5}] + [2^{[i/30] - i/30}].$$

练习

14. 证明式(4)。
15. 推导出 Petya 在第 $k$ 天要做的事情数量的公式。

由式(4)可知$A_{i+30} = A_i$。当然，你可以自己计算前三十个系数的值。

问题 5 的解决方案。这个问题源自问题 2。事实上，

$$\psi(x) - \psi(\sqrt{x}) = \theta(x) + \theta(\sqrt{x}) + \cdots \geq \theta(x),$$

$$\psi(x) - 2\psi(\sqrt{x}) = \theta(x) - \theta(\sqrt{x}) + \cdots \leq \theta(x).$$

问题6的解法。从$a_p = [\log_p x]$开始，

$$a_p \log p \leq \log_p x \log p = \log x, \quad (a_p + 1) \log p > \log x.$$

波兹尼

$$\psi(x) = \sum_{p \leq x} a_p \log p \leq \sum_{p \leq x} \log x = \pi(x) \log x,$$

$$\psi(x) + \theta(x) = \sum_{p \leq x} (a_p + 1) \log x > \sum_{p \leq x} \log x = \pi(x) \log x,$$

在哪里

$$\frac{\psi(x)}{\log x} < \pi(x) < \frac{\psi(x) + \theta(x)}{\log x}.$$
