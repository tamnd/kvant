---
id: 2009-6-shen-veroyatnostnyie-dokazatelstva-86d5c3b9
issue: kvant_2009_6
year: 2009
number: "6"
title: Probabilistic evidence
authors:
  - Шень А. Х.
rubric: osnovnye-stati
page_first: 13
page_last: 27
page_labels: 11, 13, 14, 25
tag: NKA5
lang: en
source: kvant_digital
extraction: native
content_sha256: c072ac9a30bb7140671e1dc57665d1b8cf3f5c158c39318d01de81c1bb273c72
prompt_sha256: draft-1
translated_from: content/ru/2009/06/articles/02_shen-veroyatnostnyie-dokazatelstva-86d5c3b9.md
source_content_sha256: d33668184ca25de70b8ab9e7ebee22c0d5c88f96a070920737013d3ea42e8e99
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 11⟧

Probabilistic evidence

A.SHEN

Inequalities and estimates Let's start with a very simple problem. 1. 10 numbers are written on the board. The sum of any two of them is not less than 5. Prove that the sum of all numbers is not less than 25. ⊳ There’s not much to prove here: let’s divide the numbers into five pairs. In each pair the sum is not less than 5, the total is 25. ⊲

Now a little more difficult task. 2. 9 numbers are written on the board. The sum of any two of them is not less than 5. Prove that the sum of all numbers is not less than 22.5. (If all numbers are 2.5, then the result is 22.5.) ⊳ Using similar reasoning to the previous problem, you can choose four pairs, and one number will remain. In each pair the sum is not less than 5, a total of 20. If we knew that the number left without a pair is not less than 2.5, then we would get the required one. But we cannot guarantee this. Let's say, if one of the numbers is zero and the others are 5, then the sum of any two will be at least 5 (namely, 5 or 10). In this case, zero may turn out to be unpaired. You've probably already figured out how to complete the argument. Partitioning into pairs is in our hands, and we can leave any of the numbers unpaired. In any pair at least one of the numbers is 2.5 or greater. Us

⟦column⟧

in each of which the sum is not less than 5. The total is at least 3 ◊ 5 + ( 5 3 ) = 50 3. ⊲

In the two previous problems there was only one number left. What happens if there are two left? 4. There are 11 numbers written on the board. The sum of any three of them is not less than 5. Prove that the sum of all numbers is not less than 55/3. You can solve this problem similarly to the previous ones (see problem 14 and instructions for it). But we will give another solution that generalizes to any quantities. ⊳ Let’s denote our numbers $a_{1}$, … $, a_{11}$ and write them in a circle. The sum of any three neighbors is not less than 5 (by condition):

$a_{1} + a_{2} + a_{3} \ge 5,$

$a_{2} + a_{3} + a_{4} \ge 5,$

… $a_{9} + a_{10} + a_{11} \ge 5,$

$a_{10} + a_{11} + a_{1} \ge 5, a_{11} + a_{1} + a_{2} \ge 5.$

Let's add up these eleven inequalities. Each number appears three times (included in three triplets), so it turns out

$3 ( a_{1} + a_{2} +^{…} + a_{11} ) \ge 55$, from which the required follows. ⊲

Probability and expectation is enough to know that at least one of the numbers is like this - you can leave this particular number unpaired, and everything will work out. ⊲ Let's complicate the problem a little more. 3. There are 10 numbers written on the board. The sum of any three of them is not less than 5. Prove that the sum of all numbers is not less than 50/3. ⊳ We use the same technique: in any three numbers the greater is 5/3 or more (otherwise all three numbers are less than 5/3, and the sum is less than 5). Let's take one of these numbers (not less than 5/3), three threes will remain,

Now we will consider another solution to the last problem - in the language of probability theory. Let there be 11 balls in a box (or, as they like to say in probability theory, in an urn) with the numbers $a_{1}, a_{2}$, ... $, a_{11}$ written on them. We take out one of the balls without looking, and they give us as many rubles as are written on it. How much will we win on average per game if we play many times? We mean that each time the ball is removed, it is returned to the urn and its contents are mixed. It’s easy to imagine that the answer here is -

⟦folio 13⟧

PROBABILISTIC

way. With a large number of trials, the proportion of cases where vertex A falls into the spot (the probability of the event “A is black”) is 1/10, since vertex A is evenly distributed over the entire sphere. For the same reasons, vertex B turns out to be black 10% of the time, and the same can be said about any of the 8 vertices. This means that there remains at least 20% = 100% – 80% of cases in which all vertices are white (maybe more due to cases where several vertices are black). Therefore, the cube can be inscribed in the required way. ⊲ In fact, here we are seriously cheating and sweeping the main part of the argument under the rug: why the words “randomly inscribed cube” make sense and why the vertex is evenly distributed over the sphere. Intuitively, this seems plausible and can indeed be rigorously justified (although I am not aware of any solution to this problem in the school curriculum).

Random coloring pages

Let's consider an arbitrary graph - several points (vertices) connected by lines (edges). Let's color the vertices of the graph in two colors (say, black and white). We'll call an edge multi-colored if it (as you guessed) connects vertices of different colors. The number of multi-colored ribs depends on the coloring. If we want to make this number minimal, there is nothing simpler - just paint all the vertices the same color. What happens if we want to make it maximum (for a given graph)? The answer depends on the graph, but it turns out that you can always guarantee at least half of the edges are different colors. 8. Prove that in an arbitrary graph it is possible to color the vertices in two colors so that at least half of the edges are different colors. ⊳ We will color the vertices randomly (for a graph with n vertices, $2^{n}$ colorings are possible, and we consider all of them equally probable). For each coloring, we count how many edges will be multi-colored. This is, as they say, a “random variable” - it depends on the choice of coloring. What is its mathematical expectation (the average value over a large number of trials)? In other words, let a coin be thrown at each vertex of the graph (independently of other vertices, so that all combinations are equally likely), and on each edge there is a player who receives a ruble if the edge turns out to be of different colors (coins at its ends will fall out differently). How much will players earn on average per game? Each player wins, on average, half of the games (there are four possible combinations of colors at the ends of the edge, and in two of them it is multi-colored). This means that each player on average wins fifty rubles per game, and the entire team wins on average V/2 rubles, where V is the number of edges.

PROOF

⟦column⟧

It obviously follows that there are colorings when at least half of the edges are different colors (otherwise the team would win less than V/2 in each game, and the average would also be less than V/2). ⊲ In fact, this statement has a simple constructive proof (see problem 19).

Random projections

In this section, we will apply probabilistic considerations to solve such a problem. 9. A convex figure is drawn on a plane, bounded by a curve of length L. Prove that its diameter, i.e. the maximum distance between two of its points is not less than $L \pi$. The appearance of the number $\pi$ here is not accidental: the inequality of the problem turns into an equality for the case of a circle with diameter $D = L \pi$. ⊳ We will prove a stronger statement: the average length of the projection of our figure onto a random direction is $L \pi$. (We draw a line in a randomly chosen direction, and then from each point of the figure we lower a perpendicular to this line. The result is a segment - the projection of the figure onto the line.) From this statement it follows that there is a direction, the projection onto which has a length of at least $L \pi$ (the average value cannot be greater than all). And then the points of the figure that fall at the ends of the projection are at the same or greater distance (the inclined one is longer than the perpendicular). How to prove what was promised? Consider a curve bounding a figure. The projection of a figure is the same as the projection of its boundary. Let's break this curve into many very small parts - so small that each of them can be considered a segment. Let all these segments be of equal length. The projection of the entire boundary consists of the projections of these segments. More precisely, the double projection of the entire boundary is equal to the sum of the projections of the segments (since they cover it twice - back and forth). This is true for any direction of design - which means that the doubled average length of the projection of a figure is equal to the sum of the average lengths of the projections of each of the segments that make up its boundary. But these segments are of equal length, and therefore the average lengths of their projections are the same (since we are projecting in a random direction, the direction of the segment itself does not matter). This means that the average projection length

⟦folio 14⟧

KVANT 2009/№6

the curve depends only on the number of these segments, i.e. is proportional to the length of the curve, and the proportionality coefficient can be calculated using the example of a circle. ⊲

Two boxes

10. In the Moscow metro you can transport boxes whose sum of dimensions (length, width and height) does not exceed a certain limit. The question arises: is it possible to beat the rules by placing one box inside another? In other words, let one cuboid be entirely contained within another. Can the sum of the internal dimensions be greater than the sum of the external dimensions? ⊳ It turns out that no, but it is not so easy to prove. There are some nice proofs, and one of them uses probabilistic considerations (about the same as in the previous section). We will project the box onto a straight line of a randomly chosen direction (in space). From the picture you can see that the projection of the box consists of the projection of three segments running along its height, length and width. Consequently, the average length of the projection (mathematical expectation) is equal to the sum of the average lengths of the projections of these segments. And the average length of the projection of a segment is proportional to its own length (with some coefficient, it doesn’t matter to us now - with what). Therefore, the average projection length of a box is proportional to the sum of its dimensions. Now imagine two boxes, one inside the other. Whatever line you project them on, the projection of the inner box is always inside the projection of the outer box and therefore has a smaller or equal length. This means that the average lengths of the projections are in the same ratio, and they are proportional to the sum of the measurements. ⊲

Random walk

11. A labyrinth is drawn on a squared piece of notebook paper and there is a robot in it that, following the commands “up”, “down”, “left” and “right”, walks from cell to cell. The walls of the labyrinth go along the sides of the cells; there is no exit from the labyrinth. If, having started to move on command, the robot hits a wall, then it remains in place. We don't know which labyrinth is drawn, but we know the size of the leaf, measured in squares. Prove that it is possible to create a sequence of commands that guarantees that the robot will visit all the cells of the part of the maze that is accessible to it. ⊳ We immediately admit that not only will our reasoning be a pure proof of existence (without presenting a method for constructing such a sequence), but also the length of such a sequence will be astronomical. We will give the robot random commands and see

⟦column⟧

with what probability will he get around the maze? Let the labyrinth have a closed circuit of no more than N steps. Then, for any initial position of the robot, there is some probability that when N random commands are given to it, it will follow exactly this path and go around the maze. It is not less than $4^{-} N$, and the probability

(

) can't get around the maze no more than $1 - 4^{-} N$. The process can be repeated: if we give 2N random commands, then the probability of not getting around the maze is no more

$( 1 - 4 )$ (failure at the first stage occurs in a fraction of $( 1 - 4 )$ cases or less, and in each of them

$- N^{2}$

$- N$ the probability is reduced by the same amount due to the second stage). In general, after Nk random commands the probability of failure (in a given maze with a given initial

(

) k position) no more than $1 - 4^{-} N$. Although the base of the degree is close to one, this number can still be made as small as desired by increasing k. Note that for all mazes on a board of a given size, one common N can be chosen.

(

) k

After this, we take k such that $1 - 4^{-} N$ becomes less than 1/M, where M is the number of different ways to draw a labyrinth and a robot inside it (there are a finite number of them on a piece of paper of a given size). Then for each of the M layout options, the probability of failure is less than 1/M, and therefore, with a positive probability, a sequence of commands of length Nk will be successful for all options. This means that such a successful sequence exists, which is what needed to be proven. ⊲

Incomparable sets

In this section we assume familiarity with the elements of combinatorics (sets, subsets, number of combinations). 12. Let A be a set of 2n elements. We want to select several subsets of the set A, and we require that they be incomparable: none of them should be a subset of the other. What is the maximum number of subsets that can be selected? ⊳ Note that the requirement is satisfied if all selected subsets are the same size (and different). In order for their number to be maximum, it is necessary to take size n, since the number of combinations $C_{2} kn$ for a given n

⟦folio 25⟧

INFORMATION

logical analysis, compare the results of reflections with facts or with analogues from other concepts. Independent thinking is not only an understanding of the essence and foundations of a theory and the scope of its applicability, the ability to draw consequences within its framework for particular cases, etc. It is also necessary to understand that every theory has alternatives, to admit these alternatives, to be ready at any moment to abandon familiar concepts if new facts fit into their framework “with difficulty” (especially when they go beyond these frameworks). Of course, there are concepts whose validity is difficult to doubt. For example, the reality around us with all the processes occurring in it very often demonstrates the inviolability and universality of the following three properties: economy, symmetry and relativity (the last two are, to some extent, special cases of the first). This list may not be exhaustive and needs to be supplemented (this will most likely happen in the future). But be that as it may, it is possible to list a number of provisions that cannot be included in this list of universal concepts, despite the fact that they are considered fundamental. For example, it cannot be taken for granted that an electron on earth and an electron at distances of billions of light years from it have exactly the same rest mass. It is difficult to consider such dimensionless quantities as, for example, the fine atomic structure constant, mass ratios of elementary particles, etc., to be unshakable physical constants. Einstein also doubted their, so to speak, random nature. Either these are mathematical constants (i.e., they are derived within the framework of some theory unknown to us), or they are not constants (i.e., they change in time and (or) in space). The three-dimensionality of the space around us is also one of the postulates of modern theory, but so far there is no reason to consider it unshakable. Let us conclude these examples with this statement: the possibility of something cannot be refuted! In other words, it is impossible to prove in practice that something is impossible. This is one of the attributes of infinity, demonstrating the limitations of logic. When announcing our competition, we deliberately do not specify the tasks for its participants. The content of the answer, as is known, depends on the quality of the question. As they say, a good question is half the answer. Therefore, the formulation of the problem will also be assessed. Moreover, the solution may not be the most successful or even incorrect, but this is compensated by the quality and relevance of the question. Remember that questions, signals coming from the surrounding world (facts, phenomena, etc.) are the fundamental principle, raw materials that still have to be processed in the process of study, turned into a task. And then it is necessary to analyze a clearly defined problem, determine the range of phenomena being described, the area of ​​change and the accuracy of setting parameters for which the solution will be correct, etc. We do not specifically limit competition participants in the selection and formulation of questions. Let it be anything, as long as it has some meaning. There are many problems in modern science and developing technologies. In particular, these are known divergences in quantum theory, the correct definition of the energy-momentum tensor in the general theory of relativity, paradoxes in set theory, self-developing computer programs (including random

⟦column⟧

elections, taking into account the experience of mistakes, etc.). And in everyday life there is a lot that you can try to formalize in the language of mathematics (for example, having discovered a certain similarity, try to apply the laws of gas dynamics to ... analyze the movement of cars on the highway). You can pose a problem from the “what would happen if…” series or come up with a new type of interaction. Or find out what reality would be like if, for example, Planck’s constant turned out to be noticeably larger (or smaller) than the one we know. It is not so hypothetical a problem in which any world constants could be considered non-stationary. For example, the redshift can be explained not only by the retreat of galaxies, but also by the fact that the electron mass or Planck's constant changes over time. So, we don't expect discoveries from you. We are not particularly interested in your erudition, so do not be afraid to be considered ignorant. Most likely, what we expect from you (and what you send to us) would not be accepted by any serious scientific journal. Probably, serious scientists most likely throw such “creativity” into the trash, just as an investigator discards versions that do not justify themselves. But who knows, maybe someday among such “working out” there will be something that was missed before. For example, someone, rummaging through this common basket, will come across unusual ideas that will serve as an impetus for new discoveries. But even if everything goes wrong, we hope to achieve our main goal: to help people who are capable of independent non-standard thinking and search realize themselves. This is how innovation is born. Doubt it! Refute! Offer!

Conditions of the competition

Each participant submits his project to the jury, containing a formulated problem and its solution. (In some cases, the jury is ready to consider problems with unfinished solutions.) The total volume of the project report should be no more than 10 typewritten pages, and all cumbersome calculations should be included in appendices that are an integral part of the report. A printed version of the report (1 copy) must be sent by mail to the editorial office of the journal «Kvant» at the address: 119296 Moscow, Leninsky Prospekt, 64-A, and the electronic report as a separate file must be sent to the editorial office's email address: admin@kvant.info. The title page of the report must contain the following information about the competitor: last name, first name, patronymic; postal address, email address, telephone; data on education, scientific degree (if any). The deadline for accepting applications for participation in the competition is April 15, 2010. The results of the competition will be announced at the end of May 2010. Works, with the consent of their authors and deserving general attention in the opinion of the jury, will be posted on a special website of the New Thought Foundation, indicating those works that have been awarded prizes. The magazine «Kvant», regardless of the results of the work’s participation in the competition, may (in agreement with the author) publish some works that are suitable for the format and ideology of the magazine.
