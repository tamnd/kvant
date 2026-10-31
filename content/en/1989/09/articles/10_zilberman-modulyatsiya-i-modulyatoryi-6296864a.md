---
id: 1989-9-zilberman-modulyatsiya-i-modulyatoryi-6296864a
issue: kvant_1989_9
year: 1989
number: "9"
title: Modulation and modulators
authors:
  - Зильберман А. Р.
rubric: shkola-v-kvante
page_first: 50
page_last: 52
page_labels: 48-50
tag: 0A2L
lang: en
source: kvant_digital
extraction: vision
content_sha256: f492b90dca8c417f63fa8b43936c8bc49827d458253fa9a98f132732442a27ca
prompt_sha256: draft-1
translated_from: content/ru/1989/09/articles/10_zilberman-modulyatsiya-i-modulyatoryi-6296864a.md
source_content_sha256: 7061002be219f9c4c5ab206c0508f7b630c5ed5be0f77fa9e80684a9708a4b12
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 48⟧

The second core flies uniformly and linearly at a speed $\vec{v}_{21} = \vec{v}_2 - \vec{v}_1$. Having determined the graphical directions of this speed, we can easily find at what distance from the baron the second core will fly (you just need to make sure that before this moment none of the cores will fall to the ground).

Of course, you can check all the calculations without using the Monchhausen report system, but they will be more cumbersome. The analyzed “Baron Monchhausen principle”—the relative motion of two freely flying bodies is uniform—is found in many problems. Try, for example, to explain why during a fireworks display, after a shell explodes, a luminous ball is formed, increasing in size and falling.

It is interesting to remember that one of the dramatic episodes in the history of human thought concerned nothing more than... the choice of the “correct” reporting system. The execution of the Jordans by Bruno, the struggle and renunciation of Galileo...
It was very difficult for mankind to agree that the Earth is not the center of the universe, but just one of the planets revolving around the Sun. What should humanity do when moving from a geocentric (connected to the Earth) to a geocentric (connected to the Sun) system? In the light of our conversation, one of the advantages of the transition is that in the solar system of the report, the movement of the planets looks much simpler. Obviously, thanks to this too, Kepler subsequently managed to discover the laws of planetary motion, which, in turn, helped Newoton discover the law of universal gravitation.

What is the main advantage of solar power? O. before the earthly one? A little later you will find out that from the point of view of dynamics, not everything is s. O. are equal - there are so-called inertial s. o., in which the laws of mechanics take on a particularly simple form. So, sunny s. o., unlike the earth's, can be considered inertial. But from a kinematics point of view, everything is s. O. are equal, you can use any, including those moving with acceleration and even rotating. However, the rotating s. O. have some non-training features that require separate careful maintenance, which is not provided for in the framework of this note.

A. I. Cherpotsan

Modulation and modulators

Radio waves are usually used to transmit signals over long distances. They are easy to emit and receive, any information can be “superimposed” on them, the choice of wavelength ranges is very wide - from hundreds and thousands of meters to millimeters (and for special situations - even shorter). All this allows us to solve a variety of problems - from sending messages to the whole world to running local programs that do not interfere with neighboring areas. In recent years, communication satellites have been widely used - but this is a topic for another conversation.

Let's take a closer look at the process of radio transmission and radio reception. To do this, let's look at what transformations the sound signal undergoes on the way from the performer to the radio operator.

⟦folio 49⟧

It all starts with the conversion of sound (mechanical) vibrations - those sounds that we produce and hear - into electrical signals. This is done using a microphone. In the most common microphone in practice - the range - sound waves cause vibrations of the membrane, to which a coil is attached, placed in the field of a permanent magnet. When the coil moves, an induced emf arises in it - the electrical signal that we need. Typically, the effective voltage from a microphone is very small - a fraction of a millivolt, and it is amplified several thousand times using an electronic circuit. Once successful, the signal is suitable for transmission over wires, but for radio transmission it must continue to be converted. (For telephone communications, a successful signal is too expensive and difficult; they use microphones of a different type - carbon, which make it possible to do without amplifiers, but the quality of sound reduction is below any criticism - each of you could probably see this for yourself.)

So, the electrical signal has been received. Let's consider a simple case - a cameratron sounds in front of the microphone and the volume of the sound does not change over time; then the electrical signal is a harmonic oscillation of low (sound) frequency Ω (Fig. 1).

Now let's talk about the “carrier” of the signal - about high-frequency oscillations ω. They are provided by a generator of undamped oscillations (Fig. 2). The carrier frequency ω is selected many times higher than the audio frequency Ω of the transmitted signal. For example, the cameratron promised to give Ω=2770 s⁻¹, when transmitting on medium waves ω≈6·10⁶ s⁻¹.

To transmit an electrical signal of audio frequency, it must be “embedded” in some parameter of high-frequency oscillations - amplitude, frequency or phase (or a combination thereof). In other words, the selected parameter must be changed (modulated) in accordance with the transmitted signal. The main requirement in this case is that the conversion be inverse and that upon reception the transmitted signal can be easily restored.

Obviously accept amplitude, frequency or phase (more complex combined types are possible) modulation (Fig. 3). The easiest way is to use amplitude. In this case, the signal transmitted to the “ether” - it is called amplitude-modulated - is obtained, for example, by changing the supply voltage of the continuous oscillation generator in time with the audio frequency signal. But you can get by with very simple means - include in the wire going from the generator of continuous oscillations to the transmitting

Fig. 1. Receiving an electrical signal of audio frequency. This signal has the form u(t)=U₀ cos Ωt, 2de U₀ is the amplitude, Ω is the oscillation frequency (the initial phase in this case is not important - think about why - and it is taken equal to zero).

Fig. 2. Circuit for obtaining carrier frequency oscillations. Oscillations occur according to the law u(t)=V₀ cos (ωt+φ₀), 2de V₀ is the amplitude, ω is the frequency, φ₀ is the initial phase of the oscillations (here we can no longer take φ₀=0, although this is not important for radio transmission).

⟦folio 50⟧

antenna, general carbon microphone (Fig. 4). If we speak in front of it, the resistance of the microphone will change, the track in the antenna will change in time with it, and we will get the amplitude model we need. At the dawn of radio communications, this is exactly what radio amateurs did, who wanted to move from working in Morse code to speech transmission. Of course, this method is only suitable for low-power devices and the quality of such transmission will not be very good.

The inverse conversion of amplitude-modulated signals on the application side is carried out using an amplitude detector - a simple circuit containing a semiconductor diode (Fig. 5). Actually, it is the simplicity of such a detector that is the main advantage of amplitude modeling. This type of modeling is used for radio broadcasting in the long, medium and short wave bands. It is also used to transmit television signals, but only together with other types of modeling. Let's talk a little about them.

Frequency modeling has become widespread. With this method of radio transmission, the low-frequency signal is “embedded” in the value of the instantaneous transmission frequency (instantaneous - because it no longer remains constant, but changes in time with the low-frequency signal). Such modulation is also easy to carry out “at home” - for this it is convenient to use a microphone of the so-called condenser type (Fig. 6). This is a very simple (in concept, but not for practical production!) device. It consists of the thinnest metallization membrane, which is one of the plates of a flat capacitor, and the outermost plate - the second plate. The membrane vibrates in time with the air vibrations, and the capacitance of the capacitor changes accordingly - that’s all. The membrane can be made very light, so such a microphone can provide excellent quality of conversion of an audio signal into an electrical one. For our purpose, a condenser microphone will be connected in parallel with the contra condenser of the continuous-wave generator, and changing the em-bone of the microphone gives the necessary modulation effect. This way you can make a simple and high-quality radio microphone operating in the VHF range, and its signals can be received by a regular VHF FM receiver (“VHF” - ultrashort waves, “FM” - frequency modeling).

The most difficult thing with this modulation method is demodulation (detection). It can be done, for example, like this: it uses an oscillator circuit tuned slightly - to a few tens of k-
