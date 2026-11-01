---
id: 1981-1-moskovskiy-inzhenerno-fizicheskiy-institut-8fa00794
issue: kvant_1981_1
year: 1981
number: "1"
title: 莫斯科工程物理学院
rubric: ekzamenatsionnye-materialy
page_first: 48
page_last: 50
page_labels: 46, 48
tag: VQ60
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 9b2befcfa65254b309206e22f6931be77a50a357f7d5ce7f204bc7c4cc409bcc
prompt_sha256: draft-1
translated_from: content/ru/1981/01/articles/15_moskovskiy-inzhenerno-fizicheskiy-institut-8fa00794.md
source_content_sha256: e88a7817960f1f21ddeba93e3cf3f5c50a92b1585721163ad3cae445ef7c3870
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 46⟧

莫斯科工程物理学院

数学

笔试

选项1

1. 等差数列的第二项和第十二项的乘积等于 1，同一级数的第四项和第十项的乘积等于 $b$。求这个级数的第七项。

2. 一个正圆锥内接一个正三角形，其侧面的边心长等于$k$，侧面与底面的夹角为$\alpha$。穿过侧向肋之一，存在与终端表面相交的渐进平面。如果已知该面积具有最大可能值，则通过该平面求圆锥体的面积。

3. 当$a$为多少时，由线$y = \frac{1}{x}$、$y = \frac{1}{2x-1}$、$x = 2$、$x = a$围成的图形面积等于$\ln \frac{4}{\sqrt{5}}$？

4. 找到$f'(x)$和函数$f(x) = 4x^3 - 6x^2 \cos 2a + 3x \sin 2a \sin 6a + \sqrt{\ln(2a-a^2)}$的临界点。 $f(x)$在$x = \frac{1}{2}$时是杀死还是增加？

选项2

1. 重7公斤的铁镍合金含铁量为70%；另一种相同金属的合金含有 r% 镍，重 18 公斤。必须将多少公斤第二种合金与第一种合金合金化才能获得铁含量最低的新合金？新合金含有多少铁？

2. 基础 SPQRT 的底边是四边形 PQRT，其具有 $|PT| = |TR|$ 和 $TPR = \alpha$。从顶点 $R$ 到线 $(TP)$ 的垂线长度为 $h$。如果已知三角形 PQR 的面积比三角形 TPR 的面积大 15 倍，且直线 (TS) 和 (QS) 垂直于直线 $(PR)$、$\widehat{TSQ} = 90^\circ$ 和 $|SQ| = c$，求原始 SPQRT 的体积。

3. 对于函数 $f(x) = -1 - \frac{1}{x} \log_8 e$，找到反导数 $F(x)$，它在 $x = 2$ 处取值 $6 \frac{2}{3}$。曲线$F(x)$在$x$的什么值处与$Ox$轴相交？

4. 查找 $m$ 的所有值，其中向量 $\vec{g} = (1; m; x)$ 和 $h = (7; x mx)$ 对于任何 $x \in \mathbb{R}$ 形成锐角。

解决选项1的问题

1. 让我们用$x$表示等差数列$a_7$的第七项，用$d$表示级数之差。我们有
$$\begin{cases} a_2 = x - 5d, & a_{12} = x + 5d, \\ a_4 = x - 3d, & a_{10} = x + 3d. \end{cases}$$

根据条件
$$\begin{cases} a_2 \cdot a_{12} = 1, \\ a_4 \cdot a_{10} = b. \end{cases}$$

因此，根据(1)，
$$\begin{cases} x^2 - 25d^2 = 1, \\ x^2 - 9d^2 = b. \end{cases}$$

从这个系统中我们很容易找到$x^2$和$d^2$：
$$x^2 = \frac{25b - 9}{16}; d^2 = \frac{b - 1}{16}.$$
在这种情况下，非常印度，为了使解存在，必须有$b \geqslant 1$。

回答。 $\left\{\frac{\sqrt{25b - 9}}{4}; -\frac{\sqrt{25b - 9}}{4}\right\}$。

一般来说，申请人正确地解决了这个问题。他们中的一些人在解方程$x^2 = \frac{25b - 9}{16}$时犯了错误。

2. SABC 原始高度 $SO$ (图 1)

图 1.

⟦folio 48⟧

减少到平方
$$5a^2 - 24a + 12 = 0.$$
区间 $\frac{1}{2}; 1$ 上的这个方程有一个根
$$a = \frac{1}{5}(12 - 2\sqrt{21}).$$
回答。 $\{8, 0, 4(6 - \sqrt{21})\}$。
许多申请人犯的一个典型错误是没有研究$a \in \left[ \frac{1}{2}; 1 \right]$案例而失去了第二个解决方案。
4. 首先，请注意参数$a$必须满足不等式$\ln(2a - a^2) \geq 0$。但
$$\ln(2a - a^2) \geq 0 \iff 2a - a^2 \geq 1 \iff a = 1.$$
因此，$a = 1$，
$$f(x) = 4x^3 - 6x^2 \cdot \cos 2 + 3x \cdot \sin 2 \cdot \sin 6,$$
$$f'(x) = 12x^2 - 12x\cos 2 + 3\sin 2\sin 6.$$
求解二次方程$4x^2 - 4x\cos 2 + \sin 2 \cdot \sin 6 = 0$，我们找到临界点
$$x_1 = \cos 1 \cdot \cos 3, x_2 = \sin 1 \cdot \sin 3.$$
为了找出函数$f$是否减少或出现在$x = 0,5$，您需要确定数字$f'(0,5)$的符号。
我们有$f'(0,5) = 3(1 + \sin 2 \cdot \sin 6) - 6\cos 2 > 0$，因为括号中的表达式是正数，还有$\cos 2 < 0$。
回答。
$$f'(x) = 12x^2 - 12x\cos 2 + 3\sin 2 \cdot \sin 6;$$
$\cos 1 \cdot \cos 3, \sin 1 \cdot \sin 3;$
增加。
在解决这个问题时，没有应用的人无法解决，因为函数在一点的减少（增加）的定义毫无意义。

物理

口语考试目标
1. 刚度为 $k = 10$ N/m 的弹簧连接到水平桌子上质量为 $m = 0,5$ kg 的块上。弹簧的另一端固定在块体上方$l_0 = 0,1$米的高度。在此位置，弹簧不变形。当工作台沿水平方向匀速移动时，弹簧发生偏转
48
