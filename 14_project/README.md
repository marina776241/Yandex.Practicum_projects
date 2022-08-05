####  Обработка фотографий покупателя
**Ход исследования**

Изучены фотографии, затем построена модель для определения возраста человека.

**Итоги исследования**

Нейронные сети позволяют предсказывает переменную по изображениям с высокой точностью, в этом помогают существующие сети, веса которых можно использовать для наших задач.

Модель основана на ResNet50, также были добавлены слои: Sequential, GlobalAveragePooling2D и Dense с relu-активацией, что показало результат на валидации 7.23 лет, это хорошее значение. А также модель довольно быстро обучается благодаря GPU, что также является показателем прогресса в развитии нейронных сетей.

Полученные результаты помогут бизнесу отпределить примерный возраст клиента, чтобы предложить ему определенный товар для покупки.

