---
id: 1987-4-bodik-streshinskiy-o-graficheskom-sposobe-resheniya-nekotoryih-fizicheskih-zadach-f428202b
issue: kvant_1987_4
year: 1987
number: "4"
title: On a graphical method for solving some physical problems
authors:
  - Бодик В. А.
  - Стрешинский И. Я.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 51
page_last: 53
page_labels: 49-51
tag: KMLQ
lang: en
source: kvant_digital
extraction: vision
content_sha256: 5e8028c73a748210c016b734162462f5b15550cde399d5bfac07e2891aef8c2e
prompt_sha256: draft-1
translated_from: content/ru/1987/04/articles/21_bodik-streshinskiy-o-graficheskom-sposobe-resheniya-nekotoryih-fizicheskih-zadach-f428202b.md
source_content_sha256: eb561353b24d9e832bcd51c36ad6f05415ab28a621ffdc7c231873b92398bda9
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 49⟧

On a graphical method for solving some physical problems

V. A. BODIC, I. Y. STRESHINSKY

Often, a graphical representation of a physical process makes it more visual and thereby facilitates understanding of the phenomenon under consideration. Sometimes making it possible to significantly simplify calculations, graphs are widely used in practice to solve various scientific, technical and economic problems. The ability to build and read graphs is mandatory for many specialists today.

In this article we will consider the use of graphs to solve certain types of physical problems.

§ 1. Graphic and many cinematic problems are solved easily and beautifully.

Problem 1. The equations of motion of two bodies are given: $x_1=20t, x_2=250-5t$. You need to find: a) the place and time of the meeting; b) where was the second body when the first passed the 100th meter of its path; c) at what moment the distance between the bodies is 125 m. The bodies began to move simultaneously.

On the same coordinate axes, we will construct graphs of the dependence of the coordinate $x$ on time $t$ for both bodies (Fig. 1).

a) Ordinata and abscissa of the point of intersection of the graphs are the corresponding place and time of meeting: $x=200$ m, $t=10$ s.

b) Using the first graph, we find out the moment of time at which the first one passed the 100th meter: $t=5$ s. Now, knowing this time, the coordinate of the second body is found from the second graph: $x=225$ m.

c) The distance between the bodies at the initial moment was equal to 250 m. Therefore, the distance 125 m is the length of the middle line in the triangle $ABC$, and the desired moment of time $t=5$ s. From symmetry it is clear that the same distance will be between the bodies $t=15$ s after the start of movement.

Task 2. Find the time and place of collision of parts moving along

⟦folio 50⟧

one straight line The initial speed of the first particle is $v_{10}$, its acceleration is $a_1$, the initial speed of the second particle is $v_{20}$, its acceleration is $a_2$. At time $t=0$ both particles have coordinates $x_0=0$, $v_{20}>v_{10}$, $a_2<a_1$.

By the time of the meeting, both particles will have passed the same paths $l$, therefore the conditions for their collision will be equal to the areas $S_1$ and $S_2$, protected under the graphs of the speed $v$ versus time $t$ (Fig. 2):

$$S_1 = \frac{2v_{10}+a_1\tau}{2}\tau, \quad S_2 = \frac{2v_{20}+a_2\tau}{2}\tau.$$

Considering that $S_1=S_2$, we find

$$\tau = \frac{2(v_{20}-v_{10})}{a_1-a_2}, \quad x=l = \frac{2(v_{20}-v_{10})(v_{20}a_1-v_{10}a_2)}{(a_1-a_2)^2}.$$

Problem 3. A passenger who was late for the train noticed that the penultimate valon forgave him in $t_1=10$ s, and the last one in $t_2=8$ s. Assuming the motion of the train to be uniformly accelerated, determine the time the passenger was late.

figure 3 shows a graph of the speed of train $v$ versus time $t$. Let us denote the length of one car by $l$. Then $S_1=S_2=l$. Equating $S_1$ and $S_2$, we find the required time of passenger’s delay:

$$\frac{at+a(t+t_1)}{2}t_1 = \frac{a(t+t_1)+a(t+t_2)}{2}t_2, \quad t = \frac{t_2^2+2t_1t_2-t_1^2}{2(t_1-t_2)} = 31\text{ с.}$$

§ 2. Using the area under the graph often makes it possible to significantly simplify the solution of the problem.

Problem 4. The length of the sleigh, sliding along the main mud, hits the asphalt and stops, not even half its length. After this, the sleigh is abruptly given its original speed, and after a while it stops again. How do braking paths relate in general cases?

The sliding friction force $F_{\tau p}$ in this case depends, first of all, on the length $x$ of the part of the sled located on the asphalt:

$$F_{\tau p} = \mu mgx/L$$

(here $\mu$ is the friction coefficient, $m$ is the mass of the sled, $L$ is its length). The graph of the dependence of $F_{\tau p}$ on $x$ (Fig. 4) makes it possible to find work on reducing the friction force. In general cases, the initial kinetic energies of the sled are equal, which means they are equal and equal in terms of the resistance of friction forces. Thus, writing the equality between the areas $S_1$ and $S_2$, we find the required ratio of the braking path:

$$\frac{\mu mgx_1}{2L}x_1 = \frac{\mu mgx_1+\mu mgx_2}{2L}(x_2-x_1), \quad \frac{l_1}{l_2} = \frac{x_1}{x_2-x_1} = \frac{1}{\sqrt{2}-1}.$$

§ 3. Often in problems where changes in magnitude numbers occur, we make conditions. Graphs can help you understand management techniques.

Problem 5. A body with mass $M$ at rest is attacked by a body with mass $m$ at speed $v_0$. The force generated by the interaction first grows linearly from 0 to the value $F_0$ over a period of time $t$, and then linearly decreases to 0 over the same time. Determine the velocities of the bodies after the collision, considering it to be central.

Let us plot the dependence of the interaction force $F$ on time $t$ and replace the variable force $F(t)$ constructed with the acting force $f$ (Fig. 5). Since the result of the action of a force is a change in the impulses of interacting bodies, the impulses of both must be equal.

The impulse of force is the area under this graph, therefore, we write

⟦folio 51⟧

Given the equality of the areas $S_1$ and $S_2$, we find the force $f$:
$$F_0\tau=2f\tau, \text{откуда } f=F_0/2.$$
Now let’s write down Newton’s second law for each of the colliding bodies and find the corresponding change in the speed of the bodies:
$$m(v_0-v)=2f\tau, MV=2f\tau,$$
where
$$v=v_0-2f\tau/m=v_0-F_0\tau/m,$$
$$V=2f\tau/M=F_0\tau/M.$$
§ 4. In conclusion, let us consider another area of ​​application of graphs—for a deeper understanding of physical processes.
Problem 6. A thread of length $l$ (Fig. 6) is attached to the vertical boundary of the rod. A ball is suspended from the other end of the thread. How does the distance $r$ between the ball and the rod depend on the angular velocity of rotation of the rod $\omega$? Assume that the angular velocity changes so slowly that at any value the motion of the ball has time to stabilize.
Let's write down Newton's second law for a ball with mass $m$:
$$m\omega^2 r=mg \text{ ctg } \alpha.$$
Since ctg $\alpha=r/\sqrt{l^2-r^2}$, we get
$$r=\sqrt{l^2-g^2/\omega^4}.$$

Amendment
In «Kvant» No. 1 for this year the article “On the collision of balls and “serbez” physics” was published. At the beginning of this article, the question of non-central collision of balls with an arbitrary mass ratio was considered. In the resulting expression for the speed of the first ball after the collision, one root was lost: in the formula for $v'$, together “—” should become “±”. The rule for choosing a sign turns out to be as follows. In the case of $m_1\leqslant m_2$ for any angles $\theta$ has only one solution, corresponding to the “+” sign in front of the radial. In case
$$\frac{m_2}{\sin \theta} \geq m_1>m_2 \text{ и } \frac{\pi}{2} >\theta>0$$
both signs in front of the radial gives physical implementations of the solution. Scattering at angles $\theta>\frac{\pi}{2}$ is impossible.

Exercises
1. Postal communication between piers $M$ and $K$ is carried out by two cerami. At the appointed time, the Qatari sailed from their piers, met, exchanged mail, and returned back. If the Qatari sailed from its piers at the same time, then the Qatari departing from $M$ takes 3 hours round trip, and the Qatari from $K$ takes 1.5 hours. The speeds of both catarrhs ​​relative to water are the same. Determine how much later the Qatar should sail from $K$ so that the Qatar's obiha is en route at the same time.
2. Konbekezen covers a distance of length $L$ with a constant speed, and then slows down with a constant acceleration $a$. At what speed will the travel time to stop be the shortest?
3. Penetration depth of a part with mass $m$ in the area of ​​action of a braking force directly proportional to the impulse of the part: $l=\alpha P$. Find the dependence of the braking force on the penetration depth.
4. A long cylindrical vessel contains a substance whose density increases with depth according to the law $\varphi \sim x^2$. What is the relationship between the lengths of parts of a vessel that have the same masses? The shell of the vessel is weightless.

Exercises "±" in $v'$ leads to the fact that in the formula for $\frac{|\Delta T|}{T_1}$ - for the relative change in the kinetic energy of the impacted ball - in front of the radial, together with "+" should become "−". Corresponding changes follow in figure 2.

The editors apologize for the inaccuracy.
