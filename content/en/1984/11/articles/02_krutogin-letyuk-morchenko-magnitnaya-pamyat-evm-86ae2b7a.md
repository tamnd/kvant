---
id: 1984-11-krutogin-letyuk-morchenko-magnitnaya-pamyat-evm-86ae2b7a
issue: kvant_1984_11
year: 1984
number: "11"
title: Magnetic computer memory
authors:
  - Крутогин Д. Г.
  - Летюк Л. М.
  - Морченко А. Т.
rubric: osnovnye-stati
page_first: 4
page_last: 10
page_labels: 2, 4, 5, 6, 7, 8
tag: 1QF8
lang: en
source: kvant_digital
extraction: vision
content_sha256: 86350529437254078471f791ea23849ddcaa684e9b9f4bf7edf677e007e29825
prompt_sha256: draft-1
translated_from: content/ru/1984/11/articles/02_krutogin-letyuk-morchenko-magnitnaya-pamyat-evm-86ae2b7a.md
source_content_sha256: 0ea621d24610b5858bf8599fb22786889399cf568b72a954e0b3398c8eb03ace
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 2⟧

Magnetic computer memory

Candidate of Technical Sciences D. G. KRUTOGIN, Doctor of Technical Sciences L. M. LETYUK, A. T. MORCHENKO

Our time is the beginning of the computer era. Having originated about forty years ago, the tribe of computers quickly gained strength and widely penetrated into a wide variety of areas of human activity, from cash registers to calculations of space routes. In recent years, microelectronics has made it possible to reduce the size of computers so dramatically and increase their reliability that the view of computers as exotic Russian ones has begun to fade into the realm of legend.

The purpose and necessity of using computers is to free the human brain from routine mental operations. Computers replace the brain in some ways, but their methods of operation exist but are different. The peculiarity of the structure and functioning of modern computers is that the most complex problems in them are divided into a sequence of simple arithmetic operations. But the speed of execution is enormous - computer arithmetic devices, called processors, perform millions of operations per second. Both intermediate and final results of calculations need to be remembered for some time, just as we fill out the formula “in our minds” when multiplying in a column. Therefore, any computer, both the largest one and a microcalculator, has its own memory, or more precisely, filling devices.

The filling devices (3U) store everything that the computer needs for calculations. The more a computer must know and remember, the greater the volume of its 3U, and the greater the mass of machines and its price. Memory makes up the majority of the volume and cost of a computer (up to 60-80%). In addition, memory is more like a large library, in which the time for searching and delivering the required book sometimes exceeds the time for using it.

⟦folio 4⟧

What is really needed is memory persistence, that is, the ability to quickly replace information (rewrite). Finally, if these requirements are met, it is good to have systems that do not require large amounts of energy to control, are highly reliable, etc.

Generally speaking, storage devices can be built on various principles: mechanical, acoustic, electronic, magnetic, optical. But... Mechanical memory devices do not surprise us in terms of speed, although the inventor of office accounts - the simplest storage device - we must express our gratitude for the first technical implementation of the terrible principle of storing information, the creation of a reactive medium for recording, etc. Gramophone records have a fairly high capacity, reliability, and storage space. But records are not very convenient for computer storage: they do not have the required speed and the memory capacity is very bad.

The magnetic method of recording electrical signals has long been known. It is based on the property of some materials to “remember” the magnetic field in which they have been. Probably many of you have had to magnetize nails, needles, scissors, etc., by bringing them to a permanent magnet. And you may have noticed that after this the scissors themselves become fine iron; magnetized clay can serve as a compass needle; and nails, if taken away from a magnet, quickly lose their magnetic properties. Not all magnetic materials have the ability to “remember” a magnetic field; but one of them, the mineral magnetite, which is a complex iron oxide, has been known to people for thousands of years and served as the first material for compasses.

Small silt-like particles are especially well magnetized - once they are in a magnetic field, they can fill both its induction and its direction. If such a magnetized part is designed mismo of a closed conductive coil, an induced current will arise in it.

The work of magnetic flux is based on this property of magnetic materials. The carrier of magnetic particles is a plastic tape on which needle-shaped particles of magnetic powder are fixed in a thin layer of varnish (the length of the particles is about a micron, the diameter is about a tenth of a micron). Instead of a conductive coil, a small electromagnet is used - the recording and playback head: at our request, it either magnetizes the powder particles (recording), or itself magnetizes the mismo passage field of the magnetized particle, and a current arises in its winding, repeating the shape of the previously recorded signal (playback).

The tape recorder was born almost simultaneously with the telephone - about a hundred years ago. But it was possible to ensure good recording quality only in the forties of our century.

The tape recorder immediately found a place for itself in computers. Each particle of powder can hold 1 bit of information: a magnetized particle can be assigned the value 1, a non-magnetized particle - 0. It is clear that the capacity and speed of such a memory device depends on the length of the tape and the speed of transmission.

Remaking the tape recorder allows for faster recording. Instead of magnetic tape, signals are recorded on a disk coated with magnetic varnish. The disk, whose diameter is about 0.5 m, rotates at a speed of 100 revolutions per second. The read-write head and the disk surface do not stick together (otherwise, at such speeds, they would become very hot as a result of friction and would quickly wear out). The head hovers above the disk at a distance of only 2-5 microns. For high-quality signal transmission, it is important that this distance be constant, so the disk should not have noticeable binaries. A disk tape recorder loves clean air - getting a three-micron speck of dust into a two-micron gap, which you can’t even see with the eye, causes consequences equivalent in significance to getting a large piece of paper under an automatically racing car.

Using tape recorder disks, you can satisfy the capacity and speed needs of buffer storage devices.

Ferrite ring - a reminder element

In random access memory, the main memory elements have long been

⟦folio 5⟧

mother rings. Such rings, made of an iron-on-silver alloy or ferrites (non-metallic magnetic materials), have the property of being in a state of residual magnetization for a long time. In this case, the induction of the magnetic field in the materials of the ring coincides in direction with the induction of the external field in which the ring was magnetized, and is close in magnitude to it.

Let's imagine that we magnetized a ring by passing a current pulse through the magnetized wire, and passed a current pulse in the opposite direction through the winding of the second ring (figure 1, a). Then the induction vectors of the magnetic fields generated in the rings during magnetization will be directed in opposite directions. One state has a value of 1, and the other has a value of 0. Now let’s apply current pulses of equal polarity to both rings. However (the upper one on figure 1, b) will be remagnetized - in a short time the direction of the magnetic field induction in the ring will change to the opposite. A change in induction means a change in magnetic flux, arbitrarily any section of the ring. Consequently, in the secondary winding magnetized to the ring - the read winding - during magnetization reversal, an induced emf will arise. If the secondary winding is closed, a current pulse will flow through it - a pulse of “read” units. Thus, we read the number written in the first ring and erased it, that is, we destroyed the information. What about the second ring? It does not remagnetize, since it was already previously magnetized with a given direction of the induction vector. The absence of an impulse from the second ring is also information, but about the number 0. Thus, each ring is an elementary filling of the device with a bone of 1 bit.

Magnetic memory on ring cores works quite quickly - the time for magnetization reversal of the wheels is a fraction of microseconds. Memory capacity depends on the number of wheels. For 1 metabit RAM, at least a million wheels are required, and in some cases more than two million. It is possible to track such a number of wheels, these processes are automated. Next, you need to test each wheel, because if one of a million wheels is “lying,” then all the systems are worthless. Machines were created that tested up to 5 thousand wheels per hour, but this is not the main difficulty.

Magnetic loops must first be written and read windings, and then organized in some system in order to be able to determine which particular loop corresponds to a given bit of information. A million wheels with two windings equal two million wires and four million contacts. The matrix system for constructing memory helps to get rid of this abundance. Let's connect a dozen wheels to one wire, which is called numerical (figure 2). Now all the rings can be magnetized with one pulse, and 0 will be written in all the rings. We will pass a wire through each ring perpendicular to the numerical one; These ten wires are ground discharge wires. The design we received is called a number line. To write the double number 1110001101 in it (what kind of number is this?

⟦folio 6⟧

in the decimal system?), we send along the number wire a pulse equal in magnitude to half the magnetization reversal value of the current, and another similar pulse simultaneously went to the discharge wires colcite 1, 2, 3, 7, 8 and 10. Where the pulses add up, the rings will remagnetize; it does not do this in rings 4, 5, 6 and 9. You can “count” the entire number by passing a large “negative” (magnetization reversal) pulse along the number wire. But in order to receive and generate a read signal, you need one more wire in each digit - a read winding. So, for ten colcites on the number line we have twenty-one wires. Ten number lines, that is, ten ten-row numbers, require ten number wires. (bit and read will be the same) - total - 31 wires, etc. The same, of course, is a lot, but still, to create a metabit 3U, you can limit yourself to a few hundred wires. Something else is more difficult.

Let the ring (by no means the smallest) have an outer diameter of 0.6 mm and an inner diameter of 0.35 mm. Now through each colcito it is necessary to stretch at least three wires with a diameter of 0.05 mm in different directions and repeat this operation more than a million times. This kind of work is akin to sewing with beads (it’s called stitching). Unfortunately, it was not possible to really automate it, and manual production was more difficult and eventually replaced production and increased the cost of assembled devices.

The first samples of 3U on magnetic rings, even the necessary containers, were memory cubes in the literal sense of the word - they had a volume of about 1 m³. For obvious reasons, they are trying to reduce the capacity of storage devices. To date, it has been possible to reduce the damaged diameter of the manufactured rings to 0.25 mm. You can imagine how challenging the task of flashing them is. It would seem that the difficulties of further reducing the size of ring cores are insurmountable, and the twenty-year dominance of magnetic RAM is ending; Moreover, thanks to the successes of microelectronics, semiconductor RAMs have become more efficient than magnetic ones, that is, more compact and cheaper.

At this point, you should recap the history of magnetic recording and introduce electronic memory cells. It has long been known that from two triodes it is possible to assemble a circuit that “operates” in two modes: with one direction of current, one triode operates, and the second turns out to be locked, and with another direction of current, the triodes change roles. In one operating mode, the system can be assigned the value 0, in another - 1. Such a system is called a trigger. The very first computers had triggers (thousands of triggers) that performed the functions of RAM; But they could not withstand competition with more compact, almost non-emitting, reliable, low-energy magnetic memory.

Modern 3U semiconductor microcircuits are basically the same triggers, only reduced to micron sizes. On a 5x5 mm wafer made from a semiconductor chip, the dimensions of a 200,000-bit storage device are removed; the speed of such 3U is about 10⁻⁸ s. Objectively, we note one very significant drawback of electronic RAM: turning off the power erases all accumulated

⟦folio 7⟧

new information. In many cases this disadvantage is tolerable, but sometimes, for example in military or space technology, it becomes a serious obstacle.

Running magnetic bubbles

About fifteen years ago, the first experimental 3U models appeared in an integrated design, combining the advantages of magnetic recording with the efficiency of microelectronic technology. These devices, using magnetic domains, are called 3U domains. Domains are malleable regions (volumes) of a magnetic substance (for example, iron), each of which is spontaneously completely magnetized. The induction vectors of magnetic fields separated by domains in the absence of an external magnetic field are directed so that the sample as a whole is demagnetized.

The use of so-called cylindrical magnetic domains turned out to be much more promising for creating 3U domain domains. Their history should begin at the end of the 50s, when domains of a specific shape were discovered in a number of magnetic materials, filling air bubbles in a carpenter's level. Because of this, these domains are often called magnetic bubbles. However, special interest in these domains began to be shown only after an article by American physicist Andrew Bobek appeared in October 1967, in which he first pointed out the attractive prospects for using them to create a device for storing and processing information. (It is noteworthy that Bobek himself is not a specialist in the field of physics of magnetic phenomena, but works in computer technology.)

Magnetic bubbles can occur in thin plates or films of some magnetic crystals. In the initial (demagnetized) state, the domain structure of a thin layer of such crystals consists of an equal number of domains with opposite directions of magnetization - the induction vectors of magnetic fields of individual domains are redistributed over the plane of the layer and are directed in opposite directions.

figure 3, a shows the magnetic structure of the crystal in a demagnetized state, called a labyrinth domain structure (the symmock is made under a microsop). Dark and light areas are domains of different polarities. And photographs 3, 6-e were taken during the process of magnetizing the crystal with a magnetic field, the induction of which is directed in the direction observed. As the induction of the external field increases, domains with magnetization directed along the field grow, and those directed against the field, on the contrary, narrow. In some ranges of external fields, the remnants of “unfavorably” magnetized domains are contracted first into elliptical and then into circular “bubbles”. The areas of the crystal occupied by magnetic bubbles, in combination peredicular to the plane of the film or plate, have a series of “pot-bellied” cylinders. Therefore, domains are also called cylindrical. A further increase in the induction of the external field leads to a decrease in the diameter of the “bubbles”, and at some critical values ​​of the induction $B_0$ the “bubbles” collapse, or, as they say, annihilate the cylindrical magnetic domains (CMDs) by a magnetization reversal jump to the same state in which the main part of the crystal exists. If the induction of the field applied to the plate, in which there are already CMDs, is reduced, then at certain values ​​of the field the shape of the domains begins to distort - they become elliptical and then transform

⟦folio 8⟧

into ordinary stripe domains of labyrinthine structure.

So, cylindrical domains can be nucleated (generated) by exposing the sample to a pulsed magnetic field, which arises, for example, when a current pulse is passed through a turn. By passing an impulse of figurative polarity, the CMD can be destroyed. The presence or absence of a cylindrical domain magnetic plate at a given point is equivalent to 1 or 0 information at that point.

Cylindrical domains have another great property - they can be mixed around the plate. They move quite quickly, sometimes as fast as a jet aircraft, at speeds of up to 500 m/s. It is most convenient to mix the CMD with a magnetic field, the induction vector of which lies in the plane of the plate. To give their movement an organized, directional character, special magnetic corridors are formed in the plate, within which only the domains can move. The sequence of CMD movements launched into this corridor as a single whole, the distances between neighboring domains do not change during movement. Unlike magnetic tape, in this case the information sequence is bezit in a stationary magnetic environment.

If the magnetic road (corridor) is closed in a ring, the result will be an analogy with the ring of a magnetic tape or the road of a disk magnetic drive, with the only difference that in the CMD ring there are completely no moving parts, and the dimensions of the entire ring are fractions of a millimeter.

For a complete analogy, let’s place on the ring DCM track (see Fig. 4) a domain generator (it will perform the function of a recording head), an annihilator (destroyer) of the DSD (for the page of recorded information) and, finally, some kind of sensor that cancels with an electrical signal the passage of each DMD mismo. The sensor will perform the function of a magnetic flux reading head. A magnetic field, the induction vector of which rotates in the plane of the plate at high speed (100÷400 kHz), will ensure the circulation of information in the ring road. When this field is turned off, external permanent magnets maintain all domains in a stable state and in the same order. The capacity of one track can reach hundreds of kilobits; on a plate measuring 10x20 mm you can place several tens or hundreds of tracks.

The microsoptic dimensions of the CMD (up to 0.5 microns or less), their unique properties make it possible to produce devices that have greater information speed with small sizes and low energy consumption, preserving the recorded information even when the power is turned off. What is also remarkable is that almost all technologies for the production of storage devices based on digital MDs are practically ready - these are technologies of semiconductor large-interval circuits (LSI). Therefore, such 3U developed at a rapid pace, and now there are essentially high-speed microcircuits with a memory density of 10^7 bits/cm² and a capacity of up to 10^8 bits, occupying a volume of less than a liter, acceptable in price and in terms of energy consumption for management.

3U on a digital MD can find application for a device of huge size during access to information between operational 3U (on ferrite cores or semiconductor ICs) with high speed (10^-8—10^-6 s) and external 3U of larger capacity (on magnetic tapes and disks) with relatively low speed (10^-3 s). This makes it possible to increase the efficiency of modern computers, since today about 80% of computer time is spent on exchanging information between RAM and external memory. In addition, 3U on CMD is unrivaled when working in extreme conditions, for example, in on-board electrical equipment of spacecraft, in military equipment, where increased reliability is required.

(For the end see p. 18)
