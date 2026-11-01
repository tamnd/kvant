---
id: 1985-8-solovev-sosinskiy-geometriya-skolzyaschih-vektorov-9174abb8
issue: kvant_1985_8
year: 1985
number: "8"
title: Geometry of sliding vectors
authors:
  - Соловьёв Ю. П.
  - Сосинский А. Б.
rubric: osnovnye-stati
page_first: 11
page_last: 18
page_labels: 9-16
tag: T254
lang: en
source: kvant_digital
extraction: vision
content_sha256: f27fb379bf30a108ed668f711021ba982688e27a7628121ccfde749d4fe99926
prompt_sha256: draft-1
translated_from: content/ru/1985/08/articles/06_solovev-sosinskiy-geometriya-skolzyaschih-vektorov-9174abb8.md
source_content_sha256: 1ace9701a17392def15062ecc45f984c3e8f66f579c77578d04e2b3f985807b4
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 9⟧

Geometry of sliding vectors

Candidate of Physical and Mathematical Sciences Yu. P. SOLOVEV,
Candidate of Physical and Mathematical Sciences A. V. SOSINSKY

...Yes, the Swan rushes into the clouds,
The cancer kicks back, and Shuka is pulled into the water.

You, of course, remember the lines of I. A. Krylov’s wonderful essay included in the epigraph. Have you ever thought about how to calculate the movement of air if you know with what forces a swan, crayfish and shuka drag it? This problem is completely natural, one might say, typical: forces are applied to some solid massive body in certain places - what will happen? Oddly enough, the familiar vector apparatus studied in physics and mathematics lessons at school is completely unsuitable for solving such problems. When we must take into account not only the mass, but also the dimensions of a body, when we are dealing not with an abstract material point, but with a real object, it is not always clear how to add vectors applied to an object in different places, what can and cannot be done with these vectors and, strictly speaking, what such “real” vectors are.

The answer to these questions - in the form of a simple mathematical theory (the theory of sliding vectors) - is the subject of our article.

What types of vectors are there?

A vector in space or on a plane is usually represented by the direction of the segment AB. It is defined by two points: its beginning (or point of application) A and its end B. If the segment AB is extended indefinitely in both directions, a straight line is obtained, which is called the linear action of the vector AB.

All vectors, depending on what geometric or physical quantities they represent, can be divided into the following three types.

1°. It can be assumed that two geometric vectors represent the same physical or mechanical quantity. (Recall that in geometry two vectors (directional segments) are called equal if their lines of action are parallel, the lengths are equal and the order of the points specifies the same direction on their lines of action, or, in other words, if they are combined by parallel translation.) Vectors of this kind, which have neither a definite line of action nor a definite point of application, are called free. For example, the magnetic induction vector of a constant magnetic field or the velocity vector of one inertial system relative to another are free vectors; they can be considered applied to any point. Mathematicians tend to study free vectors too; The simplest example is a vector given by a parallel translation: applied to any point, it indicates with its end the image of this point for a given translation.

2°. On the other hand, there are also physical quantities in which their vectors cannot be separated from their point of application. Vectors of this kind are called connected (or fixed). Thus, the vector of the instantaneous speed of a point at a given moment in time is an example of a coupled vector.

⟦folio 10⟧

It cannot be separated from a moving point (unless, of course, all other points in space are moving at the same speed).

3°. Finally, it may be that two geometric equal vectors represent equal physical quantities only on the condition that these vectors have the same line of action, and represent unequal physical quantities if they have different lines of action. These are, for example, vectors representing forces acting on a rigid body. Such vectors inseparable from the line of action are called slips. These are, so to speak, “real” force vectors that actually act not on abstract “infinitesimal” bodies, but on rigid objects that have a certain size and shape. Note that here the condition of rigidity of the body is essential: the body does not stretch or contract, it transmits reinforcement along the line of action without loss, so it does not matter to which point on the line of action the force is applied; the point of application can seem to slide along the line of action.

About sliding vectors and almost a story. In what follows, the word “vector” without definition should be understood precisely as a “sliding vector”; and when it comes to free or fixed vectors, this will be specified.

We will denote (sliding) vectors with either one bold letter, such as $v$, or two letters

with a leading stroke, for example $\overrightarrow{AB}$. We will denote free vectors by letters with arrows, for example $\vec{v}$ or $\overrightarrow{AB}$.

Sliding vector systems

So, the (sliding) vector $v=\overrightarrow{AB}$ is given by the line $l=AB$—its line of action—and the direction by the segment $AB$ lying on this line. Two vectors $v=\overrightarrow{AB}$ and $u=\overrightarrow{CD}$ are considered coincidences if they define the same free vector $(\overrightarrow{AB}=\overrightarrow{CD})$ and, in addition, they have the same line of action (the lines $AB$ and $CD$ coincide).

In the future, we will be interested not in individual vectors, but in finite systems of vectors $(v_1, v_2, \dots, v_k)$, because it is precisely such systems that correspond to systems of forces acting on a rigid body. Of course, there is no order in which the vectors are listed; however, the same vector can appear several times in a system, and must be counted as many times as it appears in it.

Our goal is to learn how to transform systems to each other, to match - if possible - an arbitrary system to a system of the simplest form. For this we need

Elementary Operations
and the equivalence of the system of vectors

When the lines of action of two vectors $v$ and $u$ intersect, these vectors

⟦folio 11⟧

can be added in a natural way: if $u = \vec{AB}$, $v = \vec{AC}$ (A is the common point of the action lines), then the sum $w = u + v$ of the vectors $u$ and $v$ is the vector $w = \vec{AD}$, where the point $D$ is obtained by adding $\vec{AB} + \vec{AC} = \vec{AD}$ according to the parallelogram rule (Fig. 1,a). This addition of "intersecting" vectors will be our first elementary operation; it maps a system of two vectors $(u, v)$ to a system of one vector $(w)$.

This operation has an inverse: if any vector $v = \vec{AB}$ is given, then you can choose two arbitrary straight lines passing through any point of the action lines (say, through the point $A$), and expand the vector $\vec{AB}$ according to the parallelogram rule (Fig. 1,b). From one vector $(v)$ we obtain a system of two vectors $(v_1, v_2)$.

Please note that only vectors whose action lines intersect or coincide can be added. Vectors with a general linear action are especially easy to add. In particular (Fig. 2), this is how two opposite vectors are added, that is, vectors of the form $v = \vec{AB}$ and $-v = \vec{BA}$; their sum will be the null vector $0 = \vec{AA}$.

Our second elementary operation is to destroy the null vector, that is, to move from a system of the form $(v_1, v_2, ..., v_k)$ to a system $(v_1, v_2, ..., v_k)$. In particular (for $k=0$), the simplest system $(v, -v)$ coincides with the empty or zero system, which we will denote in the same way as the null vector - by 0.

The second elementary operation also has an inverse - separation of the null vector, that is, the transition from the system $(v_1, v_2, ..., v_k)$ to the system $(v_1, v_2, ..., v_k)$. In particular (for $k=0$), the simplest system $(v, -v)$ coincides with the empty or zero system, which we will denote in the same way as the null vector - by 0.

The second elementary operation also has an inverse - separation of the null vector, that is, the transition from the system $(v_1, v_2, ..., v_k)$ to the system $(v_1, v_2, ..., v_k)$. In particular (for $k=0$), the simplest system $(v, -v)$ coincides with the empty or zero system, which we will denote in the same way as the null vector - by 0.

From a mechanical point of view, it is clear why we are interested in elementary operations and equivalent systems. After all, two equivalent systems appear on a solid body, which can be verified not only experimentally, but simply a product of the physical meaning of elementary operations. By reducing complex systems to simpler ones, we get the opportunity to easily understand what exactly the resulting effect of a given complex system of forces has on a solid body.

The simplest systems on a plane; couples

Let us now consider in more detail the reduction of a system of vectors to simpler ones for the case of systems of vectors on a plane.

figure 3 shows how, with the help of elements of operations, some simple vector systems are reduced to other systems. We advise the reader to carefully follow all the operations and even do them on paper himself.

Particular attention should be paid to figure 3, e. It shows systems of two opposite vectors of equal length on parallel linear actions; such systems are briefly called a parameter. From figure it is clear that the pairs cannot be simplified, but can only be “turned”, transformed into another pair.

figure 4 shows another series of operation elements. What happens here is not a simplification of the original system (from one vector), but its conditions: from a given vector we obtain a vector with another linear action and a pair; however, if this figure is read in reverse order (and this makes sense, or every elementary operation has an inverse), we get a simplification (a system consisting of a pair and a vector is reduced to a system of one vector). Transition $(v) \rightarrow (u, x, y)$ is worth remembering, we will need it a little later.

Let us also note that common reductions of plane systems can also be useful when considering spatial problems. So, the spatial system $(\mathbf{l}, \mathbf{p}, \mathbf{ш}, \mathbf{т})$ ($\mathbf{l} = -\mathbf{t}, |\mathbf{p}| = |\mathbf{ш}|$) applying the operation of vector decomposition results in (Fig. 5,a) to a pair $(\mathbf{u}, \mathbf{v})$: $\mathbf{l} = \mathbf{a} + \mathbf{v}, \mathbf{ш} = \mathbf{b} + \mathbf{u}$, and the flat system $(\mathbf{a}, \mathbf{b}, \mathbf{л}, \mathbf{т})$, remaining after separation from the system $(\mathbf{l}, \mathbf{p}, \mathbfш, \mathbf{т})$ couples $(\mathbf{u}, \mathbf{v})$ (Fig. 5,a), as is easy to see, is reduced to zero (Fig. 5,b)

Vector moment and couple moment

We saw above that pairs of vectors cannot be reduced to a single sliding vector. However, the couple admits

⟦folio 12⟧

The simplest transformation of flat systems:

a) two intersecting vectors → one vector;

b) two aligned vectors → two intersecting vectors;

c) two opposing vectors of different lengths → two intersecting vectors;

d) two opposite vectors of equal length (pair) → another pair.

Fig. 3.

12

⟦folio 13⟧

convenient vector characteristic. To get it, we will have to travel partly from afar.

Let a vector $v = \overline{AB} \neq 0$ and a point $O$ not lying on its line of action be given; then the moment of the vector $v$ relative to the point $O$ is called the (fixed!) vector $OM$ (attached to the point $O$) with linear action, perpendicular to the plane $OAB$, length $OM = r \cdot |v|$ (where $r$ is the arm of the vector $v$ relative to $O$, that is, the distance from $O$ to the straight line $AB$) and directed so that the direction of rotation of $v$ about $O$, as observed from point $M$, is positive (counterclockwise; Fig. 6); if point $O$ lies on the line of action of vector $v$, or $v = 0$, then the moment is taken equal to zero. Moment vector plays an important role in mechanics in the study of rotational motion and has beautiful applications in geometry.

Let now be given a pair of vectors $v = \overline{AB}, v' = \overline{A'B'}$ and a point $O$; let $OM$ and $OM'$ be the moments of $v$ and $v'$ relative to $O$. then it is easy to check (do it!) that the length and direction of the sum of moments about the point $O$ of the vectors $v$ and $v'$ does not depend on the choice of this point, that is, the sum is a free vector. It is called the (vector) moment of the pair $(v, v')$. It is easy to check that the length of the vector moment of the pair $(v, v')$ is equal to $d \cdot |v|$, where $d$ is the distance between parallel lines $AB$ and $A'B'$. Using this, as well as the statement of Problem 3, it is not difficult to prove that a pair will be reduced to zero if and only if its vector moment is equal to zero.

Reducing plane systems to a pair or vector
We will now prove the following remarkable theorem.

⟦folio 14⟧

Every (finite) system of (sliding) vectors on a plane can be reduced either to a single vector or to a pole.

Proof. If this system consists of one vector, the theorem is proven. If there are vectors in the system with intersecting lines of action, then they can be simplified in pairs (see Fig. 3,a) until only vectors with parallel lines of action remain. If there are three or more such vectors, then at least two of them are corrected, and we can simplify the system further (see Fig. 3, b). Thus, transitions 3, b and 3, a allow us to reduce the proof of the theorem to the case of two oppositely directed vectors with parallel lines of action. If the lengths of the vectors are different, then transition 3, b followed by transition 3, a gives us one vector, and if the lengths are equal, then we get a pair; Now the theorem is completely proven.

Note, first, that the proof not only establishes the validity of the theorem, but also provides an effective way to find a vector (or pair) equivalent to the original system. Secondly, if we select some fixed point in advance, then we can carry out our elementary operations in such a way as to bring this system to a system of one pair and one vector, whose line of action passes through this point. Indeed, this is true if the system is reduced to one pair. If it is reduced to a single vector, then the operation shown in figure 4 allows us to reduce the vector to a pair and a vector whose line of action passes through a given point.

Vector system calculus; basis

We have learned to reduce systems of plane vectors to simple systems. However, it turned out that systems can not only be reduced to one another, but also expressed through each other. In this case, a calculus of vector systems will arise, very similar to the usual calculus of free vectors in space.

To describe this calculus, we define the sum of two systems $N=(u_1, u_2, ..., u_k)$ and $M=(v_1, v_2, ..., v_l)$ as their “free association”, that is, the system

$$L=N+M=(u_1, u_2, ..., u_k, v_1, v_2, ..., v_l)$$

(the equality of the concept vector system here and below as their equivalence), and the product

$$\lambda N=(\lambda u_1, \lambda u_2, ..., \lambda u_k),$$

where $\lambda$ denotes a vector with the same linear action as $u$, length $|\lambda| \cdot |u|$, directed in the same direction as $u$ if $\lambda>0$, and in the opposite direction if $\lambda<0$.

Let us say that the system $N$ is linearly expressed through the systems $M_1, ..., M_n$ if there are numbers $\lambda_1, \lambda_2, ..., \lambda_n$, also that

$$N=\lambda_1 M_1+\lambda_2 M_2+\dots+\lambda_n M_n.$$

Let us now consider the case of a system on a plane. Let $O$ be an arbitrary point of the plane, $I$ and $J$ be one-vector systems consisting of non-zero non-clipneary vectors applied to the point $O$, and $K$ be any (non-zero) pair. Then the systems $I, J, K$ form a basis in the set of the system of plane vectors, that is, any system $N$ is uniquely linearly expressed through $I, J, K$:

$$N=\alpha I+\beta J+\gamma K$$

(the numbers $\alpha, \beta, \gamma$ are uniquely determined by the system $N$ for fixed $I, J, K$).

A reader familiar with the concept of a vector space will of course understand that this statement means that the set of classes of equivalent systems of (sliding) vectors in the plane with respect to the operations defined above forms a vector space of dimension 3.

* * *

Having reached this point, the authors began to think about it, and then got stuck: what exactly are the applications of the theory of sliding vectors that the stories are about? Wherever this theory is not used! In statics (the theory of trusses and vertical polygons), in structural mechanics, in kinematics and dynamics of a rigid body, and its generalizations are used in some new branches of geometry. But you cannot embrace the immensity. Here we will give only one example - from the kinematics of a rigid body, as well as, at the end of the article, a number of problems. Another application of sliding vectors - in structural mechanics - is discussed in the note “Hanging places” on p. 22.

⟦folio 15⟧

Rigid body rotation

Here we are interested in the following kinematic problem: how to describe the motion of a rigid body rotating about a certain axis, if this axis, in turn, rotates around a fixed axis? We will consider the problem solved if a method is given for finding the velocity vector of any direction of a given point of the body (relative to a stationary reporting system).

The answer is beautifully formulated in terms of sliding vectors. However, before we present it, we will talk a little about how a rigid body can move in general. Let's start with the simplest examples.

In uniform linear motion, a rigid body moves at a constant speed in a fixed direction. In this case, the velocity vectors at all points are the same, their direction and magnitude in time. All points move in straight lines. The movement is characterized by one free velocity vector $\vec{v}$.

With uniform rotational motion, the body moves with a constant angular velocity (see “Physics 8”, § 17) of a fixed axis. In this case, the velocity vector of any point on the rotation axis is zero, and the velocity vector of any other point is perpendicular to the plane passing through this point and the axis, and is proportional in magnitude to the distance from the point to the axis. The axis points remain in place, and the remaining points move in a circle with centers on the axis. Such a movement is characterized by one with a SLIDING vector $\omega$ - the angular velocity of rotation, the line of action of which coincides with the axis of rotation.

With uniform rotational motion, the body rotates with a constant angular velocity $\omega_0$ of a fixed axis $AB$, and the body itself also rotates around the axis $M_1N_1$ with a constant angular velocity $\omega_1$. (We emphasize that

⟦folio 16⟧

As a sliding vector, this angular velocity is variable, $\omega_1 = \omega_1(t)$, - the position of its linear action $M_t N_t$ changes.) How to describe the resulting movement? The answer depends on the relative position of the axes $AB$ and $M_t N_t$.

1°. The axes match. Then the body rotates around the fixed axis $AB = M_t N_t$ with a constant angular velocity $\omega = \omega_0 + \omega_1$. (Example: movement of a clock or minute hand of a clock lying at the North Pole.)

2°. The axes are parallel, and $\omega_0 \neq -\omega_1$. Then at any moment $t$ the speed of all points of the body is the same as if it were uniformly rotating with angular velocity $\omega = \omega_0 + \omega_1$ (here we mean the sum of sliding vectors - see Fig. 3 and Fig. 10) around the linear action $P_t Q_t$ of the vector $\omega$. The body is said to have an instantaneous angular velocity $\omega$ and an instantaneous axis of rotation $P_t Q_t$. In this case, the instantaneous axis rotates around the fixed axis $AB$, remaining parallel to it.

3°. The axes are parallel, and $\omega_0 = -\omega_1$. Then the body performs translational motion with a velocity vector $\vec{v}$ equal to the moment of the pair ($\omega_0, \omega_1$), that is, at any moment $t$ the velocities of all points of the body are the same and equal to $\vec{v}$. (Example: movement of the moving part of the pedal; Fig. 8.)

4°. The axes intersect. This case is similar to 2°: at any moment $t$ the body has an instantaneous axis of rotation and an instantaneous angular velocity $\omega = \omega_0 + \omega_1$. The difference is that here the instantaneous axis is described not by a cylinder, but by a cone with its apex at a fixed point of the body - the point of intersection of the axes. (Example: precessional motion of a top; Fig. 9.)

5°. The axes are crossed. In this case, the body has, so to speak, an “instantaneous helical axis”; For more information about this, see tasks 7, 8.

We see, therefore, that the solution to our kinematic problem is briefly and simply formulated in terms of the addition of sliding vectors. We leave simple proofs of assertion 1°-4° as an exercise to the reader.

Miscellaneous tasks

1. The main vector of a system of sliding vectors ($v_1, \dots, v_n$) is the sum of free vectors $\vec{v}_1 + \dots + \vec{v}_n$ equal to them, and the main moment of this system relative to the point $O$ is the sum of the moments of vectors $v_1, \dots, v_n$ relative to $O$. Prove that any two equivalent systems have the same principal vectors and principal moments about the same point $O$.

2. Show that any system of vectors located in the same plane is equivalent to those directed along the side of a triangle arbitrarily chosen in the same plane.

3. Prove that a plane system of vectors perpendicular to the sides of a convex $n$-gon at their midpoints is equivalent to zero if the lengths of the vectors are proportional to the corresponding sides and all vectors face inside the polygon (or all in the direction).

4. Form and prove a statement similar to the statement of the previous problem for the terrahedra.

5*. Show that any system of vectors in space is equivalent to six vectors directed along the edges of an arbitrary tetrahedron.

6*. Show that any system of vectors in space is equivalent to a system consisting of one vector (passing through an arbitrary chosen point) and one pair. Deduce from this that systems of sliding vectors in space, considered up to equivalence, form a six-dimensional vector space.

Note. First, reduce the system to three sliding vectors passing through three arbitrarily chosen points (putting each vector of the system in those directions), then to two vectors, one of which passes through a given point, and finally apply the construction from figure 4.

7. The rigid body rotates with an angular velocity $\omega$ about an axis, which in turn moves uniformly and rectilinearly with a speed $\vec{v}$. Prove that the body: a) does
