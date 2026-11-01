---
id: 1987-9-tabachnikov-soobrazheniya-nepreryivnosti-be3e63dd
issue: kvant_1987_9
year: 1987
number: "9"
title: Continuity considerations
authors:
  - Табачников С. Л.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 47
page_last: 52
page_labels: 45-50
tag: XQK0
lang: en
source: kvant_digital
extraction: vision
content_sha256: a7711df86605ce79b0a57c862c9a33d038dfcd0baaf2934af18d216c89245096
prompt_sha256: draft-1
translated_from: content/ru/1987/09/articles/17_tabachnikov-soobrazheniya-nepreryivnosti-be3e63dd.md
source_content_sha256: 9f2bfb51797c3e5fe2d908a99f2ef2d03f8e488b220413ea8721a7963e93d48d
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 45⟧

Continuity considerations

S. L. TAVACHNIKOV

Most problems from a school mathematics textbook require solving an equation, finding the value of some quantity, constructing a figure with given properties, etc. This article is devoted to problems of a different kind - they only require proving that the desired root, number, figure, etc. exists. The solution method we will use is continuity considerations.

Problems about plane figures

Let's start with this task. There is a certain figure on a plane. Prove

Fig. 1.

know that there is a vertical line dividing its area in half.

Let's take a vertical line located to the left of this figure (Fig. 1, a), and begin to move it to the right. At some moments the straight line will touch the border of the figure (Fig. 1, b), then it will slide along the figure (Fig. 1, ​​c-e) and finally end up to the right of the figure (Fig. 1, g). How does such a movement change the area of ​​that part of the figure that lies to the left of the straight line (the blue part at figure 1)? This area continuously changes from zero (Fig. 1, a) to the area of ​​the entire figure S (Fig. 1, g). Consequently, at some points this area is equal to half the area of ​​the entire figure. At this moment, a vertical line divided the area of ​​the figure in half.

⟦folio 46⟧

Discussion is the decision. Firstly, it does not make it possible to construct the desired straight line, but only proves its essence in the form of a given, completely arbitrary figure.

Secondly, our solution shows that there is a straight line of any direction dividing the area of ​​the figure in half. Moreover, it also follows from the solution that a straight line passing in a given direction and dividing the area of ​​the figure in half is determined in a unique way. We will use this one in the future.

Let's look at our solution from a slightly different point of view. Let us choose the number axis (Fig. 2, a) on the horizontal plane. The position of an arbitrary vertical line $l$ is characterized by the number $x$ (the point at which the line $l$ intersects the axis). Distance the area of ​​the part of the figure lying to the left of the straight line $l$ as a function of $f(x)$. The graph of this continuous function is shown in figure 2, b). Finding a straight line dividing the area of ​​a figure in half means finding the point $c$ on the numerical axis for which $f(c)=S/2$.

Consider on figure 2, b) the horizontal line $y=S/2$. The left end of the graph of the function $f(x)$ lies below the straight line, and its right end lies above, since $f(a)=0<S/2$ and $f(b)=S>S/2$. Therefore, there is a point of intersection of the horizontal line $y=S/2$ with the graph $f(x)$. At this point the equality $f(c)=S/2$ is satisfied.

The property of continuous functions that we used in solving the problem is called the intermediate value theorem:

Between two values, a continuous function takes all intermediate values.

Vollee formally: if $f(x)$ is a continuous function on the interval $[a; b]$ and $c$ is some number contained between $f(a)$ and $f(b)$, then on the interval $[a; b]$ there is a point $x_0$ such that $f(x_0)=c$.

For example, in our problem, the function $f(x)$ takes the value $S/2$, contained between $f(a)=0$ and $f(b)=S$.

The intermediate value theorem is almost obvious. And like many obvious statements, it is not entirely easy to prove. To prove this we would have to go deeper into the definition of a continuous function and a real number. We are aware that we are too far from the topic of our article, so the intermediate value theorem remains simply obvious to us. And one more thing: we did not prove that the area of ​​the part of the function lying on the line depends continuously on the position of this line (i.e., that $f(x)$ is a continuous function). This is also almost obvious; and in other problems of this article we will not separately prove the continuity of the functions arising during the solution.

Exercise
1. a) Given a convex figure*) and a point at eee. Prove that there is a line passing in a given direction and dividing the area of ​​the figure in half.
6. What will the previous problem turn into if the point tends to infinity?
b) Solve step a in the case when the point lies inside the figure.
d) Is it true that in parts a and b there is only one straight line?
2. a) Given two convex figures (maybe intersecting). Prove that there is a line dividing the area of ​​each figure in half.
6) What will this problem turn into if one of the figures shrinks to a point?

*) A convex figure, together with any two points, contains the whole and the segment connecting them. For example, a circle is a convex figure, but a circle is not.

Fig. 3.

⟦folio 47⟧

Why is the stool square?

Imagine that your kitchen floor is not very robust (this is usually the case, especially if it is covered with linoleum). Therefore, a square stool stands on the floor only with its legs while the quadruple leg hangs in the air. Is it possible to move the stool so that it stands on the floor with all four legs, or can it happen that, no matter how surprised you are, the stool will still rock? We assume, of course, that when the stool stands firmly on four legs, its surface may be slightly inclined in relation to the floor.

(Before you begin the mathematical solution to this problem, conduct an experiment in your kitchen. After this experiment gives a positive answer to our question, move on to the mathematical solution of the problem.)

We will assume that the floor surface, although not flat, does not differ too much from flat. This assumption allows the use of floors of “pathological” shape - such as, for example, the floor of a cave covered with stalgites, that is, lime icicles growing upward.

So, let the stool have legs A, B and C on the floor, and the quadruple leg D hanging in the air (Fig. 4; a).

Without lifting legs A and C from the floor, place the stool on top of a relatively straight AC so that legs B and D are in the air at an equal distance from the floor (Fig. 4, b); there is no distance to the floor along the direction of the legs). In this position (two legs of the stool are on the floor, and the other two are at an equal distance from the floor), the stool can be moved.

Let's imagine that the floor is made of dam and the legs of the stool can freely pass through it. Let's lower the stool in the direction of its legs so that legs B and D are on the floor, and legs A and C are below the floor surface and at an equal distance from it (Fig. 4, c).

Let's start turning the stool around the center counterclockwise from position 4, b, without lifting legs A and C from the floor and maintaining an equal distance from legs B and D to the floor. After rotating by 90°, legs A and C will take the position of legs D and B at figure 4, b, and legs B and D will take the positions of legs A and C, respectively, at figure 4, b. As the stool moves, the distance from legs B and D to the floor changes continuously. At the initial moment - figure 4, b - this distance is positive, since the legs are above the floor surface, and at the final moment, shown at figure 4, b, it is negative, since the legs are below the floor surface. Consequently, there was a moment when this distance was equal to zero. At that moment the stool stood on all four legs.

What we found has not only theoretical, but also practical value - by turning the stool 90° around the center, you can find a stable position. Test this experimentally. And one more note. What we found is based on the fact that the legs of the stool are located at the vertices of the square. If they were located at the vertices of a line

⟦folio 48⟧

A square or another quadrilateral, our reasoning would not work. The author does not know whether the statement of the problem is true for quadrilaterals other than a square (in any case, it is clear that the quadrilateral must be inscribed in a circle). If any of the readers can figure out this issue, be sure to let us know.

Exercise

7. The teacher asked to prove that a convex figure can be divided by a pair of mutually perpendicular lines into four equal-velocity parts. One student suggested this solution. “In any direction one can draw a single straight line l dividing the area of ​​the figure in half (Fig. 5, a). Each of the resulting flat figures can be divided into two equal-velocity parts by straight lines perpendicular to l (Fig. 5, b). Let's start changing the direction of straight line l, maintaining the appearance of the drawing. After changing direction by 180°, points A and B are swapped. This means that at some point they coincided. At this moment, figure 5, b will turn into figure 5, c and we will obtain the desired pair of perpendicular straight lines, dividing the area of ​​the figure into four equal-vector parts.

a) Find the error in this solution.
b) Come up with the correct solution to the problem.

8. Prove that a square can be written into a centrally symmetrically convex figure. (In fact, a square can be written into any figure. But to prove this theorem of the outstanding Soviet mathematician L. G. Shirelman (1905-1938), continuity messages alone are no longer enough.)

9. Given two convex figures, one of which lies inside the other. Prove that:
a) there are two parallel chords of the external figure that touch the internal figure and have the same length (Fig. 6, a);
b) there is a point X of the external figure from which two equal tangent chords will be drawn to the internal figure (Fig. 6, b).
Decree and e. Among the chords of the outer figure that touch the inner one, there is a chord of the greatest length. Draw tangents from its ends to the inner figure.

10. Three convex figures are given, extending into each other (Fig. 7). Prove that there is a point X of the outer figure from which a tangent chord can be drawn to the inner figure so that the segments contained in the middle figure are equal.

On the roots of polynomials and chords of graphs of functions

You, of course, know that a square triangle may not have roots - such, for example, is the polynomial x²+x+1. What about cubic polynomials? Now we will prove that

every cubic polynomial has at least one root

Let us first consider a cubic polynomial with leading coefficient 1:

f(x)=x³+bx²+cx+d

Let's write it in this form: f(x)=x³(1+b/x+c/x²+d/x³). If the values ​​|x| is very large, then the terms b/x, c/x² and d/x³ become very small. Therefore, the number in the bracket is close to 1 and, in any case, positive. Therefore, the sign of f(x) for large |x| is determined by the sign of the number x³. Thus, f(x)<0 for large negative x in absolute value and f(x)>0 for large positive x.

A cubic polynomial, like any polynomial, is a continuous function. Therefore, the intermediate value theorem can be applied. It follows from it that there is an x ​​such that f(x)=0. Therefore, the cubic polynomial has a root.

The case of the general cubic polynomial f(x)=ax³+bx²+cx+d is similar to what has already been discussed: it is enough to divide f(x) by a.

Our proof of goodness or prostates the merger and weakness of continuity messages. We have “for free” received a non-obvious statement about the existence of a root, but it remains unclear how the root for a specific polynomial is on it (formulas for the roots of a cubic polynomial exist, but ... this is a completely different matter, and we will not touch on it).

⟦folio 49⟧

Another example. Let $f(x)$ be a continuous periodic function on the line with period $T$. Prove that its graph has a horizontal chord of length $T/2$.

The existence of a horizontal chord of length $l$ is equivalent to the equality $f(x)=f(x+l)$ (Fig. 8). Therefore, we need to prove that there is $x$ such that $f(x+T/2)=f(x)$. In other words, we need to prove that the function $g(x)=f(x+T/2)-f(x)$ has a root, i.e. $g(x)=0$ for some $x$.

Let's take an arbitrary number $a$. If $g(a)=0$, then everything is proven; so assume that $g(a)\neq 0$. For the definition, we will assume that $g(a)<0$. Let $b=a+T/2$. Let's find the value of $g(b)$:

$$g(b)=g(a+T/2)=f(a+T/2+T/2)-f(a+T/2)=f(a+T)-f(a+T/2)=-f(a)-f(a+T/2)=-g(a).$$

So, $g(b)>0$.

The function $g(x)$ is continuous, like the difference of continuous functions. Therefore, we can use the intermediate value theorem. From this theorem it follows that between the numbers $a$ and $b$ there is a $x$ such that $g(x)=0$.

The statement about the horizontal chords of the graph of a periodic function can be known successfully: the graph of such a function has a horizontal chord of arbitrary length.

But with graphs of continuous functions on a segment the situation is different. Let a continuous function be given on a segment of length $T$ whose value at the ends of the segment coincides.

Fig. 6.

Fig. 7.

Then if the number $l$ has the form $T/n$ for some natural number $n$, then the graph of the function necessarily has a horizontal chord of length $l$; if $l$ is not of this form, then there is a continuous function with identical values ​​at the ends of the segment, the graph of which does not have horizontal chords of length $l$. (You will find a detailed story about this in the article by I.M. Yaglom “On chords of continuous curves”, «Kvant», 1977, No. 4.)

Tasks

11. Prove that a polynomial of odd degree has a root.

12. Yesterday at full it was colder than at full the day before yesterday and today. Prove that there is one and the same moment in time today when the temperature was the same.

13. Let $f(x)$ be a continuous function on a certain segment, and let all values ​​be assigned to the same segment. Prove that there is a $x$ such that $f(x)=x$.

14. The polynomial $f(x)=ax^2+bx+c$ is such that the equation $f(x)=x$ has no solution. Prove that equation $f(f(x))=x$ also has no solution.

15. Let $f(x)$ be a continuous periodic function on the line with period $T$. Prove that its graph has a horizontal chord of arbitrary length.

17. The average value of the function $f(x)$ on the segment $[a; b]$ is the value $\frac{1}{b-a}\int_a^b f(x)dx$.

Prove that if the average value of a continuous function on a certain interval is zero, then it takes on a zero value on this interval.

18. Consider a function of the form $f(x)=a_1\sin x+a_2\sin 2x+\dots+a_n\sin nx+b_1\cos x+b_2\cos 2x+\dots+b_k\cos kx$, where $a_1, \dots, a_n, b_1, \dots, b_k$ are some coefficients. Prove that the equation $f(x)=0$ has a root.

Conclusion

We analyzed several problems in the solution of which continuity considerations played a major role. In every

⟦folio 50⟧

In one of the problems, the quantity we were interested in depended on one parameter - for example, the area of ​​a part of a figure lying on one side of a straight line depended on the angle of inclination of this straight line. Continuity messages can be extended to the case where there is more than one parameter. A detailed discussion about this is not part of our plans; Let us limit ourselves to the formulation of a few theorems.

1. Three bodies are randomly located in space. There is a plane that divides the volume of each body in half. This statement is known as the “ham sandwich theorem” (the first body is a piece of bread, the second is a layer of butter, and the third is a slice of ham).

2. There are two such diametrically opposite points on earth at which temperature and pressure coincide.

3. A cube can be described around a convex body. (This theorem generalizes to the case of the space of the statement of Problem 6).

4. Imagine a ball covered with hair. Is it possible to “comb” it in such a way that each hair touches the surface of the ball, and the directions of closely spaced hairs do not differ very much? It turns out that this is impossible - at least one hair remains perpendicular to the surface of the ball. This statement is known as the "hedgehog theorem" or the "ball combing theorem."

5 (for those who know complex numbers). We have proven that a polynomial of odd degree must have a real root. What about complex roots? It turns out that any polynomial (other than a constant) has at least one complex root. This statement of the present is important that it is called the fundamental theorem of algebra. One approach to its proof is also based on continuity messages.

Guess the number

(For the beginning, see p. 34)

Try to answer the following question: “133 teams participate in the volleyball cup competitions, the competitions are held according to the Olympic system; How many games will be played to determine the winner?

At first, each one takes a very long time to count to get the answer, but the solution turns out to be extremely simple. It is enough to note that in each game exactly one team is eliminated, but only one team needs to remain; This means that in order for 132 teams to be eliminated, 132 games must be played.

The same idea is present in solving another popular problem. The chocolate consists of 3x8 pieces. How many breaks do you need to make along the lines to completely break it into pieces? At first they decide to reach a dead end: after all, you can break things in completely different ways! But let's clearly formulate the task. There is one piece of chocolate, you need to get 24 pieces, and with each breaking the number of pieces increases by exactly one. This means that you will have to break it 23 times, and it doesn’t matter in what order you do it.

The publication was prepared by A. P. Savin based on materials from V. A. Dalingar and F. N. Fazylov
