# Билет 19

### Матрицы. Линейные операции над матрицами. Умножение матриц. Единичная матрица.

**Матрица – совокупность каких-то объектов, объединенных в группу вида:**

![](<../.gitbook/assets/image (15).png>)

**Виды матриц:**

* **Квадратная матрица** – (n x n), где кол-во строк == кол-во столбцов
* **Диагональная матрица** – Матрица, у которой элементы вне главной                                                                                                                                                                                                                                                        диагонали равны нулю.&#x20;

![](<../.gitbook/assets/image (7).png>)

* **Единичная матрица** – Диагональная матрица, у которой все элементы главной диагонали равны единице

![](<../.gitbook/assets/image (3).png>)

* **Нулевая матрица** – Все элементы равны нулю.

![](<../.gitbook/assets/image (37) (1).png>)

* **Векторная матрица** – Состоит из одной строки или одного столбца.

**Операции над матрицами**

* **Сложение -** Суммой матриц ![](<../.gitbook/assets/image (36).png>) одинакового размера называется матрица ![](<../.gitbook/assets/image (5).png>) того же размера элементы которой

&#x20;![](<../.gitbook/assets/image (49).png>)

**Свойства сложения:**

1. &#x20;A + B = B + C (коммутативность)
2. (A + B) + C = A + (B + C) = A + B + C (ассоциативность)

* **Умножение на число**

Произведением матрицы ![](<../.gitbook/assets/image (17) (1).png>) на число **λ** называется матрица ![](<../.gitbook/assets/image (24).png>)того же размера, что и матрица **A** с элементами ![](<../.gitbook/assets/image (9).png>)

**Свойства умножения на число:**

1. λ · (μ · A) = (λ · μ) · A (ассоциативность)
2. λ · (A + B) = λ · A + λ · B (дистрибутивность относительно сложения матриц)
3. λ + μ) · A = λ · A + μ · A (дистрибутивность относительно сложения чисел)

* **Произведение (матрицу на матрицу)**

Произведением A · B матриц A и B (размеров m × n и n × p соответственно) называется матрица C размера m × p, что

![](<../.gitbook/assets/image (30).png>)

Таким образом, каждый элемент ![](<../.gitbook/assets/image (88) (1).png>), находящийся в i-й строке и j-м столбце матрицы C, равен сумме произведений, соответствующих элементов i-й строки матрицы A и j-го столбца матрицы B. **Произведение существует, только если число столбцов матрицы A равно числу строк матрицы B.**

**Свойства произведения матрицы на матрицу** :

1. (A · B) · C = A · (B · C) (ассоциативность)
2. (A + B) · C = A · C + B · C (дистрибутивность)
3. A · (B + C) = A · B + A · C (дистрибутивность)
4. A · B ≠ B · A — отсутствует коммутативность

**Если матрица квадратная, то ЕА=АЕ, где Е – единичная матрица.**

* **Транспонирование – это замена ее столбцов ее строками, а строк – столбцами.**

### Условия коллинеарности и перпендикулярности двух векторов. Условия компланарности трех векторов.

Векторы _a = (x1, y1, z1)_ и _b = (x2, y2, z2)_ называются **коллинеарными**, если они лежат на одной прямой или на параллельных прямых. Векторы _a = (x1, y1, z1) и \~b = (x2, y2, z2)_ коллинеарны тогда и только тогда, когда

![](<../.gitbook/assets/image (88).png>)

Таким образом, если вектор a – не нулевой, то любой вектор b, коллинеарный с ним, можно представить в виде b = λ · a. Два ненулевых вектора _a = (x1, y1, z1)_ и _b = (x2, y2, z2)_ **перпендикулярны**, тогда и только тогда, когда их скалярное произведение равно нулю, то есть

![](<../.gitbook/assets/image (59).png>)

Векторы _a = (x1, y1, z1), b = (x2, y2, z2)_ и _c = (x3, y3, z3)_ лежат в одной плоскости, то есть **компланарны**, тогда и только тогда, когда их смешанное произведение равно нулю, то есть

![](<../.gitbook/assets/image (53).png>)

### Практика. Задачи.

1. Задача

![](<../.gitbook/assets/image (100).png>)

2\.  Задача

![](<../.gitbook/assets/image (18).png>)
