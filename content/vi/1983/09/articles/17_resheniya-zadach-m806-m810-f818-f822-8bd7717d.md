---
id: 1983-9-resheniya-zadach-m806-m810-f818-f822-8bd7717d
issue: kvant_1983_9
year: 1983
number: "9"
title: Lời giải bài toán M806—M810; F818—F822
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 44
page_last: 49
page_labels: 42-47
tag: 8MIU
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 6571fdab2863c2eab5b6a6d45be03c96a933f7121e2d1e62fa07ad4ed67fe642
prompt_sha256: draft-1
translated_from: content/ru/1983/09/articles/17_resheniya-zadach-m806-m810-f818-f822-8bd7717d.md
source_content_sha256: c508927e056f9fe82d7610619c6fd3114fb22ae9d7b865ac4bdf0a2f81aa8e2f
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 42⟧

Problems M824, M825 and R833—R837 were proposed at the final round of the All-Union School Olympiad.

E. I. Butikov

P835. A heater was placed in a glass of water and the water temperature registered as a function of time (see table).

1) By how many degrees will the water cool in 1 min, if the heater is turned off when the temperature is $t_1 = 50$ °C?

2) Will the water boil, if the heater is turned on long enough? The power of the heater is assumed constant.

| Time, $\tau$ min | 0 | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Temperature, $t$ °C | 20 | 26.2 | 31.8 | 36.8 | 41.4 | 45.6 | 49.3 | 52.7 | 55.8 | 58.5 | 61.1 |

A. R. Zilberman

P836. Bản A của tụ điện dẹt đứng yên, bản B được nối bằng lò xo vào thành và có thể chuyển động, vẫn song song với A (xem hình 4). Sau khi bật công tắc K, tấm B bắt đầu chuyển động và dừng lại ở vị trí cân bằng mới, khoảng cách giữa các tấm giảm đi $\alpha_1 = 10\%$. Khoảng cách cân bằng giữa các bản sẽ thay đổi như thế nào nếu công tắc K chỉ được bật trong một khoảng thời gian ngắn? Người ta cho rằng tấm B không có đủ thời gian để di chuyển đáng chú ý trong khoảng thời gian này.

A. I. Buzdin

P837. Máy đo gió laser được sử dụng để đo vận tốc của các hạt di chuyển qua hai chùm ánh sáng laser kết hợp giao nhau (xem hình 5). Ánh sáng phản chiếu bởi các hạt được ghi lại bởi quang phần tử $\Phi$ và được chuyển thành xung điện. Các hạt chuyển động vuông góc với phân giác của góc $\alpha = 60^\circ$ giữa các dầm. Một hạt đã di chuyển theo hướng nào, nếu tín hiệu định kỳ có tần số $v = 320$ kHz được ghi lại (đối với bước sóng chùm tia laze $\lambda = 0.63$ mkm).

V. V. Mojaev

Lời giải bài toán

M806—M810; F818—F822

M806. a) Chứng minh rằng nếu $a_1 + \frac{a_2}{2} + \frac{a_3}{3} + \ldots + \frac{a_n}{n} = 0$ thì đa thức $a_n x^{n-1} + a_{n-1} x^{n-2} + \ldots + a_2 x + a_1$ có nghiệm nằm trong khoảng từ 0 đến 1.

b) Chứng minh rằng nếu với một số $p > 0$

$$\frac{a_1}{p+1} + \frac{a_2}{p+2} + \frac{a_3}{p+3} + \ldots + \frac{a_n}{p+n} = 0,$$

thì đa thức này cũng có nghiệm nằm trong khoảng từ 0 đến 1.

Trước tiên, chúng ta hãy chứng minh mệnh đề sau: nếu một hàm khả vi $f(x)$ biến thành một trường tại các điểm $x = 0$ và $x = 1$, thì đạo hàm của nó phải biến thành một trường tại một điểm bên trong nào đó từ 0 và do đó, được lấy tại điểm $x_0$ nằm bên trong đoạn thẳng [0; 1].

Điều này là hiển nhiên nếu hàm $f(x)$ cũng thực tế bằng 0 trên khoảng [0; 1]. Ngược lại, chúng ta sẽ xem xét các điểm mà tại đó nó có giá trị lớn nhất và nhỏ nhất trên đoạn này. (Những điểm như vậy tồn tại theo định lý Weierstrass - xem sách giáo khoa “Đại số và Giải tích 9-10”, đoạn 28 - hoặc hàm $f(x)$, khả vi, là liên tục.) Tuy nhiên, các giá trị này phải bằng 0 và do đó, được lấy tại điểm $x_0$ nằm bên trong đoạn [0; 1].

Do đó, $x_0$ là điểm cực trị của hàm $f(x)$ trên khoảng [0; 1] [1, và theo định lý Fermat (“Đại số và sự khởi đầu của phân tích 9-10”, đoạn 26) $f'(x_0) = 0$.

Chúng ta hãy sử dụng phát biểu đã được chứng minh cho lời giải bài toán.

a) Xét hàm $f(x) = a_1 x + \frac{a_2}{2} x^2 + \ldots + \frac{a_n}{n} x^n$.

Theo điều kiện, $f(1) = a_1 + \frac{a_2}{2} + \ldots + \frac{a_n}{n} = 0$, ngoài ra, $f(0) = 0$.

⟦folio 43⟧

Theo tuyên bố đã được chứng minh, $f'(x_0) = 0$ đối với một số $x_0$ từ khoảng $]0; 1[$. Vẫn cần lưu ý rằng $f'(x) = a_1 + a_2x + \dots + a_nx^{n-1}$.

6) Chứng minh tương tự như ở phần a) với điểm khác biệt là thay vì hàm $f(x)$ chúng ta phải lấy $g(x) = \frac{a_1}{p+1}x^{p+1} + \frac{a_2}{p+2}x^{p+2} + \dots + \frac{a_n}{p+n}x^{p+n}$ và xét rằng trong đẳng thức $g'(x_0) = x_0^p(a_1 + a_2x_0 + \dots + a_nx_0^{n-1}) = 0$ tập $x_0^p$ khác 0.

A. Gokhberg, M. Ovetsky

**M807. a) Từ một điểm tùy ý $M$ bên trong một tam giác đều, các đường vuông góc $MK_1$, $MK_2$, $MK_3$ được hạ xuống các cạnh của tam giác đó. Chứng minh rằng tổng các vectơ $MK_1 + MK_2 + MK_3$ bằng $\frac{3}{2} \vec{M}O$, trong đó $O$ là tâm của tam giác.

6) Từ một điểm tùy ý $M$ các đường vuông góc $MK_1$, ..., $MK_n$ được thả xuống tất cả các phía một cách chính xác theo nút thắt hoặc phần mở rộng của chúng. Chứng minh rằng

$$\vec{MK}_1 + \dots + \vec{MK}_n = \frac{n}{2} \vec{M}O,$$

$O$ của nó là tâm của nút $n$.

8) Từ một điểm tùy ý $M$ bên trong một khối lập phương đều, các đường vuông góc $MK_1$, $MK_2$, $MK_3$, $MK_4$ trên mặt của nó bị bỏ đi. Chứng minh rằng

$$\vec{MK}_1 + \vec{MK}_2 + \vec{MK}_3 + \vec{MK}_4 = \frac{4}{3} \vec{M}O,$$

$O$ của nó là tâm của khối đa diện.

Hình 1.

Hình 2.

a) Vẽ các đường thẳng song song với các cạnh của tam giác đi qua điểm $M$ và chỉ định giao điểm của các đường này trên cạnh của tam giác, như trên Hình 1.

Rõ ràng là $2\vec{MK}_1 = \vec{MA}_1 + \vec{MA}_2$, $2\vec{MK}_2 = \vec{MB}_1 + \vec{MB}_2$, $2\vec{MK}_3 = \vec{MC}_1 + \vec{MC}_2$ và đồng thời, $\vec{MC}_1 + \vec{MB}_2 = \vec{MA}$; $\vec{MC}_2 + \vec{MA}_1 = \vec{MB}$ và $\vec{MA}_2 + \vec{MB}_1 = \vec{MC}$. Pozny

$$2(\vec{MK}_1 + \vec{MK}_2 + \vec{MK}_3) = \vec{MA} + \vec{MB} + \vec{MC} = 3\vec{MO} + \vec{OA} + \vec{OB} + \vec{OC}.$$

Nhưng, rõ ràng, $\vec{OA} + \vec{OB} + \vec{OC} = \vec{0}$, do đó, $2(\vec{MK}_1 + \vec{MK}_2 + \vec{MK}_3) = 3\vec{MO}$, đó là điều bắt buộc.

6) Trước tiên chúng ta hãy chứng minh rằng nếu $O$ là tâm của đa giác đều $A_1...A_n$ thì $\vec{OA}_1 + \dots + \vec{OA}_n = \vec{0}$.

Trên thực tế, khi xoay $\frac{360^\circ}{n}$ quanh $O$, đỉnh $A_1$ sẽ đi đến $A_2$, $A_2$ đến $A_3$, ..., $A_n$ đến $A_1$ và vectơ $\vec{s} = \vec{OA}_1 + \vec{OA}_2 + \dots + \vec{OA}_n$ đến $\vec{OA}_2 + \vec{OA}_3 + \dots + \vec{OA}_n + \vec{OA}_1 = \vec{s}$, tức là sẽ không thay đổi. Pozny $\vec{s} = \vec{0}$.

Chúng ta hãy thả các đường vuông góc $OP_1$, ..., $OP_n$ vào các cạnh của đa giác đều đã cho $(OP_i \parallel MK_i)$, sau đó thả các đường vuông góc $MB_i$ từ điểm $M$ lên các đường thẳng $OP_i$ (nếu $n$ chẵn thì các đường thẳng $OP_i$ và $OP_{i+n/2}$ $i=1, 2, \dots, n/2$ giống như $B_i = B_{i+n/2}$; xem Hình 2 để biết $n=6$). Vì $\vec{MK}_i = \vec{B}_iP_i = \vec{B}_iO + \vec{OP}_i$ và $P_1P_2...P_n$ là các nút $n$ có tâm $O$,

$$\vec{MK}_1 + \vec{MK}_2 + \dots + \vec{MK}_n = (\vec{B}_1O + \vec{B}_2O + \dots + \vec{B}_nO) + (\vec{OP}_1 + \vec{OP}_2 + \dots + \vec{OP}_n) = \vec{B}_1O + \vec{B}_2O + \dots + \vec{B}_nO.$$

(1)

Hãy chứng minh rằng các điểm $B_1$, ..., $B_n$ nằm trên một đường tròn có đường kính $MO$ (đối với $\vec{MB}_iO = 90^\circ$), do đó đủ để chứng minh rằng đỉnh góc của bất kỳ cung nào mà đường tròn này được chia cho các điểm $B_1$, ..., $B_n$ bằng $360^\circ/n$. Đặt $B_iB_j$ là một trong các cung này và không chứa điểm $O$. Khi đó $\angle B_iOB_j$ là một trong $2m$ các góc bằng nhau mà mặt phẳng $m$ của các đường thẳng $OB_i = OP_i$ được chia (xem Hình 3, trong đó $n=m=5$, $i=2$, $j=4$). Do đó, $B_iOB_j = 180^\circ/m$ và $B_iB_j = 360^\circ/m$. Cung chứa điểm $O$ cũng có độ lớn $360^\circ - (m-1) \cdot 360^\circ/m = 360^\circ/m$.

Từ những gì đã được chứng minh, suy ra rằng $\vec{O}_1B_1 + \dots + \vec{O}_1B_n = \vec{0}$, và theo (1)

$$\vec{MK}_1 + \dots + \vec{MK}_n = \vec{B}_1O_1 + \vec{B}_2O_1 + \dots + \vec{B}_nO_1 + n\vec{O}_1O = \frac{n}{2} \vec{MO}.$$

Lưu ý rằng bài toán này cũng có thể được giải bằng phương pháp điểm $a$.

c) Chỉ cần chứng minh rằng hình chiếu của vectơ $\vec{MK}_1 + \dots + \vec{MK}_n$ và $\frac{4}{3} \vec{MO}$ lên hai mặt phẳng cắt nhau là đủ. (Thật vậy, theo sau đó

⟦folio 44⟧

rằng hai hình chiếu chênh lệch $\vec{d}$ của các vectơ này bằng vectơ null, nghĩa là vectơ $\vec{d}$ phân phối lại uranium đồng thời thành hai mặt phẳng giao nhau, và do đó $\vec{d} = 0$).

Những mặt phẳng này có thể được chọn sao cho phép chứng minh được rút gọn thành trường hợp phẳng - bài toán a). Cụ thể, chúng ta vẽ mặt phẳng $p$ qua điểm $M$, phân phối lại uranium, chẳng hạn như $\vec{MK}_4$ và chiếu các vectơ $\vec{MK}_i$, $i=1, 2, 3$ lên nó (Hình 4). Mỗi góc tạo thành một góc $\gamma$ với mặt phẳng $p$, bằng góc giữa chiều cao và mặt bên của tứ diện đều $(\cos^2 \gamma = \frac{8}{9})$, do đó hình chiếu của vectơ $\vec{MK}_i$ bằng $\vec{MH}_i = \frac{8}{9} \vec{MQ}_i$, trong đó $Q_i$ là hình chiếu của điểm $M$ lên cạnh tương ứng của tam giác, dẫn đến tiết diện của tứ diện bằng mặt phẳng $p$. Đặt $O'$ là tâm của tam giác này thì theo a),

$$\vec{MH}_1 + \vec{MH}_2 + \vec{MH}_3 = \frac{8}{9} (\vec{MP}_1 + \vec{MP}_2 + \vec{MP}_3) =$$

$$= \frac{8}{9} \cdot \frac{3}{2} \vec{MO}' = \frac{4}{3} \vec{MO}'.$$

Cần lưu ý rằng vế trái của đẳng thức này là hình chiếu của tổng $\vec{MK}_1 + \ldots + \vec{MK}_4$ lên mặt phẳng $p$ (hình chiếu của tổng các vectơ bằng tổng các hình chiếu của chúng), và vế phải là hình chiếu của vectơ $\frac{4}{3} \vec{MO}$. Lý luận tương tự cũng đúng đối với các mặt phẳng song song với các mặt khác của tứ diện.

Hãy thử giải bài toán a) theo cách tương tự, rút ​​gọn trường hợp hai chiều thành trường hợp một chiều bằng cách sử dụng phép chiếu.

Chúng ta hãy phác thảo thêm một lời giải bài toán b) (có thể áp dụng cho các bài toán a) và 6)). Hãy coi vectơ hiệu $\vec{d} = (\vec{MK}_1 + \vec{MK}_2 + \vec{MK}_3 + \vec{MK}_4) - \frac{4}{3} \vec{MO}$ là hàm của vectơ $\vec{a} = \vec{MO}$. Dễ dàng kiểm tra khẳng định bài toán đúng với các đỉnh $A_1, A_2, A_3, A_4$ của tứ diện, do đó $\vec{d}(A_iO) = 0$. Ngoài ra, $\vec{d}(\vec{a})$ là một hàm vectơ tuyến tính, tức là $\vec{d}(\vec{a} + \vec{b}) = \vec{d}(\vec{a}) + \vec{d}(\vec{b})$ và $\vec{d}(k\vec{a}) = kd(\vec{a})$. (Thật vậy, tổng các vectơ $\vec{MK}_i$ bằng tổng các hình chiếu của vectơ $\vec{MO}$ lên bốn đường thẳng, phân phối lại uranium cho các cạnh của $n$-giác. Nhưng dễ dàng thấy rằng hình chiếu của vectơ lên một đường thẳng là một hàm tuyến tính của vectơ này.) Suy ra rằng $\vec{d}(\vec{a}) = 0$ đối với bất kỳ vectơ $\vec{a}$ nào, vì nó luôn có thể được biểu diễn dưới dạng $k_1\vec{A}_1O + k_2\vec{A}_2O + k_3\vec{A}_3O$.

V. V. Prasolov

**M808. Trên một tờ giấy ca rô dài vô tận, hai người vẽ một ô hiện tại: người thứ nhất sơn một số ô màu đỏ, người thứ hai sơn một số ô (không tô màu) màu xanh lam, sau đó người thứ nhất (không tô màu) lại chuyển sang màu đỏ, người thứ hai sơn một ô màu xanh lam, v.v. Niềm đam mê đầu tiên là bốn ô màu đỏ nằm ở các đỉnh của một hình vuông (với các cạnh song song với nhau).

Đáp số: Người chơi thứ hai sẽ không thể xếp cho người chơi thứ nhất ở bất kỳ $k$ nào.

Thật thuận tiện để giải quyết bài toán từ cuối. Rõ ràng là người chơi đầu tiên (chúng tôi sẽ gọi anh ta là $K$ - “đỏ”) sẽ thắng nếu bằng một số nước đi của mình, anh ta ngay lập tức tạo ra $k+1$ các ô vuông “không hoàn chỉnh”, tại ba đỉnh của mỗi ô có màu đỏ và ở đỉnh thứ tư - không có màu. Sau đó, sau đáp số người chơi thứ hai (hãy gọi anh ta là $C$ - “xanh lam”) ít nhất một trong bốn đỉnh vẫn chưa được tô màu và sau khi tô màu nó, $K$ sẽ nhận được một “hình vuông màu đỏ”. Ví dụ về các vị trí chiến thắng như vậy được hiển thị trong Hình 1, a - đối với trường hợp chung - và 1, b - đối với $k=1$ (trong trường hợp sau, $K$ có thể hoạt động theo cách tương tự như trong trường hợp chung, đối với $k \geqslant 1$ tùy ý, nhưng nó cũng có một con đường dẫn đến chiến thắng tiết kiệm hơn, sử dụng tính đối xứng của mạng hình vuông).

⟦folio 45⟧

lưới niyam). Liệu người thứ hai có thể đặt a) với k=1; 6)* với k=2; 8)* với một số k>2?

Hình 1. Gọi vị trí cho cerraq đầu tiên a) cho k ≥1 tùy ý; 6) tại k=1. Các ô được hợp nhất bởi các khung không có màu đỏ cũng không có màu xanh. Một dấu hoa thị được đặt trên ô cuối cùng, được sơn bằng lông vũ.

Hình 2.

Hãy giải thích K nên chơi như thế nào để có được những vị trí này.

a) Đặt a và a' lần lượt là các ô đầu tiên được người chơi K và C tô màu (Hình 2). Ở bước thứ hai, K tô màu ô b, nằm trong cùng cột với a, sao cho khoảng cách giữa các ô b và a lớn hơn giữa a' và a. Sau khi di chuyển phản hồi C, một trong các ô c và c₁ của cùng một cột (xem Hình 2), chẳng hạn như c, sẽ vẫn không được tô màu. Nó được tô màu bởi K ở nước đi thứ ba. Tương tự, ở bước thứ tư K màu ô d hoặc d₁. Giả sử anh ta tô màu d, sau đó xét các cột chứa các ô e, f, g và h. Ví dụ, một trong số chúng chứa e, không có ô màu xanh lam, vì chỉ có bốn ô màu xanh lam và một trong số chúng - a' - không được bao gồm trong các cột này. Tô màu e, người chơi K sẽ nhận được vị trí hình 1, 6 (các ô a, b₁ c và e ở hình 2).

6), c) Người chơi K bắt đầu bằng cách tô màu N ô của một hàng, không chú ý đến khoảng cách giữa chúng (số N phụ thuộc vào k; chúng tôi sẽ làm rõ ở phần dưới). Sau đó, dưới hàng đầu tiên, K chọn một hàng không có ô màu xanh lam và tô màu các ô trong đó nằm chính xác dưới các ô màu đỏ của hàng đầu tiên (miễn là trong số đó vẫn còn một số ô màu đỏ hoặc xanh lam không màu). Dưới dòng thứ hai, K chọn dòng thứ ba (không có ô màu xanh lam) và tô màu các ô trong đó nằm dưới các ô màu đỏ của dòng thứ hai, v.v. Sau khi điền n dòng theo cách này (chúng ta sẽ xác định số n sau), K phải chọn một đường thẳng l đi dọc theo các đường chéo của các ô (Hình 3) bên dưới tất cả các ô có màu (đỏ và xanh lam) và tô màu trên đó k + 1 ô đứng chính xác dưới các ô của hàng cuối cùng, hàng thứ n. Vì với mỗi ô màu đỏ mới có k ô màu xanh lam, nên chỉ cần hàng thứ n có k2+k+1 ô màu đỏ là đủ. (Sau đó, trong đáp số đối với k ô đầu tiên của dòng l, K sẽ tô màu, C sẽ tô màu k2 ô, sau đó, ít nhất một ô không màu nữa sẽ nằm dưới các ô màu đỏ của hàng thứ n trên dòng l.) Các ô màu đỏ trên dòng l, cùng với các ô của một trong n dòng nằm phía trên chúng và ô a tại giao điểm của dòng này với dòng l (Hình 3) tạo thành “nêm” chiến thắng như trong Hình 1, a. Chỉ cần chọn dòng này sao cho ô a và tất cả các ô bên dưới nó không có màu xanh lam. Và điều này luôn có thể được thực hiện nếu khoảng cách dòng n lớn hơn số lượng ô màu xanh lam trên dòng l trở xuống, không vượt quá (k+1)k=k2+k, chẳng hạn như khi n=n2+k+1.

Vì vậy, số N phải lớn đến mức người chơi K có thể điền n=k²+k+1 dòng theo cách đã chỉ định và tô màu n ô ở ô cuối cùng. Chúng ta có thể lấy N=(k+1)ⁿ·k+1. Thật vậy, như chúng ta đã thấy, để K tô màu k+1 ô trên dòng l, ở hàng thứ n cần phải tô màu (k+1) k+1 ô màu đỏ; người ta cũng chứng minh tương tự rằng để điều này xảy ra, hàng thứ (n−1) phải chứa (k+1)²·k+1 ô màu đỏ, hàng thứ (n−2) phải chứa (k+1)³·k+1, ... và dòng đầu tiên phải chứa (k+1)ⁿ·k+1 ô màu đỏ.

Lưu ý rằng lời giải này gần với lời giải bài toán-M750 («Kvant», 1982, Số 12; xem thêm bài viết của S. N. Bespamyatnykh trong «Kvant» Số 6 cho năm nay).

D. G. Azov

⟦folio 46⟧

M809. Tìm số tiền
$$\frac{1}{2!} + \frac{2}{3!} + \dots + \frac{n-1}{n!}$$

(sản phẩm $1 \cdot 2 \cdot 3 \cdot \dots \cdot k$ được ký hiệu là $k!$).

Đáp số: $1 - \frac{1}{n!}$. Khá dễ dàng để có được đáp số nếu bạn biểu diễn số hạng $k$ của tổng cần thiết dưới dạng $\frac{k}{(k+1)!} = \frac{(k+1) - 1}{(k+1)!} = \frac{1}{k!} - \frac{1}{(k+1)!}$. chúng tôi có
$$\frac{1}{2!} + \frac{2}{3!} + \dots + \frac{n-1}{n!} = \left(1 - \frac{1}{2!}\right) + \left(\frac{1}{2!} - \frac{1}{3!}\right) + \dots + \left(\frac{1}{(n-1)!} - \frac{1}{n!}\right) = 1 - \frac{1}{n!}.$$

V. V. Proizvolov

M810*. Chứng minh rằng mọi đa giác lồi $M$ đều có thể chứa diện tích thẳng ít nhất là $1/4$ diện tích của đa giác $M$.

Cho $A$ và $B$ là các đỉnh của đa giác $M$, $|AB| = d$ cách xa nhau nhất (đoạn $AB$ có thể là đường chéo hoặc một cạnh). Chúng ta hãy lấy một điểm trên đoạn $AB$ cách $x$ từ $A$ ($0 \leqslant x \leqslant d$) và vẽ một đường thẳng qua nó vuông góc với $AB$. Vì đa giác $M$ là lồi nên đường này sẽ cắt với nó dọc theo một đoạn (có thể suy biến thành một điểm), độ dài của đoạn này sẽ được ký hiệu là $l(x)$. Đặt $CD$ là đoạn lớn nhất trong số các đoạn như vậy, $|CD| = l_0$ (xem hình). Rõ ràng là vậy

$$S(M) = \int_0^d l(x) dx \leqslant \int_0^d l_0 dx = l_0 \cdot d.$$

Xét một tứ giác $KLPQ$ có các đỉnh trùng với trung điểm các cạnh của tứ giác $ABCD$. Hai cạnh của nó (trong hình - $KL$ và $PQ$) là đường trung bình của các tam giác $ABC$ và $ABD$ và do đó song song với $AB$ và có chiều dài bằng nhau $d/2$; tương tự, hai cạnh còn lại song song $CD$ và có chiều dài bằng nhau $l_0/2$. Do đó, $KLPQ$ là diện tích có mức thẳng của $dl_0/4$ và $S_{KLPQ} \geqslant S(M)/4$.

Cần lưu ý rằng mức thẳng $KLPQ$ được chứa trong $ACBD$ và $ACBD$ trong $M$, vì $M$ là một đa giác lồi.

Kết quả ước tính có vẻ không chính xác. Tuy nhiên, tác giả đã không thể cải thiện nó. Có lẽ độc giả sẽ làm điều này.

F. V. Vainitein

F818. Hai thanh cứng có chiều dài $l$ được gắn bản lề tại điểm $A$ (xem hình). Thanh $BA$ được cố định chắc chắn tại điểm $B$ và điểm $C$ của thanh $AC$ có thể trượt không ma sát dọc theo thanh dẫn hướng $BC$. Thanh $BA$ bắt đầu lành lại trong mặt phẳng vẽ xung quanh điểm $B$ với vận tốc góc không đổi $\omega$. Tốc độ và gia tốc tối đa của điểm $C$ sẽ là bao nhiêu nếu tại thời điểm ban đầu các thanh được kéo dài dọc theo thanh dẫn hướng ($BAC = \pi$)?

Vì chúng cứng nên tại bất kỳ thời điểm nào, hình chiếu vận tốc của các điểm $A$ và $C$ lên hướng $AC$ phải bằng nhau, tức là (xem hình)

$$v_A \cos \beta = v_C \cos \alpha.$$

Ở đây $v_A = \omega l$ là tốc độ của điểm $A$, $v_C$ là tốc độ của điểm $C$ tại một thời điểm nhất định, $\alpha = \omega t$ là góc mà thanh $BA$ ($AC$) tạo với thanh dẫn hướng $BC$ tại một thời điểm nhất định ($\alpha \leqslant \frac{\pi}{4}$, $\beta = \frac{\pi}{2} - 2\alpha$; tại $\alpha \geqslant \frac{\pi}{4}$ $\beta = 2\alpha - \frac{\pi}{4}$). Vì thế,

$$v_A \sin 2\alpha = v_C \cos \alpha \Rightarrow v_C = 2v_A \sin \alpha = 2v_A \sin \omega t,$$

tức là tốc độ của điểm $C$ thay đổi theo thời gian theo một định luật điều hòa. Giá trị của $v_C$ tối đa là $t = 0$, tức là tại thời điểm ban đầu:

$$a_C \max = 2v_A \omega = 2\omega^2 l.$$

L. G. Markovich

⟦folio 47⟧

F819. Ba vật thể nhỏ có khối lượng tỉ lệ 3:4:5 (khối lượng của vật đó bằng m), được giữ ở ba điểm khác nhau trên bề mặt bên trong của một phần bán cầu nhẵn có bán kính R, được cố định ở điểm thấp nhất trên một bề mặt nằm ngang. Tại một thời điểm nào đó, các thi thể được thả ra và trình diện với chính họ. Lượng cơ thể tối đa có thể được giải phóng trong một hệ thống như vậy là bao nhiêu? Điều này sẽ xảy ra ở vị trí ban đầu nào của vật? Mọi va chạm của các vật đều tuyệt đối không đàn hồi.

F820. Quá trình A-B-C-A được thực hiện trên một mol khí đơn nguyên tử lý tưởng (Hình 1). Xác định hiệu suất của chu trình.

Hình 1.

Hình 2.

Để lượng nhiệt tỏa ra lớn nhất phải thỏa mãn các điều kiện sau:

1) năng lượng tiềm tàng của cơ thể tại thời điểm ban đầu phải tối đa nhất có thể;
2) các vật phải va chạm đồng thời ở điểm thấp nhất của bát;
3) tốc độ của hai vật ngay sau va chạm phải bằng 0.
Nếu những điều kiện này được đáp ứng thì toàn bộ nguồn thế năng ban đầu sẽ chuyển thành nhiệt.

Do đó, các vật tại thời điểm ban đầu phải nằm trên cái bát ở độ cao R so với điểm thấp nhất của nó. Vị trí của vật phải sao cho tổng động lượng của chúng trước khi va chạm bằng 0 (khi đó sau va chạm, vật gục xuống vẫn bất động ở điểm đáy bát). Vì các giá trị xung của cơ thể tại bất kỳ thời điểm nào đều theo tỷ lệ 3:4:5, nên vị trí của cơ thể tại thời điểm ban đầu phải giống như trong hình (hình minh họa nhìn từ trên xuống). Lượng cơ thể sẽ được giải phóng trong hệ thống là tối đa và bằng 4mgR.

S. K. Strokov

Hiệu suất chu trình η được xác định bằng tỷ số giữa công A do khí thực hiện trong chu trình với lượng nhiệt Q cung cấp cho khí trong thời gian này:

η = A/Q.

Công mà chất khí thực hiện về mặt số lượng bằng diện tích của tam giác ABC (xem Hình 1):

$$A = p_0 V_0 / 2$$

Để tìm Q, hãy xem xét từng phần của chu trình riêng biệt. Ở đoạn AB quá trình ishore đang được tiến hành. Chất khí không sinh công nên nội năng tăng lên một lượng

$$\Delta U_{AB} = 3 / 2 R (T_B - T_A) = 3 / 2 p_0 V_0.$$

Theo định luật nhiệt động thứ nhất, sự gia tăng nội năng này xảy ra do cung cấp một lượng nhiệt nhất định

$$Q_{AB} = \Delta U_{AB} = 3 / 2 p_0 V_0.$$

Trong phần CA, một quá trình đẳng áp xảy ra trong đó khí bị nén, nghĩa là nó thực hiện công âm và nội năng của khí giảm. Vì vậy, ở khu vực này khí được tách ra chứ không được nhận vào.

Bây giờ chúng ta hãy tìm hiểu điều gì đang xảy ra ở phần BC. Ở đây khí nở ra và do đó thực hiện công dương. Nội năng của khí lúc đầu tăng rồi giảm. Do đó, đến một thời điểm nhất định, khí nhận nhiệt từ bên ngoài, sau đó nhiệt lượng tỏa ra bên ngoài. Chúng ta hãy biểu thị điểm “biên giới” bằng chữ D và tìm các tham số của nó. Gọi điểm O là điểm hiện tại của phần BC (Hình 2) và các tham số của nó - p, V và T. Trên đoạn BO, chất khí thực hiện công về mặt số lượng bằng diện tích hình thang được tô màu trong Hình 2:

$$A_{BO} = (p_0 + p / 2) (V - V_0),$$

trong trường hợp này, nội năng của nó thay đổi theo giá trị

$$\Delta U_{BO} = 3 / 2 R (T - T_B) = 3 / 2 (pV - 2p_0V_0).$$

Theo định luật nhiệt động thứ nhất, một lượng nhiệt phải được truyền cho chất khí

$$Q_{BO} = A_{BO} + \Delta U_{BO} = (p_0 + p / 2) (V - V_0) + 3 / 2 (pV - 2p_0V_0).$$
