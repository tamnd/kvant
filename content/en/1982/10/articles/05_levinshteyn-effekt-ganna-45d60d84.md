---
id: 1982-10-levinshteyn-effekt-ganna-45d60d84
issue: kvant_1982_10
year: 1982
number: "10"
title: Gunn effect
authors:
  - Левинштейн М. Е.
rubric: osnovnye-stati
page_first: 13
page_last: 23
page_labels: 11, 12, 13, 14, 15, 16, 17, 20, 21
tag: RO8K
lang: en
source: kvant_digital
extraction: vision
content_sha256: d0c570a9d4fac64bf841aa05da8132a17c6583fd5f9e050fd7ebb4a10a43e189
prompt_sha256: draft-1
translated_from: content/ru/1982/10/articles/05_levinshteyn-effekt-ganna-45d60d84.md
source_content_sha256: cc5e065790f5c74d293bb9fef1d112c0bd43ad5b7270c4702380fc8d027c767e
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 11⟧

Gunn effect

About twenty years ago, in the early sixties, the English physicist John Gunn decided to study the current-voltage characteristics of the then relatively new semiconductors - gallium arsendum and indium phosphide - in strong electric fields. Unexpectedly, Gunn discovered an amazing phenomenon: when the direction applied to the sample exceeds a certain value, the current in the semiconductor at a constant voltage begins to move over time. It was amazing and completely incomprehensible.

An experienced experimenter and a well-known specialist in the field of semiconductor physics, Gann could not find any explanation for this effect. He described the results of his observations in 1963 in a short note that immediately attracted the attention of dozens of physicists and engineers around the world. Physicists found it interesting to explain this amazing phenomenon. Engineers immediately realized that Gunn's discovery heralded the emergence of a new semiconductor oscillator that could operate at ultrahigh frequencies. Such generators were very necessary in many areas of radio electronics, including radar and communication systems.

Dozens of specialists have pondered the nature of the phenomenon discovered by Gann. However, a year passed before it could be explained.

Let's try to understand the nature of the Gunn effect.

Let's imagine that we, like Gunn in his time, set out to study the current-voltage characteristic (that is, the dependence of current on voltage) of some semiconductor, for example germanium (Ge), silicon (Si) or gallium arsenum (GaAs).

Let us have at our disposal a massive single crystal, which is an n-type semiconductor (in which the main charge carriers are electrons) with a resistivity q. First, let’s cut out a regular-shaped sample from this single crystal, the most convenient one is a primangular paralleliped.

(This is not an easy task, since semiconductors are quite difficult to machine, and we will have to use a tool whose edge contains superhard materials - corundum, CBN or diamond.) Now touch the side edges of the sample with the changing ends of the tester (a device for measuring resistance). It is natural to expect that the resistance of the sample we have modified will be equal to

$$R_0 = \varrho \frac{l}{S} = \frac{l}{\sigma S} = \frac{l}{\sigma hd},$$

where $\sigma = 1/\varrho$ is the conductivity of the semiconductor, and $l, h, d$ are the geometric dimensions of the sample (Fig. 1). However, the resistance value that the device detects turns out to be millions of times greater than the value predicted by this formula. The fact is that in places of resistance of the metal ends of the tester with a semiconductor, a thin near-surface charged layer will appear - the so-called

Fig. 1. Sample with contacts.

⟦folio 12⟧

New semiconductor materials are usually produced in the form of tiny single crystals, fractions of a millimeter in size. However, modern technology makes it possible to obtain such well-studied and widely used semiconductors as Ge (1), Si (2), GaAs (3) in the form of single crystals with a volume of ten and hundreds of cubic centimeters.

the barrier is metal - semiconductor, and the device will change the resistance of the barrier, not the resistance of the sample.

To overcome this difficulty, the lateral faces of the sample must first be made into “ohmic contacts”, in which there are no barriers. As a rule, such contacts are obtained by melting certain metals (indium, tin) or alloys (germanium - gold, germanium - silver) into the side faces. It is impossible to make a good “ohmic contact”. It is necessary to select the contact material, the temperature and mode of fusing, the atmosphere in which the fusing should be carried out (often this is an atmosphere of hydrogen or an inert gas), and prepare the surface of the side faces in a certain way.

But now all the difficulties are behind us, and the tester connected to the side edges of the sample shows that the resistance is equal to the calculated value $R_0$. Now you can start measuring the current-voltage characteristic.

As long as the voltage $U$ applied to the sample is not large, the current, as would be expected, is proportional to the voltage—Ohm's law $I = U/R_0$ holds. However, at high voltages, the current begins to grow significantly faster than required by Ohm’s law (curve 1 at figure 2).

This is not surprising: when the current and voltage are high, the sample is heated by Joule heat. As is known, semiconductors, in particular, differ from metals in that with increasing temperature their conductivity increases, that is, the resistivity decreases. When a semiconductor is heated, more and more electrons break their bonds with the atoms of the crystal lattice and become free. As the concentration of free electrons increases, the resistivity of the materials decreases and the resistance of the sample decreases. This means that at the same voltage on the sample, the current becomes greater. An increase in current leads to even more heating of the sample, an even greater increase in the electron concentration, etc. This is why the current increases so sharply when heating of the sample by Joule heat becomes noticeable.

(By solving problem 1, located at the end of the article, you can find at what voltages and currents the current-voltage characteristic begins to differ from the ohmic one due to heating of the sample by the flowing current.)

It is interesting to estimate what is the speed of ordered movement of electrons along the field (drift speed of electrons) under conditions when Joule heating begins to cause a sharp increase in the current in the field.

⟦folio 13⟧

as the voltage increases. The movement of electrons in a semiconductor is similar to the movement of a body in a viscous liquid: an external force determines the steady-state speed of movement. Therefore, the drift speed of electrons $v_\pi$ is proportional to the intense electric field -

$$v_\pi = \mu E = \mu \frac{U}{l}.$$

The proportionality coefficient is called mobility. As can be seen from formula (*), the numerical mobility is equal to the drift velocity at a field strength equal to unity. If the dimension $v$ is m/s, and the dimension $E$ is V/m, then the dimension $\mu$ is $\frac{m^2}{(B \cdot c)}$. The range of electron mobility values ​​for various semiconductors is very wide: from $\sim 10^{-5} \text{ m}^2/(B \cdot c)$ to $\sim 10^2 \text{ m}^2/(B \cdot c)$. At room temperature for Ge $\mu \approx 0,5 \text{ m}^2/(B \cdot c)$, for Si - 0.1 $\text{ m}^2/(B \cdot c)$, for GaAs - 0.8 $\text{ m}^2/(B \cdot c)$. As calculations show (see Problem 1), the value of the field strength at which the influence of Joule heating begins to distort the appearance of the current-voltage characteristic does not exceed $\sim 10^4$ V/m. In this case, the values ​​of the drift speed of electrons are no more than $10^3-10^4$ m/s.

It is important to emphasize that when, due to Joule heating of the semiconductor, the current begins to increase sharply with increasing voltage, the mobility value does not change. The current returns due to the fact that heating causes the appearance of “additional” electrons.

So, Joule heating distorts the shape of the current-voltage characteristic of the semiconductor in the region of high kinetic voltage; the current grows more slowly than according to the linear law. At very high voltages, the current practically changes depending on the voltage - it saturates (curve 2 at figure 2).

Wire experiments with samples of different lengths $l$, one can notice that deviation from Ohm’s law and saturation always occur at the same values ​​of electric field strength $E = U/l$.

The first thing that comes to mind when trying to explain this phenomenon is to assume that for some reason, as the field grows $E$ concentration begins to kill $n$ electrons in the region. However, this is not true. Control experiments show that in pure Ge and Si the concentration of electrons in those fields in which current saturation is observed does not depend on the field. Since the current is

⟦folio 14⟧

Fig. 3. Dependence of the electron drift velocity $v_d$ on the electric field strength $E$ for Ge (curve 1) and Si (curve 2).

is equal to $I = env_d hd$, current saturation at a constant electron concentration means that in Ge and Si the drift velocity of electrons in strong electric fields does not depend on the field strength.

At first glance, this situation seems very strange. The electric field accelerating the electrons increases, but the speed of the directional movement of the electrons does not change. Let us remember, however, that the drift velocity of electrons is determined by two processes: the acceleration of electrons by the field and their deceleration as a result of interactions with atoms of the crystal lattice. The amount of mobility is precisely determined by the processes of collision of electrons with the crystal lattice. So it turns out that at high fields the efficiency of these processes increases, and the mobility of electrons in Ge and Si decreases with increasing field. In very strong fields, mobility falls in inverse proportion to the field strength. In this case (see formula (*)) the electron drift velocity ceases to depend on the field strength $E$ - it becomes saturated (Fig. 3).

The saturation of electron drift velocity in Ge and Si in strong electric fields was discovered before Gann began his research. The obstacle that the properties of electrons in strong fields can differ very noticeably from the properties of electrons in weak electric fields was also well known. But the effect that Gann observed in the samples

Fig. 4. Time dependence of voltage on the sample (a) and current through the sample (b) in Gunn’s experiments. The dotted line shows the case when $U < U_n$, with the help of curves - when $U > U_n$.

⟦folio 15⟧

samples: $U_n = E_n l$, where $E_n$ is the approximately identical field strength value for all samples. For GaAs, the value of $E_n$ was approximately 3.2 · 10⁵ V/m. The period of current oscillation was also proportional to the length of the sample and equal to approximately $T \approx 2l/v_n$, where $v_n \approx \mu E_n$.

Trying to understand what happens in the sample when oscillations occur, Gang carried out a study of the effectiveness he had discovered, which was equivalent to the level of experimental skill. He found that when the voltage on the sample exceeds the threshold value $U_n$, the nature of the current flow and the distribution of the electric field voltage in the sample completely change. At $U < U_n$, the current in the sample is a flow of electricity flowing from the contact of the sample to which the “minus” voltage source is applied (from the cathode) to the contact to which the “pipe” is applied (to the anode); the electric field is distributed uniformly along the sample (dashed curve at figure 5). Under these conditions, the current-voltage characteristic of the sample corresponds to Ohm's law. But as soon as the voltage applied to the sample reaches the threshold

Fig. 5. Electric field distribution in the sample at $U < U_n$ (dashed curve) and at $U \geq U_n$ (solid curve). The arrow indicates the direction of propagation of the house from the cathode to the anode. The upper part figure schematically shows the movement of the house according to the pattern.

When the value of $U_n$ is reached, the nature of the field distribution along the sample changes sharply. A narrow region of a very strong field—a “domain”*—will appear in the sample near the cathode. Although the width of this region is not large, the real advantage in it is that a significant part of the voltage applied to the sample falls on the domain (Fig. 5). The domain moves from the cathode to the anode with a speed approximately equal to $v_n/2$. The anodic contact is reached, the domain is destroyed. Immediately after this, a new domain is born at the cathode, and everything repeats again.

It is easy to understand how the periodic movement of the house in a pattern is related to the fluctuations in current that Gang observed in his first experiments.

Let a voltage equal to $U_n$ be applied to the sample. A significant portion of the voltage will arise in the sample and drop across the domain. But this means that the rest of the sample, where there is no domain, now experiences less voltage; therefore, the field outside the domain fell (compare the dotted and solid curves at figure 5). The value of the electric velocity, which is proportional to the field, also dropped, and, consequently, the current flowing through the sample also dropped.

While the domain moves along the sample, the current does not change. When the domain reaches the anode, it begins to disintegrate, and the voltage pad across it decreases. In this case, the field in the rest of the sample increases, and, consequently, the current increases. But as soon as the field in the sample in the cathode region reaches the threshold value $E_n$, a new domain begins to form in the sample, and the current begins to decrease again. As long as the voltage applied to the sample exceeds the threshold value $U_n$, this process is repeated periodically (see Fig. 4, b).

*) The word “domain” comes from the Latin word dominis (master, master). In the Middle Ages, a “domain” was called the personal possession of a large feudal lord. In physics, "domain" is used to designate an area whose properties differ sharply from the properties of the material surrounding it. There are ferromagnetic, ferroelectric domains, strong and weak field domains. figure 5 shows the strong field domain.

⟦folio 16⟧

Wonderful experiments
Gunn was allowed to “see” what happens in a sample when current oscillations occur in it. However, they did not answer the question of why a domain is formed in the sample, what is the physical reason for the formation of the domain.

American physicist Herbert Kremer was able to answer this question in 1964. He recalled that shortly before Gunn’s discovery, on the basis of theoretical calculations, it was shown that in galley arsenide, indium phoside and some other semiconductors, the dependence of the electron drift velocity on the field strength should have the form as at figure 6. In a certain range of field strength values $E$, starting from the value $E_n$, the electron drift velocity decreases with increasing strength fields. Based on formula (*), we must conclude that in this range of values ​​of $E$ the mobility of electrons decreases with increasing $E$ so sharply that the drift velocity decreases, although the electric field strength increases.

How are the coefficients that Gunn observes related to this type of dependence of the electron velocity on the field?

To answer this question, let's first consider an obvious simple problem.

Let voltage $U_1 < U_n$ be applied to the sample. In this case, the field along the sample is distributed uniformly

Fig. 6. Dependence of the electron drift velocity $v_d$ for GaAs on the electric field strength $E$. A similar dependence is characteristic for many other semiconductors (InP, GaInSb, InGaAsP, etc.).

is native and equal to $E_1 = U_1/l$. The drift speed of electrons $v_1$ is equal to $v_1 = \mu E_1$ (see Fig. 6), and the current is a stream of electrons flowing at a speed $v_1$ from κατάda to the anode. Let us now assume that somewhere in the sample a small region has accidentally formed in which the direction of the field is slightly greater than the value $E_1$. Due to the chaotic nature of the motion of electrons in a crystal, small deviations of the field from the average value $E_1$ (field fluctuations) arise continuously, and our task is to monitor what happens to such a fluctuation when it arises.

If in some area of ​​the sample the field has become slightly larger than in the rest of the sample, this means that electrical charges have accumulated at the boundaries of this area: negative on the cathode side and positive on the anode side (see Fig. 5). In other words, a small amount of electrons was formed to the left of the selected area, and a small “deficit” of electrons was formed to the right. Adding to the field of an external source, the fields of these “bulk” excess charges succeed the field inside the selected area.

What will happen to such field fluctuations in the future?

Since we are considering the case when $E_1 < E_n$, the speed of the electrons is proportional to the field. Consequently, the electrons within the fluctuations move quickly throughout the rest of the sample. This means that the fluctuation will “run away” from the excess electrons on the left and “catch up” with the area on the right where the electron is missing. As a result, the field fluctuation will dissipate.

Now let's see what happens to the fluctuations when the field voltage $E_2$ in the sample is slightly greater than the threshold value $E_n$ (see Fig. 6). We will continue to assume that initially the field is distributed uniformly along the sample; due to charge fluctuations, space charges arise; As a result, in a small area of ​​the sample the field turns out to be larger than in the rest of the sample. But now there is more polo-

⟦folio 17⟧

responds by changing the drift speed (see Fig. 6)! This means that the fluctuation moves slower than the electrodust one and to the right of it. As a result, to the left of those already available in the lime, there will be electricity fluctuations, fluctuation agreements, new electrodust fields, where there is a “shortage” of electrons, there will be even fewer of them: the electrodust fields will “run away” from the fluctuation. Thus, the space charge will become larger and the field inside the fluctuation will increase. But an increase in the field at $E > E_n$ corresponds to a decrease in the drift speed. As a result, the fluctuation will move even more slowly, even more electrons will accumulate to the left of the fluctuation and even fewer will appear to the right, the field inside the fluctuation will become even larger, etc.

So, under conditions when the drift speed of the electrons decreases with increasing field, the uniform field distribution is unstable with respect to small field fluctuations: if they become separated, such a fluctuation begins to grow uncontrollably.

When will the growth of the space charge at the fluctuation boundaries and, consequently, the growth of fluctuations stop? For this, it is very important that the speed of the electrons inside the fluctuation be equal to the speed of the electrons outside it.

While the excess field inside the fluctuation is small, a small voltage drops across it, and its presence in the sample practically does not affect the speed of the electrons outside the fluctuation. However, as the field inside the fluctuation increases, the voltage on it begins to decrease more and more. In this case, the voltage on the rest of the sample becomes less (since the total voltage applied to the sample is constant). The field outside the “fluctuation” falls. The word “fluctuation” is put in quotation marks because it is somehow inconveniently called “a word denoting a necessary random deviation - a formation that absorbs a noticeable fraction of the voltage applied to the sample. Such strongly expressing fluctuation is a domain. Outside the house, the speed of the electrons decreases with decreasing field, since the field outside the house is always less than $E_n$. Thus, as the house grows, the speed of the electrons outside the house decreases. Eventually, the speeds of the electrons inside and outside the house will become equal and the growth of the domain will stop. According to the pattern, from the kaod to the andug there will be a “stable” section of a strong field that does not change in shape - a domain.

These domains are observed by Gunn in his experiments. The maximum field in domain $E_{max}$ can be very large. With an average field on the sample of $E_n = U_n/l = 3,2$ kV/cm, the value $E_{max}$ can be $20 \div 300$ kV/cm.

Over the years since Gunn's discovery of the effect of current oscillations in GaAs and InP, more than 2.5 thousand papers devoted to the study of the Gunn effect and various related physical phenomena have been published in scientific journals.

The Gunn effect has been observed to date in more than twenty conductor compounds: indium antiimonide (InSb), arsenic antiimonide (AsSb), in rolled germanium, in silicon cooled to low temperatures, in ternary semiconductor compounds GaAlAs, InGaSb, InAsP, in the quaternary compound InGaAsP and many other semiconductors.

The main application of Gunn diodes (as samples in which the Gunn effect is observed are usually called) are ultrahigh frequency generators.

When the radar pulse reflected from the targets returns to the anti-neradion level, it must be amplified. The circuit of a sensitive modern amplifier necessarily includes a relatively low-power, but very stable and low-noise generator (heterodyne). Hann diodes successfully operate as generators in many modern radars.

Hundreds of thousands of people die as a result of machine gun accidents around the world every year. However, from the basic principles, an accident is exceeding the permitted speed. In the city for compliance

⟦folio 20⟧

To clarify this estimate, we introduce the concept of event probability. The ratio $p$ the number of ways in which the event of interest to us can occur to the total number of equally possible options is called the probability of this event. Obviously $0 \leq p \leq 1$.

In our case ($n=2, m=10$) we denote by $p_0$ the probability of the event that the zero participant went for lemonade, and by $p_1$ the probability that the first one went. Then $p_0 = \frac{61}{121} \approx 0,504, p_1 = \frac{60}{121} \approx 0,496$.

It is not difficult to calculate that in the case of “throwing” on one hand with $n=2$ and $n=3$ the players’ chances of being chosen are the same and are equal to $\frac{1}{2}$ and $\frac{1}{3}$, respectively, and with $n=4$ $p_0=0,248, p_1=p_3=0,25, p_2=0,252$. As $n$ increases, the selection of options becomes more and more successful. We carried it out using a computer up to $n=100$, based on the following messages.

Let us denote by $\Pi_m^n(N)$ the amount of representation of the number $N$ in the form of a sum $n$ of integer non-negative terms, each of which does not exceed the number $m$ (in this case, representations that differ in the order of the terms are considered different!). Let us also denote by $\Pi_i$ the number of finger-throwing methods in which the choice falls on the $i$th participant, by $\Pi$ the total number of finger-throwing options, by $p_i$ the probability of choosing the $i$th participant. Thus, $p_i = \frac{\Pi_i}{\Pi}$.

The numbers $\Pi_i$ and $\Pi$ are easily expressed in terms of $\Pi_m^n(N)$. Since the maximum possible number of finger throws is $mn$,

$$\Pi = \sum_{k=0}^{mn} \Pi_m^n(k).$$

Since the choice falls on the $i$th participant, if the number of “throw out fingers” is $i+kn$, and, obviously, $k \leq m$ (note that for $N > mn$ $\Pi_m^n(N)=0$),

$$\Pi_i = \sum_{k=0}^{m} \Pi_m^n(i+kn).$$

(1)

The number $\Pi_m^n(N)$ can be calculated using a simple recurrence formula. The number of representations of the number $N$ that interest us, for which the first term is 0, is obviously equal to $\Pi_m^{n-1}(N)$; the number of such representations for which the first term is 1 is equal to $\Pi_m^{n-1}(N-1)$; for which the first term is 2 - $\Pi_m^{n-1}(N-2)$; etc. Since the first term takes one of the values ​​0, 1, 2, ..., $m$, $\Pi_m^n(N) = \Pi_m^{n-1}(N) + \Pi_m^{n-1}(N-1) + \dots + \Pi_m^{n-1}(N-m) = \sum_{k=0}^{m} \Pi_m^{n-1}(N-k)$ (2)

(in this sum, neokotryan terms can equal 0: if $N$ is “small”, then, starting from neokotryan $k$, maybe $N-k<0$ - then $\Pi_m^{n-1}(N-k)=0$; in addition, if $N$ is “big”, then, up to neokotryan $k$, maybe $N-k>m$ ($n-1$) - then also $\Pi_m^{n-1}(N-k)=0$).

Having calculated $\Pi_m^2(k)$ for all $0 \leq k < N$, we then use (2) to find $\Pi_m^3(N)$, etc.

Relation (2) also allows us to prove that $n=m+1$ the chances of all participants are equal. Really,

$$\Pi_i = \sum_{k=0}^{m} \Pi_m^n(i+kn) = \sum_{k=0}^{m} \left[ \Pi_m^{n-1}(i+kn) + \right. + \left. \Pi_m^{n-1}(i+kn-1) + \right. + \dots + \left. \Pi_m^{n-1}(i+kn-m) \right] = \sum_{k=0}^{m} \left\{ \Pi_m^n(i+km+k) + \right. + \left. \Pi_m^n(i+km+k-1) + \right. + \dots + \left. \Pi_m^n(i+km+k-m) \right\}.$$

The "curly bracket" for each $k$ looks like

$$\Pi_m^n(a) + \Pi_m^n(a-1) + \Pi_m^n(a-2) + \dots$$

It turns out that “curly brackets” with adjacent $k$ “join”: the first term in a “curly bracket” with $k=t$ is equal to $\Pi_m^n(i+tm+t)$, the last one is weak

⟦folio 21⟧

It is not difficult to understand that the number $\Pi_m^n(N)$ at $N=0$ is equal to 1, then with an increase in $N$ it increases, at $N=1 = \left[\frac{mn}{2}\right]$ it reaches a maximum, then sharply decreases and at $N=mn$ it becomes equal to 1 again. This dependence is depicted in figure 1.

Thus, the main contribution to the sum $\Pi_i$ (see (1)) comes from the term for which $N=i+kn$ is closest to $\left[\frac{mn}{2}\right]$.

If $m$ is even, then $\frac{mn}{2}$ is an integer and $\left[\frac{mn}{2}\right] = \frac{mn}{2}$. This means that the maximum of the function $\Pi_m^n(N)$ is achieved at $\frac{m}{2} \cdot n$ and the counting, carried out in a circle formed by $n$ participants, ends at the game with number 0 (see Fig. 2, a).

If $m$ is odd, the maximum $\Pi_m^n(N)$ is achieved at $N=\frac{m-1}{2}n + \left[\frac{n}{2}\right]$, and the maximum $\Pi_i$ comes at $i=\left[\frac{n}{2}\right]$, that is, at the game*), which is opposite zero (Fig. 2, b). In particular, at $m=5$ the player opposite the one from whom the counting begins will most likely run for the lemonade; at $m=10$ - the player with whom the counting begins. This difference in chances is greater, the more $n$ and the less $m$.

For the general class of secondary school ($n\sim 40$), when “throwing out the fingers” of one hand ($m=5$), standing up and directing the leader is more profitable (several times) than being him. However, I would like to believe that those who have mastered the theory will not use it for selfish purposes, but will tell their classmates about it.

*) If $n$ is odd, then sending zero player costs two players ($i=(n-1)/2$ and $i=(n+1)/2$) and a maximum of $\Pi_i$ comes to each of them.
