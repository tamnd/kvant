---
id: 2008-3-raygorodskiy-rubanov-koshelev-hromaticheskie-chisla-fc9387de
issue: kvant_2008_3
year: 2008
number: "3"
title: Chromatic numbers
authors:
  - Райгородский А. М.
  - Рубанов О. И.
  - Кошелев В. А.
rubric: osnovnye-stati
page_first: 15
page_last: 22
page_labels: 13, 20
tag: BQTO
lang: en
source: kvant_digital
extraction: native
content_sha256: 7a3872231945713e97a4fbad770d9859397ad55dd06674a08fc85f2bb53575db
prompt_sha256: draft-1
translated_from: content/ru/2008/03/articles/02_raygorodskiy-rubanov-koshelev-hromaticheskie-chisla-fc9387de.md
source_content_sha256: 7961fb88bf23dfdcba543d9ead0d81329f13e31870d1d26c7df185cf64656664
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 13⟧

Chromatic numbers

A.RAIGORODSKY, O.RUBANOV, V.KOSHELEV

Introduction and problem statement

Modern mathematics is an almost boundless science. It takes years to become even superficially familiar with its great variety of sections, and even several lifetimes will not be enough to understand all the problems that arose in mathematics at different times. However, in this endless sea of ​​tasks there are also unique “beacons” - tasks that for many years determined the development of the areas within which they appeared. These beacons help the mathematician choose the right direction of movement. One of these beacons is the chromatic number problem - this is what we are going to talk about in this article. It belongs to one of the most popular, and in our opinion, one of the most beautiful sections of mathematics - the section that is now commonly called combinatorial geometry. Essentially, combinatorial geometry is the science of the combinatorial properties of geometric objects. It became an independent discipline only in the 20th century, and chromatic numbers, it should be noted, contributed a lot to this. Here is the problem: what is the minimum number of colors required for such a coloring of the plane (we will call it regular) such that the distance between points of the same color cannot be equal to 1? We will call the mentioned smallest number of colors chromatic $числом.^{1}$ At first glance, the question just posed is completely elementary, but we will gradually become convinced that this question is very deep and non-trivial. First of all, I would like to understand what “plane coloring” is. Surely the inexperienced reader immediately imagines something like what is depicted in figure 1. However, there are much more

⟦figure⟧

Fig. 1

tricky situations. Let, for example, a point x on the plane have coordinates $x_{1}, x_{2}$ (we will write in the future $x = ( x_{1}, x_{2} ) ).$ Let's say that the point is “blue” if the numbers $x_{1}, x_{2}$ are rational; otherwise

1 The word "chromatic" is of Greek origin. It actually translates to “colored” or “colored.”

⟦column⟧

Let's call the point “red”. A two-color painting of the plane appears, which cannot be painted so easily. It is also apparently worth recalling that the distance |x – y| between points $x = ( x_{1}, x_{2} )$ and $y = ( y_{1}, y_{2} )$ on the plane is usually found using the formula x - y =

$( x_{1} - y_{1} )^{2} + ( x_{2} - y_{2} )^{2}$.

Let's agree on notation. In mathematics, a plane is usually denoted by the symbol $R^{2}$. At the same time, the word "chrome" in Greek begins with the letter $\chi$ ("hi"). Therefore, for the chromatic number

( ) the notation $\chi R^{2}$ is adopted. And finally, a brief history of the problem. It was staged in 1950 by E. Nelson, who was then 17 years old. This is very curious and should inspire the young reader: if seventeen-year-old Nelson was able to pose such an important question for the development of science, then why shouldn’t I, the reader, dare? Very similar problems were considered by the famous geometer G. Hadwiger in the 40s of the 20th century; however, firstly, Nelson did not know about this, and most importantly, it was he who gave the modern formulation of the problem - in terms of colorings. The publications of M. Gardner, P. Erdős and the same G. Hadwiger brought enormous popularity to the Nelson problem. A very interesting historical essay on this topic can be found in A. Soifer’s note ([1]); There is also a brochure by A.M. Raigorodsky [2] and his article [3]. We will move on to studying the chromatic number.

A small retreat

As we now know, Nelson's task is to correctly paint the plane using the least amount of paint in the “palette”. We will have time to see how difficult this task is. Therefore, it is reasonable to first try your hand at solving a similar problem for the case of an ordinary straight line. What is proper straight painting? Yes, the same thing, in general, as before: you just need to require that the same-colored points (numbers) x, y are not separated from each other by a distance of 1, i.e. so that the value |x – y| was not equal to one. Obviously, if you paint a straight line one color, then there will be a lot of “X’s” and “I’s” for which the above condition is violated. This means that to properly paint a straight line you need at least two colors. On figure 2 such painting is clearly indicated.

⟦folio 20⟧

KVANT 2008/№3

vim $v_{3}$ (Fig.21, c), using $v_{3}$ and $u_{5}$ we will reproduce $v_{2}$ (Fig.21, d), and using $v_{2}$ and w we will recreate $v_{1}$ (Fig.21, d). The length of the segment $v_{1} v_{5}$ is equal to 0.98... This is almost unity, and yet the edge $v_{1} v_{5}$ is not in any distance graph on the existing set of vertices. However, the following is true. You can “move” the point $v_{5}$ in such a way, keeping the distance between it and the point y equal to one, that as a result of constructions similar to those done above (see Fig.21), a distance graph $G_{2}$ on figure 22 arises, in which with the edge $v_{1} v_{5}$ all

⟦figure⟧

Fig. 22

in order. Calculations show that the “correct” coordinates of the point $v_{5}$ are (0.3..., 0.285...). We leave the substantiation of the fact we postulated, as well as all accompanying calculations, outside the scope of this article. They are rather of a technical nature (after all, the coordinates of all points can be found, if necessary, with any predetermined accuracy), and to understand the meaning of the construction, the clarity of the last figure is quite sufficient. It can be seen, in particular, that the graph $G_{2}$ has fourteen vertices, twenty-three edges and does not contain triangles. Let's rotate the entire structure $G_{2}$ 90 degrees around the center of the square. The result is graph $G¢_{2}$. Volume

⟦column⟧

What's next?

In fact, everything is just beginning with the result of O'Donnell and Hochberg. Firstly, it can be noted that, in proving this result, we paid attention only to those single segments that we needed to justify the inequality $\chi ( G )$ ³ 4. Triangles did not form from them, and that’s great. In fact, other edges could well have appeared on the twenty-three vertices, so if we tried to consider all of them, then the chromatic number, of course, would not have become smaller, but triangles, of course, could have appeared. It is out of a reluctance to bother with (possible) extra edges that we made the appropriate assumption regarding the definition of a distance graph. In fact, the result of the previous paragraph remains valid even without this assumption. The proof just becomes a little more technically difficult. Interested

Fig. 23

Drawing columns $G_{2}$ And $G¢_{2}$ (without adding new edges), we finally form the graph $G_{3}$ with twenty-three vertices and forty-two edges. (Here 23 = 14 + + 14 – 5, since the vertices of the square and its center remain in place when rotated; similarly, 42 = = 23 + 23 – 4, where 4 is the number of edges of the square.) A boring check shows that $G_{3}$ looks exactly like it is pictured figure 23. There are no triangles in it either. Isn't it much more sophisticated than a spindle? Well, that's the price to pay for the lack of triangles. Let us now show that $\chi ( G_{3} )$ ³ 4. Indeed, let the vertices of the graph $G_{3}$ painted in three colors correctly (vertices connected by an edge are multi-colored). Let's call the colors red, yellow and green. It is clear then that either the points y and w are the same color, or the points x and z are the same color. Let's consider the first case. We have the right to believe that y and w, for example, are red. Suppose $u_{5}$, on the contrary, is not red - let's say it is yellow. Then by all means $u_{1}$ green (due to ribs $wu_{1}, u_{5} u_{1} ), u_{2}$ yellow (ribs $u_{1} u_{2}$ And $yu_{2} ), u_{3}$ green (ribs $u_{2} u_{3}$ And $wu_{3} )$ And $u_{4}$ yellow (see Fig.20, f). So, for the same reasons $u_{5}$ green, and a contradiction arises. So, the vertices of $u_{5}, w$ red. Let's look at the pentagon $v_{1} v_{2} v_{3} v_{4} v_{5}$. Vertex $v_{1}$ is connected by an edge to w, and therefore it is not red. Between the peaks $v_{2}$ And $u_{5}$ the edge also passes through, and this does not allow $v_{2}$ have a red color. Similar reasoning shows that the three remaining vertices of the pentagon must be yellow or green. Therefore, the pentagon is painted in two colors. But this is obviously impossible, and we have a contradiction with the correctness of the original painting. The case when points x and z are the same color is dealt with in exactly the same way (this is why we did the rotation). Thus, $\chi ( G_{3} )$ ³ 4, and the trick is in the bag: count $G_{3}$ - sought after. Note that it is not difficult to color $G_{3}$ in four colors, so of course $\chi ( G_{3} ) = 4$.
