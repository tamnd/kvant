---
id: 1990-4-vedenov-ivanov-s-kakoy-skorostyu-rastet-zelenyiy-list-2759a4c5
issue: kvant_1990_4
year: 1990
number: "4"
title: Một chiếc lá xanh phát triển với tốc độ bao nhiêu?
authors:
  - Веденов А.
  - Иванов О.
rubric: osnovnye-stati
page_first: 14
page_last: 20
page_labels: 12-18
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 08987e3d10a7744cd7479d67304dd7d411dc924dad1fde4a2fa655eb70865ad2
prompt_sha256: draft-1
translated_from: content/ru/1990/04/articles/03_vedenov-ivanov-s-kakoy-skorostyu-rastet-zelenyiy-list-2759a4c5.md
source_content_sha256: 097230025b6e98d859c25096064f777353152af03616109decd3d4c4bce37b2e
translation_model: draft
translation_run: vi-draft-gaps-2026-11-05
translation_quality: draft
---

⟦folio 12⟧

---
running_head:
folio:
---

Khi quan sát lượng cây xanh trên cánh đồng, chúng tôi nhận thấy sự thay đổi về lượng cây xanh đều đặn (để đơn giản, đây sẽ là một ngày).
Tỷ lệ thay đổi lượng cây xanh $\Delta K_t$ trong khoảng thời gian này (cho bất kỳ ngày nào) so với lượng cây xanh có sẵn $K_t$ vào ngày này sẽ là một giá trị không đổi bằng ngưỡng nhận biết sự thay đổi về lượng cây xanh:

$$\frac{\Delta K_t}{K_t} = \delta_\pi^K.$$

Từ mối quan hệ này, chúng ta có thể thu được phương trình tính tốc độ thay đổi của lượng cây xanh

$$v_t = \frac{\Delta K_t}{\Delta t} = \frac{\delta_\pi^K K_t}{t_\pi} = CK,$$

(1)

trong đó $C = \delta_\pi^K / t_\pi$ là một giá trị không đổi bằng với ngưỡng nhận thức về sự thay đổi về lượng cây xanh vào thời điểm mà sự thay đổi về lượng cây xanh trên một cánh đồng nhất định đạt đến ngưỡng (đối với chúng tôi đây là một ngày).

Biểu thức thu được cho thấy tốc độ tăng trưởng của số lượng cây xanh tỷ lệ thuận với số lượng cây xanh hiện có. (Một biểu thức tương tự thu được khi mô tả sự phân rã phóng xạ của hạt nhân. Trong trường hợp này, tốc độ phân rã, tức là số hạt nhân phân rã trong một đơn vị thời gian, tỷ lệ với số hạt nhân còn lại. Nhưng, không giống như sự phát triển của thực vật, đối với sự phân rã của hạt nhân ở vế phải của phương trình, tương tự như (1), có dấu trừ, vì số hạt nhân ban đầu đầu tiên giảm theo thời gian.) Trong mọi trường hợp khi tốc độ thay đổi của bất kỳ đại lượng nào đều tỷ lệ với đại lượng. bản thân sự phụ thuộc của đại lượng đang xét vào thời gian có tính chất hàm mũ. Trong trường hợp của chúng tôi, điều này có nghĩa là theo thời gian $t$ lượng cây xanh có thể được tìm thấy là

$$K_t = K_0 e^{Ct},$$

(2)

trong đó $K_0$ là giá trị ban đầu của lượng cây xanh tại $t = 0$ và $e = 2,718$.

Để chỉ ra phương trình (1) mang lại hàm mũ như thế nào

phụ thuộc vào thời gian (2), có thể thực hiện những điều chỉnh lý luận sau đây. Giả sử tại thời điểm ban đầu $t_0 = 0$ giá trị của lượng cây xanh bằng $K_0$ và chúng ta quan tâm đến giá trị $K_t$ sau thời gian $t$. Chia khoảng thời gian $0 - t$ thành $N$ những khoảng thời gian bằng nhau có độ dài $\tau (\tau = t/N)$ và chúng ta sẽ ghi lại lượng cây xanh tại các thời điểm $t_0 + \tau$, $t_0 + 2\tau$, v.v.

Sau thời gian $t$ sau thời điểm ban đầu $t_0 = 0$ lượng cây xanh có thể được tìm thấy là

$$K_1 = K_0 + \Delta K_0 = K_0 + v_0 \tau = K_0 + K_0 C \tau = K_0 (1 + C \tau)$$

(trong khoảng thời gian này, chúng tôi giả định tốc độ tăng trưởng là không đổi và bằng nhau (xem (1)) $v_0 = CK_0$); tương tự, sau thời gian $2\tau$

$$K_2 = K_1 + \Delta K_1 = K_1 + v_1 \tau = K_1 + CK_1 \tau = K_1 (1 + C \tau) = K_0 (1 + C \tau)^2$$

(tốc độ tăng trưởng không đổi và bằng $v_1 = CK_1$). Giá trị chúng ta quan tâm $K_t$ sau thời gian $t = N\tau$ có ​​thể được tìm thấy là

$$K_t = K_N = K_0 (1 + C \tau)^N = K_0 \left(1 + \frac{Ct}{N}\right)^N = K_0 \left(1 + \frac{1}{M}\right)^{M C t} = K_0 \left(1 + \frac{1}{M}\right)^{M C t},$$

trong đó chúng tôi đã giới thiệu ký hiệu $M = Ct/N$ (M là đại lượng không thứ nguyên).

Rõ ràng là giá trị $K_t$ sẽ chính xác hơn, chúng ta càng thực hiện các phép tính trung gian thường xuyên hơn, tức là $N$ càng lớn (xét cho cùng thì tốc độ tăng trưởng

⟦folio 13⟧

---
running_head:
folio:
---

thay đổi liên tục theo thời gian và $\tau$ càng nhỏ thì chúng ta càng thay thế giá trị $v_0, v_1, \dots$ bằng giá trị thực của tốc độ). Nếu bạn tăng vô hạn $N$ (tức là giảm vô hạn khoảng thời gian $\tau$), thì $M$ sẽ có xu hướng tiến tới vô cùng và các giá trị của $(1 + \frac{1}{M})^M$ tại $M \to \infty$ có xu hướng không đổi, xấp xỉ bằng 2,7182828 (ví dụ: $(1 + \frac{1}{100})^{100} = 2,7048$; $(1 + 0,001)^{1000} = 2,7169$). Số 2,7182828... trong toán học được biểu thị bằng $e$.

Vì vậy, chúng tôi đã chỉ ra rằng ở giai đoạn đầu, sự phát triển của thực vật trong một khoảng thời gian nhất định xảy ra theo quy luật hàm mũ. Các nghiên cứu thực nghiệm xác nhận rằng trong các điều kiện bên ngoài không đổi (ánh sáng, nhiệt độ, độ ẩm không khí liên tục, tưới nước thường xuyên, đất được chuẩn bị tốt), trọng lượng và kích thước của toàn bộ cây và các bộ phận riêng lẻ của nó ở giai đoạn tăng trưởng ban đầu thay đổi theo cấp số nhân theo thời gian. hình 1 thể hiện kết quả thí nghiệm trồng lúa mì trong dung dịch dinh dưỡng. Trên biểu đồ này, tỷ lệ dọc theo trục abscissa là tuyến tính và dọc theo trục tọa độ, nó là logarit, tức là những ngày đã trôi qua kể từ khi bắt đầu tăng trưởng được vẽ trên trục ngang ở những khoảng cách bằng nhau chứ không phải các giá trị của đại lượng đo mà là logarit của các giá trị này được vẽ trên trục tung.

Sử dụng thang logarit trong trường hợp sự phụ thuộc của một đại lượng vào một đối số gần với hàm mũ $y = Ae^{Cx}$ dẫn đến đồ thị có dạng một đường thẳng. Thật vậy, giá trị $\ln y$ được vẽ trên đồ thị dọc theo trục tọa độ là một hàm tuyến tính của đối số $x$ -

$$\ln y = \ln A + Cx,$$

và đồ thị của hàm tuyến tính là một đường thẳng. Từ biểu đồ này, có thể dễ dàng xác định hằng số $C$ - nó bằng tỷ lệ giữa mức tăng $\Delta(\ln y)$ với mức tăng của đối số $\Delta x$.

Hình 2.

Vì vậy, từ hình 1, rõ ràng là bắt đầu từ ngày đầu tiên sau khi nảy mầm trong ba tuần, tổng trọng lượng của cây $m$, trọng lượng khô của cây $m_0$ (tức là trọng lượng của tổ chức chất còn lại sau khi sấy khô), trọng lượng khô của lá $m_{0,n}$, diện tích của lá $S_n$ thay đổi theo cấp số nhân theo thời gian. Trong tự nhiên, tăng trưởng theo cấp số nhân là một hiện tượng phổ biến. Một ví dụ là sự gia tăng số lượng vi khuẩn hoặc sinh vật đơn bào ở trạng thái đủ dinh dưỡng. Trong trường hợp này, tăng trưởng theo cấp số nhân có một lời giải thích đơn giản. Một vi khuẩn hoặc một tế bào riêng lẻ tạo ra hai tế bào sau một thời gian nhất định $\tau$. Do đó, số lượng của chúng thay đổi theo thời gian như sau: $n_\tau = n_0 \cdot 2^{t/\tau} = n_0 e^{Ct}$, trong đó $C = \frac{\ln 2}{\tau}$.

Chúng ta hãy tìm lời giải thích vật lý cho sự tăng trưởng theo cấp số nhân của thực vật và xác định tốc độ tăng trưởng không đổi $C$ từ các định luật bảo toàn vật chất và năng lượng. Đầu tiên chúng ta cần xây dựng một mô hình cây trồng sát với thực tế và thuận tiện cho việc nghiên cứu của mình. Vấn đề lựa chọn mô hình sẽ luôn nảy sinh trong việc mô tả vật lý các hiện tượng xung quanh chúng ta. Mô hình phải nêu bật những đặc điểm chính của một đối tượng hoặc hiện tượng đủ để mô tả các quá trình giao thoa với chúng ta. Hãy lấy mô hình thực vật này. Chúng ta sẽ giả sử rằng nó bao gồm một lá (diện tích của nó bằng diện tích tất cả các lá của nó), một thân và một rễ (hình 2) và mối quan hệ

⟦folio 14⟧

---
running_head:
folio:
---

$$\frac{m}{m_0} = \frac{m_\pi}{m_{0\pi}} = \alpha$$
($m_\pi, m_{0\pi}$ - tổng trọng lượng và trọng lượng khô của lá). Ngoài ra, chúng ta sẽ xem xét các giá trị không đổi của độ dày lá $d$ và tỷ lệ khối lượng khô của lá với khối lượng khô của toàn cây:

$$\frac{m_{0\pi}}{m_0} = \varepsilon.$$

(Những giả định như vậy có thể được đưa ra từ các quan sát định lượng ở giai đoạn tăng trưởng theo cấp số nhân của cây thân thảo. Tất nhiên, mô hình như vậy không thể được sử dụng để mô tả sự phát triển của các loài thực vật khác. Ví dụ, ở cây, tỷ lệ khối lượng của lá so với khối lượng của toàn bộ cây là một giá trị thay đổi.)

Từ môn sinh học, bạn biết rằng cây tăng khối lượng thông qua quá trình quang hợp - các chất hữu cơ được hình thành từ carbon dioxide có trong không khí và nước có trong cây khi cây hấp thụ năng lượng ánh sáng. Lượng chất hữu cơ khô $\Delta m_0$ hình thành tỷ lệ thuận với năng lượng ánh sáng hấp thụ $\Delta E$:

$$\Delta m_0 = \gamma \cdot \Delta E.$$ (3)

Nếu cường độ của quang thông $I$ (năng lượng ánh sáng tới trên một đơn vị diện tích trên một đơn vị thời gian) không đổi thì

$$\Delta E = I S_\pi \cdot \Delta t.$$ (4)

Sử dụng mô hình thực vật của chúng tôi, chúng tôi biểu thị diện tích lá thông qua khối lượng khô của cây $m_0$. Diện tích của tấm bằng thể tích của tấm chia cho độ dày của nó - $S_\pi = V_\pi / d$. Chúng tôi tìm thể tích thông qua trọng lượng ướt của tấm và mật độ của nó - $V_\pi = m_\pi / \rho$ ($\rho \approx 1 \text{ г/cm}^3$), đồng thời biểu thị trọng lượng ướt của tấm thông qua $m_0$ bằng cách sử dụng công thức cho các hệ số $\alpha$ và $\varepsilon$: $m_\pi = \alpha \varepsilon m_0$. Kết quả là chúng tôi nhận được:

$$S_\pi = \frac{m_0 \varepsilon \alpha}{\rho \alpha}.$$ (5)

Bây giờ, kết hợp các biểu thức (3)—

(5), chúng ta viết phương trình tốc độ thay đổi lượng chất hữu cơ khô:

$$\frac{\Delta m_0}{\Delta t} = \frac{\gamma \varepsilon \alpha I}{\rho d} m_0.$$

Do đó, khối lượng chất khô thay đổi theo thời gian như

$$m_{0t} = m_0 e^{\gamma \varepsilon \alpha I / \rho d},$$

và hằng số tốc độ tăng trưởng bằng

$$C = \frac{\gamma \varepsilon \alpha I}{\rho d}.$$ (6)

Vì vậy, hằng số tốc độ tăng trưởng tỷ lệ thuận với cường độ ánh sáng tới cây và phụ thuộc vào các thông số $\alpha$, $\varepsilon$, $d$ và $\gamma$. Đối với lời giải, $\alpha$, $\varepsilon$ và $d$ có thể được xác định bằng cách sử dụng biểu đồ trên hình 1 bằng cách lấy giá trị của $m$, $m_0$, $m_{0\pi}$ và $S_\pi$ cho mỗi ngày. Ví dụ: vào ngày thứ 13 $m = 0,026$ g, $m_0 = 0,0043$ g, $m_{0\pi} = 0,0021$ g, $S_\pi = 1 \text{ cm}^2$ (chúng tôi đã tính toán các giá trị này bằng máy tính) và

$$\alpha = \frac{m}{m_0} = 6, \varepsilon = \frac{m_{0\pi}}{m_0} = 0,48,$$

nhưng chỉ có chiếc lá xác định, bằng cách sử dụng các giá trị giống nhau, việc loại bỏ thể tích của lá $V_\pi = m_{0\pi} \alpha / \rho$ đối với diện tích của nó:

$$d = \frac{m_{0\pi} \alpha}{\rho S_\pi} = 0,012 \text{ см.}$$

Giá trị “tương đương quang hợp” của ánh sáng $\gamma$ xác định khối lượng khô của cây tăng lên bao nhiêu khi hấp thụ một lượng năng lượng ánh sáng nhất định. Để hiểu rõ hơn ý nghĩa của giá trị này, chúng ta hãy rút ra nó bằng cách xem xét năng lượng của các quá trình xảy ra trong tế bào thực vật.

Quá trình quang hợp tổng thể có thể được biểu diễn dưới dạng phương trình:

$$\mathrm{H}_2\mathrm{O} + \mathrm{CO}_2 \xrightarrow{\text{свет}} (\mathrm{CH}_2\mathrm{O}) + \mathrm{O}_2.$$

Ở bên trái của phương trình là các phân tử nước và carbon dioxide quen thuộc, còn ở bên phải là phân tử oxy và cấu trúc tối thiểu của nhóm carbohydrate $\mathrm{CH}_2\mathrm{O}$, thu được bằng cách “đồng hóa” một phân tử carbon dioxide. Phân tử đường trái cây - fructose $C_6\mathrm{H}_{12}\mathrm{O}_6$ -

⟦folio 15⟧

---
running_head:
folio:
---

bao gồm 6 nhóm như vậy ($C_6H_{12}O_6 = 6(CH_2O)$) và phân tử đường thông thường - sucrose $C_{12}H_{24}O_{12}$ - bao gồm 12. Từ “ánh sáng” phía trên mũi tên có nghĩa là để xảy ra sự biến đổi các chất như vậy thì cần phải hấp thụ năng lượng ánh sáng.

Phương trình viết chỉ hiển thị các sản phẩm ban đầu và cuối cùng. Và quá trình quang hợp bao gồm nhiều chất trung gian và phản ứng. Trong tế bào thực vật, chính xác hơn là trong lục lạp nằm bên trong nó, các đơn vị phân tử thực sự hoạt động, các cỗ máy của chúng - phân tử protein (enzym) - có thể sử dụng năng lượng ánh sáng để tạo ra điện, tiến hành điện phân, phân phối lại các nguyên tử và nhóm nguyên tử trong phân tử.

Ánh sáng trong lục lạp được hấp thụ bởi các phân tử diệp lục. Khi một phân tử hấp thụ một photon, một trong các electron của phân tử sẽ chuyển lên mức năng lượng cao hơn. Cuối cùng, năng lượng của các electron bị kích thích này sẽ hoạt động tuần hoàn trong một mạch điện bao gồm chủ yếu là các phân tử protein. (Các phân tử diệp lục và protein liên kết với chúng đóng vai trò là tế bào quang điện của tế bào.) Dòng điện chạy qua mạch thực hiện quá trình điện phân các ion được hình thành trong quá trình phân ly của các phân tử nước ($OH^-$ và $H^+$), và của chất, đó là sự chuyển đổi các nguyên tử hydro từ mo-

Hình 4.

phân tử nước thành phân tử carbon dioxide.

Phân tử của chất hoàn nguyên này và nó sẽ được ký hiệu lần lượt là A và $A^+$.

Quá trình điện phân này có thể được so sánh với quá trình điện phân nước tinh khiết, trong đó hydro được hình thành ở cực âm và oxy ở cuối. Đúng, trong trường hợp điện phân nước tinh khiết và trong điện phân nói chung các chất điện phân khác, nguồn EMF và dây cấp nguồn của mạch điện được đặt ở bên ngoài, bên ngoài chất điện phân và chỉ các điện cực được ngâm trong chất điện phân (hình 3). Trong tế bào, toàn bộ chuỗi điện phân được ngâm trong chất điện phân - các rastoron lấp đầy tế bào (hình 4). Nó có thể được hình dung như một cái ống, bên trong chứa các nguồn EMF được phân lập từ chất điện phân - phân tử diệp lục kết nối với protein (tế bào quang điện) và dây cung cấp - protein và các phân tử hữu cơ khác. Để thực hiện công chuyển hóa một electron trong suốt chuỗi điện phân cần có năng lượng của hai phân tử diệp lục bị kích thích, do đó cần có một điện áp trên các điện cực để điện phân.

Hình 3.

⟦folio 16⟧

---
running_head:
folio:
---

được tạo ra bởi hai tế bào quang điện được nối nối tiếp. Các quá trình sau đây xảy ra trên các điện cực:

ở cực âm - 2H⁺ + 2A⁺ + 4e⁻ = 2AH,
ở cực dương - 4OH⁻ = O₂ + 2H₂O + 4e⁻

Bây giờ bạn có thể tính toán cần bao nhiêu lượng tử ánh sáng để tạo ra một nhóm carbohydrate.

Theo phương trình quang hợp, phải thêm 2 nguyên tử hydro vào phân tử carbon dioxide. Vì vậy, để thực hiện quá trình biến đổi, 2 ion A⁺ phải được điện phân. Để làm điều này, bạn cần di chuyển 4 electron dọc theo chuỗi và để làm được điều này, bạn cần 8 photon. (Hãy nhớ lại rằng việc nối lại mỗi electron cần có sự kích thích của hai phân tử diệp lục.) Năng lượng của mỗi nền phải lớn hơn 1,8 eV, năng lượng tối thiểu cần thiết để kích thích một phân tử diệp lục. Dòng điện phân xảy ra dưới tác dụng của ánh sáng ở lá xanh là rất đáng kể. Với cường độ ánh sáng mặt trời tối đa 400 W/m2, tổng dòng điện phân trong tất cả lục lạp của tất cả các tế bào có diện tích 1 cm vuông của một chiếc lá là khoảng 0,005 A. Điều này có nghĩa là trong một chiếc lá có diện tích 30 cm2, dòng điện là 0,15 A, giống như trong bóng đèn pin. Đúng, phương pháp sử dụng trực tiếp dòng điện này vẫn chưa được mô tả.

Ở giai đoạn quang hợp tiếp theo - được gọi là bóng tối vì không cần năng lượng ánh sáng - các nguyên tử hydro từ AN được chuyển đổi thành phân tử carbon dioxide và tạo thành carbohydrate, và phân tử chất mang ở dạng ion A⁺ lại sẵn sàng để điện phân.

Thông thường cây được chiếu sáng bằng ánh sáng không đơn sắc. Phần bức xạ ánh sáng đại diện cho lượng tử có khả năng kích thích diệp lục được gọi là bức xạ hoạt động quang hợp (PAR). Hiệu suất kích thích của các phân tử diệp lục phụ thuộc vào năng lượng của lượng tử. hình 5 thể hiện sự phân bố năng lượng của các nền trong dòng bức xạ mặt trời (đường cong màu đỏ n(hv)) và đường cong hiệu suất kích thích của các phân tử diệp lục tùy thuộc vào năng lượng của lượng tử (đường cong màu xanh lá cây p(hv)). Sử dụng những đường cong này, bạn có thể tính năng lượng trung bình của lượng tử PAR trong ánh sáng mặt trời; nó bằng ~2,1 eV. Và tổng năng lượng của mảng pha xấp xỉ một nửa tổng năng lượng của bức xạ mặt trời tới Trái đất. (Lưu ý rằng các nguồn sáng khác nhau sẽ phát ra năng lượng khác nhau.)

Bây giờ, sử dụng phương trình (3), chúng tôi xác định mức quang hợp tương đương cho PAR. Để tăng lượng carbohydrate thêm một mol (Δm₀ = μCH₂O × mol), cần 8·N_A lượng tử bức xạ có năng lượng trung bình hvФ, tức là ΔE = 8hvΦN_A (N_A là số Avogadro); Đó là lý do tại sao

$$\gamma = \frac{\mu CH₂O \cdot 1 \text{ molь}}{8hvΦN_A} = 18 \text{ г/MДж.}$$

Giá trị tính toán của γ chỉ có thể được quan sát trong những điều kiện thí nghiệm đặc biệt, khi không có oxy trong bầu không khí xung quanh nhà máy. Trong khí quyển nói chung, một phần sản phẩm trung gian trong chuỗi phản ứng quang hợp được tạo ra bởi oxy trong khí quyển, làm giảm một nửa sự hình thành carbohydrate. Quá trình này được gọi là quang hô hấp. Khoảng 30% được tổng hợp

⟦folio 17⟧

---
running_head:
folio:
---

Những carbohydrate này sau đó được cây sử dụng làm nguồn năng lượng trong quá trình tổng hợp các chất cần thiết cho sự tăng trưởng và trong các quá trình khác. Do đó, $\gamma$ thường nhỏ hơn ít nhất ba lần so với giá trị tối đa. Chúng ta sẽ giả định rằng $\gamma = 6$ g/MJ.

Bây giờ chúng ta đã biết mọi thứ cần thiết để tính hằng số tốc độ tăng trưởng $C$. Trong các thí nghiệm, kết quả được đưa ra ở hình 1, cường độ cải cách hành chính được tạo ra dưới ánh sáng nhân tạo là $\Gamma = 30$ W/$\mathrm{m}^2$. Mỗi ngày, cây được chiếu sáng trong 16 giờ và sau đó để trong bóng tối trong 8 giờ. Đồng thời, cường độ trung bình hàng ngày là $I = 1,7$ MJ/$\mathrm{m}^2 \cdot \mathrm{сут}$. Thay thế các giá trị số của tất cả các đại lượng vào công thức (6), chúng ta thu được $C = 0,21$ ngày$^{-1}$. hình 6 cho thấy sự phụ thuộc của $C$ vào cường độ cải cách hành chính, thu được bằng thực nghiệm. Như chúng ta có thể thấy, giá trị $C$ mà chúng tôi tính toán rất phù hợp với dữ liệu thử nghiệm.

Vào một ngày mùa xuân quang đãng, cường độ cải cách hành chính vào buổi trưa đạt 200 W/$\mathrm{m}^2$ và cường độ trung bình hàng ngày là $I \approx 3,5$ MJ/$\mathrm{m}^2 \cdot \mathrm{сут}$. Theo công thức (6)CONSTANTA, TỐC ĐỘ TĂNG TRƯỞNG TRONG ĐIỀU KIỆN ĐÓ PHẢI LỚN HƠN 2 LẦN. Nhưng ở cường độ ánh sáng cao hơn, $\varepsilon$ giảm đi, vì nó quay trở lại vào mùa xuân tương đối - cần đảm bảo nhu cầu muối khoáng tăng lên của thực vật; do đó, $C$ tăng khi tăng $I$ không tuyến tính mà chậm hơn và ở $I = 3,5$ MJ/$\mathrm{m}^2 \cdot \mathrm{сут}$ là 0,3 ngày$^{-1}$.

Theo tính toán của chúng tôi, trong điều kiện lý tưởng, cây có thể tăng kích thước mỗi ngày (mỗi ngày) lên $e^{0,3} = 1\frac{1}{3}$ lần, tức là 1/3, và sự thay đổi trong phổi có thể được nhận thấy bằng mắt. Nếu cây phát triển trong điều kiện kém thuận lợi hơn, chẳng hạn như $C = 0,1$ ngày$^{-1}$, thì một sự thay đổi đáng chú ý sẽ xảy ra sau hai ngày ($e^{0,1 \cdot 2} = 1,24$), tức là, thực sự có thể tốc độ tăng trưởng cho phép người ta nhận thấy sự thay đổi về kích thước của cây hầu như mỗi ngày.

Chúng ta đã xem xét thời kỳ thực vật mà việc cung cấp các chất chỉ diễn ra thông qua quá trình quang hợp. Trong quá trình nảy mầm, khi năng lượng dự trữ trong hạt được sử dụng và trong quá trình phát triển của lá mới, khi lá đang phát triển nhận được sản phẩm quang hợp từ các lá khác, tốc độ tăng trưởng có thể lớn hơn tốc độ tăng trưởng của chúng ta.

Giải pháp bài toán của chúng tôi về việc tìm hằng số tốc độ của cây là một ví dụ đơn giản về bài toán được giải quyết bằng vật lý nông nghiệp. Vật lý nông nghiệp là một ngành khoa học khá non trẻ, nằm ở điểm giao thoa giữa vật lý khí quyển và vật lý đất, lý sinh và sinh lý thực vật cũng như toán học ứng dụng. Cô quyết định bài toán bằng cách mô tả loại cây và sự phát triển của từng cây và toàn bộ cây trồng, về ảnh hưởng của các điều kiện vật lý bên ngoài đến chúng - cường độ ánh sáng, nhiệt độ, độ ẩm của đất và không khí, tốc độ gió.

Các nhiệm vụ này phức tạp và chứa một số bài toán độc lập. Tuy nhiên, một trong số đó là việc tạo ra một mô hình thực vật chính xác hơn mô hình mà chúng tôi đã xem xét. Mô hình cần mô tả những đặc điểm về sự tương tác của thực vật với môi trường cần nghiên cứu. Ví dụ: nếu chúng tôi muốn tìm hiểu xem cây của chúng tôi sẽ phát triển như thế nào trong một ngôi làng khi mỗi cây tạo ra $S_0$ quả, thì mô hình của chúng tôi sẽ phải được bổ sung bằng sự phụ thuộc

⟦folio 18⟧

---
running_head:
folio:
---

diện tích hấp thụ ánh sáng hiệu quả của lá $S_{\alpha}$ tùy theo giai đoạn phát triển của cây. Diện tích hiệu dụng này phải được tính cùng với diện tích của các trang tính trong công thức (4), khi các trang tính bắt đầu chồng lên nhau, tức là khi diện tích của các trang tính tương đương với $S_0$. Ví dụ, sự phụ thuộc này có thể được lấy ở dạng $S_{\alpha} = S_{\pi} / (1 + S_{\pi} / S_0)$. Công thức này mô tả rõ sự thay đổi diện tích hấp thụ hiệu quả của cây khi diện tích lá tăng lên. Thật vậy, nếu $S_{\pi} \ll S_0$, thì phân số trong giá trị của hình dạng xà phòng và $S_{\alpha} \approx S_{\pi}$, sẽ như vậy khi các tấm không chồng lên nhau. Khi $S_{\pi} \gg S_0$, giá trị có thể đứng trước một và sau đó là $S_{\alpha} \approx S_0$.

Các mô hình phức tạp hơn có tính đến sự phụ thuộc của các thông số có hại $\alpha, \varepsilon, d, \gamma$ vào các điều kiện bên ngoài, vào giai đoạn phát triển của cây và vào các thông số khác.

bài toán khác liên quan đến việc mô tả các quá trình ảnh hưởng đến sự phát triển của thực vật - ví dụ, sự khuếch tán carbon dioxide và hơi nước trong khí quyển và trong khoảng trống giữa các lá, dòng nước và sự hòa tan chất dinh dưỡng trong đất xốp. Mục tiêu của nghiên cứu lý nông học là tìm hiểu cách “điều chỉnh” các thông số vật lý bên ngoài của môi trường sống của thực vật để cây luôn ở trong điều kiện tối ưu cho sự phát triển của nó. Hiện nay đã có các cánh đồng thử nghiệm, trong đó dựa trên mô hình phát triển của cây trồng và sự tương tác của nó với môi trường, cây trồng được tưới nước và bón phân theo chỉ số của các cảm biến được lắp đặt trên đồng ruộng.

Hình 7.

Biết về sự phát triển của cây theo cấp số nhân, bạn có thể giải quyết một vấn đề nông học bài toán. Nhưng trước tiên, hãy làm quen với phương pháp băng tải trồng cây.

Trong một số trường hợp, các trạm khí tượng vùng cực hiện đang sử dụng hệ thống lắp đặt băng tải trồng rau xanh cho các đội có tên lấp đầy là “Nugget - Arctic”. Việc cài đặt các thiết bị này rất đơn giản. Một cây có kích thước $0,5 \times 1,5$ m sẽ tự động duy trì mức độ ổn định của các chất cần thiết cho sự phát triển của cây. Một đèn điện mạnh mẽ được đặt phía trên gương phản chiếu. Cây đang phát triển được di chuyển dọc theo bồn tắm trong các hộp nhựa, rễ của chúng tiếp xúc nhẹ với chất dinh dưỡng. Các băng cassette được "nạp" hạt giống và lắp vào một cạnh của bồn tắm. Khi cây phát triển, chúng được chuyển sang mép kia của bồn tắm, tách dần ra để lá của cây luôn tạo thành một lớp phủ xanh liên tục nhưng không chồng lên nhau quá nhiều (hình 7). Loại băng tải có khay tách này có hai ưu điểm. Thứ nhất, ánh sáng không bị lãng phí vì nó chỉ chiếu lên lá cây. Thứ hai, việc sản xuất rau xanh liên tục được thực hiện.

Tất nhiên, việc sử dụng băng tải lớn (và phòng thí nghiệm đã sử dụng băng tải dài 10, 20 mét trở lên) đòi hỏi phải tự động hóa chuyển động của băng cassette. Và cánh đồng “Nugget” nhỏ, chẳng hạn như trên một con tàu, được người đầu bếp giám sát. Anh ta sạc các cuộn băng, di chuyển chúng khi cần thiết và thu hoạch vụ mùa.

Có một mô hình mô tả chính xác sự phát triển của cây tùy thuộc vào các điều kiện bên ngoài (và đặc điểm của bản thân cây), bạn có thể rút ra quy luật chuyển động của băng dọc theo băng tải $l = l(t)$, trong đó các lá nằm không có khe hở và xác định thời gian giữa các băng được lắp đặt t. Chính vấn đề vật lý nông nghiệp bài toán này mà chúng tôi khuyên bạn nên tự giải quyết.
