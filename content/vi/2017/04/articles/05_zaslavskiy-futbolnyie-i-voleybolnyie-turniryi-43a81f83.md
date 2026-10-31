---
id: 2017-4-zaslavskiy-futbolnyie-i-voleybolnyie-turniryi-43a81f83
issue: kvant_2017_4
year: 2017
number: "4"
title: Giải đấu bóng đá và bóng chuyền
authors:
  - Заславский А. А.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 41
page_last: 41
tag: 7CV6
lang: vi
source: kvant_digital
extraction: native
content_sha256: d4d65bf05e60d191f84a9d8a5f81b5fca04789c56bbcace324414ca6d40cac44
prompt_sha256: draft-1
translated_from: content/ru/2017/04/articles/05_zaslavskiy-futbolnyie-i-voleybolnyie-turniryi-43a81f83.md
source_content_sha256: 592f12c1c7c45df88d81393a335d75b376d0698bae43395bf4a2e2b98c253cb3
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio none⟧

VÒNG TRÒN TOÁN HỌC

Giải đấu bóng đá và bóng chuyền

A. ZASLAVSKY

Sức mạnh của tư duy đang cạn kiệt, Nói về thời trang mới, Về bóng đá, về thời tiết Và về những chuyện vặt vãnh khác - Đó là tất cả những gì còn lại... A. Velikiy

CÓ NHIỀU TOÁN HỌC bài toán liên quan đến các cuộc thi thể thao. Thông thường họ nói về các giải đấu một vòng, trong đó mỗi người trong số n người tham gia đấu với nhau một lần. Trong trường hợp này, theo quy định, người ta giả định rằng điểm được trao theo hệ thống cờ vua, tức là nếu thắng, người tham gia nhận được một điểm, nếu hòa - một điểm, nếu thua - 0 điểm (trong các môn thể thao đồng đội, một chiến thắng từng được cho hai điểm và một cho một trận hòa, theo quan điểm toán học, về cơ bản không khác biệt với hệ thống cờ vua). «Kvant» đã nói về các giải đấu cờ vua nhiều lần$^{1}$, vì vậy ở đây chúng tôi sẽ chỉ lưu ý hai đặc điểm sau của các giải đấu đó. 1. Tổng số điểm mà tất cả người tham gia ghi được là $n ( n - 1 ) 2$. Thật vậy, trong mỗi trận đấu, những người tham gia, với bất kỳ kết quả nào, ghi được tổng cộng một điểm và tổng số trận trong giải đấu là $n ( n - 1 ) 2. 2.$ Nếu một người tham gia cuối cùng ghi được s điểm, thì hiệu số giữa số trận thắng và số trận thua của anh ta là 2 giây – n + 1. Thật vậy, nếu một người tham gia thắng w trận và thua l trận, thì anh ta hòa

1 Ví dụ, hãy xem bài viết của A. Zaslavsky “Về các giải đấu hợp lý và phi logic” («Kvant» Số 5, 1997) hoặc bài báo của A. Zaslavsky và B. Frenkin “Toán học của các giải đấu” («Kvant» Số 1, 2, 2007).

chơi n – 1 – w – l lần, tức là ghi được $s = w + + ( n - 1 - w - l ) 2 = ( n - 1 ) 2 + ( w - l ) 2$ điểm, tương đương với tính chất 2. Từ tính chất 1 và 2, có thể dễ dàng rút ra các phát biểu được xây dựng trong các bài tập sau.

⟦column⟧

Bài tập

1. Chứng minh rằng nếu tất cả những người tham gia giải đấu đều ghi được số điểm bằng nhau thì số trận thắng của mỗi người bằng số trận thua. 2. Chứng minh rằng nếu không phải tất cả những người tham gia giải đấu đều ghi điểm bằng nhau thì người thắng giải có số trận thắng nhiều hơn số trận thua và người đứng cuối giải có số trận thắng ít hơn số trận thua.

Vào cuối thế kỷ trước, các giải đấu bóng đá bắt đầu tính ba điểm cho một trận thắng và một điểm cho một trận hòa. Trong những năm gần đây, bóng chuyền đã đưa ra một hệ thống trong đó, nếu trận đấu kết thúc với tỷ số 3:0 hoặc 3:1, đội thắng sẽ nhận được ba điểm và đội thua không có điểm; Nếu trận đấu kết thúc với tỷ số 3:2 thì các đội lần lượt nhận được hai và một điểm. Rõ ràng, với hệ thống bóng đá, cả tính chất 1 và 2 đều không còn giữ nguyên, còn với hệ thống bóng chuyền, chỉ có tính chất 1 được giữ nguyên. Vì vậy, chúng ta có thể mong đợi rằng nhận định ở bài tập 1 và 2 không còn đúng nữa. Không khó để đưa ra các phản ví dụ phù hợp nếu số lượng người tham gia giải đấu đủ lớn. Tuy nhiên, câu hỏi về số lượng người tham gia tối thiểu có thể trong các giải đấu như vậy không đơn giản và khá thú vị. Chúng ta sẽ xem xét loại bài toán này trong bài viết này. Bài toán 1. Trong một giải đấu bóng đá, tất cả n đội tham gia đều ghi được số điểm bằng nhau. Với n nhỏ nhất nào thì không phải tất cả các đội đều có số trận thắng bằng số trận thua? Đáp số. n = 8. Lời giải. Nếu không phải tất cả các đội đều có số trận thắng và thua bằng nhau thì sẽ có đội thắng nhiều hơn thua và có đội thua nhiều hơn thắng. Trước tiên, giả sử rằng số trận thắng và số trận thua của cả hai đội khác nhau 1, tức là Đội thứ nhất có x thắng và x – 1 thua, còn đội thứ hai có y thắng và y + 1 thua. Khi đó từ điều kiện đẳng thức
