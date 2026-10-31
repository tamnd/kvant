---
id: 1986-10-chisla-mersenna-5bffed1c
issue: kvant_1986_10
year: 1986
number: "10"
title: số Mersenne
rubric: kvant-dlya-mladshih-shkolnikov
rubric_sub: «Квант» для младших школьников
page_first: 26
page_last: 27
page_labels: 24-25
tag: UWO5
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 44ec895012b9c7ab7b70775f538d39a551814115494f8a378d7ed352deab66a9
prompt_sha256: draft-1
translated_from: content/ru/1986/10/articles/11_chisla-mersenna-5bffed1c.md
source_content_sha256: 91d8703c744903bba4ea1df02e1b9811d13bc9289c2d9e747bec488d84244647
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 24⟧

số Mersenne

Toán học, giống như hầu hết các ngành khoa học hiện đại, hiện đang phát triển với tốc độ ở mọi lứa tuổi. Có hàng trăm tạp chí toán học được xuất bản trên khắp thế giới, trong đó có mười nghìn bài báo khoa học được xuất bản mỗi ngày. Và 350 năm trước không có tạp chí toán học nào, và các nhà khoa học đã trao đổi kết quả nghiên cứu của họ bằng thư cá nhân. Đúng vậy, có một người - tu sĩ người Pháp Maren Mersenne (1588-1648) đã nhận được những bức thư như vậy nhiều hơn những người khác. Mersenne biết viết về việc phát hiện ra một định lý mới và thiết lập mức độ ưu tiên của mình, vì Mersenne, như một quy luật, đã thông báo cho các phóng viên khác của ông về điều này, bao gồm R. Descartes, V. Pascal, P. Fermat, H. Heugens và nhiều nhà khoa học khác vào thời điểm đó.

Hoạt động này của Marin Mersenne đã góp phần thành lập Viện Hàn lâm Khoa học ở Paris.

Trong số những thành tựu toán học của Mersenne, nổi tiếng nhất là những con số có dạng $M_n=2^n-1$ mà ông đã nghiên cứu.

Bất kỳ ai biết cấp số nhân là gì sẽ nhận thấy ngay rằng $M_n$ bằng tổng của $n$ số hạng đầu tiên của cấp số nhân với số hạng ban đầu $2^\circ=1$ và được gọi là 2:

$$M_n=2^\circ+2^1+2^2+\dots+2^{n-1}.$$

Mersenne quan tâm đến số $M_n=2^n-1$ nào là số nguyên tố. Câu hỏi này nảy sinh vào năm bài toán, do người Hy Lạp cổ đại đặt ra (chúng ta sẽ quay lại vấn đề này sau).

Các số nguyên tố thu được theo công thức $2^n-1$ được gọi là số Mersenne.

Chúng ta thử đề cập một chút đến bài toán tìm số Mersenne.

Hãy tính một vài số đầu tiên $M_n=2^n-1$ và viết chúng theo thứ tự trong bảng bốn cột. Điều lo lắng đầu tiên: các số rơi vào cùng một cột sẽ có cùng một chữ số. Cụ thể, các số rơi vào cột đầu tiên là 1, số thứ hai - 3, số thứ ba - 7 và số thứ tư - 5 (hãy thử nghiêm ngặt

⟦folio 25⟧

biện minh cho quan sát này). Điều này có nghĩa là các số $M_n$ rơi vào cột thứ tư chia hết cho 5 và không thể có số Mersenne trong số đó.

Không khó để chứng minh nhận xét thứ hai: các số rơi vào cột thứ hai và thứ tư đều chia hết cho 3. Thật vậy, hiệu của hai số liên tiếp $M_{2k}$ và $M_{2k+2}$ với bốn số là bằng nhau

$$(2^{2k+2}-1)-(2^{2k}-1)=2^{2k+2}-2^{2k}=3\cdot 2^k.$$

Do đó, nếu số $M_{2k}$ chia hết cho 3 thì $M_{2k+2}$ cũng chia hết cho 3. Và số $M_2$ bằng ba.

Do đó, sẽ hợp lý hơn khi chỉ tìm số Mersenne (ngoại trừ $M_2=3$) trong cột đầu tiên và cột thứ ba.

Một nghiên cứu đơn giản hơn về các số $M_n$ dẫn đến nhận xét thứ ba: nếu $n$ là hợp số, $n=kl$, $k>1$, $l>1$, thì $M_n$ chia hết cho $M_k$ và $M_l$. (Điều này xuất phát từ thực tế là $2^{kl}-1=(2^k)l-1=(2^l)k-1$ và $(x^m-1)=(x-1)(x^{m-1}+x^{m-2}+...+x+1)).$ Nhân tiện, hai số đầu tiên cũng tuân theo quan sát thứ ba, vì tất cả các số trong cột thứ hai đều chia hết cho $M_2=3$ và tất cả các số trong cột thứ tư đều chia hết cho $M_4=15$.

Vì vậy, số $2^n-1$ sẽ chỉ là số nguyên tố nếu $n$ là số nguyên tố.

Nhưng với bất kỳ số nguyên tố $p$ nào thì số $M_p$ sẽ là số nguyên tố? Hy vọng về một đáp số tích cực sụp đổ rất nhanh: con số $M_{11}=2047=23\cdot 89$ đã là tổng hợp.

Bản thân Mersenne đã chỉ ra tất cả các giá trị nguyên tố của $n$, không vượt quá 257, mà theo ý kiến ​​​​của ông, các số $M_n=2^n-1$ sẽ là số nguyên tố. Tuy nhiên, Mersenne không đưa ra bằng chứng; sau đó người ta phát hiện ra rằng dự đoán của ông đã sai một phần.

Leonard Euler, thành viên của Viện Hàn lâm Khoa học St. Petersburg, một trong những nhà toán học vĩ đại nhất thời kỳ hiện đại, cũng tham gia vào việc tìm kiếm số Mersenne. Năm 1750, ông phát hiện ra số Mersenne thứ mười; đây là $M_{31}=2147483647$.

Nếu trước đó việc tính toán số Mersenne của Nhật Bản được thực hiện bằng phương pháp "thủ công", thì vào thế kỷ 20, máy tính bắt đầu hoạt động, đếm với tốc độ rất lớn. Năm 1952, năm số Mersenne mới được phát hiện cùng lúc: $M_{521}, M_{607}, M_{1279}, M_{2203}$ và $M_{2281}$; chúng là các số Mersenne thứ mười ba đến thứ mười bảy tương ứng. Sáu số Mersenne tiếp theo được tìm thấy từ năm 1958 đến năm 1963. Cuối cùng, vào năm 1971, số Mersenne thứ 24 $M_{19937}$ được tìm thấy, năm 1978 - số Mersenne thứ 25 $M_{21701}$, năm 1979 - số Mersenne thứ 26 và 27 $M_{23209}$ và $M_{44497}$. Số Mersenne được biết đến cuối cùng được tìm thấy vào năm 1983: nó là $M_{86243}$; nhưng vẫn chưa biết đó có phải là số Mersenne thứ 28 hay không.

Và để kết luận, chúng ta hãy giải thích sự quan tâm đến số Mersenne. Thực tế là chúng được liên kết với cái gọi là số hoàn hảo (mà người Hy Lạp cổ đại đã nghiên cứu) - những con số bằng tổng của tất cả các ước của chúng, tất nhiên, khác với chính số đó (ví dụ: $6=1+2+3$, $28=1+2+4+7+14$, $496=1+2+4+8+16+31+62+124+248$ - ba số hoàn hảo đầu tiên). Euclid cũng đã chứng minh (bạn cũng vậy!) rằng nếu số $2^n-1$ là số nguyên tố thì số $2^{n-1}(2^n-1)$ là số hoàn hảo. Leonhard Euler đã chứng minh rằng mọi số chẵn đều hoàn hảo? Nhưng vẫn chưa có ai tìm ra số hoàn hảo lẻ và cũng chưa có ai chứng minh được rằng những số đó không tồn tại.

Dựa trên tài liệu từ Yu. V. Korolev và O. M. Mamedov
