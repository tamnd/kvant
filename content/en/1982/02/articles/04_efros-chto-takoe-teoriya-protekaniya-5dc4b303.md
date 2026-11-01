---
id: 1982-2-efros-chto-takoe-teoriya-protekaniya-5dc4b303
issue: kvant_1982_2
year: 1982
number: "2"
title: What is percolation theory
authors:
  - Эфрос А.
rubric: osnovnye-stati
page_first: 4
page_last: 11
page_labels: 2, 3, 5, 7, 8, 9
tag: 28C3
lang: en
source: kvant_digital
extraction: vision
content_sha256: b5f710d0d7cff15435b00929bdc55c72c5f66d8bf33d3cc7d96ae2b443ac95e0
prompt_sha256: draft-1
translated_from: content/ru/1982/02/articles/04_efros-chto-takoe-teoriya-protekaniya-5dc4b303.md
source_content_sha256: 7187af29e11e98fd5c52494da2e6edb5f9b257ebeb6cc4079254059e3da652bc
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 2⟧

A. Efros

What is percolation theory

Two scientist husbands shred the screen grid

It is not very often that reports of experiments appear in modern scientific journals, the object of which is a piece of common screen mesh*) purchased for a somewhat unusual purpose at the nearest hardware store. And although the article by American physicists Watson and Lees, which appeared in the journal Physical Review in 1974, was far from the first work in the field of percolation theory, our story begins with it.

*) The direct purpose of the screen grid is to protect various radio equipment from electrical interference.

The piece of mesh that Watson and Lees worked with was square in shape and contained $137 \times 137 = 18769$ nodes with a distance of $1/4$ inches (6.35 mm) between adjacent nodes. The scientists soldered copper electrodes to two opposite sides of the square and included the grid in an electrical circuit (Fig. 1, ​​a) to change its electrical conductivity (remember that electrical conductivity is the reciprocal of resistance). Then they began to cut nodes from this mesh (Fig. 1, b) and study electrical conductivity depending on the proportion of cut nodes.

Each new node to be cut was chosen randomly from among the previously uncut nodes. In principle, to do this, one could write the coordinates of each node on a separate piece of paper, put all the pieces of paper in a hat, mix well and take out one at a time. However, with a large number of nodes, such a procedure (like other mechanical methods of casting lots) is extremely inconvenient, and therefore scientists used a random

⟦folio 3⟧

a sequence of coordinates compiled by a computer.

It is clear that as the number of cut nodes increased, the electrical conductivity of the mesh decreased. This is big, if the ratio of the number of uncut nodes to the total number of nodes (137²) denotes $x$, then at a certain value $x$, which we will further call the threshold value and denotes $x_c$, the electrical conductivity went to zero. This happened when the last path connecting the left and right electrodes was cut. Determining the cut out $x_c$ was one of the objectives of the Batson and Lees experiment. They found that $x_c = 0,59$.

The question naturally arises: is the value $x_c$ random and involuntary from experience to experience, or is it completely determined?

It would seem that by repeating the experiment with another piece of screen mesh and using a different random sequence of cut nodes, we would obtain a different value of $x_c$. This answer supports common sense: since at each stage the entire cutout configuration

$$\bar{x}_c(N) = \frac{x_{c1} + x_{c2} + \ldots + x_{cQ}}{Q} = \frac{\sum_{i=1}^{Q} x_{ci}}{Q}.$$

In order to determine how much on average the values ​​of $x_{ci}$ obtained in different experiments differ from $\bar{x}_c(N)$, we do the following. Let us find the sum of expressions of the form $(x_{ci} - \bar{x}_c(N))^2$ (that is, the sum of squared deviations $x_{ci}$ from $\bar{x}_c(N))$ and divide this sum by $Q$. Value

$$\delta(N) = \frac{\sum_{i=1}^{Q} (x_{ci} - \bar{x}_c(N))^2}{Q}$$

represents the average value of the squared deviation of $x_{ci}$ from $\bar{x}_c(N)$ given $N$. This quantity is called dispersion. The value $\sqrt{\delta(N)}$ characterizes the spread of values ​​$x_{ci}$ obtained in a series of experiments with grids containing $N$ nodes. (Note that if we began to add not the squared deviations, but perhigh powers, that is, expressions of the form $x_{ci} - \bar{x}_c(N)$, then for the average value of the deviation we would get zero, since $x_{ci} - \bar{x}_c(N)$ have both positive and negative values.)

So, in order to evaluate the “degree of randomness” of the value $x_c$, it is necessary to monitor the behavior of the value $\delta(N)$.

Calculations show that with an increase in the number of grid nodes $N$ the value $\delta(N)$ sharply (according to the power law)

⟦folio 5⟧

a total magnetic moment $M = \mu N$ arises, where $N$ is the number of atoms in the sample, and $\mu$ is the magnetic moment of one atoms. It is important that the magnetic moment per unit volume does not depend on the volume and is equal to $M = \mu/v_0$, where $v_0$ is the volume per atom. The value $M$ is called spontaneous magnetization (the word “spontaneous” means “spontaneous”, that is, arising not under the influence of an external field, but by itself).

Thermal motion destroys magnetic order, and therefore there is a critical temperature, called the Curie temperature, above which spontaneous magnetization is zero. For iron, for example, the Curie temperature is $770^\circ C$. At higher temperatures, iron cannot be ferromagnetic.

Let us now consider a substance that is a solid solution (a mixture of magnetic and nonmagnetic (without a magnetic moment) atoms. This is a crystal in the nodes of which magnetic or nonmagnetic atoms are located, and their arrangement turns out to be not ordered, but completely random. Let us denote $x$ relative to the concentration (fraction) of magnetic atoms and find out whether for all values of $x$ there is spontaneous magnetization, that is the substance is ferromagnetic.

Let us assume that the interaction between the magnetic moments of atoms decreases with distance so quickly that only the interaction of close, immediate neighbors is taken into account. This means that if two magnetic atoms are standing next to each other, then their moments are necessarily parallel, but if there is at least one non-magnetic atom between them, then the moments can be directed arbitrarily: they already “know nothing” about each other.

Let us introduce some definitions. We will call two magnetic atoms connected to each other either if they stand next to each other, or they are connected to each other by an integer of magnetic atoms building next to each other (Fig. 2, a). A set of related atoms is usually called a classer

Fig. 2. Magnetic atoms are indicated by red circles, non-magnetic atoms are indicated by blue circles. Dashed lines are cluster boundaries.

(● the English word “cluster”, which means “bunch”, “brush”).

Let us now assume that the magnetic atoms are very small ($x \ll 1$). Naturally, in this case they are mainly located alone. A class of two magnetic atoms is a rare event, a class of three atoms is even more rare, etc.

Thanks to magnetic interaction, the magnetic moments of the connections of these atoms are oriented in one direction. Thus, each classer has a resulting magnetic moment proportional to the number of atoms in the cluster. On the other hand, we agreed that magnetic atoms that are not close shikhmi do not interact with each other. Therefore, atoms belonging to different classers do not interact with each other. As a result of this, the oriented moments belonging to the classes turn out to be arbitrary (see Fig. 2, a), so that the average moment of all classers is equal to zero.

So, we have found that at a low concentration of magnetic atoms there is no spontaneous magnetization.

Now consider the case when almost all atoms are magnetic. Obviously, a small impurity does not eliminate the spontaneous magnetization, but only slightly reduces it. Let's discuss this issue in the language of classers. For $x=1$ all $N$ atoms belong to the same cluster. If $x$ is a little excellent-

⟦folio 7⟧

We formulated the problem of electron conductivity for a flat mesh; however, it is clear that it is easy to set it up for a cube, to the two opposite edges of which electrons are soldered. In the ferromagnetic problem, our reasoning applied equally to both the grid and the cube. Thus, from the point of view of the critical concentration $x_c$, the problem of electron conductivity of the network and the problem of an impurity ferromagnet are one and the same problem. It's called the node problem.

In conclusion of this section, we once again emphasize that the basic concepts of percolation theory, such as the percolation threshold, infinite cluster, etc., acquire a clear character only when applied to an infinitely large system. In any finite system, the percolation threshold is “blurred”; When repeating the experiment, the results are reproduced only with a certain accuracy, and the definition of the threshold itself becomes ambiguous. For example, in an experiment with a conducting grid, we could call the percolation threshold the value $x$ at which percolation occurs from top to bottom rather than from left to right, or the minimum value $x$ at which percolation occurs from both top to bottom and left to right. In a sufficiently large system, the difference between these definitions disappears, and the percolation threshold becomes a well-defined value.

Note that increased sensitivity to the size of the system is a common property of all so-called critical phenomena. Thus, the Curie temperature at which ferromagnetism disappears is always slightly “smeared” in the final system for the same reasons as the percolation threshold. It should be kept in mind, however, that the actual size of the system is only important if we are trying to artificially simulate a critical phenomenon (for example, using a screen mesh). A real macroprocessor system can practically always be considered infinite. After all, one cubic site of matter contains approximately $10^{22}$ atoms!

Other lattice problems

In the previous sections we considered the lattice problem of nodes. Now we will explain what the task of communication is. Imagine that in the experiment with a screen grid we will not triple the nodes, but will cut the wires (links) that connect these nodes (Fig. 4). Let us denote by $x$ the fraction of uncut wires. Then again we can raise the question about the critical fraction $x_c$, at which the current in a very large grid with metal contacts on the sides exceeds the limit. This problem can also be formulated in a cluster language, considering that nodes are connected to each other if they are connected by a chain of uncut wires.

The nodes task and the communication task seem very similar. However, they are not only childish. These problems can also be formed for lattices more complex than square and cubic. It is assumed that each lattice node can be connected to all nodes that are its nearest neighbors. The number of nearest neighbors depends on the lattice type, and therefore the percolation thresholds vary from lattice to lattice. But on any lattice, the percolation threshold in the problem is no greater than the percolation threshold in the knots problem.

The binding problem on a simple square lattice is solved exactly; percolation threshold $x_c = 1/2$ (it is less than the threshold value $x_c = 0,59$ in the problem of nodes on the same lattice). Exact solutions also exist for some other two-dimensional (flat) lattices. For three-dimensional (volume) lattices, not a single exact solution has yet been found. Such three-

⟦folio 8⟧

Fig. 5.

dimensional problems are solved by approximate methods (like those described in the first section) and computer modeling.

Threshold values ​​for various types of gratings are given in the table. The exact values ​​are underlined. The remaining results were obtained using approximate methods. Naturally, the approximate results obtained by different methods differ somewhat from each other. The table shows the results that are most suitable from the author's point of view.

Various applications of percolation theory

Percolation theory is a very young mathematical discipline. Its main ideas were formed in 1957 in the work of English mathematicians Broadbent and Hammersley. In the same work the theory was done and named. (In English it is called “percolation theory”.
The exact translation of “percolation” means “seepage”, “filtration”; In Russian literature, together with the term “percolation” you can find the word “percolation”.

Despite the youth of the theory, the scope of its applications is extremely wide. In this article we have analyzed only the so-called lattice problems, but they do not exhaust the entire field and play a relatively small role in applications.

In order to formulate another problem of the theory of percolation, let us recall the ancient legend of the Nevy Ark. This legend says that some say that there was once a hail flood on Earth. Only a small group of people who had built a large ship (ark) were saved from it. This ship, apparently, was cruising somewhere in the Caucasus region, since the first place where it landed when the water began to subside was the top of Mount Ararat... Now let’s imagine that the travelers decided to cross the Caucasus ridge from south to north by water. At what minimum level is this journey still

⟦folio 9⟧

will arise? In other words, to what point must the water level drop for the waterway crossing the Caucasus Range from south to north to disappear? (Of course, when you are allowed to maneuver between peaks protruding from the water.)

This problem (provided that the mountain system has a sufficiently large extent in all directions) is also a problem of the theory of percolation, only formed not on a lattice, but in continuous space. The desired water level is called the flow level.

Using the concept of a percolation level, we describe, for example, the dielectric-metal transition that occurs in semiconductors with impurities as the electron concentration increases. The fact is that impurities in semiconductors are randomly located and can be charged. As a result, in some areas positive charge predominates, in others negative charge predominates. Electrons added to the system are collected in areas with a positive charge, forming something like lakes or drops there. The areas where electron droplets appear have high electrical conductivity. However, if the electron concentration in the system is low, then these drops are not connected to each other. Between is a region with very low electrical conductivity, so that the resulting electrical conductivity of the semiconductor is negligible. The situation changes dramatically when the electron concentration increases so much that the electron droplets are located next to each other or connected to each other or connected through narrow electron channels. At certain critical concentrations, it becomes possible to cross the entire semiconductor, marveling only at the area filled with electrons. Then the electrical conductivity returns sharply. This phenomenon is called the dielectric-metal transition. To determine the critical concentration, it is necessary to solve the problem of the theory of flow, an

logical problem of a water route through a mountain system.

We can list the most diverse applications of the theory of flow: the flow of liquid into a porous body (each pore has its own diameter, and due to the capillarity of the liquid, it passes through only at a certain pressure; you need to find the critical pressure at which the liquid flows a very long distance through a system of random pores), the destruction of rocks (due to age or stress, microcracks form, which, merging, split the stone), various models of the metal-dielectric transition, the binding of anomalous properties of supercooled water, etc.

Let us now try to formulate what is common between all these problems and what, in fact, is the subject of the theory of percolation. This is quite difficult to do. I would say that percolation theory deals with the connectivity of a very large (macrosoppetic) number of elements, provided that the connection of each element with its neighbors is random, but obtained in a certain way (for example, by tossing a coin). It is important that the set of connections developed using this method must be fixed and cannot change during the process of solving the problem.

It should also be noted that the theory of percolation deals not only with finding threshold values, but also (to a much greater extent) with the laws that determine the behavior of various threshold values. If the threshold values ​​are specific for each problem, then the laws according to which such functions as $P(x)$ in the problem of an applied ferromagnet or electrical conductivity in the problem of a mesh vanish turn out to be universal for all problems of percolation theory. This is perhaps the most interesting range of questions in the theory of percolation, but the story about it should be long, and it is beyond the scope of this article.
