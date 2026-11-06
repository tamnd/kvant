---
id: 1990-7-gik-izmeneniya-v-kodekse-ea933d8f
issue: kvant_1990_7
year: 1990
number: "7"
title: Changes to the code
authors:
  - Гик Е. Я.
rubric: shahmatnaya-stranichka
rubric_sub: Шахматы
page_first: 83
page_last: 83
lang: en
source: kvant_digital
extraction: vision
content_sha256: b79a1dca5a2c375e8ce4f746f162d4ffaf0ac50f3305b638b74d533d0ddef121
prompt_sha256: draft-1
translated_from: content/ru/1990/07/articles/02_gik-izmeneniya-v-kodekse-ea933d8f.md
source_content_sha256: 4c84211a40e076dbe34c3be1375c9361f8f4cda4944813caf3029031ce6e63d5
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 84⟧

---
running_head:
folio:
---

Changes
in the code

Let us recall that, according to the chess code, a game ends in a draw if, within 50 moves, not a single capture has occurred on the board and not a single pawn has moved. Twenty years ago, this rule did not allow exceptions. But when computers began to discover endings that were won, but for more than 50 moves neither captured nor pawns moved, it was necessary to change each new edition of the code.

In the previous edition, the number 50 was increased to 100 for three types of endgames: rook and bishop versus rook; two knights against a pawn (if it is blocked on certain squares); rook and pawn against bishop and pawn (for some pawn positions, for example: white has a2, black has a3 with white’s rook in black’s dark-full bishop).

More recently, FIDE released a new code, and after it the 12th edition of the “USSR Chess Code” appeared. The rook and pawn versus bishop and pawn endgame is not considered exceptional at all.

And the number 50 is increased to 75 for six endings: rook and bishop against rook; two knights against a pawn; queen and pawn against queen; queen against two knights; queen against two bishops; two bishops against a knight.

«Kvant» talked about each of these endings and gave record positions. In them, the pieces actually captured, the movement of a pawn or checkmate occurred in the interval between the 50th and 75th moves. But while a new edition of the code was being prepared, the computer discovered new record positions.

The first is related to the already explored “two knights against a pawn” endgame. Just a year ago it was believed that the record here was 69 moves (with la-

active pawn), but now it has been brought to 82 moves.

1. Nb4+ Npb6 2. Kd3. The pawn is blocked, and now the white king and the second knight begin a long pursuit of the non-stealing king. 2... Kpc7 3. Kb5+ Kpc6 4. Ka3 Kpb6 5. Kpb8 Kpc6 6. Kc4 Kpb5 7. Kce5 Kpb6 8. Kpc8 Kpa6 9. Kpc7 Kpb5 10. Kpd6 Kpa4 11. Kpc5 Kpb3 12. Kpb5 Kpc3 13. Kpa4 Kpc2 14. Kpb4 Kpd1 15. Kpb3 Kpd2 16. Kpb2 Kpd1 17. Kc4 Kpe2 18. Kpc2 Kpf3 19. Kpd2 Kpg3 20. Kpe2 Kpg2 21. Kce5 Kpg3 22. Kpf1 Kph4 23. Kpg2 Kpg5 24. Kpf3 Kpf5 25. Kc4 Kpf6 26. Kpf4 Kpe6 27. Kpe4 Kpf6 28. Kpd5 Kpe7 29. Kpe5 Kpf7 30. Kpd6 Kpf6 31. Kd2 Kpf5 32. Kpe7 Kpg6 33. Kpe6 Kpg7 34. Ke4 Kpg6 35. Kpe5 Kpg7 36. Kpd6 Kph7 37. Kd2 Kpg7 38. Kpe6 Kpf8 39. Ke4 Kpe8 40. Kf6+ Kpf8 41. Kh5 Kpe8 42. Kg7+ Kpd8 43. Kpd8 Kpc8 44. Ke6 Kpb8 45. Kpc5 Kpa7 46. Kpc6 Kpa6 47. Kec5+ Kpa5 48. Kb3+ Kpa4 49. Kd2 Kpa5 50. Kpc5 Kpa6 51. Kc4 Kpb7 52. Kpd6 Kpc8 53. Ka5 Kpd8 54. Kb7+ Kpe8 55. Kpe6 Kpf8 56. Kd6 Kpg7 57. Kpf5 Kph6 58. Kpf6 Kph5 59. Kf7 Kpg4 60. Kg5 Kph4 61. Kpf5 Kpg3 62. Kpe4 Kpg4 63. Kf7 Kph5 64. Kpf5 Kph4 65. Kfe5 Kph5 66. Kg4 Kph4 67. Kf6 Kph3 68. Kpe5 Kpg3 69. Kpe4 Kph3 70. Kpf3 Kph4 71. Kpf4 Kph3 72. Ke8 Kph4 73. Kg7 Kph3 74. Kf5 Kpg2 75. Kpg4 Kph2 76. Kd6 Kpg2 77. Kc4 Kph2 78. Kd2 Kpg2 79. Kph4 Kph2 80. Kf4 Kpg1 81. Kpg3 Kph1 82. Kf3 d3. Finally! 83. Kh3 d2 84. Kf2×.

The second record is associated with a little-studied endgame, which was not taken care of by the machine. I got busy - and here is a new amazing discovery: the bishop and knight cope with the knight in only 77 moves!

1. Cg3 Kc4 2. Kpd1 Ke3+ 3. Kpe2 Kf5 4. Cf2 Ke7 5. Kpf3 Kc6 6. Kpg3 Kd4 7. Kpg4 Kc6 8. Kph3 Kb4 9. Cb6 Kd3 10. Kc2 Kf2+ 11. Kpg3 Ke4+ 12. Kpf4 Kd2 13. Ke3 Kph2 14. Kpg4 Kb3 15. Ca7 Kc1 16. Cd4 Kd3 17. Kph4 Kf2 18. Ce5 Kpg1 19. Cc3 Ke4 20. Ce1 Kf6 21. Kpg5 Kd7 22. Kpf4 Kc5 23. Kpf3 Ke6 24. Cc3 Kph2 25. Kpg4 Kd8 26. Ce5+ Kpg1 27. Kpg3 Ke6 28. Cf6 Kc5 29. Cd4 Kb3 30. Ca7 Kd2 31. Kc4+ Kph1 32. Ke5 Kc4 33. Kd3 Kd6 34. Kph3 Kf7 35. Ce3 Ke5 36. Kf4 Kc4 37. Cd4 Kd6 38. Kh5 Ke4 39. Ce3 Kf2+ 40. Kpg3 Ke4+ 41. Kpf3 Kd6 42. Cf4 Kc4 43. Kpf2 Ka5 44. Kf6 Kb7 45. Kpf3 Kd8 46. Cd6 Kpg1 47. Ke4 Kc6 48. Kd2 Kd4+ 49. Kpe4 Ke2 50. Kpe3 Kc3 51. Ce5 Ka2 52. Kpf3 Kb4 53. Kpg3 Kph1 54. Cd4 Kc6 55. Cc5 Kd8 56. Ke4 Kb7 57. Cb4 Kd8 58. Ca5 Ke6 59. Cb6 Kg5 60. Kf2+ Kpg1 61. Kpf4 Kf7 62. Kg4+ Kpg2 63. Ke3+ Kph3 64. Kf5 Kpg2 65. Cc5 Kh8 66. Kd4 Kph3 67. Kpf5 Kph4 68. Ke6 Kph5 69. Ce3 Kf7 70. Kg7+ Kph4 71. Cf4 Kh8 72. Ke6 Kf7 73. Kpg6 Kh8+ 74. Kpg7 Kp4 75. Ch6 Kph5 76. Kf4+ Kpg4 77. Kp:h8.

The knight is destroyed, but the game does not end and will most likely continue for more than 100 moves.

So the new chess code already requires changes and additions. Yes, it's hard to keep up with the computer!

E. Geek
