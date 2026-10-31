---
id: 1970-6-goldberg-vstupitelnyie-ekzamenyi-po-matematike-v-moskovskom-institute-stali-i-splavov-1969-goda-d344e2d2
issue: kvant_1970_6
year: 1970
number: "6"
title: 1969年莫斯科钢铁合金学院数学入学考试
authors:
  - Гольдберг В. В.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 31
page_last: 36
page_labels: 29-34
tag: 5IUN
lang: zh
source: kvant_digital
extraction: vision
content_sha256: ae7acc679ebd1913e8ee4b1fd6f802d106f1f7087789e023e7b0bb8713285541
prompt_sha256: draft-1
translated_from: content/ru/1970/06/articles/09_goldberg-vstupitelnyie-ekzamenyi-po-matematike-v-moskovskom-institute-stali-i-splavov-1969-goda-d344e2d2.md
source_content_sha256: 70114eca239335160495fdaa8d5b514c42acc28c4127eca69a15e831f862e3b0
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 29⟧

莫斯科钢铁合金学院的数学入学考试是大多数技术学校的典型考试。

MCHMIS（黑色金属和合金冶金）和 MCRMIS（有色金属和合金冶金）学院的学科包括数学、物理和化学；在物理学院（物理和化学）和 PMP（半导体材料和器件）学院 - 数学和物理的书面和口语。各院系的比赛分别举行。

请注意，大约 19%（179 人）的新学生是在工业中心招收的：贝卡巴德、伏尔加格勒、扎波罗热、诺里尔斯克、奥尔斯克、切列波维茨。

笔试和口试门票的内容与大学申请者的数学课程严格对应。

让我们看看 MCHMIS 和 MCRMIS 学院提供的选项之一。

选项 1。

1. 解方程
$$\sec^2 \frac{x}{2} + \cos^2 \frac{x}{2} = 16 \text{ ctg } x.$$

2. 解决不平等问题
$$\frac{3x^2 - 2x - 1}{\lg(x - 1)} < 0.$$

3. 简化
$$\left[ 4(a + 1) + \left( \frac{\sqrt{ab^2} + \sqrt{a}}{\sqrt{3}a + \sqrt{3}b} + \frac{\sqrt{6}a}{3} \right)^3 \right]^{1/2}$$

4. 设$E$为梯形$ABCD$($BC \parallel AD$)边$AB$的中点。证明三角形$ECD$的面积等于梯形$ABCD$的一半。

5. 边为 $a$ 的立方体内接于正四边形 Paramid 中，使其四个顶点位于侧边上，另外四个顶点位于 Paramid 的底面上。帕拉酰胺的侧面与底座平面成角度$\alpha$倾斜。确定帕拉酰胺的体积。

解决方案

1. 让我们定义 ODZ 方程：
$$x \neq \pi l \quad (l = 0, \pm 1, \dots).$$

让我们开始解方程。我们有
$$\frac{1}{\cos^2 \frac{x}{2}} + \frac{1}{\sin^2 \frac{x}{2}} = 16 \frac{\cos x}{\sin x},$$
在哪里
$$\frac{1}{\cos^2 \frac{x}{2}} \sin^2 \frac{x}{2} = 16 \frac{\cos x}{\sin x}$$
或者
$$\frac{4}{\sin^2 x} = 16 \frac{\cos x}{\sin x}.$$

从 $\sin x \neq 0$ 开始，我们得到
$$4 \sin x \cos x = 1$$
或者
$$\sin 2x = \frac{1}{2},$$
在哪里
$$2x = (-1)^n \frac{\pi}{6} + \pi n,$$

⟦folio 30⟧

或者

$$x = (-1)^n \frac{\pi}{12} + \frac{\pi n}{2}$$
$$(n = 0, \pm 1, \dots).$$

所得解包含在 ODZ 方程中。

答案：$x = (-1)^n \frac{\pi}{12} + \frac{\pi n}{2}$
$$(n = 0, \pm 1, \dots).$$

2. 解决不平等问题
$$\frac{3x^2 - 2x - 1}{\lg(x - 1)} < 0$$

请注意，如果分子和分母的符号不同，则分数将为负数。因此，这个不等式相当于两个不等式系统：

$$\begin{cases} 3x^2 - 2x - 1 > 0, \\ \lg(x - 1) < 0 \end{cases}$$

或者
$$\begin{cases} 3x^2 - 2x - 1 < 0, \\ \lg(x - 1) > 0. \end{cases}$$

求解这些系统，我们找到相应的

$$\begin{cases} x < -\frac{1}{3}, x > 1, \\ 0 < x - 1 < 1, \\ x - 1 > 1, \end{cases}$$

那是
$$\begin{cases} x < -\frac{1}{3}, x > 1, \\ 1 < x < 2, \\ x > 2. \end{cases}$$

第二个系统无解，第一个系统的解是倒数$1 < x < 2$。

答案：$1 < x < 2$。

3. 首先，我们找到有效值$a$和$b$：
$$a \geq 0, b \geq 0, a \neq -b.$$

我们进一步注意到
$$\sqrt[6]{ab^2} + \sqrt{a} = \sqrt[6]{a} \left( \sqrt[3]{a} + \sqrt[3]{b} \right).$$

考虑到$a + b \neq 0$，并将分数减少$\sqrt[3]{a} + \sqrt[3]{b}$，我们得到

$$\left[ 4(a + 1) + \left( \frac{\sqrt[6]{ab^2} + \sqrt{a}}{\sqrt[3]{a} + \sqrt[3]{b}} + \sqrt[6]{a} \right)^3 \right]^{1/2} =$$
$$= \left[ 4(a + 1) + \left( 2\sqrt[6]{a} \right)^3 \right]^{1/2} =$$
$$= 2\left[ \left( \sqrt{a} + 1 \right)^2 \right]^{1/2} = 2\left( \sqrt{a} + 1 \right).$$

4. 给定 (图 1)：$ABCD$ - 梯形，$AE = EB$。

证明：
$$S_{ECD} = \frac{1}{2} S_{ABCD}.$$

证明。我们来画梯形的中线$EF$。

然后$S_{ABCD} = EF \cdot H$，其中$H$是梯形的高度。另一边，

$$S_{ECD} = S_{ECF} + S_{EFD} = \frac{1}{2} EF \cdot \frac{H}{2} +$$
$$+ \frac{1}{2} EF \cdot \frac{H}{2} = \frac{1}{2} EF \cdot H.$$

⟦folio 31⟧

---
running_head:
folio:
---

图 3.

所以
$$S_{ECD} = \frac{1}{2} S_{ABCD}.$$

5. 首先，请注意立方体下底面的顶点位于 paramid 底面（侧边的投影）的对角线上，并且 $\angle ETO = \alpha$ (图 2)。

让我们用 $x$ 表示 paramid 的底边。从$\triangle EOT$有$EO$paramid：

$$EO = OT \cdot tg\alpha = \frac{x}{2} tg\alpha.$$ 接下来，根据三角形$EO_1K_1$和$EOC$的相似性，我们有$EO_1:EO = O_1K_1:OC$或

$$\frac{x}{2} tg\alpha - a}{\frac{x}{2} tg\alpha} = \frac{a \sqrt{2}}{2},$$

在哪里

$$x = \frac{2a(1 + tg\alpha)}{tg\alpha}.$$

paramid$EABCD$的体积等于

$$V = \frac{1}{3} x^2 \frac{x}{2} tg\alpha = \frac{1}{6} x^3 tg\alpha =$$

$$= \frac{4}{3} a^3 \frac{(1 + tg\alpha)^3}{tg^2\alpha} =$$

$$= \frac{8 \sqrt{2} a^3 \cos^3(\alpha - \frac{\pi}{4})}{3 \sin^2\alpha \cos\alpha} =$$

$$= \frac{16 \sqrt{2} a^3 \cos^3(\alpha - \frac{\pi}{4})}{3 \sin 2\alpha \sin\alpha}.$$

回答：

$$V = \frac{16 \sqrt{2} a^3 \cos^3(\alpha - \frac{\pi}{4})}{3 \sin 2\alpha \sin\alpha}.$$

现在让我们来看看 PH 和 PMP 学院笔试中提供的选项之一。

选项2

1. 四边形帕拉米德内接于半径为 $R$ 的球内，球的侧边与底面成角度 $\alpha$ 倾斜。如果在其底部有一个对角线之间的角度为 $\beta$ 的矩形，请确定 Paramid 的体积。

2. 解方程

$$\sqrt{2} \sin 10x + \sin 2x = \cos 2x.$$

3. 解决不平等问题

$$\log_{3x+4} x^2 < 1.$$

4. 简化表达式

$$(a + x^{1/2})^{-1/2} + (a - x^{1/2})^{-1/2},$$

其中 $x = 4(a-1)$ 和 $1 < a < 2$。

解决方案

1. paramid 的底面平面与球相交于靠近底面 $ABCD$ 外接的圆 (图 3) 中。 paramid 的高度将穿过球的中心 $O$ 和该圆的中心 $O_1$，因为所有边缘都以相等的角度向底座倾斜。通过底边 $AC$ 的对角线和顶点 $E$ 的平面将沿着围绕 Paramid $AEC$ 对角线部分外接的大圆与球相交。从 $\triangle AEC$ 出发，其中 $\angle AEC =$

⟦folio 32⟧

= 180° - 2α，根据正弦定理，发现
AC = 2R sin (180° - 2α) = 2R sin 2α。因为
AO₁ = $\frac{1}{2}$ AC = R sin 2α.

由△AEO₁我们确定直线度高度：
EO₁ = H = AO₁ · tg α = R sin 2α · tg α.

直线底面积等于
S_{ABCD} = 2 (S_{AO₁B} + S_{BO₁C}) =
= 2 [$\frac{1}{2}$ AO₁² sin β +
+ $\frac{1}{2}$ AO₁² sin (180° - β)] =
= 2R² sin² 2α sin β.

直线 V 的体积等于
V = $\frac{1}{3}$ 2R² sin² 2α sin β · R sin 2α · tg α =
= $\frac{2}{3}$ R³ sin³ 2α tg α sin β.

回答：
V = $\frac{2}{3}$ R³ sin³ 2α tg α sin β.

2. 注意到
cos 2x - sin 2x =
= sin ($\frac{\pi}{2}$ - 2x) - sin 2x =
= $\sqrt{2}$ sin ($\frac{\pi}{4}$ - 2x),

我们将方程重写为以下形式
$\sqrt{2} \sin 10x = \sqrt{2} \sin (\frac{\pi}{4} - 2x)$

或者
sin 10x + sin (2x - $\frac{\pi}{4}$) = 0,

在哪里
sin (6x - $\frac{\pi}{8}$) cos (4x + $\frac{\pi}{8}$) = 0.

将每个分量都等于零，我们得到
x₁ = $\frac{\pi}{48}$ (8n + 1) (n = 0, ±1, ...),
x₂ = $\frac{\pi}{32}$ (8k + 1) (k = 0, ±1, ...).

3. 让我们考虑两种情况：3x + 4 > 1 和 0 < 3x + 4 < 1。

在第一种情况下我们得到
$$\begin{cases} 3x + 4 > 1, \\ x^2 < 3x + 4, \\ x^2 > 0 \end{cases}$$ 或 $$\begin{cases} x > -1, \\ -1 < x < 4, \\ x \neq 0, \end{cases}$$

位置从哪里来？
-1 < x < 0, 0 < x < 4.

在第二种情况下我们有
$$\begin{cases} 0 < 3x + 4 < 1, \\ x^2 > 3x + 4, \\ x^2 > 0 \end{cases}$$

或者
$$\begin{cases} -\frac{4}{3} < x < -1, \\ x < -1, x > 4, \\ x \neq 0, \end{cases}$$

我们从哪里得到它？
- $\frac{4}{3} < x < -1$.

回答：
- $\frac{4}{3} < x < -1$;
- -1 < x < 0; 0 < x < 4.

求解该问题时，没有考虑 x ≠ 0 的情况，因此，加上最后两个积分，我们得到 -1 < x < 4。

4. 我们有
$$(a + x^{1/2})^{-1/2} = \frac{1}{\sqrt{a + \sqrt{x}}} =$$
$$= \frac{1}{\sqrt{a + 2\sqrt{a - 1}}} =$$
$$= \frac{1}{\sqrt{(a - 1) + 2\sqrt{a - 1} + 1}} =$$
$$(a - x^{1/2})^{-1/2} = \frac{1}{\sqrt{a - \sqrt{x}}} =$$
$$= \frac{1}{\sqrt{a - 2\sqrt{a - 1}}} =$$
$$= \frac{1}{\sqrt{(a - 1) + 2\sqrt{a - 1} + 1}} =$$
$$= \frac{1}{\sqrt{(a - 1) - 1} + 1} =$$

⟦folio 33⟧

$$\frac{1}{\sqrt{a-1}-1} = \frac{1}{1-\sqrt{a-1}},$$

从$1 < a < 2$开始，即$\sqrt{a-1} < 1$。

最后我们得到

$$\left(a + x^{1/2}\right)^{-1/2} + \left(a - x^{1/2}\right)^{-1/2} = \frac{1}{1+\sqrt{a-1}} + \frac{1}{1-\sqrt{a-1}} = \frac{2}{2-a}.$$

在解决这个问题时，他们忘记了很多条件$1 < a < 2$，因此在提取根时犯了错误。

笔试显示，建造者中的最高名次如下：

1) 在简化代数表达式时仍然会犯很多错误：申请人对度的了解很差，并且在需要使用某个论证根时会犯错误（参见上面讨论的选项2中的问题4）。

2) 许多申请人不熟悉三角函数公式，导致在解决三角函数问题时出现错误，或者选择远离最短路径来解决此类问题。

3) 在求解不等式时，由于不等式性质和函数性质的微不足道而犯了错误。例如，申请人常常没有考虑不等式中包含的函数的 VA（参见选项 1 中的任务 2，选项 2 中的任务 3）。

4) 在解决立体测量问题时，障碍往往是缺乏立体测量基本概念的含义。例如，人们经常错误地找到相邻侧边参数之间的弧角的直线角。许多人错误地认为这种情况下的线性角度是基础多边形参数的顶点处的角度。

现在尝试自己解决其他入学考试选项中的一些问题。

MCHMIS 和 MCRMIS 院系提出的问题。

1. 转换为工作

$$\sin 5\alpha \cdot \sin 4\alpha + \sin 4\alpha \cdot \sin 3\alpha - \sin 2\alpha \cdot \sin \alpha.$$

2. 如果 $\sin \alpha + \cos \alpha = 1,4$ 则求 $tg \frac{\alpha}{2}$； $0 < \alpha < 45^\circ$。

3. 证明同样的手势

$$\frac{1}{1 + tg \alpha tg 2\alpha} = \sin \left(\frac{\pi}{2} + 2\alpha\right).$$

4. 如果$\cos x = \frac{2}{3}$，则计算$18 \sin \frac{3}{2} x \sin \frac{x}{2}$。

5. 证明平等

$$\cos 10^\circ \sin 20^\circ - 2 \sin 70^\circ = 1.$$

6. 解决不平等问题

$$3^{x+1} + 18 \cdot 3^{-x} < 29.$$

7. 解方程

$$\log_2 \left(4^{x-2} + 1\right) - x + 4 = \log_2 17.$$

8. 解决不平等问题

$$\log_3 \frac{5x-3}{2-x} > 0.$$

9. 解决不平等问题

$$\log_x \frac{15}{1-2x} < -2.$$

10. 求解方程组

$$\begin{cases} \frac{x}{2} + \frac{3}{y} = 7,5, \\ \frac{7}{x} + \frac{y}{6} = 1,5. \end{cases}$$

11. 求解方程组

$$\begin{cases} \sqrt[3]{\frac{x}{y}} + \sqrt[3]{\frac{y}{x}} = 2,5, \\ x + y = 9. \end{cases}$$

12. 求解方程组

$$\begin{cases} 2 \log_a x + \log_a y = 3, \\ \log_b x - \log_b y = 1. \end{cases}$$

13. 找到 $a$ 方程组的所有实数值

$$\begin{cases} x^2 - y^2 = 1, \\ y = ax \end{cases}$$

有有效的解决方案。

14. 查找 trilen 的 $a$ 的所有值

$$(a^2 - 1)x^2 + 2(a - 1)x + 2$$

对于 $x$ 的所有实际值都将为正。

⟦folio 34⟧

15. 求 $a$ 取什么值时系统的解
$$\begin{cases} x + y = 3, \\ ax + 4y = 6 \end{cases}$$
满足不等式$x > 1, y > 0$。

16. 对于$a$的什么值，方程$3x^2 - x - a = 0$和$4x^2 + 8x + a = 0$都有实根？

17. 数字 $m$ 应该在什么区间变化，以便方程 $x^2 - 2mx + m^2 - 1 = 0$ 的根在 -2 和 4 之间？

18. 证明如果从一个三角形的一个顶点引出的中线和高将这个角分成三等分，则该三角形是矩形。

19. 证明在正五边形中，相交对角线的其中一条线段等于五边形的边长。

20. 三角形$ABC$绕平分线$AD$旋转。证明边 $AB$ 和 $AC$ 所描述的表面面积与通过旋转部分 $ABD$ 和 $ACD$ 获得的体积相关。

21. 证明如果球可以内切于截锥体，则锥体的体积等于其总表面积与 $1/6$ 高度的乘积。

22. 证明圆锥体的体积等于其总表面积与$1/3$内切球半径的乘积。

PH 和 PMP 院系提出的问题。

23. 一个长方体内接于圆柱体，其底边之一的边长等于$b$。平行六面体的对角线与底面平面形成角度$\alpha$，与穿过底面这一侧的侧面形成角度$\beta$。确定圆柱体的侧面。

24. 求一个正四边形帕拉米德的体积，其侧边等于$l$，相邻侧面之间的角度等于$\beta$。

25. 不使用表格进行计算
$$\text{tg} 9^\circ - \text{tg} 27^\circ - \text{tg} 63^\circ + \text{tg} 81^\circ.$$

26. 解方程
$$\sec^2 x = \frac{2 - \cos x - \sin x}{1 - \sin x}.$$

27. 解决不平等问题
$$x^2 + \frac{5}{2} x - \frac{3}{2} < 1.$$

28. 解决不平等问题
$$\frac{|x - 2| - |x + 2|}{x - 1} < 0.$$

29. 解决不平等问题
$$\left(\frac{1}{2}\right)^{\log_3 \log_2 \left(x^2 - \frac{4}{5}\right)} < 1.$$

30. 解决不平等问题
$$\lg \left| \frac{3x - 1}{2x + 1} \right| < 0.$$

31. 解决不平等问题
$$\log_2 x 2 \log_2 x 2 \log_2 (4x) > 1.$$

32. 证明对于 $n^2 < a < 2n^2(n > 0)$
$$\left(\sqrt{a + 2n \sqrt{a - n^2}} + \sqrt{a - 2n \sqrt{a - n^2}}\right):$$
$$\left(\frac{1}{\sqrt{a} + \sqrt{a + 1}} + \frac{1}{\sqrt{a + 1} + \sqrt{a + 2}} + \dots + \frac{1}{\sqrt{a + n - 1} + \sqrt{a + n}}\right) = 10^{\lg 2} + \lg \left(\sqrt{a} + \sqrt{a + n}\right).$$

33. 解方程
$$\sqrt{a^2 + bx} + \sqrt{a^2 - bx} = \sqrt{2abx}$$
在$a > 0, b > 0$。

34. 化简，求解方程
$$\frac{\left(\sqrt{x - 1} + \sqrt{x + 1} + 2\right)(2x - \sqrt{x^2 - 1})}{(x + 1)^{3/2} + (x - 1)(x - 1)^{1/2}} = \sqrt{x^2 - 1} \left(\frac{\log_a x}{\log_ab x} - \log_a b\right).$$

35. 求解方程组
$$\begin{cases} 3 |x| - 5y = 3, \\ 2x + |y| = 11. \end{cases}$$

36. 证明
$$\left[ \frac{1}{2^{1/4} + 2^{1/8} + 1} + \frac{1}{2^{1/4} - 2^{1/8} + 1} - 2 \cdot \frac{2^{1/4} - 1}{2^{1/2} + 2^{1/4} + 1} \right] \cdot \frac{2^{1/2} + 2^{1/4} + 1}{2} = 1 + \lg 4 + \sqrt{4 \lg^2 2 + \lg 5 - \lg 8}.$$

37. 对于参数$t$的取值，方程
$$1 + \sqrt{x + 2 \lg t} = \sqrt{x - 1}$$
有有效的解决方案吗？

V.V.加尔德贝尔
