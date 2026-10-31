---
id: 1973-11-guter-polunov-mashina-upravlyaet-0bdb0c50
issue: kvant_1973_11
year: 1973
number: "11"
title: The machine controls
authors:
  - Гутер Р. С.
  - Полунов Ю. Л.
rubric: osnovnye-stati
page_first: 13
page_last: 18
page_labels: 11, 12, 14, 15, 16
tag: 59RQ
lang: en
source: kvant_digital
extraction: vision
content_sha256: 9536d078e74cd319f63d6c06b019ef4783377085dfdf57fb4433b1cd7ed551bb
prompt_sha256: draft-1
translated_from: content/ru/1973/11/articles/03_guter-polunov-mashina-upravlyaet-0bdb0c50.md
source_content_sha256: 4c4629622f00c23ba102d2fdee913be1bc0a9beaab68fe4f8d1f67c65ceff95e
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 11⟧

The machine controls
R. S. Guter,
Yu. L. Polunov

Recently, the staff of the American magazine Computer and Automation calculated that out of six hundred “professions” of electronic computers, about fifty account for the so-called “control” machines - machines that manage fast-moving technical and experimental processes. We want to talk here about how machines control and why calculations were needed to do this.

How does a person control

An automatic car is speeding along the highway. The driver controls the movement of cars. When overtaking passing traffic and passing oncoming cars, the driver continuously monitors the road. He outlines the trajectory and speed of movement and changes the position of the pedals and steering wheel of the car so that the actual trajectory and speed differ as little as possible from the intended ones. Brain - hands - machine - eyes - brain - this is the automation control system.

In the electronic furnace there are molds for castings. The temperature in the oven should not exceed certain limits. The worker monitors the needle of a device connected to an electronic thermometer inside the oven. If the arrow approaches the specified limits, then the worker increases or decreases the current in the heating element, moving the rheostat slider so that the arrow returns to the desired position.

Borscht is being cooked on the stove. The cook tastes the borscht and adds certain

⟦folio 12⟧

food or changes the strength of the fire until the contents of the pan come in accordance with his ideas about a ready-made and tasty dish. It is easy to see that the principles of his actions are the same as those of the driver and the worker at the drying oven. The difference in actions is determined only by the peculiarities of technological processes.

Control algorithms

All our examples involved a person. However, it can be excluded from the control system. If the law for controlling any object is precisely formed in the form of a sequence of action rules (algorithm), then, in principle, it is possible to create a device and compose a program that implements this algorithm without human intervention. Such systems are usually called automatic control systems.

For example, to control a real furnace, it is enough to send the output signal of an electric thermometer to the motor control device connected to the rheostat motor. The control algorithm is clear: if the temperature in the furnace begins to fall, then the motor must turn in one direction, increasing the current in the furnace; if the temperature rises, then the motor must reduce the current and turn in the opposite direction.

Abstracting from the physical system of processes occurring in the control system, we can identify the blocks common to these systems: the control object, the control system, executive bodies and organs (devices) that transmit information about the goals and results of control to the control system. A graphical representation of such a system (block diagram) is shown in figure 1. We advise the reader to determine what exactly plays the role of another block in each of the examples given.

Closed-loop control systems described

or feedback systems. The regulation of processes in living organisms, technical devices, economic and social systems is based on the principle of feedback—the transfer of information from the output of a system to its input.

To understand the role of feedback, you need to get acquainted with open-loop systems in which such communication is absent. An example would be a soda fountain.

How does this machine work? The coin dropped in the answer is checked by weight and, falling further, closes the electrical circuit. When its electromagnet is turned on, it receives a lever that opens the valve (faucet) for a time sufficient to fill a glass of water.

There are times when the machine “does not top up”. He does this, of course, not out of “malicious intent”; simply, during operation, the properties of the electromagnet or lever have changed, and he opens the valve for a shorter period of time.

Let's try to design the machine so that feedback occurs. To do this, you need to have a device that changes the level of liquid in the glass. The output signal of this device must be fed into the electromagnet winding so that the valve remains open until the “glass full” signal arrives. Such a system will be more flexible and will not be afraid of changes.

Closed-loop automatic control systems have appeared since

⟦folio 14⟧

Feedback control

Closed-loop control systems used by computers are most widely used in the chemical and metallurgical industries, in thermal and nuclear energy. In closed control systems, the impact is generated taking into account information about the progress of the process. Devices that collect this information are called sensors.

The output signal of such sensors, as a rule, is a non-octoral physical quantity that is continuous. In order for a digital computer to accept sensor information, a continuous (often referred to as analog) quantity must be converted into digital form in a binary number system. Therefore, an important component of the machine control is the analog-to-digital converter.

The input quantity of an analog-to-digital converter is voltage or current, angular or linear movement or position of a device. A significant analog quantity is transformed from its original form into another, more convenient for conversion, for example, pressure is converted into displacement.

Let us consider as an example one of the possible schemes for converting voltage into the number of pulses. Let voltage $U_{bx}$ (Fig. 2, a) be applied at the input of the converter. The converter operates discretely, that is, it changes the voltage at certain time intervals (cycles), during which the input voltage can be considered approximately constant.

The beginning of each clock cycle is offset by a maximum pulse, which is emitted by the maximum pulse generator (Fig. 2, b). Such a pulse starts the counting pulse generator (Fig. 2, s), the sawtooth voltage generator (Fig. 2, e) and turns on the counter.

The sawtooth voltage and the input voltage $U_{bx}$ are fed to two inputs of the coincidence circuit, which at the moment of their coincidence (Fig. 2, d) produces a pulse (Fig. 2, e), which locks the counter. Number of counting names

Fig. 2.

pulses (Fig. 2, g) entering the counter will be proportional to the time interval between the clock and locking pulses, and this interval is proportional to the value of the input voltage $U_{bx}$.

Thus, in this analog-to-digital converter the following conversion circuit is carried out: analog value $\rightarrow$ voltage $\rightarrow$ time interval $\rightarrow$ digital form. A block diagram of such a conversion is shown in figure 3.

In addition to converting analogs to digital form, the reverse conversion is also required. The point is that the computer

⟦folio 15⟧

The bus produces a signal in digital form. If the executive element of the automatic control system is a stepper digitizer that controls a digital signal, then no additional transformations are required. If a common digitizer (damper, regulator) is used as an executive element, requiring a continuous input signal, then a digital-to-analog converter is needed. Such transformations are based on the same principles as the similar objects discussed above.

The block diagram of a closed-loop technical process control system using an electronic computer is shown in figure 4. It can be seen that, in addition to the computer, the control system contains quite a lot of additional equipment necessary for connecting the machines with the controlled object.

First of all, sensors of quantities characterizing the controlled process are needed. These include:

a) process input parameters (pressure, temperature, raw material consumption, thermal and electrical energy consumption, etc.). These quantities can be controllable (if we can change them using external signals) or uncontrollable (if we cannot change them);

b) disturbances that violate the normal course of processes (fluctuations in ambient temperature, mains voltage, etc.);

b) process output parameters (fluctuations and quality of the main and by-products, their temperature, composition, etc.).

All information must be converted into digital form and entered into a computer. In addition to information, it is necessary to enter into the machine a control algorithm translated into machine language (control program). It is thanks to the program that the machine can calculate what control actions are needed in a given situation so that the controlled process proceeds in the most beneficial way.

How the algorithm is compiled

Drawing up a control algorithm for each system, or, more precisely, for each controlled process, is a complex task. Very often it is not possible to obtain a strict mathematical description of complex processes and express the dependencies between the characteristics of their magnitude in a similar form. Then it comes to resorting to experimental methods of establishing such dependencies.

The information and descriptions obtained are used to construct a mathematical model of the object, which is a complex task. In addition, it is also necessary to have an exact criterion for the optimal process that determines the control goal *). More often

*) How important a clear formulation of management goals is, the reader can judge from the story of the American science fiction writer P. Shackle, Guardian Bird, M., “Young Guard”, 1968 (Science Fiction Library. Vol. 16).

⟦folio 16⟧

The goal of management is to achieve maximum economic efficiency. However, sometimes it comes down to other criteria, such as maximum productivity, minimum costs or the shortest possible time.

In a number of control cases, the algorithm first succeeds in “self-learning ability.” This means that the program will be able to analyze the results of control actions and the compliance of the selected mathematical model of the process of its implementation and make the required adjustments to the mathematical model.

"START" system
All readers have probably seen an automatic traffic light - the simplest open-loop system. In it, the lights are switched in a certain order at certain intervals without taking into account the actual situation at the intersection. In the summer of 1972, on the Serpukhovskaya Zastava square in Moscow (with a rather complex traffic pattern, see Fig. 5) an automatic traffic flow control system was turned on. From sensors located under the passages of the streets facing the square, the system receives information about the number of cars moving at each possible position of the traffic lights, the computer calculates the number of moving and idle machines and determines the average downtime per car, after which it selects the position of the traffic lights so that the downtime is minimal.

In 1974, the “START” automatic traffic flow control system was experimentally introduced in Moscow, which would “manage” all traffic lights inside the capital’s Garden Ring. For each internal node of the circuit, it will be possible to calculate the number of cars approaching this node in different directions.

The control algorithm for such a system includes calculating the average downtime of machines; criterion for optimal process flow) is the minimum of this downtime.
