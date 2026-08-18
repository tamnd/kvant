---
id: 1972-5-rabbot-trigonometricheskie-funktsii-784fa2df
issue: kvant_1972_5
year: 1972
number: "5"
title: Тригонометрические функции
authors:
  - Раббот Ж. М.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 38
page_last: 44
page_labels: 36-42
tag: 3T64
lang: ru
source: kvant_digital
extraction: vision
content_sha256: 03dfbcd899b8451daac0529c7b88193be1e8f98d27d6b78ff9c91068d3d45ffe
---

⟦folio 36⟧

ПРАКТИКУМ АБИТУРИЕНТА

Трионометрическое функция, шифровка у поступающих вузы на вступательных экземплярах.

1. Трионометрическое функция числа

Что макое sin 1? Какой знак имеет ctg 21? Подобные вопросы часто ставят в тупик многих абитурентов.

Мы хотим определить трионометрическое функция на множество всех действительных (вещественных) чисел. Для этого рассмотрим на координатной плоскости круг единичного радиуса с центром в начале координат («triонометрический круг»).

Пусть нам задано произвольное число $t_0$. Отложим на окружности трионометрического круга от точки $E(1; 0)$ (рис. 1)дугу длиной $|t_0|$ в положительном направлении (против часовой стрелки), если $t_0 \geq 0$, и в отрицательном направлении (по часовой стрелке), если $t_0 < 0$ (единицей длины служебных трионометрического круга). При этом мы получим на окружности точку $P_{t_0}$ с координатами $(x_{t_0}, y_{t_0})$. Абсцисса $x_{t_0}$ точки $P_{t_0}$ называется косинусом числа $t_0$, а ordinата $y_{t_0}$ этой точки — синусом числа $t_0$:

$$\cos t_0 = x_{t_0}; \sin t_0 = y_{t_0}.$$

Найболее тонкое место в нашем определении — процесс открывания на окружности даниной длины. Его можно наглядно представлять себе как наматывание (без растяжения) отрезка на окружность.

Итак, чтобы получить, скажем, сину числа $t_0$, мы сначала сопоставили (с помощью наматывания) числу $t_0$ определению точки $P_{t_0}$ на окружности, а затем взяли ordинату этой точки:

$$t_0 \rightarrow P_{t_0}(x_{t_0}; y_{t_0}) \rightarrow y_{t_0} = \sin t_0.$$

Пользовать нашим определением, мы можем изучить свойства функции $y = \sin t$. Покажем, как это делается.

⟦folio 37⟧

a) Найдем корни уравнения sin t=0. Пусть число $t$ такое, что sin t=0. Это означает, что ordinata точки $P_t$, соответствующей числу $t$, равна нулю. Таких точек на единичной окружности две: $E$ и $E'$ (см. рис. 1). Они будут получаться при откладывании друг, длины которых кратны длине полукружности.

Заметив теперь, что половина длины единичной окружности равна $\pi$, мы получим, что равенство sin t=0 равносильно равенству $t=\pi k$, где $k=0, \pm 1, \pm 2, \dots$.

6) Если числа $t_1$ и $t_2$ отличаются друг от друга на число, кратное 2π (то есть на целое число длин окружности), то соответствующие числам $t_1$ и $t_2$ точки единичной окружности совпадают. Это означает, что из равенства $t_1-t_2=2\pi k$ ($k=0, \pm 1, \pm 2, \dots$) следует равенство sin $t_1=\sin t_2$, то есть число 2π является периодом функции $y=\sin t$.

Докажем, что число 2π является наименьшим положительным периодом функции $y=\sin t$. Предположим противное: пусть $0<a<2\pi$ и

$$\sin (t+a)=\sin t$$

(1)

при любом $t$ (то есть нашлось положительное число $a$, меньше 2π, которое тоже является периодом).

Пусть $t=0$. Тогда из (1) получим, что sin a=0. Но в промежутке $0<a<2\pi$ есть лишь число $\pi$, синус которого равен нулю, поэтому $a=\pi$. Подставив теперь в (1) $t=\frac{\pi}{2}$, мы получим, что $1=-1\left(\sin \frac{\pi}{2}=1-\text{это ordinata точки } A\text{ на рисунке 1}, a \sin \left(\pi+\frac{\pi}{2}\right)=-1-\text{это ordinata точки } A'\right)$. Мы пришли к противению. Итак, 2π — наименьший положительный период функции $y=\sin t$.

Установленное нами свойство периодичности позволяет проводить дальнейшее исследование свойств синуса только в пределах одного периода, например, при $0\leq t\leq 2\pi$.

В связи с доказанной периодичностью синуса следует заменение. В учебнике Кочетковых «Алгебра и элементарные функции» (§ 207) подразумевается, но явно не сказано, что для периодической функции вместе с числом $x$ должны входить в область определения и все числа $x+nT$ ($n$-любое целое число, $T$-period). Между тем это очень важно: иногда удается доказать периодичность функций, получясь именно этим свойством. Покажем, например, что функция $y=\cos \frac{1}{x}$ — неперiodическая. Предположим, что $T$-period этой функции. При $x=-T$ наша функция определяна, значит, она должна быть определена и при $x=-T+T=0$, но при $x=0$ ссылася $\frac{1}{x}$ не существует: мы пришли к противению.

Совершенно аналогично можно исследовать свойства функции $y=\cos t$. Вам, по-видимому, совершенно ясно, как определить функцию $y=\tg t$, $y=\ctg t$ (числового аргумента) и исследовать их свойства.

Уражения

1. Найдите наименьшие положительные периоды функций:

a) $y=\sin 3x$; 6) $y=\tg 2x-\sin 3x$; в) $y=2 \sin \left(\frac{\pi}{4}+\frac{x}{2}\right)$; г) $y=\sin^2 x$; д) $y=\sin(\cos x)$; e) $y=\cos(\sin x)$.

Пример 1. Доказать неперiodичность функции $y=\sin x^2$.

Решен и е. Предположим, что данная функция периодическая. Найдем нулю этой функции (то есть значения $x$, при которых она обращается в нуль): sin $x^2=0$, откуда $x^2=\pi k$ ($k=0, 1, 2, \dots$), $x=\pm \sqrt{\pi k}$. Если $k=0$, то $x_0=0$; если $k=1$, то $x_1=\sqrt{\pi}$. Из сделанного предположения о

⟦folio 38⟧

перiodичности функций $y=\sin x^2$ следует, что найдется еще бесконечного пар соседних ее нулей (получаются из $x_0$ и $x_1$ сdwгами вправо на целое число периодов), разность между которых равна $x_1-x_0=\sqrt{\pi}$. Но для любого $k>1$ имеем

$$|x_{k+1}-x_k|=|V(k+1)\pi-Vk\pi|=\frac{\pi}{\sqrt{(k+1)\pi}+\sqrt{k\pi}}<\sqrt{\pi}.$$

так как $V(k+1)\pi+Vk\pi>\sqrt{\pi}$. Полученное противоречие доказывает неперiodичность функций $y=\sin x^2$.

Упражнения

2. Докажите неперiodичность функций: a) $y=\sin \sqrt{x}$; b) $y=\cos x\cos \sqrt{2}x$.
3. Укажите знаки следующих чисел:
a) $\sin 2$; 6) $\cos 3,1$; b) $tg 10$; r) $\sin \pi^2$; d) $tg(\cos 2)$.
4. Дано, что $\cos^2 t+p\cos t+q>0$ при всех действительных значениях $t$. Следует ли отсюда, что $x^2+px+q>0$ при всех действительных значениях $x$?

Нетрудно установить простую между определениями трионометрических функций (обобщенного) угла и числового аргумента. Расположим угол так, чтобы его начальная сторона шла по оси $Ox$ (рис. 2). Тогда синус угла по определению равен ordinate точки, в которой конечная сторона угла пересекает единичную окружность.

Если угол содержит $\alpha$ радиан, то конечная сторона угла будет пересекать единичную окружность в конце дуги, соответствующей числу $\alpha$ при наматывении. Поэтому (сравните рисунки 1 и 2)

Рис. 2.

Именно это свойство принято в школьном учебнике за определение синуса числа (и аналогично для других функций: косинуса, тангенса, котангенса).

2. Преобразование трионометрических выражений

При решении различных задач часто приходится проводить тожестевые преобразования, пользоваться формулами трионометрики. При этом надо помнить, что некоторые формулы изменяют область определения; кроме того, необходимо выяснить обратимость всех переходов.

Пример 2. (МАИ, 1970). Доказать мождество:

$$\frac{\left(\cos \alpha+\cos \frac{\alpha}{2}\right)^2-\left(\sin \alpha+\sin \frac{\alpha}{2}\right)^2}{\sin 2\alpha-\sin \alpha}=\mathrm{ctg} \frac{\alpha}{4}.$$

Решение е. Найдем прежде всего ОДЗ. Левая часть (2) определена, когда $\sin 2\alpha-\sin \alpha\neq 0$, то есть когда $2\sin \alpha\cos \alpha-\sin \alpha\neq 0$, откуда $\sin \alpha\neq 0$, $\cos \alpha\neq \frac{1}{2}$; окончательно $\alpha\neq \pi n$, $\alpha\neq \pm \frac{\pi}{3}+2\pi k^*)$. Правая

*) Здесь и далее, если не овогрено противное, следуемается, что параметры $n, k, l$ и т.п. принимают все целочисленные значения.

⟦folio 39⟧

чась (2) существует при $\sin \frac{\alpha}{4} \neq 0$, то есть при $\alpha \neq 4\pi l$. Итак, ОДЗ найдена: $\alpha \neq n\pi, \alpha \neq \pm \frac{\pi}{3} + 2\pi k$.

Обозначим левую часть тождества через $M$. Тогда

$$M = \frac{\cos^2\alpha + 2\cos\alpha \cos \frac{\alpha}{2} + \cos^2 \frac{\alpha}{2} - \sin^2\alpha - 2\sin\alpha \sin \frac{\alpha}{2} - \sin^2 \frac{\alpha}{2}}{\sin 2\alpha - \sin\alpha} =$$

$$= \frac{(\cos^2\alpha - \sin^2\alpha) + \left(\cos^2 \frac{\alpha}{2} - \sin^2 \frac{\alpha}{2}\right) + 2\left(\cos\alpha \cos \frac{\alpha}{2} - \sin\alpha \sin \frac{\alpha}{2}\right)}{\sin 2\alpha - \sin\alpha} =$$

$$= \frac{\cos 2\alpha + \cos\alpha + 2\cos \frac{3\alpha}{2}}{\sin 2\alpha - \sin\alpha} = \frac{2\cos \frac{\alpha}{2} \cos \frac{3\alpha}{2} + 2\cos \frac{3\alpha}{2}}{2\sin \frac{\alpha}{2} \cos \frac{3\alpha}{2}} =$$

$$= \frac{\cos \frac{\alpha}{2} + 1}{\sin \frac{\alpha}{2}} = \frac{2\cos^2 \frac{\alpha}{4}}{2\sin \frac{\alpha}{4} \cos \frac{\alpha}{4}} = \text{ctg} \frac{\alpha}{4}.$$

Итак, в ОДЗ $M = \text{ctg} \frac{\alpha}{4}$.

Пример 3. Докажите, что если $\text{ctg}(\alpha + \beta) = 0$, то

$$\sin(\alpha + 2\beta) = \sin\alpha.$$

(3)

Решение. Заметим, что условие $\text{ctg}(\alpha + \beta) = 0$ эквивалентно условию

$$\cos(\alpha + \beta) = 0.$$

(4)

Рассмотрим теперь разность правой и левой части (3): $\sin(\alpha + 2\beta) - \sin\alpha = 2\sin\beta \cos(\alpha + \beta)$, откуда, использяя (4), получим требуемое.

Упражнения

5. (МАИ, 1970). Докажите тождества:
a) $(\sin\alpha - \cos\alpha)^2 + (\cos\alpha - \sec\alpha)^2 = 4\text{ctg}^2 2\alpha + 1$;
b) $\sin\alpha + \text{ctg}\alpha - \text{ctg}\alpha \cos\alpha - 1 = \frac{2\cos\left(\frac{\pi}{4} + \alpha\right)\sin\left(\frac{\alpha}{2} - \frac{\pi}{4}\right)}{\cos \frac{\alpha}{4}}.$

6. Докажите тождества:
a) (МИСП, 1969). $\frac{1}{1 + \text{tg}\alpha \text{tg}2\alpha} = \sin\left(\frac{\pi}{2} + 2\alpha\right)$; б) (МИФИ). $\cos^2\varphi + \cos^2(\alpha + \varphi) - 2\cos\alpha \cos\varphi \cos(\alpha + \varphi) = \sin^2\alpha$.
7. (Физ. фак. МГУ).
a) Докажите, что если $5\sin\beta = \sin(2\alpha + \beta)$, то $\frac{\text{ctg}(\alpha + \beta)}{\text{tg}\alpha} = \frac{3}{2}$;
b) Докажите, что если $\cos x = \cos a \cos b$, $x \pm a \neq \pi(2k + 1)$, $b \neq \pi(2k + 1)$, то $1 + \text{tg}\frac{x + a}{2} \text{tg}\frac{x - a}{2} = \frac{1}{\cos^2 \frac{b}{2}}$.

Пример 4. Упростим выражение

$$M = \sin\alpha + \sin(\alpha + \delta) + \dots + \sin(\alpha + n\delta).$$

⟦folio 40⟧

Решение. Заметив, что аргументы синусов образуют аргументную прогрессию с разностью $\delta$, умножим обе части равенства на $2 \sin \frac{\delta}{2}$:

$$2 \sin \frac{\delta}{2} \cdot M = 2 \sin \frac{\delta}{2} \sin \alpha + 2 \sin \frac{\delta}{2} \sin (\alpha + \delta) + \dots + 2 \sin \frac{\delta}{2} \times$$

$$\times \sin (\alpha + n\delta) = \cos \left( \alpha - \frac{\delta}{2} \right) - \cos \left( \alpha + \frac{\delta}{2} \right) + \cos \left( \alpha + \frac{\delta}{2} \right) -$$

$$- \cos \left( \alpha + \frac{3\delta}{2} \right) + \dots + \cos \left[ \alpha + \left( n - \frac{1}{2} \right) \delta \right] - \cos \left[ \alpha + \left( n + \frac{1}{2} \right) \delta \right] =$$

$$= \cos \left( \alpha - \frac{\delta}{2} \right) - \cos \left[ \alpha + \left( n + \frac{1}{2} \right) \delta \right] = 2 \sin \left( \alpha + \frac{n\delta}{2} \right) \sin \frac{n+1}{2} \delta.$$

Итак, если $\sin \frac{\delta}{2} \neq 0$, то есть $\delta \neq 2\pi k$, то

$$M = \frac{\sin \left( \alpha + \frac{n\delta}{2} \right) \sin \left( \frac{(n+1)\delta}{2} \right)}{\sin \frac{\delta}{2}}.$$

Если же $\delta = 2\pi k$, то

$$M = \sin \alpha + \sin (\alpha + 2\pi k) + \dots + \sin (\alpha + 2\pi nk) = (n+1) \sin \alpha.$$

Упражнения

8. Доказите точдества:

$$= \frac{\sin \frac{n\alpha}{2} \cos \frac{(n+1)\alpha}{2}}{\sin \frac{\alpha}{2}};$$

a) (МИФИ). $\cos \alpha + \cos 2\alpha + \cos 3\alpha + \dots + \cos n\alpha =$

b) (МГУ). $\cos \frac{\pi}{5} + \cos \frac{3\pi}{2} = \frac{1}{2}$.

9. (МИФИ). Упростите выражения. a) $\cos \alpha \cdot \cos 2\alpha \cdot \cos 4\alpha \dots \cos 2^{n}\alpha$;

b) $\cos \alpha - \cos 2\alpha + \cos 3\alpha - \cos 4\alpha + \dots + (-1)^{n+1} \cos n\alpha$;

b) $\sin \alpha + 2 \sin 2\alpha + 3 \sin 3\alpha + \dots + n \sin n\alpha$;

r) $\sin^3 \frac{\alpha}{3} + 3 \sin^3 \frac{\alpha}{3^2} + 9 \sin^3 \frac{\alpha}{3^3} + \dots + 3^{n-1} \sin^3 \frac{\alpha}{3^n}$.

Пример 5. Доказать мождество:

$$\mathrm{tg} \alpha + \frac{1}{2} \mathrm{tg} \frac{\alpha}{2} + \frac{1}{4} \mathrm{tg} \frac{\alpha}{4} + \dots + \frac{1}{2^n} \mathrm{tg} \frac{\alpha}{2^n} = \frac{1}{2^n} \mathrm{ctg} \frac{\alpha}{2^n} - 2 \mathrm{ctg} 2\alpha.$$

Решение. Заметив, что в правой части точдества стоит котан-генсы, выразим $\mathrm{tg} \alpha$ через $\mathrm{ctg} 2\alpha$ и $\mathrm{ctg} \alpha$: $\mathrm{tg} \alpha = \mathrm{ctg} \alpha - 2 \mathrm{ctg} 2\alpha$.

Тогда

$$\mathrm{tg} \alpha = \mathrm{ctg} \alpha - 2 \mathrm{ctg} 2\alpha,$$

$$\mathrm{tg} \frac{\alpha}{2} = \mathrm{ctg} \frac{\alpha}{2} - 2 \mathrm{ctg} \alpha,$$

$$\mathrm{tg} \frac{\alpha}{4} = \mathrm{ctg} \frac{\alpha}{4} - 2 \mathrm{ctg} \frac{\alpha}{2},$$

$$\dots$$

$$\mathrm{tg} \frac{\alpha}{2^n} = \mathrm{ctg} \frac{\alpha}{2^n} - 2 \mathrm{ctg} \frac{\alpha}{2^{n-1}}.$$

⟦folio 41⟧

Умножая выписанные тождества соответственно на 1, $\frac{1}{2}$, ..., $\frac{1}{2^n}$ и полученно складывая, мы получим нужный результат. Наши преобразования имеют смысл лишь при $\alpha \neq \frac{\pi k}{2}$ (проверьте!).

Упражнения

10. Докажите тождества: a) (УГПИ). $\sin^2 \alpha + \sin^2 (120^\circ + \alpha) + \sin^2 (120^\circ - \alpha) = \frac{3}{2}$;
6) (МАИ). $tg 3\alpha = tg \alpha tg \left(\frac{\pi}{3} + \alpha\right) tg \left(\frac{\pi}{3} - \alpha\right)$; b) (МагГПИ). $4 \cos^2 \alpha + \sin^2 2\alpha + 4 \sin^4 \alpha = 4$.

11. Преобразуйте в произведение: a) (МагГПИ). $\cos^2 (x + y) + \sin (x + y) + \cos (x + y) + \sin^2 (x + y)$;
6) (МАИ). $tg^3\alpha + \frac{1}{\cos^2 \alpha} + 3 \text{ctg} \left(\frac{3\pi}{2} + \alpha\right) - 4$;
b) (МИСП, 1969). $\sin 5\alpha \sin 4\alpha + \sin 4\alpha \sin 3\alpha - \sin 2\alpha \sin \alpha$; r) (MTИ, 1970).

$\sec^2 \alpha - tg^2 \alpha + tg \left(\frac{\pi}{2} - \frac{\alpha}{2}\right) + \text{ctg} \left(\frac{\pi}{4} - \frac{\alpha}{2}\right)$.

Пример 6. Вычислить без таблиц sin 18°.
Решение е. Мы воспользовемся тем, что $18^\circ \cdot 5 = 90^\circ$, то есть, что $2 \cdot 18^\circ + 3 \cdot 18^\circ = 90^\circ$, откуда

$$\cos (2 \cdot 18^\circ) = \sin (3 \cdot 18^\circ)$$

и тем, что cos 2α и sin 3α рационально выражаются через sin α. Применив формулы cos 2α = 1 - 2 sin²α и sin 3α = 3 sin α - 4 sin³α, мы из (5) получим: $4 \sin^3 18^\circ - 2 \sin^2 18^\circ - 3 \sin 18^\circ + 1 = 0$.

Обозначив sin 18° через y, мы приходим к уравнению

$$4y^3 - 2y^2 - 3y + 1 = 0,$$

которое легко решить, заметив, что $y = 1$ — его корень (отсюда сразу следует, что левая часть (6) делится на $y - 1$): $(y - 1) (4y^2 + 2y - 1) = 0$, откуда $y_1 = 1, y_2, 3 = \frac{-1 \pm \sqrt{5}}{4}$. Учитывая, что sin 18° ≠ 1, sin 18° > 0, находим, что sin 18° = $\frac{\sqrt{5} - 1}{4}$.

Пример 7. Упростим выражения: a) $S_1 = \cos^2 \alpha + \cos^2 2\alpha + \dots + \cos^2 n\alpha$; b) $S_2 = \sin^2 \alpha + \sin^2 2\alpha + \dots + \sin^2 n\alpha$.
Решение е. Так как sin²x + cos²x = 1, то

$$S_1 + S_2 = n.$$

Приименив теперь результат упражнения 8a) (при каких α это можно сделать?), мы получим:

$$S_1 - S_2 = (\cos^2 \alpha - \sin^2 \alpha) + (\cos^2 2\alpha - \sin^2 2\alpha) + \dots + (\cos^2 n\alpha - \sin^2 n\alpha) = \cos 2\alpha + \cos 4\alpha + \dots + \cos 2n\alpha = \frac{\sin n\alpha \cos (n + 1)\alpha}{\sin \alpha}$$

Теперь из (7) и (8) легко получить: $S_1 = \frac{n}{2} + \frac{\sin n\alpha \cos (n + 1)\alpha}{2 \sin \alpha}$; $S_2 = \frac{n}{2} - \frac{\sin n\alpha \cos (n + 1)\alpha}{2 \sin \alpha}$. Каков ответ при α = πk?

Упражнения

12. Вычислите без таблиц: a) cos 15°; b) tg 7,5°; c) tg 18°; r) (МАИ, 1970). cos 55° · cos 65° · cos 175°; d) (МИСП, 1969). tg 9° - tg 27° - tg 63° + tg 81°.

⟦folio 42⟧

Пример 8. Найти $\cos \alpha + \sin \alpha$, если $\sin \alpha \cos \alpha = 0,48$.

Решение. Извлекая из обеих частей тождества $(\cos \alpha + \sin \alpha)^2 = 1 + 2 \sin \alpha \cos \alpha$, квадратный корень (как всегда, арифметический!), получим: $|\cos \alpha + \sin \alpha| = \sqrt{1 + 2 \sin \alpha \cos \alpha} = 1,4$ (подкоренное выражение неотрицательное: $1 + 2 \sin \alpha \cos \alpha = 1 + \sin 2\alpha \geq 0$, так как $\sin 2\alpha \geq -1$). Поскольку по условияю $\sin \alpha \cos \alpha > 0$, то $\sin \alpha$ и $\cos \alpha$ имеют одинаковые значки, то есть $\alpha$ находится либо в I, либо в III четверти. Если $2\pi n < \alpha < \frac{\pi}{2} + 2\pi n$, то $\sin \alpha + \cos \alpha = 1,4$;

если же $\pi + 2\pi n < \alpha < \frac{3\pi}{2} + 2\pi n$, то $\sin \alpha + \cos \alpha = -1,4$.

Упражнения

13. a) (МАИ). Найдите $\frac{1 - 2 \sin^2 \frac{\alpha}{2}}{1 + \sin \alpha}$, если $tg \frac{\alpha}{2} = m - 1$; 6) (МГУ). Докажите, что если $tg \alpha = \frac{1}{7}$, $\sin \beta = \frac{1}{\sqrt{10}}$, то $\alpha + 2\beta = \frac{\pi}{4}$ ($\alpha$ и $\beta$ – углы I четверти); 7) (МИСП). Найдите $18 \sin \frac{3\alpha}{2} \sin \frac{\alpha}{2}$, если $\cos \alpha = \frac{2}{3}$. 8) (MTИ). Найдите $tg \frac{\alpha}{2}$, если $tg \alpha = \frac{4}{3}$, $\pi < \alpha < \frac{3\pi}{2}$.

14. (МГУ). Известно, что $\alpha + \beta + \gamma = \frac{\pi}{2}$, $\alpha > 0$, $\beta > 0$, $\gamma > 0$ и что $ctg \alpha, ctg \beta, ctg \gamma$ образуют арифметическую прогрессию. Найдите $ctg \alpha$ $ctg \gamma$.

15. (МИФИ). Докажите, что если $\alpha, \beta, \gamma$ – углы треугольника, то

a) $\sin \alpha + \sin \beta + \sin \gamma = 4 \cos \frac{\alpha}{2} \cos \frac{\beta}{2} \cos \frac{\gamma}{2}$;

b) $tg \alpha + tg \beta + tg \gamma = tg \alpha tg \beta tg \gamma$;

r) $\sin 2\alpha + \sin 2\beta + \sin 2\gamma = 4 \sin \alpha \sin \beta \sin \gamma$;

d) $\sin^2 \alpha + \sin^2 \beta + \sin^2 \gamma = 2 \cos \alpha \cos \beta \cos \gamma + 2$;

e) $tg \frac{\alpha}{2} tg \frac{\beta}{2} + tg \frac{\alpha}{2} tg \frac{\gamma}{2} + tg \frac{\beta}{2} tg \frac{\gamma}{2} = 1$;

ж) $\cos \alpha + \cos \beta + \cos \gamma \leq \frac{3}{2}$;

3) $\sin^2 \alpha + \sin^2 \beta + \sin^2 \gamma > 2$ (треугольник остроугольный).

16. Докажите неравенства:

a) (МФТИ).

$ctg \frac{\alpha}{2} > 1 + ctg \alpha \left(0 < \alpha < \frac{\pi}{2}\right)$;

6) (ВГУ). $\cos \alpha + 3 \cos 3\alpha + 6 \cos 6\alpha \geq -7,2$;

b) (МФТИ). $(1 - tg^2\alpha) (1 - 3tg^2\alpha) (1 + tg2\alpha tg3\alpha) > 0$; r) (МФТИ).

$(ctg^2\alpha - 1) (3ctg^2\alpha - 1) \times (ctg3\alpha tg2\alpha - 1) \leq -1$; d) (МГУ). $4 \sin 3\alpha + 5 \geq 4 \cos 2\alpha + 5 \sin \alpha$.

Причеме. В статье прияты следующее сокращения:

МАИ – Московский авнационный институт, МГУ – Московский государственный университет, МГПИ – Московский государственный педагогический институт, МагГПИ – Магаданский государственный педагогический институт, МТИ – Московский текстильный институт, МИСП – Московский институт стали и славов, МИФИ – Московский инженерно-физический институт, УГПИ – Ульяновский государственный педагогический институт, ВГУ – Воронежский государственный университет, МФТИ – Московский физико-технический институт.
