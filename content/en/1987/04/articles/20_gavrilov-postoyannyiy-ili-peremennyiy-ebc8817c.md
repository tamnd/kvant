---
id: 1987-4-gavrilov-postoyannyiy-ili-peremennyiy-ebc8817c
issue: kvant_1987_4
year: 1987
number: "4"
title: Constant or variable?
authors:
  - Гаврилов С. Л.
rubric: laboratoriya-kvanta
rubric_sub: Лаборатория «Кванта»
page_first: 47
page_last: 50
page_labels: 45, 46, 48
tag: RVBP
lang: en
source: kvant_digital
extraction: vision
content_sha256: 8e1fe2c22f56754f9e90f1b135695be15c386eca47cacb9a24afc36a99a53be2
prompt_sha256: draft-1
translated_from: content/ru/1987/04/articles/20_gavrilov-postoyannyiy-ili-peremennyiy-ebc8817c.md
source_content_sha256: e592ef9409e16f46c07ac188d79e56124f6963513ae0e2596abf1017a2b83694
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 45⟧

Constant or variable?

S. L. GAVRILOV

Today we are all accustomed to the fact that direct current and alternating current coexist peacefully in technology and everyday life, complementing and “helping out” each other. And this is years ago, in the eighties of centuries, in America, for example, a desperate struggle unfolded between supporters of one and the other current.

The previous history of electricity - from the invention of the first galvanic cell by A. Volta in 1800 to T. Edison's development of the goals of the electrical system in 1880 - was the history of the development of direct current. By this time, in particular, Edison had won a victory over the supporters of gas lighting, who did everything possible to prevent the introduction of electric lighting.

In 1886, after the creation of the first operational transformers, direct current had a strong competitor - alternating current. Its direction with the help of a transformer can be transformed within a very wide range, which is especially important when transmitting electricity through wires over long distances. Generating alternating current is also easier and cheaper than direct current.

Nevertheless, supporters of direct current fought with all means. If any accident occurred to any of the personnel servicing the alternating current systems, articles appeared in the newspapers with loud headlines: “Murder by Electrical Wire,” “New Body on Wires,” etc. When a commission appointed by the US counterpress to select a method of execution more “humane” than hanging recommended the use of alternating current, this was the subsequent one argument in the fight against alternating current.

But the application of alternating current in many areas was very obvious that Edison, being primarily an inventor and engineer, stopped fighting. And over time, the General Electric Company, which emerged from the Edinov company, became one of the main companies producing transformers.

Let's figure out what kind of alternating current were used that helped him win? But first, a little about him.

In an alternating current circuit, its direction and the numerical value of the variables change. These changes can be described by the formula

$$i = I_m \cos \omega t = I_m \cos 2\pi vt = I_m \cos(2\pi t/T),$$

⟦folio 46⟧

Fig. 1. Graph of changes in current and voltage in an alternating current circuit.

where $i$ is the instantaneous value of the alternating current, $I_m$ is its amplitude, $v$ is the frequency, $\omega = 2\pi v$ is the cyclic frequency, $T$ is the period of change of the current. A similar expression can be written for voltage:

$$u = U_m \cos \omega t = U_m \cos 2\pi v t = U_m \cos (2\pi t/T).$$

The graphs of these functions are presented on figure 1, but they can be enlarged directly on the screen of a school oscilloscope. To do this, you need to connect a piece of wire about a meter long to the oscilloscope input (Fig. 2). The wire will act as an antenna, and a signal induced from the electrical wiring will appear on it. By measuring the period of the sine wave with an oscilloscope, you can verify that the frequency of the induced signal is $v = 50$ Hz, which corresponds to the frequency of the alternating current in the electrical network.

The alternator can be assisted by rotating a frame with a wire winding between the strips of a permanent magnet, as shown in figure 3. Another way to do this is to rotate a permanent magnet inside a stationary winding. By the way, this is the operating principle of most industrial generators, but they use an electromagnet together with a built-in magnet.

The conveniences of alternating current in electrical engineering are very great. With the help of such a current, it is possible to create a so-called rotating magnetic field, which will drive the shafts of the electric motor. To transmit electricity over long distances with minimal losses, the voltage at the beginning of the transmission line needs to be increased, and at the end (in front of the consumer) - lowered. In the case of alternating current, this can be easily done using step-up and step-down transformers (Fig. 4).

Radio engineering and electronics also usually deal with alternating current signals of various frequencies and voltages. Thus, a radio transmitter converts high-frequency current into radio waves, which in the radio receiver are again converted into high-frequency alternating current. The microphone converts sound into low-frequency alternating current that matches the frequency of the sound. Conversely, a loudspeaker converts audio frequency current into sound. If you assemble the circuit shown in figure 5, you can observe the operation of the microphone using an oscilloscope. For a successful signal, you can use any ready-made audio amplifier (which, of course, is in the school physics room).

The given examples, although not exhaustive, clearly illustrate the diverse applications of alternating current. Nevertheless, there is also a lot to do for the constructed current. Direct current, for example, powers electronic circuits, electric motors (trams and electric trains are driven by direct current), aircraft on-board systems, automatic transmission, etc. Further

Fig. 2. Alternating current on the oscilloscope screen.
Fig. 3. Model of alternator.

⟦folio 48⟧

Fig. 7. Balanced DC amplifier: $T_1, T_2 - M\Pi 41; R_3=5,1$ kOhm; $R_{\kappa1}=R_{\kappa2}=3,3$ kOhm.

Based on such a circuit, it is possible to build a multistage amplifier with a sufficiently large number. figure 8 shows a diagram of a two-stage DC amplifier, which can be assembled and tested in operation. For example, it can be used to measure temperature using a thermocouple.

The operating principle of a thermocouple is based on the following phenomenon. If two junctions of different metals included in an electrical circuit are at different temperatures, then a current will arise in the circuit. It is caused by the so-called thermo-emf, which appears in places of spars. In other words, the soldering of two different metals can convert thermal energy into electrical energy. Thermocouples are typically used to measure very high or very low temperatures.

The voltage generated by a thermocouple is very small, usually no more than a few tens of microvolts per degree. Therefore, a thermocouple is often connected to a DC amplifier, and a successful signal is sent to a measuring device or temperature control device. Good thermocouples are made from compounds of alloys chromel (an alloy of chromium with nickel) and copel (an alloy of copper with nickel and manganese) or alumel (an alloy of aluminum, nickel, manganese and silicon) and copel. But you can make a thermocouple from more affordable materials, such as iron and aluminum.

The metals at the point of contact must be securely folded. It can be done like this. The graphite rod from a flashlight battery must be carefully sharpened and connected to one terminal of a laboratory autotransformer. Wires made of different metals must be folded at the ends and twisted, and the free ends of the wires must be connected to the second terminal of the autotransformer. If you now bring the graphite rod closer to the twisted ends of the wires, then at sufficient voltage (but selected experimentally) a voltaic arc will arise and the wires will be welded. In order for the junction to turn out clean, without scale, it is better to moisten the ends of the wires with alcohol or triple cologne (taking precautions so that the alcohol does not flare up during welding! It is obvious that the places of graphite and wires that the brothers touch with their hands when welding must be securely sealed, since the direction may require quite a lot - up to 100 volts.

The manufactured thermocouple will be connected to the input of the DC amplifier, and a millivoltmeter can be connected to its output. In order to program the device, the thermocouple can be placed first in a vessel with boiling water and then in a vessel with ice. The voltmeter readings will correspond to 100 °C and 0 °C.

There are also DC amplifiers using AC amplifiers. In them, the DC signal is converted into an AC signal, compressed, and then converted back into DC.

From all that has been said, we can conclude that the “war between direct current and alternating current” that began a hundred years ago ended not only in peace, but also in a very dark and fruitful cooperation.
