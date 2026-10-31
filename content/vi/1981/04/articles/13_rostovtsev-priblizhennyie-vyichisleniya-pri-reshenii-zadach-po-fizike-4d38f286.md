---
id: 1981-4-rostovtsev-priblizhennyie-vyichisleniya-pri-reshenii-zadach-po-fizike-4d38f286
issue: kvant_1981_4
year: 1981
number: "4"
title: Các phép tính gần đúng ở lời giải bài toán trong vật lý
authors:
  - Ростовцев Н. М.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 42
page_last: 44
page_labels: 40-42
tag: U2PI
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 3b2d9c47e4f247cc9ee43012caa2635be2bb596936c21e6a8a03bac39faaa786
prompt_sha256: draft-1
translated_from: content/ru/1981/04/articles/13_rostovtsev-priblizhennyie-vyichisleniya-pri-reshenii-zadach-po-fizike-4d38f286.md
source_content_sha256: f26f600a2c36c4c33a2757acd962c21d7678de490c9ed0816d01b35314d031fa
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 40⟧

Các phép tính gần đúng ở lời giải bài toán trong vật lý

Khi bắt đầu lời giải bất kỳ bài toán vật lý nào, trước hết cần tìm hiểu xem hiện tượng hoặc quá trình nào đóng vai trò quan trọng và hiện tượng hoặc quá trình nào đóng vai trò không tồn tại. Việc bỏ qua các hiện tượng không cần thiết chắc chắn sẽ dẫn đến việc bỏ qua các đại lượng tương đối nhỏ, tức là tính toán gần đúng. Kiến thức về các công thức tính toán gần đúng và khả năng sử dụng chúng thường giúp đơn giản hóa các phép tính rất nhiều.

Từ quá trình toán học, người ta biết rằng biểu thức $(1+x)^n$ tại $|x|<1$ có thể được biểu diễn dưới dạng

$$(1+x)^n = 1 + nx + \frac{n(n-1)}{1 \cdot 2} x^2 + \frac{n(n-1)(n-2)}{1 \cdot 2 \cdot 3} x^3 + \dots$$

Ở đây $n$ là số thực bất kỳ. Với $n$ tự nhiên, tổng này được chuyển đổi thành số hạng ở bậc $n$; công thức thu được được gọi là công thức Newton.

Giả sử tồn tại biểu thức $(a+b)^n$ thì từ (1)

$$(a+b)^n = a^n \left(1 + \frac{b}{a}\right)^n = a^n \left(1 + n \frac{b}{a} + \frac{n(n-1)}{1 \cdot 2} \left(\frac{b}{a}\right)^2 + \dots\right).$$

Nếu $|b| \ll |a|$, các số hạng chứa mối quan hệ $b/a$ với lũy thừa thứ hai trở lên, chúng ta có thể bỏ qua và giới hạn chỉ ở hai số hạng đầu tiên:

$$(a+b)^n = a^n \left(1 + \frac{b}{a}\right)^n \approx a^n \left(1 + n \frac{b}{a}\right).$$

Lỗi nào sẽ xảy ra khi sử dụng công thức gần đúng này? Để ước tính sóng, chúng ta có thể giả sử rằng sai số bằng số hạng thứ ba trong khai triển:

$$\Delta y = a^n \frac{n(n-1)}{1 \cdot 2} \left(\frac{b}{a}\right)^2.$$

Với sóng lời giải vật lý bài toán, các phép tính với độ chính xác một phần trăm thường được chấp nhận. Từ biểu thức (3) người ta có thể tìm thấy giá trị lớn nhất là $b/a$, tại đó độ chính xác của phép tính không vượt quá kích thước cho phép.

Các công thức tính gần đúng giá trị của các hàm lượng giác rất đơn giản và tiện lợi. Nếu góc $α$, biểu thị bằng bán kính, đủ nhỏ, chúng ta có thể lấy

$$\sin α \approx α,$$

$$tg α \approx α,$$

$$\cos α \approx 1.$$

Tính toán cho thấy sai số không vượt quá một phần trăm nếu góc $α$ thỏa mãn điều kiện

$$α \leq 23° \approx 4.0 \cdot 10^{-1}$$

vui mừng vì tội lỗi $α$,

$$α \leq 18° \approx 3.1 \cdot 10^{-1}$$

rất vui vì tg $α$,

$$α \leq 8° \approx 1.4 \cdot 10^{-1}$$

rất vui vì cos $α$.

(Ví dụ: điều này có thể được kiểm tra bằng cách sử dụng bảng Bradis.)

Trong vật lý, hàm mũ $y=a^x$ khá phổ biến. Đối với các giá trị nhỏ của $x$, đẳng thức gần đúng được thỏa mãn

$$a^x \approx 1 + \frac{\lg a}{0.43} x.$$

Bây giờ chúng ta hãy xem xét một số bài toán cụ thể.

Bài 1. Điện trở $R$ của dây dẫn được thay đổi bằng ampe kế và vôn kế theo sơ đồ như hình 1. Điện trở của vôn kế $R_V \gg R$. Xác định lỗi đang mắc phải

⟦folio 41⟧

tính điện trở của dây dẫn mà không tính đến dòng điện chạy qua vôn kế.

Điện trở của dây dẫn tính từ số đọc của ampe kế và vôn kế, không tính đến điện trở của vôn kế, bằng

$$R' = \frac{U}{I},$$

trong đó $U$ là điện áp trên vôn kế, $I$ là dòng điện chạy qua ampe.

Sức đề kháng thực sự là

$$R = \frac{U}{I - I_V} = \frac{U}{I - U/R_V}.$$

Lỗi bạn đang tìm kiếm

$$\Delta R = R - R' = \frac{U}{I - U/R_V} - \frac{U}{I} = \frac{U}{I} \left( \left( 1 - \frac{U/R_V}{I} \right)^{-1} - 1 \right).$$

Vì $R_V \gg R$, nên $U/R_V \ll I$. Áp dụng công thức (2), ta thu được

$$\Delta R = R - R' \approx \frac{U}{I} \left( 1 + \frac{U/R_V}{I} - 1 \right) \approx \frac{U^2}{I^2 R_V}.$$

Nhiệm vụ 2. Lực hấp dẫn sẽ thay đổi bao nhiêu phần trăm khi lên đến độ cao $h = 1$ km so với bề mặt Trái đất? Bán kính Trái đất được coi là bằng $R = 6400$ km.

Lực hấp dẫn của một vật có khối lượng $m$ ở bề mặt Trái đất bằng

$$F_0 = G \frac{mM}{R^2},$$

trong đó $G$ là hằng số hấp dẫn, $M$ là khối lượng của Trái đất.

Khi chúng ta di chuyển ra khỏi bề mặt Trái đất, lực hấp dẫn giảm dần và ở độ cao $h$ nó bằng

$$F_1 = G \frac{mM}{(R+h)^2}.$$

Từ các biểu thức của $F_0$ và $F_1$ chúng ta tìm thấy

$$\frac{F_0 - F_1}{F_0} = 1 - \frac{F_1}{F_0} = 1 - \frac{R^2}{(R+h)^2} = 1 - \frac{1}{(1+h/R)^2} = 1 - \left( 1 + \frac{h}{R} \right)^{-2}.$$

Vì $h \ll R$, tức là $h/R \ll 1$, sử dụng công thức (2), chúng ta thu được

$$\frac{F_0 - F_1}{F_0} \approx 1 - \left( 1 - 2 \frac{h}{R} \right) = 2 \frac{h}{R} \approx 3 \cdot 10^{-4}.$$

Nhiệm vụ 3. Trong lý thuyết năng lượng tương đối, giải tích

Các hạt $E_k$ được tính bằng công thức $E_k = E - E_0$, trong đó $E$ là năng lượng của một hạt chuyển động và $E_0$ là năng lượng của một hạt đứng yên. Chứng tỏ rằng khi tốc độ của hạt là $v \ll c$ (bằng tốc độ ánh sáng) thì động năng của hạt gần đúng là $m_0 v^2/2$, trong đó $m_0$ là khối lượng của hạt ở trạng thái nghỉ.

Theo lý thuyết năng lượng tương đối

$$E = \frac{m_0 c^2}{\sqrt{1 - (v/c)^2}}$$ và $E_0 = m_0 c^2.$

Từ đây

$$E_k = E - E_0 = m_0 c^2 \left( \frac{1}{\sqrt{1 - (v/c)^2}} - 1 \right) = m_0 c^2 \left( \left( 1 - \frac{v^2}{c^2} \right)^{-1/2} - 1 \right).$$

Vì $v \ll c$, tức là $v/c \ll 1$, và do đó, $v^2/c^2 \ll 1$, áp dụng công thức (2), chúng ta tìm thấy

$$E_k \approx m_0 c^2 \left( 1 + \frac{1}{2} \frac{v^2}{c^2} - 1 \right) = \frac{m_0 v^2}{2}.$$

Bài tập 4. Một vật trượt từ một mặt phẳng nghiêng tạo một góc $\alpha = 7^\circ$ với đường chân trời. Tìm gia tốc của vật nếu hệ số ma sát của vật trên mặt phẳng là $\mu = 3 \cdot 10^{-2}$.

Ba lực tác dụng lên một vật chuyển động dọc theo mặt phẳng nghiêng: lực hấp dẫn $m\vec{g}$, hướng thẳng đứng xuống dưới, lực hấp dẫn $\vec{F}_{\text{тр}}$, hướng lên trên dọc theo mặt phẳng nghiêng và phản lực pháp tuyến $\vec{R}$, vuông góc với mặt phẳng nghiêng. Hãy chiếu các lực lên trục tọa độ $OX$ và $OY$, như trên Hình 2, và viết phương trình chuyển động:

$$mg \sin \alpha - F_{\text{тр}} = ma,$$

$$R - mg \cos \alpha = 0.$$

Xem xét rằng

$$F_{\text{тр}} = \mu R,$$

⟦folio 42⟧

từ phương trình chuyển động, chúng ta tìm được mô đun gia tốc của vật:
$$a = g(\sin \alpha - \mu \cos \alpha).$$

Vì góc là $\alpha < 8^\circ$ nên chúng ta có thể sử dụng công thức (4) và (6) và giả sử rằng $\cos \alpha \approx 1$ và $\sin \alpha \approx \alpha$ (góc $\alpha$ phải được biểu thị bằng radian). Thay thế các giá trị $\cos \alpha \approx 1$ và $\sin \alpha \approx 1,2 \cdot 10^{-1}$, chúng ta nhận được $a \approx g(1,2 \cdot 10^{-1} - 3 \cdot 10^{-2}) = 8,8 \cdot 10^{-1}$ m/s$^2$.

Bài toán 5. Có bao nhiêu nguyên tử phân rã theo thời gian $t = 1$ từ một gam radium? Chu kỳ bán rã của radium là $T = 1600$ năm. Có $N_0 = 2,6 \cdot 10^{21}$ nguyên tử trong một gam radium.

Nếu số nguyên tử phóng xạ tại thời điểm ban đầu là $N_0$ thì theo định luật phân rã phóng xạ, sau thời gian $t$ số nguyên tử không tan chảy là $N$

$$N = N_0 2^{-t}.$$

Từ đây chúng ta có thể tìm thấy số ngoại lệ $n$ của các nguyên tử bị phân rã:

$$n = N_0 - N = N_0 (1 - 2^{-t}).$$

Vì $t/T \ll 1$, áp dụng công thức (7), ta thu được

$$n \approx N_0 \left(1 - 1 + \frac{\lg 2}{0,43} \frac{t}{T}\right) \approx 3,7 \cdot 10^{10}.$$

Lưu ý rằng hoạt độ của một bộ chuyển đổi phóng xạ, trong đó các nguyên tử $3,7 \cdot 10^{10}$ phân rã trong 1 s, được lấy làm đơn vị hoạt độ và được gọi là 1 curie.

Tóm lại, một vài lời về phép tính số cho lời giải bài toán. Ghi lại một điều kiện ngắn bài toán, việc biểu thị tất cả các giá trị số ở dạng $a \cdot 10^n$ (trong đó $1 \leq a < 10$) là hợp lý và có cùng độ chính xác. Trong phần lớn các trường hợp, deve có số lượng đáng kể. Sau đó, kết quả thu được cũng phải được làm tròn thành hai chữ số có nghĩa (ví dụ: xem lời giải bài toán 4).

Bài tập

1. Tính các giá trị tối đa của $a$ mà tại đó sai số của công thức $(1+a)^3 \approx 1+3a$ và $\sqrt{1-a} \approx 1 - \frac{1}{2}a$ không vượt quá 0,01.

2. Hệ số phân bố tuyến tính của đồng thau $a = 2 \cdot 10^{-5} \text{K}^{-1}$. Chistsy với một nam châm bằng đồng sẽ tụt lại phía sau bao xa trong 24 giờ do nhiệt độ tăng $\Delta T = 10$ K?

3. Xác định gia tốc trọng trường ở độ cao 10 km tính từ Trái đất, nếu ở bề mặt nó bằng 981 cm/$^2$. Bán kính Trái đất là $R = 6400$ km.

4. Xác định hướng trường của hệ điện tích chính xác $+q$ và $-q$ tại điểm $B$ (Hình 3), nếu $l \ll L$.

5. Một ô tô có khối lượng $m = 2 \cdot 10^3$ kg xuất phát từ trạng thái đứng yên và đi lên dốc, độ dốc của mỏ là $a = 0,02$. Sau khi đi được quãng đường $s = 100$ m, nó phát triển tốc độ $v = 32,4$ km/h. Hệ số cản chuyển động $k = 0,05$. Xác định công suất trung bình do máy tự động tạo ra trong quá trình chuyển động này.

Liên vũ trụ nhỏ

(Để bắt đầu, xem trang 8)

Các đội của các trường, tổ chức ngoài trường học, hiệp hội khoa học và kỹ thuật của các tổ chức tham gia tích cực và dày đặc nhất trong cuộc thi, cũng như các phân ban và đội của các doanh nghiệp, tổ chức, trường đại học đã hỗ trợ hiệu quả cho công việc của các nhà nghiên cứu và kỹ thuật trẻ, sẽ được trao bằng danh dự, và các giáo viên, trưởng nhóm, chuyên gia tư vấn trong số các nhà khoa học và chuyên gia dưới sự hướng dẫn của họ, những người chiến thắng trong cuộc thi - bằng cấp và huy hiệu.

Mọi thắc mắc liên quan đến việc tổ chức và tiến hành cuộc thi, vui lòng liên hệ với Ủy ban Trung ương Komsomol (Moscow, New Square 6/8, tel. 206-84-70, 206-89-92), Trạm Giáo dục Kỹ thuật Trẻ Trung ương của RSFSR (tel. 289-75-44), Cung điện Pinoyers của Thành phố Moscow (tel. 139-89-54, 139-84-88).
