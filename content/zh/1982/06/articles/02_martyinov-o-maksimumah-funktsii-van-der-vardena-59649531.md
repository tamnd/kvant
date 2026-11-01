---
id: 1982-6-martyinov-o-maksimumah-funktsii-van-der-vardena-59649531
issue: kvant_1982_6
year: 1982
number: "6"
title: 关于 van der Waerden 函数的极大值
authors:
  - Мартынов Б.
rubric: osnovnye-stati
page_first: 10
page_last: 15
page_labels: 8, 9, 10, 12, 13
tag: O53W
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 98e6707a1943689dbf7aa9e9a08928b48ad32d28785e6ca11cd6c7f7ca33d34b
prompt_sha256: draft-1
translated_from: content/ru/1982/06/articles/02_martyinov-o-maksimumah-funktsii-van-der-vardena-59649531.md
source_content_sha256: 369c2e8a600d3647673a773c087b382f6f316efa3f33bf568d56fa32b3a78114
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 8⟧

B·马丁诺夫

关于 van der Waerden 函数的极大值

我们熟悉的函数

九年级和十年级的学生知道，在某个点可微的函数在该点是连续的（“代数和分析原理 9-10”，第 19 段）。他们还知道反之亦然：例如，函数 $y = |x|$ 在 $x = 0$（以及任何其他点）处连续，但在 $x = 0$ 处不是任意的。一般来说，任何图形在某个点有“角”的函数在该点都是不可微的。很明显，很容易构造一个在区间上的函数，例如 [0; 1]有无数个“角度”（图1显示了这样一个函数的一部分图形；当然，不可能完整地画出它）。

然而，所有这些函数以及您已知的其他连续函数在“大多数”点仍然是可微的。

在微分学发明后的很长一段时间里，数学家们认为连续函数通常是可微的。因此，当几个世纪过去的六十年代，德国数学家卡尔·韦尔斯特拉斯（Karl Weierstrass）发表了一个函数在一条直线上的每一点都是连续的并且在任何一点都不是任意的函数的例子*)时，数学界将出现一个施特拉斯之夜。

*) 第一个此类例子是由捷克数学家和哲学家伯恩哈德·博尔扎诺 (Bernhard Bolzano) 早于维尔斯特拉斯四十年建造的，但他的例子比维彻斯特拉斯的例子更晚为人所知。

图 1.

⟦folio 9⟧

如果把所有函数$\varphi_n$都加起来会怎样？有理由希望“总和”在任何情况下在每个点都是连续的，并且在 $x = \frac{k}{2^n} (k \in \mathbb{Z}, n \in \mathbb{N})$ 形式的点上不可微。不幸的是，我们不知道无限多项的总和是多少。

因此，我们将这样做：我们形成函数$\Phi_n(x) = \varphi_0(x) + \varphi_1(x) + \dots + \varphi_n(x)$的序列（因此，$\Phi_{n+1}(x) = \Phi_n(x) + \varphi_{n+1}(x)$；参见图3-5）并证明对于任何$x$都存在$\lim_{n \to \infty} \Phi_n(x)$。

为了证明这一点，我们需要维尔斯特拉斯定理，该定理指出单调有界序列有极限（代数与分析 9，第 32 段）。

从 $\varphi_{n+1}(x) \geq 0$ 开始，它遵循 $\Phi_{n+1}(x) \geq \Phi_n(x)$——序列 ($\Phi_n(x)$) 是单调的。由于 $\Phi_n(x) = \varphi_0(x) + \varphi_1(x) + \dots + \varphi_n(x) \leq \frac{1}{2} + \frac{1}{4} + \dots + \frac{1}{2^{n+1}} = 1 - \frac{1}{2^{n+1}} < 1$，序列 ($\Phi_n(x)$) 是有界的。因此，$\lim_{n \to \infty} \Phi_n(x)$存在。让我们用 $\Phi(x)$ 表示这个极限。因此，函数 $\Phi$ 被定义在整个数轴上。它是周期性的（周期为 1），$0 \leq \Phi(x) \leq 1$ 对于所有 $x \in \mathbb{R}$，函数 $\Phi$ 的图形相对于任何直线 $x = \frac{k}{2} (k \in \mathbb{Z})$ 对称 - 所有这些都可以轻松地从函数 $\varphi_0$ 的属性和极限的属性中得出。因此，函数$\Phi$的图形是不可能的：在图3-5中，您可以看到函数$\Phi_n$的图形有“角点”的点是如何“升温”的，即这些函数不具有任意函数的点。

构造函数$\Phi_n$的连续性在直线的每个点都是连续的。

直观上，这是非常清楚的：如果$\Phi$在某个点$x_0$有不连续性，那么对于足够大的

⟦folio 10⟧

$n \in \mathbb{N}$ 在点 $x_0$ 和 $\Phi_n$ 处将具有大致相同的不连续性，并且 $\Phi_n$ 沿整条线是连续的。以下证据澄清了这些报告。

我们先研究一下$r_n(x) = \Phi(x) - \Phi_n(x)$的差异（这里$x$是固定的，$n$是可变的）。

$$\Phi_{n+m}(x) - \Phi_n(x) = \varphi_{n+1}(x) + \varphi_{n+2}(x) + \dots + \varphi_{n+m}(x).$$

很明显

$$0 \leqslant \Phi_{n+m}(x) - \Phi_n(x) \leqslant \frac{1}{2^{n+2}} + \frac{1}{2^{n+3}} + \dots +$$

$$+ \frac{1}{2^{n+m+1}} = \frac{1}{2^{n+2}} \cdot \frac{1 - \frac{1}{2^m}}{1 - \frac{1}{2}} < \frac{1}{2^{n+1}}.$$

从$\lim_{m \to \infty} \Phi_{n+m}(x) = \Phi(x)$和$\lim_{m \to \infty} \Phi_n(x) = \Phi_n(x)$开始，

$$0 \leqslant r_n(x) \leqslant \frac{1}{2^{n+1}}.$$

现在我们可以继续证明函数$\Phi$在任意点$x_0 \in \mathbb{R}$的连续性。让我们以 $\varepsilon > 0$ 来考虑差分模型

$$|\Phi(x_0 + h) - \Phi(x_0)| = |\Phi_n(x_0 + h) + r_n(x_0 + h) - \Phi_n(x_0) - r_n(x_0)| \leqslant$$

$$\leqslant |\Phi_n(x_0 + h) - \Phi_n(x_0)| + |r_n(x_0 + h)| + |r_n(x_0)|.$$

但是$|r_n(x_0)| \leqslant \frac{1}{2^{n+1}}$和$|r_n(x_0 + h)| \leqslant \frac{1}{2^{n+1}}$；这就是为什么

$$|\Phi(x_0 + h) - \Phi(x_0)| \leqslant$$

$$\leqslant |\Phi_n(x_0 + h) - \Phi_n(x_0)| + \frac{1}{2^n}.$$

当$n$足够大时

$$\frac{1}{2^n} < \frac{\varepsilon}{2}.$$

函数 $\Phi_n$ 作为有限个连续函数的和，在点 $x_0$ 连续。因此，通过选择$\delta > 0$可以实现$|h| < \delta$

$$|\Phi_n(x_0 + h) - \Phi_n(x_0)| < \frac{\varepsilon}{2}.$$

选择$\delta$时

$$|\Phi(x_0 + h) - \Phi(x_0)| < \varepsilon,$$

这就证明了函数$\Phi$在点$x_0$的连续性。

构造函数的不可微性

函数 $\Phi$ 在线上任何点都不可微。

乍一看，这似乎非常令人惊讶：随着$n$的增长，函数$\Phi_n$的不可微点集变得越来越密集和更深，因此很自然地期望“在极限内”，即对于函数$\Phi$，它将填满整条直线。然而，这种天真的推理是不正确的，如示例函数所示

$$G(x) = \lim_{n \to \infty} G_n(x),$$

其中函数 $G_1, G_2, G_3$ 显示在 图 6 上。显然，$G(x) = 1 - x^2$ 是一个在任意点可微的函数。

通过反证法，我们假设对于某些 $x_0 \in \mathbb{R}$ 存在 $\Phi'(x_0)$。

通过缺陷和图像将 $x_0$ “锁定”在一系列双重近似中：

$$\frac{s_k}{2^{k+1}} \leqslant x_0 < \frac{s_k + 1}{2^{k+1}} \quad (k = 0, 1, 2, \dots; \ s_k \in \mathbb{Z}).$$

让我们输入$\alpha_k = \frac{s_k}{2^{k+1}}, \beta_k = \frac{s_k + 1}{2^{k+1}}$。然后

$$\alpha_k \leqslant x_0 < \beta_k \quad (k = 0, 1, 2, \dots)$$

和

$$\lim_{k \to \infty} \alpha_k = \lim_{k \to \infty} \beta_k = x_0.$$

来自 (1)

$$0 < \frac{\beta_k - x_0}{\beta_k - \alpha_k} \leqslant 1$$

$$0 \leqslant \frac{x_0 - \alpha_k}{\beta_k - \alpha_k} \leqslant 1.$$

从这里，从（2）和易于验证的身份

$$\frac{\Phi(\beta_k) - \Phi(\alpha_k)}{\beta_k - \alpha_k} - \Phi'(x_0) =$$

$$= \frac{\beta_k - x_0}{\beta_k - \alpha_k} \left[ \frac{\Phi(\beta_k) - \Phi(x_0)}{\beta_k - x_0} - \Phi'(x_0) \right] +$$

$$+ \frac{x_0 - \alpha_k}{\beta_k - \alpha_k} \left[ \frac{\Phi(x_0) - \Phi(\alpha_k)}{\beta_k - x_0} - \Phi'(x_0) \right]$$

应该

$$\lim_{k \to \infty} \frac{\Phi(\beta_k) - \Phi(\alpha_k)}{\beta_k - \alpha_k} = \Phi'(x_0).$$

⟦folio 12⟧

$$\Phi(2\bar{x}) = 2\Phi(\bar{x}) - 2\varphi_0(\bar{x}) = 2\Phi(\bar{x}) - 2\bar{x} = 2M - 2\bar{x} \leqslant M$$
$$\bar{x} \geqslant \frac{M}{2} \geqslant \frac{1}{3}.$$

根据函数 Ф 的图形相对于直线 $x = \frac{1}{2}$ 的对称性，可以得出区间 $] \frac{2}{3}; 1]$ 上不存在极大点。

现在让我们证明$M = \frac{2}{3}$。我们再次应用等式（3）：

$$\Phi(4x) = 2\Phi(2x) - 2\varphi_0(2x) = 2[2\Phi(x) - 2\varphi_0(x)] - 2\varphi_0(2x) = 4\Phi(x) - 4\varphi_0(x) - 2\varphi_0(2x)$$
$$\Phi(x) = \varphi_0(x) + \frac{1}{2}\varphi_0(2x) + \frac{1}{4}\Phi(4x) = \Phi_1(x) + \frac{1}{4}\Phi(4x).$$

构造了线段 $[\frac{1}{4}; \frac{3}{4}]$ 上的函数 $\Phi_1$ 并等于 $\frac{1}{2}$ (图 3)，因此在该线段上

$$\Phi(x) = \frac{1}{2} + \frac{1}{4}\Phi(4x).$$

由于$\bar{x} \in [\frac{1}{3}; \frac{2}{3}] \subset [\frac{1}{4}; \frac{3}{4}]$，等式（4）可以应用于$\bar{x}$：

$$M = \Phi(\bar{x}) = \frac{1}{2} + \frac{1}{4}\Phi(4\bar{x}) \leqslant \frac{1}{2} + \frac{1}{4}M$$
$$M \leqslant \frac{2}{3}.$$

让我们记住$M \geqslant \Phi(\frac{1}{3}) = \frac{2}{3}$，最后找到$M = \frac{2}{3}$。另外，$\Phi(\frac{1}{3}) = \Phi(\frac{2}{3}) = \frac{2}{3}$。

进一步证明若$\bar{x} - \text{точка максимума},$则$4\bar{x} - \text{точка максимума};$若$4\bar{x} - \text{точка максимума}$且$\{\bar{x}\} \in [\frac{1}{4}; \frac{3}{4}]$则$\bar{x} - \text{точка максимума}$。为了证明这一点，请注意等式 (4) 对于所有 $x$ 都成立，其中$\{x\} \in [\frac{1}{4}; \frac{3}{4}]$（检查！）。让$\bar{x} - \text{точка максимума}$。然后$\{\bar{x}\} \in [\frac{1}{3}; \frac{2}{3}] \subset [\frac{1}{4}; \frac{3}{4}]$。

$$\frac{2}{3} = M = \Phi(\bar{x}) = \frac{1}{2} + \frac{1}{4}\Phi(4\bar{x})$$
$$\Phi(4\bar{x}) = \frac{2}{3} = M.$$

现在让$4\bar{x} - \text{точка максимума}$和$\{\bar{x}\} \in [\frac{1}{4}; \frac{3}{4}]$。然后$\Phi(4\bar{x}) = M = \frac{2}{3}$和$\Phi(\bar{x}) = \frac{1}{2} + \frac{1}{4}\Phi(4\bar{x}) = \frac{2}{3} = M.$

许多最大点

让我们找出集合$E$的结构。

或许，如果埃尔米特知道它有多么复杂，他会对范德瓦尔登的功能更加厌恶。另一方面，谁知道呢——也许这个集合美丽而微妙的结构会吸引埃尔米特去研究不可微函数。

我们知道集合$E$的两个点：

$$\frac{1}{3} \text{ и } \frac{2}{3};$$我们也知道$E \subset [\frac{1}{3}; \frac{2}{3}]$。

此外，集合$E$是闭集。这意味着：如果集合$E$中存在收敛的点序列，则该序列的极限也属于$E$。让我们证明一下。设$x_n \in E$($n=1, 2, 3, \dots$)，即$\lim_{n \to \infty} x_n = \bar{x}$；那么根据函数$E$在点$\bar{x}$的连续性可以得出$\Phi(\bar{x}) = \Phi(\lim_{n \to \infty} x_n) = \lim_{n \to \infty} \Phi(x_n) = M$，即$\bar{x} \in E$。

根据上一段最后的证明以及$1$是函数$E$的周期，可以得出，如果$x - \text{точка максимума} E$，则点$\frac{1}{4} + \frac{x}{4} = \frac{x+1}{4}, \frac{2}{4} + \frac{x}{4} = \frac{x+2}{4}$也属于$E$。因此，从点$\frac{1}{3}, \frac{2}{3}$开始，可以构造集合$E: \frac{1}{4} + \frac{1}{4} \cdot \frac{1}{3}, \frac{2}{4} + \frac{1}{4} \cdot \frac{1}{3}, \frac{1}{4} + \frac{1}{4} \cdot \frac{2}{3}$的许多点，等等。

很容易看出所有数字的形式

$$x = \frac{a_1}{4} + \frac{a_2}{4^2} + \dots + \frac{a_n}{4^n} + \frac{1}{4^n} \cdot \frac{a_{n+1}}{3},$$

⟦folio 13⟧

其中$a_1, a_2, \dots, a_n, a_{n+1}$是一个或两个，并且是集合$E$的元素。自从
$$\frac{1}{3} = \frac{1}{4} + \frac{1}{4^2} + \frac{1}{4^3} + \dots,$$
这样的$x$可以表示为
$$x = \frac{a_1}{4} + \frac{a_2}{4^2} + \dots + \frac{a_n}{4^n} + \frac{a_{n+1}}{4^{n+1}} + \frac{a_{n+1}}{4^{n+2}} + \dots$$
或者，类比小数，以周期长度为 1 的无限周期四元分数的形式：
$$x = 0, a_1 a_2 \dots a_n a_{n+1} a_{n+1} = 0, a_1 a_2 \dots a_n (a_{n+1}).$$
由于集合 $E$ 是闭集，任意数
$$x = \frac{a_1}{4} + \frac{a_2}{4^2} + \dots + \frac{a_n}{4^n} + \frac{a_{n+1}}{4^{n+1}} + \frac{a_{n+2}}{4^{n+2}} + \dots$$
其中$a_i$是一个或两个，集合$E$属于。事实上，对于每个这样的$x$，我们可以找到一系列从$E$收敛到$x$的$(x_n)$元素；例如如果
$$x_n = \frac{a_1}{4} + \frac{a_2}{4^2} + \dots + \frac{a_n}{4^n} + \frac{1}{4^n} \cdot \frac{1}{3},$$
然后$\lim_{n \to \infty} x_n = x \left(0 \leqslant x - x_n \leqslant \frac{1}{4^{n+1}}\right)$。

因此，集合$E$包含所有数字，其中$0, a_1 a_2 a_3 \dots$作为无限四元分数的表示，所有数字$a_i$不是一就是二（在图8上描述了数字$\frac{1}{12}, \frac{2}{12}, \dots, \frac{11}{12}$的四元展开式）。

现在让我们证明$E$不包含任何其他数字。设$x \in E$的四进制数中小数点后某位有一个数字0，即$x = 0, a_1 a_2 \dots a_n 0 a_{n+2} \dots$；然后$\{4^n x\} = 0, 0 a_{n+2} \dots \in E$。

但$0, 0 a_{n+2} a_{n+3} \dots < 0, 033 \dots = 3 \left(\frac{1}{4^2} + \frac{1}{4^3} + \dots\right) = \frac{1}{4}$，因此点$\{4^n x\}$不属于包含$E$的线段$\left[\frac{1}{3}; \frac{2}{3}\right]$。

若数$x \in E$的四元数包含数字3，即$x = 0, a_1 a_2 \dots a_n 3 a_{n+2} \dots$，则
