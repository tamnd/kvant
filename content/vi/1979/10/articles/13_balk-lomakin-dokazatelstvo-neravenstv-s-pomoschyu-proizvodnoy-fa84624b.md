---
id: 1979-10-balk-lomakin-dokazatelstvo-neravenstv-s-pomoschyu-proizvodnoy-fa84624b
issue: kvant_1979_10
year: 1979
number: "10"
title: Chứng minh bất đẳng thức bằng đạo hàm
authors:
  - Балк М. Б.
  - Ломакин Ю. В.
rubric: po-stranitsam-shkolnyh-uchebnikov
rubric_sub: По страницам школьных учебников
page_first: 38
page_last: 40
page_labels: 36-38
tag: CPOD
lang: vi
source: kvant_digital
extraction: vision
content_sha256: f8a5d2e5a4b5ee0f2a68c3238f7be7585fc8ba3ee9188f2659adc21ea7322c5e
prompt_sha256: draft-1
translated_from: content/ru/1979/10/articles/13_balk-lomakin-dokazatelstvo-neravenstv-s-pomoschyu-proizvodnoy-fa84624b.md
source_content_sha256: a062e6d54767d0c633bd1c9a5662cae9e503489fc2fc841f9d249f01164772a0
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 36⟧

Chứng minh các bất đẳng thức bằng cách sử dụng một giá trị tùy ý tại trại trường "Matematik-79" (vùng Vologda), nó cho thấy cách sử dụng quy trình thông tin về các giá trị tùy ý để xác minh tính đúng đắn của các bất đẳng thức.

Để chứng minh các bất đẳng thức, định lý sau đây đặc biệt hữu ích (“Đại số và Nguyên tắc Phân tích 9,” đoạn 54):

Định lý 1. Nếu hàm $f$ có tích phân dương tùy ý $|a|; b|$, thì hàm này trở về $|a|; b|$. Nếu chức năng $f$ có tích phân âm tùy ý $|a|; b|$, thì chức năng tạo ra nước tiểu (hoặc tương ứng là giảm) diễn ra trong toàn bộ kết quả này $*$).

Hãy bắt đầu với hai ví dụ về ứng dụng định lý này: ví dụ thứ nhất đơn giản, ví dụ thứ hai là ví dụ cuối cùng.

Ví dụ 1. Chứng minh rằng với $x > 1$
$$x^2 - 1 > 2 \ln x.$$
Bất đẳng thức này có đúng với $0 < x < 1$ không?

Lời giải. Xét hàm $f(x) = x^2 - 1 - 2 \ln x$.

*) Một phát biểu tương tự vẫn đúng nếu thay vì nhận được phân chia $|a|; b|$ chúng ta nhận được phân chia $|a|; b|$ hoặc phân đoạn $|a|; b|$.

chúng tôi có
$$f'(x) = 2x - \frac{2}{x} = \frac{2}{x}(x^2 - 1) > 0$$
tại $x > 1$.

Do đó, $f$ trở về $1; +\infty$ [. Nếu chúng ta cũng tính đến việc hàm $f$ liên tục trên $1; +\infty$ [ (nghĩa là tại bất kỳ điểm nào trong khoảng này), thì sự trả về của $f$ diễn ra trên $1; +\infty$ [. Do đó, tại $1 < x < +\infty$ sẽ có $f(x) > f(1)$, tức là $x^2 - 1 - 2 \ln x > 0$. Vì vậy, $x^2 - 1 > 2 \ln x$ tại $0 < x < 1$.

Ví dụ 2. Độ cao, cái nào lớn hơn: $79^{3/5} + 1900^{3/5}$ hay $1979^{3/5}$?

Lời giải. Hãy giải bài toán mở rộng hơn: cái nào lớn hơn $a^p + b^p$ hoặc $(a + b)^p$, nếu $0 < a < b$ và $0 < p < 1$? Hãy xem xét $0; +\infty$ [chức năng $f(x) = (a + x)^p - (a^p + x^p)$].

Chúng tôi có:
$$f'(x) = p(a + x)^{p-1} - px^{p-1} = p\left(\frac{1}{a+x}\right)^{p-1} - \left(\frac{1}{x}\right)^{p-1} < 0$$
tại $0 < x < +\infty$. Điều này có nghĩa là $f$ bằng $0; +\infty$ [giảm. Do đó, từ $0 < a < b$ suy ra $f(b) < f(a)$, tức là $(a + b)^p - (a^p + b^p) < (a + a)^p - (a^p + a^p) = a^p(2^p - 2) < 0, a^p + b^p > (a + b)^p$. Cụ thể là $79^{3/5} + 1900^{3/5} > 1979^{3/5}$.

Đối với lời giải các ví dụ khác, chúng ta cần hệ quả tất yếu sau từ Định lý 1:

Định lý 2. Giả sử bất kỳ hàm nào trong số các hàm $f$ và $g$ liên tục trong đó chúng ta thu được tích phân $|a|; b|$ và có tích phân tùy ý $|a|; b|$ trong bất kỳ hàm nào. Để làm được điều này, bất đẳng thức đúng ở mọi nơi trên tích phân $|a|; b|$
$$f(x) < g(x),$$
(1)
Chỉ cần đồng thời thỏa mãn hai điều kiện:
I. $f'(x) < g'(x)$ ở mọi nơi trên $|a|; b|$,
(2)

⟦folio 37⟧

P. $f(a) \leq g(a)$. (3)

Bằng chứng. Hàm $F(x) = g(x) - f(x)$ liên tục trên $[a; b]$, và $F(a) \geq 0$ và $F'(x) > 0$ trên $[a; b]$. Theo Định lý 1, hàm $F$ tăng $[a; b]$, do đó với $a < x < b$ chúng ta có $F(x) > F(a) \geq 0$, tức là $f(x) < g(x)$ ở mọi nơi trên $[a; b]$.

Chúng ta cũng sẽ minh họa việc áp dụng Định lý 2 bằng hai ví dụ.

Ví dụ 3. Chứng minh rằng với $x > 0$
$$\ln(1+x) < x.$$ (4)

Lời giải e. Đạo hàm (4), ta thu được
$$\frac{1}{1+x} < 1,$$
điều này rõ ràng đúng ở $[0; +\infty]$. Ngoài ra, $\ln(1+0) = 0$. Do đó, theo Định lý 2, bất đẳng thức (4) đúng với $0 < x < +\infty$.

Ví dụ 4. Kiểm tra xem bất đẳng thức có đúng với $x_1 > x_2 > 0$ không
$$\frac{x_1 - x_2}{\ln \frac{x_1}{x_2}} < \frac{1}{2}(x_1 + x_2).$$ (5)

Lời giải e. Chúng ta có thể chuyển từ bất đẳng thức có hai biến sang bất đẳng thức có một biến nếu chúng ta đặt $x = \frac{x_1}{x_2}$. Khi đó (5) có dạng
$$\frac{x-1}{\ln x} < \frac{1}{2}(x+1).$$ (6)

$x_1 > x_2 > 0$ ngụ ý $x > 1$. Việc phân biệt một phân số có $\ln x$ trong mẫu số là bất tiện. Do đó chúng ta hãy viết lại bất đẳng thức (6) dưới dạng tương đương sau:
$$\frac{x-1}{x+1} < \frac{1}{2}\ln x.$$ (7)

*) Nếu chúng ta yêu cầu thêm rằng các hàm $f$ và $g$ không đúng tại điểm $b$, thì (như đã thấy rõ từ chứng minh) bất đẳng thức (1) sẽ đúng tại điểm $b$. Có thể chứng minh rằng Định lý 2 vẫn đúng trong trường hợp vi phạm bất đẳng thức nghiêm ngặt (2) (được thay thế bằng đẳng thức $f'(x) = g'(x)$) tại một số hữu hạn các điểm (hoặc thậm chí ở vô số điểm, trừ khi các điểm đó lấp đầy một khoảng nào đó có dạng $]a; c[$, trong đó $a < c \leq b$).

Để quyết định xem bất đẳng thức này có đúng hay không, chúng ta hãy tìm hiểu xem bất đẳng thức phát sinh khi vi phân từng số hạng có đúng hay không. Vì vậy ta phải xét bất đẳng thức
$$\frac{2}{(x+1)^2} < \frac{1}{2x}$$ (8)

hoặc bất đẳng thức tương đương $(x-1)^2 > 0$.

Điều sau đúng với $x > 1$ và do đó, với những $x$ (8) này là đúng. Hơn nữa, tại $x = 1$ cả hai vế của bất đẳng thức (7) đều có giá trị bằng (không). Ta thấy rằng các điều kiện của Định lý 2 được thỏa mãn nên bất đẳng thức (7) đúng và cùng với nó (6) và (5) đều đúng.

Đôi khi, khi chứng minh bất đẳng thức, việc áp dụng vi phân từng số hạng không phải một lần mà nhiều lần sẽ rất hữu ích. Chính xác hơn, đôi khi sẽ hữu ích khi sử dụng hệ quả tất yếu sau đây của Định lý 2*):

Định lý 3. Cho hàm số $f$ và $g$ sai về đạo hàm $[a; b]$ và có đạo hàm cấp $n$ tại mỗi điểm của tích phân $]a; b[$. Để sự bất bình đẳng đúng ở mọi nơi
$$f(x) < g(x) \text{ на } [a; b],$$ (9)
chỉ cần thỏa mãn các điều kiện sau là đủ:
I. Bất đẳng thức thu được từ bất đẳng thức [9] bằng đạo hàm $n$ lần, $m. k$, đúng. ở mọi nơi trên $[a; b]$
$$f^n(x) < g^n(x);$$ (10)
II. $f(a) \leq g(a)$,
$$f'(a) \leq g'(a),$$ ...
... $f^{(n-2)}(a) \leq g^{(n-2)}(a);$
$$f^{(n-1)}(a) \leq g^{(n-1)}(a).$$

Bằng chứng. Vì $[f^{(n-1)}(x)]' < [g^{(n-1)}(x)]'$ nằm trên $[a; b]$ và $[f^{(n-2)}(x)]' < [g^{(n-2)}(x)]'$ ở mọi nơi trên $[a; b]$. Ngoài ra, theo điều kiện, $f^{(n-2)}(a) \leq g^{(n-2)}(a)$. Do đó, theo định lý

*) Đạo hàm của hàm tùy ý $f$ được gọi là hàm tùy ý thứ hai và ký hiệu là $f''$; tương tự, các định nghĩa về phần thứ ba, thứ tư là tùy ý và nói chung là tùy ý theo bất kỳ thứ tự nào $n$ (ký hiệu: $f^{(n)}$).

⟦folio 38⟧

biện pháp 2: $f^{(n-2)}(x) < g^{(n-2)}(x)$ luôn bật $|a|; b[$. Lặp lại các phép tính tương tự, sau một số hữu hạn bước, chúng ta thu được rằng mọi thứ trên $|a|; b[$ đều đúng đối với các bất đẳng thức nghiêm ngặt $f^{(n-3)}(x) < g^{(n-3)}(x), \dots, f''(x) < g''(x), f'(x) < g(x)$ và cuối cùng, $f(x) < g(x)$, đó là điều chúng ta cần chứng minh.

Ví dụ 5. Chứng minh rằng với $x \neq 0$ bất đẳng thức $e^x + e^{-x} > 2 + x^2$ đúng.

Lời giải. Trước tiên chúng ta hãy xem xét trường hợp $x > 0$. Chúng ta hãy phân biệt (11) số hạng này với số hạng khác vài lần và xem liệu chúng ta có nhận được một bất đẳng thức có giá trị chắc chắn không còn nghi ngờ gì nữa hay không. Chúng tôi nhận được những điều sau đây:
$e^x - e^{-x} > 2x;$
$e^x + e^{-x} > 2;$
$e^x - e^{-x} > 0$.

Bất đẳng thức cuối cùng cho $x > 0$ là rất đúng. Ngoài ra, với $x = 0$ các đẳng thức $e^0 + e^{-0} = 2 + 0^2, e^0 - e^{-0} = 2 \cdot 0, e^0 + e^{-0} = 2$ là đúng. Theo Định lý 3, bất đẳng thức (11) đúng với $x > 0$. Vì thay $x$ bằng $-x$ cả hai vế của bất đẳng thức (11) đều không thay đổi nên bất đẳng thức này cũng đúng với mọi $x < 0$.

Danh sách độc giả gửi sửa lời giải bài toán từ Bài toán Kvant
(Kết thúc. Xem phần đầu ở trang 7, 14, 25)
(Kaynas) 38; G. Irisov (Donetsk) 40;
A. Kapralov (Tbilisn) 38-41; V. Kelman (Moscow) 38, 40; E. Kodan (Dipropetrovsk) 38; A. Kozhevnikov (Dipropetrovsk) 34; G. Kolomitsev (Sumgant) 36; V. Komov (Alexandrov) 33-41, 43-46; K. Kondratye (Moscow) 38, 40, 45, 47; Yu. Kordyukov (Serov) 38; I. Korotkov (Volgograd) 43, 47; A. Kostereyev (Semiluk) 38-41; O. Kravets (Voronezh) 40, 41, 46; A. Kreines (Kolchugino) 35; A. Kruntsov (Kursk) 33; A. Kuprin (Moscow) 38—41; V. Kuryan (Rostov-on-Don) 34, 38—41, 44; A. Kucher (Donetsk) 35; A. Kusherov (Moscow) 38, 44; A. Lazaryan (Lobnya, vùng Moscow) 35, 37; V. Lashkin (Kyiv) 35-40; A. Lebedev (Gorky) 40; S. Lodunov (Moscow) 40, 47; D. Lodmirsky (Kyiv) 33, 34, 36, 37, 47; S. Mazaryan (Kostroma) 38; S. Malamanov (Leningrad) 35, 38; A. Maslennikov (n. N-Taryal Mar Cộng hòa xã hội chủ nghĩa Xô viết tự trị) 46; A. Minaev (Saratov) 38; A. Mocilier (Sverdlovsk) 35, 38, 40, 41, 44, 46, 47; M. Morozov (Ashgabat) 40; I. Muromtsev (Moscow) 33, 36, 38-41; D. Nadezhdin (Kurgan) 38-41; V. Natalia (Ashgabat) 38, 47; A. Odlovlin* (Irkutsk) 38, 41; I. Omelyan (Lviv) 35, 37-44, 46, 47; O. Orzamedov (trung tâm khu vực Kyzyl-Atrek, TSSR)

Urazhenya

Kiểm tra tính đúng đắn của các bất đẳng thức sau:
1. $e^x > 1 + x$ tại $x \neq 0$;
2. $(p + q)^6 < 32(p^6 + q^6)$ tại $p > 0, q > 0$;
3. $\sin x > x - \frac{x^3}{6}$ tại $x > 0$;
4. $2\sqrt{x} > 3 - \frac{1}{x}$ tại $x > 1$;
5. $tg x > x + \frac{x^3}{3}$ tại $0 < x < \frac{\pi}{2}$;
6. $\sin x < \frac{1}{2}x(\pi - x)$ tại $0 < x < \frac{\pi}{2}$;
7. $2ab \ln \frac{b}{a} < b^2 - a^2$ tại $0 < a < b$;
8. $e^x > 1 + x + \frac{1}{2}x^2$ tại $x > 0$;
9. $\ln (1 + x) < x - \frac{x^2}{2} + \frac{x^3}{3}$ tại $x > 0$.

10. Một $n$-giác đều có chu vi $p_n$ được ghi trong một hình tròn bán kính $R$, và một $n$-giác đều có chu vi $P_n$ không được ghi. Chứng minh bất đẳng thức sau (do nhà vật lý và toán học nổi tiếng Christas Huygens thực hiện): $2p_n + P_n > 6\pi R$.
