---
id: 1974-6-gershteyn-signalyi-spektryi-961a2228
issue: kvant_1974_6
year: 1974
number: "6"
title: Signals. Spectra
authors:
  - Герштейн Г. М.
rubric: osnovnye-stati
page_first: 4
page_last: 10
page_labels: 2-8
tag: Q6VY
lang: en
source: kvant_digital
extraction: vision
content_sha256: a13924d5281738d507d4098dfdadb5d142339d22ab96b88c2cdbf4d9a76fc346
prompt_sha256: draft-1
translated_from: content/ru/1974/06/articles/02_gershteyn-signalyi-spektryi-961a2228.md
source_content_sha256: 419faa0173615e23c0b0e29f4a9b4e7b7dd9e743ce57bfc1735b61b79dd1977b
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 2⟧

In modern life, we are literally overwhelmed by the flow of various information, the volume of which is steadily increasing. This information is transmitted using radio, television, telephone and telephony in the form of signals. A very important characteristic of any signals is their spectrum, limited by the shape and duration of the signals. Spectral representations make it possible to compare physical processes of different nature and study active, electromagnetic, optical and other phenomena from a single point of view. Therefore, it is useful to have an understanding of signals and their spectra, to know the relationship between spectra and other characteristics of signals. This will be discussed in this article.

About the signal

Initially, we receive information about the rich and diverse world around us through our eyes and ears. We admire the delightful spectacle of sunrise or sunset on the sea or at the edge of a forest, rainbows and radiance, attempts by famous masters of painting, slender buildings, various machines, etc. Looking at the text and formulas, we perceive the thoughts of other people expressed by it. The same thing happens when we serve speech or music. In all these cases, a person perceives messages that play the role of information carriers. From this point of view, sounds and images are examples of messages.

To transmit sound or image over long distances, the message is converted into a corresponding electrical signal, that is, in the electrical process $u(t)$, characterized by a certain dependence of the electrical quantity $u$ on time $t$, or, as they say, the message is encoded. Sounds are relatively easily encoded by a microphone device. The microphone is affected by other air vibrations, the role of the message is played by the sound pressure $p$ on the membrane of the microphone, which changes in time according to the law $p(t)$. In this case, for example, in a carbon microphone, the resistance of the microphone and the current in its circuit change accordingly, as a result of which the voltage $u(t)$ at the output of the microphone device changes over time according to the same law as the sound pressure $p(t)$.

It is much more difficult to encode an image. First, a special photoelectric device converts the optical image into an electrical one, in which the directional distribution corresponds to the intensity of different parts of the image. then, with the help of an electron beam running around the electric image, a sequential

⟦folio 3⟧

further transformation of this image into an electrical signal $u(t)$, characterizing a certain dependence of $u$ on time $t$. Depending on $u(t)$, information about this image is pyromorphized.

When studying an electrical signal, it is usually not clear which electrical quantity is meant by $u$—voltage, current, or charge. What matters is not what changes, but how this value changes over time. You can abstract from the physical nature of this quantity and be interested in the nature of the mathematical dependence $u(t)$, that is, the function of time $t$, for example, whether it is continuous or pulsed, sinusoidal or non-sinusoidal, etc. In the final case, it is important for us that, regardless of the physical nature of the message, the signal encoding it is transmitted in the form of a certain function of time.

Temporal and spectral representations of the signal

When studying an event, we are usually interested in where and when it will happen, what movements in space and changes in time have taken place. Therefore, we are accustomed to considering the largeness of a quantity as a function of spatial coordinates and time.

The signal is another matter. The value of the spatial coordinates of the signal source does not make much sense, since on an earthly scale signals transmitted by electromagnetic waves propagate almost instantly (recall that in air the speed of an electromagnetic wave is $\approx 3 \cdot 10^8$ m/s). For example, when a play is broadcast from the Moscow Theater, radio listeners in Vladivostok will hear the sound spoken on stage, even before the Muscovites sitting in the back rows of the stalls, since electromagnetic waves travel approximately a million times faster than sound waves.

But it is very important how the signal changes over time, since it is the dependence $u(t)$ that contains the transmitted information. It depends, you can write similar ones or present them in the form of a graph $u(t)$. But the signal can be characterized differently, from the point of view of its spectral state, and also represented graphically in an appropriate way. What is the signal spectrum? Let's try to figure this out.

We will consider mainly such signals that are periodic, that is, the function $u(t)$ satisfies accordingly.

$$u(t + nT) = u(t),$$

where $T$ is a constant called period, $n$ is any number. A periodic process can also be characterized by frequency $v = \frac{1}{T}$. Theoretically, it is assumed that such periodicity lasts forever and has no beginning or end in time. In practice, periodic processes also include processes whose duration is much longer than the period.

figure 1 shows graphs of three different periodic processes. It is easy to notice that they have the same frequency, but different vibration shapes. Later you will see that these vibrations, which are different in shape, have different spectral compositions.

Let's consider this experience. Let there be many different resonant circuits tuned to frequencies $v_0, 2v_0, 3v_0$, etc., and electrical signals corresponding to the indicated processes simultaneously affect these circuits. It turns out that the first signal $u_1(t)$ excites oscillations in three circuits tuned to frequencies $v_0, 2v_0$ and $3v_0$; significantly more circuits respond to the second signal $u_2(t)$, and when exposed to the last signal $u_3(t)$

⟦folio 4⟧

oscillations occur only in one circuit with a natural frequency $v_0$. Obviously, for such oscillatory circuits the periodic process $u_3(t)$ is the simplest, since it causes excitation at only one frequency equal to $v_0$. This process is certainly familiar to you; it represents the so-called sinusidal, or harmonic, oscillation, described by the correspondence

$$u(t) = A \sin(2\pi v_0 t + \varphi) = A \sin(\omega_0 t + \varphi),$$

Fig. 1.

oscillations occur only in one circuit with a natural frequency $v_0$. Obviously, for such oscillatory circuits the periodic process $u_3(t)$ is the simplest, since it causes excitation at only one frequency equal to $v_0$. This process is certainly familiar to you; it represents the so-called sinusidal, or harmonic, oscillation, described by the correspondence

$$u(t) = A_1 \sin(\omega_0 t + \varphi_1) + A_2 \sin(2\omega_0 t + \varphi_2) + A_3 \sin(3\omega_0 t + \varphi_3) + \dots + A_h \sin(k\omega_0 t + \varphi_h) + \dots$$

or, more briefly,

$$u(t) = \sum_{k=1}^{\infty} A_k \sin(k\omega_0 t + \varphi_k),$$

where $k$ is the number of the harmonic, which determines its frequency, $A_k$ is the amplitude of the harmonic, $\varphi_k$ is the initial phase of the harmonic, $\omega_0$ is the circular frequency of the process under study.

Thus, a signal represented as a sum of sine waves can be conveniently and simply characterized by a combination of the values ​​$A_k$ and $\varphi_k$. The set of quantities $A_k$ is called the amplitude spectrum. This spectrum is clearly represented graphically, plotting the values ​​$A_k$ along the ordinat axis and $v$ along the abscissa axis and depicted

⟦folio 5⟧

Fig. 3.

compressing the amplitudes of individual vertical harmonics in segments of appropriate length. Such a spectrum is line and harmonic. The latter means that there are simple multiple correspondences between harmonic frequencies. If the process is not periodic, it can also be represented by a sum of sinusoids, but the spectrum of such a process will not be harmonic. The set of quantities $\varphi_h$ is called the phase spectrum. When analyzing signals, in most cases it is enough to know only the amplitude spectra. Therefore, for the sake of multiplicity, the amplitude spectra are called simple spectra, which is what we will do in the future.

As a rule, as the number of harmonics increases, their amplitudes decrease, and, starting from a certain number, the amplitudes of subsequent harmonics become so small that they can be neglected. Therefore, practical spectra have a limited number of spectral lines. However, one of the characteristics of the spectrum is its width. The spectrum width is the interval on the frequency scale in which such a spectrum is located.

figure 2 shows the spectra of functions $u_1(t), u_2(t)$ and $u_3(t)$, obtained, for example, using the above-mentioned set of resonant circuits. They clearly illustrate the relationship between temporal and spectral representations of a signal. We see that the more accurately a function changes over time, the richer and wider its spectrum. It's natural. In order to obtain sharp changes in the results of functions by adding continuous and smoothly varying sinusoids, it is necessary to add a large number of sinusoids with different frequencies, amplitudes and phases. To reproduce a continuous process close to a sinusoid, a small number of such sinusoids is sufficient. As an example, figure 3 shows the graphical addition of three sinusoids with frequencies and amplitudes corresponding to the spectrum of Figure 2, $a$, and initial phases equal to zero. The resulting curve (shown in blue) is the same shape as the curve at figure 1, $a$.

Sound spectra

Audio messages are usually divided into musical sounds and noises.

Musical sound is a periodic changing process, for example, such as on figure 4, $a$. In particular, if this process is harmonic, we speak of musical tone. Using Fourier, musical sound can be considered as a collection of fundamental musical tones and several high harmonics - overtones. In the spectrum of the corresponding signal, the fundamental tone has the most amplitude; with increasing number of harmonics, their amplitude is noticeable

⟦folio 6⟧

The name of the instrument is where this note sounds. figure 5 shows graphs and spectra of the sound role and clarinet for the same note.

Discontinuous sounds such as the beat of a drum or the knocking of a bet are noises. Noise signals are distinguished by their non-periodicity and complex time dependence (for example, such as on figure 4, 6).

One such spectrum, the compressor noise spectrum, is shown in figure 6. It has many different frequency components. The noise spectrum is significantly wider and richer than the spectrum of musical tones. This can be easily verified by performing, for example, a simple experiment with chambertoms having different natural frequencies of vibration. Only one of the chamberts responds to the long sound of a pure musical tone. If you hit the drum sharply close, many chamberts begin to play. That is, a pure tone can be represented by one frequency, and drum beats can be represented by a large number of frequencies.

Fig. 4.

falls, so that the practical spectrum of a musical ton has relatively few harmonics. The role of these harmonics in the emotional perception of music is very great. They determine the timbre of musical sounds. Playing the same note on different instruments, we get sounds with different numbers of harmonics and different correspondences between their amplitudes. The correspondence and spectra of these sounds will be different, thanks to which ours already distinguishes on which

Fig. 5.

Fig. 6.

⟦folio 7⟧

The qualitative difference between different noises is expressed in the fact that the spectrum of one noise may have more integrated spectral components in the low-frequency region, while another noise may have more integrated spectral components at higher frequencies, that is, in different proportions between the spectral components.

What color is the noise?

Spectral representations make it possible to create a unified and visual language for describing processes of various physical natures, sometimes using unexpected associations and analogies.

For example, specialists sometimes use the term “white noise”. From the point of view of philologists, this is nonsense, and they can show themselves that noise has no color, we do not see it, but hear it. However, for a physicist this is a completely understandable, fairly accurate and capacious definition, using the analogy between sound and light.

It is known that the white color error is the result of exposure of the eye to a whole range of light rays, from red to philological. White light has a continuous spectrum, in which all frequencies of the visible part of the electromagnetic wave scale are represented (from 3.8·10¹⁴ to 7.5·10¹⁴ etz).

Although there is a definition of the distribution of energy by frequency and the maximum energy emitted by a white light source falls on a specific part of the visible spectrum (in particular, the maximum energy of solar radiation is in the yellow-green part), the radiation in other parts of the visible spectrum is also intense, that is, in white light the energy of red, green, blue and other colors is white or less evenly distributed over the entire range of visible light waves.

Similarly, “white noise” is noise in which all sound frequencies are present in the continuous spectrum, and the differences in energy between different spectral components are not very strong.

Spectra of pulse signals

In modern technology, for example, in telephones, radar, and television, signals in the form of periodic repeating pulses of a straight-line shape (Fig. 7 and 8) are often used. As can be seen from these figure, such signals have a rich spectrum containing many spectral lines grouped into peculiar “petals”, and the frequencies corresponding to the “nodes” of these petals are equal to n/τ, where n is the number of the petal. Theoretically, such spectra have an infinite extent in frequency, but since after the third lobe the amplitude of the harmonics becomes negligible, practical ones can be limited.

⟦folio 8⟧

is covered with the first crown petals. The width of such a limited spectrum Δv is related to the pulse duration τ of a simple dependence:

$$\Delta v = \frac{3}{\tau},$$

that is, the width of the spectrum of a direct limited pulse is inversely proportional to its duration.

This correspondence is of great practical importance. It shows that the shorter the pulse duration, that is, the less significant the communication line, the wider the spectrum of such a signal and the wider the frequency band required for its fairly correct reproduction.

For example, when transmitting telegraph signals, the average duration of pulses (dots and types) is approximately 0.1 s. This corresponds to the spectrum width Δv = 30 2ts. If, in order to occupy a communication line, a telegraph signal is transmitted 100 times faster (τ = 0.001 s), Δv increases to 3000 2ts. Therefore, the faster the signal is transmitted, the wider its spectrum.

The different nature of the message requires the rapid transmission of the corresponding signal. This is the case, in particular, in television. Since the visual noise of the image is retained in our eyes for only about 1/25 of a second, during this time it is necessary to transmit one frame, that is, in the form of sequential pulses, transmit information about the brightness of approximately 500,000 image elements (by modern standards). In this case, each pulse lasts less than a millionth of a second, while the spectrum of the television signal occupies a frequency band tens of millions of hertz wide, which causes special difficulties in its transmission.

Using the example of direct pulses, we encountered a very large pattern that is also valid for other types of pulses. This pattern can be expressed mathematically by rewriting the above correspondence as τ·Δv = const.

The physical meaning of this correspondence is that it is impossible to simultaneously concentrate such a signal in time and in frequency. If, for example, in an effort to scale a signal in time, that is, to transmit information faster, we reduce the pulse duration τ, while the frequency band increases and the spectrum of the signal expands.

It also follows from the above formula that the spectrum width Δv of direct pulses is determined only by their duration τ and does not depend on the pulse repetition frequency v = 1/T. This is important practical, as it makes it possible to easily determine the minimum value of τ at which the frequency band occupied by a given signal does not exceed that permissible for a given system for transmitting and receiving signal pulses.

However, with a change in frequency v, the number of spectral lines in each lobe changes, that is, their density. Thus, with increasing interval between pulses, v decreases, and the number of these lines in the spectrum lobes increases (Fig. 7 and 8). Obviously, in the limiting case of transition from periodic repeated pulses to a single pulse (T → ∞ and v → 0), the spectrum should become continuous, which is indeed confirmed by experiment.

Of great practical interest is the spectrum of pulses that arise when switches and contacts of various electrical circuits are turned on, when the current in the circuit increases sharply from zero to a certain value (Fig. 9, a). Such a signal has a continuous spectrum, shown in figure 9, b, where the continuously changing frequency v is plotted along the horizontal axis. From
