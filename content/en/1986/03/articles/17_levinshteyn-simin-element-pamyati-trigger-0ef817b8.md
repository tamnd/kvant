---
id: 1986-3-levinshteyn-simin-element-pamyati-trigger-0ef817b8
issue: kvant_1986_3
year: 1986
number: "3"
title: Memory element - trigger
authors:
  - Левинштейн М. Е.
  - Симин Г. С.
rubric: raznoe
rubric_sub: Разное
page_first: 50
page_last: 50
page_labels: "48"
tag: FU5Z
lang: en
source: kvant_digital
extraction: vision
content_sha256: fa5f56243ccb3e740a55b75db0695a1540f83fe11ffb42b4f940324550dbce8f
prompt_sha256: draft-1
translated_from: content/ru/1986/03/articles/17_levinshteyn-simin-element-pamyati-trigger-0ef817b8.md
source_content_sha256: a8a53fed2ca4fd1e761d84086db18d2c46dc303d4757f2fa24d7365af669ee9f
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 48⟧

VII. Memory element - trigger

Doctor of Physical and Mathematical Sciences M. E. LEVINSHTEIN,
Candidate of Physical and Mathematical Sciences G. S. SIMIN

We began the previous section on logical circuits (see «Kvant», 1986, No. 1, 2) with a discussion of logical problems that a device that controls the movement of elevators in a common house must solve. Now is probably a good time to mention that even such a simple device cannot function if it does not contain memory elements. Several data were recorded in the “memory” of the elevator control device: how many seconds should the door remain open after the elevator is released; what to do if the door automatically closes and encounters a problem; what is the sequence of operations when pressing the emergency “stop” button, etc. In addition to these available data, operational data is entered and recorded into the elevator “memory”, changing during operation - on which floors the buttons are pressed; where the elevator is moving at the moment: up, down, standing still.

Hundreds of thousands and sometimes millions of data are recorded in the memory of a computer solving a complex problem. This data, as already mentioned, is written in a form that a computer can perceive and process, that is, using “zeros” and “ones” (in the double number system).*

It is clear that neither the elements of computer technology we have considered - transistors, nor the logical circuits based on them - can themselves be memory elements. All of them, after the cessation of the input pulse, immediately return to their original state.

For a memory element, you need a device that, under the influence of an input pulse, could switch from state “0” to state “1” and back; and at the same time, after the termination of the input pulse, it would fill its state and could remain in it indefinitely (until the arrival of the next switched input pulse).

A radio circuit that meets these requirements is called a trigger (from the English trigger).

The easiest way to understand the principles of operation of a flip-flop is to use the already known property of the NOT (inverter) logic circuit.

Consider two inverters connected in series (Fig. 1). For example, at the input of the first inverter, $U_{bx} = x$ can equal either $U^0$ (logical zero) or $U^1$ (logical one). For example, the output of the first inverter is always $x$ (not $x$), that is, $U^1$ for $U_{bx} = U^0$ and $U^0$ for $U_{bx} = U^1$. Output voltage first

*) The humorous poem “An Extraordinary Girl” (p. 50) will help you figure out how the double and decimal number systems are connected.
