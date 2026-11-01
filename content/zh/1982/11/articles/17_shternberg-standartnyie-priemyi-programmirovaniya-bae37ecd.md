---
id: 1982-11-shternberg-standartnyie-priemyi-programmirovaniya-bae37ecd
issue: kvant_1982_11
year: 1982
number: "11"
title: 标准编程技术
authors:
  - Штернберг Л. Ф.
rubric: raznoe
rubric_sub: Разное
page_first: 64
page_last: 66
page_labels: 62, 64
tag: B1OF
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 99691f6a3cb04a12eef1ead4f09d1e2041cee591120ed587a2690570867c063a
prompt_sha256: draft-1
translated_from: content/ru/1982/11/articles/17_shternberg-standartnyie-priemyi-programmirovaniya-bae37ecd.md
source_content_sha256: b71b60a5fe3f3f12f5a315692abc813abd608d8dd15bc9e94e4aa8b6d49f50ad
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 62⟧

编程的艺术

标准编程技术
第 2 课. 线性搜索

搜索问题是最常见的问题之一：它们在构建翻译器时以及在您遇到的许多大大小小的程序中出现。如果搜索是在文件中，或者正在搜索的数组是无序的（即元素的值无法判断它位于何处），则唯一可能的搜索类型是线性搜索，其中编程信息从头到尾逐个元素地执行。另外，数组是有序的，但长度较小；使用比线性搜索更复杂的东西是没有意义的。因此，所有三项准备任务*)

*) 请参阅第 1 课，«Kvant» 第 10 条。

解决方案
在所有解决方案中：x 是给定值，k 是所需的索引

a)
问题1（第一个适合的问题）
i:=1; k:=0;
while (i<=n) AND (k=0) do
begin
if a[i]=x then k:=i;
i:=i+1
end;

b)
for k:=1 to n do
if a[k]=x then goto 7;
k:=0;
7:...

问题2（最后一个合适）

k:=0;
for i:=1 to n do
if a[i]=x then k:=i;

问题 3（第 个月适用）
k:=0; i:=1; j:=0;
while (i<=n) AND (k=0) do
begin j:=j+1;
if j=m then k:=i
end;
i:=i+1
end;

j:=0;
for k:=1 to n do
if a[k]=x then
begin j:=j+1;
if j=m then goto 7;
end;
k:=0;
7:...

62

⟦folio 64⟧

图 1.

图 2.

图 3.

首先，他们沿着穿过其中心的相互垂直的平面进行切割——结果是 8 块；然后他们进行了第四次斜切，将除“后”那一块之外的所有这些碎片分成两部分 - 结果是 15 块，但其中一块（即中央那块 - 前“八”的果肉最可折叠的部分）没有外壳。这个 arbr 还剩下 14 个外壳。其他切割选项也是可能的。

主编-I.K. Kikoin院士
第一副主编——柯尔莫哥洛夫院士
副主编：M. N. Danilcheva、V. A. Leshkovtsev、Yu。 P·索洛维约夫

编辑集：L. G. Aslamazov、M. I. Bashmakov、V. E. Belonuchkin、V. G. Boltyansky、A. A. Borovoy、Yu。 M.布鲁克、V.V.瓦维洛夫、N.B.瓦西里耶夫、S.M.沃罗宁、V.V.格内登科、V.L.古滕赫默、N.P.多尔比林、V.N.杜布罗夫斯基、A.N.泽姆利亚科夫、A.R.齐尔伯曼、S.M.科泽尔、S.S.克罗托夫、L.D.库德里亚夫采夫、A.A.米奈洛夫，E.M.尼基申，S.P.诺维科夫，M.K.波塔波夫，V.G.拉祖莫夫斯基，N.A.罗迪纳，N.H.罗佐夫，A.P.萨文，Ya。 A. 斯莫罗金斯基、A. B. 索辛斯基、V. M. 乌罗耶夫、V. A. 法布里坎特

编辑委员会：A. M. Baldin、S. T. Belyaev、B. B. Bukhovtsev、E. P. Velikikhov、I. Ya。 Verchenko，B. V. Vozdvijzhensky，G. V. Dorofeev，N. A. Ermolaeva，A. P. Ershov，Yu。 B. 伊万诺夫、L. V. Kantorovich、P. L. Kapitsa、V. A. Kirillin、G. L. Kotkin、R. N. Kuzmin、A. A. Logunov、V. V. Mozhaev、V. A. Orlov、N. A. Patrikeeva、A. V. Peryshkin、R. Z. Sagdeev、S. L. Sobolev、A. L. Stasenko、I. K.苏林，E.L.苏尔科夫，L.D.法德耶夫，V.V.菲尔索夫，G.N.雅科夫列夫。

已发出号码：
B.加尔金、L.丹尼森科、M.杜巴赫、
N.库兹明、E.纳扎罗夫、A.佩尔明、E.坦丘里纳

编辑部主任 L. Chernova
艺术编辑 T. Makarova
校对员 M. Medvedskaya

103006，莫斯科，K-6，圣。高尔基，32/1，
«Kvant»，电话。 251-82-42

交付至 2082 年 9 月 17 日。 1982 年 11 月 3 日签署出版。
胶印
纸 70×108 1/16。物理。烤箱4
有条件的烤箱l。 5.60 学术版。湖7.15T-20908
价格40戈比。订单 2378 发行量 175,067 份。

红色劳动勋章
契诃夫印刷厂
VO“Soizpolgrafprom”
苏联国家委员会
出版及印刷事务
和图书贸易
契诃夫，莫斯科地区
