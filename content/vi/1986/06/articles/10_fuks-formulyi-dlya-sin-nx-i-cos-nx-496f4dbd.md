---
id: 1986-6-fuks-formulyi-dlya-sin-nx-i-cos-nx-496f4dbd
issue: kvant_1986_6
year: 1986
number: "6"
title: Công thức tính sin nx và cos nx
authors:
  - Фукс Д. Б.
rubric: shkola-v-kvante
page_first: 27
page_last: 27
page_labels: "25"
tag: A6YA
lang: vi
source: kvant_digital
extraction: vision
content_sha256: caf5a34620dd52823ad3daa5f8c21974c2fa73df85e9cd0b5ddd663d57852e0c
prompt_sha256: draft-1
translated_from: content/ru/1986/06/articles/10_fuks-formulyi-dlya-sin-nx-i-cos-nx-496f4dbd.md
source_content_sha256: 58395d83c49d768d1bc203714af5b14f08b28ae72127bf189f3faf7c3e88be84
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 25⟧

Mathematica 9, 10

Ghi chú được xuất bản dưới đây dành cho các tác phẩm kinh điển thực sự và mười tác phẩm kinh điển. Nó cũng sẽ hữu ích cho những ai đang chuẩn bị cho kỳ thi tuyển sinh đại học.

Công thức tính sin nx và cos nx

Bộ sưu tập bài toán dành cho những trường đại học đang xây dựng này có rất nhiều sin và cosin “nhiều góc”, tức là các biểu thức như sin 7x, cos 9x, v.v. Không phải lúc nào cũng vậy, nhưng khá thường xuyên, việc viết các biểu thức này dưới dạng hàm của sin x và cos x thường rất hữu ích. Về nguyên tắc, việc này có thể được thực hiện hoàn toàn tự động bằng cách sử dụng công thức tính sin và cos của một tổng, nhưng với việc sử dụng nhiều lần ngay cả công thức đơn giản nhất, không ai tránh khỏi sai sót; Ngoài ra, nó có thể gây lãng phí thời gian. Dưới đây là cách viết công thức sin nx và cos nx đơn giản, dễ nhớ và đáng tin cậy.

Tam giác Pascal. Rất có thể người đọc biết nó là gì; Tuy nhiên, chúng ta hãy nhớ lại định nghĩa. Tam giác Pascal là một bảng số có hàng thứ n chứa n+1 số tự nhiên. Trong trường hợp này, ở dòng trên cùng có hai đơn vị và với mỗi n ở dòng thứ n có các đơn vị ở các cạnh, và ở những vị trí khác có tổng của các cặp số liền kề liên tiếp từ dòng thứ (n-1) (hình 1).

Hình 1.

Tính chất đáng chú ý nhất của tam giác Pascal là các số từ hàng thứ n của nó là hệ số của đa thức $(x+1)^n$:
$(x+1)^1=x+1,$
$(x+1)^2=x^2+2x+1,$
$(x+1)^3=x^3+3x^2+3x+1,$
$(x+1)^4=x^4+4x^3+6x^2+4x+1,$
$(x+1)^5=x^5+5x^4+10x^3+10x^2+5x+1$

Họ đã từng làm điều này ở trường, nhưng bây giờ thì không.

Công thức. Viết dòng thứ n của tam giác Pascal. (Nhân tiện, để tìm dòng thứ n, bạn không cần đếm các dòng: ở dòng thứ n có n ở vị trí thứ hai.) May $\cos^n x$, $\cos^{n-1}x \sin x$, $\cos^{n-2}x \sin^2x$, ..., $\sin^n x$ vào các số từ dòng này theo trình tự. Trong chuỗi kết quả, hãy gạch chân các biểu thức ở vị trí chẵn: thứ hai, thứ tư, v.v. Viết các biểu thức không được nhấn mạnh và các biểu thức được gạch chân thành hai dòng riêng biệt. Trong mỗi dòng trong số hai dòng kết quả, hãy đặt một dấu trừ trước biểu thức thứ hai, một dấu trừ trước dòng thứ ba, một dấu trừ trước dòng thứ tư, v.v. Mọi thứ đã sẵn sàng - ở dòng trên cùng bạn đã viết biểu thức cho cos nx, ở dòng dưới cùng - cho sin nx.

Ví dụ về các biện pháp Với n=2, hàng trong tam giác Pascal có dạng 1, 2, 1. Chúng ta viết:

$$\cos^2x \ 2\cos x \sin x \sin^2x$$

$$\cos 2x=\cos^2x-\sin^2x,$$

$$\sin 2x=2\cos x \sin x.$$

Với n=3 chúng ta viết:

$$\cos^3x \ 3\cos^2x \sin x \ 3\cos x \sin^2x \sin^3x$$

$$\cos 3x=\cos^3x-3\cos x \sin^2x,$$

$$\sin 3x=3\cos^2x \sin x-\sin^3x.$$

Người đọc sẽ tìm thấy một số công thức tính cos nx và sin nx thu được theo cách này trên hình 2; dọc theo các đường đứt nét màu đỏ trên hình này bạn có thể đọc được các đường của tam giác Pascal.

Bài tập. Biết hàng thứ n của tam giác Pascal, người ta dễ dàng viết một công thức biểu diễn tg nx theo tg x. Hãy thử điều này.

Chứng minh công thức Trên thực tế, những công thức này là hệ quả của “Công thức Moivre” («Kvant», 1983, Số 2, trang 19, bài viết của L. S. Pontryagin “Số phức”). Tuy nhiên, để không đề cập đến những thứ không có trong chương trình,
