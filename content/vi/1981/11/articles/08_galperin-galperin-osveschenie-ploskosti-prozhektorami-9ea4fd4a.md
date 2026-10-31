---
id: 1981-11-galperin-galperin-osveschenie-ploskosti-prozhektorami-9ea4fd4a
issue: kvant_1981_11
year: 1981
number: "11"
title: Chiếu sáng máy bay bằng đèn pha
authors:
  - Гальперин В.
  - Гальперин Г. А.
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 30
page_last: 32
page_labels: 28-30
tag: ESJY
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 2cae9d9286e32fa92bc5cbd70c00fa38fcecd15cf3f6bfd1294c5d58815cbbce
prompt_sha256: draft-1
translated_from: content/ru/1981/11/articles/08_galperin-galperin-osveschenie-ploskosti-prozhektorami-9ea4fd4a.md
source_content_sha256: 68d7dfcd82a8c35d498523f7f6dd46d07ca5d088c5cdd9372582fe989e4adb2a
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 28⟧

V. Galperin, G. Galperin

Che phủ máy bay bằng máy chiếu

Thú vị và khó bài toán M545, lời giải mà lưu ý này liên quan đến, trong việc xây dựng câu hỏi và phương pháp lời giải là điển hình cho hình học tổ hợp - một phần hình học xử lý bài toán với các phân vùng, lớp phủ, gói các hình.
Chúng ta hãy nhớ lại công thức của nó:

Có n điểm cho trên mặt phẳng. Cần đặt n máy chiếu tại các điểm này, mỗi máy chiếu một góc có độ lớn $\frac{360^\circ}{n}$ để chiếu sáng toàn bộ mặt phẳng. Chứng minh rằng điều này có thể xảy ra với bất kỳ vị trí nào của những điểm này nếu a) n=3; 6) n=4; c) n - số tự nhiên bất kỳ (trong trường hợp a) - c) hình chiếu quay được); d) Bây giờ hãy để các máy chiếu chiếu sáng các góc $a_1, a_2, \dots, a_n$ ($a_1 + a_2 + \dots + a_n = 360^\circ$) và bố trí tại một điểm sao cho chúng chiếu sáng toàn bộ mặt phẳng. Chứng minh rằng có thể chuyển*) một trong n máy chiếu tới mỗi điểm trong số này sao cho toàn bộ mặt phẳng vẫn được chiếu sáng.

Lịch sử của bài toán này khá thú vị. Trường hợp đặc biệt đơn giản nhất 6) đã được trình bày tại Cuộc Tối ưu hóa Toán học Toàn Liên minh đầu tiên vào năm 1967. Chính tại đó, người thứ hai trong số các tác giả của ghi chú này đã gặp cô ấy (lúc đó anh ấy vẫn còn là một cậu học sinh). Vài năm sau ông tìm thấy bằng chứng về nhiều hơn nữa

*) Điều này có nghĩa là các máy chiếu có thể được di chuyển song song nhưng không thể xoay!

Bây giờ chúng ta hãy xem xét các góc đối xứng với các góc này đối với điểm O. Hình 2 cho thấy cách điều khiển một máy chiếu đặt tại điểm $M_1$ sao cho nó chiếu sáng góc được tô màu đỏ. Tương tự, máy chiếu tại các điểm $M_2$ và $M_3$ có ​​thể được định hướng sao cho chiếu sáng các góc “của chúng”.

Ý tưởng tương tự - chia mặt phẳng thành nhiều phần. Để mỗi chúng có thể được chiếu sáng bằng nhóm máy chiếu riêng, điều này có thể được áp dụng trong trường hợp c).

Để làm được điều này chỉ cần chứng minh hai khẳng định sau là đủ.

Phát biểu 1. Cho có k máy chiếu nằm bên trong một góc có độ lớn $\alpha = k \frac{2\pi}{n}$, trong đó $k \leqslant \frac{n}{2}$. Sau đó, chúng có thể được xoay sao cho chúng cùng chiếu sáng toàn bộ góc đối xứng với góc đã cho so với đỉnh của nó (Hình 3).

Để chứng minh phát biểu này bằng chỉ thị trên k, ta có thể sử dụng bổ đề số học sau đây. Nếu $s_1, s_2, \dots, s_k$ là số nguyên không âm và $s_1 \geqslant 1$,

Hình 1.
Hình 2.

⟦folio 29⟧

$s_k \geq 1$ và $s_1 + s_2 + \dots + s_k = k$, thì có $m < k$ mà $s_1 + \dots + s_m = m$ (tức là, $s_{m+1} + \dots + s_k = k - m$).

Cuối cùng, vẫn còn phải chứng minh thực tế khá đều đặn này - việc thực hiện điều này một cách riêng biệt đối với $n$ chẵn và lẻ sẽ dễ dàng hơn.

Phát biểu 2. Nếu một mặt phẳng có $n$ điểm $A_1, A_2, \dots, A_n$, thì nó có thể được chia thành hai nửa mặt phẳng chứa $n/2$ mỗi điểm, nếu $n$ chẵn hoặc thành ba góc có cùng một đỉnh và độ lớn $k_1, k_2, \frac{2\pi}{n}, k_3, \frac{2\pi}{n}$, trong đó $k_1 + k_2 + k_3 = n$ và $k_i < n/2$ ($i=1, 2, 3$), mỗi góc chứa bởi $k_i$ điểm nếu $n$ lẻ.

Bài tập 1. Chứng minh khẳng định 1, bổ đề và khẳng định 2.

Sau đó, theo Tuyên bố 1, chúng ta dùng các máy chiếu tương ứng chiếu sáng các góc đối xứng với đỉnh chung của chúng theo góc mà chúng nằm và toàn bộ mặt phẳng được chiếu sáng.

Thuật toán cải tiến

Hãy phác thảo ý tưởng về điểm lời giải. G). Chúng ta hãy sắp xếp các máy chiếu tại các điểm $M_1, M_2, \dots, M_n$ này một cách tùy ý. Nếu toàn bộ mặt phẳng không được chiếu sáng, chúng tôi sẽ trình bày một phương pháp sắp xếp máy chiếu “cải tiến” khác (trong trường hợp này, “chất lượng” của việc sắp xếp sẽ được đánh giá bằng một hàm số nhất định $f$). Vì chỉ có một số hữu hạn cách sắp xếp máy chiếu tại các điểm $M_1, M_2, \dots, M_n$ (bằng $n!$), lấy cách sắp xếp sao cho giá trị của hàm $f$ là lớn nhất, chúng ta sẽ tự động chiếu sáng toàn bộ mặt phẳng: thật vậy, nếu không phải toàn bộ mặt phẳng được chiếu sáng, chúng ta vẫn có thể “cải thiện” cách sắp xếp, từ đó thu được một mâu thuẫn.

Hãy thực hiện kế hoạch này. Bây giờ các máy chiếu là bất kỳ góc $a_i$ nào có một đỉnh chung $O$, $0 < a_i < \pi$, $a_1 + a_2 + \dots + a_n = 2\pi$ và mỗi máy chiếu chiếu sáng phần bên trong của một lồi nhất định $n$-gon $A_1A_2\dots A_n$ (Hình 4), $A_i \overrightarrow{OA_{i+1}} = a_i$. Chúng ta hãy thả các đường vuông góc $OH_i$ từ điểm $O$ đến các cạnh của đa giác (hoặc phần mở rộng của chúng); hãy để $|OH_i| = h_i$.

Xét các vectơ $\vec{e}_i = \frac{1}{h_i} \overrightarrow{OH_i}$. Rõ ràng là $|\vec{e}_i| = \frac{1}{h_i}$ (Hình 5).

Việc sắp xếp các máy chiếu tại các điểm $M_1, M_2, \dots, M_n$ tương ứng với việc sắp xếp các vectơ $\vec{e}_1, \vec{e}_2, \dots, \vec{e}_n$ tại các điểm này (dường như chúng ta gắn vectơ $\vec{e}_i$ vào máy chiếu $a_i$ và sắp xếp lại chúng lại với nhau thành một tổng thể duy nhất).

Thực tế hình học duy nhất mà chúng ta cần trong tương lai và điều đó “biện minh”, thoạt nhìn, việc lựa chọn vectơ $\vec{e}_i$, là như sau:

Bổ đề. Để máy chiếu $a_p$ đặt tại điểm $M$ chiếu sáng điểm $N$, nhưng máy chiếu $a_q$ thì không. Sau đó $\overrightarrow{MN} \cdot \vec{e}_p > \overrightarrow{MN} \cdot \vec{e}_q$.

Bằng chứng. Hãy để $\overrightarrow{MN} = \vec{v}$. Chúng ta hãy vẽ vectơ $\overrightarrow{OP} = \vec{v}$ từ điểm $O$ (Hình 6). Tia [OP] cắt cạnh thứ $p$ của đa giác $A_1A_2\dots A_n$ tại một điểm nào đó $K$, nhưng không cắt cạnh thứ $q$, khoảng cách của máy chiếu $s_k \geq 1$ và $s_1 + s_2 + \dots + s_k = k$ thì tồn tại $m < k$ mà $s_1 + \dots + s_m = m$ (tức là $s_{m+1} + \dots + s_k = k - m$).

Cuối cùng, vẫn còn phải chứng minh thực tế khá thường xuyên này - việc thực hiện điều này một cách riêng biệt sẽ dễ dàng hơn đối với $n$ chẵn và lẻ.

Phát biểu 2. Nếu một mặt phẳng được cho $n$ điểm $A_1, A_2, \dots, A_n$, thì nó có thể được chia thành hai nửa mặt phẳng chứa $n/2$ mỗi điểm, nếu $n$ chẵn hoặc thành ba góc có cùng một đỉnh và độ lớn $k_1, k_2, \frac{2\pi}{n}, k_3, \frac{2\pi}{n}$, trong đó $k_1 + k_2 + k_3 = n$ và $k_i < n/2$ ($i=1, 2, 3$), mỗi góc chiếu sáng phần bên trong của một lồi nhất định $n$-gon $A_1A_2\dots A_n$ (Hình 4), $A_i \overrightarrow{OA_{i+1}} = a_i$. Chúng ta hãy thả các đường vuông góc $OH_i$ từ điểm $O$ đến các cạnh của đa giác (hoặc phần mở rộng của chúng); hãy để $|OH_i| = h_i$.

Xét các vectơ $\vec{e}_i = \frac{1}{h_i} \overrightarrow{OH_i}$. Rõ ràng là $|\vec{e}_i| = \frac{1}{h_i}$ (Hình 5).

Hình 6.

máy chiếu $a_p$ chiếu sáng điểm $N$, nhưng máy chiếu $a_q$ không chiếu sáng.

Có hai khả năng: 1) tia [OP] không cắt đường thẳng mà cạnh thứ $q$ nằm trên đó và 2) tia [OP] cắt đường thẳng này tại một điểm nào đó $R$.

Trong trường hợp đầu tiên, nó rất quan trọng, vì $\vec{v} \cdot \vec{e}_p > 0$ và $\vec{v} \cdot \vec{e}_q \leq 0$.

Trong trường hợp thứ hai, nó rất quan trọng, vì $\vec{v} \cdot \vec{e}_p > 0$ và $\vec{v} \cdot \vec{e}_q \leq 0$.

Tia [OP] cắt cạnh thứ $p$ của đa giác $A_1A_2\dots A_n$ tại một điểm nào đó $K$, nhưng không cắt cạnh thứ $q$, khoảng cách của máy chiếu $s_k \geq 1$ và $s_1 + s_2 + \dots + s_k = k$ thì có $m < k$, sao cho chúng được chiếu sáng bởi các điểm $n/2$, nếu $n$ chẵn hoặc chia thành ba góc có cùng đỉnh và độ lớn $k_1, k_2, \frac{2\pi}{n}, k_3, \frac{2\pi}{n}$, trong đó $k_1 + k_2 + k_3 = n$ và $k_i < n/2$ ($i=1, 2, 3$), mỗi góc chiếu sáng phần bên trong của một lồi nhất định $n$-gon $A_1A_2\dots A_n$ (Hình 4), $A_i \overrightarrow{OA_{i+1}} = a_i$. Chúng ta hãy thả các đường vuông góc $OH_i$ từ điểm $O$ đến các cạnh của đa giác (hoặc phần mở rộng của chúng); hãy $|OH_i| = h_i$.

Xét các vectơ $\vec{e}_i = \frac{1}{h_i} \overrightarrow{OH_i}$. Rõ ràng là $|\vec{e}_i| = \frac{1}{h_i}$ (Hình 5).

⟦folio 30⟧

Bây giờ chúng ta giới thiệu các đại lượng $f_{\sigma}(N)$, phụ thuộc vào điểm $N$ của mặt phẳng và cách bố trí $\sigma$ của các hình chiếu tại các điểm $M_1, M_2, \dots, M_n$, như sau:

$$f_{\sigma}(N) = \overrightarrow{M_1} N \cdot \overrightarrow{e_{\sigma(1)}} + \overrightarrow{M_2} N \cdot \overrightarrow{e_{\sigma(2)}} + \dots + \overrightarrow{M_n} N \cdot \overrightarrow{e_{\sigma(n)}}$$

(1) ($\sigma(i)$ là số lượng máy chiếu đặt tại điểm $M_i$).

Tuyên bố chính sau đây cho thấy hàm $f_{\sigma}(N)$ có thể mô tả “chất lượng” của sự sắp xếp.

Phát biểu 3. Nếu điểm $N$ trong cách sắp xếp $\sigma$ không được chiếu sáng thì có cách sắp xếp các máy chiếu m sao cho $f_{\tau}(N) > f_{\sigma}(N)$.

Bằng chứng. Trước tiên chúng ta hãy trình bày một thuật toán cho phép chúng ta “cải thiện” sự sắp xếp $\sigma$.

Đặt máy chiếu $\alpha_i$ tại điểm $M_i$. Để máy chiếu $\alpha_1$ đứng ở điểm $M_1$ không chiếu sáng điểm $N$. Chúng ta hãy tháo nó ra một lúc và đến điểm $M_1$ chúng ta sẽ vượt qua máy chiếu, sau đó sẽ chiếu sáng lại điểm $N$.

Bài tập 2. Chứng minh rằng có một máy chiếu như vậy.

Hãy để đây là máy chiếu $\alpha_2$. Bây giờ tại điểm $M_2$, nơi đặt máy chiếu $\alpha_2$, không có gì cả. Hãy đặt một trong những máy chiếu còn lại $n-1$ tại điểm này, sau đó sẽ chiếu sáng điểm $N$. Hãy để nó là một máy chiếu $\alpha_3$. Bây giờ chúng ta đặt máy chiếu $\alpha_4$ tại điểm $M_3$, sau đó sẽ được chiếu sáng bởi $N$, tại điểm $M_4$ đặt máy chiếu $\alpha_5$, v.v. cho đến khi hình thành một chu trình (Hình 7): điều này có nghĩa là tại điểm $M_k$ máy chiếu $\alpha_{k+1}$ giao nhau, tại điểm $M_{k+1}$ — máy chiếu $\alpha_{k+2}$, tới điểm $s$ — máy chiếu $\alpha_k$ ($s > k$). Chúng tôi sẽ trả lại các máy chiếu $\alpha_1, \alpha_2, \dots, \alpha_{k-1}$ về vị trí cũ (đến các điểm có cùng số). Do đó, điểm $N$ sẽ được chiếu sáng bởi mỗi máy chiếu $\alpha_k, \alpha_{k+1}, \dots, \alpha_s$ (vì điểm $N$ không được chiếu sáng, $s \geq k+1$).

Hãy xem con số $f(N)$ đã thay đổi như thế nào nhé. Các số hạng khác ngoài $k, k+1, \dots, s$ trong tổng (1) không thay đổi. Và từ bổ đề, suy ra rằng tất cả các số hạng có số $k, k+1, \dots, s$ đều tăng sau khi sắp xếp lại được chỉ định.

Vậy khẳng định 3 đã được chứng minh. Đúng, các giá trị $f_{\sigma}$ chưa thể được sử dụng trực tiếp để đánh giá “chất lượng” của sự sắp xếp $\sigma$ - xét cho cùng, nó phụ thuộc vào điểm $N$. Đây là nơi điều tuyệt vời tiết kiệm.

Phát biểu 4. Đối với hai điểm $N_1$ và $N_2$ bất kỳ, sự khác biệt $f_{\sigma}(N_1) - f_{\sigma}(N_2)$ không phụ thuộc vào cách sắp xếp máy chiếu.

Bằng chứng. $f_{\sigma}(N_1) - f_{\sigma}(N_2) = \sum_{i=1}^{n} \overrightarrow{M_{\sigma(i)}} N_1 \cdot \overrightarrow{e_{\sigma(i)}} - \sum_{i=1}^{n} \overrightarrow{M_{\sigma(i)}} N_2 \cdot \overrightarrow{e_{\sigma(i)}} = \sum_{i=1}^{n} (\overrightarrow{M_{\sigma(i)}} N_1 - \overrightarrow{M_{\sigma(i)}} N_2) \cdot \overrightarrow{e_{\sigma(i)}} = \sum_{i=1}^{n} \overrightarrow{N_2} N_1 \cdot \overrightarrow{e_{\sigma(i)}} = c$.

Tổng $\sum_{i=1}^{n} \overrightarrow{e_{\sigma(i)}}$ là một vectơ không đổi (không phụ thuộc vào cách sắp xếp), $N_2 N_1$ cũng là một vectơ cố định nên số $c$ không phụ thuộc vào sự sắp xếp của các phép chiếu, đây là điều cần chứng minh.

Điều này có nghĩa là hàm $f_{\sigma}(N)$ có thể được thay thế bằng hàm $f_{\sigma} = f_{\sigma}(N) + \overrightarrow{N_0} \cdot \overrightarrow{e_{\sigma(i)}} = \sum_{i=1}^{n} \overrightarrow{M_{\sigma(i)}} N_0 \cdot \overrightarrow{e_{\sigma(i)}}$, trong đó $N_0$ là một điểm cố định tùy ý của mặt phẳng.

Số $f_{\sigma}$ không còn phụ thuộc vào điểm $N$ và sẽ tăng theo mỗi hoán vị mà chúng tôi đã mô tả.

Do đó, ý tưởng đã được hiện thực hóa đầy đủ: một “chức năng chất lượng” đã được tìm thấy chỉ phụ thuộc vào sự sắp xếp của các máy chiếu và nó đã được chỉ ra cách tăng giá trị của nó nếu một số điểm không được chiếu sáng. Vì trong một số cách sắp xếp $\omega$ số $f_{\omega}$ là tối đa, với cách sắp xếp $\omega$ toàn bộ mặt phẳng được chiếu sáng.

Bài tập 3. Tiến hành chứng minh các biến thể không gian bài toán về máy chiếu.

a) Tại 8 điểm bất kỳ trong không gian, bạn có thể đặt các cạnh (góc tam diện có góc phẳng vuông góc (xem Hình 8, a)) sao cho chúng bao phủ toàn bộ không gian.

b) Cho một khối đa diện lồi có các mặt $\Gamma_1, \Gamma_2, \dots, \Gamma_n$ và một điểm $O$ bên trong nó, cũng như $n$ điểm $M_1, M_2, \dots, M_n$, được cho trong không gian. Mỗi mặt $\Gamma_i$ xác định một góc đa diện $\alpha_i$ với đỉnh tại $O$. Tại điểm $O$ có $n$ máy chiếu và máy chiếu thứ $i$th $1 \leq i \leq n$ chiếu sáng góc đa diện $\alpha_i$ (do đó toàn bộ không gian được chiếu sáng hoàn toàn (Hình 8, b)). Chứng minh rằng có thể di chuyển máy chiếu đến các điểm $M_1, M_2, \dots, M_n$ sao cho toàn bộ không gian vẫn được chiếu sáng.
