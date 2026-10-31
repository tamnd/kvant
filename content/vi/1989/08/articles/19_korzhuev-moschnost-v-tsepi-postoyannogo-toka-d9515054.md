---
id: 1989-8-korzhuev-moschnost-v-tsepi-postoyannogo-toka-d9515054
issue: kvant_1989_8
year: 1989
number: "8"
title: nguồn điện một chiều
authors:
  - Коржуев А. В.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 69
page_last: 71
page_labels: 67-69
tag: HM4O
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 7009fce7c6c27fd1ac5108414f02edf74d9e48a3c365ed40ceea70051b0c50b9
prompt_sha256: draft-1
translated_from: content/ru/1989/08/articles/19_korzhuev-moschnost-v-tsepi-postoyannogo-toka-d9515054.md
source_content_sha256: e134fd1086fe0cad2201e335dbcf4face093f343aed6216f6ef75df80f690a95
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 67⟧

nguồn điện một chiều

A. V. KORZHUEV

Chúng ta hãy nhớ lại các nguyên tắc cơ bản được sử dụng ở lời giải bài toán để tính toán mạch điện một chiều.

Giả sử có một mạch kín đơn giản (không phân nhánh) (hình 1), chứa một nguồn dòng điện có EMF và điện trở trong $r$ và một điện trở có điện trở $R$ (còn gọi là điện trở ngoài). Theo định luật Ohm đối với mạch điện như vậy thì dòng điện chạy trong nó

$$I = \frac{\mathcal{E}}{R + r}.$$

Trong trường hợp này, điện áp ở phần bên ngoài của mạch bằng

$$U = \mathcal{E} - Ir,$$

Công suất tỏa ra trên điện trở bằng

$$P_{\text{вн}} = IU,$$

và tổng công suất của nguồn là

$$P_{\pi} = I\mathcal{E}.$$

Bây giờ chúng ta hãy xem xét một số bài toán cụ thể thảo luận trước hết về vấn đề nguồn DC.

Bài toán 1. Mạch điện chứa một nguồn có suất điện động là $\mathcal{E}$ và điện trở trong $r$, và điện trở biến trở $R$ (xem hình 1). Tính tổng công suất do nguồn phát ra, công suất cung cấp cho mạch ngoài của nó (công suất thuần) và hiệu suất của nguồn. Xác nhận sự phụ thuộc của các đại lượng này vào điện trở bên ngoài.

Theo định luật Ôm thì dòng điện chạy qua mạch

$$I = \frac{\mathcal{E}}{R + r}.$$

Công suất tỏa ra trong phần mạch là

⟦folio 68⟧

Pi có điện áp $U$ theo định nghĩa bằng $P = IU$. Trong trường hợp của chúng tôi

$$P_{\text{BH}} = IU = I^2R = \frac{\mathcal{E}^2R}{(R+r)^2}.$$

Tổng công suất của nguồn là

$$P_{\pi} = I\mathcal{E} = \frac{\mathcal{E}^2}{R+r},$$

và hiệu quả của nó là

$$\eta = \frac{P_{\text{BH}}}{P_{\pi}} = \frac{R}{R+r} = \frac{1}{1+r/R}.$$

Bây giờ chúng ta hãy phân tích sự phụ thuộc của tất cả các đại lượng tìm thấy vào điện trở bên ngoài $R$. Có thể thấy rằng khi tăng $R$ thì tổng công suất sẽ giảm và ngược lại, hiệu suất sẽ tăng - khi tăng $R$ thì phần tổng công suất được phân bổ cho phần bên ngoài của mạch ngày càng lớn hơn (so với công suất được phân bổ bởi nguồn bên trong). Kết quả là tình hình phức tạp hơn với sức mạnh được giải phóng. Từ biểu thức $P_{\text{BH}} = \mathcal{E}^2R/(R+r)^2$ suy ra $P_{\text{BH}} = 0$ tại $R = 0$ (điều này hoàn toàn tự nhiên) và tại $R \to \infty$. Rõ ràng, có một giá trị $R$ mà tại đó công suất hữu ích là tối đa. Dễ dàng tìm thấy nó bằng cách tiếp tục $P_{\text{BH}}$ thông qua mức kháng cự $R$ và đánh đồng đạo hàm này bằng 0:

$$P'_{\text{BH}} = \frac{\mathcal{E}^2(R+r)^2 - 2\mathcal{E}^2R(R+r)}{(R+r)^4} = 0,$$

chúng ta lấy nó từ đâu

$$R = r$$

— $P_{\text{BH}}$ là lớn nhất và bằng $\mathcal{E}^2/(4r)$, với điều kiện là điện trở bên ngoài và bên trong bằng nhau. Tuy nhiên, hiệu quả tương đương

$$\eta = \frac{R}{R+R} = \frac{1}{2},$$

tức là một nửa tổng công suất được tạo ra được phân bổ cho điện trở trong của nguồn. Đổi lại, hiệu suất đạt cực đại và bằng 1 tại $R \to \infty$, nhưng $P_{\text{BH}}$ có xu hướng bằng 0. Vì vậy, không thể đạt được đồng thời năng lượng đầu ra tối đa và hiệu quả nhất trong một mạch như vậy. Chúng ta thua về mặt quyền lực nhưng lại đạt được hiệu quả và ngược lại.

Đồ thị về sự phụ thuộc của $P_{\text{BH}}$, $P_{\pi}$ và $\eta$ vào điện trở ngoài $R$ được thể hiện ở hình 2. Các đồ thị xác nhận rõ ràng rằng ở $R = 0$ toàn bộ công suất được giải phóng tại điện trở trong của nguồn. Ở $R = r$ công suất truyền ra mạch ngoài bằng một nửa tổng công suất phát ra và hiệu suất là 1/2. Khi $R$ tăng lên, đồ thị phụ thuộc $P_{\pi}(R)$ và $P_{\text{BH}}(R)$ ngày càng gần nhau hơn, công suất giải phóng ở điện trở trong giảm dần. Ở $R \gg r$ gần như toàn bộ năng lượng được tạo ra được giải phóng ra mạch ngoài và hiệu suất có xu hướng bằng 1.

Bài toán 2. Từ mạch hiển thị ở hình 1, luồng 1. Giả sử đã biết $\mathcal{E}$ và $r$ của nguồn, hãy tính công suất giải phóng ở mạch ngoài, tổng công suất và hiệu suất

⟦folio 69⟧

nguồn. Phân tích sự phụ thuộc của các đại lượng này vào dòng điện trong mạch.

Rõ ràng là

$$P_{\pi} = I \mathcal{E},$$

và $P_{\mathrm{bH}}$ sẽ được tìm thấy bằng cách trừ đi tổng công suất công suất phân bổ cho điện trở trong của nguồn:

$$P_{\mathrm{bH}} = \mathcal{E} I - I^2 r.$$

Khi đó hiệu quả

$$\eta = \frac{P_{\mathrm{bH}}}{P_{\pi}} = \frac{\mathcal{E} I - I^2 r}{\mathcal{E} I} = 1 - \frac{I r}{\mathcal{E}}.$$

Khi dòng điện tăng $I$, tổng công suất tăng tuyến tính (kể từ $\mathcal{E} = \text{const}$) và hiệu suất giảm - có thể đạt được sự gia tăng dòng điện bằng cách giảm điện trở bên ngoài và do đó giảm tỷ lệ $P_{\mathrm{bH}}$ so với công suất giải phóng ở điện trở trong. Sự phụ thuộc của $P_{\mathrm{bH}}$ vào $I$ là bậc hai. $P_{\mathrm{bH}}$ biến mất tại $I = 0$ và tại $I = \mathcal{E}/r$. Điều này có nghĩa là có một giá trị hiện tại nhất định mà tại đó công suất hữu ích là tối đa. Vi phân theo dòng điện, chúng ta thấy

$$P'_{\mathrm{bH}} = \mathcal{E} - 2 I r = 0, \text{ если } I = \frac{\mathcal{E}}{2 r}.$$

Hơn nữa, $P_{\mathrm{bH} \max} = \mathcal{E}^2/(4 r)$, phù hợp với nhiệm vụ 1.

Để minh họa trực quan kết quả thu được, chúng ta hãy xây dựng biểu đồ về sự phụ thuộc của tất cả các giá trị tìm thấy vào dòng điện (hình 3). Như ở bài toán trước, công suất tối đa tương ứng với giá trị hiệu suất là 1/2; đồng thời $I = \mathcal{E}/r$ $P_{\mathrm{bH}} = 0$ (trường hợp điện trở ngoài bằng 0) và $\eta = 0$.

Bài toán 3. Người ta biết rằng theo thời gian, một cục pin bao gồm khí

$$\frac{\mathcal{E}^2}{R + r} \quad \frac{\mathcal{E}^2}{R} \quad \frac{\mathcal{E}}{R + r}$$

Các phần tử Vanich, “ngồi xuống” (sức điện động của nó giảm xuống). Tổng công suất và hiệu suất trong mạch ngoài phụ thuộc như thế nào vào emf của nguồn $(\text{см. рис. 1})?$ Giả sử điện trở trong $r$ của nguồn không thay đổi.

Như đã thu được trong bài toán 1,

$$P_{\pi} = \frac{\mathcal{E}^2}{R + r}, \quad P_{\mathrm{bH}} = \frac{\mathcal{E}^2 R}{(R + r)^2},$$

$$\eta = \frac{R}{R + r}.$$

Từ các biểu thức này, rõ ràng là khi $\mathcal{E}$ giảm, cả công suất tổng và công suất giải phóng vào mạch ngoài đều giảm, cả hai đều tuân theo định luật bậc hai, và hiệu suất không đổi cho đến khi emf nguồn bằng 0 và quá trình giải phóng công suất dừng hoàn toàn.

Các đồ thị tương ứng được hiển thị trong hình 4.

Bài toán 4. Một động cơ điện có điện trở cuộn dây phần ứng là $R$, được cấp nguồn bởi nguồn điện áp không đổi $U$, trong khi dòng điện $I$ (hình 5) chạy qua nó. Tính công suất tiêu thụ, công suất tổn thất do cuộn dây nóng lên và hiệu suất của động cơ. Phân tích sự phụ thuộc của các giá trị được chỉ định vào dòng điện trong động cơ.

Động cơ lấy điện từ nguồn

$$P_{\mathrm{ot}} = I U.$$

Trong trường hợp này, theo định luật Joule-Lenz, nhiệt năng được dùng để làm nóng cuộn dây

$$P_{\tau} = I^2 R.$$

Sự khác biệt giữa các giá trị này
