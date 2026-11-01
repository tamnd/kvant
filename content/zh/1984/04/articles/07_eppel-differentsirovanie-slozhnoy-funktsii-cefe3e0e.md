---
id: 1984-4-eppel-differentsirovanie-slozhnoy-funktsii-cefe3e0e
issue: kvant_1984_4
year: 1984
number: "4"
title: 复杂函数的微分
authors:
  - Эппель Б. С.
rubric: shkola-v-kvante
rubric_sub: Школа в «Кванте»
page_first: 28
page_last: 29
page_labels: 26-27
tag: XU9Q
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 3297790bb8b3a1691a36cd8920e3c8e8273376833cd14acbc0272d76a7c44dee
prompt_sha256: draft-1
translated_from: content/ru/1984/04/articles/07_eppel-differentsirovanie-slozhnoy-funktsii-cefe3e0e.md
source_content_sha256: a901df70b8c9497bdfa82aed0636d9ea30d927b5870358f5f205858c3bcbc399
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 26⟧

丝波，其强度与加速度的平方成正比。

该定律还要求 RENTEN 管发射电磁波。电子在阴极和异头物之间的空间中的深真空中通过，被电场加速到高速，然后当它们与异头物碰撞时急剧减速。在这种情况下，会发生显着的加速，并且电子发射电磁波。这种类型的辐射称为轫致辐​​射。

事实证明，当电子减速时，它们会发射不同频率（或波长）的全谱电磁波。这个频谱是连续的，但它被限制在某个最大频率$v_{\text{max}}$（这样的频率限制只能从量子理论的角度来解释）。

最高频率（以及相应的最小波长）由电子动能 $eU$（U 是异头物和阴极之间的电压）等于发射量子的能量的条件确定：

$$eU = hv_{\text{max}},$$

在哪里

$$v_{\text{max}} = \frac{eU}{h},$$

相应地，最小波长

$$\lambda_{\text{min}} = \frac{c}{v_{\text{max}}} = \frac{ch}{eU} \cdot$$

其中 $h$ 是普朗克常数，$c$ 是光速。在几十千伏的电位差下，最小波长达到零点几埃 ($1\mathring{\mathrm{A}} = 10^{-10}\text{ m}$)。这种短体积辐射具有很高的穿透能力，被称为RENTen辐射。

(*) 通过实验测量最小波长$\lambda_{\text{min}}$和电压$V$，我们可以根据这个等式确定普朗克常数$h$的值。从这样的实验中获得值$h = 6,62 \cdot 10^{-34}\text{Дж} \cdot \text{с}$。

复杂函数的微分

V.S.埃佩尔

所有申请者都知道$(\sin x)' = \cos x$。然而，像$(\sin 2x)' = \cos 2x$或$(\sin^3 x)' = \cos^3 x$这样的等式是申请人犯下的错误，这是非常不正确的。事实上，函数 $\sin 2x$ 和 $\sin^3 x$ 很复杂，并且区分了它们 - 任务也更复杂。我们将在这里展示如何实际解决这个问题。

当申请人不知道如何破译条目$y = \sin^3 x$并且没有在这个简单的表达式中看到一个复杂的函数——两个函数的组合时，就会出现像$(\sin^3 x)' = \cos^3 x$这样的错误（参见“代数和分析的开始”9-10，第20段）。事实上，函数$y = \sin^3 x$是通过顺序执行两个运算得到的：取角度$x$的蓝色并对结果数$\sin x$进行立方：

$$x \rightarrow \sin x \rightarrow (\sin x)^3.$$

在函数 $y = \sin^3 x$ 的表示法中，您需要能够一个接一个地分别看到组成该函数的两个函数（正弦函数和幂函数）。如果这个函数写成$y = (\sin x)^3$，就更容易做到。

为了清楚起见，我们首先将使用颜色帮助读者识别复杂的函数。在我们的例子中

$$y = (\sin x)^3 \quad \text{или} \quad y = \sin^3 x$$

在一般情况下，应用复函数的微分规则（“代数和分析原理 9-10”，第 21 段）

$$(f(g(x)))' = f'(g(x)) \cdot g'(x)$$

有必要能够以$f(g(x))$的形式“看到”这个函数。要做到这一点，颜色首先会帮助我们。两个示例之间的距离。

让我们对函数进行微分

$$y = \sin 2x = \sin u, u = 2x$$

（每个函数都有自己的颜色）：

$$y' = (\sin u) \cdot (2x)' = (\cos u) \cdot 2 = 2\cos 2x.$$

⟦folio 27⟧

（但不是 cos 2x。）
完全一样
$$y = \sin^3 x = u^3, \quad u = \sin x;$$
$$y' = (u^3)' \cdot (\sin x)' = (3u^2) \cdot (\cos x) = 3 \sin^2 x \cos x.$$

（但不是 cos³ x。）
实际上，对任意城市的这种区分更短、更简单，至少不需要将 u 引入符号中。

区分复杂函数的艺术在于能够在区分时只看到一个函数（即在给定时刻被区分的函数），而不会注意到其他函数 - 他们的视野在区分时是开放的。

这里再举几个演示例子，不引入中间的“u”，复杂函数的微分通常是由那些具有熟练微分技巧的人来执行和编写的。只是，和以前一样，我们将用相同的颜色编写每个可微函数及其任意一个。

$$y = (2x^4 - 5x^2 + 6)^8;$$
$$y' = 8(2x^4 - 5x^2 + 6)^7 \cdot (8x^3 - 10x).$$
$$y = \sqrt{R^2 - x^2} = \left(R^2 - x^2\right)^{\frac{1}{2}};$$
$$y' = \frac{1}{2}\left(R^2 - x^2\right)^{-\frac{1}{2}} \cdot (-2x) = \frac{-x}{\sqrt{R^2 - x^2}}$$

下一个复杂函数是
$$y = \sin^3 5x.$$

至少从颜色的数量可以看出，它是三个功能的组合：1）蓝色； 2）求幂； 3）乘以5。

我们来区分一下：
$$y = \sin^3 5x;$$
$$y' = \left(3 \sin^2 5x\right) \cdot \left(\cos 5x\right) \cdot \left(5\right) = 15 \left(\sin^2 5x\right) \cos 5x.$$

由于更改化合物的位置不会改变产品，因此不用说，您可以按任何顺序对功能进行排序以进行差异化。

再举几个例子：
$$y = \mathrm{tg} x^3; \quad y' = \frac{3x^2}{\cos^2 x^3}.$$
功能

我们使用公式 $(uv)' = u'v + v'u$ 将函数的乘积微分：
$$y' = \left(x^2\right)' \left(\ln x^3\right) + \left(x^2\right)' \cdot \left(\ln x^3\right)' = 2x \ln x^3 + x^2 \cdot \frac{1}{x^3} \cdot \left(3x^2\right) = 2x \ln x^3 + 3x.$$

$$y = 2x^3 - 5x;$$
$$y' = 2x^3 - 5x \ln 2 \cdot \left(3x^2 - 5\right)$$

于差别处。根据需要使用多颜色符号进行区分：
1. $y = (x^3 + 2)^4$; 2. $y = \sqrt{1 + 5x^2}$;
3. $y = e^{x^2 - 3x}$; 4. $y = \ln (2x^3 - 4x^2)$;
5. $y = \lg (2x^3 - 4x^2)$; 6. $y = 5^{\sin x}$;
7. $y = \log_{0.3}(8x^2 - 2x^3)$;
8. $y = \cos (2x - 1)$; 9. $y = \cos^2 3x$;
10. $y = \sqrt{\mathrm{tg} x}$; 11. $y = x \mathrm{tg}^2 x$;
12. $y = \sin \sqrt{ax}$; 13. $y = \ln \sin x$;
14. $y = 3^{\frac{1}{x}}$; 15. $y = \frac{1}{\cos 2x}$.

16. 证明函数 $y = c \sqrt{1 + x^2}$ 可作为微分方程 $y' = xy / (1 + x^2)$ 的解。

修正案
1) 在 «Kvant» 第 1 页中。选项1的问题1的第二个方程中的57，15被错误地与55打印在一起。
2) 在第 4 页的最后一段中。 47 «Kvant» No.2 第 1、4、7 个粗体字母 A 和第 1、3、5、6、8 个粗体字母 B 上方应有一行（A、B），因印刷厂故障而漏掉。
