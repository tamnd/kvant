---
id: 1979-6-resheniya-zadach-m515-f527-f529-9ac62eae
issue: kvant_1979_6
year: 1979
number: "6"
title: Lời giải bài toán M515; F527—F529
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 19
page_last: 25
page_labels: 17, 18, 21, 22, 23
tag: OUOZ
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 0d6c8bc0e1d79c83d86027e26d2eabd52a95874cc4fff0f804f41a35ddc1da7a
prompt_sha256: draft-1
translated_from: content/ru/1979/06/articles/08_resheniya-zadach-m515-f527-f529-9ac62eae.md
source_content_sha256: cac3f27e74224000546fe7936380ab359611fca053057bebb504df54bf6cc0a3
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 17⟧

lα tạo bởi thanh ở một phía của góc này, gia tốc của lõi thanh (điểm C), nếu đầu B của thanh chuyển động với vận tốc không đổi v?

F579. Trong mạch điện ở hình 2, $R_1 = 10$ Ohm, $R_2 = 20$ Ohm, $R_3 = 15$ Ohm, chiều trong mạng điện xoay chiều là $U = 10$ V. Xác định công suất phân bổ cho các điện trở có điện trở $R_2$ và $R_3$.

G. Komkin

F580. Trong mạch như hình 3, suất điện động của pin là $\&$, điện trở trong của nó là $r$ và điện trở của điện trở là $R$. Khi phím $K_1$ đóng, kim điện kế $G$ lệch một góc $\alpha$. Kim điện kế sẽ lệch một góc bao nhiêu nếu phím $K_1$ đóng khi phím $K_2$ đóng? Độ lệch của kim tỷ lệ thuận với điện tích truyền qua điện kế.

F581. Một người đàn ông đứng trước gương với một mắt nhắm lại. Anh ta che đi hình ảnh một con mắt đang nhắm trong gương bằng cách mổ một mảnh giấy lên gương. Một người sẽ nhìn thấy gì nếu anh ta mở mắt nhắm và nhắm mắt lại?

F582. Một vật nổi trong nước sao cho $2/3$ thể tích của nó chìm trong nước. Phần thể tích nào sẽ ở dưới nước nếu một bình chứa nước chuyển động với gia tốc $a$ theo hướng trên?

Lời giải bài toán
M515; F527—F529

Trong bài toán này, chúng ta nghiên cứu phép toán sau trên một hình (tập hợp điểm) tùy ý Ф:

$$W(\Phi) = \bigcup_{M \in \Phi} S_M(\Phi)$$

— các ảnh đối xứng của hình Ф so với các điểm khác nhau $M \in \Phi$ được xem xét và sự kết hợp của chúng được thực hiện (trên tất cả các điểm $M$). Rõ ràng là luôn luôn $W(\Phi) \supset \Phi$ và

$$\text{ если } \Phi \subset \Phi', \text{ то } W(\Phi) \subset W(\Phi').$$

Làm rõ các câu hỏi cụ thể đặt ra trong điều kiện cho một chuỗi các dạng

$$\Phi, W(\Phi), W^2(\Phi) = W(W(\Phi)), \dots, W^n(\Phi) = W(W^{n-1}(\Phi))$$,

thu được bằng cách áp dụng lặp lại phép toán $W$ cho một tập hữu hạn $\Phi$ nào đó, chúng tôi sẽ đưa vào một nghiên cứu nhỏ, trong đó, về cơ bản, chúng tôi sẽ học cách tìm bao lồi của hình $W^n(\Phi)$ - tập lồi nhỏ nhất chứa $W^n(\Phi)$ - cho một hình tùy ý $\Phi$ và lưu ý một số tính chất thú vị của phép toán $W$.

⟦folio 18⟧

6) Cho $K_0$ gồm ba đỉnh của một tam giác đều có diện tích 1. Tìm diện tích của đa giác lồi nhỏ nhất chứa các tập hợp $K_n$ ($n=1,2,\dots$).

Trong ba đoạn tiếp theo, $K_0$ là tập hợp bốn đỉnh của một khối trung diện đều ở tập 1.

8) Khoảng cách của đa giác lồi nhỏ nhất chứa tất cả các điểm của tập hợp $K_1$. Đa giác này có bao nhiêu và ranh giới như thế nào?

e) Thể tích của đa giác này là bao nhiêu?

d) Tìm thể tích của đa giác lồi nhỏ nhất chứa các tập hợp $K_n$ ($n=2,3,\dots$).

Hình 1.

Hình 2.

Hình 3.

Hình 4.

Trước khi đọc thêm lời giải, hãy vẽ các hình $W(\Phi)$ và $W^2(\Phi)$ nếu $\Phi$ là một cặp điểm; phân đoạn; hình chữ nhật; bốn đỉnh thẳng/lib; ba đỉnh của một tam giác. $W(\Phi)$ là gì nếu $\Phi$ là hình lập phương? tám đỉnh của một hình lập phương?

Hãy bắt đầu với trường hợp “một chiều”, khi hình $\Phi$ nằm trên một đường thẳng. Trường hợp này cần thiết cho lời giải bài toán a), nhưng, như chúng ta sẽ thấy, nó cũng hữu ích trong những bài toán khó hơn.

Đầu tiên, giả sử hình của chúng ta là một đoạn $\Pi=[AB]$ có độ dài $d$ với điểm giữa của nó tại điểm $O$. Khi đó $\Phi(\Pi)=[A_1B_1]$ là đoạn có độ dài $3d$ với điểm giữa của nó tại cùng điểm $O$. Ngay sau đó là $\Phi^2(\Pi)=[A_2B_2]$, trong đó $|A_2B_2|=9d$ và nói chung $\Phi^n(\Pi)=[A_nB_n]$, trong đó $|A_nB_n|=3^n d$ và tất cả các đoạn $[A_nB_n]$ có điểm giữa tại cùng một điểm $O$ (Hình 1).

Trong phần tiếp theo, chúng ta sẽ biểu thị các hình $\Phi$, có tâm đối xứng $O$ và trong tomothenia với hệ số $k$ và tâm $O$ được ký hiệu là $k\Phi$. Chúng tôi phát hiện ra rằng nếu $\Pi$ là một phân đoạn thì $W(\Pi)=3\Pi$ và nói chung là $W^n(\Pi)=3^n\Pi$.

Nhìn về phía trước, chúng tôi lưu ý rằng điều này đúng với mọi hình lồi đối xứng tâm $\Pi$. Nhưng trước hết hãy trả lời câu a) theo định luật trong trường hợp một chiều.

a) Đặt $K_0=\{A,B\}$, $|AB|=1$. Theo (2), trong đó $\Phi=\{A,B\}$, $\Pi=\Phi'=[AB]$,

$$K_n=\Phi^n(K_0)\subset\Phi^n(\Pi)=3^n\Pi.$$

Rõ ràng là $K_n$ chứa tất cả các điểm của đoạn $[A_nB_n]=3^n\Pi$, nằm cách điểm $A$ một khoảng nguyên, và các điểm cực trị $\{A_n,B_n\}=3^n\{A,B\}$ nằm cách $A$ ở khoảng cách $(3^n-1)/2$ và $(3^n+1)/2$ (Hình 2). Vì những con số này (Hình 3) lớn hơn 10.000 tại $n\geqslant10$, đáp số nên câu hỏi a): $n=10$.

Trong lời giải mặt phẳng và không gian bài toán về phép toán $W$ thuộc tính sau của nó rất hữu ích: nếu $\Phi_l$ là hình chiếu của hình $F$ lên đường thẳng $l$, thì

$$W(\Phi_l)=(W(\Phi))_l$$

(hình chiếu $W(\Phi)$ lên đường thẳng $l$ giống như kết quả của việc áp dụng $W$ cho hình chiếu $\Phi_l$) *. Điều này ngay lập tức tuân theo định nghĩa của $W$ và thực tế là trong quá trình chiếu, các điểm đối xứng với điểm $M$ rơi vào các điểm đối xứng với hình chiếu của nó $M_l$ (Hình 4).

Từ đó, nếu $\Pi$ là một dải và $3^n\Pi$ là ảnh của nó trong điều khiển chuyển động với hệ số $3^n$ so với tâm đối xứng (bất kỳ điểm nào trên đường giữa), thì sự tương ứng $\Pi$ được đáp ứng - tập hợp các điểm nằm giữa hai mặt phẳng.

Từ (2), (3), (5) và lời giải bài toán a) cũng suy ra rằng nếu chúng ta đặt hình $F$ trong một dải hỗ trợ $\Pi$ theo bất kỳ hướng nào - một dải như vậy $\Pi\supset\Phi$, các cạnh của nó chứa tất cả các điểm từ $\Phi$ - thì dải $3^n\Pi\supset W^n(\Phi)$ sẽ là dải hỗ trợ cho $W^n(\Phi)$ (Hình 5). Thông báo này, tổng quát hóa (4), cho phép chúng ta tìm bao lồi $W(\Phi)$ cho mọi hình $F$.

Hãy xem xét các ví dụ cụ thể.

6) Đặt $K_0=\{A,B,C\}$ là các đỉnh của một tam giác đều, $K_n=W^n(K_0)$, $n=1,2,\dots$ (Hình 6). Hãy để chúng tôi chứng minh rằng với mọi $n\geqslant1$, bao lồi của tập hợp $K_n$ thu được như sau: chúng ta cần lấy các đầu của các đoạn $3^n[AB]$, $3^n[BC]$ và $3^n[AC]$ rồi dựng một hình lục giác lồi $\Sigma_n$ với các đỉnh tại các điểm này.

*) Hình chiếu của hình không gian $F$ lên đường thẳng $l$ là tập hợp các điểm $M\in l$ sao cho mặt phẳng, hình chiếu qua các điểm $M$ và vuông góc với $l$ cắt nhau $\Phi$.

⟦folio 21⟧

F527. Trong mạch như hình 8, suất điện động của pin là $G=100$ V, điện trở trong của nó là $r=100$ Ohm, điện dung của tụ điện là $C=200$ uF và điện trở của máy cắt là $R=10$ Ohm. Phím K chuyển đổi giữa các điểm ngưng tụ a và b với tần suất $f=10$ lần mỗi giây. Khi nối nó với cực a thì tụ điện được tích điện đầy, khi nối với cực b thì tụ điện được tích điện đầy. Hiệu suất của mạch là bao nhiêu? Cao hơn bao nhiêu lần so với khi máy cắt nối trực tiếp với pin? Sức mạnh nào được giải phóng ở mức kháng cự $R$?

Hình 8.

Khi một tụ điện được nối với pin, nó sẽ sạc tới điện áp $U=\mathcal{E}$, nhận điện tích $q=CU=\mathcal{C}\mathcal{E}$. Năng lượng của tụ điện trở thành $W=\frac{1}{2}C\mathcal{E}^2$.

Pin hoạt động $A=\mathcal{E}q=\mathcal{C}\mathcal{E}^2$. Do đó, lượng nhiệt $Q$ tỏa ra trong mạch bằng $A-W=\frac{1}{2}C\mathcal{E}^2$. Pin được mắc nối tiếp với pin được làm nóng và tại bất kỳ thời điểm nào cũng có cùng một dòng điện chạy qua chúng. Do đó, nhiệt được phân bổ giữa chúng tỷ lệ với điện trở của chúng, tức là nhiệt tỏa ra khi đun nóng $R$

$$Q_1=(A-W)\frac{R}{R+r}=\frac{C\mathcal{E}^2}{2}\frac{R}{R+r}.$$

Khi đóng tụ điện trên bộ sưởi (phím $K$ ở vị trí $6$), tụ điện được tích điện đầy và năng lượng $W$ của nó chuyển thành nhiệt tỏa ra trên bộ sưởi:

$$Q_2=W=\frac{C\mathcal{E}^2}{2}.$$

Vì vậy, trong một chu kỳ đầy đủ, bạn làm nóng nhiệt

$$Q=Q_1+Q_2=\frac{C\mathcal{E}^2}{2}\frac{R}{R+r}+\frac{C\mathcal{E}^2}{2}=\frac{C\mathcal{E}^2}{2}\left(\frac{2R+r}{R+r}\right).$$

Hiệu suất của mạch là

$$\eta_1=\frac{Q}{A}=\frac{C\mathcal{E}^2}{2}\frac{2R+r}{R+r}=\frac{2R+r}{2(R+r)}=\frac{6}{11}.$$

Khi nối trực tiếp vào ắc quy thì hiệu suất của mạch bằng

$$\eta_2=\frac{R}{R+r}=\frac{1}{11}.$$

Vì vậy, $\eta_1/\eta_2=6$.

Hãy tìm công suất $P$ được giải phóng khi đun nóng. Trong 1 giây, $n=f/2$ hoàn thành chu kỳ chuyển đổi phím $K$ xảy ra. Kể từ đây,

$$P=nQ=\frac{f}{2}\frac{C\mathcal{E}^2}{2}\left(\frac{2R+r}{R+r}\right)\approx 5,5\text{ Вт.}$$

At.mechane. Trong điều kiện bài toán, đề xuất giả định rằng tụ điện tự sạc lại thành công trong thời gian $t=1/f=0,1$ giây. Hãy kiểm tra xem giả định này đúng đến mức nào.

Khi nối tụ điện với pin thì dòng điện thu được là $I=\mathcal{E}/(R+r)$. Trong thời gian $t$, sau đó tụ điện được sạc đến điện áp $U=\mathcal{E}$, điện tích đầy $q=C\mathcal{E}$ sẽ đi qua pin. Do đó, ở dòng điện $I=\mathcal{E}/(R+r)$ tụ điện được tích điện đúng thời gian $t=q/I=C\mathcal{E}/(R+r)/\mathcal{E}=C(R+r)=2,2\cdot 10^{-2}\text{ c}$. Trong thực tế, khi điện áp trên tụ tăng, dòng điện sẽ giảm và tụ sẽ không được tích điện vào điện áp $U=\mathcal{E}$. Tuy nhiên, vì $t\gg t$, có thể coi phép tính gần đúng là tụ điện đã được sạc đầy thành công.

A. Zilberman

◆

Công suất $P$ do bóng đèn giải phóng bằng $U_\pi I$, trong đó $U_\pi$ là điện áp trên bóng đèn, $I$ là dòng điện trong mạch. Mối quan hệ có thể có giữa $U_\pi$ và $I$ được xác định bởi đặc tính dòng điện-điện áp của bóng đèn (Hình 9). Mặt khác, điện áp trên bóng đèn được xác định bởi điện áp tương ứng

⟦folio 22⟧

một chiều không đổi nick $U=10B$ nối tiếp với một điện trở có điện trở $R=4\Omega$. Xác định công suất của bóng đèn.

![Graph](image)

Hình 9.

F529. Sử dụng công thức dành cho áp phích quảng cáo (Hình 10), xác định: 1) tiêu cự của vật thể camera; 2) ống kính nằm ở khoảng cách bao nhiêu so với lòng bàn tay khi lập công thức; 0) kích cỡ của con cá mà ngư dân đánh bắt được; 4) đường kính của vật thể (giả sử kích thước chi tiết hình ảnh trên công thức không vượt quá 0,2 mm). Thấu kính công thức được coi như thấu kính một mắt.

Sheniem

$$U_{\pi}=U-U_R=U-IR,$$

trong đó $U_R$ là điện áp trên điện trở. Do đó, đối với một giá trị điện trở cho trước $R$ $U_{\pi}$ và $I$ được xác định bởi giao điểm của đường thẳng $U-IR=10-4I$ (gọi là đường thẳng tải) với đặc tính dòng điện - điện áp của bóng đèn. Vẽ đường thẳng tải trọng trên đồ thị, ta tìm được các giá trị $U_{\pi}$ và $I$ tương ứng với điểm $A$:

$$U_{\pi}\approx 5,5\ B, \ I\approx 1,2\ A.$$

Vậy công suất phát ra của bóng đèn bằng

$$P=U_{\pi}I\approx 6,6\ Bt.$$

I. Slobodetsky

Phối cảnh trong bức ảnh bị bóp méo rất nhiều. Nhiều chi tiết khác nhau của vật thể (khuôn mặt của ngư dân, lòng bàn tay, v.v.) được hình thành ở các độ phóng đại khác nhau.

Độ phóng đại thường được gọi là tỷ lệ kích thước của hình ảnh và vật thể, bằng tỷ lệ khoảng cách từ đường thẳng đến mặt phẳng ảnh (nghĩa là đến phim ảnh) và từ vật thể đến đường thẳng. Trong trường hợp của chúng tôi, mức tăng ở tất cả các phần nhỏ hơn một. Sự khác biệt đáng chú ý về độ phóng đại của khuôn mặt và bàn tay chỉ có thể đạt được khi tính toán ở cự ly gần.

Kỹ thuật ước tính kích thước khuôn mặt của người câu cá là $l_1\approx 20$ cm, chiều rộng lòng bàn tay là $l_2\approx 10$ cm, và khoảng cách từ mặt đến lòng bàn tay dang rộng của anh ta là $a\approx 50$ cm. Chúng ta hãy biểu thị khoảng cách từ lòng bàn tay đến vật thể bằng $x$ và khoảng cách từ vật thể đến phim ảnh bằng $y$. Theo công thức, kích thước khuôn mặt là $h_1\approx 1,5$ cm, chiều rộng lòng bàn tay là $h_2\approx 1,5$ cm. Độ phóng đại $\Gamma_1$ và $\Gamma_2$ của các chi tiết này được thể hiện tương ứng với

$$\Gamma_1=\frac{h_1}{l_1}=\frac{y}{x+a}, \ \Gamma_2=\frac{h_2}{l_2}=\frac{y}{x},$$

Ở đâu

$$x=\frac{l_2}{h_2}\ y, \ y=\frac{ah_1h_2}{l_1h_2-l_2h_1}.$$

Từ các biểu thức này sau khi thay thế các giá trị số

$$x\approx 50\ cm, \ y\approx 7,5\ cm.$$

⟦folio 23⟧

Vì trong bức ảnh khoảng cách giữa hai lòng bàn tay là $h \approx 8$ cm nên chúng ta có thể kết luận rằng kích thước của cá trảng là

$$l = \frac{h}{\Gamma_2} = \frac{h l_2}{h_2} \approx 53 \text{ см.}$$

Để xác định khoảng cách công thức $F$ của một vật thể và đường kính của nó $D$, cần phải tính đến việc vật thể được lập công thức trong trường hợp của chúng ta có kích thước đáng kể dọc theo trục quang học (độ sâu). Điểm cực gần (lòng bàn tay) cách vật khoảng 50 cm, điểm cực xa (mặt) cách vật khoảng 100 cm. Rõ ràng là thấu kính không thể cho ảnh rõ nét đồng thời của cả hai điểm này (và tất cả các điểm trung gian) trên phim ảnh, nằm ở khoảng cách $y \approx 7,5$ cm phía sau thấu kính. Khi tia truyền đi từ điểm xa (A) và gần nhất (B) của vật, chỉ xuất hiện một số điểm trung gian $C$, nằm ở đâu đó giữa điểm gần nhất và điểm xa nhất. Hình ảnh rõ ràng của các điểm $A$ và $B$ lần lượt nằm ở phía trước và phía sau phim ảnh, trên phim ảnh của chúng thu được ở dạng điểm có kích thước $\Delta$, không vượt quá bài toán 0,2 mm tùy theo điều kiện. Giả sử để ước tính điểm tạo hình $C$ nằm cách thấu kính một khoảng $x + a/2 \approx 75$ cm, ta viết nó ra bằng công thức tuyến tính,

$$\frac{1}{x + a/2} + \frac{1}{y} = \frac{1}{F}.$$

Từ đây, sau khi thay thế các giá trị số, ta tìm được $F \approx 6,8$ cm. Có thể thấy từ Hình 11, để độ sắc nét của mọi chi tiết ở độ sâu đáng kể của vật thể, ống kính máy ảnh phải được định khung lại thật mạnh, tức là đường kính $D$ của phần mở của vật thể phải khá nhỏ. Xác định vị trí của ảnh $B_1$ của điểm gần nhất $B$ bằng công thức tuyến tính -

$$\frac{1}{x} + \frac{1}{d_1} = \frac{1}{F}$$

- và lập tỷ lệ ước tính

$$\frac{D}{d_1} = \frac{\Delta}{d_1 - y},$$

chúng tôi tìm thấy sau khi thay thế các giá trị số: $d_1 \approx 7,9$ cm; $D \approx 4$mm. (Tất nhiên, vị trí ảnh của điểm xa nhất $A$ có ​​thể được sử dụng để ước tính đường kính của vật thể.)

Vì vậy, ước tính của chúng tôi đưa ra:

1) công thức: khoảng cách đối tượng camera $F \approx 6,8$ cm; 2) khi tạo hình đối tượng, nó được đặt ở khoảng cách $x \approx 50$ cm so với lòng bàn tay; 3) con cá đã cố gắng thử một con cá có kích thước khoảng 53 cm; 4) ống kính máy ảnh có khẩu độ 4 mm.

S. Kozel
