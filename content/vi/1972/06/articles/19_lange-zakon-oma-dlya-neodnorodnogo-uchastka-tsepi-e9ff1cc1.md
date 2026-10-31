---
id: 1972-6-lange-zakon-oma-dlya-neodnorodnogo-uchastka-tsepi-e9ff1cc1
issue: kvant_1972_6
year: 1972
number: "6"
title: Định luật Ohm đối với phần không đồng nhất của mạch điện
authors:
  - Ланге В. Н.
rubric: ekzamenatsionnye-materialy
rubric_sub: Экзаменационные материалы
page_first: 61
page_last: 62
page_labels: 59-60
tag: B2MJ
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 7d0cc753d4db7b7b9010be808dda7880aef8e1f97010b7bac1091f2ae6457462
prompt_sha256: draft-1
translated_from: content/ru/1972/06/articles/19_lange-zakon-oma-dlya-neodnorodnogo-uchastka-tsepi-e9ff1cc1.md
source_content_sha256: 54785fcab857f77c49d81c3625e0c43a2f7245a3b42b9ac8f87339b5d5aab225
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 59⟧

Định luật Ohm đối với một phần của mạch điện, cho phép tăng cường độ dòng điện chạy qua nó, có dạng sau:

$$I = \frac{U}{R}.$$

Trong công thức này, $R$ là điện trở của đoạn mạch, $U$ là hiệu giữa điểm bắt đầu và điểm kết thúc tiềm năng của đoạn mạch, tức là

$$U = \varphi_1 - \varphi_2.$$

Tuy nhiên, luật viết dưới dạng này không phải lúc nào cũng được áp dụng. Để chỉ ra điều này, hãy xem xét mạch đơn giản nhất bao gồm một nguồn

$$\begin{array}{c}
I \\
R
\end{array}$$

Cơm. 1.

dòng điện có suất điện động $E$ và điện trở trong $r$ và điện trở $R$ (Hình 1). Chia chuỗi này thành hai phần $ARB$ và $BEA$. Khi áp dụng cho phần $ARB$, công thức (1) cho:

$$I_R = \frac{U_{AB}}{R} = \frac{\varphi_A - \varphi_B}{R}.$$

Chúng ta hãy thử sử dụng cùng một công thức (1) để tính cường độ hiện tại, tìm kiếm phần $BEA$. Điểm đầu và điểm cuối của nó lần lượt là các điểm $B$ và $A$. Đó là lý do tại sao

$$I_E = \frac{U_{BA}}{r} = \frac{\varphi_B - \varphi_A}{r}.$$

Nếu bạn không chú ý đến dấu, thì tử số của biểu thức (2) và (3) trùng nhau, trong khi mẫu số nói chung là khác nhau. Vì vậy, chúng ta phải kết luận rằng

$$I_R \neq I_E,$$

và điều này tất nhiên không sai, vì trong mạch không mang tính giải trí, cường độ dòng điện phải giống nhau ở mọi nơi. Nguyên nhân của lỗi là do công thức (1) chỉ được áp dụng cho các phần đồng nhất của mạch điện, tức là cho các phần không chứa nguồn dòng điện (tế bào điện, pin, máy điện môi, tế bào quang điện, v.v.). Phần $BEA$ không đồng nhất - nó chứa nguồn hiện tại có e. d. c.

Công thức định luật Ohm đối với một phần không đồng nhất của mạch điện như thế nào? Hóa ra có thể dễ dàng thu được biểu thức mong muốn từ định luật Ohm đối với mạch kín

$$I = \frac{E}{R + r}.$$

Chúng ta hãy giảm đẳng thức (4) thành mẫu số chung:

$$IR + Ir = E.$$

Số hạng đầu tiên bao gồm các đại lượng liên quan đến diện tích đồng nhất $ARB$ (xem Hình 1), và dựa trên đẳng thức (1) chúng ta có thể viết

$$IR = U_{AB} = \varphi_A - \varphi_B.$$

Khi đó biểu thức (5) có thể được viết lại như sau:

$$Ir = E + (\varphi_B - \varphi_A),$$

Ở đâu

$$I = \frac{E + (\varphi_B - \varphi_A)}{r} = \frac{E + U_{BA}}{r}.$$

Khi rút ra công thức (6), chúng tôi đã xem xét một phần không đồng nhất của mạch điện, điện trở của nó bao gồm điện trở trong của nguồn. Nói chung

⟦folio 60⟧

một phần không đồng nhất của mạch có thể chứa các điện trở khác nhau (một phần, đôi khi cần tính đến điện trở của dây) và khi đó công thức (6) được viết dưới dạng

$$I = \frac{(\varphi_1 - \varphi_2) + E}{R_\pi},$$

trong đó $R_\pi$ là tổng điện trở của tiết diện.

Từ công thức (7) định luật Ohm đối với mạch kín và đối với phần đồng nhất của chuỗi tuân theo các trường hợp đặc biệt.

Thật vậy, đối với một chuỗi khép kín $\varphi_1 = \varphi_2$ (vì trong trường hợp này phần đầu và phần cuối của “phần” trùng nhau). Khi đó từ công thức (7) ta có

$$I = \frac{E}{R_\pi}.$$

Trong trường hợp phần đồng nhất của chuỗi $E = 0$ và công thức (7) có dạng

$$I = \frac{\varphi_1 - \varphi_2}{R}.$$

(Ở đây $R$ không còn chứa điện trở trong của nguồn nữa.)

Khi sử dụng công thức (7) cho lời giải bài toán cần nhớ rằng e. d.s. được coi là dương nếu khi di chuyển dọc theo một phần đồng nhất của chuỗi từ đầu đến cuối, trước tiên chúng ta vượt qua sọc âm và sau đó là sọc dương. Nếu, do lời giải, cường độ dòng điện thu được giá trị âm, thì điều này có nghĩa là dòng điện trong một phần của mạch chạy theo hướng “ngược lại”, tức là từ cuối phần đó đến phần đầu.

Bây giờ chúng ta hãy xem xét một số bài toán, có thể giải dễ dàng bằng công thức (7).

Bài 1. Xác định dòng điện chạy qua hình ở Hình 2, phần $AB$. E.m.f. nguồn

Cơm. 2.

biệt danh $E = 20 \text{ } \theta$, nội kháng $r = 1 \text{ } \omega$; thế năng của các điểm $A$ và $B$ lần lượt là $\varphi_A = 15 \text{ } \theta$, $\varphi_B = 5 \text{ } \theta$; điện trở dây $R = 3 \text{ } \omega$.

Lời giải. Coi điểm $A$ là điểm bắt đầu của phần và điểm $B$ là điểm kết thúc nên lấy e. d.s. với dấu trừ, chúng ta thu được từ công thức (7):

$$I = \frac{(15\theta - 5\theta) - 20\theta}{3\omega + 1\omega} = -2,5 \text{ } a.$$

Dấu âm cho biết dòng điện chạy theo hướng $B \rightarrow A$, nghĩa là từ điểm có điện thế thấp hơn đến điểm có điện thế cao hơn. Nhân tiện, hành vi “không tự nhiên” này của dòng điện thường được quan sát thấy bên trong tất cả các nguồn dòng điện.

Nhiệm vụ 2. Hai phần tử được kết nối “hướng” vào nhau (Hình 3). Xác định sự chênh lệch giữa dòng điện tiềm năng $A$ và $B$

Cơm. 3.

(tại các cực của pin) nếu $E_1 = 1,4 \text{ } \theta$, $r_1 = 0,4 \text{ } \omega$; $E_2 = 1,8 \text{ } \theta$, $r_2 = 0,6 \text{ } \omega$.

Lời giải. Công thức (7) áp dụng cho phần $AE_2B$ cho

$$I = \frac{(\varphi_A - \varphi_B) + E_2}{r_2}.$$

Đối với phần $BE_1A$ chúng ta có

$$I = \frac{(\varphi_B - \varphi_A) - E_1}{r_1} = -\frac{(\varphi_A - \varphi_B) + E_1}{r_1}.$$

Vì dòng điện trong cả hai phần là như nhau (mục tiêu không được phân nhánh), chúng ta có thể đánh đồng vế phải của các biểu thức này và giải phương trình thu được:
