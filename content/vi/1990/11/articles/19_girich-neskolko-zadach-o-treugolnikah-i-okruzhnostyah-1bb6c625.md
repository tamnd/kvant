---
id: 1990-11-girich-neskolko-zadach-o-treugolnikah-i-okruzhnostyah-1bb6c625
issue: kvant_1990_11
year: 1990
number: "11"
title: Một số bài toán về hình tam giác và hình tròn
authors:
  - Гирич А.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 48
page_last: 50
page_labels: 46-48
lang: vi
source: kvant_digital
extraction: vision
content_sha256: ac03070e823d1a1b3965dd86c713653dcc0a2694cf9a6b0e1cee9782ffefb4b7
prompt_sha256: draft-1
translated_from: content/ru/1990/11/articles/19_girich-neskolko-zadach-o-treugolnikah-i-okruzhnostyah-1bb6c625.md
source_content_sha256: 509fc0644c2cc0ba3f045a7205984706d65bf443ee9820e8db0e22a46f00eb73
translation_model: draft
translation_run: vi-draft-gaps-2026-11-05
translation_quality: draft
---

⟦folio 46⟧

---
running_head:
folio:
---

Một số bài toán về hình tam giác và hình tròn

A. GIRICH

Trong phần ghi chú này chúng ta sẽ nói về đường tròn tiếp xúc với hai cạnh của một tam giác và đường tròn ngoại tiếp tam giác này. Chúng tôi sẽ gọi những vòng tròn như vậy là viết một nửa. Chúng ta sẽ khám phá một số tính chất thú vị của vòng tròn nửa viết.

Như thường lệ, chúng ta biểu thị các cạnh dài của tam giác $ABC$, đối diện với các đỉnh $A, B$ và $C$, bằng $a, b$ và $c$, tương ứng các góc ở các đỉnh này là $\alpha, \beta$ và $\gamma$, bán kính của đường tròn nội tiếp và ngoại tiếp là $r$ và $R$, diện tích hình tam giác - $S$, nửa chu vi của nó - $p$.

Trước khi bắt đầu nghiên cứu các vòng tròn nửa viết, chúng ta hãy giải phụ trợ bài toán sau.

Bài toán 1. Biểu thị bán kính $R$ của đường tròn ngoại tiếp theo bán kính $r$ của đường tròn ngoại tiếp và các góc $\alpha, \beta, \gamma$.

Lời giải. Có hai công thức tính diện tích tam giác đã biết

$$S = \frac{abc}{4R} = rp. \tag{1}$$

Theo định lý sin $a = 2R \sin \alpha, b = 2R \sin \beta, c = 2R \sin \gamma$. Thay các biểu thức này vào (1), ta được

$$2R^2 \sin \alpha \sin \beta \sin \gamma = Rr(\sin \alpha + \sin \beta + \sin \gamma),$$

nhưng $\alpha + \beta + \gamma = \pi$ và $\sin \gamma = \sin(\alpha + \beta)$. Pozotomu

$$\sin \alpha + \sin \beta + \sin \gamma = 4 \cos \frac{\alpha}{2} \cos \frac{\beta}{2} \cos \frac{\gamma}{2}.$$

Vì vậy, $2R \sin \alpha \sin \beta \sin \gamma = 4r \cos \frac{\alpha}{2} \times \cos \frac{\beta}{2} \cos \frac{\gamma}{2}$, từ đâu chúng ta dễ dàng có được

$$r = 4R \sin \frac{\alpha}{2} \sin \frac{\beta}{2} \sin \frac{\gamma}{2}.$$

Bài toán 2. Chứng minh rằng bán kính của nửa đường tròn tiếp xúc với các cạnh $AB$ và $AC$ của tam giác $ABC$ là $r/\cos^2 \frac{\alpha}{2}$.

Bằng chứng. Gọi $r_1$ là bán kính, $I_1$ tâm của nửa hình tròn, $O$ tâm đường tròn ngoại tiếp tam giác $ABC$ (hình 1). Sau đó $OI_1 = R - r_1$, $AI_1 = r_1/\sin \frac{\alpha}{2}$, $OA = R$, $\cos \angle OAI_1 = \cos \frac{(\beta - \gamma)}{2}$ (hãy đảm bảo điều này).

Áp dụng định lý cosin cho tam giác $OAI_1$, ta thu được sau khi biến đổi

$$r_1 \cos^2 \frac{\alpha}{2} = 2R(\cos \frac{\beta - \gamma}{2} - \sin \frac{\alpha}{2}) \sin \frac{\alpha}{2}. \tag{2}$$

⟦folio 47⟧

---
running_head:
folio:
---

$$\cos \left( \frac{\beta - \gamma}{2} \right) - \sin \frac{\alpha}{2} = \cos \frac{\beta - \gamma}{2} - \cos \frac{\beta + \gamma}{2} = 2 \sin \frac{\beta}{2} \sin \frac{\gamma}{2},$$
vế phải của đẳng thức (2) bằng $4R \sin \frac{\alpha}{2} \sin \frac{\beta}{2} \sin \frac{\gamma}{2} = r$.

Vì vậy, $r_1 = r / \cos^2 \frac{\alpha}{2}$.

Bài toán 3. Chứng minh rằng trung điểm $I$ của đoạn thẳng $B_1C_1$, trong đó $B_1$ và $C_1$ là điểm tiếp tuyến của nửa đường tròn có cạnh $AB$ và $AC$ (xem hình 1), là tâm đường tròn nội tiếp tam giác $ABC$.

Bằng chứng. Rõ ràng, tam giác $AB_1C_1$ là tam giác đều và tam giác $AIC_1$ là hình chữ nhật. Pozotomu
$$AI = AC_1 \cos \frac{\alpha}{2} = r_1 \text{ ctg} \frac{\alpha}{2} \cos \frac{\alpha}{2} = r / \sin \frac{\alpha}{2}.$$
Nhưng điều này có nghĩa là điểm $I$ là tâm của đường tròn nội tiếp.

Bài toán 4. Đường thẳng $B_1C_1$ chạm vào đường tròn ngoại tiếp tam giác $BIC$.

Bằng chứng. Gọi $W$ là giao điểm của phân giác của góc $A$ với đường tròn ngoại tiếp tam giác $ABC$ (hình 2.) Khi đó $CW = WB$, $\angle CBW = \alpha/2$ nên $\angle IBW = (\alpha + \beta)/2$. Ngoài ra, $\angle WIB = (\alpha + \beta)/2$ (là góc ngoài của tam giác $AIB$). Do đó, tam giác $WIB$ là tam giác đều. Do đó, $CW = WI = WB$, tức là $W$, là tâm của đường tròn ngoại tiếp tam giác $CIB$. Tuyên bố bài toán được rút ra từ tính vuông góc đã được chứng minh trước đó của $AI$ và $B_1C_1$.

Bây giờ chúng ta vẽ các tiếp tuyến của nửa đường tròn đi qua các đỉnh $B$ và $C$. Đặt $K$ là điểm giao nhau của chúng, và $M$ và $N$ là các điểm tiếp tuyến tương ứng (hình 3).

Bài toán 5. Chứng minh rằng đường thẳng $B_1M, C_1N, BC$ và $AK$ cắt nhau tại một điểm.

Bằng chứng. Đặt $T$ là giao điểm của các đoạn $B_1M$ và $BC$ (xem hình 3). Từ các tam giác $B_1TC$ và $BMT$ ta thu được (theo định lý sin)
$$\frac{CT}{\sin \angle CB_1T} = \frac{CB_1}{\sin \angle B_1TC},$$
$$\frac{BT}{\sin \angle BMT} = \frac{BM}{\sin \angle BTM},$$
nhưng $\angle B_1TC = \angle BTM$ và $\angle BMT + \angle CB_1T = \pi$ ($\angle CB_1M = \angle B_1MK$, vì $AC$ và $KB$ tiếp xúc với cùng một đường tròn). Pozotomu
$$\frac{CT}{BT} = \frac{CB_1}{BM} = \frac{CB_1}{C_1B}.$$

⟦folio 48⟧

---
running_head:
folio:
---

$\angle BC_1V_1 + \angle CB_1V_1 = 180^\circ$. Vì vậy, $\frac{BV_1}{CV_1} = \frac{BC_1}{CB_1}$. Tương tự, chúng ta thu được (giả sử rằng $V_2$ là giao điểm của $MN$ với $BC$): $\frac{BV_2}{CV_2} = \frac{BM}{CN}$, nhưng $BM = BC_1$, $CN = CB_1$. Vì vậy, $\frac{BV_1}{CV_1} = \frac{BV_2}{CV_2}$, do đó $V_1 = V_2$.

Bài toán 7. Chứng minh rằng các đường thẳng $BB_1$, $CC_1$ và $AK$ cắt nhau tại một điểm (xem hình 3).

Bằng chứng. Vì $B_1A = AC_1$, và, như đã được thiết lập trước đó, $\frac{BT}{CT} = \frac{BC_1}{CB_1}$, chúng ta thu được

$$\frac{BT}{CT} \cdot \frac{CB_1}{B_1A} \cdot \frac{AC_1}{C_1B} = 1.$$

Vẫn còn sử dụng định lý Ceva (về định lý Ceva, xem bài viết của B. Erdriev và N. Matsaev trong «Kvant» số 3 năm 1990).

Để kết luận, chúng tôi đề xuất một chuỗi bài toán cho một lời giải độc lập.

Bài tập

1. Bây giờ gọi $A_1, A_2, B_2, C_2$ là điểm tiếp tuyến của hai nửa đường tròn khác (khác với khoảng cách) trên cạnh của tam giác. Chứng minh rằng giao điểm của các đường thẳng $B_1C_1$ và $BC, B_2A_2$ và $AB, A_1C_2$ và $AC$ cùng nằm trên một đường thẳng.

2. Gọi $K_1, K_2, K_3$ là giao điểm của các tiếp tuyến vẽ từng hình bán nguyệt đi qua các đỉnh của tam giác. Chứng minh rằng đường thẳng $AK_1, BK_2$ và $CK_3$ cắt nhau tại một điểm.

3. Gọi $D$ là giao điểm của đường $BB_2$ và $CC_2$. Chứng minh rằng $D$ thuộc đường trung bình của tam giác $ABC$ vẽ qua đỉnh $A$.

4. Gọi $P_1, P_2, P_3$ là điểm tiếp tuyến của hình bán nguyệt với đường tròn ngoại tiếp. Chứng minh rằng đường thẳng $AP_1, BP_2$ và $CP_3$ cắt nhau tại một điểm.
