---
id: 1980-12-chehlov-eti-kovarnyie-vektoryi-0c44aef9
issue: kvant_1980_12
year: 1980
number: "12"
title: Những vectơ "quỷ quyệt" này
authors:
  - Чехлов В. И.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 42
page_last: 46
page_labels: 40, 42, 43, 44
tag: KANU
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 267e2997c5a9725515f4e3eac0b3daf22942e139af096588c2cf1e09dd043377
prompt_sha256: draft-1
translated_from: content/ru/1980/12/articles/18_chehlov-eti-kovarnyie-vektoryi-0c44aef9.md
source_content_sha256: e5111849d0c4099c441094159fd3a9621927bbef7137fa03666b83f0dc17b893
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 40⟧

Những vectơ "quỷ quyệt" này

Ghi chú này dành cho một số tính năng của việc áp dụng vectơ cho lời giải hình học bài toán.

Việc sử dụng vectơ dựa trên thực tế là các phát biểu khác nhau về vị trí tương đối của một điểm, đường thẳng và mặt phẳng có thể được hình thành bằng “ngôn ngữ vectơ”, đặc biệt là sử dụng các khái niệm cộng tuyến và đồng phẳng. Điều này cho phép chúng ta giảm hình học bài toán thành đẳng thức vectơ. Ngược lại, một đẳng thức vectơ có thể được rút gọn (đặc biệt, dựa trên tính duy nhất của định lý phân rã) thành một đẳng thức đại số hoặc một hệ các đẳng thức đại số.

Bài toán 1. Đáy của hình bình hành ABCD. Mặt phẳng cắt các cạnh SA, SB, SC và SD của đường song song tương ứng tại các điểm M, N, P và Q sao cho |SM|:|SA|=a, |SN|:|SB|=b, |SP|:|SC|=c,

Cơm. 1.

|SQ|:|SD|=d. Chứng minh rằng $\frac{1}{a} + \frac{1}{c} = \frac{1}{b} + \frac{1}{d}$.

Lời giải e. Các đoạn NM, NP và NQ (Hình 1) nằm trong cùng một mặt phẳng. Theo định nghĩa của vectơ đồng phẳng thì các vectơ NM, NP và NQ là đồng phẳng. Các vectơ NM và NP hiển nhiên không thẳng hàng nên theo định lý phân tích các vectơ đồng phẳng có các số x và y sao cho $NQ = xNM + yNP$. (1)

Chúng ta hãy phân tách các vectơ này thành ba vectơ không đồng phẳng SA, SB và SC. Chúng ta có SM=aSA, SN=bSB, SP=cSC, SQ=dSD, từ đâu

$NM = SM - SN = aSA - bSB$, (2)
$NP = SP - SN = cSC - bSB$, (3)
$NQ = SQ - SN = dSD - bSB$. (4)

Vì $SD = SA + AD$ và $AD = BC = SC - SB$, nên từ (4) suy ra $NQ = dSA - (d + b)SB + dSC$. (5)

Thay (2), (3), (5) vào (1), ta được

$NQ = dSA - (d + b)SB + dSC = axSA - b(x + y)SB + cySC$. (6)

Do tính duy nhất của khai triển nên đẳng thức vectơ (6) tương đương với hệ

$$\begin{cases}
d = ax; \\
d + b = b(x + y), \\
d = cy.
\end{cases}$$

Do đó $x + y = \frac{d}{a} + \frac{d}{c} = \frac{d + b}{b}$ hoặc $\frac{1}{a} + \frac{1}{c} = \frac{1}{b} + \frac{1}{d}$.

Trong ví dụ được xem xét, đẳng thức vectơ (6) đã được rút gọn thành hệ (7). Cần nhớ rằng đẳng thức của vectơ trong không gian tương đương với hệ ba đẳng thức đại số. Do đó, nếu ít nhất một trong các đẳng thức của hệ này sai đối với bất kỳ giá trị nào của biến, thì đẳng thức vectơ là sai và hình học ban đầu bài toán không có nghiệm. Ví dụ đơn giản sau đây xác nhận điều này.

⟦folio 42⟧

Chúng tôi nhấn trong mặt phẳng OAB. Điều này có nghĩa là các vectơ $\vec{a}, \vec{b}$ và $\vec{c}$ là đồng phẳng. Với những ngoại lệ ở trên, việc chứng minh thậm chí còn đơn giản hơn và chúng tôi xin nhường lại cho bạn đọc.

Bài toán 3 (“Hình học 9-10”, Số 247). Điểm A là đỉnh chung của hình bình hành ABCD và $AB_1C_1D_1$. Chứng minh rằng các vectơ $\vec{BB}_1, \vec{CC}_1, \vec{DD}_1$ đồng phẳng.

Lời giải. Chúng ta có $\vec{CC}_1 = \vec{CB} + \vec{BB}_1 + \vec{B}_1\vec{C}_1$ (Hình 4) và vì $\vec{CB} = \vec{DA}$ và $B_1\vec{C}_1 = \vec{AD}_1$, chúng ta nhận được $\vec{CC}_1 = \vec{BB}_1 + (\vec{DA} + \vec{AD}_1)$. Nhưng $\vec{DA} + \vec{AD}_1 = \vec{DD}_1$, do đó $\vec{CC}_1 = \vec{BB}_1 + \vec{DD}_1$. Từ (*) suy ra rằng các vectơ $\vec{CC}_1, \vec{BB}_1$ và $\vec{DD}_1$ là đồng phẳng.

Bài toán 4. Ba vectơ đơn $\vec{a}, \vec{b}$ và $\vec{c}$ này giống với $(\vec{a}, \vec{c}) = (\vec{b}, \vec{c}) = \frac{\pi}{3}, (\vec{a}, \vec{b}) = \frac{\pi}{2}$. Các vectơ này có đồng phẳng không?

Chúng tôi đề nghị trước tiên hãy tìm lỗi trong lý do sau:

"Chúng ta hãy chứng minh rằng $\vec{a}, \vec{b}$ và $\vec{c}$ là đồng phẳng. Chúng ta sẽ tìm các số $x$ và $y$ thỏa mãn $\vec{c} = \vec{x}a + \vec{yb}$.

Để làm điều này, chúng ta nhân cả hai vế của (11) với vectơ $\vec{a}$. Chúng ta nhận được $\vec{c} \cdot \vec{a} = \vec{x}a \cdot \vec{a} + \vec{yb} \cdot \vec{a}$, từ đó $x = \frac{1}{2}$. Nhân cả hai vế của (11) với $\vec{b}$, chúng ta thu được $\vec{c} \cdot \vec{b} = \vec{x}a \cdot \vec{b} + \vec{yb} \cdot \vec{b}$, do đó $y = \frac{1}{2}$. Có nghĩa,

$$\vec{c} = \frac{1}{2} \vec{a} + \frac{1}{2} \vec{b},$$

nghĩa là, bởi (*) các vectơ $\vec{a}, \vec{b}, \vec{c}$ là đồng phẳng.”

Thật dễ dàng để khẳng định rằng lý luận này là sai lầm. Ở một thời điểm nào đó, chỉ cần thử các vectơ $\vec{a}, \vec{b}, \vec{c}$ với các góc cho trước giữa chúng là đủ. Ngay lập tức làm rõ rằng điều này là không thể. Điều này có nghĩa là các vectơ $\vec{a}, \vec{b}$ và $\vec{c}$ không đồng phẳng.

Để hiểu sai lầm xảy ra ở đâu, chúng ta hãy quay lại phần đầu của cuộc tranh luận. Ở đó, mục tiêu được thể hiện là tìm các số $x$ và $y$ mà đẳng thức (11) là đúng. Nhưng việc đánh số này đã không được thực hiện. Thật vậy, các phép tính sau đây chỉ chứng minh rằng từ (11) suy ra (12), và không chứng minh gì thêm. Cả sự tồn tại của các số $x$ và $y$ mà (11) là đúng, cũng như các đẳng thức (12) đều chưa được chứng minh. Và điều này có nghĩa là kết luận “theo (*) các vectơ $\vec{a}, \vec{b}, \vec{c}$ là đồng phẳng” là không hợp lý.

Sai lầm ở đây là từ việc lập luận đã rút ra một kết luận không tương ứng với nhận định đã được chứng minh.

Bây giờ chúng ta trình bày vectơ lời giải bài toán 4.

Ta hãy chứng minh bằng phản chứng rằng các vectơ $\vec{a}, \vec{b}, \vec{c}$ không đồng phẳng. Giả sử có các số $x$ và $y$ sao cho đẳng thức (11) là đúng. Khi đó, như trước đây, chúng ta thấy rằng (12) cũng đúng. Nhân (12) vô hướng với $\vec{c}$, ta thu được đẳng thức $1 = \frac{1}{4} + \frac{1}{4}$ đúng, tức là $1 = \frac{1}{2}$. Mâu thuẫn này chứng tỏ (11) không đúng với mọi $x$ và $y$, tức là các vectơ $\vec{a}, \vec{b}, \vec{c}$ không đồng phẳng.

Hãy xem xét một ví dụ khác về việc việc dịch không đầy đủ các điều kiện của hình học bài toán sang “ngôn ngữ vectơ” có thể dẫn đến sai sót như thế nào.

Bài toán 5. Độ dài cạnh AD của tứ diện ABCD thỏa mãn các điều kiện tương ứng:

$$\overrightarrow{ABC} = \frac{\pi}{2}, \overrightarrow{BCD} = (AB, CD) = \frac{5}{7},$$

$$|AB| = |BC| = |CD| = a?$$

⟦folio 43⟧

"Lời giải". Vì $\vec{AD} = \vec{AB} + \vec{BC} + \vec{CD}$, chúng ta nhận được $\vec{AD}^2 = \vec{AB}^2 + \vec{BC}^2 + \vec{CD}^2 + 2\vec{AB} \cdot \vec{BC} + 2\vec{AB} \times \vec{CD} + 2\vec{BC} \cdot \vec{CD}$. Ở đây $\vec{AB}^2 = \vec{BC}^2 = \vec{CD}^2 = a^2$, $\vec{AB} \cdot \vec{BC} = 0$, $\vec{BC} \times \vec{CD} = a^2$ cos $(\pi - \vec{BCD}) = -\frac{5}{7} a^2$, $\vec{AB} \cdot \vec{CD} = a^2$ cos $(\vec{AB}, \vec{CD})$ và vì có thể xảy ra hai trường hợp: $(\vec{AB}, \vec{CD}) = \arccos \frac{5}{7}$ hoặc $(\vec{AB}, \vec{CD}) = \pi - \arccos \frac{5}{7}$ nên chúng ta nhận được $\vec{AB} \times \vec{CD} = \frac{5}{7} a^2$ hoặc $\vec{AB}, \cdot \vec{CD} = -\frac{5}{7} a^2$. Theo sau đó là $\vec{AD}^2 = 3a^2$ hoặc $\vec{AD}^2 = \frac{a^2}{7}$. Vì vậy, $|\vec{AD}| = \sqrt{3} a$ hoặc $|\vec{AD}| = \frac{a}{\sqrt{7}}$.

Thoạt nhìn, không có chỗ cho sai sót trong lời giải này. Tuy nhiên, có một lỗi trong đó. Thực tế là hình học bài toán được đặt cân bằng bài toán với hệ vectơ lời giải:
$$\begin{cases}
|\vec{AB}| = |\vec{BC}| = |\vec{CD}| = a, \\
\vec{AB} \cdot \vec{BC} = 0, \\
\vec{AB} \cdot \vec{CD} = \pm \frac{5}{7} a^2, \\
\vec{BC} \cdot \vec{CD} = -\frac{5}{7} a^2, \\
\vec{AD} = \vec{AB} + \vec{BC} + \vec{CD}.
\end{cases}$$

Đây là một hệ thống có bốn vectơ chưa biết $\vec{AB}, \vec{BC}, \vec{CD}$ và $\vec{AD}$, và công thức hình học bài toán 5 hiện có thể được thay thế bằng công thức đại số (vectơ): chiều dài là bao nhiêu

Cơm. 5.

⟦folio 44⟧

Nhân cả hai vế của (15) với $\vec{AB}$, chúng ta thu được $x = \pm \frac{5}{7}$ và nhân (15) với $\vec{BC}$, chúng ta tìm được $y = -\frac{5}{7}$. Sau đó

$$|\vec{CD}|^2 = (x^2 + y^2 + z^2)a^2 = \left(\frac{50}{49} + z^2\right)a^2 > a^2,$$

và điều này mâu thuẫn với điều kiện $|\vec{CD}| = a$.

Điều này có nghĩa là hệ thống (14) không có lời giải và chúng ta nhận được đáp số giống như trước.

bài toán kèm theo ghi chú này có thể được giải bằng cách sử dụng vectơ và số hình học.

Bài tập
1. Cho các điểm $A, B, C$ không nằm trên cùng một đường thẳng và các điểm $D$ và $O$, $O \neq D$. Chứng minh rằng để điểm $D$ thuộc mặt phẳng $ABC$ thì cần và đủ $OD = xOA + yOB + zOC$, trong đó $x + y + z = 1$.

2. Đáy của đường thẳng $SABCD$ là hình bình hành $ABCD$. Trên các cạnh $AB, AS$ và $SC$ lần lượt có các điểm $M, N$ và $P$ sao cho $|BM| : |AB| = |AN| : |AS| = |SP| : |SC| = 2:3$. Một đường thẳng được vẽ qua điểm giữa $Q$ của cạnh $BC$, song song với mặt phẳng $MNP$ và cắt đường thẳng $SD$ tại điểm $R$. Tìm tỉ số $|DR| : |DS|$.

3. Tất cả các cạnh của một đường thẳng đều $ABCA_1B_1C_1$ có độ dài $a$. Một đường thẳng vuông góc với mặt phẳng $BA_1C_1$ cắt các đường thẳng $BC_1$ và $AB_1$ lần lượt tại các điểm $M$ và $N$. Tìm $|MN|$.

4. Cho ba đường thẳng không cùng thuộc một mặt phẳng. Có bao nhiêu đường thẳng đi qua một điểm cho trước và tạo các góc bằng nhau với các đường thẳng $^2$.

5. Trong tứ diện $ABCD$ $|AB| = |BC| = |CD|$, $ABC = a$, $BCD = (AB, CD) = \beta$. Tìm góc giữa các đường thẳng $AD$ và $BC$. Với những gì a và β bài toán a) không có lời giải; b) có một lời giải; c) có hai lời giải?

Danh sách độc giả đã gửi đúng lời giải bài toán từ Zadanika «Kvant»
(Để bắt đầu, xem trang 34)

S. Doronin (Dnepropetrovsk) 17; A. Dremin (làng Chernogolovka, vùng Moscow) 12; A. Durbak (Rohatyn) 16; S. Dymshakov (Shadrinsk) 16, 17; Yu. Eliseev (Velikiye Luki) 4; I. Eliseevich (Chernigov) 4, 6, 7; I. Elkanovich (Baku) 17; T. Enchev (Yambol, NRB) 9, 12; V. Zhordochki (Orsk) 4, 6-8; V. Zavarzin (Chimkent) 16; A. Zanevsky (Leningrad) 4, 6-9, 11, 16, 17; M. Zeifman (Vologda) 4, 6, 7, 9, 11, 12, 16; I. Zilberberg (Alma-Ata) 6; V. Zolotagevsky (p/o Berezovskoye, vùng Kharkov) 7; I. Zybtsev (Uzhur) 9, 11, 12, 17; T. Ivanov (Pleven, Belarus) 16, 17; A. Ivanov (Voronezh) 8, 12; V. Ivakhenko (Kyiv) 11; V. Izerenin (Novosibirsk) 7, 9, 11, 12, 16, 17; V. Izrailit (Dnepropetrovsk) 9, 16, 17; V. Kaazlovsky (Kharkov) 11, 12; S. Kalmykov (Kopeisk) 6, 12; A. Kaplan (Sumgant) 8, 17; D. Kaplan (Zelenograd) 7; A. Karsev (Belgorod) 7, 17; M. Kachkatsivili (Rustavi) 12; E. Kashanov (Ufa) 4; A. Kechedjyan (Yerevan) 6, 7, 9, 11, 12, 16; M. Kibirev (Tula) 8, 9, 12; Yu. Kirpach (Kyiv) 4, 6, 7, 11, 17; Yu. Kovernik (Zaporozhye) 6; E. Koran (Dnepropetrovsk) 8, 9, 11, 12; A. Kozhevnikov (Dnepropetrovsk) 8, 9, 12; V. Kozlovsky (Novolukoml) 8-12; T. Kozhoridze (Telvi) 12; D. Kolomotsev (Sumgant) 4, 6-9, 11; V. Komov (Aleksadrov) 4, 6-12, 16, 17; T. Kondratskaya (Kyiv) 4, 6-8; S. Konkin (Arzamas) 4, 9, 11, 12; V. Korobov (Kirovograd) 16; K. Korchazin (Yerevan) 16; M. Kostin (Saratov) 12; I. Kostyuevich (Leningrad) 4, 6, 9, 12, 17; D. Kotelnikov (Magnitogorsk) 4, 6, 7, 16, 17; M. Kravtsov (Kommunarsk) 16; K. Krapivnoy (Zaporozhye) 6, 7; I. Krasikov (Kyiv) 8, 9, 11, 12; A. Kreines (Kolchugino) 17; L. Kreminskaya (Rivne) 8; E. Krenzel (Moscow) 17; R. Chris (Kyiv) 4, 7, 8, 11, 12; I. Krolivets (Kramatorsk) 11, 12; E. Kuznetsov (CHISINAU) 6, 8, 11, 12; P. Kuznetsov (Kyiv) 4, 6, 8-12; A. Kuzmin (Alma-Ata) 6, 7, 11; D. Kuksenkov (Leningrad) 16, 17; S. Kurchatov (Saratov) 4, 7; B. Lapidus (Moscow) 11, 12, 17; M. Levenkov (Vereshchino) 17; V. Leites (Moscow) 4, 6, 7; I. Leonov (Voronezh) 6, 11, 12; D. Leshchinsky (Magnitogorsk) 16; F. Lomaya (Simferopol) 9, 12; I. Lukuyanchuk (Kyiv) 4, 6, 17; E. Lyubovitsky (Kostroma) 16; A. Lyapin (Gomel) 4, 6, 16, 17; A. Mazurkovich (Lytkarino) 6, 9, 11, 12; Z. Makimov (Tashkent) 16, 17; A. Maltsin (Gorky) 16; V. Maltsev (Ufa) 17; O. Manuilenko (Kyiv) 17; S. Maslennikov (làng Meshon, vùng Gomen) 4; S. Makhortykh (Lisichansk) 9; A. Mikula (Zhidachkov) 4, 6, 12, 17; S. Milovanov (Zaporozhye) 17; S. Mikhailovsky (quận Vinogradovsky, vùng Arkhangelsk) 7, 11, 12, 16; G. Molchanov (Saratov) 7-9, 11, 12; D. Myakshev (Angarsk) 11; R. Nabokov (Moscow) 4, 7; S. Nadtochiy (Moscow) 4, 6-9, 11, 12; A. Nazarenko (Kyiv) 6-9, 11; M. Nylovzen (Baku) 16; D. Nishinaidze (Kutansi) 8; D. Nozdrin (Saratov) 4, 6; S. Obochevets (Leningrad) 6, 7; D. Ovsyannikov (Leningrad) 4, 6-9, 12; S. Odintsova (Kyiv) 4, 6, 7, 11; A. Orlov (Cuối cùng xem trang 55)
