---
id: 1977-7-futer-signalyi-grafyi-i-koroli-na-tore-9ba3f2ae
issue: kvant_1977_7
year: 1977
number: "7"
title: Signals, graphs and kings on the torus
authors:
  - Футер А. Л.
rubric: osnovnye-stati
page_first: 16
page_last: 21
page_labels: 14-19
tag: RLVU
lang: en
source: kvant_digital
extraction: vision
content_sha256: d756525099d45822ced624bd55f5b217e115b62c656139907618b861aca20710
prompt_sha256: draft-1
translated_from: content/ru/1977/07/articles/05_futer-signalyi-grafyi-i-koroli-na-tore-9ba3f2ae.md
source_content_sha256: 45ffcaa2cdeffaa76379f5509a23566fca717e3338c476f64bac8ab63166d167
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 14⟧

A. Footer

Signals, graphs and kings on the torus

The next morning Melefon howls! I jumped up, undressed, grabbed my mrubka and kritsa:
- I’m listening!
And from the village in response:
- Why are you grunting?
- How do I grunt? “I don’t grunt,” I say.
- Stop grunting! Speak like a human! - Mishka shouts.
- I speak humanly. Why grunt?
- Well, enough of my pampering!
Still, I won’t believe that we put a piglet in the room.

N. Nosov. Telephone

then it turns out that some letters are often confused, for example “f” and “s”, “b” and “g”, etc.

It distorts signals from almost every communication method, be it telephone, radio, binoculars. There are different ways to combat this phenomenon, but they all reduce the effectiveness of communication. For example, by telephone you can transmit not individual letters, but connected words: “b” as “Boris”, “g” as “Gregory”, etc. - but then together with one letter we will have to transmit 5-8. It is possible to repeat each signal many times, as, for example, the first photograph of the far side of the Moon was transmitted to Earth in 1959, but it will take the same amount of time. This note explores one cost-effective way to combat signal distortion during transmission*). The idea of ​​this method is simple: if we already know which signals can be confused with which, then we will transmit only one signal from each such group, and refuse the rest. For example, on the telephone, from the sounds “f”, “s”, “sh” - only the sound “s”.

⟦folio 15⟧

Each message usually consists of separate “elementary” signals: words (in a telephone conversation), letters (in a maritime flag signal “semaphore”) or other signs (dot and type on a telephone). Let these signal elements form the set $S$—the input alphabet. Let us select each signal from $S$ as a circle and connect a pair of circles with a segment (“edge”) if the corresponding signals during transmission can be confused with each other. The result is a graph $^*$ with a set of vertices $S$. Let's call it the error graph of our transmitting device.

Let's give an example. The minute hand of an electric clock changes its position first as soon as the next minute ends, the hand jumps to the next one. If this clock is further away from us, then we cannot accurately determine the position of the minute hand. But let us make a mistake every time not very much - no more than for a minute. then the input alphabet will contain 60 elements - 60 possible positions of the minute hand (each of them corresponds to a point on the circle - the boundary of the dial), and the error graph $\Gamma$ will be a regular 60-gon - which point is connected by segments to two neighbors.

Now let’s try to figure out what needs to be done so that we can accurately recognize the number of readings on the minute hand. We pass the clock so that the minute hand jumps every 2 minutes, that is, so that the clock shows only an even number of minutes. then no indication visible to us can be confused with any other - after all, we do not allow errors of 2 minutes or more. Thus, if you realize that the set of transmitted signals is only 30 even numbers from 0 to 58, then all of them will be accurately determined. On the other hand, it is very important that 30 is the maximum value: if in the graph $\Gamma$ we take 31 vertices or more, then somehow two of them will definitely be connected (prove it!).

In this example, we have constructed a set $M$ of graph vertices that has the following property: any two vertices from $M$ are not connected by an edge. Such a set $M$ is called an independent set (I.S.). In our example, any sets of four minute hands are independent, for example: {2, 8, 34, 52, 56}, or a set of readings divisible by 5: {0, 5, 10, ..., 55}.

If the $M$ vertices of a certain graph $G$ contains the most number of vertices among all its $M$, then it is called the most independent set (n.i.s.), and the number $\alpha(G)$ of vertices in it is called the most independent number (n.i.) of the graph $G$.

In the discussion above, the graph $\Gamma$ has many different $M$ and $H, N, M$. - only two (a set of four numbers from 0 to 58 and a set of four numbers from 1 to 59), and $\alpha(\Gamma) = 30$.

If the graph $G$ is the error graph of some transmitting device $A$, then $\alpha(G)$ is the maximum number of different signals that can be transmitted through this device without confusion. Therefore, $\alpha(G)$ is also called the throughput of the device $A$.

⟦folio 16⟧

Alphabet square

With each transmitting device $A$ we associated the input alphabet $S$, the error graph $G$ and the graph independence number $G$ (the throughput of the device $A$) $\alpha(G)$. But what if the device $A$ is set once and for all, and its capacity is insufficient for us? Let's say, if $A$ - the phone number is transmitted by phone letter? The solution is known - this is Morse code: you need to transmit packs of several characters (dots - type) through $A$ and count each such pack as one signal.

First, let's try to transmit two consecutive signals from $S$ through the same device $A$. Let's see how much the elements of any alphabet increase (we will call them letters).

Let's try to determine the throughput of the device $A^2$. To do this, first of all, you need to build an error graph, denoted by $G^2$. Let's see under what conditions the signal $(v_1; v_2)$ can be confused with the signal $(w_1; w_2)$. Obviously, for this to happen, one of the following three conditions must be met:

a) $v_1 = w_1$, $v_2 \sim w_2$;
b) $v_1 \sim w_1$, $v_2 = w_2$;
c) $v_1 \sim w_1$, $v_2 \sim w_2$.

Thus, vertices $(v_1; v_2)$ and $(w_1; w_2)$ of graph $G^2$ are connected by an edge if graph $G$ contains edges $v_1 - w_1$ (or $v_1 = w_1$) and $v_2 - w_2$ (or $v_2 = w_2$). For example, if the graph $G$ contains only two vertices connected by an edge, then $G^2$ is a square with diagonals (Fig. 2).

Problem 3. Construct a graph $G^2$ for each of the graphs $G$ shown in figure 3.

Thus, we can consider that $G^2$ is a “layered” graph: each of its vertical or horizontal layers coincides with $G$, and each edge $a - b$ of the graph $G$ corresponds to a square with diagonals in the graph $G^2$.

Let's try to find some independent set in the graph $G^2$.

Let the set $M$ be independent in the graph $G$. This means that elements from $M$ are not confused with each other when transmitted by device $A$. Then, when transmitting pairs of letters from $M$, none of these letters will be distorted, therefore in the alphabet $S^2$ elements of the form $(a; b)$, where $a \in M$, $b \in M$, are not confused with each other. The set of pairs $(a; b)$, where $a \in M$, $b \in M$, is denoted by the symbol $M^2$. It is easy to see that if $p$ is the number of elements in $M$, then the number of elements in the set $M^2$ is $p^2$. Thus, the throughput of device $A^2$ is at least the square of the throughput of device $A$, that is, in graph language

$$\alpha(G^2) \geqslant (\alpha(G))^2.$$

Note, however, that such an increase in throughput is not given in vain - the signal transmission speed drops by half.

In fact, letters are transmitted slightly differently over the telephone. In principle, for all 33 letters of the alphabet, sets of 6 characters are needed (five-character ones are not enough), but not only accurate

⟦folio 17⟧

Kings on the torus

Let's complicate the graph $G_5$ figure 3 a little: let's glue points 0 and $n$. The result will be $n$-gon 012 ... $(n-1)$. Let us denote this graph by $P_n$. Its square $P_n^2$ will be obtained from the square of the segment if two horizontal and two vertical sides are glued together in pairs. But a square segment is a real square, and if you glue its opposite sides together, you get a torus! More precisely, a grid on a torus containing $n^2$ squares $1 \times 1$ with diagonals (Fig. 4).

If the vertices of these squares are set aside with the cells of the horizon of the board of size $n \times n$, then the neighboring board fields in the chess sense turn out to be connected by grid segments, or, what is the same, by the edges of the graph $P_n^2$, and the problem $M415$ about the maximum number of non-neighboring kings on the torus will turn into the problem of determining the independence number of the graph $P_n^2$. Its solution is given in this issue of the journal (see p. 37).

If you want to imagine the structure of n more clearly. n. m. graph $P_n^2$, solve the following problems.

Problem 4. Let the set $M$ be n. n. m. graph $P_n^2$ (or, what is the same, the horizon of the board $n \times n$). Prove that

a) if $n=2s$, then $M_1^2$, where $M_1$ is some n. n. m. $P_n$, is n. n. m., and $\alpha(P_2s^2) = s^2$;

⟦folio 18⟧

6) if $n=4s+1$, then on each vertical and on each horizontal of the board there will be exactly $s=\left[\frac{n}{4}\right]$ points (kings) from $M$ (here $[a]$ is the integer part of the number $a$);
c) if $n=4s+3$, then on each vertical and on each horizontal of the board there will be either $s$ or $s+1$ points from $M$.

Problem 5. We will represent the graph $P_2^2$ (torus) as a square, remembering that its opposite sides are glued together. The cyclic property of the graph $P_n^2$ is a “parallel transfer” mapping, under which the element (0; 0) goes to $(s; t)$.

Prove that any n. n. $M$ graph $P_2^2$ can be reduced to the form depicted in figure 5, if we resolve the cyclic cdv of the board graph and the symmetrical relation of the diagonal, vertical and horizontal of the square.

Notes. Symmetry with respect to the diagonal (0; 0) $(n-1; n-1)$ of a square can be written by the formula $(x; y) \rightarrow (y; x)$. Cyclic cdviz can be written like this: $(x, y) \rightarrow (x+s; y+t)$, but there will be one inaccuracy in this formula. I would like to put aside the numbers $n$ and $0$, $h+1$ and $1$, etc. For this, the icons $\equiv$ and $(mod n)$ are used. They say that $a$ is comparable to $b$ modulo $n$ and write $a \equiv b$ $(mod n)$ if $a$ and $b$ when divided by $n$ give equal remainders. Let us denote by $a$ $(mod n)$ the remainder of the division of $a$ by $n$. Then we can say that the element $(x; y)$ goes into the element $((x+s) (mod n); (y+t) (mod n))$ under cyclic transformation of the graph, and when deposited with respect to, say, the straight line $x=a$ - into the element $(2a-x) (mod n); y)$.

Fig. 6.

All that is known

Let's try further conditions for our transmitting apparatus; Let's construct the apparatus $A^k$, where $k$ is some natural number. This means that with the help of the machine $A$ we will transmit packs of $k$ letters, each of which is taken from the initial input alphabet $S$.

By analogy with two-letter signals, it is easy to construct a graph $G^k$ of machine errors $A^k$. Its vertex set is the alphabet $S^k$, consisting of all possible sets of letters of length $k$: $(v_1; v_2; ...; v_k)$, where all $v_i$ are taken from the alphabet $S$. It is not difficult to construct edges in the graph $G^k$, that is, to understand which signals $(v_1; v_2; ...; v_k)$ and $(w_1; w_2; ..., w_k)$ can be confused. To do this, the letters of each of the coordinates must be mixed up with each other, that is, for each $i$ $(1 \leq i \leq k)$ they must fulfill one of two conditions: either $v_i = w_i$ or $v_i \sim w_i$ (if $v_i = w_i$ for each $i$, then these sets coincide).

Determining the exact value of the device throughput $A^k$ in the general case is quite difficult, but it can be estimated from below.

Problem 6. Prove that $\alpha(G^k) \geqslant (\alpha(G))^k$.

And far... Even in one of the simplest cases, when the error graph is the $n$-gon $P_n$, little is known about $\alpha(P_n^k)$. Everything that is known from literature will now be told.

A toric chessboard of size $n \times n$ is also called a two-dimensional pestilence. Similarly, the $k$-th degree of a $n$-gon (graph $P_n^k$) can be called a $k$-dimensional mora from the $n$ side. Ver-

⟦folio 19⟧

Fig. 7.

The graph buses $P^k_n$ can be plotted with a set of $k$ integers: $(x_1; x_2; \dots; x_k)$, where each number $x_i$ ranges from 0 to $n-1$.

Task 7. Determine the number of vertices in the graph $P^k_n$.

According to the definition, two sets $(x_1; x_2; \dots; x_k)$ and $(y_1; y_2; \dots; y_k)$ are adjacent in the graph $P^k_n$ if in the $n$-gon each pair of coordinates $x_i, y_i$ are neighbors, that is, for each value of the $i$ coordinates differ by no more than one: $|x_i - y_i| \equiv h_i$ (mod $n$) $\in \{0, 1\}$ for all $i$ from 1 to $k$ (for example, on figure 6 for the case $k=3, n=5$ the neighbors of the set (0; 1; 2) are marked).

Task 8. Determine the number of neighbors of each vertex of the $k$-dimensional tora.

Task 9. Prove that

$$\alpha(P^k_n) \leq \left[ \left( \frac{n}{2} \right)^k \right].$$

Task 10. Determine $\alpha(P^k_n)$ if $n$ is even.

For odd $n$ the following estimate holds:

$$\left( \frac{n-1}{2} \right)^k \leq \alpha(P^k_n) \leq \left[ \left( \frac{n}{2} \right)^k \right],$$

and sometimes the exact value of $\alpha(P^k_n)$ is known.

Theorem. If $n-1$ is divisible by $2^k$ then

$$\alpha(P^k_n) = \frac{n-1}{2^k} \cdot n^{k-1}.$$

The full proof of this theorem is quite long, so we will only show how to define an independent set with such a number of elements. For each set of $(x_1; x_2; \dots; x_{k-1})$ first $k-1$ coordinates we obtain $r = \frac{n-1}{2^k}$ values ​​of the $k$-th coordinate:

$$x_k \equiv 2l + r(2^{k-1}x_1 + 2^{k-2}x_2 + \dots + 2^1x_{k-1}) \pmod n.$$

Here $l$ is any integer from 0 to $r-1$.

If for the case $k=2$ you draw the set of vertices whose coordinates are given by the last formula, then the answer will be given. M415 with $n-1$ dividing by 4.

These results allow us to construct a table of values ​​$\alpha(P^k_n)$ (Fig. 7).

In it, some of the numbers are obtained theoretically, and the rest are obtained using a computer. You see that as $k$ and $n$ grow, there are more and more empty spaces.

Maybe some of you will fill in the blanks in this table and solve the problem of determining the transmission capacity of devices?
