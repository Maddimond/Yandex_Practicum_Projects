# Прогнозирование оттока клиентов Банка


## Описание проекта

Из «Бета-Банка» стали уходить клиенты. Каждый месяц. Немного, но заметно. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых.

Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. В наше распоряжение предоставлены исторические данные о поведении клиентов и расторжении договоров с банком.

Требуется построить модель с предельно большим значением F1-меры(от 0.59 или выше). Дополнительно проверим F1-меру на тестовой выборке.


## Инструменты:

*Pandas, sklearn, машинное обучение*

## Краткое описание проведённой работы:

Из банка стали уходить клиенты каждый месяц. Спрогнозирована вероятность ухода клиента из банка в ближайшее время. Построена модель с предельно большим значением F1-меры с последующей проверкой на тестовой выборке. Доведена метрика до 0.62. Дополнительно измерен AUC-ROC, соотнесен с F1-мерой. Обучение с учителем. Работа с несбалансированными данными.


## Вывод

Обучили следующие модели классификации на обучающей выборке:

Дерево Решений
Случайный лес
Логистическая регрессия

Наилучший результат показала модель случайного леса ее F1_score равен 0.60 с ROC_AUC_score равным 0.85 с применение метода увеличение выборки методом upsampling и применение параметра class_weight = balanced.
У дерева решений наилучший F1_score равен 0.56, а ROC_AUC_score равен 0.82 с применением параметра class_weight = balanced.
У логистической регресии наилучший F1_score равен f1_score равен 0.44, аROC_AUC_score равен 0.72 используя параметры solver='liblinear', class_weight со значением 'balanced'

На этапе Тестирования модели - взяи лучшую модель - Случайный лес и проверили ее на тестовой выборке.

Мы получили f1_score на тестовой выборке - 0.61, который больше проходного значения, и ROC_AUC_score - 0.86 который близко к 1. Значит данная модель очень хорошо предсказывает результаты


## Статус проекта

Завершён
