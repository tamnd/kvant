---
id: 1975-12-reznikov-odno-geometricheskoe-neravenstvo-c803621b
issue: kvant_1975_12
year: 1975
number: "12"
title: One geometric inequality
authors:
  - Резников А. Г.
rubric: smes
page_first: 58
page_last: 58
page_labels: "56"
tag: X3XJ
lang: en
source: kvant_digital
extraction: publisher
content_sha256: 5612f3815fdea26c66d29e2c73a6fc0e39d48686f5fb3f6e28d053b6aba0b3aa
prompt_sha256: draft-1
translated_from: content/ru/1975/12/articles/14_reznikov-odno-geometricheskoe-neravenstvo-c803621b.md
source_content_sha256: 246b6f90279961923a660e51e1281fe820c0f881ed7aa2f2b379e32b2f846358
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

## One geometric inequality

In «Kvant» No. 7 for this year (p. 65) the following assumption was made:
$$
\dfrac9{20}(ab+bc+ca)\le m_am_b+m_bm_c+m_cm_a,
$$
where $a$, $b$, $c$, $m_a$, $m_b$, $m_c$ are the lengths of the sides and, accordingly, the medians of an arbitrary triangle.

Below is a “geometric” proof of this statement.

Lemma 1. $m_a+m_b+m_c\lt a+b+c$.

Lemma 2. $a^2+b^2+c^2\lt2(ab+ac+bc)$.

Lemma 3. $m_a^2+m_b^2+m_c^2=\dfrac34(a^2+b^2+c^2)$.

Prove these lemmas yourself.

Lemma 4. $m_am_b+m_bm_c+m_am_c\lt\dfrac54(ab+bc+ac)$.

Proof. According to Lemma 1, $(m_a+m_b+m_c)^2\lt(a+b+c)^2$, i.e.
$$
\begin{gather*}
m_a^2+m_b^2+m_c^2+2m_am_b+2m_bm_c+2m_am_c\lt\\
\lt(a^2+b^2+c^2)+2ab+2bc+2ac,
\end{gather*}
$$
whence, by Lemmas 3 and 2:
$$
2m_am_b+2m_bm_c+2m_am_c\lt\dfrac14(a^2+b^2+c^2)+2(ab+bc+ac)\lt\dfrac52(ab+bc+ac),
$$
Q.E.D.

Lemma 5. If we construct medians in a triangle with sides $\dfrac13m_a$, $\dfrac13m_b$ and $\dfrac13m_c$, then their lengths will be equal to $\dfrac14a$, $\dfrac14b$ and $\dfrac14c$.

Proof. Let $G$ be the center of gravity of the triangle, $ABC$, $AM$, $BK$ and $CP$ the medians, $R$ the midpoint of the segment $BG$. By construction, $|RG|=\dfrac13m_b$, $|PG|=\dfrac13m_c$, and $PR$ is the middle line in the triangle $ABG$, whence $|PR|=\dfrac12|AG|=\dfrac13m_a$. Thus, triangle $PRG$ is the desired one. Let's draw a median $PQ$ in it. It is the midline in the triangle $ABK$ and therefore $|PQ|=\dfrac12|AK|=\dfrac14a$.

The statement of the lemma is proven.

Now applying Lemma 4 to the triangle $PRG$, we obtain the required inequality.
