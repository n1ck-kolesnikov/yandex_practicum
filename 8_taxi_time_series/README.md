# Название проекта

Прогнозирование заказов такси


# Описание проекта 

Компания «Чётенькое такси» собрала исторические данные о заказах такси в аэропортах.
Чтобы привлекать больше водителей в период пиковой нагрузки, нужно спрогнозировать количество заказов такси на следующий час.
Построим модель для такого предсказания.

   
# Системные требования 

python==3.9.12
pandas==1.4.2
matplotlib==3.5.1
seaborn==0.11.2
numpy==1.21.5
scikit-learn==1.2.1
lightgbm==3.3.5
statsmodels==0.13.2


# Вывод 

Отвечая сразу на главный вопрос проекта: мы предлагаем использовать обученную нами модель ridge-регрессии для предсказания количества заказов на следующий час.
RMSE модели на тестовой выборке - 45.
Кроме того, она хорошо экстраполируется на будущие данные.