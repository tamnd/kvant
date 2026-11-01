---
id: 1986-8-balk-sekret-starogo-bondarya-1894f471
issue: kvant_1986_8
year: 1986
number: "8"
title: The Old Cooper's Secret
authors:
  - Балк М. Б.
rubric: osnovnye-stati
page_first: 17
page_last: 20
page_labels: 15-18
tag: KU0Q
lang: en
source: kvant_digital
extraction: vision
content_sha256: 76200bdec3101c8ceabc0269e0160bb71d9cf9c0754763fe4e9711e32e08638f
prompt_sha256: draft-1
translated_from: content/ru/1986/08/articles/08_balk-sekret-starogo-bondarya-1894f471.md
source_content_sha256: 46e3b558ef4248a60b0e32e19ffeb833f39d15f24a0fa5609ffd72ec5a5c5b34
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 15⟧

For example, they fill a barrel there, without quantities of leaves, “amphoras” (a container taken as a unit of measurement), and then burn it onto the barrel together - so that, God forbid, you don’t have to perform this tedious procedure again.

And here... The guy pushes the copper end of the ruler through the filling hole of a full barrel (Fig. 1),

Pis. 1.

across to the “heel” (the lowest point) of the wooden bottom, and according to the mark on the ruler that was at the filling hole (at the top point of the “belly” of the barrel), he immediately names the barrels together. The barrels were different - large and small, more “pot-bellied” and completely “thin” - but this did not bother the guy, he gave the answer equally quickly and confidently. “Do you need any wishes?” - flashed through Kepler's head.

“Don’t worry, Mr. His Majesty’s Mathematician,” said the guy, as if he had read Kepler’s thought. — This method of measuring capacity has been established in Linz by the city authorities, and their coopers vouch for the accuracy of the measurement.

- Do you need any barrels?

“I don’t know about any, but for the barrel here in Austria, I’m sure it was compiled by a guy.”

- But on what basis are you so sure of the correctness of this method?

- I don’t know, I don’t know that. I won't lie. They say that many years ago the Old Bondar lived here, and he suggested this method. I don’t know why he suggested that.

***

He spoke about how Kepler unraveled the secret of the author's coopers in the book “New stereometry of wine barrels, mainly Austrian, as having the most advantageous shape, and the extremely convenient use of a cubic ruler for them, with an additional addition to Archimedean stereometry.” Although the book was published 370 years ago (1615), it is, as we will see, still received today.

Fig. 2.

cylindrical barrels (Fig. 2). Let $ND=\lambda$, the length of the generatrix $AB$ be equal to $2x$, the diameter of the body $AD$ be equal to $2y$; Then

$$x^2+4y^2=\lambda^2,$$

(1)

and together the barrels can be found using the formula

$$v=\frac{1}{2}\pi(\lambda^2-x^2)x.$$

(2)

It is not difficult to express the barrels together through the distance $\lambda$ and the ratio $(t)$ of the length of the generatrix to the diameter of the dish $(t=x/y)$. From (1) and (2) it follows that

$$v=2\pi\lambda^3t(4+t^2)^{-\frac{3}{2}}.$$

(3)

“From these formulas it is clear,” Kepler reasoned, “that the capacity of a cylindrical barrel is not determined only by the distance $\lambda$; In order to be able to use the Austrian coopers' method, we must deal with barrels for which the ratio $t$ is fixed $(t=t_0)$. What is the best way to choose this relationship? What is the best way to choose the correspondence between the length of the generatrix and the diameter of the dish? We think from the point of view of a winemaker. He is interested in choosing—among all possible values ​​of the parameter $t$—a value $(t_0)$ such that among all the barrels for which the location $ND$ is equal to $\lambda$, the barrel he selected has the largest volume $(v_0)$: then he can calculate its capacity using formula (3), and if

⟦folio 16⟧

It turns out that when making a barrel, the cooper was not able to accurately observe the ideal ratio $t_0$, but deviated a little from it ($t \approx t_0$, but $t > t_0$ or $t < t_0$), then VINDel will also not go wrong: the actual capacity of the barrel $v$ will necessarily be less than $v_0$. Thus, INDEL will call the volume $v_0$ (and will receive the corresponding payment from the buyer), but in fact will give the buyer a slightly smaller amount of wine, namely $v$.

But, on the other hand, a self-respecting businessman is not interested in deceiving the buyer; he is interested in ensuring that the capacity of the barrel implementation (corresponding to the implementation of the choice of parameter $t$, close to $t_0$) differs as little as possible from the capacity $v_0$, corresponding to the best value of the parameter ($t_0$). The buyer is even more interested in this. It turns out that this is also achieved with such a choice of parameter $t$, at which the volume of the barrel $v$ is greatest.

Knowing the concept of derivative, we can easily substantiate this message of Kepler (it was much more difficult for Kepler than for us to find a substantiation: after all, his book was published 70 years before the birth of differential calculus). Let's use it as follows. Let $f(t)$ be some function of $t$ (for the sake of simplicity, one that has a first-order derivative at $t > 0$); let $t_0$ be some value of the argument $t$ that we choose. Then, with a small increment $h$, that is, with $t = t_0 + h$, we have

$$f(t) - f(t_0) = f'(t_0)h + \alpha(h) \cdot h,$$

where $\alpha(h) \rightarrow 0$ at $h \rightarrow 0$ (see “Algebra and principles of analysis 9-10”, paragraph 22).

From here we see: if $f'(t_0) \neq 0$, then the deviation of $f(t)$ from $f(t_0)$ will be - for small $h$ - practically proportional to $h$. But if $t_0$ is the maximum (or minimum) point for a given function, then the deviation is $\alpha(h) \cdot h$, where $\alpha(h) \rightarrow 0$ is at $h \rightarrow 0$. This means that near the extremum point ($t_0$), the slight deviation of the parameter $t$ from $t_0$ affects the change in the function $f(t)$ much weaker (Kepler says: “insensitive”) than near another value of the argument $t$, where $f'(t) \neq 0$. In relation to our case (see formula (3)), this means that it is most advantageous to choose the parameter $t$ so ($t = t_0$) that the cylindrical barrel has the highest capacity ($v_0$): in this case, if necessary and inevitable in practice, deviations of the parameter $t$ from $t_0$ deviation of the capacity $v$ of the barrel from $v_0$ would be "insensitive".

Kepler finds (given $\lambda$) the value of the ratio $t$ at which the capacity of the barrel ($v$) will be most suitable. Using the concept of arbitrary, we can do this much easier and faster than Kepler. Let us use formula (2) for $v$. Then

$$v'(x) = \frac{1}{2} \pi(\lambda^2 - 3x^2),$$

$$x = \lambda / \sqrt{3}, 4y^2 = \lambda^2 - x^2 = 2\lambda^2 / 3, y = \lambda / \sqrt{6},$$

$$t_0 = x / y = \sqrt{2} \approx 1,41.$$

(4)

With this value of the parameter $t$, the capacity of the cylindrical barrel will be maximum (for a given $\lambda$) and will be equal to

$$v_0 = \frac{\pi}{3\sqrt{3}} \lambda^3.$$

(5)

* * *

“I will now turn to a more general case,” Kepler reasoned, when the “rivets” of the barrel (the boards that make up its side surface) will be curved (and not straight, as in the case of a cylindrical barrel). Such a barrel can be imagined with sufficient accuracy as being composed of two identical truncated cones, formed by their large bases (Fig. 3).

Fig. 3.

At the same time, of course, I will allow some miscalculation, but if the barrel is not very close to the distance $ND$ equal to the given $\lambda$, I will choose the one that has the highest capacity.”

⟦folio 17⟧

Following this solution plan proposed by Kepler, we can express the capacity (v) of the barrel in terms of the distance λ, in terms of the radius (y) less than the base of the truncated cone, and in terms of the distance z=NF (F is the base of the perpendicular dropped from the point D less than the base of the truncated cone to the larger base). Let us carry out these calculations using the formula for the volume of a truncated cone and taking into account that the height of the truncated cone is $DF=\sqrt{\lambda^2-z^2}$. Simple transformations lead us to the formula
$$v=\frac{2}{3}\pi\left(y^2+(z-y)^2+y(z-y)\right)\times\sqrt{\lambda^2-z^2}.$$
(Kepler managed to find out at what ratios between the dimensions of the barrel (in other words, at what values ​​of y and z for a given λ) the togetherness of the barrel will be most complete. We could obtain Kepler’s result by solving the following problem:

Task a. Prove, using the concept of arbitrary, that among a barrel of the specified type with a given value λ of the distance ND, the most compatible is a cylindrical barrel, which has a disc forming a larger diameter at $\sqrt{2}$. (For the solution, see p. 63.) Now let’s take into account Kepler’s message that “near its maximum point, a small change in the arguments of a function has an insensitive effect on the change in its value.” In our case, this means that if the dimensions of a barrel deviate slightly from the dimensions of the existing barrel (that is, cylindrical, with a ratio of $AB:AD=\sqrt{2}$), then these deviations “insensitively” affect the capacity of the barrel. Therefore, the volume of a barrel that differs little from the “best” one can be calculated using the same formula (5).

“Now it’s clear,” Kepler thought, what an “Austrian” barrel is: this is a barrel whose generatrix ANB is approximately $\sqrt{2}$ times its diameter. Since when choosing the length of the “rivet” $PNQ$ one should also take into account the thickness of the two bottoms and the fact that the riveting should extend slightly beyond the edge of the bottoms, in practice this means that the riveting should be approximately one and a half times the length of the diameter of the bottoms.”

Moreover, Kepler became clear how to find the volume of the “Austrian barrel” using a regular ruler: you need to change the distance ND and calculate the capacity of the barrel $v_0$ using formula (5). “It’s not like the winemaker named the volume of the barrel without calculations! - Kepler thought. - Apparently, the fact is that the ruler is not a teaching one, the marks on it are placed differently from the general ruler. How is this ruler programmed?...

First, we need to tell you what kind of thin-walled “amphora” this Vnodeel was talking about. This is probably also some kind of barrel, but its totality is taken as a unit of volume. But if Austrian barrels prefer to make all barrels so that the ratio of the length to the diameter of the base is optimal (about 1.5), then in the manufacture of the standard barrel, the “amphora,” they suffered from the same ratio. Let the reference barrel (Fig. 4) have a distance $N_1D_1$ equal to $\lambda_1$. Then

Fig. 4.

we have (see (5)) $1=(\pi/3\sqrt{3})\lambda_1^3$. Taking into account (5), we obtain for the capacity of any “Austrian” barrel such a good approximate formula: $v_0=(\lambda/\lambda_1)^3$ (amphoras). This means that in order to find $v_0$, it is enough for us to know not $\lambda$, but the relation $\lambda/\lambda_1$. And not even this relation itself, but its cube. The numbers $(\lambda/\lambda_1)^3$ for different $\lambda$ must be applied to the ruler, that is, the ruler should not be graduated evenly, but according to the “cubic law”. At a distance from the copper tip (Fig. 5), equal to $\lambda_1$, $2\lambda_1$, $3\lambda_1$, etc., put marks: 1; $8=(2^3)$;

Fig. 5.

$27=(3^3)$, etc. And in general - at a distance $k\lambda_1$ (k is any positive number) put a mark equal to $k^3$. If I now insert such a ruler into the barrel so that its copper

⟦folio 18⟧

the tip rested on the heel of the bottom (D), then the numerical mark at the filling connection (N) just indicates how many amphorae are in the barrel together.”

* * *

In the autumn of 1615, at the request of Kepler, in the city hall of Linz he met with the head of the coopers' workshop.

“Mr. Elder,” Kepler began, “I am interested in the method that Austrian coopers and winemakers use to measure the integrity of barrels.”

“You see, Mr. His Majesty’s mathematician,” the headman objected, “this is an arbitrary secret of our workshop.” This secret has been passed down from one generation of coopers to the next, since the time of the Old Cooper.

“I thought that once upon a time there was a certain excellent geometer who taught this method to your coopers.” But I thought that I was able to unravel his secret.

“Then tell me, Mr. His Majesty’s Mathematician, what, in your opinion, is the secret of the Old Bondar, and I promise to confirm what you say will be true.”

“Reflections have led me to the conclusion,” answered Kepler, “that when making a barrel of any size, you, coopers of Linz, use only one message: that the length of the staves be one and a half times greater than the diameter of the bottom.”

“Absolutely true!” the cooper confirmed with surprise.

— And besides, to measure the capacity of the barrel, you use a ruler on which the divisions are located according to the “cubic law.”

“And it’s true,” the head of the cooper’s workshop confirmed with even greater surprise, looking dangerously at Kepler. “Aren’t you a clairvoyant, Mr. Kepler?” I heard that you, as a royal star, can read the past and future by the location of the stars. Did you really need to figure out the Old Bondar's secret with the help of astrology?

“No, I calculated it using mathematics,” Kepler replied, and that was the end of the conversation.

Dry rubbing

(For the beginning, see p. 8)

With a uniform movement of the bow, the string is carried away by it and stretched. Along with the tension of the string, the friction force between the bow and the string is carried away. When the magnitude of the friction force becomes the maximum possible, the string begins to pierce relative to the bow. If the friction force did not depend on the relative speed of the bow and string, then obviously the deviation of the string from the equilibrium position would not change.

But when pierced, the trene decreases. Therefore, the string begins to move towards the equilibrium position. In this case, the relative speed of the string is entrained, and this further reduces the friction force. When the string, having vibrated, moves in the opposite direction, its speed relative to the bow decreases, and the bow again grabs the string. Everything repeats itself. This is how the flask scab arose. These vibrations are insignificant, since the energy lost by the string during its movement each time makes up for the work of the friction force, which strengthens the string to the position at which the string breaks.

This can justify an article about dry friction - a phenomenon whose nature we do not yet fully understand, but we can describe with the help of laws that are fulfilled with satisfactory accuracy. This gives us the opportunity to explain many physical phenomena and make calculations necessary when designing machines.
