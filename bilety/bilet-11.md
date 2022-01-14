# Билет 11

### Линейная зависимость и независимость строк и столбцов. Необходимое и достаточное условие линейной зависимости. Теорема о базисном миноре.

**Базисный минор**

**Определение:**&#x20;

Минор, определяющий ранг матрицы, называется Базисным минором. Строки и столбцы, формирующие базисный минор, называются базисными строками и столбцами.

**Теорема о базисном миноре:**&#x20;

Столбцы матрицы А, входящие в базисный минор, образуют линейно независимую систему. Любой столбец матрицы А линейно выражается через столбцы из базисного минора.

**Доказательство.**&#x20;

Предположим противное - система длинных столбцов линейно зависима, следовательно система коротких столбцов (входящих в длинные) $$А_1,  А_2, … А_т$$  линейно зависима ($$r_a = r$$), следовательно о свойству определителя А (1 2 … r) = базисный минор = 0. Противоречие, т.к. базисный минор не равен 0.

**Линейная зависимость и независимость строк (столбцов) матрицы**

Система из n столбцов $$А_1,  А_2, … А_n$$  называется линейно зависимой, если существуют такие числа $$a_1, a_2 … a_n$$ не все равные нулю одновременно, что

$$(a_1 * A_1 + a_2 * A_2 + … + a_n * A_n = o)$$.

(o - нулевой столбец соответствующих размеров)

Система из n столбцов $$А_1, А_2 … А_n$$  называется линейно не зависимой когда линейная комбинация в левой части $$(a_1 * A_1 + a_2 * A_2 + … + a_n * A_n = o)$$тривиальная. Аналогичные определения формулируются и для строк (матриц-строк).

**Необходимое и достаточное условие линейной зависимости.**

«Для линейной зависимости множества строк квадратной матрицы необходимо и достаточно обращение в нуль ее определителя.»

**Доказательство:**

Необходимость. Допустим, что det A ≠ 0, где

![](<../.gitbook/assets/image (39).png>)

Равенство $$c_1 * u_1 + c_2 * u_2 + … + c_n * u_n = 0$$, где $$u_1, u_2, …, u_n$$ – строки А, равносильно системе линейных уравнений

![](<../.gitbook/assets/image (55).png>)

Которая имеет единственное нулевое решение, ибо det AT = det A ≠ 0. Иными словами, если det A ≠ 0, то строки А линейно независимы, т.к. для линейной зависимости необходимо, что бы det A = 0.

Достаточность. Доказательство достаточности проведем методом мат. индукции по порядку матрицы А. Для m = 1 утверждение теоремы очевидно, ибо равенство det A = 0 означает, что А состоит из нулевого элемента. Пусть для матрицы порядок m – 1 теорема доказана, и в этом предположении докажем ее для матриц порядка m. Без нарушения общности можно считать $$a_{11} ≠ 0$$. Обозначим через $$u_1, u_2, …, u_n$$  строки матрицы А и введем в рассмотрение строки:

![](<../.gitbook/assets/image (87).png>)

По свойству определителей:

![](<../.gitbook/assets/image (91).png>)

Далее, det A = 0, $$a_{11} ≠ 0$$, следовательно,

![](<../.gitbook/assets/image (54).png>)

ПО индуктивному предположению, строки $$(a’_{22} , …, a’_{2n}), ..., (a’_{2n}, … a’_{nn})$$ линейно зависимы, а тогда линейно зависимы и строки $$v_2, …, v_n$$, с теми же коэффициентами. Итак, существует не равные одновременно нулю коэффициенты $$c_2, …, c_n$$ такие, что $$c_2v_2 + … + c_nv_n = 0$$, и тогда &#x20;

![](<../.gitbook/assets/image (95).png>)

чтд.

### Понятие линии на плоскости. Полярная система координат. Линия первого порядка. Понятия направляющего вектора прямой и вектора нормали.

**Прямая на плоскости.**

Прямая на плоскости определяется какой-либо своей точкой Р и направляющим вектором a параллельным этой прямой.

**Различные виды уравнения прямой:**

_Общее уравнение прямой_ – АХ + BY + C = 0. Геометр. смысл этого уравнения: уравнение любой прямой является линейно-зависимо относительно входящих в него переменных.

_Уравнение прямой в отрезках –_ 𝑥/𝑎 + 𝑦/𝑏 = 1, где 𝑎 = − 𝐶/𝐴 , 𝑏 = − 𝐶/𝐵 — отрезки, которые прямая отсекает на координатных осях.

_Уравнение прямой с угловым коэффициентом -_ Если 𝐵 ≠ 0, то из общего уравнения прямой можно получить уравнение прямой с угловым коэффициентом: 𝑦 = 𝑘𝑥 + 𝑏, где коэффициент 𝑘 = − 𝑏/𝑎 = − 𝐴/𝐵 называется угловым коэффициентом. Он равен тангенсу угла наклона прямой к оси 𝑂𝑥: 𝑘 = tg𝜑. Уравнение прямой с угловым коэффициентом 𝑘, проходящей через точку $$𝑀_0$$(𝑥0, 𝑦0 ): 𝑦 = 𝑘(𝑥 − 𝑥0 ) + 𝑦0.

_Уравнение прямой, проходящей через две заданные точки -_ Возьмем произвольную точку на прямой $$М(x;y) → M_1M_2 = (x_2 – x_1 ; y_2 – y_1) → (x – x_1)/(x_2 – x_1) = (y – y_1)/(y_2 – y_1)$$

_Векторное уравнение прямой -_ Пусть 𝑝 = {𝑚, 𝑛} — направляющий вектор прямой 𝑙. Произвольная точка 𝑀 принадлежит прямой 𝑙 тогда и только тогда, когда 𝑀0 𝑀 ∥ 𝑝 . Это эквивалентно тому, что$$∃𝑡 ∈ ℝ: 𝑀_0 𝑀 = 𝑡𝑝$$ . Поскольку $$𝑀_0 𝑀 = 𝑟 − 𝑟_ 0$$, где 𝑟 — радиус-вектор точки 𝑀, 𝑟  — радиус-вектор точки $$𝑀_0$$, то получаем параметрическое уравнение прямой 𝑙 в векторном виде: $$𝑟 = 𝑟_0 + 𝑡𝑝$$

**Полярная система координат**

Для описания положения точки  плоскости _x_0_y_ можно использовать **полярные координаты** _r_ и φ, где _r_ – расстояние от точки до начала координат, называемого **полюсом**. Полярные координаты (𝑟, φ ) точки связаны с ее декартовыми прямоугольными координатами (x, y) простыми соотношениями:

![](<../.gitbook/assets/image (66).png>)

**Линия первого порядка**

К линиям первого порядка относятся те линии, для кото­рых задающее их уравнение содержит переменные x и у только в первой степени. Иными словами, такие линии описываются уравнениями вида Ax + By + C = 0, где А, В и С — постоянные числа. Из этого уравнения можно выразить переменную Y как функцию от аргумента Х. При В ≠ 0: y = kx + b.

**Понятия направляющего вектора прямой и вектора нормали.**

Направляющий вектор прямой - это любой ненулевой вектор, лежащий на данной прямой или на параллельной ей прямой.

Из определения направляющего вектора прямой следует, что существует бесконечно много направляющих векторов заданной прямой. Более того все направляющие векторы прямой лежат либо на этой прямой, либо на прямой ей параллельной, то есть, все направляющие векторы заданной прямой коллинеарны. Таким образом, если a - направляющий вектор прямой a, любой из векторов $$t*a$$ при некотором ненулевом действительном значении t также является направляющим вектором прямой a.

Из определения направляющего вектора прямой также следует, что множества направляющих векторов параллельных прямых совпадают. Другими словами, если прямые a и $$a_1$$ параллельны и вектор a - направляющий вектор прямой a, то вектор а также является направляющим вектором прямой $$a_1$$.

Нормальный вектор прямой - это любой ненулевой вектор, лежащий на любой прямой перпендикулярной данной.

Так как прямая, перпендикулярная одной из двух параллельных прямых, перпендикулярна и второй прямой, то можно утверждать, что множества нормальных векторов параллельных прямых совпадают. То есть, если прямые a и a1 параллельны и n - нормальный вектор прямой a, то n также является нормальным вектором прямой $$a_1$$.

Определение нормального вектора прямой и определение направляющего вектора прямой позволяют заключить, что любой нормальный вектор данной прямой перпендикулярен любому направляющему вектору этой прямой.

### Практика. Задачи