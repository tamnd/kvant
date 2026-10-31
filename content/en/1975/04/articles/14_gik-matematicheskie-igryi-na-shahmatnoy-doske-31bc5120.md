---
id: 1975-4-gik-matematicheskie-igryi-na-shahmatnoy-doske-31bc5120
issue: kvant_1975_4
year: 1975
number: "4"
title: Math games on chessboard
authors:
  - Гик Е. Я.
rubric: kvant-dlya-mladshih-shkolnikov
rubric_sub: «Квант» для младших школьников
page_first: 56
page_last: 61
page_labels: 54-59
tag: 171V
lang: en
source: kvant_digital
extraction: vision
content_sha256: 7f91c2e25be4cb63ff5150c80dd363f86e47259b08669c371215698d8a5f86ff
prompt_sha256: draft-1
translated_from: content/ru/1975/04/articles/14_gik-matematicheskie-igryi-na-shahmatnoy-doske-31bc5120.md
source_content_sha256: afbfa3d6c6733287e47b56d09c6ab41093f27906f47ae5b3a476ad273e798130
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 54⟧
## E.Ya. GIK
## MATH GAMES ON THE CHESS BOARD

⟦figure⟧

The game of chess has been created over many centuries, and its rules have changed several times. However, from a mathematical point of view, the movement of chess pieces and the shape of the board are very conditional. There are many different games on rectangular boards, the theory of which occupies a significant place in the mathematical literature. There are more than a dozen known checkers games alone: ​​Russian, hundred-cell, Lasker checkers (see «Kvant», 1970, No. 4), giveaways, corners and others. Even modern chess has many varieties. For example, M. Gardner in the book “Mathematical Puzzles and Entertainment” (M., “Mir”, 1971) talks about Japanese chess (sogi), Chinese (qun ki) and Korean (tian keui). We will now focus on some games and problems (containing mathematical elements) in which the board or rules of the game differ from the usual ones.

## Until the first check

In this game, everything is like in real chess, only the winner is not the one who is “first” to give checkmate, but the one who is the first to declare check. With the usual starting position, White wins by force, and no later than the fifth move:

1. Nb1-c3. There is a threat of a knight attack on e4, d5 or b5 with an inevitable check, Black has the only answer: 1...e7-e6. Now after 2. Kc3—e4

⟦column⟧

Ke8-e7 the second knight comes into play with a decisive effect: 3.Kg1-f3 Qd8-e8 4. Kf3-e5 and check on the next move.

To “spice up” the game, you should change the starting position in some way, for example, moving the white pawn from c2 to c3, and the black pawn from c7 to c6. Now 1. Kc3 is impossible, and therefore the entire variation indicated. The forced win is no longer visible, for example: 1. Qb3 d5! 2. Qb4 Qd6! 3. Qa4 Bd7 4. Qh4 Kf6, and the black king is securely protected.

## Two-move chess

In this game, each move of White and Black consists of two ordinary moves. Apparently, it is no simpler than real chess. It is all the more surprising that it is possible to prove the following non-obvious fact: *if White plays two-move chess correctly, White is at least guaranteed a draw.*

Here is the proof given in some sources. Let's assume the opposite: let white lose if both sides play best. After 1. Nb1-c3-b1 the initial position is preserved, and the first move already belongs to Black. In fact, now Black is playing White and, by assumption, is losing. Contradiction.

This evidence is not entirely accurate. After White's first move, the position is indeed repeated, but the situation is different! So, after 1...Ng8 - f6 - g8 2. Nb1 - c3 - b1 White cannot yet demand a draw, but Black can, since 2...Ng8 - f6 - g8 leads to a threefold repetition of the original position when White moves. Thus, it is impossible

⟦folio 55⟧

consider that after 1.K b1 - c3 - b1 “black plays white” - possibly side zones. By the way, a similar example can be given for the 50-move rule.

Let us now give a rigorous proof. We still believe that Black wins if both sides play flawlessly. We will play on two boards simultaneously. On the first subdem 1.K b1 - c3 - b1, and Black's counter move will be reproduced on the second board from White's side. Then we will repeat Black’s response on the second board for White on the first, Black’s move on the first for White on the second, etc. According to our assumption, Black wins and, therefore, the moment will come when on the first board with their next move they will checkmate the White king. But then on the second board, when this move is repeated as White, a position will arise in which the black king gets mated! But Black played flawlessly on the second board too—a contradiction.

The above proof, as mathematicians say, is not constructive. We've proven that White can't lose at two-move chess, but we haven't figured out how he should play. Moreover, if a forced win is found for White (as, for example, in the game “before the first check”), then, very indo, the first move 1. Nb1 - c3 - b1 loses. Thus, it is possible that our proof of White’s win-win situation was carried out using a losing move!

Chess without zugschang

If in a normal game a position arises that any of our moves loses, then we talk about a zgushang (if any move on the ground also loses, then the zugshang is mutual). Chess without zugschang differs from ordinary chess by the addition of one move - a move on the spot. There is no zugschang in them, since it is always possible to pass the turn of the ground move.

The above proof that if White plays correctly a draw is guaranteed, completely holds true for chess without zugschang. However, unlike two-move chess, finding an unrepresented checkmate is hopeless here! Let us recall that in real chess, where White’s chances, judging by statistics, are noticeably higher, it is not at all proven that even with the best play he is guaranteed at least a draw.

Secondary students of mexmata Moscow State University enjoy the following game of crosses and crosses. On checkered paper of any shape (even “endless”), two people take turns placing crosses and polniks.

Fig. 1. Endgame in a giveaway.

The winner is the one who is the first to place five of his icons in a row (vertically, horizontally or diagonally). Similar to double chess and chess without zugschang, it can be proven that here, too, a beginner with perfect play does not lose. True, the proof in this case is more complicated than in chess games.

Giveaways

This game is more popular in checkers, but its chess version is also very interesting. The winner in it is the one who manages to separate all his pieces. Capture in this game is mandatory (including the king, which can be put into battle), and if several are possible, then the choice is arbitrary. By the way, Grandmaster D. Bronstein plays chess giveaways no less willingly than real chess.

The theory of giveaways is quite oriental and is completely different from the laws of ordinary chess. The distance is the simplest endgame (Fig. 1). There are only two pawns on the board, but look how many subtleties the position contains. 1. a2—a3! But not 1. a4, since the white pawn must be promoted later than the black one. 1...h6—h5 2. a3—a4 h5—h4. 3. a4—a5 h4—h3 4. a5—a6 h3—h2 5. a6—a7 h2—h1Л! It is the rook; during other transformations of the black pawn (into a queen, bishop or knight), White places a queen, which will separate immediately or on the next move. 6. a7—a8C!! This is the only way, otherwise Black will easily capture his rook. Now on any black move

⟦folio 56⟧

Fig. 2. The knight’s route across all squares of a 4×4×4 volumetric board.

fret follows 7. Ca8—h1!, and White gets rid of the bishop.

We invite you to independently evaluate one ending in the giveaway game and solve one stage.

Tension 1. White has a pawn on d7, and Black has a knight on f5 (there are no other pieces on the board). How the giveaway game will end:
a) when White moves;
b) when Black moves?
Tension 2 (X. Klüver and K. Fabel). The white king is on f3, black has two pieces - the king on d7 and the queen on c8. White starts and loses (that is, wins at the giveaway).

Chess on a straight board
Numerous games and problems arise when moving to straight boards $m \times n$ for various values ​​of $m$ and $n$. Most of the well-known chess-mathematical problems and puzzles about the movement of pieces, routes, arrangements, strength of pieces can be easily translated onto such boards (see «Kvant», 1971, No. 9; 10; 1973, No. 1; 1974, No. 6). You can also play on an infinite and projective chessboard (see «Kvant», 1974, No. 3). All these boards, like the traditional chessboard, are flat.

Volumetric chess
They are played on a three-dimensional board, which is a parallelepid $m \times n \times k$, the unit cubes of which form the fields of the board.

The problem that Euler deals with is well known: to go around with a knight all the squares of the board $8 \times 8$, visiting each of them once (see «Kvant», 1971, No. 9). Let's consider a similar problem on a three-dimensional board, consisting, like a regular one, of 64 squares (cups): bypass with a knight all the squares of the three-dimensional chessboard $4 \times 4 \times 4$, raising on each of them once.

It is convenient to imagine the board as four horizontal layers lying one on top of the other. On figure 2 the surfaces of these layers are depicted, and the layers themselves are occupied. To find the desired route, it is enough to indicate the numbering in which the cubes with adjacent numbers are spaced from each other by one knight move. Such numbering is possible; it is shown in figure 2.

U tense 3. Find the route of the knight on the surface of the volumetric board $8 \times 8 \times 8$. Here the knight actually moves across six flat boards. The main difficulty of the problem is the conjugation of six object routes; to solve it, it is convenient to use the unfolding of the cube.

Cylindrical chess
From a common board one can, generally speaking, make two cylindrical ones (see also «Kvant», 1970, No. 5; 1971, No. 8). A vertical cylindrical board is obtained by gluing the vertical “a” to “h”, and a horizontal one by gluing the vertical to the eighth.

⟦folio 57⟧

⟦figure⟧
4

⟦figure⟧
Fig. 3. Checkmate in 1 move.

⟦figure⟧
Fig. 4. Checkmate in 4 moves.

When switching to a cylindrical board, it is not possible to solve some problems that can be solved on a regular board. For example, the famous problem of placing eight queens, which was studied by Gauss, has 92 solutions on an ordinary board and none on a cylindrical board!

Exercise 4. Prove that on a cylindrical board it is impossible to place eight queens so that no two of them threaten each other.

figure 3 shows the starting position of three problems at once: both the regular board and the two cylindrical boards have their own solution:

a) on a regular board 1.Fe2-e8 mate;

b) on a vertical cylinder 1. Qe8 is only a check due to the answer 1... Kra8-h7!, and 1. Qe2-g8 mate leads to the goal (the white queen took the route e2-a6-h7-g8);

c) on a horizontal cylinder 1. Qe8+ also gives nothing because of 1... Kra8-a1!, and 1. Qe2-a2 mate solves it!

## Toroidal chess

A toroidal board is obtained by double gluing the opposite edges of a regular board.

Let's solve the problem given on figure 4. After 1. Qf5—h7! Black has two answers at his disposal:

a) 1... Ke8-f8 (the squares d1, e1 and f1 are controlled by the white king with e2 - the horizontal rules apply on the torus

⟦column⟧

tal cylinder!) 2. Qh7—g6 Kpf8—e7 3. Kpe2—e1 Kpe7—d7 (now the white king with e1 holds the squares d8 and f8) 4. Qg6—e8 checkmate!

b) 1... Ke8—d8 2. Qh7—c7+ Kpd3—e8 3. Kb5—h6! (the knight moves along the torus as if along a vertical cylinder!) 3...Ke8—f8 4. Qs7—e1 mate! (the squares f7 and g8 are held by the white knight, and the rest by the queen).

## Chess on unusual boards

The list of chess games on various boards, obtained from a regular one using geometric transformations, can be continued. There are multi-dimensional boards, a two-on-two board (so-called “quadruple chess” is played on this board) and a “three-on-three” board (here the winner is the one who eats both opponents’ kings).

You can play on two parallel boards - on each of them the rules are normal and, in addition, pieces are allowed to move from one board to another like in an elevator. If, when gluing, the board is twisted half a turn, then instead of a cylindrical board we will get a Möbius strip! On it, a piece in one move can end up on the same field, but only on the other side!

The funny board is shown at figure 5, it was exhibited at an exhibition of French avant-garde artists!

⟦folio 58⟧

⟦rubric⟧
Fairy tales

In chess composition, problems and games with unusual rules, on non-standard boards and with unusual pieces are classified as fairy-tale (or fantastic) chess. We have already talked about several fabulous games on unusual boards. Let us now dwell on some of the most popular fairy-tale figures.

A number of fairy-tale characters are obtained by combining the usual moves of a rook, bishop and knight. There are four possible combinations: rook+bishop (in this case the result is a queen), rook+knight (*chancellor*), bishop+knight (*centaur*), rook+bishop+knight (*maharajah* or *amazon*).

The Maharaja is a very powerful piece, significantly superior in strength to the queen (try to find the strength of the Maharaja using the method described in «Kvant», 1974, No. 6). The next popular game is associated with the Maharaja.

*One player has a full set of pieces standing in their original places, while the other has only one maharajah, which he places on a random field. The Maharajah loses if she is eaten, and wins if she checkmates the enemy king.*

In this game, pawns are forbidden to promote, since otherwise the winning is too simple - it is enough to move both outer pawns into queens, after which three queens and two rooks will easily surround the maharajah. If a reservation is made, the Maharajah puts up stubborn resistance, and an inexperienced player may lose. And yet, the player who plays with a full set of pieces has a forced win. M. Gardner in the book “Mathematical Novels” (M., “Mir”, 1974) proposes a plan for encircling the Maharaja, consisting of 25 moves. However, the goal can be achieved at least ten moves earlier.

Ignoring the movements of the Maharajah, White makes a sub-

⟦column⟧

series of the following 14 moves: a4, h4, Ra3, Rhh3, Nc3, Nf3, Rb3, Rg3, d4, Qd3, Qe4, Rb7, Qd5, Rg8 (it is easy to see that so far the Maharajah could not eat a single white piece or give checkmate). Now the Maharaja has only two safe squares - a6 and f6. In the first case, it dies after 15.Cg5, and in the second - after 15.e4. Maybe you can improve this record?

Exercise 5. Arrange 10 maharajas on the board $10\times10$ so that they do not hit each other (on smaller boards it is impossible to arrange them in the required manner).

⟦figure⟧
Fig. 5. The chessboard is an exhibit of an exhibition of avant-garde artists.

## Fairytale horses

Various fairy figures are obtained from the generalized knight $(a, b)$ by choosing certain values ​​$a$ and $b$. Such a knight moves $a$ squares in one direction and $b$ squares in a perpendicular direction. For a regular knight $a=1$, $b=2$.

Horse $(1,3)$ is called *camel*, $(1,4)$ - *giraffe*, $(2,3)$ - *zebra*. If one of the numbers $a$, $b$ is equal to zero, then the result is a rook moving to a fixed number of squares, but if $a=b$, then the result is a bishop,

⟦folio 59⟧

giving the same property. A horse that makes several leaps in a row in one move has the “title” of *gardener*. problem M268 is dedicated to an interesting game (see «Kvant», 1974, No. 6). In it, one player moves the same piece as a regular knight (with a double move), and the other as a camel. At the same time, the horse turns out to be more cunning than the camel!

There are many mathematical games and problems taking into account fairy-tale figures; all the topics mentioned above (routes, arrangements, strength of figures and others) are easily transferred to such figures.

Shashmy

This game, which is a mixture of chess and checkers, was invented by the American mathematician S. Golomb, known in our country for his game “polyominoes”. Chess is played with chess pieces, but only on black squares (as in checkers). An ordinary knight here is not able to make a single move (it immediately ends up on a forbidden white square), so it is replaced by a camel - a knight (1,3), which does not change the color of the fields.

figure 6 shows one of the camel’s closed routes across all squares of the chessboard. It is known that a maximum of 32 knights can be placed on a chessboard without threatening each other (they can be placed on all white or on all

Fig. 6. Closed route of a camel on a chessboard.

black fields). The maximum number of “peaceful” camels on a chessboard is 16, that is, they can also occupy half of all fields. Camels can be placed on squares with all even numbers or with all odd numbers on figure 6. Thus, this figure gives a solution to two problems on the chessboard at once. A more detailed story about chess (in particular, the arrangement of pieces before the start of the game) can be found in the second of the mentioned books by M. Gardner.

In conclusion, we’ll tell you about a few more fairy-tale figures that don’t look like anything else at all! The cricket moves like a queen, but jumps over its own and other people's pieces, leaving them right behind it. The lion, unlike the cricket, recognizes the overturned piece on any free field. There are non-imperial pieces that can be played by both white and black. Battle pieces are only allowed to move with captured pieces. The beating horse is called *zinnonomatom*, and the former figure is called *dinosaur*. The figure *dinlomat* does not walk on its own, but it cannot be taken either; Moreover, around the diplomat, his own figures are inviolable! And the *kamikadze* (suicide) piece is removed from the board along with the captured piece!

Until six years ago it was exclusively about figures. However, many varieties have been created for pawns. *Chameleon pawn* when capturing a non-hiding piece, it turns into the same piece, but of its own color. The over-the-top moves to any number of fields in a straight line and to any number of fields diagonally. *Maxi Pawn* moves both forward and backward. Finally, once in a game, a pawn can be allowed to become an “atomic bomb”. Immediately after its appearance, this piece is placed on any field of the board and within a radius of *r* fields (the number *r* is specified in advance) destroys everything around it.
