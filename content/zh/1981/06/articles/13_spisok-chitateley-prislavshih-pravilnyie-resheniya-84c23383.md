---
id: 1981-6-spisok-chitateley-prislavshih-pravilnyie-resheniya-84c23383
issue: kvant_1981_6
year: 1981
number: "6"
title: 发送正确答案的读者名单
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 43
page_last: 44
page_labels: 41-42
tag: 3EOS
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 945e83519600a06654b222074e519b4a74be442ffe061a0814ae559ff0593825
prompt_sha256: draft-1
translated_from: content/ru/1981/06/articles/13_spisok-chitateley-prislavshih-pravilnyie-resheniya-84c23383.md
source_content_sha256: 8fe2df3885768a67d66ff251801adf5a3470796be4e6f594da06f81707f1ea99
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 41⟧

F662。为了利用强大的电压源 $U=5$ V 产生的电动势 $\mathcal{E}=12$ V 对电池进行充电，电路由电感为 $L=1$ Gi 的线圈、二极管 D 和电阻器 K（参见 图）组成，该电路周期性地闭合和打开，时间周期为 $\tau_1=\tau_2=0,01$ s。确定平均电池充电电流。

为了找到平均电池充电电流，您需要确定钥匙的一个关闭-打开周期期间电池上流动的电荷。

当开关闭合时，线圈直接连接到电源，产生的自感电动势等于$U$。这意味着通过线圈的电流按照线性规律变化。考虑到钥匙关闭的瞬间，通过线圈的电流开始按照规律线性消杀

$$I = \frac{U}{L} t.$$

当钥匙打开时，电流将等于

$$I_0 = \frac{U}{L} \tau_1.$$

打开钥匙后，二极管打开，自感电动势$\mathcal{E}_{c,n}$变成电池和电池的方向差-$\mathcal{E}_{c,n}=U-\mathcal{E}$-并且改变符号。这意味着通过线圈的电流开始按照定律线性消杀

$$I = I_0 - \frac{\mathcal{E}-U}{L} t.$$

电流减小的速率（开关打开）大于电流增加的速率（开关闭合）。这意味着即使在时间$\tau_2$到期之前，在时间$\tau_3$之后（从开关打开的那一刻起）电流也会降至零，此时二极管将闭合。从条件中可以找到电池充电的时间$\tau_3$

$$\frac{\mathcal{E}-U}{L} \tau_3 = I_0 = \frac{U}{L} \tau_1,$$

在哪里

$$\tau_3 = \frac{U}{\mathcal{E}-U} \tau_1.$$

在此期间流经电池的电荷等于

$$\Delta q = I_{cp} \tau_3 = \frac{1}{2} I_0 \frac{U}{\mathcal{E}-U} \tau_1 = \frac{1}{2} \frac{U^2 \tau_1^2}{L(\mathcal{E}-U)}.$$

电池平均充电电流为

$$I_{cp} = \frac{\Delta q}{\tau_1 + \tau_2} = \frac{U^2 \tau_1^2}{2L(\mathcal{E}-U)(\tau_1 + \tau_2)} \approx 8,9 \text{ мА.}$$

A·齐伯曼

发送正确答案的读者名单

本期我们公布了M626—M630、M641—M645、F633—F662添加正确答案的人的名字【姓氏后的粗体数字为已解答题数的最后一位】。

数学

大多数提交解决方案的读者都成功完成了问题M630、M641。剩下的问题都解决了：

E. 阿卜杜拉耶夫 (Masally) 26, 28； V.阿列克谢耶夫（莫斯科）26、29； M. Alekseev (莫斯科) 26, 45; A.阿拉金（新库兹涅茨克）27； M.阿拉斯卡诺夫（扎波罗热）28； Y. Bazaliy (顿涅茨克) 26, 29; A. 巴尔（基辅）28、29、43、45； S.巴塔洛夫（阿尔扎马斯）42、45； E.贝洛瓦（Vidnoe）26；于。贝尔塞尔科夫斯基（明斯克）26、27、29、42、45； M. Berushivili（卡舒里）26；于。别斯波洛夫（肖斯特卡）26、28、29； I.布卢斯（第聂伯罗彼得罗夫斯克）26； A. Boldyrkhin（莫吉廖夫-波多尔斯基）26； A. 布鲁德尼 (雅罗斯拉夫尔) 26-29, 42; A.沃尔诺夫（基辅）26； A.加夫里洛夫（别尔哥罗德-德涅斯特洛夫斯基）28； M.盖辛斯基（塔什干）42、43、45； M.加波诺娃（高尔基）26； V. Geshkbein（莫斯科）26、42、44； Z.古纳什维利（第比利斯）26； S.戈尔什科夫（莫斯科）42； E.戈尔什科娃（彼尔姆）26、42、44； A. Grigoryan（列宁格勒）26、27； V. Grina（格罗德诺地区Dyatlovo村）26；

⟦folio 42⟧

S.古佐夫（利沃夫）26、27； A.古廷（克林齐）26、27、42； V. 杰尼索夫 (Kashira) 26, 42; S. Deepak (塔什干) 26; O. Dranko（基辅）42； A. Drobishchev（列宁格勒）42； O. 埃罗什金 (第聂伯罗彼得罗夫斯克) 27, 29, 42; I.朱可夫（列宁格勒）27、29、43、45； A. Zee（明斯克）28、45； A.佐洛提赫（库尔斯克）26、27、42； I. Zyabrev (Krolevets) 26, 28; Z. 伊布拉齐莫夫 (Masally) 26, 28; A. Kadaramanov（别洛列茨）42、44； D. Kamutavitsus（维尔诺斯）42； N. Katsan（明斯克州亚基莫夫卡村）26； V. Kim (Bektemir) 26, 27, 42； S. Kim (Bektemir) 26, 42, 45； A. Kiselev（塔什干）45； V.基塞尔（敖德萨）45； V. Kozlovsky（格罗德诺地区 N. Dvor 村）26； I.科尔帕科夫（索契）28； A. Konyshin（顿河畔罗斯托夫）26、27、42； I. Korneeva（莫斯科）45； A.科尔尼洛夫（顿河畔罗斯托夫）42； D.科罗特金（列宁格勒）27, 42-45； A.科罗特金（高尔基）45； O. 克里扎诺夫斯基 (哈尔科夫) 42, 43; A.克鲁谢尔尼茨基（喀山）26； S.拉米霍夫（塔什干）26-29、42； V.莱文（莫斯科）26； L. Leytsin（切尔尼戈夫）26、42、45； V. 利哈切夫 (利沃夫) 27, 28; O.马洛夫（喀山）45； S.马梅多夫（巴库）26、29、42； V.曼加泽夫（克麦罗沃）26； S. Matyuov（沃洛格达）26-29； L. Merkyavitsus (Lentvaris) 26-29, 42； A.米尔曼（奥德斯卡）26、28； E. Mirzoyan（埃里温）26、29、42； S.莫里诺（莫斯科）28、29；于。纳扎连科（基辅）26—29、42、45；于。尼古拉耶夫斯基（哈尔科夫）27、29、42； A. 尼科洛夫 (基洛沃格勒) 26, 27, 42; P.奥夫钦尼科夫（维亚兹尼基）26、27、42； M. Okroin（埃里温）42； K.佩利赫（巴甫洛夫斯基镇）26-28； N. Pendiorin (奔萨) 26, 27; G.佩雷尔曼（列宁格勒）26、28、42； E.波波夫（别洛雷茨）26、27； S.波波夫（雅库特苏维埃社会主义自治共和国埃尔盖村）26；于。普罗科罗夫 (奥列霍沃-祖埃沃) 26, 28; L.普里亚德科45； V. Romanok（伏尔纳地区 Kunishche 村）26-28； A. Rudensky（顿涅茨克）42、45； N.Saitsina（萨拉托夫）26、28； E.萨利莫夫（基洛瓦巴德）26； M. Sverdlilikov（新西伯利亚）45； V. Svetlchiky (扎波罗热) 26; V.西多林（Retov）26； A. Syksa（基辅）26； I. Skrypnik（伊万诺沃-弗兰科夫斯克）26； A. Slinkin (莫斯科) 42； A. 斯米尔诺夫（库尔干）26、27、45； A.Sokhet（哈尔科夫）45； A.斯皮瓦克（Sterlitamak）27-29、42、43； S.斯皮瓦克（普里皮亚季）28、29、43、45； E. Stenayan（巴库）26、28、42；于。塔尔登科（苏梅）26、45； V. Titenko（明斯克州布卢扎村）26、27、29、42、45； R. Uerinovsky (赫米尔尼克) 26, 28; N.费丁（鄂木斯克）26； Y.费尔德曼（基辅）42； D.福明（列宁格勒）42； O.福纳列夫（Sumgan）26-28； A. Kharitonsky（基辅）43； A. 希尔科夫 (新莫斯科斯克) 26, 28; A. Khokhlov (莫斯科) 26, 42; V. Tsekanovsky（顿涅茨克）26； I.齐莫赫（基洛沃格勒）26、28、42； V. Tsolov（Panagirshe，NRB）42； O. Chalkh (维捷布斯克) 26, 28, 42; V. Shabunin（沃罗涅日地区霍霍尔斯基村）26、45； S.沙拉波夫（塔什干）26； V. Shah（伏尔纳地区 Zamshany 村）26、27、45； Z。 希布祖霍夫（纳尔奇克）26； V. Shirkov（莫斯科）42；于。什科尔尼科夫（基辅）28； L. Elkun（塔什干）26、28； L. Epremidze（第比利斯）42, 43。

物理

几乎所有提交解决方案的读者都遇到了问题F634、F647——
