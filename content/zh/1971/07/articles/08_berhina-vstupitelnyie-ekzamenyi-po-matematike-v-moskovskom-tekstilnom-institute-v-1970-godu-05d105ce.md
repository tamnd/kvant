---
id: 1971-7-berhina-vstupitelnyie-ekzamenyi-po-matematike-v-moskovskom-tekstilnom-institute-v-1970-godu-05d105ce
issue: kvant_1971_7
year: 1971
number: "7"
title: 1970年莫斯科纺织学院数学入学考试
authors:
  - Берхина Т. И.
  - Кан Э. М.
rubric: raznoe
rubric_sub: Разное
page_first: 47
page_last: 49
page_labels: 45-47
tag: 9UJO
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 223bc15be5fbbfd9bc5e77d98c02f0f2476283638211b2618c1ac3917a90300a
prompt_sha256: draft-1
translated_from: content/ru/1971/07/articles/08_berhina-vstupitelnyie-ekzamenyi-po-matematike-v-moskovskom-tekstilnom-institute-v-1970-godu-05d105ce.md
source_content_sha256: 73484fbabe9defac7f2665cf412b6797b1c15aaaf43f719831d5686fa376767e
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 45⟧

麻省理工学院的入学考试完全按照大学申请者的数学课程进行。与所有技术学校一样，数学是麻省理工学院入学的一门专业科目。

在能源机械和技术工程学院，申请者将参加两项数学考试：笔试和口试。在机械技术、化学技术和工程经济学院，有一项数学考试——口试。所有院系的奖牌获得者都将参加数学考试。

让我们看一下笔试中提供的选项之一。

选项

1. 解方程
$$\text{ctg} x - 1 = \frac{\cos 2x}{\text{tg} x + 1}.$$

2. 解方程
$$\log_5^4 (x - 1)^2 + \log_5^2 (x - 1)^3 = 25.$$

3. 用 $0 < a \leq 1$ 化简：
$$\frac{1}{\sqrt{5}} \left[ 4 (a + 1) + \left( \sqrt[3]{a \sqrt{a}} - 1 \right)^2 - \left( \frac{\sqrt[6]{ab^2} + \sqrt{a}}{\sqrt[3]{a} + \sqrt[3]{b}} \right)^3 \right]^{\frac{1}{2}}.$$

4. 该示例的底边是直角三角形，具有斜边$c$和锐角$\alpha$，示例的侧边以角度$\phi$倾斜于底平面。查找体积示例。

varnat问题分析

1. 我们找到方程 $x \neq \frac{\pi}{2} l, x \neq \frac{\pi}{4} (4m - 1) (l, m = 0, \pm 1, \dots)$ 的 ODZ。现在让我们变换左侧：$(\text{ctg} x - 1) (\text{tg} x + 1) = \cos 2x,$
$$\frac{\cos x}{\sin x} - \frac{\sin x}{\cos x} = \cos 2x,$$
$$\cos 2x = \frac{1}{2} \cos 2x \sin 2x,$$
$$\cos 2x \left( 1 - \frac{1}{2} \sin 2x \right) = 0.$$ (*)

由于 (*) 中的第二个因子非零 ($\sin 2x \neq 2$)，因此 $\cos 2x = 0$ 和
$$x = \frac{\pi}{4} (2k + 1) \quad (k = 0, \pm 1, \dots).$$

考虑到 ODZ，我们排除了针对奇数 $k$ 获得的值 $x$。

回答：
$$x = \frac{\pi}{4} (4n + 1) \quad (n = 0, \pm 1, \dots).$$

解决这个例子并没有造成任何特别的困难，但是由于没有考虑 ODZ，所以出现了很多额外的根。

2. ODZ 方程为：$x > 1$。让我们使用对数的属性来变换左侧：
$$16 \log_5^4 (x - 1) + 9 \log_5^2 (x - 1) = 25.$$

求解所得的双二次方程

⟦folio 46⟧

nechne，它等价于给定的，我们发现

$$\log_5^2 (x-1) = 1 \text{ или } \log_5^2 (x-1) = -\frac{25}{16}.$$

最后的平等是不可能的；剩下的是$\log_5 (x-1) = \pm 1$，因此$x_1 = 6, x_2 = \frac{6}{5}$。

一个典型的错误是：许多申请人在将指标 2 和 3 放在对数符号之外时，忘记将指标 2 和 3 求相应的幂。

3. 首先我们找到$a$和$b$的有效值：$a \neq -b$。我们来改造一下原来的表达式：

$$\frac{1}{\sqrt{5}} \left[ 4 (a+1) + (\sqrt{a}-1)^2 - \left( \frac{\sqrt[6]{a} (\sqrt[3]{b} + \sqrt[3]{a})}{\sqrt[3]{a} + \sqrt[3]{b}} + \sqrt[6]{a} \right)^3 \right]^{\frac{1}{2}} = \frac{1}{\sqrt{5}} \left[ 4 (a+1) + a - 2 \sqrt{a} + 1 - (2 \sqrt[6]{a})^3 \right]^{\frac{1}{2}} = \left| \sqrt{a}-1 \right| = 1-\sqrt{a}.$$

在解决这个例子时，申请人并没有总是注意条件$0 < a \leq 1$，因此在提取平方根时犯了错误。

4. 示例的高度（参见 图）将穿过底部附近描述的圆的中心 $O$，因为侧边

46

⟦folio 47⟧

这种不平等相当于不平等系统
$$\begin{cases} x^2 - 6 > 0, \\ 0 < \log_3(x^2 - 6) < 1 \end{cases}$$

或者
$$\begin{cases} x^2 - 6 > 0, \\ 1 < x^2 - 6 < 3. \end{cases}$$

第二个不等式包括第一个不等式，从中我们可以找到$7 < x^2 < 9$，$\sqrt{7} < |x| < 3$。

回答：
$$\sqrt{7} < x < 3$$ 或 $-3 < x < -\sqrt{7}$。

在这道题中，很多申请者没有考虑到外对数的底数小于1，还有一些申请者忘记了模数符号，从而丢失了答案的第二部分。

总之，我们提出了一种可供独立决策的口试版本。

选项

解方程：
1. $$\cos \frac{x}{2} \cos \frac{3}{2}x - \sin x \sin 3x - \sin 2x \sin 3x = 0.$$
2. $$2\lg 2 + \left(1 + \frac{1}{2x}\right)\lg 3 - \lg \left(\frac{x}{\sqrt{3}} + 27\right) = 0.$$
3. 简化：
$$\frac{a + x}{\sqrt{a^2} - \sqrt{x^2}} + \frac{\sqrt[3]{ax^2} - \sqrt[3]{a^2}x}{\sqrt[3]{a^2} - 2\sqrt[3]{ax} + \sqrt[3]{x^2}} - \sqrt[6]{a} - \sqrt[6]{x}.$$
4. 正三角形的底边等于$a$，侧面与底平面的夹角为$\phi$。求直线的体积。

个人任务

解方程组：
5. $$\sin^4 x + \sin^4 \left(\frac{\pi}{2} - x\right) = \sin 2x.$$

6. $$\frac{\sqrt{3}}{2} \sin 3x - \frac{1}{2} \cos 3x = \cos 7x.$$
7. $$\tg x + \frac{\cos x}{1 + \sin x} = 2.$$
8. 转换为产品：
$$\sec^2 \alpha - \tg^2 \alpha + \mathrm{tg} \left(\frac{\pi}{2} - \frac{\alpha}{2}\right) + \mathrm{ctg} \left(\frac{\pi}{4} - \frac{\alpha}{2}\right).$$
9. 给定：$\tg \alpha = \frac{4}{3}$，$\pi < \alpha < \frac{3}{2}$ π。

找到$\tg \frac{\alpha}{2}$。

解方程：
10. $$\sqrt[3]{64} - \sqrt[3]{2^{3x+3}} + 12 = 0.$$
11. $$10^{\lg^3 x} + x^{\lg x} = 20.$$
12. $$\lg^2 10x + \lg x = 19.$$
13. $$4^{\log_3 x} + x^2 = 8.$$
14. $$\log_3 (3^x - 1) \log_3 (3^{x+1} - 3) = 6.$$
解决不等式：
15. $$\frac{0,2^{x-0,5}}{\sqrt{5}} > 5 \cdot 0,04^{x-1}.$$
16. $$0,8^{\frac{3-x}{1-x}} < \frac{16}{25}.$$
17. $$\lg x^2 < \lg^2 x.$$
18. $(x^2 - 4) \log_{0,5} x > 0.$
19. $$\log_{0,5} (2x + 6) > \log_{0,5} (x + 8).$$
20. $$\frac{|2x - 3| - x}{x - 2} > 0.$$
21. 对于$a$的什么值，方程$(5a - 1)x^2 - (5a + 2)x + (3a - 2) = 0$有等根？
22. 简化：
$$4x^4 \left(\frac{x}{a} + \sqrt[5]{a}x^{-0,6}\right) - \frac{1}{2} - 5^{0,4} \sqrt[5]{a}x^{-0,6} + \frac{3x}{a} \sqrt[5]{a^{-0,2}} \sqrt{ax^{-1}}$$
23. 证明在直角三角形中，直角平分线平分中线和高之间的角度，降低到斜边。
24. 在直角三角形的斜边上构造的等边三角形的面积是后者面积的两倍。确定三角形的直角。
