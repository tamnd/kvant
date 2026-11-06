---
id: 1990-9-blioh-so-storonyi-vidnee-80e0a628
issue: kvant_1990_9
year: 1990
number: "9"
title: Seen better from the outside
authors:
  - Блиох П. В.
rubric: osnovnye-stati
page_first: 4
page_last: 9
page_labels: 2-7
lang: en
source: kvant_digital
extraction: vision
content_sha256: a479959b9883fcb2bb6dfe1cdc9d4f691e7338176aa60d0cae920916454b9eff
prompt_sha256: draft-1
translated_from: content/ru/1990/09/articles/03_blioh-so-storonyi-vidnee-80e0a628.md
source_content_sha256: 2724cd247e3149b15a737c3577b46993b61c46306ecdba4e376e9de1b1dbcffb
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 2⟧

---
running_head:
folio:
---

(Tale about RBO)

Doctor of Physical and Mathematical Sciences
P. VLIOH

Take a look at figure 1. How clearly the coastline, river and terrain details are visible in the photo. To the question: what were the lighting conditions when you took the photo? - the answer will almost certainly follow: it was a clear sunny day, the sun was from the top of the picture, since the mountain slopes facing that direction are illuminated, and the opposite slopes are immersed in shadow.

However, let's not rush. Please note that the shadows of the mountains at the top of the photo are shorter than those at the bottom. This means that for the objects captured in the upper part of the image, the sun was closer to the zenith than for the lower ones. But over an area of ​​several tens of kilometers (and judging by the picture the scale is approximately the same), the earth is illuminated by the sun at almost the same angle. Therefore, the answer regarding lighting contains some kind of contradiction.

This would not have happened if we had warned in advance that figure 1 shows not a photograph, but a “raduphotography” - a photograph taken not in light, but in radio rays (using radio waves). The sun, where it is located, has nothing to do with it at all, and the source of “lighting” is the radar installed on the plane. The plane flew somewhere beyond the upper boundary of the picture, and the angles of incidence of the radio waves were the rounder (greater) the higher (in the picture) on the

Fig. 1. Map of the area, remove from the aircraft.

⟦folio 3⟧

---
running_head:
folio:
---

a section of terrain is being walked. Therefore, the “radio shadow” of mountain slopes downwards is longer than at the top. What the weather conditions were when the “radio SIM” was made is completely irrelevant. It could have been cloudy, foggy, or overcast. This does not affect the quality of chimka. But one circumstance, seemingly completely unrelated to the four-style arrangement, is in fact extremely important. Take a look at figure 2 and notice where the radar is “looking”: the antenna is sending out radio waves at a 90° angle to the track. This, as we will be convinced to do, plays a decisive role. So decisive that such radars (they were invented relatively recently, in the 60s) were even given a special name - side-looking radars (SSRs).

Why is “radio photography” good only from the “side”? In order to answer this question, we must first understand what determines the parity of the image on the screen of a conventional stationary radar.

So, the path of the radar is on the ground. The clarity of the terrain image depends on the accuracy with which the coordinates of “targets” are determined - individual parts of the relief from which radio waves are reflected. The coordinates of the reflectors are determined as follows. The radar transmitter generates radio waves in short pulses and the antenna emits them in a specific direction. Radio pulses are reflected from any disturbance in the area and return back to the radar, to the receiver. Knowing the delay time - this is the name given to the time from the emission of a pulse by the transmitter to the reception of the reflected pulse, i.e., the time it takes for the pulse to travel to the “targets” and back, it is easy to calculate the distance to the place of reflection:

$$R = ct_{зап}/2,$$

(1)

where $c$ is the propagation speed of radio waves ($c = 3 \cdot 10^8$ m/s). In addition to the distance $R$, you also need to know the direction from which the reflected signal came. It is determined directly by the position of the antenna: where the antenna is directed, there is an object that reflected the radio waves (Fig. 3).

It would seem that by very accurately determining the angle $\theta$ and the distance $R$ to each of the reflectors, we will be able to construct a clear map of the area. So it is, but the trouble is that it is impossible to determine absolutely exactly $R$ and $\theta$. Indeed, the pulses have a certain duration, so the arrival of the reflected signal is recorded with a certain error, which we will denote by $\Delta t$. This error is approximately equal to the pulse duration. (Similar to

⟦folio 4⟧

---
running_head:
folio:
---

This inaccuracy also arises in ordinary watches due to the fact that their hands always have a certain width.) An error in determining the delay times by $\Delta t$ will entail, according to (1), an error in the distance to the “target”

$$\Delta R = c \cdot \Delta t / 2.$$ (2)

Something similar happens when determining direction. When they say that an antenna emits radio waves at an angle of $\theta$, they assume an existing somethingness. In fact, radiation always occurs at a certain angle, which we will denote as $\Delta \theta$. This “blurring” of the radio beam leads to the fact that the coordinate of the reflecting object located at a distance of $R$ from the emitter is “blurred” by $R \cdot \Delta \theta$. The shaded area on figure 3 in the form of a curved quadrilateral on the side $\Delta R$ and $R \cdot \Delta \theta$ precisely determines the clarity of the “radio symmetry”. The situation is as if we had started to draw a map of the area using a thick brush. It is clear that we were unable to depict details finer than the thickness of the brush.

Now that the principles of “blurring” a radio image have been established, let it become more clear to increase clarity: it is necessary, to the extent this arises, to reduce the pulse duration $\Delta t$ and the width of the radio beam $\Delta \theta$. However, along the way we repeat ourselves with very server-side physical limitations.

Let's start with the radio pulse (Fig. 4). It does not immediately reach its maximum amplitude when the gear is turned on, and does not immediately drop to zero after turning off. If you try to make the impulse very short, it simply will not have time to “grow” to the maximum. The duration of the pulse must be such that during its existence quite a lot of oscillations can occur. Let's denote their number by $N$. Then we can write $\Delta t = NT$, where $T$ is the period of oscillation, and $\Delta R = NcT / 2 = N\lambda / 2$, where $\lambda = cT$ is the wavelength. It can be seen that the shorter the wave, the smaller the error $\Delta R$. A numerical estimate can only be made by knowing what $N$ is equal to. Generally it is never less than several tens or even hundreds. Let us put $N = 200$ for definition. Then $\Delta R \approx 100\lambda$. If the radar operates at a wavelength of $\lambda = 10$ cm, the accuracy of determining the distance is 10 m, which is quite sufficient for most services.

The problem of narrowing the radio beam turns out to be much more complex. To understand what $\Delta \theta$ depends on, let us schematically consider the operation of the antenna when emitting a radio wave. figure 5, $a$ shows how radio waves propagate from individual elements 1, 2, 3, ... of the antenna opening in the direction of the antenna axis (axis $x$ to figure). It can be seen that the waves from all points of the antenna aperture have the same phase. Therefore, they all add up, creating a resulting wave along the $x$ axis.

Let's try to repeat the same reasoning, but considering not along the $x$ axis, but in the $x'$ direction at an angle $\Delta \theta$ to the antenna axis (Fig. 5, 6). At the antenna itself, the oscillations still remain in phase, but at some distances from it, for waves from different points, a phase difference will arise due to the difference in path lengths. It can be seen that at points $1'$ and $5$ the phases differ from each other by l, i.e., waves coming from the lower and upper parts of the antenna in the direction $x'$ will cancel each other. It is not difficult to determine how the angle $\Delta \theta$, at which complete mutual cancellation occurs, is related to the size of the antenna and the length of the emitted waves: $\sin \Delta \theta = \lambda / 2a$ (a is the antenna diameter), or, since at small angles $\sin \Delta \theta \approx \Delta \theta$,

⟦folio 5⟧

---
running_head:
folio:
---

Of course, our reasoning is not completely rigorous - after all, we considered the path difference only for edge waves in one section of the antenna. However, the dependences of $\Delta \theta$ on $\lambda$ and $a$ turned out to be absolutely correct, and it reveals a very important property of any wave process (not just radio waves): the concentration of radiation in a certain direction is more effective, the larger the size of the radiating system and the shorter the wavelength.

Let's try to estimate what kind of antenna is needed to obtain a radio image of an object located at a distance of $R = 100$ km with a resolution of $\rho = 10$ m at a wavelength of $\lambda = 10$ cm. In other words, we want to obtain an image in which the coordinates of the object are determined with an accuracy of 10 m, i.e. $\Delta R = R \cdot \Delta \theta = \rho$. From formula (3) we find: $a \approx \lambda / (2\Delta \theta)$, therefore,

$$a \approx \frac{\lambda R}{2\rho} = 0,5 \text{ км.}$$

(We also note that the given resolution also determines the maximum pulse length (see (2)): $\Delta t = 2\Delta R/c \approx 0,66 \cdot 10^{-7}$ s.))

So, to obtain a radio map with a resolution of $\sim 10$ m at a wavelength of $\lambda = 10$ cm, an antenna with a diameter of 0.5 km is required! Even if we reduce the requirements for clarity and consider blurred $\sim 100$ m acceptable, the dimensions of the antenna ($a \approx 50$ m) still turn out to be columnar, so that installing it is actually out of the question. But clear radio maps from airplanes and satellites are still obtained (see Fig. 1)! How did you manage to overcome such gray difficulties?

Now is the time to remember that we have so far considered the operation of a stationary radar, but the plane is moving all the time, or, what is the same, objects that reflect radio waves are moving relative to the radar. It turns out that when reflected from a moving wave, very important changes will occur with a radio wave, which were used to obtain clear “radio signals”.

So, we need to consider how radio waves are reflected from a moving object. First of all, let us recall the mathematical expression for sinusoidal oscillations:

$$E = A \sin (\omega t + \varphi).$$

Since we are talking about radar radiation, here the letter $E$ denotes the direction of the electric field, $A$ is the amplitude, $\omega$ is the circular frequency, $\varphi$ is the initial phase of oscillations.

A signal reflected from some obstacle at a distance $R$ from the radar travels there and back in time $t = 2R/c$. Therefore, for a mathematical description of the reflected signal, it is necessary to replace the time $t$ with $t - 2R/c$ in formula (4) (thus we take into account the recessing of the reflected signal relative to the original radiation). Signal amplitude

Fig. 5. Emission of radio waves by the radar antenna.

⟦folio 6⟧

---
running_head:
folio:
---

upon reflection, it naturally decreases (the degree of this change depends on the properties of the reflector). Therefore, for the reflected wave we can write
$$E_{\text{отр}} = A_{\text{отр}} \sin \left( \omega \left( t - 2R/c \right) + \varphi \right) = A_{\text{отр}} \sin \left( \omega t + \left( \varphi - 2R\omega/c \right) \right).$$
It can be seen that the phase of the reflected signal also changes in a strictly defined manner (φ is replaced by $\varphi - 2\omega R/c$). However, this conclusion is not suitable for an aircraft radar, since the distances from a flying aircraft to objects on the ground change all the time. With uniform movement along the radio beam $R_t = R_0 \pm vt$, where $R_0$ is the initial distance (at $t = 0$), and $v$ is the aircraft speed (the “—” sign corresponds to approaching the object, and “+” to moving away from it). Now the reflected signal is written like this:
$$E_{\text{отр}} = A_{\text{отр}} \sin \left( \omega \left( t - 2 \frac{R_0 \pm vt}{c} \right) + \varphi \right).$$
Let us simplify this formula by introducing the following notation:
$$\omega' = \omega \left( 1 \mp 2v/c \right), \varphi' = \varphi - 2R_0/c.$$
Then
$$E_{\text{отр}} = A_{\text{отр}} \sin \left( \omega' t + \varphi' \right).$$
Compare this expression with (4), we replace that, compared to the original signal, the amplitude, frequency and phase of the reflected signal have changed. Extremely important is the change in frequency, which can be very accurately recorded using special devices - frequency meters.
The change in the frequency of radiation when the reflector moves is called the Doppler effect (after the Austrian physicist Christin Doppler (1803-1853), who studied the influence of movement on wave processes). Note that if, instead of radar reflections, we consider the propagation of a wave in one direction, then with the relative movement of the receiver and transmitter at a speed of $v$, the frequency changes will be described by the expression $\omega' = \omega \left( 1 \mp v/c \right)$, which is usually used
is found in the textbook (“—” - removal, “+” - approximation). Replacing $v$ with $2v$ in our formula is explained by the fact that we are considering the reflection of the signal, and the length of the path there and back changes twice as fast.
As a result of our reasoning, let us formulate the main feature that distinguishes a moving aircraft radar from a ground-based one. Due to the effective Doppler, the frequencies of signals reflected from local objects will be different: reflections coming from in front of the aircraft have a higher frequency ($\omega' > \omega$, “+” sign in the formula for $\omega'$), and those coming from the ground have a lower frequency ($\omega' < \omega$, “—” sign in the formula for $\omega'$). As for reflections coming exactly from the side (at an angle $90^\circ$ to the aircraft heading), their frequency does not change and coincides with the original frequency ($\omega' = \omega$). Therefore, by changing the frequency of the reflected signal $\omega'$, one can find out in which direction the reflecting object is located. A simple mathematical calculation will show that due to the effective Doppler, the direction is reflected with very high accuracy. These capabilities are implemented in a side-view radar.
Take a look at figure 6, which shows planes and a reflective object at one point in time. The reflector at point $P$ is located at an angle $\Delta \theta$ to the axis $x$, which coincides with the antenna axis and is perpendicular to the aircraft heading. If the plane moves at speed $v$ upwards by figure, then the speed of the reflector $P$ relative to the plane is equal to $-v$ and at

⟦folio 7⟧

---
running_head:
folio:
---

pointing down. Changes in the distance between points $O$ and $P$ are determined by the projection of speed $-\vec{v}$ onto line $OP$. This projection (we will denote it $v_R$) is equal to $v_R \approx -v \sin \Delta \theta$, and at small angles $\Delta \theta$, for which $\sin \Delta \theta \approx \Delta \theta$, $v_R \approx -v \cdot \Delta \theta$. Due to this speed, the frequency of the reflected signal will increase: the corresponding change in frequency will be equal to

$$\Delta \omega = \omega' - \omega \approx \frac{2\omega v \cdot \Delta \theta}{c}.$$

Having measured $\Delta \omega$ using a frequency meter, we immediately determine $\Delta \theta$:

$$\Delta \theta \approx c \cdot \Delta \omega / (2\omega v).$$

The directional properties of the antenna itself do not play a role here at all, therefore, we will not need large antennas, as mentioned earlier. It would seem that there are no restrictions at all on the accuracy of determining the angle. You just need to very accurately change $\omega'$ and the corresponding frequency difference $\Delta \omega$. However, this is where the pitfalls are hidden. The fact is that changing the frequency of oscillations requires timing. Indeed, it is generally impossible to judge its frequency by the value of a signal at any one moment in time. It is necessary to monitor changes in the signal over at least one period, and even better over several periods. There is a universal law: the error in determining the frequency $\Delta \omega$ is inversely proportional to the time of change $\Delta t$ and is equal to $\Delta \omega \approx 2\pi/\Delta t$. Substituting this correspondence into formula (5), we obtain

$$\Delta \theta \approx 2\pi c / (2\omega v \cdot \Delta t).$$

Next, remember that $\omega = 2\pi f = 2\pi T$ ($f$ is the frequency, $T$ is the oscillation period), and $cT = \lambda$. Therefore, expression (5) for $\Delta \theta$ can be rewritten as follows:

$$\Delta \theta \approx \frac{\lambda}{2v \cdot \Delta t} = \frac{\lambda}{2L},$$

where $L = v \cdot \Delta t$ is the path traveled by the aircraft during the time of change in the frequency of the reflected signal. Compare formulas (3) and (6): they are very similar, only the antenna dimensions $a$ are equal to the aircraft path segment $L$. We can say that the DBR creates an effective antenna that coincides with the trajectories of the aircraft. Hence, another name for DBR, which is often used in the literature, is synthetic antenna radar.

Let's return to our original example. Previously, we came to the conclusion that to obtain a radio map at a wave of $\lambda = 10$ cm with an error not exceeding 10 m, a fixed antenna of $a \approx 500$ m in size is required. However, for an aircraft flying at a speed of $v \approx 300$ m/s, the corresponding accuracy will be achieved if $\Delta t \approx 1,7$ s ($L = v \cdot \Delta t \approx 500$) is spent on signal processing m). This is not a very long time, and you can get a “radio SIM” almost immediately when the plane passes. It is in this way that the clear “radio photograph” of which we presented on figure 1 was made.

In conclusion, a little fantasy about the possibility of using DBR for radar detection of cosmic bodies. In this case, there is no need to install a radar on an aircraft or satellite. After all, the variable radar moves along with the Earth, participating both in the rotation of the Earth around its axis (for this movement, the characteristic speeds in the middle spins are ~300 m/s), and in the rotation of the Earth around the Colnitsa (here the speed is ~30 km/s). Moreover, for very distant objects it is necessary to take into account the movement of the Colon itself, which occurs at an even greater speed.

All these complex movements make it possible to synthesize antennas of enormous size and very accurately determine the angles of arrival of radio signals. Perhaps the most interesting thing about the described “fantasies” is that they have already been realized and can be effectively used in space radar and radio astronomy to the fullest. Moreover, in fact, the first RBO started working during the Lunyi radar in 1960. RBO aircraft appeared a little later, and they began to be used for radio mapping of terrain only in the 70s.
