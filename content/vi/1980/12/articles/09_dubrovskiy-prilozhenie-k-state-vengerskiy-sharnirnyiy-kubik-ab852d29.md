---
id: 1980-12-dubrovskiy-prilozhenie-k-state-vengerskiy-sharnirnyiy-kubik-ab852d29
issue: kvant_1980_12
year: 1980
number: "12"
title: '[Phụ lục của bài viết “Khối khớp nối Hungary”]'
authors:
  - Дубровский В. Н.
rubric: smes
page_first: 23
page_last: 23
page_labels: "21"
tag: 66OK
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 8038ce77cb40df0dbde2804e2b7b5b30ee9048aa0a324f723a090317e9d72b94
prompt_sha256: draft-1
translated_from: content/ru/1980/12/articles/09_dubrovskiy-prilozhenie-k-state-vengerskiy-sharnirnyiy-kubik-ab852d29.md
source_content_sha256: bd15af4de5cc2f68cda6d7c7bfad3324dc2707140783f29611953f58ce30ed76
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 21⟧

Nếu chỉ có hai viên xúc xắc được quay không chính xác thì cả hai viên xúc xắc đó không thể yêu cầu quay theo cùng một hướng. Nếu không, chúng ta sẽ cùng nhau xoay chúng và một khối khác - một tình huống sẽ xuất hiện với một khối được xoay không chính xác, điều này là không thể do III.

Vì vậy, hai con xúc xắc quay không chính xác đòi hỏi phải quay theo các hướng khác nhau. Hãy biến một trong các hình khối này và hai hình khối trước đó đứng đúng hướng. Và sau đó - theo hướng khác - hai khối mới này và khối thứ hai trước đó bị quay sai. Kết quả là tất cả các hình khối sẽ ở đúng vị trí!

Ứng dụng*)

Hãy để chúng tôi biểu thị trạng thái chính xác của khối bằng $S_0$. Chúng ta hãy chèn các số $i=1, 2, ..., 8$ của các đỉnh của nó (khối góc) và các số $j=1, 2, ..., 12$ của các cạnh của nó (khối giữa). Trên các cạnh, chúng ta sẽ chọn (và điền) bất kỳ hướng nào (và hướng các mũi tên tương ứng vào các hình khối ở giữa) sao cho các cạnh song song được căn chỉnh.

Giả sử rằng ở một trạng thái nhất định**) $S$ của khối $j$ khối ở giữa rơi vào cạnh $j'$; Hãy so sánh hướng của cạnh $j'$ (mà chúng ta đã điền) với mũi tên chỉ trên khối $j$. Chúng ta hãy biểu thị bằng $n_j(S)$ các giá trị bằng 0 nếu các hướng biểu thị trùng nhau và bằng 1 nếu ngược lại. Nếu số tiền

$$n_1(S) + n_2(S) + ... + n_{12}(S)$$

là số chẵn, chúng ta giả sử $n(S)=0$, nếu không thì $n(S)=1$; chúng ta có thể nói rằng $n(S)$ là “sự chẵn lẻ của tổng chuyển động quay của các cốc ở giữa”. Chứng minh rằng

1. Đại lượng $n$ là bất biến, nghĩa là nó giống nhau đối với mọi trạng thái của khối: $n(S)=n(S_0)=0$. (Gợi ý. Nó đủ để chứng tỏ rằng $n(S)$ không thay đổi theo bất kỳ vòng quay nào của một lần đúc).

2. Theo định luật, trạng thái của khối không thể quay bằng một khối ở giữa (tính chất I, trang 19). (Gợi ý. Ở trạng thái này $n(S)=1$).

Chúng ta hãy nhớ rằng vị trí của khối trung tâm trong không gian không thay đổi khi quay; để xác định, giả sử khối trung tâm phía dưới có màu xanh lá cây, khối phía trên có màu xanh lam; Chúng ta sẽ xem xét hai màu này được nhìn thấy. Hãy lấy khối góc thứ $i$ của khối lập phương của chúng ta, ở trạng thái $S$. Chính xác một ô của khối góc được tô sáng (tại sao?). Nếu ô này nằm ngang, chúng ta đặt (theo định nghĩa) $N_i(S)=0$; nếu ô này nằm ngang khi xoay khối lập phương $120^\circ$ (theo chiều kim đồng hồ) xung quanh đường chéo của khối lớn, hãy đặt $N_i(S)=1$; nếu đạt được chiều ngang bằng cách xoay $240^\circ$ thì $N_i(S)=-1$. Nếu số tiền

$$N_1(S) + N_2(S) + ... + N_8(S)$$

khi chia cho 3 thì số dư là 0, 1, 2 ta đặt các giá trị $N(S)$ lần lượt bằng 0,1, -1. Chúng ta có thể nói rằng đại lượng $N$ là “hướng chuyển động toàn phần của các cốc ở góc”. Chứng minh rằng

3. Đại lượng $N$ là bất biến, nghĩa là nó giống nhau đối với mọi trạng thái của khối: $N(S)=N(S_0)=0$.

4. Theo định luật, trạng thái của khối không thể quay bằng một khối ở giữa (thuộc tính III, trang 19).

Giả sử ở trạng thái $S$ các khối ở giữa có số 1, 2, ..., 12 lần lượt được chiếm các số $j_1, j_2, ..., j_{12}$ và các khối góc 1, 2, ..., 8 lần lượt được chiếm các vị trí $i_1, i_2, ..., i_8$. Các bộ $I(S)=(i_1, i_2, ..., i_8)$ và $J(S)=(j_1, j_2, ..., j_{12})$ chỉ đơn giản là các số cốc được viết theo một thứ tự khác; Các nhà toán học còn gọi tập hợp là hoán vị. Một hoán vị được gọi ngay cả khi nó có số chẵn, nghĩa là một số chẵn các cặp chữ số không theo thứ tự tăng dần và lẻ. Chúng ta có thể nói rằng $\epsilon$ là “sự sắp xếp đồng đều của tất cả các cốc”. Chứng minh rằng

5. Đại lượng $\epsilon$ là bất biến, trong khi $\epsilon(S)=\epsilon(S_0)=0$ đối với bất kỳ trạng thái pháp luật nào $S$. (Gợi ý. Hãy chứng minh rằng với bất kỳ chuyển động quay nào của bánh xe thì số chẵn lẻ $I$ và số chẵn lẻ $J$ thay đổi).

6. Chính xác một khối góc không thể hoán đổi cho nhau (tính chất II, trang 19).

7*. Trạng thái $S$ của hình lập phương là theo định luật tosyada và chỉ tosyada, khi

$$n(S)=N(S)=\epsilon(S)=0$$.

8*. Tất cả các trạng thái (bao gồm cả những trạng thái thu được bằng cách tháo rời và lắp ráp khối lập phương đều được phát triển thành 12 lớp; trong trường hợp này, hai trạng thái $S, S'$ được chuyển đổi thành nhau bằng cách lần lượt thắp sáng tosyada và chỉ tosyada khi $n(S)=n(S')$, $N(S)=N(S')$, $\epsilon(S)=\epsilon(S')$.

*) Tác giả Phụ lục - V. Dubrovsky.
**) Tức là ở trạng thái thu được từ các lượt đúc chính xác (không sơn lại các ô hoặc tháo rời khối lập phương).
