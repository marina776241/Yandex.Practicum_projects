#### Обучение модели классификации комментариев
**Ход исследования**

Текстовый признак был очищен и приведен к леммам, выборка была разбита на обучающую и тестовую, а также вычислен TF-IDF для корпуса текстов для того, чтобы научить модель классифицировать комментарии на позитивные и негативные.

**Итоги исследования**

Признаки, подготовленные с помощью TfidfVectorizer и использованные на модели логистической регрессии показали лучший требуемый результат F-1: 0,7791, в то время как дерево решений и случайный лес не справились с поставленной задачей (случайный лес).

