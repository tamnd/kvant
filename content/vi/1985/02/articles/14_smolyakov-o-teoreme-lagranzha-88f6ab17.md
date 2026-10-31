---
id: 1985-2-smolyakov-o-teoreme-lagranzha-88f6ab17
issue: kvant_1985_2
year: 1985
number: "2"
title: Về định lý Lagrange
authors:
  - Смоляков Л. Н.
rubric: shkola-v-kvante
page_first: 32
page_last: 32
page_labels: "30"
tag: AVKX
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 6102963d254c787b127b38bb373ec791ab11f1e36a9cf870114936de3b1adb5e
prompt_sha256: draft-1
translated_from: content/ru/1985/02/articles/14_smolyakov-o-teoreme-lagranzha-88f6ab17.md
source_content_sha256: cf05311bef7b010d2c27b8d1a161579a1d6684a661714932dabad669da38d76e
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 30⟧

AD:BD=CF:FB. Từ sự giống nhau của các tam giác ABC và DBF, ta có AC:CB=FD:FB, và vì CF=FD nên AC:BC=CF:FB. Do đó, AD:BD=AC:BC (cả hai tỷ lệ đều bằng CF:FB).

Bằng chứng thứ năm. Diện tích của các tam giác có chiều cao bằng nhau thì có liên hệ với các đáy tương ứng. Do đó $S_{CDA}:S_{CDB}=AD:DB$ (Hình 5). Mặt khác, theo tính chất phân giác, chiều cao trong các tam giác CDA và CDB rơi từ đỉnh D đều bằng nhau. Vì vậy, $S_{CDA}:S_{CDB}=AC:BC$. Vì vậy, AD:BD=AC:BC=S_{CDA}:S_{CDB}.

Bằng chứng thứ sáu. Hãy vẽ một đường tròn bao quanh tam giác ABC và tiếp tục CD cho đến khi nó cắt đường tròn tại điểm E (Hình 6). Từ sự đồng dạng của các tam giác ACE và DCB ta thu được AC:AE=CD:DB, tức là AC·DB=AE·CD. Từ sự đồng dạng của các tam giác BCE và DCA ta có BC:BE=CD:AD, tức là BC×AD=BE·CD. Chú ý rằng AE=BE, ta có AC·DB=BC·AD, từ đó AD:BD=AC:BC.

Bằng chứng thứ bảy. Vẽ hai đường thẳng đi qua điểm D, một đường thẳng song song với cạnh AC và cắt cạnh BC tại điểm M, đường kia song song với cạnh BC và cắt cạnh AC tại điểm K (Hình 7). Dễ dàng chứng minh tứ giác KCMD là hình thoi. Từ sự đồng dạng của các tam giác AKD và DMB ta có AD:BD=DK:BM. Vì DK=DM nên AD:BD=DM:BM. Nhận thấy trong tỷ lệ kết quả tỷ lệ DM:BM bằng tỷ lệ AC:BC bằng nhau (dựa trên sự giống nhau của các tam giác ABC và DBM), chúng ta thu được

tỷ lệ cần thiết.

Với sự trợ giúp của các cách xây dựng được mô tả trong Hình 8-11, người đọc có cơ hội hiểu thêm bốn cách phát triển khác của định lý này.

Để kết luận, chúng tôi trình bày thêm hai cách chứng minh định lý, dành cho độc giả đã quen với vectơ và các phép biến đổi hình học.

1. Đối với bất kỳ điểm D nào của đoạn $AB\cdot CD=λ\vec{A}+(1-λ)\vec{B}$, trong đó λ=DB:AB; 1-λ=AD:AB. Thật vậy, $\vec{CD}=\vec{CB}+\vec{BD}=\vec{CB}+\lambda\vec{BA}=\vec{CB}+\lambda(\vec{CA}-\vec{CB})=\lambda\vec{CA}+(1-λ)\vec{CB}$.

Trong trường hợp của chúng ta, vectơ $\vec{CD}$ song song với vectơ $(1/CA)\cdot\vec{CA}+(1/CB)\cdot\vec{CB}$ (xem Hình 7) và do đó $(1/CA):(1/CB)=λ:(1-λ)$, từ đó AD:DB=CA:CB.

2. Chúng ta hãy thực hiện một phép đối xứng tuần tự đối với điểm D, chuẩn bị $H_{D}^{BD/AD}$ và $H_{C}^{AC/BC}$, sau đó là một phép đối xứng đối với đường phân giác CD (bằng $H_{O}^{k}$ chúng ta biểu thị sự đồng nhất với tâm O và hệ số k). Kết quả là điểm A sẽ giữ nguyên và đường thẳng CD sẽ biến thành chính nó, một phần khoảng cách giữa chúng sẽ không đổi. Do đó, hệ số của phép biến đổi độ tương tự cuối cùng là 1, tức là $AC/BC\cdot BD/AD=1$.

V.I.

Về định lý Lagrange

Trước hết, chúng ta hãy nhớ lại việc phát biểu định lý Lagrange.

Giả sử hàm f khả vi tại mỗi điểm của một khoảng nào đó. Khi đó giữa hai điểm a và b bất kỳ của khoảng này tồn tại một điểm c sao cho

$$f(b)-f(a)=f'(c)(b-a).$$

Định lý này cho phép giải thích hình học đơn giản. Lấy hai điểm A=M(a; f(a)) và B=M(b; f(b)) trên đồ thị của hàm f (xem hình). Độ dốc của đường thẳng AB bằng $(f(b)-f(a))/(b-a)$, độ dốc của tiếp tuyến với đồ thị hàm số f tại điểm hoành độ x=c bằng $f'(c)$. Vì vậy, sau khi viết ra

(Cuối cùng, xem trang 36)
