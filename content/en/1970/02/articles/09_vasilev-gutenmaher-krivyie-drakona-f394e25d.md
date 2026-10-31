---
id: 1970-2-vasilev-gutenmaher-krivyie-drakona-f394e25d
issue: kvant_1970_2
year: 1970
number: "2"
title: Dragon Curves
authors:
  - Васильев Н. Б.
  - Гутенмахер В. Л.
rubric: osnovnye-stati
page_first: 38
page_last: 48
page_labels: 36-46
lang: en
source: kvant_digital
extraction: vision
content_sha256: df33411a562129b5041b6b2ae8f3e6a60b58058071e1626fbeaebc6512459211
prompt_sha256: draft-1
translated_from: content/ru/1970/02/articles/09_vasilev-gutenmaher-krivyie-drakona-f394e25d.md
source_content_sha256: 4f832c953c85640d6bdc25922f42c0451a91abc1a49970209bd690b8dd1d4dae
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 36⟧

---
running_head:
folio:
---

CURVES
DRAGON

From this article
you will learn about interesting things
personal family,
one of which
drawn here
and several others -
on pages 42 and 43.

N. B. VASILIEV, V. L. GUTENMACHER

⟦folio 37⟧

WHAT IS CURVE AND BROKEN
DRAGON

Take a long strip of paper, fold it in half and in half again. Place the folded strip edge-on on the table and unfold it so that the angle at each fold is 90° (Fig. 1). If you look from above, you can see the broken line shown in Fig. 2, a or 6.

When the strip is folded in half three times, significantly different broken lines are obtained (Fig. 2, in or 2) depending on how the strip is folded. If you fold the strip four times or more, and then unfold its stibs to right angles, you can get many different broken lines. Fig. 3 shows one of the broken lines resulting from five folds in half.

In practice, you will not be able to fold a strip of paper more than seven times - after all, even with the eighth folding, you would end up with $2^8 = 256$ layers! However, we will soon learn how to draw quite long such broken lines without a strip. On page 38 (below) one of the broken lines has already been drawn, which would be obtained if the strip was folded 12 times. It consists of $2^{12} = 4096$ links.

It is easy to see that if you fold a strip more than three times, then after some of it is unrolled, its corners will definitely “touch” each other (Fig. 2, in and Fig. 3). Due to numerous such touches, a mesh is obtained in places along broken lengths. To figure out how a broken line goes, you can round its corners (as shown in Fig. 3 colored lines). If you do this for the broken line shown under figure 3, you will get the intricate line drawn on the previous page. This figure suggested the name “dragon curves” to the American physicist John Heighway. Anyone who has ever seen a dragon might believe that it looks exactly like this.

⟦folio 38⟧

This kind of broken line (“Main Dragon Line”) is obtained if you start from a segment and turn the previous broken line in the same direction each time. (This corresponds to the method of folding in half, shown on Fig. 2 a, c; here the strip is folded “from right up to left” each time.) On Fig. 3 the beginning of this broken line is shown (32 links), on this figure there are 4096 links. If the broken line is continued in the same way further, then it will slowly go around its origin, making one full turn per 8 “doubles”. The red dots lie on a logarithmic spiral (for those familiar with the polar coordinate system, we can write its equation: $\varphi = \log_a r$, where $r$, $\varphi$ are polar coordinates; $a = a^{2:\pi}$).

⟦folio 39⟧

HOW TO DRAW LONG
BROKEN DRAGONS?

We will call any broken line obtained from a piece of paper folded in half $n$ times, unfolding the folds up to $90^\circ$, a dragon's broken line $n$. Let's find out how broken dragons are arranged and how to draw them for large enough $n$.

First way

The broken dragon wound $n$ consists of $2^n$ links and accordingly has $2^n-1$ vertices (not counting the ends). Thus, it has a middle vertex on $(n>0)$ as well, since the number of vertices is odd. On Fig. 2 and 3, the middle vertex of each broken line is offset by a green circle. It can be noted that each of these broken lines consists of two identical pieces, obtained from each other by turning by $90^\circ$. It turns out that this is a general pattern.

Theorem 1. If you continue any broken dragon wound $n$ with end at point $O$ can also be a polyline obtained from this by rotating by $90^\circ$ around the point $O$, then you get a broken dragon wound $n+1$, and back, love breaking the dragon wound $n+1$ comes from some broken wound $n$ this way.

In fact, let's say we want to fold the strip $n+1$ in half. First, fold it in half once. Then its two halves coincide and, when further folded, will bend in half perfect (Fig. 4). Now let's expand on $90^\circ$ the last $n$ stibs of the strip. We get two matching broken dragon wounds $n$; All that remains is to separate them by $90^\circ$ - and we will get a broken dragon wound $n+1$ (Fig. 5). Think about how to derive both statements of Theorem 1 from these messages.

Using Theorem 1, it is easy to draw long polygonal dragon lines.

Since the drawing of the dragon follows the lines of a square grid, it is convenient to draw it on checkered paper.

Let's take any short dragon line (for example, just a segment). Let's agree that one of its extreme points is the beginning, and the other is the end. Let's continue it with the same broken line, rotated relative to its end by $90^\circ$ clockwise (or counterclockwise). We continue the resulting new broken line from the end in the same way; We do this as many times as we want and as much as we can. This can be done automatically and quickly if you have tracing paper or, even better, slightly transparent checkered paper at hand. (Think how!)

Obviously, in the same way we can immediately draw both the sides and necks of the dragon: we only need to round off the middle mushroom each time.

The remarkable property of all dragon curves is that they do not intersect themselves, or, what is the same, dragon curves never pass along the same segment twice. Thus, although the dragon's breaker can pass through the same point (the vertex of the grid) twice, it does not hit the same point more than twice.

⟦folio 40⟧

From Theorem 1 it is not immediately obvious how to prove that dragon lines do not pass twice along the same segment - on the contrary, the longer and more intricate broken lines or curves you draw, the more surprising is how well their “protrusions” and “valleys” fit together (see the “locomotive” dragon curve on page 43).

However, it is not difficult to prove this *), using another theorem about the “doubling” of dragon polygons, which, by the way, gives one way to draw long polygons.

Second way

On Fig. 6 the vertices of the black dragon lines are connected by red segments through one another. We see that the red segments again make up the broken lines of the dragon. It turns out that this is also a general pattern.

To formulate it precisely, then also that each red segment is the hypotenuse of an isosceles right triangle, the legs of which are the links of the original broken line (at figure the triangles are slightly shaded), and every two adjacent such triangles are obtained from each other by a rotation of 90° around their common vertex; in other words, if you go along the red broken line of the dragon, then these

*) See problem 9 at the end of the article.

triangles will appear alternately on the right and then on the left.

Theorem 2. If on each link of the dragon's polyline n, as a zinotenuse, we construct a right-angled isosceles triangle, and in such a way that for two adjacent links these triangles are one of two by rotating by 90° relative to the common vertex, then the stones of the constructed triangles constitute the dragon's polyline n+1. And vice versa, each broken line n+1 can be obtained in this way from some broken line n.

In fact, let's follow the last one and folding the strip in half. For convenience, we will refer to the conditional Fig. 7. We want to fold the strip in half n+1 times. Let's first fold it n times and draw it in profile (red line at Fig. 7). Then fold it in half again and rotate this last fold 90° (black line on the same figure*). The paper goes from mushrooms A to mushrooms B and back not along the hypotenuse, but along the legs of an isosceles right triangle ABC. Let's unfold all other folds

Fig. 6

the segment is the hypotenuse of an equilateral right triangle, the legs of which are the links of the original broken line (at figure the triangles are slightly shaded), and every two adjacent such triangles are obtained from each other by rotating by 90° around the vertex point; in other words, if you go along the red broken line of the dragon, then these

up to 90° (at Fig. 8 it is shown how a separate fold will unfold). Then the stones of the rectangles form the dragon's broken line n+1, and the hypotenuse forms n.

Using these messages, it is easy to prove both statements of Theorem 2. You can try to give another proof: derive Theorem 2 from Theorem 1.

*) On our figure the black line is $\sqrt{2}$ times longer than the red one, but this does not matter since we are interested in the shape of the broken line, not its size.

⟦folio 41⟧

Using Theorem 2, from each dragon's broken line of rank $n$ one can obtain two different broken lines of rank $n+1$: it all depends on which side of the first link to complete the triangle.

Please note that when we move from a broken line of rank $n$ to a broken line of rank $n+1$ according to Theorem 1, the broken line becomes twice as long, and the length of each link does not change; if we use Theorem 2 for “doubling,” then the length of the broken line increases by $\sqrt{2}$ times, and the length of the link decreases by $\sqrt{2}$ times.

Now practice drawing polygonal dragon lines using Theorem 2.

WORDS

The property discussed in Theorem 2 can be explained quite simply if we look at dragon lines (or, if you prefer, at ways of folding a piece of paper) from a slightly bluer point of view.

Let the turtle crawl along the dragon's broken line (Fig. 9). Every time she gets to the top, she has to turn $90^\circ$ left or right. From the turtle's point of view, its path will be determined by a sequence of turns. For example, for a broken line at Fig. 2, $a$ (starting at the red dot), this sequence will look like this: left, left, right.

We will denote a turn to the right by the letter $R$, a turn to the left by the letter $L^*$). Then the entire broken line will be written in the following “word”:

LLR

(“a word” in many branches of mathematics and logic simply means any sequence of letters). In the same way, you can write any dragon line as a word from the letters $L$ and $R$.

To get the broken line $a$ from the broken line $\delta$ (Fig. 2), you need to fold the piece of paper one more time “to the left” (see Fig. 2, $\delta$ and 10). In this case, between each two vertices of the broken line $a$ there will be one more turn, and at Fig. 10 it is clearly seen that these new turns will be through

*) We chose the first letters of the English words right (right) and left (left), because the Russian letters P and L are too similar to each other (by the way, the German Rechts and links begin with the same letter).

⟦folio 42⟧

This curve is obtained if, starting from the segment, the “doubling” process is repeated 12 times, and through turns clockwise and counterclockwise. To better show how this curve goes, we rotate each time not by 90°, but by 95° (black line); if you reduce the angles to 90°, you get the dragon curve, which is depicted on the same figure colored line; it fills an equilateral right triangle with a uniform pattern.

⟦folio 43⟧

This rank 12 dragon curve has the special name "Father, Mother and Son". Find its middle. Can you imagine that the curve develops from this point into two perfectly identical pieces, resulting from each other by turning 90°? To believe this, we will have to faithfully trace the curve with a colored pencil from beginning to middle.

Here, one of the two halves, the curve (“it’s called the “locomotive”), is drawn on a colored background to show how these two curves “stage” each other. One half, after rotating it 90° around the midpoint, will coincide with the other

⟦folio 44⟧

to give in; thus we get
$$L L R \rightarrow L L R L R R,$$

i.e., words that are a recording of broken line 6. With one more bend to the left, we would get a broken line characterized by the word

$$L L R L L R R \rightarrow L L R L R L R R,$$

Draw this broken line. This is the main broken line of a rank 4 dragon. If you want, twist the corners of it, as Heiwei suggested.

If you continue the same operation on the last word received again (starting the sequence of interlaced letters again with $L$), you will get words of 31 letters - a record of the Main Dragon Line of rank 5, shown at Fig. 3.

Of course, the sequence of intersecting letters can begin not with $L$, but with $R$ - this will result in other broken lines.

It is easy to see that our method of constructing a word for a broken line of rank $n+1$ from a word for a broken line of rank $n$ exactly corresponds to the geometric method of doubling, which is discussed in Theorem 2 (new letters correspond to enough verbs). In general, the entire “theory” of broken dragon lines could be built not geometrically - using rotations, obtaining triangles, etc., but “algebraic” - using operations on words from two

Fig. 10

letters $L$ and $R$, “records” of broken dragons *).

The reader will be able to partially follow this path and get acquainted with a number of interesting patterns that words have - records of dragon curves, solving the following problems.

TASKS

1. How long do you need to take a strip so that, after folding it in half 30 times, you get a distance between adjacent folds of 1 cm? Are the distances from the Earth to the Moon larger or smaller?

2. How will the dragon's line change if the strip of paper is placed on the table with the other edge? How will the words that write the broken line change?

3. a) How many different (not similar to each other) broken dragons of rank 4 are there? Draw them all. Write the corresponding words from the letters $L$ and $R$.

6) How many different broken lines of rank $n$ are there?

4. Let's say that the turtle crawled along the dragon's broken line and found words from the letters $L$ and $R$. What word will she read if she crawls along this broken line in the opposite direction?

5. Let $s$ be some word from the letters $L$ and $R$. Let us denote by $s$ the words that will be obtained from $s$ if we rearrange the letters in it in the reverse order and then place $L$ on $R$ and $R$ on $L$. (For example, if $s=LLR$, then $s=LRR$).

Let $s$ and $t$ be some words from the letters $L$ and $R$. We will denote by $st$ the words obtained if the words $s$ and $t$ are written side by side. (For example, if $s=LLR$, $t=RL$, then $st=LLRRL$).

Prove that:

a) For any words $s$ and $t$

$$\overline{st} = \overline{t} \overline{s}.$$

6) If $s_{n+1}$ are words corresponding to the dragon line of rank $n+1$, then

$$s_{n+1} = s_n x \overline{s}_n,$$

where $s_n$ are some words corresponding to the dragon's polyline of rank $n$, and $x$ are words corresponding to one letter.

*) It was this method of presentation that was chosen by the Canadian mathematicians Knuth and Davis, from whose manuscript “Number representations and dragon curves” (Ch. Davis, D. E. Knuth) the authors of the article first became acquainted with curved dragons. A series of figure length dragon curves are also studied from this manuscript.

⟦folio 45⟧

c) If $s_n$ is a word corresponding to the dragon's line, then $s_n$ differs from $s_n$ only by one middle letter.

d) A word that writes a dragon's broken line of rank $n$ can be constructed in a unique way by arbitrarily specifying $n$ letters that should appear in this word in places with numbers $2^k$, where $k=0,1,2,...,n-1$ (i.e., in the first, second, fourth, eighth,..., $2n^{-1}-m$ places); after that, to find which letter is in the $m$th place, you need to represent $m$ as $m=2^k(2l+1)$, where $k$ and $l$ are integers; if $l$ is even, then the $m$th place has the same letter as the $2^k$th, if $l$ is odd, the opposite letter.

e) Two words $s_n'$ and $s_n''$ define broken dragons of the same shape (similar) if and only if, after crossing out the middle letter, these words either coincide, or one is obtained from the other by replacing $L$ with $R$ and $R$ with $L$. (For example, the words LLRLLRR, LLRRLRR, RRLRRLL define the same broken lines.)

6. Let us have a broken line of a dragon of rank $n$. From it you can obtain two broken dragon lines of rank $n+1$, using either Theorem 1 (taking one or the other end of the broken line as the point $O$) or Theorem 2 (extending the triangle in one direction or the other). Will both cases produce the same two broken dragons of rank $n+1$ or, generally speaking, different ones? How to obtain their words from a word of a given broken line of rank $n$?

7. Two points $A$ and $B$ are given on the plane. Let's draw a square with the center in the middle of the segment $AB$, one of whose sides is equal to $2AB$ and parallel to the segment $AB$. Prove that any dragon line with ends at points $A$ and $B$ lies inside this square. Prove that for any point $M$ inside this square and any positive number $e$ one can find a dragon line with ends $A$ and $B$ that passes from the point $M$ at a distance less than $e$ (in mathematical language, “the union of all dragon lines with ends at the points $A$ and $B$"). Its first $2^n$ links form a broken line of rank $n$.

Prove that:

a) The end of such a broken line of rank $n$ will be at the point

$$\left( \frac{n}{2} \cos \frac{\pi n}{4}, \frac{n}{2} \sin \frac{\pi n}{4} \right)$$

(red dots on figure on page 38).

⟦folio 46⟧

---
running_head:
folio:
---

6) The word that is the recording of this broken line can be quickly written like this. First, we write the letters $L$ and $R$ through the numbers, leaving spaces between them for the missing letters:

$$L_R_L_R_L_R_L_R_L_R...$$

and then we proceed as follows. With the finger of our left hand we point to the first letter, and with our right hand we write it in the first gap, then with our left hand we point to the second letter, and with our right hand we insert it into the second gap, with our left into the third... and so on sequentially through all the letters (without missing new ones), and with our right hand we insert each indicated letter into the first free gap.

$$LLRLLRLLLRRLRLLLRL$$

c) If, as in Problem 10, we release four main broken lines of rank ∞ from one point, then along each segment of the grid exactly one link of one of these broken lines will pass (Fig. 11).

(This is a difficult theorem; it was first proved by D. E. Knuth.)

Fig. 11.

LITERATURE

M. Gardner, Mathematical games, Scientific American 216, 1967, March (124-125), Appel (118-120), July (115).
