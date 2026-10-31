---
id: 1971-4-resheniya-06ad36a2
issue: kvant_1971_4
year: 1971
number: "4"
title: Lời giải các bài toán M28—M30; F41, F42, F44—F47
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 37
page_last: 44
page_labels: 35-42
tag: SHZH
lang: vi
source: kvant_digital
extraction: vision
content_sha256: cc19f4df0c91fea926cfd3b5f73eaff8ccaee069e0a7f2c778ab3a99a874b85a
prompt_sha256: 3ec6b8aabd9b98576af76503cd8a2902b9f5d18e01ee867dfb1228f59c6d52d8
translated_from: content/ru/1971/04/articles/10_resheniya-06ad36a2.md
source_content_sha256: 0e1c17b796bb8be52d46a94c5f226f916906f17a0db41766594bff265bc2448d
translation_model: gpt-5.6-terra
translation_run: vi-codex-2026-10-31
---

⟦folio 35⟧

LỜI GIẢI

Trong số này chúng tôi công bố lời giải các bài toán M28—M30

M28

(Tiếp tục lời giải, xem «Kvant» số 3, tr. 33). Nhắc lại rằng $f_1(n)$ chúng tôi đã kí hiệu là số nguyên nhỏ nhất lớn hơn hoặc bằng $\log_2 n$ (nó bằng số lần kiểm tra nhỏ nhất, sau đó có thểlo lần kiểm tra, sau đó có thể chọn m ộ t quả cầu phóng xạ trong $n$), còn $f_2(n)$ — số nhỏ nhất đối với việc $f_2(11) \geq 7$. Dưới đây chúng tôi sẽ chứng minh rất ngắn gọn rằng $f_2(6) \geq 5$;

Hình 1.

chọn m ộ t quả cầu phóng xạ trong $n$), còn $f_2(n)$ — số nhỏ nhất đối với việc $f_2(11) \geq 7$. Dưới đây chúng tôi sẽ chứng minh rất ngắn gọn rằng $f_2(6) \geq 5$;

⟦folio 36⟧

$f_2(8) \geq 6; \quad f_2(11) \geq 7; \quad f_2(10) \leq 6;$
$f_2(15) \leq 7; \quad f_2(21) \leq 8.$

Bạn đọc muốn chắc rằng mọi số ở hàng dưới của bảng ở trang 35 đều đúng thì ngoài ra sẽ phải chứng minh rằng $f_2(16) \geq 8;$
$f_2(22) \leq 8; \quad f_2(23) \geq 9; \quad f_2(25) \leq 9$ (quả thật, rõ ràng hàm $f_2$ không giảm, tức là nếu $m > n,$ thì $f_2(m) \geq f_2(n)$, vì vậy chỉ cần chỉ ra đúng những giá trị $n,$ mà $f_2(n+1)$ lớn hơn nghiêm ngặt $f_2(n).$

Trước khi chứng minh các bất đẳng thức đã hứa, hãy lưu ý rằng việc xác định chính xác giá trị $f_2(n)$ với mọi $n$ trong bài toán này, cũng như trong nhiều bài toán khác, không quá thú vị. Vấn đề là phương pháp tương ứng để xác định các viên bi, có vẻ như rất phức tạp. Mặt khác, có thể dễ dàng chỉ ra những thuật toán hoàn toàn đơn giản để xác định các viên bi, chỉ cần số phép kiểm tra lớn hơn $f_2(n),$ không nhiều. Chẳng hạn, nếu trước hết xác định một viên bi phóng xạ, rồi bỏ nó đi và chọn một viên khác trong số những viên còn lại, thì cần không quá $f_1(n)+f_1(n-1)$ phép kiểm tra, và, như không khó để chứng minh, hiệu $f_1(n)+f_1(n-1) - f_1(C_n^2)$ luôn không lớn hơn 2, do đó hiệu $f_1(n)+f_1(n-1)-f_2(n)$ cũng không lớn hơn 2. Trong những bài toán thực tế tương tự bài toán này, nếu bản thân số phép kiểm tra $k$ không quá nhỏ, một hoặc hai phép kiểm tra thừa rất có thể sẽ không đóng vai trò đặc biệt, miễn là phương pháp kiểm tra đơn giản hơn (chẳng hạn, với $n=15$ chúng ta đã không thể thu nhỏ trên một trang tạp chí một sơ đồ tương tự hình 1, và việc hiểu mô tả phương pháp kiểm tra trở nên không dễ dàng).

Dưới đây chúng tôi dùng các ký hiệu sau: dấu “-” có nghĩa là trong nhóm được kiểm tra không có viên bi phóng xạ, còn dấu “+” — có nghĩa là có.

Không thể xác định 2 viên bi trong số 6 bằng 4 phép kiểm tra

Giả sử lần kiểm tra đầu tiên là một nhóm gồm 6—q viên bi, trong đó $q=2, 3, 4$ hoặc 5. Khi đó kết quả “-” tương ứng với $C_q^2$ khả năng (cả hai viên bi phóng xạ nằm trong $q$ viên còn lại), kết quả “+” — với $(C_6^2-C_q^2)$ khả năng. Tuy nhiên, mỗi số này đều lớn hơn $2^3=8$.

Không thể xác định 2 viên bi trong số 8 bằng 5 phép kiểm tra

Nếu
$C_q^2 < 2^4 = 16$ và $C_8^2 - C_q^2 < 16,$ thì $q$ chỉ có thể bằng 6. Nếu kết quả là “-”, thì còn phải xác định 2 quả cầu trong 6 quả, điều này không thể làm được trong 4 lần kiểm tra.

Trong 6 lần kiểm tra không thể xác định 2 quả cầu trong 11 quả

Nếu $C_q^2 < 2^5 = 32$ và $C_{11}^2 - C_q^2 < 32,$ thì $q=8,$ nhưng $f_2(8) \geq 6$.

Trong 6 lần kiểm tra có thể xác định 2 quả cầu trong 10 quả

Lần kiểm tra đầu tiên — nhóm 4 quả cầu {1—4}. “-” trong 5 lần kiểm tra xác định 2 quả cầu trong 6 quả {5—10}. “+” kiểm tra {4—6}. “+-” trong 4 lần kiểm tra xác định 2 quả cầu trong 7 quả {1—3, 7—10}, nếu biết rằng {1—3} cho “+” (xem nửa bên trái hình 1). “++” kiểm tra {5, 6}. “++-” trong 3 lần kiểm tra xác định 1 quả cầu trong {1—3, 7—10}. “+++” trong 1 lần kiểm tra xác định 1 quả cầu trong {5, 6} và trong 2 lần — 1 quả trong {1—4}.

Trong 7 lần kiểm tra có thể xác định 2 quả cầu trong 15 quả

Lần kiểm tra đầu tiên {1—5}. “+” kiểm tra {5—9}. “+-” trong 5 lần kiểm tra xác định 2 quả cầu trong 10 quả {1—4, 10—15}, trong đó {1—4} cho “+” (xem 10 quả cầu, “+”). “++” kiểm tra {5}. “++-” trong 4 lần kiểm tra xác định 1 quả trong {1—4, 6—15}. “++-” trong 2 lần kiểm tra xác định 1 quả trong {1—4} và trong 2 lần kiểm tra — 1 quả trong {6—9}.

Trong 8 lần kiểm tra có thể xác định 2 quả cầu trong 21 quả

Lần kiểm tra đầu tiên {1—6}. Ngoài các lần kiểm tra được ghi trên hình và các lần kiểm tra tiếp theo, còn nêu “+-” trong 6 lần kiểm tra xác định 2 quả trong 15 quả {1—5, 12—21}, trong đó {1—5} cho “+” (xem 15 quả cầu, “+”). “++-” trong 2 lần kiểm tra xác định 1 quả trong {1—4} và trong 2 lần kiểm tra — 1 quả trong {8—11}.

⟦folio 37⟧

Hình 2.

M29

n đồng xu giống nhau nằm trên bàn, tạo thành một chuỗi khép kín (xem hình 2). Đồng xu cùng kích thước sẽ quay bao nhiêu vòng trong thời gian nó lăn một vòng dọc phía ngoài của toàn bộ chuỗi, như chỉ trên hình?

Đáp số sẽ thay đổi thế nào nếu đồng xu $M$ có bán kính khác bán kính của mỗi đồng xu trong chuỗi $k$ lần?

Lấy bán kính các đồng xu tạo thành chuỗi bằng đơn vị. Từ hình 3 thấy rằng trong thời gian đồng xu bán kính $k$ lăn theo cung $\alpha$ của đường tròn cố định bán kính 1, nó sẽ quay một góc $\alpha (1+1/k)$: trên hình này các bán kính $MA$ và $M'A''$ song song, $\angle A''M'B = \angle AOB = \alpha$

Hình 3.

và, vì các cung $\widehat{A'B}$ và $\widehat{AB}$ bằng nhau về độ dài, $\angle BMA' = \alpha/k$, do đó toàn bộ góc $\angle A''MA'$, mà đồng xu $M$ quay qua, bằng $\alpha + \alpha/k$ (đặc biệt, khi $k=1$ góc này bằng $2\alpha$).

Bây giờ ta tìm tổng các cung gồm những điểm của các đồng xu cố định mà đồng xu $M$ đã tiếp xúc khi lăn theo chuỗi. Gọi $O_1, O_2, \ldots, O_n$ là tâm các đồng xu của chuỗi. Tổng các cung nằm bên trong đa giác $O_1O_2 \ldots O_n$ bằng tổng các góc trong của nó, tức là $\pi (n-2)$. Vậy tổng các cung nằm bên ngoài đa giác bằng $2\pi n - \pi (n-2) = \pi (n+2)$. Cần trừ khỏi nó thêm

Hình 4, a.

Hình 4, b.

⟦trang 38⟧

Hình 5.
tổng các cung nằm trong chỗ lõm giữa hai đồng xu kề nhau mà $M$ không đi vào. Trong mỗi chỗ lõm trong số $n$ chỗ lõm, tổng của hai cung như vậy bằng $2\pi/3$ khi $k=1$ (hình 4a) và bằng $2\arccos \frac{1}{k+1}$ trong trường hợp tổng quát (hình 4, 6). Vậy tổng các cung mà đồng xu $M$ sẽ lăn theo bằng $\pi(n+2)-2\pi n/3$ (trong trường hợp tổng quát là $\pi(n+2)-2n\arccos \frac{1}{k+1}$). Để tìm số vòng quay cần tìm, cần nhân đại lượng này với 2 (trong trường hợp tổng quát, với $1+1/k$) rồi chia cho 2π.

Đáp số. $\left(\frac{n}{3} + 2\right)$
vòng khi $k=1$;
$\frac{k+1}{2k}\left(n - \frac{2}{\pi}n\arccos \frac{1}{k+1} + 2\right)$
vòng trong trường hợp tổng quát ($n \geqslant 3$).

Hình 6.

Trong lời giải này, chúng ta đã dùng (khi tính các “hao hụt” trong các chỗ lõm giữa các đồng xu) việc đồng xu $M$ lăn qua tất cả $n$ đồng xu liên tiếp, không ngoại lệ. Như bạn đọc A. Virovyansky từ Gorky, người đã gửi cho chúng tôi lời giải, đã nhận xét đúng, điều kiện này cần thiết để bài toán có một đáp số xác định. Đối với một chuỗi có “khe hở hẹp” (xem hình 5), dĩ nhiên không thể chỉ từ số $n$ mà biết được đồng xu $M$ sẽ quay bao nhiêu. Một điều kiện đủ, nhưng không cần thiết, để bài toán giải được là điều sau đây: đa giác $O_1$, $O_2...O_n$ lồi.

Hãy suy nghĩ cách tìm đáp số nếu thay vì một chuỗi khép kín chỉ có một đồng xu, hai đồng xu tiếp xúc nhau, và nói chung là một chuỗi không khép kín gồm $n$ đồng xu $O_1,...,O_n$, trong đó $O_k$ tiếp xúc với $O_{k+1}$, được bố trí sao cho $M$ có thể lăn đi rồi lăn lại qua tất cả các đồng xu theo thứ tự như sau:

$O_1$, $O_2,...,O_{n-1}$, $O_n$, $O_{n-1},...,O_1$ (hình 6) (Gợi ý. Chỉ cần trong các công thức viết ở trên khép $n$ thành $2n-2$.).

M30

Chứng minh rằng $N$ điểm trên mặt phẳng luôn có thể được phủ bởi một số hình tròn không giao nhau, tổng các đường kính của chúng nhỏ hơn $N$ và khoảng cách giữa bất kỳ hai hình tròn nào lớn hơn 1. (Khoảng cách giữa hai hình tròn được hiểu là khoảng cách giữa các điểm gần nhau nhất của chúng.)

Ta sẽ cần bổ đề hiển nhiên sau.

Nếu hai hình tròn có đường kính $a'_1$ và $a'_2$ giao nhau (có một điểm chung), thì chúng có thể được chứa trong một hình tròn có đường kính không lớn hơn $a'_1+a'_2$ (hình 7, a, 6).

Dựng một hình tròn tâm tại mỗi trong $N$ điểm đã cho, bán kính $a$ ($a$ lớn hơn $1/2$ một chút; giá trị chính xác của $a$ sẽ được chọn dưới đây). Nếu trong các hình tròn này có những hình tròn cắt nhau, thì, dùng bổ đề, thay hai hình tròn cắt nhau nào đó (bất kỳ hai hình nào) bằng một hình tròn bao phủ chúng. Nếu trong các hình tròn nhận được vẫn còn những hình tròn cắt nhau, lại dùng bổ đề, v.v. Giả sử nói chung có một hệ nào đó gồm các hình tròn mà: 1) bao phủ tất cả các điểm đã cho cùng với các hình tròn bán kính $a$ tâm tại các điểm ấy và 2) có tổng các đường kính không lớn hơn $N \cdot 2a$. Khi đó nếu trong số chúng có các hình tròn cắt nhau, thì ta có thể

⟦folio 39⟧

dùng bổ đề và dựng một hệ mới gồm ít hình tròn hơn, thỏa mãn các điều kiện 1), 2) như cũ, và tiếp tục như vậy cho đến khi nhận được một hệ gồm $k$ hình tròn mà không có hai hình nào cắt nhau.

Bây giờ giảm bán kính của mỗi trong $k$ hình tròn này đi một lượng $b$, giữ nguyên tâm của chúng ($b$ lớn hơn $1/2$ và nhỏ hơn $a$; giá trị chính xác của $b$ được chỉ ra dưới đây). Khi đó $k$ hình tròn nhận được:

1) chứa tất cả các điểm đã cho,
2) có tổng các đường kính không lớn hơn $N \cdot 2a - k \cdot 2b \leq 2Na - 2b$,
3) cách nhau không ít hơn $2b$.

Rõ ràng, nếu chọn $a$ và $b$ sao cho các bất đẳng thức $b < a$; $2Na - 2b < N$, $2b > 1$ được thỏa mãn, thì mọi yêu cầu của bài toán sẽ được đáp ứng. Chẳng hạn, ngay từ đầu chỉ cần lấy $a = \frac{1}{2} + \frac{1}{2N}$ và $b = \frac{1}{2} + \frac{1}{4N}$.

Dĩ nhiên, các $a$ và $b$ như vậy chỉ cần thiết vì trong điều kiện đòi hỏi thỏa các bất đẳng thức nghiêm ngặt: tổng các đường kính nhỏ hơn $N$, khoảng cách giữa các hình tròn lớn hơn 1. Nếu lấy đơn giản $a = b = 1/2$, thì sẽ chứng minh được rằng $N$ điểm của chúng ta có thể được phủ (với một $k$ nào đó) bởi các hình tròn sao cho khoảng cách giữa các hình tròn không nhỏ hơn 1, còn tổng các đường kính của chúng không lớn hơn $N - k$. Lưu ý rằng vì mệnh đề này được chứng minh cho mọi đơn vị đo, nên (chọn đơn vị này nhỏ hơn một chút) từ đó có thể

Trong số này chúng tôi công bố lời giải các bài toán Ф41—Ф47 *)

Ф41

Độ rọi vào đêm trăng tròn nhỏ hơn độ rọi vào ngày nắng bao nhiêu lần? Độ cao của Mặt Trăng và Mặt Trời trên đường chân trời là như nhau. Coi rằng bán cầu được chiếu sáng của Mặt Trăng tán xạ ánh sáng đều vào không gian.

Lấy bán kính Mặt Trăng bằng 2000 km, còn khoảng cách từ Mặt Trăng đến Mặt Trời là 400 000 km.

Vì khoảng cách từ Mặt Trời đến Trái Đất và đến Mặt Trăng lớn so với đường kính Mặt Trời, nên trong tính toán ta có thể coi Mặt Trời là một nguồn sáng điểm, phát đều năng lượng ánh sáng vào mọi phía. Giả sử cường độ sáng của nguồn này, tức là năng lượng do Mặt Trời phát ra trong một đơn vị góc khối trong 1 giây, bằng $I$. Khi đó độ rọi của bề mặt Trái Đất vào một ngày nắng sáng sẽ bằng $E_c = \frac{1}{L^2}$, trong đó $L$ là khoảng cách từ Mặt Trời đến Trái Đất.

Mặt Trăng chiếu sáng Trái Đất bằng ánh sáng Mặt Trời phản xạ. Vì khoảng cách từ Mặt Trời đến Mặt Trăng có thể coi bằng khoảng cách từ Mặt Trời

*) Lời giải bài toán Ф43 sẽ được công bố trong “Квант” số 5

⟦folio 40⟧

đến Trái Đất, nên độ rọi của bề mặt Mặt Trăng vào đêm trăng tròn cũng bằng $\frac{I}{L^2}$. Toàn bộ bề mặt Mặt Trăng nhận năng lượng ánh sáng

$$W = \frac{I}{L^2} \pi r^2.$$

Vì năng lượng này sau đó được tán xạ đều theo mọi hướng trên “bán cầu”, nên trong một đơn vị góc khối phát ra năng lượng

$$I_\pi = \frac{I \pi r^2}{L^2 \cdot 2\pi}$$

(góc khối toàn phần bằng 4 π, một nửa là 2π). Bây giờ dễ dàng tìm được độ rọi của bề mặt Trái Đất vào đêm trăng tròn. Coi Mặt Trăng là một nguồn điểm có cường độ sáng $I_\pi$, ta được

$$E_\pi = \frac{I r^2}{2 L^2 l^2},$$

trong đó $l$ là khoảng cách từ Mặt Trăng đến Trái Đất.

Tỉ số độ rọi của Trái Đất vào ngày trăng bán nguyệt và vào một ngày nắng là

$$\frac{E_\pi}{E_c} = \frac{1}{2} \left( \frac{r}{l} \right)^2 = \frac{1}{80 000}.$$

Ф42

Một sợi dây được vắt qua một ròng rọc, trong đó một phần dây nằm trên bàn, còn một phần — trên sàn. Sau khi thả dây, nó bắt đầu chuyển động. Hãy tìm vận tốc chuyển động đều ổn định của dây. Chiều cao của bàn bằng $h$ (hình 8).

Hình 8.

Dễ nhất là giải bài toán bằng cách sử dụng định luật II Newton.

Trong thời gian $\Delta t$, một đoạn dây dài $\Delta l = v \Delta t$ được cuốn vào chuyển động. Nếu khối lượng của một đơn vị chiều dài dây được ký hiệu là $\mu$, thì khối lượng của đoạn dây $\Delta l$ bằng $\Delta m = \mu \Delta l = \mu v \Delta t$. Trong thời gian $\Delta t$, đoạn dây có khối lượng $\Delta m$ nhận được xung lượng (lượng chuyển động) bằng $\Delta mv = \mu v^2 \Delta t$. Rõ ràng, sự thay đổi xung lượng này xuất hiện nhờ hiệu các trọng lực tác dụng lên phần bên trái và bên phải của dây. Hiệu này bằng $mgh$.

Theo định luật II Newton, ta có thể viết

$$\mu v^2 \Delta t = \mu gh \Delta t.$$

Suy ra

$$v = \sqrt{gh}.$$

Lời giải đúng được gửi bởi H. Ezhov từ Odessa và A. Viktorov từ Tula.

Ф44

Hai con delfin bơi về phía nhau. Một trong chúng phát ra âm có tần số $\omega$. Con delfin kia nghe thấy âm có tần số bao nhiêu, nếu vận tốc của các delfin đối với nước bằng nhau và bằng $v$? Vận tốc âm trong nước là $u$.

Dùng kết quả thu được trong bài “Hiệu ứng Doppler”, ta thấy rằng con delfin thứ hai sẽ nghe âm có tần số

$$\omega_2 = \omega \frac{u + v}{u - v}.$$

Thật vậy, vì con delfin thứ nhất chuyển động, nên tần số của các sóng âm mà một máy thu đứng yên ở phía trước nhận được bằng

$$\omega_1 = \frac{\omega}{1 - \frac{v}{u}} = \frac{\omega u}{u - v}.$$

⟦folio 41⟧

Hình 9.

Nhờ chuyển động của con delfin thứ hai, nó nghe âm có tần số

$$\omega_2 = \omega_1 \left( 1 + \frac{v}{u} \right) = \omega_1 \frac{u + v}{u} = \omega \frac{u + v}{u - v}.$$

Ф45

Một tụ điện hình cầu, được lấp đầy bằng điện môi và tích điện đến một hiệu điện thế nào đó, phóng điện qua chất điện môi của nó. Từ trường của các dòng điện phóng trong không gian giữa các mặt cầu sẽ như thế nào?

Ta tách trong chất cách điện một “dây dẫn” hình nón hẹp. Rõ ràng rằng đối với bất kỳ điểm $A$ nào (hình 9), ta luôn có thể tìm được một “dây dẫn” hình nón khác sao cho dòng điện chạy qua nó tạo ra tại điểm $A$ một trường có phương trùng với phương của trường do dòng điện trong “dây dẫn” đã tách ra tạo nên và có chiều ngược lại. Điều đó có nghĩa là từ trường của các dòng điện phóng giữa các mặt cầu bằng không.

Ф46

Một khối lập phương rơi từ độ cao 1 m xuống một quả bóng, rồi sau đó nảy lên gần đến 1 m. Quả bóng nảy lên đến độ cao nào?

Quả bóng sẽ nảy lên đến độ cao nào nếu một quả bóng hoàn toàn giống nó rơi từ độ cao 1 m xuống nó?

Vào lúc khối lập phương rời khỏi quả bóng, vận tốc của khối lập phương bằng vận tốc của điểm trên cùng của quả bóng. Ký hiệu vận tốc này là $v$. Sau đó khối lập phương chuyển động tự do. Vì vậy, viết định luật bảo toàn năng lượng cho nó

$$\frac{Mv^2}{2} = Mgh$$

($h — высота подъема$), ta được $v = \sqrt{2gh}$.

Vận tốc của điểm dưới cùng của quả bóng vào lúc khối lập phương rời khỏi nó bằng không, do đó vận tốc của tâm quả bóng bằng $\frac{v}{2}$. Viết định luật bảo toàn năng lượng cho quả bóng

$$\frac{m \left( \frac{v}{2} \right)^2}{2} = mgh_1$$

trong đó $h_1$ là độ cao nâng lên của khối lập phương, ta được

$$h_1 = \frac{h}{4} \approx 25 \text{ cm}$$

Hãy tự xét xem sự va chạm của các quả bóng sẽ diễn ra như thế nào.

⟦folio 42⟧

Nếu khí lí tưởng thực hiện quá trình ABC (hình 10), thì nó được cung cấp một lượng nhiệt Q. Lượng nhiệt nào được cung cấp cho khí trong quá trình ADC?

Nhiệt được cung cấp cho khí dùng để tăng nội năng W của nó và thực hiện công khi khí nở ra. Vì trạng thái đầu và cuối, do đó cả nhiệt độ của khí, đều như nhau trong cả hai quá trình, nên độ biến thiên nội năng của khí cũng như nhau. Còn công thực hiện khi khí nở ra thì trong trường hợp thứ nhất bằng $P_2(V_2-V_1)$, còn trong trường hợp thứ hai: $P_1(V_2-V_1)$.

Từ định luật bảo toàn năng lượng suy ra rằng

$$Q = W + P_2(V_2-V_1)$$

và

$$Q_1 = W + P_1(V_2-V_1),$$

trong đó $Q_1$ — lượng nhiệt trong quá trình

$$A \rightarrow D \rightarrow C.$$

Từ các phương trình này dễ dàng tìm được rằng

$$Q_1 = Q - P_2(V_2-V_1) + P_1(V_2-V_1) = Q - (P_2-P_1)(V_2-V_1).$$

Đại lượng $(P_2-P_1)(V_2-V_1)$ về trị số bằng diện tích hình chữ nhật ABCD. Vì vậy kết quả của chúng ta khá tự nhiên.

Hiển nhiên, hiệu $Q-Q_1$ phải bằng hiệu các công thực hiện khi khí nở ra, mà công khi khí nở ra về trị số bằng diện tích hình được tạo bởi đồ thị sự phụ thuộc của $P$ vào $V$ và trục $V$.

Lời giải đúng được A. Rozovin từ Izhevsk gửi đến.

I. Sh. Slobodetsky
