---
id: 1985-11-levinshteyn-simin-bipolyarnyie-tranzistoryi-66c5b29e
issue: kvant_1985_11
year: 1985
number: "11"
title: Bipolar transistors
authors:
  - Левинштейн М. Е.
  - Симин Г. С.
rubric: raznoe
rubric_sub: Разное
page_first: 50
page_last: 51
page_labels: 48-49
tag: 9MVF
lang: en
source: kvant_digital
extraction: vision
content_sha256: 17cc9f1be5b94253b73d1207d401a465f7e5359056b59c1e77438cdc88fe4b6c
prompt_sha256: draft-1
translated_from: content/ru/1985/11/articles/21_levinshteyn-simin-bipolyarnyie-tranzistoryi-66c5b29e.md
source_content_sha256: d2b2b41830856673a36e1d65836a94e5ccd0b0eeae9366265f2c2d42ede90af2
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 48⟧

III. Biopolar transistors

Doctor of Physical and Mathematical Sciences M. E. LEVINSHTEIN, Candidate of Physical and Mathematical Sciences G. S. SIMIN

The operating principle of a biopolar transistor (BT) is discussed in some detail in a school physics course (“Physics 9”, §81). Therefore, here we will limit ourselves to only a brief description of the main features of the BT operation.

The transistor consists of three layers of semiconductor with intersecting conductivity types, that is, it is a p-n-p- or n-p-n-structure.

In a pnp structure, accelerator impurities are added to the two extreme regions of the transistor, called the emitter and collector, and the current in these regions is carried by positively charged holes. Additional impurities are added to the middle part of the structure, called the base, which enriches the semiconductor with imprinted conduction electrons.*)

In the n–p–n structure, a supporting impurity is added to the emitter and collector, and an accelerator impurity is added to the base, respectively.

Both types of transistor structures are widely used. In the future, for the purpose of definition, we will only talk about BTs of the n-p-n type, especially since such transistors are more often used in computers.

Figure 1 shows the operating principle of the BT. An external voltage source connected between the emitter and the base will mix the emitter-base p-n junction in the forward (throughput) direction. The second source will mix the p-n junction collector - base in the opposite (blocking) direction. With this connection, a small current flowing in the base causes the appearance of a current in the collector circuit that is larger in magnitude.

The ratio of the collector current to the base current—the current success rate of the transistor β—is determined by the mobility of current carriers in the materials and the base thickness W. The smaller W and the larger μ, the greater the success rate. The value of β in BT ranges from several tens to several thousand.

In computer circuits, BTs are often powered not from two, as shown in figure 1, but from one power source (Fig. 2) and operate in the so-called key mode.

*) Since in transistors of this type an equally important role is played by carriers of both signs - negatively charged electrons and positive holes - then such transistors are called biopolar. In field-effect transistors (see the previous issue of the magazine), the movement of carriers of only one sign is used - either electrons or holes. Therefore, field-effect transistors are sometimes also called unipolar.

Fig. 1. Schematic representation of a biopolar transistor.

Fig. 2. BT operation in key mode.

This is how the biopolar transistor was designed (1947). Wrap a gold foil (3) into a plate of monocrystalline thermanium (6) with a strong pressing plastic triangle (2). At the top of the triangle, pressed into the plate, the foil is cut with a razor. At the point of contact of the foil with the surface of the single crystal, a p-type region is formed: emitter (1) and collector (4); between them is the base (5).

⟦folio 49⟧

The first industrial binary transistor (1948). The emitter and collector junctions are manufactured by fusing thin wires into a thermane crystal. Gain $\beta \cong 2$, switching time $t_0 \cong 30$ ms, case diameter 1 cm, height 4 cm.
1 - contact to emitter;
2 - contact to the collector;
3 - body; 4 - insulating gasket; 5 - two wiring contacts; 6—thermanium crystal; 7 - contact to the base.

When operating in this mode, the BT can be in one of two possible states - open or closed.

Let no signal be applied to the input of the transtor shown in figure 2. The power supply voltage $E$ will mix the collector-base junction in the reverse (blocking) direction, and $p$ - the emitter-base junction - in the forward direction. Since the resistance of the $p$ - $n$ junction in the blocking direction is very high, almost the entire direction drops at the collector junction BT. The voltage between base and emitter is close to zero. So through the transtor it is practically absent. In this state, the transistor is “closed”. The entire direction of the source $E$ falls on the transistor. The output direction $U_{вых} \approx E$ is large.

A small signal between the base and emitter, mixing the emitter-base junction in the forward (through) direction, causes the appearance of a large current in the collector-emitter circuit. In this case, the direction of the power supply drops at the load resistance $R_H$. The voltage on the transistor becomes low - the transistor is “open”.

These two easily distinct states correspond to the "0" and "1" states in BT-based logic circuits.

The speed of switching BT from open to closed and back is determined both by the parameters of the device itself and by its connection circuit. The shortest switching time that can in principle be obtained is determined by the time during which the carriers (electrons in the $n$ - $p$ - $n$-or holes in the $p$ - $n$ - $p$-transistors) pass through the base of the transistor due to the diffusion process.

During diffusion (random walk), carriers in time $t$ move away from the initial position by a distance $x = \sqrt{Dt}$, where $D$ is the diffusion coefficient of carriers in a given material$^*$). Hence, the minimum possible switching time $t_0$ in a BT with base thickness $W$ is defined as $t_0 \approx W^2/D$.

It should be noted that the diffusion coefficient is related to the carrier mobility $u$ dependence established by Albert Einstein. According to Einstein's correspondence, the value of $D$ is directly proportional to the value of $u$.

Thus, the maximum possible speed of binolar transistors, as well as useful ones, the higher, the shorter the path length traveled by the current carriers (base thickness $W$), and the higher the mobility of carriers $u$ in the materials from which the transistor is made.

Currently, the vast majority of BT is made from silicon (Si). The electron mobility in Si is approximately $0,1 \text{ m}^2 / (\text{B} \cdot \text{c})$. The most promising material for the manufacture of BT in the near future is gallium arsenide (GaAs). The electron mobility in it is about $1 \text{ m}^2 / (\text{B} \cdot \text{c})$.

The practical ripping speed of modern serial logic cells on BT is 1 - 10 ns. The record low BT switching time, obtained in 1984, is 30 ps ($30 \cdot 10^{-12} \text{ c}$).

$^*)$ Read about this in more detail, for example, in the book by M. E. Levinshtein and G. S. Simin “Introduction to Semiconductors”, Library «Kvant», no. 33. (Editor's note)
