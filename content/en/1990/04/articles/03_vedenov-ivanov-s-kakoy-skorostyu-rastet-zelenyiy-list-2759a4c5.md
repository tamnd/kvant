---
id: 1990-4-vedenov-ivanov-s-kakoy-skorostyu-rastet-zelenyiy-list-2759a4c5
issue: kvant_1990_4
year: 1990
number: "4"
title: At what speed does a green leaf grow?
authors:
  - Веденов А.
  - Иванов О.
rubric: osnovnye-stati
page_first: 14
page_last: 20
page_labels: 12-18
lang: en
source: kvant_digital
extraction: vision
content_sha256: 6af6e013744aec8fc7281d01e504f3562edb2710821d1acd39ecd76a4999d543
prompt_sha256: draft-1
translated_from: content/ru/1990/04/articles/03_vedenov-ivanov-s-kakoy-skorostyu-rastet-zelenyiy-list-2759a4c5.md
source_content_sha256: 097230025b6e98d859c25096064f777353152af03616109decd3d4c4bce37b2e
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 12⟧

---
running_head:
folio:
---

In our observations of the amount of greenery in the field, we noticed a change in the amount of greenery at regular intervals (empty for simplicity, this will be one day).
The ratio of the change in the amount of greenery $\Delta K_t$ for this period of time (for any day) to the available amount of greenery $K_t$ on this day will be a constant value equal to the threshold for perceiving a change in the amount of greenery:

$$\frac{\Delta K_t}{K_t} = \delta_\pi^K.$$

From this relationship we can obtain an equation for the rate of change of the amount of greenery

$$v_t = \frac{\Delta K_t}{\Delta t} = \frac{\delta_\pi^K K_t}{t_\pi} = CK,$$

(1)

where $C = \delta_\pi^K / t_\pi$ is a constant value equal to the threshold of perception of a change in the amount of greenery by the time during which the change in the amount of greenery in a given field reaches the threshold (for us this is one day).

The resulting expression shows that the growth rate of the amount of greenery is proportional to the amount of already existing greenery. (A similar expression is obtained when describing the radioactive decay of nuclei. In this case, the decay rate, i.e., the number of nuclei decaying per unit time, is proportional to the number of remaining nuclei. But, unlike the growth of plants, for the decay of nuclei on the right side of the equation, similar to (1), there is a minus sign, since the number of the first initial nuclei decreases with time.) In all cases when the rate of change of any quantity is proportional to the quantity itself, the dependence of the quantity under consideration on time has an exponential character. In our case, this means that by time $t$ the amount of greenery can be found as

$$K_t = K_0 e^{Ct},$$

(2)

where $K_0$ is the initial value of the amount of greenery at $t = 0$, and $e = 2,718$.

To show how equation (1) yields the exponential

time dependence (2), the following reasoning adjustments can be made. Let at the initial moment of time $t_0 = 0$ the value of the amount of greenery be equal to $K_0$, and we are interested in the value $K_t$ after time $t$. Divide the time interval $0 - t$ into $N$ equal periods of time long $\tau (\tau = t/N)$ and we will record the amount of greenery at times $t_0 + \tau$, $t_0 + 2\tau$, etc.

After time $t$ after the initial moment $t_0 = 0$ the amount of greenery can be found as

$$K_1 = K_0 + \Delta K_0 = K_0 + v_0 \tau = K_0 + K_0 C \tau = K_0 (1 + C \tau)$$

(in this time interval we assumed the growth rate to be constant and equal (see (1)) $v_0 = CK_0$); similarly, after time $2\tau$

$$K_2 = K_1 + \Delta K_1 = K_1 + v_1 \tau = K_1 + CK_1 \tau = K_1 (1 + C \tau) = K_0 (1 + C \tau)^2$$

(the growth rate is constant and equal to $v_1 = CK_1$). The value we are interested in $K_t$ after time $t = N\tau$ can be found as

$$K_t = K_N = K_0 (1 + C \tau)^N = K_0 \left(1 + \frac{Ct}{N}\right)^N = K_0 \left(1 + \frac{1}{M}\right)^{M C t} = K_0 \left(1 + \frac{1}{M}\right)^{M C t},$$

where we introduced the notation $M = Ct/N$ (M is a dimensionless quantity).

It is clear that the value $K_t$ will be more accurate, the more often we carry out intermediate calculations, i.e., the greater $N$ is (after all, the growth rate

⟦folio 13⟧

---
running_head:
folio:
---

changes continuously in time, and the smaller $\tau$, the more we substitute the value $v_0, v_1, \dots$ to the actual value of the speed). If you infinitely increase $N$ (i.e., infinitely decrease the time interval $\tau$), then $M$ will tend to infinity, and the values ​​of $(1 + \frac{1}{M})^M$ at $M \to \infty$ tend to a constant, approximately equal to 2.7182828 (for example, $(1 + \frac{1}{100})^{100} = 2,7048$; $(1 + 0,001)^{1000} = 2,7169$). The number 2.7182828... in mathematics is represented by $e$.

Thus, we have shown that at the initial stage, plant growth over a certain period of time occurs according to an exponential law. Experimental studies confirm that under constant external conditions (constant light, temperature, air humidity, regular watering, well-prepared soil), the weight and size of the entire plant and its individual parts at the initial stage of growth change exponentially over time. figure 1 shows the results of experiments on growing wheat in an aqueous solution of nutrients. On this graph, the scale along the abscissa axis is linear, and along the ordinat axis it is logarithmic, i.e., the days that have passed since the beginning of growth are plotted on the horizontal axis at equal distances, and not the values ​​of the measuring quantities, but the logarithms of these values ​​are plotted on the vertical axis.

Using a logarithmic scale in cases where the dependence of a quantity on an argument is close to exponential $y = Ae^{Cx}$ results in the graph taking the form of a straight line. Indeed, the value $\ln y$ plotted on the graph along the ordinat axis is a linear function of the argument $x$ -

$$\ln y = \ln A + Cx,$$

and the graph of a linear function is a straight line. From this graph it is easy to determine the constant $C$ - it is equal to the ratio of the increment $\Delta(\ln y)$ to the increment of the argument $\Delta x$.

Fig. 2.

So, from figure 1 it is clear that starting from the first day after emergence for three weeks, the total weight of the plant $m$, the dry weight of the plant $m_0$ (i.e. the weight of the organization of the substance remaining after drying), the dry weight of the leaves $m_{0,n}$, the area of ​​the leaves $S_n$ change exponentially with time. In nature, exponential growth is a common phenomenon. An example would be the increase in the number of bacteria or single-celled organisms in a state of sufficient nutrition. In this case, exponential growth has a simple explanation. A bacterium or individual cell makes two after a certain time $\tau$. Therefore, their number changes over time as follows: $n_\tau = n_0 \cdot 2^{t/\tau} = n_0 e^{Ct}$, where $C = \frac{\ln 2}{\tau}$.

Let's find a physical explanation for the exponential growth of plants and determine the constant $C$ growth rate from the laws of conservation of matter and energy. First we need to build a plant model that is close to reality and convenient for our research. The problem of choosing a model will always arise in the physical description of the phenomena around us. The model should highlight the main features of an object or phenomenon that are sufficient to describe the processes that intersect with us. Let's take this model of a plant. We will assume that it consists of one leaf (the area of ​​which is equal to the area of ​​all its leaves), a stem and a root (Fig. 2) and the relation

⟦folio 14⟧

---
running_head:
folio:
---

$$\frac{m}{m_0} = \frac{m_\pi}{m_{0\pi}} = \alpha$$
($m_\pi, m_{0\pi}$ - total and dry weight of the leaf). In addition, we will consider constant the values ​​of leaf thickness $d$ and the ratio of the dry mass of the leaf to the dry mass of the whole plant:

$$\frac{m_{0\pi}}{m_0} = \varepsilon.$$

(Such assumptions can be made from quantitative observations at the stage of exponential growth of herbaceous plants. Of course, such a model cannot be used to describe the growth of other plants. For example, in trees, the ratio of the mass of leaves to the mass of the entire plant is a variable value.)

From a biology course, you know that a plant increases its mass through the process of photosynthesis - organic substances are formed from carbon dioxide contained in the air and water contained in the plant when the plant leaves absorb light energy. The amount of dry organic matter $\Delta m_0$ formed is proportional to the absorbed light energy $\Delta E$:

$$\Delta m_0 = \gamma \cdot \Delta E.$$ (3)

If the intensity of the luminous flux $I$ (light energy incident per unit area per unit time) is constant, then

$$\Delta E = I S_\pi \cdot \Delta t.$$ (4)

Using our plant model, we express the leaf area through the dry mass of the plant $m_0$. The area of ​​the sheet is equal to the volume of the sheet divided by its thickness - $S_\pi = V_\pi / d$. We find the volume through the wet weight of the sheet and its density - $V_\pi = m_\pi / \rho$ ($\rho \approx 1 \text{ г/cm}^3$), and express the wet weight of the sheet through $m_0$ using the formulas for the coefficients $\alpha$ and $\varepsilon$: $m_\pi = \alpha \varepsilon m_0$. As a result we get:

$$S_\pi = \frac{m_0 \varepsilon \alpha}{\rho \alpha}.$$ (5)

Now, combining expressions (3)—

(5), we write the equation for the rate of change in the amount of dry organic matter:

$$\frac{\Delta m_0}{\Delta t} = \frac{\gamma \varepsilon \alpha I}{\rho d} m_0.$$

Consequently, the mass of dry matter changes over time as

$$m_{0t} = m_0 e^{\gamma \varepsilon \alpha I / \rho d},$$

and the growth rate constant is equal to

$$C = \frac{\gamma \varepsilon \alpha I}{\rho d}.$$ (6)

So, the growth rate constant is proportional to the intensity of light incident on the plant and depends on the parameters $\alpha$, $\varepsilon$, $d$ and $\gamma$. To solve, $\alpha$, $\varepsilon$ and $d$ can be determined using the graph on figure 1 by taking the value of $m$, $m_0$, $m_{0\pi}$ and $S_\pi$ for each day. For example, on the 13th day $m = 0,026$g, $m_0 = 0,0043$g, $m_{0\pi} = 0,0021$g, $S_\pi = 1 \text{ cm}^2$ (we calculated these values ​​using a calculator), and

$$\alpha = \frac{m}{m_0} = 6, \varepsilon = \frac{m_{0\pi}}{m_0} = 0,48,$$

but only the leaf determines, using the same values, the exfoliation of the leaf volume $V_\pi = m_{0\pi} \alpha / \rho$ to its area:

$$d = \frac{m_{0\pi} \alpha}{\rho S_\pi} = 0,012 \text{ см.}$$

The value of the “photointegrative equivalent” of light $\gamma$ determines how much the dry mass of a plant increases when a certain amount of light energy is absorbed. To better understand the meaning of this value, let us derive it by considering the energetics of processes that occur in a plant cell.

The overall process of photosynthesis can be represented as an equation:

$$\mathrm{H}_2\mathrm{O} + \mathrm{CO}_2 \xrightarrow{\text{свет}} (\mathrm{CH}_2\mathrm{O}) + \mathrm{O}_2.$$

On the left side of the equation are the familiar water and carbon dioxide molecules, and on the right side are the oxygen molecule and the minimal structure of the carbohydrate group $\mathrm{CH}_2\mathrm{O}$, which is obtained by “assimilation” of one carbon dioxide molecule. Fruit sugar molecule - fructose $C_6\mathrm{H}_{12}\mathrm{O}_6$ -

⟦folio 15⟧

---
running_head:
folio:
---

consists of 6 such groups ($C_6H_{12}O_6 = 6(CH_2O)$), and the regular sugar molecule - sucrose $C_{12}H_{24}O_{12}$ - consists of 12. The word “light” above the arrow means that in order for such a transformation of substances to occur, absorption of light energy is necessary.

The written equation shows only the initial and final products. And the process of photoynthesis includes many intermediate substances and reactions. In a plant cell, more precisely in the chloroplasts located inside it, real molecular units work, the machines of which - protein molecules (enzymes) - can, using light energy, generate electricity, carry out electrolysis, redistribute atoms and groups of atoms in molecules.

Light in chloroplasts is absorbed by chlorophyll molecules. When a molecule absorbs one photon, one of the molecule's electrons moves to a higher energy level. Ultimately, the energy of these excited electrons goes to work on recirculation in an electrical circuit composed mainly of protein molecules. (Chlorophyll molecules and proteins associated with them play the role of photocells of the cell.) The current flowing through the circuit carries out the electrolysis of ions formed during the dissociation of water molecules ($OH^-$ and $H^+$), and of the substance, which is the conversion of hydrogen atoms from the mo-

Fig. 4.

water molecules to a carbon dioxide molecule.

The molecule of this reconstituted substance and it will be denoted by A and $A^+$, respectively.

This electrolysis can be compared to the electrolysis of pure water, in which hydrogen is formed at the cathode and oxygen at the end. True, in the case of the electrolysis of pure water and in the general electrolysis of other electrolytes, the EMF source and the supply wires of the circuit are located outside, outside the electrolyte, and only the electrodes are immersed in the electrolyte (Fig. 3). In the cell, the entire electrolysis chain is immersed in the electrolyte - the rastorons that fill the cell (Fig. 4). It can be imagined as a tube, inside of which there are EMF sources isolated from the electrolyte - chlorophyll molecules connected to proteins (cellular photocells) and supply wires - proteins and other organic molecules. To perform the work of converting an electron throughout the electrolysis chain, the energy of two excited chlorophyll molecules is required, therefore, a voltage on the electrodes is necessary for electrolysis

Fig. 3.

⟦folio 16⟧

---
running_head:
folio:
---

is created by two cellular photocells connected in series. The following processes occur on the electrodes:

at the cathode - 2H⁺ + 2A⁺ + 4e⁻ = 2AH,
at the anode - 4OH⁻ = O₂ + 2H₂O + 4e⁻

Now you can calculate how many quanta of light are required to produce one carbohydrate group.

According to the photosynthesis equation, 2 hydrogen atoms must be added to the carbon dioxide molecules. Therefore, to carry out the transformation, 2 A⁺ ions must be electrolyzed. To do this, you need to move 4 electrons along the chain, and for this you need 8 photons. (Recall that rewiring each electron requires excitation of two chlorophyll molecules.) The energy of each background must be greater than 1.8 eV, the minimum energy required to excite a chlorophyll molecule. The electrolysis current occurring under the influence of light in green leaves is significant. With a full intensity of sunlight of 400 W/m², the total electrolysis current in all chloroplasts of all cells of one square centimeter of a leaf is approximately 0.005 A. This means that in a leaf with an area of ​​30 cm² the current flow is 0.15 A, like in a flashlight bulb. True, a method for directly using this current has not yet been depicted.

At the next stage of photosynthesis - it is called dark because it does not require light energy - the hydrogen atoms from AN are converted to carbon dioxide molecules and form carbohydrates, and the carrier molecule in the form of the A⁺ ion is again ready for electrolysis.

Typically the plant is illuminated with non-monochromatic light. That part of the light radiation that represents quanta capable of exciting chlorophyll is called photosynthetic active radiation (PAR). The efficiency of excitation of chlorophyll molecules depends on the energy of the quanta. figure 5 shows the energy distribution of backgrounds in the solar radiation flux (red curve n(hv)) and the efficiency curve of excitation of chlorophyll molecules depending on the energy of quanta (green curve p(hv)). Using these curves, you can calculate the average energy of a PAR quantum in sunlight; it is equal to ~2.1 eV. And the total energy of the phased array is approximately half of the total energy of solar radiation incident on the Earth. (Note that different light sources should emit different energies.)

Now, using equation (3), we determine the photosynthetic equivalent for PAR. To increase the amount of carbohydrates by one mol (Δm₀ = μCH₂O × mol), 8·N_A quanta of radiation with average energy hvФ are required, i.e. ΔE = 8hvΦN_A (N_A is Avogadro’s number); That's why

$$\gamma = \frac{\mu CH₂O \cdot 1 \text{ molь}}{8hvΦN_A} = 18 \text{ г/MДж.}$$

The calculated value of γ can only be observed under special experimental conditions, when there is no oxygen in the atmosphere surrounding the plant. In the general atmosphere, part of the intermediate products in the chain of photosynthesis reactions is described by atmospheric oxygen, which reduces the formation of carbohydrates by half. This process is called photorespiration. Approximately 30% is synthesized

⟦folio 17⟧

---
running_head:
folio:
---

These carbohydrates are subsequently used by the plant as a source of energy in the synthesis of substances necessary for growth and in other processes. Because of this, $\gamma$ is usually at least three times smaller than the maximum value. We will assume that $\gamma = 6$ g/MJ.

We now know everything we need to calculate the growth rate constant $C$. In the experiments, the results of which are given in figure 1, the intensity of PAR created under artificial lighting was $\Gamma = 30$ W/$\mathrm{m}^2$. Every day, the plants were illuminated for 16 hours and then kept in darkness for 8 hours. At the same time, the average daily intensity was $I = 1,7$ MJ/$\mathrm{m}^2 \cdot \mathrm{сут}$. Substituting the numerical values ​​of all quantities into formula (6), we obtain that $C = 0,21$ days$^{-1}$. figure 6 shows the dependence of $C$ on the PAR intensity, obtained experimentally. As we can see, the value $C$ we calculated agrees well with the experimental data.

On a clear spring day, the PAR intensity at noon reaches 200 W/$\mathrm{m}^2$, and the average daily intensity is $I \approx 3,5$ MJ/$\mathrm{m}^2 \cdot \mathrm{сут}$. According to formula (6)CONSTANTA, THE GROWTH RATE UNDER SUCH CONDITIONS SHOULD BE 2 TIMES GREATER. But at higher light intensities, $\varepsilon$ decreases, since it returns in relative spring - it is necessary to ensure the increased need of plants for mineral salts; therefore, $C$ increases with increasing $I$ not linearly, but more slowly, and at $I = 3,5$ MJ/$\mathrm{m}^2 \cdot \mathrm{сут}$ it is 0.3 days$^{-1}$.

From our calculations it follows that under ideal conditions the plant can increase in size every day (every day) by $e^{0,3} = 1\frac{1}{3}$ times, i.e. by 1/3, and the change in the lung can be noticed by eye. If the plant grows in less favorable conditions and, for example, $C = 0,1$ days$^{-1}$, then a noticeable change will occur after two days ($e^{0,1 \cdot 2} = 1,24$), i.e., it is indeed possible that the growth rate allows one to notice a change in the size of the plant almost every day.

We considered a period of plants when the supply of substances occurs only through photosynthesis. During germination, when the energy stored in the seed is used, and during the growth of new leaves, when the growing leaf receives photosynthetic products from other leaves, the growth rate can be greater than that obtained from our growths.

The problem we solved about finding the speed constant of a plant is a simple example of problems solved by agrophysics. Agrophysics is a fairly young science, located at the intersection of atmospheric physics and soil physics, biophysics and plant physiology, and applied mathematics. It solves problems of describing plants and the development of individual plants and entire crops, and the influence of external physical conditions on them - light intensity, temperature, soil and air humidity, wind speed.

These tasks are complex and contain several independent tasks. However, one of them is the creation of a plant model that is more accurate than the one we considered. The model should describe those characteristics of the interaction of the plant with the environment that need to be studied. For example, if we wanted to find out how our plant would grow in the village, when each plant has to produce $S_0$, then our model would have to be supplemented with the dependence

⟦folio 18⟧

---
running_head:
folio:
---

effective area of ​​light absorption by leaves $S_{\alpha}$ depending on the plant development stage. This effective area should be included together with the area of ​​the sheets in formula (4), when the sheets begin to overlap, i.e., when the area of ​​the sheets is comparable to $S_0$. This dependence can be taken, for example, in the form $S_{\alpha} = S_{\pi} / (1 + S_{\pi} / S_0)$. This formula well describes the change in the effective absorbing area of ​​the plant with increasing leaf area. Indeed, if $S_{\pi} \ll S_0$, then the fraction in the value of the soap shape, and $S_{\alpha} \approx S_{\pi}$, as it should be when the sheets are not overlapped. When $S_{\pi} \gg S_0$, the value can be preceded by one, and then $S_{\alpha} \approx S_0$.

More complex models take into account the dependence of the harmful parameters $\alpha, \varepsilon, d, \gamma$ on external conditions, on the stage of plant development, and on other parameters.

Other problems involve describing the processes that influence plant growth, such as the diffusion of carbon dioxide and water vapor in the atmosphere and between leaves, the flow of water, and the release of nutrients in porous soil. The goal of agrophysical research is to learn how to “correct” the external physical parameters of a plant’s habitat so that the plant is always in optimal conditions for its growth. Now there are already experimental fields in which, based on the model of plant development and its interaction with the environment, crops are watered and fertilized according to the readings of sensors installed in the field.

Fig. 7.

Knowing about exponential plant growth, you can solve one agrophysical problem. But first, get acquainted with the conveyor method of growing plants.

In some cases, polar meteorological stations are now using installations for conveyor growing of greens for crews, which have the filling name “Nugget - Arctic”. Installation of these devices is simple. A plant measuring $0,5 \times 1,5$ m automatically maintains a constant level of substances necessary for plant growth. A powerful electric lamp is located above the mirror reflector. Growing plants are moved along the bathtub in plastic cassettes, the roots of which lightly touch the nutrients. The cassettes are “loaded” with seeds and installed on one edge of the bath. As the plants develop, they are moved to the other edge of the bath, gradually separating them so that the leaves of the plants always form a continuous green cover, but do not overlap too much (Fig. 7). This type of conveyor with separating cassettes has two advantages. Firstly, the light is not wasted, since it only falls on the leaves of the plants. Secondly, continuous production of greens is carried out.

The use of large conveyors (and the laboratory has already used conveyors 10, 20 and more meters long), of course, requires automation of the movement of cassettes. And the small “Nugget” field, say on a ship, is monitored by the cook. He charges the cassettes, moves them as needed and harvests the crop.

Having a model that well describes the growth of a plant depending on external conditions (and the characteristics of the plant itself), you can obtain the law of moving the cassette along the conveyor $l = l(t)$, in which there are no gaps in the leaves, and determine the time between installed cassettes t. It is this agrophysical problem that we suggest you solve yourself.
