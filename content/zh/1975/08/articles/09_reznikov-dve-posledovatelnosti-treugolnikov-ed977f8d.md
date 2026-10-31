---
id: 1975-8-reznikov-dve-posledovatelnosti-treugolnikov-ed977f8d
issue: kvant_1975_8
year: 1975
number: "8"
title: 两个三角形序列
authors:
  - Резников А. Г.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 48
page_last: 49
page_labels: 46-47
tag: QXB0
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 4e9fd93d2ef9e5c3cbea3a1102135f70cd66744f15375d60ee39d195142f09ff
prompt_sha256: draft-1
translated_from: content/ru/1975/08/articles/09_reznikov-dve-posledovatelnosti-treugolnikov-ed977f8d.md
source_content_sha256: 898b0404e7e7d6dd6e003ed598110b739f67650461693980d35a87a29f5169e3
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 46⟧

考虑任意三角形$ABC$。 $A_1B_1C_1$我们表示一个三角形，其顶点是$ABC$内接圆与其边（图1）的接触点。类似地，对于三角形$A_1B_1C_1$，我们定义三角形$A_2B_2C_2$等。因此，我们获得了一系列互相内接的三角形

$$ABC, A_1B_1C_1, A_2B_2C_2, \dots$$

(1)

我们定义另一个三角形序列如下：用$A^{(1)}B^{(1)}C^{(1)}$表示一个三角形，其顶点是三角形$ABC$的平分线与外接圆的交点。类似地，对于三角形$A^{(1)}B^{(1)}C^{(1)}$，我们定义三角形$A^{(2)}B^{(2)}C^{(2)}$等。因此，我们获得三角形序列

$$ABC, A^{(1)}B^{(1)}C^{(1)}, A^{(2)}B^{(2)}C^{(2)}, \dots$$

(2)

在本文中，我们将研究序列（1）和（2）的一些属性。我们的许多言论

图 1.

我们不证明这一点。我们希望您能自己完成此操作。

1. 很容易用原三角形的内角来表示三角形$A_1B_1C_1$的内角。例如，$\hat{A}_1 = 90^\circ - \frac{1}{2}\hat{A}$。同样，$\hat{A}_2 = 90^\circ - \frac{1}{2}\hat{A}_1$ 和一般的$\hat{A}_n = 90^\circ - \frac{1}{2}\hat{A}_{n-1}$。

换句话说，角度的顺序 $A, A_1, A_2, \dots, A_n, \dots$，将处理算术几何级数。 Ya 的文章中描述了此类进展。 N.苏科尼卡 «Kvant» 今年排名第一。使用本文的结果，我们得到以下表达式：

$$\hat{A}_n = 60^\circ + \left(-\frac{1}{2}\right)^n (\hat{A} - 60^\circ).$$

(3)

三角形 $A^{(1)}B^{(1)}C^{(1)}$ 的角等于三角形 $A_1B_1C_1$ 的相应角（检查！）。这意味着序列 (1) 和 (2) 是相似三角形的序列。

由式(3)可知，如果$A \neq 60^\circ$，则所有$\hat{A}_n \neq 60^\circ$和$\lim_{n \to \infty} \hat{A}_n = 60^\circ$。同样，$\lim_{\hat{B}_n \to 60^\circ} \hat{B}_n = 60^\circ$ 和角度 $\hat{A}^{(n)}, \hat{B}^{(n)}, \hat{C}^{(n)}$ 也是如此。

2. 设$p_n, S_n R_n, r_n$分别为三角形$A_nB_nC_n$的半周长、面积、外接圆半径和内切圆半径。三角形的值$p^{(n)}, S^{(n)}, R^{(n)}, r^{(n)}$的确定方式类似

⟦folio 47⟧

$A^{(n)}B^{(n)}C^{(n)}$ 和 $p_0, S_0, R_0, r_0$ 为原始三角形 $ABC$。显然$R^{(n)}=R_0, R_n=r_{n-1}$。

让我们证明一下

$$S_n = \frac{1}{2} \frac{R_n}{R_{n-1}} S_{n-1}. \tag{4}$$

足以证明这一点

$$S_1 = \frac{1}{2} \cdot \frac{r_0}{R_0} S_0. \tag{4'}$$

证明。很容易看出（见图1）

$$S_{A_1OB_1} = \frac{1}{2} r_0^2 \sin B_1OA_1 = \frac{1}{2} r_0^2 \sin \hat{C},$$

$$S_{B_1OC_1} = \frac{1}{2} r_0^2 \sin \hat{A},$$

$$S_{C_1OA_1} = \frac{1}{2} r_0^2 \sin \hat{B}.$$

因此$S_1 = \frac{1}{2} r_0^2 (\sin \hat{A} + \sin \hat{B} + \sin \hat{C})$。但根据正弦定理$AB = 2R_0 \sin \hat{C}, BC = 2R_0 \sin \hat{A}, CA = 2R_0 \sin B$。因此，$\sin \hat{A} + \sin \hat{B} + \sin \hat{C} = p_0/R_0$。因此，

$$S_1 = \frac{1}{2} r_0^2 \cdot \frac{p_0}{R_0} =$$

$$= \frac{1}{2} \cdot \frac{r_0}{R_0} r_0 p_0 = \frac{1}{2} \frac{r_0}{R_0} S_0.$$

3. 让我们证明序列 $S_0, S^{(1)}, S^{(2)}, \ldots, S^{(n)}$ 与年龄相关。

因为

$$S_0 = 2 R_0^2 \sin \hat{A} \sin \hat{B} \sin \hat{C},$$

$$S^{(1)} = 2 R_0^2 \cos \frac{\hat{A}}{2} \cos \frac{\hat{B}}{2} \cos \frac{\hat{C}}{2}^*),$$

那么不等式 $S^{(1)} \geq S_0$ 等价于不等式

$$\sin \frac{A}{2} \sin \frac{\hat{B}}{2} \sin \frac{\hat{C}}{2} \leq \frac{1}{8}. \tag{5}$$

让我们证明不等式（5）。使用什么

$$\hat{C} = 180^\circ - (\hat{A} + \hat{B}),$$

让我们像这样变换(5)：

$$\cos \hat{A} + \cos \hat{B} - \cos (\hat{A} + \hat{B}) \leq \frac{3}{2}$$

或者

$$2 \cos \frac{\hat{A} + \hat{B}}{2} \cos \frac{\hat{A} - \hat{B}}{2} - 2 \cos^2 \frac{\hat{A} + \hat{B}}{2} -$$

$$-\frac{1}{2} \leq 0,$$

$$-2 \left( \cos \frac{\hat{A} + \hat{B}}{2} - \frac{1}{2} \cos \frac{\hat{A} - \hat{B}}{2} \right)^2 -$$

$$-\frac{1}{2} \left( 1 - \cos^2 \frac{\hat{A} - \hat{B}}{2} \right) \leq 0. \tag{5'}$$

最后一个不等式是显而易见的。从(5')可知，(5)中的等式仅发生在三角形所有角都等于$60^\circ$的情况下。由于三角形$A_1B_1C_1$和$A^{(1)}B^{(1)}C^{(1)}$相似且相似系数为$\frac{R_0}{r_0}$，则

$$S^{(1)} = \frac{1}{2} \frac{R_0}{r_0} S_0 \tag{6}$$

（见公式4'）。但从$S^{(1)} \geq S_0$开始，这意味着众所周知的不等式$R_0 \geq 2r_0$。

由于序列$S_0, S^{(1)}, S^{(2)}, \ldots, S^{(n)}$与年龄相关，

由于序列$S_0, S^{(1)}, S^{(2)}, \ldots, S^{(n)}$与年龄相关，

4. 可以证明，对于半周长数列$p_0, p_1, p_2, \ldots$，以下不等式成立：

$$p_n \leq \frac{1}{2} p_{n-1}. \tag{7}$$

和之前一样，对于 $n=1$ 证明 (7) 就足够了：

$$p_1 \leq \frac{1}{2} p_0. \tag{7'}$$
