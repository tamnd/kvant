---
id: 1972-3-margulis-radunskiy-uchites-rabotat-s-logarifmami-fc3b830c
issue: kvant_1972_3
year: 1972
number: "3"
title: 学习使用对数
authors:
  - Маргулис А. Я.
  - Радунский Б. А.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 52
page_last: 57
page_labels: 50-55
tag: YENX
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 916117314f86d8d5f882d6a99b8915a86273348056e9f05c06b5f805a07acb0b
prompt_sha256: draft-1
translated_from: content/ru/1972/03/articles/15_margulis-radunskiy-uchites-rabotat-s-logarifmami-fc3b830c.md
source_content_sha256: 746a80a55cbfb2ad5cdcc9777c72ae441553aa8c434e9707c8cbe2fc3432e429
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 50⟧

学习工作
带对数
A. 是的。马古利斯，B.A.拉敦斯基

定对数

众所周知，数$N$以$a$为底的对数（$a > 0; a \neq 1$）是指以$a$为底必须乘以得到给定数$N$的指数，即对于$a > 0$、$a \neq 1$、$x = \log_a N$，如果$a^x = N$。

对数定义的数学符号是所谓的基本对数恒等式：

$$a^{\log_a N} = N \quad (a > 0, a \neq 1, N > 0).$$

让我们回想一下，任何具有任何底数（正且不同于 1）的正数都有对数，但负数和零没有对数。

主要身份的 10 个推论

如果数字 $a$ 和 $b$ 为正且不等于 1（$M > 0$ 和 $N > 0$），则以下关系（对数性质）有效：

$$\log_a MN = \log_a M + \log_a N,$$

$$\log_a \frac{M}{N} = \log_a M - \log_a N,$$

$$\log_a M^\alpha = \alpha \log_a M,$$

$$\log_a N = \frac{\log_b N}{\log_b a},$$

$$\log_b a \times \log_a N = \log_b N,$$

$$\log_a b = \frac{1}{\log_b a},$$

$$\log_a^k N = \frac{1}{k} \log_a N \quad (k \neq 0),$$

$$\log_a^k N^k = \log_a N \quad (k = 0),$$

$$\frac{\log_a N}{\log_a M} = \frac{\log_b N}{\log_b M} \quad (M \neq 1),$$

$$\log_a N \times \log_b M = \log_a M \times \log_b N,$$

$$a^{\log_b c} = c^{\log_b a}.$$

式(1)、(2)、(3)称为对数规则。它们可以让您找到乘积 (1)、商 (2) 和度（或

⟦folio 51⟧

（3）。相同的公式允许您通过对数（即增强的乘积）找到一个数字。

公式（4）有特殊的意义——它是移动到新基地的公式。由于这个公式，不需要有不同底数的对数表：例如，有一个十进制对数表就足够了，可以使用公式（4）找到与我们相交的任何底数的对数。

式（8）表明两个数的对数之比不依赖于底数。

公式(1)-(5)的证明是在学校课程中进行的*)；读者可以很容易地自己证明公式（6）和（7），利用公式（4）移至底数$a$。如果你注意到公式（8）的左右两边都等于数字$\log_M N$，就很容易验证公式（8）的有效性（为什么？）；式(9)只是等式(8)的另一种表示。公式（10）的基本原理如下：

$$a^{\log_b c} = a^{\frac{\log_a c}{\log_a b}} = (a^{\log_a c})^{\log_b a} = c^{\log_b a}.$$

评论

我们提出了$M > 0$和$N > 0$。然而，在求解对数方程（或不等式）时，当$M$和$N$的作用是未知数$x$的表达式时，使用上述公式进行变换可能会导致不等式（不等式）。在这种情况下，应使用更通用的公式**)；例如，如果$M(x) \cdot N(x) > 0$，那么

$$\log_a M(x) \cdot N(x) = \log_a |M(x)| + \log_a |N(x)|.$$

现在我们也不会考虑头发。我们的目标是展示对数的基本属性如何应用于方程，如何用一个对数计算另一个对数，并比较它们的大小。

简化包含对数的表达式

仔细检查用铅笔和纸给出的例子；理解上面列出的公式在哪里使用很重要（我们专门详细地进行了转换，但几乎没有解释）。

示例 1. 简化：$\log_3 5 \cdot \log_4 9 \cdot \log_5 2$。

解决方案。 $\log_3 5 \cdot \log_4 9 \cdot \log_5 2 = \log_3 5 \cdot \log_5 2 \cdot \log_2 3 = \log_3 2 \cdot \log_2 3 = \log_3 3 = 1$。

示例 2. 简化表达式：

$$N = \frac{\log_a \left[ \frac{1}{2} \log_b a^2 \right] \cdot \lg a \cdot \log_a \frac{1}{2} 100}{\left(\lg a \cdot 2^{\log_2 \lg a}\right)^{\frac{1}{2}} \cdot \lg^{-\frac{1}{2}} a^2}.$$

解决方案。首先定义允许的参数值范围：$a > 0$、$a \neq 1$、$b > 0$、$b \neq 1$（因为$a$和$b$作为对数的底）、$a > 1$（对于$\log_2 \lg a$的存在，必然存在$\lg a > 0$，因此$a > 1$), 窗户

*) 例如，参见 E. S. Kochetkov、E. S. Kochetkova，《代数和初等函数》，M.，“启蒙”，1970 年，第 183-186 段。

**) 欲了解更多详情，请参阅 G.V.多罗费耶夫，M.K.波塔波夫，N.Kh. Rozov，大学申请者数学手册，M.，“Nauka”，1970 年。

⟦folio 52⟧

特别

$$a > 1; b > 0; b \neq 1.$$

我们有
$$\log_a \left[ b^{\frac{1}{2} \log_b a^2} \right] \cdot \lg a \cdot \log_a^{\frac{1}{2}} 100 = \log_a b^{\log_b a} \cdot \lg a \sqrt{2 \log_a 10} =$$
$$= \frac{\log_a a \cdot \lg a \cdot \sqrt{2}}{\sqrt{\lg a}} = \sqrt{2 \lg a}; \quad (\lg a \cdot 2^{\log_2 \lg a})^{\frac{1}{2}} \lg^{-\frac{1}{2}} a^2 =$$
$$= \frac{\sqrt{\lg a \cdot \lg a}}{\sqrt{2 \lg a}} = \sqrt{\frac{\lg a}{2}};$$

最后$N = \frac{\sqrt{2 \lg a}}{\sqrt{\frac{\lg a}{2}}} = 2.$

示例 3. 让我们简化一下表达式：
$$\left( b^{\frac{\log_{1000} a}{\lg a}} \cdot a^{\frac{\log_{1000} b}{\lg a}} \right)^3 \log_{ab} (2a + 3b)$$

解决方案。参数必须满足条件$a > 0; a \neq 1; b > 0; b \neq 1$（解释原因）。

我们有$b^{\frac{3 \log_{1000} a}{\lg a}} \cdot a^{\frac{3 \log_{1000} b}{\lg b}} = b^{\frac{\lg a}{\lg a}} \cdot a^{\frac{\lg b}{\lg b}} = ab,$
可摆姿势的

$$N = (ab)^{\log_{ab} (2a + 3b)} = 2a + 3b.$$

示例 4. 让我们简化一下表达式：
$$N = \left[ \left( \frac{\log_a^2 b + 1}{2 \log_a b} - 1 \right)^{\frac{1}{2}} + \left( \frac{2 \log_a^2 b + 1}{2 \log_a b} + 1 \right)^{\frac{1}{2}} \right] \sqrt{2} \log_a^{\frac{1}{2}} b.$$

解决方案。参数必须满足以下条件：$a > 0; a \neq 1; b > 0, b \neq 1$（解释原因）；此外，要存在$\log_a^{\frac{1}{2}} b$，就必须存在$\log_a b \geq 0$。因此，明确：$a > 1$和$b > 1$或$0 < a < 1$和$0 < b < 1$。下一个，

$$N = \left[ \sqrt{\frac{(\log_a b - 1)^2}{2 \log_a b}} + \sqrt{\frac{(\log_a b + 1)^2}{2 \log_a b}} \right] \sqrt{2 \log_a b} = |\log_a b - 1| + (\log_a b + 1) = \left\{ \begin{array}{l} 2 \log_a b, \text{ если } b \geq a > 1 \text{ или } 0 < b \leq a < 1; \\ 2, \text{ если } a \geq b > 1 \text{ или } 0 < a \leq b < 1. \end{array} \right.$$

示例 2 和 4 清楚地表明考虑允许的参数值范围是多么重要。

通过其他对数提高一些对数

示例 5. 给定：$\log_{30} 3 = a; \log_{30} 5 = b; \text{ найти } \log_{30} 8.$

解决方案。 $\log_{30} 8 = 3 \log_{30} 2 = 3 \log_{30} \frac{30}{15} = 3 (\log_{30} 30 - \log_{30} 3) - \log_{30} 5) = 3 (1 - a - b).$

这里一切都很简单，因为，首先，所有对数的底都是相同的，其次，你可以通过数字、对数来表达数字 2

⟦folio 53⟧

这是给定（或已知）的，即通过数字 30、3 和 5。显然，这并不总是容易做到。

示例 6. 给定：lg196=a； lg56=b;求lg 0.175。

解决方案。用众所周知的数字 196、56 和 10 来表示数字 0.175 并不那么容易。我们来转换一下：

$$\lg 0,175 = \lg \frac{175}{1000} = \lg \frac{7}{40} = \lg 7 - 2 \lg 2 - 1.$$

因此，问题就简化为寻找lg7和lg2。

问题的条件可以写成两个等式的形式：

$$2\lg 2 + 2\lg 7 = a,$$
$$3\lg 2 + \lg 7 = b.$$

其中有

$$\lg 2 = \frac{2b-a}{4}; \quad \lg 7 = \frac{3a-2b}{4}.$$

然后

$$\lg 0,175 = \frac{3a-2b}{4} - \frac{4b-2a}{4} - 1 = \frac{5a-6b-4}{4}.$$

示例 7. 给定：$\log_{14}7=a; \log_{14}5=b; \text{найти } \log_{25}28.$

解决方案。在不同基地的情况下，建议去一个基地：

$$\log_{35}28 = \frac{\log_{14}28}{\log_{14}35} = \frac{\log_{14}2 \cdot 14}{\log_{14}5 \cdot 7} = \frac{1 + \log_{14} \frac{14}{7}}{a+b} = \frac{2-a}{a+b}.$$

示例 8. 给定：$\log_{12}27=a; \text{найти } \log_{6}16.$

解决方案。 $\log_{6}16 = 4\log_{6}2 = 4\frac{\log_{12}2}{\log_{12}6} = \frac{4\log_{12}2}{\log_{12} \frac{12}{2}} = \frac{4\log_{12}2}{1-\log_{12}2}.$

剩下的就是找到$\log_{12}2$。根据问题的条件

$$a = \log_{12}27 = 3\log_{12}3 = 3\log_{12} \frac{12}{4} = 3(1-2\log_{12}2).$$

从这里$\log_{12}2 = \frac{3-a}{6}$，然​​后

$$\log_{6}16 = \frac{4 \cdot \frac{3-a}{6}}{1-\frac{3-a}{6}} = \frac{4(3-a)}{3+a}.$$

按大小比较对数

知道了对数函数的性质，就很容易回答以下问题：两个数字哪个更大：$\log_{2}3$或$\log_{3}2$？

（$\log_{2}3 > \log_{3}2$、或$\log_{2}3 > 1$、$\log_{3}2 < 1$）；

$$\log_{\frac{1}{2}}3 \text{ или } \log_{3}1,1? \quad \left( \log_{\frac{1}{2}}3 < 0, \quad \log_{3}1,1 > 0; \quad \log_{\frac{1}{2}}3 < \log_{3}1,1 \right);$$

$$\log_{3}5 \text{ или } \log_{4}5? \quad (\log_{3}5 > \log_{4}5 - \text{объясните почему});$$

$$\log_{\frac{1}{2}}3 \text{ или } \log_{\frac{1}{2}}4? \quad \left( \log_{\frac{1}{2}}3 > \log_{\frac{1}{2}}4 - \text{объясните почему} \right).$$

当解决更复杂的例子时，除了利用对数函数的性质之外，还需要执行各种变换。

⟦folio 54⟧

实施例 9（MSU，化学系，1969）。没有表格，确定哪个更大：$\log_{20}80$ 或 $\log_{80}640$？

解决方案。我们将尽可能使用给定的对数并将它们减少到相同的底数：

$$\log_{20}80 = 1 + 2\log_{20}2 = 1 + \frac{2}{\log_{2}20},$$

$$\log_{80}640 = 1 + 3\log_{80}2 = 1 + \frac{3}{\log_{2}80}.$$

剩下的就是比较数字$\frac{2}{\log_{2}20}$和$\frac{3}{\log_{2}80}$。但是$\log_{2}20 > 0; \log_{2}80 > 0$和$2\log_{2}80 = \log_{2}6400 < 3\log_{2}20 = \log_{2}8000$。因此$\frac{2}{\log_{2}20} < \frac{3}{\log_{2}80}$，即$\log_{20}80 < \log_{80}640$。

实施例 10.（密歇根州立大学心理学系，1969 年）。不使用表格，证明$\log_{3}7 > \log_{7}27$。

解决方案。由于$\log_{7}27 = 3\log_{7}3 = \frac{3}{\log_{3}7}$和$\log_{3}7 > 0$，证明$\log_{3}^27 > 3$或$\log_{3}7 > \sqrt{3}$或$7 > 3\sqrt{3}$就足够了。

让我们尝试详细说明无理指数的“方便”近似。也就是说，利用$\sqrt{3} < 1,75 = \frac{7}{4}$这个事实，让我们比较$7$和$3^{\frac{7}{4}}$，即$7^4$和$3^7$。从它开始引入$7^4 = 2401 > 3^7 = 2187$，然后是$7 > 3^{\frac{7}{4}} > 3^{\sqrt{3}}$，然后是$\log_{3}7 > \log_{7}27$。

示例 11. 在没有表格的情况下，确定哪个更大：$\log_{5}7$ 或 $\log_{13}17$？

解决方案。减少到一个基数并不会带来任何好处。不过这个例子已经被前面两个解决了。注意$1 < \log_{5}7 < 2$，$1 < \log_{13}17 < 2$。那么我们来比较一下数字

$$\log_{5}7 - 1 = \log_{5}7 - \log_{5}5 = \log_{5}\frac{7}{5}$$

和

$$\log_{13}17 - 1 = \log_{13}17 - \log_{13}13 = \log_{13}\frac{17}{13}.$$

但是$\log_{5}\frac{7}{5} > \log_{13}\frac{7}{5} > \log_{13}\frac{17}{13}$（解释原因），然后是$\log_{5}7 > \log_{13}17$。

例 12. 证明对于任何自然数 $n > 1$

$$\log_{n}(n+1) > \log_{n+1}(n+2).$$

解决方案。显然$\frac{n+1}{n} = 1 + \frac{1}{n} > \frac{n+2}{n+1} = 1 + \frac{1}{n+1}$。因此，利用对数函数的性质，我们有（对于 $n > 1$）

$$\log_{n}\frac{n+1}{n} > \log_{n+1}\frac{n+1}{n} > \log_{n+1}\frac{n+2}{n+1}.$$

对左右两边进行变换，我们立即得到

$$\log_{n}(n+1) > \log_{n+1}(n+2).$$

例如，从这里可以得出

$$\log_{2}3 > \log_{3}4 > \dots > \log_{k+1}(k+2).$$

⟦folio 55⟧

招待会 13。（密歇根州立大学，语言学院，1969 年）。无需使用表格即可证明 $\log_2 3 > \log_3 5$。

解决方案。前面两个例子中使用的方法不能直接应用（勾选此项）。因此，我们会这样做：$\log_2 3 = \log_8 27$；

$$\log_3 5 = \log_9 25, \text{ а } \frac{27}{8} > \frac{25}{9}.$$

接下来是$\log_8 \frac{27}{8} > \log_9 \frac{27}{8} > \log_9 \frac{25}{9}$或$\log_8 27 - 1 > \log_9 25 - 1$，因此是$\log_2 3 > \log_3 5$。

练习

化简下列表达式：

1. $\frac{1}{5} \left( 2a^{\log_2 b} + 3b^{\log \sqrt{2}} \sqrt{a} \right)$.
2. $\left[ 1 + 2^{\frac{\lg a}{\lg \sqrt{2}}} - a^{1 + \frac{1}{\log_4 a^2}} \right]^{\frac{1}{2}} - 3 \log_3 2 \times \log_4 3 \cdot \log_5 4 \cdot \log_6 5 \cdot \log_7 6 \cdot \log_8 7$.
3. $\sqrt{\log_a b + \log_b a + 2 \cdot \log_{ab} a} \cdot \log_a^2 b$.

不使用表格计算：

4. $2^{\sqrt{\log_2 3}} - 3^{\sqrt{\log_3 2}}$.
5. （密歇根州立大学，心理学家学院，1971 年）。
$$\frac{\log_3 135}{\log_{15} 3} - \frac{\log_3 5}{\log_{405} 3}$$.
6. 如果$\log_12 2 = a$，则计算$\log_6 32$。
7. 如果$\lg 2 = a$，$\lg 3 = b$，则计算$\log_5 0,18$。
8. 如果$\log_8 15 = \alpha$，$\log_{12} 18 = \beta$，则计算$\log_{25} 24$。
无需表格的帮助，确定哪个更大：

9. $\log_2 3$还是$\log \frac{1}{4}$？
10. $\log_4 5$还是$\log \frac{1}{16}$？
11. $\log_5 7$还是$\log_8 3$？
12. $\log_2 3$还是$\log_5 8$？
13. （密歇根州立大学，机制，1971）。 $3 \log_{16} 1862 + \log_{16} 1866$还是$\log_2 1863$？
14. （密歇根州立大学，化学系，1969 年）。 $\log_{189} 1323$还是$\log_6 147$？
15. （密歇根州立大学，心理学家学院，1969 年）。无需使用表格即可证明 $\log_3 16 > \log_16 729$。
16. （密歇根州立大学语言学院，1969 年）。无需使用表格即可证明 $\log_5 14 > \log_7 18$。
