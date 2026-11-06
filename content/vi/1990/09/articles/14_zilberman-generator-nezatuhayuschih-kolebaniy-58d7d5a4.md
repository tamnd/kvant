---
id: 1990-9-zilberman-generator-nezatuhayuschih-kolebaniy-58d7d5a4
issue: kvant_1990_9
year: 1990
number: "9"
title: Máy tạo dao động liên tục
authors:
  - Зильберман А. Р.
rubric: raznoe
page_first: 46
page_last: 49
page_labels: 44-47
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 6f4adc37ea062aebc5f1c29c97b03177189539a14bbfdf05cf08b16dd6b153c9
prompt_sha256: draft-1
translated_from: content/ru/1990/09/articles/14_zilberman-generator-nezatuhayuschih-kolebaniy-58d7d5a4.md
source_content_sha256: 5d6f44f22bffa584d9979ddf99811ab8eb37d2ae95bbb6b492d3a80596d8057c
translation_model: draft
translation_run: vi-draft-gaps-2026-11-05
translation_quality: draft
---

⟦folio 44⟧

Máy tạo dao động liên tục

Những máy phát điện như vậy được sử dụng trong nhiều thiết bị - radio, tivi, máy ghi âm, máy tính, đàn điện, v.v. - và chúng có nhiều bộ phận khác nhau (tần số thấp trong đàn điện) lên đến hàng trăm mét (ti vi) và thậm chí lên đến vài gigahertz (truyền hình vệ tinh, radar được cảnh sát giao thông sử dụng để xác định tốc độ tự động). Công suất mà máy phát điện có thể cung cấp cho người tiêu dùng nằm trong khoảng từ vài microwatt (máy phát điện trong đồng hồ bên ngoài) đến 10 watt (máy phát quét truyền hình) và trong một số trường hợp đặc biệt, công suất có thể cao đến mức không có ích gì khi viết ra - bạn vẫn sẽ không tin điều đó. Hình thức dao động có thể đơn giản như hình sin (bộ tạo dao động cục bộ vô tuyến) hoặc hình chữ nhật (bộ hẹn giờ máy tính), hoặc rất phức tạp - "bắt chước" âm thanh của nhạc cụ (bộ tổng hợp âm nhạc).

Tất nhiên, chúng tôi sẽ không xem xét tất cả các loại này mà sẽ giới hạn ở một ví dụ đơn giản - một máy phát hình sin công suất thấp có công suất vừa phải (hàng trăm kilohertz).

Như đã biết, trong mạch dao động đơn giản nhất, bao gồm một tụ điện lý tưởng và một cuộn dây lý tưởng, có thể xảy ra các dao động điều hòa không suy giảm. Có thể dễ dàng thu được phương trình quá trình bằng cách đánh đồng (có tính đến các dấu) hướng của tụ điện và cuộn dây - xét cho cùng, chúng được mắc song song (hình 1):

$$\frac{q}{C} = -LI'.$$

Vì vậy, dòng điện chạy qua cuộn dây sẽ làm thay đổi điện tích của tụ điện; những đại lượng này có liên quan bởi mối quan hệ

$$I = q'.$$

⟦folio 45⟧

---
running_head:
folio:
---

Bây giờ chúng ta có thể viết phương trình
$$q'' + \frac{q}{LC} = 0.$$

Lời giải của phương trình này được nhiều người biết đến - đó là một dao động điều hòa. Tần số của chúng được xác định bởi các tham số của mạch dao động: $\omega = 1/\sqrt{LC}$ và biên độ chỉ phụ thuộc vào năng lượng ban đầu được cung cấp cho mạch (và năng lượng này không đổi đối với mạch lý tưởng).

Điều gì sẽ thay đổi nếu các phần tử mạch không lý tưởng, như trường hợp thực tế trong thực tế (trong nhiều năm, tác giả chưa bao giờ thấy một cuộn dây lý tưởng nào, mặc dù ông rất quan tâm đến vấn đề này)? Để định nghĩa, toàn bộ sự không hoàn hảo của mạch điện là do cuộn dây, hay chính xác hơn là dây mà nó được quấn, có điện trở hoạt động (Omish) $r$ (hình 2). Tất nhiên, trên thực tế, tụ điện cũng mất năng lượng (mặc dù ở tần số không quá cao, bạn có thể tạo ra một tụ điện rất tốt mà không gặp nhiều khó khăn). Và người tiêu dùng sẽ hấp thụ năng lượng từ mạch điện, điều này cũng góp phần làm giảm dao động. Tuy nhiên, nói một cách dễ hiểu, chúng ta sẽ giả sử rằng $r$ là đại lượng tương đương gây ra toàn bộ tổn thất năng lượng trong mạch. Khi đó phương trình quá trình có dạng

$$LI' + rI + \frac{q}{C} = 0.$$

Rõ ràng rằng chính số hạng thứ hai đã ngăn cản chúng ta thu được phương trình dao động liên tục như mong muốn. Vì vậy, bài toán của chúng tôi là thời hạn bồi thường. Về mặt vật lý, điều này có nghĩa là năng lượng bổ sung phải được bơm vào mạch, tức là phải đưa vào một EMF khác. Làm thế nào điều này có thể được thực hiện mà không phá vỡ chuỗi? Cách dễ nhất để sử dụng từ trường là tạo ra một từ thông bổ sung tạo ra các vòng quay trong cuộn dây trong mạch. Để làm điều này, không xa cuộn dây này, bạn cần đặt một cuộn dây khác (hình 3) và cho một dòng điện chạy qua nó, cường độ của nó sẽ thay đổi theo định luật mong muốn, tức là sao cho dòng điện này tạo ra một từ trường mà khi dao động các cuộn dây của mạch sẽ tạo ra trong nó một từ thông như vậy, khi thay đổi sẽ tạo ra một suất điện động cảm ứng bù chính xác cho số hạng không mong muốn trong phương trình của quá trình. Toàn bộ cụm từ dài này, gợi nhớ đến “ngôi nhà mà Jack đã xây”, chỉ đơn giản là kể lại định luật Faraday mà bạn biết về hiện tượng cảm ứng điện từ.

Bây giờ chúng ta hãy xem dòng điện sẽ chạy qua cuộn dây bổ sung. Rõ ràng là nó cần một nguồn năng lượng (để bổ sung năng lượng bị mất trong mạch) và sự điều chỉnh của thiết bị, đảm bảo quy luật thay đổi dòng điện như mong muốn theo thời gian. Pin thông thường có thể được sử dụng làm nguồn và ống chân không hoặc bóng bán dẫn có thể được sử dụng làm thiết bị điều khiển.

Các bóng bán dẫn có nhiều loại khác nhau - loại chung (chúng được gọi là bioplair) và hiệu ứng trường, đó là

⟦folio 46⟧

---
running_head:
folio:
---

Chúng còn được chia thành các loại trường trường có cổng cách nhiệt (chúng thường được sử dụng trong các thiết bị kỹ thuật số) và có điểm nối $p - n$ điều khiển. Bất kỳ bóng bán dẫn hiệu ứng trường nào cũng chứa một "kênh" với hai lựa chọn - chúng được gọi theo tưởng tượng là nguồn và cống, và độ dẫn của nó được điều chỉnh bằng cách đặt điện áp điều khiển vào lựa chọn thứ ba - cổng (hình 4). Trong một bóng bán dẫn hiệu ứng trường có điểm nối $p - n$ điều khiển - và chúng ta sẽ nói về nó sâu hơn - cổng được tách khỏi kênh chỉ bằng một quá trình chuyển đổi như vậy, trong đó khu vực cổng được tạo thành từ loại độ dẫn ngược lại so với kênh. Ví dụ: nếu kênh có độ dẫn tạp chất loại $p$ thì cổng có loại $n$ và ngược lại.

Khi đặt điện áp chặn $U_3$ (hình 5) vào điểm nối, tiết diện của kênh dẫn giảm và khi xác định được điện áp - gọi là điện áp cắt - kênh bị chặn hoàn toàn và dòng điện dừng lại. Sự phụ thuộc của dòng điện kênh $I_к$ vào điện áp cổng $U_3$ được thể hiện ở hình 6. Sự phụ thuộc này gần giống như sự phụ thuộc của ống điện tử (triode). Điều quan trọng cần lưu ý là điện áp điều khiển là điện áp chặn, có nghĩa là dòng điện trong mạch điều khiển cực kỳ nhỏ (thường là vài nanoamp) và công suất điều khiển tương ứng thấp, điều này rất tốt. Đối với các giá trị nhỏ của điện áp điều khiển thì chỉ phụ thuộc vào điện áp.

$I_к = I_0 + SU_3$,

trong đó $S$ là một hằng số. Đối với một máy phát điện, độ lệch so với tuyến tính cũng rất đáng kể, nhưng còn nhiều điều hơn thế nữa.

hình 7 thể hiện sơ đồ của một bộ tạo dao động liên tục. Ở đây, điện áp điều khiển cho bộ chuyển đổi trường là điện áp trên tụ điện của mạch dao động:

$$U_3 = U_c = \frac{q}{C},$$

và dòng điện qua cuộn dây bổ sung là

$$I_к = I_0 + \frac{Sq}{C}.$$

Từ thông bổ sung tỷ lệ với dòng điện này và EMF bổ sung của mạch bằng EMF tùy ý của từ thông này, được lấy với dấu ngược lại:

$$\mathcal{E}_и = -\Phi' = -(MI_к)' = -\frac{MS}{C}q'.$$

Dấu trừ ở đây khá thông thường - cuộn dây có thể được kết nối với một bóng bán dẫn hiệu ứng trường ở đầu này hoặc đầu kia, và dấu của EMF bổ sung sẽ thay đổi thành ngược lại. Nói một cách dễ hiểu, EMF bổ sung phải đủ để bù đắp cho tổn thất năng lượng trong mạch. Chúng ta hãy viết lại phương trình quá trình:

$$LI' + rI + \frac{q}{C} - \frac{MS}{C}q' = 0.$$

⟦folio 47⟧

---
running_head:
folio:
---

Nếu chúng ta chọn các giá trị $M$ sao cho số hạng thứ tư bù cho số hạng thứ hai thì chúng ta thu được phương trình
$$LI' + \frac{q}{C} = 0,$$
tương ứng với dao động điều hòa không tắt dần.

Làm cách nào bạn có thể tác động đến các giá trị của $M$? Hóa ra là cô ấy sẽ được thông báo nếu các vòng quay lớn được quấn trong một cuộn dây bổ sung hoặc nếu cuộn dây này được đặt gần cuộn dây hơn. Phải nói rằng hệ số $M$ đủ để phát điện khá dễ dàng có được trong thực tế. Tốt hơn là nên chọn giá trị này với một số biên độ - điều này sẽ dẫn đến mạch không những không bị tổn hao mà ngay cả khi bơm năng lượng từ nguồn bên ngoài (với tổn thất “âm”). Khi bật máy phát điện, biên độ dao động ban đầu sẽ tăng lên, nhưng sau một thời gian nó sẽ ổn định lại - năng lượng đi vào mạch trong một khoảng thời gian sẽ bằng năng lượng bị mất trong cùng thời gian. Và thực sự, với sự gia tăng biên độ hướng tới tụ điện (hướng điều khiển của bóng bán dẫn hiệu ứng trường), bóng bán dẫn bắt đầu hoạt động kém hơn, vì với hướng âm lớn, dòng điện trong mạch kênh dừng lại và với hướng dương, quá trình chuyển đổi bắt đầu mở, điều này cũng dẫn đến tổn thất trong mạch. Dao động thu được sẽ không hoàn toàn là hình sin, nhưng nếu tổn hao trong mạch nhỏ thì độ méo sẽ không đáng kể.

Để sử dụng các dao động thu được - và đây chính xác là mục đích của máy phát điện - bạn cần kết nối trực tiếp với mạch điện hoặc cuộn một cuộn dây khác. Nhưng trong cả hai trường hợp, cần phải tính đến sự “rò rỉ” năng lượng từ mạch điện và bù đắp nó bằng những tổn thất khác.

A. Zalberman
