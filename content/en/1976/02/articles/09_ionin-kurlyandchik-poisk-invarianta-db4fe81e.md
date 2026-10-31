---
id: 1976-2-ionin-kurlyandchik-poisk-invarianta-db4fe81e
issue: kvant_1976_2
year: 1976
number: "2"
title: Search for an invariant
authors:
  - Ионин Ю. И.
  - Курляндчик Л. Д.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 34
page_last: 37
page_labels: 32-35
tag: JLXY
lang: en
source: kvant_digital
extraction: vision
content_sha256: 24f942da826558ff5212b10349ad8d1997e5f6078e5f2897d95a8765c41e824d
prompt_sha256: draft-1
translated_from: content/ru/1976/02/articles/09_ionin-kurlyandchik-poisk-invarianta-db4fe81e.md
source_content_sha256: 8ae8ecc2445127d6ed1444566debb5cca6c5ba6a4f6d9a0d8effa3e2588d1318
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 32⟧

Yu. Ionin, L. Kurlyandchik

Ponsk
invariant

This article examines problems that are similar in formulation. Each of them talks about certain sets of numbers or signs, and indicates what can be done arbitrarily over them. A reader who carefully studies the article will discover not only the external similarity of the tasks and exercises found in it, but also the general idea on which their solution is based.

Problem 1. Ten planes and fifteen minutes are written on the board. It is allowed to erase any two characters and write them flat together if they are the same, and otherwise. What sign will remain on the board after twenty minutes of operations?

Solution. Let's replace each plane with the number 1, and each minute with the number -1. The permitted operation is then described as follows: take any two numbers and write their product. Therefore, the product of all numbers written on the board remains unchanged. Since at the beginning this product was equal to -1, then at the end the number will remain -1, that is, the sign of minutes.

This reasoning could have been carried out differently. Let us replace all the planes with zeros, and the minutes with ones, and then the sum of the two erased numbers has the same parity as the number written together. Because

At first, the sum of all numbers was odd (it is equal to 15), then the last number remaining on the board will be odd, that is, one, and, therefore, minutes will remain on the board.

Finally, the required task can be obtained, then, as a result of each operation, the number of minutes either does not change or is reduced by two. Since the number of minutes in the problem was odd, there will be minutes left at the end.

Let's analyze all three solutions.

The first solution is based on the invariability of the product of the written numbers, the second - on the invariability of the parity of their sum, and the third - on the invariability of the parity of the number of minutes. In mathematics, the term “invariance” is used together with the word “immutability.” We can say that in each solution we managed to find an invariant: the product of the written numbers, the evenness of the sum, the evenness of the number of minutes. The solution to subsequent problems and exercises is also based on the successful selection of an invariant.

Exercise 1. Several planes and minutes are written on the board. It is allowed to erase any two signs and write them flat together if they are different, and otherwise. Prove that the last sign remaining does not depend on the order in which the pages were randomized.

Problem 2. In a 4x4 table, the signs “+” and “—” are considered as shown in figure 1. It is allowed to change the sign to the opposite at the same time in all cells located in the same row, in the same column or along a straight line parallel to any of the diagonals (in particular, in any corner cell). Is it possible to use these operations to obtain a table that does not contain any minutes?

Solution. Let's replace the planes and minutes with the numbers 1 and -1. As an invariant, we can take the product of the numbers in the cells that

⟦folio 33⟧

krytse are shaded at figure 2, since as a result of the permitted operation it always retains the original value equal to -1.
But this means that among the shaded numbers there will always remain -1, therefore, it is impossible to get a table that does not contain a single minus.

Exercise 2. Solve problem 2 for the table shown in Figures 3-5.

Problem 3*). Several zeros, ones and twos are written on the board. It is allowed to erase two unequal numbers and write together one number that is different from the erased ones (2 instead of 0 and 1, 1 instead of 0 and 2, 0 instead of 1 and 2).
Prove that if as a result of several such operations there is only one digit left on the board, then it does not depend on the order in which the sterems are randomized.

*) This is problem M338 from the “Problem Book «Kvant»”, see «Kvant», 1975, No. 8.

Fig. 1.
Fig. 2.
Fig. 3.

Solution. Let us denote by $x_0, x_1, x_2$ the number of zeros, ones and twos, respectively. By performing the allowed operation once, we will change each of these numbers to 1 and therefore change the parity of all three numbers. When there is one digit left on the board, two of the numbers $x_0, x_1, x_2$ become zero, and the third becomes one. This means that from the very beginning two of these numbers have one parity, and the third has another. Therefore, regardless of the order in which the sterems are arbitrated, at the end unite can only equal one of the numbers $x_0, x_1, x_2$, which from the very beginning is not the same parity as the other two.

From the above solution it is clear that if the numbers $x_0, x_1, x_2$ have the same parity, then we will not be able to ensure that only one digit remains on the board. Prove that if the numbers $x_0, x_1, x_2$ are both even and odd, and, in addition, at least two of them are non-zero, then there is such an order

Fig. 4.
Fig. 5.
Fig. 6.

⟦folio 34⟧

erases, leaving only one number on the board.

Let us change the conditions of Problem 3: we require that the same two nervous digits be erased twice, and one digit different from the erased ones be recorded together. Suppose that again after a certain number of operations there is only one unit left on the board, based on the number of zeros, ones and twos, can you predict what number this is?

The four reasoning doesn't help here, but each operation results in one of the numbers $x_0, x_1, x_2$ changing its parity and the other two maintaining parity, so that numbers having different parities can now end up with the same parity. However, you can notice that the remainders from dividing the numbers $x_0, x_1, x_2$ by 3 change each time in such a way that equal remainders remain equal, and nervous remainders remain nervous. Further differences repeat the solution to problem 3.

Problem 4. Each cell of the table $8 \times 8$ contains some integer. You are allowed to select any square of size $3 \times 3$ or $4 \times 4$ in the table and increase by one all the number cells in the selected square. Is it always possible to use such operations to transform the original table into a table whose numbers are divisible by 3?

Solution i.e. No, not always. Let's find the sum of the numbers written in the 6 cells shaded on figure. Since any square of size $4 \times 4$ contains 12 shaded cells, and a square of size $3 \times 3$ contains 6 or 9 such cells, then as a result of the described operation, the remainder of division by 3 of this sum (the numbers in the shaded cells) will not change. Therefore, if from the very beginning the found sum is not divisible by 3, then among the shaded cells there will always be cells in which the written numbers are not multiples of those.

Y dilution 3. From any table, under the conditions of problem 4, is it possible to obtain a table that does not contain even numbers?

Problem 5. The numbers 1, 2, 3, ..., $n$ are arranged in some order. It is allowed to swap places of any two adjacent numbers. Prove that if you perform an odd number of such operations, you will certainly get a different arrangement of the numbers 1, 2, 3, ..., $n$ from the initial one.

Solution. Let $a_1, a_2, ..., a_n$ be an arbitrary permutation of the numbers 1, 2, 3, ..., $n$. We will say that the numbers $a_i$ and $a_j$ form inversions in this permutation if $i < j$ but $a_i > a_j$, that is, the larger of these numbers precedes the smaller. By swapping two adjacent numbers in a permutation, we will increase or decrease the inversion number by 1. By performing an odd number of such operations, we will change the parity of the inversion number, and therefore change the permutation.

Y decomposition 4. Prove that the statement of problem 5 remains valid if you resolve the positions of any two numbers in the permutation.

U cauldron i.e. Prove that any two numbers can be swapped by performing the odd number operation described in Problem 5.

The transition from one permutation of the numbers 1, 2, 3, ..., $n$ to another permutation of these numbers, in which any two numbers are swapped and the rest remain in place, is called transposition. The result of exercise 4 can be formed as follows: perform an odd number of transpositions, we will change the permutation.

Problem 6. At different points, the number of automatic machines at the same time in one direction was 25 automatic. According to the rules, they can bypass each other automatically, but double bypass is prohibited. The cars were picked up at the same time at the same points where they were picked up. Prove that during the zonka there was an even number of designations.

Solution. We'll paint one of the machines yellow, and the rest will be assigned numbers automatically.

⟦folio 35⟧

1, 2, 3, ..., 24 in the order in which they are located at the start behind the yellow machine. In the center of the author, there is a table property installed, on which, after each overtaking, we will indicate the numbers of the machines in the order in which they follow the yellow machine. Then overtaking, in which the yellow automatic car does not participate, leads to two adjacent numbers changing places on the light display.

Let's see what happens if some automatic vehicle overtakes the yellow one. If before this overtaking the numbers on the table formed the permutation $a_1, a_2, a_3, ..., a_{24}$, then after overtaking they form the permutation $a_2, a_3, ..., a_{24}, a_1$. Note that the same rearrangement can be arrived at by performing 23 consecutive transpositions:

$$a_1, a_2, a_3, ..., a_{24} \rightarrow a_2, a_1, a_3, ..., a_{24}, a_1.$$

If the yellow automatic car overtook, then from the permutation $a_1, a_2, a_3, ..., a_{24}$ we get the permutation $a_{24}, a_1, a_2, a_3, ..., a_{24}, a_1.$

This transition can also be replaced by two adjacent transposition numbers.

Thus, either overtaking is reduced to an odd number of transpositions. If the total number of overtakings were odd, then the total number of transpositions would also be odd. It remains to use the result of control 4.

Exercises
5. Four ones and five zeros are written in random order around the circle. A 1 is written between two identical digits, and a 0 between different digits, after which all original digits are erased. Is it possible, by repeating this operation several times, to obtain a set of nine zeros?
6. Pete tore a piece of paper into ten pieces, some of these pieces he again tore into ten pieces, etc. Could Pete get 1975 pieces of paper in this way?
7. The numbers 1, 2, 3, ..., 1975 are written on the board. You are allowed to erase any two numbers

and write together the erased numbers, the remainder from dividing the sum of these numbers by 13. After a certain number of such operations, one number remains on the board. What could it be?

8. Each number from 1 to 1,000,000 is replaced by a number equal to the sum of its digits. The same operation is performed on the resulting numbers, and this is done until the numbers become single digits. Which numbers result in larger numbers: ones or two?
9. From a three-digit number I will calculate its digits. With the resulting number they sell the same thing, and so on - that’s it. What is the resulting number?
10. The circle is divided into 10 sectors, each of which contains one number. In one move, you can move any two chips to adjacent sectors, but so that the chips move in opposite directions. Is it possible to collect all the chips in one sector?
11a). At the top $A_{12}$ of the correct 12-gon $A_1A_2A_3...A_{12}$ a minus is placed, and at the remaining vertices there are plots. You are allowed to select any three vertices forming an indirect equilateral triangle and change the signs written at these vertices to the opposite ones. Is it possible, with the help of such operations, to ensure that the top $A_1$ has a minus, and the remaining vertices have plots?
6). Is the result of control a) preserved if we allow a change of sign in the upper parts of any equilateral triangle, including a right triangle? *).
12. In each cell of the table $4 \times 4$ a plane is written. It is allowed to simultaneously change the sign to the opposite one in all cells of one row or one column. The smallest minus number that can be reached by starting from a given table is called the characteristic of this table. What values ​​can a characteristic take?
13. There are 30 chips in a circle - 10 white and 20 black. It is allowed to swap places of any two chips, between which there are three more chips. Two arrangements of tokens are said to be equivalent if one of them can be obtained from the other by applying the specified operation several times. How many unequal arrangements of chips are there?
14. The numbers 1,2,3, ..., 1975 are written in order. You are allowed to choose any numbers and place them in the places they occupied, but in reverse order. Is it possible to use such operations to arrive at the location 1975, 1974, ..., 3, 2, 1?

*) This problem was sent to «Kvant» by Vilayam Guseyov, a 10th grade student at school No. 3 in Nakhivan.
