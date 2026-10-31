---
id: 1975-12-reznikov-odno-geometricheskoe-neravenstvo-c803621b
issue: kvant_1975_12
year: 1975
number: "12"
title: 一种几何不等式
authors:
  - Резников А. Г.
rubric: smes
page_first: 58
page_last: 58
page_labels: "56"
tag: X3XJ
lang: zh
source: kvant_digital
extraction: publisher
content_sha256: 6b01384b61d40dc1eb6ea51d90a668a1cb571b5f1a721b9c43582e19456cc520
prompt_sha256: draft-1
translated_from: content/ru/1975/12/articles/14_reznikov-odno-geometricheskoe-neravenstvo-c803621b.md
source_content_sha256: 246b6f90279961923a660e51e1281fe820c0f881ed7aa2f2b379e32b2f846358
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

## 一种几何不等式

今年的«Kvant» No. 7（第65页）做出了以下假设：
$$
\dfrac9{20}(ab+bc+ca)\le m_am_b+m_bm_c+m_cm_a,
$$
其中 $a$、$b$、$c$、$m_a$、$m_b$、$m_c$ 是边长，因此也是任意三角形的中线。

以下是该陈述的“几何”证明。

引理 1. $m_a+m_b+m_c\lt a+b+c$。

引理 2. $a^2+b^2+c^2\lt2(ab+ac+bc)$。

引理 3. $m_a^2+m_b^2+m_c^2=\dfrac34(a^2+b^2+c^2)$。

自己证明这些引理。

引理 4. $m_am_b+m_bm_c+m_am_c\lt\dfrac54(ab+bc+ac)$。

证明。根据引理 1，$(m_a+m_b+m_c)^2\lt(a+b+c)^2$，即
$$
\begin{gather*}
m_a^2+m_b^2+m_c^2+2m_am_b+2m_bm_c+2m_am_c\lt\\
\lt(a^2+b^2+c^2)+2ab+2bc+2ac,
\end{gather*}
$$
由此，根据引理 3 和 2：
$$
2m_am_b+2m_bm_c+2m_am_c\lt\dfrac14(a^2+b^2+c^2)+2(ab+bc+ac)\lt\dfrac52(ab+bc+ac),
$$
Q.E.D.

引理 5. 如果我们在边长为 $\dfrac13m_a$、$\dfrac13m_b$ 和 $\dfrac13m_c$ 的三角形中构造中线，那么它们的长度将等于 $\dfrac14a$、$\dfrac14b$ 和 $\dfrac14c$。

证明。令$G$为三角形的重心，$ABC$、$AM$、$BK$和$CP$为中线，$R$为线段$BG$的中点。根据构造，$|RG|=\dfrac13m_b$、$|PG|=\dfrac13m_c$和$PR$是三角形$ABG$的中线，$|PR|=\dfrac12|AG|=\dfrac13m_a$由此而来。因此，三角形 $PRG$ 就是所需的三角形。我们在其中画一个中位数$PQ$。它是三角形 $ABK$ 的中线，因此是 $|PQ|=\dfrac12|AK|=\dfrac14a$。

引理的陈述已被证明。

现在将引理 4 应用于三角形 $PRG$，我们得到所需的不等式。
