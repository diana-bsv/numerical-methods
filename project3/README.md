# Вычисление наилучшего приближения
Программа для построения наилучшего приближения на отрезке [a,b] – функции класса C0[a,b], используя базисные функции узлов конечных элементов (интерполяционные многочлены Лагранжа для локальной интерполяции).

1. Используя генератор случайных чисел (равномерное распределение), задать на каждом конечном элементе L > N внутренних «случайных точек».
2. Сформировать систему линейных алгебраических уравнений (СЛАУ) для определения коэффициентов элемента наилучшего приближения на основе значений функции y = f (x) в «случайных точках», сгенерированных в предыдущем пункте.
3. Решить СЛАУ, используя библиотечную функцию.
4. Вычислить абсолютную и относительную погрешности наилучшего
приближенияв«случайныхточках».
5. Визуализировать одном рисунке два графика: функции y = f (x) и наилучшего приближения. 