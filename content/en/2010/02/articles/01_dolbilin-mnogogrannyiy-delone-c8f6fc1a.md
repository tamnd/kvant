---
id: 2010-2-dolbilin-mnogogrannyiy-delone-c8f6fc1a
issue: kvant_2010_2
year: 2010
number: "2"
title: Multifaceted Delaunay
authors:
  - Долбилин Н. П.
rubric: osnovnye-stati
page_first: 4
page_last: 11
page_labels: 2, 3, 6, 7, 8, 9
tag: 7G20
lang: en
source: kvant_digital
extraction: native
content_sha256: 8b4cbc44dabe0adb2893829341dc155ca7bdf324b87cde1dcdbe268e0ee00058
prompt_sha256: draft-1
translated_from: content/ru/2010/02/articles/01_dolbilin-mnogogrannyiy-delone-c8f6fc1a.md
source_content_sha256: f1781319110ebd105eb9efa0ff0c5908f5dfe4778da3fbce8684efcb982ea4ca
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 2⟧

KVANT 2010/№2

Multifaceted Delaunay

N. DOLBILIN

Empty sphere method and Delaunay triangulation

Boris Nikolaevich Delaunay was a remarkable popularizer of science. At the same time, he adhered to the principle: every popular article about mathematics should contain a proof of at least one statement. We will follow this principle and present with proof the main ideas of a very useful geometric theory - the theory of Delaunay tilings. This theory was outlined by him in the early 20s in his work “On the Empty Sphere.” In a number of special cases, the idea of ​​such a partition has already been encountered, for example, in the works of Voronoi. The merit of Boris Nikolaevich was that he, with his characteristic clarity and transparency, described this simple geometric construction for a very general class of sets. We will now explain the main ideas of this science - for simplicity, only on a plane, although this theory can easily be transferred to space of any dimension. Let us consider a certain set X of points on the plane. Points of the set X, in order to distinguish them from other points of the plane that do not belong to X, will be called nodes. It is assumed that the set X of nodes satisfies the following two conditions. There are two positive numbers r and R such that (1) any circle of radius r contains within itself at most one node from X; (2) any circle of radius R contains within itself or on its boundary at least one node from X. Delaunay called such a set an X (r, R)-system. Now this, by the way, is not very successful, the name has changed to the Delaunay set (with parameters r and R). It is clear that conditions (1) and (2) are equivalent to the conditions $( 1 ' )$ the distance between nodes is at least 2r and $( 2 ' )$ the distance from any point in the plane to the nearest node in X does not exceed R. Quite often, another equivalent definition of the Delaunay set turns out to be useful. We will consider circles with centers only at nodes from X. Then conditions (1) and (2) can be reformulated: $( 1 '' )$ circles of radius r with centers at nodes from X do not overlap in pairs, i.e. form a package (Fig. 1); $( 2 '' )$ circles of radius R with centers at nodes from X cover the entire plane, i.e. form a coating. In other words, any point on the plane belongs to at least one of these circles. It is easy to see that, due to condition (2), the number of all nodes in the Delaunay set is infinite.

End. For the beginning, see «Kvant» No. 1.

01-.p65

⟦column⟧

Note that the parameters r and R are specified ambiguously: from conditions (1) and (2) it obviously follows that the set X satisfies the same conditions (1) and (2) for any values ​​of $r '$ and $R '$, if $0 < r ' \le r$ and $R ' \ge R$. Now, following Boris Nikolaevich, let us proceed to $по-^{Рис.} 1$ the construction of some special partition of the plane into polygons, uniquely associated with the set X. Partition of the plane is a somewhat new term, although the meaning of this term is the same as that of an event known from childhood: breaking glass. A whole glass is broken into fragments from which a whole can be made, while the individual fragments do not overlap each other $друга.^{1}$ The division of a plane into polygons is a set of polygons $M_{1}, M_{2}$, etc., so located on the plane that (a) no two polygons overlap each other (packing condition), and (b) polygons taken together cover the entire plane (condition coatings). Parquet on the floor, tiles on the wall, Penrose mosaic (Fig.2) - all these are limited fragments of the partition of the (infinite) plane. Let us now present the idea of ​​the “empty sphere”, which belongs to Boris $Ни-^{Рис.} 2$ Kolaevich Delaunay. 0th step. Let us take on the plane where the set X is located a small circle, say of radius less than r, which is neither inside nor on the boundary

1 This analogy, like any analogy in general, is far from perfect.

⟦folio 3⟧

MULTIFACETED

contains nodes from X. Such a circle exists because the distance between nodes is at least 2r. 1st step. Leaving the center $O_{1}$ of the circle motionless, we increase its radius, leaving it empty of nodes inside, until the boundary of the inflated circle encounters some node x from X. Such a moment will certainly occur, since according to condition (2) the radius of the empty circle does not exceed R (Fig.3).

DELAUNAIS

⟦column⟧

Note that after the third step, a certain number k of nodes, $k \ge 3$, are located on the boundary circle of the circle. Let's construct a k-gon with vertices at the given k nodes (Fig.6). It is clear that this polygon

⟦figure⟧

Fig. 6

⟦figure⟧

Fig. 3

2nd step. Now, without removing the circle from node x, we move the center of the expanding circle away from node x along a straight line $xO_{1}$ until it hits another node y (Fig.4). Such a moment will certainly come due, again, to condition (2). Let us denote the center of this circle by $O_{2}$.

⟦figure⟧

Fig. 4

3rd step. Without removing the circle from nodes x and y, we will remove its center from nodes x and y along the median perpendicular to the segment xy until the expanding circle encounters another node z (Fig.5).

⟦figure⟧

Fig. 5

This completes the process of expanding the circle. Let us denote the final circle by K and its center by O.

01-.p65

is inscribed in a circle that has no other nodes from X either inside or on the boundary $содержит.^{2}$ A polygon M is called a Delaunay polygon for a given set X of nodes if its vertices are nodes from X and it is inscribed in some circle K that does not contain any other nodes except vertices either inside or on the boundary. The k-gon obtained as a result of the “four-move” described above is a Delaunay polygon. Thus, the set of Delaunay polygons is not empty. Moreover, it is easy to see that by applying the “four-move” to small circles taken in different parts of the plane, one can obtain an infinite number of Delaunay polygons. Note that any node in X is a vertex of at least one of the Delaunay polygons. Such a polygon can be constructed by means of a four-pass move applied to a small circle fairly close to the given node. Boris Nikolaevich proved a not very complicated but important theorem: Theorem. The set of all Delaunay polygons for a given set X of nodes forms a partition of the plane. Proof. Recall that the set of nodes X satisfies conditions (1) and (2). Let us first prove that no two Delaunay polygons $M_{1}$ and $M_{2}$ overlap, i.e. do not have common interior points. Take the "empty" circles $K_{1}$ and $K_{2}$, described around $M_{1}$ and $M_{2}$ respectively. None of these circles is contained in the other, since each of them is empty of nodes from X inside and each of them contains a certain number of nodes on the boundary. If the circles $K_{1}$ and $K_{2}$ do not overlap, then the polygons $M_{1}$ and $M_{2}$ contained in them do not overlap. Let the circles overlap along some “lens” (Fig.7), composed of the arc $a_{1}$ of the first circle entering inside the second circle

2 An attentive reader might have noticed that already at the first step the expanding circle could have encountered not one, but two, or even more nodes. Note that in this case we could go from step 1 directly to step 3, or even get the final circle K.

⟦folio 6⟧

KVANT 2010/№2

mo, in which, according to Delaunay himself, he reported that he had studied these partitions back in the 1920s. In 1924, Delaunay asked academician $В.А.Стеклова^{4}$, who was heading to the International Congress of Mathematicians in Toronto, to report on his work. Later, in 1928, this work was published in the proceedings of Congress. At the same time, in his letter, Boris Nikolaevich did not fail to mention that the congress was held in Coxeter’s hometown, Toronto. Coxeter's answer was very correct. He found a mention of Delaunay's work in the materials of the 1924 mathematical congress. In a letter, Coxeter asked Delaunay to forgive him, especially since in 1924 he, Coxeter, was so young that, again according to Boris Nikolayevich, he “walked under the table in short pants.” At the same time, Coxeter wrote to Professor K. A. Rogers at Cambridge, who was finishing his book, “Laying and Coatings,” which had become a kind of mathematical bestseller. Rogers included a reference to the Delaunay partition in the book. Most likely, the term - Delaunay partition (in computational geometry - Delaunay triangulation) - first appeared in this book. In the 1980s, it became widespread in the West, from where it came to Russia at the end of the last century. In the 1990s, I had the opportunity to meet Professor Coxeter and speak at his seminar at the University of Toronto. I asked the master to tell about this story. Coxeter generally confirmed the story told by Boris Nikolaevich, with the exception of “walking under the table in short pants.” In 1924, Coxeter (1907–2003) was already 17 years old. And the phrase about “walking under the table” was a manifestation of expression and humor characteristic of Boris Nikolayevich - qualities that Delaunay possessed in full.

4 Vladimir Andreevich Steklov (1864–1926) - famous Russian mathematician, academician. In the 1920s he organized the Institute of Physics and Mathematics of the Academy of Sciences and was its first director. Later, in 1934, this institute was divided into two academic institutes: the V.A. Steklov Mathematical Institute and the V.A. Steklov Institute of Physics. P.N. Lebedeva.

⟦column⟧

Leningrad period (1922–1934) Work on partitions of space marked a shift in research towards geometry. It was gradual and natural. A certain role here was played by the contact in the study of indefinite equations with the work of Voronoi. But the main reason for the geometrization of Boris Nikolaevich’s research lay in himself, in his exclusively figurative, artistic perception of the world. It is characteristic that Boris Nikolaevich spared no effort and time to bring the understanding of an already completed mathematical result to the level at which the result would be formalized in a geometric image. “What does this simply mean?” - a favorite question that he asked himself and his colleagues every time another job was discussed. Recognition of scientific merits did not take long to arrive: in 1929, B.N. Delone was elected a corresponding member of the Academy of Sciences. By this time, he had been a professor at Leningrad University for 7 years. His extremely clear and thoughtful lectures arouse great interest among students. His popularity was so great that the first lectures of his special (elective) courses attracted several hundred students who wanted to see the legendary lecturer. It must be said that Delaunay never missed an opportunity to tell students about a difficult unsolved problem. Boris Nikolaevich was guided by a well-known principle, apparently belonging to Plutarch: “The student is not a vessel that needs to be filled, but a torch that needs to be lit.” And the one who burns himself can light the fire. High scientific authority, a devoted and at the same time aesthetic attitude towards science, personal charm - all this attracted young people to him. It is not surprising that he had many students, including several outstanding mathematicians: academicians Alexander Danilovich Alexandrov (1912–1999) and Igor Rostislavovich Shafarevich (b. 1923), corresponding member of the Academy of Sciences Dmitry Konstantinovich Faddeev (1907–1989).

B.N. Delaunay gives a lecture

01-.p65

⟦folio 7⟧

MULTIFACETED

In the spring of 1934, in Leningrad, Boris Nikolaevich organized the first school mathematics Olympiad, which began mathematical Olympiads in our country. Participants in the first Leningrad Olympiad recalled for a long time what a stunning impression their meetings with B.N. Delaunay made on them (see, for example, «Kvant» No. 9 for 1984, p. 52).

A.D.Alexandrov

B.N.Delone and I.R.Shafarevich (late 1940s)

Moscow period (1934–1980)

In 1934, the V.A. Steklov Mathematical Institute was founded in Leningrad, where Boris Nikolaevich worked from the moment of its foundation. Until 1960, he headed the algebra department, and then the geometry department until the end of his life. Soon after its creation, the Mathematical Institute (or rather, most of it) was transferred along with other leading scientific institutions of the Academy of Sciences to Moscow. Since 1935, Delaunay has been working as a professor at Moscow University, for many years he has headed the department of geometry, now it is the department of higher geometry and topology at the Faculty of Mechanics and Mathematics. At Moscow State University he created a very original course in analytical geometry, which stood out for its exceptional richness of geometric ideas. It is not difficult to verify this by opening a two-volume book on analytical geometry, written by him in collaboration with D.E. Raikov. Students who had the good fortune to listen to his lectures hardly suspected that behind their magnificence was hidden the most careful preparation. It took him two full days to prepare a two-hour lecture, then a day. He polished every idea, every figure. And, as a consequence, in

01-.p65

DELAUNAIS

⟦column⟧

During the lecture, clear dodecahedrons and icosahedrons, elegant paraboloids and hyperboloids, cute “affine cats”, which he introduced into his course of analytical geometry to illustrate what happens to a figure during an affine transformation, quickly and easily appeared on the blackboard. At one time, students of the Faculty of Mechanics and Mathematics at Moscow State University were in vogue for a series of very witty anecdotes about their professors on the topic: “Which (of the professors) cooks soup in what?” According to the student version, which is not without irony, Boris Nikolaevich cooked soup in n-dimensional $решетке^{5}$: the soup, however, flowed out, but geometric clarity remained. Boris Nikolaevich was completely devoid of any reasoning or tediousness. I will cite an episode that N.Ya. Vilenkin, who studied with Delaunay, told me about. One day Boris Nikolaevich appeared at a lecture with some kind of angry expression on his face and began to make unpleasant grimaces and even growl. The students, accustomed to seeing Delaunay always smiling slightly slyly, were stunned: what happened to Boris Nikolaevich? This lasted about ten to fifteen seconds, and then the grimace disappeared, everyone saw a familiar smile and heard an explanation of what happened: “On the way to you, I met your curator. She complained to me very much about you, you skip classes, many did not pass colloquiums, etc., and really asked to scare you...” Regarding scientific work in the Moscow period, I will name only some of the main directions in which Boris Nikolaevich worked hard and obtained important results. This is, first of all, the geometry of positive quadratic forms and its applications to the theory of so-called lattice coverings and packings of space. Fundamentally new results were obtained in the theory of regular and crystallographic partitions of multidimensional space, as well as in the geometry of numbers. A number of results from 1960–70 were obtained in collaboration with colleagues and students. B.N. Delaunay was an outstanding popularizer of mathematics and science in general. His popular lectures, intended for a wide audience, attracted hundreds of listeners. He had pre-prepared “impromptus” - techniques with which he made the lecture lively, exciting and unforgettable. For example, in the 1940s, he lectured several times on the topic “N.E. Zhukovsky’s theorem on the supporting force of an airplane wing.” Boris Nikolayevich began his lecture in the famous Great Auditorium of the Polytechnic Museum in Moscow in front of several hundred people gathered like this. B.N.: “You probably know the famous mathematician Academician Pavel Sergeevich $Александрова^{6}$?” Individual voices: “Yes, of course.”

5 Lattice here means a set of points with integer coordinates. 6 P.S. Aleksandrov (1896–1982) - an outstanding mathematician, one of the founders of the national topological school, academician, professor of mechanics and mathematics at Moscow State University.

⟦folio 8⟧

KVANT 2010/№2

B.N.: “Do you know that the famous mathematician Academician Alexandrov never flies by plane?” A slight hum, the audience is perplexed. B.N.: “Do you know why Academician Alexandrov is afraid to fly by plane?” The noise is growing. B.N. (with a sly smile) concludes: “Academician Alexandrov never flies by plane because he does not know Zhukovsky’s theorem. But I know and fly a lot. Today I will introduce you to this theorem, and you will never be afraid of flying.” By this point, the audience is “warmed up” and ready to listen to a story about such an important theorem.

Not just science

01-.p65

Peak Belukha and Peak Delone

Among Boris Nikolaevich's many non-mathematical hobbies, mountaineering occupied a special place. This is, undoubtedly, the strongest passion that has lasted throughout my life. It originated, as already mentioned, in childhood during the family’s summer trips to Switzerland. In mountaineering, he was especially attracted by the beauty of far-opening panoramas, geometrically expressive silhouettes of ridges and peaks. And, of course, the passion to conquer heights at any cost. He was involved in mountaineering quite professionally. In the Alps, back in 1910, he climbed the second highest peak after Mont Blanc, but technically not difficult, Monte Rosa. Then there was the Caucasus with numerous difficult ascents, including first ascents. But Boris Nikolaevich especially loved Altai. In 1926, he also visited the mountain that now bears his name. Delone Peak is located on the shoulder leading to the highest peak of Altai - Belukha. Traveling through Altai together $И.Е.Таммом^{7}$, they discovered an amazingly beautiful place: Lake Shavlo, in the clear water of which two magnificent peaks covered with snow were reflected. Delaunay called one of them Beauty, Tamm called the other Fairy Tale. According to Delaunay, the beauty of this place surpasses all the famous places in the Alps. Nowadays, the route to Beauty and Fairy Tale is one of the most attractive in Altai. In the 30s and 40s of the last century, Boris Nikolaevich was actively involved in organizing mass mountaineering in our country. In the summer of 1931, he organized the country's first mountaineering camp in the Caucasus for

⟦column⟧

workers of the Leningrad Putilov plant and conducted classes in mountaineering techniques there, and analyzed ascents together with instructors. In 1934 he was awarded the title of master of mountaineering. At this time, mountaineering was becoming a mass sport, and it became necessary to create a classification system.

7 Igor Evgenievich Tamm (1895–1971) - an outstanding theoretical physicist, Nobel Prize laureate (1958).

Lower Shavlinskoye Lake and snow-white peaks Skazka and Krasavitsa

⟦folio 9⟧

MULTIFACETED

fication of sporting achievements. Delaunay developed principles for the classification of mountain ascents (five stages) and, in accordance with them, classified more than 200 routes to the peaks of the Caucasus, Central Asia and Altai. In 1938, he wrote the first guide for climbers, “Peaks of the Western Caucasus” (part of the Caucasus Range located west of Elbrus). It describes several dozen of the main peaks of this area and the routes to climb them. The description was accompanied by figure of each peak along with the routes to climb it. In the book, on an insert, there was a panorama of the entire West Caucasian ridge, which Boris Nikolaevich made, moving from peak to peak on a parallel ridge. With age, mountaineering has been replaced by hiking. Not walks of 5–10 kilometers, but real 30–40-kilometer hikes, sometimes very difficult, which invariably took place in the most beautiful places in the Moscow region. Boris Nikolaevich was a physically exceptionally hardened man. And it was still unsettling to see an elderly man naked to the waist walking quickly with a backpack at the end of winter. The falling snow melted and, flowing down his gray head, froze in the form of large icicles. Boris Nikolaevich loved nature very much and always admired its beauty silently, as if trying to absorb everything and everyone. His admiration was involuntarily transmitted to his companions. Communication with nature was like a sacrament, and it was unpleasant for him, although he did not show it, when this sacrament was accidentally disturbed by someone's conversations. But around the fire or on the train, his companions became listeners to numerous stories, each more interesting than the other. B.N. Delaunay was a wonderful storyteller... “You, of course, don’t know that my sister is a saint (pause, the narrator’s sly look, the listeners’ bewilderment). Yes, yes, quite seriously, saint...” ...Then began an interesting story about his cousin and childhood friend Elizaveta Pilenko (married Kuzmina-Karavaev), a poetess (her poems were highly valued by Alexander Blok). After the revolution of 1917, she emigrated to France and became a nun (Mother Mary was the monastic name; that was also the name of our feature film dedicated to her). During the occupation of France by the Nazis, Mother Maria joined the ranks of the Resistance, was arrested and died in a German concentration camp. After the war she was officially canonized by the Catholic Church.

"Evening of Life"

In a greeting address on the occasion of the 80th anniversary, the German Academy of Naturalists “Leopoldina” wished B. N. Delaunay, a member of this academy, a “good evening of life.” “Evening of Life” lasted ten years. During these years, he, together with his students, obtained important results on the theory of optimal coverings of space by balls, on the local theory of the so-called

01-.p65

DELAUNAIS

⟦column⟧

formed regular structures, which are a kind of mathematical models of crystals. Boris Nikolaevich was the head and support of a large family. He loved his grandchildren very much, who adored their grandfather. Boris Nikolaevich took care of them, but he was especially worried about the fate of his eldest grandson, Vadik. Vadim Delone (see http://vadim-delaunay.org), talented poet, handsome, had a tender heart and sympathetic soul. At the age of 18 he became a dissident and human rights activist. At the age of 19 he was convicted of organizing a political demonstration in Moscow. A year after his release, on August 25, 1968, he went out as part of the famous “seven” to Red Square to protest against the introduction of Soviet troops into Czechoslovakia. For the slogan “For your and our freedom,” which he held for a few seconds, Vadim received 3 years of “unfreedom.” Boris Nikolaevich did everything to ease the fate of his grandson. He collected signatures from famous people in defense of Vadim, and with these letters he visited the “highest” offices in Lubyanka. After the trial, as soon as he received permission, he went to visit him in a camp in the north of the Tyumen region. Another object of special care was his wife. was ill and needed care. After Vadim left abroad and the death of his wife, he, already 86 years old, “threw himself into everything”: work, lectures, trips, two hikes a week of 20–40 km each. On one of his most active days, he suffered a stroke: a stroke, almost complete loss of speech, memory, limited mobility, taking into account his age, the doctors were extremely stingy in assessing his prospects. a full life and wins the last, but perhaps the most important victory in life (not without the help of his loved ones, students and colleagues). His lost functions are restored, and he returns to real life. Of course, long hikes were replaced by walks of “only” some 10–15 kilometers, and not through dense forests, but through places with an “industrial landscape”, and not twice, but only once a week. Of course, his performance was not so high, but it was. a full-fledged bright life. However, the “evening of life” came to its natural limit. I will never forget how one gray March day (it was about four months before the end) Boris Nikolaevich took a book out of the bookcase and read one remarkable passage by Poincaré. His breathing was interrupted by excitement, his voice was trembling: “... life is just a fleeting episode between two eternities of death and... in this episode, the past and future duration of conscious thought is no more than a moment. A thought is just a flash of light in the middle of a long night. But this flash is everything.”
