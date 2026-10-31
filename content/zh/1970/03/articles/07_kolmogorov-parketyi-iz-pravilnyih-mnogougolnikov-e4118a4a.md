---
id: 1970-3-kolmogorov-parketyi-iz-pravilnyih-mnogougolnikov-e4118a4a
issue: kvant_1970_3
year: 1970
number: "3"
title: 由正多边形制成的镶木地板
authors:
  - Колмогоров А. Н.
rubric: osnovnye-stati
page_first: 27
page_last: 28
page_labels: 25-26
tag: WWZ6
lang: zh
source: kvant_digital
extraction: vision
content_sha256: eb418a181c4c62b31835d0f2bb576a1a57866046225c5adfa26474e241702af1
prompt_sha256: draft-1
translated_from: content/ru/1970/03/articles/07_kolmogorov-parketyi-iz-pravilnyih-mnogougolnikov-e4118a4a.md
source_content_sha256: 94cb08ee0ea26b99fcff68196ee0c07e637357fbe1e0840763e22ec63bc8a9a8
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 25⟧

例如，在 图 2, 6 处，将构成六边形、正方形和三角形拼花的整个顶点和边网格围绕其中一个六边形的中心旋转 60°，我们得到相同的顶点和边网格。该镶木地板每个六边形的中心是“六阶对称中心”*）。

问题 1. 找到 图 2 所示镶木地板的所有 4 阶、3 阶和 2 阶对称中心，a。

什么是正确的实木复合地板
从对称的角度来看，我们对实木复合地板的定义并不算太遥远。它允许不具有任何对称性的镶木地板。采用常见的六边形拼花地板 (图 1, c)，您可以通过将一些六边形细分为六个三角形来“破坏”它。很容易理解，结果将再次是我们定义意义上的“镶木地板”。但可以证明（尝试一下！），例如，通过细分三个六边形（如 图 3 所示），并保留所有其余部分不分割，我们会得到完全不对称的镶木地板。为了安装丑陋且不够对称的镶木地板，我们使用以下定义：

如果镶木地板可以以其任何给定顶点可以叠加在其任何其他给定顶点上的方式叠加在自身上，则称为规则镶木地板。

任务 2. 证明图 1 和图 2 中显示的镶木地板是正确的，并自己构建尽可能多的正确镶木地板。

*) 如果某个图形绕 O 旋转 $\frac{360^\circ}{n}$ 时，它与自身重叠，则称 O 点为该图形的 n 阶对称中心。

⟦folio 26⟧

主要目标

事实证明，所有种类的正确镶木地板都可以被描述。如果给定镶木地板多边形的边长$h$，则存在有限数量的不同（不重叠）的常规镶木地板。我不想告诉你具体是多少。

将它们全部列出并回答有关其数量的问题是您必须解决的主要任务。

一些指导方针

解决自然问题从使用镶木地板开始。规则的 $n$ 边形有 $n$ 外角 (图 4)，其总和等于四个直角（您自己看看）。因此，正 $n$ 边形的每个角等于

$$\alpha_n = 2d - \frac{4d}{n} = 2\left(1 - \frac{2}{n}\right)d.$$

角度总和等于 4d 的多边形必须会聚在镶木地板的顶点处。所以，

$$\alpha_3 = \frac{2}{3}d, \alpha_4 = d, \alpha_6 = \frac{4}{3}d, \alpha_8 = \frac{3}{2}d$$

对于 图 1 和 2 中所示的镶木地板，我们有：

$$4\alpha_4 = 4d,$$

$$6\alpha_3 = 4d,$$

$$3\alpha_6 = 4d,$$

$$\alpha_4 + 2\alpha_8 = 4d,$$

$$\alpha_3 + 2\alpha_4 + \alpha_6 = 4d.$$

在一般情况下，用$m_n$表示对$n$边形顶点的应用次数，我们应该得到

$$\sum m_i\alpha_i = 4d,$$

(1)

在总和中，我们包括那些数字 $i$ 的项，其中 $m_i > 0$ 和 $\alpha_i = 2\left(1 - \frac{2}{i}\right)d$。

我们的第一个任务是找到方程（1）的所有解，其中整数$m_i > 0$。式（1）减少2d，可以方便地写成以下形式

$$\sum m_i\left(1 - \frac{2}{i}\right) = 2.$$

对于方程（2）的每个解，必须使用相应的
