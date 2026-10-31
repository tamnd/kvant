---
id: 1974-11-guter-donskoy-mashina-igraet-v-shahmatyi-ee9d8eaf
issue: kvant_1974_11
year: 1974
number: "11"
title: The machine plays chess
authors:
  - Гутер Р. С.
  - Донской М. В.
rubric: osnovnye-stati
page_first: 19
page_last: 24
page_labels: 17-22
tag: KYFY
lang: en
source: kvant_digital
extraction: vision
content_sha256: 87ae2fdc5e7f5ced984afbb19428c4613f73c0ed6fae9153bce3d01f3c077e61
prompt_sha256: draft-1
translated_from: content/ru/1974/11/articles/07_guter-donskoy-mashina-igraet-v-shahmatyi-ee9d8eaf.md
source_content_sha256: da388e5603ff53a3277b741e200a5574dc4a93973cb84d04fde211ce443ce0f7
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 17⟧

Drawing up a chess game program for an electronic computer requires solving the following problems:

1) creating a method for recording and storing information about the position on the board and the move in the machine;
2) creating an algorithm with which the machine must choose the next move;
3) implementation of this algorithm in the form of a program using a known method of recording and storing information.

Recording a position

Let's number the cells of the chessboard with two starting numbers, the first digit of which means the number of the vertical (in the general chess notation it is designated by a letter), and the second - the number of the horizontal (both numbers starting from the number 0). Since there are eight horizontal and vertical lines, you can use the machine-friendly eight-digit system of numbers, which uses the numbers 0, 1, 2, ..., 7 *). Thus, after a1 there will be number 00, after a8 - number 07, after d5 - number 34, and after h8 - number 77.

Let's also number the chess numbers, assigning the number 1 to the pawn, 2 to the knight, 3 to the bishop, 4 to the rook, 5 to the queen and 6 to the king, with the white numbers being positive numbers and the black numbers being negative. Each doxy in a position is comparable to a number - the number of the digit in this field or 0 if the field is empty.

In the proposed numbering, the number of a digit is an eight digit, for which three double digits are enough to represent, and a sign (the color of the digit), which requires another digit to be written. By-

*) It will be useful for the reader to remember or read the articles: P. C. Guter, Computing machines and number systems, «Kvant», 1971, No. 9, Human language and machine languages, «Kvant», 1971, No. 10,

⟦folio 18⟧

this requires four digits per field to record the position. We will reserve the first digit for recording the sign (0 - “plus”, 1 - “minus”), and the next three - for recording the number of the figure. One memory cell will contain information about one horizontal line, while 32 bits will be occupied in the memory cell. All information about the position on the board will occupy 8 cells (1 for each horizontal line).

figure 1 shows the entry of the first horizontal line of the starting position. The reader can easily understand it by remembering the representation of octal digits in the form of thirteen doubles:
$$0_8 = 000_2, 1_8 = 001_2, 2_8 = 010_2, 3_8 = 011_2, 4_8 = 100_2, 5_8 = 101_2, 6_8 = 110_2, 7_8 = 111_2$$
(here the index of the number indicates the number system in which it is written).

Recording a move
A move can be represented as a pair of numbers: the number of the square on which the piece was, and the number of the square on which the piece moved. It is more convenient, however, as is done in a chess position, to report both fields, as well as the name and color (that is, the number and sign) of the moving piece. Then you will need three numbers, and the first of them will be single-digit (but with a sign), and the other two will be double-digit.

Yes, record
+1 41 43
means the move of the white (+) pawn (1) from square e2 (41) to square e4 (43), that is, in the general chess position the whole

ma popular move e2 - e4, known even to O. Bender. Record
—5 37 64
corresponds to Black's move, generally written as Qd8 - g5.

Choice of move
It is quite simple to “teach the machine” to make a move, that is, to check its possibility and enter the corresponding change in the position record. It is immeasurably more difficult to teach her quickly, although there are several possible ones in a given position, one “best”. To do this you need to be able to compare different moves.

One way is to sort through the options. But searching “to the end,” that is, to the position in which the result is known, is impossible due to the immense size of the required number of options. We have to limit ourselves to considering a certain number of moves. But then you need to be able to compare positions and answer the question which one is better. We can then consider that the best move is the one that leads to the best position.

A much simpler assessment would be the difference between white and black resource materials. In this case, each figure is assessed with a certain number of points (points). To evaluate a position, it is enough to calculate the sum of points corresponding to the white and black pieces on the board and find their difference. Of course, such an assessment is too rough: it is known that it is often necessary to sacrifice material for the sake of

Horizontal
Field numbers
Entry in cell

Fig. 1.

⟦folio 19⟧

acquiring positional or tactical advantages. Therefore, more subtle assessments also include tactical factors: the possibility of forming a winning material, the presence of overpowered pawns on oneself or the opponent, the possibility of castling, occupying an open line with a rook or queen, etc.

How to use the ability to evaluate position using one or another selected evaluation function? It is clear that it is not enough to evaluate the position that receives the last of one move, but it is necessary to consider all possible positions several moves ahead. Naturally, the greater the “depth of search,” that is, the number of moves after which it is evaluated, the better the choice of move. However, it is necessary to take into account that increasing the depth by 1 move increases the time for choosing a move by approximately 40 times.

The choice of move is carried out using a minimal procedure, which we will illustrate using the example of a search for 1 move. Let from position $A$ (our move) moves leading to positions $B_1, B_2, B_3$ ... (Fig. 2) are possible. From the resulting positions, the opponent's moves are possible, leading to positions $C_1, C_2, C_3, C_4$, ..., the estimates of which are known to us. Since in a position, say, $B_1$, the opponent will most likely choose the strongest possible move, then the score $B_1$ should be taken as the minimum of the position scores $C_1, C_2, C_3$. The estimates of the remaining positions $B_2, B_3$, ..., obtained after our various moves, are also determined.

Knowing the position estimates $B_1, B_2, B_3$, ..., we can choose the most suitable one. The move leading to the position with this maximum score will be the best for the selected search depth.

A similar move selection strategy is used for any other search depth: a given number of moves is made from a given position, and the resulting position is estimated using the selected evaluation function. Then the last move is changed and the new position obtained is evaluated. Once all possible last moves have been checked, the second to last move is changed, and so on, so that in the end all positions that can be obtained from the original last number of moves are evaluated. The estimates obtained “at the lower level” are restored “upward”, and for positions with the enemy’s move, the minimum is selected, and for positions with our move, the maximum is selected from the estimates of the “lower” positions.

Thus, your own move and your opponent's move should be considered differently. In the future we will call them *half-moves*. An example of a scheme for selecting a move when searching for

⟦folio 20⟧

three half-hours are shown on figure 3. Here the circles indicate the positions, the red segments indicate your moves, and the blue segments indicate the opponent’s moves.

The numbers in the circles represent the position estimates obtained in the manner described above (for “low” positions - using the evaluation function, for “higher” - using the minimal procedure). The numbers next to the segments show the sequence of distances of the corresponding moves during the search. The best moves from each position are marked with double lines.

Let us only note that for greater clarity figure we limited ourselves to a small number of possible moves from each position. As a result, translate this algorithm into machine language, turning it into a game program. This is hard work that requires programming skill, since the program’s running time, that is, the time for selecting a move, largely depends on the quality of the program for implementing the algorithms. Naturally, we are not able to reproduce the structure of such a program in any detail; we will describe it only in the most general terms.

There are six subroutines $P_1$—$P_6$ (one for each type of game). Each of them compiles a list of moves possible from a given position by a game of a given type. Subroutine $P_7$ coordinates these six subroutines and writes out all the moves possible in a given position.

In addition to the listed subroutines, there is a subroutine $P_8$, which performs a move with an estimate, obtaining a new position, a subroutine $P_9$, which calculates an estimate

the resulting position, a subroutine $P_{10}$ that implements the minimal procedure, and, finally, a control program $P_0$. The latter decides which subroutine to contact, designates which position is considered and which move is made from it, and actually implements the move selection algorithm.

Routines $P_1$—$P_7$ can use positional auxiliary information. Thus, when constructing possible moves, it is convenient to use the “possibility raster”, which for each game is written as follows. One digit is allocated for each chessboard; for all boards it is enough to occupy two memory cells, 32 bits each. In the bits corresponding to the fields that this game can go into, 1 is placed, the remaining bits contain 0.

For example, for the position shown on figure 4, the raster of possibilities for rook Rc4 is shown on figure 5. The bottom cell here corresponds to the bottom line of the board (horizontals 4-1 in chess terminology).

The work of the subroutine $P_4$, which builds this raster, can be imagined as follows. In the position record, the subroutine selects the tetrad (four double signs) corresponding to the adjacent field in the same horizontal line and analyzes it.

If this tetrad is zero, then the field is free, the rook can go to it - it will place 1 in the rank corresponding to this field. After this, it is checked whether this field is the outermost field of the board. If not, then it is considered next

⟦folio 21⟧

Blowing neighboring field; if the field was extreme, then the subroutine moves on to the other direction.

If the selected terrad is not zero, then the subroutine $P_4$ analyzes its first digit, which determines the color of the figure occupying this field. If this number is 0 (+ sign, white figure), then the field is occupied by its own figure. The subroutine $P_4$ places 0 in the corresponding digit of the raster and proceeds to the divergence of a new direction. When the number is 1 (sign -, the piece is black), the subroutine also proceeds to explore a new direction, but puts 1 in the rank corresponding to this field: the rook can move to this square, capturing the black piece standing here.

When the possible horizontal moves of a rook are different, you need to select terrads from the same cell. For the vertical, you need to select terrads that occupy the same position in adjacent cells corresponding to different horizontal ones.

The work of other subroutines is based on the same principles. Thus, the subroutine $P_3$, which determines the moves of the bishop, to select the terrad of the neighboring field, produces a shift by 4 bits and moves to the neighboring cell. Subroutine $P_5$ for queen constructs all possible moves for rook using subroutine $P_4$ and all possible moves for bishop using subroutine $P_3$, and then combines them.

Normally, a "move selection" program ends up selecting a move to make at a given position, printing it, and leaving it. The move can be printed in the form described above, for example:

$$+2\ 10\ 22,$$

Or you can use an alphanumeric printing device and print the same move in a form similar to chess

To b1 - c3.

Now it is not difficult to organize a “full game”. To do this, in addition to the “move selection” program, a program is needed that connects the chess program “with the outside world.” This program must be able to enter into the machine the position in which a move must be selected, the conditions for selecting a move (for example, the search depth), and provide control over the correctness of the entered information.

This program has a "main doxa", the position of which remains unchanged during the move selection process, it changes only after the move is selected and printed.

There is no need to think that the methods we have described for solving the main problems of programming a chess game are the only ones. This is not true at all, there may be others. By looking at each of these problems in isolation, it is possible to find ways to simplify or improve certain details of solving one of them, but this may have a negative impact on other parts of the program. For example, you can choose a different way of recording a position, which is much more compact, that is, saving the amount of computer memory. But estimating a position with this recording method may require a much larger number of actions. Although it is possible to achieve improvements “in all parameters,” it is very difficult.

Formation The three main problems of programming a chess game are not considered equal, and their solution has a very different effect on the quality of the program. If earlier ways to solve the first

⟦folio 22⟧

and the third problem could somehow affect the running time of the program, but now there are almost no reserves left. The situation is completely different with the move selection algorithm: its influence on quality and strength is decisive.

In “Kanssa-72” this problem is solved as follows: all options are sorted out to a depth of 7 half-deads, after this depth only the so-called “forced moves” are sorted out - captures, checks and answers to them. The total search depth varies from 7 to 30 half-days.

The reader may notice that with a full search for 7 half-days (with an average of 40 moves from each position), 40⁷ positions will have to be considered, not even counting forced moves. It's too much. However, the authors of “Kanssa-72” did a great job of developing rules that allowed them to work out some positions or moves, which allowed the creature to reduce the search. In fact, when searching for 7 half-hours (together with forced options), about 750,000 positions were considered, which took less than an hour of machine operation.

In the best American chess program, created at the Massachusetts Institute of Technology by Greenblatt, in each position 10 moves are considered, the “best” ones according to some assessment different from the assessment of the position that arose after the corresponding move, and an arbitrary search, the depth of which varies from 6 to 16 half-days. There are other ways to solve this problem.

However, despite the existing conditions, there is still no move selection algorithm that allows sufficiently strong moves with a natural limitation on the selection time. To find such an algorithm, fundamentally new ideas are needed. The search for these ideas requires a detailed study of the “behavior” of the program when choosing a move, the reasons that influence both the chosen move and the time of choice. This can be seen in a large number of experiments with chess programming.
