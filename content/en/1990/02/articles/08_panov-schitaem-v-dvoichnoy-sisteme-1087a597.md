---
id: 1990-2-panov-schitaem-v-dvoichnoy-sisteme-1087a597
issue: kvant_1990_2
year: 1990
number: "2"
title: We count in binary system
authors:
  - Панов А.
rubric: nam-pishut
rubric_sub: Нам пишут
page_first: 32
page_last: 32
page_labels: "30"
lang: en
source: kvant_digital
extraction: vision
content_sha256: 9eaa91e1ddf1fe89cbdd08bd4b2c8c69e1387675108205608417f91b56ceeb71
prompt_sha256: draft-1
translated_from: content/ru/1990/02/articles/08_panov-schitaem-v-dvoichnoy-sisteme-1087a597.md
source_content_sha256: 1c522c1e5d40dd01144d17f11ef69b670040de157a02f360674c9532bb4a74c0
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 30⟧

We count in the dual system
Let there be several objects in front of us and we need to count them. As usual, we do this by sequential recalculation: we take the first item and say “one”, take the next one – “two”, the next one – “tri” and so on until the last one. Since we are counting in the decimal system, we will also obtain the number of objects $N$ in the decimal system

$$N = a_k a_{k-1} \dots a_1 a_0.$$
Here each digit $a_i$ is 0, 1, 2, 3, 4, 5, 6, 7, 8 or 9 and $N = a_k \cdot 10^k + a_{k-1} \cdot 10^{k-1} + \dots + a_1 \cdot 10 + a_0$.

Now let’s imagine that when combining we use exclusively a dual system (in our time, the time of universal computerization, this is probably not so difficult to imagine).

In this system, the number $N$ is represented as

$$N = b_l b_{l-1} \dots b_1 b_0,$$

where each digit $b_i$ is either 0 or 1 and

$$N = b_l \cdot 2^l + b_{l-1} \cdot 2^{l-1} + \dots + b_1 \cdot 2 + b_0.$$

To count the number of objects in the dual system, we can use the same sequential recalculation: sequentially go through the objects one by one and sequentially call the numbers in the dual system.

However, in the dual system there is a fundamentally different method of counting, which I want to introduce you to. Let's turn to figure: structuring all items according to parameters. In this case, either nothing will remain, or one unpaired object will remain. Let's add it up like this: there will be either 0 items left or 1 item. At the second stage, we combine every two pairs into quadruples. In this case, again either 0 pairs or 1 pair will remain. Next, we will combine fours in pairs, then eights, and so on. After the last unification, we get a division of all objects into groups, and the number of elements in each group is a power of two. If the partition contains groups with $2^i$ elements, then we put $b_i = 1$, if there is no such group - $b_i = 0$. And then

$$N = b_l b_{l-1} \dots b_1 b_0$$

— records of the number of objects in the dual system.

Which of these two methods is preferable? I suggest you resolve this issue yourself.

A. Panov
