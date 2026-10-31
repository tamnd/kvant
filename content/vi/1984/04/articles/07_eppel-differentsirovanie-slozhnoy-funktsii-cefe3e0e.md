---
id: 1984-4-eppel-differentsirovanie-slozhnoy-funktsii-cefe3e0e
issue: kvant_1984_4
year: 1984
number: "4"
title: Đạo hàm một hàm phức tạp
authors:
  - Эппель Б. С.
rubric: shkola-v-kvante
rubric_sub: Школа в «Кванте»
page_first: 28
page_last: 29
page_labels: 26-27
tag: XU9Q
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 0db3874fbc3be460000e2acc1b547dc59ebfefd8042016ba6f09910b22aa3809
prompt_sha256: draft-1
translated_from: content/ru/1984/04/articles/07_eppel-differentsirovanie-slozhnoy-funktsii-cefe3e0e.md
source_content_sha256: a901df70b8c9497bdfa82aed0636d9ea30d927b5870358f5f205858c3bcbc399
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 26⟧

sóng dây tóc, cường độ của nó tỉ lệ với bình phương gia tốc.

Luật này cũng yêu cầu phát ra sóng điện từ trong ống RENTEN. Các electron, truyền trong chân không sâu trong không gian giữa cực âm và anome, được điện trường gia tốc đến tốc độ cao, sau đó giảm tốc mạnh khi chúng va chạm với anome. Trong trường hợp này, xảy ra gia tốc đáng kể và các electron phát ra sóng điện từ. Loại bức xạ này được gọi là bremsstrahlung.

Hóa ra, khi các electron giảm tốc, chúng phát ra toàn bộ phổ sóng điện từ với các tần số (hoặc bước sóng) khác nhau. Phổ này là liên tục, nhưng nó bị giới hạn ở một tần số tối đa nhất định $v_{\text{max}}$ (giới hạn tần số như vậy chỉ có thể được giải thích theo quan điểm của lý thuyết lượng tử).

Tần số cao nhất (và theo đó, bước sóng nhỏ nhất) được xác định từ điều kiện động năng của electron $eU$ (U là hiệu điện thế giữa anome và cathode) bằng năng lượng của lượng tử phát ra:

$$eU = hv_{\text{max}},$$

Ở đâu

$$v_{\text{max}} = \frac{eU}{h},$$

và theo đó, bước sóng tối thiểu

$$\lambda_{\text{min}} = \frac{c}{v_{\text{max}}} = \frac{ch}{eU} \cdot$$

trong đó $h$ là hằng số Planck và $c$ là tốc độ ánh sáng. Với hiệu điện thế vài chục kilovolt, bước sóng tối thiểu đạt tới phần nhỏ angstrom ($1\mathring{\mathrm{A}} = 10^{-10}\text{ m}$). Bức xạ có khối lượng ngắn như vậy có khả năng xuyên thấu cao và được gọi là bức xạ RENTen.

(*) Sau khi đo thực nghiệm bước sóng tối thiểu $\lambda_{\text{min}}$ và điện áp $V$, chúng ta có thể xác định giá trị của hằng số Planck $h$ từ đẳng thức này. Từ những thí nghiệm như vậy người ta thu được giá trị $h = 6,62 \cdot 10^{-34}\text{Дж} \cdot \text{с}$.

Đạo hàm một hàm phức

V. S. EPPEL

Tất cả các ứng viên đều biết rằng $(\sin x)' = \cos x$. Tuy nhiên, những đẳng thức như $(\sin 2x)' = \cos 2x$ hoặc $(\sin^3 x)' = \cos^3 x$ mà người nộp đơn phạm phải là hoàn toàn không chính xác. Thực tế là hàm $\sin 2x$ và $\sin^3 x$ rất phức tạp và các hàm vi phân bài toán của chúng cũng phức tạp hơn. Ở đây chúng tôi sẽ chỉ ra cách giải quyết bài toán này một cách thực tế.

Các lỗi như $(\sin^3 x)' = \cos^3 x$ phát sinh khi người nộp đơn không biết cách giải mã mục $y = \sin^3 x$ và không thấy trong biểu thức đơn giản này là một hàm phức tạp - thành phần của hai hàm (xem “Đại số và sự khởi đầu của phân tích 9-10”, đoạn 20). Trên thực tế, hàm $y = \sin^3 x$ có ​​được bằng cách thực hiện tuần tự hai thao tác: lấy màu xanh lam của góc $x$ và lập phương số kết quả $\sin x$:

$$x \rightarrow \sin x \rightarrow (\sin x)^3.$$

Trong ký hiệu hàm $y = \sin^3 x$ bạn cần có khả năng nhìn thấy riêng biệt, lần lượt, hai hàm (sin và lũy thừa) mà nó được tạo thành. Điều này sẽ dễ thực hiện hơn nếu hàm này được viết dưới dạng $y = (\sin x)^3$.

Để rõ ràng, ban đầu chúng tôi sẽ giúp người đọc nhận ra các chức năng phức tạp bằng cách sử dụng màu sắc. Trong ví dụ của chúng tôi

$$y = (\sin x)^3 \quad \text{или} \quad y = \sin^3 x$$

Trong trường hợp tổng quát, áp dụng quy tắc đạo hàm của hàm phức (“Đại số và nguyên tắc phân tích 9-10”, đoạn 21)

$$(f(g(x)))' = f'(g(x)) \cdot g'(x)$$

bạn cần có khả năng “nhìn thấy” chức năng này ở dạng $f(g(x))$. Để làm được điều này, màu sắc sẽ giúp chúng ta trước tiên. Khoảng cách giữa hai ví dụ.

$$y = \sin 2x = \sin u, u = 2x$$

$$y' = (\sin u) \cdot (2x)' = (\cos u) \cdot 2 = 2\cos 2x.$$

⟦folio 27⟧

(Nhưng không phải cos 2x.)
Hoàn toàn giống nhau
$$y = \sin^3 x = u^3, \quad u = \sin x;$$
$$y' = (u^3)' \cdot (\sin x)' = (3u^2) \cdot (\cos x) = 3 \sin^2 x \cos x.$$

(Nhưng không phải cos³ x.)
Trong thực tế, việc phân tích một thành phố tùy ý như vậy ngắn hơn và đơn giản hơn, ít nhất là không đưa u vào ký hiệu.

Nghệ thuật phân biệt một chức năng phức tạp nằm ở khả năng chỉ nhìn thấy một chức năng tại thời điểm phân biệt (cụ thể là chức năng đang được phân biệt tại một thời điểm nhất định), trong khi không chú ý đến những chức năng khác - tầm nhìn của họ vẫn mở cho đến thời điểm phân biệt.

Dưới đây là một vài ví dụ minh họa nữa, không giới thiệu chữ “u” trung gian, theo cách vi phân của một hàm phức tạp thường được thực hiện và viết bởi những người có kỹ năng thành thạo về vi phân đó. Chỉ có điều, như trước đây, chúng ta sẽ viết từng hàm khả vi và hàm tùy ý của nó bằng cùng một màu.

$$y = (2x^4 - 5x^2 + 6)^8;$$
$$y' = 8(2x^4 - 5x^2 + 6)^7 \cdot (8x^3 - 10x).$$
$$y = \sqrt{R^2 - x^2} = \left(R^2 - x^2\right)^{\frac{1}{2}};$$
$$y' = \frac{1}{2}\left(R^2 - x^2\right)^{-\frac{1}{2}} \cdot (-2x) = \frac{-x}{\sqrt{R^2 - x^2}}$$

$$y = \sin^3 5x.$$

Có thể thấy ít nhất qua số lượng màu sắc, nó là sự kết hợp của ba chức năng: 1) màu xanh lam; 2) lũy thừa; 3) nhân với 5.

Hãy phân biệt nó:
$$y = \sin^3 5x;$$
$$y' = \left(3 \sin^2 5x\right) \cdot \left(\cos 5x\right) \cdot \left(5\right) = 15 \left(\sin^2 5x\right) \cos 5x.$$

Vì việc thay đổi vị trí của hợp chất không làm thay đổi tích nên không cần phải nói rằng bạn có thể sắp xếp các hàm để lấy vi phân theo bất kỳ thứ tự nào.

Một vài ví dụ nữa:
$$y = \mathrm{tg} x^3; \quad y' = \frac{3x^2}{\cos^2 x^3}.$$
Chức năng

chúng ta lấy vi phân làm tích của một hàm bằng công thức $(uv)' = u'v + v'u$:
$$y' = \left(x^2\right)' \left(\ln x^3\right) + \left(x^2\right)' \cdot \left(\ln x^3\right)' = 2x \ln x^3 + x^2 \cdot \frac{1}{x^3} \cdot \left(3x^2\right) = 2x \ln x^3 + 3x.$$

$$y = 2x^3 - 5x;$$
$$y' = 2x^3 - 5x \ln 2 \cdot \left(3x^2 - 5\right)$$

1. $y = (x^3 + 2)^4$; 2. $y = \sqrt{1 + 5x^2}$;
3. $y = e^{x^2 - 3x}$; 4. $y = \ln (2x^3 - 4x^2)$;
5. $y = \lg (2x^3 - 4x^2)$; 6. $y = 5^{\sin x}$;
7. $y = \log_{0.3}(8x^2 - 2x^3)$;
8. $y = \cos (2x - 1)$; 9. $y = \cos^2 3x$;
10. $y = \sqrt{\mathrm{tg} x}$; 11. $y = x \mathrm{tg}^2 x$;
12. $y = \sin \sqrt{ax}$; 13. $y = \ln \sin x$;
14. $y = 3^{\frac{1}{x}}$; 15. $y = \frac{1}{\cos 2x}$.

16. Chứng minh rằng hàm $y = c \sqrt{1 + x^2}$ đóng vai trò là nghiệm của phương trình vi phân $y' = xy / (1 + x^2)$.

Sửa đổi
1) Ở «Kvant» số 1 trên trang. 57 во втором уравнении bài toán 1 варианта 1 ошибочно напечатано 15 вместе 55.
2) Trong đoạn cuối cùng trên p. 47 «Kvant» Số 2 phía trên chữ in đậm thứ 1, 4, 7 A và các chữ in đậm thứ 1, 3, 5, 6, 8 B nên có một dòng (A, B), bị thiếu do lỗi của nhà in.
