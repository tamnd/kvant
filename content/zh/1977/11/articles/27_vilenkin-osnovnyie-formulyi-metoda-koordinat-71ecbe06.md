---
id: 1977-11-vilenkin-osnovnyie-formulyi-metoda-koordinat-71ecbe06
issue: kvant_1977_11
year: 1977
number: "11"
title: 坐标法的基本公式
authors:
  - Виленкин А. Н.
rubric: raznoe
page_first: 90
page_last: 91
page_labels: 88-89
tag: 8JWV
lang: zh
source: kvant_digital
extraction: vision
content_sha256: bc3682d9e81bd85814499cd74c60c388752134a4f1fb40cdd10087caa5eb0ab1
prompt_sha256: draft-1
translated_from: content/ru/1977/11/articles/27_vilenkin-osnovnyie-formulyi-metoda-koordinat-71ecbe06.md
source_content_sha256: a172f440d18531ae743647734e7379a2129c8b9f09a1817eada7d5fe0cca6db5
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 88⟧

（很容易看出$h > 0$）。因为一定有$|\overrightarrow{O_1Q}| = r$，所以我们得到等式
$$(a \mathrm{tg} \varphi - r - r \mathrm{tg} \varphi) \cos \varphi = r,$$
从中找到$r$：
$$r = \frac{a \sin \varphi}{1 + \sin \varphi + \cos \varphi}.$$
在差异处
1. 证明任意三角形$ABC$的面积可以用公式计算
$$S_{ABC} = \frac{1}{2} \sqrt{|AB|^2 \cdot |AC|^2 - (\overrightarrow{AB} \cdot \overrightarrow{AC})^2}.$$
2. 长方体的两个相邻侧面的不相交的对角线相对于底面倾斜角度$\alpha$和$\beta$。找出这些对角线之间的角度。
3. 正四边形帕拉米德$SABCD$的底边是$a$，高是$h$。求线 $BD$ 和 $SA$ 之间的距离。
4. 四面体的边等于 $l$。求四面体各面交叉高度之间的距离。
5. 直立平行六面体的底面是一个锐角$\alpha$的菱形。将这个平行六面体切割成正方形的平面与底面的倾斜角度是多少？
6. （密歇根州立大学，机制，1970）。三角形paramid$SABC$每条边的长度都等于1，点$D$是三角形$ABC$的高度$BD$的底。等边三角形$BDE$位于与边$AC$成$\varphi$角的平面上，且点$S$和$E$位于平面$ABC$的同一侧。求点 $S$ 和 $E$ 之间的距离。
7. （密歇根州立大学，物理学，1976）。给定一个立方体$ABCDA_1B_1C_1D_1$，边为$a$。点$E$是边$A_1D_1$的中间，点$F$是边$AA_1$的中间。求小于通过点 $E$ 和 $F$ 并接触由平面 $BB_1C_1C$ 和 $DD_1C_1C$ 形成的二面角的面的球体的半径。

应用

坐标法的基本公式

向量坐标$\vec{a}$
$$\vec{a} = x\vec{i} + y\vec{j} + z\vec{k} = (x; y; z)$$
$$x = \vec{a} \cdot \vec{i}, y = \vec{a} \cdot \vec{j}, z = \vec{a} \cdot \vec{k}$$

点$M$的坐标
如果$\overrightarrow{OM} = (x; y; z)$则$M (x; y; z)$

向量$\overrightarrow{AB}$的坐标与其起点$A (x_1; y_1; z_1)$和终点$B (x_2; y_2; z_2)$的坐标之间的关系

并行传输公式$\vec{p} = (a; b; c)$、$M (x; y; z)$
$$\vec{p} (M) = M_1 (a + x; b + y; c + z)$$

向量 $\vec{a} = (x_1; y_1; z_1)$ 和 $\vec{b} = (x_2; y_2; z_2)$ 的和与差
$$\vec{a} + \vec{b} = (x_1 + x_2; y_1 + y_2; z_1 + z_2)$$
$$\vec{a} - \vec{b} = (x_1 - x_2; y_1 - y_2; z_1 - z_2)$$

向量 $\vec{a} = (x; y; z)$ 和数字 $p$ 的乘积
$$\vec{p a} = (px; py; pz)$$

非叶向量 $\vec{a} = (x_1; y_1; z_1)$ 和 $\vec{b} = (x_2; y_2; z_2)$ 的标量积
$$\vec{a} \cdot \vec{b} = |\vec{a}| \cdot |\vec{b}| \cdot \cos (\vec{a}, \vec{b})$$
$$\vec{a} \cdot \vec{b} = x_1x_2 + y_1y_2 + z_1z_2$$

⟦folio 89⟧

向量长度$\vec{a} = (x; y; z)$
$$|\vec{a}| = \sqrt{x^2 + y^2 + z^2}$$

点 $A(x_1; y_1; z_1)$ 和 $B(x_2; y_2; z_2)$ 之间的距离
$$|AB| = \sqrt{(x_2 - x_1)^2 + (y_2 - y_1)^2 + (z_2 - z_1)^2}$$

向量 $\vec{a} = (x_1; y_1; z_1)$ 和 $\vec{b} = (x_2; y_2; z_2)$ 之间的角度
$$\cos(\vec{a}, \vec{b}) = \frac{\vec{a} \cdot \vec{b}}{|\vec{a}| \cdot |\vec{b}|} = \frac{x_1x_2 + y_1y_2 + z_1z_2}{\sqrt{x_1^2 + y_1^2 + z_1^2} \sqrt{x_2^2 + y_2^2 + z_2^2}}$$

具有中心 $O(0; 0; 0)$ 和系数 $k$、$M(x; y; z)$ 的齐次公式
$$H_O^k(M) = M_1(kx; ky, kz)$$

平面方程
$$ax + by + cz + d = 0$$

开头包含点 $O(0; 0; 0)$ 于
$$ax + by + cz + d > 0 \quad d > 0$$
$$ax + by + cz + d < 0 \quad d < 0$$

关闭
$$ax + by + cz + d \geq 0 \quad d \geq 0$$
$$ax + by + cz + d \leq 0 \quad d \leq 0$$

垂直于平面 $\alpha: ax + by + cz + d = 0$ 的向量
$$\vec{n}_\alpha = (a; b; c)$$

包含点 $A(x_1; y_1; z_1)$ 并垂直于向量 $\vec{n} = (a; b; c)$ 的平面方程
$$a(x - x_1) + b(y - y_1) + c(z - z_1) = 0$$

平面之间的角度 $\alpha: a_1x + b_1y + c_1z + d_1 = 0$, $\beta: a_2x + b_2y + c_2z + d_2 = 0$
$$\vec{n}_\alpha = (a_1; b_1; c_1), \vec{n}_\beta = (a_2; b_2; c_2)$$

位于平面 $\alpha$ 内面积为 $S$ 的多边形在平面 $\beta$ 上的正交投影的面积 $S_{\pi p}$
$$S_{\pi p} = S \cdot \cos(\alpha, \beta)$$

半径为 $R$、中心为点 $S(a; b; c)$ 的球体方程
$$(x - a)^2 + (y - b)^2 + (z - c)^2 = R^2$$

与球体 $(x - a)^2 + (y - b)^2 + (z - c)^2 = R^2$ 在点 $A(m; p; q)$ 相切的平面方程
$$(m - a)(x - a) + (p - b)(y - b) + (q - c)(z - c) = R^2$$
$$(a - m)(x - m) + (b - p)(y - p) + (c - q)(z - q) = 0.$$
