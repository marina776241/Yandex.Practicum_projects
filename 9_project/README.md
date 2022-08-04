#### Исследование технологического процесса очистки золота
**Ход исследования**

Нужно подготовить данные (проверить данные, заполнить пропуски), проанализировать данные, чтобы построить модель, которая должна предсказать коэффициент восстановления золота из золотосодержащей руды.

**Итоги исследования**

Для построения модели, предсказывающей коэффициент восстановления золота из золотосодержащей руды, были использованы данные с параметрами добычи и очистки, проверен расчет эффективности обогащения, удалены строки, где значения суммы концентрации всех веществ равны 0.

Модель CatBoost показала лучший результат метрики итогового sMAPE (6,57), модель прошла проверку на адекватность.