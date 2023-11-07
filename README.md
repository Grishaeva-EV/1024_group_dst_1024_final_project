# 1024_group_dst_1024_final_project
Дипломный проект : "Модель прогнозирования стоимости жилья для агентства недвижимости по брифу учебного кейса"
Цели и задачи проекта
Задача проекта - создать модель, которая позволит предсказывать стоимость жилья по характеристикам.

В ходе работы над проектом были решены следующие задачи:

## EDA

* Датасет очищен от мусора, дубликатов, пропущенных значений и выбросов.
* Созданы новые переменные.
* Произведен отбор признаков различными методами.

## MODEL

* Обработаны и отнормированы признаки
* Построина "наивная" модель, предсказывающую цену по общей площади и городу (с ней будем сравнивать другие модели)
* Построина модель при помощи LinearRegression
* Построина модель на основе случайного леса RandomForestRegressor
* Построина модель с L1 и L2 регуляризаций ElasticNetCV
* Построина модель градиентного бустинга CatBoostRegressor
* На основе предыдущих шагов выбрана и выгружена оптимальная модель CatBoostRegressor
