---
id: 1977-10-geydman-gomotetiya-i-zamechatelnyie-tochki-v-treugolnike-5e2ac1e4
issue: kvant_1977_10
year: 1977
number: "10"
title: Những điểm đồng đẳng và những điểm đáng chú ý trong một tam giác
authors:
  - Гейдман Б. П.
rubric: po-stranitsam-shkolnyh-uchebnikov
rubric_sub: По страницам школьных учебников
page_first: 50
page_last: 51
page_labels: 48-49
tag: 4OXW
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 3b4229edb7ebe66d038752fce20203b46dc2425c291fc64483418d76f07363d3
prompt_sha256: draft-1
translated_from: content/ru/1977/10/articles/10_geydman-gomotetiya-i-zamechatelnyie-tochki-v-treugolnike-5e2ac1e4.md
source_content_sha256: 4d6685a4b8f6ba3fba0b1f895f930e434cc4137ab0836296b81ba2ca25a98d34
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 48⟧

Những điểm đồng đẳng và những điểm đáng chú ý trong một tam giác

Trong lưu ý này, chúng tôi sẽ giải thích cách sử dụng tính đồng nhất để giải nhiều bài toán khó về mặt phẳng bài toán - đặc biệt là bài toán về các điểm đáng chú ý trong một hình tam giác.

Bài toán về vật lộn

Hãy bắt đầu với bài toán về cây nho. Đây là cách diễn đạt của nó:

Chứng minh rằng đường thẳng đi qua giao điểm của các cạnh bên kéo dài của hình nho và giao điểm của các đường chéo của nó đi qua trung điểm của các đáy hình nho.

Làm thế nào để giải quyết nó? Hãy vẽ một cây nho, tiếp tục các cạnh của nó, vẽ các đường chéo và nối các điểm giữa của các đáy (xem Hình 1). Ta thấy có nhiều cặp tam giác đồng dạng được tạo thành. Gắn liền với những hình vẽ như vậy là sự ánh xạ của mặt phẳng lên chính nó, được gọi là hình học. Dưới sự đồng nhất với tâm O và hệ số $k \neq 0$, ảnh của một điểm X tùy ý là một điểm $X_1$ sao cho $\overrightarrow{OX_1} = k\overrightarrow{OX}$ (xem “Hình học 7”, mục 79). Hãy thử giải bài toán của chúng ta về Grapecia bằng cách sử dụng tính đồng nhất.

Đặt $S$ là điểm giao nhau của các cạnh bên mở rộng $AB$ và $CD$ của đường cong $ABCD$, $O$ là điểm giao nhau của các đường chéo của nó (Hình 1).

Hãy xem xét hai điểm tương đồng: $H_S$ với tâm $S$ và $H_O$ với tâm $O$, chuyển phần đế $AD$ của quả nho vào phần đế $BC$. Trung điểm $M$ của đoạn $AD$ trong cả hai điểm đồng tính đều tiến đến trung điểm $N$ của đoạn $BC$, khi đó các điểm $M$ và $N$ nằm trên đường thẳng $OS$ đi qua tâm của các điểm đồng tính $H_S$ và $H_O$.

Chúng ta hãy xem xét lời giải này chi tiết hơn.

Tính đồng nhất $H_S$ được xác định bởi tâm $S$ của nó và một cặp điểm tương ứng $A$ và $B$. Theo tính chất đồng âm, đường thẳng $AD$ khi đó sẽ biến thành đường thẳng song song $BC$. Hình ảnh của điểm $D$ sẽ nằm trên đường $BC$. Mặt khác, điểm tương ứng với điểm $D$ nằm trên đường thẳng $SD$ đi qua tâm đồng âm $S$.

Do đó, tính đồng nhất $H_S$ lấy điểm $D$ đến điểm giao nhau của các đường $BC$ và $SD$, tức là lấy điểm $C$, và gốc cây nho $AD$ với gốc $BC$: $H_S([AD]) = [BC]$.

Tương tự, người ta chứng minh rằng $H_0([AD]) = [CB]$ (tính đồng âm $H_O$ được cho bởi tâm $O$ và cặp điểm tương ứng $A$ và $C$).

Tính đồng nhất biến phần giữa của một đoạn thành phần giữa của hình ảnh của đoạn này, vì với tính đồng nhất, tất cả khoảng cách giữa các điểm được nhân với cùng một số bằng modulo của hệ số đồng nhất.

Và cuối cùng, trung điểm của các đáy cây nho, là điểm đồng nhất tương ứng, nằm trên một đường thẳng đi qua tâm của nó.

Trọng tâm tam giác

Bây giờ chúng ta hãy chứng minh, bằng cách sử dụng kết quả bài toán trên Grapecia, định lý về các đường trung tuyến của một tam giác, cụ thể là, chúng ta chứng minh rằng các đường trung tuyến của một tam giác cắt nhau tại một điểm và được chia tại điểm đó theo tỷ lệ 2:1, tính từ đỉnh.

Bằng chứng. Đặt $AD$, $BE$ và $CF$ là đường trung tuyến của tam giác $ABC$ (Hình 2). Trong đồ thị $AFDC$, các đường trung tuyến $AD$ và $CF$ đóng vai trò là đường chéo, sau đó điểm $M$ giao nhau của chúng nằm trên đường thẳng nối điểm giữa $E$ của đáy $AC$ của đồ thị với giao điểm của các cạnh bên mở rộng $AF$ và $CD$, đó là - với đỉnh $B$ của tam giác. Như vậy, điểm $M$ giao điểm của đường trung tuyến $AD$ và $CF$ nằm và

⟦folio 49⟧

Trực tâm của tam giác
Hãy chứng minh thêm một định lý nữa.

Các đường cao của tam giác cắt nhau tại một điểm. (Điểm mà các đường cao cắt nhau gọi là trực tâm của tam giác.)

Bằng chứng. Gọi $M$ là trọng tâm của tam giác đã cho $ABC$; $F, D$ và $E$ là phần giữa của cạnh của nó (Hình 3). Hãy xem xét một $H_M^{-2}$ làm sẵn với tâm tại điểm $M$ và hệ số $k = -2$. Công cụ làm sẵn này lần lượt biến đổi các điểm $F, D$ và $E$ thành các đỉnh $C, A$ và $B$ của tam giác $ABC$, và độ cao của tam giác $FDE$ thành các đỉnh của tam giác $ABC$. Nhưng các đường cao của tam giác $FDE$, là các đường phân giác vuông góc với các cạnh của tam giác $ABC$, cắt nhau tại một điểm $O$ - tâm của đường tròn ngoại tiếp tam giác $ABC$. Do đó, ảnh của chúng (khi chuẩn bị $H_M^{-2}$) cũng giao nhau tại một điểm $R$ (trực tâm của tam giác $ABC$).

Trong quá trình thực hiện, chúng tôi đã chứng minh được hệ quả quan trọng sau:

Trọng tâm $M$ của bất kỳ tam giác nào, trực tâm $R$ và tâm $O$ của đường tròn ngoại tiếp nó nằm trên cùng một đường thẳng (gọi là đường thẳng Euler) và điểm $M$ nằm giữa các điểm $O$ và $R$ sao cho $|MR| = 2 |OM|$.

Bài tập

1. Tìm những đoạn làm sẵn để chuyển đổi một trong hai đoạn song song đã cho thành đoạn kia.
2. Một đường tròn và hai điểm $A$ và $B$ trên đó được cho trên mặt phẳng. Đặt $N$ là một điểm tùy ý của đường tròn này, $M$ trọng tâm của tam giác $ABN$. Tìm tập hợp điểm $M$.
3. Hai đường tròn đồng tâm được cho trên một mặt phẳng. Vẽ một hợp âm ở phần lớn hơn sao cho nó được chia bởi một vòng tròn nhỏ hơn thành ba phần tắc nghẽn.
4. Hai vòng tròn tiếp xúc ở bên ngoài. Các điểm tiếp tuyến của các tiếp tuyến chung ngoài được nối nối tiếp. Chứng minh rằng một đường tròn có thể nội tiếp được trong tứ giác đó.
5. Cho một góc nhọn $AOB$ và các điểm $C$ bên trong góc đó. Tìm một điểm $M$ trên cạnh $OB$, cách đều cạnh $OA$ và cách đều điểm $C$.
6*. Chứng minh rằng trong một tam giác bất kỳ, đáy các đường cao, trung điểm các cạnh và trung điểm các đoạn thẳng nối trực tâm với các đỉnh của tam giác đều nằm trên cùng một đường tròn. (Vòng tròn này được gọi là vòng tròn chín thùy.)
