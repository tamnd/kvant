---
id: 2017-3-bakaev-pereklyucheniya-ryadov-8a4ee2e7
issue: kvant_2017_3
year: 2017
number: "3"
title: Switching rows
authors:
  - Бакаев Е. В.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 41
page_last: 47
page_labels: 40-45
tag: DI3H
lang: en
source: kvant_digital
extraction: native
content_sha256: 6237a0e8fce30c83c0ea26fdd47fbafeb0b2f66bf2568ea237a0e5e6e5a07244
prompt_sha256: draft-1
translated_from: content/ru/2017/03/articles/02_bakaev-pereklyucheniya-ryadov-8a4ee2e7.md
source_content_sha256: 4d680d3f3468c5e384a40f2dd977dfa19e66c1cbab1543cf6c4de5ddc00d97ca
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio none⟧

MATHEMATICAL CIRCLE

Switching rows

E.BAKAEV

Let's start with a problem that is reasonable to consider, this is $2 \times 2$. Let's find out which of its fillings can be obtained from which ones. There are $2^{4} = 16$ ways to fill the cells of the table $2 \times 2$ with pros and cons. You can consider them all and make a diagram (graph). We will connect two fillings with a line (edge) if one can be obtained from the other by just switching the row (Fig.2).

Problem 1. All cells of the table $8 \times 8$ are filled with pluses and minuses (one sign per cell). One operation allows you to select any row (row or column) and change the sign in each of its cells to the opposite one. At first all the signs were positive. Is it possible that after several such operations it turns out that there is exactly one minus in the table? figure 1 shows an example of such an operation.

⟦figure⟧

Fig. 1

We will not only solve this problem, but also generally figure out which tables can be obtained from which using these operations. We will call rows and columns rows. The operation described in Problem 1 will be called row switching.

Table $2 \times 2$

Instead of solving the problem about the table $8 \times 8$, we will first deal with a small table for which all possible recoloring options can be sorted out manually. Smallest table

Solutions to the problems in the article are given, but it is worth thinking about the problem yourself before reading its solution - this will bring more benefit. The article also contains exercises, they are often simpler than problems, they are also worth solving, this can help you understand the subsequent material. Answers and instructions for the exercises are given at the end of the issue.

⟦figure⟧

Fig. 2

It can be seen that all the fillings are divided into two groups (two connected components of the graph): the fillings of one group cannot be obtained from the fillings of another. What do the entries in each group have in common? How do the fillings of different groups differ? You can notice that in the fillings of one group there is an even number of pluses, and in the fillings of the other there is an odd number. This can be proven without going through all the filling options. Indeed, with each move we change two signs, i.e. either we change 2 pluses to 2 minuses, or we change 2 minuses to 2 pluses, or the number of pluses and minuses does not change. This means that the number of pluses when switching rows retains its parity.

Exercise 1. There are 5 glasses on the table upside down. It is allowed to turn over any 2 glasses at the same time. Is it possible to repeat

⟦folio 40⟧

KVANT 2017/№3

When performing this operation, place all the glasses correctly?

Even number of pluses

We've completely figured out the tables $2 \times 2$. Similar considerations will help in solving Problem 1. Indeed, in this case, the parity of the number of pluses in the entire table will not change. Let's prove it. Let there be x pluses in some row, then after switching it there will be 8 – x pluses in this row, and in the rest of the table the pluses will remain in place. But the numbers x and 8 – x are of the same parity. This means that the parity of the number of pluses in the entire table will not change - it is an invariant. (An invariant is a property that does not change under given transformations.) So, at first there were 64 pluses in the table, which means that their number will always be even and cannot become equal to 63. Problem 1 is solved.

⟦column⟧

nal cells – advantages. Is it possible to switch rows so that all signs become pluses? Does a solution similar to the first problem work for them? No: in problem 2, 3 digits change each time, which means that the parity of the number of pluses changes each time and can be anything. In Problem 3, the parity of the number of pluses is indeed an invariant, but this does not give a contradiction - in the initial and final positions their parity is the same. How to solve problem 2? Let's look at the start and end positions (Fig.3). Let's assume that one can get another.

⟦figure⟧

Fig. 3

Exercises

2. There are 15 glasses on the table upside down. It is allowed to turn over any even number of glasses at the same time. Is it possible to repeat this operation and place all the glasses correctly? 3. From table A, by switching rows, we obtained table B. Prove that from table B, by switching rows, we can obtain table A. 4. Table $8 \times 8$ was filled with pluses and minuses, after which we made several switches of rows. a) Can it turn out that the final filling of the table with signs differs from the initial one in exactly one cell? b) Can the final and initial fillings be different in all cells? c) Is it possible to obtain a “chess coloring” from filling with only pluses, i.e. such a filling in which any two adjacent signs on a side are different?

Let's consider two more problems similar to the first. Problem 2. In the table $3 \times 3$ one corner cell has a minus, and the rest have pluses. Is it possible to switch rows so that all signs become pluses? Problem 3. In table $8 \times 8$ there are minuses in the four corner cells;

Let's look at the top left cell. There was a minus in it, but there should be a plus. This means that it must be changed an odd number of times. The sign changes when one of the two rows at the intersection of which it is located is switched, so one of the rows must be changed an odd number of times, and the other an even number. Due to the symmetry of the situation, we can assume that the row was switched an odd number of times, and the column (Fig.4,a) was switched an even number of times.

⟦figure⟧

Fig. 4

Let's now look at the middle sign in the top row. He was a plus and should remain so. This means that it must be changed an even number of times. But the first row changes an odd number of times, which means the second column also changes an odd number of times. Reasoning similarly, but now considering the middle cell of the first column, we can conclude that the second row changes an even number of times (Fig.4,b).

⟦folio 41⟧

MATHEMATICAL

But then the middle column and middle row will change in total an odd number of times, which means that the central sign of the table will change an odd number of times and will become a minus, not a plus (Fig.4,c). We get a contradiction - you cannot get from one position to another by switching rows. Problem 2 is solved. Note that to obtain a contradiction, it was enough for us to consider the 4 signs forming the square $2 \times 2$, and the signs in the remaining cells were not important for the solution. Let us remember that when switching rows in the square $2 \times 2$, the parity of the number of pluses in it does not change, because each time 2 signs change. But this is also true for the $2 \times 2$ square inside a larger square! Accordingly, the solution to Problem 2 can be stated more briefly by considering the square $2 \times 2$ (see Fig.4,c) and noting that the parity of the number of pluses in it is an invariant.

Exercise 5. Make sure that problem 3 can be solved in a similar way.

Some problems are solved using the same seemingly simple invariant as in problems 2 and 3 (parity of the number of pluses), but it can be difficult to guess for which region (in our case it was a certain square $2 \times 2 )$ such an invariant works. Such problems can be found in the article by Yu. Ionin, L. Kurlyandchik “Search for an invariant” in «Kvant» No. 2 for 1976 year, see also additional problems 2 and 3 at the end of this article.

Exercises

6. In the table $8 \times 8$ initially all signs were pluses. Then we made several row switches. How many pluses can appear on the main diagonal after an odd number of operations? 7. In table $8 \times 8$ initially all the signs were pluses. Then we made several row switches, after which some of the signs were hidden. a) Some signs are known (Fig.5,a). Find the characters marked with question marks. b) A similar question for the table at figure 5, b. c) Some signs are known (Fig.5,c). Is it possible to use this information to determine whether an even or odd number of operations were performed? d) Some signs are known (Fig.5,d). Look for the one marked with a question mark.

CIRCLE

⟦column⟧

⟦figure⟧

Fig. 5

Number of actions

As we have already found out, the sign in a cell will change only if an odd number of operations containing this cell were performed. It follows, firstly, that the order of operations does not affect the result. Secondly, only the parity of the number of such operations matters, i.e. the result will not change, for example, if you change the row not 13 times, but 1 time. This means that we can assume that each row can either not be switched at all, or switched once, and switching it more times is pointless. It turns out that if some filling of the table $n \times n$ can be obtained from another, then this can be done in no more than 2n operations (since there are 2n rows in total). But a stronger assessment is also true. Problem 4 (A. Kanel-Belov, XXXIII Tournament of Cities, 2012). The cells of the table $n \times n$ contain pros and cons. In one move, you are allowed to change all signs in an arbitrary row or in an arbitrary column to the opposite ones. It is known that from the initial arrangement one can obtain one in which all cells contain pluses. Prove that this can be achieved in no more than n moves. We have already shown that it is always possible to do it within 2n moves. But when might we need exactly 2n moves? When we switched each row once. But then each character will change 2 times, because its line and its column have changed. This means that filling the table will remain the same, so it could be obtained faster - without making a single move! So

⟦folio 42⟧

KVANT 2017/№3

Thus, we have proven that it is unnecessary to make 2n moves. Let's move on. When might you need exactly 2n – 1 moves? When they switched all the rows except one. Then the signs of this series will change once, and the remaining signs - 2 times. Again, this filling could have been achieved faster - it was enough to switch only one row, which we did not switch. But the same can be done in other cases! Let's assume that we switched some x rows. If you switch not these rows, but all the others, then there will be 2n – x moves, but the result will not change (if the sign changed 2 times, then it will not change now; if it did not change, then it will change 2 times; if the sign changed 1 time, then it will now change 1 time). Accordingly, if there were more than n moves, then after such an “inversion” of our actions we will get the same result in less than n actions. Problem 4 is solved.

Exercise 8. Is it possible to strengthen the assessment in task 4? In other words, is it always possible to achieve what you want in no more than n – 1 moves?

Feasibility criterion

Let's return to the question of which fillings can be obtained from which ones. We will call a filling realizable if it can be obtained by switching rows from a filling in which all signs are pluses. When solving Problem 2, we already found out that if the filling contains a square $2 \times 2$, in which there is an odd number of pluses, then it is not realizable. Instead of the square $2 \times 2$, you can consider any 4 cells that are the vertices of a rectangle with sides parallel to the sides of the table (an example of such four cells is in figure 5,a). In such four cells, the parity of the number of pluses also does not change, so if initially they were all pluses, then there will always be an even number of pluses among them. This means that if there are 4 cells in which there is an odd number of pluses, then filling is not feasible. But if they are not found, does this mean that it is feasible? Yes, it turns out that the following criterion of realism is true. Equivalent

⟦column⟧

There are three properties of filling (i.e., if one of these properties is satisfied, then the other two are also satisfied): 1) it is realizable; 2) in any square $2 \times 2$ an even number of pluses; 3) in any 4 cells that are the vertices of a rectangle with sides parallel to the sides of the table, there is an even number of pluses. The second property follows directly from the third, because a square $2 \times 2$ - a special case of such a rectangle. We have already shown how the second and third follow from the first property. To complete the proof of the equivalence of the three properties, we will show how the first follows from the second. Consider an arbitrary filling for which the second property holds: in it in any square $2 \times 2$ an even number of advantages. Let us prove that it is realizable, i.e. Let us show that by switching rows it can be brought to a situation where all signs are pluses. Let's make such changes Fig. 6 inclusions of rows so that all signs of the first column and first row become pluses. See example at figure 6.

Exercise 9. Prove that such switches can always be made.

Now we will prove that after such switchings, all other signs of the table became pluses. Any square $2 \times 2$ still has an even number of pluses, since switching rows does not violate this property. Now consider the upper left square $2 \times 2$ (Fig.7,a). Its three signs are pluses,

⟦figure⟧

Fig. 7

that means the fourth is a plus. Let's consider the next square $2 \times 2$, moving one cell to the right (Fig.7,b), for it the situation is similar. Considering all such squares sequentially, we find that all the signs of the table are pluses.

⟦folio 43⟧

MATHEMATICAL

Exercises

10. The equivalence of the second and third properties can be proven without using either the first property or switching signs at all. Try this. 11. One of the rows of the implemented table $8 \times 8$ contains x pluses. Prove that each line of this filling contains x or 8 – x pluses. 12. Consider some implementable filling of table $8 \times 8$. Let there be x minuses in one of its rows, and y minuses in one of the columns, and at their intersection there is a plus. How many minuses are there in this filling? 13. Is there a feasible completion of table $8 \times 8$ that contains exactly 6 pluses?

Number of fills sold

Let's fill the first row and first column of the table $m \times n$ in an arbitrary way. Then: firstly, the remaining cells can be filled in such a way that the filling is feasible; secondly, this can be done in the only way.

Exercise 14. Prove these statements. Note. Use the feasibility criterion and the result of Exercise 9.

Thus, the number of ways to fill a table with pros and cons so that the filling is feasible is equal to the number of ways to fill its first row and first column in an arbitrary manner. In the first row and first column of the table $m \times n$ there are a total of m + n – 1 cells, which means that there are $2 m + n - 1$ realizable fillings of such a table.

Filling graphs

In the section about the table $2 \times 2$ we built a graph in which an edge connected the vertices corresponding to such table fillings that can be obtained from each other by just switching a row. We can consider the same graph, but for a table $m \times n$ (it has $2^{mn}$ vertices). Each filling belongs to some connected component of this graph. Two fillings belong to the same component if one can be obtained from the other by switching rows.

CIRCLE

Exercises

15. How many fillings are in the connected component in which the filling is located, where all the signs are pluses? 16. How many connected components are there in this graph and how many fillings are there in each of them? Note. Any filling can be brought by switching rows to a filling in which in the first row and first column all signs are pluses. In this case, the parity of the number of pluses in any 4 cells that are the vertices of a rectangle with sides parallel to the sides of the table will not change.

Finding the number of implementable fillings is part b) problem M665 of the Problem Book «Kvant». See her decisions in «Kvant» No. 9 for 1981.

⟦column⟧

Auxiliary character switching

The condition of the following problem does not say anything about operations that change signs, however, you can consider such operations, and then the feasibility criterion will help solve the problem. Problem 5 (E. Bakaev, XXXIV Tournament of Cities, 2012, M2289). Some cells of the square $11 \times 11$ contain pluses, and there are an even number of pluses. Each square $2 \times 2$ also has an even number of pluses. Prove that the number of pluses in the 11 squares of the main diagonal of the square is even. For the table from this task, the second property is satisfied, which means that its filling is feasible. Then we can consider the sequence of switching rows, which allows us to obtain a given filling from a filling with only pluses. Let's consider the number of pluses in the entire table. Each row switch changes 11 signs, which means it changes the parity of the number of pluses in the entire table. Since, according to the condition, there is an even number of pluses in the entire table, and initially the number of pluses $11^{2} = 121$ is odd, then there were an odd number of operations. Each operation changes one sign on the diagonal and thereby changes the parity of the number of pluses on the diagonal. Since there were initially 11 pluses, and there were an odd number of operations, then there will be an even number of pluses on the diagonal.

Exercise 17. Solve problem 5 in a different way, without considering the operations of changing signs.

⟦folio 44⟧

KVANT 2017/№3

Try solving the following problem using auxiliary row switching.

Exercise 18 (V. Proizvolov, XXIII All-Union Olympiad, M1181). There are 8 rooks placed on a chessboard so that they do not attack each other. Prove that there are an even number of rooks on black squares.

Erased signs

As we have already found out, using m + n – 1 signs of the table, you can restore the rest if it is known that filling is feasible. For example, this can be done using the characters of one row and one column. But m + n – 1 signs, from which the realizable filling can be reconstructed, can be located differently, as can be seen by solving Exercise 19.

Exercises

19. Prove that all unknown filling signs on figure 5,r can be uniquely restored. 20. Is the filling uniquely restored for any 50 characters of table $8 \times 8$?

So, for some arrangements of m + n – 1 known signs, it is possible to unambiguously reconstruct the remaining signs from them. But is it true that this is the smallest number of characters required? Yes, that’s right, and this is exactly what task 15 of the A.P. Savin Competition was about (see «Kvant» No. 1 for 2017). Problem 6. Petya drew a table $10 \times 10$ and filled all its cells with pluses. Then he did a few things according to the following rule. With each action, he randomly selected a row (row or column) and changed each of its 10 signs to the opposite (plus for minus, minus for plus). When Petya left after this, the bully Vasya erased some of the signs - only N signs remained. For what smallest N can it turn out that Petya’s resulting table can be uniquely reconstructed from the remaining data? Let us present a solution to a more general case – for table $m \times n$. Answer: m + n – 1 (respectively, for table $10 \times 10$ answer: 19). So, it remains to prove that if less than m + n – 1 characters are known, then the filling cannot be uniquely restored.

⟦column⟧

Consider a graph in which the vertices correspond to rows (there are m + n vertices in total) and two vertices are connected by an edge if and only if there is a known sign at the intersection of these two rows. This graph has m + n vertices, and there are as many edges as there are known signs, which means there are fewer than m + n – 1. From this ratio of the number of vertices and edges, we can conclude that the graph is disconnected. Let's consider one of the connected components, call all its vertices (and all corresponding rows) red, and all other vertices (and their rows) blue. Let us assume that using the known signs it was possible to unambiguously restore the entire filling. Let's consider it. Let's switch the signs in each of the red rows sequentially. Each known sign stands either at the intersection of two blue rows or two red ones, which means that with this sequence of actions, each known sign will either not change at all, or will change 2 times, in any case it will remain the same. At the same time, the filling did not remain the same, since each sign standing at the intersection of the red and blue rows changed. Thus, we received another filling in which the known signs are exactly the same. This means that the filling cannot be unambiguously restored using known signs. The article by P. Kozhevnikov and A. Shapovalov “Contact the graph” in «Kvant» No. 4 for 2014 is devoted to various problems with such a solution idea (considering an auxiliary graph and using its connectedness or disconnection). Let us now consider the similar problem M112 “Problem book «Kvant». Problem 7. A table of size $m \times n$ contains numbers in such a way that for any two rows and any two columns, the sum of the numbers in the two opposite vertices of the rectangle they form is equal to the sum of the numbers in its two other vertices. Some of the numbers have been erased, but the remaining ones can be used to restore the erased numbers. Prove that there are at least (n + m – 1) numbers left. In problem 6 we were talking about realizable filling, which means that in all the same four cells standing at the intersection of 2 rows and 2 columns, the number of pluses is even. We are not talking about repainting here.

⟦folio 45⟧

MATHEMATICAL

yakh or about the pros and cons, but again a condition is imposed on all such four cells. Let's try to solve this problem in a similar way. Consider the same disconnected graph. Again, let's call the vertices of one component red and all the others blue. In the previous problem we were talking about switching rows, but here no operations are mentioned in the condition, but we ourselves can introduce some auxiliary operations with rows. What do we want from these operations? We want the numbers in the cells at the intersection of single-color rows not to change, but at the intersection of multi-colored rows to change. Moreover, the operation should not violate the property that for any two rows and any two columns, the sum of the numbers in the two opposite vertices of the rectangle they form is equal to the sum of the numbers in its two other vertices. For example, the following operation is suitable: for a column, we increase all the numbers in the column by 1, and for a row, we decrease all the numbers in the row by 1. It is easy to check that this operation satisfies the necessary requirements. Consequently, having carried out one such operation with each red row, we obtain a table in which the known signs are the same, but some unknown ones have changed. This means that the table cannot be reconstructed uniquely, knowing less than n + m – 1 numbers. This problem is about the uniqueness of the solution to a system of linear equations. Another solution to this problem, using linear algebra, is given in «Kvant» No. 8 for 1972. The previous problem is, in fact, the same problem, but instead of the usual linear equations - comparisons modulo 2. This approach (considering problems about switching signs from the point of view of linear algebra) is devoted to the article by V. Dorofeev, A. Spivak “Graph colorings and linear equations” in «Kvant» No. 4 for 2011. We recommend it for further study of the issue.

Additional tasks

1. 30 nickels lie with the coat of arms facing up. You are allowed to turn over any 29 of them at a time. Is it possible to ensure that all the nickels are face down? 2 (IX Tournament of Cities, 1987). A regular triangle is divided by parallel lines

CIRCLE

its sides into equal regular triangles. One of the small triangles is black, the rest are white. It is allowed to recolor simultaneously all triangles intersected by a line parallel to any side of the original triangle. Is it always possible, with the help of several such recolorings, to ensure that all the small triangles become white? 3 (E. Bakaev, Matfight Tournament in memory of A.P. Savin, 2015). Given a checkered square: a) $5 \times 5$; b) $8 \times 8$. With one operation you can select any square $3 \times 3$, or any row, or any column and change the colors of all cells in this area to the opposite ones. With the help of such operations, from a completely white square we obtained a square containing exactly one black cell. Where might this cell end up? Please indicate all options. 4. In how many ways can the cells of the table $10 \times 10$ be colored black and white so that any square $3 \times 3$ has an even number of black cells? 5 (A. Zelevinsky, Moscow Olympiad, 1970, M32). All cells of the table of size $100 \times 100$ contain pluses. It is allowed to simultaneously change the signs in all cells of one row or in all cells of one column. Is it possible, after performing such operations several times, to obtain a table with exactly 1970 minuses? 6 (V. Alekseev, Moscow Olympiad, 2007). In a table of $n \times n$ cells, two opposite corner cells are black and the rest are white. What is the smallest number of white cells that needs to be repainted black so that after this, using transformations consisting of repainting all the cells of any column or row in the opposite color, it is possible to make all the cells of the table black? 7 (A. Bystrikov, XXV Tournament of Cities, 2003). Table $m \times n$ lists the pros and cons. In one move, you are allowed to change signs to opposite ones in any row or column or on any diagonal (corner cells are also considered diagonals). Prove that if the table is not reduced by such actions to a table of only pluses, then it contains a square $4 \times 4$, which is also not reduced.
