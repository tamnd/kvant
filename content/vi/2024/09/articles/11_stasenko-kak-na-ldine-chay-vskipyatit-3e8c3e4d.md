---
id: 2024-9-stasenko-kak-na-ldine-chay-vskipyatit-3e8c3e4d
issue: kvant_2024_9
year: 2024
number: "9"
title: Cách đun trà trên tảng băng
authors:
  - Стасенко А. Л.
rubric: shkola-v-kvante
rubric_sub: Школа в «Кванте»
page_first: 45
page_last: 46
page_labels: "44"
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 2809d4442416461de3a2dcbd417fffa1622776da90637b04662642ceff30baf8
prompt_sha256: draft-1
translated_from: content/ru/2024/09/articles/11_stasenko-kak-na-ldine-chay-vskipyatit-3e8c3e4d.md
source_content_sha256: 26f4305a7c49bdda9bfc2582d07067b284e893b76a4c0050538d038293f43d7a
translation_model: draft
translation_run: vi-draft-gaps-2026-11-02
translation_quality: draft
---

⟦folio none⟧

---
running_head:
folio:
---

Giống như trên một tảng băng
đun sôi trà
A. STASENKO

Có rất nhiều lũy thừa trong vật lý: tốc độ của một vật rơi tỉ lệ thuận với thời gian, quãng đường di chuyển là bình phương thời gian, thể tích của quả bóng là lập phương bán kính, ..., và dòng năng lượng phát ra, hóa ra, tỉ lệ với lũy thừa bốn của nhiệt độ! Đúng vậy, bất cứ ai cũng có thể bị thuyết phục về điều này nếu họ biết các hằng số cơ bản như hằng số Boltzmann $k$ (Ludwig Boltzmann, 1844–1906), hằng số Planck $h$ (Max Planck, 1858–1947), tốc độ ánh sáng $c$. Thông điệp từ lý thuyết về kích thước và sự tương đồng sẽ hữu ích ở đây.

Vì vậy, bạn cần thu được sự phụ thuộc của mật độ thông lượng năng lượng $q$, kích thước của nó $\frac{J}{\left(m^2 \cdot c\right)}$, vào nhiệt độ $T$, được biểu thị bằng độ Kelvin, K. Rõ ràng là công thức tương ứng phải chứa $kT$, J, với một số lũy thừa $m$, và để đạt được J lũy thừa thứ nhất, giá trị này phải được chia cho $h^{m-1}$, J·s. Và mở chữ ghép $m^2$ ở mẫu số? Tất nhiên, chia cho bình phương tốc độ ánh sáng $c^2$, $m^2/c^2$. Hóa ra $q \sim \frac{(kT)^m}{c^2 h^{m-1}}$.

Không vì giây sẽ xuất hiện ở mẫu số, nên sẽ có
$$\frac{1}{c^2} \cdot c^{m-1} = c^{m-3} = c$$,
từ đâu $m = 4$. Kết quả là chúng tôi có
$$q \sim \frac{(kT)^4}{c^2 h^3} \sim T^4$$.

Đây là định luật Stefan-Boltzmann nổi tiếng (Josef Stefan, 1835–1893). Phức của các hằng số cơ bản, đứng như một thừa số tại $T^4$ và được gọi là hằng số Stefan–Boltzmann, có dạng
$$\sigma = \frac{2\pi^5}{15} \cdot \frac{k^4}{c^2 h^3} \approx 40 \cdot \frac{(1,4 \cdot 10^{-23})^4 \cdot Jx^4/K^4}{(3 \cdot 10^8)^2 m^2/c^2 \cdot (6,63 \cdot 10^{-34})^3 Jx^3 \cdot c^3} = 5,67 \cdot 10^{-8} \cdot Jx/\left(m^2 \cdot c \cdot K^4\right)$$.

DOI: https://doi.org/10.4213/kvant20240904

(Hãy chú ý xem các số được sắp xếp như thế nào: 5, 6, 7, 8.) Định luật thu được mô tả bức xạ của cái gọi là vật đen tuyệt đối. Kết quả là hệ số độ đen được đưa ra nhỏ hơn một.

Đối với nhiều mục đích, chỉ có lũy thừa bốn của nhiệt độ của vật bức xạ là quan trọng. Ví dụ, có thể ước tính nhiệt độ của "bề mặt" Mặt trời mà không cần gửi nhiệt kế tới nó, dựa trên sự cân bằng năng lượng.

Toàn bộ năng lượng do Mặt trời phát ra bằng $\sigma T_C^4 \cdot 4\pi R_C^2$, trong đó $R_C$ là bán kính của Mặt trời. Phần của nó bị đĩa Trái đất chặn lại bằng $\frac{\pi R_3^2}{4\pi L^2}$, ở đây $L$ là khoảng cách giữa Mặt trời và Trái đất. Tổng năng lượng mà Trái đất phát ra là $\sigma T_3^4 \cdot 4\pi R_3^2$. Đánh đồng các dòng năng lượng tới đĩa Trái đất và phát ra từ bề mặt của nó, chúng ta thu được

$$\sigma T_C^4 \cdot 4\pi R_C^2 \cdot \frac{\pi R_3^2}{4\pi L^2} = \sigma T_3^4 \cdot 4\pi R_3^2.$$

Có thể thấy rằng cả hai vế của phương trình này đều có thể giảm đi $\sigma \cdot 4\pi R_3^2$. Điều này có nghĩa là chỉ có mức nhiệt độ thứ tư là quan trọng. Ngoài ra, khả năng có thể đứng được là như nhau đối với tất cả các hành tinh. Thái độ đóng vai trò quan trọng

$$\frac{R_C^2}{4L^2} = \frac{(2R_C)^2}{16L^2} = \left(\frac{\alpha_C}{16}\right)^2$$,

trong đó $\alpha_C$ là kích thước góc của đường kính Mặt trời khi quan sát từ Trái đất, bằng khoảng $10^{-2}$ radian. Kết quả là chúng tôi có

$$\sqrt{\alpha_C} / 2 \cdot T_C = T_3, T_C = 20T_3.$$

Lấy nhiệt độ trung bình của Trái Đất là 300 K, ta được $T_C = 6000$ K.

Lưu ý rằng kích thước góc của đường kính Mặt trăng giống như đối với Mặt trời. Điều này cho phép chúng ta quan sát cả nhật thực toàn phần và nhật thực của ngôi sao của chúng ta.

Không cho phép nó! - người ngư dân kêu lên, đỡ cần câu của mình qua hố băng, - nếu mọi cơ thể đều tỏa ra năng lượng, thì có thể sử dụng một bề mặt phản chiếu có diện tích vừa đủ $S$ đêm, để tập trung bức xạ của băng vào ấm đun nước và đun sôi nó!? Hãy kiểm tra xem nó ra.

Mật độ thông lượng bức xạ mặt trời trên bề mặt Trái đất là $q_C \approx 1000$ J/$\left(m^2 \cdot c\right)$. Bằng cách tập trung bức xạ vào ấm trà,

⟦folio 44⟧

---
running_head:
folio:
---

bị ảnh hưởng bởi một màn hình có diện tích khoảng một mét vuông, chúng ta có một chiếc bếp kilowatt! Do đó, để thu được cùng một dòng từ một tảng băng ở nhiệt độ, chẳng hạn như −3 ° C (270 K), thì cần phải có diện tích bề mặt phản chiếu là $S = \left(\frac{6000}{270}\right)^4 \cdot 1\text{m}^2 \approx 25 \cdot 10^4\text{ m}^2$. Do đó bán kính phản xạ $R = \sqrt{\frac{S}{\pi}} \approx 300\text{ m}$.

Tất nhiên, đáp số của một vật thể do sự đối lưu từ một vật thể nóng lên sẽ tăng lên khi nhiệt độ của nó khác với nhiệt độ môi trường. Điều này có thể được bù đắp bằng cách thêm diện tích phản xạ. Tuy nhiên, ấm trà và tiêu điểm của một thiết bị như vậy (hình parabol hoặc gương cầu) ở độ cao bao nhiêu! – người đánh cá nghĩ, nhưng rồi klev bỏ đi.

Chúc mừng bắt được!
