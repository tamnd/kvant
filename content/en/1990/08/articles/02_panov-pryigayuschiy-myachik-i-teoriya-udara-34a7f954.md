---
id: 1990-8-panov-pryigayuschiy-myachik-i-teoriya-udara-34a7f954
issue: kvant_1990_8
year: 1990
number: "8"
title: Bouncing ball and hitting theory
authors:
  - Панов А.
rubric: osnovnye-stati
page_first: 4
page_last: 8
page_labels: 2, 6
lang: en
source: kvant_digital
extraction: vision
content_sha256: f5ca107bd33d893fce76b37c39cce2c0edad89c8cb82679f4c05b195eba90697
prompt_sha256: draft-1
translated_from: content/ru/1990/08/articles/02_panov-pryigayuschiy-myachik-i-teoriya-udara-34a7f954.md
source_content_sha256: eb5e68ffb650edd1f4af8fd4ce52194925f1010c6d2b9b0d1b54de2e17606618
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 2⟧

---
running_head:
folio:
---

The right-handed ball is a black (or maybe colorful or even multi-colored, depending on your luck) cast rubber ball with a diameter of several centimeters. I think that this toy is familiar to many of you. Every day I watch with satisfaction how numerous fans of right-handed balls appear on the dried asphalt after the classics fans. Let's take the right ball in our hands and teach our experiments.

Right-handed ball and Newton's hypothesis

Let the ball fall from a height $h$ on a horizontal plane, hit it and bounce vertically upward (Fig. 1). From the school physics course it is known that the speed of the ball at the moment of impact is equal to $v = \sqrt{2gh}$, where $g$ is the acceleration of gravity. We are interested in the speed $v'$ with which the ball begins to move upward after impact.

At one time, Newton, analyzing similar experiments with balls, came to the conclusion that the value $e = -v'/v$ is constant for a given ball and a given surface.

The assumption that the value $e$ is constant is called Newton’s hypothesis, and the constant $e$ itself is the restitution coefficient. If we assume that Newton's hypothesis is true, then to determine the value of $e$ for a given ball and a given surface, it is enough to check only one experiment. Namely, release the ball from a height $h$ and change the maximum height $h'$ at which it will rise after impact. Then the pre-shot speed of the ball will be $v = -\sqrt{2gh}$, and the post-shot speed will be $v' = \sqrt{2gh'}$ and, therefore, $e = \sqrt{h'}/h$.

I released the right-handed ball from a height of $h = 1$ m onto a smooth concrete slab, and it bounced to a height of $h' = 0,80 \pm 0,01$ m. Thus, for the right-handed ball and the concrete slab, the previous formula gives $e = 0,90$ with an accuracy of 0.01. This is a very high recovery rate. Under the same conditions, for a glass ball $e = 0,80$, and for a steel ball even less $e = 0,6$. So, for the right ball $e = 0,90$. How can you use this result? Let's release the ball again from a height of $h$, but this time we won't catch it after the first hit, but give it the opportunity to bounce indefinitely.

Problem 1. Prove that from Newton's hypothesis one should bounce over time

$$T = \frac{1 + e}{1 - e} \sqrt{\frac{2h}{g}}.$$ (1)

Note. Let $t_0$ be the time before the first strike, and $t_n$ be the time between strikes numbered $n$ and $n+1$. Then $t_1 = 2et_0$, $t_{n+1} = et_n$ at $n \geqslant 1$ and $T = t_0 + t_1 + \dots + t_{n+1}$.

⟦folio 6⟧

---
running_head:
folio:
---

(2)—(4). Show that $|v'_n+1/u'_n+1| \leqslant |v'_n/u'_n|$ for any $n$, i.e., only trajectories are possible in which the parallels become more and more flat.

Note. From (3) it follows that the quantities $|v'_n|$ kill. Using the geometric interpretation of correspondences (2) and (4), namely figure 8, show that the subsequent values ​​$u'_n$ return as $n$ increases.

But as for the second experiment:

Problem 4. Let the ball move between two vertical parallel planes $u$, as in figure 5, before the first impact $u_1=0$, $\omega_1=0$. Let also, upon impact, correspondences (2) and (4) be fulfilled. Show that then for any $n$ $u'_n \geqslant 0$, i.e., after each impact, the speed of the ball is directed downward.

This task is more necessary than the previous one. I will only say that here too the geometric interpretation of correspondences (2) and (4) should be used. Thus, problem 3 shows that when fulfilling correspondences (2)—(4), there cannot be trajectories like the one on figure 4. And problem 4 shows that when fulfilling (2) and (4), there cannot be trajectories like the one on figure 5. From here we conclude that for a spinning ball, at least one of the correspondences (2) must be violated. or (4). To find which one, it is enough to return to the experiment, illustrated at figure 4. Before the first blow, $u_1=0$, $\omega_1<0$, therefore $u_1+r\omega_1<0$. The experiment shows that after the first strike $u'_1>0$ and $\omega'_1>0$, i.e. $u'_1+r\omega'_1>0$. Therefore, $(u'_1+r\omega'_1)/(u_1+r\omega_1)<0$, which contradicts correspondence (4).

We have obtained an important result. It turns out that the spinning ball does not behave as the theory dictates. And they precisely indicated the place where the theory is violated - this is correspondence (4). But, of course, we still need to find out whether (4) actually allows us to obtain trajectories similar to those in Figures 4 and 5.

Linear models

Using our previous experience in discussing Newton’s hypothesis, we will try to build such a simple mathematical model of impact that it still allows us to obtain both the trajectory chosen at figure 4 and the trajectory chosen at figure 5. Let me remind you that we always adhere to the notation figure 6, where $v$ is the component of the pre-impact velocity the center of the ball, directed perpendicular to the impact plane, $u$ is the component directed along this plane, and $\omega$ is the pre-impact angular velocity of the ball; $u'$, $v'$, $\omega'$ - correspond to post-shot velocities.

Although we refuted Newton’s hypothesis and found out that the ratio $v'/v$ depends on the value of the pre-impact velocity $v$, we also replaced that the value $v'/v$ changes little when $v$ changes over a wide range. Therefore, in our model, we assume that Newton’s hypothesis is that the recovery coefficient $e=-v'/v$ is a constant value and does not depend on the pre-impact velocity $v$. For a spinning ball, we can take $e=0,9$, and in general, $e$ is some constant contained within $0 \leqslant e \leqslant 1$. The quantity $u_A=u+r\omega$ is the component of the impact velocity (figure 6) directed along the plane. We will also accept hy-
