---
id: 1980-4-pervin-saltovskiy-pamyat-evm-366e2bb6
issue: kvant_1980_4
year: 1980
number: "4"
title: Computer memory
authors:
  - Первин Ю. А.
  - Салтовский А. Н.
rubric: raznoe
rubric_sub: Разное
page_first: 56
page_last: 59
page_labels: 54-57
tag: DBAP
lang: en
source: kvant_digital
extraction: vision
content_sha256: 05524112b6175c3594e6e0f94f73a1cabf0168d9f90db2a86edb5d6df7a90a0e
prompt_sha256: draft-1
translated_from: content/ru/1980/04/articles/18_pervin-saltovskiy-pamyat-evm-366e2bb6.md
source_content_sha256: 2021eeadb1a0a27de5989c557511860604d483718e131fce14a6a18388dc5575
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 54⟧

Computer memory

A modern electronic computer is a miniature factory. The word “factory” means, of course, not only compilations of industrial buildings that are filled with machines and equipment; A factory is also a technological process (a described list of rules for processing a product, instructions, moods, drawings), the implementation of which leads to the miraculous transformation of raw materials into finished products.

In a computer, the raw materials, semi-finished products at all stages of the technical process, as well as finished products are information, that is, information recorded in symbolic form about objects, phenomena and processes of the surrounding world.

If a computer is a plant for processing information, then the warehouse in which raw materials prepared for processing, workpieces that have undergone part of the technical process, as well as products ready for shipment are stored is a memory or storage device (storage device).

Thus, memory or storage is a technical device designed to store information. Of course, this device must freely output and record information. The speed, or rather the speed, of memory is expressed by the names and types of storage devices - ultra-random access memory, random access memory, external memory.

The faster the memory works, the more expensive it is on the road. In mainframe computers, which use memory of various speeds, the relationship between the central part of the computer and various types of memory is built hierarchically, so that access to cheaper and more capacious external memory is reminiscent of the negotiations between the king and the queen in “The Ballad of the Royal Sandwich.”

Coding

The physical storage medium is a scene (in a computer - an electronic signal). The transformation of information from one form to another is carried out using coding. Our knowledge about the world around us is, to a certain extent, determined by our ability to perceive and analyze information, that is, we will be able to correctly interpret the code. The coding mechanism may be much more complex than the one solved by Sherlock Holmes in The Dancing Men. For example, geneticists believe that the chromosomes of an embryonic cell contain a complete “blueprint” of the future person.

The creators of the first computers had to decide how best to encode the information being processed and stored in order to provide

— simplicity and reliability;
— the fastest;
— minimum equipment costs (cost-effectiveness).

All these requirements are met much more fully by the double coding system, where to display information it uses numerical combinations consisting of only two digits - 0 and 1. You can read more about this in the book by F. Bauer and G. Gooz “Informat” (M., “Mir”, 1976).

From the point of view of convenience of communication with a computer, it would be most reasonable to use the traditional ten-finger number system (by the way, it is instilled in us only because it is ten fingers

⟦folio 55⟧

served ancient man as the first portable memory devices). But the technical requirements listed above were decisive when choosing a coordination system - we had to come to terms with the fact that from the point of view of an information processing machine, the most reasonable is not the decimal, but the double number system.

The material remembers
The material with which a person organizes the recording and storage of information was very diverse - stones, fingers and sticks, and later - paper and pen. All these materials have various advantages, including, for example, clarity, but the common main disadvantage of such storage systems remained very low performance: try counting a hundred stones several times or finding the necessary material in a thick book.

Modern technology has materials that make it possible to produce compact and high-speed memory devices that allow storing large amounts of information. A number of materials and simple devices have the remarkable property of maintaining one of two stable states for a relatively long time: ferrite (see below) retains its magnetization even after the current in the magnetization coil is turned off; the capacitor remains charged after the voltage supplied to it is turned off; The electromechanical solution keeps its contacts closed as long as current flows through the solenoid coil.

Ferrite
The ability of materials to “remember” the results of previous experience is based on a remarkable property called “hysteresis.”
Ferrite, an artificial material with exceptionally bright magnetic properties, is quite common in computers as a storage material that uses the phenomenon of hysteresis. figure 1 shows the dependence of the direction and magnitude of the magnetic flux in ferrite on the magnitude and direction of the current in the magnetization coil. This dependence has a stepwise (rectangular) character.

Ring-shaped ferrites are usually used in memory: the magnetic flux closed in a ferrite ring best preserves the energy spent on magnetization reversal (Fig. 2).

When storing information on ferrites, it is agreed that

Fig. 1. Primogular petlehysteria is a characteristic of ferrites: materials with particularly bright magnetic properties.

Fig. 2. Ferrite bead is the most common element of magnetic storage devices.

⟦folio 56⟧

tso stores “1” if the value of the magnetic flux inside the kolyz corresponds to point $A_1$ (Fig. 1), and “0” if the value of the magnetic flux corresponding to point $A_0$.

To write information into a ferrite core, it is necessary to change the direction and magnitude of the magnetic flux, for which an electric current of the corresponding magnitude and direction is passed through the magnetization coil. As can be seen from the graph, a sharp change in the value of the magnetic flux will occur at the moment when the magnitude of the current in the coil reaches a certain critical value $+I_K$ (Fig. 1). You can find out what exactly the ferrite core stores by reversing the magnetization of the core in a certain direction, for example, to point $A_0$. It is known from a physics course that a change in magnetic flux in a closed loop causes the appearance of an emf. It is by the magnitude of the EMF that you can find out whether the ferrite core was “0” or “1”. In fact, if the ring stored “one” (the value of the magnetic flux is $A_1$), and magnetization reversal (during reading) is performed to point $A_0$ (for this, a current is passed through the coil - $I_K$), a rapid change in the magnitude and direction of the magnetic flux will occur in the ring. This change in magnetic flux will result in the appearance of an EMF in a closed readout loop. If the coluto stored “zero”, and according to the reading conditions, magnetization reversal occurs with current - $I_K$, then a change in flux from point $N$ to point $A_0$ will not destroy the stored “zero”. A change in the magnetic flux in the ring from point $N$ to $A_0$ results in an equally insignificant EMF value.

So, we got acquainted with the element of magnetic memory - ferrite, which can remember only one of two possible states, denoted zero and one. Knowledge about the state of an object, which can only be in one of two positions, constitutes the smallest piece of information - one bit*! Thus, a physical ferrite represents 1 bit, i.e. one double digit.

Units of information

To measure information, information violation, violation - byte (8 bits), kilobyte (2$^{10}$ bytes), abbreviated as KB, and merabyte (2$^{20}$ bytes). These are “out-of-machine” units.

A standard piece of information that is issued or received

*) The word “bit” comes from the English words “Vpagu digiT” (“binary digit”).

COMPUTER is a machine word. The “length” of a machine word (that is, the number of double digits) is usually fixed in each computer: in Minsk-32 a machine word consists of 37 bits, and in VESM-6 it consists of 48 bits.

A machine word is a unit of memory measurement that is often used by a programmer. For the machine itself, for the operation of its devices, a piece of information called a cell turns out to be more important. However, in many machines the concepts of a machine word and a cell turn out to be the same. But not in all of them. For example, in EC series machines, a cell contains one byte, so that one 32-bit EC computer word is located in four rows of cells.

Cell addresses

The most important characteristic of a cell is its number in the set of all cells. This number is called the cell address. By address in memory, a cell or a machine word starting in this cell is found.

The address plays a major role in retrieving information in memory. When the address of a cell is known, its contents are added when determining memory devices, as simple as finding a given cell in the game “Battleship” or seeing a piece on a specified chess field. This type of memory processing (usually done on ferrites) is called direct (or random) access memory.

An address plays a similar role in determining where in memory to store information.

Performance

Physical processes occurring in memory at the time of recording or reading information require a certain time. It is this time of determination of memory, and often the quick determination of the computer as a whole. The search time for a cell in the primary access memory (made on ferrite cores) is 2-5 microseconds (1 microsecond).

⟦folio 57⟧

yes = 10⁻⁶ seconds), and in extra-RAM it is even less - 10-100 nanoseconds (1 nanosecond = 10⁻⁹ seconds).

Memory based on ferrite pins is currently not the fastest. The success of semiconductor interral technology allows the widespread use of fundamentally new materials and devices in modern computers. While the cost of such devices is high, new memory elements are used to create ultra-random access memory - small in volume, but very high-speed storage devices, in which, as a rule, information is recorded, most often used in solving a given problem on a computer. A separate article in one of the following issues «Kvant» will be devoted to the story about interral circuits used in computer memory.

Tape recorder

The tape recorder has good characteristics in terms of memory capacity and low cost. You are probably familiar with the “home” relative of this type of memory - the household tape recorder. True, unlike its everyday counterpart, a tape recorder used in a computer is more solid not only in appearance: a high-quality tape allows you to record information with a very high density (for example, 64 bits per millimeter). If you take into account that the length of tape in tape recorders reaches 750 meters, then you can understand how important such external memory is to him.

Information is located on the tape sequentially, and each section of a fixed length, called a zone, has its own number. A zone usually consists of a large number (hundreds and thousands) of cells. When storing on tape, the individual cells and their address are ignored; a portion of processed information becomes a zone; You can distinguish cells from one another by the relative number, counted from the beginning of the zone, after the zone is copied from the tape into RAM. The size of the zone, generally speaking, is arbitrary (within certain limits), but is fixed for the duration of solving one or several problems. The division of a magnetic tape into zones, called marking, is performed programmatically not during the calculation, but before them: this, in essence, consists of preliminary preparation of the physical storage medium - the tape - for participation in the computational procedure.

When marking a magnetic tape, zone numbers are automatically placed at the beginning of each tape. In the future, this allows you to write information to a specific zone and read it from there when it is needed. When reading information, the tape recorder is assigned a zone number, then it begins to move the tape in the desired direction. The search time for information takes ten seconds, and sometimes up to minutes. The fact is that to search for the desired memory cell on the tape, you must first view all the presented zones, and then, in the desired zone called into RAM, view sequentially all the cells preceding the desired one. This type of memory is called sequential access memory.

Hierarchy of storage devices

Computers include devices that are intermediate in speed between ultra-random and random access memory - direct access devices, on the one hand, and tape recorders - sequential access memory, on the other hand. These are, first of all, manitina discs and manitino drums. Both of these devices are used on ferromagnetic coatings due to the fact that a change in the magnitude or direction of the current in the magnetization coil causes a change in the magnetic field, which forms a “fingerprint” of information on the magnetic coating;
