---
id: 1985-10-levinshteyn-simin-polevyie-tranzistoryi-21ce4f71
issue: kvant_1985_10
year: 1985
number: "10"
title: Field effect transistors
authors:
  - Левинштейн М. Е.
  - Симин Г. С.
rubric: raznoe
rubric_sub: Разное
page_first: 48
page_last: 49
page_labels: 46-47
tag: WFPP
lang: en
source: kvant_digital
extraction: vision
content_sha256: cbffb183859796d9af6aa15c45dd0323368f15595ee94cc6275830d9fd08c5a3
prompt_sha256: draft-1
translated_from: content/ru/1985/10/articles/19_levinshteyn-simin-polevyie-tranzistoryi-21ce4f71.md
source_content_sha256: 88a5b51843eb25203a66c69fde90c9eaf3c32d170e177751986abf5dbfdeb6b0
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 46⟧

II. Field transistors

Doctor of Physical and Mathematical Sciences
M. E. LEVINSHTEIN,
Candidate of Physical and Mathematical Sciences
G. S. SIMIN

The operation of a field-effect transistor (FET) is very simple (Fig. 1). There are three electrodes located on a thin field plate. If a voltage is applied between electrodes 1 (source) and 2 (drain), current will be drawn through the plate, called a channel. The amount of current flowing through the channel changes when a control voltage is applied to the third electrode (gate).*)

Different types of field-effect transistors (and there are quite a few of them) differ from each other in the principle of gate operation. There are PTs in which the role of the gate is played by a $p$ junction, a metal-field conductor contact, a metal-dielectric-field conductor structure (MIS structure), etc.

figure 2 shows a FET that uses $p$, a reverse-mixed junction, as a gate. As is known (“Physics 9” §79), at the boundary between electron ($n$-type) and hole ($p$-type) field conductors, a layer depleted of free current carriers (barrier layer) is formed. If we apply the $p$-transition of the blocking voltage $U_3$: “flat” to the $n$-type and “minus” to the $p$-type, then the width of this layer increases. Since there are no free carriers in the barrier layer, no current flows through it. Thus, an increase in gate voltage leads to drying of the channel through which current flows, and at a constant drain-source voltage a decrease in current through the transistor is produced. Even more, the gate voltage completely blocks the channel, and the current goes to zero.

figure 3 shows another type of transistor, widely used in modern computers, especially in microcalculators. A MIS structure is used as a gate in this FET. The metal gate is separated from the field platinum by a thin (hundredths of a micron) layer of silicon dioxide SiO$_2$, which is a good dielectric. Therefore, transistors of this type are sometimes also called MOS-PT (metal-oxide-field conductor). On a $p$-type silicon plate, $n$-type regions (Fig. 3, a) are created under the drain and source. The drain-source voltage $U_{cn}$ is thus applied to two series-connected $p$ junctions. Whatever the polarity of the voltage $U_{cn}$ in the absence of voltage on the gate, one of the $p$ junctions always turns out to be locked. In this state, the resistance of the $p$ junction is very high, and the current flowing through the transistor is close to zero.

*) Since the channel resistance is controlled by the electric field of the gate, transistors of this type are called field-effect transistors.

The minimum achievable channel length $L$ is determined by technical perfection. For a field-effect transistor of the 60s $L \approx 20$ µm. For a perfect silicon MOS transistor $L \approx 3$ µm. Devices with $L \lesssim 0,3$ microns have been obtained in research laboratories.

The intrinsic switching time of a “3 µm transistor” is $3 \cdot 10^{-11}$ s. Practical speed compared

⟦folio 47⟧

The operating time of a modern serial logical MIS cell is 5·10⁻⁹ s. The record-breaking short switching time of an MOS transistor, obtained in 1984, is ~10⁻¹¹ s.

Microphotograph of a MDP-BIS fragment. The channel length of the largest elements is ~10 µm, the smallest is ~1 µm.

With a huge packing density of elements on the wafer (~10⁵) and tiny sizes of the elements (≤1 μm), each piece of dust that lands on the wafer leads to failure of the LSI.

Surgeons usually work in such suits. But this girl “operates” no more: she performs an operation to destroy the BIS.

If you apply a relatively small positive potential to the gate $U_3$, then on the other side of the dielectric, in the $p$ channel, which, as it were, serves as the second plate of the capacitor, negative charges will begin to accumulate. A positive charge on the gate causes electrons to appear in the channel, which are attracted by the field of the metal electrode. At a certain voltage $U_3=U_0$, called the threshold voltage, in a narrow layer under the gate, the condensation of field-induced electrons will exceed the initial concentration of holes in the $p$ channel. There will be a change in the conductivity characteristic (inversion). Instead of a $p$-type semiconductor, a $n$-type semiconductor will appear within this layer. As a result, the $p$-transitions between the drain and the source disappear and a continuous conducting channel is formed (Fig. 3, 6). In this state, the resistance of the transistor is low.

PTs in which, in the absence of control on the gate, the channel is open and the resistance is low, are called normal open. PTs in which, on the contrary, in the absence of control the channel is closed, are called normal closed. MDP-PT, the operating principle of which is higher distances (Fig. 3), refers to normal closed PT.

In order for a circuit containing a PT to have two easily distinct states “0” and “1”, and thus be able to serve as an element of a logic cell, it is sufficient to include a load resistance $R_H$ and a voltage source $\varepsilon$ in series with the transistor in the drain-source target.

If, for example, a normal closed PT is used in such a circuit, then in the absence of voltage at the gate ($U_3=0$), the resistance of the transistor is very high and almost the entire source voltage $\varepsilon$ drops across the transistor. When the gate voltage exceeds the threshold value $U_0$, the transistor resistance is low and the entire voltage drops across resistance $R_H$. These two easily distinct states correspond to the "0" and "1" states in logic circuits based on MOS transistors. A small (≈1 V) gate signal is enough to switch the transistor from the “0” state to the “1” state.

The most important parameter of a transistor as an element of computer logic circuits is the speed of its switching from open to closed and vice versa. This speed is determined both by the properties of the device itself and by the circuit in which it is switched on. The shortest switching time that, in principle, can be obtained is approximately equal to the time of passage of carriers m along the channel under the influence of the applied voltage $U_{cn}$. With channel length $L$ and carrier speed $v$, the travel time t is $\tau=L/v$. The drift speed of electrons (or holes) in an electric field is known to be proportional to the field voltage $E$ ($v=\mu E$). The proportionality coefficient $\mu$, which has a dimension $m^2/(B \cdot c)$, is called mobility. Since the field is intense in channel $E=U_{cn}/L$, we finally obtain: $\tau=L^2/\mu U_{cn}$. Thus, the maximum fast solution of field-effect transistors is determined by how short the transistor channel can be made, and the mobility of carriers in the materials from which the transistor is made.

You will learn about the actual types of transistors, their switching speeds and packaging density in modern computers from the adjacent column.
