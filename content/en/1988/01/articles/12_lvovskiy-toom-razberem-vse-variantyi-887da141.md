---
id: 1988-1-lvovskiy-toom-razberem-vse-variantyi-887da141
issue: kvant_1988_1
year: 1988
number: "1"
title: Let's look at all the options
authors:
  - Львовский С. М.
  - Тоом А. Л.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 44
page_last: 48
page_labels: 42-46
tag: UFKD
lang: en
source: kvant_digital
extraction: vision
content_sha256: bc3e34a5c040e333ed928a4ae86f6785db4090a0ed973e7751b8dc5254cc09a3
prompt_sha256: draft-1
translated_from: content/ru/1988/01/articles/12_lvovskiy-toom-razberem-vse-variantyi-887da141.md
source_content_sha256: 743c44ca50009cd7e15695e862310e89af24dac1b8afa3b3606cf6a6e58f8c02
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 42⟧

Let's look at all the options

S. M. LVOVOVSKY,
Candidate of Physical and Mathematical Sciences
A. L. TOOM

The method here is approximately the same as when searching for one pea in a bag of peas: first you need patience, young man.
K. Chapek. "Coupon"

When in elementary grades students first begin to solve problems in mathematics, they are specially selected problems that can be solved by previously overcome methods, and one definite answer is obtained. Optimization involves selecting problems that have an unexpected, but simple and beautiful solution.

But Nature does not take into account our tastes. Therefore, a professional, solving problems that arose during the development of natural theory, constantly faces problems that either have no solution, or have many solutions, or require non-privileged, and sometimes cumbersome, “ugly” methods of solution.

Primary school students often consider the brute force method to be such an “ugly” method. Some even think that the brute force method is the “wrong” method and supposedly cannot be used to solve problems. In fact, the problem can be solved in any way, as long as you get a correct and reasonable answer. Finding all the answers and proving that there are no others is what it means to solve the problem. And there can be any number of these answers: one, several, none, or an infinite number.

Of course, the method of recruiting employees discussed in this article must be used wisely, and not haphazardly. First of all, let us note that any excess that one person or all of humanity once

⟦folio 43⟧

anyone can implement it - this is a finite search, and no amount of computer technology will change this. But even a finite search is feasible only within limited limits. In fact, when solving problems “manually”, using a pen and paper, you can go through ten, well, a hundred options. The computer is notified of this number up to a thousand, well - millions. However, problems often arise whose solutions by brute-force methods lead to a much larger number of options. Already simple board games like chess provide a number of positions that no machine can handle. Therefore, the art of programming, like the art of solving mathematical problems, includes the ability to reduce enumeration to a feasible scale.

A complete search of all options is feasible only in the simplest cases. For. Swift wittily covered it in his book Gulliver's Travels. In the fifth chapter of the third part, he describes a machine that carried out an enumeration of everything and could form a complete overview of all the arts and sciences. Swift's satire aimed at a very real goal: the creation of “thinking” machines associated with the idea of ​​brute force. Back in the 12th century, the knight-monk Raymudus Lull designed a machine for mechanical proof of all the provisions of Christianity and went with it to the Moors, confident that this “science” would convert them to the true faith. Lullai's ideas were of interest to Giordano Bruno and Leibniz, who dreamed of such progress in science that allows one not to argue, but to calculate.

The great German scientist Leibnitz (1646-1716), who was an older contemporary of Swift (1667-1745), in his life developed the idea of ​​a “universal characteristic,” that is, a description equal in accuracy to mathematics of all processes of human thinking.

This idea has not yet been fully realized and, perhaps, will never be realized. But the mathematization of many aspects of human activity will undoubtedly occur. And at the same time, basic mathematical ideas, including the idea of ​​enumerating options, are becoming more and more widely used.

Problem 1. There are 5 machines in a warehouse weighing the corresponding 1500 kg, 1020 kg, 800 kg, 750 kg and 600 kg. It is required to increase some of them on a machine with a lifting capacity of 3 tons, loading it to the maximum, but not overloading it. What machines need to be cut into a car?

Solution. Let's assume that we decide not to be the heaviest machine. Then the mass of the remaining machines is 1020+800+750+600=3170 kg, which is more than three tons. This means that we will have to leave another machine. We will capture the heaviest weight if we leave the lightest machine - 600 kg. Of course, we still need

⟦folio 44⟧

check whether the three-horsepower can increase the remaining machines: 1020 + 800 + 750 = 2570 kg <3 tons. So: if we do not take the heaviest machine, then we will increase, at most, 2570 kg. Let us now load a 1500 kg machine onto the machine; then there is still 1500 kg of space left in the car. We can meet these 1500 kg by taking only one machine, which will give us, at most, 1020 kg (and in total there will be 2520 kg in the truck), or by taking two machines, which will give us, at most, 800 + 600 = 1400 kg, and in total there will be 2900 kg on the truck.

Comparing all the options, we see that the last one is the most. So, you need to load machines weighing 1500 kg, 800 kg, and 600 kg.

Such a direct search is not always possible. More often it is necessary to use it in combination with other methods. Here's an example.

Problem 2.*) Find all natural three-digit numbers, each of which has the following two properties:

- the first digit is 3 times less than its last digit;
- the sum of the number itself with the number obtained from it by rearranging its second and third digits is divisible by 8 without a remainder.

Here, direct enumeration method would mean going through all three-digit numbers and selecting those that satisfy the conditions. Doing it manually is like looking for a needle in a haystack or the right pea in a bag of peas. True, it won’t take long to sort through all three-digit numbers using a computer, but it’s “sportier” to solve simple problems using simple means: this will force us to develop techniques for reducing the search; By the way, these techniques will dramatically increase our capabilities when we have a computer.

We will begin to solve this problem algebraically and will resort to enumeration only when we can solve it in a few cases.

Solution. Let $x$ be the hundreds digit, $y$ be the tens digit of the desired number. Then the digit of its units is 3x. Obviously 3x≤9, hence $x\leq 3$. The first digit of a number cannot be zero. This means that $x$ cannot equal a number other than 1, 2 and 3. We will consider these three possibilities separately, but first we write down the second condition, denoting the time with dots (:) the expression “divisible by”:

$((100x+10y+3z)+(100x+30x+y))\div 8,$

i.e.

$(200x+33x+11y)\div 8.$

We purposely left 200x and 33x as separate terms. This makes it easier to see that 200x can be discarded (since 200 : 8) and write this condition like this:

$((33x+11y)\div 8,$

or

$11(3x+y)\div 8.$

For this it is necessary and sufficient that 3x+y is divisible by 8. Now let’s look at the search, which is quite feasible, since it consists of only three cases.

1) $x=1$. Then $3+y$ : 8. This will be at $y=5$.

2) $x=2$. Then $6+y$ : 8. This will be at $y=2$.

3) $x=3$. Then $9+y$ : 8. This will be at $y=7$.

So, the problem has three answers: 153, 226, 379.

Problem 3. Solve the equation in natural numbers

$$\frac{1}{x}+\frac{1}{y}+\frac{1}{z}=1.$$

Recall that positive integers are called natural numbers. Solving an equation in natural numbers means finding all its solutions in which the unknowns take natural values. By exhaustive search, considering all triplets of natural numbers separately, this problem can be solved in general: there are an infinite number of such three. Therefore, before brute force, it is necessary to somehow reduce to a finite number of cases. It will be more convenient for us to carry out re-

⟦folio 45⟧

problem if we slightly change the conditions of the problem.
Problem 3'. Solve the system in natural numbers

$$\begin{cases} \frac{1}{x} + \frac{1}{y} + \frac{1}{z} = 1, \\ x \leqslant y \leqslant z. \end{cases}$$

Solution of problem 3'. Obviously,

$$\frac{1}{x} \geqslant \frac{1}{y} \geqslant \frac{1}{z}.$$

Let us first assume that $x > 3$. Then

$$\frac{1}{3} > \frac{1}{x} \geqslant \frac{1}{y} \geqslant \frac{1}{z},$$

where

$$\frac{1}{x} + \frac{1}{y} + \frac{1}{z} < \frac{1}{3} + \frac{1}{3} + \frac{1}{3},$$

which is contrary to the conditions. So, $x$ cannot equal anything other than 1, 2 and 3. (See how dramatically we reduced the search!)
1) $x = 1$. Then

$$\frac{1}{y} + \frac{1}{z} = 0,$$

chero cannot be.
2) $x = 2$. Then

$$\frac{1}{y} + \frac{1}{z} = \frac{1}{2}.$$

If $y > 4$, then

$$\frac{1}{4} > \frac{1}{y} \geqslant \frac{1}{z},$$

where

$$\frac{1}{y} + \frac{1}{z} < \frac{1}{4} + \frac{1}{4},$$

chero cannot be. So, $y$ cannot equal anything other than 2, 3 and 4. Substituting each of these values, we see that $y = 2$ is not suitable, and the other two values ​​give two answers: (2, 3, 6) and (2, 4, 4).
3) $x = 3$. Then

$$\frac{1}{y} + \frac{1}{z} = \frac{2}{3}.$$

If $y > 3$, then

$$\frac{1}{3} > \frac{1}{y} \geqslant \frac{1}{z},$$

where

$$\frac{1}{y} + \frac{1}{z} < \frac{1}{3} + \frac{1}{3},$$

chero cannot be. So, in this case, we need to consider only one value 3 for $y$, which gives another answer: (3, 3, 3).

All cases have been resolved. Problem 3' solutions. It has three answers: (2, 3, 6), (2, 4, 4), (3, 3, 3).

In contrast, Problem 3 has a different list of answers resulting from all these possible permutations. Here is the answer to problem 3:

(2, 3, 6), (2, 6, 3), (3, 2, 6),
(3, 6, 2), (6, 2, 3), (6, 3, 2),
(2, 4, 4), (4, 2, 4), (4, 4, 2), (3, 3, 3).

(In each of these answers, the first number is the value $x$, the second is the value $y$, and the third is the value $z$.)

In the problems that we have solved so far, it was necessary to find all the answers that satisfy a given condition. In order to prove that such an object does not exist, it is necessary to separate all cases or carry out general reasoning. To prove that such an object exists, it is enough to give just one example. Here are two problems of this type.

Problem 4. It is known that for two triangles $ABC$ and $A'B'C'$ the following three conditions are satisfied:

$$\angle A = \angle A', AB = A'B', BC = B'C'.$$

Can triangles $ABC$ and $A'B'C'$ be unequal?

Answer: they can.

⟦folio 46⟧

Proof. Let us construct two unequal triangles for which the equalities in the conditions are true. Let's take an acute angle $A$ and put the segment $AB$ (Fig. 2) on one side of it. Let's draw a circle with center $B$ and a radius that is less than $AB$, but greater than the distance from point $B$ to the other side of the corner. This circle will intersect the other side of the angle at two points, which we will call $C$ and $C'$. Triangles $ABC$ and $ABC'$ are not congruent, although the three conditions above are satisfied.

Problem 5. Is it possible to calculate $k$ different numbers in a circle so that from each two adjacent ones it is possible to form a number divisible by 7? Here $k$ is whole, $3 \le k \le 10$.

In fact, eight different problems are assumed here for eight different values ​​of $k$. But it is convenient to solve them all together using the following technique.

Let's write down all two-digit numbers divisible by 7 (Fig. 3). Then we draw all ten numbers on paper and connect with lines those of them that make up any of the directed numbers (Fig. 4). Arranging $k$ numbers in the required manner is the same as the total $k$ of different circles and returning to the beginning of the path.

As you can see, all the numbers are scattered in three “islands”. It is now clear that it is impossible to arrange more than five digits in the required manner. And you can arrange three, four or five numbers. Write down the required arrangements yourself.

Task 1. Four statements were made about the triangle $ABC$:
a) triangle $ABC$ equilateral;
b) the triangle $ABC$ is right-angled;
c) $AB=BC$;
d) $AB=2AC$.

We know that two of these statements are true and the other two are false. What can the perimeter of the triangle $ABC$ be equal to if its shortest side is equal to one?

2. Find two numbers whose square is one greater than the other number.

3. What can the perimeter of triangle $ABC$ be equal to, if it is known that $\angle A=60^\circ$, $AB=8$, $BC=7$?

4. Solve, for positive numbers, the equation

$$x^2+y^2+z^2+xyz=20.$$

5. The snail crawled a meter long segment and stopped. Then she turned to $90^\circ$, crawled another meter long segment and stopped. She did this 6 times in a row: crawling 6 straight meter-long segments, turning the afterbirth of each $90^\circ$ to the right or left. What could be the distance between the beginning and the end of her journey?

6. Find all three-digit numbers that are each 19 times the sum of their digits.

7. In the sunny clearing there are triangles of snakes, sparrows, mice, beetles and plows. All together they have four more legs than heads. If the snakes crawl away, then there will be four more legs than heads. Mice and beetles together have four more legs than heads. Beetles and plows together have a hundred nails. How many animals are there in the clearing? (We hope that everyone knows how much someone doesn’t have: already - 0, uvorov - 2, mouse - 4, beetle - 6, pashka - 8.)

8. The distance $AB$ is 225 km. At 12 o'clock in the afternoon a bus leaves from $A$ to $B$ and at the same time a bus leaves from $B$ to $A$. The bus arrives at $B$ at 6 pm on the same day, and makes 4 stops along the way at regular intervals of 15 minutes each. The bus travels the entire way without stopping and meets the bus at a distance of 90 km from $A$. What can be the speed of the bus?

9. Is it possible to arrange the numbers 1, 2, 3, 4, 5, 6, 7, 8, 9 in a circle so that from each two adjacent digits you can form a simple two-digit number? (We remind you that a natural number is called prime if it has two equal divisors: itself and one.)

10. Find three numbers whose square is 3 greater than the sum of the other two numbers.

11. All the vertices of a certain quadrilateral lie inside a square whose side is 1.

a) Can the perimeter of this quadrilateral be greater than 5?

b) Can the perimeter of this quadrilateral be greater than 6?

12. A pedestrian walked from point $A$ to point $B$. After some time, the pedestrian followed from point $A$ into Volospedict. After driving for an hour,
