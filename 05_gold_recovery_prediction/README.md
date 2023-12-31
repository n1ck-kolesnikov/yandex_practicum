# Предсказание коэффициента восстановления золота из руды

[ipynb](https://github.com/n1ck-kolesnikov/yandex_practicum/blob/main/05_gold_recovery_prediction/gold_recovery_prediction.ipynb)


## Описание проекта 

Наш заказчик - золотодобывающая промышленная компания - просит нас построить модель для предсказания коэффициента восстановления золота из золотосодержащей руды.

Нам доступны данные с параметрами добычи и очистки золотосодержащей руды.

Наша модель поможет оптимизировать производство, чтобы не запускать предприятие с убыточными характеристиками.

   
## Инструменты

- python
- pandas
- matplotlib.pyplot
- seaborn
- numpy
- scikit-learn
- lightgbm
- phik
- missingno


## Вывод 

Отвечая на главный вопрос проекта: рекомендуем использовать обученные модели ridge-регрессии для предсказания значений "rougher.output.recovery" (эффективность обогащения чернового концентрата) 
и случайного леса для предсказания "final.output.recovery" (эффективность обогащения финального концентрата). 
Итоговое sMAPE для этих моделей равно 9.0%.
 
