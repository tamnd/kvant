---
id: 1981-11-vertgeym-igryi-s-kvadratichnyimi-funktsiyami-18187e5a
issue: kvant_1981_11
year: 1981
number: "11"
title: Games with quadratic functions
authors:
  - Вертгейм Б. А.
rubric: osnovnye-stati
page_first: 8
page_last: 11
page_labels: 6-9
tag: Q6FW
lang: en
source: kvant_digital
extraction: vision
content_sha256: eadd4af08f856518708bedef6485af7bcc70506af8fadf1f5eb51e1f075c146e
prompt_sha256: draft-1
translated_from: content/ru/1981/11/articles/03_vertgeym-igryi-s-kvadratichnyimi-funktsiyami-18187e5a.md
source_content_sha256: 234640e8479dcd5911970f8958c7e0c0f7d4f54c3d3228955b673630c518409e
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 6⟧

B. Vergeem

or to your right. Their skill is reflected in the table *): if the player

Games
with square functions

Is it possible to study mathematics through a game? It turns out that it is possible, since in mathematics there are many problems that describe “game situations”.

We will deal with games related to finding the most and most values ​​of functions. The art of such search is important in many problems of economics, military affairs, biology, sports,...

Decisive ten equal meters

We are on the football field. Player A and goalkeeper B prepare for a series of 10 equal-meter shots. The player will go right or left; the goalkeeper, trying to guess the direction of the shot, prepares to jump to the left

bet to the right (this is his strategy No. 1), and the goalkeeper prepares to jump to his left (this is strategy No. 1 for B), then on average there will be 7 goals out of 10; if B was preparing to jump to the right, then 10 balls are thrown, etc.

Both players will alternate their choices randomly. If each of them chooses each of their strategies about half the time (as they say, with a probability of 1/2), then on average (7 + 10 + 9 + 6): 4 = 8 goals will be scored.

If A applies his first strategy with probability 0.6 (in the 60% case), and the second with probability 0.4 (in the 40% case),

*) In game theory and economics, such tables are called pay matrices.

⟦folio 7⟧

and the goalkeeper uses his first strategy with a probability of 0.8, and the second with a probability of 0.2, then on average $(7 \cdot 0,6 + 9 \cdot 0,4) \times 0,8 + (10 \cdot 0,6 + 6 \cdot 0,4) \cdot 0,2 = 7,92$ goals will be scored, which is less than 8. Of course, it makes no sense to say that in this particular series 7.92 goals will be scored. What is meant here is that with multiple repetitions of series that satisfy the set conditions, the average number of goals scored (the ratio of the total number of goals to the number of series) will be close to 7.92.

In general, let $A$ choose its first and second strategies with probabilities $x$ and $1-x$ ($0 \leq x \leq 1$), and $B$ with probabilities $y$ and $1-y$ ($0 \leq y \leq 1$). In this case, the numbers $x$ and $y$ are said to determine the players' mixed strategies. then the average number of goals scored is $m = (7x + 9(1-x))y + (10x + 6(1-x)) \times (1-y) = -6xy + 4x + 3y + 6$. (*)

The question naturally arises: what are the highest values ​​of $x$ for $A$, $y$ for $B$? The best value $x^*$ for $A$, placed, should guarantee the minimum number of goals scored (on average), regardless of the goalkeeper's tactics. The best value of $y^*$ for $B$ should guarantee the minimum number of goals scored (on average), regardless of the former penalty shooter's strategy.

It turns out (you will see this by solving Exercise 1), $x^* = 1/2$, $y^* = 2/3$; in this case, (on average) $m^* = 8$ goals will be scored. It is easy to check (be sure to do this!) that if at least one of the players adheres to the specified “best” strategy, then, regardless of the strategy of the other, $m^* = 8$ goals will be scored (on average). If one of the players does not follow the specified strategy, then he can no longer guarantee anything - the result will depend on the actions of the rule.

So, if the goalkeeper jumps to the right and to the left equally often (that is, $y = 1/2$), and the player always stays in the right corner ($x = 0$), then fewer goals will be scored on average ($m = 7,5$). But if the player $A$ is hittee, he will always be the left corner ($x = 1$) and then will score more often ($m = 8,5$).

And now let’s take a break from football, assumptions and let’s deal with “simple” functions, without restrictions on $x$ and $y$ - this will make the first steps easier.

Win, lose, draw

Let two players play the following game: $A$ chooses the real number $x$, $B$ chooses the number $y$, and each makes his own choice without knowing the choice of his opponent. Both numbers are communicated to fate, after which, according to the rules known in advance to the players, the winnings of the first $v = f(x, y)$, equal to the loss of the second, are calculated; more precisely, at $v > 0$ A wins against $B$ value $v$, at $v < 0$ A loses $B$ value $|v|$; if $v = 0$, then the game is a draw; the symbol $f(x, y)$ means that $v$ is a given function of two variables ($x, y$).

For example, let the rule for calculating winnings in a game be:

$$v = y^2 - x^2.$$

Try playing rule (1) several times. After several “games,” the player will notice that it is better for each of them to win zero values: with $x = y = 0$ it turns out to be a draw, and it is disadvantageous for either player to deviate from this choice, even knowing the opponent’s choice.

Indeed, since for $x = 0$ $v = y^2$, the best response of player $B$ is to choose $y = 0$. Likewise, with $y = 0$ $v = -x^2$ and the best move $A$ is $x = 0$.

It is now clear that playing with the plugin function $v = y^2 - x^2$ is not interesting: a draw is guaranteed for both players. It is more difficult and more interesting to play with the following plugin function:

$$v = y^2 - x^2 + 8x - 10y + 9.$$

In this case, are there numbers $x$ and $y$ that can be recommended to players and from which it will be “costly” for them to deviate?

A simple key to the game (2) is given by the expansion

⟦folio 8⟧

Fig. 1.

$$v = (9 - x - y)(x - y + 1).$$

Having created a system of equations
$$\begin{cases} 9 - x - y = 0, \\ x - y + 1 = 0, \end{cases}$$

having a unique solution $x^* = 4, y^* = 5$, we conclude that game (2) has a draw outcome $v^* = v(x^*, y^*) = 0$ for $x = x^* = 4, y = y^* = 5$.

The geometric explanation here is as follows (Fig. 1): the pair of numbers $(x^*; y^*) \in R^2$ is determined by the point of intersection of the lines corresponding to the equation of the system; if a point with coordinates $(x; y)$ lies on one of them, then $v = 0$; for points lying inside the angles formed on shimmy straight lines, the value $v$ has the sign indicated at figure. This figure is supplemented by the following calculations and reasoning; if $x = 4$, then $v = (5 - y)^2 \geq 0$; $v_{\min} = 0$ at $y = 5$ (at vertical points $x = 4$ always $v \geq 0$); if $y = 5$, then $v = -(x - 4)^2 \leq 0$; $v_{\max} = 0$ at $x = 4$ (along the horizontal $y = 5$ we have $v \leq 0$).

Thus, if $A$ chooses $x = 4$, then player $B$ with any choice other than $y = 5$ will lose. Likewise, if $A$ chooses $x \neq 4$, player $B$ wins by taking $y = 5$.

So, the first player has a move, which he certainly won’t lose. The second player has the same move. Therefore, in this game, the one who risks playing not “according to theory” will lose (unless, of course, his opponent also takes the risk of abandoning the theory).

Let us give as an example the results of the heel of the games in our game (in each triple the first number is $x$, the second is $y$, the third is $v$): $(0,0,9), (0,7, -12), (4,7,4), (4,5,0), (5,5, -1)$.

Studying these games suggests another solution (unfortunately, not always suitable). We try to reason for the first player: “If $B$ chooses $y = y_0$, then we get a square triangle $v(x, y_0) = (9 - y_0 - x)(x - y_0 + 1)$ with respect to $x$, which I must make as large as possible by choosing suitable $x$; but this one has a triangle maximum at $x = 4$, so I want $x = 4!$. Reasoning in a similar way, the second player will ensure himself a minimal loser $y = 5$ (for any move $x = x_0$ of the drive).

Saddle point and game solution

We have seen that in a game with function (2) each player can guarantee himself against loss, since the ability to find a pair of numbers (4:5) such that $f(4,5) = 0$ and for all other $x$ and $y$ values ​​of the function $f$ satisfy the inequality
$$f(x, 5) \leq f(4, 5) \leq f(4, y).$$

From this we can see that the first player, choosing $x = 4$, in any case, does not lose (this follows from the last inequality), just as the second player does not lose, choosing $y = 5$.

Let's give a general definition.

Definition of a saddle point.

Let a function $f$ be given, defined on some set $G$ of points in the plane. The point $(x^*; y^*) \in G$ is called the saddle point of the function $f$ or the equilibrium point if at $(x, y^*) \in G, (x^*, y) \in G,$
$$f(x, y^*) \leq f(x^*, y^*) \leq f(x^*, y).$$

From these inequalities it follows that $\max f(x, y^*) = f(x^*, y^*) =$
$$= \min f(x^*, y)$$
(on the left side there is a maximum in the variable $x$ for the functionin $y = y^*$, on the right side there is a minimum in $y$ for the functionin $x = x^*$).

In theory, the player saddle point $(x^*; y^*)$ is often called the solution to the game (with a payoff function $v = f(x, y)$), the number $v^* = f(x^*, y^*)$ is called the cost of the game, and the numbers $x^*, y^*$ are the optimal strategies of the first and second players, respectively.

⟦folio 9⟧

Fig. 2.

Tourists and climbers

Tourists, wanting to go from valley $D_1$ to valley $D_2$, go through the pass (saddle) - while the maximum height on the way from $D_1$ to $D_2$ (Fig. 2) turns out to be minimal compared to all close routes that do not pass through the saddle. Climbers, wanting to make a traverse from peak $V_1$ to peak $V_2$, pass the same saddle for a different reason - so as not to “lose altitude,” that is, so that the minimum height on the way from $V_1$ to $V_2$ is as high as possible.

Figure 1 is shown on the map, where the height of the pass is taken as zero, and $x$ and $y$ are the chisels and latitude. We will consider straight lines parallel to the axes as path possibilities for tourists and climbers. Like routes in the mountains, the main straight lines of Figure 1 ($y=5$ and $x=4$) are highlighted by the fact that
$$f(x^*, y^*) = \min_{y} \max_{x} f(x, y) = \max_{x} \min_{y} f(x, y),$$
and this is very useful when analyzing the game. Here max $f(x, y)$ is the maximum value of $f$ for a given $y$ and variable $x$, that is, this is finding the outcome for $B$ for a selected value $y$; Obviously, this value is minimal at $y=5$. Interpret the choice $x=4$ for player $A$ in a similar way.

Now consider a game with a payoff function $v=x^2-y^2$, which has no saddle point (check this). Analysis of a game with such a function becomes very complicated. In this example, opponents will be interested in choosing the largest numbers to achieve. If we introduce restrictions on the variables $x$ and $y$ of the form $|x| \leq a, |y| \leq b$, which is often encountered in practice, 4 saddle points will appear: $x^* = \pm a, y^* = \pm b, (v^* = a^2 - b^2)$.

However, with this kind of restriction, the saddle point may not appear (see Exercise 3).

Solution to a game with a square payoff function

The result of our theoretical consideration is summed up by the following theorem. Let a price with a payment function be given
$$v = ax^2 + 2bxy + cy^2 + 2px + 2qy + r.$$
This function has a saddle point and a cer is a solution in the following seven cases and only in them:
1) $a < 0, c > 0$;
2) $a < 0, c = 0 \neq b$;
3) $a < 0, c = b = q = 0$;
4) $a = 0 \neq b, c > 0$;
5) $a = b = p = 0, c > 0$;
6) $a = c = 0, b \neq 0$;
7) $a = b = c = p = q = 0$.

A saddle point is a solution to a system of equations
$$\begin{cases} ax + by + p = 0, \\ bx + cy + q = 0. \end{cases}$$

This solution is $(x^*, y^*)$ in all these cases except cer, reader: an analysis of the previous specific examples will help him.

Exercises

1. a) Consider the game with payoff function $m = 6 + 4x + 3y(1-2x)$ and find the value $x$ for which $m$ does not depend on $y$, as well as the value $y$ for which $m$ does not depend on $x$. Does this pair of values ​​provide a solution to the game?

2. Find a solution and prices game with the following payment functions:
a) $v = -x^2 + 6xy + y^2 - 10x - 10y + 15$;
b) $v = (x + y - a)(y - x - b)$;
c) $v = 10\ln x - x^2 + 2xy + y^2 + 10x - 8y - 40, x > 0$;
d) $v = k(\sqrt{x}, -\sqrt{y}) + \sqrt{a-x} - \sqrt{b-y}$;
d) $v = k(-x^2 + 2pxy + y^2) - x_0^2 - 2px_0y + y_0^2$, where $x_0 = a - x, y_0 = b - x$;
