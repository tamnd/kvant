---
id: 1990-1-slinko-kompyuternyiy-turnir-xxiii-vsesoyuznoy-olimpiadyi-po-matematike-3fb46654
issue: kvant_1990_1
year: 1990
number: "1"
title: Giải đấu máy tính của Olympic Toán học toàn Liên minh lần thứ XXIII
authors:
  - Слинько А. М.
rubric: olimpiady
rubric_sub: Олимпиады
page_first: 77
page_last: 78
page_labels: 75-76
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 496642c22dc8423f03d40c45ac98f69174ad9361609004f85db46461147ab1b6
prompt_sha256: draft-1
translated_from: content/ru/1990/01/articles/19_slinko-kompyuternyiy-turnir-xxiii-vsesoyuznoy-olimpiadyi-po-matematike-3fb46654.md
source_content_sha256: 15731058a196dbf456e3bb3a8144c4f136272f0a11139e2ff3d5c292ca6fa6b3
translation_model: draft
translation_run: vi-draft-gaps-2026-11-01
translation_quality: draft
---

⟦folio 75⟧

Giải máy tính Olympic Toán quốc gia lần thứ XXIII

Năm 1989, tại Olympic Toán học toàn Nga, ban giám khảo quyết định thử nghiệm một giải đấu trên máy tính lần đầu tiên. lời giải này đã chín từ lâu; Trong vài năm nay, các trò chơi trên máy tính đã được tổ chức dành cho những người tham gia Olympic và ban giám khảo đã có cơ hội tận mắt chứng kiến ​​​​sự thu hút của trẻ em đối với máy tính tạo ra sự khác biệt như thế nào. Tất nhiên, vẫn còn quá sớm để chuẩn bị đưa giải máy tính vào cuộc thi chính thức của Olympic; trong tương lai, Olympic Toán toàn năng có thể sẽ có vòng thi thực tế riêng. Điều này sẽ rất đáng mong đợi, vì toán học rất nguy hiểm đối với những nguồn cung cấp sự sống cho các ứng dụng của nó - khi đã phát triển một sợi dây kết nối chúng, chúng ta có nguy cơ làm chảy máu cả hai bên.

Bài toán tham quan máy tính

1. Với một cặp số $(a, b)$, được phép thực hiện các phép biến đổi sau: thêm một số khác vào một trong các số này và biến cặp hiện có thành cặp $(a+b, b)$ hoặc cặp $(a, a+b)$. Viết và lập trình một thuật toán tính số phép biến đổi nhỏ nhất cần thiết để biến cặp $(1, 1)$ thành một cặp chứa số $N$ ($1 \leq N \leq 2000$).

V. Rozhdestvensky

2. Dãy số $\{a_n\}$ được xác định bởi số hạng đầu tiên $a_1=1/e$ và hệ thức truy hồi $a_n=1-na_{n-1}$. Tính số $a_n$ cho $n \leq 50$ đến bốn chữ số thập phân. Hãy coi như đã biết rằng

$$\frac{1}{e} = \frac{1}{2!} - \frac{1}{3!} + \frac{1}{4!} - \frac{1}{5!} + \dots$$

E. Tyrtyshnikov

24 (10). Phương trình có bao nhiêu lời giải số thực?

$$\sin(\sin(\sin(\sin x)))) = x/3?$$

25 (10). Máy vi tính FN-89 chỉ thực hiện hai thao tác: $x \rightarrow 2x-1$ và $x \rightarrow 2x$. Một số tự nhiên đã được nhập vào máy tính vi mô. Chứng minh rằng bằng cách nhấn các nút, bạn có thể nhận được từ nó một số chính xác là lũy thừa thứ năm.

Bài toán đề xuất bởi: A. Burago (20), S. Genkin (2, 4, 14), A. Golovanov (3), M. Gusarov (1, 13), V. Kozyrev (2), A. Merkuryev (22), F. Nazarov (6, 17, 25), N. Nechetaev (11), D. Fomin (5, 7, 8, 10, 12, 16, 18, 19, 21, 23, 24), S. Fomin (9), I. Sharyzin (15). Năm bài toán khác của sự tối ưu hóa này tạo thành “Bài toán to Kvanta” trong Toán học số 11, 1989 (M1191–M1195).

3. Dãy số $\{x_n\}$ được gọi là tuần hoàn nếu đối với một số số tự nhiên $M$ và $T$ đẳng thức $x_n=x_{n+T}$ đúng với mọi $n>M$. Số nhỏ nhất $M$ và $T$ có đặc tính này được gọi là dilium của phần làn đường và dilium của chu kỳ tương ứng.

Người ta biết rằng đối với một số hạn chế về hàm của đối số tự nhiên $f(x)$ với mọi $i \geq 1$ thì đẳng thức $x_{i+1}=f(x_i)$ là đúng nên dãy $\{x_n\}$ là tuần hoàn.

a) Chỉ định một thuật toán, cho một chuỗi như vậy, sẽ xác định $M$ và $T$, sử dụng số so sánh tuyến tính ở mức lớn nhất của hai số này;

b) Lập trình thuật toán này để tính độ dài của khoảng thời gian và độ dài của phần làn của chuỗi $\{x_n\}$ cho số hạng đầu tiên $x_1$ cho các hàm $f(x)$, giá trị của nó tại điểm $x$ là phần còn lại của phép chia cho $10^8$ của số $g(x)$, xác định công thức

$$g(x) = \begin{cases} x/3 & \text{при } x=3k \\ 2(x-1)/3 & \text{при } x=3k+1 \\ 13(x-2)/3 & \text{при } x=3k+2. \end{cases}$$

Y. Nesterenko, A. Slinko

Khi kiểm tra nhiệm vụ được giao, ban giám khảo đã gặp một số khó khăn, dường như đây là những khó khăn điển hình của tất cả các cuộc thi trên máy tính. Đây chỉ là một số trong số đó: không thể kiểm tra tính đúng đắn của chương trình và tính đúng đắn của các thuật toán do thời gian và số lượng thành viên ban giám khảo có hạn; sự không đồng nhất trong việc sử dụng công nghệ máy tính và ngôn ngữ lập trình; sự cần thiết phải tính đến các đặc điểm thời gian của chương trình liên quan đến tính không đồng nhất đã chỉ định.

Sau khi viết chương trình và tuyên bố mức độ sẵn sàng của mình, học sinh được yêu cầu tính toán ba ví dụ kiểm tra cho mỗi bài toán. Một điểm được trao cho mỗi câu đúng đáp số. Mọi kế toán viên đều có thể ghi được 9 điểm. Họ đã được tuyển dụng, qua đó giành vị trí đầu tiên của giải đấu, B. Dubrov (Minsk, s. sh. Số 107), M. Khosidov-

⟦folio 76⟧

---
running_head:
folio:
---

Theo ý kiến ​​chung, việc tham quan bằng máy tính đã bị loại bỏ và nên thực hiện trong thời gian tới. Tuy nhiên, cần lưu ý rằng không phải thành phố nào bây giờ cũng có thể, như Riga, cung cấp cho người tham gia hơn một trăm máy tính cá nhân, bởi vì 116 học sinh bày tỏ mong muốn được tham gia vào thanh ngang.

Chuyến tham quan này không thể diễn ra nếu không có điều kiện tốt của ban tổ chức và trước hết,

Ombet chỉ ra Leningrad, s.sh. số 239).

Máy điện DC
1. $n_3 = n_1 - 1, 2(n_1 - n_2) = 640$ vòng/phút.
2. $P_2 = P_1 \frac{I_2^2}{I_1^2} - \frac{UI_2(I_2 - I_1)}{I_1} = 6$ kW.
3. Sức mạnh tích cực tăng 21%.
4. $P_{\text{c max}} = \frac{U^2}{4(R_1 + R_2)} < P_{\text{ш max}} = \frac{U^2}{4R_1}$;
$\eta_{\text{c}} = \frac{1}{2}; \eta_{\text{ш}} = \frac{1}{2} \frac{1}{1 + 2R_1/R_2}$.

Viện Vật lý-Kỹ thuật Moscow
Toán học
Tùy chọn 1
1. $\left(0; \frac{-1 + \sqrt{5}}{2}\right)$.
2. $\pm \frac{1}{2}$ arccos $\frac{3}{7} + \pi n, n \in \mathbb{Z}$.
3. $\frac{8}{9\sqrt{5}}$.
4. $\frac{25}{2}$ arccos $\frac{3}{5} - 6$. Gợi ý. Tập lời giải của bất đẳng thức thứ nhất—khoảng $(-3; a^2 + b^2)$—phải nằm hoàn toàn trong đoạn có điểm cuối $(a + b)$ và 25/2.
Pozotomu
$$\begin{cases} a + b \geq 3, \\ a^2 + b^2 \leq \frac{25}{2}. \end{cases}$$

Hình Ф được mô tả trên hình 1. Để tính diện tích của nó, hãy trừ diện tích của tam giác $AOB$ khỏi diện tích của hình cung $OAmB$. 5. 183:40. Lời giải. Đặt $r_1$ và $r_2$ là bán kính của các đường tròn mà mặt phẳng $C_1EF$ giao với hình cầu thứ nhất (bán kính $R_1 = 13$) và thứ hai (bán kính $R_2 = 5$) của các hình cầu tương ứng (hình 2), $h_1$ và $h_2$ khoảng cách từ tâm $O_1$ và $O_2$ những quả cầu này với mặt phẳng $C_1EF$. Sau đó $h_i = \sqrt{R_i^2 - r_i^2}, i = 1, 2$. Nó tuân theo điều kiện là $r_1:r_2 = R_1:R_2 = 13:5$, do đó $h_1:h_2 = 13:5$, tức là $h_1 \neq h_2$, và do đó, đường tâm của hình cầu $O_1O_2$ không song song với mặt phẳng $C_1EF$. Gọi $P$ là giao điểm của đường thẳng $O_1O_2$ với mặt phẳng $C_1EF$. Sau đó $PO_1:PO_2 = h_1:h_2$. Theo đó, điểm $P$ trùng với điểm $P_1$ tiếp tuyến của hình cầu hoặc với điểm $P_2$ của giao điểm của các đường $O_1O_2$ và $AD$. Trường hợp thứ hai là không thể, vì mặt phẳng đi qua các điểm $C_1$, $E$ và $P_2$ hiển nhiên không cắt cạnh $BC$. Do đó, mặt phẳng $C_1EF$ cắt đoạn $O_1O_2$ tại điểm $P_1$ tiếp xúc với hình cầu đã cho.

Xét hình lập phương theo mặt phẳng $AB_1C_1D$ (hình 3). Gọi $M_1, T, M_2$ là hình chiếu trực giao của điểm $O_1, P_1, O_2$ lên đoạn $AD$. Khi đó cạnh $AD$ của hình lập phương bằng $AM_1 + M_1M_2 + M_2D = R_1 + M_1M_2 + R_2 = 18 + M_1M_2$. Hãy cùng tìm $M_1M_2$. Vì $O_1M_1 = R_1\sqrt{2}, O_2M_2 = R_2\sqrt{2}, O_1O_2 = R_1 + R_2$, nên $M_1M_2 = \sqrt{O_1O_2^2 - (O_1M_1 - O_2M_2)^2} = \sqrt{(R_1 + R_2)^2 - 2(R_1 - R_2)^2} = 14$. Vì $FC = \frac{1}{2}HD$ và ngoại lệ là $\frac{BF}{FC} = \frac{BC - FC}{FC} = \frac{BC}{FC} - 1 = \frac{2AD}{HD} - 1$, nên vẫn phải tìm $HD$. Từ sự giống nhau của các tam giác vuông $O_1LO_2$ và $P_1NO_2$ (xem hình 3), suy ra rằng $P_1N = \frac{O_1L \cdot P_1O_2}{O_1O_2} = \frac{\sqrt{2(R_1 - R_2)R_2}}{R_1 + R_2}$, và do đó $P_1T = P_1N + NT = P_1N + O_2M_2 =$

Hình 1.
