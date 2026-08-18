---
id: 1979-1-gabovich-vektoryi-pomogayut-na-ekzamene-44128586
issue: kvant_1979_1
year: 1979
number: "1"
title: Векторы помогают на экзамене
authors:
  - Габович И. Г.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 47
page_last: 51
page_labels: 45, 47, 48, 49
tag: YCER
lang: ru
source: kvant_digital
extraction: vision
content_sha256: 147580f88b1b028ee08593afe0f97d9ebd0151d4d741aa775622025db810f6ac
---

⟦folio 45⟧

В этой статье приведены четыре важных векторных соотношения и показано на примере материлов вступительных экзаменов 1977—1978 гг., как их применять при решении конкурсных задач.

Основное соотношение. В треугольнике ABC на строоне AC взята точка D так, что |AD|:|DC| = m:n. Тогда
$$\overrightarrow{BD} = \frac{n}{m+n} \overrightarrow{BA} + \frac{m}{m+n} \overrightarrow{BC}^*).$$ (1)

Доказательство. Имеем (рис. 1)
$$\overrightarrow{AC} = \overrightarrow{BC} - \overrightarrow{BA},
\overrightarrow{AD} = \frac{m}{m+n} \overrightarrow{AC} = \frac{m}{m+n} \overrightarrow{BC} - \frac{m}{m+n} \overrightarrow{BA},
\overrightarrow{BD} = \overrightarrow{BA} + \overrightarrow{AD} = \overrightarrow{BA} + \frac{m}{m+n} \overrightarrow{BC} -
\frac{m}{m+n} \overrightarrow{BA} = \frac{n}{m+n} \overrightarrow{BA} + \frac{m}{m+n} \overrightarrow{BC}.$$
Задача 1 (МГУ, эконом. фак., 1978). В треугольнике KLM на строоне KL взята точка A так, что |KA|:|AL| = 1:3; на строоне LM взята точка B так, что |LB|:|BM| = 4:1. Пусть С—точка пересечения прямых KB и MA. Известно, что площадь треугольника KLC равна 2. Найти площадь треугольника KLM.

*) В несолько ином виде эта формула рассматривается в стате С. Овчинникова («Квант», 1978, № 3, с. 48). См. также статью В. Болтянского в «Квант» 1978, № 10, с. 14.

Решение. Положим $S_{\Delta KLB} = S$. Тогда (рис. 2), очевидно, $S_{\Delta KLM} = \frac{4}{5} S$. Введем векторы $\overrightarrow{KL}$ и $\overrightarrow{KM}$. На основании (1) имеем
$$\overrightarrow{KB} = \frac{1}{5} \overrightarrow{KL} + \frac{4}{5} \overrightarrow{KM}.$$
Пусть $\overrightarrow{KC} = x\overrightarrow{KB}$, где $0 < x < 1$. Тогда
$$\overrightarrow{KC} = \frac{x}{5} \overrightarrow{KL} + \frac{4x}{5} \overrightarrow{KM}.$$ (2)

Пусть $|AC|:|CM| = m:n$. Тогда из треугольника AKM по той же формуле (1) имеем
$$\overrightarrow{KC} = \frac{n}{m+n} \overrightarrow{KA} + \frac{m}{m+n} \overrightarrow{KM} =
\frac{n}{m+n} \frac{1}{4} \overrightarrow{KL} + \frac{m}{m+n} \overrightarrow{KM}.$$ (3)

В силу единственной разложения вектора по двум неоколичным векторам из (2) и (3) получаем систему
$$\begin{cases} \frac{x}{5} = \frac{n}{4(m+n)} \\ \frac{4x}{5} = \frac{m}{m+n}, \end{cases}$$ или
$$\begin{cases} \frac{4x}{5} = \frac{n}{m+n} \\ \frac{4x}{5} = \frac{m}{m+n}. \end{cases}$$

Рис. 1.

Рис. 2.

⟦folio 47⟧

$$\overrightarrow{MN}^2 = \frac{4}{9} a^2 + \frac{a^2}{9} = \frac{5a^2}{9},$$

откуда

$$|MN| = \frac{a \sqrt{5}}{3}.$$

Ответим теперь на второй вопрос задачи. Пусть $|D_1M|:|MA| = p$.

Тогда

$$\overrightarrow{MN} = \frac{1}{p+1} \overrightarrow{D_1D} + \frac{p}{p+1} \overrightarrow{AB_1} =$$

$$= -\frac{a}{p+1} \vec{k} + \frac{2ap}{p+1} \vec{j} + \frac{ap}{p+1} \vec{k} =$$

$$= \frac{2ap}{p+1} \vec{j} + \frac{a(p-1)}{p+1} \vec{k},$$

$$\overrightarrow{MN}^2 = \frac{4a^2p^2}{(p+1)^2} + \frac{a^2(p-1)^2}{(p+1)^2} =$$

$$= \frac{a^2(5p^2-2p+1)}{(p+1)^2}.$$

Очевидно, $|MN|$ будет иметь наименьшее значение при том значении $p$, при котором его достигает функция

$$y = \frac{5p^2-2p+1}{(p+1)^2}.$$

Читатель легко проверит (пользовясь произвольной), что это будет при $p = \frac{1}{3}$. Подставляя это значение в последнее выражение для $\overrightarrow{MN}^2$ и извлекая корень, находим искомое минимальное расстояние:

$$\frac{a \sqrt{2}}{2}.$$

III основное соотношение. Дан метраэдр ABCD и в плоскости его грани ABC точка M. Доказать, что для разложения

$$\overrightarrow{DM} = \alpha \overrightarrow{DA} + \beta \overrightarrow{DB} + \gamma \overrightarrow{DC}$$

выполняется равенство

$$\alpha + \beta + \gamma = 1^*).$$

Решение. Допустим, что точка M лежит внутри треугольника ABC (рис. 5). Проведем через точки A и M прямую, к которой пересекает сторону BC в точке E. Пусть точка E делит сторону BC в отношении

$$*)\text{ В несколько ином виде это соотношение имеется в цитированной статье C. Овчинникова.}$$

Рис. 5.

$m:n$, т. е. $|BE|:|EC| = m:n$. Тогда по формуле (1)

$$\overrightarrow{DE} = \frac{m}{m+n} \overrightarrow{DC} + \frac{n}{m+n} \overrightarrow{DB}.$$

Пусть, далее, точка M делит отрезок AE в отношении $p:q$, т. е. $|AM|:|ME| = p:q$. Тогда

$$\overrightarrow{DM} = \frac{p}{p+q} \overrightarrow{DE} + \frac{q}{p+q} \overrightarrow{DA} =$$

$$= \frac{p}{p+q} \left( \frac{m}{m+n} \overrightarrow{DC} + \frac{n}{m+n} \overrightarrow{DB} \right) +$$

$$+ \frac{q}{p+q} \overrightarrow{DA} = \frac{q}{p+q} \overrightarrow{DA} + \frac{p}{p+q} \times$$

$$\times \frac{n}{m+n} \overrightarrow{DB} + \frac{p}{p+q} \frac{m}{m+n} \overrightarrow{DC}.$$

Итак, вектор $\overrightarrow{DM}$ разложен по векторам $\overrightarrow{DA}, \overrightarrow{DB}$ и $\overrightarrow{DC}$. Неопределенный подсчет суммы коэффициентов в этом разложении дает

$$\frac{q}{p+q} + \frac{p}{p+q} \frac{n}{m+n} +$$

$$+ \frac{p}{p+q} \frac{m}{m+n} = \frac{q}{p+q} + \frac{p}{p+q} = 1,$$

что и требовалось. Остальные случаи (точка M лежит вне треугольника ABC или на одной из его сторон) аналогичны и мы их опускаем.

Задача 3 (МФТИ, 1978). Длина ребра правильного метраэдра ABCD равна $a$. Точка E — середина ребра CD, точка F — середина высоты BL грани ABD. Отрезок MN с концами прямых AD и BC пересекают прямую EF и перепадкуя ей. Найдем длину этого отрезка.

Решение. Введем векторы $\overrightarrow{AB} = \vec{b}; \overrightarrow{AC} = \vec{c}; \overrightarrow{AD} = \vec{d}$ (рис. 6). Заметим, что $\|\vec{b}\| = \|\vec{c}\| = \|\vec{d}\| = a$ и

⟦folio 48⟧

Рис. 6.

$\overrightarrow{b}, \overrightarrow{c} = \overrightarrow{c}, \overrightarrow{d} = \overrightarrow{d}, \overrightarrow{b} = \frac{\pi}{3}$. Так как $E$ – середина ребра $DC$, то $\overrightarrow{AE} = \frac{1}{2}(\overrightarrow{c} + \overrightarrow{d})$.

Аналогично,
$\overrightarrow{AF} = \frac{1}{2}(\overrightarrow{b} + \overrightarrow{AL})$,
но $\overrightarrow{AL} = \frac{1}{2}\overrightarrow{d}$, поэтому
$\overrightarrow{AF} = \frac{1}{2}\overrightarrow{b} + \frac{1}{4}\overrightarrow{d}$.

Далlee,
$\overrightarrow{EF} = \overrightarrow{AF} - \overrightarrow{AE} = \frac{1}{2}\overrightarrow{b} + \frac{1}{4}\overrightarrow{d} - \frac{1}{2}\overrightarrow{c} - \frac{1}{2}\overrightarrow{d} = \frac{1}{2}\overrightarrow{b} - \frac{1}{2}\overrightarrow{c} - \frac{1}{4}\overrightarrow{d}$.

Пусть $\overrightarrow{AM} = m\overrightarrow{d}, \overrightarrow{BN} = n\overrightarrow{BC}$, (9) где $0 < m < 1$ и $0 < n < 1$. Из последнего равенства сразу следует $|BN| : |NC| = n : (1 - n)$.

Тогда, на основании (1),
$\overrightarrow{AN} = n\overrightarrow{c} + (1 - n)\overrightarrow{d}$.

Далlee, $\overrightarrow{MN} = \overrightarrow{AN} - \overrightarrow{AM}$, откуда $\overrightarrow{MN} = n\overrightarrow{c} + (1 - n)\overrightarrow{d}$. (11)

Так как, по условияю, отрезки $EF$ и $MN$ перpendикулярны, то $\overrightarrow{EF} \cdot \overrightarrow{MN} = 0$, или
$\left( \frac{1}{2}\overrightarrow{b} - \frac{1}{2}\overrightarrow{c} - \frac{1}{4}\overrightarrow{d} \right) \times \left( (1 - n)\overrightarrow{b} + n\overrightarrow{c} - m\overrightarrow{d} \right) = 0$.

Учитывая сделанное выше заменение относительно моделей векторов $\overrightarrow{b}, \overrightarrow{c}$ и $\overrightarrow{d}$ и углов между ними, раскроем скобки влевой части этого равенства.

Получим
$2m - 4n + 1 = 0$. (12)

В силу III основного соотношения $\overrightarrow{AN} = \alpha\overrightarrow{AF} + \beta\overrightarrow{AE} + \gamma\overrightarrow{AM}$, (13) причем $\alpha + \beta + \gamma = 1$.

Подставим в (13) вместо $\overrightarrow{AF}, \overrightarrow{AE}$ и $\overrightarrow{AM}$ их выражения через $\overrightarrow{b}, \overrightarrow{c}$ и $\overrightarrow{d}$, т. е. (7), (6), (9):

$\overrightarrow{AN} = \frac{\alpha}{2}\left(\overrightarrow{b} + \frac{1}{2}\overrightarrow{d}\right) + \frac{\beta}{2}\left(\overrightarrow{c} + \overrightarrow{d}\right) + \gamma m\overrightarrow{d} = \frac{\alpha}{2}\overrightarrow{b} + \frac{\beta}{2}\overrightarrow{d} + \left(\frac{\alpha}{4} + \frac{\beta}{2} + \gamma m\right)\overrightarrow{d}$.

В силу единственной разложения вектора по треем данных некомпланным векторам $(\overrightarrow{b}, \overrightarrow{c}, \overrightarrow{d})$ отсюда и из (10) получаем систему
$\frac{\alpha}{2} = 1 - n; \frac{\beta}{2} = n; \frac{\alpha}{4} + \frac{\beta}{2} + \gamma m = 0,$
решая которой получем
$\alpha = 2 - 2n, \beta = 2n, \gamma = -\frac{1 + n}{2m}$.

Пользовать соотношение $\alpha + \beta + \gamma = 1$, получим отсюда
$2m - n = 1 = 0$.

Решая это уравнение совместно с (12), найдем $n = \frac{2}{3}$ и $m = \frac{5}{6}$. Осталось подставить эти значения в выражение (10) для $\overrightarrow{MN}$; получим
$\overrightarrow{MN} = \frac{2}{3}\overrightarrow{c} + \frac{1}{3}\overrightarrow{b} - \frac{5}{6}\overrightarrow{d}$;

после несложного вычисления найдем $|MN| = \frac{a\sqrt{23}}{6}$.

IV основное соотношение. Если $M$ — точка пересечения медиан треугольника $ABC$ и $O$ — произвольная точка пространства, то выполняется равенство:
$\overrightarrow{OM} = \frac{1}{3}\left(\overrightarrow{OA} + \overrightarrow{OB} + \overrightarrow{OC}\right)$.

Это соотношение формулировано и доказано в учебнике «Геометрия 9» (§ 22, задача 2).

Заддача 4 (Киевск. политехн. ин-т, 1978). Около равностороннего треугольника, сторона коморого равна $a$, описана окружность. Доказать,

⟦folio 49⟧

Чимо сумма квадратов расстояний от произвольной точки окружности до вершин этого треугольника равна $2a^2$.

Решение. Пусть $D$ — произвольная точка окружности (рис. 7). Положим $|DA| = x; |DB| = y; |DC| = z$.

Тогда по теореме косинусов имеем:
из $\Delta ADB: a^2 = x^2 + y^2 - xy,$
из $\Delta BDC: a^2 = y^2 + z^2 - yz,$
из $\Delta ADC: a^2 = x^2 + z^2 + xz$.

Сложив по частям эти равенства, получаем
$3a^2 = 2(x^2 + y^2 + z^2) - xy - yz + zx.$ (14)

В силу IV основного соотношения
$\overrightarrow{DO} = \frac{1}{3} (\overrightarrow{DA} + \overrightarrow{DB} + \overrightarrow{DC})$,

где $O$ — центр окружности.

Возведя обе части этого равенства в квадрат, получаем
$|\overrightarrow{DO}|^2 = \frac{1}{9} (\overrightarrow{DA}^2 + \overrightarrow{DB}^2 + \overrightarrow{DC}^2) + 2\overrightarrow{DA} \cdot \overrightarrow{DB} + 2\overrightarrow{DB} \cdot \overrightarrow{DC} + 2\overrightarrow{DC} \cdot \overrightarrow{DA})$.

Так как $|DO|$ — радиус окружности, описанной около равностороннего треугольника, сторона которого равна $a$, то $|\overrightarrow{DO}|^2 = |DO|^2 = \frac{1}{3} a^2$.

Позтому
$\frac{a^2}{3} = \frac{1}{9} (x^2 + y^2 + z^2 + xy + yz - zx)$

или
$3a^2 = x^2 + y^2 + z^2 + xy + yz - zx$.

Сложив это равенство по частям с (14), получим
$6a^2 = 3(x^2 + y^2 + z^2)$,
откуда
$x^2 + y^2 + z^2 = 2a^2$.

Читатель «Кванта», готовящий к экзаменам, может спросить: имеет ли он право пользоваться «основными соотношениями» при решении экзаменционных задач? Разумеется,—да! Оdnako при этом для соотношения I—III необходимо привести ввод использующего соотношения в экзаменционной работе. (Для соотношения IV, разумеется, достаточно сслаться на учебник.)

Чтобы привыкнуть к самостоятельному применению основных соотношения, рекомендуем решить нижеследующие упражнения. Из них 1—2 решаются с помощью I, 3—4 с помощью II, 5—6 с помощью III.

Уражнения

1 (МФТИ, 1970). В треугольнике $ABC$ bicсектириса $A1$ делит сторону $BC$ в отношении $|BD|: |CD| = 2:1$. В каком отношении медиана $CE$ делит эту bicсектирису?

2 (МГУ, биофак, 1973). Через середину $M$ стороны $BC$ параллелограмма $ABCD$, площадь которого равна 1, и вершину $A$ проведена прямая, пересекающая диагональ $BD$ в точке $Q$. Найти площадь четырехугольника $QMCD$.

3 (МФТИ, 1977). Все ребра правильной признамы $ABCA_1B_1C_1$ имеют длину $a$. Рассматривают отрезки с концами на диагонали $BC_1$ и $CA_1$ боковых граней, параллельные плоскости $ABB_1A_1$.

1) Один из этих отрезков проведен через точку $M$ диагонали $BC_1$ такую, что $|BM|: |BC_1| = 1:3$. Найти его длину.

2) Найти наименьшую длину всех расматриваемых отрезков.

4 (МФТИ, 1977). Сторона основания $ABCD$ правильной прямой $SABCD$ имеет длину $a$, боковое ребро — длину 2a. Рассматривают отрезки с концами на диагонали $BD$ основания и боковом ребре $SC$, параллельные (SAD).

Найти наименьшую длину всех расматриваемых отрезков.

5 (МФТИ, 1978). В правильной прямой признаме $ABCA_1B_1C_1$ длина стороны основания равна 4a, длина бокового ребра равна $a$. Точки $D$ и $E$ — середины ребра $A_1B_1$ и $BC$. Отрезок $MN$ с концами на прямых $AC$ и $BB_1$ пересекает прямую $DE$ и перпендикулярен к ней. Найти длину этого отрезка.

6 (МФТИ, 1978). Длина ребра куба $ABCDA_1B_1C_1D_1$ равна $a$. Точки $P, K, L$ — середины ребер $AA_1, A_1D_1, B_1C_1$ соответствственно, точки $Q$ — центр грани $CC_1D_1D$. Отрезок $MN$ с концами на прямых $AD$ и $KL$ пересекает прямую $PQ$ и перпендикулярен к ней. Найти длину этого отрезка.
