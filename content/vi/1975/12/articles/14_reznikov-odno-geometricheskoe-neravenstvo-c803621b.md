---
id: 1975-12-reznikov-odno-geometricheskoe-neravenstvo-c803621b
issue: kvant_1975_12
year: 1975
number: "12"
title: Một bất đẳng thức hình học
authors:
  - Резников А. Г.
rubric: smes
page_first: 58
page_last: 58
page_labels: "56"
tag: X3XJ
lang: vi
source: kvant_digital
extraction: publisher
content_sha256: 4bbb6e8864d25f483cd3ff84e22526bd0c2f32019f7f5bf81dba579722189983
prompt_sha256: draft-1
translated_from: content/ru/1975/12/articles/14_reznikov-odno-geometricheskoe-neravenstvo-c803621b.md
source_content_sha256: 246b6f90279961923a660e51e1281fe820c0f881ed7aa2f2b379e32b2f846358
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

## Một bất đẳng thức hình học

Trong «Kvant» số 7 của năm nay (trang 65), giả định sau đã được đưa ra:
$$
\dfrac9{20}(ab+bc+ca)\le m_am_b+m_bm_c+m_cm_a,
$$
trong đó $a$, $b$, $c$, $m_a$, $m_b$, $m_c$ là độ dài của các cạnh và theo đó là đường trung tuyến của một tam giác tùy ý.

Dưới đây là một bằng chứng "hình học" của tuyên bố này.

Bổ đề 1. $m_a+m_b+m_c\lt a+b+c$.

Bổ đề 2. $a^2+b^2+c^2\lt2(ab+ac+bc)$.

Bổ đề 3. $m_a^2+m_b^2+m_c^2=\dfrac34(a^2+b^2+c^2)$.

Hãy tự mình chứng minh các bổ đề này.

Bổ đề 4. $m_am_b+m_bm_c+m_am_c\lt\dfrac54(ab+bc+ac)$.

Bằng chứng. Theo Bổ đề 1, $(m_a+m_b+m_c)^2\lt(a+b+c)^2$, tức là
$$
\begin{gather*}
m_a^2+m_b^2+m_c^2+2m_am_b+2m_bm_c+2m_am_c\lt\\
\lt(a^2+b^2+c^2)+2ab+2bc+2ac,
\end{gather*}
$$
từ đó, theo Bổ đề 3 và 2:
$$
2m_am_b+2m_bm_c+2m_am_c\lt\dfrac14(a^2+b^2+c^2)+2(ab+bc+ac)\lt\dfrac52(ab+bc+ac),
$$
Q.E.D.

Bổ đề 5. Nếu chúng ta dựng các đường trung tuyến trong một tam giác có các cạnh $\dfrac13m_a$, $\dfrac13m_b$ và $\dfrac13m_c$ thì độ dài của chúng sẽ bằng $\dfrac14a$, $\dfrac14b$ và $\dfrac14c$.

Bằng chứng. Đặt $G$ là trọng tâm của tam giác, $ABC$, $AM$, $BK$ và $CP$ là các đường trung tuyến, $R$ là trung điểm của đoạn $BG$. Theo cách xây dựng, $|RG|=\dfrac13m_b$, $|PG|=\dfrac13m_c$ và $PR$ là đường giữa trong tam giác $ABG$, từ đó $|PR|=\dfrac12|AG|=\dfrac13m_a$. Vì vậy, tam giác $PRG$ là tam giác mong muốn. Hãy vẽ một trung vị $PQ$ trong đó. Nó là đường trung bình trong tam giác $ABK$ và do đó $|PQ|=\dfrac12|AK|=\dfrac14a$.

Tuyên bố của bổ đề đã được chứng minh.

Bây giờ áp dụng Bổ đề 4 cho tam giác $PRG$, chúng ta thu được bất đẳng thức cần thiết.
