# Russian_car_market_feb-march-2023

Проект реализован на открытых [данных](https://www.kaggle.com/datasets/serge1024/russian-car-market-feb-march-2023?select=final_geografic.csv), взятых на платформе Kaggle.
Этот датасет состоит из фотографий и других материалов об авто, добавленных на российский авторынок Drom. Данные были собраны в феврале-марте 2023 года. Набор данных состоит из пяти каталогов. В первом каталоге сохраните наборы данных с именем вида *_main.csv. 

**Целью** работы является анализ объявлений о продаже автомобилей за февраль-март 2023 и выбор модели для предсказания цены автомобиля.

Для реализации цели были поставлены следующие **задачи** :
* Загрузка и изучение данных.
* Исследование данных.
* Подготовка данных (предобработка данных, подготовка тренировочной и тестовой выборок).
* Выбор модели (построение pipeline, подбор гиперпараметров и анализ метрик на кросс-валидации).
* Тестирование модели.

Использованный стэк: `pandas` , `matplotlib`, `seaborn` `numpy`, `scikit-learn`,`NLP`,`TF-IDF`, `optuna`, `xgboost`, `lightgbm`, `Pipeline`