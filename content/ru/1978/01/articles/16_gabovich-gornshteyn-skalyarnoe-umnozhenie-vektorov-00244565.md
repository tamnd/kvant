---
id: 1978-1-gabovich-gornshteyn-skalyarnoe-umnozhenie-vektorov-00244565
issue: kvant_1978_1
year: 1978
number: "1"
title: Скалярное умножение векторов
authors:
  - Габович И. Г.
  - Горнштейн П. И.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 49
page_last: 54
page_labels: 47, 49, 50, 51, 52
tag: 1RBG
lang: ru
source: kvant_digital
extraction: vision
content_sha256: 2ce29be6e593c98c2e8a7332d2872ad3e40b5208e0753ac63b0d733546f586d0
---

⟦folio 47⟧

Скалярное умножение векторов является одним из основных понятий векторной алгебры. Его свойство широко используется при доказательстве теории и решения задач.

В этой статье мы проиллюстрируем применение скалярного умножения векторов к решению геометрических задач, предлагавшихся в последние годы на вступительных экзаменах в развития изучения векторов изложены в пособии «Геометрия 9» под редакцией З. А. Скопеца. Поэтому мы не будем останавливаться на теории этого вопроса. Перейдем к решению задач.

Задача 1. (МФТИ, 1977). Сторона основания правильной треугольной признамы $ABCA_1B_1C_1$ имеет длину $a$. Вершины $M$ и $N$ правильного треугольра $MNPQ$ лежат на прямой, проходящий через точки $C_1$ и $B$, а вершины $P$ и $Q$ — на прямой $A_1C$. Найти:

1) объем признамы;
2) расстояние между серединами отрезков $MN$ и $PQ$.

Решение. Расмотрим векторы: $\overrightarrow{CA}, \overrightarrow{CB}, \overrightarrow{CC_1}, \overrightarrow{CA_2}$ и $\overrightarrow{BC_1}$ (рис. 1). Обозначим $\overrightarrow{CA} = \vec{u}, \overrightarrow{CB} = \vec{v}, \overrightarrow{CC_1} = \vec{h}$ и $\overrightarrow{|h|} = h$. Из условия следует, что $\overrightarrow{|u|} = \overrightarrow{|v|} = a$.

Так как в правильном tetraэдре (как, впрочем, и во всякой правильной треугольной примине) любые два скрещивающихся ребра взаимно перпендикулярны, то $\overrightarrow{CA_1} \perp \overrightarrow{BC_1}$. Поэтому $\overrightarrow{CA_1} \cdot \overrightarrow{BC_1} = 0$. Но в наших обозначениях

$$\overrightarrow{CA_1} = \vec{u} + \vec{h} \text{ и } \overrightarrow{BC_1} = \vec{h} - \vec{v},$$

следовать,

$$(\vec{u} + \vec{h}) \cdot (\vec{h} - \vec{v}) = 0,$$

$$\vec{u} \cdot \vec{h} - \vec{u} \cdot \vec{v} + \vec{h}^2 - \vec{h} \cdot \vec{v} = 0.$$

Учитывая, что $\vec{h} \perp \vec{u}, \vec{h} \perp \vec{v}$ и $(\vec{u}, \vec{v}) = \frac{\pi}{3}$, получаем

$$h^2 - \frac{a^2}{2} = 0, \text{ или } h = \frac{a}{\sqrt{2}},$$

откуда находится объем признамы $V = \frac{a^2 \sqrt{3}}{4} \cdot \frac{a}{\sqrt{2}} = \frac{a^3 \sqrt{6}}{8}$.

Пусть $K$ и $L$ — середины отрезков $PQ$ и $MN$ соответственно. Найдем $|KL|$. Заметим, что $[KL]$ является общим перпендикуром ребер $PQ$ и $MN$ (доказатель сам), то есть $|KL|$ — расстояние между скрещивающимися прямыми $CA_1$ и $BC_1$.

Существует несколько способов вычисления расстояния между скрещивающимися прямыми. Мы определим искомое расстояние с помощью скалярного умножения. При этом, как

⟦folio 49⟧

Ни $\overrightarrow{HN}$ и $\overrightarrow{AB}$. Обозначим: $\overrightarrow{HP} = \vec{p}$, $\overrightarrow{HQ} = \vec{q}$ и $\overrightarrow{HR} = \vec{r}$. Остальные векторы выразим через $\vec{p}$, $\vec{q}$ и $\vec{r}$. Очевидно, что $|\vec{p}| = |\vec{q}| = 2$ и $|\vec{r}| = 1$.

Пусть

$$|RA| = x |RF|,$$
$$|HB| = y |HN|.$$

Тогда $\overrightarrow{RA} = x\overrightarrow{RF}$ и $\overrightarrow{HB} = y\overrightarrow{HN}$.

Очевидно, что $\overrightarrow{RF} = \frac{1}{2}\vec{p} - \vec{r}$ и $\overrightarrow{HN} = \frac{1}{2}\vec{p} + \frac{1}{2}\vec{q}$ ([HN] — медиана в треугольнике HPQ). Позтому

$$\overrightarrow{RA} = \frac{x}{2}\vec{p} - x\vec{r},$$
$$\overrightarrow{HB} = \frac{y}{2}\vec{p} + \frac{y}{2}\vec{q}.$$

Выразим теперь $\overrightarrow{AB}$ через векторы $\vec{p}, \vec{q}$ и $\vec{r}$:

$$\overrightarrow{AB} = \overrightarrow{AR} + \overrightarrow{RH} + \overrightarrow{HB} = -\overrightarrow{RA} - \overrightarrow{HR} + \overrightarrow{HB} = -\frac{x}{2}\vec{p} + x\vec{r} - \vec{r} + \frac{y}{2}\vec{p} + \frac{y}{2}\vec{q} = \frac{1}{2}(y-x)\vec{p} + \frac{y}{2}\vec{q} + (x-1)\vec{r}.$$

Так как $[AB] \perp [RF]$ и $[AB] \perp [HN]$, то $\overrightarrow{AB} \cdot \overrightarrow{RF} = 0$ и $\overrightarrow{AB} \cdot \overrightarrow{HN} = 0$. Составляем систему

$$\begin{cases}
\left(\frac{1}{2}(y-x)\vec{p} + \frac{y}{2}\vec{q} + (x-1)\vec{r}\right) \times \\
\times \left(\frac{1}{2}\vec{p} - \vec{r}\right) = 0, \\
\left(\frac{1}{2}(y-x)\vec{p} + \frac{y}{2}\vec{q} + (x-1)\vec{r}\right) \times \\
\times \left(\frac{1}{2}\vec{p} + \frac{1}{2}\vec{q}\right) = 0.
\end{cases}$$

Из этой системы, учитывая, что векторы $\vec{p}, \vec{q}$ и $\vec{r}$ взaimно перепendику-

⟦folio 50⟧

кулярны, то $\overrightarrow{AC} \cdot \overrightarrow{BM} = 0$ или
$(\vec{b} - \vec{h}) \cdot (\vec{a} + \vec{h} - \vec{y}) = 0,$
$\vec{a} \cdot \vec{b} + \vec{b} \cdot \vec{h} - \vec{b} \cdot \vec{y} - \vec{a} \cdot \vec{h} -$
$-\vec{h}^2 + \vec{h} \cdot \vec{y} = 0$. (5)

Как уже отмечалось, $\vec{a} \cdot \vec{h} = \vec{h} \cdot \vec{y} = 0$
На том же основании $\vec{b} \cdot \vec{h} = 0$. Поэтому из (5) имеем
$$\vec{a} \cdot \vec{b} - \vec{b} \cdot \vec{y} - \vec{h}^2 = 0,$$
$$ab - by - h^2 = 0,$$
$$y = \frac{ab - h^2}{b}.$$ (6)

Значение $y$ из (6) подтвердляем в (4)
$$h^2 = \frac{a^2b - ah^2}{b},$$

откуда
$$h = \frac{a\sqrt{b}}{\sqrt{a+b}}.$$

Задача 4 (УрГУ, 1971). Треугольник $AOB$ повернуть в своей плоскости вокруг вершины $O$ на $90^\circ$, причем вершина $A$ перешага в $A'$, а вершина $B - bB'$. Доказать, что в треугольнике $OAB'$ медиана стороны $AB'$ является высотой для треугольника $OA'B$ (анаалогично медиана стороны $A'B$ в треугольнике $OA'B$ является высотой для $\Delta OAB'$).

Решение. Пусть $C$ — середина $[AB']$ (рис. 4). Доказем, что $\overrightarrow{OC} \perp \overrightarrow{A'B}$, т. е. $\overrightarrow{OC} \cdot \overrightarrow{A'B} = 0$; имеем

Рис. 4.

Рис. 5.

⟦folio 51⟧

$$DP = \frac{a\sqrt{6}}{3}, \quad |PQ| = |MN| = \frac{a}{2}.$$
Пусть $\varphi$ – величины угла между векторами $\overrightarrow{MN}$ и $\overrightarrow{PQ}$. Найдем значение $\varphi$ из определения скалярного умножения двух векторов

$$\cos \varphi = \frac{\overrightarrow{MN} \cdot \overrightarrow{PQ}}{|\overrightarrow{MN}| \cdot |\overrightarrow{PQ}|}.$$

Запишем очередные векторы равенства

$$\overrightarrow{MN} = \overrightarrow{MD} + \overrightarrow{DN},$$

$$\overrightarrow{PQ} = \overrightarrow{DQ} - \overrightarrow{DP}.$$

Значения $\overrightarrow{MN}$ и $\overrightarrow{PQ}$ из (8) подставляем в (7)

$$\cos \varphi = \frac{(\overrightarrow{MD} + \overrightarrow{DN}) \cdot (\overrightarrow{DQ} - \overrightarrow{DP})}{|\overrightarrow{MN}| \cdot |\overrightarrow{PQ}|} = \frac{\overrightarrow{MD} \cdot \overrightarrow{DQ} + \overrightarrow{DN} \cdot \overrightarrow{DQ} - \overrightarrow{DP} \cdot \overrightarrow{MD}}{|\overrightarrow{MN}| \cdot |\overrightarrow{PQ}|} + \frac{-\overrightarrow{DN} \cdot \overrightarrow{DP}}{|\overrightarrow{MN}| \cdot |\overrightarrow{PQ}|}.$$

Заметим, что $(\overrightarrow{MD}, \overrightarrow{DQ}) = \frac{2}{3}\pi$ и $(\overrightarrow{DP}, \overrightarrow{MD}) = \pi - \overrightarrow{MDP}$. Очевидно, что $\cos MDP = \frac{\sqrt{6}}{3}$, а $\cos NDP = \frac{2\sqrt{2}}{3}$.

Учитывая сказанное выше, получаем

**Рис. 6.**

$$\cos \varphi = \frac{-\frac{a^2}{8} + \frac{a^2}{4} + \frac{a^2}{3} - \frac{4a^2}{9}}{\frac{a}{2} \cdot \frac{a}{2}} = \frac{1}{18}.$$

$\varphi = \arccos \frac{1}{18}$ и есть угол между отрезками $MN$ и $PQ$.

Задание 6 (МГУ, механизм, 1970). Длина каждого ребра треугольной пирамиды $SABC$ равна 1, $[BD]$ – высота треугольника $ABC$. Равностроенный треугольник $BDE$ лежит в плоскости, образующей угол $\varphi$ с ребром $AC$, причем точки $S$ и $E$ лежат по одному сторону от плоскости $ABC$. Найти расстояние между точками $S$ и $E$.

Решение. Проведем (рис. 6) в треугольнике $BDE$ высоту $EM$ и соединим точки $O$ и $E$. Через точку $M$ проведем $[MN] \parallel [AC]$ и $[MP] \parallel [SO]$. Так как отрезки $MN$ и $AC$ параллельны, что они составляют плоскостью $BDE$ равные углы. Так как $[MN] \perp [BD]$ и $[EM] \perp [BD]$, то $\angle EMN$, как легко понять, является тем углом, который $[MN]$ (а, значит, и $[AC]$) составляет с плоскостью $BDE$, то есть $\hat{EMN} = \varphi$. Так как $[MP] \parallel [SO]$, то $[MP] \perp (ABC)$ и, следовательно, $[MP] \perp [BD]$ и $[MP] \perp [MN]$. Поэтому $\hat{EMP} = 90^\circ + \varphi$. Очевидно, что $\overrightarrow{SE} = \overrightarrow{SO} + \overrightarrow{OM} + \overrightarrow{ME}$.

Найдем скалярный квадрат вектора $\overrightarrow{SE}$:

$$\overrightarrow{SE}^2 = \overrightarrow{SO}^2 + \overrightarrow{OM}^2 + \overrightarrow{ME}^2 + 2 \cdot \overrightarrow{SO} \cdot \overrightarrow{OM} + 2 \cdot \overrightarrow{SO} \cdot \overrightarrow{ME} + 2 \cdot \overrightarrow{OM} \cdot \overrightarrow{ME}.$$

Очевидно, что $\overrightarrow{SO} \cdot \overrightarrow{OM} = \overrightarrow{OM} \cdot \overrightarrow{ME} = 0$. Как нетрудно сообщить, $(\overrightarrow{SO}, \overrightarrow{ME}) = \hat{EMP} = 90^\circ + \varphi$, $|SE|^2 = |SO|^2 + |OM|^2 + |ME|^2 - 2 \cdot |SO| \cdot |ME| \cdot \sin \alpha$. 10).

Но $|SO| = \frac{\sqrt{6}}{3}$ – как высота правильного треугольра с ребром, равным 1; $|ME| = \frac{3}{4}$ – как высота правиль-

⟦folio 52⟧

ного треугольника со стороны, равной $\frac{\sqrt{3}}{2}$; $|OM| = \frac{\sqrt{3}}{12}$ (вычислите самостояльно).

Найdenные значения $|SO|, |OM|$ и $|ME|$ подставляем в (10):

$$|SE|^2 = \left(\frac{\sqrt{6}}{3}\right)^2 + \left(\frac{\sqrt{3}}{12}\right)^2 + \frac{9}{16} - 2 \cdot \frac{\sqrt{6}}{3} \cdot \frac{3}{4} \sin \varphi = \frac{5 - 2\sqrt{6} \sin \varphi}{4},$$

$$|SE| = \frac{1}{2} \sqrt{5 - 2\sqrt{6} \sin \varphi}.$$

Задача 7 (МФТИ, 1974.) Сторона основания правльной треугольной признамы $ABCA_1B_1C_1$ равна $a$; точки $O$ и $O_1$ являются центрами оснований $ABC$ и $A_1B_1C_1$ соответственно. Длина ortogonalной проекции отрезка $AO_1$ на прямую $B_1O_1$ равна $\frac{5}{6}a$. Определить высоту признамы.

Решение. Положим $|OO_1| = H$. Очевидно (рис. 7), что $|\overrightarrow{AO}| = |\overrightarrow{OB}| = \frac{a\sqrt{3}}{3}$ и $|\overrightarrow{OB}_1| = \sqrt{\frac{a^2}{3} + H^2}$. Далее $\overrightarrow{AO}_1 \cdot \overrightarrow{OB}_1 = |AO_1| \cdot |OB_1| \cdot \cos \varphi$. (11)

Известно, что проекция одного вектора на другой равна длине первого вектора, умноженного на косинус угла между направлениями векторов, то есть $\pi \overrightarrow{OB}_1 \cdot \overrightarrow{AO}_1 = |\overrightarrow{AO}_1| \times \cos \varphi = |\overrightarrow{AO}_1| \cdot \cos \varphi$.

Согласно условия задачи

$$\pi \overrightarrow{OB}_1 \cdot \overrightarrow{AO}_1 = \frac{5a}{6}.$$

Поэтому равенство (11) записывается так:

$$\overrightarrow{AO}_1 \cdot \overrightarrow{OB}_1 = |OB_1| \cdot \frac{5a}{6}.$$

Запишем очередные равенства:

$$\overrightarrow{AO}_1 = \overrightarrow{AO} + \overrightarrow{OO_1},$$

$$\overrightarrow{OB}_1 = \overrightarrow{OB} + \overrightarrow{BB_1}.$$

Таким образом,

$$\overrightarrow{AO}_1 \cdot \overrightarrow{OB}_1 = (\overrightarrow{AO} + \overrightarrow{OO_1}) \cdot (\overrightarrow{OB} + \overrightarrow{BB_1}) = \overrightarrow{AO} \cdot \overrightarrow{OB} + \overrightarrow{AO} \cdot \overrightarrow{BB_1} + \overrightarrow{OO_1} \cdot \overrightarrow{OB} + \overrightarrow{OO_1} \cdot \overrightarrow{BB_1}.$$

Так как $\overrightarrow{AO} \perp \overrightarrow{BB_1}$ и $\overrightarrow{OO_1} \perp \overrightarrow{OB}$, то $\overrightarrow{AO} \cdot \overrightarrow{BB_1} = \overrightarrow{OO_1} \cdot \overrightarrow{OB} = 0.$

Кроме того, $\overrightarrow{OO_1} = \overrightarrow{BB_1}$, следовательно, $\overrightarrow{OO_1} \cdot \overrightarrow{BB_1} = |OO_1|^2$,

$$\overrightarrow{AO}_1 \cdot \overrightarrow{OB}_1 = \overrightarrow{AO} \cdot \overrightarrow{OB} + |OO_1|^2 = \frac{a\sqrt{3}}{3} \cdot \frac{a\sqrt{3}}{3} \cdot \frac{1}{2} + H^2 = \frac{a^2}{6} + H^2.$$

Найdenные значения $\overrightarrow{AO}_1 \cdot \overrightarrow{OB}_1$ и $|OB_1|$ подставляем в (12) $\frac{a^2}{6} + H^2 = \frac{5a}{6} \sqrt{\frac{a^2}{3} + H^2}$, откуда $108H^4 = -39a^2H^2 - 22a^4 = 0$. Так как $H > 0$, то $H = \frac{a\sqrt{6}}{3}$.

1 (МФТИ, 1977). Основанием прямой треугольной признамы $ABCA_1B_1C_1$ является равноведренный прямойугольный треугольник с катетами $|AC| = |BC| = a$. Вершины $M$ и $N$ правильного тетраэдра $MNPQ$ лежат на прямой $CA_1$, а вершины $P$ и $Q$ – на прямой $AB_1$. Найти: 1) объем прямых; 2) расстояние между серединами отрезков $MN$ и $PQ$.

2 (МФТИ, 1977). Длина ребра куба $ABCDA_1B_1C_1D_1$ равна $a$. Точка $E$ – середина ребра $AD$. Вершины $M$ и $N$ правильного тетраэдра $MNPQ$ лежат на прямой $ED_1$, а вершины $P$ и $Q$ – на прямой, проходящей через точку $A_1$ и пересекающей прямую $BC$ в точке $R$.

Найти: 1) относение $|BR| : |BC|$; 2) расстояние между серединами отрезков $MN$ и $PQ$.

3 (МФТИ, 1969). В правильном тетраэдре $ABCD$ отрезок $MN$ соединяет середину ребра $AC$ с центром грани $BCD$, а точка $E$ лежит на середине ребра $AB$. Найти угол между отрезками $MN$ и $DE$.

4 (Физ. фак. МГУ, 1963). Два отрезка – $AB$ длины $a$ и $CD$ длины $b$ лежат на скрещивающихся прямых, угол между которых $a$. Основания $O$ и $O_1$ общего перпендикула длины $c$ к этим прямым делят отрезки $AB$ и $CD$ так, что $|OA| : |OB| = 2:3$, а $|OO_1| : |C_1D| = 3:2$. Найти длины отрезков $BD$ и $BC$.

5 (Из заданий 3ФТШ). В правильной 4-угольной прямиле $SABCD$ длина общего перпендикула ребер $SA$ и $BC$ равна $d$ и его основание делит отрезок $BC$ в отношении 1:3. Определить объем прямых.

6 (Киевский политехнический институт, 1977). В плоскости прямойгника $ABCD$ дана точка $M$. Докажите, что $\overrightarrow{MA} \cdot \overrightarrow{MC} = \overrightarrow{MB} \cdot \overrightarrow{MD}$.

7 (Весоюзная олимпида 1974 г.). Дан квадрат $ABCD$. Точки $P$ и $Q$ лежат соответственно на сторонах $AB$ и $BC$, причем $|BP| = |BQ|$. Пусть $H$ – основание перпендикула, опущенного из точки $B$ на отрезок $PC$. Докажать, что угол $DHQ$ – прямой.
