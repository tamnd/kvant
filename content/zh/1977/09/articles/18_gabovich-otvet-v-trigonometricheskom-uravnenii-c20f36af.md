---
id: 1977-9-gabovich-otvet-v-trigonometricheskom-uravnenii-c20f36af
issue: kvant_1977_9
year: 1977
number: "9"
title: 三角方程的答案
authors:
  - Габович И. Г.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 55
page_last: 57
page_labels: 53-55
tag: FRLD
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 4be9f21b97177ebac56882504ce6499cc8a7d9af39f9e4533f0f26de8f5a66e8
prompt_sha256: draft-1
translated_from: content/ru/1977/09/articles/18_gabovich-otvet-v-trigonometricheskom-uravnenii-c20f36af.md
source_content_sha256: 492e6b37de7a9a2d39c55fc08132eef73cee9ed68da19350ca5217565e467067
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 53⟧

回答
在三角方程中

写出三角方程的答案主要与集合的并集和交集的概念有关。通常，在求解此类方程时，会获得一系列根，并且在最终形式中，答案被写为这些系列的组合。但如果这些系列相交，生活会怎样呢？是否应该排除重复的决定还是不能这样做？
与集合的清晰交集相关的是另一个显然是最重要的问题：答案不应包含未定义方程左侧或右侧表达式的变量值。如果这些值出现在求解过程中，则必须将其排除。为此，您需要能够找到不同系列的交集。

本文就是专门讨论这些问题的。

一个例子
让我们考虑解决以下问题。

示例 1：求解方程
$$\frac{1}{\sin x} - \frac{1}{\sin 2x} = \frac{1}{\sin 4x}.$$ (1)

条件定义变量的有效值为：sin x ≠ 0、sin 2x ≠ 0、sin 4x ≠ 0。这给出了 x ≠ πk、x ≠ πm/2、x ≠ πn/4 (k, m, n∈Z)。不难看出，这三个条件可以用一个条件代替：x ≠ πn/4 (n∈Z)。这既可以从所考虑的三角圆（级数 x = πn/4 包含级数 x = πk 和 x = πm/2）看出，也可以从纯代数角度看出：对于偶数 n，从级数 x = πn/4 获得级数 x = πm/2，对于 n 个 4 的倍数，获得级数 x = πk。这样的k也可以被排除。之后是等式
$$\sin 2x \sin 4x - \sin x \sin 4x = \sin x \sin 2x,$$
在变量的允许值范围上等于原来的。对这个方程进行变换，我们得到：
$$\sin 2x \sin 4x = \sin x (\sin 2x + \sin 4x),$$
$$\sin 2x \sin 4x = 2 \sin x \sin 3x \cos x,$$
$$\sin 2x \sin 4x = \sin 2x \sin 3x,$$
$$\sin 2x (\sin 4x - \sin 3x) = 0,$$
$$\sin 2x \cdot \sin \frac{x}{2} \cdot \cos \frac{7x}{2} = 0.$$

还需要考虑三种情况：
$$\sin 2x = 0, \sin \frac{x}{2} = 0, \cos \frac{7x}{2} = 0.$$

方程 sin 2x = 0 并没有给出原始方程的根，因为在所考虑的区域中必定存在 sin 2x ≠ 0。

方程 sin $\frac{x}{2} = 0$ 和 cos $\frac{7x}{2} = 0$ 给出了级数对应 $x_1 = 2\pi k$ 和 $x_2 = \frac{\pi}{7} (2k + 1) (k \in Z)$。

仍然需要检查它们是否位于区域 $x \in \mathbb{R}$，x ≠ πn/4，n∈Z。级数$x_1$很容易检查：因为$x \neq \pi n/4$，并且对于n = 8l的n倍数，结果只是x≠2πl，整个级数$x_1$被排除。第$x_2$集的情况更加复杂。这里我们需要找出对于什么整数k，有一个满足方程的n
$$\frac{\pi (2k + 1)}{7} = \frac{\pi n}{4},$$
并排除这样的k。之后，方程

⟦folio 54⟧

依稀想起
$$8k + 4 = 7n,$$
此外，出于数值目的，必须求解该方程。

二变量线性微分方程
具有两个变量的线性微分方程称为以下形式的方程
$$ax + by = c,$$
(2)
其中$a$和$b$是非零整数，$c$是任意整数，只需要找到整数解。
我们可以假设方程（2）中的数字$a, b$和$c$是互质的（我们总是可以将方程（2）两边都约简gcd$(a, b, c) \neq 1$）。
但如果数字互质，它们可能不会成对互质（例如：6、10、15）。显然，如果方程（2）中的数$a$和$b$不互质，则该方程无整数解。事实上，把$a = ka_1$，$b = kb_1$，我们得到$(a_1x + b_1y) = c$，打开$(a_1x + b_1y = c/k)$，如果$x$和$y$是整数，那么$c/k$是整数，这是不可能的，因为$c$不能被$k$整除（我们假设$a, b$和$c$是互质数）。

若式(2)中$a$和$b$互质数，则该方程有整数解。我们不会详细讨论这一事实的证明，而只会展示如何找到所有解决方案，如果至少其中一个解决方案已知（必须通过选择来搜索）。

令 $(x_0, y_0)$ 为方程 (2) 的某个整数解：
$$ax_0 + by_0 = c.$$
让我们从方程（2）中逐项减去这个等式项；我们得到
$$a(x - x_0) + b(y - y_0) = 0,$$
在哪里
$$x = x_0 - \frac{b(y - y_0)}{a}.$$

为了使由式(3)定义的$x$是整数，数$\frac{b(y - y_0)}{a}$也是整数是必要且充分的。但是，根据假设，$a$和$b$互质，因此$\frac{y - y_0}{a}$必须是整数。用字母$t$表示关系$\frac{y - y_0}{a}$，我们得到：
$$x = x_0 - bt,$$
$$y = y_0 + at,$$
其中$t \in \mathbb{Z}$。

继续这个例子
因此，出于数字目的，我们需要求解方程
$$7n - 4 = 8k.$$
很明显，$n$ 必须能被偶数整除；放入$n = 4$，我们找到$7 \cdot 4 - 4 = 24 = 8k$，打开$k = 3$。我们很快找到了方程的一个解：$k = 3$，$n = 4$。通解则写为 $k = 3 + 7t$, $n = 4 + 8t$ ($t \in \mathbb{Z}$)。

由此可见，在系列$x_2$（参见第53页）中，需要排除形式$3 + 7t$的所有$k$，即示例1的答案可以写成以下形式
$$x = \frac{\pi}{7}(2k + 1), k \neq 7t + 3, t \in \mathbb{Z}$$
或者
$$\left\{\frac{\pi}{7}(2k + 1)\right| k \neq 7t + 3; k, t \in \mathbb{Z}\}.$$

方程$8k + 4 = 7n$无需使用一般理论即可求解。由此得出 $n = 4l$（因为等式左边可被偶数整除）。将$n = 4l$代入方程，可得：$8k + 4 = 28l$，开$2k + 1 = 7l$。接下来，$l$必须是奇数，$l = 2t + 1$；因此$2k + 1 = 14t + 7$，$k = 7t + 3$。这是解决方案：$k = 7t + 3$，$n = 4l = 4(2t + 1) = 8t + 4$。

记录响应
现在我们来看另一个问题。
示例 2：求解方程
$$\sin^2 2x + \sin^2 3x + \sin^2 4x + \sin^2 5x = 2.$$
使用已知的数据点，我们得到：
$$\frac{1 - \cos 4x}{2} + \frac{1 - \cos 6x}{2} + \frac{1 - \cos 10x}{2} = 2,$$
与 $4x + \cos 6x + \cos 8x + \cos 10x = 0,$
$2 \cos 5x \cos x + 2 \cos 9x \cos x = 0,$

⟦folio 55⟧

cos x (cos 5x + cos 9x) = 0,
cos x cos 2x cos 7x = 0.

考虑三种情况，我们获得三个系列的根（$k, l, m \in \mathbb{Z}$）：

1) cos x = 0, $x_1 = \frac{\pi}{2} + \pi k$;
2) cos 2x = 0, $x_2 = \frac{\pi}{4} + \frac{\pi l}{2}$;
3) cos 7x = 0, $x_3 = \frac{\pi}{14} + \frac{\pi m}{7}$.

怎样写出答案呢？我需要列出所有三集吗？让我们看看这些系列是否相交。在这里你可以以不同的方式行动。

几何方法。该级数的“周期”等于 π。让我们考虑落在区间 [0; 中的级数 $x_1, x_2, x_3$ 中的那些根。 π]。这将是

$$x_1 : \pi/2;$$
$$x_2 : \pi/4, 3\pi/4;$$
$$x_3 : \pi/14, 3\pi/14; 5\pi/14, \pi/2, 9\pi/14, 11\pi/14, 13\pi/14.$$

很明显，系列$x_1$包含在系列$x_3$中，并且系列$x_2$和$x_3$不相交。这意味着答案可以写成以下形式

$$\left\{ \frac{\pi}{4} + \frac{\pi k}{2}; \frac{\pi}{14} + \frac{\pi k}{7} \mid k \in \mathbb{Z} \right\}.$$

代数方法。系列 $x_1$ 和 $x_2$ 中的公分母为 4：

$$x_1 = \frac{\pi(2+4k)}{4}, \quad x_2 = \frac{\pi(1+2l)}{4}.$$

如果$x_1 = x_2$，则$2+4k = 1 + 2l$，但它后面是偶数，右边是奇数。相等是不可能的，级数$x_1$和$x_2$不相交。同样，我们发现级数$x_2$和$x_3$也不相交。但对于系列 $x_1$ 和 $x_3$，我们得到公式

$$x_1 = \frac{\pi(7+14k)}{14}, \quad x_3 = \frac{\pi(1+2m)}{14}.$$

从等式 7 + 14k = 1 + 2m 我们得到 $m = 7k + 3$。这意味着对于每个$k$，都有一个整数$m$满足等式7 + 14k = 1 + 2m，也就是说，系列$x_1$中的每个根都出现在系列$x_3$中，因此系列$x_1$包含在系列$x_3$中，并且不需要将其固定在答案中。

示例 3. 求解方程 $\cos 7x (\sin 5x - 1) = 0$。

我们立即得到两种情况（$k, n \in \mathbb{Z}$）：

1) cos 7x = 0, $x_1 = \frac{\pi}{14} + \frac{k\pi}{7}$;
2) sin 5x = 1, $x_2 = \frac{\pi}{10} + \frac{2n\pi}{5}$.

这些系列有重叠吗？建议

$$\frac{\pi}{14} + \frac{\pi k}{7} = \frac{\pi}{10} + \frac{2\pi n}{5}$$

接下来是$5k = 14n + 1$。这个方程有解。然而，通过选择找到其中之一：$k = 3, n = 1$，而一般的则具有$k = 3 + 14t, n = 1 + 5t$的形式。

答案可以写成以下形式

$$\left\{ \frac{\pi}{14} + \frac{\pi k}{7}; \frac{\pi}{10} + \frac{2\pi n}{5} \mid k \neq 3 + 14t; \right.$$
$$k, n, t \in \mathbb{Z}$$

或以以下形式

$$\left\{ \frac{\pi}{14} + \frac{\pi k}{7}; \frac{\pi}{10} + \frac{2\pi n}{5} \mid n \neq 1 + 5t; \right.$$
$$k, n, t \in \mathbb{Z}$$.

扫地。否则，系列的组合看起来比较小的系列更复杂。在这种情况下，将这些系列分成“块”可能会很有用。例如，级数$x_1 = \frac{\pi k}{2}$和$x_2 = \frac{\pi}{6} + \frac{\pi k}{3}$的并集可以写为

$$\left\{ \frac{\pi k}{2}; \frac{\pi}{6} + \pi k; \frac{5\pi}{6} + \pi k \mid k \in \mathbb{Z} \right\}.$$

系统

当求解一些三角方程时，它们被方程组代替，
