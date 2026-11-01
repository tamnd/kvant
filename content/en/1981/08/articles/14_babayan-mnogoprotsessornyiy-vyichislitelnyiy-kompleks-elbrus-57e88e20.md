---
id: 1981-8-babayan-mnogoprotsessornyiy-vyichislitelnyiy-kompleks-elbrus-57e88e20
issue: kvant_1981_8
year: 1981
number: "8"
title: Multiprocessor computing complex "Elbrus"
authors:
  - Бабаян Б. А.
rubric: raznoe
rubric_sub: Разное
page_first: 56
page_last: 59
page_labels: 54, 55, 57
tag: YFZ2
lang: en
source: kvant_digital
extraction: vision
content_sha256: 3f471574cd3af6b2a3682be5c7488ac89916d97840a56d3a52fcaf79315a2187
prompt_sha256: draft-1
translated_from: content/ru/1981/08/articles/14_babayan-mnogoprotsessornyiy-vyichislitelnyiy-kompleks-elbrus-57e88e20.md
source_content_sha256: 43ee56a673f88818e339fea86e53a0a2c662a4bd0a4d2ee544150efa029ba8b1
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 54⟧

The Art of Programming

B. Babayan

Multiprocessor computing complex "Elbrus"

This article talks about the new Soviet computer. Like any computer, it has a processor («Kvant», 1980, No. 5) and memory («Kvant», 1980, No. 4). Or rather, even a whole black storage device: very fast-acting, but relatively small in memory capacity, located in the processor itself; main memory; slow “external memory”. Information from external memory enters main memory using special input/output processes.

Modular system

So now all devices are computers. The difference between Elbrus is that it is divided into relatively loosely interconnected parts (devices), called modules. Examples of models: processor, main memory, input/output device, etc. The models are characterized by a small number of external connections and good interchangeability. As a rule, modules are connected to each other according to the “each to each” principle, that is, each processor model is connected to each main memory model, etc.

Such an organization has many advantages. Firstly, it uses a different number of single-spin models, you can get different computers with different performance; increasing the number of mo-

⟦folio 55⟧

blows, you can gradually increase the power of the machine. Secondly, if any model in the car breaks down, this will only lead to a temporary decrease in its speed, since the other models continue to work. Thirdly, by collecting many similar models into one system, we can get a machine that calculates significantly faster than in the usual case.

Thus, the Elbrus system has a very variable composition. If proper precautions were not taken, programs would have to be rewritten every time the state changed. This would be the case, for example, if the program contained the address of a memory cell from a model that had broken down. To prevent this from happening, in Elbrus, in addition to the implementation of regular memory, there is virtual, or mathematical, memory. This is no longer a realizable device located in a certain place on the machine, but an astractive concept consisting of a set of numbers indicating the address of “mathematical cells” (for Elbrus these are numbers from 0 to $2^{33} \approx 4 \cdot 10^9$). It is these addresses that are used when the program runs, and their translation into the addresses of real cells is done automatically, using special tables. Thus, if the composition of the machine changes, then the faces of these tables change, but the programs remain unchanged.

The amount of virtual memory is significantly larger than the amount of RAM in the actual machine. The initial tables are transferred to store currently unnecessary information in external memory, noting this fact in the tables.

For the convenience of the program

An even more important black "Elbrus" is its attention to programming problems. The developers tried to make this machine convenient for the program. And the problems in the field of programming are now very serious. At the end of the 60s, they even began to talk about a programming crisis.

The fact is that over the 30-odd years of the existence of computer technology, the methods of producing computers have advanced even in time, but the production of a program (programming) remains mainly manual labor. There are so many programs to be developed that it seems that the day is not far off when almost every educated person will program. In addition, there are many useful algorithms that could be executed by modern computers, but which are simply impossible to program due to the large size and complexity of the corresponding programs.

One of the well-known methods that facilitate programming is the so-called high-level languages ​​(Algol, Pascal, Rapier, etc.). High-level languages ​​are essentially abstract machines conceived by programmers and implemented on real machines using a program. Special programs called translators translate programs from high-level languages ​​into machine languages.

In Elbrus, a lot has been done to make it easy and quick to translate programs from high-level languages ​​and to get programs to work quickly and take up little memory space. This, for example, is the addressless command system, described in the article “Three-address, uniaddress and ... addressless machines” («Kvant», 1981, No. 4).

Teri

It is very important, from the point of view of the program, to pay attention to programming problems. The developers tried to make this machine convenient for the program. And problems in the field of programming are still ongoing, despite the recent developments in the field of programming.

⟦folio 57⟧

Elbrus memory protection is based on the use of tags.

Address information containing a description of specific memory areas needed for a given task, and equipped with specialists, is called `deckrintopom`.

If a task has only decryptors that describe its own areas, then in no way can one add to other areas while solving this problem, that is, violate the protection. In Elbrus, security is carried out not only between tasks, but also between individual parts of the same task. Such parts are called `процедурами`.

It is very convenient to debug processes independently of each other, and then combine them into one large program. This programming method, supported in Elbrus in hardware, thanks initially to ready-made procedures in the machine, is often called `modульным`. It also makes programming very easy.

On Elbrus, all programs are written only in high-level languages, including the most complex program systems, such as the operating system and transports. Previously, these programs were usually written in practical machine language.

Still fast

Convenience of programming is the most important aspect of the Elbrus system,

*) In terms of speed, the ten-processor Elbrus-2 exceeds one of the most powerful modern domestic machines BESM-6 by about 100 times.
