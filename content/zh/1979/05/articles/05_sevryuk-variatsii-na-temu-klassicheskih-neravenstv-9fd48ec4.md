---
id: 1979-5-sevryuk-variatsii-na-temu-klassicheskih-neravenstv-9fd48ec4
issue: kvant_1979_5
year: 1979
number: "5"
title: 经典不等式主题的变体
authors:
  - Севрюк М. Б.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 20
page_last: 22
page_labels: 18-20
tag: BKFN
lang: zh
source: kvant_digital
extraction: vision
content_sha256: e671221d8a2aa6f9c12004edfc5d8b9fa6eb7299892c8fe7ecab69c6e47faeb2
prompt_sha256: draft-1
translated_from: content/ru/1979/05/articles/05_sevryuk-variatsii-na-temu-klassicheskih-neravenstv-9fd48ec4.md
source_content_sha256: abba9462a930ff67d0dfa9baba6b6a4757307714873df878c61bde5c6edc2950
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 18⟧

经典不等式主题的变体

这篇笔记是十年级学生Misha Sevriok根据他在莫斯科第二学校会议上的报告写的。它证明了作者发现的不等式，关于算术平均数和几何平均数的可见的和广义的不等式。当然，它们并不新鲜：在数学的经典领域中，几乎不存在无需服务器培训即可实现的“空白点”。例如，上述不等式的证明包含在 Hardy、Leathwood 和 Polyan 的精彩但难以阅读的书中*)；然而，M. Sevriok 的纯组合证明是原创的并且明显简单。

我们的许多其他读者也对这种类型的不平等感兴趣。除了 M. Sevriok 的注释外，本期我们还以问题 (M565) 的形式发布了麦克劳林不等式（M. Rosenberg 发送了有趣的证明），以及 P. Vinokur 的问题，显示了此类不等式在各种情况下的适用性。

在我们的电子计算机时代，很高兴知道代数变换的生动艺术并没有失去其吸引力，也没有停止有用......

甚至古希腊人也知道，两个非负数的几何平均值$\sqrt{ab}$不会超过其算术平均值$\frac{a+b}{2}$。该定理对于任意数量的非负数$a_1, a_2, \dots, a_n$都有效：

$$\frac{1}{n} (a_1 + \cdots + a_n) \geq (a_1 \dots a_n)^{1/n}$$

（只有当所有 $a_i$ 匹配时才会出现相等）；它将作为后续一切的基础。

第一组不等式

这里，和之前一样，$a_1, a_2, \dots, a_n$是任意非负数。除了所有 $a_i$ 单独的总和 $S_1$ 之外，如不等式 (1) 中那样，我们还会对它们可能的成对乘积 $S_2 = a_1 a_2 + a_1 a_3 + \dots + a_{n-1} a_n$ 的总和感兴趣，

三者可能的乘积之和

$$S_3 = a_1 a_2 a_3 + a_1 a_2 a_4 + \dots + a_{n-2} a_{n-1} a_n$$

一般来说，其乘积的总和 $S_k$ 超过 $k$ 分量 ($k \leq n$)。类似地，除了所有 $a_i$ 的乘积 $P_1$ 之外，我们还将对所有可能的成对和的乘积感兴趣

$$P_2 = (a_1 + a_2) (a_1 + a_3) \dots \dots (a_{n-1} + a_n)$$

三之和的乘积

$$P_3 = (a_1 + a_2 + a_3) (a_1 + a_2 + a_4) \dots \dots (a_{n-2} + a_{n-1} + a_n)$$

一般来说，它们的总和超过 $k$ 项 ($k \leq n$) 的乘积 $P_k$。

事实证明，$k=1, 2, \dots, n$的数量$S_k$和$P_k$可以给出以下上限和下限（根据$S_1 = a_1 + \dots + a_n$和$P_1 = a_1 \dots a_n$）：

$$C_n^k \left( \frac{S_1}{n} \right)^k \geq S_k \geq C_n^k P_k^{\frac{k}{n}}$$

$$\left( \frac{k}{n} \right)^{C_n^k} S_1^{C_n^k} \geq P_k \geq k^{C_n^k} P_1^{\frac{k}{n}}$$

展开这些公式的记录看起来很内在。别开枪自杀！更好地破译这些公式之一（对于特定的、不太大的$k, n$值），你会发现这一切并不那么可怕。例如，对于 $k=3, n=4$，形式

⟦folio 19⟧

mula $(I_2)$ 看起来像这样：

$$4 \left( \frac{a_1 + a_2 + a_3 + a_4}{4} \right)^3 \geq a_1 a_2 a_3 + a_1 a_2 a_4 + a_1 a_3 a_4 + a_2 a_3 a_4 \geq 4 \left( a_1 a_2 a_3 a_4 \right)^{3/4}.$$

在 $k=1$ 处，不等式 $(I_2)$、$(II_1)$ 变为 $(1)$； $(I_1)$ 和 $(II_2)$ 在 $k=n$ 处变为 $(1)$（检查！）。因此，所有四个不等式$(I)$、$(II)$都可以被视为不等式$(1)$的推广。

证明不等式$(I_2)$。为了简洁起见，让我们输入 $C = C_n^k$，并通过 $\tilde{p}_1, \tilde{p}_2, \dots, \tilde{p}_{C_n^k}$ 来表示总和 $S_k$ 的项（事实上，它们有 $C = C_n^k$）。由于$\frac{S_k}{C}$是数字$\tilde{p}_1, \tilde{p}_2, \dots, \tilde{p}_c$的算术平均值，根据（1）

$$\frac{S_k}{C} \geq \left( \tilde{p}_1 \tilde{p}_2 \dots \tilde{p}_c \right)^{1/C}.$$

每个$a_i$恰好是数字$\tilde{p}_1, \tilde{p}_2, \dots, \tilde{p}_c$的$C_{n-1}^{k-1}$的组成部分。所以，$\left( \tilde{p}_1 \tilde{p}_2 \dots \tilde{p}_c \right)^{1/C} = P_1^v$，其中$v = \frac{C_{n-1}^{k-1}}{C} = \frac{C_{n-1}^{k-1}}{C_n^k} = \frac{k}{n}$。因此，需要$\frac{S_k}{C} \geq P_1^{k/n}$，即$S_k \geq CP_1^{k/n}$。

当 $k=n$、$a_1 = \dots = a_n$ 或集合 $\{a_1, a_2, \dots, a_n\}$ 中的至少 $n-k+1$ 数等于 0 时，$(I_2)$ 相等。

证明不等式$(II_2)$。让我们用 $\tilde{s}_1, \tilde{s}_2, \dots, \tilde{s}_C$ 表示产品 $P_k$ 的组成部分（如之前的 $C = C_n^k$）。为了简洁起见，让我们输入$q = k^C$。在不等式的左侧，即在表达式 $P_k$ 中，我们打开括号。我们获得 $q$ 项的总和，其中每一项都是集合 $\{a_1, a_2, \dots, a_n\}$ 中的 $C$ 个数的乘积，从每个 $\tilde{s}_i$ 中取出一个。在这些项的乘积中，由于对称性，每个 $a_i$ 都包含相同次数的分量（我们用 $\mu$ 表示该数字）。因此该乘积等于 $P_1^\mu$，因此

$$\frac{P_k}{q} = \left( P_1^\mu \right)^{1/q},$$

此外，当且仅当所有 $q$ 项都相等时，相等才会发生，特别是对于 $a_1 = \dots = a_n$ 而言；使用这个，找到$\mu$。

让$a_1 = a_2 = \dots = a_n = 2$。那么在 (2) 中，等式 $\tilde{s}_1 = \tilde{s}_2 = \dots = \tilde{s}_C = 2k, P_1 = 2^n$ 成立，因此$\frac{(2k)^C}{q} = \left( 2^n \right)^{\frac{\mu}{q}}, 2^C = 2^{\frac{n\mu}{q}}, \mu = \frac{Cq}{n}$。

将这个值代入(2)，我们得到$(II_2)$。

很明显，当 $k=1$ 或 $a_1 = \dots = a_n$ 时，或者当集合 $\{a_1, a_2, \dots, a_n\}$ 中的至少 $k$ 数等于 0 时，就会发生相等。

为了证明不等式$(I_1)$，我们需要麦克劳林不等式。让我们输入$S_k = \frac{S_k}{C_n^k}$。然后

$$\bar{S}_1 \geq \bar{S}_2^{\frac{1}{2}} \geq \bar{S}_3^{\frac{1}{3}} \geq \dots \geq \bar{S}_n^{\frac{1}{n}}$$

（如果所有 $a_i$ 均为正值且并非所有 $a_i$ 都相同，则输入停止符号 >）。

这种不等式的证明可以在 HLP 第 69 页 *) 中找到。

不等式$(I_1)$的证明立即由(3)得出。确实是$S_k C^{-1} = \bar{S}_k, S_1 n^{-1} = \bar{S}_1$，从$C_n^k = n$开始。这意味着 $(I_1)$ 采用 $\bar{S}_1 \geq \bar{S}_k^{\frac{1}{k}}$ 的形式，并且包含在 (3) 中。

使用麦克劳林不等式来证明$(I_2)$。

不等式$(II_1)$的证明方式与$(I_2)$类似；我们把这个证明留给读者。

$(I_1)$中相等的条件：$a_1 = a_2 = \dots = a_n$或$k=1$，$(II_1)$中：$a_1 = a_2 = \dots = a_n$或$k=n$。

*) M. Rosenberg 发送的另一个证明将作为解决方案���题 M565 发布。

⟦folio 20⟧

第二系列不等式

这里$a_1, a_2, \dots, a_n - n$是正x数。让我们引入以下符号（我们假设$k \leq n - 1$）：

$$\Sigma_i = \frac{\tilde{s}_i}{S_1 - \tilde{s}_i},$$

$$\Pi_i = \frac{\tilde{p}_i}{P_1 - \tilde{p}_i} \left( i = 1, 2, \dots, C = C_n^k \right).$$

我们感兴趣的是值$^*$$\Sigma_1 + \Sigma_2 + \dots + \Sigma_C, \Pi_1 + \Pi_2 + \dots + \Pi_C, \Sigma_1 \Sigma_2 \dots \Sigma_C, \Pi_1 \Pi_2 \dots \Pi_C$的变化边界。事实证明，表达式 $\Sigma_1 \Sigma_2 \dots \Sigma_C$ 的这些界限取决于 $k$；确切地：

$$\text{при } k \in \left[ 1, \frac{n}{2} \right] \quad \text{имеем}$$
$$\Sigma_1 \dots \dots \Sigma_C \in \left[ 0, \left( \frac{k}{n-k} \right)^C \right], \quad (\text{III}_1)$$

$$\text{при } k = \frac{n}{2} \quad \text{(если } n \text{ четно)}$$
$$\Sigma_1 \dots \dots \Sigma_C = 1, \quad (\text{III}_2)$$

$$\text{при } k \in \left[ \frac{n}{2}, n-1 \right] \quad \text{имеем}$$
$$\Sigma_1 \dots \dots \Sigma_C \in \left[ \left( \frac{k}{n-k} \right)^C, +\infty \right]. \quad (\text{III}_3)$$

声明证明 (III$_3$)。我们将第一类关系称为从$n$数字$a_1, a_2, \dots, a_n$到$k$的关系，第二类关系 - 从相同数字到$n-k$的关系。从 $C_n^k = C_n^{n-k}$ 开始，还会有 $C$。任意顺序的第二类关系的内部，以及第二类第$i$个关系中的数字之和将用$\tilde{s}_i'$表示。显然$\tilde{s}_1' \cdot \tilde{s}_2' \dots \tilde{s}_C' = \left( S_1 - \tilde{s}_1 \right) \times \left( S_1 - \tilde{s}_2 \right) \dots \left( S_1 - \tilde{s}_C \right)$。让我们考虑与数字 $i - \left( a_{i_1}, a_{i_2}, \dots, a_{i_k} \right)$ 的第一类任意关系。从$k > \frac{n}{2}$可以得出$k > n-k$以及该关系中包含的数字，可以组成第二类关系$C_n^{n-k}$（带有一些数字$\gamma_1, \gamma_2, \dots, \gamma_R$，其中$R = C_n^{n-k}$），并且集合$\{ a_{i_1}, a_{i_2}, \dots, a_{i_k} \}$中的每个数字都将恰好包含在$C_n^{n-k-1}$这样的第二类关系中。所以，$C_n^{n-k-1} \tilde{s}_i = \tilde{s}'_{\gamma_1} + \tilde{s}'_{\gamma_2} + \dots + \tilde{s}'_{\gamma_R}$。

从(1)和(4)可以得出$C_n^{n-k-1} \tilde{s}_i \geq R \left( \tilde{s}'_{\gamma_1} \tilde{s}'_{\gamma_2} \dots \tilde{s}'_{\gamma_R} \right)^{1/R}$。 (5)

*) 这些量对于概率论中的一些问题很有趣（ed.）。
