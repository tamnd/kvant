---
id: 2010-6-vyishinskiy-kudrov-stasenko-nad-pozharom-samolyot-ef862ff7
issue: kvant_2010_6
year: 2010
number: "6"
title: There is a plane above the fire
authors:
  - Вышинский В. В.
  - Кудров М. А.
  - Стасенко А. Л.
rubric: osnovnye-stati
page_first: 4
page_last: 18
page_labels: 2, 3, 10, 13, 14, 15, 16
tag: KYZR
lang: en
source: kvant_digital
extraction: native
content_sha256: 0cc1ae8566e91b8fdbb695a063602ce27b973190363883022e54f8996aaf2614
prompt_sha256: draft-1
translated_from: content/ru/2010/06/articles/01_vyishinskiy-kudrov-stasenko-nad-pozharom-samolyot-ef862ff7.md
source_content_sha256: 56bcf5594e7cf587aa5a9427f57c9d83a9a3cebfe350f30cfdb9fd6ad8f67acc
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 2⟧

There is a plane above the fire

V. VYSHINSKY, M. KUDROV, A. STASENKO

" T

OH THE SUMMER WAS FULL OF THUNDERSTERMS, / HEAT AND SPIRITUALITY, /... / And the sun was scarlet even at noon” (N. Gumilyov). In such conditions, the likelihood of terrible forest fires is high. Here is an artistic description of one of them: “The fire moved like a hasty, rumbling avalanche, madly bringing death to everything. The trees, as if about to run, tried to break away, swaying and disturbing the roots. But in vain their peaks hummed, in vain they shed resinous tears. Another moment - and at once, like a deafening explosion, a whole wall of terrified trees flares up, with a crash the needles are dressed in gold, and everything drowns in fire. Further and further, the flaming lava floats persistently and imperiously, and there is no strength to stop it” (from the story “Taiga” by V.Ya. Shishkov). It turns out that there is a force that can stop the fire. This is aviation. And indeed, who other than a firefighting aircraft will be able to collect ten tons of water from a river, lake or sea in a few seconds and drop them onto a burning strip of forest from a safe height? Of course, the higher the height, the safer. But if you climb too high, what will reach the ground? Scattered cloud of droplets? Thanks to many years of experience, a minimum standard has already been developed: to extinguish a large forest fire in front of its front, it is necessary to create an irrigation strip about ten meters wide, and approximately one liter of water should fall for each square meter of irrigation area. It is clear that there is an optimal operating altitude for the aircraft such that, on the one hand, the width of the falling mass of water will have time to grow to ten meters due to the deformation and fragmentation of its original volume, and on the other hand, not all of the mass will turn into drops that are easily carried away by the wind. You can also estimate the length of the irrigation strip. If an airplane drops, for example, three tons of water (or $3 \cdot 10^{3}$ l), then with a standard surface density of 1 l $м^{2}$ and a required strip width of 10 m, we will obtain a length of the order of 300 m. But this is if all the water reached this strip and settled evenly. And if only half reaches, then this length is halved, and if a third, then... And here it is necessary to build a physical and mathematical model of the processes occurring with the discharged water. First, let's look at the experiment. In flight conditions, it is difficult to measure anything inside a falling mass of water (unless you put a scuba diver with a parachute and instruments there). However, impressive external filming also provides something (Fig.1). Before

⟦column⟧

⟦figure⟧

Fig. 1. Firefighting aircraft dropping water

In total, it is clear that some time after “falling out” of the hatch, the liquid breaks up into parts (Fig.2). This disintegration occurs due to the impact of the oncoming air flow (at a speed of $u_{0} )$), which flattens the liquid in the transverse direction.

⟦figure⟧

Fig. 2. Crushing of liquid when falling to the ground

The liquid is crushed into pieces at a vertical distance of about 10 m from the aircraft. At this moment, the falling velocity of the liquid is approximately 10 m/s, and the horizontal speed relative to the ground is almost equal to the speed of the airplane.

⟦folio 3⟧

OVER

BY FIRE

Of course, in this process of “almost vertical” fall there is an intense blowing off of the surface layer of water. Experimenters found that before the main volume of liquid is crushed in the form of drops, 20–30% of the initial mass has already been lost. As a result, a wide range of sizes of “chunks” of water are formed - from large fragments that continue to collapse under air pressure, to fine water spray that extends far behind the aircraft, which will be carried away by the wind or the rising hot flow from a fire. Of course, we are primarily interested in the fate of those fragments of the original mass of water that should get to the right place on the surface of the earth. This is similar to the problem of bombing, which was solved by the invention of instruments that take into account the speed and altitude of flight, wind, and also the distance to the target. Only in the case under consideration the “bomb” has a variable mass and an unpredictable shape. And how tempting it would be to make an on-board device that would calculate, taking into account all the determining factors, the moment when you need to press the water release button. Or even better - for it to press such a button itself. In principle, the modern level of development of aerohydrodynamics makes it possible to solve such a problem numerically, but the trouble is that it takes a long time for even the most modern computers to carry out the calculations. But let’s try to explore individual features of the phenomenon, using the clues that the flight experiment has already presented to us. First of all, let us highlight in the stream of water flowing from the aircraft a horizontally flat fragment of water, which initially had the shape of a rectangular hatch. The liquid we are considering is blown by a counter flow of air. Using a modern numerical research software package, we obtain

–

AIRPLANE

⟦column⟧

a characteristic picture (Fig.3) corresponding to a certain point in time. In our case, the chosen flight speed is $u_{0} = 70$ m s and the time moment t = = 0.27 s. Of course, figure shows only half of the “top view” of this layer (to save space) - since there is a vertical plane of symmetry. Under figure the accepted Cartesian coordinate system is given: the x axis is directed along the speed of “blowing” the water layer (it is equal to the flight speed with the opposite sign), the z axis is perpendicular to it and lies in the horizontal plane, the y axis is vertical. A color digitization of speed values ​​and a geometric scale is also given here. The arrows show the direction of air speeds. The thinned end regions of a strongly deformed “rectangle” are visible, from which smaller fragments and drops should be especially intensively torn off. Behind the former rectangle one can see the formation of vortices, which help to retain drops near the falling mass of water. But this planar layer model assumes that someone is forcibly holding water between two fixed planes. In reality, after a short period of time, the remaining mass of water will be flattened by the incoming air flow and will become more like a vertical pancake, which will then fall apart; these parts, in turn, will flatten and fall apart, and so on - until they fall to the ground or completely disintegrate into small drops (in the case of a very high flight altitude). And here another model of stage-by-stage fragmentation arises (see Fig.2). Let at some stage of the process—its number j—the water fragment have the shape of a sphere with radius r j. Flattening under the pressure of air, it turns into a pancake (in scientific terms, an ellipsoid of rotation) with an axial ratio of $\Delta x \Delta y = 1 10$, after which

Fig. 3. Velocity distribution and vortex formation in a falling fragment of water

⟦folio 10⟧

KVANT 2010/№6

⟦figure⟧

Fig.20. Three types of bricks for Yanga fortress

Prove it yourself. Note, by the way, that the constructions with which we specified the height functions are not the only possible ones. For example, if we have already come up with a three-dimensional model, nothing prevents us from rotating it in space. As a result, the heights of all points will change rather cunningly and the combinatorial rule defining the height function may become completely indigestible. Now that the height function is given, we can construct the "bricks" corresponding to the flips. As in the previous paragraph, consider a figure (a square of two dominoes or a rhombus of four dominoes) in which a flip is performed, and for each node of this figure we construct a point in three-dimensional space whose z-coordinate is equal to the value of the height function at this node. The constructed points define a certain polyhedron. The flip of the first type corresponds to a tetrahedron, and the flips of the second type correspond to a quadrangular pyramid (Fig.20). So, performing a flip is adding or removing a brick from some box, where by box we, as before, mean the graph of the minimum height function. The domino split corresponding to the empty box is shown at figure21 on the left; The full box (i.e., the maximum height function) corresponds to a partition by figure 21 on the right. As you can see, our box has two opposite

⟦figure⟧

Fig.21. Empty and filled boxes

The first peaks of the fortress are located low (at height 0), and the other two are located high (at height 3). Thus, the brick box is close in shape to a tetrahedron (compare with figure 20,a). Several examples of box filling are shown in Figures 23–27.

⟦column⟧

Let us describe the process of filling an empty box layer by layer using box $5 \times 5$ as an example. The lowest place in an empty box is the diagonal going from bottom left to top right (Fig.21, left). Let's put 5 tetrahedra along this diagonal, the upper edges of the tetrahedra are at height 1 (Fig.22,a; figure25 shows what the box looks like when one tetrahedron is added). There are 6 points left on the diagonal, located at a height of 0. We cannot do anything with the extreme ones, and we will cover the remaining 4 points with inverted pyramids (bricks of the third type, see Fig.20, c), we will get a large flat area at a height of 1 (Fig.22, b). On this site we can place 6 pyramids (bricks of the second type, see Fig.20, b), the tops of the pyramids should be above the marked nodes. Another placement of the pyramids is not possible here, because, as we noted, the center of the diamond, where the corresponding flip occurs, must lie on the base square grid; if, for example, you make a flip in a rhombus centered on the diagonal in question, this will lead to the removal of one of the newly laid inverted pyramids (Fig.26). So, by adding 6 pyramids, we got the picture shown on figure 22,c. The added pyramids are in contact with each other and with the box with edges at height 1, let's put tetrahedrons on these edges: 9 tetrahedrons on the edges going in one diagonal direction, and 4 on the edges of the second diagonal direction; the result is shown on figure 22,g. We will cover the remaining vertices inside the platform at height 1 with 6 inverted pyramids, we will get a large flat platform at height 2 (Fig.22,d). On this site we place 4 pyramids with the vertices located above the marked nodes, the result is shown in figure 22,f. If we now cover the edges lying at height 2 with five tetrahedra, we get a filled box (see Fig. 21, right). This whole design is reminiscent of laying eggs in a box: first they put a substrate with holes for the eggs, then they put the eggs themselves, and cover them with an inverted substrate on top, etc. To count the number of flips, we need the following lemma.

Lemma $2. 1 \cdot ( n - 1 ) + 2 \cdot ( n - 2 ) + 3 \cdot ( n - 3 ) +^{…}$

… $+ ( n - 2 ) \cdot 2 + ( n - 1 ) \cdot 1 = ( n - 1 ) n ( n + 1 ) 6$.

⟦folio 13⟧

About moire, animated illustrations and the benefits of models

Z. PYATAKOVA, A. PYATAKOV

IN OUR TIME, ELECTRONIC BOOKS are increasingly pushing out their paper counterparts, but they do not intend to give up their positions so easily. Recently, picture books have appeared that “come to life” the moment the reader begins to turn their pages (Fig.1). From a good old book like this

⟦column⟧

the reader can easily find them on the Internet using the keyword Scanimation. We got our hands on a copy of this book that brings the characters of the Star Wars series to life, and we couldn’t resist looking at what was inside. Using a razor blade, we separated the layers from which the book page was glued together (Fig.2,a). It turned out that under the transparent film with a lattice of vertical black lines printed on it there is hidden figure, in which one can guess the original image of the illustration, but upon closer inspection)

⟦figure⟧

Fig. 1. Books with “come to life” pictures

abilities, it would seem, cannot be expected. It is not surprising that these books have already become bestsellers abroad. Books of this type have not yet appeared on the shelves of our bookstores, but a) c)

Fig. 2. How does the “coming to life” picture work?

⟦folio 14⟧

KVANT 2010/№6

When you breathe, it becomes noticeable that it consists of a series of vertical stripes (Fig.2,b; inset). These series of stripes correspond to different phases of the object's movement. If you again put a transparent film with vertical shading on figure and start moving it (Fig.2,c), then the picture will come to life and the figures will begin to move. Does this remind you of anything? Let's take a break from space battles and go into a quiet room with light tulle curtains hanging on the windows. Look what happens if you put curtains on top of each other - a changing picture of light and dark areas will appear. Such paintings are called moire - from the beautiful French word moire, meaning fabric with stains, shimmering in the light with different shades. Moire always occurs when periodic structures overlap each other, be it threads of fabric, fence bars or comb teeth (Fig.3).

b) a)

⟦column⟧

naty, in our case we draw lattices with sharp edges and the change occurs only in space. But in principle, nothing prevents us from drawing a sinusoidal intensity distribution - the moire pattern will not change significantly, it will only become less sharp. Well, now let's start the experiments. Let's print periodic systems of strokes (Fig.4,a) or concentric rings (Fig.4,b) first on transparent

⟦figure⟧

Fig.4. Periodic structures of strokes and rings

film and then on paper. Let's superimpose these two printouts - transparent and opaque - on top of each other at different angles, and we will see a non-uniform distribution of stroke density (Fig.5).

⟦figure⟧

Fig.3. The emergence of moire

Moire can also be observed by computer users - when looking at the striped figure on a small scale, rings appear out of nowhere, and when the scale figure changes, the sizes of the rings change. For designers and photographers, moire turns into an annoying nuisance, which they try to combat using different methods. We invite the reader to create his own patterns and experiment with them, and so that this is not just empty fun, at the same time simulate the phenomena of wave interference using moiré patterns. Indeed, moire and electromagnetic waves have one common property - periodicity. Thus, in an electromagnetic wave, the electric and magnetic fields periodically change in space and time, and moiré is characterized by periodicity in space. If two waves meet in a certain region of space, then the waves superimpose on each other, just as two combs superimpose on each other (see Fig.3, b). And under certain conditions, an interference pattern appears with a characteristic alternation of intensity maxima and minima. Thus, the moiré model can be used to explain interference. True, here it is necessary to make a small reservation - usually light is characterized by harmonic, i.e. sinusoidal dependence of field strength on time and coordination

⟦figure⟧

Fig.5. Moire model of interference of plane and spherical waves

The same experiments can be carried out even without printing pictures on film, but simply by looking at them on a computer screen in some graphics editor that allows you to work with individual objects and transparency. By rotating the gratings relative to each other, you can observe how the picture changes. Note that the case of parallel lines models the interference of plane waves, and systems of concentric circles model the interference of spherical waves. Using these models, it is easy to see how the interference pattern depends on the angle between plane waves (see Fig.5,a) and on the distance between point sources (see Fig.5,b). The closer to each other the directions of wave propagation or the locations of point sources, the wider the interference fringes (Fig.6). This fact is well known, but, nevertheless, it does not fit very well into the consciousness of a person who has just begun to study the phenomenon of wave interference. The moiré model allows you to feel these patterns “at your fingertips.” Let us note one more property of moire (see Fig.6): moire patterns are much larger than the structure that gave rise to them. This circumstance is successfully used

⟦folio 15⟧

ABOUT

MUARAH,

REVIVED

ILLUSTRATIONS

AND

BENEFIT

MODELS

⟦figure⟧

Fig.6. The relative position of light sources and the width of interference fringes

in modern super-resolution microscopy. Let's imagine that we want to study a surface with such a fine relief that it can no longer be seen with an ordinary optical microscope. And here the moire effect comes to the rescue: if you illuminate an object with radiation with a periodic distribution of intensity in space, i.e. so that the light spot itself forms a lattice of dark and light stripes, then these two gratings (relief and backlight) will give a large moiré pattern that is easy to see through a microscope. True, you still need to be able to separate the image itself from moire. However, knowing the structure of the backlight, as well as taking a frame under uniform illumination, with the help of calculations it is possible to obtain an image of the surface with a resolution twice that of a microscope. Of course, the amount of computation when processing images will be significant, but in our digital age this does not bother anyone. Is it possible to make quantitative calculations of interference patterns using moire? Unfortunately, things are not that simple here. An electromagnetic wave, unlike moire, changes both in space and time, and the difference in the path of two waves at one point in space cannot be unambiguously correlated with any distance in the moire pattern. At the same time, moire is quite helpful for understanding the qualitative patterns of interference patterns. Finally, moire allows us to understand one of the most difficult issues in physical optics: the concept of coherence. Let us recall that waves are called coherent if the phase difference between the oscillations excited by the waves remains constant over time. Let's try to compare visual images with the concept of coherence using the same moiré model. Draw on a transparent film (or in a graphic editor) several short lattice elements with a random distance between them (Fig.7,a) or rotated at a small random angle relative to each other (Fig.7,b). It is important here that the distance

⟦column⟧

The difference between the lattice systems or the angle by which they were rotated were precisely random variables, i.e. did not obey any predetermined law. If such gratings are superimposed on each other, then a clear interference pattern with a certain period will no longer be visible, but some average distribution of illumination will be obtained (Fig.7, c, d). In this case, they say that the waves are incoherent, and the cause of the incoherence cannot be determined by eye. But in the case of Figures 7,c and 7,d, it is still clear that the reasons that caused the incoherence are different.

⟦figure⟧

Fig.7. Illustration of coherence failure in a moiré model

Usually there are two types of coherence – spatial and temporal. Spatial coherence means that the difference in the path of waves emitted by different points of an extended source at the same moment in time remains constant over time. Temporal coherence means that the difference in the path of waves emitted by one source point at different times remains constant over time.

⟦folio 16⟧

KVANT 2010/№6

An illustration of a violation of temporal coherence will be a random distribution of distances between grating systems (see Fig.7,a), and an illustration of a violation of spatial coherence will be a random distribution of inclination angles of gratings (see Fig.7,b). In this case, we can assume that time is represented along the horizontal axis in these figures. How can we quantify coherence? For this purpose, there are the concepts of coherence length and time. (These concepts are not introduced in the school physics course; they can be found in more detail in textbooks for universities, for example, in the “General Physics Course” by I.V. Savelyev.) The coherence length is the maximum difference in the path of the waves emitted by the source, at which a stable interference pattern is still observed. The coherence time is the maximum difference in the arrival times of waves at a given point in space, at which a stable interference pattern is still observed. For light propagating in a vacuum, the coherence length l is related to the coherence time $\tau$ as follows: $l = c \tau$, where c is the speed of light. The coherence time for a point source can be defined as the duration of one pulse, or, as they say, a radiation train. During this time, the random change in the oscillation phase reaches a value of the order of $\pi$. The length of an individual element of a periodic structure is figure 7, and precisely characterizes the coherence time. If we look at parts of moire smaller than this length, we will see a clear picture, but if we look at it on a larger scale, unfortunately, only something in between will be visible. For spatial coherence, a coherence radius is introduced - the characteristic size of the source at which the waves emitted by it can be considered coherent. The coherence radius is defined as $r = \lambda / \phi$, where $\lambda$ is the wavelength of the radiation, $\phi$ is the range of angles in which the observer can detect the radiation from the source. In the case of spatial coherence, the maximum angle at which the gratings are rotated relative to each other at figure 7b characterizes the radius of coherence. For each light source, the limitations of spatial and temporal coherence operate simultaneously, but may manifest themselves to different degrees. For example, for small sources emitting different wavelengths (such as an incandescent light bulb), the limitation of temporal coherence is stronger, and for extended sources emitting in a narrow range of wavelengths, the limitation of spatial coherence is stronger. On spatial scales smaller than the coherence length or on time intervals shorter than the coherence time, wave interference can be observed, and if we consider a large region of space or a large time interval, then on average the energy distribution will be uniform. This is exactly the picture we see when light is superimposed, for example, two incandescent light bulbs. For a light bulb, the coherence time is about $10^{-} 8 c$.

⟦column⟧

and our eye, of course, does not notice the rapid flickering of the interference pattern - after all, the characteristic reaction time of the eye is approximately 0.1 s. It turns out that during the reaction time of the eye, the interference pattern manages to change tens of millions of times! Most natural light sources have a short coherence time, and therefore we do not observe interference from independent sources. To overcome temporal incoherence, two sources are “made” from one. For example, in Jung's classic experiment, two small holes in a screen were illuminated by a single wave of light. In this case, these source-holes will already be connected to each other in time, i.e. will be coherent. To combat spatial incoherence, it is necessary to reduce the size of the source, i.e. extract a small part from it. In the same Young experiment, if the holes are placed too far apart or made too large, the spatial coherence limitation will come into play and the interference pattern will blur. But there are also light sources that can produce an interference pattern without any additional tricks. These are lasers. For a laser, the coherence time turns out to be on the order of $10^{3}$ s, and the coherence length is approximately $10^{11}$ m - larger than the diameter of the Earth's orbit! However, even in lasers, spatial coherence limitations often come into play. For example, if you look closely at the spot produced by a regular laser pointer (just don’t look directly into the laser itself, it’s dangerous for your eyes), you can see a constantly changing structure of many dots. These points act as independent sources, and such light does not have spatial coherence, which is due to the large divergence angle of a conventional laser pointer. We can talk about lasers for a long time, but you can read about them in other articles and books. Our article is coming to an end, and we hope that a comparison of such seemingly distant things - light and moire - will allow you to better understand both.

⟦figure⟧

Fig.8. What is shown here?

Finally, try to guess what is shown on figure 8. Did you guess it? Can you find a lattice like this to bring this picture to life?
