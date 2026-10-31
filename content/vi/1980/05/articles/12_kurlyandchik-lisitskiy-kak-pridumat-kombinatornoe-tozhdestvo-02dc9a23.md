---
id: 1980-5-kurlyandchik-lisitskiy-kak-pridumat-kombinatornoe-tozhdestvo-02dc9a23
issue: kvant_1980_5
year: 1980
number: "5"
title: Làm thế nào để đưa ra một danh tính tổ hợp
authors:
  - Курляндчик Л. Д.
  - Лисицкий А. Д.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 36
page_last: 36
page_labels: "34"
tag: KJUA
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 9149445694ea2e631aac4075c1c94e12ab93ed80a3dcd3194763c934546be0e7
prompt_sha256: draft-1
translated_from: content/ru/1980/05/articles/12_kurlyandchik-lisitskiy-kak-pridumat-kombinatornoe-tozhdestvo-02dc9a23.md
source_content_sha256: 76165c6f0174b4d1cdd500fdf6a0d52d2e4ce7b81ca0d30a7ed96d66bd32114c
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 34⟧

Làm thế nào để đưa ra một danh tính tổ hợp

Trong nhiều bài toán khác nhau, và thậm chí cả trong Bài toán Kvant, người ta thường gặp phải các đồng nhất thức chứa hệ số sinh học $C_k^i$. Thông thường, có thể chứng minh chúng bằng phương pháp quy nạp toán học, đôi khi bằng nhiều phép biến đổi xảo quyệt khác nhau, nhưng những bằng chứng này, như một quy luật, để lại cảm giác không hài lòng: họ hoàn toàn không rõ danh tính này được phát minh như thế nào, nói chung các danh tính mới được tìm thấy như thế nào.

Ở đây chúng tôi sẽ chỉ ra một số nguyên tắc cho phép bạn đưa ra những nhận dạng như vậy. Đặc biệt, chúng tôi sẽ giải thích cách chúng tôi nghĩ ra bài toán M470; Cậu học sinh Dagestan A. Gabibov đã hỏi về điều này trong một bức thư gửi «Kvant».

Hãy tưởng tượng rằng chúng ta cần tìm $\sum_{k=1}^{n} kx^{k-1}$. Hãy thử sử dụng nơi chúng tôi gặp biểu thức $kx^{k-1}$. Tất nhiên, trong công thức $(x^k)' = kx^{k-1}$. Thỏa thuận của chúng tôi “giết chết” bài toán; Thực ra,

$$\left( \sum_{k=1}^{n} x^k \right)' = \sum_{k=1}^{n} (x^k)' = \sum_{k=1}^{n} kx^{k-1}.$$

Ở phía bên kia,

$$\left( \sum_{k=1}^{n} x^k \right)' = \left( \frac{x^{n+1}-x}{x-1} \right)' =$$

$$= \frac{((n+1)x^n-1)(x-1)-(x^{n+1}-x)}{(x-1)^2} =$$

$$= \frac{1}{(1-x)^2} + \frac{nx-n-1}{(1-x)^2} x^n.$$

(Trong phép tính này, chúng ta đương nhiên giả định rằng $x \neq 1$.) Vì vậy,

$$\sum_{k=1}^{n} kx^{k-1} = \frac{1}{(1-x)^2} + \frac{nx-n-1}{(1-x)^2} x^n. \quad (1)$$

Bây giờ chúng ta hãy thử tìm

$$\sum_{k=1}^{n} k(k-1)x^{k-2}. \quad (\text{Особенности человекого характера побуждают повторить процедуру, которая помогла нам ранее в анализной ситуации...})$$

(D. Poya “Khám phá toán học”, M., “Nauka”, 1970, tr. 88). Vì vậy, hãy lặp lại nó!

$$\sum_{k=1}^{n} k(k-1)x^{k-2} =$$

$$= \sum_{k=1}^{n} (kx^{k-1})' = \left( \sum_{k=1}^{n} kx^{k-1} \right)' =$$

$$= \left( \frac{1}{(1-x)^2} + \frac{nx-n-1}{(1-x)^2} x^n \right)' = \frac{2}{(1-x)^3} +$$

$$+ \frac{n(1-x)^2+2(1-x)(nx-n-1)}{(1-x)^4} x^n +$$

$$+ \frac{n(nx-n-1)}{(1-x)^2} x^{n-1}. \quad (2)$$

Đẳng thức (1) và (2) rất cồng kềnh. Dựa vào chúng, chúng ta có thể thu được (ở mức $|x| < 1$) một công thức đẹp hơn

$$\sum_{k=0}^{\infty} C_{k+n}^n x^k = \frac{1}{(1-x)^{n+1}},$$

nhưng kết luận của nó vượt ra ngoài chương trình giảng dạy ở trường.

Bây giờ chúng ta hãy nói về một kỹ thuật cho phép chúng ta có được danh tính “mới” từ những danh tính “cũ”. Khoảng cách chiết tốt Công thức Newton

$$(1+x)^n = \sum_{i=0}^{n} C_i^n x^i.$$

Chúng ta hãy phân biệt sự bình đẳng này. chúng tôi nhận được

$$n(1+x)^{n-1} = \sum_{i=1}^{n} iC_i^n x^{i-1}. \quad (3)$$

Đặt $x=1$ và $x=-1$ bằng (3), chúng ta tìm thấy.
