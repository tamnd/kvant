---
id: 1980-11-ashkinazi-mgd-generator-018d2aad
issue: kvant_1980_11
year: 1980
number: "11"
title: MHD generator
authors:
  - Ашкинази Л. А.
rubric: osnovnye-stati
page_first: 4
page_last: 8
page_labels: 2-6
tag: UW38
lang: en
source: kvant_digital
extraction: vision
content_sha256: 2dbdfc06e5b7d6d95523a0958234ef090f4f479869c12b189df919e28aba6b33
prompt_sha256: draft-1
translated_from: content/ru/1980/11/articles/02_ashkinazi-mgd-generator-018d2aad.md
source_content_sha256: 700e90f118fb421eb3a5ddb95912fde261074c0ccaa5393da3d4b0cc992d8ae0
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 2⟧

L. Ashkinazi

MHD generator

Human society cannot live without energy. So far, the main source of energy for humans is natural fuel: coal, oil, gas. But the supply of this fuel does not last forever. True, we know other sources of energy - the Sun and Atom. In the future, they will become the main sources, but their development takes time, and in the meantime, natural fuel reserves are decreasing. How to effectively use these reserves? A natural proposal is to increase the efficiency of devices that convert the energy of natural fuels into electrical energy. An important application of high efficiency energy conversion is the reduction of environmental pollution.

As is known, the efficiency of a heat engine increases with increasing maximum and decreasing minimum temperatures of the working fluid. But the minimum temperature is limited to blue - this is the ambient temperature. What is the maximum temperature limited by? The strength of turbine blades - or the strength of all metals decreases with increasing temperature, and high-speed parts bear greater loads. The turbine blades of thermal power plants work “to the limit,” and one of the main goals is to obtain materials that have high strength at high temperatures. The best thermal power plants have an efficiency of 35-40%.

If we want to increase efficiency by increasing the temperature of the working fluid, we must look for a way to convert the energy of hot gas into electrical energy that does not require high strength materials.

One day a man stood at a place across the Thames and tried to change the potential difference between two

⟦folio 3⟧

Electrodes immersed in water. However, the potential difference was equal to zero for half an hour, and the huge Michael Faraday (and it was he) went home. Faraday's failure was explained only by the low sensitivity of the instruments he used. But the potential difference existed, and it was changed 19 years later by the physicist Wollaston. And then William Thomson (Lord Kelvin) proposed using this effect to convert the energy of the movement of sea water during tides into electrical energy.

Thus, the ideal foundations were laid for a new method of energy conversion, which makes it possible to use natural fuel with greater efficiency than in traditional thermal power plants. This method is called magnetohydridydynamic.

MHD generator

Let's imagine a pipe made of electrically insulating material and having conductive electrodes on the inside of two opposite walls. The pipe is placed in a magnetic field. A stream of hot gas moves inside the pipe. This is the basic diagram of a magnetohydridydynamic generator - MHD generator. (The movement of a hot gas stream is in many respects similar to the movement of a liquid. Hence the name of both the method itself and the generator.) In an MHD generator, the mechanical energy of the moving hot gas is converted into electrical energy. Let's see how it's done.

To determine this, let the gas in the MHD channel (the so-called tube with electrodes on the inner walls) move from left to right with a speed of $\vec{v}$, and the magnetic field indication $\vec{B}$ is directed as shown in figure.

If there are free electrons in the gas moving along the MHD channel, then under the influence of the Lorentz force $F=evB$ they will drift in the gas towards the electrode close to us (at figure) and chip off on it. As a result, a potential difference will be created between the electric cells on the walls of the MHD channel. If we connect some electrical load to the electrics, then current will flow through the load circuit.

So, the solution problem is that by placing a stream of hot gas in a pipe with two electric hydrants and a magnetic field, we made an electrical energy generator.

The mechanism of current generation in an MHD generator is the same as in any electric generator - the current will arise in a conductor moving in a magnetic field. But only in electric generators are these conductors metallic and solid, and in an MHD generator they are hot gas.

However, this is just a principle of action. To understand under what conditions such a generator will operate, let’s calculate its parameters - emf and internal resistance. Let the load resistance be infinite, in other words, the load is open. What will be the voltage $\delta$ at the output of the generator, that is, the EMF? It is equal to the work of moving

⟦folio 4⟧

unit charge between the electrodes. Since this work is arbitrary against the force $F = evB$, with a channel tension equal to $d$, $\mathcal{E} = Fd/e = vBd$. For $d = 3$ m, $v = 1500$ m/s and $B = 5$ T $\mathcal{E}$ will be 22.5 kV - quite a significant value, sufficient for practical applications.

Let's go back to Faraday's time for a minute and estimate the EMF for a pair of electrodes lowered into the Thames (of course, a river is not a stream of conducting gas, but a stream of conducting liquid, but there is no fundamental difference). The Thames is a wide river (this is good), but slow (this is bad), and the Earth's magnetic field is small (this is also bad). Polling $d = 30$ m, $v = 0,1$ m/s, $B = 10^{-4}$ T, we get $\mathcal{E} = 3 \cdot 10^{-4}$ V. (Faraday could not change this value...)
The current internal resistance of the $M\Gamma D$-oscillator.

As is known, the resistance of a metal conductor of length $L$ and cross-section $S$ is equal to $R = \frac{mL}{e^2n\tau S}$, where $m$ and $e$ are the mass and charge of the electrode, $n$ is the concentration of free electrodes in the metal, $\tau$ is the time of free passage of the electrode (see “Physics 9”, p. 175). We can use this formula for the case of a gas with electronic conductivity, substituting the “gas” values ​​$t$ and $n$ into the formula. At a temperature of $T = 2000$ K and a gas pressure in the channel of $10^5$ Pa (values ​​common for $M\Gamma D$ generators) $t$ is $\sim 10^{-12}$ s. As can be seen from figure, in our case $L = d$, $S = hl$, so $R = 3,5 \cdot 10^{19} \frac{d}{nhl}$. So, we related the internal resistance of the $R$ $M\Gamma D$ generator to the channel dimensions and the concentration of the electrodes in the gas.

What values ​​of $R$ must be ensured in order for the use of the $M\Gamma D$ generator to be economically feasible? Suppose that from a generator with channel dimensions $d = h = 3$ m, $l = 15$ m we want to obtain a power of $P = 2000$ MBt. If the load resistance is $R_H$, then the current in the generator and the load is $I = \mathcal{E}/(R + R_H)$, the power developed by the generator is $P_r = \mathcal{E}I = \mathcal{E}^2/(R + R_H)$, the power released in the load is $P = \mathcal{E}^2R_H/(R + R_H)^2$, the power loss is $P_n = \mathcal{E}^2R/(R + R_H)^2$. Since according to the conditions $P = 2000$ MBt, and $\mathcal{E} = 22,5$ kV, then $R_H = 4(R + R_H)^2$. The main reason why we “invent” the $M\Gamma D$ generator is high efficiency. This means that $P_n$ should be only a small part of $P_r$ - say, no more than 10%. Otherwise, the $M\Gamma D$-generator turns out to be no more efficient than a conventional thermal power plant. So, $P_n \leq 0,1P_r$ are empty, that is, $\mathcal{E}^2R/(R + R_H)^2 \leq 0,1\mathcal{E}^2/(R + R_H)$; then $R \leq 0,11R_H$. From here and from $R_H = 4(R + R_H)^2$ we have $R \leq 0,022$ Ohm. In order to obtain such $R$ for given values ​​of $d = h = 3$ m, $l = 15$ m, it is necessary to have an electrode concentration of $n \geq 10^{20}$ electrodes/m³. But is so many electrodes missing from the gas? At a temperature of 2000 K, practical celecomostite is made up of neonized molecules; it can be incinerated by heating, for example, to 8000 K. But at this temperature all known materials float - the $M\Gamma D$-channel and the combustion chamber simply will not be made from...

However, the concentration of the electrodes can be increased by adding easily oxidizing additives to the gas. Such additives, or additives as they are called, can be alkali metals, with the addition of potassium and cesium being the most effective. For example, the addition of 1% potassium to a mixture of $\text{CO}_2 + \text{H}_2\text{O}$ (products of combustion of coal or natural gas) creates an electrode concentration at a gas temperature of 2500 K that is $10^{24}$ times more shuto than in its absence.

The potassium additive is introduced into the very beginning of the $M\Gamma D$-channel, immediately behind the combustion chamber, in the form of salts $K_2\text{CO}_3$ or $K_2\text{SO}_4$ - cheap and readily available potassium compounds. The particles must be small, about a micron in size - they must have time to melt, evaporate, decompose and ionize at the very beginning of the channel, so that gas with sufficient conductivity reaches the electrodes.

The addition of cesium further increases the conductivity of the gas. But cesium is very expensive, and it can only be used if there is no need for constant flow during operation of the $M\Gamma D$ generator

⟦folio 5⟧

Open cycle MHD generator.

additives. To find out how the additive is consumed during the operation of an MHD generator, we will have to ask questions about the fate of the gas passing through the MHD channel.

This gas still has enough energy to turn the turbines of thermal power plants. In this case, the MHD generator will play the “highest temperature stage” in the thermal power plant. This will further increase its efficiency. After the MHD channel and turbines, gases are released into the atmosphere. And although the filters retain almost 95% of the additive at the exit from the channel, 4 tons of additive per hour will still be released into the atmosphere from the pipes of a 2000 MW MHD power plant. Therefore, cesium cannot be used in an MHD generator, which produces gases into the atmosphere after the channel - it will cost too much. For such MHD generators, called open-cycle MHD generators, only potassium in the form of K₂CO₃ or K₂SO₄ can be used as an additive.

Since there is an open-cycle MHD generator, then perhaps there is also a closed-cycle MHD generator? Yes. In it, the working fluid is usually an inert gas (usually argon), and the additive is cesium.

Gas after the channel and turbines (if there are any) returns... where? Not in the sorting chamber - there is nothing to burn in a closed-cycle MHD generator; natural fuel is not burned in it. The gas returns to the heating zone, which could be, for example, the “inside” of a nuclear reactor. In this case, there is no loss of gas or additive, and cesium can be used, which creates greater conductivity than potassium.

The use of an MHD generator with a closed cycle can reduce the efficiency of a nuclear power plant, but for the widespread use of MHD generators with both open and closed cycles, it is necessary to solve a group of problems, of which the most complex, so to speak, is the “nodal” one.

Open cycle MHD generator.

⟦folio 6⟧

Channel problem.

Insulating and conductive materials are needed that do not degrade too quickly under operating conditions of the MHD generator. And these conditions are not easy.

THE ENVIRONMENT in an open-cycle MHD generator is chemically active products of fuel combustion with even more chemically active impurities (sulfur) and additives (potassium).

In a closed-cycle MHD generator, although there are chemical inactive inert gases, there is a very chemical active additive (cesium).

TEMPERATURE 2000÷3000 K.
And in addition, this chemically active and rather hot wind has

SPEED 1000÷2000 m/s.

Only the most refractory compounds (Al₂O₃, MgO) can withstand such conditions. They are used as insulators for the walls of the MHD channel. And metals also cannot withstand the conditions at all. Therefore, electrodes are made not from metals, but from conductive chemical compounds and their mixtures (ZrO₂+CeO₂, ZrO₂+La₂O₃, LaCrO₃, etc.). However, the durability of these materials also leaves much to be desired. Numerous attempts to protect the electrodes from the action of a flow of hot gases have not yet been crowned with complete success. If the “channel problem” and a number of other, equally complex problems (a powerful electromagnet, a high-temperature nuclear reactor) can be solved, then the following will open up for the MHD generator.

Prospects for application.

1. MHD GENERATOR WITH OPEN CYCLE ON NATURAL FUEL AS A METHOD OF USING ENERGY WITH MAXIMUM EFFICIENCY.

Such a generator will operate on coal, oil or gas, having an efficiency of 50-60% (with a two-stage scheme: MHD generator + thermal power plant turbines at its output). To generate, for example, a power of 2000 MW, the generator (MHD+TES) must have a cross-section of 9 m² (d=h=3 m) and a length of 15 m. The gas velocity in the channel will be 1500 m/s, the magnetic field 5 Tesla. Every second in the combustion chamber, two tons of fuel will be converted into a mixture of CO₂+H₂O gases, heated to 2500 K, and 20 kg of K₂CO₃ additive will be added to the beginning of the channel every second. The gas correspondence in the channel will be 0.02 ohms. An important parameter of an MHD generator as a high-temperature stage of a thermal power plant will be the continuous operation time - you cannot stop the MHD power plant too often to repair the channel. (Ensuring a long continuous operation time is another important problem in the creation of powerful MHD generators.) On the current U25 MHD generator (maximum power 20 MW), a continuous operation time of about 10 days has been achieved when operating at a power of 3 MW. But in order for the use of MHD generators to be economically feasible, the power must be increased by 10-100 times.

2. MHD GENERATOR WITH OPEN CYCLE ON NATURAL FUEL TO COVER “PEAK LOADS” IN THE ELECTRIC NETWORK.

Such power plants are called “peak” or “half-peak”, in contrast to “baseload”. Energy consumption changes throughout the day - for example, in cities the “peak load” comes in the evening. Changing the operating mode of thermal power plants is usually quite difficult, and in the evening there is not enough energy. The situation can be alleviated if you have an MHD generator of appropriate power, since turning it on or changing the operating mode takes several minutes. Such a generator would turn on only during the “peak load” period and increase the power of the power plant as necessary.

3. MHD GENERATOR AS A POWERFUL LOCAL SOURCE OF ELECTRICITY FOR SHORT-TERM CONSUMPTION.

To power experimental physical installations it is often required
