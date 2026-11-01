---
id: 1986-2-levinshteyn-simin-logicheskie-shemyi-na-tranzistorah-e051e94b
issue: kvant_1986_2
year: 1986
number: "2"
title: Transistor logic circuits
authors:
  - Левинштейн М. Е.
  - Симин Г. С.
rubric: raznoe
rubric_sub: Разное
page_first: 46
page_last: 47
page_labels: 44-45
tag: IDFV
lang: en
source: kvant_digital
extraction: vision
content_sha256: 03a7c1f3565b3a8c54f0eba86c8782e025833d79507f898ab04c6f2b82dee0ef
prompt_sha256: draft-1
translated_from: content/ru/1986/02/articles/17_levinshteyn-simin-logicheskie-shemyi-na-tranzistorah-e051e94b.md
source_content_sha256: 3a3e5a12427c778a650d8785ffdf207117e4bf9f07138b65e0c00ca4825a1860
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 44⟧

VI. Transistor logic circuits

Doctor of Physical and Mathematical Sciences M. E. LEVINSHTEIN, Candidate of Physical and Mathematical Sciences G. S. SIMIN

Having gained an understanding of elementary logical operations (see «Kvant», 1986, No. 1), we can now become familiar with how they are implemented using a transistor circuit.

The simplest logic circuit that performs the “OR” operation is shown in figure 1. The circuit contains two biopolar transistors of the “n-p-n” type.

The designation corresponds to a biopolar transistor of the p-n-p type; the designation corresponds to an n-p-n type transistor.

An oblique arrow corresponds to the empter, a vertical dash to the base, and an oblique dash without an arrow to the collector.

The collectors of the common transistors are connected in parallel to the “plus” of the power source E. The emitters are connected to the load resistance Rₙ. If the direction between the base and empteter of the transistor is zero, then the base-empteter junction is closed, so there is no flow through it. Therefore, the collector-ampteter in the circuit is also fuzzy (the transistor is closed). From figure 1 it is clear that if there is no signal at the inputs of the transistors, that is, the direction at the inputs Uₙ₁ and Uₙ₂ is zero, then the transistor is closed. So I does not flow through the load resistance Rₙ, and the output signal Uₙ₁=IRₙ is also zero. If at least one of the directions supplied to the inputs of the circuit is sufficient to send transistors T₁ and T₂, then the circuit sharply reverses and the output direction increases significantly.

Silicon transistors are usually closed if the direction to the base-amptet junction is less than 0.6 V. Therefore, in a circuit of this type, the “logical zero” level usually corresponds to the U⁰ direction, close to zero, and the “logical one” - U¹≈0.8 V.

Figures 2 and 3 show the “AND” and “NOT” circuits on biopolar transistors. Reasoning in the same way as when analyzing the “OR” circuit, it is easy to verify that for the “AND” circuit the output direction Uₙ₁>0 only if the transistor T₁ and T₂ are simultaneously open, that is, the direction corresponding to the logical unit is applied to both inputs (Uₙ₁=U¹, Uₙ₂=U¹). In the “NOT” scheme, Uₙ₁=U¹ with Uₙ₂=U⁰ and, conversely, Uₙ₁=U⁰ with Uₙ₂=U¹.

An important disadvantage of logic circuits based on biopolar transistors is that in one of the states of the circuit a large current flows through the output resistance Rₙ. In computers containing millions of logic circuits, this leads to significant power loss, heating of the circuits during operation and reduced computer reliability. This disadvantage is eliminated in logic circuits based on complementary*) useful transistors - CMOS circuits.

An example of a CMOS circuit is shown in figure 4.

*) “Complementary” translated from English means “additional”.

Fig. 1. An example of the implementation of an “OR” circuit on two biopolar transistors of the n-p-n type.

Fig. 2. Example of implementation of the “AND” circuit.
Fig. 3. Example of implementation of the “NOT” circuit.

⟦folio 45⟧

IN THE ULTIMATE FUTURE, COMPUTERS WILL APPEAR, THE LOCAL DIAGRAMS OF WHICH WILL BE MANUFACTURED BY GALLIUM CZAREND (Ga As).
These schemes are significantly faster.
The microphotograph shows a VIS based on Aspendall field-effect transistors. The size of the VIS is 2.7×2.25 mm. The gate length of transistors in VIS is ~1 µm.
The switching speed of elements of VIS logical cells is 150 ps. In terms of performance, this circuit is four times faster than the best silicon VIC, similar to its intended purpose.

Principal diagram and conditions designation of a modern logic chip of the K187 series on silicon biolar p-p-n transistors.
The circuit has 5 inputs and 2 outputs. At one of the outputs (pin 6), a logical sum voltage is generated (operation “OR”) of sisals $x_1$—$x_5$, supplied to outputs 1—5, at the other output (pin 7) a signal combining the operation of logical summation and inversion (operation “OR”—“NOT”) is generated.
The existence of the conditions of a logical circuit in comparison with the simplest cell shown in figure 1 is caused by the need to ensure high performance, low power consumption, insecurity of the circuit parameters from the power supply voltage and the number of other logical circuits connected to it, the requirement for noise immunity of logical output signals, etc.
The comparative time of the microcircuit is about $10^{-8}$ s, the current consumption is ~10 mA.

The vertical line indicates the transistor channel. The horizontal lines extending from it are the source (lower) and drain (upper). A line running parallel to the channel next to it represents the gate. The gate output is drawn at the same level as the source output.

The MOS transformers $T_1$ and $T_2$ used in the circuit have different types of structures. Tranitor $T_1$ is normally open, that is, in the absence of voltage on the gate, the conductivity of its channel is high; tranitor $T_2$ is normally closed; at zero voltage on the gate, no current flows through its channel. With a sufficiently large positive voltage on the gate $U^1$, the normally open tranitor $T_1$ is locked, and the normally closed $T_2$ is unlocked.

In the circuit shown in figure 4, with $U_{bx}=0$ $T_1$ is open and $T_2$ is closed, so the entire power supply voltage drops across the tranitor $T_2$; since the output voltage sigma with tranitor $T_2$, $U_{bx}$ is high. At $U_{bx}=U^1$ $T_1$ closes and $T_2$ opens, so $U_{bx} \approx 0$. In general states, the current flowing in the circuit is zero, since one of the transitors is in the closed state. Therefore, the CMOS circuit consumes power from the source only at the moment of switching. Based on CMOS circuits, microcalculators and microcomputers have been created that have record low power consumption - fractions of a microwatt. Such micro-computers can be powered by a photocell, for which the light from a central lamp is sufficient to operate.
