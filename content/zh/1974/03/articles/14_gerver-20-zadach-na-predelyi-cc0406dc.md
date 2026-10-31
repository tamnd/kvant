---
id: 1974-3-gerver-20-zadach-na-predelyi-cc0406dc
issue: kvant_1974_3
year: 1974
number: "3"
title: 20 极限问题
authors:
  - Гервер М. Л.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 29
page_last: 33
page_labels: 27, 28, 30, 31
tag: QO67
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 8ab82c56398ac389a8fa9bbd8fb8492560707dc1be1a0dbd5feda503987b01e4
prompt_sha256: draft-1
translated_from: content/ru/1974/03/articles/14_gerver-20-zadach-na-predelyi-cc0406dc.md
source_content_sha256: e402d349b78a7ddafa566a63c103f1c2f1f4193d23a46a5fb4a817850baf4450
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 27⟧

20项极限挑战

议员格弗

很多人可能都知道数列极限的定义：“如果对于任何$\varepsilon > 0$，都存在一个$N$，并且对于所有$n > N...$，则数字a称为序列$x_n$的极限。但是记住它是一回事，而能够自由地处理它，证明定理，而不与所有“存在”，“对于任何人”等混淆，则是另一回事。这可能是最大的踏上“高等数学”之路，这不仅是小学生，也是学生都难以逾越的。

如果您设法解决本文中收集的问题 - 或者至少了解它们的解决方案 - 那么进一步的数学分析对您来说将变得更加容易和有趣。

1. 证明对于任意自然数$n$
a) $\frac{1}{2 \cdot 3} + \frac{1}{3 \cdot 4} + \dots + \frac{1}{n(n+1)} = \frac{1}{2} \cdot \frac{n-1}{n+1}$;
b) $\frac{1}{n+1} + \frac{1}{n+2} + \dots + \frac{1}{2n} \geq \frac{1}{2}$.

接下来，我们将使用字母 $n$ 来仅表示自然数。

2. a) 证明你可以找到$n$使得$2^n > 10^{10}$。
b) 证明您可以找到 $k$，使得对于任何 $n > k$ $1 + a)^n \geq 1 + na$ 为真。
b) 证明您可以找到 $k$，使得对于任何 $n > k$ $10^n > n^{10}$ 为真。
d) 设 $|q| < 1$。证明您可以找到 $k$，使得对于任何 $n > k$ $|q|^n < 10^{-10}$ 都成立。
e) 是否存在一个正数使得对于任何 $n$ 都小于 $1/n$？

e) 设 $|q| < 1$。证明对于任何 $\varepsilon > 0$ 都存在 $k$，使得对于任何 $n > k$ $\left|q\right|^n < \varepsilon^*$ 为真。
g) 是否有可能找到$k$，使得对于任何$n > k$和任何$\varepsilon > 0$，等式$\left(\frac{1}{2}\right)^n < \varepsilon$成立？
然后呃。比较2e和2g，我们发现词序就是东西！
h) 设置$s_n = \frac{1}{2} + \frac{1}{4} + \frac{1}{8} + \dots + \frac{1}{2^n}$。证明对于任何$\varepsilon > 0$，都存在一个$k$，使得对于任何

*) $\varepsilon$是一个希腊字母，读作：“episilon”，通常用来表示小的正数。 “小数”这个词的确切含义是可用的 - “小”是什么意思：0.01 或 $10^{-10}$？所以他们说； “对于任何$\varepsilon > 0$”——通常的意思是：“无论它有多小。” 1关于这个问题，说得很多：center：放入$\varepsilon = 0,01$，然后找到一个$k$，这样对于任何$n > k$都会有$|q|^n < 0,01$；放入$\varepsilon = 10^{-10}$，然后找到另一个$k$（更大），这样对于每一个比这个新的$k$大的$n$，就会有$|q|^n < 10^{-10}$；一般来说，对于任何$\varepsilon > 0$（无论多小），您都可以选择$k$（可能非常大），这样对于任何$n > k$都会有$|q|^n < \varepsilon$。

⟦folio 28⟧

波哥$n > k$
$$|s_n - 1| < \varepsilon.$$
编号顺序。让我们写一些数字：$x_1$，然​​后另一个：$x_2$，然后第三个：$x_3$，等等。

我们将得到一个数列
$$x_1, x_2, x_3, \dots, x_n, \dots$$
字母 $x$ 旁边的数字表示该数字在序列中的位置：$x_1$ - 第 1 个，$x_2$ - 第 2 个，$\dots$、$x_n$ - $n$、$\dots$。

简而言之，用符号$\{x_n\}$表示。当然，也可以用其他字母来表示序列：$\{s_n\}, \{y_n\}, \{z_n\}$等。

让我们写下以下任务中使用的十几个序列：

(1) $1, \frac{1}{2}, \frac{1}{3}, \frac{1}{4}, \dots$

(2) $1, 0, \frac{1}{2}, 0, 0, \frac{1}{3}, 0, 0, 0, \frac{1}{4}, 0, 0, 0, 0, \dots$

(3) $\{s_n\}, s_n = \frac{1}{2} + \frac{1}{4} + \frac{1}{8} + \dots + \frac{1}{2^n}$.

(4) $\{y_n\}, y_n = \frac{1}{2} - \frac{1}{4} + \frac{1}{8} - \dots - \frac{(-1)^n}{2^n}$.

(5) $1, 1, 1, 1, \dots$.

(6) $1, -1, 1, -1, \dots$.

(7) $1, \frac{1}{2}, 1, \frac{1}{3}, 1, \frac{1}{4}, 1, \frac{1}{5}, \dots$.

(8) $1, -\frac{1}{2}, \frac{1}{3}, -\frac{1}{4}, \frac{1}{5}, -\frac{1}{6}, \dots$.

(9) $\frac{1}{1}, \frac{1}{1}, \frac{1}{2}, \frac{1}{1}, \frac{1}{3}, \frac{1}{1}, \dots, \frac{1}{9}, \frac{1}{1}, \frac{1}{10}, \frac{1}{2}, \frac{1}{11}, \frac{1}{2}, \dots, \frac{1}{99}, \frac{1}{2}, \frac{1}{100}, \frac{1}{3}, \dots$

（偶数位分数的分母等于前一个分数分母的位数）。

(10) $\frac{1}{2}, \frac{2}{1}, \frac{2}{3}, \frac{3}{2}, \frac{3}{4}, \frac{4}{3}, \frac{4}{5}, \frac{5}{4}, \dots$

定义 1. 如果对于任何 $\varepsilon > 0$ 存在一个 $k$，使得对于任何 $n > k$，数字 $a$ 被称为*序列的极限* $\{x_n\}$
$$|a - x_n| < \varepsilon.$$
数字$a$是$\{x_n\}$的极限，这样写：
$$\lim_{n \to \infty} x_n = a$$
（读作：“当$n$趋于无穷大时，$x_n$的极限等于$a$”）或者像这样：
$$x_n \rightarrow a \text{ при } n \rightarrow \infty$$
（读作：“$x_n$趋于$a$，因为$n$趋于无穷大”）。在一些国家，趋于无穷大的$n$被省略，简单地写成：
$$\lim x_n = a \text{ при } x_n \rightarrow a.$$
有极限的序列称为*收敛*。

3. a) 使用定义 1 形成问题 2e 和 23。

6) 证明0是序列(1)、(2)、(8)和(9)的极限。

b) 求序列(3)、(4)和(10)的极限。

d) 证明1不是序列(1)的极限。

d) 序列（5）、（6）和（7）有极限吗？

e) 令 $x_n - n$ 为序列 (9) 的一项。指定 $k$，使得不等式 $x_n < \frac{1}{2}$ 对于 $n > k$ 成立。

g) 两个不同的数可以作为同一个数列的极限吗？

4. 令 $\{x_n\}$ 为任意序列。我们来写一些

⟦folio 30⟧

关于极限 4。他们说，如果对于任何 $C$ 都存在一个 $k$，使得对于任何 $n > k$ $|x_n| > C$，则序列 $\{x_n\}$ 趋于无穷大（可以这样写：$x_n \to \infty$ 对于 $n \to \infty$）。

7. 以下哪些序列趋于无穷大，哪些序列无界？

a) $x_n = n$, $6)$ $x_n = (-1)^n \cdot n$,
b) $x_n = n^{(-1)^n}$
g) $x_n = \begin{cases} n^2 \text{ при } n \text{ четном,} \\ \sqrt{n} \text{ при } n \text{ нечетном.} \end{cases}$

在极限 5 上。如果对于任何 $\varepsilon > 0$ 和对于任何 $k$ 都存在一个 $n > k$ 使得 $|a - x_n| < \varepsilon$，则数字 $a$ 被称为序列 $\{x_n\}$ 的“极限点”。

8. 证明a) 收敛序列的极限就是它的极限点，
6) 如果$x_n \to a$和$b \neq a$，则$b$不是$\{x_n\}$的极限点。
b) 如果$a$是$\{x_n\}$的极限点，则$\{x_n\}$包含收敛​​于$a$的子序列。

9. 提出一个序列 $\{x_n\}$ ，其极限点是：
a）所有自然数（并且只有它们），
b) 所有数字$1/n$，
b) 所有有理数。

10. a) 提出一个满足问题 9a 但不包含整数的序列。
6) 令$\{x_n\}$满足问题96。0有可能不是它的极限点吗？
b) 列出满足问题9b 的序列的所有极限点。

16个条件。 “Apu”在英文中意为“任意”，“Exist”意为“存在”。符号 $\vee$ 和 $\exists$ - 分别反转这些单词的第一个字母：
“对任何人来说”和“有一些东西......那个。”
考虑以下 16 个条件：

1) $\exists \varepsilon > 0 \exists k \exists n > k |x_n - a| < \varepsilon$,
2) $\exists \varepsilon > 0 \exists k \exists n > k |x_n - a| \geqslant \varepsilon$,
3) $\exists \varepsilon > 0 \exists k \forall n > k |x_n - a| < \varepsilon$,
4) $\exists \varepsilon > 0 \exists k \forall n > k |x_n - a| \geqslant \varepsilon$,
5) $\exists \varepsilon > 0 \forall k \exists n > k |x_n - a| < \varepsilon$,
6) $\exists \varepsilon > 0 \forall k \exists n > k |x_n - a| \geqslant \varepsilon$,
7) $\exists \varepsilon > 0 \forall k \forall n > k |x_n - a| < \varepsilon$,
8) $\exists \varepsilon > 0 \forall k \forall n > k |x_n - a| \geqslant \varepsilon$,
9) $\forall \varepsilon > 0 \exists k \exists n > k |x_n - a| < \varepsilon$,
10) $\forall \varepsilon > 0 \exists k \exists n > k |x_n - a| \geqslant \varepsilon$,
11) $\forall \varepsilon > 0 \exists k \forall n > k |x_n - a| < \varepsilon$,
12) $\forall \varepsilon > 0 \exists k \forall n > k |x_n - a| \geqslant \varepsilon$,
13) $\forall \varepsilon > 0 \forall k \exists n > k |x_n - a| < \varepsilon$,
14) $\forall \varepsilon > 0 \forall k \exists n > k |x_n - a| \geqslant \varepsilon$,
15) $\forall \varepsilon > 0 \forall k \forall n > k |x_n - a| < \varepsilon$,
16) $\forall \varepsilon > 0 \forall k \forall n > k |x_n - a| \geqslant \varepsilon$.

11. 以下哪一个条件表达了您已经熟悉的序列的属性（受限、以 $a$ 作为极限或极限点、趋于无穷大）或这些属性的否定？剩下的条件是什么意思？

关于极限 6. 如果满足以下两个条件之一，则序列 $\{x_n\}$ 称为“单调”：
1) $x_1 \leqslant x_2 \leqslant x_3 \leqslant \dots \leqslant x_n \leqslant \dots$,
2) $x_1 \geqslant x_2 \geqslant x_3 \geqslant \dots \geqslant x_n \geqslant \dots$.
在第一种情况下，$\{x_n\}$称为*递增*，在第二种情况下称为*递减*。

12. a) 证明任意序列都包含单调子序列。
6) 证明单调序列的极限点就是它的极限。
b) 证明每个单调有界序列都有极限（有时实数的这一性质被视为公理）。
13. a) 证明每个有界序列至少有一个极限点。
6) 检查语句 12c 和 13a 是否等效：每个语句都可以从另一个推导出来（因此 13a 也可以视为公理）。
14. a) 设$|q| < 1$，$s_n = 1 + q + \dots + q^{n-1}$。证明序列 $\{s_n\}$ 收敛，并且

⟦folio 31⟧

找到它的极限。

6) 检查对于$|q| \geq 1$，序列$\{s_n\}$没有限制。

15. 让$x_n \rightarrow a$，$y_n \rightarrow b$位于$n \rightarrow \infty$。那么证明

a) $x_n + y_n \rightarrow a + b$,
b) $x_n - y_n \rightarrow a - b$,
c) $x_n y_n \rightarrow ab$,
d) 如果$b \neq 0$，则$x_n/y_n \rightarrow a/b$。

扫地。 $y_n$中可能有零，但如果$b \neq 0$存在（证明）只有有限个：$\exists N \forall n > N y_n \neq 0$；序列$x_n/y_n$取决于极限，因此对于$n > N$。

e) 如果$b = 0$，则序列$x_n/y_n$（如果已定义）可能没有极限，可能趋向于任意数或无穷大——请给出相关例子。

16. a) 证明如果$x_n \geq 0$对于所有$n$且$x_n \rightarrow a$对于$n \rightarrow \infty$，则$a \geq 0$。

6) 如果一切都是$x_n > 0$，是否可以说$\lim_{n \rightarrow \infty} x_n > 0$？

b) 设$x_n \leq y_n \leq z_n$，并设$x_n \rightarrow a$和$z_n \rightarrow a$以及$n \rightarrow \infty$。然后证明$y_n \rightarrow a$对于$n \rightarrow \infty$。

17. a) 序列 $\{x_n\}$ 具有以下性质：对于任何 $\varepsilon > 0$ 都有一个 $k$ ，使得对于任何 $n > k$ 和任何自然数 $p$
$$|x_{n+p} - x_n| < \varepsilon.$$
证明$\{x_n\}$有极限。

6) 反之证明：若$x_n$是收敛序列，则$\forall \varepsilon > 0 \exists k \forall n > k \forall p |x_{n+p} - x_n| < \varepsilon.$
b) 序列 $\{x_n\}$ 具有以下属性： $\forall \varepsilon > 0 \exists k \forall n > k |x_{n+p} - x_n| < \varepsilon.$
$\{x_n\}$对财产有义务吗？

18. 让我们像这样构造序列$\{x_n\}$：$|x_n| = 1/2^n$，任意选择符号$x_1, x_2, x_3, \dots$。接下来我们输入$s_n = x_1 + \dots + x_n$。

a) 证明序列$\{s_n\}$收敛。

6) 列出$\lim_{n \rightarrow \infty} s_n$可以取的所有值（当以各种不同方式选择符号$x_n$时）。

复杂$\{x_n\}$。到目前为止，我们已经考虑了由实数组成的序列。

现在让 $x_n$ 为任何复数。

这种情况下极限的定义实际上与之前相同。但它的几何意义不同：不等式$|x_n - a| < \varepsilon$现在意味着$x_n$位于以点$a$为圆心、半径为$\varepsilon$的圆内；因此，如果任何以 $a$ 为圆心的圆都只有有限数 $\{x_n\}$，则数 $a$ 充当$\{x_n\}$ 的限制。

19. a) 设 $x_n = a_n + ib_n$。当且仅当序列$\{a_n\}$和$\{b_n\}$收敛时，序列$\{x_n\}$收敛。证明一下。

6) 让 $|x_n| = r_n$，arg $x_n = \alpha_n$。当且仅当$\{r_n\}$和$\{\alpha_n\}$都收敛时，$\{x_n\}$收敛吗？

20. 让序列$\{x_n\}$趋于0。让我们像这样构造序列$\{s_n\}$：
$$s_1 = x_1, \quad s_2 = x_1 + x_2, \dots, \quad s_n = x_1 + x_2 + \dots + x_n, \dots$$
找出 $\{s_n\}$ 是否可以恰好有两个极限点：

a) 如果 $x_n$ 是实数，
b) 如果 $x_n$ 是复数（在这种情况下，极限点的定义实际上与之前相同）。
