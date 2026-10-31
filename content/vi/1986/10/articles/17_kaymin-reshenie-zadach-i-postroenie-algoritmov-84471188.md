---
id: 1986-10-kaymin-reshenie-zadach-i-postroenie-algoritmov-84471188
issue: kvant_1986_10
year: 1986
number: "10"
title: Lời giải bài toán và xây dựng thuật toán
authors:
  - Каймин В. А.
rubric: raznoe
rubric_sub: Разное
page_first: 49
page_last: 52
page_labels: 47, 49, 50
tag: ND9D
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 006911bf0aaab5b2a028c0108d2f85549236034582d66b3114d378ef29d35821
prompt_sha256: draft-1
translated_from: content/ru/1986/10/articles/17_kaymin-reshenie-zadach-i-postroenie-algoritmov-84471188.md
source_content_sha256: d79888c33118941c0e71839c76bbd5ed962fb78d7a94c9e7c8662feef9d71cd7
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 47⟧

Lời giải bài toán và xây dựng thuật toán

Ứng viên khoa học kỹ thuật
V. A. KAIMIN

Bài toán, bài toán, bài toán... Việc học tập, công việc và cuộc sống cá nhân của chúng ta là hàng ngày, hàng ngày lời giải bài toán - giáo dục và tình nguyện, kỹ thuật và khoa học, tổ chức và cá nhân. Trình độ, năng lực làm việc của kỹ sư, chuyên gia được quyết định bởi kiến ​​thức và khả năng giải quyết các vấn đề phát sinh trong công việc bài toán. Giai đoạn đầu tiên trong lời giải bài toán là giai đoạn dàn dựng.

Giai đoạn thứ hai lời giải bài toán bao gồm việc lựa chọn các phương tiện và phương pháp lời giải. Đối với lời giải phức tạp bài toán, chúng tôi lập kế hoạch trong đó các nhiệm vụ phụ được xác định, sau đó các phương pháp và phương tiện được chọn cho lời giải nhiệm vụ được phân bổ. Giai đoạn cuối cùng là thực hiện các kế hoạch và phương pháp đã chọn lời giải, kết thúc là đạt được kết quả cần thiết.

Khi nói đến lời giải bài toán bằng máy tính, việc lựa chọn thuật toán cho lời giải bài toán chiếm vị trí trung tâm. Trong phần này và phần lưu ý tiếp theo, chúng ta sẽ nói về việc xây dựng các thuật toán một cách có hệ thống liên quan đến những vấn đề được giải trong môn học “Cơ bản về Khoa học Thông tin và Máy tính” lớp 9 và 10.

Các bước chính trong việc xây dựng thuật toán có hệ thống có thể được minh họa bằng sơ đồ sau (hình 1). Hãy xem quá trình sản xuất này như thế nào

⟦folio 49⟧

Cho: $a$ — góc ban đầu [rad],
$v_0$ — tốc độ ban đầu [m/s].
Bắt buộc: $l$ — tầm bay [m].

Sự liên quan:
$l = v_{x_0} t$ — tầm bay,
$-g t^2/2 + v_{y_0} t = 0$ — phương trình bay,
$v_{x_0} = v_0 \cos \alpha$ - tốc độ ngang,
$v_{y_0} = v_0 \sin \alpha$ - tốc độ dọc,
$g = 9,81$ — gia tốc rơi tự do.

Tại: $v_0 > 0$ và $0 < \alpha \leq \frac{\pi}{2}$.

Phương pháp
$$\begin{cases}
l = vx0 \cdot t, \\
t = 2vy0/g, \\
vx0 = v0 \cdot \cos \alpha, \\
vy0 = v0 \cdot \sin \alpha, \\
g = 9,81.
\end{cases}$$

Thuật toán
phạm vi alg (trọng lượng $a, l, v0$)
tranh luận $v0, a$
độ phân giải $l$

bắt đầu $g, vx0, vy0, t$
$g := 9,81$
$vx0 := v0 \cdot \cos \alpha$
$vy0 := v0 \cdot \sin \alpha$
$t := 2vy0/g$
$l := vx0 \cdot t$
lừa đảo

***

Đối với elematrine bài toán phương pháp lời giải có thể thu được ở dạng phân tích chính xác. Đối với phức tạp bài toán, khi không có được hệ thống công thức tính toán rõ ràng thì sử dụng các phương pháp gần đúng lời giải, đòi hỏi khối lượng tính toán lớn. Để tính gần đúng một đại lượng nhất định $y$ một chuỗi xấp xỉ nhất định được xác định: $y_0, y_1, y_2, \dots$, trong giới hạn có xu hướng đạt đến giá trị mong muốn $y = \lim_{n \to \infty} y_n$. Trình tự xấp xỉ $y_k (k=0,1,2)$ thường được chọn sao cho giá trị ước lượng $y_k$ phụ thuộc vào trước đó

Hình 2. Tính diện tích của bóng đèn.

Hình 3. Khoảng cách giữa giải pháp a) thời điểm ban đầu, b) thời điểm hiện tại.

Hình 4. Phạm vi ném đá.

⟦folio 50⟧

I. V. Kurchatov:
bước đầu tiên
tại LPTI

(Để bắt đầu, xem trang 3)

(Kurchatov và Sinelnikov không cho biết ống có pít-tông được đặt vào loại chất lỏng nào; họ viết rằng họ hạ xuống “... đầu ống có lá mỏng gắn vào bình chứa chất lỏng và cẩn thận thổi vào không khí.”) Trong điều kiện nhiệt độ bình thường, σ đối với một số chất lỏng (etyl ete, diethylamine, v.v.) nằm trong khoảng 0,015-0,020 J/m³. Đặt σ=0,015 J/m2. Sau đó, thay giá trị σ và d=0,5 μm này vào (*), chúng ta tìm được giá trị mong muốn Δp: Δp=1,2·10⁵ Pa (~1 atm) - một áp suất khá cao! Không có gì ngạc nhiên khi các tác giả viết rằng họ loại bỏ không khí trong ống hình trụ một cách “thận trọng”. Điều cần thiết là giấy bạc không bị bong ra khỏi đầu ống và quan trọng nhất là không bị rách. Các lá kim loại được Kurchatov và Sinelnikov sử dụng đủ bền để chịu được áp lực tác dụng. Điều tương tự cũng xảy ra với các phép tính (sử dụng các công thức đã biết về độ bền của vật liệu làm màng), theo đó ứng suất phát triển ở giá trị Δp được chúng tôi xem xét nhỏ hơn giới hạn cường độ của thuật toán.

(Lưu ý rằng công thức của Laplace cho những mục đích tương tự đã được sử dụng vào năm 1923 bởi không ai khác ngoài A. Einstein trong công trình thí nghiệm chung với bạn của ông, bác sĩ G. Muhsam. Trong công trình này, một kỹ thuật đã được đề xuất để “xác định thực nghiệm kích thước của các kênh trong bộ lọc” (đó là tên của bài báo tương ứng, nghiên cứu các bộ lọc xốp được sử dụng cho mục đích vi khuẩn và y tế). được đặt, đường kính tối đa của các lỗ (kênh) trong bộ lọc đã được xác định.)

Như có thể thấy từ các ước tính, các phản hồi có đường kính nhỏ hơn 0,5 micron có thể hoàn toàn không được Hartig chú ý. Trong khi đó, dòng electron qua những phản ứng như vậy trong bộ lọc là quá đủ để ghi lại trong các thí nghiệm. Mục tiêu công trình của Kurchatov và Sinelnikov, đạt được nhờ các thí nghiệm điều khiển đỏ và đơn giản của họ, là chứng tỏ sự sai lầm trong các kết luận do Hartig đưa ra về tính thấm của các bộ lọc mỏng rắn (không khuyết tật) đối với các electron chậm.
