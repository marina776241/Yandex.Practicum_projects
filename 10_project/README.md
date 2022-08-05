#### Защита данных клиентов страховой компании
**Ход исследования**

Нужно преобразовать данные так, чтобы по ним было сложно восстановить персональную информацию, а также обучить модели на преобразованных данных и без преобразований так, чтобы качество моделей машинного обучения не ухудшилось. 

**Итоги исследования**

Создана случайная матрица для шифрования признаков, а также сравнены значения R2 двух моделей: без шифрования признаков и с шифрованием.

Качество моделей различается после 15 знака, чем можно пренебречь (скорее это погрешность, т.к. случайная матрица состоит из чисел с плавающей точкой).

При умножении признаков на обратную матрицу качество линейной регрессии не изменяется, что было доказано теоретически, используя формулу расчета весов линейной регрессии, а также сравнив 2 модели линейной регрессии (первая не была умножена на обратную матрицу, вторая была умножена на обратную матрицу).