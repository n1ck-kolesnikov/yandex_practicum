# Исследование рыночной стоимости объектов недвижимости

[ipynb](https://github.com/n1ck-kolesnikov/yandex_practicum/blob/main/12_real_estate_price_analysis/real_estate_price_analysis.ipynb)


## Описание проекта 

Наш заказчик, сервис Яндекс.Недвижимость, передаёт нам архив объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктов за несколько лет. Нам нужно определить рыночную стоимость объектов недвижимости.

По каждой квартире на продажу доступны два вида данных. Первые вписаны пользователем, вторые — получены автоматически на основе картографических данных. Например, расстояние до центра, аэропорта, ближайшего парка и водоёма.

   
## Инструменты

- python
- pandas
- matplotlib.pyplot
- missingno


## Вывод 

Мы выяснили, что:

- объекты недвижимости предпочитают выставлять на продажу в рабочие дни;
- меньше всего выставляют объектов на продажу в следующие месяцы - январь, май и декабрь; неохотно выставляют квартиры в июне, июле и августе; а больше всего предложений продажи появляется в феврале, марте и апреле;
- в среднем, продажа обычно занимает 96 дней (медианное значение) - 50% квартир из набора данных были проданы именно за 96 дней. Быстрыми можно считать продажи длительностью меньше 1.5 месяцев. Долгими продажами являются от 232 до 500 дней; и аномально долгими - больше 500; также мы обнаружили характерные для риэлторских агентств пики продаж в 7, 30, 45, 60 и 90 дней - случаи срочного выкупа жилья у собственников.
- цена зависит от общей площади, жилой площади, площади кухни и количества комнат. Данные параметры влияют на цену со средней - ниже-среднего силой (коэффициенты корреляции колеблются от 0.65 до 0.36);
- квартиры на первом и последних этажах на 20% и 12% меньше стоят, чем квартиры, расположенные на иных этажах;
- зависимость между днём или месяцем размещения и ценой незначительна, но её можно выразить следующим образом: цена на квартиры, которые размещаются в начале недели (понедельник/вторник), в среднем на 5% выше цен на квартиры, размещающихся в конце недели (пятница-воскресенье); цены на квартиры в апреле - самые высокие, они на 9% выше самых низких цен в мае-июне;
- после 2014 года цена на объекты резко упала (на 43%); в период с 2015 года до 2017 года цена медленно снижалась; с 2018 года по 2019 год явный тренд на рост цены;
- самым дорогим населённым пунктом оказался Санкт-Петербург с ценой в 114789 рублей за квадратный метр, а самым бюджетным стал Выборг - 58142 рубля за квадратный метр;
- цены в Санкт-Петербурге снижаются с увеличением расстояния до центра; зависимость цены от расстояния до центра больше всего похожа на гиперболу.