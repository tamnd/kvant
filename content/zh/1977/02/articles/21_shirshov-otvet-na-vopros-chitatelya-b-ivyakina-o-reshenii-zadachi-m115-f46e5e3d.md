---
id: 1977-2-shirshov-otvet-na-vopros-chitatelya-b-ivyakina-o-reshenii-zadachi-m115-f46e5e3d
issue: kvant_1977_2
year: 1977
number: "2"
title: !!binary |
  44CQ5Zue562U6K+76ICFQi4gSXZ5YWtpbuWFs+S6juino+azleeahOmXrumimO+/vbmg6a
  KYIE0xMTXjgJE=
authors:
  - Ширшов А. И.
rubric: raznoe
page_first: 60
page_last: 60
page_labels: "58"
tag: 22Z5
lang: zh
source: kvant_digital
extraction: vision
content_sha256: e66cb4d23d6db8bb5ceab73fea5c43837522cebe52a5b4df178e6e8ca811b381
prompt_sha256: draft-1
translated_from: content/ru/1977/02/articles/21_shirshov-otvet-na-vopros-chitatelya-b-ivyakina-o-reshenii-zadachi-m115-f46e5e3d.md
source_content_sha256: ed0b18678873a9e957f2286d048787523af853184209b360da401e667e5454d3
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 58⟧

提问 - 我们回答

编辑收到了十年级学生 B. Ivachin 的来信。他在文中写道：

“翻阅旧题«Kvant»，我注意到M115题解法末尾有一个注释”……这个题最早出现在现代著名代数学家A. I. Shirshov的一部著作中。他需要它来构建基于服务器的数学理论。 Integrano 找出她是如何解决这个问题的吗？这个计算是使用数学，还是由元素的意志做出决定？毕竟，如果是初等的话，我的周期可以通过服务器端数学研究的意志写下来。”

我们询问了苏联科学院通讯院士 A.I.希尔绍夫来回答这些问题。

亲爱的博利亚！

您不必通过旧的 «Kvant» 数字来发现有趣的数学想法。他们就在我们周围。

您对问题 M115 感兴趣。让我提醒您一下它的条件：

核磁共振成像显示，容器中充满了整数升的水。任何容器都被切割以倒出与其他容器中已容纳的水一样多的水。为了证明几个格言溢出，可以释放其中一个容器。 （容器足够大：可以容纳所有的水）。

有一次我找到了下面概述的解决方案。

令 $(n, p, q)$ 为容器的某种初始状态，$\gamma$ 为最自然数，使得数字 $n+p$、$n+q$、$p+q$ 中至少有一个可被$2^\gamma$整除。显然$\gamma > 0$。令$n+p=2^\gamma (2s+1)$，$n=2^\alpha (2t+1)$，$p=2^\beta (2r+1)$。我们假设$\alpha=\beta$。然后$\alpha<\gamma$。如果$n>p$，那么我们就输血$(n, p, q) \Leftrightarrow (n-p, 2p, q)$；如果$n<p$，则输血$(n, p, q) \Leftrightarrow (2n, p-n, q)$。从$n-p=2^{\alpha+1}(t-r)$和$2p=2^{\alpha+1}(2r+1)$开始，在某些步骤中，当两个数字变得不同时，或者相应的数字变得相等时。因此，我们可以假设$\alpha>\beta=\gamma$。如果$n<p$，那么我们将进行多次输血$(n, p, q) \Rightarrow (2n, p-n, q) \Rightarrow \dots$，直到$n_i$大于$p_i$（β不会改变，但$\alpha$会增加）。所以，$n>p$，$\alpha>\beta=\gamma$。如果$p<q$、$(n, p, q) \Leftrightarrow (n, 2p, q-p)$和$n+2p=2^{\gamma+1}m$，即γ数增加。如果$p>q$、$(n, p, q) \Leftrightarrow (n-p+q, 2(p-q), 2q)$和$2(p-q)+2q=2p$。 $\gamma$持续增加。由于 $\gamma$ 不能无限增加，因此在某个步骤将获得一个空容器。

很容易理解，如果我决定的话，我也会是一样的。所有容器都可以被清空，也许除了两个之外。

当然，在我的著作（数学集 45：2，1958）中，没有谈论容器。
