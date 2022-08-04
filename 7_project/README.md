#### Прогнозирование оттока клиента Банка
**Ход исследования**

Нужно подготовить данные (обработать пропуски, удалить ненужные признаки, преобразовать категориальные признаки), подготовить данные для моделей и выяснить, уйдёт клиент из банка в ближайшее время или нет.
 
**Итоги исследования**

Для решения задачи прогнозирования оттока клиентов были построены модели дерева решений, случайного леса и логистической регрессии сначала без учета дисбаланса классов. Дисбаланс был исправлен разными методами, метод добавления веса для класса, который встречается реже дал улучшение F-1-меры.

Полученная модель случайного леса со взвешенными классами показала значение F-1-меры, равное 0,6136. Также модель показала себя лучше случайной, значение AUC-ROC равно 0,8545 (у случайной модели этот показатель равен 0,5). Точность модели достигает 0,85, Precision равен 0.67, а Recall равен 0.565, значит модель делает высокоточные предсказания, определяя, уйдет ли клиент из банка.