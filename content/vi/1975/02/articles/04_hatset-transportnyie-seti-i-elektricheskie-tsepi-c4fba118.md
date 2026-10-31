---
id: 1975-2-hatset-transportnyie-seti-i-elektricheskie-tsepi-c4fba118
issue: kvant_1975_2
year: 1975
number: "2"
title: Mạng lưới giao thông và mạch điện
authors:
  - Хацет А. Б.
rubric: osnovnye-stati
page_first: 12
page_last: 19
page_labels: 10-16
tag: HH2N
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 4bdcfa91803a02beab9b3a4a097307e2e65e7f63fb8141ea2cc40db9b03548c1
prompt_sha256: draft-1
translated_from: content/ru/1975/02/articles/04_hatset-transportnyie-seti-i-elektricheskie-tsepi-c4fba118.md
source_content_sha256: 287c874e504e895bced702185aee7c76ca167f5b6a64b358705f62b44947a3a0
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 10⟧

1. Lời giải nên tối ưu
Cần tổ chức vận chuyển hàng hóa liên tục từ điểm A đến địa điểm B. Có đủ trọng tải tự động, thực tế không giới hạn đến điểm A, nhưng lượng hàng gửi từ A đến B trong một đơn vị thời gian bị hạn chế do điều kiện đường xá.

Điểm A và B được nối với nhau bằng mạng lưới đường, sơ đồ như hình 1. Số 1 trên sơ đồ này biểu thị điểm xuất phát A, số 5 - điểm đến B, số 2, 3, 4 - điểm trung gian - nút giao đường. Hướng chuyển động được chỉ định bởi các mũi tên. Mỗi đoạn đường có thể đi qua trong một đơn vị thời gian không quá một số tấn hàng hóa nhất định (được xác định bởi chiều rộng của đoạn đường tại điểm hẹp nhất, tính chất của bề mặt, tình trạng của các địa điểm, v.v.). Hãy gọi con số này là dung lượng và giả sử nó được biết đến với từng đoạn của đường dẫn nối một hoặc hai điểm trên sơ đồ của chúng ta.

⟦folio 11⟧

Năng lực của đoạn dẫn từ điểm $i$ đến điểm $j$ (đoạn $i - j$) sẽ được thể hiện qua $a_{ij}(T/\mu a c)$.

Giả sử rằng chúng ta cố gắng gửi càng nhiều hàng hóa càng tốt trong mỗi đơn vị thời gian từ $A$ đến $B$. Tuy nhiên, bạn không nên nghĩ rằng để làm được điều này, bạn cần gửi $a_{12}$ tấn hàng ngày dọc theo đoạn $1 - 2$ và $a_{13}$ tấn dọc theo đoạn $1 - 3$: xét cho cùng, có thể do các đoạn khác của tuyến đường không đủ năng lực nên “ùn tắc giao thông” sẽ hình thành tại một số điểm trung gian, do đó giao thông sẽ bị gián đoạn hoặc dừng hẳn. Ví dụ: nếu $a_{12} > a_{23} + a_{24}$ thì sẽ xảy ra “ùn tắc giao thông” tại giao lộ 2. Điều này có nghĩa là để tổ chức vận chuyển hàng hóa tốt nhất từ $A$ đến $B^*$), chúng ta cần giải quyết vấn đề bài toán sau: xác định số tấn hàng hóa cần thiết hàng ngày cho mỗi đoạn của mạng lưới đường kết nối các điểm $A$ và $B$, để không vượt quá công suất của bất kỳ phần nào của mạng lưới, không để tạo ra một “ùn tắc giao thông” duy nhất tại các điểm trung gian và để số lượng hàng hóa được giao hàng ngày đến $B$ được tối đa hóa.

*) Tổ chức cung ứng như vậy được gọi là tối ưu.

Lượng hàng hóa cần vận chuyển qua đoạn $i - j$ hàng ngày (khối lượng vận chuyển) sẽ được ký hiệu là $x_{ij}(T/\mu a c)$.

Vì vậy, bài toán được đặt. Nhưng làm thế nào để giải quyết nó?

2. Lật qua số cũ «Kvant»

Nhìn qua bộ tạp chí «Kvant» năm 1970, trong phần “Mạng và dòng” của M.I. Trong bài báo “Mạng lưới kết hợp và vận chuyển” của Bashmkov, chúng tôi tìm thấy bài toán của mình, chỉ ở những bộ quần áo “giảm giá” hơn một chút.

Hóa ra các sơ đồ gồm các điểm và mũi tên (như trong Hình 1) được gọi là đồ thị có hướng, với các điểm là các đỉnh và các mũi tên là các cạnh của đồ thị. Mỗi cung có một hướng nhất định (do đó có tên là đồ thị có hướng), do đó một trong các điểm nối của nó là điểm đầu, điểm còn lại là điểm cuối cùng; họ cũng nói rằng cung rời khỏi đỉnh ban đầu và đi vào đỉnh cuối cùng. Đỉnh, là đỉnh đầu tiên (cuối cùng) của tất cả các cung được kết nối với nó, được gọi là đầu vào (đầu ra) của đồ thị (trong Hình 1 - đỉnh 1 và 5 tương ứng). Đồ thị có hướng có một đầu vào và một đầu ra là mạng biên (đây là đồ thị trong Hình 1). Các đỉnh truyền tải mạng không phải là đầu vào hoặc đầu ra được gọi là các đỉnh chiếu.

Hãy dừng dòng thuật ngữ này trong một phút và dịch hai thuật ngữ. Tất nhiên, việc thay thế các từ “mạng lưới đường” - “mạng lưới giao thông”, “điểm” - “đỉnh”, “đoạn đường đi” - “vòng cung” không đưa chúng ta đến gần hơn với lời giải. Nhưng hóa ra chúng tôi không đặc biệt quan tâm đến khoảng cách như vậy. Kiên nhẫn hơn một chút, bạn sẽ đi đến công thức nổi tiếng của bài toán trong toán học.

Giá trị yêu cầu của lưu lượng giao thông $x_{ij}$ được gọi là luồng dọc

⟦folio 12⟧

cung $i-j$ và tổng các luồng dọc theo tất cả các cung rời khỏi đầu vào mạng (trong trường hợp của chúng tôi $x_{12} + x_{13}$) là luồng qua mạng. Bây giờ, cuối cùng, bài toán của chúng ta có thể được trao “đồng phục nghi lễ”.

Bài toán về lưu lượng tối đa. Một mạng lưới giao thông được đưa ra và công suất được chỉ định cho từng cung Komori. Cần phải xác định các luồng dọc theo các cung mạng không vượt quá khả năng thông lượng tương ứng, sao cho đối với bất kỳ đỉnh trung gian nào, tổng các luồng dọc theo các cung đến bằng tổng các luồng dọc theo các cung đi (“điều kiện liên tục của luồng”) và sao cho luồng qua mạng là thấp nhất có thể.

Vì vậy, bài toán của chúng tôi là trường hợp đặc biệt bài toán về lưu lượng tối đa (điều kiện liên tục của luồng là điều kiện quen thuộc để không xảy ra ùn tắc giao thông). Sử dụng ký hiệu trên, nó có thể được hình thành như sau:

Tìm luồng $x_{ij}$ tối đa dọc theo các cung, tại đó đạt được giá trị cực đại của luồng qua mạng
$$X = x_{12} + x_{13}$$

(1)
theo các điều kiện sau:
a) xác định công suất hồ quang
$$x_{12} \leq a_{12}, x_{13} \leq a_{13}, x_{23} \leq a_{23},$$
$$x_{24} \leq a_{24}, x_{34} \leq a_{34}, x_{35} \leq a_{35},$$
(2)
tính liên tục của dòng chảy tại các đỉnh đi qua
$$x_{12} - x_{23} - x_{24} = 0,$$
$$x_{13} + x_{23} - x_{34} - x_{35} = 0,$$
$$x_{24} + x_{34} - x_{45} = 0.$$

(3)
Với luồng ổn định, số lượng hàng hóa xuất khẩu từ lối vào 1 phải bằng số lượng hàng hóa đến lối ra 5 cùng một lúc (nếu không sẽ vi phạm điều kiện liên tục của luồng):
$$X = x_{12} + x_{13} = x_{35} + x_{45}.$$

(4)
Vì chúng tôi đã tìm ra công thức bài toán của chúng tôi trong M.I. Bài viết của Bashmkov, việc tìm kiếm lời giải ở đó cũng là điều đương nhiên. Và thực sự, khi đi sâu hơn vào bài đọc, chúng tôi tìm thấy phần trình bày về thuật toán Ford-Folkerson, với sự trợ giúp của nó, bạn có thể xác định tất cả các giá trị của $x_{ij}$ (tuy nhiên, giả sử rằng đây là số nguyên). Chỉ cần kiên nhẫn; Để hiểu thuật toán và có thể áp dụng nó, bạn sẽ phải làm việc chăm chỉ. Sẽ không có gì đáng ngạc nhiên nếu những độc giả không thích tính toán sẽ hỏi vào thời điểm này: liệu có thể làm khác đi không?

3. Ôi đầy sự tương tự

Nhìn bên ngoài phương trình (3). Theo một cách nào đó, chúng rất quen thuộc với chúng ta... Bah, nhưng nếu mạng lưới giao thông được coi là một mạch điện và khối lượng vận chuyển $x_{ij}$ là cường độ dòng điện theo các nhánh của mạch, thì phương trình (3) chỉ đơn giản biểu thị định luật Kirchhoff thứ 1 cho các nút trung gian của chuỗi: theo cáo buộc, tổng dòng điện trong một nút bằng 0 (nghĩa là tổng dòng điện chạy vào một nút bằng tổng dòng điện chạy trong một nút từ nút)!

Đúng, sự tương tự này chưa hoàn chỉnh, vì định luật Kirchhoff thường được xây dựng cho một mạch kín và áp dụng cho mọi mạch không đóng, và các điều kiện như (3) không đúng với các nút cực trị 1 và 5. Tuy nhiên, có thể thay đổi bài toán về dòng chảy sao cho ghi nhận được sự phân kỳ của thiết bị. Với mục đích này, chúng tôi sẽ không đưa một cung giới hạn bổ sung vào mạng truyền tải mà sử dụng luồng dọc theo nó bằng $X$, tức là luồng qua mạng. Theo mạng tổng quát thu được, luồng sẽ tạo một đường dẫn khép kín từ lối vào đến lối ra dọc theo một mạng lưới giao thông nhất định, sau đó từ lối ra đến lối vào dọc theo một vòng cung bổ sung.

Khi đó bài toán của chúng ta có thể được phát biểu lại như sau: cũng xác định vận chuyển tổng quát $x_{ij}$, trong đó

⟦folio 13⟧

Cơm. 2.

chúng tôi truy cập giá trị tối đa $X$ (bảy hỗ trợ) theo các hạn chế (2) và các điều kiện (3) và (4) về tính liên tục của luồng ở tất cả các nút:

$$X - x_{12} - x_{13} = 0,$$
$$x_{12} - x_{23} - x_{24} = 0,$$
$$x_{13} + x_{23} - x_{34} - x_{35} = 0,$$
$$x_{24} + x_{34} - x_{45} = 0,$$
$$x_{35} + x_{45} - X = 0.$$

Kết quả hoàn toàn tương tự với định luật Kirchhoff, và do đó câu hỏi được đặt ra: liệu có thể xây dựng một mô hình điện của mạng lưới giao thông trong đó dòng điện yêu cầu dọc theo các cung sẽ tương ứng với dòng điện trong các nhánh, được xác định trực tiếp bằng phép đo mà không cần bất kỳ tính toán nào không?

Chúng tôi sẽ chỉ ra rằng một mô hình như vậy có thể được xây dựng.

Đương nhiên, các cung của mạng trong mô hình này phải tương ứng với các nhánh của mạch điện và đỉnh phải tương ứng với các nút của mạch.

Quét nó lên. Chúng ta sẽ sử dụng ký hiệu sau: $\sigma$ - nguồn dòng điện theo hướng chỉ định, $a$ - cường độ dòng điện trong nhánh; $\mu$ — nguồn hướng, $u$ — cường độ hướng trong nhánh; $\beta$ là một diode truyền dòng điện theo hướng từ trái sang phải.

Để dòng điện chạy qua mạch điện thì phải có một lực điện nào đó tồn tại trong mạch điện đó. Do đó, trong nhánh bổ sung của mạch, nguồn một chiều

⟦folio 14⟧

Cơm. 4.

Đồng thời, các nút $\alpha$ và $\beta$ xuất hiện trong sơ đồ nhánh, không được vận chuyển. Hướng và độ lớn của dòng điện trong nhánh $\alpha - M - \beta$ chứa nguồn dòng được thực hiện bởi nguồn này; chiều dòng điện trong nhánh $\alpha - N - \beta$ được xác định bởi diode; Chúng ta biểu thị cường độ dòng điện trong đó bằng $I_{ij}$. Chúng ta biểu thị dòng điện trong nhánh $i - \alpha$ và $\beta - j$ lần lượt là $\tilde{x}_{ij}$ và $\tilde{y}_{ij}$; chiều của các dòng điện này được chỉ ra trên sơ đồ.

Áp dụng định luật Kirchhoff cho:
1) tại nút $\alpha$: $\tilde{x}_{ij} + I_{ij} = a_{ij}$ hoặc $I_{ij} = a_{ij} - \tilde{x}_{ij}$ theo tính chất của diode $I_{ij} \geq 0$, do đó,
$$\tilde{x}_{ij} \leq a_{ij},$$
(6)
2) tại nút $\beta$: $a_{ij} = \tilde{y}_{ij} + I_{ij}$, tức là
$$\tilde{y}_{ij} = \tilde{x}_{ij}.$$
(7)

Điều này có nghĩa là dọc theo nhánh chính $i - j$ của mạch có một dòng điện theo hướng nhất định (từ nút $i$ đến nút $j$), giá trị của nó $\tilde{x}_{ij}$ lần lượt không vượt quá công suất $a_{ij}$; theo quy tắc xây dựng mô hình $U = 1$.

Chúng tôi khẳng định rằng dòng điện $\tilde{x}_{ij}$, được thiết lập trong các nhánh chính của mô hình vận chuyển điện, bằng về mặt số với khối lượng vận chuyển dọc theo các cung tương ứng và cho lời giải bài toán mức tối đa

⟦folio 15⟧

luồng nom cho mạng này. Trong trường hợp này, dòng điện $\tilde{X}$ trong nhánh bổ sung của mô hình bằng với lưu lượng tối đa qua mạng.

Nếu chúng ta chứng minh được điều này, thì mô hình được xây dựng sẽ giải quyết hoàn toàn bài toán của chúng ta: đủ rồi, hãy đưa mô hình vào hoạt động, thay đổi dòng điện $x_{ij}$ trong các nhánh bằng một ampe kế!

4. Vì vậy - hãy bắt tay vào làm việc

Để đảm bảo rằng các giá trị số của dòng điện $\tilde{x}_{ij}$ trong các nhánh của mô hình là lưu lượng giao thông cho lời giải bài toán về luồng tối đa, cần phải chứng minh rằng ở các điều kiện $\tilde{x}_{ij} = \tilde{x}_{ij}$ (2) và (3) được thỏa mãn và các giá trị luồng $X$ trong mạng được lấy là giá trị lớn nhất có thể.

Chúng tôi đã chứng minh không phải phần đầu tiên của tuyên bố này. Trên thực tế, khi viết các bất đẳng thức (6) cho tất cả các nhánh của mô hình $\tilde{x}_{12} \leq a_{12}, \tilde{x}_{13} \leq a_{13}, \tilde{x}_{23} \leq a_{23}, \tilde{x}_{24} \leq a_{24}, \tilde{x}_{34} \leq a_{34}, \tilde{x}_{35} \leq a_{35}, \tilde{x}_{45} \leq a_{45}$, (9), chúng ta thu được điều đó đối với dòng điện $\tilde{x}_{ij}$ điều kiện (2) được thỏa mãn và áp dụng định luật Kirchhoff thứ 1 cho tất cả các nút chính của mô hình, chúng ta thu được năm điều kiện tương ứng (3) cho dòng điện $\tilde{x}_{ij}$.

Điều này có nghĩa là tất cả những gì còn lại là chứng minh rằng giá trị $\tilde{X}$ trong mạch điện là giá trị lớn nhất có thể có của từ thông $X$, phù hợp với điều kiện (2) và (3). Bằng chứng của thực tế này bao gồm hai phần.

1. Trước tiên chúng ta hãy chỉ ra rằng với mọi giá trị của biến $x_{ij}$ thỏa mãn điều kiện (2) và (3), thì bất đẳng thức
$$\tilde{X} = x_{12} + x_{13} \leq \sum_{i,j} a_{ij}u_{ij},$$ (11)

trong đó $u_{ij}$ là giá trị số của điện áp trong nhánh $i - j$ và tổng được lấy trên tất cả các nhánh của mạch điện *), nghĩa là, chúng tôi sẽ chỉ ra rằng đối với bất kỳ lưu lượng vận chuyển cho phép nào dọc theo các cung vận chuyển mạng, lưu lượng $X$ qua mạng không vượt quá số $\sum_{i,j} a_{ij}u_{ij}$.

Do bất đẳng thức (2) và tính không âm của $u_{ij}$ (xem (8)), chúng ta có $x_{ij}u_{ij} \leq a_{ij}u_{ij}$; kể từ đây,
$$\sum_{i,j} x_{ij}u_{ij} \leq \sum_{i,j} a_{ij}u_{ij}.$$ (12)

Bây giờ chúng ta hãy nhớ rằng $u_{ij} = p_i - p_j$, trong đó $p_i, p_j$ là các điện thế tương ứng với các nút. Đó là lý do tại sao
$$\sum_{i,j} x_{ij}u_{ij} = \sum_{i,j} x_{ij}(p_i - p_j) = x_{12}(p_1 - p_2) + x_{13}(p_1 - p_3) + x_{23}(p_2 - p_3) + x_{24}(p_2 - p_4) + x_{34}(p_3 - p_4) + x_{35}(p_3 - p_5) + x_{45}(p_4 - p_5) = p_1(x_{12} + x_{13}) + p_2(-x_{12}) + p_2(x_{13} - x_{23}) + p_3(-x_{13} - x_{23}) + p_4(-x_{24} - x_{34}) + p_5(-x_{35} - x_{45}).$$

Các biểu thức trong ngoặc đơn tại $p_2, p_3$ và $p_4$ bằng 0 (xem (3)); khi $p_1$ và $p_5$ bằng $X$ và $-X$ (xem (4)), $p_1 - p_5 = U = 1$; Đó là lý do tại sao
$$\sum_{i,j} x_{ij}u_{ij} = p_1X - p_5X = (p_1 - p_5)X = X.$$ (13)

Xét (12), ta thu được bất đẳng thức cần tìm
$$\tilde{X} \leq \sum_{i,j} a_{ij}u_{ij}.$$ (14)

*) Ký hiệu $\sum_{ij}$ biểu thị tổng các số hạng của loại đang được xem xét, tương ứng với tất cả những gì có thể có đối với một tập hợp các giá trị chỉ mục bài toán cho trước $i, j$. Trong trường hợp của chúng tôi
$$\sum_{i,j} a_{ij}u_{ij} = a_{12}u_{12} + a_{13}u_{13} + a_{23}u_{23} + a_{24}u_{24} + a_{34}u_{34} + a_{35}u_{35} + a_{45}u_{45}.$$

⟦folio 16⟧

Cơm. 5.

Điều này có nghĩa là $\tilde{X}$ là giá trị cao nhất có thể có của $X$.

Để chứng minh đẳng thức (14), chúng ta sử dụng sự tương ứng (8), mô tả tính chất của một diode lý tưởng:

$$u_{ij} (a_{ij} - \tilde{x}_{ij}) = 0$$ hoặc $a_{ij} u_{ij} = \tilde{x}_{ij} u_{ij}$.

Nó ngay sau đó

$$\sum_{i,j} a_{ij} u_{ij} = \sum_{i,j} \tilde{x}_{ij} u_{ij}.$$ (15)

Vì các dòng điện $\tilde{x}_{ij}$, $\tilde{X}$ thỏa mãn các tương ứng (1), (4) như đối với $x_{ij}$ và $X$, nên

$$\sum_{i,j} \tilde{x}_{ij} u_{ij} = \tilde{X}.$$ (16)

5. Hãy tự mình thử

Từ các phần tử giống nhau (được lý tưởng hóa!)—nguồn dòng điện, nguồn điện áp và điốt—các mô hình điện có thể được xây dựng cho lời giải và các tối ưu hóa bài toán khác liên quan đến mạng lưới giao thông. Chúng ta hãy xem xét ở đây một bài toán như vậy, có ý nghĩa quan trọng hơn trong kinh tế học.

Bài toán về việc giảm thiểu chi phí vận chuyển. Giả sử có một mạng lưới giao thông và người ta biết rằng chi phí vận chuyển một đơn vị hàng hóa dọc theo đường $i - j$ bằng $c_{ij}$ (xem Hình 5). Cần xác định khối lượng vận chuyển $x_{ij}$ bằng đường hàng không

Cơm. 6.

⟦folio none⟧

gam của mạng, trong đó 1 đơn vị hàng hóa sẽ được vận chuyển từ đầu vào của mạng đến đầu ra của mạng và tổng chi phí vận chuyển sẽ ở mức tối thiểu.

Vận chuyển $x_{ij}$ đơn vị hàng hóa dọc theo một vòng cung $i-j$ chi phí $c_{ij}x_{ij}$.

Do đó, tổng chi phí vận chuyển bằng

$$S = \sum_{i,j} c_{ij} x_{ij}. \tag{17}$$

Cần tìm các giá trị đại lượng $x_{ij}$ sao cho $S$ lấy giá trị nhỏ nhất có thể và thỏa mãn điều kiện:

a) tính liên tục của dòng chảy tại các nút trung gian (xem (3));

b) lưu lượng giao thông không âm: $x_{ij} \geqslant 0$;

c) bằng một đơn vị của tổng lưu lượng qua mạng:

$$X = x_{12} + x_{13} + x_{35} + x_{45} = 1. \tag{18}$$

Để xây dựng mô hình điện của mạng truyền tải bài toán này, cần thay thế mỗi cung $i-j$ bằng một nhánh có một diode và một nguồn điện áp mắc nối tiếp, giá trị của nó bằng $c_{ij}$ và đưa một nguồn dòng điện duy nhất vào nhánh bổ sung từ đầu ra đến đầu vào của mạng. Sơ đồ tương ứng được trình bày trong Hình 6.

Nó có thể được chứng minh...

Nhưng đã đến lúc chúng ta phải chấm dứt nó. Bạn đọc quan tâm đến những câu hỏi này có thể thử sức mình giải các bài toán sau

Bài tập

1. Chứng minh rằng dòng điện $x_{ij}$ lắp vào các nhánh của mạch điện như ở Hình 6, cho lời giải bài toán để giảm thiểu chi phí vận chuyển.

2. Chứng minh rằng mọi dòng điện khác 0 dọc theo một nhánh của mạch này nhất thiết phải bằng 1, tức là trên thực tế dòng điện không phân nhánh tại các nút mà đi từ đầu vào đến đầu ra dọc theo một đường dẫn nhất định (“đường đi của chi phí tối thiểu”).

3. Sử dụng bài toán để giảm thiểu chi phí vận chuyển, hãy chỉ ra cách sử dụng mô hình tương tự (Hình 6) để xác định đường đi ngắn nhất dọc theo các cung của mạng lưới giao thông dẫn từ lối vào đến lối ra.

2 Lượng tử số 2

⟦column⟧
