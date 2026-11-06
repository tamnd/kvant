---
id: 1991-6-sheronov-rabota-i-izmenenie-energii-idealnogo-gaza-20d30b55
issue: kvant_1991_6
year: 1991
number: "6"
title: Work and energy change of an ideal gas
authors:
  - Шеронов А. А.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 47
page_last: 60
page_labels: 45, 47, 48, 49, 51, 52, 54, 55, 56, 57, 58
lang: en
source: kvant_digital
extraction: vision
content_sha256: 7d6eaa68dd67d5cfa04caae1d174cf5c35c8a14da6a73f1de5f88bf32fd9b947
prompt_sha256: draft-1
translated_from: content/ru/1991/06/articles/16_sheronov-rabota-i-izmenenie-energii-idealnogo-gaza-20d30b55.md
source_content_sha256: b8c1f650c355b5aa54359d2509fc9a068b9b404fa1e12810575f9d92c82c87b7
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 45⟧

---
running_head:
folio:
---

Work and energy change of an ideal gas
A. SHERONOV

In this article we will focus on some features of thermal processes in which the main character is an ideal gas.

As is known, a gas can perform work due to an external source of heat or due to its internal energy. But in any process, the basic correspondence of thermodynamics is satisfied - the law of conservation of energy, or the first law of thermodynamics. Let's write it in the form

$$Q = \Delta U + A$$

— the amount of heat $Q$ supplied to the gas goes to change its internal energy $\Delta U$ and the gas does work $A$ against external forces.

The internal energy $U$ of an ideal gas depends only on the temperature $T$ and is a function of its state. Thus, for one mole of a monatomic gas $U = 3/2RT$, where $R$ is the universal gas constant. Therefore, any (both infinite small and finite) change in internal energy is determined only by the temperature difference between the final and initial states:

$$\Delta U = \frac{3}{2} R \Delta T$$

and does not depend on the method of transition from one state to another. This remains true even if the gas is transferred from the initial equilibrium state to the final equilibrium state as a result of a nonequilibrium, unimaginable process.

Elementary work $\Delta A$, as it is sometimes called, is by definition equal to the product of pressure $p$ and the small change in gas volume $\Delta V$ in two adjacent equilibrium states:

$$\Delta A = p \Delta V.$$

For a finite change in volume from $V_1$ to $V_2$ in some inverse process, the work $A$ is numerically equal to the area under the gas pressure versus volume curve $p = p(V)$, limited by the isochormic $V_1$ and $V_2$. Mathematically this area is equal to

$$A = \int_{V_1}^{V_2} p(V) dV.$$

For a closed cycle, the work of the gas is determined by the area of ​​the internal $p(V)$ forming this cycle. The work of a gas with a finite change in volume, like the work of a gas in a closed cycle, depends on the type of function $p(V)$.

The amount of heat $Q$ supplied to the gas in the reverse process can be expressed through the heat capacity of the gas $C$ and the small temperature change $\Delta T$ by the known correspondence

$$Q = C \Delta T.$$

⟦folio 47⟧

---
running_head:
folio:
---

The efficiency can be written as
$$\eta = \frac{T_1 - T_2}{T_1}.$$

Now let's move on to analyzing some specific characteristic problems.

Problem 1. Find the work done by a mole of an ideal gas in a cycle consisting of two sections of the linear dependence of pressure on volume and isochore (Fig. 1). Points 2 and 3 lie on the isotherm, straight line 1-3 passes through the origin. Temperatures $T_1$ and $T_2 = T_3$ are set.

Work on isochore 1-2 is zero. Work on section 2-3 is equal to the area of ​​the trapezoid. Denoting $V_3/V_2 = \beta$ and taking into account that $p_2V_2 = p_3V_3 = RT_2$, we have
$$A_{23} = \frac{p_2 + p_3}{2}(V_3 - V_2) = \frac{p_2V_3 - p_3V_2}{2} = RT_2 \frac{\beta^2 - 1}{2\beta}.$$
The work on section 3-1 is also equal to the area of ​​the trapezoid. Since line 1-3 passes through the origin and therefore $p_1/V_1 = p_3/V_3$, we get
$$A_{31} = \frac{p_1 + p_3}{2}(V_3 - V_1) = \frac{p_3V_3 - p_1V_1}{2} = \frac{R}{2}(T_2 - T_1).$$
Condition $p_1/V_1 = p_3/V_3$ implies $T_1/V_1^2 = T_1/V_2^2 = T_2/V_3^2$. Therefore, the works $A_{23}$ can be finally written in the form
$$A_{23} = RT_2 \frac{T_2/T_1 - 1}{2\sqrt{T_2/T_1}} = \frac{R}{2} \sqrt{\frac{T_2}{T_1}}(T_2 - T_1).$$
The required work in the cycle is equal to
$$A_\pi = A_{23} - A_{31} = \frac{R}{2}(T_2 - T_1)(\sqrt{\frac{T_2}{T_1}} - 1).$$

Note that for the section of straight line 2-3 connecting the points of the isotherm, as well as for the isotherm itself, the work of the gas is determined only by the ratio of volumes. The work of the gas along a section of an arbitrary straight line passing through the origin of coordinates on the diagram $pV$ is determined only by the temperature difference between the final and initial states.

Problem 2. Find the molar heat of the gas in a process with a linear dependence of pressure on volume.

Let us write the law of conservation of energy in the form
$$C\Delta T = C_V\Delta T + p\Delta V.$$
By condition $p = \alpha V + \beta$, where $\alpha$ and $\beta$ are constants. Taking into account the equation of state of the gas, we find
$$RT = \alpha V^2 + \beta V.$$
From here we find the connection between a small change in temperature $\Delta T$ and elementary work $p\Delta V$:
$$R\Delta T = (2\alpha V + \beta)\Delta V.$$
Then finally for the desired heat capacity we obtain
$$C = C_V + \frac{p\Delta V}{\Delta T} = C_V + R \frac{\alpha V + \beta}{2\alpha V + \beta}.$$
It can be seen that the heat is variable and, with a negative angular coefficient of the straight line $\alpha$, can change its sign. This means that such areas should be handled carefully (for example, in problems where it is necessary to find efficiency). The reader is recommended to independently monitor the change in heat capacity depending on the location of the section on the plane $pV$. We will limit ourselves to the replacement that for an arbitrary straight line passing through the origin of coordinates ($\beta = 0$), the heat capacity is constant and equal to $C_V + R/2$.

Problem 3. A mole of an ideal gas from the initial state 1 with a temperature $T_1 = 100$ K, located through the tubbina into an empty vessel, goes into state 2, performing non-actor work $A_{12}$. This transition occurs when the body is brought in or out. Then the gas is compressed in two processes, returning to its original state.

⟦folio 48⟧

---
running_head:
folio:
---

First you should go through process 2-3 with a linear dependence of pressure on volume, and then in the advabatic process 3-1 (Fig. 2). Find the work done by the gas during expansion through the turbine in transition 1-2, if in the process of rolling 2-3-1 the work done on the gas is $A=1090$ J. It is known that $T_2=T_3$, $V_2=2V_3$.

The process of expansion of gas through a turbine into an empty vessel is non-equilibrium, so that all masses of gas at any moment cannot be attributed to some identical pressure and the same temperature. However, if the initial and final states are in equilibrium, then, based on the law of conservation of energy, it can be argued that the gas does work by changing its internal energy:

$$A_{12} = -(U_2 - U_1) = \frac{3}{2} R(T_1 - T_2).$$

According to the condition, the work done on the gas rolling down is equal to

$$A = A_{13} + A_{32} = \frac{3}{2} R(T_1 - T_3) + RT_2 \frac{(V_2/V_3)^2 - 1}{2V_2/V_3} = \frac{3}{2} R(T_1 - T_2) + \frac{3}{4} RT_2.$$

Here we used the equalities $T_2=T_3$ and $V_2/V_3=2$ and the expression for work in section 2-3 from problem 1. From the resulting expression we find the temperature $T_2$, and then the work $A_{12}$:

$$A_{12} = 2A - \frac{3}{2} RT_1 \approx 935 \text{ Дж}.$$

Task 4. The efficiency of the cycle 1-2-4-1, consisting of three sections of the linear dependence of pressure on volume (Fig. 3), is equal to $\eta_1$. The efficiency of the 2-3-4-2 cycle is equal to $\eta_2$. Set the cycle efficiency to 1-2-3-4-1. All sections of the linear dependence have positive equations.

In all areas, temperature is a monotonic function of volume, i.e., it either increases or decreases. On the other hand, it can be shown (see Problem 2) that in each section the heat, although it changes in value, does not change its sign. This means that in each section heat is either supplied or removed. For the corresponding cycles we have

$$\eta_1 = 1 - \frac{Q_{24}}{Q_{12} + Q_{41}},$$

$$Q_{12} + Q_{41} = Q_{24} \frac{1}{1 - \eta_1},$$

$$\eta_2 = 1 - \frac{Q_{23} + Q_{34}}{Q_{42}},$$

$$Q_{23} + Q_{34} = Q_{42}(1 - \eta_2).$$

Required efficiency

$$\eta = 1 - \frac{Q_{23} + Q_{34}}{Q_{41} + Q_{12}} = \eta_1 + \eta_2 - \eta_1 \eta_2.$$

Exercises

1. Find the work done by a mole of an ideal gas in a cycle consisting of four sections of the linear dependence of pressure on volume (Fig. 4). The vertices of the cycle lie on two isotherms with given temperatures $T_1$ and $T_2$. Techniques 1-2 and 3-4 pass through the origin, $V_2=V_4$.

2. A mole of a monatomic ideal gas from the initial state 1 with a temperature $T_1 = 100$ K, expanding through a turbine into an empty vessel, does some work and goes into state 2. This process occurs without the supply or removal of a body. Then the gas is skimmed in the process of 2-3 linear dependence

⟦folio 49⟧

---
running_head:
folio:
---

pressure from the volume and, finally, along the 3-1 isochore returns to the initial state (Fig. 5). Find the work done by the gas during expansion through the turbine in the 1-2 transition, if in the 2-3-1 process the amount of heat $Q=72$ J is ultimately supplied to the gas. It is known that $T_2=T_3$ and $V_2=3V_1$.

3. A mole of an ideal gas undergoes a closed cycle consisting of a process of linear dependence of pressure on volume, isobar and isochore (Fig. 6). Find the amount of heat

diverted from gas in areas where its temperature decreases. It is known that $T_1=T_2$ and $p_1=4p_3$. The bypass location is indicated by arrows. Temperature $T_1$ is considered known.

4. The efficiency of cycle 1-2-3-1 is $\eta_1$, that of cycle 1-3-4-1-$\eta_2$. Find the efficiency of the cycle 1-2-3-4-1 if sections 2-3 and 4-1 are adinabats, 1-3 are isotherms, 1-2 and 3-4 are abutments with positive angular coefficients (Fig. 7).

Division with remainder and modulo comparisons

(For the beginning, see p. 36)

$(ak)n \equiv n \equiv bk(\text{mod } m)$,
from where we immediately get
$n = bk + ml$,
where $l$ is an arbitrary integer.
The question arises, how to find $k$ in a specific situation?

For not too large $m$ this problem can be solved quite simply (by simple selection). We will talk about the general solution to this and many other problems in the next article.

Task 5. Solve the comparison
$32n \equiv 7(\text{mod } 37)$.

Solution. Since $32 \equiv -5(\text{mod } 37)$, we come to the comparison
$5n \equiv -7 \equiv 30(\text{mod } 37)$

or
$n \equiv 6(\text{mod } 37)$

Towards the solution of comparison of evidence, the problem of solving linear equations with integer coefficients in integers.

Task 6. Find all pairs of integers $x$, $y$ satisfying the equation $7x-23y=131$.

Solution. Since $23 \equiv 2(\text{mod } 7)$, we get the comparison $2y \equiv -131(\text{mod } 7)$ or $2y \equiv 9 \equiv 2(\text{mod } 7)$, hence $y \equiv 1(\text{mod } 7)$.

So $y=7k+1$, where $k$ is an integer. Now you can easily find $x$:

$7x-23(7k+1)=131$,

where
$7x=154+23 \cdot 7k$,

i.e.
$x=22+23k$.

In conclusion, we suggest you solve several equations.

Exercises
30. Solve comparisons
a) $17x \equiv 19(\text{mod } 37)$,
b) $147x \equiv 63(\text{mod } 29)$.
31. Solve equations in whole numbers
a) $7x+8y=1$,
b) $257x+18y=175$.
32. Solve systems of equations in whole numbers
$$\begin{cases} 3x+5y-7z=1, \\ 4x+9y+11z=2. \end{cases}$$

A. Egorov

⟦folio 51⟧

---
running_head:
folio:
---

ROUNDING IN THE BLOOD
(fantasy story)

G. BIR

“Then I mixed the leukocytes with my blood, drew it into a syringe and injected it all back into myself. “He pulled back the top of his shirt and smiled uncertainly. “I asked them to do everything possible, communicating with him at the highest level that znisms and the like allow. After which they moved on with their lives.

— Did you ask them to be fruitful and multiply? Get better? — I repeated his phrase.

“I thought they had developed some of the characteristics that were present in biochili at the stage of intestinal bacteria.” Leukochki could already communicate with each other, releasing chemically encoded memory areas into the environment. And they probably found ways to absorb other types of cells or transform them without killing them.

- You're crazy.

- But you yourself saw the image on the screen! Edward, I haven't been sick since then. I used to catch colds all the time, and when I got a tan I felt just fine.

- But they are inside you and constantly find something, change something...

- And now what group is no deeper than you or me.

-You really are not normal.
He shrugged.

- In short, I was kicked out. They apparently decided that I was trying to take revenge for the way they dealt with my work. Therefore, I was kicked out of the laboratory, and until now I had no real opportunity to find out what was happening in my body. A month has already passed.

- And you... - I kept up with the agreements that were surpassing each other. - You lost everything because they improved your fat metabolism. The bones have become stronger, the spine has been completely rebuilt...

“My back doesn’t hurt at all now, even if I sleep in a very uncomfortable position.”

“Your heart doesn’t look right either.”

“I didn’t agree on the heart,” he said, carefully examining the image on the screen. - And about fat... I thought about that. They could very well improve my metabolism. I never feel headachey these days. My eating habits have not changed that much - I still want what I always wanted - for some reason I only give him healthy foods. Apparently they haven't figured out what my brain is like yet. They have mastered the glandular system, but have not yet realized the global picture, if you understand what I mean. They don't yet know that I am me. But what reproductive organs are, they agreed to simply replace them.

I glanced at the screen and the eye's response.

“No, outwardly everything looks fine,” he chuckled. “But how do you think I picked up this beauty Candis?” She was simply counting on a one-time adventure with a techie. Even then I already looked good: no tan, but already built and dressed appropriately. She, you see, had never come across a techie before, so she decided to try it for fun... But my little geniuses didn’t let us sleep until almost the morning, and every time they became smarter. I was in a fever.

The smile disappeared from his face.

“But one day I felt muashka running all over my skin. I got really scared then and decided that the experiment was getting out of control. In addition, I was worried about what might happen when they overcome the blood-brain barrier and learn about me, about the real functions of brain cells. So I started a campaign of containment. As far as I understood, they were trying to penetrate the skin, because the surfaces of the gasket

⟦folio 52⟧

---
running_head:
folio:
---

It is much easier to create communication channels than to establish circuits through or bypassing organs, mencules and vessels. It was easier on the skin. I had to buy a quartz lamp... - Then he caught my surprised glance. — In the laboratory, we destroyed proteins in biochips by exposing them to ultraviolet irradiation, and I alternated a fluorescent lamp with a quartz lamp. As a result, they do not climb to the surface, and I get a great tan.

“You can still get skin cancer,” I added.

“I think they themselves will do everything they need to do to protect me.” Like police patrols.

- OK. I served you, you told me a story that is hard to believe... but what do you want from me now?

“I'm not as carefree as I might seem, Edward.” I still have anxiety and I wish there was some way to limit them before they found out about my brain. Just think: there are now trillions of them, and each one is no more stupid than me. They cooperate to a certain extent, so I may be the smartest creature on the planet, but in reality they still have a long way to go. I wouldn’t want them to seize power over me.” He laughed, and an unpleasant chill ran down my spine. “Or they stole my soul... So I ask you to think of some way to limit them.” Maybe these little devils can be shaken off their heads? Think about it.” He handed me a piece of paper with his address and phone number, then went to the keyboard, removed the image from the screen and erased the survey data. “For now, no one but you should know anything.” And please... hurry up.

Virgil left only at three in the morning. Before that, I took the cover from him for analysis, then shook his damp, trembling palm, and he jokingly warned me not to accept the samples inside.

Before leaving home on my own, I made arrangements for an analysis, the results of which were ready the very next day. I got them during the palm break, then destroyed everything. I did this completely mechanically, like a robot. Only after five days and almost as many sleepless nights did I accept what I had seen. His blood turned out to be completely normal, except that the machine revealed an infection: a high level of leukitis - white blood cells - and histamines. On the fifth day I finally believed.

Gail got home before me, but that evening it was my turn to cook dinner. She put one of the children's discs on the player and showed me examples of video computer art that her debtors had created. I watched silently. Dinner also passed in silence.

That night I had two dreams at once - apparently a sign that I had finally accepted the facts. During the first one, from which I constantly tossed and turned and crumpled everything up, I had the destruction of the planet Krypton, Superman’s home world, where billions of supergenes perished in the fire. Most likely, this nightmare was brought about by the sterilization of the blood samples that I took from Virgil.

The second dream was worse. I dreamed of the huge city of New York raping a woman. In the end, she gave birth to many small city fetuses, wrapped in translucent film and filled with wings after a difficult birth.

On the morning of the sixth day I called Virgil. He answered after the fourth breast.

“I have some results,” I said. “Nothing final, but I would like to talk to her.” Not by phone.

“Okay,” he answered, and his voice conveyed fatigue to me. “I’m judging at home for now.”

Virgil's apartment is in a luxury high-rise building on the lake. I took the elevator up to it, looked at the advertising chatter at the heads with pictures of goods, available apartments and the owner of the building discussing social events for the current week.

Virgil opened the door and motioned for me to come inside. He was wearing a long-sleeved checkered robe and homemade slippers. He held an uncapped pipe in his hand. He silently walked into the room and sat down in a chair; his fingers twirled the pipe without ceasing.

“You have an infection,” I said.

- Yes?

“That’s all I could learn from the tests.” I don't have access to e-juices.

“I didn’t think it was actually an infection,” he said. “After all, these are my own cells.”

⟦folio 54⟧

---
running_head:
folio:
---

other individuals. Equals. Chiefs. Subordinates.
“Virgil, I’m listening attentively, but I really think that you should go to the hospital.”
“This is my wedding, Edward,” he said. “I am following them.” They are amazed at the new horizons that have opened up...
Virgil fell silent again. I squatted down next to his chair and rolled up the sleeve of my robe. His whole arm seemed to be criss-crossed with white lines. I was about to call an ambulance when he suddenly stood up and stretched.
“Have you ever wondered,” he asked, “how many cells we kill every time we make even a simple movement?”
“I’ll call a car,” I said.
“No,” he said firmly. “I said that I’m not sick.” And I want to be able to manage myself. Do you know what they'll do to me in the hospital?... It's as if cavemen started reading completions the same way they repair their stone axes. Farce...
“Then what the hell am I doing here?” I asked, angry. “After all, I can’t help you.” I'm such a caveman.
“You’re a friend,” Virgil said, looking into my eyes, and I had the mistake that he wasn’t the only one looking in my direction. “I need you for company.” He laughed. “Although in fact, I’m by no means alone.”
Over the next two hours, he paced around the apartment, touched things, looked out of the windows, then slowly, leisurely prepared lunch.
“You know, they can really be mistaken in their own thoughts,” he said around noon. “I mean the cytoplasm.” Apparently, it has its own will, a kind of subconscious life - in contrast to the mind that the cells acquired very recently. They hear something similar to the chemical “noise” of molecules separating and returning to their place.
At two o'clock I called Gail and said that I would be late. I was literally shaking from tension, but I tried to speak calmly.
-Remember Virgil Ulam? I'm with him now.
“Is everything okay?” she asked. Yes, where is it...
“Everything is fine,” I replied.
Virgil looked into the room as I said goodbye to Gail and hung up.

“This is a whole culture!” he proclaimed. “They are constantly swimming in a sea of ​​information.” And they constantly introduce something new there. It turns out to be your own “gestalt”. The strictest Czech Republic. For cells that interact with others incorrectly, they send special phages. Specially manufactured viruses that target specific cells or groups. There is absolutely no protection against them. Virus against the cell, it bursts, explodes and disintegrates. But this is not tyranny. I think they actually have much greater freedoms than in a democracy. In the sense that they are so different from each other. Can you imagine it? They distinguish from each other even greater than us.
“Wait,” I said, taking him by the shoulders. “Virgil, you put too much on me at once.” I can't do this anymore. I don’t understand anything and don’t really believe it.
- Even now?
- OK. Let's say you give me the uh... correct interpretation. Honest. And it's all true. Have you thought about the consequences? What does all this mean and what can it lead to?
He walked into the kitchen, poured a glass of water, returned it and stood next to me. The childish enthusiasm on his face gave way to sober concern.
“I always had a bad idea of ​​the future.”
- Aren’t you scared?
- It was scary. But now I’m not sure.” He fiddled with the waist of his robe. “You know, I wouldn’t want you to think that I was going around you, over my head or something like that, but yesterday I met with Michael Bernard.” He settled me in his private clinic and took samples for testing. He told me to stop irradiating myself with quartz-lima. In the middle of the morning, right before you, he called me and said that everything was confirmed. But the requester is not to say anything.” Virgil fell silent, and a dreamy, self-absorbed expression appeared on his face again. “The purpose of the city is made of cells... Edward, they are pushing channels through the tissues of the fimbrics to disseminate information...”
“Stop it!” I couldn’t resist. “What else is confirmed there?”
“As Bernard said, my oraism showed “extremely enlarged macrophagocytes.” And he believed

⟦folio 55⟧

---
running_head:
folio:
---

-What is he going to do?
- Don't know. I think he can convince Genetron management to resume work in my laboratory.
- Is this what you want?
“It’s not just about the laboratory. Now I'll show you. When I stopped using the lamp, I changed even more.
He unbuttoned his robe and threw it to the floor. His entire body was lined with white intersecting lines. On the back along the spine, these lines have already begun to form a solid ridge.
- Good God! - I got it right.
- A little more - and I will no longer be able to appear anywhere except the laboratory. It's impossible to be in public like this. And in the hospital, as I said, they simply won’t understand what to do with me.
“But you... You can talk to him, tell him not to act so quickly,” I suggested, realizing that I was saying the scales of the page of the thing.
- Yes, I can. But they won't necessarily listen to me.
“I thought you were rich to them or something.”
“Those who connected to my neurons are actually not very important figures. Just researchers or something like that. They know about my existence, they know who I am, but this does not mean that they have convinced those who stand on the upper steps of the Perkhinsky ladder.
— Are they having debates?
- Looks like it. However, everything is not as bad as you think. If they open my laboratory again, I will have both a home and a workplace.” He looked out the window, as if he was looking out for someone below. “I don’t have anything else.” Except them. And they're not afraid of anything, Edward. Never in my life have I felt such a kinship with anyone. - Again the blissful smile. - I am responsible for them. I'm like a mother to them.
“But you don’t know what they will do next.”
He shook his head.
“Indeed, Virgil.” You said that this is civilization...
- A thousand civilizations!
- Especially. And civilization, as we know, ends badly. Wars, environmental pollution...
It was as if I was grasping at straws, trying to calm the growing panic. I clearly lacked the experience and competence to comprehend what had happened in all its stunning magnitude. The same applied to Virgil. When it comes to global problems, it is difficult to even imagine a person less insightful and capable of mature decisions.
“But I’m the only one at risk.”
“You can’t know anything new for sure.” Come on, Virgil, look what they do to you!
- With me! Only with me! - he shouted. - With no one else!
I pointed with my head and raised my hands, admitting my defeat.
- OK. Well, Bernard will open a laboratory, you will move there and turn into an experimental guinea pig. What should I do?
- They don't harm me. I'm more than good old Virgil Ulam now. I am the whole galaxy, damn it! Super-parent!
“Perhaps you mean, superincubator?”
He shrugged, not wanting to get involved in an argument.
All this turned out to be more than enough for me. Having come up with some useful excuses, I said goodbye to him and left. Then he sat for a long time in the cold downstairs, calming his nerves... Someone should make sure of him. But who will Virgil listen to? He saw Bernard...
And what’s more, Virgil’s story was not only convincing, but also very interesting. People like Vernadd obcino do not push the virgils of the ulama of this world to the need for action - except in those cases when they feel that the situation can be turned to their advantage.
Just a contract, but I decided to try it. The cook's phone came up, stuck a credit card into the slot and called Genetron.
“Please find Dr. Michael Vernadd,” I turned to the secretary.
- Excuse me, who is asking him?
- This is his secretary from Telephone Service. I received an extremely important call, and its beeper apparently does not work.
After several minutes of waiting, Vernadda answered the phone.
-Who the hell are you? I don't have any secretary at Telephone Service.
— My name is Edward Milligan. I'm a friend of Virgil Ulam. Well, we need to meet and discuss something.

⟦folio 56⟧

---
running_head:
folio:
---

We agreed to meet the next morning. On the way home, I tried to come up with some excuse for not going to work one more day, because I could not think at all about medicine and the patients who deserved my passionate attention.

I experienced guilt, familiarity, anger and fear.

It was in this state of mind that Gail found me. I put on a mask of calm, and we cooked dinner together. Then, hugging each other, we stood for a long time at the window overlooking the bay, watching the city lights appear in the twilight. A few of the starlings that had remained for the winter still lay down on the lawn in the last glimmer of daylight, then flew away with a gust of wind that shook the windows.

“Did something happen, Edward?” - Gail asked softly. “Are you going to tell me yourself or are you going to continue to pretend that everything is fine?”

“I’m just not in a good mood,” I answered. - Nerves. Working in a hospital.

“Oh God, I understand,” she said, sitting down in the cross. “You decided to divorce me and marry that woman named Baker.”

Mrs. Baker, whom I once told Gail about, weighed three hundred and sixty feet and did not realize that she was pregnant until she was five months old.

“No,” I said listlessly.

- Oh, great happiness! - Gail declared, lightly touching her forehead. “But if we pull everything out of you with kleets, you can go crazy.”

“You see, I can’t talk about this yet, so...” I stroked her hand.

“How poisonously hearty we are,” she said, getting up. “I’ll get some tea.” Will you?

She was offended, and I myself was mucilia because I couldn’t tell anyone anything. Although why not open up to her? My old friend is turning into a galaxy...

Instead, I cleared the table. That night I couldn’t sleep for a long time. I sat in bed with the pillow behind my back and looked at Gail. I tried to figure out which of everything I know is reality and which is speculation.

I am a doctor, I told myself. A profession related to science and technology. And I am supposed to be immune to such futuristic shocks.

Virgil Ulam turns into a galaxy.

How would I feel if I had a trillion tiny Chinese people transplanted into me? I smiled in the darkness and at the same moment almost screamed: the creatures that lived inside Virgil were completely alien to us, so alien that I or Virgil could not even count on a quick understanding. Maybe we will never eat them at all.

However, this is all speculation, and I knew very well what actually belongs to reality. Bedroom. City lights shining through tulle curtains. Sleeping Gail. This is very important. Gail sleeping in bed.

I got that same con again. This time the city entered through the window and attacked Gail. Otromny, shpapsky, creeping, all in lights - he knighted something in a language I did not understand, consisting of machine gun breasts, the noise of a sick toll and the thunder of a line. I tried to fight him, but he still got to Gail... and turned into a stream of twinkling stars scattered across the bed, throughout everything that surrounded us. I woke up abruptly and didn’t sleep again until dawn. He stood up, dressed with Gail and kissed her breathlessly, feeling the trace reality of gullible people's lips.

Then he went to meet Bernard. An office in one of the large prison hospitals was given to him. I took the elevator to the sixth floor and saw firsthand what fame and fortune can do.

A beautifully appointed room, exquisite silk prints adorning wood paneling, chromed metal and glass furniture, cream colored carpet, Chinese bronze, polished cabinets and tables.

Bernard offered me a cup of coffee. I didn't refuse. He sat at the side of the desk, I sat opposite him with a cup of coffee in my damp palms. He was wearing a serial with a needle bone. Gray hair and a clear profile completed the picture. At sixty, he has great help from Leonard BernSTRAN.

“About our promised acquaintance...” Bernard began. “Mr. Ulam.” A brilliant scientist and, I dare say, brave.

- He's my friend. And I'm worried about what will happen to him.

Bernard left me with a raised finger:

“But this brave man committed a reckless, idiotic act. Togo,

⟦folio 57⟧

---
running_head:
folio:
---

what happened to him simply could not be allowed to happen. Circumstances forced him to take such a step, but this, of course, is not true. However, what's done is done. As far as I understand, he told you everything.
I nodded.
- He wants to return to Genetron.
- Of course. All his equipment is there. And apparently, his house will be there until we sort out this problem.
- You’ll figure it out... How? And what is the use of this? — A slight headache prevented me from thinking.
“Oh, I can imagine many applications for small, ultra-dense, bio-based computers.” Really, it's not that difficult. Genetron has already made several important discoveries, but here is a completely new promising direction.
-What do you mean?
“I’m not in the right to discuss prospects,” Bernard smiled, “but it will be something completely revolutionary.” And we just need to put Mr. Ulam into laboratory conditions. We must also conduct experiments on animals. Of course, you'll have to start all over again. The fact is that uh... Burngil's colonies cannot be transferred to another organization: they are based on his leukots. Therefore, we will need to create new colonies that will not cause an immunological reaction in other organizations.
- Like an infection? - I asked.
- I think such a comparison can be made. But Burngil is not infected.
- My tests showed that this is not so.
“Apparently, the equipment was mediating those sections of information flows that float in his circulatory system. How do you think?
- I don't know.
“Listen, I'd like you to stop by our lab when Burngil moves in.” Your experience may be useful to us.
Us. This means he is at one with Genetron. Is he able to maintain objectivity?
—What is your own interest in this whole matter?
“Edward, I have always been at the forefront of my science. And I don’t see any principle why not work here. With my knowledge of the functions of the brain and nervous system, after all the neuroscience research I've done...
— You could help Genetron

avoid a proper investigation,” I said.
- Very rude. Too rude and, moreover, unfair.
- Maybe. But I agree. I'd really like to visit the lab when Burngil moves there. Of course, if, despite all my rudeness, the invitation still stands.
Bernard looked at me with a sharp look. He understood that I would not play on his side, and for a moment these thoughts appeared completely absent on his face.
- Certainly.
He stood up and extended his hand to me. His palm was wet. Although Bernard tried not to show it, he was just as nervous as he was.

I returned home and sat there until noon. I read and tried to make sense of my thoughts. Come to some conclusion. In particular, to decide what is real and what I should protect.
Changes a person can take only in certain doses. Innovation is good, but little by little and gradually. They cannot be imposed by force. Everyone has the right to remain the same until they decide they are ready.
The greatest scientific discovery since...
And Bernard will impose it by force. "Genetron" too. The thought of this seemed unbearable. “Neoludite,” I called myself. Indeed, a civil charge.
When I pressed the button with Burngil's apartment number on the intercom panel in the cold high-rise building, he answered almost immediately.
“Yes,” he said excitedly. “Get up.” I'm in the bathroom. The door is not locked.
I entered the apartment and moved along the corridor of the bathroom. Burngil did in the pinkish water, plunging all the way to the top. He smiled absently and clasped his hands.

(End to follow)
Translation from English by A. Korzhenevsky

⟦folio 58⟧

---
running_head:
folio:
---

This article opens a series of publications on finding and analyzing prime numbers using the most popular and inexpensive programmable microcomputers (PMKs) from B3-34 to MK-61 or microcomputers MK-85 (with the BASIC language). In each article, the reader will be offered one legitimate program. They allow you to generate prime numbers, find prime divisors of natural numbers, explore integer sequences with “abnormal” content of prime numbers, build educational and cognitive constructions from prime numbers and algorithms for their production.
But be warned: reading the articles provided without simultaneously checking the programs they contain (for example, on MK-61) will be ineffective. You can even tell Silica: it will be useless.
