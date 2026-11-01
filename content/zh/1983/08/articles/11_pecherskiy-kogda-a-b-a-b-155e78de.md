---
id: 1983-8-pecherskiy-kogda-a-b-a-b-155e78de
issue: kvant_1983_8
year: 1983
number: "8"
title: 当 |a + b| 时=|一个| + |b|？
authors:
  - Печерский Л. Б.
rubric: shkola-v-kvante
rubric_sub: Школа в «Кванте»
page_first: 40
page_last: 42
page_labels: 38, 40
tag: CUWN
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 8757df45d305f65917d4c5ed80c60930bee21c62a59dafaf39cf53ea91263b76
prompt_sha256: draft-1
translated_from: content/ru/1983/08/articles/11_pecherskiy-kogda-a-b-a-b-155e78de.md
source_content_sha256: 766abcee508261ba8dd7ea58d95fac6cd7ce23742a7283a2354d12d8f62df28b
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 38⟧

什么时候
$$|a + \theta| = |a| + |\theta|$$?

L·B·佩切尔斯基

众所周知（“代数和分析原理 9-10”，第 3 段），
$$|a| - |b| \leqslant |a+b| \leqslant |a| + |b|$$ (1)

从模型的几何意义很容易得出，当且仅当$a$和$b$是相同符号的数字时，$|a+b| = |a| + |b|$，更准确地说（因为不禁止它们中的任何一个为零） - 当$a \geqslant 0$和$b \geqslant 0$或当$a \leqslant 0$和$b \leqslant 0$时。

显然，制定的平等准则可以写为：
$$|a+b| = |a| + |b| \Leftrightarrow ab \geqslant 0.$$ (2)

因此，
$$|a+b| < |a| + |b| \Leftrightarrow ab < 0.$$

“复杂形式”的相等性标准对于任意数量的项都有效： $|a_1+a_2+\dots+a_n| = |a_1| + |a_2| + \dots + |a_n|$ 然后且仅当 $a_1, a_2, \dots, a_n$ - 相同符号的数字（更准确地说，当数字之间 $a_1, a_2, \dots, a_n$ 没有数量不同的标志）。

顺便说一句，陈述 $|a+b+c| = |a| + |b| + |c| \Leftrightarrow abc \geqslant 0$ 是不正确的（为什么？）。

示例 1. 求解方程
$$|\lg(2x-3) + \lg(4-x^2)| = (3) = |\lg(2x-3)| + |\lg(4-x^2)|.$$

根据准则（2），该方程等价于方程
$$\lg(2x-3) \cdot \lg(4-x^2) \geqslant 0$$,
反过来，这相当于系统
$$\begin{cases} \lg(2x-3) \cdot \lg(4-x^2) \geqslant 0 \\ 2x-3 > 0 \\ 4-x^2 > 0 \end{cases}$$

由于$\frac{3}{2} < x < 2 \Leftrightarrow 0 < 2x-3 < 1$，后一个系统等价于系统
$$\begin{cases} \lg(2x-3) < 0 \\ \lg(4-x^2) \leqslant 0 \\ \frac{3}{2} < x < 2 \end{cases}$$

$$\begin{cases} \frac{3}{2} < x < 2 \\ 0 < 4-x^2 \leqslant 1 \end{cases}$$

$$\begin{cases} \frac{3}{2} < x < 2 \\ x^2 \geqslant 3 \end{cases}$$

$$\begin{cases} \frac{3}{2} < x < 2 \\ x \geqslant \sqrt{3} \end{cases}$$

回答。 $[\sqrt{3}; 2]$。

解决不平等问题
$$|\lg(2x-3) + \lg(4-x^2)| < |\lg(2x-3)| + |\lg(4-x^2)|$$

可以通过从其定义域中删除相应方程（3）的$\frac{3}{2}; 2$[解$[\sqrt{3}; 2]$来获得。回答。 $\frac{3}{2}; \sqrt{3}$[。

示例 2. 求解“带参数的方程”
$$|a-2\sin x| + 2|\sin x-\cos x| + |2\cos x-1| = a-1.$$

对于$a < 1$，这个方程显然没有根。现在让$a \geqslant 1$。因为
$$(a-2\sin x) + 2(\sin x-\cos x) + (2\cos x-1) = a-1,$$

您可以对三个项使用相等准则。此外，由于$a-1 \geqslant 0$，方程的解等效于系统
$$\begin{cases} a-2\sin x \geqslant 0 \\ \sin x-\cos x \geqslant 0 \\ 2\cos x-1 \geqslant 0 \end{cases}$$

或“三重不平等”
$$\frac{1}{2} \leqslant \cos x \leqslant \sin x \leqslant \frac{a}{2}.$$

⟦folio 40⟧

不寻常的水晶发生器

（关于开头，请参见第 31 页）
积累的洞多于被扔掉的洞。这将导致波动区域中空穴数量的增加，换句话说，导致波动的增加和额外数量的自由电子的流入。结果，场倾角的深度将增加，这将导致捕获的孔的数量进一步增加，等等——所有波动作为一个整体都会增加。然而，也有减少波动的原因。首先，这是电子寿命以及电子和空穴扩散的有限性。

波动的特征尺寸（其宽度）不能小于自由空穴间隙的长度，即它们在陷阱上的两个捕获之间投影的距离。否则，这些空洞将“让”通过波动而不会被捕获。另一方面，只要波动发生，电子就必须保持自由。因此，对于所考虑的过程，无论是在空间上还是在时间上，都存在确定波长及其周期的可能性的特征间隔。

波在晶体中传播，产生载流子富集和耗尽的区域。到达样本末端后，这些区域逐渐消失。结果，样品的电阻周期性变化，并且在电路中观察到电流波动。这就是晶体中产生振动的方式。由于这些振荡与复合过程相关，因此它们以及由它们产生的波被称为复合。

通过研究复合波的特性，科学家们注意到它们的频率和振幅不仅取决于产生晶体的特性，还取决于外部条件——压力、温度、光照和磁场的存在。这意味着这种晶体可以用作将机械、热、光和其他影响转换为电信号的微型转换器。
