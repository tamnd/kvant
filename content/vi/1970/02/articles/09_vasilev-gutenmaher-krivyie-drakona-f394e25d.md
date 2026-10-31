---
id: 1970-2-vasilev-gutenmaher-krivyie-drakona-f394e25d
issue: kvant_1970_2
year: 1970
number: "2"
title: Đường cong rồng
authors:
  - Васильев Н. Б.
  - Гутенмахер В. Л.
rubric: osnovnye-stati
page_first: 38
page_last: 48
page_labels: 36-46
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 89175e0a9f6f5044ef4214161ac11fe75bf236feae9304a3f5028e5cc999ec41
prompt_sha256: draft-1
translated_from: content/ru/1970/02/articles/09_vasilev-gutenmaher-krivyie-drakona-f394e25d.md
source_content_sha256: 4f832c953c85640d6bdc25922f42c0451a91abc1a49970209bd690b8dd1d4dae
translation_model: draft
translation_run: vi-draft-gaps-2026-10-31
translation_quality: draft
---

⟦folio 36⟧

---
running_head:
folio:
---

ĐƯỜNG CONG
RỒNG

Từ bài viết này
bạn sẽ tìm hiểu về những điều thú vị
gia đình cá nhân,
một trong số đó
vẽ ở đây
và một số người khác -
ở trang 42 và 43.

N. B. VASILIEV, V. L. GUTENMACHER

⟦folio 37⟧

ĐƯỜNG CONG VÀ GÃY LÀ GÌ
RỒNG

Lấy một dải giấy dài, gấp làm đôi và làm đôi lại. Đặt cạnh dải đã gấp lên bàn và mở ra sao cho góc ở mỗi nếp gấp là 90° (hình 1). Nếu nhìn từ trên xuống, bạn có thể thấy đường đứt nét hiển thị ở hình 2, a hoặc 6.

Khi dải được gấp làm đôi ba lần, sẽ thu được các đường gãy khác nhau đáng kể (hình 2, in hoặc 2) tùy thuộc vào cách gấp dải. Nếu bạn gấp dải giấy bốn lần trở lên, sau đó mở các đầu nhọn của nó thành các góc vuông, bạn có thể có được nhiều đường gãy khác nhau. hình 3 hiển thị một trong những đường gãy do năm nếp gấp làm đôi.

Trong thực tế, bạn sẽ không thể gấp một dải giấy quá bảy lần - xét cho cùng, ngay cả với lần gấp thứ tám, bạn sẽ chỉ có $2^8 = 256$ lớp! Tuy nhiên, chúng ta sẽ sớm học cách vẽ những đường đứt đoạn khá dài như vậy mà không cần dải. Ở trang 38 (bên dưới) một trong những đường gãy đã được vẽ, sẽ có được nếu dải được gấp 12 lần. Nó bao gồm các liên kết $2^{12} = 4096$.

Dễ dàng nhận thấy rằng nếu bạn gấp một dải quá ba lần thì sau khi một số dải được trải ra, các góc của nó chắc chắn sẽ “chạm” vào nhau (hình 2, trong và hình 3). Do có nhiều lần chạm như vậy, lưới sẽ thu được ở những nơi dọc theo chiều dài bị đứt. Để tìm hiểu đường nét đứt diễn ra như thế nào, bạn có thể làm tròn các góc của nó (như thể hiện trong hình 3 đường màu). Nếu bạn làm điều này cho đường gãy hiển thị bên dưới hình 3, bạn sẽ có được đường vẽ phức tạp ở trang trước. hình này đã gợi ý cái tên “đường cong rồng” cho nhà vật lý người Mỹ John Heightway. Bất cứ ai từng nhìn thấy rồng đều có thể tin rằng nó trông giống hệt như thế này.

⟦folio 38⟧

Loại đường gãy này (“Dòng rồng chính”) có được nếu bạn bắt đầu từ một đoạn và lần lượt xoay đường đứt đoạn trước đó theo cùng một hướng. (Điều này tương ứng với phương pháp gấp đôi, được hiển thị trên hình 2 a, c; ở đây dải được gấp "từ phải lên trái" mỗi lần.) Trên hình 3, phần đầu của đường gãy này được hiển thị (32 liên kết), trên hình này có 4096 liên kết. Nếu đường gãy được tiếp tục theo cách tương tự xa hơn, thì nó sẽ từ từ đi vòng quanh điểm gốc của nó, thực hiện một lượt đầy đủ cho mỗi 8 lượt “nhân đôi”. Các chấm đỏ nằm trên một đường xoắn ốc logarit (đối với những ai quen với hệ tọa độ cực, chúng ta có thể viết phương trình của nó: $\varphi = \log_a r$, trong đó $r$, $\varphi$ là tọa độ cực; $a = a^{2:\pi}$).

⟦folio 39⟧

CÁCH VẼ DÀI
RỒNG HỎI?

Chúng ta sẽ gọi bất kỳ đường đứt nét nào thu được từ một mảnh giấy được gấp làm đôi $n$ lần, mở các nếp gấp lên đến $90^\circ$, đường gãy của rồng $n$. Hãy cùng tìm hiểu cách sắp xếp những con rồng gãy và cách vẽ chúng sao cho đủ lớn $n$.

Cách đầu tiên

Vết thương rồng gãy $n$ bao gồm các liên kết $2^n$ và theo đó có $2^n-1$ đỉnh (không tính các đầu). Do đó, nó cũng có một đỉnh ở giữa trên $(n>0)$ vì số đỉnh là số lẻ. Trên hình 2 và 3, đỉnh giữa của mỗi đường gãy được bù bằng một vòng tròn màu xanh lá cây. Có thể lưu ý rằng mỗi đường đứt nét này bao gồm hai mảnh giống hệt nhau, thu được từ nhau bằng cách quay $90^\circ$. Hóa ra đây là một mô hình chung.

Định lý 1. Nếu tiếp tục có vết thương rồng nào bị gãy $n$ với điểm kết thúc $O$ cũng có thể là một đa tuyến thu được từ điều này bằng cách xoay bởi $90^\circ$ xung quanh điểm $O$, sau đó bạn nhận được một vết thương rồng bị gãy $n+1$, và ngược lại, tình yêu phá vỡ vết thương rồng $n+1$ đến từ một vết thương vỡ nào đó $n$ cách này.

Trên thực tế, giả sử chúng ta muốn gấp dải $n+1$ làm đôi. Đầu tiên, gấp nó làm đôi một lần. Sau đó, hai nửa của nó trùng nhau và khi gấp lại thêm, sẽ uốn cong một nửa hoàn hảo (hình 4). Bây giờ, hãy mở rộng trên $90^\circ$ phần $n$ cuối cùng của dải. Chúng ta nhận được hai vết thương do rồng gãy tương ứng $n$; Tất cả những gì còn lại là tách chúng ra $90^\circ$ - và chúng ta sẽ có một vết thương rồng gãy $n+1$ (hình 5). Hãy suy nghĩ về cách rút ra cả hai phát biểu của Định lý 1 từ những thông điệp này.

Sử dụng Định lý 1, người ta dễ dàng vẽ được những đường rồng đa giác dài.

Vì hình vẽ rồng tuân theo các đường kẻ của ô vuông nên vẽ trên giấy ca rô sẽ rất tiện lợi.

Hãy lấy bất kỳ dòng rồng ngắn nào (ví dụ: chỉ một đoạn). Hãy đồng ý rằng một trong những điểm cực đoan của nó là điểm bắt đầu và điểm còn lại là điểm kết thúc. Hãy tiếp tục với cùng một đường đứt nét, xoay tương ứng với điểm cuối của nó $90^\circ$ theo chiều kim đồng hồ (hoặc ngược chiều kim đồng hồ). Chúng ta tiếp tục tạo đường đứt nét mới từ cuối theo cách tương tự; Chúng tôi làm điều này nhiều lần nếu chúng tôi muốn và nhiều nhất có thể. Điều này có thể được thực hiện tự động và nhanh chóng nếu bạn có sẵn giấy can hoặc thậm chí tốt hơn là giấy ca rô hơi trong suốt. (Hãy nghĩ xem!)

Rõ ràng, theo cách tương tự, chúng ta có thể vẽ ngay cả hai bên và cổ của con rồng: chúng ta chỉ cần làm tròn phần nấm ở giữa mỗi lần.

Đặc tính đáng chú ý của tất cả các đường cong rồng là chúng không tự cắt nhau, hoặc tương tự, các đường cong rồng không bao giờ đi dọc theo cùng một đoạn hai lần. Như vậy, mặc dù kẻ phá rồng có thể đi qua cùng một điểm (đỉnh của lưới) hai lần, nhưng nó không chạm vào cùng một điểm quá hai lần.

⟦folio 40⟧

Từ Định lý 1, không rõ ràng ngay lập tức làm thế nào để chứng minh rằng các đường rồng không đi qua hai lần dọc theo cùng một đoạn - ngược lại, bạn vẽ các đường đứt đoạn hoặc đường cong càng dài và phức tạp thì càng đáng ngạc nhiên là “các phần nhô ra” và “thung lũng” của chúng khớp với nhau đến mức nào (xem đường cong rồng “đầu máy” ở trang 43).

Tuy nhiên, không khó để chứng minh điều này *), sử dụng một định lý khác về việc “nhân đôi” các đa giác rồng, nhân tiện, định lý này đưa ra một cách để vẽ các đa giác dài.

Cách thứ hai

Trên hình 6 các đỉnh của đường rồng đen được nối với nhau bằng các đoạn màu đỏ. Chúng ta thấy những đoạn màu đỏ lại tạo nên những đường đứt đoạn của con rồng. Hóa ra đây cũng là một mô hình chung.

Để xây dựng nó một cách chính xác, thì mỗi đoạn màu đỏ là cạnh huyền của một tam giác vuông cân, hai chân của tam giác này là các liên kết của đường gãy ban đầu (tại hình các hình tam giác được tô bóng một chút) và mỗi hai hình tam giác liền kề như vậy đều thu được từ nhau bằng cách quay 90° quanh đỉnh chung của chúng; nói cách khác, nếu bạn đi dọc theo đường đứt nét màu đỏ của con rồng thì những

*) Xem bài toán 9 ở cuối bài viết.

các hình tam giác sẽ xuất hiện xen kẽ ở bên phải và bên trái.

Định lý 2. Nếu trên mỗi liên kết của đường đa giác n của con rồng, như một zinotenuse, chúng ta dựng một tam giác cân vuông, và theo cách mà đối với hai liên kết liền kề, các tam giác này là một trong hai bằng cách quay 90° so với đỉnh chung, thì các viên đá của các hình tam giác được tạo thành sẽ tạo thành đa tuyến n+1 của con rồng. Và ngược lại, mỗi đường đứt nét n+1 có thể thu được theo cách này từ một đường đứt nét n nào đó.

Trên thực tế, hãy làm theo cách cuối cùng và gấp dải vải làm đôi. Để thuận tiện, chúng ta sẽ tham khảo điều kiện hình 7. Chúng ta muốn gấp dải vải làm đôi n+1 lần. Đầu tiên chúng ta hãy gấp nó n lần và vẽ nó theo hình nghiêng (đường màu đỏ ở hình 7). Sau đó gấp đôi lại và xoay nếp gấp cuối cùng này 90° (đường màu đen trên cùng hình*). Tờ giấy đi từ nấm A đến nấm B và quay lại không dọc theo cạnh huyền mà dọc theo hai chân của tam giác vuông cân ABC. Hãy mở ra tất cả các nếp gấp khác

Hình 6

đoạn này là cạnh huyền của một tam giác vuông đều, hai chân của tam giác đó là các đường nối của đường gãy ban đầu (tại hình các tam giác được tô bóng một chút) và cứ hai tam giác liền kề như vậy thu được từ nhau bằng cách xoay 90° quanh điểm đỉnh; nói cách khác, nếu bạn đi dọc theo đường đứt nét màu đỏ của con rồng thì những

lên đến 90° (ở hình 8, nó được hiển thị cách một nếp gấp riêng biệt sẽ mở ra). Khi đó các viên đá của hình chữ nhật tạo thành đường gãy của con rồng n+1, và cạnh huyền tạo thành n.

Sử dụng các thông báo này, thật dễ dàng để chứng minh cả hai phát biểu của Định lý 2. Bạn có thể thử đưa ra một chứng minh khác: suy ra Định lý 2 từ Định lý 1.

*) Trên hình của chúng tôi, đường màu đen dài hơn $\sqrt{2}$ lần so với đường màu đỏ, nhưng điều này không quan trọng vì chúng tôi quan tâm đến hình dạng của đường đứt nét chứ không phải kích thước của nó.

⟦folio 41⟧

Sử dụng Định lý 2, từ đường gãy thứ hạng $n$ của mỗi con rồng, người ta có thể thu được hai đường đứt gãy thứ hạng $n+1$: tất cả phụ thuộc vào cạnh nào của liên kết đầu tiên để hoàn thành tam giác.

Xin lưu ý rằng khi chúng ta chuyển từ một dòng đứt gãy thứ hạng $n$ sang một dòng đứt gãy thứ hạng $n+1$ theo Định lý 1, đường gãy sẽ dài gấp đôi và độ dài của mỗi mắt xích không thay đổi; nếu chúng ta sử dụng Định lý 2 để “nhân đôi”, thì độ dài của đường đứt nét tăng $\sqrt{2}$ lần và độ dài của liên kết giảm $\sqrt{2}$ lần.

Bây giờ hãy thực hành vẽ các đường rồng đa giác bằng Định lý 2.

TỪ

Tính chất được thảo luận trong Định lý 2 có thể được giải thích khá đơn giản nếu chúng ta nhìn vào các đường rồng (hoặc, nếu bạn thích, nhìn vào các cách gấp một mảnh giấy) từ một quan điểm xanh hơn một chút.

Để rùa bò dọc theo đường gãy của rồng (hình 9). Mỗi lần lên đến đỉnh, cô ấy phải rẽ $90^\circ$ sang trái hoặc phải. Theo quan điểm của con rùa, đường đi của nó sẽ được xác định bởi một chuỗi các ngã rẽ. Ví dụ: đối với một đường đứt nét ở hình 2, $a$ (bắt đầu từ chấm đỏ), trình tự này sẽ như sau: trái, trái, phải.

Chúng ta sẽ biểu thị rẽ phải bằng chữ cái $R$, rẽ trái bằng chữ cái $L^*$). Khi đó toàn bộ dòng đứt quãng sẽ được viết bằng chữ “từ” sau:

LLR

(“một từ” trong nhiều ngành toán học và logic đơn giản có nghĩa là bất kỳ chuỗi chữ cái nào). Theo cách tương tự, bạn có thể viết bất kỳ dòng rồng nào dưới dạng một từ của các chữ cái $L$ và $R$.

Để lấy đường gãy $a$ từ đường gãy $\delta$ (hình 2), bạn cần gấp mảnh giấy thêm một lần nữa “sang bên trái” (xem hình 2, $\delta$ và 10). Trong trường hợp này, giữa mỗi hai đỉnh của đường đứt nét $a$ sẽ có thêm một ngã rẽ nữa, và tại hình 10 có thể thấy rõ những ngã rẽ mới này sẽ đi qua

*) Chúng tôi đã chọn các chữ cái đầu tiên của các từ tiếng Anh phải (phải) và trái (trái), vì các chữ cái P và L trong tiếng Nga quá giống nhau (nhân tiện, Rechts và các liên kết trong tiếng Đức bắt đầu bằng cùng một chữ cái).

⟦folio 42⟧

Đường cong này có được nếu bắt đầu từ đoạn này, quá trình "nhân đôi" được lặp lại 12 lần và lần lượt theo chiều kim đồng hồ và ngược chiều kim đồng hồ. Để thể hiện rõ hơn đường cong này diễn ra như thế nào, chúng ta xoay mỗi lần không phải 90° mà là 95° (đường màu đen); nếu bạn giảm các góc xuống 90°, bạn sẽ có được đường cong rồng, được mô tả trên cùng một đường màu hình; nó lấp đầy một tam giác vuông đều bằng một mẫu đồng nhất.

⟦folio 43⟧

Đường cong rồng hạng 12 này có tên gọi đặc biệt là “Cha, Mẹ và Con”. Tìm phần giữa của nó. Bạn có thể tưởng tượng rằng đường cong phát triển từ điểm này thành hai phần hoàn toàn giống hệt nhau, tạo thành từ nhau bằng cách quay 90° không? Để tin được điều này, chúng ta sẽ phải vẽ một cách trung thực đường cong bằng bút chì màu từ đầu đến giữa.

Ở đây, một trong hai nửa, đường cong (“nó được gọi là “đầu máy”), được vẽ trên nền màu để cho thấy hai đường cong này “di chuyển” lẫn nhau như thế nào. Một nửa, sau khi xoay 90° quanh điểm giữa, sẽ trùng với nửa còn lại

⟦folio 44⟧

nhượng bộ ; do đó chúng tôi nhận được
$$L L R \rightarrow L L R L R R,$$

tức là các từ ghi lại dòng đứt gãy 6. Uốn cong sang trái một lần nữa, chúng ta sẽ có một dòng đứt gãy đặc trưng bởi từ đó

$$L L R L L R R \rightarrow L L R L R L R R,$$

Vẽ đường gãy này. Đây là đường gãy chính của rồng bậc 4. Nếu bạn muốn, hãy vặn các góc của nó, như Heiwei gợi ý.

Nếu bạn tiếp tục thao tác tương tự đối với từ cuối cùng nhận được một lần nữa (bắt đầu lại chuỗi các chữ cái xen kẽ với $L$), bạn sẽ nhận được các từ gồm 31 chữ cái - một bản ghi của Dòng Rồng Chính ở hạng 5, hiển thị ở hình 3.

Tất nhiên, chuỗi các chữ cái giao nhau không thể bắt đầu bằng $L$ mà bằng $R$ - điều này sẽ dẫn đến các dòng bị đứt khác.

Dễ dàng nhận thấy rằng phương pháp xây dựng từ cho dòng thứ hạng đứt quãng $n+1$ từ một từ cho dòng thứ hạng đứt quãng $n$ hoàn toàn tương ứng với phương pháp nhân đôi hình học đã được thảo luận trong Định lý 2 (các chữ cái mới tương ứng với đủ động từ). Nói chung, toàn bộ “lý thuyết” về các đường rồng đứt đoạn có thể được xây dựng không phải bằng hình học - sử dụng phép quay, thu được hình tam giác, v.v., mà là “đại số” - sử dụng các phép tính trên các từ từ hai

Hình 10

chữ cái $L$ và $R$, “kỷ lục” về những con rồng bị gãy *).

Người đọc sẽ có thể đi theo một phần con đường này và làm quen với một số mẫu thú vị mà các từ có - bản ghi các đường cong của rồng, giải quyết bài toán sau đây.

NHIỆM VỤ

1. Bạn cần lấy một dải trong bao lâu để sau khi gấp đôi 30 lần, bạn có khoảng cách giữa các nếp gấp liền kề là 1 cm? Khoảng cách từ Trái đất đến Mặt trăng lớn hơn hay nhỏ hơn?

2. Đường của con rồng sẽ thay đổi như thế nào nếu dải giấy được đặt trên bàn với cạnh bên kia? Những từ viết dòng gãy sẽ thay đổi như thế nào?

3. a) Có bao nhiêu con rồng gãy hạng 4 khác nhau (không giống nhau)? Hãy vẽ tất cả chúng. Viết các từ tương ứng từ các chữ cái $L$ và $R$.

6) Có bao nhiêu dòng xếp hạng khác nhau $n$?

4. Giả sử con rùa bò dọc theo đường gãy của con rồng và tìm thấy các từ trong các chữ cái $L$ và $R$. Cô ấy sẽ đọc từ gì nếu bò dọc theo đường đứt nét này theo hướng ngược lại?

5. Đặt $s$ là một số từ trong các chữ cái $L$ và $R$. Chúng ta hãy biểu thị bằng $s$ các từ sẽ thu được từ $s$ nếu chúng ta sắp xếp lại các chữ cái trong đó theo thứ tự ngược lại rồi đặt $L$ trên $R$ và $R$ trên $L$. (Ví dụ: nếu $s=LLR$ thì $s=LRR$).

Đặt $s$ và $t$ là một số từ trong các chữ cái $L$ và $R$. Chúng ta sẽ biểu thị bằng $st$ các từ thu được nếu các từ $s$ và $t$ được viết cạnh nhau. (Ví dụ: nếu $s=LLR$, $t=RL$ thì $st=LLRRL$).

Chứng minh rằng:

a) Đối với mọi từ $s$ và $t$

$$\overline{st} = \overline{t} \overline{s}.$$

6) Nếu $s_{n+1}$ là các từ tương ứng với dòng rồng cấp bậc $n+1$ thì

$$s_{n+1} = s_n x \overline{s}_n,$$

trong đó $s_n$ là một số từ tương ứng với đa dòng xếp hạng $n$ của rồng và $x$ là những từ tương ứng với một chữ cái.

*) Chính phương pháp trình bày này đã được các nhà toán học người Canada Knuth và Davis lựa chọn, từ bản thảo “Biểu diễn số và đường cong rồng” (Ch. Davis, D. E. Knuth), các tác giả của bài báo lần đầu tiên làm quen với những con rồng cong. Một loạt các đường cong rồng có chiều dài hình cũng được nghiên cứu từ bản thảo này.

⟦folio 45⟧

c) Nếu $s_n$ là từ tương ứng với dòng rồng thì $s_n$ chỉ khác $s_n$ một chữ ở giữa.

d) Từ viết dòng đứt gãy của rồng về thứ hạng $n$ có thể được xây dựng một cách độc đáo bằng cách chỉ định tùy ý các chữ cái $n$ xuất hiện trong từ này ở các vị trí có số $2^k$, trong đó $k=0,1,2,...,n-1$ (tức là ở vị trí thứ nhất, thứ hai, thứ tư, thứ tám,..., $2n^{-1}-m$); sau đó, để tìm chữ cái nào ở vị trí thứ $m$, bạn cần biểu thị $m$ dưới dạng $m=2^k(2l+1)$, trong đó $k$ và $l$ là số nguyên; nếu $l$ là số chẵn thì vị trí thứ $m$ có cùng chữ cái với vị trí thứ $2^k$, nếu $l$ là số lẻ thì có chữ cái ngược lại.

e) Hai từ $s_n'$ và $s_n''$ xác định những con rồng gãy có hình dạng giống nhau (tương tự) khi và chỉ khi, sau khi gạch bỏ chữ cái ở giữa, các từ này trùng khớp hoặc một từ được lấy từ từ kia bằng cách thay thế $L$ bằng $R$ và $R$ bằng $L$. (Ví dụ: các từ LLRLLRR, LLRRLRR, RRLRRLL xác định các đường đứt nét giống nhau.)

6. Hãy để chúng tôi có một đường gãy của một con rồng có cấp bậc $n$. Từ đó, bạn có thể thu được hai đường rồng gãy có hạng $n+1$, sử dụng Định lý 1 (lấy đầu này hoặc đầu kia của đường gãy làm điểm $O$) hoặc Định lý 2 (kéo dài hình tam giác theo hướng này hoặc hướng khác). Cả hai trường hợp sẽ tạo ra hai con rồng bị hỏng giống nhau có cấp bậc $n+1$ hay nói chung là những con khác nhau? Làm cách nào để lấy được từ của họ từ một từ thuộc một dòng xếp hạng nhất định $n$?

7. Cho hai điểm $A$ và $B$ trên mặt phẳng. Hãy vẽ một hình vuông có tâm ở giữa đoạn $AB$, một trong các cạnh của nó bằng $2AB$ và song song với đoạn $AB$. Chứng minh rằng mọi đường rồng có điểm cuối tại $A$ và $B$ đều nằm trong hình vuông này. Chứng minh rằng với bất kỳ điểm $M$ nào bên trong hình vuông này và bất kỳ số dương $e$ nào, người ta có thể tìm thấy một đường rồng có các đầu $A$ và $B$ đi từ điểm $M$ ở khoảng cách nhỏ hơn $e$ (theo ngôn ngữ toán học, “sự kết hợp của tất cả các đường rồng có điểm cuối tại các điểm $A$ và $B$"). Các liên kết $2^n$ đầu tiên của nó tạo thành một dòng xếp hạng đứt quãng $n$.

Chứng minh rằng:

a) Điểm cuối của đường đứt nét thứ hạng $n$ đó sẽ là điểm

$$\left( \frac{n}{2} \cos \frac{\pi n}{4}, \frac{n}{2} \sin \frac{\pi n}{4} \right)$$

(chấm đỏ trên hình trên trang 38).

⟦folio 46⟧

---
running_head:
folio:
---

6) Từ ghi dòng đứt quãng này có thể viết nhanh như thế này. Đầu tiên, chúng ta viết các chữ cái $L$ và $R$ thông qua các số, chừa khoảng trống giữa chúng cho các chữ cái còn thiếu:

$$L_R_L_R_L_R_L_R_L_R...$$

và sau đó chúng tôi tiến hành như sau. Bằng ngón tay trái, chúng ta chỉ vào chữ cái đầu tiên và bằng tay phải, chúng ta viết nó vào khoảng trống đầu tiên, sau đó bằng tay trái, chúng ta chỉ vào chữ cái thứ hai, và bằng tay phải, chúng ta chèn nó vào khoảng trống thứ hai, bằng tay trái của chúng ta vào khoảng trống thứ ba... và cứ thế tuần tự qua tất cả các chữ cái (không bỏ sót chữ cái mới) và bằng tay phải, chúng ta chèn từng chữ cái được chỉ định vào khoảng trống đầu tiên.

$$LLRLLRLLLRRLRLLLRL$$

c) Nếu, như trong bài toán 10, chúng ta giải phóng bốn đường đứt nét chính của thứ hạng ∞ từ một điểm, thì dọc theo mỗi đoạn của lưới sẽ có chính xác một liên kết của một trong những đường gãy này (hình 11).

(Đây là một định lý khó; nó được chứng minh lần đầu tiên bởi D. E. Knuth.)

Hình 11.

VĂN HỌC

M. Gardner, Trò chơi toán học, Scientific American 216, 1967, March (124-125), Appel (118-120), July (115).
