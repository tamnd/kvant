---
id: 2019-12-zadachi-db163927
issue: kvant_2019_12
year: 2019
number: "12"
title: Tasks
rubric: kvant-dlya-mladshih-shkolnikov
rubric_sub: «Квант» для младших школьников
page_first: 20
page_last: 23
page_labels: 20-21
tag: MLML
lang: en
source: kvant_digital
extraction: native
content_sha256: 75a8630a92ff6b8f94775e1971c1c7ef89ae9f161c020caa7a564d7149fbf8d4
prompt_sha256: draft-1
translated_from: content/ru/2019/12/articles/02_zadachi-db163927.md
source_content_sha256: 8b5ca9fd446881e952f2e10da9c11bcc10ece225dfc7e9598556c62cf53e3759
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio none⟧

“QUANT” FOR JUNIOR SCHOOLS LENNIK O V

Tasks

1.

Three sticks can be used to form a triangle. They broke off a piece from each stick and folded them into another triangle. Is it always possible to form a triangle from the remaining parts? L. Emelyanov number a, for which the number a ◊ 1001 ◊ 1003 ◊ 1005 + 4 will be an exact square. N. Agakhanov

3. The outline map shows 10 cities (without names) and roads between some of them. Dunno was given the task of putting names on the map

These problems were proposed at the XIV Southern Mathematical Tournament.

⟦column⟧

4. We call a rectangle consisting of chessboard cells important if all its corner cells are black. On each square of the chessboard is written the number of important rectangles containing that square. Let B be the sum of the numbers written on the black cells, and W the sum of the numbers written on the white cells. Find B – W. South African Olympics

Illustrations by D. Grishukova

2. Give an example of natural cities, but you only received a list of pairs of cities directly connected by a road. This was enough to unambiguously establish the name of each city. How could this be? S.Volchenkov

⟦folio 20⟧

KVAN T 2019/№12

let's call this the figure's outer set of numbers. An example is given in figure 3,a.

Exercise 2. Is there a figure with the following external set of numbers:

a) 0,3,3,3,3; b) 0,2,3,3; c) 0,0,2,2,2,2,2,2,2,2,2,2,2,3,3,3,3,3,3; d) 1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1?

Problem 2. How to find the perimeter of a figure using an external set of numbers? In the outer set, each unit segment of the perimeter is counted once (Fig.3,b). This means that the sum of the numbers in the outer set is equal to the perimeter: $¦_{внешн} p$. Now we use the found properties of the internal and external sets to derive a useful formula. Problem 3. Let s be the area of ​​the figure, p its perimeter, and i the number of internal partitions. Find and prove a formula connecting these three quantities. Let us understand how the external and internal sets are connected. In one case, for each cell we counted how many of its sides lay inside, and in the other, how many were on the border. Thus, in the two sets together we counted all 4 sides of each of the s cells. So, ¦ internal ¦ external 4s. Using the results of previous problems, we get: 2 i p 4 s.

⟦column⟧

Exercises 4. A square 5 u 5 was cut into several polygons so that the total length of the cuts is 12. What can the total perimeter of all polygons be equal to? 5. A board 6 u 6 was cut into rectangles 1 u 2. What could be the total length of the cuts? 6. The 8 x 8 square was cut into tetraminoes (figures of four cells). The total length of the cuts turned out to be 60. How many squares can there be among these figures?

Now let's discuss the next problem. Problem 5 (N.Strelkova). Apartment 3 u 3 consists of 9 square rooms 1 u 1. Every two adjacent rooms are connected by a door. What is the minimum number of doors that must be open so that a cat in one of the rooms can freely walk throughout the apartment? We will call a territory a set of rooms between which you can move freely. If it is impossible to walk from one room to another, then they are assigned to different territories. (In the example at figure 4, the cat's territory consists

Exercise 3. Find all the figures whose perimeter is a) 5 times greater than their area; b) 4 times; c) 3 times.

The following property follows from the proven formula. Problem 4. Prove that the perimeter of a checkered figure is always an even number. From the formula it is clear that p is the difference of the even numbers 4s and 2i, so it is also even. In the following exercises, the idea that the cuts are counted twice when adding up the perimeters of the parts helps again.

⟦figure⟧

Fig. 4

of 5 rooms, and the total number of territories is 3.) First solution (size of the cat's territory). First, we will close all the doors and open them in order. Let the cat choose this order himself. He can go to any closed door and meow, and then we will open that door for him. If it leads to a new room, it's cat territory.

⟦folio 21⟧

"QUANTUM"

FOR

YOUNGER

will increase by one room. If this door leads to a room that the cat could already reach in another way, then the territory will not change. It turns out that with each open door the cat’s territory increases by no more than 1. At first it is equal to 1, and at the end it is 9. This means that at least 8 doors will need to be opened. The problem is solved. Think about where exactly it is used that we offer the cat to choose the door, and do not open it ourselves. Second solution (number of territories). Let's close all the doors again and open them one by one. Now we will count the total number of territories. At first, each room forms one territory, i.e. There are 9 territories in total. At the end, all rooms form one territory. The door can connect either two different territories - then when it opens, the number of territories will decrease by 1, or connect the territory with itself - then the number of territories will not decrease. Again it turns out that at least 8 doors must be open. The same technique helps in the next exercise.

Exercise 7. In a square maze of size 6 x 6, you can walk from any cell to any other. What is the largest number of internal partitions it can have?

Now let's apply this approach to checkered pieces. Problem 6. What is the smallest number of internal mesh segments that can be in a figure with area s? Consider an arbitrary figure of area s and paint it all white. Let's select one of the figurine's cells and paint it black. Next, we will paint one white cell at a time black so that the new black cell adjoins the side of the already painted part. (It will always be possible to find such a cell: if there is both a white cell and a black one, then on the way from one to the other there will be a pair of two adjacent multi-colored cells.) Each time the number of internal segments of the grid in the black figure will increase, although

SHK O LNIK O V

⟦column⟧

would be by one. As a result, all cells will turn black. This means that the internal segments of the original figure are at least s – 1. Note that the algorithm for adding cells here is exactly the same as in the cat problem. It is easy to give an example in which there are really so many internal segments: this is, for example, the rectangle 1 u s. Problem 7. What is the largest perimeter a figure with area s can have? We have already proven the formula 2 i p 4 s. It shows that for a fixed s, the larger p, the smaller i. This means that the perimeter is greatest when the number of internal segments is smallest. As we have already found out, this is achieved in the case of i s 1. Substituting this into the formula 2 i p 4 s, we obtain that p 2 s 2. So, the perimeter of a figure with area s is not more than 2 s 2. The same example applies. Try the same idea of ​​adding cells sequentially in the following exercises.

Exercises 8. From a figure consisting of 20 cells, you can cut a square 3 u 3. Prove that its perimeter is not more than 34. 9. It is known that some cell figure can be cut into 5 squares 2 u 2. What is the largest perimeter it can have? 10. Draw 10 different figures, each of which has a perimeter of 14 and an area of ​​a) 6; b) 7. c) Why do the figures from point b) contain a square 2 u 2, but the figures from point a) do not?

Let us now analyze a problem where we can apply the perimeter estimate proven in Problem 7. Problem 8. Is it possible to cut a 5 u 5 square into two checkered polygons, each with a perimeter of 28? Let's assume that it can be cut like this. Then you can proceed in different ways. First decision. Since the sum of the areas of the figures is 25, then one of the resulting figures has an area of ​​no more than 12. According to the previous problem, its perimeter is no more than 2 12 2 26. A contradiction.
