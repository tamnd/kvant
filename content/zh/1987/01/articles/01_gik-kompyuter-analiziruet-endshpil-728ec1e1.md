---
id: 1987-1-gik-kompyuter-analiziruet-endshpil-728ec1e1
issue: kvant_1987_1
year: 1987
number: "1"
title: 计算机分析残局
authors:
  - Гик Е. Я.
rubric: shahmatnaya-stranichka
rubric_sub: Шахматы
page_first: 67
page_last: 67
tag: 8X80
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 41d0a5eb1c6ca80b2ebe777ee1e6f966686c3635e21113a73cc06d966f792282
prompt_sha256: draft-1
translated_from: content/ru/1987/01/articles/01_gik-kompyuter-analiziruet-endshpil-728ec1e1.md
source_content_sha256: 94ecc1b049032eaea73fc9bd072494a3a99f4f5bf458e07224ee6d07b86b8b00
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 43⟧

电脑
分析
结束语

去年我们谈论了计算机在国际象棋结局研究方面的新成就。据报道，第二期中，计算机已经彻底分析了非常复杂的结局“国王和两个相反颜色的主教对抗国王和骑士”。直到最近，这还被认为是平局，但计算机证明，这是更强的一方获胜，并且在创纪录的位置上，当双方都以最好的方式发挥时，两位主教仅用了67步就对付了骑士。又一个服务器按照50步规则来打击！

让我们介绍 O. Komziy 编写的程序所指示的主要选项。 1. Ca4+ Kp1 2. Cb2 Kpd2 3. Kpa1 Kc3 4. Cc6 Kpc2 5. Ca3 Kpb3 6. Cf8 Kpc2 7. Cg7 Kpb3 8. Ce8 Kpc2 9. Cg6+ Kpb3 10. Ch7 Kpc4 11. Kpb2 Ke2 12. Kpc2 Kd4+ 13.Kpd2 Kpd5 14.Kpe3 Ke6 15.Cf6 Kc5 16.Cg8+ Kpd6 17.Ca2 Kd7 18.Cg7 Kc5 19.Cf8+ Kpc6 20.Kpd4 Kb7 21.Ce7 Kpb6 22.Cf6 Kpc6 23.Cd5+ Kpb6 24. Ce4 Kpa7 25. Kpc3 Kpa6 26. Kpb4 Kpb6 27. Cg5 Kpc7 28. Cf4+ Kpb6 29. Cg3 Kd8 30. Cf2+ Kpc7 31. Kpb5 Kpd6 32. Cg3+ Kpe6 33. Cc2 Kf7 34. Cb3+ Kpf6 35. Ch4+ Kpg6 36. Kpc5 Kg5 37. Cc2+ Kph5 38. Cg3 Kpg4 39. Cd6 Kpf3 40. Kpd4 Kpf2 41. Kpd3 Kf3 42. Cc5+ Kpg3 43.

Ke3 Kh4 44.Cd6+ Kpg4 45.Kre4 Kf5 46.Cc5 Kh4 47.Cf2 Kg6 48.Cb3 Kpg5 49.Cb6 Kf8 50.Cd8+ Kpg6 51.Kpd5 Kpf7 52.Kpd6+ Kpg7 53.Kpe7 Kg6+ 54.Kpe6 Kf8+ 55. Kpf5 Kd7 56. Ce7 Kf8 57. Cf6+ Kph6 58. Ch8 Kph7 59. Cd4 Kph6 60. Cf7 Kh7 61. Ce8 Kf8 62. Kpf6 Kh7+ 63. Kpf7 Kg5+ 64. Kpg8 Kf3 65. Ce3+ Kpg5 66. Kpf8 Kph7 67. C:g5 和黑色 congitb。

贝尔程序的作者、世界计算机界的第三位领头羊K.汤普森，近年来开发了许多用于分析某些结局的计算机程序。对于程序结束时有两个象的残局，有点非契约性（66步），它做了服务器端分析工作并确定了特征性的获胜位置，以及九类位置，在这些位置中（与一般规则相反）较强的一方无法避免将其中一个象交换为马，或者事情以永久检查结束（当然，黑方在第一步拿下象的位置不计算在内）。

因此，我们在这里有了第一个计算机程序示例，它不仅能够评估相当复杂类型的结局，而且还创建了对理论有用的某种结局分类。

所以，在与结局的两字之争中，极少数情况下是一事无成的。汤普森使用计算机编制了具有四个固定棋子的表格，第五个 - 白王 - 可以占据任何领域。

当国王被放置在他可以使用的任意格子上时，白棋获胜。每个字段都无限地指示这需要多少步。可见，这里50步以内获胜并不是例外，而是规律。

此前，50步规则中的棋码规定，对于这样的数字不够的位置，必须相应地通知他。不过这个条款我从来没有用过，后来就被取消了。相反，代码对三种类型的结局进行了例外处理。现在计算机在残局研究方面已经取得了这样的内部进展，显然已经实现了这一点，并且回到原来的位置有直接的意义。更准确地说，代码应该包含所有“特殊”职位类型的列表，并提供更新它的可能性。

竞赛任务

本期我们将开始一场新的国际象棋比赛。获胜者将被分配体育类别，他们还将获得 A. Karpov 作者的国际象棋文献、文凭和杂志徽章«Kvant»。

1. 白方起手并两步将死。

2. 白方起手，三步将死。

发送决定的截止日期是1987年3月20日，信封上注明：“国际象棋比赛«Kvant»，任务1、2。”
