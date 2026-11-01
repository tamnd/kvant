---
id: 1986-9-gik-novyie-uspehi-kompyutera-14dbeeae
issue: kvant_1986_9
year: 1986
number: "9"
title: 计算机新进展
authors:
  - Гик Е. Я.
rubric: shahmatnaya-stranichka
rubric_sub: Шахматы
page_first: 67
page_last: 67
tag: UJ2L
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 4d3c1516653052140ccb03d76bfae11676b5fca45f02e3ec220cbd4b818eb125
prompt_sha256: draft-1
translated_from: content/ru/1986/09/articles/02_gik-novyie-uspehi-kompyutera-14dbeeae.md
source_content_sha256: 71b89921dd174bbd267b1cb615393be915b4a4edeeef8b7148d52f25aebfc99d
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio none⟧

新计算机的进步

在1986年的«Kvant»第2期中，我详细讨论了车和主教对车的残局。理论上被认为是正确的，但实际上是强者占上风。我们写道，计算机应该结束分析。最近发表了对一台美国计算机的分析，其中特别发现了以下内容：

双方尽全力，白方获胜，59步就取得胜利！让我们展示游戏的最佳版本。 1. Cf5 Jh4 2. Cd3 Jf4 3. Ce4+Kpa7 4.Cc6 Jg4 5. Kpc7 Jg7+ 6. Cd7 Jg6 7. Ce6 Jg7+ 8. Kpc6 Jg1 9. Jla2+ Kpb8 10. Jlb2+ Kpa8 11. Kpb6 Jlc1 12. Cf5 Jlc3 13.Jlb1 Kpb8 14.Jlb4 Jla3 15.Cd7 Jla2 16.Jlb4 Jlb2+ 17.Cb5 Jlc2 18.Cc4 Jlb2+ 19.Kpc6 Jlf2 20.Jlb8+ Kpa7 21.Jh7+ Kpb8 22.Jlb7+ Kpa8 23.Jlb4 Jg2 24. Cd3 Jg3 25. Jld4 Jf3 26. Cc4 Jh3 27. Jld8+ Kpa7 28. Cd5 Jh2 29. Jld7+ Kpb8 30. Jlb7+ Kpa8 31. Jlb1 Jlc2+ 32. Kpb6+ Kpb8 33. Ce6 Jle2 34. Kpc6+ Kpa8 35. Jla1+ Kpb8 36. Cd5 Jh2 37. Jlb1+ Kpa7 38. Ce4 Jh6+ 39. Kpc5 Jlb6 40. Jlh1 Jla6 41. Jlh8 Jla5+ 42. Kpc6 Jlg5 43. Jh7+ Kpa6 44. Cd5 Kpa5。

白棋加上“菲洛多位置”，剩下的就知道了。 45. Kpc5 Jlg6 46. Jh2 Jlg4 47. Jlb2 Jhl4 48. Jlb7 Jhl6 49. Cf7 Jlf6 50. Cc4 Jlf5+ 51. Cd5 Jlf6 52. Jlb5+ Kpa6 53. Jlb2 Kpa7 54. Jlb7+ Kpa6 55. Jle7 Kpa5 56. Ce6 Kpa6 57. Cc8+ Kpa5 58. Jla7+ Jla6 59. Jl:a6×。

白棋的许多棋步都是独一无二的：通过不同的下法，白棋将错失胜利或推迟胜利。布莱克也巧妙地为自己辩护。只要稍有不准确，他们就会输得更快。毫无疑问，任何一个粗暴者都无法进行这样的分析。顺便说一句，它表明这种类型的结局，即理论问题，应该被视为较强的一方获胜（尽管也有例外）。

因此，国际象棋代码中的 50 步规则在这个残局中被更改是有充分理由的。最强的一方有 100 步棋来赌马蒂尔赢得车。

现在让我们回顾一下计算机解决国际象棋数学问题的能力之一。美国数学家 S. Kim 对著名的 8 皇后问题提出了一个有趣的概括。

在棋盘上排列最多数量的皇后 (8x8)，使每个皇后与其他 p 个皇后完全对齐。

条件p=0意味着皇后不会威胁到另一个朋友，也就是说，我们来到了伟大的高斯感兴趣的经典问题。 8x8 棋盘上所需的皇后数量等于所有的皇后数量。对于 p=1，最大值为十，对于 p=2 - 十四。年轻的基辅数学家 S. Bely 和 E. Rovensky 获得了该问题的完整解决方案。他们证明，当 p=3 时，最大值为 18，而当 p=4 时，最大值为 21（当 p>4 时，不存在必要的排列）。

这些结果首次发表在 1985 年的«Kvant» No. 8 上。最近，S. Bely 和 E. Rovensky 向我们发送了他们在服务科学出版物上发表的文章副本，其中考虑了将该问题推广到所有 n×n（n≤8）的方板。下表给出了不同n、p值的最大皇后数。收到了，意义重大

作者报告说，该解决方案算法基于“编写和返回”，对于熟悉编程搜索问题的学童来说很容易理解。

总之，我们注意到金的问题，就像棋盘上的许多其他数学问题一样，与图论直接相关，其解决方案对于数学和控制论的这一分支很重要。

竞争问题
两个职位的主角也是女王。

17. 白起和多多三步交配。

18. 白起和多多三步交配。

发送决定的截止日期是1986年11月20日，从信封上注明的日期开始：“国际象棋比赛«Kvant»，第17、18版。”
