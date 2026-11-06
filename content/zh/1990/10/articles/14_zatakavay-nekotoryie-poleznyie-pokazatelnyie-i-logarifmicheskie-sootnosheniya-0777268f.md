---
id: 1990-10-zatakavay-nekotoryie-poleznyie-pokazatelnyie-i-logarifmicheskie-sootnosheniya-0777268f
issue: kvant_1990_10
year: 1990
number: "10"
title: 一些有用的指数和对数关系
authors:
  - Затакавай В. В.
rubric: shkola-v-kvante
page_first: 44
page_last: 45
page_labels: 42-43
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 9a7acdcf238b4d4ed7250718a3cb3743b28f1ef6b269af19c4cec847351afb71
prompt_sha256: draft-1
translated_from: content/ru/1990/10/articles/14_zatakavay-nekotoryie-poleznyie-pokazatelnyie-i-logarifmicheskie-sootnosheniya-0777268f.md
source_content_sha256: 70fff0bf14e0b8a754f79cd2aea384b33b5b90411433e35bf3e078b624b10722
translation_model: draft
translation_run: zh-draft-2026-11-06
translation_quality: draft
---

⟦folio 42⟧

---
running_head:
folio:
---

$x^{\log_2 5} = (5^{\log_5 x})^{\log_2 5} = (5^{\frac{\log_2 x}{\log_2 5}})^{\log_2 5} = 5^{\log_2 x}$，方程的形式为
$5^{\log_2 x} + 2 \cdot 5^{\log_2 x} = 15$.

从这里
$5^{\log_2 x} = 5, \log_2 x = 1, x = 2$.

答案：2。

通过解这个方程，我们实际上推导出了公式
$a^{\log_2 b} = b^{\log_2 a}$. (1)

很容易用一般形式验证式(1)的有效性。让我们以 $c$ 为底对 (1) 的右侧和左侧进行三角剖分。我们得到$\log_c (a^{\log_2 b}) = \log_c (b^{\log_2 a})$，或$\log_c b \times \log_c a = \log_c a \cdot \log_c b$。

显然，这对于$a, b, c$的所有允许值也成立。

这是学校教科书中留下的另一个有用的公式：
$a^{\sqrt{\log_a b}} = b^{\sqrt{\log_b a}}$. (2)

这个公式的证明和上一个公式的证明类似：需要将公式（2）两边以$a$为底进行多边形化：
$\log_a (a^{\sqrt{\log_a b}}) = \log_a (b^{\sqrt{\log_b a}})$,

或者
$\sqrt{\log_a b} = \sqrt{\log_b a} \cdot \log_a b$.

移动到基数$a$，我们得到$\sqrt{\log_a b} = \sqrt{\log_b a}$。

示例 2.
$2^{\sqrt{\log_2 x}} + x^{\sqrt{\log_2 x}} = 4$.

根据式（2）
$x^{\sqrt{\log_2 x}} = 2^{\sqrt{\log_2 x}}$，所以方程变为
$2^{\sqrt{\log_2 x}} + 2^{\sqrt{\log_2 x}} = 4; 2^{\sqrt{\log_2 x}} = 2;$
$\log_2 x = 1; x = 2$.

答案：2。

示例 3.
$\log_3 x (42x^2 - 13x + 1) > 0$.

从“学校的角度”解决这种不平等是劳动密集型的。需要考虑两种情况

⟦folio 43⟧

---
running_head:
folio:
---

茶：当$3x > 1$时和当$0 < 3x < 1$时。
这两种情况都会导致繁琐的不平等制度。
我们声称，如果$\log_a b > 0$，则$(a-1) \cdot (b-1) > 0$，即$(a-1)$和$(b-1)$具有相同的符号。
事实上，如果$\log_a b > 0$，则$\log_a b > \log_a 1$。
对于$a > 1$，我们有$b > 1$，该陈述是正确的。
对于$0 < a < 1$，我们得到$b < 1$，否则该陈述再次为真，因为$(a-1) < 0$和$(b-1) < 0$。
同样，你可以证明 if $\log_a b < 0$ then $(a-1) \cdot (b-1) < 0$ （自己做）。
让我们将我们的陈述应用到示例 3 中。因此，我们有：
$$(42x^2 - 13x)(3x - 1) > 0.$$
使用积分方法可以很容易地解决这个不等式。当然，在这种情况下，有必要考虑限制对数函数定义域的对应关系：
$3x > 0; \quad 3x \neq 1; \quad 42x^2 - 13x + 1 > 0.$
答案：$\left(0; \frac{1}{7}\right) \cup \left(\frac{1}{6}; \frac{13}{42}\right) \cup \left(\frac{1}{3}; +\infty\right)$。
经过深思熟虑的技术使我们能够解决更复杂的不等式。例 4.
$\log_{2-x}(x+2) \cdot \log_{x+3}(3-x) \leq 0.$
应用已证明的陈述，我们得到
$(x+1)(1-x)(2-x)(x+2) \leq 0.$
考虑到不等式左边的定义域：$(-2; 1) \cup (1; 2)$，我们得到
答案：$(-2; -1] \cup (1; 2)$。
总之，我们提供了几个独立解决方案的示例。
1. $5^{\lg x} + x^{\lg 5} = 50.$
2. $25^{\lg x} = 5 + 4 \cdot x^{\lg 5}$.
3. $x^{\log_2 9} = x^2 \cdot 3^{\log_2 x} - x^{\log_2 3}$.
4. $10^{\sqrt{\lg x}} + x^{\sqrt{\log_2 x}} = 0,2.$
5. $3^{-\sqrt{\log_1 x}} + x^{\sqrt{\log_1 x}} = 4,5^{-1}$.
6. $\log_2 x^2(x^2 + x - 1) < 0.$
7. $\log_2 x(5x - 1) \cdot \log_3 x(7x - 1) > 0.$
8. $\log_2 x(10x + 3) \cdot \log_10 x(3x + 10) \geq 0.$
9. $\log_2 x\left(6x + \frac{1}{7}\right) \cdot \log_5 x\left(3x + \frac{4}{7}\right) \leq 0.$

竞赛“数学6-8”
杂志«Kvant»与保加利亚青年杂志“Mathematika”一起继续举办针对6-8年级学生解决数学问题的竞赛。比赛共27题（每期3题），将于明年5月结束。获奖者将获得«Kvant»和Mathematika期刊颁发的奖品。不幸的是，在上一期问题的情况下（参见第 48 页），存在现有的不准确之处。编辑们将他们的发现带给读者并重复这些任务的条款。请在 1990 年 12 月 15 日之前将本期所有问题的解决方案发送至地址：103006, Russia K-6, st.高尔基，32/1，«Kvant»（标记为“竞赛“数学 6-8”}）。不要忘记写上您的姓氏、名字、学校和班级。
