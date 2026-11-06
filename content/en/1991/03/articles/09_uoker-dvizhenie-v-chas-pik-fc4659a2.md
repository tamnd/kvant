---
id: 1991-3-uoker-dvizhenie-v-chas-pik-fc4659a2
issue: kvant_1991_3
year: 1991
number: "3"
title: Rush hour traffic
authors:
  - Уокер Дж.
rubric: raznoe
page_first: 34
page_last: 39
page_labels: 32-37
lang: en
source: kvant_digital
extraction: vision
content_sha256: 28c7367bb0bf72a91b8dd764c3d22478f99e4e1fb7d18d2ea92bb31aa097bfa4
prompt_sha256: draft-1
translated_from: content/ru/1991/03/articles/09_uoker-dvizhenie-v-chas-pik-fc4659a2.md
source_content_sha256: b750488f3fe6d61f70a54d38f236a39772c8cf7da7a0c25c6a736ae2e78f00ab
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 32⟧

TRAFFIC DURING RUSH HOUR

J. Walker

⟦folio 33⟧

---
running_head:
folio:
---

Traffic lights in a small town usually do not require much regulation. Traffic flow through a traffic light system can be random, but red light queues are rarely long. But in a big city, especially during rush hours, careful adjustment is necessary. Without it, the tails of the cars stretch out and block intersections, creating what is called a traffic jam, and it can take hours to free the cars from captivity.

Let's say you have to design a traffic signal system for a one-way street with several lanes. Each traffic light is green for 50 seconds, yellow for 5 seconds, and red for 25 seconds (a typical traffic light for a busy urban area). You may be tempted to increase the green light time and decrease the red light time to "maintain" the flow of traffic. However, we must remember that traffic on perpendicular streets cannot be held back for too long, otherwise long queues will form there.

How to calculate the time for turning on green signals at intersections? It is clear that if you turn on all the green signals at the same time, then movement will only be possible for 50 seconds. Each time the light turns green, traffic will move along the street until all traffic lights switch to red. In order to travel as far as possible, the driver is tempted to speed the car. Large streams of cars traveling at, say, 55 mph (≈90 km/h) through the streets of a densely populated city will resemble automatic racing and will obviously be dangerous.

A better and safer project would be one in which the traffic light at each intersection does not switch to green until the cars in front of the group from the previous intersection are approaching. For example, suppose that a group of cars is at intersection I and is moving towards intersection II. How long after the green light turns on at intersection I should the green light turn on at intersection II? Let $d$ be the distance between two intersections and $v_r$ be the speed you think the group of cars should have (perhaps the speed limit). The required time delay for turning on the green light at intersection II is $d/v_r$. If the distance between intersections is the same, the green signal delay from one intersection to the next is always $d/v_r$, and drivers traveling at $v_r$ will pass through the entire traffic light system without stopping. The scheme works just as well if the distance between intersections is different. You simply consider the desired values ​​of $d$ to determine the time delay for the green signal at a given intersection. Driving a car at a speed greater than $v_r$ through the traffic light system is also free, since you will have to stop at a red light.

The scheme is slightly changed by two factors. The group leader must see the green light turn on before he approaches the intersection, otherwise he will slow down, afraid to pass the red light. Considering this factor, you should reduce the time delay for turning on the green signal by a few seconds. However, if a group of cars stayed at the red light at Intersection I for a few seconds, the lead car would take a few extra seconds to react to the green light there and pick up speed. Thus, the front car does not move at speed $v_r$ the entire distance between intersections. This factor requires increasing the delay time for turning on the green signal by several seconds. In some cases, these two factors can cancel each other out.

All this is shown in figure 1. On the left is a system of traffic lights, on the right are graphs of the paths traversed by cars from the group standing at time $t=0$ in front of the intersection.

⟦folio 34⟧

---
running_head:
folio:
---

Fig. 1. Graphical representation of how a group of cars left at intersection I moves through the traffic light system.

com I. The curved sections of the graphs correspond to the acceleration and deceleration of the movement of cars when switching traffic lights. Note that the traffic light at intersection II turns green a few seconds before the leading car approaches it.

But even with a system of traffic lights that operate with a delay, traffic can become congested. The problem is that if the group has stopped and then starts moving when the green light turns on, they automatically pick up speed not at the same time, but in order of rotation. A starting wave comes from the lidar throughout the group of cars. (You can change the speed of the starting wave by positioning yourself near a stopped group of cars. Determine the length of the group by multiplying the number of cars by the approximate distance between the folded bumpers. Then change the time from the green light to the last car moving. The speed of the starting wave is the length of the group divided by the changed time. It is usually 5 m/s (11 mph.) So, compared to the leader, the last one automatically has to not only drive a longer distance to intersection II, but also have to wait until it gets there. There is a starting wave. Thus, with a long “tail” before the traffic light, the last car will always need a long time to get to the next intersection.

If the end of the group does not have time to pass the green light with the rest of the cars (this is exactly the situation that figure 1), subsequent groups may begin to lengthen. Let us consider the case when the tail part of the cars remains at intersection II, as shown in figure 2. Let's call this part A. While A is waiting at the red light, group B at intersection I receives a green signal and starts moving (situations 2, 3). If the traffic light at intersection II is adjusted to lidar group B (i.e., given that its average speed is less $v_r$), the green light at intersection II is delayed, and the front cars of group B run up to the “tail” of group A before the first automatic Atrons move off. Everything is further complicated by the fact that the last cars of group A must wait until the starting wave reaches them.

Fig. 2. If the green light is delayed at intersection II, the group of stopped cars may increase (C+D is greater than A+B).

⟦folio 35⟧

---
running_head:
folio:
---

As a result, $A$ and $B$ unite, forming a new group at intersection II. It may be too long to complete intersection II. Let $C$ be the tail of the group left by the next red light at intersection II (situation 7 at figure 2). If $C$ is longer than $A$, the situation goes away. While $C$ is turning the red light, the next group approaches from intersection I (let’s call it $D$). Then the merged group of $C$ and $D$ may be longer than the previous union of $A$ and $B$, and as a result the next tail left at intersection II will be longer than $C$.

If, with each signal switch, the new “tail” left at intersection II is longer than the previous one, the situation can quickly become hopeless. Eventually the “tail” becomes so long that it extends to intersection I. Suppose that at this intersection there is a group of cars in front of red traffic light I. When the light turns green, they enter intersection I. Since these cars cannot move until the starting wave from intersection II reaches them, they are in the same place when the light turns red at intersection I. Drivers on the perpendicular street cannot proceed when their traffic light turns green—intersection I is blocked. The queues on side streets are lengthening and other intersections are being blocked. The congestion quickly spreads until the entire area becomes one big parking lot.

A traffic jam can form even with a good traffic light system. However, I was caught in a traffic jam in Cleveland as heavy snow began to fall during the afternoon rush hour. Because the street I was driving on was slippery, the leading cars in the group were driving slowly. The starting waves also moved slower than usual. In about 20 minutes, the “tails” stretched almost to the previous intersections, blocking them. 2 miles along my route and five parallel

Traffic on the Lelny arteries almost stopped. I was a little sold just because the cars on the outer end of the route were gradually moving into the suburbs. As soon as they separated from the group, the starting wave began to move gradually through the two-million detachment and gave me the opportunity to move several machine gun corps forward. A trip that was supposed to take five minutes took over two hours!

The traffic jam situation caused by outside snowfall cannot be alleviated. However, traffic jams caused by unexpected machine group lengths can be avoided if the engineer or computer works together in a normal sequence of signal changes. Let's say that through a remote sensor system you detect a gradual accumulation of automatic traffic at, say, intersection II. Let $A$ be a group of cars detained there at the moment of our togetherness, and $B$ be a group of cars left at intersection I. Depending on what the length of $A$ is, c-

Fig. 3. Factors important in determining the relative timing of green lights at adjacent intersections I and II.

⟦folio 36⟧

---
running_head:
folio:
---

Tuatsyumo can be “discharged” in two ways. It is possible to give green lights at both intersections at the same time; but with a long “tail” $A$ this path may not work. You can turn on the green traffic light at intersection II earlier than at intersection I. Which path should you take? This depends on the correspondence between the length $l$ of the “tail” $A$ and the distance $d$ between the intersections.

If the front cars $B$ move towards the “tail” $A$ at a constant speed $v_r$, they need time $(d-l)/v_r$ to complete this segment (see Fig. 3). Meanwhile, the starting wave moves along $A$ at speed $v_c$, and it takes time $l/v_c$ to reach the rear $A$. In order for the vanguard of group $B$ to reach $A$ at the moment when those cars begin to move, the time between the green lights at intersections I and II must be

$$t = \frac{d-l}{v_r} - \frac{l}{v_c} = \frac{1}{v_r} \left( d-l \left( 1 + \frac{v_r}{v_c} \right) \right).$$

If

$$\frac{l}{d} = \frac{v_c}{v_c + v_r},$$

then $t=0$ - this means that with such a correspondence between $l$ and $d$ intersections I and II should be “opened” simultaneously. At

$$l > d \frac{v_c}{v_c + v_r}$$

time $t$ turns out to be negative, i.e. traffic light II must switch to green light at time $t$ earlier than traffic light I. If

$$l < d \frac{v_c}{v_c + v_r},$$

then the green light turns on first at intersection I. With typical traffic speeds of 10 m/s (22 mph) and a starting wave speed of 5 m/s, simultaneous turning on of the green light is necessary at $l/d=1/3$. If $l/d>1/3$, the green signal at intersection II should be turned on earlier than at intersection I.

We can say that we have found the speed at which the “wave” of turning on green signals moves along the street. If $l/d<1/3$, this wave moves in the direction of the cars and with the same speed as theirs. At $l/d=1/3$ the light turns on green at all intersections. If $l/d>1/3$, the green wave is moving in the opposite direction to the cars.

This result is only a rough estimate because the calculation ignores three facts. The front cars of group $B$ start moving, picking up speed after stopping. Their drivers must see that the tail $A$ has begun to move well in advance of them approaching it, otherwise they will slow down or stop as a precaution. The last cars $A$, of course, must pick up speed before the cars $B$ approach. I hope you enjoy making an accurate calculation that takes these additional factors into account.

How would you design a traffic light system to optimize traffic flow on a two-way street? Is there a way to prevent cars from stopping on such a street? Is it possible to use a comploter to assist the movement of a group of cars through a traffic light system? If so, then you will be able to explore the problem of traffic jams without getting into them.

⟦folio 37⟧

---
running_head:
folio:
---

Physics 9, 10, 11

The note published below “On two methods of interaction” is intended for the classics, the note “On glaciers, pressure cookers and Carnot’s theorem” is intended for the classics, “What the spectrum of the hydrogen atom told about” is equally classic.
In addition, we continue to publish “Selected school problems in physics.”
