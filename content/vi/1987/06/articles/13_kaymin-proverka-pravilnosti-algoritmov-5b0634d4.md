---
id: 1987-6-kaymin-proverka-pravilnosti-algoritmov-5b0634d4
issue: kvant_1987_6
year: 1987
number: "6"
title: Xác thực các thuật toán
authors:
  - Каймин В. А.
rubric: raznoe
rubric_sub: Разное
page_first: 45
page_last: 46
page_labels: 43-44
tag: 60RP
lang: vi
source: kvant_digital
extraction: vision
content_sha256: fc8edd73d7c4cc44cc493b2ff2c19b49f15aaec2720c22a5cf308d971435e985
prompt_sha256: draft-1
translated_from: content/ru/1987/06/articles/13_kaymin-proverka-pravilnosti-algoritmov-5b0634d4.md
source_content_sha256: 976608c1a4b86dc63d732d5e46e0ce5902694fc59ce1609d49540b2a361adf38
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 43⟧

Xác thực các thuật toán

Ứng viên khoa học kỹ thuật
V. A. KAIMIN

Lập trình là một nghệ thuật, một khoa học hay một nghề thủ công? Có thể viết chương trình và đảm bảo rằng không có lỗi trong đó không? Hai câu hỏi này là chủ đề của các cuộc tranh luận khoa học, xung đột và nghiên cứu dịch vụ nóng bỏng. Hãy cố gắng tìm ra nó.

Có ba cách tiếp cận để biên dịch một chương trình cho máy tính.

Cách tiếp cận đầu tiên - chúng tôi gọi là truyền thống - bao gồm viết chương trình bằng một số ngôn ngữ lập trình (BASIC, FORTRAN, PL/1, COBOL, v.v.) ngay lập tức theo các công thức có ý nghĩa bài toán:

Ngôn ngữ lập trình thường có từ vựng tiếng Anh và các chương trình bằng những ngôn ngữ này rất khó đọc, hiểu và học đối với những người không nói tiếng Anh bản xứ. Khi biên dịch một chương trình theo cách truyền thống, hầu như luôn xuất hiện một số lượng lớn lỗi và trình biên dịch chương trình cố gắng truy cập vào máy tính càng sớm càng tốt và bắt đầu gỡ lỗi chương trình.

Số lượng lỗi trong một chương trình không bao giờ được biết trước và do đó không ai biết khi nào chương trình sẽ kết thúc việc gỡ lỗi. Hơn nữa, khi tác giả chương trình khẳng định rằng chương trình của họ đã được gỡ lỗi hoàn toàn thì những chương trình này thường vẫn có lỗi.

Cách tiếp cận thứ hai đối với lập trình, thường được gọi là lập trình có cấu trúc, bao gồm việc suy nghĩ cẩn thận thông qua logic lời giải bài toán và tạo ra các thuật toán có cấu trúc. Chúng tôi khuyên bạn nên viết ra các thuật toán này bằng ngôn ngữ thuật toán của trường từ sách giáo khoa của bạn và chỉ sau đó dịch bản ghi chương trình sang một trong các ngôn ngữ lập trình. Sơ đồ thiết kế chương trình có thể

⟦folio 44⟧

miêu tả như thế này:

Với cách tiếp cận này, có thể dễ dàng phân biệt các lỗi cú pháp và thuật toán. Lỗi cú pháp (vi phạm quy tắc ngôn ngữ lập trình) chỉ có thể xuất hiện nếu chương trình được mã hóa không chính xác bằng thuật toán. Lỗi thuật toán (vi phạm logic lời giải bài toán) phát sinh khi biên soạn thuật toán; việc tìm kiếm và sửa lỗi của chúng có thể được thực hiện theo mô tả của các thuật toán trước khi viết và kiểm tra chương trình trên máy tính.

Cách tiếp cận thứ ba, mà chúng tôi gọi là các chương trình mang tính xây dựng có hệ thống, là cách tiếp cận mang tính phát triển. Nó có thể được biểu diễn dưới dạng sơ đồ sau:

Cách tiếp cận này được mô tả chi tiết hơn trong «Kvant» (1986, Số 10, trang 47 và Số 11, trang 40).

Việc kiểm thử một chương trình máy tính bao gồm các cuộc kiểm tra được lên kế hoạch cẩn thận để đảm bảo rằng máy hoạt động theo đúng kịch bản chương trình. Việc kiểm tra bao gồm kiểm tra tất cả các trường hợp đặc biệt chính của câu lệnh bài toán, kiểm tra các điều kiện biên, kiểm tra phản ứng của chương trình đối với dữ liệu không hợp lệ và các hành động không thể chấp nhận của con người. Về mặt này - liên quan đến kịch bản của các chương trình đối thoại (xem «Kvant», 1986, số 11, tr. 40) - ở đây chúng tôi sẽ không đi sâu vào chi tiết.

Việc xác định lỗi và biện minh cho tính đúng đắn của chương trình theo cách tiếp cận này được thực hiện thông qua suy luận logic, tất cả đều là bằng chứng - chương trình sẽ đưa ra kết quả và thông báo cần thiết hay không? Chỉ có thể đảm bảo hoàn toàn không có sai sót nếu có các công thức toán học của giải bài toán và mô tả chi tiết về kịch bản làm việc với máy tính.

Trong tình huống này, chúng tôi gọi một chương trình là chính xác nếu với bất kỳ dữ liệu ban đầu hợp lệ nào, nó tạo ra các kết quả tương ứng hoàn toàn với kịch bản cho bất kỳ hành động nào của người dùng. Chương trình có lỗi nếu có thể chỉ định dữ liệu đó mà máy tạo ra kết quả mâu thuẫn với kịch bản thiết lập bài toán đã giải quyết hoặc hoạt động của nó không tương ứng với mô tả của kịch bản chương trình.

Ở đây chúng ta sẽ xem xét một số ví dụ chứng minh tính đúng đắn của các đoạn chương trình riêng lẻ được viết bằng ngôn ngữ thuật toán của trường học (chúng tôi bỏ qua một phần tiêu đề chương trình để cho ngắn gọn).

Ví dụ 1 (bài toán tính toán).

alg "phép tính x⁵"
bắt đầu v := x x
v := v · v
y := v · x

kết quả
v₁ = x · x,
v₂ = v₁ · v₁,
y = v₂ · x.

Xin lưu ý rằng một số giá trị không được mô tả cho biến v trong quá trình hoạt động của thuật toán, vì vậy khi ghi kết quả, trước tiên chúng ta viết chữ v kèm theo các chỉ số bằng số. Dựa trên chương trình này, chúng tôi làm như sau

Tuyên bố. y = x⁵.

Bằng chứng. Từ việc mô tả kết quả thực hiện các thao tác ta có
y = v₂ · x = (v₁ · v₁) · x =
= ((x · x) · (x · x)) · x = x⁵.

Ví dụ 2 (thuật toán có tính đến phân nhánh).

alg "tính |x|"
bắt đầu nếu x > 0
thì y := x
khác y := -x

kết quả
x với x > 0,
-x cho x ≤ 0.

Tuyên bố. Chương trình này luôn cho y = |x|.

Bằng chứng được thực hiện bằng cách phân tích trường hợp. Khi x > 0, phương án thay thế đầu tiên được thực thi. Kết quả của việc cộng giá trị sẽ bằng y = x, tương ứng với định nghĩa
