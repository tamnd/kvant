---
id: 2018-11-ashkinazi-mehanika-nevidimogo-d44e4ee9
issue: kvant_2018_11
year: 2018
number: "11"
title: Mechanics of the invisible
authors:
  - Ашкинази Л. А.
rubric: osnovnye-stati
page_first: 12
page_last: 18
page_labels: 11-16
tag: RRMU
lang: en
source: kvant_digital
extraction: native
content_sha256: dbe8265fb5e1649c9574542316e0bbddbb0ead778b03b9bbc024274396529aea
prompt_sha256: draft-1
translated_from: content/ru/2018/11/articles/01_ashkinazi-mehanika-nevidimogo-d44e4ee9.md
source_content_sha256: 3cb89459c5df45d48689ab00f64db4f023a97d94d7c68a2504da00820802656d
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio none⟧

Mechanics of the invisible

L.ASHKINAZI

Obedience to laws

Everything we see around us obeys the laws of mechanics. You can easily name many examples, and, in accordance with the school physics course, these examples can be divided into several groups. Related to movement – ​​celestial bodies and vehicles; with collisions - in technology and sports; with balance – in sports, technology, construction; as well as with the strength and rigidity of things and structures. We see all this around us. But what we don’t see also behaves in accordance with the laws of mechanics - forces and mechanical stresses in the material of aircraft engine turbine blades and in a computer hard drive are described by the same formulas. You can easily estimate these voltages if you are given all the necessary (by the way, what?) parameters. But something that rotates quickly and therefore must be subject to forces that create the necessary accelerations is not all. Blood in the vessels, air in the lungs - all this moves under the influence of corresponding forces. And so do individual cells moving around inside our bodies. Moreover, bacteria have several mechanisms of movement, and they are not yet fully understood. The same article will talk about the application of mechanics in a variety of electronic devices - in Geiger counters, in mechatrons, in high-power electron tubes, in transmission electron microscopes and scanning tunneling microscopes, as well as in devices for which no name has yet been invented. Moreover, it will be said not just that the details should be

DOI: https://doi.org/10.4213/kvant20181102

⟦column⟧

durable, but about something more interesting and less obvious.

Geiger counter

You know the operating principle of this device from the textbook. In this case, it is important for us that the gas pressure inside is significantly less than atmospheric pressure, so a force acts on the walls of the meter. The walls do not interfere with neutrons and J-radiation, but if we want the device to react to E-particles with relatively low energy and to D-particles, then a window must be made somewhere that will let them through, and it must be thin. Let's try to estimate the possible thickness of such a window. If the atmospheric pressure is p and the diameter of the window is d, then the force acting on the window is $p S d^{2} 4$. Let us take the thickness of the window to be equal to h and assume that the force falls on the maximum cross-section of the window material, equal to S dh. Then it turns out that the stress in the material is pd 4 h, and the minimum permissible thickness value is h pd 4 V, where V is the maximum permissible mechanical stress in the window material. Assuming p = 0.1 MPa, d = 1 cm, V = 0.3 GPa, we find h = 1 µm. The strength here is taken from beryllium and mica, from which windows are often made. It is possible to make a window 1 micron thick, but it will work “to the limit” and the reliability of the device will become unacceptably low. Therefore, the window is made several microns thick. Photos 1 and 2 show two Geiger counters - one with a beryllium window and one with a mica window. Since mica is transparent, a button is placed on the window to make the presence of the window visible. In this case, the mechanical properties of the window material directly determine the capabilities of the device. The stronger the window material, the more it can

⟦folio 11⟧

MECHANICS

INVISIBLE

Window for energy

Photo 1. Geiger counter with beryllium window

⟦column⟧

Electron-vacuum devices that amplify or generate electromagnetic waves have a vacuum inside them so that electrons can move freely. And there is an atmosphere outside. This means that we again need a window that will withstand the pressure difference and transmit an electromagnetic wave. In this case, the problem is alleviated by the fact that in a good dielectric, waves with a wavelength of the order of a centimeter or more (and this is all communications, television, radar) are weakly attenuated, so the window can be thicker. However, reflection occurs at the dielectric boundary - part of the energy is returned to the device. Once upon a time, mica was used as a material for “energy output” (photo 3), now

Photo 3. Electron-vacuum device with a mica window

Photo 2. A Geiger counter with a mica window should be larger - this increases the sensitivity of the device, or thinner - this expands the energy range of detected particles towards lower energies. Because the lower the energy, the smaller the depth of penetration of the particle into the material. We will soon encounter this problem – in an electron microscope. For now, let's return to the windows.

this is usually ceramic (photo 4). A ceramic shape elongated along the waveguide (top object in photo 4) is used to reduce the reflection of the electromagnetic wave. By the way, about the fact that “there is an atmosphere outside.” When flights into space began, some breathed a sigh of relief - the problems with creating a vacuum in electronic devices and extracting energy were solved! But no: it turned out that

⟦folio 12⟧

KVANT 2018/№11

Photo 4. Electron-vacuum device with a ceramic window, the vacuum in near space is much worse than what should be in an electronic device (from $10^{7}$ to $10^{15}$ atm), and the device still needs a cylinder. It’s not worth talking about the Moon and Mars - dust flies around the Moon from micrometeorites hitting its surface, and you know what happens on Mars. Or look in a textbook or on the Internet. So vacuum devices are as clean as deep space.

Again a window - for a microscope

In a transmission electron microscope, the electron beam must propagate without scattering, so the device requires a vacuum. And the beam must pass through our sample - therefore the sample must be thin. Moreover, the sample should not spoil the vacuum, and the vacuum should not spoil the sample. The first problem is easily solved: the sample is small, and what it releases will be pumped out by the microscope pumps, but the second problem is more complicated. Because of this, it is impossible to simply examine biological objects, such as living cells, in an electron microscope - the water instantly evaporates and the cell dies.

⟦column⟧

However, we will not touch upon biology, but will turn our attention to computers, routers, cameras, smartphones and other gadgets. All of them have a source of energy - a battery or accumulator. There is no need to tell how and why the energy supply is important - anyone who has urgently looked for somewhere to plug a charger knows this. Therefore, research in the field of improving battery parameters is ongoing. It is very important, for example, to understand how the structure of its materials changes during the charging and discharging of a battery. A non-trivial task arises: to make a battery microns thick so that the beam will pierce through it. But that's not all - the battery contains electrolyte, and in a vacuum it (like the liquid from the cell) will instantly evaporate, and the battery (like the cell) will die. A solution was found by a group led by A.M. Abakumov (MSU, Skoltech) - in their device, an electron beam passed through a window a fraction of a micron thick, made of compound $Si_{3} N_{4}$. The deceleration of electrons in a solid depends on the concentration of its electrons in it, therefore the range is greater, the lower the atomic numbers of the elements that make up the barrier. Note that Si, N, Be and what mica is made of, most often muscovite $KAl_{2} > AlSi_{3} O_{10}$ @ $OH_{2}$, are all at the top of the Periodic Table. Of course, it is also important whether it is possible to make a micron plate from such material, what its strength will be and how to connect it to the rest of the body. Compared to a Geiger counter, in the case of an electron microscope the problem is slightly alleviated by the fact that the sensitivity of the method does not depend on the area of ​​the window, so the window can be made smaller. But, on the other hand, in a counter it is important that the particle simply gets inside, and in a microscope it is also important that the electron beam does not scatter in the window material.

Release the electron

The range of an electron in a substance depends on the number of electrons encountered along the way. But it depends not only on atoms

⟦folio 13⟧

MECHANICS

the number of elements, and also on the concentration of atoms in space. Therefore, in the atmosphere, i.e. in a gas, the electron range must be relatively large. Indeed, in air under normal conditions and at an electron energy of 20 keV, their range is about 2 cm, and at an energy of 20 MeV - 100 m. This energy range approximately corresponds to the energies of electrons during E -decay. The fact that electrons can travel appreciable distances in air suggests the possibility of their use for initiating chemical reactions, for processing materials, for welding, etc. Indeed, such possibilities exist. However, in order to use them, you must first separate electrons from other components of the substance, then accelerate them, i.e. give them energy. Electrons can be obtained through thermal or field emission (we will meet this later) from a solid or liquid, or they can be extracted from the plasma of a gas discharge. It is convenient to accelerate electrons in a vacuum, but the problem of releasing the electron flow into the atmosphere immediately arises. Naturally, the beam is released through titanium (Ti) foil ten or more microns thick. Since the beam is initially accelerated to energies of hundreds of kilovolts, its range in titanium is on the order of hundreds of microns, so foil tens of microns thick will intercept part of the beam and heat up, but most of the beam will pass through the foil. The use of titanium, and not, say, beryllium, is due to the availability of titanium foil - it is much cheaper. And what will happen when you try to pass a flow of electrons through mica, despite the fact that the mica still intercepts some of the electrons, think for yourself. For now, let's turn to microscopes - but to different ones.

How many atoms can fit on the tip of a needle?

If we ask you what a microscope is, you will answer that it is something through which we see something small,

INVISIBLE

⟦column⟧

which cannot be seen otherwise. This is correct, but we receive information not only through vision, why was the microscope discriminated against in this sense? What if he tells us some information about a small object not in the form of an optical signal? The limitation is associated only with tradition, we are accustomed to “seeing” objects - their location, shape, surface topography and its “optical” properties, i.e. color, reflectance, gloss, etc. The listed parameters are not independent, they are related in a complex and interesting way; for example, think about what “shine” is and what it depends on. But now something else is important to us: no matter how the microscope receives information about the object, it must present it in the form of a picture that we look at. This picture is flat, but often creates a three-dimensional image in our brain; A microscope is also possible, which creates a real three-dimensional image. But at the stage, as they say, “visualization” we need to look more carefully. Because what a microscope shows us, namely the location, shape, surface of an object, is not always what we would see if the object were magnified a million or a billion times. For example, because in the nanometer range the meaning of the concepts “shape” and “surface” changes, and the concepts “color” and “brilliance” disappear altogether. Even when a familiar electron microscope (a person has been working with it since 1931) shows us a picture, we must understand and remember how he obtained and transformed it. (If we want to understand something at all, and not just ooh and ahh.) An ion projector is, in principle, a simple thing. Let's place a metal needle in a vacuum and apply high voltage to it. Near the tip, the field strength is such that the gas atoms remaining in the vacuum are ionized, and the ions are accelerated by the field, fly to the luminescent screen and create an image. Ionization occurs more often, the higher the field strength, and it is higher near individual atoms protruding from the remaining

⟦folio 14⟧

KVANT 2018/№11

Photo 5. Metal lattice in the atomic image of a riya. So we get on the screen an image of a metal lattice with atomic resolution (photo 5). But it is important to remember that in this case we see not atomic, but electron density. And we must also not forget about Coulomb’s law and the strength of the crystal lattice - the corresponding force can tear individual atoms away from the needle (“field evaporation”) or destroy the needle. During a vacuum breakdown, and we’ll talk about it now, this is exactly what happens.

Vacuum breakdown

When we talk about electrical breakdown of a dielectric, we mean the following. We take a piece of dielectric, apply an electric voltage to it and begin to increase this voltage. There are no ideal dielectrics, so a current appears - initially small. And since there is current and voltage, that means there is power. If we multiply power by time, we get energy, which means something must be happening in the dielectric. And indeed, at some point the current increases abruptly, the dielectric ceases to be a dielectric. Moreover, something happens to the dielectric material itself, to the substance. But in a vacuum there is no matter! And what happens during a vacuum breakdown can only happen to the material

⟦column⟧

electrodes. How does the electrode material get into the gap? Actually, there is only one way for this - evaporation and filling of the vacuum gap electrode material with vapor. And in this pair a breakdown occurs, a discharge is ignited (if there is enough power, an arc burns), the device is destroyed. The only small thing left is to understand who is evaporating the electrode material. There are two mechanisms for this. The first mechanism is as follows. At high field strength, field emission of one of the electrodes begins. The electrons emitted from it reach the opposite electrode and release their energy on it. The field strength is highest at the tips, which is why the electrodes of high-voltage vacuum capacitors are polished. The second mechanism is this: the electric field tears off a piece of material from the electrode (since its surface is charged), this piece flies through the gap, accelerating all the way (Newton’s second law in action), and transfers its energy to another electrode, and then heats up, evaporates and breaks down in the vapor. Therefore, they try to make electrodes from durable metals. By the way, vacuum capacitors are far from the only or even the main situation when we have a vacuum and high voltage. This happens in almost all powerful electric vacuum devices - and this includes space communications, radar, accelerator technology, and television... Even a tokamak will not work without such devices!

Two more microscopes: scanning tunnel and atomic force

The advantage of these two microscopes is that they do not require a vacuum, which destroys many interesting objects (for example, biological ones). If you bring a needle close to the surface of an object and apply voltage to it, a current will begin to flow between the needle and the surface (if it is at least a bad conductor) - the same field-electronic current that sometimes begins a vacuum breakdown. The sharper the needle, the

⟦folio 15⟧

MECHANICS

higher spatial resolution, and it can reach tenths of the interatomic distance in the lattice! The current generated is very dependent on the distance between the surface and the needle, and we can measure this distance with high accuracy. But the distance to what exactly - we haven’t touched atoms in any sense? This will be just the “distance to electrons”, i.e. we get the electron density profile above the surface. An example for silicon is shown in photo 6.

Photo 6. Electron density profile above the silicon surface

But, as you know, forces act between atoms - attraction over long distances and repulsion over short distances. The atoms in a molecule are located, on average, at such a distance from each other that the sum of these forces is zero. Therefore, if we bring the needle to the surface, a force will begin to act on it. This force is measured by the bending of the “cantilever” - the beam on which the needle is attached. And this is precisely mechanics, and the foundations of the theory of beam bending were laid not by just anyone, but by Euler and Bernoulli in the 17th–18th centuries. Note that atomic force microscopes of the 21st century work more cunningly. They approach the surface, vibrating slightly, and the parameters of these vibrations are influenced by the forces acting on the needle creeping towards the surface... This is modern mechanics at the very forefront of surface science, as it is now fashionable to say - nanoscience. We'll talk about them later.

INVISIBLE

Mechanotron

⟦column⟧

How do we measure movement? And it depends on which ones and with what accuracy. But first of all, mechanical and optical measuring instruments come to mind - tape measures, rulers, laser rangefinders, interferometers. Processing of measurement results is now carried out quite often by computers, and in order to communicate the measurement result to the computer, you must first receive it in the form of an electrical signal, then convert it into digital form. The second is a mastered thing; the corresponding devices are called analog-to-digital converters (ADCs). How can you make the movement of something respond with an electrical signal? One option is to move the ferromagnetic core, changing the inductance of the coil, the other is to move the capacitor plate, changing the capacitance. Further, inductance and capacitance can be used in different ways, for example through reactance or the resonant frequency of the circuit (Thomson's formula). But there is another, less common way - to move the anode of the vacuum tube. In this case, its parameters change, for example, the anode current at a certain

Photo 7. Mechanotron

⟦folio 16⟧

KVANT 2018/№11

rated anode voltage. The corresponding lamp is called a “mechanotron” (photo 7), its glass cylinder is soldered to a metal frame, a membrane is soldered into the frame (its edge is visible in the picture), and an anode is attached to the inside of the membrane. When the membrane is pressed, the anode moves. The parameters of the lamp as a force-to-current converter depend on the rigidity of the membrane, but as a displacement-to-current converter they do not. Do you understand why this is so?

Isotope motor

One of the exotic sources of electricity is an isotope battery. The simplest option is a capacitor in a vacuum, conclusions are drawn from its plates, and an E-active isotope is applied to one of the plates. Electrons fly out, hit the opposite plate and return through the load. What happens if the load is not connected? Let's imagine a situation where there is no external load, but one of the plates is made flexible. Then, as the charge on it increases, this plate will begin to bend, and if it manages to touch another plate, the capacitor will discharge, the plate will straighten, and everything will start all over again. The parameters of such a motor depend, naturally, on the energy of the electrons and their current, on the geometry of the system (plate dimensions and gap) and material parameters (Young’s modulus). You can try to solve this problem at your leisure. It is quite possible that someday such micro or, rather, nanomotors will be used. Moreover, ideas began to appear on using these movements to generate electricity - for example, by making a ferroelectric plate. However, a conventional isotope battery is already a source of electricity.

Nano: electronics and friction

The laws of physics are the same at all levels - from interatomic distances in a solid body to intergalactic distances above our heads. But they manifest themselves in different ways. And what we usually don’t pay attention to

⟦column⟧

attention, thinking about the processes in a solid body and when solid bodies come into contact, becomes decisive in space - for example, gravity. But some things remain just as important - for example, diffusion in solids and diffusion of radiation in stars. True, this is the diffusion of something else... Descending into the world of nanodistances, we must not forget about mechanics, but the relative role of its different aspects may change. The simplest example: the volume of a body depends on its linear dimensions in a cube, and the surface - in a square, so the role of surface effects, such as friction, increases. And in general, strange things begin to happen: uncharged surfaces are attracted, sound is transmitted through a vacuum, otherwise heat is transferred, non-contact friction arises... But do not rush to throw away school textbooks. All this becomes significant only at distances comparable to interatomic distances, and only when you engage in Serious Physics.

There's an advanced student here...

...who spends his day without letting go of the Unified State Examination codifier, and spends his nights in an embrace with a university physics course, will ask: why did I need to read this? I already know all this. Well, almost everything... There are two answers to this - one is offensive, and the other is to the point. The offensive answer is this: it seems to you that you know. And the teacher will ask two or three questions, and you yourself will understand that the ability to make intelligent eyes and nod in the right places is not knowledge. The answer is essentially this: this was written by me, and read by you so that you understand - the world is not divided into mechanics, thermodynamics, electricity, and the list goes on. You need to know everything about physics. More precisely - the entire width, and in depth - within the limits of a school, then a serious university course. And electronic devices are not the worst thing. The study of elementary particles and the behavior of stars and galaxies - Newton rules there too. Straight from its 17th century.
