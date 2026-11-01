---
id: 1987-5-pevzner-luchshee-pari-dlya-prostakov-403d5e87
issue: kvant_1987_5
year: 1987
number: "5"
title: The best bet for simpletons
authors:
  - Певзнер П. А.
rubric: osnovnye-stati
page_first: 6
page_last: 9
page_labels: 4-7
tag: S8TH
lang: en
source: kvant_digital
extraction: vision
content_sha256: bf6514bdd28a56e0b844d1645fb439d871cf8fb7e5820232fa988b3ec3a8ef66
prompt_sha256: draft-1
translated_from: content/ru/1987/05/articles/02_pevzner-luchshee-pari-dlya-prostakov-403d5e87.md
source_content_sha256: 22a0dd0d8284e7362e23f13c57d4009346461f4d7424e5a1044289ff9c2f5d4f
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 4⟧

BEST BET
FOR SIMPLES

Candidate of Physical and Mathematical Sciences
P. A. PEVZNER

- Why don’t you ever play? - The Kid asked Smoke when they once did it at the Deer Rose. Don't you really want to go to the tart table?
“Tuyet,” Smoke replied. “But I know the production statistics, and I need a true approximation.”

Jack London, Smoke Bellew

You probably know the heads-tails game: player A chooses some side of the coin (for example, O - heads), informs B about it; B takes the other side; after that, the coin is tossed... No one doubts that the heads-tails player is a fair way of resolving controversial issues.

In 1974, Martin Gardner, in the article “The Paradox Arising from Non-discriminating Relationships,” introduced Scientific American readers to an “equally pure” game that he called the best pair of spacers. This game is similar to the heads-tails game, only the players conceived words not from one letter, as in the heads-tails game, but from several letters. Martin, player A conceives the words ORO and informs B about it; In turn, it thinks of some word of the same length, for example, OOP. Of course, the chosen words must not be the same, so A reports his choice to B. After this, the players begin tossing a coin, recording the result of each toss. Martin, after 6 tosses with the outcomes: tails, heads, tails, tails, heads, tails, the sequence POPPOP will be recorded. The game stops at the moment when the word chosen by A or B appears at the end of the recorded sequence of letters; in the first case, victory is awarded to A, in the second - to B. Thus, the one whose word appears first wins. Martin, if O appears on the next coin, then A will win, since POPPOP will be written (the words chosen by A in the sequence are highlighted in italics); If P is rolled on the next roll, the game must continue (since POPPOP contains neither OPO nor OOP); Moreover, in the case when O, O, P come up on the 8th, 9th and 10th rolls, B will win - after all, POPPOPOOR will be written.

If you are playing a game of heads and tails, then the choice of heads or tails is a matter of taste, since the words O and P are equal. At first glance, it seems that in the “best bet for simpletons” all words are equal. In 1969, the creator of this game, Walter Penney, discovered the inequality of words. Most mathematicians, having learned the rules of the game, at first refuse to believe it. Nevertheless, this is so - for many pairs of words, the choice of one of them (the most “strong”) provides an advantage to the game that made this choice: this player wins more than his opponent, the game turns out to be unfair. Moreover, there is a formula that allows you to quantify this advantage.

There is almost a detective story associated with this formulation. Gardner cited it in his article, citing the famous English mathematician John Conway, who reported it in a letter (without proof). Gardner admitted that he had no idea how to prove it and "assumed" that it was obtained with the help of matini, like many of Conway's other results.

Conway's reports on this problem have not yet been published, but in the late 70s and early 80s, his formula was independently proven by several mathematicians in different ways. However, all these works used a rather server-side mathematical apparatus, and the formula appeared in them like a trick: after dividing some three-digit expressions into others. It turns out that the creature

⟦folio 5⟧

There is an elementary proof of Convel's formula, a sketch of which is given at the conclusion of this article. Moreover, there is now a simple algorithm for finding the best answer for the second player, although the original replacement algorithm (for words of three letters), proposed in Gardner’s article and owned by his colleague V. Volk, is not inferior in its vagueness and intricacy to the alchemical sieves for obtaining the philosopher’s stone.

But we digress. It remains unclear why words in our game may be unequal.

Which word is stronger?

Let's look at a specific example. Let's imagine that in a game with two-letter words, player A bet on the "tails-tails" combination, and B - on the "heads-tails" combination. Then A will win only if PP comes up on the first two throws: if OP comes up, B wins immediately, if PO or OO comes up, then B also wins, although not immediately; namely, in the last two cases, B will win as soon as P comes up during the next toss (and this will happen someday - with a clean toss, the coin cannot always land on heads). Thus, out of four equally possible hearings (PP, OP, PO, OO), player A will win one (PP), i.e. the chances of y A winning are three times worse than y B.

Regarding the game with two-letter words, it is worth noting that a smart player A will not win the word PP (nor the word OO). He will choose the word OP (or PO), and then his chances of winning and losing are the same, unless, of course, B chooses one of the “weak” words OO or PP (check!).

Fig. 1.

But if we move on to three-letter words, the receiving picture changes. Namely: no matter what three-letter word church A chooses, his opponent B can choose another word that gives him a better chance of winning.

“How is it,” the reader will ask, “why doesn’t player A choose the “strongest” word, since he chooses first? But the point is that there is no strongest word. The situation clearly appears figure 1. All three-letter words made up of the letters O, P are written on it, and the red arrows between the two words indicate which of these two words is stronger (i.e., gives a greater chance of winning).

Look at figure 1: at least one arrow comes out of each word; This means that for any word there is a stronger one, i.e. there is no strongest word. Notice the cycle of words PPO, OPP, OOP and PPO. We see: from the fact that the words X are stronger than Y, and Y is stronger than Z, it does not at all follow that X will be stronger than Z (a situation that often arises in modern sports). Mathematicians say that the attitude of being stronger is non-positive (hence the title of Gardner's paper). Having figure 1 at his disposal, player B, guided by the arrows, can always win for himself a stronger word in response to A’s choice. And then he will win more often than his opponent.

But how much more often? And how does it follow that figure 1 correctly reflects the real situation? We have to answer these questions.

Let's evaluate the chances of winning

Let's return to the two-letter game. We will, as before, assume that the naive player A chose the word A=11, and his cunning opponent B bet on the word B=01 (instead of the letters O, P we now write the numbers 0,1, and the player and the word he chose are denoted by one letter). Sequences of coin tosses in which A wins will be called A-series (the B-series is defined similarly). For example, 11 is the A-series, and 01, 001, 0001, 101, 1001, 10001 are the B-series.

⟦folio 6⟧

Table 1.

Obviously, 11 is the only A-series (i.e., A wins if and only if the first two coin tosses result in 1). Further, it is no less important that the B-series has the form 0...1, or 10...1 (in place of a multi-point one, any number of zero can become).

So, 11 is the only A-series. Let's try to determine the probability*) of winning A, i.e. must merge, in which after two throws the sequence 11 appears.

As a result of one toss, two outcomes are possible (0 and 1) - the probability of each outcome is 1/2. As a result of two throws, there are four possible outcomes, the probability of each is 1/4, therefore the probability of A winning is 1/4 (i.e. A will win in 1/4 of all merges):

$$P(A, B) = P(11) = 1/4$$

($P(A, B)$ denotes the probability of A winning against B, and $P(11)$ the probability of series 11).

$n$ throws can result in $2^n$ (equally possible) outcomes; therefore, the probability of each run of length $n$ is $1/2^n$. In order to calculate the probability of $P(B, A; n)$ winning B in $n$ steps or less, it is necessary to find the probability of each $B$-series of length $\leq n$ and sum these probabilities. We get

$$P(B, A; n) = P(01) + P(001) + \dots$$

$$\dots + P(0...01) + P(101) + P(1001) + \dots$$

* We will not define the concept of probability here - in our country the words “probability” and “proportion of mergers” are synonyms. We refer the reader who wishes to become acquainted with this concept to the book: A. N. Kolmogorov, I. G. Zhurbenko, A. V. Prokorov, Introduction to Probability Theory, M.: Nauka, 1978.

Table 2.

$$\dots + P(10...01) = \left( \frac{1}{4} + \frac{1}{8} + \dots + \frac{1}{2^n} \right) +$$

$$+ \left( \frac{1}{8} + \frac{1}{16} + \dots + \frac{1}{2^n} \right) = \frac{3}{4} - \frac{1}{2^{n-1}}.$$

Consequently, B wins against A in $n$ steps or less with a probability that for large $n$ the estimate is close to 3/4; the probability that no one has won after $n$ tosses is $1/2^{n-1}$ (i.e., nothing is small for large $n$). Going to the preposition in the equality $P(B, A; n) = 3/4 - 1/2^{n-1}$ with $n \to \infty$, we can assume that we will get the probability $P(B, A)$ of winning B from A with “unlimited continuation” of the game:

$$P(B, A) = 3/4.$$

The winning probabilities for arbitrary two-letter words $A$ and $B$ are shown in Table 1 (the number at the intersection of row $B$ and column $A$ gives the probability of B winning against A). This table is not difficult to create.

Let's evaluate the advantage

Based on Table 1, Table 2 is constructed, giving B an advantage over $A$

$$d(B, A) = \frac{P(B, A)}{P(A, B)}.$$

Table 3 shows the benefits for all three-letter words. Using this table, we built the “non-boundary” graph shown in figure 1.

But how to find the numbers in table 3? Unfortunately, formula (1) is of little use for calculations with word length $l \geq 3$. Already for three-letter words $A, B$ finding $P(A, B)$ directly is a very difficult task, and for large $l$ it is hopeless. But here the “magic” helps us out

⟦folio 7⟧

Convel's formula

Convel's formula allows us to find $d(B, A)$ for arbitrary $B$ and $A$ without calculating any probabilities. In order to explain this formula, we need to define the Convel polynomial $K_{XY}(t)$ words $X, Y$.

On figure 2, the words $Y$ are written under the word $X$ six times, with each new word $Y$ shifting one position to the right compared to the previous one (for $n$-letter words, the words $Y$ will be written under $X, n$ times).

Each shift of the word $Y$ will be assigned a number 1 or 0, depending on whether all the letters located under each other in the common positions $X$ and $Y$ coincide or not. The resulting word (of length $n$) from zeros and ones is called the correlation of $X$ and $Y$ and is denoted $\langle XY \rangle$. So, for example, for the 2nd shift $Y$ the general position is the same, therefore in the second line at figure 2 a unit is written - the second letter of the word $\langle XY \rangle$.

In our example
$$\langle XY \rangle = 010011.$$

In general, let $\langle XY \rangle = e_1 \dots e_n$ (where $e_i$ are zeros or ones). Then the Convel polynomial of words $X, Y$ is defined as follows:
$$K_{XY}(t) = e_1 + e_2 t + \dots + e_n t^{n-1}.$$

In our case $K_{XY}(t) = t + t^4 + t^5$. A very strange definition! In any case, it is completely unclear how one could get to him. But it works - Convel’s formula is based on it:

$$d(B, A) = \frac{K_{AA}(1/2) - K_{AB}(1/2)}{K_{BB}(1/2) - K_{BA}(1/2)}.$$

One can understand Gardner when he attributes the choice of this unusual formula to “otherworldly” slams: well, magic, and nothing more!

Without dwelling on the derivation of formula (*), we will show how to use it. First we need to find the correlations $\langle AA \rangle, \langle AB \rangle, \langle BB \rangle, \langle BA \rangle$. Then write four Convel polynomials from them, substitute $t = 1/2$ in each of them and, finally, perform the actions indicated in the right
