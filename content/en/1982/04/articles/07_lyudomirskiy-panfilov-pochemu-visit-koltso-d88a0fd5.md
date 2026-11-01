---
id: 1982-4-lyudomirskiy-panfilov-pochemu-visit-koltso-d88a0fd5
issue: kvant_1982_4
year: 1982
number: "4"
title: Why is the ring hanging?
authors:
  - Людомирский М.
  - Панфилов А.
rubric: laboratoriya-kvanta
rubric_sub: Лаборатория «Кванта»
page_first: 24
page_last: 26
page_labels: 22-24
tag: KO6K
lang: en
source: kvant_digital
extraction: vision
content_sha256: 24100ea21d1b1d12830e79c65c5978b84463bdab489729a8bf228075a468bb1d
prompt_sha256: draft-1
translated_from: content/ru/1982/04/articles/07_lyudomirskiy-panfilov-pochemu-visit-koltso-d88a0fd5.md
source_content_sha256: 522b9ebf7f60821231690a5cdee4bd62324087a0acec172268dfbc64f6e6c0ed
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 22⟧

Why is the stake hanging?

“Why does the aluminum stake hang loosely on the open core of the transformer?” — this question was proposed by a participant in the III Moscow Tour of Young Physicists. Probably, any ninth-grader, without hesitation, would answer something like the following: “Currents are generated in the ring, which interact with the external magnetic field. According to Lenz's rules, the indurian current is always directed in such a way that its action interferes with the cause that generated it. In this case, the indurion currents have such a direction that the Ampere force seems to push the stake away from the transformer coil. In some, this force balances the gravity of the ring, and it hangs in the air.”

It is easy to verify that this behavior of the ring is due precisely to indurian currents. To do this, simply cut the stake across - it will not hang under any conditions. However, there are two points in the above explanation that we would like to draw attention to. Firstly, it is not clear which ring resistance - active or inductive - plays a decisive role. Secondly, the existence of only one equilibrium position of the ring needs to be explained. Let's try to understand these issues.

1. Let us show that the ring hanging effect would not exist if the ring had only active resistance. Let's do some calculations.

The Ampere force acting on a thin stake of length l carrying a current I is equal to

$$F = B_r I l,$$

where $B_r$ is the horizontal projection of the magnetic induction vector of the external field (Fig. 1). Induction current I is determined by Ohm's law:

$$I = \frac{\varepsilon}{R}.$$

Here $\varepsilon$ is the electromotive force of induction, $R$ is the active resistance of the ring. According to the law of electromagnetic induction, the induced emf is equal to the rate of change of the magnetic flux, taken with the opposite sign:

$$\varepsilon = -\Phi' = -(B_B S)'$$

($B_B$ is the vertical projection of the magnetic induction vector, $S$ is the area limited by the volume). Let the magnetic field vary according to the harmonic law with frequency $\omega$, then

$$B_r = B_{rm} \cos \omega t,$$

$$B_B = B_{bm} \cos \omega t,$$

$$\varepsilon = -(B_B S)' = B_{bm} S \omega \sin \omega t.$$

$$I = \frac{\varepsilon}{R} = \frac{B_{bm} S \omega}{R} \sin \omega t,$$

And

$$F = B_r I l = \frac{B_{rm} B_{bm} S \omega}{2 R} \sin 2 \omega t,$$

where $B_{rm}$ and $B_{bm}$ are the maximum values ​​of the horizontal and vertical projection of the induction vector.

Since the average value of the sine over the period is zero, the average value of the Ampere force is also zero. Therefore, Kolyu will not be able to do everything.

This contradiction is eliminated if we assume that kola has not only active, but also in-

⟦folio 23⟧

ductive resistance too, which plays a primary role. In this case, the current in the ring will change with a phase change relative to the EMF, and for the instantaneous value of the Ampere force, another expression will be obtained:

$$I = \frac{B_{\text{BM}} S \omega}{Z} \sin(\omega t + \varphi),$$

And

$$F = B_{\text{r}} I l = \frac{B_{\text{GM}} B_{\text{BM}} S \omega l}{Z} \cos \omega t \times \sin(\omega t + \varphi) = \frac{B_{\text{GM}} B_{\text{BM}} S \omega l}{2 Z} \times (\sin(2 \omega t + \varphi) + \sin \varphi)$$

(here $Z$ is the total resistance of the ring, $\varphi$ is the phase shift between the current and the electromotive force). The average value of force over the period will be equal to

$$F_{\text{cp}} = \frac{B_{\text{GM}} B_{\text{BM}} S \omega l}{2 Z} \sin \varphi,$$

which is certainly not zero.

In our experiments, we used rings made of several layers of aluminum foil with a total thickness of about 1 mm. The inner radius of the rings was 15 mm, and the outer radius was 30 mm. It is estimated that at a frequency of 50 Hz the active resistance of such rings is milliohms, and the inductive resistance is ten milliohms. With such parameters, the Ampere force was of the order of $10^{-2}$ N, which is sufficient to hold a ring weighing several grams. This is what is observed experimentally.

2. Why is the ring in equilibrium in only one position, at one specific height? We received the answer to this question from experience.

The expression for the Ampere force includes the amplitude values ​​of the vertical and horizontal projections of the magnetic induction vector. It was necessary to find out how these values ​​change with height.

We worked on an installation, a photograph of which is presented on figure 2. A cylindrical core made of iron rods (length 200 mm, diameter 2 mm) is placed in a coil (its internal radius is 10 mm, radius 40 mm, height 70 mm) with a winding of enameled copper wire (diameter 1.2 mm). The coil was supplied with voltage (100-120 V) from a laboratory autotransformer. We were able to change the vertical and horizontal projections of the magnetic field in the immediate vicinity of the core at various distances from the coil. As a sensor, we used a coil (made of 300 turns of enameled copper wire with a diameter of 0.2 mm), in which the induced emf was induced. To measure this EMF, the coil was connected to the input of the oscilloscope.

It turned out that the vertical projection of the magnetic induction vector practically does not change with height, and the horizontal projection changes as shown in figure 3. Here, the height $H$ above the coil (measured in centimeters) is plotted along the abscissa axis (measured in centimeters), and the amplitude value $B_{\text{GM}}$ of the horizontal projection of the magnetic field (in milliseconds) is plotted along the ordinate axis. The resulting graph allows us to explain the significant single position of the ring installation.

⟦folio 24⟧

Let the stake have such a mass that to compensate for the force of gravity acting on the stake, a horizontal field projection of approximately 0.9 mT is necessary. On the graph, only one point A corresponds to this value; This means that the stake will hang at a height of 4 cm above the coil. This equilibrium position is stable, since if the ring is accidentally lowered, it will fall into a stronger magnetic field, the Ampere force will increase and raise the stake to its previous height.

What if a horizontal projection of approximately 0.75 mT is required to equilibrate the ring? This value corresponds to two points on the graph - C and D. However, in this case, there is only one stable equilibrium - at point C, that is, at a height of 6 cm above the coil. And at point D the equilibrium is unstable. Indeed, if the stake drops slightly below the height of 11.5 cm, the Ampere force will decrease and will not be able to balance the force of gravity; therefore, the stake will drop even lower (to point C).

Note that it is quite difficult to experimentally detect the position of an unstable equilibrium. This is due to the presence of various external influences that remove the stake from this position.

Can you hear the roar of a mammoth?
(For the beginning, see p. 20)

Leonid Martynov, therefore, who closely followed the development of physical science, depicted the correspondence of sound and light in this form:

It's almost a torment of immobility.
Rush somewhere at the speed of sound,
Knowing perfectly well that there is already somewhere
Someone
flying
With speed
Sveta!

But here is Mikhail Svetlov’s poem “Voices,” which suggests that over time, thanks to space flights, a person can hear the voices of previously living people and animals:

And it’s possible that beyond the horizon
He lives among the starry worlds -
Not recorded by tape recorder
Dead mammoths.
We - living together in the world -
Not all miracles have been solved.
And they will suffer from planet to planet
The strength of men's voices.
And perhaps on all horizons
Repeating again now
The incessant whisper of lovers
And thick Mayakovsky you.

Let not only the star split,
But understandable and eternally alive
With Tsiolkovsky's hoarse voice
The sound wave did not stop.
Since childhood I have not been strong in science;
Without entering into an argument with scientists,
I stretched out my aged hands
Into the ageless blue expanse.

The sky is full of heads
Those who lived and loved on Earth.

If Svetlov is right, then it is not difficult to calculate at what supersonic speed the cosmos must move away from the Earth so that, say, in ten years of flight it will catch up with the roar of mammoths that has gone into space. As you know, mammon disappeared about ten thousand years ago.

Dear reader, do some math and evaluate the difficulties of launching a rocket flying at the appropriate speed.

Unfortunately, the self-criticism of the pose in this poem is not without foundation. Remembering Puskin's story, let's not be strict with the posture, but still, what is Svetlov's main physical mistake? The answer to the present question is simple: you should not send it to our magazine. Think about how much more complicated life on Earth would be if Svetlov were right.
