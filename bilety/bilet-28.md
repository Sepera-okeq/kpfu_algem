# Билет 28

### **Системы линейных уравнений. Решение систем методом Гаусса.**

Метод исключения неизвестных (метод Гаусса).

Рассмотрим метод решения систем линейных уравнений с произвольной матрицей, который называется методом последовательного исключения неизвестных.

_Определение_ 33. Две системы линейных уравнений с одинаковым числом неизвестных называется равносильными, если множества всех решений этих систем совпадают.

_Теорема_ 12. При элементарных преобразованиях строк расширенной матрицы, система переходит в равносильную систему. На основании этой теоремы запишем расширенную матрицу системы A¯. Элементарными преобразованиями над строками матрицы, приведем ее к ступенчатому виду (все элементы ниже главной диагонали равны нулю). Эти действия называются прямым ходом метода Гаусса. После чего из системы, составленной на основе полученной матрицы, находим переменные с помощью последовательных подстановок (обратный ход метода Гаусса).

Если r(A) = r(A) = n, то система совместна и имеет единственное решение, которое можно найти, применяя обратный ход метода Гаусса. Если r(A) = r(A) < n, то система имеет более одного решения.



**Короче говоря, метод Гаусса заключается в том, чтобы все уравнения системы представить в виде расширенной матрицы, а потом все элементы матрицы ниже главной диагонали привести к нулю элементарными преобразованиями (сделать матрицу ступенчатой). А после этого вернуться от матрицы к системе уравнений, имея одно уравнение с известной переменной (z = 3, к примеру). Имея такую систему остается просто подставлять известные переменный в вышестоящие уравнения и, как итог, найти все неизвестные.**

**Начинать приводить матрицу к ступенчатому виду стоит с левого столбца, идя вправо.**

&#x20;

![](<../.gitbook/assets/image (67).png>)

1\) Если в матрице есть (или появились) пропорциональные (как частный случай – одинаковые) строки, то следует **удалить** из матрицы все эти строки кроме одной. Рассмотрим, например матрицу  ![](<../.gitbook/assets/image (37).png>).&#x20;

В данной матрице последние три строки пропорциональны, поэтому достаточно оставить только одну из них:  ![](<../.gitbook/assets/image (3).png>).

2\) Если в матрице в ходе преобразований появилась нулевая строка, то ее также следует **удалить**. Рисовать не буду, понятно, нулевая строка – это строка, в которой _одни нули_.

3\) Строку матрицы можно **умножить (разделить)** на любое число, отличное от нуля.



Пример решения СЛАУ методом Гаусса:

![](<../.gitbook/assets/image (8).png>)

### **Геометрическая интерпретация комплексных чисел. Модуль и аргумент комплексного числа.**

Комплексные числа изображаются на так называемой комплексной плоскости. Ось, соответствующая в прямоугольной декартовой системе координат оси абсцисс, называется действительной осью, а оси ординат - мнимой осью

![](<../.gitbook/assets/image (71).png>)

**Модуль комплексного числа.**

![](<../.gitbook/assets/image (46).png>)

**Модуль комплексного числа вычисляется по формуле:**

![](<../.gitbook/assets/image (52) (1).png>)

**Аргумент комплексного числа.**

![](<../.gitbook/assets/image (65).png>)



![](<../.gitbook/assets/image (84).png>)

![](<../.gitbook/assets/image (27).png>)

### Практика. Задачи.

1\. Составить уравнения прямой, проходящей через точку

перпендикулярно прямой и пересекающей эту

прямую. Найти расстояние от точки до искомой прямой.

2\. Решить систему по правилу Крамера

&#x20;![](<../.gitbook/assets/image (50).png>)

![](<../.gitbook/assets/image (60) (1).png>)
