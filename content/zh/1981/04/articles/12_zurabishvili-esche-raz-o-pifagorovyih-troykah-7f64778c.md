---
id: 1981-4-zurabishvili-esche-raz-o-pifagorovyih-troykah-7f64778c
issue: kvant_1981_4
year: 1981
number: "4"
title: 再次关于毕达哥拉斯三元组
authors:
  - Зурабишвили З.
rubric: smes
page_first: 41
page_last: 41
page_labels: "39"
tag: A164
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 2b799563e09a8d65e4105a851e573dfed3c38d18d5f3db87c758923ccc3e129d
prompt_sha256: draft-1
translated_from: content/ru/1981/04/articles/12_zurabishvili-esche-raz-o-pifagorovyih-troykah-7f64778c.md
source_content_sha256: b997b152d0e046a140475f53096e8f54ca0ae2d075b5b8c14a3cf0df90f06277
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 39⟧

再次关于毕达哥拉斯三元组

自然数的三元组 (3, 4, 5) 是 Pyfadorian 的：$3^2 + 4^2 = 5^2$。如何找到所有毕达哥拉斯三元组？这已经在«Kvant»（1979，第 4 期，第 40 页）中写过。这是解决这个问题的另一种方法。

显然，如果 $(a, b, c)$ 是勾股三元组，则任何三元组 $(ak, bk, ck)$（其中 $k$ N）都是毕达哥拉斯三元组。如果任意两个数$a, b, c$有一个公素因数$p$，那么第三个数也能被$p$整除。因此，列出具有成对同时质数 $a, b, c$ 的勾股三元组就足够了。

因此，令 $(a, b, c)$ 为勾股三元组，并令数字 $a, b, c$ 成对简化。

数字$a$和$b$不能同时为偶数。它们不能同时为奇数，因为否则它们的平方和可被 2 整除，但不能被偶数整除，因此不能是自然数的平方。所以，$a$和$b$之一必须是偶数，第二个奇数；而且，$c$是奇数。我们假设$a$是奇数，$b$是偶数。

让我们从边长$c$画一个正方形。在它的左上角，我们从长度为$a$的一边放置一个正方形，在右下角 - 从长度为$b$的一边放置一个正方形（参见图）。该正方形与红色正方形相交，并且在大正方形中，两个同步的矩形将保持未覆盖状态。根据条件$a^2 + b^2 = c^2$，正方形的面积等于同步矩形的面积之和。

同步矩形的边长为$c - a$和$c - b$，红色正方形的边长为$a + b - c$。由于$c - a$和$a + b - c$是偶数，因此每个同步矩形都可以分为两个相同的矩形，而红色正方形可以分为四个边长为整数的相同正方形。让我们用$k$和$l$（$k = c - b, 2l = c - a$）表示受保护矩形的边长，用$s$（$2s = a + b - c$）表示受保护正方形的边长。根据它们的面积相等，得出$kl = s^2$。

根据数$a, b$和$c$成对互质，可以得出数$k$和$l$互质。确实，数字$k$和$l$有一个共同的质因数$p$。因为$b^2 = c^2 - a^2 = (c - a)(c + a) = 2l(c + a)$被$p$放大了。但是$c = b + k$。这意味着$c$也能被$p$整除，这与$b$和$c$互质相矛盾。

让我们回到等式$kl = s^2$。由于 $k$ 和 $l$ 是互质的，并且它们的乘积是完全平方数，因此这些数字中的每一个本身都必须是平方数。让$k = m^2, l = n^2$。然后$s = m \cdot n$。

现在让我们用$m$和$n$来表达$a, b$和$c$：

$$a = k + 2s = m^2 + 2mn = (m + n)^2 - n^2,$$
$$b = 2l + 2s = 2n^2 + 2mn = 2n(m + n),$$
$$c = k + 2l + 2s = m^2 + 2n^2 + 2mn = (m + n)^2 + n^2.$$

输入$m + n = t$，我们得到$a = t^2 - n^2, b = 2nt, c = t^2 + n^2$。

很容易检查，对于任何 $t$ 和 $n$，如果 $t > n$，这些公式给出毕达哥拉斯三元组。如果$t$和$n$是不同奇偶校验的互质数，那么数字$a, b, c$将是两两互质。

3. 祖拉比维利
