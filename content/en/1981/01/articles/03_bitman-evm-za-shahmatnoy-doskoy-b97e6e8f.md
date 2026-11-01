---
id: 1981-1-bitman-evm-za-shahmatnoy-doskoy-b97e6e8f
issue: kvant_1981_1
year: 1981
number: "1"
title: Computer at the chessboard
authors:
  - Битман А. Р.
  - Гик Е. Я.
rubric: osnovnye-stati
page_first: 13
page_last: 19
page_labels: 11-17
tag: GPH8
lang: en
source: kvant_digital
extraction: vision
content_sha256: ce8467d2e335bf5f808fa032ac76acbc9024ac13ce3f2f66fbaa9259c4c346d3
prompt_sha256: draft-1
translated_from: content/ru/1981/01/articles/03_bitman-evm-za-shahmatnoy-doskoy-b97e6e8f.md
source_content_sha256: 7b34c53f3c14142ab530d4d2e9233f3133d7f2e8a645a2ce16546f0d5091752b
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 11⟧

A. Bitman, E. Gik

Computer at the chess board

In economics, in management problems, in long-term planning, in other words, in so-called large systems, choosing a sufficiently good solution seems to be a difficult task. The fact is that a decision has to be made in a limited time, in a complex, changing situation, depending on a large number of factors that cannot be unequivocally assessed and mechanically taken into account. Here it is no longer possible to do without modern technical means that can take on part of the intellectual work.

The meaning of modern automation is the transfer to a computer of such functions as perception of the situation, processing of large objects of information, the ability to compare and evaluate different situations, and draw logical conclusions.

In order for a computer to be able to solve all these problems, it is necessary to formalize them, then develop sufficiently effective algorithms (that is, such that a solution can be obtained) and, finally, implement these algorithms in the form of a computer program.

This is where... chess comes to our aid. They represent a very convenient model of a “large system”. Indeed, in chess it is easy to formulate final and many intermediate goals, but it is impossible to give an exact recipe for achieving them. Choosing an exit in a chess game is making a decision in the difficult situation described above. That is why scientists from many countries working on the problem of artificial intelligence have chosen chess as an excellent model for their research.

Teaching a machine to play chess is not too difficult. It is enough to choose some way of encoding the chessboard fields

⟦folio 12⟧

board and pieces, and then write a program that would determine all the legal moves in a given position. By making any of these moves, the machine would thereby be playing chess. It's not hard to imagine the quality of such a game!
But teaching a machine to play chess well is an extremely difficult task. To solve it, you need to learn to find the best possible move in the presented position. How to build an algorithm that finds such a move? At the same time, it is important that the algorithm provides a solution to the problem not theoretically, but realistically, that is, it allows you to choose a move in a reasonable time. To prepare for solving this problem, we will have to put together some terms and concepts used in general game theory.

Some information from game theory
Chess is a finite game with complete information. In this respect they are no different from, say, the simplest game of tic-tac-toe on a board $3 \times 3$. For such games, almost everything is theoretically known, their structure is absolutely clear. In every position there is a best move (maybe not the only one). The sequence of the best moves on both sides leads this imaginary game to a clear result. In this sense, they say that the outcome of the game in any position, including the initial one, is predetermined. But if in tic-tac-toe the fight ends in a draw if the sides are playing, then in chess the question of how exactly the initial position is predetermined will apparently remain open.

The proof that the outcome of a game in any chess position is predetermined was first given by the Italian mathematician Zermelo in 1913. We present it here because it is necessary for further understanding.

Let us denote the initial (not necessarily the initial) chess position by $P_0$ (Fig. 1), let there be a white move in it (a position with a white move corresponds to white circles, and a position with a black move corresponds to black circles). Let's make all possible moves for White from $P_0$, from each position obtained - all possible moves for Black, etc. Graphically, this procedure is the so-called `дерево церры`, started at $P_0$ (the root of the tree).

Positions in which it is no longer possible to make a move (that is, the board is checkmate or stalemate) are called `заключительный`. Let us introduce natural estimates for them: $1$—white win, $1/2$—draw, $0$—black win. If a certain position along the branch is repeated, then it will also be considered final and a score of $1/2$ will be assigned to it. Since the number of chess positions is finite, any game will reach the final position after a finite number of moves.

Let the maximum length of a game started from $P_0$ be equal to $N$ moves (under the concept of a move, only one of the sides moves). Let's consider all games of length $N$ one move before the end. At figure 1 below the point corresponds to the final position ($N$ level). Let us show that assessments can be transferred from the $N$ level to the $(N-1)$ level using simple rules. Let $A$ be the position from which all moves lead to the final positions. Since we know their estimates, we can also establish an estimate for the position $A$. If it has White to move (as on figure 1), then its score is equal to the maximum of the score for

⟦folio 13⟧

key positions that can be reached from $A$. If it’s Black’s move at $A$, then instead of the maximum score, the minimum score should be taken. In our case, White can make 4 moves from $A$. Two of them lead to a draw, two to a win. The score for position $A$ is 1.

After the described procedure, all positions of the game tree ($N-1$)-th level will be evaluated. Indeed, some of these positions were concluded from the very beginning and already had a valuation, the rest received it according to the specified rule. Now you can remove all positions of the $N$ level from the game tree and continue the described procedure on a new, slightly trimmed tree. As a result, all positions of the ($N-2$) level will be evaluated, etc.

Thus, each time a position with White's convergence is assigned the maximum of the estimates of the positions that can be reached from it, and a position with Black's convergence is assigned the minimum. This procedure is called *minimum or minimax*. Applying minimax for the last time, that is, at the $N$th step, we find the estimate of the initial position $P_0$, and at the same time the best move from it. This ends the proof.

Note that the minimak procedure underlies most gaming programs. Only in this case, the positions obtained from the analyzed one for a certain, not too large number of moves are considered as prisoners.

Based on the Zermelo method, we can create an algorithm that exactly solves our problem - choosing the best move in a position. However, from the point of view of obtaining results, this will be an absolutely unrealistic algorithm. The machine will not make a move, since traversing the entire game tree, both at the current level of technology and in the foreseeable future, will be clearly beyond its capabilities.

General approach to creating chess programs

In 1950, the famous American mathematician K. Shannon published an article in which he gave a general approach to constructing chess programs. First of all, he introduced the concept of *evaluation function*, which associates each chess position with a defining number (score). He further proposed to search through options to a certain fixed depth, and evaluate the resulting terminal positions using an evaluation function. The best move is then determined according to the rules of the minimax procedure.

Shannon pointed to two possible search schemes. According to the first scheme, in the process the truncated game tree is considered into gatherings that are permissible according to the rules of the game. The second scheme will involve enumerating only those moves that, according to some reports, are considered reasonable. When implementing a brute force scheme, it is difficult to achieve a large depth of calculation, since the catastrophic brute force tree grows quickly. In the second case, problems arise related to determining the “reasonableness” of moves.

As an evaluation function, Shannon proposed using a polynomial of the form $\sum_{i=1}^{k} a_i p_i$, where $k$ is the number of features of the position, $a_i$ is the “weight” of the feature, $a_p$ is equal to 1 or 0 depending on the presence or absence of this feature in the position. Using the evaluation function, you can take into account material correspondence with also positional factors: weak pawns, possession of the center, open lines, mobility of pieces, etc.

The question arises: is it possible to come up with a columnar evaluation function (not necessarily of the specified type) that would allow them to be used in any proposed position? With the help of such a function it would be possible to play chess without errors, without having to perform tedious search. The best move is the one that leads to the position with the maximum score*).

*) Strictly speaking, for an optimal game you should also learn how many moves to win a position. To do this, it is enough in Zermelo’s theorem to assign scores $\pm 1/n$ to winning positions, and 0 to drawn ones ($n$ is the length of the branch leading to a given position).

⟦folio 14⟧

The fact that such an evaluation function exists in principle follows from Zermel’s theorem. The values ​​of this function can be specified in the form of a table, the left column of which is a set of all chess positions, and the right column is their scores (1, 0, 1, 2). However, this table will only be as vast as the complete tree of a chess game. Of course, we are not interested in the table evaluation function, but also in one that uses statistical characteristics of the position as arguments. It is impossible to prove this, but most likely, an ideal evaluation function based on simple and explicit features of a position will be as cumbersome as a table function. It is apparently possible to construct a compact function, but then the signs must be too “smart”.

The difficulties encountered in creating a good estimating function are natural and reflect the complexity of the chess game. The messages expressed show that an unbeatable game of chess is hardly possible. To illustrate, consider the following example.

In the position on figure 2, White has a material advantage, but both of his bishops are under attack, and it is easy to see that the ending is a draw. Let's change the position a little by adding a pawn to black on c5. As if this could only make Black's position worse, he loses the same color: 1. h7+! Kr:h7 2. Ca4! R:b2+ 3. Cc2+! R:c2+ 4. Kpf3, and his own stove prevents the black rook from returning to the last rank. The fatal role of the c5 pawn was revealed only in the process of enumerating the options. Now imagine an evaluated function that could sort all this out, that is, pre-seat (for White) the second position with the pen!

Evaluation functions used in real chess programs usually consist of two components - material and positional. Calculating the material component is simple and arbitrary

Fig. 2.

A child in accordance with the scale of relative value of a function adopted by chess players. As for the positional component, various positional assessments can be considered, and as practice shows, reasonable expression of feature weights does not affect the playing strength of the machine. Much more important is the fact of taking into account one or another positional factor.

Obviously, when creating a program, factors such as mobility of the function, possession of the center and open lines, the safety of the king are taken into account, and in the solved structure - phalanxes, strong points, passage, doubled and isolated pawns, etc. Let's consider one of the factors - possession of the center. This is how the evaluated function of the Soviet program “Kanssa” interprets it: the center from White’s point of view is considered to be squares e4, d4, e5, d5, e6, d6; a pawn or minor piece standing in the center gives 20 conventional units; a blow with a pawn or piece to the central square is worth 10 units. To clarify the scale, we add that the mobility of a function is determined by the number of fields it contains, and one number is added for each field.

In various stages of a chess game (opening, midgame, endgame), an assessment of some positional factors may exist. In accordance with this, strong programs have the setting of an evaluation function, that is, a function for which the set of features and their weights is determined by the program itself depending on the situation on the board. In particular, “Kansa” has four such states:

⟦folio 15⟧

re - three are intended for three stages of the game, and the fourth is used to checkmate the opponent’s king with an overwhelming material advantage.

Modern methods of chess programming

Any chess program one way or another implements some sort of exhaustive search scheme. In this section we will look at methods and algorithms that are common to large-scale running chess programs.

1°. Method of edges and estimates
A very powerful method of reducing search is the method of edges and estimates, which is currently used in all gaming programs. Let's look at it in more detail. To do this, we select a certain fragment from the game tree, schematically depicted in figure 3.

Let White in position $A$ have already studied the move $AB$ (that is, the move leading from position $A$ to position $B$). In this case, the corresponding subsection with vertex $B$ as a result of the minimkas must have a position $B$ score $+20^*$). This means that, trying other moves from $A$ as he goes down the tree, White will never agree to a score less than or equal to 20 (since the move $AB$ provides him with this score).

The score $+20$ is the guaranteed score of the position $A$ (for White), or, in other words, its lower bound. When moving down the tree, the guaranteed scores are each time transferred to the corresponding position through one level.

Now let White, continuing the search, try the move $AC$, and Black respond with the move $CD$. For vertex $D$, its estimate has so far been written as $+20$, transferred from $A$. If now the score brought to the position $D$ is no more than 20, this will mean the following:

*) Here and in what follows, the score is understood from White’s point of view (for Black, the score of this position is 20).

1. The move $AC$ is no better than $AB$ (if Black answers $CD$ correctly, White's score will be no higher than with the move $AB$). We will call the move $AC$ bad.

2. The move $CD$ determines the move $AC$ (in the sense indicated). We will call it closing.

3. Black's other moves from position $C$ need not be considered.

In this case, a countdown is said to occur, and moves $CE$ and $CF$ are no longer studied.

It is important to note that in the descriptive method, the order in which moves are considered is more important. Let's assume that the moves $CE$ and $CF$ were tried first and only then $CD$. If one of the moves $CE$ and $CF$ had not turned out to be closing, then we would have wasted our time trying out unnecessary options.

Let us assume that the lower bound of the position $C$ is equal to +30. This means that in the future the search will only consider those positions whose estimates are in the interval ]20, 30[.

Let the score of the position $D$ brought by the spiz turn out to be equal to 25. Then the move $CD$ is called improving, the guaranteed score of the position $C$ becomes equal to 25, Black continues the search with the move $CE$ and will carry it out within the limits ]20, 25[.

There are subsequent countdowns that improve the move. The moves $CE$ and $CF$ can further improve the score for Black or even prove to be a closing move.

⟦folio 16⟧

In any case, the search is reduced if the best move is tried first.

Finally, if the score of position $D$ turns out to be at least 30, then move $CD$ will be bad. Black will continue the search with $CE$ within the same boundaries. In the case when all moves from vertex $C$ turn out to be flat, White's move $AC$ becomes closing, and Black will have to change the move that led to position $A$.

In the example considered, the boundaries were obtained directly from the search as minimum estimates. However, when we are just starting to search, there are no boundaries yet or they can be considered endless. In this case, one for the first time before the final position, the program will even tolerate the loss of the queen. The best move will eventually be found, but at the cost of considering a huge number of endless options.

To avoid this, it is common to set some boundaries at the beginning of the search. They can be obtained in different ways, for example by checking a shallow search or using some kind of warant formation (see below). It is only important that the original boundaries turn out to be more accurate or less reliable.

In the event that we failed with the boundaries and the estimate obtained as a result of the search did not fall into them, we have to move the boundaries in accordance with the search side. Repetition is mandatory if the search takes us to the lower limit - all moves within the established limits “lose.” Shifting the boundaries is necessary here to select fewer of the zolls. If the score turns out to be equal to the upper limit and at the same time the “winning” move (leading to this limit) is the only one, then it will be the best, although its true strength is unknown to us. Shifting the boundaries to the right and re-searching occurs only if there are winning competing moves.

The described algorithm is usually called the $\alpha$-β-procedure, referring to the designation of the faces $] \alpha, \beta]$. The effectiveness of this algorithm depends entirely on the quality of the ordering of moves in the search. So, if the best moves get through first, then there is a general lack of looking at only about $\sqrt{n}$ positions, where $n$ is the full volume of the search tree.

$2^\circ$. Forced version. When we talked about the evaluation function, we noted that it takes into account only the statistical properties of the position and therefore it can be trusted only in relatively calm situations in which one of the parties cannot change the material correspondence of forces to its advantage with close moves. If we process the calculation purely mechanically when the maximum depth of the search is reached, then it may turn out that the side with the right to move wins a piece or even declares checkmate.

To avoid these scoring errors, various heuristics have been invented to make better use of the scoring function. However, one of these methods is the “forced version” or abbreviated as PV. Implemented as a subroutine, the PV is used by the main program at various points in the game and for various purposes, but its main purpose is to obtain a reliable estimate for the final positions of the search tree.

PV is a non-rejective search scheme with its own rules for selecting candidate moves and its own heuristic. Valid moves in PV are captures, transformations, checks and responses to checks, that is, moves that can exist in a situation on the board. The search is carried out within certain pre-established boundaries. The main idea of ​​the PV is the following: the side that has the right to move and is not in check can evaluate the position that has arisen and give it this statistical estimate. It immediately follows that in PV it is reasonable to consider if the best move is tried first.

⟦folio 17⟧

Fig. 4. Bogolyubov-Capablanca (New York, 1924).

Not all are taken, but only those that retain material at least to the level of their lower limit.

If he means human and machine collaborators, then already knowing the result of the PV in a given position would greatly help the chess player. Often, non-obvious combinations take place in the direction of a pure forced warant. Let's take an example from the game of famous grandmasters (Fig. 4).

Black in this position played: 1...K:d4!, and after 2. cd R8:c5! Bogolyubov did it, since on 3. dc the solution is 3...Q:c5+ and 4...R:c1.. A program using FV would have found this combination even with a calculation depth of one half-move.

FV was first implemented as a program in 1962 in one of the early versions of Kansa. Currently, it is actively used by many chess programs.

3°. The order of the distance of moves in a position. Let us now dwell on those methods that allow us to achieve high-quality ordering of moves in positions of the search tree. As shown above, this issue is critical to the running time of a chess program.

The moves from the root of the tree should be ordered more accurately. This will contribute to the occurrence of maximum clippings during the search process. For this purpose, after each of these moves, a PV is applied, which brings the score of the move.

At deeper levels of search, the means for diagnosing ride quality are more varied. If it is possible to take an unprotected piece or eat a strong piece with a weak piece, then such candidate moves are considered first. These are the so-called profitable bribes. Among the first are also the absence of pieces when they are attacked (the “attacked” rule). It is effective to capture an opponent's piece that has just made a move. All other things being equal, it is more profitable to start with moves to unbeaten squares, etc.

All these messages serve for a prior assessment of the progress. They are certainly useful, although somewhat abstract. The “best moves service” comes to the rescue, allowing you to take into account the dynamics of the position. This help service remembers those moves that turned out to be the best (that is, closing or improving) at various levels during the search. These moves are then proposed as candidate moves in new emerging positions. Interestingly, when Kansa first used the “best moves service”, the machine's operating time was reduced by more than 10 times.

In conclusion, it should be noted that many interesting problems remained unconsidered by us. In addition, one should not think that the ideas and methods used in programming a chess game described in this article are the only possible ones. Thus, the former world champion, Doctor of Technical Sciences M. M. Botvinnik, who is currently working on chess programming issues, follows a different path *). The future will show which of the ways to solve this problem is more fruitful.

*) See the book by M. M. Botvinnik “From Chess to the Machine” (M., “Physical Culture and Sports”, 1979).
