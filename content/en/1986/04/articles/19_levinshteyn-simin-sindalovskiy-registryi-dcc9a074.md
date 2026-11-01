---
id: 1986-4-levinshteyn-simin-sindalovskiy-registryi-dcc9a074
issue: kvant_1986_4
year: 1986
number: "4"
title: Registers
authors:
  - Левинштейн М. Е.
  - Симин Г. С.
  - Синдаловский В. Я.
rubric: raznoe
rubric_sub: Разное
page_first: 48
page_last: 49
page_labels: 46-47
tag: U7MX
lang: en
source: kvant_digital
extraction: vision
content_sha256: e5597cc77dff469398d653ce36b6285ee37c7274329af39ce4bd83a0ef0e7177
prompt_sha256: draft-1
translated_from: content/ru/1986/04/articles/19_levinshteyn-simin-sindalovskiy-registryi-dcc9a074.md
source_content_sha256: 0730eb4bb342f385368f0c2a7abe4f3181cda73855ad57df582efe0d826bd16d
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 46⟧

VIII. Registers

Doctor of Physical and Mathematical Sciences M. E. LEVINSHTEIN, Candidate of Physical and Mathematical Sciences G. S. SIMIN, V. Y. SINDALOVSKY

A computer is often compared to a living organism. In this complex organism, the role of the heart is played by the clock generator, which sets the rhythm of the machine, and the role of the brain is played by the processor that controls all operations derived from the computer. The “eyes” and “ears” of the computer are information input devices, the “nervous system” is a complex network of conductors that unites the elements of the computer into a single whole, and “speech” is the device for inputting the results obtained.

In this complex organism, we studied the work of single cells - transistors. It is from such “cells”—bioplar or field-effect transistors—that almost all parts of a computer are made up. Without studying how a cell is structured and how it works, it is impossible to fully understand the work of an organization. But on the other hand, it is clear that limiting oneself only to acquaintance with a single cell will not advance particularly far in the study of a complex organism.

In this and the next notes we will discuss, as an example, how, based on the simplest logical circuits and flip-flops on transistors that we have already studied, more complex radio-electronic circuits are created that directly serve as computer nodes - registrations and adders.

All information stored and processed in a computer is presented, as we know, in the form of numbers written in a dual system. Registers are used in computers to write, store and read numbers.

figure shows a simplified registration scheme for recording numbers with four digits (in fact, registrations of modern computers can contain up to 64 digits). The register consists of storage elements - flip-flops, input “AND” circuits that allow writing, and output “AND” circuits that allow reading a number.

Pay attention to the trigger symbol. It is similar to the symbol for other logic circuits, but contains a “T” in the upper right corner. The two inputs of the trigger are designated by the letters S (from the English word set - set) and R (from the word reset - return, restore). The difference between the inputs is relative - they are completely electric.

This is how the RAM of a modern computer works. Silicon integrated circuits are visible on the printed circuit board. The write and read time of such memory is 50–100 ns.

When performing operations with large numbers, we use the following representation of the number:

0.123826·10⁵ Magnets order base of the number system

In computer resistors, it is used in a similar way to represent numbers with the only difference being that the base of the number system is 2 (binary system), and mantissa and the order of notation are in the binary system.

Recording the number 4.5 in a nine-rard computer resistor:

1 2 3 4 5 6 7 8 9

1 0 0 1 1 1 0 0 1

sign order sign magnets mantissa.

The first digit of the resistor is allocated to record the sign of the number (mantissa). The number 1 in the digit corresponds to a minute, 0 - plus. The second digit shows the order sign. In this example, the order has a plus sign. Bits 3 to 5 are reserved for recording order; in this example the order is +3. Bits 6 to 9 are used to write the double mantissa. A unit in the 6th digit corresponds to 2⁻¹, in the 7th - 2⁻², in the 8th - 2⁻³, etc. Thus, the number is written - (1·1/2 +0×(1/4+0·1/8+1·1/16)). 2³ = -4.5.

In the example given, mantissa can vary from

⟦folio 47⟧

- $\frac{15}{16}$ to + $\frac{15}{16}$, and the order is from - 7 to + 7. In the EC series computers, numbers from $\approx 5,4 \cdot 10^{-79}$ to $\approx 7,2 \cdot 10^{75}$ are stored in 32-bit latches.

In the near future, silicon VICs will be replaced by RAM ICs based on semiconductor materials. The photograph shows a cell of such an IC having a size of 62×65 microns. The field-effect transistors included in the circuit have gates 1 micron long. The chip with a memory capacity of 4 kbit contains 26,600 field-effect transistors and has a size of 5.6 × 6 mm. Lined IS - 2 IS.

The amount of RAM is insufficient to solve complex problems on a computer. The main part of the information is stored in external memory, which has a much larger volume, although it is slower. The photo shows an external memory device on magnetic tape, a bit like a regular reel-to-reel magnetfon. A 750 m long belt can store up to 6 ml. 32-bit numbers. The reading time for the entire tape is 6-7 minutes.

Chennault are equivalent. Input $R$ is used to set the initial “zero” state of the flip-flop, and input $S$ is used to supply the signal to be filled. The output of a flip-flop, for example on which is set equal to “1” when a “1” is applied to $S$, is called the main one (upper selection on figure 1), and the second choice, for example on which it is inverse with respect to the input signal, is called additional. Inversion, as in “NOT” type schemes, is indicated by a circle.

The “zero setting” inputs $R$ of all flip-flops are connected; Before recording, a “1” signal is applied to them, as a result of which “0” is set at all main outputs of the triggers.

Let's see how a number is written to a register. Each of the input AND circuits has two inputs. One of them (low at figure 1) is common to all schemes. The wire connecting these common inputs is called a recording bus (RW). If zero voltage is applied to the recording bus, then all outputs of the “AND” circuits will also have zero voltage, regardless of the signals at the second, “signal” inputs - this is a property of “AND” circuits (see notes in No. 1, 2 «Kvant», 1986). However, if the signal “1”—recording permission—is supplied to the RAD recording bus, then the voltage at the outputs of the “AND” circuits, and therefore at the $S$ inputs of the triggers, will depend on what signal is received at that moment on the second, signal inputs of the “AND” circuits.

At figure 1 the number 9 (1001) is shown as an example. In the first and fourth digits at the signal inputs there is a “1” signal. If there is also a “1” signal on the RAC bus, then a “1” signal will be received at the input $S$ of the 1st and 4th digit flip-flops, which will “flip” these flip-flops. “1” will be written in the 1st and 4th digits. In bits 2 and 3, where there is “0” at the signal inputs, there will also be “0” at the outputs of the “AND” circuits and “0” remains written in the triggers.

The action of the output “AND” circuits is similar to the action of the input ones. As soon as a “1” signal is applied to the readout bus (MF), “1” signals will appear at the outputs of the “AND” circuits in those bits in which “1” was written at the main output of the trigger.

In circuits that implement flip-flops. At these outputs, a so-called “reverse code” of the written number is created, in which “0” is in place of “1” and vice versa. The reverse code is used in computers to perform some arithmetic operations with double numbers.

The set of recordings that use a computer to fill out the work program, initial and intermediate data of mathematical operations is called RAM. The RAM of one of the large domestic computers “VESM-6” contains 32768 (32768=2$^{15}$) registers, each of which allows storing 48-bit double numbers.

RAM is required to be very fast because it must be able to write and read numbers at the same speed as the machine performs calculations. Among modern industrial circuit interfaces, ICs based on silicon bipolar transistors are the fastest to build. Therefore, the RAM of large computers is made of logical circuits and flip-flops on bipolar transistors.

The registers of microcalculators are made on the basis of useful MOS transistors. The speed of such memory is much lower, but these MOS transistors consume much less energy. Thanks to this microcalculator, tens of hours of operation can be achieved on a miniature battery.
