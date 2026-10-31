---
id: 2019-4-gribok-mudretsyi-kolpaki-i-arifmetika-konechnyih-poley-1b1683a6
issue: kvant_2019_4
year: 2019
number: "4"
title: Sages, caps and the arithmetic of finite fields
authors:
  - Грибок С. В.
rubric: osnovnye-stati
page_first: 7
page_last: 9
page_labels: 6-7
tag: D2QW
lang: en
source: kvant_digital
extraction: native
content_sha256: 816631cba55cc292db6af4cfd14e54bd835a12208f170fe58c6a5d05b5d81525
prompt_sha256: draft-1
translated_from: content/ru/2019/04/articles/01_gribok-mudretsyi-kolpaki-i-arifmetika-konechnyih-poley-1b1683a6.md
source_content_sha256: fc085d37a9c4d2b3038343c4ee03fafcfd73b9fdf1fd7959ef9e92f95ff49f1e
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio none⟧

Sages, caps and the arithmetic of finite fields

S.GRIBOK

Test 1. Two out of three. About binary sets, cubes and balls

Once upon a time, King Shahryar ruled in Persia. All day long the king feasted, hunted and had fun, arranging cruel trials for his courtiers. While the king spent his time in idleness, the council of court sages was engaged in solving all the complicated affairs of state and governing the country. One day the king decided to check whether his court sages were really that smart. He ordered the three wise men to be called and announced the conditions of the test that awaited them tomorrow. Each sage will have a white or black cap placed on his head. Everyone will be able to see other people's caps, but will not know what color their cap is. The executioner will decide which cap to put on each sage by tossing a coin three times, one side of which is white and the other black. Then each wise man will be given a quill and a piece of parchment on which he will write what color his cap is. If at least two wise men answer correctly, everyone will be rewarded, but if at least two are wrong, all wise men will be executed. It is prohibited to give any signs to each other during the test. The night before the test, the wise men have the opportunity to come to an agreement and develop a unified strategy. How should wise men act to maximize their chances of staying alive? Let us prove that there is no way to make the probability of winning for the wise men greater than 3 4.

DOI: https://doi.org/10.4213/kvant20190402

⟦column⟧

Let the test be repeated many times. Let the sages manage to develop a method that allows two out of three sages to guess the colors of their caps on average more often than in three out of four games. Thus, out of 12 answers from the sages over the course of four games, on average more than 6 answers will be correct (6 3 2). But this is impossible, since every wise man guesses the color of his cap in one case out of two, which means that out of 12 answers, on average, exactly 6 answers are correct. In total there are 8 different options for distributing the caps between the three sages. The probability of winning 3 4 means that the wise men win in six options and lose in two out of eight options. Let's try to build a strategy for the wise men that will allow them to win in six out of eight cases. For convenience of recording sets of caps, we will use the number 0 to denote a white cap, and the number 1 to denote a black cap. For example, the entry 001 would mean that the first two wise men received white caps, and the third wise man received a black cap. Let's choose two “deadly” sets of caps that the wise men will not be able to guess. For example, let's say the deadly sets are 000 and 111. We want the sages to be able to win on all other sets. How to achieve this? First of all, note that for any non-lethal set of caps, one of the wise men sees that the neighbors have caps of the same color. The strategy of this sage is clear: if you see two caps of the same color on your neighbors, call the other color. Ouch-

⟦folio 6⟧

KVANT 2019/№4

Apparently, for any non-lethal set this strategy works and is guaranteed to allow the sage to guess the color of his cap. Let's deal with the remaining two wise men, each of whom sees caps of different colors on their neighbors. To win, it is enough for at least one of these wise men to name the color of his cap correctly. Note also that their own caps are the same color. This means that if one of the wise men names white and the other black, then one will definitely guess correctly. But how do wise men know what color to call if they both see the same picture - their neighbors are wearing caps of different colors? The point is that if we look closely, we will notice that there are some differences in what these two wise men see. For example, let the wise men stand in a circle. Then one of the two wise men sees a white cap on the left and a black one on the right. Another sage sees a different picture: on the left is a black cap, and on the right is white. Now it’s easy to come up with a rule that will allow one of these wise men to guess the color of his cap: if you see caps of different colors on your neighbors, name the color that you see on the right (note that the “mirror-symmetrical” rule also works: if you see caps of different colors on your neighbors, then name the color that you see on the left). So, the problem is solved, but let's not rush. First, let us consider whether it is possible to simplify the rules that wise men must follow. It is not difficult to guess that the two rules we found can be reformulated as one simple rule: name NOT the color that you see on the neighbor on the left. Secondly, let us construct a geometric interpretation of the three-cap problem. It is convenient to imagine many options for distributing caps in the form of a cube (Fig.1). Each set of caps corresponds to one of the vertices of the cube. If two sets of caps differ only in the color of one cap (such sets are called

⟦column⟧

⟦figure⟧

Fig. 1

neighboring), they are located at vertices connected by an edge. Let us now complete two balls, the centers of which are at the death points 000 and 111, and the radii are equal to the edge of the cube. Each ball covers four points of the cube. Each point of the cube is either on the surface or in the center of one of the balls. In such cases, they say that a “covering of the cube with non-intersecting balls” has been constructed. If the point is in the center of the ball, the sages will not guess the colors of their caps, but if the point lies on the surface of the ball, most of the sages will name their colors correctly.

Test 2. Four out of seven. About polynomials and code sets

The next day, seven wise men were brought to the king. The ruler announced that another test would take place today. The rules are the same as yesterday: each sage will put a white or black cap on his head, after which each sage must write down what color he thinks the cap is on his head. If at least four wise men answer correctly, everyone will be rewarded, but if at least four are wrong, everyone will be executed. How should the wise men act in order to minimize the likelihood of execution this time? Let's start again with a lower estimate of the probability of execution. Let's prove that it doesn't exist

⟦folio 7⟧

SAGES,

CAPS

AND

ARITHMETIC

a method that allows you to make the probability of winning greater than 7 8. The proof is the same as in the first problem, up to the replacement of numbers. Let the sages manage to develop a method that allows four out of seven sages to guess the colors of their caps on average more often than in seven out of eight games. Thus, out of 56 answers from the sages over the course of eight games, on average more than 28 answers will be correct (28 7 4). But this is impossible, since every wise man guesses the color of his cap in one case out of two, which means that out of 56 answers, on average, exactly 28 answers are correct. There are a total of 128 different options for distributing the caps among the seven sages. The probability of winning 7 8 means that the wise men win in 112 options, and lose in 16 options out of 128. By analogy with the first task, now we need to somehow select 16 deadly sets. But how to do this? In the previous problem, we placed all sets of three caps at the vertices of a cube. Now there are seven caps, which means that many sets correspond to the vertices of the seven-dimensional hypercube. It is difficult to imagine this figure, but this does not prevent us from speculating about its properties. Note that since there are seven wise men, for each set of caps there are seven neighboring sets, therefore, each 7-dimensional ball of unit radius centered at the vertex of an N-dimensional cube covers exactly 8 points of the cube. Since 128 16 8, then theoretically, to cover all 128 vertices of a 7-dimensional cube, sixteen disjoint 7-dimensional balls should be enough, in the center of each of which we will place a deadly set. But how to do this in practice? We will call the distance between two sets the number of positions in which these sets differ. The distance between adjacent sets is equal to one. Now let us formulate the properties of the set of deadly sets that we want to construct.

FINAL

FIELDS

⟦column⟧

1) There are 16 sets in total. 2) The distance between any two sets is at least three (so that the balls in the centers of which there are deadly sets do not intersect). 3) The cyclic shift of a death set is also a death set (otherwise different sages will have to use different strategies). Intuitively, it is clear that lethal sets must be uniformly distributed over the set of all possible sets. We can try to imagine each set of caps as a binary representation of some integer from 0 to 127, and the set of death sets as elements of some arithmetic progression, but traditional arithmetic operations are poorly suited to provide the properties 2 and 3 we need. Since traditional arithmetic does not suit us, we will use “non-traditional” arithmetic, namely, the so-called arithmetic of polynomials over the field {0,1}. First of all, we define the operation of adding two sets of caps. The sum of two sets of length n is a set of length n, each element of which is equal to the modulo 2 sum of the corresponding elements of the original sets. Let us recall the rules for addition modulo 2: 0 + 0 = 0, 0 + 1 = 1, 1 + 0 = 1, 1 + 1 = 0. Example: 00110101 + 11110000 = 11000101. To define the operations of multiplication and division of sets of caps, it is convenient to write sets in the form of polynomials. The set of caps $v_{0}, v_{1}, v_{2},^{…}, v n_{1}$ can be written as a polynomial in the variable $х:_{0}^{v} v_{1}$ $x_{2}^{v}$ $x^{2} …^{v} n_{1}$ $x^{n} 1$. Thus, the set of tuples of length n is equivalent to the set of polynomials whose degrees do not exceed n – 1. Now we define the product of two tuples as the set corresponding to the polynomial
