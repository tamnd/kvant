---
id: 1977-8-rabinovich-affinnyie-zadachi-i-teoremyi-b94941ab
issue: kvant_1977_8
year: 1977
number: "8"
title: Affine bài toán và các định lý
authors:
  - Рабинович В. Л.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 40
page_last: 43
page_labels: 38, 40, 41
tag: F9MH
lang: vi
source: kvant_digital
extraction: vision
content_sha256: f8c173d42de0ca7bfe23184c00e49d03650caf98eb73797dd57142b003877f91
prompt_sha256: draft-1
translated_from: content/ru/1977/08/articles/10_rabinovich-affinnyie-zadachi-i-teoremyi-b94941ab.md
source_content_sha256: 58b110e96f77b6692cd0b30b19f2867afcd1f82dba6e87d6e87d2bc9bbce16cc
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 38⟧

V. Rabinovich

Affine bài toán và các định lý

Có thể giải bài toán về hình bình hành cho hình vuông không? Chứng minh định lý tam giác cho tam giác đều đã đủ chưa? Hóa ra đôi khi có thể, đôi khi là đủ. Những vấn đề và định lý như vậy sẽ được thảo luận trong bài viết này.

1. Kỹ thuật đồng thời

Cho có hai mặt phẳng $\alpha$ và $\beta$ và một đường thẳng $a$ giao nhau với mỗi mặt phẳng này (Hình 1). Chúng ta xác định ánh xạ $\Pi_a$ của mặt phẳng $\alpha$ lên mặt phẳng $\beta$ như sau: tới một điểm tùy ý $A \in \alpha$ ta gán một điểm $A' \in \beta$, tại đó một đường thẳng đi qua điểm $A$ và song song với đường thẳng $a$ cắt mặt phẳng $\beta$. Sử dụng ký hiệu hàm tổng quát, chúng ta sẽ viết $\Pi_a (A) = A'$. Ánh xạ $\Pi_a$ đương nhiên được gọi là phép chiếu song song. Rõ ràng, nếu $A \neq B$ ($A \in \alpha$ và $B \in \alpha$), thì $\Pi_a (A) \neq \Pi_a (B)$. Do đó, phép chiếu song song là một ánh xạ nghịch đảo (“Đại số 8”, đoạn 20)*. Vì vậy chúng ta có thể nói về một ánh xạ nghịch đảo. Ánh xạ $\Pi_a^{-1}$, nghịch đảo với hình chiếu song song $\Pi_a$, rõ ràng sẽ là hình chiếu song song của mặt phẳng $\beta$ lên mặt phẳng $\alpha$: $\Pi_a^{-1} (A') = A$.

Phép chiếu song song $\Pi_a$ biến đổi bất kỳ hình $\Gamma$ nào trên mặt phẳng $\alpha$ thành một số hình $\Pi_a (\Gamma)$ trên mặt phẳng $\beta$ (Hình 1) - ảnh của hàm $\Gamma$ dưới ánh xạ $\Pi_a$.

1. Chứng minh ảnh của một đường thẳng dưới hình chiếu song song là một đường thẳng, hơn nữa, nếu điểm $A$ nằm giữa $B$ và $C$ thì $\Pi_a (A)$ nằm giữa $\Pi_a (B)$ và $\Pi_a (C)$.

Từ đây suy ra rõ ràng ảnh của một đoạn là một đoạn, ảnh của một đa giác là một đa giác (có cùng số cạnh).

Bạn razzhenne 2. Chứng minh rằng phép chiếu song song bảo toàn tính song song: nếu $l \parallel m$ thì $\Pi_a (l) \parallel \Pi_a (m)$.

Điều này có nghĩa là hình ảnh của sự song song là sự song song. 3. Chứng minh tỉ số độ dài của các đoạn thẳng song song là bất biến của phép chiếu song song: nếu các đoạn thẳng $AB$, $CD$ nằm trên một đường thẳng (hoặc trên các đường thẳng song song) trong mặt phẳng $\alpha$ thì $\frac{|AB|}{|CD|} = \frac{|A'B'|}{|C'D'|}$ (ở đây $A' = \Pi_a (A)$, v.v.).

Do đó, nếu $AK$ là đường trung bình của tam giác $ABC$ ($\triangle ABC \subset \alpha$), thì $A'K'$ là đường trung bình của tam giác $A'B'C'$.

U razzhenne 4. Chứng minh tỉ số diện tích của các hình là bất biến của phép chiếu song song: nếu $\Gamma \subset \alpha$ và $\Delta \subset \alpha$ thì $\frac{S(\Gamma)}{S(\Delta)} = \frac{S(\Pi_a (\Gamma))}{S(\Pi_a (\Delta))}$. Chỉ định. Dựa trên bằng chứng, nó được cho phép

*) Thiết kế song song, được thảo luận trong bài viết này, là ánh xạ của một mặt phẳng (đến một mặt phẳng). Phép chiếu song song từ §12 của “Hình học 9” là ánh xạ không gian (lên một mặt phẳng). Nó không phải là điều ngược lại.

⟦folio 40⟧

Từ bài tập 2, 10, định lý này là định lý quan hệ. Theo Bài tập 7, trong số các ảnh affine của hình thang $ABCD$ đã cho có một hình thang cân. Thực hiện phép chiếu P song song tương ứng, chúng ta chuyển từ hình thang $ABCD$ sang hình thang cân $A'B'C'D'$. Các đường chéo $AC$ và $BD$ của hình thang $ABCD$ sẽ chuyển thành các đường chéo $A'C'$ và $B'D'$ của hình thang $A'B'C'D'$, các điểm $O, K, P, Q$ thành các điểm tương ứng, $O' = [A'C'] \cap [B'D']$, $K' = (A'B') \cap (C'D')$, $P' = (K'O') \cap [B'C']$ và $Q' = (K'O') \cap [A'D']$ (Hình 3).

Trong hình thang đều $A'B'C'D'$, như đã biết, $|A'C'| = |B'D'|$ và $B' \hat{A}'D' = C' \hat{D}'A'$ (bài toán 2 đến đoạn 50 của “Hình học 7”). Từ đây dễ dàng suy ra $|A'K'| = |D'K'|$ và $A' \hat{K}'Q' = D' \hat{K}'Q'$. Do đó, trong tam giác đều $A'K'D'$ đoạn $K'Q'$ là đường phân giác và do đó là đường trung tuyến: $|A'Q'| = |Q'D'|$. Tương tự, người ta chứng minh rằng $|B'P'| = |P'C'|$.

Bây giờ chúng ta thực hiện phép chiếu song song ngược $\Pi^{-1}$. Với $\Pi^{-1}$, “mọi thứ” sẽ “quay lại”: $A'$ - đến $A, B'$ - đến $B$, v.v. Từ Bài tập 10, nó tuân theo $|BP| = |PC|$ và $|AQ| = |QD|$.

Trên thực tế, nếu chúng ta đã kiểm tra trước rằng định lý mà chúng ta đang chứng minh là định lý quan hệ và chúng ta chứng minh nó theo cách này (bằng cách chuyển sang ảnh quan hệ), thì không cần phải thực hiện kỹ thuật đảo ngược: tính đúng đắn của kết luận của định lý đang được chứng minh chỉ đơn giản là từ tính chính xác của nó.

Bằng cách này người ta có thể chứng minh - về nguyên tắc - bất kỳ định lý ái lực nào.

Về bài tập 14. Chứng minh các định lý ở bài tập 12, 13 theo cách này.

4. Nhìn từ trên cao

Trên thực tế, định nghĩa tự nhiên hơn về hình ảnh cảm xúc sẽ như sau: hình phẳng $\Delta$ được gọi là hình ảnh liên kết của hình phẳng $\Gamma$ nếu nó có thể thu được từ $\Gamma$ bằng cách kết hợp một số hữu hạn các hình chiếu song song. Tương tự, tính chất của một hình phẳng đương nhiên được gọi là afficine nếu nó được bảo toàn dưới sự hợp thành của một số hữu hạn các hình chiếu song song.

Do đó, định nghĩa của khái niệm hình ảnh tình cảm (ngược lại với hình ảnh được định nghĩa ở đoạn 2) có tính bắc cầu: nếu $\Delta$ là ảnh liên kết của hình (phẳng) $\Gamma$ và $\Sigma$ là ảnh liên kết của hình $\Delta$, thì $\Sigma$ là ảnh liên kết của hình $\Gamma$. Vì khái niệm này cũng đối xứng (nếu $\Delta$ là ảnh liên kết của hình $\Gamma$, thì $\Gamma$ là ảnh liên kết của hình $\Delta$) và phản chiếu (bất kỳ hình phẳng $\Gamma$ nào cũng là ảnh liên kết của chính nó), nên chúng ta có thể (= hợp lý) đưa ra định nghĩa sau: hai hình phẳng $\Gamma$, $\Delta$ được gọi là afficino tương đương nếu một trong số chúng là ảnh gốc của cái kia.

Thay vì các định lý từ bài tập 5-7, giờ đây chúng ta có thể hình thành các định lý đã được nghiên cứu kỹ hơn: mọi tam giác afficino đều tương đương, mọi hình bình hành afficino đều tương đương, mọi hình thang afficino đều tương đương.

Trong hình học phổ thông, các số thực sự được coi là đồng đẳng, nghĩa là các số đồng dạng được xác định và coi là tương đương. Vì vậy, hình học này có thể coi là môn khoa học về các tính chất

⟦folio 41⟧

những số liệu không thay đổi khi có sự thay đổi.

Hình học trên mặt phẳng, dựa trên sự hợp thành của một số hữu hạn các hình chiếu song song *) (các thành phần như vậy được gọi là các phép biến đổi affine của mặt phẳng), tức là hình học trong đó vẽ các hình tương đương affine được gọi là hình học affine. Hình học affine là môn khoa học về các tính chất của một hình không thay đổi dưới các phép biến đổi affine. Bài viết này đã giới thiệu cho bạn một số khái niệm về hình học này.

Bài tập
1. Qua điểm $P$ nằm trong tam giác $ABC$ vẽ các đường thẳng $l, m, n$, song song, tương ứng với [$AB$, $BC$, $CA$]. Đặt $l \cap [BC] = A_1$, $m \cap [AC] = B_1$, $n \cap [AB] = C_1$. Chứng minh rằng $\frac{|PA_1|}{|AB|} + \frac{|PB_1|}{|BC|} + \frac{|PC_1|}{|CA|} = 1$.

2. Chứng minh định lý Menalay: nếu đường thẳng $l$ cắt cạnh $AB$ của tam giác $ABC$ tại điểm $R$, cạnh $BC$ tại điểm $P$ và tiếp tục của cạnh $AC$ tại điểm $Q$ thì $\frac{|PB| \cdot |QC| \cdot |RA|}{|PC| \cdot |QA| \cdot |RB|} = 1$.

3. Trong tam giác $ABC$, thông qua các điểm $L \in [AC]$ và $K \in [AC]$, cũng như $|AL| = |CK|$, các đường thẳng tương ứng $l \parallel AB$ và $k \parallel BC$ được vẽ. Hãy để $k \cap l = O$. Chứng minh rằng đường thẳng $BO$ đi qua chính giữa đoạn $AC$.

4. Trên các cạnh $AB, BC, CD, DA$ của gam song song $ABCD$ lấy các điểm tương ứng $P, Q, R$ và $S$. Tìm mặt phẳng của tứ giác $A_1B_1C_1D_1$ được tạo bởi giao điểm của các đường thẳng $AR, BS, CP$ và $DQ$, nếu mặt phẳng của hình song song ban đầu $ABCD$ là $t$, $|AS| = |CQ|$, $|BP| = |DR|$ và $\frac{|AS|}{|AD|} = \frac{|DR|}{|CD|}$.

5. Song song với gam $ABCD$, các điểm $A_1, B_1, C_1, D_1$ lần lượt nằm trên $[AB], [BC], [CD]$ và $[DA]$. Trên các cạnh $A_1B_1, B_1C_1, C_1D_1$ và $D_1A_1$ của tứ giác $A_1B_1C_1D_1$ lấy các điểm tương ứng

*) Trong bài viết này, hình chiếu song song được coi là ánh xạ của một mặt phẳng nói chung lên một mặt phẳng khác. Nhưng nhờ vào thành phần của các ánh xạ như vậy, chúng ta có thể đạt được vị trí của ảnh trong mặt phẳng ban đầu.

$A_2, B_2, C_2$ và $D_2$. Được biết, $\frac{|AA_1|}{|BA_1|} = \frac{|BB_1|}{|CB_1|} = \frac{|CC_1|}{|DC_1|} = \frac{|DD_1|}{|AD_1|} = \frac{|A_1D_2|}{|D_1D_2|} = \frac{|D_1C_2|}{|C_1C_2|} = \frac{|C_1B_2|}{|B_1B_2|} = \frac{|B_1A_2|}{|A_1A_2|}$.

Chứng minh rằng tứ giác $A_2B_2C_2D_2$ là hình bình hành có các cạnh song song với cạnh $BC$ – thành $n$ phần bằng nhau. Các đường thẳng được vẽ qua các điểm chia như Hình 4. Diện tích hình bình hành $ABCD$ là diện tích của tứ giác $NFGH$ là bao nhiêu?

8. Trong hình thang $ABCD$ ([AD] || [BC]) qua điểm $B$ có đường thẳng song song với $CD$ và cắt $AC$ tại điểm $P$, qua $C$ có đường thẳng song song với $AB$ và cắt $BD$ tại điểm $P$. Chứng minh rằng $[PQ] || [AD]$.

9. Trong hình thang $ABCD$ ([AD] || [BC]) qua điểm $C$ có một đường thẳng song song với $AB$ và cắt $BD$ tại điểm $P$. Được biết, $|BO| = |PD|$, trong đó $O = [AC] \cap [BD]$. Chứng minh rằng $|AD|^2 = |BC|^2 + |AD| \cdot |BC|$.
