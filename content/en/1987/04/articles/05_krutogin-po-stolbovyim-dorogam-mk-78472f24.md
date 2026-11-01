---
id: 1987-4-krutogin-po-stolbovyim-dorogam-mk-78472f24
issue: kvant_1987_4
year: 1987
number: "4"
title: Along the main roads of MK
authors:
  - Крутогин Д. Г.
rubric: raznoe
page_first: 17
page_last: 19
page_labels: 15-17
tag: AZJH
lang: en
source: kvant_digital
extraction: vision
content_sha256: 1e991d13c05eea279412c1bdcd8b51d186d677c9c2863beb8461c92d441768e4
prompt_sha256: draft-1
translated_from: content/ru/1987/04/articles/05_krutogin-po-stolbovyim-dorogam-mk-78472f24.md
source_content_sha256: ff82eb9a8a1734fa5dd5a3c63f8ecc04dcc57fc9efcc80653749cb43c6af5339
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 15⟧

BY PILLAR
ROADS MK

(Journey through a microcomputer)
Candidate of Technical Sciences D. G. KRUTOGIN

From viewing the panorama and studying the city plan of MK (see «Kvant» No. 2, 3), let's move on to a tour of it. Today our goal is to beat RAM and ROM in the “residential” areas of the city. We will get there along the main street of the city, which is called the “common bus” and connects all districts of the city. On the accepted scale*), moving along the tire, we will see under our feet ten primogol metal strips with dimensions of 1 × 2 m (figure 1). In appearance they are indistinguishable, but from the plan we know that these tracks form three road systems, or three separate buses. The widest bus is the address bus. It is intended to distribute machine words into memory cells when writing and recall them from there when reading. Memory cells are organized into a matrix (figure2); the selection of the desired cell is made when

*) We remind you that for the journey we will have to shrink a million times.

15

⟦folio 16⟧

power of address signals. The matrix organization of storage devices is the most rational in terms of ease of control and the number of required wires.

The other two buses—the data bus and the control bus—typically contain fewer wires. The data bus, unlike others, has two-way organizational movement (towards or away from the process).

Traffic speeds on city streets are always high. But there are few streets, and a lot of people travel along them, so the data bus is busy for a long time. To avoid oncoming traffic and accidents, near the exits to the main street in all areas there are unique “traffic police posts” - buffers that set the regime in an agreed manner

Fig. 1. Fragment of a tire. Photograph with a magnification of approximately 2000.

Fig. 2. Scheme of organization of 4×4 bit matrix RAM. Squares indicate RAM cells, triangles indicate input buffers, set to write or read mode; X and Y are the address bus wires, PШ₀, PШ₁ are the bit wires of the data bus.

Street traffic. Buffers prevent the movement of fish words by an unorganized crowd; they form them into dense columns and send them to their destination. The most active exchange will take place between the Processor and RAM areas.

Let us assume that a request is sent from the Processor to RAM for a certain word contained in a certain memory cell. This means that pulses corresponding to the coordinates of this cell are sent to the address bus wires, while at the same time a read command is sent via the control bus. At the entrance to the RAM area, this command is indicated by writing to the memory cells of the buffer register *). After this, depyrification and execution of the command begins. The cell's response signals (one for each bit of the requested word) do not, as a rule, go directly to the data bus, but again to the buffer register of this bus. When it is full, i.e. the response word has been generated, the buffer switch sends the entire contents of this register to the Processor. At the same time, the no longer needed request command is erased from the control bus buffer register. Arriving at its destination (for example, at the processor), the word - the RAM response - will once again be placed in the “reception”, the process’s own buffer register.

We have already said that the efficient operation of the Processor ensures fast and sufficiently large memory. To quickly find the required information, the designers divided the RAM area into blocks - pages. However, a page is a matrix of 16x16 cells, i.e. 256 cells capable of storing binary information. If our page is 256, then the total amount of RAM is 256².

Transistors of logical elements are placed at the input of each quarter-page. As if pinmailing, this requires that the page code and cell code be present in the address. Therefore, the address itself is a machine word.

City for guests

The cell that stores a bit of information in RAM is a flip-flop and usually contains four transistors. Previously, we considered one transistor to be a house, now it would be more appropriate to consider it one of the buildings

*) Hereinafter, we will use the term “register” to mean a small RAM memory with a capacity of one or two machine words.

⟦folio 17⟧

Fig. 3. Static RAM cell with a capacity of 1 bit: a) - an uncontrolled cell with two equal states, b) - a trizer with two inputs based on such a cell.

Fig. 4. Pritsitsit acting dynamic memory.

cell houses*). The trigger circuit was described by Russian radio engineer M.A. BonchBruevich almost 70 years ago. The simplest trigger of two transistors is shown at figure 3, a. Of the two transistors, one is always closed, the other is open. By applying a short signal from the outside to a closed transistor, the position can be changed to symmetrical and opposite. This design is called a bistable cell. For flexible control, you need to add two more transistor switches to it. The circuit that you see on figure 3, b, practically, is a 1-bit trigger memory cell. This is a typical building element of the OZU district. Such memory on a trigger is called static. It works quickly and reliably, but... Constructing a “house” of four transistors for each bit becomes very cumbersome when the count is hundreds of thousands of bits (the RAM of a modern microcomputer must have a capacity of at least 64 kB). The main thing is that there is not enough space for RAM.

Therefore, for large RAMs, a different memory system is used, the principles of which appear on figure 4. If capacitor C is charged through the key S, then after the key is opened, the capacitor will maintain the mode of the transistor T, specified by the initial charging signal. Thus, the transistor mode (open or closed) seems to store one bit of information; but until when? Until capacitor C*) is discharged. The switch S is, as always in microelectronics, a transistor, and its resistance is high, but not infinite.

To prevent the capacitor from being discharged and the stored bit not being lost, capacitance C must be periodically (about 500 times per second!) recharged, as if “refreshing” the memory. Such a fragile, leaked memory is called dynamic. Taking into account the maintenance systems, the general RAM circuit turns out to be much more complex than on figure 4, but still simpler and more economical than on flip-flops. In dynamic RAM it is possible to reduce the power consumption to 2.5 transistors per bit. Today, diac circuits reach capacities of 1 Mbps on a 7 x 9 mm silicon die. This is a record for building density.

Leaving the RAM area, one can state that its architecture, although rational, is still very monotonous. This is often characteristic of new residential areas and in our cities. Note that no weight area of ​​the RAM is provided to the microcomputer client; Some pages, sometimes up to 50%, are used by the Processor itself to save the results of intermediate calculations, store the maintenance program, etc.

City for farming

Let's now move to the ROM area, it was located nearby. There are many common elements in the structure of RAM and ROM, for example, matrix organization of memory, input logical and buffer devices, etc. However, there are also differences. Well, first of all, permanent residents of our city are accommodated here. They are so constant that they never leave their residential area. Anyone who has read the novella “Monday Begins on Saturday” by A. and V. Strugatsky may remember that its hero, enthusiastic researchers at the Institute of Witchcraft and Wizardry (NIICHAVO), created their own personal duplicate copies, or “doubles,” to perform various routine tasks. Commands located in ROM, without any interaction and without the harm of repeatedly creating “duplicates” at the request of the Processor. Once on the data bus, the “takes” are no different from other command signals. Country matrix

*) In computing, the term “cell” is used for a trigger chain capable of storing 1 byte = 8 bits or one machine word. We are simplifying the RAM structure somewhat for the first acquaintance.

*) There are no special capacitors C in the microcircuit. We previously indicated («Kvant», 1986, No. 2) that the transistor in SVIS is often used as a diode or capacitor.
